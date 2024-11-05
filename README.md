# shimmer - pleasant firefox userchrome with sidebery support

## demonstration

### light theme with sidebery, sidebar on left side
![sidebery_light](https://github.com/user-attachments/assets/27a8b0b0-64dd-4807-b71c-ee1b50362054)

| menus                                                                                       | urlbar                                                                                     |
|---------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------|
| ![ctxmenu](https://github.com/user-attachments/assets/7da9bdff-d247-4680-ad20-70d12c886272) | ![urlbar](https://github.com/user-attachments/assets/fec1c172-78b3-4c2b-a98c-90fe23f47e4a) |

### compact sidebar (very proud of the icons :P)
![findbar](https://github.com/user-attachments/assets/942f7b2d-bb06-4d79-8487-9cf587fe8643)

### native tabs (no sidebery)
![tabs_darkmagic](https://github.com/user-attachments/assets/087c5eb0-a819-406f-aab9-6ddf6f270509)




## features
 - popover url-bar (see demo animated image)
 - works with custom themes (create an issue on github if you have any problems :D)
 - rounded browser/sidebar corners
 - minimized context menus
 - subtle, non-obstructive transitions
 - minimized findbar
 - setting available to move sidebar to the right side

## installation

 - download code from github (green "code" button)
 - download sidebery from mozilla addons if wanted
 - go to sidebery settings, styles editor
 - paste styles from sidebery.css into the textarea
 - press f1 to open sidebery
 - go to about:config
 - toggle `toolkit.legacyUserProfileCustomizations.stylesheets` true
 - toggle `svg.context-properties.content.enabled` true
 - if you're using firefox nightly, type `shimmer.nightly` into the config search box, then click `+` below
 - open about:profiles, find your profile and open the root folder
 - move "chrome" folder into the directory
 - reopen firefox
 - done! :3

## config
 i've implemented some custom `about:config` values for you to modify. the list is small right now but i'm hoping to see some ideas and issues pop up
 - `shimmer.nightly` - toggle true if using firefox nightly
 - `shimmer.show-sidebar-header` - toggle true to show sidebar header
 - `shimmer.show-sidebar-header-close-button` - even if you enable the header, the close button is automatically hidden. toggle this true to make it reappear
 - `shimmer.sidebar-right-side` - toggle true if you use sidebery on the right side. you have to move the sidebar first in firefox using the sidebar header, which has to be reenabled in config
   
 some of the usual buttons that appear on the right-click context menu are hidden. right now you can change them at the top of `userChrome.css`. i will maybe later introduce `about:config` variables for easier customization


## maintaining
 please keep in mind that i won't always have time to fix a problem created by a new version of firefox in a day. if you'd like to create a pull request, feel free to do so. if you find any issues, please report them at the "issues" tab on github.

## ko-fi
 if you want to send me moneys  
 [![KO-FI BUTTON](https://github.com/user-attachments/assets/18d7f816-f784-46b2-97b1-89173f68e227)](https://ko-fi.com/nuclearcodecat)