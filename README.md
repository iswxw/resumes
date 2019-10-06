### 本项目源于：https://github.com/JoeyBling/anires  向作者表示深深的敬意。

# 一个会动的简历模板

> This is my resume

[预览](https://githubwxw.github.io/resume/public/)

## 使用方法

``` bash
git clone https://github.com/GitHubWxw/resume.git
cd animating-resume
npm install
npm run dev
```

## 部署方法


1. 编辑 config/index.js，修改第 10 行的 assetsPublicPath，值为 `项目名./`。如果你没有修改项目名 resume，则可跳过此步骤。

2. 编译、上传
    ``` bash
    npm run build
    git add .
    git commit -m "update"
    git push
    ```

3. 开启 GitHub Pages 功能

