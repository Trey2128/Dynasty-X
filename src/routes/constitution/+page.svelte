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
    
        <h4 class="noUnderscore clickable" onclick={() => goToSection(sixOne)}>6.1 Expansion</h4>
            <h5 class="noUnderscore clickable" onclick={() => goToSection(sixOneOne)}>6.1.1 Setup</h5>
            <h5 class="noUnderscore clickable" onclick={() => goToSection(sixOneTwo)}>6.1.2 The Expansion Draft</h5>
            <h5 class="noUnderscore clickable" onclick={() => goToSection(sixOneThree)}>6.1.3 After the Draft</h5>

    <h3 class="noUnderscore clickable" onclick={() => goToSection(seven)}>Section 7: League Finances</h3>
    
        <h4 class="noUnderscore clickable" onclick={() => goToSection(sevenOne)}>7.1 League Dues</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(sevenTwo)}>7.2 Payouts</h4>
        <h4 class="noUnderscore clickable" onclick={() => goToSection(sevenThree)}>7.3 Raising Dues</h4>
    
    
    <hr />
    
    <h2 class="sectionHeading" bind:this={one}>Section 1: Roster</h2>
    
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

    <ul>
        <li>1st round pick - 1st + 2nd round picks</li>
        <li>2nd round pick - 1st round pick</li>
        <li>3rd round pick - 2nd round pick</li>
        <li>4th round pick - 3rd round pick</li>
        <li>Free Agent pickup - 4th round pick</li>
    </ul>

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

        <ul>
            <li>First Offense – Loss of current year 1st round draft pick & one year playoff ban (for both teams if trade is accepted)</li>
            <li>Second Offense – Removal from league</li>
        </ul>

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
    <ul>
        <li>First 3 weeks – divisional matchups (random order)</li>
        <li>Next 8 weeks – non-divisional matchups (random order)</li>
        <li>Final 3 weeks – divisional matchups (random order)</li>
    </ul>

    <p>You will play the teams in your division twice and all other teams once</p>

    <p>Every week you will play against your opponent and the league median</p>


    <h2 class="sectionHeading" bind:this={two}>Section 2: Ownersship Expectations</h2>

    <h3 bind:this={twoOne}>2.1 Setting Lineups</h3>

    <p>All owners are expected to set their lineups every week. Tanking is not allowed so sitting star players, having healthy players on IR, starting players who aren’t playing, or leaving starting lineup spots empty will result in disciplinary action. Those are as follows:</p>

    <ul>
        <li>First Offense – 10 points added to your season Max Points for every spot left empty/healthy player on IR</li>
        <li>Second Offense – 10 points added to your season Max Points for every spot left empty/healthy player on IR + forfeiture of 2nd round pick</li>
        <li>Third Offense – 10 points added to your season Max Points for every spot left empty/healthy player on IR + forfeiture of 1st round pick</li>
        <li>Fourth Offense – Removal from the league</li>
    </ul>

    <p>Only exceptions are:</p>

    <ol>
        <li>When an owner is leading while their opponent has no players left to play. This way a player can’t score negative points and cost that owner the game</li>
        <li>When there’s no available free agents to pickup and start or an owner is outbid for said free agent</li>
    </ol>

    <p>If an owner is dismissed for not setting lineups then the new owner taking over will have the max point additions removed and their draft picks reinstated</p>


    <h3 class="subSectionHeading" bind:this={twoTwo}>2.2 Leaving the League</h3>

    <p>If you would like to sell the ownership of your team for the current season, you will be responsible for finding someone interested in purchasing it. If you plan on leaving in a future season please let me know ASAP so I can work on finding a new owner to keep the league running as smoothly as possible. If you have paid future dues for any trades that have been completed these dues WILL NOT be refunded</p>

    <h4 bind:this={twoTwoOne}>2.2.1 New Owners</h4>
    <div class="subBlock">

        <p>A new owner taking over a team that does not have both their 1st and 2nd round picks will not have to pay the league fee that season, and the current season pot will be decreased by $50 (with the $50 deposit the previous owner paid for that year going toward the kitty and pot). A decrease of $50 will result in each payout being reduced by $10 that season. The new owner may also get a discounted league fee ($50) their first season if they are taking over a team that has a very poor outlook for the future. This way if an owner leaves a terrible team it’s not impossible to fill it. It also gives the new owner a discount year to accrue picks and other assets to begin a rebuild</p>

    </div>

    <h3 bind:this={twoThree}>2.3 Removal</h3>

    <p>The owners can vote to remove any owner from the league during each offseason. As long as they feel this owner is ruining the integrity of the league and they can provide acceptable evidence. If any owner is removed it will fall on the commissioner to replace said owner. If an owner has paid and is subsequently removed before the start of the fantasy season they will receive a league fee refund</p>

    <p>Future dues paid for draft pick trades already made WILL NOT be refunded as reversing these trades could undo the league and giving a refund will screw over future owners of that team or the kitty. Just don’t do stupid stuff and we won’t have to worry about this</p>

    <p>Owners cannot be voted out during the season, only removed for egregious misconduct</p>

    <p>If an owner quits or is removed in the middle of the fantasy season, it will fall on the commissioner to manage said team until a new owner is found. No roster transactions will be allowed to occur with this team until a new owner is found, only setting the starting lineup</p>

    <h3 bind:this={twoFour}>2.4 Rule Voting</h3>

    <p>Each season new rules and regulations will be brought to the attention of the owners at the league draft. All rules and regulations will be voted on and must receive a majority vote to be approved. Majority vote is classified as 7 or more votes</p>

    <p>Please send any new rule ideas to me prior to the draft to make sure it is possible to implement them on the Sleeper site. This ensures that we don’t waste time voting on impossible rules</p>

    <h3 bind:this={twoFive}>2.5 Last Place Punishment</h3>

    <p>The owner who loses the toilet bowl will have to pay for the new plaque engraving on the trophy for the winner. This will be $15 for taxes and shipping. This fee will be added to their following season’s dues</p>

    
    <h2 class="sectionHeading" bind:this={three}>Section 3: Drafting</h2>

    <h3 bind:this={threeOne}>3.1 Draft Order</h3>

    <p>The draft order for the first 6 picks will be determined by reverse max points with only non-playoff teams being eligible. The following 6 picks will be determined by playoff finish</p>

    <h3 bind:this={threeTwo}>3.2 Draft Day Trades</h3>

    <p>All trades during the league draft must be made within the 10 minute timer. Once a trade has been completed the timer will reset to allow the new team to make a selection</p>

    <p>FUTURE PICK TRADE RULES STILL APPLY</p>

    <h3 bind:this={threeThree}>3.3 Draft Date & Time</h3>

    <p>2027 Draft - TBD</p>


    <h2 class="sectionHeading" bind:this={four}>Section 4: Scoring System</h2>
    
    <h3 bind:this={fourOne}>4.1 Scoring</h3>

    <p>Passing</p>
    <ul>
        <li>TD: 4</li>
        <li>Yards: .04 point per yard</li>
        <li>Interception: -2</li>
        <li>Sack: -0.5</li>
        <li>2-Pt Conversion: 1</li>
    </ul>

    <p>Rushing</p>
    <ul>
        <li>TD: 6</li>
        <li>Yards: .1 point per yard</li>
        <li>2-Pt Conversion: 2</li>
    </ul>

    <p>Receiving</p>
    <ul>
        <li>Reception: 0.5 (1 for TE)</li>
        <li>TD: 6</li>
        <li>Yards: .1 point per yard</li>
        <li>2-Pt Conversion: 2</li>
    </ul>

    <p>Special Teams</p>
    <ul>
        <li>Return Yards: .02 point per yard</li>
        <li>TD: 6</li>
    </ul>

    <p>Miscellaneous</p>
    <ul>
        <li>Fumble: -3</li>
        <li>Fumble Recovery TD: 6</li>
    </ul>

    <h3 bind:this={fourTwo}>4.2 Voting on Scoring System</h3>

    <p>Each season at the draft, owners can bring forth any scoring proposals they would like to see changed. If the proposal is well received, we will proceed with a league vote. If the proposal receives a majority vote, it will be approved</p>


    <h2 class="sectionHeading" bind:this={five}>Section 5: Postseason</h2>
    
    <h3 bind:this={fiveOne}>5.1 Playoffs</h3>

    <p>At the end of the season the top 6 teams will make the playoffs. The top 2 teams will receive a bye week in the first round. Each playoff matchup will only last one week and the winner will advance. Each week of the playoffs is reseeded with the higher seed teams always playing the lower ones</p>

    <h3 bind:this={fiveTwo}>5.2 Playoff Tiebreakers</h3>

    <p>If two teams tie in the playoffs, the playoff tiebreaker will be bench points scored. If they are also tied in bench points, it will go to the team with the higher seed</p>

    <h3 bind:this={fiveThree}>5.3 Seeding Tiebreakers</h3>

    <p>If two teams finish with the same record the tiebreakers will go as follows:</p>

    <ol>
        <li>Points For</li>
        <li>Head 2 Head</li>
        <li>Total Points Against</li>
        <li>Coin Toss (conducted by Sleeper)</li>
    </ol>

    <h3 bind:this={fiveFour}>5.4 Toilet Bowl</h3>

    <p>The 6 teams not in the playoffs will be put into the Toilet Bowl. Seeding works the same way as the playoffs except the bottom 2 teams get a bye. The winners of each week will get “flushed” out and the losers advance. The team who loses every game will receive the punishment of buying a new plaque</p>


    <h2 class="sectionHeading" bind:this={six}>Section 6: Expansion</h2>
    
    <h3 class="subSectionHeading" bind:this={sixOne}>6.1 Expansion</h3>

    <p>This is how we would conduct expansion if we ever do. It does not mean we are guaranteed to expand. I just wanted this put in place so nobody was surprised by the process if it were to ever happen. Expansion will always be in increments of 2, never leaving an odd number of teams</p>

    <h4 bind:this={sixOneOne}>6.1.1 Setup</h4>
    <div class="subBlock">

        <p>Every team will “franchise tag” 9 players they would like to keep. The 9 players must be made up of different positions. The position limits are as follows:</p>

        <ul>
            <li>1 QB</li>
            <li>2 RBs</li>
            <li>3 WRs</li>
            <li>1 TE</li>
            <li>2 Flex</li>
            <li>1 Superflex</li>
        </ul>

        <p>All non-tagged players including free agents will be put into an expansion draft. This will leave at least 1 “starting caliber” player available from every team</p>

    </div>

    <h4 bind:this={sixOneTwo}>6.1.2 The Expansion Draft</h4>
    <div class="subBlock">

        <p>The 2 expansion teams will conduct a 22-round serpentine draft from the available player pool of non-tagged players and free agents. This draft will have no position limits. The limit of players that can be drafted from a single team is 4. Whenever a player is drafted from a team that team’s owner is allowed to immediately tag an additional player</p>

    </div>

    <h4 bind:this={sixOneThree}>6.1.3 After the Draft</h4>
    <div class="subBlock">

        <p>Following the 22 round expansion draft, the original 12 teams will have to lower their roster to 22 players if they’re not there already. The rookie draft will proceed as normal with the 1.01 and 1.02 given to the 2 expansion teams. The rookie draft would then be trimmed to 3 rounds along with the Taxi Squad to 3 spots</p>

    </div>


    <h2 class="sectionHeading" bind:this={seven}>Section 7: League Finances</h2>
    
    <h3 bind:this={sevenOne}>7.1 League Dues</h3>

    <p>League Fee Deadline – July 1st</p>

    <p>League fees of $100 have a deadline of 2 weeks prior to the draft. Owners are expected to pay this fee by the deadline to get payouts situated. The league fee breakdown goes as follows:</p>

    <ul>
        <li>$80 towards season payouts</li>
        <li>$20 towards the 5 year kitty</li>
    </ul>

    <h3 bind:this={sevenTwo}>7.2 Payout</h3>
    <p>League payout is structured as follows:</p>

    <p>Annual Pot</p>

    <ul>
        <li>1st place - $500</li>
        <li>2nd  place - $250</li>
        <li>3rd place - $110</li>
        <li>4th place - $50</li>
        <li>High Score - $50</li>
    </ul>

    <p>Kitty</p>

    <ul>
        <li>1st place - $600</li>
        <li>2nd place - $400</li>
        <li>3rd place - $200</li>
    </ul>

    <h3 bind:this={sevenThree}>7.3 Raising Dues</h3>

    <p>After the kitty is paid out we can hold a league vote to raise dues. A ⅔ majority is required for this to pass. Voting will be held every 5 years</p>

</div>
