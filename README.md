1. npm run serve  开发
2. npm run build  准备打包
3. 将dist/index.html   所有css js 链接改成 ./ 相对路径
   上线的代码都在dist 下
4. 使用git -checkout -b new_branch  新建并切换分支
5. gh-pages
  MIT github master   最稳定的版本
  gh-pages 分支上把 dist目录下的代码搞过去
  git push origin gh-pages  源码在master分支， 上线的代码在 dist/