# The Idea Of North 2.0: Documentation

## Dev version of the site:
Normal version:   
[dev.theideaofnorth2.com](http://dev.theideaofnorth2.com)  
In order to get the time in seconds in the player, add the query parameter "debug": [dev.theideaofnorth2.com/?debug](http://dev.theideaofnorth2.com/?debug)  


## CMS

Available at:   
[theideaofnorth2.com/admin](https://theideaofnorth2.com/admin)  

## Assets

#### Egg videos
- Upload video to youtube and copy ID of the video (last part of the url once published)
- Add ID to egg in CMS

#### Egg icons:
- Create icon in svg in a square format (the image will be displayed in a 63px X 63px square on the site)

#### Zoomer images:
- Use chrome with the profile theideaofnorth2 and go to [dev.theideaofnorth2.com/capture.html](http://dev.theideaofnorth2.com/capture.html)
- Choose origin and click "Open tabs" (you may need to allow the site to open multiple popups)
- Generate screenshots of all tabs with the screen capture extension installed (button is at the right of the URL bar), and save them with their zoom level as file name (ex: "12.jpg"). The zoom level is the last number in the URL.
- Add images to the CMS as zoomers 

## CDN
Cloudflare, a free CDN, is used to speed up the load time of images. In order to purge the cache:
- Use chrome with the profile theideaofnorth2
- Log in to cloudflare (login / password are already saved)
- Go to the cache section
- Select "purge individual file" or "purge all files"
More information can be found on the [Cloudflare support page](https://support.cloudflare.com/hc/en-us/articles/200169246-How-do-I-purge-my-cache-)
