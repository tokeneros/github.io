# github.io 目录结构
.
├── _includes        # 包含部分，如页眉、页脚或共享的HTML片段
├── _layouts         # 页面布局，用于组织和渲染页面的HTML结构
├── _posts           # 博客文章，通常为 Markdown 文件，按日期排序
├── _drafts          # 草稿文章，未发布的Markdown文件
├── _data            # YAML 数据文件，用于存储可重用的数据
├── assets           # 静态文件，如图片、JavaScript和CSS文件
│   ├── images       # 图片文件
│   ├── js  # JavaScript 文件
│   └── css  # CSS 文件
├── .gitignore       # Git忽略文件列表
├── Gemfile          # Bundler配置文件，列出项目的Ruby依赖
├── _config.yml      # Jekyll配置文件
├── README.md        # 项目README文件
├── index.md         # 网站首页内容，可选
└── 404.html         # 错误页面

## 问题一 github代码推送不上去
通过 https://www.ipaddress.com/website/github.com/ 配置 /etc/hosts