

#### 个性域名 http://wapchief.com

搭建教程请参考http://www.jianshu.com/p/a39573555039

联系方式：[![alt text](http://rescdn.qqmail.com/zh_CN/htmledition/images/function/qm_open/ico_mailme_02.png)](http://mail.qq.com/cgi-bin/qm_share?t=qm_mailme&email=zLutvK_kpamqjL294q_joQ)

master分支用于部署后生产的静态页面。

hexo分支用于存放源文件，更新文章等需要用hexo分支。

如果只有一个master分支存放页面的话，那么一旦更换电脑，hexo所部署需要的文件就无法重现

警告：远程克隆之后，在部署前需要删除掉.deploy_git文件。
git删除命令操作  
``rm -rf .deploy_git``
或者手动删除
否则会出现冲突
