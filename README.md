# 小胰宝项目官网

这是小胰宝项目的官方网站代码仓库。该网站旨在介绍小胰宝项目，展示我们的使命和愿景，以及分享近期活动信息。

## 项目结构

```
xyb-web/
├── index.html          # 主页
├── recruitment.html    # 招募页面
├── activities.html     # 近期活动页面
├── css/
│   └── style.css      # 样式文件
└── images/
    └── logo.png       # 项目logo
```

## 部署说明

本网站使用GitHub Pages部署。要部署网站，请按照以下步骤操作：

1. 确保所有文件都已提交到main分支
2. 在GitHub仓库设置中启用GitHub Pages
3. 选择main分支作为源分支
4. 等待几分钟，网站将自动部署

## 本地开发

要在本地预览网站：

1. 克隆仓库：
```bash
git clone [仓库地址]
```

2. 使用任意HTTP服务器在本地运行，例如：
```bash
python -m http.server 8000
```

3. 在浏览器中访问 `http://localhost:8000`

## 贡献指南

欢迎提交Pull Request来改进网站。在提交PR之前，请确保：

1. 代码符合项目规范
2. 所有页面都能正常显示
3. 响应式布局正常工作

## 许可证

本项目采用MIT许可证。详见LICENSE文件。
