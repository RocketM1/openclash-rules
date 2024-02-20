# 使用

基础规则：[ACL4SSR_Online_Full](https://github.com/ACL4SSR/ACL4SSR/blob/master/Clash/config/ACL4SSR_Online_Full.ini)

转换规则：[subconverter](https://github.com/tindy2013/subconverter/blob/master/README-cn.md)

订阅链接

    https://api.dler.io/sub?target=clash&new_name=true&insert=true&emoji=true&udp=true&scv=true&clash.doh=true&config=https%3A%2F%2Fraw.githubusercontent.com%2FRocketM%2Fopenclash-rules%2Fmain%2FFull.ini&url=

基础版

    https://api.dler.io/sub?target=clash&new_name=true&insert=true&emoji=true&config=https%3A%2F%2Fraw.githubusercontent.com%2FRocketM%2Fopenclash-rules%2Fmain%2FFull.ini&url=
    
url后跟你的订阅链接，需要使用URL编码


# 注意事项

1. 关闭浏览器 `http3`

```csharp
    chrome://flags/#enable-quic
    edge://flags/#enable-quic
```
    
降级成 `http1/2`

2. 自定义规则在 `direct.list` 和 `proxy.list`中编辑
