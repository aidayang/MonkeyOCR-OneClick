# MonkeyOCR-OneClick
MonkeyOCR:PDF/图片转Markdown格式软件免安装部署一键启动整合包

![](https://raw.githubusercontent.com/aidayang/MonkeyOCR-OneClick/refs/heads/main/mocr.webp)

## MonkeyOCR整合包使用说明

输入文件路径就处理文件，输入文件夹路径就处理文件夹内所有pdf文档

【组大小】按特定分组大小对输入路径（一个目录）中的图像进行分组解析

【nums】这是我自己添加的一个参数，因为原应用用起来有些问题，这个主要是增加对低端显卡的支持，如果显卡为20X6G等低端显卡，运行报错的话尝试设置为1.如果还报No enough gpu memory for runtime的话，就需要更大显存。如果显卡为40X高端大显存显卡可尝试增大该值，会影响处理速度。如果软件没有报错的话建议保持默认

即可。

【单任务】单任务识别，如识别文本、公式、表格，（仅输出 Markdown 格式）

【输出单页面】解析 PDF 并按页面拆分结果

默认只输入待处理文件和保存位置即可，没有必要的话其它设置可不用管。

软件支持批量操作，输入文件夹路径或是将文件夹拖入软件窗口即可。

视频教程及效果演示：https://www.youtube.com/watch?v=NHc6mNJDyl8

## 注意事项
未测试最低配置要求，建议英伟达显卡显存不低于6G，如果报错：No enough gpu memory for runtime。则需要更多显存

软件只支持windows 10或11

软件运行路径中不要有非英文字符及空格，待处理文件同样注意

## PDF转MD软件MonkeyOCR整合包下载链接
https://pan.quark.cn/s/e25dfa6e0f5a

## 原项目链接
https://github.com/Yuliang-Liu/MonkeyOCR
