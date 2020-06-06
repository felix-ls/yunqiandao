# 超星云签到
  用的知乎大佬的云函数超星学习通签到https://zhuanlan.zhihu.com/p/135829536 的源代码
  
  简单改写https://github.com/wangziyingwen/AutoApiSecret 的yml，实现自动定时运行
  
  不太会cron，设置的星期一到星期五7点20,9点20,1点20，3点20触发，每次运行一个小时

>### 使用方法
  在云签到.py中把账号信息填好，然后把云签到.yml 中第9行和第10行的#去掉，保存即可
