# electron-jspaint

在macOS下对Windows附件里的画图本念念不忘，于是找到了JS Paint。
但感觉每次使用都在浏览器里不太习惯，所以就将其用electron打包，合成electron-jspaint。

<img width="1048" alt="image" src="https://user-images.githubusercontent.com/21050753/172583275-bee3af4f-cffb-4a02-891a-dd90f219baef.png">

# 下载
可以从右侧Packages进行下载。

# 打包方法
请先安装npm。

然后，安装electron与electron-forge

```
$ npm i -D electron@latest
$ npm install -g @electron-forge/cli
```


接着，下载并切换到本工程，开始打包

```
$ cd electron-jspaint
$ npm install
$ npm start
$ npm run make
```
