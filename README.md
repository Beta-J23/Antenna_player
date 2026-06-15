A simple tv and radio player all in browser.

Available at https://beta-j23.github.io/Antenna_player/

Currently only tv channels fetching from m3u8 playlist is available. The program fetches directly only the italian channels, this is just a test.

Currently, the player opens in a new window since with thismethos is possible to open all channels.

The goal of this project is to have a simple player that can be run also on old android tablets (android 4.4),  so next step will be:
- testing on android 4.4
- modify the parsing to fetch channels since old android use an old version of chrome that do not accept some functions of recent javascript.
- put some flags to fetch channels for different nations (many contents could be geo-blocked), but this depends from the list you choose.
