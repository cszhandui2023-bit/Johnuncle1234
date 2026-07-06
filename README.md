# 轻背单词

一个可以直接发布到 GitHub Pages 的背单词小网页。

## 本地打开

如果你只是自己电脑上看，可以运行：

```bash
python3 -m http.server 8765 --directory docs
```

然后打开：

```text
http://localhost:8765/index.html
```

## 发布到 GitHub Pages

1. 在 GitHub 新建一个仓库，比如 `word-card-app`。
2. 把这个文件夹上传到仓库。
3. 进入仓库的 `Settings`。
4. 左侧点 `Pages`。
5. `Build and deployment` 里选择：
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/docs`
6. 点击 `Save`。

几分钟后，GitHub 会给你一个公开网址，任何电脑都能打开。

## 说明

学习进度保存在每台设备自己的浏览器里。别人打开网页后，会有自己的背单词进度，不会看到你的进度。
