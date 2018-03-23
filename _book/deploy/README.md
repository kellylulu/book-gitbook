# 发布

## 源码发布

1、Github上新建仓库
   
2、gitbook build编译，确保_book目录生成
   
3、git init  添加git管理
   
4、git add * 所有文件添加到版本库
   
5、git commit -m "first commit" 提交版本库
   
6、git remote add origin （刚新建仓库的地址） 添加远程仓库地址

7、git push -u origin master  推送到远程仓库master分支
   
8、源码发布完成

## 静态页发布(即将_book目录下文件发布到gh-pages分支)

1、git subtree push --prefix=_book origin gh-pages