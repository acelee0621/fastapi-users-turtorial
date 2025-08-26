
# FastAPI-Users 中文实战教程示例代码

这是配合微信公众号《FastAPI-Users 中文实战教程》系列文章的示例代码仓库。  
本系列旨在系统介绍 **FastAPI-Users**，从官方文档解读到项目实战，帮助你快速掌握用户认证与管理。  

---

## 📖 教程进度

- **第一期**：[核心概念与快速上手]  
  - FastAPI-Users 是什么？它解决了哪些问题？  
  - 核心概念总览：UserManager、适配器、策略、Schemas、路由  
  - 5 分钟上手：用默认配置快速搭建一个注册 + 登录的应用  

（后续内容将持续更新，包括 SQLAlchemy/Beanie 集成、自定义用户模型与 RBAC 等）  

---

## 🚀 快速运行

1. 克隆本仓库  
   ```bash
   git clone https://github.com/yourname/fastapi-users-tutorial.git
   cd fastapi-users-tutorial
````

2. 安装依赖（推荐使用 [uv](https://github.com/astral-sh/uv) 或 pip）

   ```bash
   uv sync   
   ```

3. 启动应用

   ```bash
   uvicorn app.main:app --reload
   ```

4. 打开浏览器访问 [http://127.0.0.1:8000/docs](http://127.0.0.1:8000/docs)

---

## 🗂 目录结构（第一期示例）

```bash
fastapi-users-tutorial/
├── app/
│   ├── __init__.py
│   ├── main.py
│   ├── db.py
│   ├── schemas.py
│   └── users.py
└── # 其他uv生成的文件
```

---

## 📌 说明

* 本仓库代码对应微信公众号文章内容，请结合教程阅读。
* 当前完成 **FastAPI-Users保姆级教程（一）：核心概念与快速入门** 示例。
* 后续章节的代码将会逐步更新到本仓库。

---

## 📬 联系

* 微信公众号：**码间絮语**
<center>
  <img src="https://mmbiz.qpic.cn/sz_mmbiz_png/icqSakibXlSs3kU9fZV4MUT1DSic0LqMFcZoIkr6bMlvKwk5Zr5mYNQMthDx7BF8tibOZIULdykkhuRibFwxhozrOwA/640?wx_fmt=png&amp;from=appmsg" alt="签名图">
</center>

* 欢迎 Star ⭐ & 关注，获取最新教程和代码更新。