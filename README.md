# nanbeichao-privacy

《南北朝天下对弈》的隐私政策托管仓库。

这个仓库只包含一个文件 `index.html`，通过 GitHub Pages 发布，作为 Steamworks
后台「隐私政策网址」字段的指向地址。

## 为什么单独建仓库

主游戏仓库 `nanbeichao-game` 有自动化任务（`loop-engineering[bot]`）持续推送
提交，混放法律文档容易产生意外冲突；独立仓库也让隐私政策的更新路径清晰可见。

## 怎么改

直接编辑 `index.html`，改完提交即可，GitHub Pages 会自动重新部署（通常 1 分钟内）。

需要同步维护 `52270801@qq.com`（支持邮箱）与发行商名称 **AN YUSHEN**。

## 本地预览

```bash
# 任选其一
python -m http.server 8000
npx serve .
```

然后打开 <http://localhost:8000/>。

## 正式地址

<https://anyushen4-sys.github.io/nanbeichao-privacy/>

## 版权

© 2026 AN YUSHEN. 保留所有权利。