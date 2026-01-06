<p align="center">
  <img src="static/favicon.svg" width="60" height="60" alt="Snake Game Logo">
</p>
<p align="center">
  <strong style="font-size: 20px;">一个由 AI 完全生成的贪吃蛇游戏</strong><br>
  这个项目展示了 AI 在现代软件开发中的能力，同时也作为一个有趣的技术探索案例。
</p>

<div align="center">

[![Go Version](https://img.shields.io/badge/Go-1.22-00ADD8?style=flat-square&logo=go)](https://go.dev)
[![AI Generated](https://img.shields.io/badge/AI-Generated-green?style=flat-square&logo=openai)](https://github.com/haozishuizhaole/snake)
[![License](https://img.shields.io/badge/License-Mulan_PSL_v2-yellow.svg?style=flat-square)](LICENSE)

</div>

## 截图

![欢迎页](screenshots/welcome.png)

![游戏页](screenshots/game.png)

## 功能特点

- 经典贪吃蛇玩法
- 实时分数统计
- 历史最高分记录
- 响应式设计，支持键盘控制
- 碰撞检测
- 游戏暂停/继续功能
- 实时更新的全球排行榜
- 游戏回放功能
- AI 自动演示
- 完整的防作弊机制

## 技术栈

- 后端：Go
- 前端：HTML5 Canvas + JavaScript
- 样式：CSS3
- 数据存储：SQLite3

## 项目结构

    snake-game/
    ├── main.go              # Go 后端服务入口
    ├── README.md           # 项目说明文档
    ├── static/             # 静态资源目录
    │   ├── css/
    │   │   └── style.css   # 游戏样式表
    │   └── js/
    │       └── snake.js    # 游戏核心逻辑
    ├── templates/          # 模板目录
    │   └── game.html      # 游戏页面模板
    └── versions/          # 版本记录目录
        └── v1.0.0.md      # 版本更新记录

每个文件的主要功能：

- `main.go`: 提供 Web 服务器功能，处理路由和请求
- `static/css/style.css`: 定义游戏界面样式
- `static/js/snake.js`: 实现贪吃蛇游戏的核心逻辑
- `templates/game.html`: 游戏的 HTML 模板
- `versions/v1.0.0.md`: 版本更新记录
- `README.md`: 项目说明文档

## 安装和运行

### 前置要求

- Go 1.22 或更高版本
- 现代浏览器（支持 HTML5 Canvas）
- SQLite3

### 安装步骤

1. 克隆项目

    ```bash
    git clone git@github.com:tootscharlie/snake.git
    cd snake
    ```

2. 构建项目

    ```bash
    ./build.sh
    ```

### 运行方式

1. 启动服务器

    ```bash
    cd build
    ./snake # 默认8080端口
    # 或 ./build/snake -port 3000 自定义端口 
    ```

2. 访问游戏

   在浏览器中打开 `http://localhost:8080`（或自定义端口）

### 游戏控制

- 方向键控制蛇的移动
  - ↑: 向上移动
  - ↓: 向下移动
  - ←: 向左移动
  - →: 向右移动
- 空格键: 暂停/继续游戏
- ESC键: 重新开始游戏

## 更新记录

查看 [CHANGELOG](versions/v1.0.0.md) 了解详细更新内容。

## 贡献

本项目代码完全由 AI 生成，暂不接受人工代码贡献。如有问题或建议，欢迎提交 Issue。

## 许可证

[Mulan PSL v2 License](LICENSE)

---

<div align="center">

🤖 **本项目代码由 AI 自动生成，人工代码 0 添加**

</div>

