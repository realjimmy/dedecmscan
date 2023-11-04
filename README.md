![A959A7B612035ABFFB13EF2EC4BE03A8](https://github.com/realjimmy/dedecmscan/assets/35913414/bf13767a-1e7f-4e64-b0f8-97e9853e6639)# dedecmscan



dedescan是一款可以扫描所有已公开的dedecms漏洞的扫描器。

```
        ...                 ...                                                     
        ...                 ...                                                     
        ...                 ...                                                     
        ...                 ...                                                     
        ...                 ...                                                     
   ........  .......   ........   .......   .......    ......    ......   ........  
  ...  .... .... ....  ... ....  .... ...  .... ...   ... ....  ...  ...  .... .... 
 ....  .... ...   ... ...   ...  ...   ... ...       ...   ...  .    ...  ...   ... 
 ....   ... ......... ...   ... ..........  ....     ...           .....  ...   ... 
 ....   ... ...       ...   ... ....         ......  ...        ........  ...   ... 
 ....  .... ...       ...   ... ....            .... ...   ... ....  ...  ...   ... 
  ...  .... ....  ... ....  ...  ...  .... ...   ... ....  ... ....  ...  ...   ... 
  .........  ........  ........   .......  ........   ........  ........  ...   ... 
    .......   .....     .......    .....     .....      ....     ........ ...   ... 

```

用法： python3 dedescan.py

然后直接输入域名即可

## 已实现的功能

- 后台查找（win）
- 版本探测
- 短路经检测
- 路径检测
- trace检测
- advancedsearch.php SqlInject
- sql_class.php SqlInject
- feedback_js.php SqlInject
- getpage xss
- guestbook.php SqlInject
- infosearch.php SqlInject
- jump.php xss
- login.php xss
- recommend.php SQL 
- redirect
- reg_new.php SqlInject
- search.php sqlinject
- V5order by SqlInject
- article_keyword_select.php xss
- catelog_tree.php xss
- content_list.php xss
- file_pic_vie.php xss
- pic_view.php xss
- select_images.php xss
- writebook getshell
- digg_frame.php  rce
- list.php xss
- login.php xss
- config.php xss
- flash xss

## 部分截图

![](http://ww1.sinaimg.cn/large/007F8GgBly1g61fkee3tnj30pf0cdjta.jpg)

## 其他说明
本程序依赖：

- requests
- re
- termcolor
- threading
- itertools

forked from zjacai/dedecmscan，原版的库貌似没有了，做个备份


