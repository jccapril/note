## 新手引导安装

### 后台运行
`openclaw onboard --install-daemon`
### 前台运行
`openclaw onboard`

### 检查网关状态
`openclaw gateway status`

### 重启网关
`openclaw gateway restart`

### 打开Web后台UI
`openclaw dashboard`

### 重新设置配置
`openclaw configure`
重新设置channel
`openclaw configure --section channels`


### 安装企业微信插件
`openclaw plugins install @wecom/wecom-openclaw-plugin`

1. 企业微信 可在客户端-工作台，点击-智能机器人-创建机器人，选择API模式创建。
![[ef7d33d6af1501c58403284d412794f6 1.jpg]]![[23d59a33b9450b7042112e300de421b9.jpg]]

2. 选择以 长连接 方式创建，并获取Bot ID 和 Secret。
![[e2d1d0f3752b8729aabfbb114156fbb0 1.jpg]]

3. 在企业微信中，保存机器人，并跟它发消息，会收到一个配置密钥
![[bbd9546ae2d8e6f103196fc845c54693.png]]


## 安装钉钉插件
`openclaw plugins install @soimy/dingtalk`
 
步骤请看：
https://github.com/soimy/openclaw-channel-dingtalk