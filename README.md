# 祝你生日快乐｜翻页回忆相册

纯静态 GitHub Pages 网站，无需构建工具。

## 上传发布

1. 新建 GitHub 仓库。
2. 上传本文件夹中的 `index.html` 和 `assets/` 到仓库根目录。
3. 打开仓库 **Settings → Pages**。
4. **Source** 选择 `Deploy from a branch`。
5. Branch 选择 `main` 和 `/root`，保存后等待一两分钟。

## 修改留言

用记事本或 VS Code 打开 `index.html`，搜索“想改留言”，直接替换下面几段文字即可。

## 替换音乐

把自己的音乐文件放到 `assets/`，再在 `index.html` 中搜索 `birthday-music.wav`，替换成你的文件名即可。

## 本地预览

双击 `index.html`，或在本文件夹运行：

```bash
python -m http.server 8000
```

然后访问 `http://localhost:8000`。
