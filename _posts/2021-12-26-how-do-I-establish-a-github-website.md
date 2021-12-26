---

layout: post 

title: How do I establish a GitHub Website

categories: [2021年]

tags: []

---



**Reference:**

https://sinantang.github.io/ -《用 Jekyll 在 GitHub 上搭建你的个人网站》

https://jekyllcn.com/docs/posts/ -jekyll官方网站

​    之所以把reference放到这么前面，是因为我觉得sinan写得很好，我几乎是按照她的方式走下来的。

在sinan的基础上，我写这篇博客的原因，是想加几个步骤以免自己忘记。



**我在建立网站的过程中遇到的问题：**

1. jekyll local发布时网站显示良好，上传到github后github的page是一片空白。

   **原因：**github在2020年把default folder从master换成了main。

   **解决方式：**在github页面需要将 source folder设置为master branch，这样上传的时候可以上传master，github能够显示。

   例如：以 我为例，我前往自己的peiyaosun.github.io的responsiry，点击右边的Settings, 选择Pages, 在Source下将main改成选择master，直到出现“Your GitHub Pages site is currently being built from the `master` branch.”, 点击save，完成。

2. 图片在jekyll local网站显示良好，在github page时有些图片无法加载成功。

   **原因：**github page对于大小写敏感。例如：IMG7070.jpg 与 IMG7070.JPG是不一样的。

   **解决方式：**我将所有图片转化成jpg格式，并确保后缀为小写jpg. 在markdown文件同步引用时也采用jpg小写格式引用。

   值得注意的是，如果仅仅在本地修改图片的大小写，再次上传到github时，git会显示没有可更新的。我的解决方法是粗暴地删除文件，上传，再加入文件，上传。最后work out！

   

   

   从最初知道sinan的博文，试图建立网站到最终今天成功发出第一篇博文，一年已经过去。希望大家都能如愿建立自己的个人网站！

   

   

   

   

   

   

   