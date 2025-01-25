![Icon](/page/custom/hdlogo.png)

# lifeinvader.com
A backup of lifeinvader.com, a promotional website hosted by Rockstar Games that was shut down in 2024.

Huge thanks to https://github.com/GreenSoupDeveloper; he is the main developer. At this point, I am just gathering information.

Also, big thank you to "MGgames100" for providing us with copies of all company websites and research to make this even possible.

Thank you to **EVERYONE** who made videos on this page or even just uploaded a picture of a post. This helped us a lot in puzzling the pieces together.

## Website: https://redsoupdev.github.io/lifeinvader.com/

## About this project:
This website was remade on the basis of "MGgames100" copies of all company websites, Wayback Machine code, Wiki pages, and most importantly, YouTube videos exploring the website and its pages.  
This website also works on mobile like the original but still has some bugs.

## List of known domains:
All of these have been restored at this point:
- https://www.lifeinvader.com/profile/elitas_travel
- https://www.lifeinvader.com/profile/herr_kutz
- https://www.lifeinvader.com/profile/inkinc
- https://www.lifeinvader.com/profile/legendary_motorsport
- https://www.lifeinvader.com/profile/los_santos_customs
- https://www.lifeinvader.com/profile/sprunk
- https://www.lifeinvader.com/profile/warstock_cache_n_carry
- https://www.lifeinvader.com/profile/karlkelly
- https://www.lifeinvader.com/profile/jackhowitzer
- https://www.lifeinvader.com/profile/drray
- https://www.lifeinvader.com/profile/duaneearl
- https://www.lifeinvader.com/profile/alanmcclean
- https://www.lifeinvader.com/profile/redwood_cigarettes

## Progress:
- All (known) pages have been restored.
- Index (custom made)
- Added Sign In/Out and logos (custom to restore features)
- Fixed and added a lot of missing/broken features of the page
- Localized all files and links
- Re-added disabled code (Comment - Share - Stalk Bar under posts)

## Current bug report:

Missing view picture feature: https://imgur.com/a/iSAnKyy
- You could press on arrows to switch pictures too

Missing function Comment/Share/Stalk bar: https://imgur.com/8BL8CHx  
- Bar has been fully implemented; the buttons do not work yet (unknown what exactly they did).

Missing stalk button on Warstock post: https://imgur.com/PIGnbU6  
  - There may be more on other posts; needs to be researched.

Cookies link on the bottom is broken on all pages.

Broken Stalk button:  
- How it is if pressed: https://imgur.com/XH53vjp  
- How it should be: https://imgur.com/KxayObr  

**Bugs on mobile**  

- If logged in, page scales wrong:  
Logged off: https://imgur.com/CpHopWq  
Logged in: https://imgur.com/OvAlvEZ  

- User icons under some posts are too big (inconsistent; on some they work, on some they don't. I think the placement of div is the problem):  
https://imgur.com/x1gwJBs
  - Size got fixed but position still broken  

- Our custom index page does not support mobile (only this one; the login page works):  
https://imgur.com/CN6yniW  

## What is from Rockstar Games and what was added by us?
- All pages inside the "profile" folder are from Rockstar Games **except the example page**. It is used to show how you could create your own custom pages and for testing new features.
- Index.html is **NOT** from Rockstar Games. It is made by us to make the website more user-friendly. The original index would just load a random page.
- Login.html and Logoff.html are **NOT** from Rockstar Games but from us to enable Social Club features like profile pictures and names. The pictures have been grabbed from Social Club.
- 404.html and page404.html are **NOT** from Rockstar Games. They were made for the GitHub website.
- The page/custom folder is **NOT** from Rockstar Games. It contains files for the 404.html, page404.html, Logoff.html, Login.html, and Index.html.
- The "main.js" inside the "page" folder contains custom code for the 404.html, page404.html, Logoff.html, Login.html, and Index.html under line 135.

## How to remove our additions and only use Rockstar Games code:
- Get this index.html:  
```html
<!DOCTYPE html>
<html lang="en">
<head>
   <link rel="shortcut icon" href="page/favicon.ico">
   <script src="page/main.js"></script>
</head>
<body>
   <script>
      // Automatically redirects to a random page when this script runs
      randomPage();
   </script>
</body>
</html>
```
- Delete all files from root except your new "index.html", "login.html", and "logoff.html".
- Delete the "member" folder from root.
- Delete the "example_site" folder and the "example_site.htm" file.  
This gives you the website like it was hosted by R*. The only non-Rockstar pages will be "login.html" and "logoff.html", but these are required to access all content.

All rights to these pages belong to Rockstar Games and Take-Two Interactive.
