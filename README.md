# SarynBlog

本项目采用 Vue2、FLask、element-UI 搭建

# 1.1 如何使用

环境 python3.10，npm6.14，nodejs8.11.2，vue2.9.6

## 1.2 Backend

打开终端:

```bash
$ cd back-end
$ python -m venv venv
$ venv/Scripts/activate.act
(venv)$ pip install -r requirements.txt

# 创建更新数据库
(venv)$ flask db upgrade

# 创建.env文件并输入
FLASK_APP=madblog.py
FLASK_DEBUG=1

(venv)$ flask run
```

浏览器访问: `http://localhost:5000/api/ping`

## 2.2 Frontend

打开终端:

```bash
$ cd front-end
$ npm install
$ npm run dev
```

浏览器访问: `http://localhost:8080`
