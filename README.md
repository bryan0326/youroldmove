# myapp

A Flutter project for slow jogging for seniors
<br> the video demo with youtube https://www.youtube.com/watch?v=ThW5HIHt8Is
<br> the report of canva https://www.canva.com/design/DAGpxqosIQM/o_Rmc8QYIAZC07qb7HZmCQ/view?utm_content=DAGpxqosIQM&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=hbc334dbb08


## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

# 關於share_plus問題
請把\Users\使用者名稱\AppData\Local\Pub\Cache\hosted\pub.dev\share_plus-4.5.3\android\src\main\AndroidManifest.xml中的部分改掉
移除package="dev.fluttercommunity.plus.share"

# bulid.gradle問題
請在C:\Users\使用者名稱\AppData\Local\Pub\Cache\hosted\pub.dev\share_plus-4.5.3\android\build.gradle
的android中新增
namespace 'com.example.myapp'

kotlinOptions {
jvmTarget = '1.8' // 明確指定 JVM 目標版本為 1.8 (較為通用)
}
//以下不知是否需要
在C:\Users\使用者名稱\AppData\Local\Pub\Cache\hosted\pub.dev\share_plus-6.3.4\android\build.gradle
的android中新增
namespace 'dev.fluttercommunity.plus.share' // 在這裡添加 namespace
