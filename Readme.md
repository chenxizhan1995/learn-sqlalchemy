# 学习SQLAlchemy，随书代码
当前 sqlalchemy 的版本是 `1.3`。

## 环境(Windows)
1. 创建虚拟环境
这是为了保持项目环境干净，所以为此项目单独构建虚拟环境。
这不是必须的。创建虚拟环境的方法有很多，这里使用Python自带的venv模块。
```sh
G:\learn\learn-sqlalchemy>py -m venv G:\venvs\learn-sqlalchemy --clear --prompt=py --symlinks   
```
2. 激活虚拟环境

```sh
G:\venvs\learn-sqlalchemy\Scripts\activate
REM 可以看到，当前已经处于虚拟环境了
(py) G:\learn\learn-sqlalchemy>py -0
Installed Pythons found by py Launcher for Windows
 (venv) *
 -3.9-64
 -3.8-64
 -3.7-64
```

3. 安装依赖
激活虚拟环境后执行如下命令：
```sh
py -m pip install -r requirements.txt
```
