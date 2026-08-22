---
AIGC:
    Label: "1"
    ContentProducer: 001191440300708461136T1XGW3
    ProduceID: 0458e8f990e0c40ed265fae3e70c5d22_7f778f229e6411f1a413525400287e28
    ReservedCode1: 0Zoclc0b6WeWvQH+EoyEJ3UWvNCR3Wvmb4pDjTW343lQ4OKqfwd/xM5qg5uMfCH+M60zq1wSiJaqtlpfRTpBJmp6cvR8QXTgFn2m48kT4Uhax/kC+PHkOsaFwMYFHb/jag8cgiEM69YtY1/sOAbTesy3z73vAdkQE7tKdRQpp8tnMt9geT6lcVTOx1g=
    ContentPropagator: 001191440300708461136T1XGW3
    PropagateID: 0458e8f990e0c40ed265fae3e70c5d22_7f778f229e6411f1a413525400287e28
    ReservedCode2: 0Zoclc0b6WeWvQH+EoyEJ3UWvNCR3Wvmb4pDjTW343lQ4OKqfwd/xM5qg5uMfCH+M60zq1wSiJaqtlpfRTpBJmp6cvR8QXTgFn2m48kT4Uhax/kC+PHkOsaFwMYFHb/jag8cgiEM69YtY1/sOAbTesy3z73vAdkQE7tKdRQpp8tnMt9geT6lcVTOx1g=
---

# 硬件学习传承站

实验室硬件方向的学习路线、项目分享与踩坑记录。目标是让每一届学弟学妹都有一条可以照着走的硬件成长路径，把嵌入式与电赛的经验沉淀下来。

## 技术栈

- [Hexo](https://hexo.io/) 7.x — 静态博客框架
- [Butterfly](https://github.com/jerryc127/hexo-theme-butterfly) 5.x — 主题
- Node.js 18+ / pnpm（或 npm）

## 栏目

| 栏目 | 内容 |
|---|---|
| 学习路线 | 给新人的硬件主线地图：电子基础 → 单片机 → PCB → 进阶 → 电赛实战 |
| 项目分享 | 每个项目一篇：背景 / 方案 / 代码仓库 / 遇到的问题与解决 |
| 软件心得 | Keil、CubeMX、立创EDA、Altium 等工具的使用经验 |
| 电赛传承 | 备赛清单、分工建议、踩坑合集 |
| 月记 | 阶段复盘与总结 |
| 关于我 | 个人简介与联系方式 |

## 本地运行

```bash
# 安装依赖
npm install
# 或 pnpm install

# 本地预览（默认 http://localhost:4000）
hexo server

# 生成静态文件
hexo generate

# 部署到 GitHub Pages
hexo deploy
```

## 写文章

在 `source/_posts/` 下新建 `.md` 文件，开头填写 Front Matter：

```markdown
---
title: 文章标题
date: 2026-08-23 10:00:00
categories: [项目分享]
tags: [STM32, PCB]
---
```

`categories` 决定文章归属栏目，可选：`项目分享` / `软件心得` / `电赛传承` / `月记`。

## 目录结构

```
source/
├── _posts/          # 文章（Markdown）
├── about/           # 关于我页面
├── learning-path/   # 学习路线页面
├── categories/      # 分类页
└── tags/            # 标签页
_config.yml              # 站点配置
_config.butterfly.yml    # 主题配置
```

## 贡献

欢迎实验室同学补充内容：直接提 PR 或在 Issues 里讨论。文章结构参考各栏目的模板文章即可。

## License

文章内容遵循 [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.zh)（署名-非商业性使用-相同方式共享）。
*（内容由AI生成，仅供参考）*
