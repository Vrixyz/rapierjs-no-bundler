# Readme

This folder provides a reproduction for
[discord's discussion](https://discordapp.com/channels/507548572338880513/1386258005628293192/1392511570260791326):
 we need to "monkey patch" (change the downloaded file in `node_modules/..`) the package.json to remove `"type": "module",`.

## Reproduction

run `npm install`
run `npm run start`: an error will guide you to make the fix mentioned above.
