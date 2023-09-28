# 抖音弹幕

#### 介绍
抖音直播间消息采集，包括弹幕消息、礼物消息、点赞、进入直播间、关注直播间
纯协议，提供急速API。1分钟完成接入。

[演示视频](https://www.bilibili.com/video/BV1BH4y1U7TM/)

#### 接口说明
> http://[host]/douyin/ws-start?live_id=7829759800&num=100

|  参数名 |  说明 |
|---|---|
|  live_id | 直播间房间号  |
|  num |  获取消息数量 |

#### 接口返回：
```
[
    {
        "content": "来了",
        "msg_type": "in",
        "t": 1695785584,
        "user": {
            "dyh": "1110537461",
            "fss": 28,
            "gender": 0,
            "gzs": 42,
            "nickname": "卫男aa",
            "profie_id": "MS4wLjABAAAAuYdv9pOQwXSnJMJzZsxSWA-09Afjc4qr3JCLOioqod4",
            "tx": "https://p6.douyinpic.com/aweme/100x100/aweme-avatar/mosaic-legacy_3793_3131589739.jpeg?from=3067671334",
            "xzdj": 3
        }
    }
]
```
|  参数名 |  说明 |
|---|---|
|  **msg_type** |  消息类型： in=进入直播间   chat=弹幕消息  like=点赞   gift=礼物     gz=关注 |
|  **content** | 消息内容  |
|  **t** |  消息时间 |
|   **dyh** | 抖音号  |
|   **fss** |  粉丝数 |
|  **gzs** | 关注数  |
|   **gender** |  性别 0=女 1=男     |
|  **nickname** | 昵称  |
|  **tx** |  头像 |
|  **xzdj** | 直播间徽章等级  |



#### 联系
![输入图片说明](vx.jpg)
> QQ：1161149119

#### 演示
![输入图片说明](2023-09-28%2009-53-23_1.gif)
