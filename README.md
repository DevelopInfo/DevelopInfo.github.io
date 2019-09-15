该项目是本人的个人博客项目，主要是基于 Hexo 博客生成工具进行生成。

基本的操作流程是利用 Hexo 工具生成博客网站的静态文件，然后将静态文件同步到 Github 上，下面主要介绍一下 Hexo 工具生成静态文件的过程：

1. 安装git和nodo.js；
2. 安装Hexo，` npm install -g hexo-cli `；
3. 修改配置文件`_config.yml`。修改配置项`public_dir`，将其修改为需要发布到的文件夹，例如`../DevelopInfo.github.io`；
4. 在文件夹`source/_posts`中添加博客文档；
5. 利用Hexo生成静态文件，`hexo generate`，静态文件生成到配置的`public_dir`中；
6. 开启hexo服务器，`hexo server`，通过访问网址`http://localhost:4000/`进行本地浏览；

