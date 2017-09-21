# A Node.js Discord Game Stats Bot!
-------------

### Setup:

* Goto https://discordapp.com/developers/docs/intro click Applications > My Apps on te left and side.
 * Click New App and set up your bot, Under 'APP BOT USER' copy the token this is the token for clientToken.
 * Edit index.js
 * Add your `clientToken` to line 5
 * Add your server ip to `YorServerIP` on line 8
 * Add your server port to `YorServerPort` on line 9
 * Goto https://pubgtracker.com/site-api signup and get a PUBG api key.
 * Add your PUBG api key to `apikey` on line 12

`npm install`

`npm start` or `node index.js`

Done..

### Bot Commands

* !info for server info
* !Players for a list of online players
* !stats for info/players
* !search for other server stats expample: `!search 45.121.211.65 2302`
* !pubg for PUBG player stats example: `!pubg AHappyTeddyBears`