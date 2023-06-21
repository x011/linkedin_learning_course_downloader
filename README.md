Simple yet effective script to download Linkedin full courses with videos and exercise files.
You'll need to change the following variables inside the script:

----
```
############################# TO CHANGE START #############################
res = "720" # video resolution  
base_path = "/mnt/f/Courses" # path to download courses  
course_url = 'https://www.linkedin.com/learning/web-servers-and-apis-using-c-plus-plus/why-use-c-plus-plus-to-make-a-website' # any link from the course, even a chapter, will do 
skip = False # Skip if video exists  

# https://cookie-script.com/documentation/how-to-check-cookies-on-chrome-and-firefox
jsession = 'ajax:6778916039974719485' # get value on 'jsession' cookie  
li_at = 'AQEDAURmNjAE5Y0nAAABiNrKtugAAAGI_tc66E0ADgeMKZ55Ok3qpLsNUnCh-G8rkg60xjfDnzjTUCpyyrP7JGgxfA9BNKc00T-3UKMh2fzRJLR37FfFBupIPuVhKxyefuXDoC8dlCAp59QTSJl8ikSh' # get value on 'li_at' cookie

# IMPORTANT >>> Bear in mind that you need a premium susbcription to download all videos.
############################# TO CHANGE END #############################
```

