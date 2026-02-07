# 时差转换器

一个纯静态的时区转换单页工具，支持常用时区选择与手动输入 IANA 时区名，自动处理夏令时（DST），可一键复制结果。

## 如何本地运行

1. 下载或克隆本仓库。
2. 直接双击 `index.html` 在浏览器中打开即可。

## 如何部署到 GitHub Pages

1. 在 GitHub 新建一个仓库（例如：`timezone-converter`）。
2. 将本项目文件上传到仓库根目录（至少包含 `index.html`，以及可选的 `README.md`）。
3. 打开仓库页面，进入 `Settings` → `Pages`。
4. 在 `Build and deployment` 中：
   - `Source` 选择 `Deploy from a branch`
   - `Branch` 选择 `main`（或你的主分支）
   - `Folder` 选择 `/root`
   - 点击 `Save`
5. 等待 GitHub Pages 部署完成。
6. 访问地址格式：
   - `https://<你的用户名>.github.io/<仓库名>/`

## 常见问题

- 部署后页面未更新？
  - 可能是缓存导致。请尝试强制刷新（Windows/Linux：`Ctrl+F5`；macOS：`Cmd+Shift+R`）。
- 子资源无法加载？
  - 确认所有资源路径都是相对路径，且文件已上传到仓库。
