# mse-with-two-source-bufffers

Basic MSE-based playback using Media Source and MPD Manifest Parser

## Install dependencies

`npm i`

## Build

`npm run build`

## Start local server

`npm run start`

## To play with EC-3 Audio

By default the player will pick EC-3 Audio track

## To Play with mp4a Audio

change the following in code and restart the app

```javascript
const isEc3Audio = true; // Change this to false
startPlayback(isEc3Audio);
```
