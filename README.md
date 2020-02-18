# quickapp-log
快应用的成长记录

## 开始
- 安装 NodeJS [官网下载安装](https://nodejs.org/)

- 安装 toolkit ```npm install -g hap-toolkit```

- 创建项目模板 ```hap init <ProjectName>```

- 安装依赖模块 ```npm install```

- 手动编译 ```npm run build``` 自动编译 ```npm run watch```

- 手机安装调试器 [下载地址](https://www.quickapp.cn/docCenter/post/69)

- 启动服务器 ```npm run server```


##相关问题

有部分同学如果`node`版本用的是8以上的话，在运行完`npm install`后再运行`npm run build`时可能会报`Cannot find module .../webpack.config.js`异常，这时大家不要惊慌，请重新执行一次`hap update --force`。这是由于高版本的`npm`在`npm install`时，会校验并删除了`node_modules`下部分文件夹，导致报错。而`hap update --force`会重新复制`hap-toolkit`文件夹到`node_modules`中
