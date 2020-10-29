## 笔记
## 使用VuePress搭建github在线blog
- 创建一个远程仓库 xxx_ts_study
- 修改docs/.vuepress/config.js: base: '/xxx_ts_study/'
- 打包文档: npm run doc:build
- 将项目推送到github
  - git init
  - git add .
  - git commit -m "init"
  - git remote add origin 仓库地址       //关联仓库
  - git push origin master
- 发布文档: npm run doc:deploy
- 
- 访问在线文档: https://zxfjd3g.github.io/xxx_ts_study/ (可能要等待一定的时间)



在远端仓库的Settings 中找到Github Pages 这里有网址

![image-20201029105912406](C:\Users\20722\Desktop\2020-10-29_TS\TS\ts-study\README.assets\image-20201029105912406.png)