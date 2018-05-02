# 一个会动的简历模板

> This is my resume

[![GitHub issues](https://img.shields.io/github/issues/zzlw/resume.svg)](https://github.com/zzlw/resume/issues)
[![GitHub forks](https://img.shields.io/github/forks/zzlw/resume.svg)](https://github.com/zzlw/resume/network)
[![GitHub stars](https://img.shields.io/github/stars/zzlw/resume.svg)](https://github.com/zzlw/resume/stargazers)
[![GitHub license](https://img.shields.io/github/license/zzlw/resume.svg)](https://github.com/zzlw/resume/blob/master/LICENSE)

[预览](https://baby925.top/resume/public/)

## 使用方法

``` bash
git clone git@github.com:resume/resume.git
cd resume
npm install
npm run dev
```

## 部署方法


1. 编辑 config/index.js，修改第 10 行的 assetsPublicPath，值为 `项目名/dist`。如果你没有修改项目名 resume，则可跳过此步骤。

2. 编译、上传
    ``` bash
    npm run build
    git add .
    git commit -m "update"
    git push
    ```

3. 开启 GitHub Pages 功能
