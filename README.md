# video_server

# 模块解析

- 前端服务
    - 接收页面发送的浏览器请求
- API模块
    - 处理核心业务逻辑
        - 用户登录
        - 用户信息获取
        - 添加视频
        - 视频列表
        - 删除视频
        - 提交评论
        - 展示评论
- Streaming
    - 删除视频
    - 播放视频, 并且限制同时播放视频的连接数
- Scheduler
    - 维护定时任务
    - 定时删除视频