# GitHub Pages 个人主页模板

这是一个可直接部署到 GitHub Pages 的静态个人主页模板，适合做学术主页、简历型主页或个人介绍页。

## 文件说明

- `index.html`：主页结构
- `styles.css`：页面样式
- `assets/profile-placeholder.svg`：默认占位头像，建议替换成自己的照片

## 你需要修改的内容

打开 `index.html`，至少替换下面这些占位内容：

- `你的名字`
- `职位 / 身份`
- `学校 / 公司 / 实验室名称`
- `your-email@example.com`
- `your-github-username`
- `Google Scholar`、`LinkedIn` 的链接
- `About`、`News`、`Research Interests`
- `Selected Publications`
- `Experience`
- `Education`
- `Awards`

## 头像文件

把你的头像放到：

- `assets/profile-placeholder.svg`

你可以直接把它替换成自己的图片，也可以新增比如 `assets/profile.jpg`，然后同步修改 `index.html` 里的图片路径。

## 发布到 GitHub Pages

1. 在 GitHub 新建一个仓库，仓库名必须是 `你的用户名.github.io`
2. 把当前目录里的文件推送到这个仓库
3. 进入 GitHub 仓库页面
4. 打开 `Settings`
5. 打开 `Pages`
6. 在 `Build and deployment` 里选择：
   - `Source`: `Deploy from a branch`
   - `Branch`: `main`，目录选 `/ (root)`
7. 保存后等待几十秒到几分钟
8. 访问 `https://你的用户名.github.io/`

## 本地预览

如果你想先在本地看效果，可以在当前目录运行：

```bash
python3 -m http.server 8000
```

然后打开：

```text
http://localhost:8000
```
