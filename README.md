# -
网络通信
　　1、ASIHTTPRequest
　　这是一个经典的老库，功能完全而强大，但已经停止更新很久了(iOS5.0停止更新，但是我最近看github上这个项目有新改动)。在不同iOS版本上略微有一些小问题(提醒显示上的)，所以用的时候还是稍微修改一下比较好。
　　下载地址：https://github.com/pokeb/asi-http-request

　　2、AFNetworking
　　轻量级的通讯类库，使用非常简单。
　　下载地址：https://github.com/AFNetworking/AFNetworking
　　3、MKNetworkKit
　　最近做的不错的一个通讯类库，具有AFNetworking和ASIHTTPRequest双方的优点，甚至功能更丰富一些，但是本人还没有使用过。
　　下载地址：https://github.com/MugunthKumar/MKNetworkKit
　　Socket
　　1、CocoaAsyncSocket
　　CocoaAsyncSocket是用的最广泛的socket开发库，省略了程序员与CFNetwork接触的时间，延长了程序员寿命。
　　下载地址：https://github.com/robbiehanson/CocoaAsyncSocket
　　2、SocketRocket
　　SocketRocket是Square开发的一个实现webSocket的库，可以轻松的实现即时通信。
　　下载地址：https://github.com/square/SocketRocket
　　数据解析
　　1、SBJSON
　　SBJson的解析速度其实是比较慢的，但是不知道为什么它却是用的最广的。
　　下载地址：

　　2、JSONKit
　　JSONKit解析速度上最接近iOS原生解析类，当然iOS5.0才开始支持原生解析，所以选择一个库还是很必要的。
　　下载地址：https://github.com/johnezang/JSONKit

　　3、TouchJSON
　　TouchJSON用的也比较广泛.
　　下载地址：https://github.com/TouchCode/TouchJSON

　　4、json-framework
　　没有用过。
　　下载地址：https://github.com/stig/json-framework
　　5、TBXML
　　TBXML是一套轻量级的DOM方式的XML解析类库，有很好的性能和低内存占用，不过它不对XML格式进行校验，不支持XPath，并且只支持解析，不支持对XML进行修改。
　　下载地址：https://github.com/71squared/TBXML

　　6、TouchXML
　　TouchXML这也是一套DOM方式的XML解析类库，支持XPath，不支持XML的修改。
　　下载地址：https://github.com/TouchCode/TouchXML

　　7、KissXML
　　KissXML这是一套基于TouchXML的XML解析类库，只不过实现了支持XML的修改。
　　下载地址：https://github.com/robbiehanson/KissXML

　　8、GDataXML
　　GDataXML是Google开发的DOM方式XML解析类库，支持读取和修改XML文档，支持XPath方式查询。
　　下载地址：

　　第三方管理
　　1、fmdb
　　fmdb是一个数据库管理库，封装了sqlite相关的sql语句，简化数据库操作。
　　下载地址：https://github.com/ccgus/fmdb
　　2、ssziparchive
　　ssziparchive与sstoolkit是同一个作者，这哥们儿简直是个天才。
　　https://github.com/soffes/ssziparchive
　　3、ZipArchive
　　ZipArchive同样是minizip的封装。
　　https://github.com/mattconnolly/ZipArchive
　　4、Objective-Zip
　　Objective-Zip将Zlib和MiniZip用Objective-C进行了封装，使用起来非常简单。
　　https://github.com/flyingdolphinstudio/Objective-Zip
　　5、zxing
　　zxing是一个开源Java类库用于解析多种格式的1D/2D条形码。目标是能够对QR编码、DataMatrix、UPC的1D条形码进行解码。 其提供了多种平台下的客户端。
　　https://github.com/zxing/zxing
　　6、ZBar
　　ZBar 是款桌面电脑用条形码/二维码扫描工具，支持摄像头及图片扫描，支持多平台包括 iPhone 手机。同时 ZBar提供了二维码扫描的 API 开发包。
　　https://github.com/ZBar/ZBar
　　7、ObjQREncoder
　　ObjQREncoder 是 Objective-C 的二维码的编码器，用于生成二维码图像。
　　https://github.com/jverkoey/ObjQREncoder
　　8、OpenUDID
　　OpenUDID是iOS禁止使用系统UDID之后的新解决方法。
　　https://github.com/ylechelle/OpenUDID
　　9、RegexKitLite
　　RegexKitLite 是一个轻量级的 Objective-C 的正则表达式库，支持 Mac OS X 和 iOS，使用ICU 库开发。
　　https://github.com/wezm/RegexKitLite
　　10、STUtils
　　STUtils是一系列的工具集，包含了很多对于iOS原生类的扩展，当然也包含一个用于安全保存用户密码STKeyChain。
　　https://github.com/ldandersen/STUtils
　　11、scifihifi-iphone
　　scifihifi-iphone用于安全保存用户密码到keychain中。
　　https://github.com/ldandersen/scifihifi-iphone
　　12、sskeychain
　　sskeychain同scifihifi-iphone一样，不过属于轻量级。
　　https://github.com/soffes/sskeychain
　　13、SDWebImage
　　SDWebImage调用网站上的图片，跟本地调用内置在应用包里的图片一样简单。操作也很简单。
　　https://github.com/rs/SDWebImage
　　14、umeng
　　umeng既有统计分析，也有社会化组件。但是统计分析的用户数似乎明显多于其社会化组件的用户。
　　http://dev.umeng.com/analytics/ios/sdk-download

　　第三方UI
　　1、appirater
　　appirater是一个可以直接使用到任何iPhone应用中的开源类，用于提醒用户在打开App时，对应用进行评论或打分。
　　下载地址：https://github.com/arashpayan/appirater
　　2、FDStatusBarNotifierView
　　FDStatusBarNotifierView 实现了在状态栏中显示自定义提醒信息的功能。
　　下载地址：https://github.com/frankdilo/FDStatusBarNotifierView
　　3、MTStatusBarOverlay
　　MTStatusBarOverlay 是一个定制的 iOS状态栏，用于覆盖系统默认的状态栏。
　　下载地址：https://github.com/myell0w/MTStatusBarOverlay
　　4、iCarousel
　　iCarousel 是一个用来简化在 iOS 上实现旋转木马时的视图切换效果，支持 iPad，提供多种切换效果。
　　下载地址：https://github.com/nicklockwood/iCarousel
　　5、MBProgressHUD
　　MBProgressHUD就不多说了，伟大的菊花。
　　下载地址：https://github.com/jdg/MBProgressHUD
　　6、SVProgressHUD
　　SVProgressHUD是一个轻量级的菊花。
　　下载地址：https://github.com/samvermette/SVProgressHUD
　　7、MWPhotoBrowser
　　MWPhotoBrowser 实现了一个照片浏览器类似 iOS自带的相册应用，可显示来自手机的图片或者是网络图片，可自动从网络下载图片并进行缓存。可对图片进行缩放等操作。
　　下载地址：https://github.com/mwaterfall/MWPhotoBrowser
　　8、ShareSDK
　　ShareSDK支持分享到新浪微博、微信好友、微信朋友圈、QQ好友、腾迅微博、QQ空间、人人网、开心网、豆瓣、搜狐微博、网易微博、短信、邮件、打印、拷贝等。但是由于这个SDK包很大，所以用的时候一定要精简一下。下载地址：http://sharesdk.cn/Download
