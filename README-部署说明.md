# ECUT-VQA GitHub Pages 一键上传文件说明

目标仓库：`ECUT-VQA/ecut-vqa.github.io`（Public）
网站地址：`https://ecut-vqa.github.io`

## 通过 GitHub 网页部署

1. 使用组织 Owner 在 ECUT-VQA 下创建公开仓库 `ecut-vqa.github.io`，打开 `Add README` 开关后创建。
2. 进入仓库的 **Code** 页面，点击 **Add file > Upload files**。
3. 从本压缩包解压后的 **站点文件夹内部** 选取并上传 `index.html`、`members.html`、`publications.html`、`assets` 文件夹和 `people` 文件夹。注意根目录必须有 `index.html`。
4. 如果 GitHub 网页未保留拖入的文件夹结构，请先上传三个根目录 HTML 文件，然后在相应目录中创建或上传内页。
5. 提交到 `main` 分支。
6. 打开仓库 **Settings > Pages > Build and deployment**，Source 选 `Deploy from a branch`，Branch 选 `main`，Folder 选 `/(root)`，点击 **Save**。
7. 返回 Pages 设置页，部署完成后点击 **Visit site**。测试 `/members.html`、`/publications.html` 和 `/people/tonghan-wang.html` 等链接。
8. 为本人账号授予 `ecut-vqa.github.io` 仓库的 Write 权限；原 `.github` 仓库权限不会自动继承。

## 重要说明

- 教师卡片上的 TW/HJ 是照片占位符，不是人物照片。正式上线前与老师确认并替换。
- 确认学生姓名、研究方向及照片展示授权后，再添加学生与校友。
- 第二篇论文的 2026 年录用与 2027 年计划刊出信息依据课题组提供的资料，正式卷期页码以期刊为准。
- 不需要服务器、数据库或 Node.js。网页全部采用静态 HTML/CSS，可直接使用 GitHub Pages。
- 这个站点使用相对路径，因此也可以直接在本地浏览器中打开 `index.html` 预览。
