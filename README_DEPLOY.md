# Mini Platform Fighter Public Build

这个文件夹就是可公开发布的网页版本。

## 文件

- `index.html`：完整游戏网页，资源已经内联，不依赖服务器构建。
- `.nojekyll`：给 GitHub Pages 使用，避免额外处理静态文件。

当前版本包含人机训练、单人训练场、创建房间、加入房间和快速匹配入口。联机使用 WebRTC，静态托管即可运行。

## 发布方式

把这个文件夹上传到任意静态网页托管服务即可：

- GitHub Pages
- Netlify Drop
- Vercel
- Cloudflare Pages
- 任何能托管静态 HTML 的服务器

网站入口是 `index.html`。
