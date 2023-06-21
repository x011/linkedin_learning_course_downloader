
### Linkedin Learning Course Downloader

2023 Python 3.5+ script to download Linkedin Learning full courses with videos and exercise files.    
You'll need to change the following variables on `downloader.py`:
```
############################# TO CHANGE START #############################

res = "720" # video resolution  
base_path = "/courses" # path to download courses - Windows example: c:/courses or c:\\courses
course_url = 'https://www.linkedin.com/learning/web-servers-and-apis-using-c-plus-plus' # any link from the course, even a chapter, will do 
skip = False # Skip if video exists  

# https://cookie-script.com/documentation/how-to-check-cookies-on-chrome-and-firefox
jsession = 'ajax:6778916039974719485' # get value on 'jsession' cookie  
li_at = 'AQEDAURmNjAE5Y0nAAABiNrKtugAAAGI_tc66E0ADgeMKZ55Ok3qpLsNUnCh-G8rkg60xjfDnzjTUCpyyrP7JGgxfA9BNKc00T-3UKMh2fzRJLR37FfFBupIPuVhKxyefuXDoC8dlCAp59QTSJl8ikSh' # get value on 'li_at' cookie

############################# TO CHANGE END #############################
```
----
### Requirements: 
 - Python 3.5+
 - beautifulsoup4 - Install with `pip install beautifulsoup4` or `pip3 install beautifulsoup4`
 - You'll need a Linkedin premium subscription to download all videos

### FAQ:
 - Problems, errors, questions? [Open an issue](https://github.com/x011/linkedin_learning_course_downloader/issues)
 - Improvments? Issue a [Pull Request](https://github.com/x011/linkedin_learning_course_downloader/pulls)
 - For educational purposes only, use at you own risk

