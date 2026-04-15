# Flutter-learning


## 预备工作
> https://docs.flutter.cn/community/china/

配置环境变量：
export PUB_HOSTED_URL="https://pub.flutter-io.cn"
export FLUTTER_STORAGE_BASE_URL="https://storage.flutter-io.cn"

下载SDK
使用镜像下载

下载基于镜像站点的 Flutter SDK 压缩包
需要从镜像中的 SDK 版本列表 下载 Flutter, 请将 storage.googleapis.com 替换为你信任的镜像站点 URL。在浏览器或其他应用程序中使用镜像站点（如 IDM 或 Thunder）将提高下载速度。

下面的示例展示了如何将下载 Flutter 的 URL，从 Google 更改为 CFUG 的镜像。

要下载 macOS arm64 版本的 Flutter SDK，你需要将原始 URL：
```
https://storage.googleapis.com/flutter_infra_release/releases/stable/macos/flutter_macos_arm64_3.35.5-stable.zip
```
改为镜像 URL：
```
https://storage.flutter-io.cn/flutter_infra_release/releases/stable/macos/flutter_macos_arm64_3.35.5-stable.zip
```

配置gradle 8.9 镜像
```
distributionUrl=https\://mirrors.cloud.tencent.com/gradle/gradle-8.9-bin.zip
```

配置 ndk
```
sdk.dir=/Users/michelle/Documents/DevelopTools/android-sdk
sdk.ndk=/Users/michelle/Documents/DevelopTools/android-sdk/ndk/26.1.10909125
flutter.sdk=/Users/michelle/Documents/DevelopTools/flutter-tool/flutter
flutter.buildMode=debug
flutter.versionName=1.0.0
flutter.versionCode=1
```

将 `flutter.compileSdkVersion`和`flutter.ndkVersion`替换
```
//    compileSdk = flutter.compileSdkVersion
    compileSdk = 35
//    ndkVersion = flutter.ndkVersion
    ndkVersion = "26.1.10909125"
```



