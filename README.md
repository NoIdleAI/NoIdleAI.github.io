# NoIdle 官网

NoIdle 品牌官网 —— 纯静态、零外部依赖,由 GitHub Pages 托管。

- 线上地址:<https://noidleai.github.io/>
- 品牌资产仓库:NoIdleAI 内部维护

## 本地预览

```bash
cd 本目录
python3 -m http.server 8642
# 打开 http://127.0.0.1:8642
```

## 目录结构

```
index.html          # 单页官网
404.html            # 404 回首页
robots.txt
assets/css/         # 样式
assets/js/          # 交互(入场动画 / 导航状态)
assets/img/         # 品牌 logo 与图标
```

## 内容约定

- 只有**公开开源**的仓库才在页面上挂链接(如 noidle-resume);
- 私有仓库一律只做文字与概念展示,标注「私有 · 未开源」;
- 品牌素材版权归 NoIdle 所有,页面内容遵循 Apache-2.0 与 © NoIdle 署名。
