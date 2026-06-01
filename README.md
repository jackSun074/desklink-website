# DeskLink 官网

DeskLink 是一款免费开源的 Windows 远程桌面连接管理器的官方网站。

## 本地开发

直接在浏览器中打开 `index.html` 文件即可预览网站。

或者使用 Python 启动本地服务器：

```bash
python -m http.server 8000
```

然后访问 http://localhost:8000

## 部署到 Vercel

### 方法一：使用 Vercel CLI

1. 安装 Vercel CLI：
```bash
npm i -g vercel
```

2. 登录 Vercel：
```bash
vercel login
```

3. 部署项目：
```bash
vercel
```

### 方法二：使用 Vercel 网站

1. 访问 [vercel.com](https://vercel.com)
2. 登录或注册账号
3. 点击 "New Project"
4. 导入此项目目录
5. 点击 "Deploy"

## 文件结构

```
desklink-website/
├── index.html      # 主页面
├── styles.css      # 样式文件
├── vercel.json     # Vercel 配置
└── README.md       # 说明文档
```

## 许可证

MIT License
