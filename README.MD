#   如何使用
我们的愿景：该blog将作为dealmoon技术团队的分享主要途径，在各个技术社区中分享我们的技术文章，提升技术团队影响力。
###  fork博客项目代码到你的github账户
https://github.com/dealmoontech/blog-code.git
###  clone代码
git clone https://github.com/你的github账户/blog-code.git [本地项目名]
###  安装hexo脚手架
cd [本地项目名]<br />
npm install -g hexo-cli<br />
PS：可能需要加 sudo npm install -g hexo-cli 获得相关权限<br />
###  安装项目依赖
npm install
###  开始一篇新的文章
hexo new '博客title'
###  进入刚新建的文章
source/_posts<br />
PS：找到你新建的文章，文章文件名为‘博客title.md’，支持[markdown语法](https://www.appinn.com/markdown/)
###  启动服务调试（用于本地开发调试）
hexo s --debug
###  书写完毕之后
发起一个PR，待合并后可访问[dealmoontech](https://dealmoontech.github.io)进行预览。


