[![badge](https://img.shields.io/twitter/follow/api_video?style=social)](https://twitter.com/intent/follow?screen_name=api_video)

[![badge](https://img.shields.io/github/stars/apivideo/deleteVideoDemo?style=social)](https://github.com/apivideo/deleteVideoDemo)

[![badge](https://img.shields.io/discourse/topics?server=https%3A%2F%2Fcommunity.api.video)](https://community.api.video)

![](https://github.com/apivideo/.github/blob/main/assets/apivideo_banner.png)

<h1 align="center">api.video video deletion</h1>

[api.video](https://api.video) is the video infrastructure for product builders. Lightning fast video APIs for integrating, scaling, and managing on-demand & low latency live streaming features in your app.


# deleteVideos

This demo uses api.video's delete API to remove videos from the cloud storage.

Test this demo live at [delete.a.video](https://delete.a.video)

## What's happening

This very simple demo queries an api.video account for videos with the title "Live Stream" and sorts them oldest to newest.  The response only requests 3 such videos.  The thumbnail and creation date are presented on the page

On pressing the ```DELETE``` button, the api uses the videoID for all three videos and calls the delete endpoint - permanently removig them from the server.

## Another delete

https://github.com/dougsillars/deleteVideos

is the parent application to this one. Since this demoo allows for deleting videos from an account - it is limited to only one search term.

This version allows for searches on video tag or video name.

## installation

clone the repo
npm install (for all dependencies)
node src/index.js
