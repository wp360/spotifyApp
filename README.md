## 原注释
The boilerplate comes with webpack, and react installed along with enzyme as a testing suite and chai for asserions

NPM install to download all the modules

The environment also uses babel-eslint as a linter core for es-lint, the configuration for which can be changed in .eslintrc

## 个人总结
## 步骤
### 1. git克隆代码到spotifyApp文件夹
>`git clone https://github.com/veebuv/React-Exercise-Udemy-Starter.git spotifyApp`
### 2.打开编辑器 (使用Atom的话，atom .)
>`cd react-basic  / react-basic文件夹下 code .`
### 3.npm安装依赖
`npm install`
### 4.启动项目
`npm start`

## git上传
```javascript
echo "# spotifyApp" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/wp360/spotifyApp.git
git push -u origin master
报错，使用
git push --set-upstream origin master
不行的话，删除.git文件
重新上传一遍
```