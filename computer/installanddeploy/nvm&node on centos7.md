

1. 下载命令

`wget -qO- https://raw.githubusercontent.com/creationix/nvm/v0.33.8/install.sh | bash
`

2. 下载完成后加入系统环境
 
`source   ~/.bashrc`
 
3. 查看 NVM 版本list

`nvm list-romote`
 
4. 修改nvm下载为国内的淘宝源
在/root/.bashrc中增加以下内容,并刷新环境变量

`export NVM_NODEJS_ORG_MIRROR=https://npm.taobao.org/mirrors/node`

`source /root/.bashrc`
 
5. 安装需要的node版本

`nvm install  v8.12.0`
 
6. 查看当前机器已安装版本号

`nvm list`
 
7. 切换node版本

`nvm use v8.12.0`