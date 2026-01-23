# Roamix Official Site

静态官网（中英双语），用于展示公司主体信息、联系方式、隐私政策与服务条款，适配 GitHub Pages。

## 目录结构

```
roamix-site/
├─ index.html
├─ privacy.html
├─ terms.html
└─ assets/
   └─ logo.svg   (可选)
```

## 本地预览

直接打开 `index.html` 即可预览。

## GitHub Pages 部署

1. 在 GitHub 创建仓库（例如：`roamix-site`）。
2. 将本项目文件提交到仓库根目录。
3. 进入仓库 **Settings → Pages**。
4. Source 选择 **Deploy from a branch**。
5. Branch 选择 `main`，目录选择 `/root`。
6. 保存后等待生效，即可访问 `https://<你的用户名>.github.io/<仓库名>/`。

## 绑定自定义域名（可选）

1. 在 **Settings → Pages → Custom domain** 填写你的域名（例如 `www.roamix.cn`）。
2. 到 DNS 添加 CNAME 记录指向 `你的用户名.github.io`。
3. 生效后勾选 **Enforce HTTPS**。

## 提交更新

更新公司信息或政策内容时，直接修改对应 HTML 文件并提交即可。
