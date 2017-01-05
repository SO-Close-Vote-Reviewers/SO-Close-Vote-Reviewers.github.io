Random notes about the SOCVR GitHub page.

# Folders

  - _posts  holds the top level articles
  - tools/_posts hold the tools artcles
  - room/_posts hold the room articles
  - room/meeting/_posts hold the roommeeting articles

# categories

- tools, room and meeting are categories
- they are used in _includes\*header.md to render the correct menu items
- a post appears in the top menu if the Front Matter contains: ```main: title of page```
- a post that appears in an subment needs in the Front Matter contains: ```menu: text for menu```
- the correct header file is chosen in default.html 

### DON'T BREAK OLD LINKS

- the files in _posts folders that have their ```permalink``` specified require this because otherwise old links that are out in the wild will no longer work
- in the .config.yml the permalink setting is removed which enables us to deep link to the files we have (for example /room/meetings/2016/10/03/October-2016-meeting.html)
- These changes should make it easier to add new content and re-organize or add new index pages when needed.

# Notes

 - New post must be in "_posts" in the following pattern: "YEAR-MONTH-DAY-TITLE"
 - Files can be written in simple markdown and need this at the start of each post
 
  ```
---
layout: default
title: XY
---
  ```
  
 - Links to other posts must follow this pattern "{% post_url YEAR-MONTH-DAY-TITLE %}"
 - More information see: https://jekyllrb.com/
 
