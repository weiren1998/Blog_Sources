# Blog_Sources
图片无法加载解决方案：
1. 修改host：https://www.geek-share.com/detail/2829062120.html
2. 改用gitee：https://www.its203.com/article/weixin_44052936/113748403

试了`1`这种方式，本地可以访问，但是换台电脑就不行了，因此另找了他法，[这篇文章](https://mianao.info/2020/05/03/%E5%A6%82%E4%BD%95%E8%A7%A3%E5%86%B3GitHub%E4%BD%9C%E5%9B%BE%E5%BA%8A%E5%9B%BD%E5%86%85%E6%97%A0%E6%B3%95%E6%98%BE%E7%A4%BA%E7%9A%84%E9%97%AE%E9%A2%98)借助了jsDelivr的CDN，非常简单的就把github图床里的图片搞定了！！
~~~c
https://cdn.jsdelivr.net/gh/weiren1998/Blog_Sources@main/imgs/比赛.jpg
# 修改开头部分，以及main前加上@
~~~
