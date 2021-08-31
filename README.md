### 文档内容
HBuilder X 下创建的项目文件通过 npm 方式进行编译处理(脱离HBuilder编译使用)

### 安装依赖包
```
npm i

```

### development 使用方式
```
npm run dev:%PLATFORM%

```

### production 使用方式
```
npm run build:%PLATFORM%
```

### %PLATFORM% 参考列表

%PLATFORM% | 描述
---- | -----
h5|H5
mp-alipay|支付宝小程序
mp-baidu|百度小程序
mp-weixin|微信小程序
mp-toutiao|字节跳动小程序
mp-qq|qq 小程序
mp-360|360 小程序
mp-kuaishou|快手小程序
quickapp-webview		|快应用(webview)
quickapp-webview-union	|快应用联盟
quickapp-webview-huawei|快应用华为

### 项目编译位置
```

根目录下dist内 build(发行包)  dev(测试包)   

```