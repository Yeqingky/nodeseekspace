# 部署 IP 探针 到 Cloudflare Pages 教程

## 1. 下载项目
1. 点击右上角绿色的 **Code** 按钮 → 选择 **Download ZIP**    

---

## 2. 修改 `_worker.js` (可选)
1. 在解压后的文件夹里找到 `_worker.js` 文件  
2. 使用文本编辑器打开它  
3. 你可以通过在URL中添加 `?name=你的名字` 来动态设置名字，例如 `https://your-page-url.pages.dev/?name=张三`
4. 如果不提供 `name` 参数，将默认显示“你的名字”。你也可以在 `_worker.js` 文件中修改默认名字。  

---

## 3. 准备上传文件
1. 确认文件夹中包含以下文件：  
   - `index.html`  
   - `_worker.js`  
2. 将这两个文件放在同一个文件夹内  

---

## 4. 部署到 Cloudflare Pages
1. 打开 [Cloudflare Pages](https://dash.cloudflare.com/)
2. 点击 Workers → Workers 和 Pages → 创建应用程序 → 选择 Pages
3. 将准备好的文件 **夹** **拖拽**到页面中  
4. 点击 **部署 (Deploy)**  
5. 部署完成后会生成一个访问链接（域）
