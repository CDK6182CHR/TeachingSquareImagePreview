# 教学立方图片预览插件
 A Chrome extension to preview images at teaching.applysquare.com

## 原理

直接注入js脚本从页面获取作业真实下载链接，如果是图片就直接用`<img>...</img>`嵌入到网页而不必单独下载，如果不是就转换为真实下载链接而不是`javascript:void(0);`。

## 安装方式

1. `clone`到本地（如果是`.zip`压缩包那解压成文件夹）
2. 打开Chrome或Chromium系浏览器，Chrome输入`chrome://extensions`，Chromium Edge输入`edge://extensions`
3. 打开“开发人员模式”
4. 点击“加载解压缩的扩展包”，选中本地的仓库文件夹

## 使用方式

打开每个学生的教学立方作业批改页面，直接点击插件图标。

## 已知问题

+ 由于本人能力有限只能暂时解决图片问题，pdf和word文档基本都是一个文档其实也不太妨碍。
+ 实际测试中，极个别图片显示不正常，目前不知道原因，但绝大多数可以用

## 欢迎改进

非常非常非常欢迎有大佬看见感兴趣可以改进的，特别是文件预览因为url含有验证遭遇到不小麻烦，暂时没办法解决。当然最好的办法是官方技术能抽个小空来改造，这样这个插件从此就用不上了……