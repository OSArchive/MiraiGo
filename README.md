# MiraiGo
qq-android协议的golang实现 移植于mirai

# 警告
本项目为协议实现，api非常原始，并不推荐使用。

建议基于 [go-cqhttp](https://github.com/Mrs4s/go-cqhttp) 使用框架开发。

# 已完成功能/开发计划
#### 登录
- [x] 账号密码登录
- [x] 验证码提交
- [x] 设备锁验证
- [x] 错误信息解析

#### 消息类型
- [x] 文本
- [x] 图片
- [x] 语音
- [x] 表情
- [x] At
- [x] 回复
- [x] 长消息
- [x] 链接分享
- [x] 小程序(暂只支持RAW)
- [ ] 位置
- [x] 合并转发
- [x] 群文件(仅接受消息)

#### 事件
- [x] 好友消息
- [x] 群消息
- [x] 临时会话消息
- [x] 登录号加群
- [x] 登录号退群(包含T出)
- [x] 新成员进群/退群
- [x] 群/好友消息撤回 
- [x] 群禁言
- [x] 群成员权限变更
- [x] 收到邀请进群通知
- [x] 收到其他用户进群请求
- [ ] 新好友
- [x] 新好友请求
- [x] 客户端离线

#### 主动操作
> 为防止滥用，将不支持主动邀请新成员进群

- [x] 发送群消息
- [x] 发送好友消息
- [x] 发送临时会话消息
- [x] 获取/刷新群列表
- [x] 获取/刷新群成员列表
- [x] 获取/刷新好友列表
- [x] 处理加群请求
- [x] 处理被邀请加群请求
- [x] 处理好友请求
- [x] 撤回群消息
- [ ] 群公告设置
- [x] 获取群文件下载链接
- [x] 群设置 (全体禁言/群名)
- [x] 修改群成员Card
- [x] 修改群成员头衔
- [ ] ~~群成员邀请~~
- [x] 群成员禁言/解除禁言
- [x] T出群成员
