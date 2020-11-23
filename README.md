# github-actions-youtube-dl

使用 GitHub Actions 下载 YouTube 视频。

## 原理

使用 GitHub Actions 的服务器，从 YouTube 下载视频。将需要下载的视频添加到 playlist.txt 文件中，每次 push 的时候，github action 读取 playlist.txt 列表，并下载列表中的所有视频。

## 使用

- 点右上角 **Fork** 按钮复制本 GitHub 仓库
- 在自己的项目中，点上方 **Actions** 选项卡进入项目 GitHub Actions 页面, 点击绿色按钮 “**I understand my workflows, go ahead and enable them**” 开启自动提交功能
- 编辑 [playlist.txt](./playlist.txt) 文件，将视频的 url 添加到列表中
- 等待 github action 执行成功，视频会出现在 [downloads](./downloads/) 目录

## Roadmap

- [x] 使用 GitHub Action 下载视频
- [x] 从列表中下载多个视频
- [x] 自定义配置
- [ ] CDN 加速

## License

[github-actions-youtube-dl](https://github.com/justjavac/github-actions-youtube-dl) is released under the MIT License. See the bundled [LICENSE](./LICENSE) file for details.
