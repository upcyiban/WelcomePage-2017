# WelcomePage-2017

## 安装环境
 
 
> 必须的环境（以我为例）
```bash
ruby（gulp用ruby写的）

Python（报错提示安装）

vs2005（报错提示安装）

版本8以下node.js(目前高版本不支持Sass)

Sass如果单独安装参考中文网站，换淘宝后使用vpn会报错
```
## 本地运行这个项目

> 首先安装 yo bower gulp
> (如果你很慢的话可以考虑使用换淘宝源或者使用 cnpm)

```bash
npm i -g yo bower gulp

# 或者使用yarn
yarn global add yo bower gulp
```

> 安装所需依赖

```bash
npm i
bower i
```

> 启动 gulp 服务预览

```bash
gulp serve
```

> 打包

```bash
gulp build
```
