# hexo-gitpage

这是我的 gitpage 博客的静态网页生成环境备份。
主要使用方法：

hexo n #写文章
hexo g #生成
hexo d #部署 # 可与hexo g合并为 hexo d -g

##安装

Node和Git都安装好后，可执行如下命令安装hexo：

    npm install -g hexo
    
    # 根据情况可能会用到以下两个命令
    
    npm install hexo --save
    npm install hexo-server --save

初始化

然后，执行init命令初始化hexo到你指定的目录：

    hexo init

也可以cd到目标目录，执行hexo init。
好啦，至此，全部安装工作已经完成！
生成静态页面

cd 到你的init目录，执行如下命令，生成静态页面至hexo\public\目录。

    hexo generate
