#   如何使用
##  直接登录DealMoon前端github账号进行操作
用户名，密码由全体共同维护
###  clone代码
git clone https://github.com/DealmoonFrontend/blog-code.git [本地项目名]
###  安装hexo脚手架
cd [本地项目名] <br />
npm install -g hexo-cli <br />
PS：可能需要加 sudo npm install -g hexo-cli 获得相关权限
###  安装项目依赖
npm install
###  开始一篇新的文章
hexo new '博客title'
###  启动服务调试
hexo s --debug
###  进入刚新建的文章
source/_posts <br />
PS：找到你新建的文章，文章文件名为‘博客title.md’，支持[markdown语法](https://www.appinn.com/markdown/)
###  书写完毕之后
hexo clean // 清空 public 目录 <br />
hexo g && hexo d // 生成静态文件和部署 <br />
PS：部署的过程需要你输入用户名和密码。
### 将blog-code代码提交到远程（方便多人开发）
cd blog-code <br />
git add -A <br />
git commit -m 'new blog title' <br />
git push ... <br />

##  ~~PR方式（暂不使用该方式）~~
###  ~~fork博客项目代码到你的github账户~~
https://github.com/DealmoonFrontend/blog-code.git
###  ~~clone代码~~
git clone https://github.com/你的github账户/blog-code.git [本地项目名]
###  ~~安装hexo脚手架~~
cd [本地项目名]
npm install -g hexo-cli
PS：可能需要加 sudo npm install -g hexo-cli 获得相关权限
###  ~~安装项目依赖~~
npm install
###  ~~开始一篇新的文章~~
hexo new '博客title'
###  ~~启动服务调试~~
hexo s --debug
###  ~~进入刚新建的文章~~
source/_posts
PS：找到你新建的文章，文章文件名为‘博客title.md’，支持[markdown语法](https://www.appinn.com/markdown/)
###  ~~书写完毕之后~~
hexo clean // 清空 public 目录
hexo g && hexo d // 生成静态文件和部署
PS：为了简化流程，我们将 public（打包的代码）的代码也提交的远程，每次只需要直接替换public目录即可
你需要将你的代码提交到自己的远程仓库，以PR的方式进行代码合并。


