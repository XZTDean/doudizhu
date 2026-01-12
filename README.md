# Javascript版在线斗地主
Javascript版斗地主游戏，后台基于nodejs， 支持多桌、多人同时在线游戏、支持快速加入游戏、支持房间内聊天
### 安装
本游戏后台基于node.js，请先确保已安装node.js，否则游戏无法运行
首先clone本项目到本地
```sh
git clone git@github.com:laivv/doudizhu.git
```
进入项目根目录并安装依赖
```sh
cd ./doudizhu
npm install
```
运行下面的命令启动游戏
```sh
npm start
```
游戏启动后，会自动打开游戏链接

### Docker
构建镜像
```sh
docker build -t doudizhu .
```
运行容器
```sh
docker run --rm --name doudizhu -e BASE_PATH=/ddz doudizhu
```
访问地址示例：`http://localhost:8001/ddz/`

![image](https://raw.githubusercontent.com/laivv/doudizhu/master/static/images/game2.jpg)
![image](https://raw.githubusercontent.com/laivv/doudizhu/master/static/images/game.jpg)
### License
MIT
### lincense说明
本游戏的图片资源来源于网络素材，不在lincense许可范围内
