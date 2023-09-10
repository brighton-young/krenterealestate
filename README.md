# krenterealestate

PS C:\Users\brigh\Downloads\64526658ea6f9.site123.me> ls

    Directory: C:\Users\brigh\Downloads\64526658ea6f9.site123.me

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d----            9/8/2023  3:15 PM                _DataURI
d----            9/8/2023  3:15 PM                64526658ea6f9.site123.me
d----            9/8/2023  3:15 PM                analytics.site123.io
d----            9/8/2023  3:15 PM                cdn-cms-s.f-static.net
d----            9/8/2023  3:15 PM                fonts.googleapis.com
d----            9/8/2023  3:15 PM                fonts.gstatic.com
d----            9/8/2023  3:15 PM                sessions.bugsnag.com
d----            9/8/2023  3:15 PM                static1.s123-cdn-static-a.com
-a---           9/10/2023 12:47 AM             19 README.md

PS C:\Users\brigh\Downloads\64526658ea6f9.site123.me> cd 64526658ea6f9.site123.me 
PS C:\Users\brigh\Downloads\64526658ea6f9.site123.me\64526658ea6f9.site123.me> ls

    Directory: C:\Users\brigh\Downloads\64526658ea6f9.site123.me\64526658ea6f9.site123.me

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a---           9/10/2023  4:57 PM         123470 index.html
-a---            9/8/2023  3:15 PM           1751 sw.js

PS C:\Users\brigh\Downloads\64526658ea6f9.site123.me\64526658ea6f9.site123.me> cd ../                        
PS C:\Users\brigh\Downloads\64526658ea6f9.site123.me> git status
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   64526658ea6f9.site123.me/index.html

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\Users\brigh\Downloads\64526658ea6f9.site123.me> git add . 
PS C:\Users\brigh\Downloads\64526658ea6f9.site123.me> git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   64526658ea6f9.site123.me/index.html

PS C:\Users\brigh\Downloads\64526658ea6f9.site123.me> git commit -m "<div id="showSmallAdOnScroll" class="upgrade-website-preview-helper style2 static"><a rel="nofollow" target="_blank" href="https://www.site123.com/?utm_source=user-website&utm_medium=powered-by-ad-en&utm_content=all&utm_campaign=all"><span class="s123-b-b-s-1">I BUILT MY SITE FOR FREE USING</span> <img src="https://cdn-cms-s.f-static.net/manager/websites/site123_website/files/logos/brand_files_2020/Logo/Horizontal/PNG/Horizontal_Black.png?v=y83131" style="height:21px;width:auto;vertical-align:middle;">&nbsp;&nbsp;&nbsp;<span class="site123link hidden-xs">CREATE YOUR WEBSITE</span></a></div> DELETED IN INDEX.HTML AT LINES 683 - 688" 
ParserError: 
Line |
   1 |  … cal-align:middle;">&nbsp;&nbsp;&nbsp;<span class="site123link hidden- …
     |                                                      ~~~~~~~~~~~
     | Unexpected token 'site123link' in expression or statement.
PS C:\Users\brigh\Downloads\64526658ea6f9.site123.me> git commit -m "<div id="showSmallAdOnScroll" class="upgrade-website-preview-helper style2 static"><a rel="nofollow" target="_blank" href="https://www.site123.com/?utm_source=user-website&utm_medium=powered-by-ad-en&utm_content=all&utm_campaign=all"><span class="s123-b-b-s-1">I BUILT MY SITE FOR FREE USING</span> <img src="https://cdn-cms-s.f-static.net/manager/websites/site123_website/files/logos/brand_files_2020/Logo/Horizontal/PNG/Horizontal_Black.png?v=y83131" style="height:21px;width:auto;vertical-align:middle;">&nbsp;&nbsp;&nbsp;<span class="(site123link) hidden-xs">CREATE YOUR WEBSITE</span></a></div> DELETED IN INDEX.HTML AT LINES 683 - 688, ALSO ADDED ( ) AROUND site123link, NEED TO REMOVE TO RESTORE"^C

PS C:\Users\brigh\Downloads\64526658ea6f9.site123.me> git commit -m "<div id="showSmallAdOnScroll" class="upgrade-website-preview-helper style2 static"><a rel="nofollow" target="_blank" href="https://www.site123.com/?utm_source=user-website&utm_medium=powered-by-ad-en&utm_content=all&utm_campaign=all"><span class="s123-b-b-s-1">I BUILT MY SITE FOR FREE USING</span> <img src="https://cdn-cms-s.f-static.net/manager/websites/site123_website/files/logos/brand_files_2020/Logo/Horizontal/PNG/Horizontal_Black.png?v=y83131" style="height:21px;width:auto;vertical-align:middle;">&nbsp;&nbsp;&nbsp;<span class="(site123link) hidden-xs">CREATE YOUR WEBSITE</span></a></div> DELETED IN INDEX.HTML AT LINES 683 - 688, ALSO ADDED ( ) AROUND site123link, NEED TO REMOVE TO RESTORE" 
ParserError: 
Line |
   1 |  … cal-align:middle;">&nbsp;&nbsp;&nbsp;<span class="(site123l …
     |                                                      ~
     | Unexpected token '(' in expression or statement.

ANYWAY... I DELETED THIS
