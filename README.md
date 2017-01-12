# Blog
***
Blog 必要源文件备份
***
# 日常使用时遵循如下步骤：
1. 从GitHub上更新必要源文件
```
git pull
```
2. 在本地或写文章，或修改配置，或换主题
*注：需要注意的是换主题时一定要删除其中的以`.git`开头的文件*
3. 将必要源文件更新到GitHub上
```
git add .
git commit -m "xxx"
git push
```
4. 部署到GitHub Pages上
```
hexo g
hexo d
```

5. 打完收工

***
# 增加可编写博客的终端时遵循如下步骤：
1. 新终端/电脑安装Git、node环境

2. 新终端/电脑clone远程远程Blog（Github）仓库
```
//克隆必要文件
git clone add origin git@github.com:你的github用户名/Blog.git
```

3. 在新终端/电脑Blog目录中配置Hexo
```
//安装hexo
npm install hexo
//安装依赖
npm install
```

4. 测试
```
//启动服务器，进入http://localhost:4000/查看，已正常显示
hexo s
//生成静态文件
hexo g
//部署到GitHubPages
hexo d
//打开https://你的github用户名.github.io/查看，已正常显示
```

5. 打完收工

*注：详参见[Hexo博客的多终端使用方法](https://swibinchter.github.io/posts/technology/2017-01-11-Hexo%E5%8D%9A%E5%AE%A2%E7%9A%84%E5%A4%9A%E7%BB%88%E7%AB%AF%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95.html)
