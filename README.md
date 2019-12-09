# ShortenURL
:scissors: Shorten or Expand your URLs with a simple bash command

***
**Example:** </br>
<details>
  <summary> Input URL </summary>
http://developers.jollypad.com/fb/index.php?dmmy=1&fb_sig_in_iframe=1&fb_sig_iframe_key=8e296a067a37563370ded05f5a3bf3ec&fb_sig_locale=bg_BG&fb_sig_in_new_facebook=1&fb_sig_time=1282749119.128&fb_sig_added=1&fb_sig_profile_update_time=1229862039&fb_sig_expires=1282755600&fb_sig_user=761405628&fb_sig_session_key=2.IuyNqrcLQaqPhjzhFiCARg__.3600.1282755600-761405628&fb_sig_ss=igFqJKrhJZWGSRO__Vpx4A__&fb_sig_cookie_sig=a9f110b4fc6a99db01d7d1eb9961fca6&fb_sig_ext_perms=user_birthday,user_religion_politics,user_relationships,user_relationship_details,user_hometown,user_location,user_likes,user_activities,user_interests,user_education_history,user_work_history,user_online_presence,user_website,user_groups,user_events,user_photos,user_videos,user_photo_video_tags,user_notes,user_about_me,user_status,friends_birthday,friends_religion_politics,friends_relationships,friends_relationship_details,friends_hometown,friends_location,friends_likes,friends_activities,friends_interests,friends_education_history,friends_work_history,friends_online_presence,friends_website,friends_groups,friends_events,friends_photos,friends_videos,friends_photo_video_tags,friends_notes,friends_about_me,friends_status&fb_sig_country=bg&fb_sig_api_key=9f7ea9498aabcd12728f8e13369a0528&fb_sig_app_id=177509235268&fb_sig=1a5c6100fa19c1c9b983e2d6ccfc05ef
</details>

Output URL: https://tinyurl.com/6qvyjt4

***
## How to use? Simply..
1. git clone this repo
2. In terminal, run the bash script as: **/path/to/dir/shorten**

***
### To run it like a bash command:
**_Temporarily:_**
```bash
export PATH="$PATH:/path/to/dir" 
(e.g. export PATH="$PATH:~/clonedRepo")
```


**_Permanently:_**
```
1. sudo vim ~/.bashrc
2. Add this line to the file: alias shorten="/path/to/script"   (e.g. alias shorten="~/clonedRepo/shorten")
```
* Then, in terminal, you can run the script as: **shorten**

***
**Misc:**
_Future plans:_
1. Add update option in script

**_Tested and made on Ubuntu._**
