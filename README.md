安卓开源项目总结
----

# 1、app开发
## 1.1 app 开发模板级项目
- compose——[nowinandroid](https://github.com/android/nowinandroid): 官方积极维护、纯kotlin+compose，搭建好了基础功能。适合当学习资料或者项目启动模板（实测最新不稳定版本可能存在问题，issues已提但...）,建议使用稳定版
- view——[android-multi-module-demo](https://github.com/JefferyBoy/android-multi-module-demo): android安卓模块化开发最佳实践demo,其实算是老项目了（View类），可以稍微参考学习，但我更推荐上面那个（如果你想学compose的话）。
- 安卓官方媒体示例-[media-samples](https://github.com/android/media-samples)，如果尝试做媒体类安卓应用，可以参考一下...


## 1.2 功能级别的项目
- view终端模拟器——[termux-app](https://github.com/termux/termux-app)： 终端模拟器，但是开源协议是GPL，你可以使用它的 Ap 婴儿版本：[Android-Terminal-Emulator](https://github.com/jackpal/Android-Terminal-Emulator)
不建议直接使用婴儿版本，我建议是多参考类似的最新的项目，可以参考去改。
- view终端模拟器——[NeoTerm](https://github.com/NeoTerrm/NeoTerm): 终端模拟器，也是GPL代码，里面部分代码也是使用上面的项目。可以参考学习。
todo:至于compose版本，我还没找到可用的...
- compose代码编辑器【已经不能用】[compose-code-editor](https://github.com/n34t0/compose-code-editor): 但是可以参考，其中一部分引用了 [androidx](https://github.com/androidx/androidx) 库的源码，很久很更新了（再加上compose库更新太快了），所以很多函数都废弃了，导致可能代码都跑不了了。但是如果你要开发一款compose代码编辑器，可以参考学习。
- view的代码编辑器-[EditorKit](https://github.com/massivemadness/EditorKit)，可以参考（如果你使用View的话），它用在这个项目里面 [Squircle-CE](https://github.com/massivemadness/Squircle-CE)——————一个比较成熟的代码编辑器、文件浏览..
- 判断app是什么技术开发的-[apkanalyser](https://github.com/sugood/apkanalyser)通过对apk包的解析，查看使用的开发框架，如：Flutter, ReactNative, Weex
- 身份验证器-[andOTP](https://github.com/andOTP/andOTP)[未维护] Android 的开源双因素身份验证.基于时间的一次性密码 (TOTP) 和基于 HMAC 的一次性密码 (HOTP)。
- view应用————身份验证器OTP[freeotp-android](https://github.com/freeotp/freeotp-android)————FreeOTP是一款双因素身份验证应用程序，适用于使用一次性密码协议的系统。只需扫描二维码即可轻松添加令牌。HOTP（基于 HMAC 的一次性密码算法）、TOTP（基于时间的一次性密码算法）。你也可以看它的改进版本：[FreeOTPPlus](https://github.com/helloworld1/FreeOTPPlus)
- View-安卓app开发IDE手机端[AndroidIDE](https://github.com/AndroidIDEOfficial/AndroidIDE) 是一个用于开发全功能 Android 应用程序的 Android IDE。
- 

- 
## 1.3 辅助工具包（util）
- 网络请求- [EasyHttp](https://github.com/getActivity/EasyHttp): Android 网络请求框架，简单易用，so easy
- 权限请求-[XXPermissions](https://github.com/getActivity/XXPermissions):Android 权限请求框架，已适配 Android 14
-  root-[libsu](https://github.com/topjohnwu/libsu):针对使用 root 权限的应用程序的完整解决方案
- compose-辅助工具库-[accompanist](https://github.com/google/accompanist): 官方开源的，目前很多都已经融合进compose一些内部库了，目前最常用的是它的权限处理部分。
- 工具类-[android-common](https://github.com/litesuits/android-common)：比较老的工具类了，可以学习参考。其中包括bitmap处理，文件操作，加密存储器，shell命令，静默安装，计数器，均值器，吐司，日志，校验，提示，网络监测等基础功能，以及一些Base64、MD5、Hex、Byte、Number、Dialog、Filed、Class、Package、Telephone、Random等工具类。
- 文件系统级别的库-[okio](https://github.com/square/okio),适用于 Android、Java 和 Kotlin Multiplatform 的现代 I/O 库。没深入使用过，浅浅使用了一下，感觉还行。优势是kotlin、并且低版本使用 Java.io,高版本使用Java.nio。。。
- 网络存储-[dav4jvm](https://github.com/bitfireAT/dav4jvm):WebDAV/CalDAV/CardDAV 库————Java 虚拟机 (Java/Kotlin) 的 WebDAV（包括 CalDAV、CardDAV）库
- 网络存储-[sshj](https://github.com/hierynomus/sshj) ：java 的 ssh、scp 和 sftp
- 
- 扫码二维码-[ZXingLite](https://github.com/jenly1314/ZXingLite):ZXing的精简极速版，优化扫码和生成二维码/条形码，内置闪光灯等功能。扫描风格支持：微信的线条样式，支付宝的网格样式。几句代码轻松拥有扫码功能 ，ZXingLite让集成更简单。（扫码识别速度快如微信）
- AndroidSVG-[androidsvg](https://github.com/BigBadaboom/androidsvg)适用于 Android 的 SVG 渲染库——————没用过，不清楚
- [material-color-utilities](https://github.com/material-foundation/material-color-utilities)Material You 的颜色库，你可以在里面找到一些常用的颜色工具，进行颜色方面的工具开发....
- 

## 1.4 compose组件
- 下拉刷新-[UltraSwipeRefresh](https://github.com/jenly1314/UltraSwipeRefresh)：一个可带来极致体验的Compose刷新组件；支持下拉刷新和上拉加载，可完美替代官方的SwipeRefresh；并且支持的功能更多，可扩展性更强。
- 滑动页面导航动画-[Fragula](https://github.com/massivemadness/Fragula)：Fragula 是 Android 导航组件库的滑动关闭扩展
-  可滑动列表项-[compose-swipeBox](https://github.com/KevinnZou/compose-swipeBox)：通过 anchoredDraggable 实现的 Jetpack Compose 可滑动列表项（具有定向滑动操作）
-  一些常用组件 [ComposeViews](https://github.com/ltttttttttttt/ComposeViews)：在 Android、Web、桌面和 iOS 中编写多平台视图：寻呼机、横幅、指示器、刷新布局、流程布局、菜单浮动操作按钮、下拉刷新、链式滚动组件、可滚动应用栏（嵌套滚动视图）、日期选择器（时间选择器日期选择器）、滑动关闭、图像查看器、缩放布局、星形栏等
- 树形组件-[bonsai](https://github.com/adrielcafe/bonsai)：包含电池的 Jetpack Compose 树形视图
- 拖动排序-[Reorderable](https://github.com/Calvin-LL/Reorderable)： 通过拖放操作重新排序 Jetpack Compose 和 Compose Multiplatform 中列表和网格中的项目。体验过，但是当时我试了到我的手机上有一些bug就没再用，有时间可以研究一下
- 

- 
## 1.5 compose多平台（跨端）
-  官方示例库[compose-multiplatform](https://github.com/JetBrains/compose-multiplatform)，包含了一些官方写的婴儿级别的库。compose跨端开发的梦开始的地方...xxx...
-  compose桌面端的反编译集成-[ApkNurse](https://github.com/vsloong/ApkNurse)，一个集成了反编译工具的compose桌面端，可以简单参考一下。



## 1.6 插件化
- 插件框架- [VirtualAPK](https://github.com/didi/VirtualAPK)：滴滴开源的插件化开发框架，很老了，停留在安卓9
- 

# 2、app逆向


# 3、app保护
- 虚假目录构建状态-[fakedirectory](https://github.com/x4e/fakedirectory): 欺骗 WinRAR、JD-GUI 和几乎所有 zip 文件阅读器。
- 混淆-[fakedirectory](https://github.com/lcpp-nt/fakedirectory)：使用由 cts 和 bibl 设计的 MapleIR 框架的公共概念验证混淆器，据说是最有前途的混淆器
-  混淆器- [radon](https://github.com/ItzSomebody/radon)：[废弃] Scuffed Java 字节码混淆器。我主要看中了他在里面写的推荐。
- 资源混淆- [AndResGuard](https://github.com/shwenzhang/AndResGuard):微信团队为 Android 提供的 proguard 资源.类似于ProGuardJava源代码，但只针对资源文件。
- java、kotlin混淆-[dProtect](https://github.com/open-obfuscator/dProtect): dProtect 是一款基于 Proguard 的 Java 和 Kotlin 混淆器。特点是支持 kotlin ————相当于 Proguard 的kotlin 兼容版？
- Java混淆：[ProGuard](https://github.com/Guardsquare/proguard)：，Java 优化器和混淆器
- 字符串加密：[StringFog](https://github.com/MegatronKing/StringFog):一款自动对字节码中的字符串进行加密Android插件工具


# 4、Flutter
- 树视图-[animated_tree_view](https://github.com/embraceitmobile/animated_tree_view),效果看起来不错，但是我已经不碰 Flutter 了，我希望 compose 取代 Flutter！：）
- Flutter的终端模拟器-[xterm.dart](https://github.com/TerminalStudio/xterm.dart)
- Flutter 状态管理框架 [getx](https://github.com/jonataslaw/getx)，我还是挺推荐的，虽然已经不打算做Flutter了...
- 

# 其他
- 谷歌官方- [ksp](https://github.com/google/ksp)，一般用在安卓grade里面的Kotlin 符号处理 API
- 屏幕截图测试-[roborazzi](https://github.com/takahirom/roborazzi)：我关注他的原因是在 [nowinandroid](https://github.com/android/nowinandroid) 里面用。
- 编程工具的增量解析系统，[tree-sitter](https://github.com/tree-sitter/tree-sitter),Tree-sitter 是一个解析器生成器工具和增量解析库。它可以为源文件构建具体的语法树，并在编辑源文件时高效地更新语法树
- 
