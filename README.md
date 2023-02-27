# Send-Font-News-Bot

利用 Action 获取前端资讯文章，每日定时推送

## 方式
    利用[schedule](https://docs.github.com/en/actions/using-workflows/events-that-trigger-workflows#schedule)设置时间段定时，
    当前设置- cron: "59 23 * * *"，意思是UTC时间的第23个小时的第59分钟调用，实质上定时任务是会存在延迟的，可能服务器位置原因，毕竟免费资源
    当前项目如两个月无提交，schedule会自动关闭
    
## 前端咨询地址
https://front-end-rss.vercel.app


## 其他

实现总结文章：
[基于GITHUB ACTION的定时任务，真香！](https://blog.csdn.net/qq_40748336/article/details/110749375)

[GitHub Actions 实现 RN App 自动化构建并推送到蒲公英](https://github.com/giscafer/blog/issues/53)
