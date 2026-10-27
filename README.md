# PropDesk

PropDesk is a single-page tool for researching player props. It puts each prop line next to the player's recent game logs, so you can see how often the player has gone over or under that number before you bet it.

**Use it here: [propdeskbet.netlify.app](https://propdeskbet.netlify.app)**. Nothing to download or install.

## What it does

- **Props table.** Every player prop on the slate with its line, odds and side, plus hit rates for the last 5, 10 and 15 games, the season and head-to-head against tonight's opponent. It also shows the current streak and the gap between the player's average and the line.
- **Filters and sorting.** Filter by team, minimum L10 hit rate (60% to 100%) and odds range. Sort by any hit-rate window, streak, average, odds or name. You can switch between a table and a card view, and choose to show the side as listed or the stronger side for each prop.
- **Player detail.** Click a player to open a game-log chart that draws the line across their recent games, with their stats for each game.
- **Slate and date picker.** Step through days or pick one from a calendar to see that day's games and the players in them.
- **Live sportsbook odds.** Pull real prop lines and prices from DraftKings, FanDuel, BetMGM, Hard Rock Bet, theScore Bet and PrizePicks (Fanatics needs a paid odds plan). Pick one book, or "Best price" to see the highest payout for each prop. Props with no posted price show "—" instead of a made-up number. You can also type in your own line and odds for any prop.
- **Pick slip.** Star props to add them to a slip and build a parlay.
- **Light and dark themes.**

## Leagues

NBA, WNBA, NFL, MLB, college football, and men's and women's college basketball.

## How to use it

Open [propdeskbet.netlify.app](https://propdeskbet.netlify.app) in any browser, on desktop or phone.

When the page can reach ESPN's public API, it pulls live schedules, rosters, game logs and headshots. Recent game logs are cached in your browser so they load faster the next time. If the API can't be reached, the page falls back to the snapshot of data built into the file.

## Live odds setup

Live odds come from [The Odds API](https://the-odds-api.com). Each person uses their own key:

1. Sign up for a free key at the-odds-api.com. The free plan gives 500 credits a month.
2. On the site, open the sportsbook menu (top right), paste the key and tap **Save**. The key stays in your browser only. It is never sent to GitHub or anyone else.
3. Pick a game, or leave all games showing, and tap **Load odds**. One game costs about 4 credits. Loaded prices are saved and reload for free for 30 minutes.

## Notes

- Hit rates come from past games only. They don't account for injuries, minutes changes or lineup news.
- Live data relies on ESPN's unofficial public endpoints, which can change or go down without notice.
- This is a research tool, not betting advice. Bet responsibly and only where it's legal for you.
