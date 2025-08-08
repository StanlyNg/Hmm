# 设备检测与登录工具网站

## 📌 项目简介
这是一个基于 HTML + JavaScript + CSS 的纯前端网页工具，可以检测访问者的设备信息（系统、浏览器、分辨率、IP、语言、时间等），并带有用户登录验证、加密密码存储、多平台 UI 适配（Windows、Android、iOS）和深色主题动画效果。

---

## 🚀 使用方法
1. 打开网站首页 `index.html`  
2. 输入用户名和密码进行登录（默认账号：admin / 默认密码：12345678）  
3. 登录后可查看完整设备信息  
4. 支持深色模式动画 UI 和全球语言显示（默认简体中文）

---

## 🌍 可部署平台列表
你可以将本项目部署到以下任意平台：
- **GitHub Pages**（免费）
- **Vercel**（免费）
- **Netlify**（免费）
- **Cloudflare Pages**（免费）
- **Firebase Hosting**（免费基础额度）
- **Surge**（免费 CLI 部署）
- **Render**（免费静态网站托管）
- **AWS S3 + CloudFront**（按用量计费）
- **Google Cloud Storage + CDN**（按用量计费）
- **Azure Static Web Apps**（免费基础额度）
- **本地服务器 / 内网运行**（Apache、Nginx 等）

---

## 📦 部署方法

### 1. GitHub Pages
1. 新建或进入一个 GitHub 仓库  
2. 上传 `index.html` 到仓库根目录  
3. 打开 **Settings → Pages**  
4. 选择 `main` 分支，文件夹 `/root`  
5. 保存后获取访问链接 `https://用户名.github.io/仓库名/`

---

### 2. Vercel
1. 登录 [Vercel](https://vercel.com/)  
2. 点击 **New Project** → 导入 GitHub 仓库  
3. 选择无构建命令（Static HTML）  
4. 部署完成后获取访问链接

---

### 3. Netlify
1. 登录 [Netlify](https://www.netlify.com/)  
2. 点击 **Add New Site → Import an existing project**  
3. 连接到 GitHub 仓库  
4. 选择分支并部署，获取访问链接

---

### 4. Cloudflare Pages
1. 登录 [Cloudflare Pages](https://pages.cloudflare.com/)  
2. 创建项目并连接 GitHub 仓库  
3. 选择分支部署即可

---

### 5. Firebase Hosting
1. 安装 Firebase CLI  
    ```bash
    npm install -g firebase-tools
    ```
2. 登录 Firebase  
    ```bash
    firebase login
    ```
3. 初始化并部署  
    ```bash
    firebase init hosting
    firebase deploy
    ```

---

### 6. 本地运行
1. 直接双击 `index.html` 用浏览器打开（部分功能可能受限）  
2. 或使用 Python 开启本地服务器：  
    ```bash
    python -m http.server 8000
    ```
   访问 `http://localhost:8000/index.html`

---

## ⚖️ 版权与许可 / License

© 2025 神阿 (Shen A). 保留所有权利。  
开发者: StanlyNg  
本项目仅供学习和个人测试使用，不得用于任何违法用途。  
在遵守 MIT 许可证的前提下，允许自由复制、修改和发布。

© 2025 Shen A. All rights reserved.  
Developer: StanlyNg  
This project is for learning and personal testing purposes only and must not be used for any illegal activities.  
You are free to copy, modify, and distribute under the terms of the MIT License.

---

## 📞 联系方式 / Contact

如有问题或建议，请通过 GitHub Issues 联系我。  
For issues or suggestions, please contact me via GitHub Issues.
