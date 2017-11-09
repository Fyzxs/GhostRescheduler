#Ghost Blog Rescheduler

##It's Hacky
##It's Crappy
#BUT
##It's Working


This is a minimal Electron application based on the [electron-quick-start](https://github.com/electron/electron-quick-start).

This is a quick and so so very dirty app to be able to drag and drop Ghost blog posts.
I normally have almost 2 dozen posts queued for weekly posting. Trying to insert a post... pain in the ... buttock.

## To Use
For most of the setup; follow what the Electron Quick Start guide says to do. This isn't packaged as an app - I don't know NEAR enough right now to make this good.

Once you run the app; you'll need to follow the steps outlined in the [Ghost Docs](https://api.ghost.org/docs/user-authentication) to get a bearer token.
With that; you'll fill in the domain; the full domain for any self hosted solutions; and fill in the text box with the Bearer Token.

This needs to be the full value; "Bearer BASE64-FTW!"

Hit refresh and in a moment your posts should be pulled down.
