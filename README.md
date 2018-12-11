# Download HKUST Lecture Video

Download the HKUST streaming lecture video by parsing and getting the ts url link, then download them individually.

## How to use

1. Log in UST CAS / [UST canvas](https://canvas.ust.hk)
2. Go to the lecture video URL, such as `https://ptz141.ust.hk/rvcprotected/mp4:18FA_CIVL1160-L1_181022_45315.mp4/media_w1817981_6.ts?UId=XXXXXX&SessionId=XXXXXXXXXX`
3. Open the browser development console, in Chrome example, by `cmd` + `option` + `j`
4. Copy and paste the code from `index.js` to Chrome console

The lecture video ts files will then download automatically, and will stop after all files are downloaded, usually 4xx ~ 5xx files for a lecture class.

## How to combine the ts files