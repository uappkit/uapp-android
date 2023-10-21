已通过 uapp add android 创建工程

代码发布位置：
<https://gitee.com/uappkit/platform>

> 此工程将存档，不再维护，未来将移除。

## uapp android 离线工程

```
.
├── README.md
└── app
    ├── app.keystore # 用于 apk 安装包签名
    ├── build.gradle # 基础配置, uapp manifest 会更新相关信息
    ├── custom.gradle # 自定义相关配置, 新增第三方依赖等
    ├── libs -> # 指向uappsdk 下的相关软连接, 此目录下的 libs 都会打包进 apk, 根据自身需要做调整
    └── src
```

> Android 编译必须选择 java 11，版本太高 Gradle 版本和库的依赖目前还无法支持。等 Uniapp 离线SDK 相关库的依赖版本同步升级时，我们也会跟进升级相关版本。

## License

The Apache License 2. Please see [License File](LICENSE.md) for more information.
