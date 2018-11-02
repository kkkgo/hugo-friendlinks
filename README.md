## usage
 - 1. Copy "layouts" to your hugo website path or theme path.   
 - 2. Creat a xxx.md, set page layout to "links", If you want to add to index, set menu to main.  
```markdown
---
title: "Myfriends"
date: 2018-11-02
layout: "links"
menu: "main"
weight: 50
---
```
 - 3. Now you can add friend's links in the xxx.md by shortcode. The format looks like:  
```markdown
---
title: "Myfriends"
date: 2018-11-02
layout: "links"
menu: "main"
weight: 50
---
{{< friend name="Tony" url="http://tony.blog" logo="/tony.jpg" word="A funny guy" >}}  
{{< friend name="Mike" url="http://Mike.blog" logo="/Mike.jpg" word="A poor guy" >}}  
```

- 4. Preview:   
![Preview](https://i.loli.net/2018/11/02/5bdbb398c097c.png)
 - 5. You need to find a template based on your theme, such as "single.html", copy the code to modify links.html, insert the original code.
