<script>
    import { dues } from '$lib/utils/helper';
    let one, oneOne, oneTwo, oneTwoOne, oneThree, oneFour, oneFourOne, oneFourTwo, oneFourThree, oneFourFour, oneFive, oneFiveOne, oneFiveTwo, oneFiveThree, oneSix, oneSeven;
    let two, twoOne, twoTwo, twoTwoOne, twoThree, twoFour, twoFive;
    let three, threeOne, threeTwo, threeThree;
    let four, fourOne, fourTwo;
    let five, fiveOne, fiveTwo, fiveThree, fiveFour;
    let six, sixOne, sixOneOne, sixOneTwo, sixOneThree;
    let seven, sevenOne, sevenTwo, sevenThree; 

    const goToSection = (section) => {
        const top = section.getBoundingClientRect().top + window.pageYOffset;
        window.scrollTo({left: 0, top, behavior: 'smooth'});
    }
</script>

<style>
    .constitution {
        position: relative;
        z-index: 1;
        width: 92%;
        max-width: 800px;
        margin: 8em auto 10em;
    }

    h1 {
        font-size: 2em;
        line-height: 1.2em;
        text-align: center;
        margin: 2em 0 1.5em;
    }

    h2 {
        font-size: 1.5em;
        line-height: 1.2em;
    }

    h3 {
        text-decoration: underline;
        font-size: 1.3em;
        line-height: 1.2em;
    }

    h4 {
        text-decoration: underline;
        margin-left: 2em;
        font-size: 1.2em;
        line-height: 1.2em;
    }

    h5 {
        margin-left: 6em;
        font-size: 0.8em;
        line-height: 1.1em;
    }

    .subBlock {
        margin-left: 2.4em;
    }

    .sectionHeading {
        margin: 4em 0 1.5em;
    }

    .subSectionHeading {
        margin: 1.5em 0 1.5em;
    }

    .underscore {
        text-decoration: underline;
    }

    .right {
        text-align: right;
    }

    .positionMaximums td {
        min-width: 3em;
    }

    .noUnderscore {
        text-decoration: none;
    }

    .clickable {
        cursor: pointer;
    }

    .clickable:hover {
        color: #00316b;
    }

    p {
        color: #777;
    }
</style>

