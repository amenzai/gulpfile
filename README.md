# 一个简单的gulp项目
集合了一些常用插件，加速前端开发。

##功能
1. 编译`src>styles`目录下的less文件，对一些CSS3代码加前缀，压缩，放入`dist>css`目录。
2. 合并`src>scripts`目录下的每个js文件，并压缩，放入`dist>js`目录。
3. 压缩`src`目录下的html文件，放入`dist`目录。
4. 复制`src>images`下的图片文件，放入`dist>img`目录。
5. 使用`browser-sync`插件，监控`src`目录下的文件变化。

## 使用方法
```
git clone https://github.com/amenzai/gulpfile.git
cd gulpfile
npm install
gulp serve
```
运行gulp serve命令后

1. 在本目录生成一个dist文件夹（里面就是生成的网站）
2. 监听src目录下所有文件的变更
3. 在2016端口启动服务器，浏览器自动打开生成的网站