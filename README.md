# The Idea Of North 2.0: Documentation

## Dev version of the site:
[dev.theideaofnorth2.com](http://dev.theideaofnorth2.com)  
In order to get the time in seconds in the player, add the query parameter "debug": [dev.theideaofnorth2.com/?debug](http://dev.theideaofnorth2.com/?debug)  


## CMS

[theideaofnorth2.herokuapp.com/keystone](https://theideaofnorth2.herokuapp.com/keystone)  
Log in and update the site content. Once changes have been made, open a new tab to:  
[theideaofnorth2.herokuapp.com/api/config](https://theideaofnorth2.herokuapp.com/api/config)

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
- Create origin in CMS and remember its key (visible in the CMS on the origin page). Then open a new tab to:  
[theideaofnorth2.herokuapp.com/api/config](https://theideaofnorth2.herokuapp.com/api/config)
- Use chrome with the profile theideaofnorth2 and go to [dev.theideaofnorth2.com/capture.html](http://dev.theideaofnorth2.com/capture.html)
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
