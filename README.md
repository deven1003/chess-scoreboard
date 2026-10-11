# Chess Scoreboard

A head-to-head chess scoreboard for tracking games between two players (PARESH vs DEVEN).

**Live site:** https://deven1003.github.io/chess-scoreboard/

## Features

- Record each game with the result and which colour each player had
- Filter the history by player, colour (white / black) and result (wins / draws)
- Edit player names and link their Chess.com usernames
- Data is saved in the browser (`localStorage`), so nothing needs a server
- **Export / Import JSON** to back up the history or move it to another device

## Run locally

It's a single static page:

```sh
git clone https://github.com/deven1003/chess-scoreboard.git
cd chess-scoreboard
# open index.html in your browser
```

> Because scores live in `localStorage`, each browser keeps its own copy. Use **Export JSON** regularly as a backup.
