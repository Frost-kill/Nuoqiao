# Digital Marketing Pro - GitHub Pages 网站

## 项目概述

这是一个为亚马逊广告合作伙伴注册准备的静态网站，包含首页和隐私政策页面。

## 文件结构

```
.
├── index.html          # 网站首页
├── privacy-policy.html # 隐私政策页面
└── README.md          # 项目说明
```

## GitHub Pages 部署步骤

### 1. 创建 GitHub 仓库

1. 登录 [GitHub](https://github.com)
2. 点击右上角的 "+" 号，选择 "New repository"
3. 输入仓库名称，例如 `digital-marketing-pro`
4. 选择 "Public"（公开）
5. 点击 "Create repository"

### 2. 上传文件

#### 方法一：通过 Git 命令行

```bash
# 克隆仓库（替换为您的仓库地址）
git clone https://github.com/您的用户名/digital-marketing-pro.git

# 进入项目目录
cd digital-marketing-pro

# 将网站文件复制到此目录

# 添加文件到 Git
git add .

# 提交更改
git commit -m "Initial commit: Add website files"

# 推送到 GitHub
git push origin main
```

#### 方法二：通过 GitHub 网页上传

1. 在仓库页面点击 "Add file" -> "Upload files"
2. 拖拽或选择 `index.html` 和 `privacy-policy.html` 文件
3. 点击 "Commit changes"

### 3. 启用 GitHub Pages

1. 在仓库页面，点击 "Settings"（设置）
2. 在左侧菜单中找到 "Pages" 选项
3. 在 "Source" 部分：
   - Branch: 选择 `main` 或 `master`
   - Folder: 选择 `/(root)`
4. 点击 "Save"

### 4. 访问您的网站

- 等待几分钟让 GitHub Pages 部署完成
- 您的网站地址将是：`https://您的用户名.github.io/digital-marketing-pro/`
- 隐私政策页面地址：`https://您的用户名.github.io/digital-marketing-pro/privacy-policy.html`

## 在亚马逊广告合作伙伴注册中使用

1. 在注册表单中的"公司网站"字段，填写您的 GitHub Pages 地址：
   ```
   https://您的用户名.github.io/digital-marketing-pro/
   ```

2. 确保网站可以正常访问，并且包含隐私政策页面

## 自定义内容

### 修改公司信息

编辑 `index.html` 和 `privacy-policy.html` 中的以下内容：

- 公司名称：搜索并替换 `Digital Marketing Pro`
- 联系邮箱：替换 `privacy@digitalmarketingpro.com`
- 公司地址：替换 `[您的公司地址]`

### 修改样式

网站使用内联 CSS 样式，您可以直接编辑 HTML 文件中的 `<style>` 部分来自定义颜色、字体等。

## 注意事项

1. **HTTPS**：GitHub Pages 默认提供 HTTPS，符合亚马逊广告合作伙伴的要求
2. **隐私政策**：确保隐私政策内容符合您的实际业务情况和当地法律法规
3. **更新维护**：定期检查和更新网站内容

## 技术支持

如有问题，请参考：
- [GitHub Pages 文档](https://docs.github.com/en/pages)
- [GitHub 文档](https://docs.github.com)
