# bug list

## version1.0

- 01：连续加载图片可导致oom异常退出，solve：可尝试更改加载策略，缓存大小。
- 02: 个人主页出现recycleview的布局错误，solve： 可以baseAdapter查看issu，或跟踪导致这一错误的原因。

--------------------

# update log


## Version1.0

- 初始版本


## Version1.1
- 数据加密
- sid实现访问控制 （这两个尽管1.0曾尝试实现，必要时可更换web框架，android适应Web app）
- ~~添加@别人~~
- ~~发帖添加地理位置信息（github search “城市选择”，“仿微信”，计划加入仿微信发送位置）~~
- 替换现有的短视频录制 copy by
- 优化发帖(视频录制库 copy by)和帖子的显示（播放器的延迟时间，更新或修改）