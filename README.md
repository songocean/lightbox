title: lightbox 

domain: http://nixwang.com  

======
```
特别感谢
[衣不如新](!http://motype.org/‎)
```

---
# site.md配置说明   
    
 weibo: 使用新浪个人工具生成的iframe标签中，截取类似代码即可。注意不能漏了verifier字段。 
 rpost： 有此项配置时侧栏显示最近文章，最大值20。
 duoshuo: 侧栏最新评论使用的多说，字段值为多说的short_name。 
 keywords: meta 的keywords属性。
 analytics ：一段script脚本，可以将脚本压缩成一行，填入site.md。
 
# 链接类主题   
当文章头部有link标签时，文章列表内的标题将直接链到该link  
 
    Title:协议森林by-Vamei
    Date: 2013-02-21 21:18:54  
    link: http://www.cnblogs.com/vamei/archive/2012/12/05/2802811.html  
    tags: 互联网协议  

# 在原作基础上的修改

- 文章列表页面图片的缩略图移到了标题下面靠右侧。这样每一篇文章的标题以及相关信息的显示都是一致的，无论是否包含图片。
- 右侧SideBar中的新浪微博版块使用了一个iframe，高度改到500。
- Tag List中的显示过于拥挤，现在改成每个Tag一行，后面是这个Tag下文章的数目。
- NavBar中的Photos指向的地址有错误，导致不能正常显示图片目录。
- 修改了图片浏览的导航。
- 修改了导航条样式、侧边栏样式。
- 修改了文章页面样式。

# Feedback
http://nixwang.com/post/2013-12-01-farbox-theme
https://github.com/nix1024/lightbox