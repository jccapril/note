1. 企业微信 可在客户端-工作台，点击-智能机器人-创建机器人，选择API模式创建。
![[ef7d33d6af1501c58403284d412794f6 1.jpg]]![[23d59a33b9450b7042112e300de421b9.jpg]]

2. 选择以 长连接 方式创建，并获取Bot ID 和 Secret。
![[e2d1d0f3752b8729aabfbb114156fbb0 1.jpg]]
3. 开始为Openclaw配置企业微信

安装企业微信插件
`openclaw plugins install @wecom/wecom-openclaw-plugin`

开始配置
`openclaw configure --section channels`


![[Pasted image 20260313153754.png]]
选择**Local**

![[Pasted image 20260313153816.png]]
选择 **Configure/link**

![[Pasted image 20260313153840.png]]
选择 **企业微信** 我的图里没有企业微信

按照指引输入企业微信的参数
主要是：Bot ID 和 Secret。

然后选择 开始Pair 

5. 在企业微信中，保存机器人，并跟它发消息，会收到一个配置密钥
![[bbd9546ae2d8e6f103196fc845c54693.png]]
