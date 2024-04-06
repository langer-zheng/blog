1 搭建简单 只需要三步 不依赖任何本地环境 不需要用到一行命令 只要能网页访问 github 就行

2 发文章方便 可以用直接 github 网页端提交 md 文章，不需要保存工程文件，随意切换设备

下面是搭建和发文章教程

前置条件：有 github 账号，能用浏览器访问 github

核心步骤 1：找到喜欢的 Jekyll 模板工程，fork 到自己仓库，修改项目名为 yourname.github.io
以比较火热的 next 主题为例：
项目地址 https://github.com/Simpleyyt/jekyll-theme-next
demo 预览地址 https://simpleyyt.com/jekyll-theme-next/
在项目页面右上角 Fork ，然后到自己仓库里就可以把这个 Fork 来的项目改名为 yourname.github.io(yourname 是你 github 的名字)

-- 到这一步你的博客已经有了 只是名字和文章都还是别人的 可以通过 yourname.github.io 直接访问，不过可能要等几分钟


核心步骤 2：在 Fork 来的项目里直接点击_config.yml 文件在线编辑

这个文件是博客的配置文件，可以修改名字，头像什么的 具体参数要看每个模板的教程
-- 到这一步你的博客打开已经是显示你的名字了

核心步骤 3：在 Fork 来的项目里，点进去_posts 文件夹

里面会看到一些别人的 md 文件，每个文件就是一篇文章，在线删掉这些文件（最好留一个，不然整个文件夹都没了）
然后上传自己的 md 文件，要注意 Jekyll 的 md 文件格式要以 yyyy-mm-dd-开头，比如 2021-12-24-第一篇文章.md

到这就完全搞定了，顺利的话 yourname.github.io 已经是你的博客了

发文章也很简单，就是在_posts 目录下上传符合命名格式的 md 文件。

写文章的方式就丰俭由人了，你可以本地 md 编辑器写之后上传，也可以 prose 这个网站在线写，也可以用 github 的在线工程写，甚至可以直接再网页端项目里新增文件写

觉得这个方法好的话推荐给别人吧！再也不要因为配环境和设备妨碍“写博客”这件事本身了
