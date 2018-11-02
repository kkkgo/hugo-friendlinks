# a hugo friend links templates.
## usage
 - 1. copy "layouts" to your hugo website path or theme path.   
 - 2. creat a xxx.md, set page layout to "links", If you want to add to menu, set menu to main.  
```markdown
---
title: "Myfriends"
date: 2018-11-02
layout: "links"
menu: "main"
weight: 50
---
```
 - 3. now you can add friend's links there by shortcode, The format looks like:  
>{{< friend name="Tony" url="http://tony.blog" logo="/tony.jpg" word="a good guy" >}}  
>{{< friend name="Chrome" url="https://www.google.cn/chrome" logo="https://www.google.cn/chrome/static/images/chrome-logo.svg" word="The faster browser" >}}  

- 4. Preview: https://03k.org/dalao  
									
