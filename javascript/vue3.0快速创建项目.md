### 本地安装vue-cli
参考：

- https://blog.csdn.net/xuqipeter/article/details/80452271

#### 前置条件

- 更新npm到最新版本 
```js
命令行运行: 
npm install -g npm 
npm就自动为我们更新到最新版本
npm install -g cnpm
npm install -g yarn
```
- 淘宝npm镜像使用方法 
```js
npm config set registry https://registry.npm.taobao.org 
cnpm config set registry https://registry.npm.taobao.org 
yarn config set registry https://registry.npm.taobao.org 
```
- 配置后可通过下面方式来验证是否成功 ： 
```js
npm config get registry
```
- 使用 npm 全局安装 vue-cli ：(这里采用官网命令）
- https://cli.vuejs.org/
```js
npm install -g @vue/cli
# OR
yarn global add @vue/cli

vue create my-project
```
