# TV Web App

这是一个简单的Android应用，将网站 [https://github.com/LibreSpark/LibreTV](https://github.com/LibreSpark/LibreTV) 包装成一个移动应用。

## 功能

- 完整展示网站内容
- 支持JavaScript
- 启用缩放功能
- 处理后退按钮
- 支持DOM存储和应用缓存

## 构建方法

### 使用Android Studio

1. 克隆此仓库
2. 在Android Studio中打开项目
3. 点击"Build"菜单，然后选择"Build Bundle(s) / APK(s)" > "Build APK(s)"
4. 构建完成后，APK文件将位于`app/build/outputs/apk/debug/app-debug.apk`

### 使用GitHub Actions

您也可以直接从GitHub Actions下载最新构建的APK：

1. 进入本仓库的"Actions"选项卡
2. 点击最新的成功构建
3. 在"Artifacts"部分下载APK文件

## 权限

应用需要以下权限：

- `android.permission.INTERNET` - 访问互联网
- `android.permission.ACCESS_NETWORK_STATE` - 检查网络状态

## 贡献

欢迎提交问题和拉取请求。

## 许可

[MIT License](LICENSE)