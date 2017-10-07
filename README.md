# The Idea Of North 2.0: Documentation

## Dev version of the site:
Normal version:   
[dev.theideaofnorth2.com](http://dev.theideaofnorth2.com)  
Light version:   
[dev.theideaofnorth2.com/?light](http://dev.theideaofnorth2.com/?light)  
In order to get the time in seconds in the player, add the query parameter "debug": [dev.theideaofnorth2.com/?debug](http://dev.theideaofnorth2.com/?debug)  


## CMS

Normal version:   
[theideaofnorth2.herokuapp.com/keystone](https://theideaofnorth2.herokuapp.com/keystone)  
Light version:   
[theideaofnorth2-light.herokuapp.com/keystone](https://theideaofnorth2-light.herokuapp.com/keystone)  

## Assets

#### Interview sounds
- Upload sound in .mp3 or .m4a format to Bluehost under 'assets/sounds/'
- Add file name to interview in CMS

#### Egg videos
- Upload video to youtube and copy ID of the video (last part of the url once published)
- Add ID to egg in CMS

#### Egg icons:
- Create icon in svg in a square format (the image will be displayed in a 63px X 63px square on the site)
- Upload image to Bluehost under 'assets/images/eggs/'
- Add file name to egg in CMS

#### Cities images:
- Upload image in full HD to Bluehost under 'assets/images/cities/'
- Add file name to destination or origin in CMS

#### Interview images:
- Upload images in full HD to Bluehost under 'assets/images/interviews/CUSTOM_ID_OF_INTERVIEW'

#### Zoomer images:
- Create origin in CMS and remember its key (visible in the CMS on the origin page)
- Use chrome with the profile theideaofnorth2 and go to [dev.theideaofnorth2.com/capture.html](http://dev.theideaofnorth2.com/capture.html) (for the light version: [dev.theideaofnorth2.com/capture.html?light](http://dev.theideaofnorth2.com/capture.html?light))
- Choose origin and click "Open tabs" (you may need to allow the site to open multiple popups)
- Generate screenshots of all tabs with the screen capture extension installed (button is at the right of the URL bar), and save them with their zoom level as file name (ex: "12.jpg"). The zoom level is the last number in the URL.
- Upload all images to Bluehost under 'assets/images/zoomers/KEY_OF_ORIGIN/' 

## Slideshow:
- Edit Google Drive spreadsheet named "slideshow" located in "TheIdeaOfNorth2/interviews/themes/"
- Each sheet in the document must be named after the custom ID of the interview (visible in the CMS)
- Once changes have been named, click in the menu bar "Add-ons", "Export Sheet Data", "Open Sidebar"
- tick the first checkbox "Replace existing file(s)" and the checkbox "Export sheet arrays" under "JSON Options" and click the "Export" button
- Wait for the json file to be generated, then open it in Drive and save it locally to the project folder
- Upload the file "slideshow.json" to Bluehost in the directory "api/"

## CDN
Cloudflare, a free CDN, is used to speed up the load time of images. In order to purge the cache:
- Use chrome with the profile theideaofnorth2
- Log in to cloudflare (login / password are already saved)
- Go to the cache section
- Select "purge individual file" or "purge all files"
More information can be found on the [Cloudflare support page](https://support.cloudflare.com/hc/en-us/articles/200169246-How-do-I-purge-my-cache-)
