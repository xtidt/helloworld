# helloworld
一个最简单的vue + electron 模板
## 搭建过程
1. [`最简框架搭建.md`](./docs/1.最简框架搭建.md) 记录了最开始搭建这个模板的过程
2. [`添加常用插件.md`](./docs/2.添加常用插件.md) 记录了添加插件的一些过程
3. [`恢复vue目录.md`](./docs/3.恢复vue目录.md) 恢复vue-cli的目录结构
4. [`启用热重载(hot reload)调试.md`](./docs/4.启用热重载\调试') 使用`webpack-dev-server`实现
## 项目安装
```
npm install
```

### 编译和启动 development 模式
```
npm run dev 
```
### 编译和启动 production 模式
```
npm run serve
```
### 打包压缩文件
```
npm run pack
```
### 编译和构建生产版本
```
npm run build
```

## 在此基础上如何扩展?
目前的配置肯定还不能满足生产的需求，还需要扩展不少东西。  
使用vue-cli等就很方便对此进程扩展, 如安装各种vue插件等，还有使用原生模块，如'ffi'等, 但目前的配置是不能完成的，还需要以后多多完善。

## helloworld之后
在此之后我还是想要完善或者说将这个项目能做成一个真正的模板，但主要以学习为主，需要寻求很多帮助，希望有兴趣的朋友能一起来玩玩。
