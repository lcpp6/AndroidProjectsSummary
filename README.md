安卓开源项目总结
----

# 1、app开发
## 1.1 app 开发模板级项目
- [nowinandroid](https://github.com/android/nowinandroid): 【compose】官方积极维护、纯kotlin+compose，搭建好了基础功能。适合当学习资料或者项目启动模板（实测最新不稳定版本可能存在问题，issues已提但...）,建议使用稳定版
- [android-multi-module-demo](https://github.com/JefferyBoy/android-multi-module-demo): 【view】android安卓模块化开发最佳实践demo,其实算是老项目了（View类），可以稍微参考学习，但我更推荐上面那个（如果你想学compose的话）。
- [media-samples](https://github.com/android/media-samples)，【安卓官方媒体示例】如果尝试做媒体类安卓应用，可以参考一下...
- [MaterialPopupMenu](https://github.com/zawadz88/MaterialPopupMenu) ，【View】 显示按部分分组的 Material 弹出菜单等,特点是分组。


## 1.2 功能级别的项目
- [termux-app](https://github.com/termux/termux-app)： 【view】终端模拟器，但是开源协议是GPL，你可以使用它的 Ap 婴儿版本：[Android-Terminal-Emulator](https://github.com/jackpal/Android-Terminal-Emulator)
不建议直接使用婴儿版本，我建议是多参考类似的最新的项目，可以参考去改。
- [NeoTerm](https://github.com/NeoTerrm/NeoTerm): 【view】终端模拟器，也是GPL代码，里面部分代码也是使用上面的项目。可以参考学习。
todo:至于compose版本，我还没找到可用的...
- [compose-code-editor](https://github.com/n34t0/compose-code-editor): 【compose】代码编辑器【已经不能用】但是可以参考，其中一部分引用了 [androidx](https://github.com/androidx/androidx) 库的源码，很久很更新了（再加上compose库更新太快了），所以很多函数都废弃了，导致可能代码都跑不了了。但是如果你要开发一款compose代码编辑器，可以参考学习。
- [sora-editor](https://github.com/Rosemoe/sora-editor) 【view】代码编辑器，一个多功能的 Android 代码编辑器库。（又名 CodeEditor）
- [EditorKit](https://github.com/massivemadness/EditorKit)，【view】的代码编辑器可以参考（如果你使用View的话），它用在这个项目里面 [Squircle-CE](https://github.com/massivemadness/Squircle-CE)——————一个比较成熟的代码编辑器、文件浏览..
- [apkanalyser](https://github.com/sugood/apkanalyser)，【判断app是什么技术开发的】通过对apk包的解析，查看使用的开发框架，如：Flutter, ReactNative, Weex
- [andOTP](https://github.com/andOTP/andOTP) 【身份验证器】[未维护] Android 的开源双因素身份验证.基于时间的一次性密码 (TOTP) 和基于 HMAC 的一次性密码 (HOTP)。
- [freeotp-android](https://github.com/freeotp/freeotp-android)————【view】FreeOTP是一款双因素身份验证应用程序，适用于使用一次性密码协议的系统。只需扫描二维码即可轻松添加令牌。HOTP（基于 HMAC 的一次性密码算法）、TOTP（基于时间的一次性密码算法）。你也可以看它的改进版本：[FreeOTPPlus](https://github.com/helloworld1/FreeOTPPlus)
- [AndroidIDE](https://github.com/AndroidIDEOfficial/AndroidIDE) ，【View】，安卓app开发IDE手机端。是一个用于开发全功能 Android 应用程序的 Android IDE。
- [gkd](https://github.com/gkd-kit/gkd) ，【View】基于无障碍，高级选择器，订阅规则的自定义屏幕点击 Android 应用
- [MaterialFiles](https://github.com/zhanghai/MaterialFiles)：【View】一款开源的文件管理器，虽然是View，但是有些东西还是值得参考的...尤其是开发文件管理器...
- [AmazeFileManager](https://github.com/TeamAmaze/AmazeFileManager)，【View】，文件管理器，Android 的 Material Design 文件管理器
- [Elf-Editor](https://github.com/ha1vk/Elf-Editor) 简单的十六进制编辑器，算是老项目了...一个安卓/java算法用于编辑elf、so文件的符号名和字符串常量池，目前修改，字符串和符号名长度必须和原来一样，本算法修复hash段。现在将其开放，希望各界人士能继续完善，破除字符串修改的长度限制，这个比较麻烦。本工具对于修改二进制文件非常有用
- [storage-samples](https://github.com/android/storage-samples/tree/main) 安卓官方的存储示例程序：了解 Android 中的存储（在存储中保存文件、键值数据、共享简单数据、共享文件、打印文件、内容提供商、存储访问框架 [SAF] 等），对于开发文件管理器会有启发作用...
- [sl4a](https://github.com/damonkohler/sl4a) SL4A 将脚本语言引入 Android，允许您直接在 Android 设备上编辑和执行脚本和交互式解释器。SL4A 为 Android 引入了脚本语言，允许您直接在 Android 设备上编辑和执行脚本和交互式解释器。这些脚本可以访问成熟 Android 应用程序可用的许多 API，但界面却大大简化，让您可以轻松完成任务。
- Android功能示例工程 [ProjectX](https://github.com/AlexMofer/ProjectX): Android平台的FTP服务器。\仿微信式，平滑输入面板，防止键盘的出现与消失导致特殊输入面板的顶起与塌陷。....
- [Notes](https://github.com/MiCode/Notes) 【View】小米便签社区开源版
- [Joplin](https://github.com/laurent22/joplin) - 【View】专注于隐私的笔记应用程序，具有与 Windows、macOS、Linux、Android 和 iOS 同步功能。

- 
## 1.3 辅助工具包（util）
- [okhttp](https://github.com/square/okhttp) 网络请求- 针对 JVM、Android 和 GraalVM 的细致 HTTP 客户端。
- [EasyHttp](https://github.com/getActivity/EasyHttp): 网络请求- Android 网络请求框架，简单易用，so easy
- [okhttp-OkGo](https://github.com/jeasonlzy/okhttp-OkGo)  网络请求- OkGo - 3.0 震撼来袭，该库是基于 Http 协议，封装了 OkHttp 的网络请求框架，比 Retrofit 更简单易用，支持 RxJava，RxJava2，支持自定义缓存，支持批量断点下载管理和批量上传管理功能
- [okhttputils](https://github.com/hongyangAndroid/okhttputils) 网络请求- [停止维护]okhttp的辅助类
- [jmdns](https://github.com/jmdns/jmdns) jmDNS 库的官方网站域名解析,这是 Java 中多播 DNS 的实现。它支持服务发现和服务注册。它与 Apple 的 Bonjour 完全互操作。

- [XXPermissions](https://github.com/getActivity/XXPermissions):权限请求-Android 权限请求框架，已适配 Android 14
- [androidDataWithoutRootAPI33](https://github.com/folderv/androidDataWithoutRootAPI33) 无需 root 权限即可在 Android 13 上读写 Android/数据文件
- [AndroidDirectoryAccess](https://github.com/Aghajari/AndroidDirectoryAccess) 无需 root 即可获取 Android/{data,obb} 目录访问权限的简单项目，适用于 Android >= 11。（支持所有版本的 Android）
- 
- [Shizuku-API](https://github.com/RikkaApps/Shizuku-API) Shizuku 和 Sui 的 API 和开发者指南。
- [Shizuku](https://github.com/RikkaApps/Shizuku):普通应用程序直接使用具有 adb/root 权限的系统 API。
- [Sui](https://github.com/RikkaApps/Sui) Android 上的现代超级用户界面实现。
  
-  root-[libsu](https://github.com/topjohnwu/libsu):针对使用 root 权限的应用程序的完整解决方案
- [accompanist](https://github.com/google/accompanist): 【compose】-辅助工具库-官方开源的，目前很多都已经融合进compose一些内部库了，目前最常用的是它的权限处理部分。
- [android-common](https://github.com/litesuits/android-common)：工具类-比较老的工具类了，可以学习参考。其中包括bitmap处理，文件操作，加密存储器，shell命令，静默安装，计数器，均值器，吐司，日志，校验，提示，网络监测等基础功能，以及一些Base64、MD5、Hex、Byte、Number、Dialog、Filed、Class、Package、Telephone、Random等工具类。
- [AndroidUtilCode](https://github.com/Blankj/AndroidUtilCode),工具类-非常全面，近期也有在更新，可以学习参考...
- [okio](https://github.com/square/okio),文件系统级别的库-适用于 Android、Java 和 Kotlin Multiplatform 的现代 I/O 库。没深入使用过，浅浅使用了一下，感觉还行。优势是kotlin、并且低版本使用 Java.io,高版本使用Java.nio。。。
- [dav4jvm](https://github.com/bitfireAT/dav4jvm):网络存储-WebDAV/CalDAV/CardDAV 库————Java 虚拟机 (Java/Kotlin) 的 WebDAV（包括 CalDAV、CardDAV）库
- [sardine-android](https://github.com/thegrizzlylabs/sardine-android) 适用于 Android 的 WebDAV 库
- [sshj](https://github.com/hierynomus/sshj) ：网络存储-java 的 ssh、scp 和 sftp
- [jcifs](https://github.com/codelibs/jcifs) ：网络存储-CIFS 是一个开源客户端库，它 100% 用 Ja​​va 实现 CIFS/SMB 网络协议。从 2.x 版开始，该项目从jcifs-ng分叉，现有的 jcifs 代码合并为smb1。
- [jcifs-ng](https://github.com/AgNO3/jcifs-ng): 网络存储-jCIFS 库的清理和改进版本.SMB2（2.02 协议级别）支持，部分 SMB3 支持

- [commons-net](https://github.com/apache/commons-net)，网络存储-Apache Commons Net 库包含一组网络实用程序和协议实现。支持的协议包括 Echo、Finger、FTP、NNTP、NTP、POP3(S)、SMTP(S)、Telnet 和 Whois。
- [samba](https://github.com/dperson/samba)，网络存储-——————自 1992 年以来，Samba 为所有使用 SMB/CIFS 协议的客户端（例如所有版本的 DOS 和 Windows、OS/2、Linux 等）提供安全、稳定、快速的文件和打印服务。

- [7-Zip-JBinding-4Android](https://github.com/omicronapps/7-Zip-JBinding-4Android) 压缩 -7z 归档引擎的 Android Java 包装器----本机（JNI）跨平台库，用于提取（受密码保护，多部分）7z Arj BZip2 Cab Chm Cpio Deb GZip HFS Iso Lzh Lzma Nsis Rar Rpm Split Tar Udf Wim Xar Z Zip 档案并在 Android 上从 Java 创建 7z、Zip、Tar、GZip 和 BZip2。
-  [zip4j](https://github.com/srikanth-lingala/zip4j) 压缩-Zip4j - 用于 zip 文件/流的 Java 库。唯一支持 zip 加密的 Java 库。
- [commons-compress](https://github.com/apache/commons-compress) 压缩- Apache Commons Compress 定义了用于处理压缩和存档格式的 API。这些格式包括 bzip2、gzip、pack200、LZMA、XZ、Snappy、传统 Unix Compress、DEFLATE、DEFLATE64、LZ4、Brotli、Zstandard 以及 ar、cpio、jar、tar、zip、dump、7z、arj。
- [commons-text](https://github.com/apache/commons-text)  Apache Commons Text 是一组实用函数和可重用组件，用于处理和操作在 Java 环境中使用的文本
- [commons-io](https://github.com/apache/commons-io)  Apache Commons IO 库包含实用程序类、流实现、文件过滤器、文件比较器、字节序转换类等等。
- [java-diff-utils](https://github.com/java-diff-utils/java-diff-utils) Diff Utils 库是一个开源库，用于执行文本或某种数据之间的比较/差异操作：计算差异、应用补丁、生成统一差异或解析它们、生成差异输出以便于将来显示（如并排视图）等等。

- [guava](https://github.com/google/guava) Guava：Google 的 Java 核心库。Guava 是 Google 的一组核心 Java 库，其中包括新的集合类型（例如多映射和多集）、不可变集合、图库以及并发、I/O、哈希、原语、字符串等实用程序！它在 Google 的大多数 Java 项目中得到广泛使用，并且也被许多其他公司广泛使用。
- [jregex](https://github.com/eropple/jregex) jregex 库的 Mavenized 版本。正则表达式
- [trilead-ssh2](https://github.com/jenkinsci/trilead-ssh2) Jenkins 中使用的修补 trilead-ssh2
- [FFmpeg-Android](https://github.com/bravobit/FFmpeg-Android) FFMpeg/FFprobe 针对 Android 编译。在您的 Android 项目中轻松执行 FFmpeg 和 FFprobe 命令。

- [zxing](https://github.com/zxing/zxing) 适用于 Java、Android 的 ZXing（“斑马线”）条形码扫描库.项目仅处于维护模式；条形码扫描仪不可用.它不适用于 Android 14，不会更新。请不要为其提交问题。
- [ZXingLite](https://github.com/jenly1314/ZXingLite):扫码二维码-ZXing的精简极速版，优化扫码和生成二维码/条形码，内置闪光灯等功能。扫描风格支持：微信的线条样式，支付宝的网格样式。几句代码轻松拥有扫码功能 ，ZXingLite让集成更简单。（扫码识别速度快如微信）
- AndroidSVG-[androidsvg](https://github.com/BigBadaboom/androidsvg)适用于 Android 的 SVG 渲染库——————没用过，不清楚
- [material-color-utilities](https://github.com/material-foundation/material-color-utilities)Material You 的颜色库，你可以在里面找到一些常用的颜色工具，进行颜色方面的工具开发....

- [Fresco](https://github.com/facebook/fresco) 是一个用于在 Android 应用程序中显示图像的强大的系统。Fresco 负责图片的加载和显示，因此您无需自己处理。它会从网络、本地存储或本地资源加载图片，并显示占位符，直到图片到达。它有两级缓存；一个在内存中，另一个在内部存储中。
- [coil](https://github.com/coil-kt/coil)适用于 Android 和 Compose Multiplatform 的图像加载(也有视频扩展库，但好像没有音频...)。
- [glide](https://github.com/bumptech/glide) 专注于平滑滚动的 Android 图像加载和缓存库。快速高效的 Android 开源媒体管理和图像加载框架，它将媒体解码、内存和磁盘缓存以及资源池整合到一个简单易用的界面中
- [3DObjectViewer](https://github.com/lrusso/3DObjectViewer) 安卓 3D 对象查看器 ——————STL、OBJ 和 3DS 格式的 3D 对象查看器，具有重量、尺寸、体积、成本和打印时间功能
- [TinyPinyin](https://github.com/promeG/TinyPinyin) 适用于Java和Android的快速、低内存占用的汉字转拼音库。
- [retrofit](https://github.com/square/retrofit) 适用于 Android 和 JVM 的类型安全 HTTP 客户端.
- [lottie-android](https://github.com/airbnb/lottie-android) 安卓动画库lottie 
- [android-gif-drawable](https://github.com/koral--/android-gif-drawable) Views 以及DrawableAndroid 中的动画 GIF。--- 通过 JNI 捆绑的 GIFLib 用于渲染帧。这种方式应该比WebView或Movie类更有效。
- [DanmakuFlameMaster](https://github.com/bilibili/DanmakuFlameMaster)，Android开源弹幕引擎·烈焰弹幕使 ～ 
  

## 1.4 compose组件
- [UltraSwipeRefresh](https://github.com/jenly1314/UltraSwipeRefresh)：下拉刷新-一个可带来极致体验的Compose刷新组件；支持下拉刷新和上拉加载，可完美替代官方的SwipeRefresh；并且支持的功能更多，可扩展性更强。
- [Fragula](https://github.com/massivemadness/Fragula)：滑动页面导航动画-Fragula 是 Android 导航组件库的滑动关闭扩展
- [compose-swipeBox](https://github.com/KevinnZou/compose-swipeBox)：可滑动列表项-通过 anchoredDraggable 实现的 Jetpack Compose 可滑动列表项（具有定向滑动操作）
- [ComposeViews](https://github.com/ltttttttttttt/ComposeViews)： 一些常用组件-在 Android、Web、桌面和 iOS 中编写多平台视图：寻呼机、横幅、指示器、刷新布局、流程布局、菜单浮动操作按钮、下拉刷新、链式滚动组件、可滚动应用栏（嵌套滚动视图）、日期选择器（时间选择器日期选择器）、滑动关闭、图像查看器、缩放布局、星形栏等
- [bonsai](https://github.com/adrielcafe/bonsai)：树形组件-，包含电池的 Jetpack Compose 树形视图
- [Reorderable](https://github.com/Calvin-LL/Reorderable)： 拖动排序-，通过拖放操作重新排序 Jetpack Compose 和 Compose Multiplatform 中列表和网格中的项目。体验过，但是当时我试了到我的手机上有一些bug就没再用，有时间可以研究一下，以下是我当时的使用报告：在测试 LazyList 之类的高级Api，会出现以下问题：
    1、按下拖动的时候目标块消失。怀疑是zIndex的问题，但是尝试修改该属性无效。
        怀疑是 新版的 LazyItem 的Scop 和普通（以及以前的）布局不一样，所以zIndex在其中作用失效
        也就是新的Lazy的Item域的布局方式可能以及不支持 提供zIndex 来控制绘图顺序。
    2、但是使用 ReorderableColumn 不会出现此问题（也就是普通的布局不会出现这种绘图顺序错乱的情况）
  
- [compose-markdown](https://github.com/jeziellago/compose-markdown)适用于 Android Jetpack Compose 的 Markdown 文本 📋。
- compose官方示例集 [compose-samples](https://github.com/android/compose-samples)

- 
## 1.5 compose多平台（跨端）
-  [compose-multiplatform](https://github.com/JetBrains/compose-multiplatform)，官方示例库-包含了一些官方写的婴儿级别的库。compose跨端开发的梦开始的地方...xxx...
-  compose桌面端的反编译集成-[ApkNurse](https://github.com/vsloong/ApkNurse)，一个集成了反编译工具的compose桌面端，可以简单参考一下。


## 1.6 插件化
- [VirtualAPK](https://github.com/didi/VirtualAPK)：插件框架- 滴滴开源的插件化开发框架，很老了，停留在安卓9
- [Android-Plugin-Framework](https://github.com/limpoxe/Android-Plugin-Framework)  (近期更新)Android插件框架，免安装运行插件APK ，支持独立插件和非独立插件
- [RePlugin](https://github.com/Qihoo360/RePlugin) (近期更新)一个灵活，稳定，易于使用的Android插件框架,360开源的一个插件开发框架

# 2、app逆向
- [smali](https://github.com/JesusFreke/smali) smali/baksmali 是 dalvik（Android 的 Java VM 实现）使用的 dex 格式的汇编器/反汇编
- [Apktool](https://github.com/iBotPeaches/Apktool)  Apktool 是一款用于对第三方、封闭、二进制 Android 应用进行逆向工程的工具。它可以将资源解码为接近原始形式，并在进行一些修改后重建它们；它可以逐步调试 smali 代码。由于具有类似项目的文件结构和一些重复任务（例如构建 apk 等）的自动化，它还可以更轻松地使用应用。

- [Jadx](https://github.com/skylot/jadx): Java反编译器...
- [ArscEditor](https://github.com/MrIkso/ArscEditor) 带有 GUI 的 resources.arsc 开源编辑器。没用过，不知道具体效果。单纯记录一下。
- [Recaf](https://github.com/Col-E/Recaf)现代 Java 字节码编辑器。MIT协议。
- [Threadtear](https://github.com/GraxCode/threadtear) 是一款多功能的 Java 反混淆工具。
- [APKiD](https://github.com/rednaga/APKiD)提供有关 APK 制作方式的信息。它可以识别许多编译器、打包程序、混淆器和其他奇怪的东西。它是Android 版PEiD 。安卓应用程序识别器，用于识别加壳程序、保护程序、混淆程序和异常程序 - PEiD for Android
- [simplify](https://github.com/CalebFenton/simplify)  Android虚拟机和反混淆器
- [jd-gui](https://github.com/java-decompiler/jd-gui)    独立的图形实用程序，可显示“.class”文件的 Java 源代码。您可以使用 JD-GUI 浏览重建的源代码，以便即时访问方法和字段。
- [jd-core](https://github.com/java-decompiler/jd-core)关于:JD-Core是一个用JAVA编写的JAVA反编译器。
- [procyon](https://github.com/mstrobel/procyon)Procyon 是一套 Java 元编程工具，包括丰富的反射 API、用于运行时代码生成的 LINQ 启发的表达式树 API 和 Java 反编译器。
- [GDA-android-reversing-Tool](https://github.com/charles2gan/GDA-android-reversing-Tool)  最快、最强大的 APK、DEX、ODEX、OAT、JAR、AAR 和 CLASS 文件的 Android 反编译器（无需 Java VM 即可运行的本机工具）。支持恶意行为检测、隐私泄露检测、漏洞检测、路径解析、加壳器识别、变量跟踪、反混淆、python 和 java 脚本、设备内存扩展……
- [LLM4Decompile](https://github.com/albertan017/LLM4Decompile)  逆向工程：使用大型语言模型反编译二进制代码
- [frida-dexdump](https://github.com/hluwa/frida-dexdump)  frida-dexdump是一个frida工具，用于在内存中查找和转储dex，以支持安全工程师分析恶意软件。
- [anti-emulator](https://github.com/strazzere/anti-emulator)  Android 反模拟器  ,没研究，不知道是啥，看着很秀就先收藏了...)

- [cfr](https://github.com/leibnitz27/cfr)-----另一个 Java 反编译器 \o/
- [fernflower](https://github.com/fesh0r/fernflower) FernFlower Java 反编译器的非官方镜像(Java 分析反编译器)
- [uber-apk-signer](https://github.com/patrickfav/uber-apk-signer) 一个 CLI 工具，可帮助使用调试或提供的发布证书对单个或多个 Android 应用程序包 (APK) 进行签名和压缩对齐。它支持 v1、v2 和 v3 v4 Android 签名方案，具有嵌入式调试密钥库，并在签名后自动验证。
- [APK-Explorer-Editor](https://github.com/apk-editor/APK-Explorer-Editor)APK Explorer & Editor (AEE) 的源代码，一个用于探索已安装 APK 内容的开源工具！
- [kstools](https://github.com/fourbrother/kstools)Android中自动爆破签名工具
- [ghidra](https://github.com/NationalSecurityAgency/ghidra)Ghidra 软件逆向工程框架
- [radare2](https://github.com/radareorg/radare2) 类似 UNIX 的逆向工程框架和命令行工具集
- [TweakMe](https://github.com/liaoguobao/TweakMe) android免root native层与java层注入框架
- [APKEditor](https://github.com/REAndroid/APKEditor),强大的 android apk 编辑器 - aapt/aapt2 独立——————该工具使用[ARSCLib](https://github.com/REAndroid/ARSCLib)编辑任意apk资源，有六大主要功能
- [ARSCLib](https://github.com/REAndroid/ARSCLib)  Android 二进制资源读取/写入 java 库————该库基于 androidfw/ResourceTypes.h 的 AOSP 结构开发，完全替代 aapt/aapt2
- [sandhook-docs](https://github.com/AlienwareHe/sandhook-docs) 了解 sandhook 的工作原理.Android ART 钩子\原生内联钩子
- [xHook](https://github.com/githubXiaowangzi/xHook)———————— [xHook](https://github.com/iqiyi/xHook) 是一个针对 Android 原生 ELF（可执行和共享库）的 PLT（Procedure Linkage Table）钩子库。
- [android-arscblamer](https://github.com/google/android-arscblamer) 解析 Android 应用程序的 resources.arsc 文件并提取有关其内容的有用、可操作的信息。
- [LSPlant](https://github.com/LSPosed/LSPlant) LSPlant 是一个 Android ART 钩子库，提供 Java 方法钩子/解除钩子和内联去优化。该项目是 GNU 宽通用公共许可证下的 LSPosed 框架的一部分。
- [dex-editor](https://github.com/aNNiMON/dex-editor) dex编辑器...
- [dex2jar](https://github.com/pxb1988/dex2jar)  处理 android .dex 和 java .class 文件的工具
dex-reader/writer：读取/写入 Dalvik 可执行文件 (.dex)。它具有与 ASM 类似的轻量级 API。
d2j-dex2jar：将 .dex 文件转换为 .class 文件（压缩为 jar）
smali/baksmali：将 dex 反汇编为 smali 文件并从 smali 文件组装 dex。与smali/baksmali的实现不同，语法相同，但我们支持类型 desc“Lcom/dex2jar\t\u1234;”中的转义。
其他工具： d2j-decrypt-string

- [DeveloperHelper](https://github.com/WrBug/DeveloperHelper) 📌易开发是一款帮助开发人员快速开发的工具，功能包括界面分析，页面信息，加固脱壳，支持Android9.0.目前软件尚未完成，更多功能完善中


# 3、app保护
- [fakedirectory](https://github.com/x4e/fakedirectory): 虚假目录构建状态-欺骗 WinRAR、JD-GUI 和几乎所有 zip 文件阅读器。
- [fakedirectory](https://github.com/lcpp-nt/fakedirectory)：混淆-使用由 cts 和 bibl 设计的 MapleIR 框架的公共概念验证混淆器，据说是最有前途的混淆器
- [radon](https://github.com/ItzSomebody/radon)：混淆器- [废弃] Scuffed Java 字节码混淆器。我主要看中了他在里面写的推荐。
- [AndResGuard](https://github.com/shwenzhang/AndResGuard):资源混淆- 微信团队为 Android 提供的 proguard 资源.类似于ProGuardJava源代码，但只针对资源文件。
- [dProtect](https://github.com/open-obfuscator/dProtect): java、kotlin混淆-dProtect 是一款基于 Proguard 的 Java 和 Kotlin 混淆器。特点是支持 kotlin ————相当于 Proguard 的kotlin 兼容版？
- [ProGuard](https://github.com/Guardsquare/proguard)：Java混淆：，Java 优化器和混淆器
- [obfuscator](https://github.com/obfuscator-llvm/obfuscator) llvm4混淆器：
- [StringFog](https://github.com/MegatronKing/StringFog): 字符串加密：一款自动对字节码中的字符串进行加密Android插件工具
- [dexguard](https://github.com/Ivonhoe/dexguard)Android app防dex2jar的gradle插件——————美团如何预防dex2jar————issue：无语然并卵。。。。jadx-gui一览无余 #5
- [genuine](https://github.com/brevent/genuine)一个模块反Xposed钩子，反假签名，反虚拟应用程序（binder代理），以及可选的反odex，反覆盖。自 2019-03 起，Genuine 已转为使用纯 c 来隐藏自身。如果您想隐藏包名称和/或类名称，请联系我，或者像fill_XXX在 中一样进行操作genuine.c。
- [dcc](https://github.com/amimo/dcc)DCC（Dex-to-C Compiler）是一种基于方法的aot编译器，可以将DEX代码转换为C代码。
- [FreeReflection](https://github.com/tiann/FreeReflection) 一个让你在 Android P （包括 Q 和 R）以上不受任何限制地使用反射的库
- [Dobby](https://github.com/jmpews/Dobby) 一个轻量级、多平台、多架构的钩子框架。Dobby 是一个轻量级、多平台、多架构的漏洞挂钩框架。
- [obfuscator](https://github.com/heroims/obfuscator) ollvm混淆器，基于 llvm-clang 5.0.2, 6.0.1 , 7.0.1,8.0,9.0,9.0.1,10.x,11.x,12.x,13.x,14.x,swift-llvm-clang 5.0,swift-llvm-clang 5.5
- [zipalign-java](https://github.com/iyxan23/zipalign-java) zip对齐的纯Java工具 
- [Obfuscapk](https://github.com/ClaudiuGeorgiu/Obfuscapk)一种用于 Android 应用程序的自动混淆工具，采用黑盒方式工作，支持高级混淆功能，并具有可通过新技术轻松扩展的模块化架构.一个模块化 Python 工具，用于对 Android 应用进行混淆处理，无需源代码
- [paranoid](https://github.com/MichaelRocks/paranoid)  Android 应用程序的字符串混淆器。
- [BlackObfuscator](https://github.com/CodingGay/BlackObfuscator) Black Obfuscator 是一款针对Android APK DexFile的混淆器，它可以帮助开发人员通过控制流平坦化来保护源代码，并使分析实际的程序控制流变得困难。
- [VMProtect-devirtualization](https://github.com/JonathanSalwan/VMProtect-devirtualization) 使用 VMProtect 软件保护。使用符号执行和 LLVM 自动反混淆纯函数。一种实验性的动态方法，用于对受VMProtect 3.x保护的纯函数进行去虚拟化
- [nmmp](https://github.com/maoabc/nmmp) 基于dex-vm运行dalvik字节码从而对dex进行保护，增加反编译索引。项目分成两部分nmm-protect是纯java项目，对dex进行转换，把dex里数据转为c结构体，opcode随机化生成ndk项目，编译后生成后的apk。nmmvm是一个安卓项目，包含dex-vm实现及各种dalvik指令的测试等。
- [dpt-shell](https://github.com/luoyesiqiu/dpt-shell) 一个android Dex保护壳的实现(将dex文件中的函数代码抽空，然后在程序运行时将函数代码填回的那么一个shell。)
- [LSPatch](https://github.com/LSPosed/LSPatch) LSPatch：从 LSPosed 扩展而来的非 root Xposed 框架___LSPosed框架的无root实现，通过将dex等插入到目标APK中来集成Xposed API。
- [native-obfuscator](https://github.com/radioegor146/native-obfuscator)用于 JNI 的 Java .class 到 .cpp 转换器
- 

# 4、Flutter（x）
- [animated_tree_view](https://github.com/embraceitmobile/animated_tree_view) ，树视图-,效果看起来不错，但是我已经不 Flutter 了，我希望 compose 取代 Flutter！：）
- Flutter的终端模拟器-[xterm.dart](https://github.com/TerminalStudio/xterm.dart)
- Flutter 状态管理框架 [getx](https://github.com/jonataslaw/getx)，我还是挺推荐的，虽然已经不打算做Flutter了...
- Flutter 应用逆向...[reflutter](https://github.com/Impact-I/reFlutter)

# 5 机器学习、AI相关
- [course](https://github.com/huggingface/course) 创建Hugging Face 课程的内容。本课程将教您如何将 Transformers 应用于自然语言处理及其他领域的各种任务。在此过程中，您将学习如何使用Hugging Face生态系统 — 🤗 Transformers、🤗 Datasets、🤗 Tokenizers和🤗 Accelerate — 以及Hugging Face Hub。它完全免费且开源！
- [tensorflow](https://github.com/tensorflow/tensorflow)适合每个人的开源机器学习框架.一个端到端的机器学习开源平台。它拥有一个全面、灵活的 工具、 库和 社区资源生态系统，让研究人员能够推动机器学习的最新发展，让开发者能够轻松构建和部署由机器学习驱动的应用程序。
- [pytorch](https://github.com/pytorch/pytorch) 具有强大 GPU 加速的 Python 张量和动态神经网络.PyTorch 是一个 Python 包，提供两个高级功能：具有强大 GPU 加速的张量计算（如 NumPy）\基于磁带自动分级系统构建的深度神经网络
- [ChatGLM3](https://github.com/THUDM/ChatGLM3) 开源双语对话语言模型--清华大学
- [OpenChat](https://github.com/imoneoi/openchat) 是一个创新的开源语言模型库，通过C-RLFT进行微调- 一种受离线强化学习启发的策略。利用不完善的数据推进开源语言模型
- [transformers](https://github.com/huggingface/transformers) 适用于 Pytorch、TensorFlow 和 JAX 的最先进的机器学习.Transformers 提供数千个预训练模型，用于执行文本、视觉和音频等不同模态的任务。
- [Coursera-ML-AndrewNg-Notes](https://github.com/fengdu78/Coursera-ML-AndrewNg-Notes) 吴恩达老师的机器学习课程个人笔记 


# 其他
- 一个安卓UI总结库，比我总结的多得多了(虽然经典但大多都是view)：[awesome-android-ui](https://github.com/wasabeef/awesome-android-ui)
- 《安卓逆向这档事》视频系列————正己吾爱教程.... [AndroidReverse](https://github.com/ZJ595/AndroidReverse)
- [kotlin-in-chinese](https://github.com/huanglizhuo/kotlin-in-chinese)kotlin 官方文档翻译
- 谷歌官方- [ksp](https://github.com/google/ksp)，一般用在安卓grade里面的Kotlin 符号处理 API
- Android 单元测试框架 [robolectric](https://github.com/robolectric/robolectric):  Android 的行业标准单元测试框架。借助 Robolectric，您的测试可以在 JVM 内的模拟 Android 环境中运行，而无需担心模拟器的开销和不稳定问题。Robolectric 测试的运行速度通常比冷启动模拟器上的测试快 10 倍。
Robolectric 支持为14 个不同版本的 Android运行单元测试，范围从 Lollipop（API 级别 21）到 U（API 级别 34）。
- 屏幕截图测试-[roborazzi](https://github.com/takahirom/roborazzi)：我关注他的原因是在 [nowinandroid](https://github.com/android/nowinandroid) 里面用。
- 编程工具的增量解析系统，[tree-sitter](https://github.com/tree-sitter/tree-sitter),Tree-sitter 是一个解析器生成器工具和增量解析库。它可以为源文件构建具体的语法树，并在编辑源文件时高效地更新语法树
- KIMI AI 免费 服务 [kimi-free-api](https://github.com/LLM-Red-Team/kimi-free-api)
-  [slf4j](https://github.com/qos-ch/slf4j)  Java 的简单日志外观 (SLF4J) 作为各种日志框架 (例如 java.util.logging、logback、reload4j、log4j 2.x、logevents、penna、rainbowgum、tinylog) 的简单外观或抽象，允许最终用户在部署时插入所需的日志框架。

- 小米开源的内核源码-[Xiaomi_Kernel_OpenSource](https://github.com/MiCode/Xiaomi_Kernel_OpenSource)
- NotePad++ 开源 [notepad-plus-plus](https://github.com/notepad-plus-plus/notepad-plus-plus)

- [simpleC](https://github.com/luoyesiqiu/simpleC) 安卓平台 C、C++ 编程工具
- [XQCEditor](https://github.com/wangchen11/XQCEditor) 安卓平台 C、C++ 编程工具

- 开源协议一览 [licenses](https://github.com/phodal/licenses)









