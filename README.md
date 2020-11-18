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