<div class="constitution">
    <h1 class="noUnderscore">DYNASTY X CONSTITUTION</h1>
    
    <h2 class="noUnderscore">TABLE OF CONTENTS</h2>
    
    <h3 class="noUnderscore clickable" onclick={() => goToSection(one)}>Section 1: Roster</h3>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(oneOne)}>1.1 Positional Breakdown</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(oneTwo)}>1.2 Taxi Squad/IR</h4>
            <h5 class="noUnderscore clickable" onclick={() => goToSection(oneTwoOne)}>1.2.1 Taxi Squad Stealing</h5>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(oneThree)}>1.3 Dynasty</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(oneFour)}>1.4 Trading</h4>
            <h5 class="noUnderscore clickable" onclick={() => goToSection(oneFourOne)}>1.4.1 Trade Collusion</h5>
            <h5 class="noUnderscore clickable" onclick={() => goToSection(oneFourTwo)}>1.4.2 Trade Deadline</h5>
            <h5 class="noUnderscore clickable" onclick={() => goToSection(oneFourThree)}>1.4.3 Trade Restrictions</h5>
            <h5 class="noUnderscore clickable" onclick={() => goToSection(oneFourFour)}>1.4.4 Trade Processing</h5>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(oneFive)}>1.5 Waiver Wire</h4>
            <h5 class="noUnderscore clickable" onclick={() => goToSection(oneFiveOne)}>1.5.1 Free Agent Auction Budget (FAAB)</h5>
            <h5 class="noUnderscore clickable" onclick={() => goToSection(oneFiveTwo)}>1.5.2 Offseason Waivers</h5>
            <h5 class="noUnderscore clickable" onclick={() => goToSection(oneFiveThree)}>1.5.3 Season Waivers</h5>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(oneSix)}>1.6 Divisional Breakdown</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(oneSix)}>1.7 Schedule</h4>



    <h3 class="noUnderscore clickable" onclick={() => goToSection(two)}>Section 2: Owner Expectations</h3>
    
        <h4 class="noUnderscore clickable" onclick={() => goToSection(twoOne)}>2.1 Setting Lineups</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(twoTwo)}>2.2 Leaving the League</h4>
            <h5 class="noUnderscore clickable" onclick={() => goToSection(twoTwoOne)}>2.2.1 New Owners</h5>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(twoThree)}>2.3 Removal</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(twoFour)}>2.4 Rule Voting</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(twoFive)}>2.5 Last Place Punishment</h4>


    
    <h3 class="noUnderscore clickable" onclick={() => goToSection(three)}>Section 3: Drafting</h3>
    
        <h4 class="noUnderscore clickable" onclick={() => goToSection(threeOne)}>3.1 Draft Order</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(threeTwo)}>3.2 Draft Day Trades</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(threeThree)}>3.3 Draft Date & Time</h4>

    
    <h3 class="noUnderscore clickable" onclick={() => goToSection(four)}>Section 4: Scoring System</h3>
    
        <h4 class="noUnderscore clickable" onclick={() => goToSection(fourOne)}>4.1 Scoring</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(fourTwo)}>4.2 Voting on Scoring System</h4>

    <h3 class="noUnderscore clickable" onclick={() => goToSection(five)}>Section 5: Postseason</h3>
    
        <h4 class="noUnderscore clickable" onclick={() => goToSection(fiveOne)}>5.1 Playoffs</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(fiveTwo)}>5.2 Playoff Tiebreakers</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(fiveThree)}>5.3 Seeding Tiebreakers</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(fiveFour)}>5.4 Toilet Bowl</h4>


    <h3 class="noUnderscore clickable" onclick={() => goToSection(six)}>Section 6: Expansion</h3>
    
        <h4 class="noUnderscore clickable" onclick={() => goToSection(sixOne)}>6.1 Expansion Rules</h4>
            <h5 class="noUnderscore clickable" onclick={() => goToSection(sixOneOne)}>6.1.1 Setup</h5>
            <h5 class="noUnderscore clickable" onclick={() => goToSection(sixOneTwo)}>6.1.2 The Expansion Draft</h5>
            <h5 class="noUnderscore clickable" onclick={() => goToSection(sixOneThree)}>6.1.3 After the Draft</h5>

    <h3 class="noUnderscore clickable" onclick={() => goToSection(seven)}>Section 7: League Finances</h3>
    
        <h4 class="noUnderscore clickable" onclick={() => goToSection(sevenOne)}>7.1 League Dues</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(sevenTwo)}>7.2 Payouts</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(sevenThree)}>7.3 Raising Dues</h4>
    
    
    <hr />
    
    <h2 class="sectionHeading" bind:this={one}>Section 1 Roster</h2>
    
    <h3 class="subSectionHeading" bind:this={oneOne}>1.1 Positional Breakdown</h3>
    
    <p>26 Total Players</p>
    
    <p class="underscore">Starters</p>
    <ul>
        <li>QB</li>
        <li>RB</li>
        <li>RB</li>
        <li>WR</li>
        <li>WR</li>
        <li>WR</li>
        <li>TE</li>
        <li>FLEX (RB/WR/TE)</li>
        <li>FLEX (RB/WR/TE)</li>
        <li>SUPERFLEX (QB/RB/WR/TE)</li>
    </ul>
    
    <p>12 Bench</p>

    <p>4 Taxi Squad Spots (Rookies or 2nd year players only)</p>

    <p>2 IR Spots (Player must be labeled as IR, Out, DNR, or Covid in the Sleeper App)</p>


    <h3 class="subSectionHeading" bind:this={oneTwo}>1.2 Taxi Squad/IR</h3>
    
    <p>The Taxi Squad are development roster spots where you can put 4 rookies or 2nd year players. Any player in their 3rd year or later is ineligible for the Taxi Squad. Taxi Squads lock at the start of the first game of the season. At any point during the season you can call a Taxi Squad player up to your active roster. The Taxi Squad roster spot cannot be refilled until the next offseason. </p>
   
    <p>The 2 Injury Reserve spots can be filled by anyone who’s out, suspended, holding out, or on Covid-19 reserve. Leaving healthy players on IR will result in punishments referred to in section 2.2.</p>
    
    <h4 bind:this={oneTwoOne}>1.2.1 Taxi Squad Stealing</h4>
    <div class="subBlock">
        <p>To claim a player:</p>

        <p>Claiming Owner (CO) must send Original Owner (OG) a trade for the Taxi Squad Player sending proper draft pick compensation by Tuesday 11:59pm. Proper comensation is as follows:</p>

        <p>1st round pick - 1st + 2nd round picks</p>

        <p>2nd round pick - 1st round pick</p>

        <p>3rd round pick - 2nd round pick</p>

        <p>Free Agent pickup - 4th round pick</p>

        <p>After sending the trade, CO must post a screenshot of the trade offer in the league chat. This is their claim submittal. Once a claim is in no other owner can submit a claim for that same player</p>

        <p>After the claim:</p>

        <p>Once OG receives the claim and it’s posted in the league chat OG has until 6pm on Thursday to either accept the claim, activate the player onto their active roster, or trade the player for BETTER compensation than the claim. OG can auction the player and shop them around to get better compensation. They cannot accept equal compensation. So for example, if CO claims a player for a 3rd round pick (because that player was drafted in the 4th round of their draft), OG can only trade that player for a 2nd or better. They cannot trade that player for a 3rd round pick to a different team. If OG finds a better trade offer they can accept that before 6pm Thursday</p>

        <p>If OG does not respond to the claim offer before 6pm Thursday the claim is automatically accepted and the commissioner will manually push the trade through</p>

        <p>Side Notes:</p>

        <p>If OG decides to activate the player with a claim on them to their active roster they cannot cut them for the rest of the season. Penalty is forfeiture of next 1st round pick</p>

        <p>Draft pick must be for the following year for claims. So any claim this year must be for a 2027 pick</p>

        <p>Claims can be for better draft picks, not worse. So for example, if I want to claim a player drafted in the 4th round but don’t have a 3rd round pick for 2027, I can submit a claim using a 1st or 2nd round pick for 2027</p>

        <p>If a player is picked up off free agency and then claimed off someone’s Taxi Squad they are valued as an undrafted player. So if a player is drafted in any round, dropped, then placed on Taxi by the owner who picks them up they can be claimed for a 4th round pick</p>

        <p>Each team gets 2 claims per season, regardless if it’s successful or not. So if you put in a claim for a player and the original owner activates them or trades them for better picks, you still only have 1 claim left</p>
    
    </div>

    <h3 bind:this={oneThree}>1.3 Dynasty</h3>
    
    <p>With this league being a dynasty league all players will be kept on current rosters for the entirety of their careers</p>

    <p>Only way players are removed from rosters are via retirement, cuts, and trades</p>
    
    
    <h3 class="subSectionHeading" bind:this={oneFour}>1.4 Trading</h3>   

    <p>Owners will have the option to exchange players and draft picks during the trade window. As long as both parties come to an agreement with no foul play, and all future dues involved in the deal are paid, the trade will be approved and processed. Owners will have 3 days to pay future dues owed for trades. If not paid within this time frame the trade will be denied</p>

    <p>If there is an accidental trade (i.e. someone accidentally hits accept instead of decline) the trade will be reversed as long as it is brought up immediately. If you wait to bring it up then the trade will still be processed as long as it meets the above criteria. If both owners come to the agreement of canceling the trade then the trade will be canceled</p>

    <p> If for any reason the commissioner accidentally rejects a trade that should be pushed through (draft picks paid for and no collusion occurring) then the commissioner will just manually make the trade using commissioner settings. If the commissioner accidentally rejects a trade that still hasn’t met the trade criteria (draft picks not paid for or collusion occuring) the two trading teams will have to re-agree to the trade and resubmit it</p>

    <h4 bind:this={oneFourOne}>1.4.1 Trade Collusion</h4>
    <div class="subBlock">
        <p>All trades will be reviewed by the commissioner to make sure no foul play is occurring. If any owners are found to be guilty of accepting/offering bribes to enhance their/anothers team via trade they will be susceptible to punishment and the trade will be denied. The punishments will go as follows:</p>

        <p>First Offense – Loss of current year 1st round draft pick & one year playoff ban (for both teams if trade is accepted)</p>

        <p>Second Offense – Removal from league</p>

        <p>Commissioners can reverse and deny trades at any time if they feel it is necessary to keep the integrity of the league</p>

        <p>First offense will stay on your record for 3 seasons before having a clean slate</p>

    </div>

    <h4 bind:this={oneFourTwo}>1.4.2 Trade Deadline</h4>
    <div class="subBlock">

       <p>The trading deadline will be week 11. All deals must be made prior to the end of the final game of week 11. As soon as the final game is over, trades will be closed. Trading will open back up once the league is renewed after the Super Bowl</p>

    </div>

    <h4 bind:this={oneFourThree}>1.4.3 Trade Restrictions</h4>
    <div class="subBlock">

       <p>Trading of future 1st or 2nd rounders will require a 50% deposit for that year. For example, if you want to trade a 2026 2nd rounder you will have to pay $50 for 2026 for the trade to be pushed through. You, or whoever owns that team come 2026 will still owe the remaining $50 come that season</p>

       <p>Deposit will only be required if you’re trading away your only 1st or 2nd rounder. If you own multiple 1sts or 2nds you will not have to pay a deposit to trade them. Trading future 3rd and 4th rounders will not require a deposit. Trading for better picks will also not require a deposit (ex: trading your 2nd rounder to get a 1st)</p>

       <p>Trades will pend for 3 days for deposits. If deposits are not made then the trade will be cancelled</p>

       <p>*if for whatever reason only one team pays a deposit when both are required to within the 3 day window then the deposit will be returned to the paying team and the trade will be cancelled*</p>

    </div>

    <h4 bind:this={oneFourFour}>1.4.4 Trade Processing</h4>
    <div class="subBlock">

       <p>Trades will only be denied if foul play is discovered, future dues are not paid, or the trade jeopardizes the league</p>

    </div>

    <h3 class="subSectionHeading" bind:this={oneFive}>1.5 Waiver Wire</h3>

    <p>The waiver order will begin each season based off the order at the end of the previous year. The order will only change when owners make FAAB bids that tie with another owner. The owner with the lower waiver priority will receive the player and be put at the bottom of the list</p>

    <p>Everyone has the right to run their team how they see fit. However, commissioners have the right to prevent unreasonable drops to maintain integrity of the league</p>

    <h4 bind:this={oneFiveOne}>1.5.1 Free Agent Auction Budget (FAAB)</h4>
    <div class="subBlock">

        <p>How FAAB works - https://support.sleeper.app/en/articles/1876040-how-does-faab-bidding-work</p>

        <p>Each owner will receive $100 of FAAB money after the draft every year. Owners will have the ability to trade FAAB money. You cannot trade future FAAB money and will not be allowed to go into the negative. FAAB will not roll over into the next season</p>

        <p>You cannot exceed $1,000 of FAAB in a single season. Meaning since you start with $100 the maximum you can trade for throughout the year is an additional $900</p>

    </div>

    <h4 bind:this={oneFiveTwo}>1.5.2 Offseason Waivers</h4>
    <div class="subBlock">

        <p>Offseason Waivers will open after the draft and process once a week on Monday morning @ 10am. This gives every team enough time to see recent news and put their bids in for players</p>

    </div>

    <h4 bind:this={oneFiveThree}>1.5.3 Season Waivers</h4>
    <div class="subBlock">

        <p>Season waiver settings will take effect the week before the NFL season starts. Players must be on a roster for 24 hours after being picked up to go back on waivers. Any player picked up and dropped less than 24 hours later will become a regular free agent. Players cannot be dropped after their game has started. The waiver schedule will be as follows:</p>

        <li>Monday - FA</li>
        <li>Tuesday - Locked</li>
        <li>Wednesday - Waivers to FA</li>
        <li>Thursday - Locked</li>
        <li>Friday - FA</li>
        <li>Saturday - FA</li>
        <li>Sunday - FA</li>

        <p>Legend:</p>

        <li>Locked - no FA transactions allowed</li>
        <li>Waivers - players clear waivers at noon, other FA remain on waivers after</li>
        <li>Waivers to FA - players clear waivers at noon then become first come first serve</li>
        <li>FA - players are first come first serve all day</li>

    </div>

    <h3 bind:this={oneSix}>1.6 Divisional Breakdown</h3> 

    <p>At the Draft the top 3 teams based off playoff finish will draft their division mates for the upcoming season. The champion will pick 1st, runner-up 2nd, and winner of the 3rd place game will pick 3rd. It will be a serpentine draft with the 3rd place team picking twice in a row and so on</p>

    <p>Divisions are purely for scheduling and have no effect on playoffs or seeding</p>

    <h3 bind:this={oneSeven}>1.7 Scheduling</h3> 

    <p>After the Divisional draft the schedule will consist of 14 weeks:</p>
    </ul>
        <li>First 3 weeks – divisional matchups (random order)</li>
        <li>Next 8 weeks – non-divisional matchups (random order)</li>
        <li>Final 3 weeks – divisional matchups (random order)</li>
    </ul>

    <p>You will play the teams in your division twice and all other teams once</p>

    <p>Every week you will play against your opponent and the league median</p>



    <h3 bind:this={twoOne}>2.1 Draft Order</h3>
    <p>The draft order each year will be a linear draft in reverse order of the previous year’s regular season standings.</p>

    <h3 bind:this={twoTwo}>2.2 Rookie Drafts</h3>
    <p>Rokkie drafts will consist of 3 round of drafting, with 5 minutes alotted for each pick. To make room for the incoming players, benches will be expanded by (5) spots. These spots will be removed in mid-August, at which point you will need to have cut the necessary players.</p>
    <p>Any spots not filled during the draft, can be filled immediately afterwards from the waiver wire.</p>
    
    <h3 bind:this={twoThree}>2.3 Draft Day Trades</h3>
    <p>If a trade is being made during the draft, one or both parties can alert the commissioner to pause the draft to allow for extra time to negotiate the trade.</p>
    
    <h2 class="sectionHeading" bind:this={three}>Section 3 Scoring System</h2>

    <h3 bind:this={threeOne}>3.1 Scoring System</h3>
    <p>The league scoring system breakdown is listed on the Sleeper fantasy app (for the most part, it follows typical .5PPR Scoring). The scoring system will never change without a majority league vote.</p>
    
    <h2 class="sectionHeading" bind:this={four}>Section 4 Postseason</h2>
    
    <h3 bind:this={fourOne}>4.1 Playoffs</h3>
    <p>At the end of the season 6 teams will make the playoffs. The first round of playoffs will commence in week 15. Each team that wins their division and the 4 wild card teams that finish with the best records, will receive a playoff berth. The 2 teams that win their division will receive a bye week in the first round of the playoffs. Each playoff matchup will only last one week and the winner will advance. Week 18 will not be used.</p>
    
    <h3 bind:this={fourTwo}>4.2 Seeding Tiebreakers</h3>
    <p>If two teams finish with the same record the tiebreakers will go as followed:</p>

    <ol>
        <li>Points For</li>
        <li>Head 2 Head Record</li>
        <li>Division Record</li>
        <li>Total Points Against</li>
        <li>Coin Flip</li>
        <li>Duel to the death</li>
    </ol>

    <h2 class="sectionHeading" bind:this={five}>Section 5 Tanking Policy</h2>
    
    <h3 bind:this={fiveOne}>5.1 League Tanking Policy</h3>
    <p>No team may intentionally leave starting roster spots empty. Any evidence of intentionally leaving roster spots empty in order to improve your draft position may be subject to punishment, including but not limited to the forfeiture of draft selections.</p>

    <h2 class="sectionHeading" bind:this={six}>Section 6 Replacing Managers</h2>
    
    <h3 bind:this={sixOne}>6.1 Removing Managers</h3>
    <p>Short of continuously failing to set a valid lineup, or confirmed collusion, no manager can be removed against their will. Participation, through the league chat, trade offers, and the waiver wire, is strongly encouraged but generally grounds for removal.</p>
    
    <h3 bind:this={sixTwo}>6.2 Replacing Managers</h3>
    <p>When a manager needs to be replaced, the commisiooners will try to find a suitable candidate with some connection to at least a portion of the existing managers. Priority will be placed on managers who are eager to take on a dynasty commitment and will be very active within the league.</p>
    
    <h3 bind:this={sixThree}>6.3 Replacement Incentive</h3>
    <p>In the event that a manager chooses to quit the league or is removed by a comissioner, an incoming manager is offered a 50% reductioon on their first year buy-in.</p>

    <h2 class="sectionHeading" bind:this={seven}>Section 7 League Finances</h2>
    
    <h3 bind:this={sevenOne}>7.1 League Dues</h3>
    <p>League dues are set at {dues}$. Dues are collected through <a href="https://www.leaguesafe.com/league/3949641">LeagueSafe</a> and collection will be sent out no later than the first of August. All managers must be fully paid up before the start of regular season. In the event that a manager fails to pay before the deadline, a 10% penalty will be addd to their payment and will go towards the payouts at the end of the year.</p>
    
    <h3 bind:this={sevenTwo}>7.2 Payout</h3>
    <p>League payout is structured as follows:</p>
    <ul>
        <li>1st place: {dues * 8}$</li>
        <li>2nd place: {dues * 3}$</li>
        <li>3rd place: {dues}$</li>
    </ul>
    <p>In the event that a manager was fined due to late payment, their extra fee will be added to the winner's payout. Similarly, if new managers come into the league and the payout is smaller, the difference will come out of the winner's prize.</p>
    
    <h3 bind:this={sevenThree}>7.3 Raising Dues</h3>
    <p>A ⅔ majority vote is required in order to raise league dues. In the event that a manager is no longer financially comfortable with the buyin, finding a co-manager to split the cost is reccomended.</p>

</div>
