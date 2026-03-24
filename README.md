# ROBO.PORTFOLIO

机器人风格的个人作品集网站。

## 技术栈

- 纯 HTML / CSS / JavaScript（无框架依赖）
- 赛博朋克 + 终端风格 UI
- Google Fonts（Orbitron + Share Tech Mono + Rajdhani）
- GitHub Actions 自动部署到 GitHub Pages

## 快速开始

```bash
# 本地预览
python -m http.server 8000
# 或
npx serve .
```

然后访问 http://localhost:8000

## 部署

推送到 GitHub `main` 分支后，GitHub Actions 自动部署到：
`https://[your-username].github.io/[repo-name]/`

## 自定义

在 `index.html` 中修改：

- **个人信息**：ABOUT 区块文字
- **技能数据**：SKILLS 区块的 skill-bar width %
- **项目列表**：PROJECTS 区块
- **联系方式**：CONTACT 区块的 footer 链接
- **统计数字**：ABOUT 区块的 stat-num

## GitHub Pages 启用步骤

1. Fork 或复制此仓库
2. 进入 **Settings → Pages**
3. Source 选择 **Deploy from a branch** → **main** → **/ (root)**
4. 保存后等待 1-2 分钟，网站自动上线
