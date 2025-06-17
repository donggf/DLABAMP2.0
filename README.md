# DLABAMP2.0
DLABAMP2.0 is an upgraded platform for lactic acid bacteria antimicrobial peptides. Building on DLABAMP1.0, it expands to 1955 high - quality entries with 20 - field annotations. It offers functions like flexible retrieval, multi - model prediction (family classification &amp; antibacterial activity), data visualization, and batch processing. 


DLABAMP2.0/
├── .idea/          # 集成开发环境（如 PyCharm）的配置文件夹，存储项目的代码风格、插件设置等IDE相关信息
├── backup/         # 备份文件夹，用于存放项目数据、配置等的备份文件，保障数据安全与恢复需求
├── model/          # 模型文件夹，存储深度学习模型（如 KAN、BERT、ESM 相关模型）的代码、权重文件等，是实现抗菌肽预测功能的核心模块 
├── static/         # 静态资源文件夹，存放 CSS 样式文件、JavaScript 脚本、图片等前端静态资源，用于页面展示与交互 
├── templates/      # 模板文件夹，包含 HTML 页面模板，结合 Flask 渲染机制，动态生成展示给用户的网页内容 
├── 1.sql           # SQL 源文件，存储数据库表结构定义、初始化数据等，用于搭建和初始化项目所需的 MySQL 数据库 
└── app.py          # 项目主应用文件，基于 Flask 框架编写，实现路由定义、业务逻辑处理、与数据库和模型交互等核心功能，是项目启动和运行的入口 
