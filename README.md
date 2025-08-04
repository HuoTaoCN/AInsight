# 见微 (AInsight)

> 于细微处，洞见未来。

## 项目简介

见微（AInsight）是一个专注于人工智能深度思考的中文博客网站。在AI重塑世界的时代，我们致力于探索从代码到文明的深远影响，不追逐热点的喧嚣，只专注于那些真正塑造未来的深层力量。

我们相信，理解技术的细微之处，正是洞见文明走向的关键。

> **特别说明**: 本网站的搭建、文章内容、设计等均通过AI技术生成，这本身就是对人工智能创造能力的一次实践探索。

## 网站结构

### 🔍 解码智能
深入人工智能的核心概念与技术引擎，从算法本质到涌现能力，为你构建理解智能时代的知识基石。

- **基础概念** - 智能的本质等基础理论
- **技术引擎** - 深度学习、机器学习等核心技术

### 📖 深度专题
长篇深度分析，系统性探讨AI对社会、经济、文化的深远影响。每一篇都是对时代议题的深度思辨。

主要专题包括：
- AI与科学革命
- 算法伦理与治理
- 意识边界与AGI
- 创意产业变革
- 数字原住民的崛起
- 量子计算的未来

### ⚡ 思想碎片
记录那些不成系统却极具启发性的灵感火花。一个突然的洞察，一篇论文的精彩观点，一个开放性的思考。

## 技术栈

- **前端**: 纯HTML + CSS + JavaScript
- **样式**: 自定义CSS，响应式设计
- **部署**: 静态网站，可部署到任何静态托管服务

## 项目结构

```
AInsight/
├── index.html              # 首页
├── about.html              # 关于页面
├── decode.html             # 解码智能页面
├── features.html           # 深度专题页面
├── sparks.html             # 思想碎片页面
├── css/
│   └── styles.css          # 主样式文件
├── articles/               # 文章目录
│   ├── basic-concepts/     # 基础概念文章
│   ├── tech-engines/       # 技术引擎文章
│   ├── deep-features/      # 深度专题文章
│   └── sparks/             # 思想碎片文章
├── LICENSE                 # GPL v3.0 许可证
└── README.md              # 项目说明文档
```

## 本地运行

由于这是一个纯静态网站，你可以通过以下方式在本地运行：

### 方法一：直接打开
直接在浏览器中打开 `index.html` 文件。

### 方法二：使用本地服务器

使用Python内置服务器：
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

使用Node.js的http-server：
```bash
npx http-server -p 8000
```

然后在浏览器中访问 `http://localhost:8000`

## 部署

这个项目可以部署到任何静态网站托管服务：

- **GitHub Pages**: 推送到GitHub仓库，启用Pages功能
- **Netlify**: 拖拽文件夹到Netlify或连接Git仓库
- **Vercel**: 导入GitHub仓库到Vercel
- **传统服务器**: 上传所有文件到web服务器目录

## 贡献指南

我们欢迎各种形式的贡献：

1. **内容贡献**: 提交高质量的AI相关文章
2. **技术改进**: 优化网站性能、用户体验
3. **设计优化**: 改进UI/UX设计
4. **错误修复**: 修复bug和错别字

### 提交流程

1. Fork 本仓库
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 创建 Pull Request

## 许可证

本项目基于 [GNU General Public License v3.0](LICENSE) 开源协议。

## 联系方式

- 网站: [见微 AInsight](https://github.com/huotaocn/ainsight)
- GitHub: [@huotaocn](https://github.com/huotaocn)
- 邮箱: mail@huotao.com

---

*在人工智能重塑世界的时代，让我们一起于细微处洞见未来。*