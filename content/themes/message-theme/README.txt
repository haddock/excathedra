Thank you for Purchasing "Message Theme"!

Updated 04/05/2014
Updated for Ghost 0.4.2
Added Tag Pages - using index.hbs
Added Search Page
Added Read Time To Posts



HOW TO USE:

PLEASE UPDATE YOUR GHOST INSTALLATION TO 0.4.2


IF YOU ARE UPDATING
Please note: If you have made any edits/additions to the templates, this update will overwrite them.
If you like, you can rename the message-theme folder, to retain the older version.
Upload the entire message-theme folder to /ghost/content/themes/
Restart Ghost if needed.
Activate the theme in the Ghost admin panel.


ACTIVATE
Upload the entire message-theme folder to your Ghost themes directory.
Restart Ghost if needed.
Activate the theme in the Ghost admin panel.


STATIC PAGES
To add static pages, create a new post in the Ghost admin and set it to a static page using the gear icon in the bottom right of the Ghost editor.
To link to static pages, open /partials/drawer.hbs 
Add your link to the list.
For example, the code below will add a link to a page named "About Us"
<li><a href="{{@blog.url}}/about-us">About Us</a></li>

SEARCH PAGE
To have a search page: Create a static page in the Ghost admin called "Search" Un-comment the search link in /partials/drawer.hbs


FEATURED IMAGES
Featured images and Blog cover should be at least 1000px wide by 500px tall - I wouldn't use much bigger in order to keep it optimal.

Message Theme expects a featured image for each post/page. If no image is provided, it will fall back to your blog cover.
To create a featured image use this code in the editor: ![main-image](http://YOUR IMAGE URL) and make sure it is the first thing in your post.


FOLLOW URLS
Open /partials/author.hbs
Line 23 - 25 contain the urls for Facebook, Twitter and Google Plus
Simply edit the link to point to your profile
E.G. https://www.facebook.com/yourfacebookpage

Remove the links you don't want.

To add links, simply add a line to the list.

For example, the following will add a link and icon to a Behance profile.
<li><a href="http://www.behance.net/yourprofile" class="gplus" target="_blank"><img src="{{@blog.url}}/assets/img/icons/32/behance.png" /></a></li>

You will find 32px icons for 84 social networks in: /assets/img/icons/32
Or 64 px icons in: /assets/img/icons/64

32px are suggested for the follow buttons


THAT'S IT
Everything else should be automatic.

Any questions, please contact us at:

http://madeforghost.com/

Thank you!