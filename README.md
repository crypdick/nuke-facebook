# nuke_facebook
Actiona scripts that automate mass deletion and unliking of Facebook content.

## The Problem
Facebook does not have an easy way to delete content en mass, and their API has disabled deletion (so you can't make a third party app to do it). This project implements a workaround using [Actiona](https://github.com/Jmgr/actiona), a cross-platform automation tool. The scripts are very simple: they simulate mouse movement, clicking, and keyboard presses to navigate FB menus to delete content. All the scripts are open source and can be modified to automate other tedious Facebook tasks.

## Editing scripts
If one of the steps in the script is not working correctly, make sure that the first step of the script is moving the cursor to the right place.

# Deleting albums
Go to 'https://www.facebook.com/[your-username-here]/photos_albums' and use the 'delete all albums.ascr' script to delete them.

# Delete all photos inside album
Some albums can't be deleted (such as your Profile and Timeline albums). You need to go into them individually and run the 'delete all photos inside album.ascr' script.

[![Automatically deleting all the pictures in your Facebook Profile album](https://img.youtube.com/vi/GXBGFrCzhw8/0.jpg)](https://www.youtube.com/watch?v=GXBGFrCzhw8)

# Deleting activity
Go to 'https://www.facebook.com/[your-username-here]/allactivity' to view your liked content, pages, apps, etc.

## Likes
On the left side, click "Likes". Run the 'unlike all liked content.ascr'. This will take hours!
[![Automatically unliking all your Facebook Likes](https://img.youtube.com/vi/Nu-MalmHSoo/0.jpg)](https://www.youtube.com/watch?v=Nu-MalmHSoo)

## Pages
Similarly, click the "Pages" on the left side and run 'unlike all pages.ascr' to delete all liked pages.

## Apps
Same as above. Run 'remove all apps.ascr'
