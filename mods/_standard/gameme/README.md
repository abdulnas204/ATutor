# ATutor Gamification Module
This module provides tools for creating gamification elements, adding them to courses, and monitoring student behaviour. It can be used to motivate students, as they collect points and badges, with tailored rewards for actions taken and milestone accomplishments met.

## Gamification Base

PHPGamification

Cloned from: https://github.com/TiagoGouvea/PHPGamification.git

## Module Code

ATutor module repository: gameme

https://github.com/atutor/gameme
## Features
### Admin

* Create and maintain game elements: levels, events, and badges
* Enable/Disable instructor game element creation

### Instructor

* Create and maintain course level game elements: levels, events, and badges (if enabled)
* Enable/Disable game elements within their courses
* Review user participation and accomplishments

### Student

#### Collect badges for accomplishments per course
* 1 profile_view_badge    
* 2 profile_viewed_badge  
* 3 profile_pic_upload_badge 
* 4 prefs_update_badge 
* 5 read_page_badge
* 6 new_folder_badge 
* 7 upload_file_badge 
* 8 create_file_badge 
* 9 forum_view_badge 
* 10 forum_post_badge 
* 11 forum_reply_badge 
* 12 blog_add_badge
* 13 blog_comment_badge 
* 14 chat_login_badge 
* 15 chat_post_badge
* 16 link_add_badge
* 17 photo_create_album_badge 
* 18 photo_create_album_badge
* 19 photo_upload_badge 
* 20 photo_comment_badge 
* 21 photo_album_comment 
* 22 photo_description_badge 
* 23 photo_alt_text 
* 24 login_badge
* 25 logout_badge
* 26 welcome_badge

#### Advance through levels with course participation
* logins  
* logouts  
* forum views 
* forum posts 
* forum replies 
* blog posts 
* blog comment 
* blog view 
* content page views 
* content page duration 
* chat login 
* chat post 
* link add  
* link view 
* poll responses  
* photo gallery create album 
* photo gallery view album  
* photo gallery view image  
* photo gallery view image   
* photo gallery add photo comment   
* photo gallery add photo alt text   
* photo gallery add photo description   
* photo gallery add album comment  (one comment per session only)
* calendar events added XXXXX (Waiting on Herat)
* profile views of others 
* others view of your profile 
* add a profile picture 
* private messages send (inbox) 
* view reading list item 
* files uploaded to file storage 
* new file created with file storage 
* comment on file in file storage 
* file descriptioon for file in file storage 
* update personal preferences 

#### See who are the most active, and most accomplished
* leaderboard showing the top contributors (sidemenu, progress tab) 

#### See your progress to the next level (sidemenu, progress tab) 

#### Badge and level icon default max file sizes
$max_levelicon_size = 15000;  // maximum file size for  level icon in bytes
$max_height = 95;
$max_width = 95;


