# Theme Starter
一、预览
预览：主题预览

如果你有计划长期使用主题，也来这里留下你的博客链接吧。

二、说明

关于主题使用上的一些问题可以参见 主题使用手册-基础篇

如有疑问，欢迎加入主题交流群：
111

个人博客交流，友链交换，欢迎加入 个人博客交流群：

欢迎参与主题开发的一些问题探讨

欢迎关注微信公众号，主题版本更新消息与要点说明将在公众号发布。
三、版本适配关系
主题版本	适配Halo版本	测试用Halo版本
1.x	2.0.0+	2.3.0
四、安装 & 更新
进入主题 Release 界面：https://github.com/nineya/halo-theme-dream2.0/releases 下载主题压缩包 halo-theme-dream.zip 压缩包文件；
进入博客后台管理 主题->主题管理->安装主题，选择下载的 halo-theme-dream.zip 安装包进行上传；
等待安装完成；
更新主题时同样前往主题 Release 界面下载主题安装包，然后通过 主题->主题管理->Dream->升级 方法上传安装包进行更新。
五、参与主题开发
推荐使用 IDEA 进行主题开发，能够比较好的支持 FreeMarker。

开发环境准备

安装 nodejs 版本需要在 15+；
主题目录下执行 npm i 安装依赖；
npm 命令

npm run lint 执行代码风格校验。

npm run zip 执行安装包打包，在无须重新编译 js/css 时使用。

npm run build 执行主题打包操作，主题将被打包为压缩包文件存放在 dist/ 目录下，同时 source 目录下的文件也将被更新。

npm run build --devel 开发模式进行主题打包，js 和 css 不会被做压缩和混淆处理，方便排查问题。

npm run release --tag=$version 发布模式执行主题打包操作，将自动更新主题中的版本号，并使用这个版本标签重新创建 FreeCDN 清单文件。

六、打赏项目
感谢您对本项目的喜爱，您的打赏是对本项目最好的支持！
