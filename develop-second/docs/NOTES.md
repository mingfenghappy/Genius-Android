### V2.+.+


### V2.4.0
* `2015/02/26` 统一化 Attribute 命名方式
* `2015/02/26` 添加新的 Drawable: ColorState, Paint, SeekBar, AlmostRipple, BalloonMarker
* `2015/02/26` 添加新控件 SeekBar
* `2015/02/28` 添加气球标记控件 BalloonMarker
* `2015/02/28` 对气球标记控件进行悬浮控制
* `2015/02/28` 实现 SeekBar 拖动等功能
* `2015/03/01` 实现 SeekBar 颜色控制以及自动对齐功能
* `2015/03/01` 实现 SeekBar 主题颜色
* `2015/03/01` 优化 SeekBar 各个属性实现，以及显示，包括属性格式化
* `2015/03/02` 优化 SeekBar 无需 XML 通过纯 Java 实例化
* `2015/03/02` 其他各项属性以及浮动标记优化
* `2015/03/02` SeekBar 自适应高度计算
* `2015/03/02` 演示图片准备，说明文档准备等工作，准备发布相关
* `2015/03/02` **Publish Version 2.4.0**


### V2.3.1
* `2015/02/10` 优化 TouchEffectAnimator 透明度计算方法
* `2015/02/12` 优化所有涉及透明度复合的计算方法
* `2015/02/12` 修复属性设置颜色中，数量错误设置为'8'的BUG，应是'6'
* `2015/02/12` EditText 添加左右对齐设置
* `2015/02/12` 准备发布修正包
* `2015/02/10` **Publish Version 2.3.1**


### V2.3.0
* `2015/02/04` 优化 TouchEffectAnimator 点击效果，减少 CPU 消耗，同时优化第一次点击时出现动画未显示的现象。
* `2015/02/05` 优化 TextView ，减少不必要的内存消耗
* `2015/02/05` 添加 EditText Line Style ，添加底部线条效果
* `2015/02/06` 添加 EditText ，状态效果，普通、选中、无法操作
* `2015/02/06` 优化 EditText ，不同的效果采用不同的渲染，减少内存消耗
* `2015/02/09` 重新设计 Attribute 类，尽可能的分块封装
* `2015/02/09` 重新设计 CheckBox、EditText 动画实现，使其更加流畅减少内存消耗
* `2015/02/09` 优化并简化 EditText 实现，添加 Title 变色属性
* `2015/02/10` Button 添加边框属性
* `2015/02/10` 所有控件优化并把属性集中到 Attributes 中，添加后更改应使用 Attribute.notifyAttributeChange()
* `2015/02/10` 修复 程序退出后 执行命令行出现 空指针异常 的BUG
* `2015/02/10` 更新说明文档，添加代码更新界面的方法，准备发布迭代
* `2015/02/10` 在代码中同时添加中文与英文
* `2015/02/10` **Publish Version 2.3.0**


### V2.2.0
* `2015/01/15` 修复动画类中：`mAnimation` 属性一直为空的BUG
* `2015/01/16` 修复按钮动画当控件不可点击时还能触发触摸效果的BUG
* `2015/01/16` 按钮增加 `g_delayClick` 属性，用于是否等待动画完成后触发点击事件
* `2015/01/20` 更改 Button 控件中动画宽度高度的计算时机为点击时，减少加载控件时间
* `2015/01/21` 修复 CheckBok 控件所计算的高宽大小为0的情况
* `2015/01/23` 添加新控件 GeniusEditText
* `2015/01/25` 控件 GeniusEditText 完成 Hint 动画 Title
* `2015/01/26` 修复 GeniusEditText 中 Hint 为空时异常BUG
* `2015/01/26` 优化 GeniusButton 点击模式动画进入时间
* `2015/01/27` 为控件添加可独立设置4个顶点的圆角大小属性
* `2015/01/30` 为字体与字体样式添加枚举属性，简化设置操作
* `2015/01/30` 更新演示界面控件样式
* `2015/01/30` 撰写新文档，准备发布
* `2015/01/30` 整理文件，生成动画图片，整理Eclipse所需文件等
* `2015/01/30` **Publish Version 2.2.0**


### V2.1.0
* `2015/01/07` 调整触摸动画颜色透明度
* `2015/01/10` 按钮动画添加按压驻留特效
* `2015/01/10` 按钮动画新增纯按压特效
* `2015/01/10` 优化按钮特效Ripple中的半径运算法则
* `2015/01/10` 调整按钮特效中的特效顺序
* `2015/01/10` 按钮背景可自定义
* `2015/01/10` 按钮字体颜色可自定义
* `2015/01/10` 按钮触摸颜色可自定义属性：`g_touchEffectColor`
* `2015/01/10` 优化触摸波纹特效，消除锯齿情况
* `2015/01/10` 修复动画中传入颜色具有透明度情况下的BUG
* `2015/01/12` 优化APP模块中的属性等参数
* `2015/01/13` 优化了Command模块中的属性等，并修复可能出现的BUG
* `2015/01/14` 优化NetTool模块，删除SimplePing，并重写组织TraceRoute实现，解决可能存在的内存溢出情况
* `2015/01/14` 优化Util模块，修复FixedList中可能存在的BUG
* `2015/01/14` HashUtils类中更改MD5方法名统一为：getMD5String()
* `2015/01/14` 优化Log部分，更改写入Log类中的List为Queue，提高效率
* `2015/01/14` 调整演示界面显示效果，撰写新文档
* `2015/01/14` **Publish Version 2.1.0**


### V2.0.0
* `2014/12/29` 更名 MaterialUI 类为 GeniusUI
* `2014/12/29` 添加 CheckBox 控件
* `2014/12/29` CheckBox 控件添加动画效果
* `2014/12/29` 更改 Colors 资源，删除原来的颜色资源
* `2014/12/29` 优化 GeniusUI 类，重新添加静态颜色属性
* `2014/12/29` 更名 MaterialButton 类为 GeniusButton
* `2014/12/29` 移动并迁移文件夹 material 到 widget 文件夹
* `2014/12/29` 优化 GeniusCheckBox 控件，添加对应属性
* `2014/12/30` 更改所有属性名称，重写所有属性名称
* `2014/12/30` 优化 GeniusButton 控件中的点击触发条件
* `2014/12/30` GeniusCheckBox 控件添加属性 enable 和 check 属性，用于替代默认的属性
* `2014/12/30` GeniusCheckBox 控件优化，在编辑器中可直接预览效果；及其他属性优化
* `2014/12/30` Genius 颜色卡重新选取颜色，更加真实
* `2014/12/30` Genius 中 GeniusCheckBox 修复几个由于 SDK 版本导致的异常错误
* `2014/12/30` 更新演示代码中模糊图片（Blur）部分的实现方式
* `2015/01/01` 更新部分说明文档
* `2015/01/01` 修复 BlurKit 中当模糊半径为1时出现异常的情况
* `2015/01/04` 添加新控件 GeniusTextView 到项目
* `2015/01/04` Fixed GeniusCheckBox Bug
* `2015/01/04` 最大更改：移除 util nettool command 等模块
* `2015/01/04` 重新建立新的 Sample 包，更改 Genius-Android 为：GeniusUI
* `2015/01/05` 重新合并框架，重新整合，调整UI，调整说明
* `2015/01/06` 更名 ToolKit 为 UIKit 并重命名其子类
* `2015/01/06` 重新设计 GeniusButton ,重新设计动画控制
* `2015/01/07` 修复动画控制中的一个BUG
* `2015/01/07` 撰写新的说明文档，重新组织文件
* `2015/01/07` **Publish Version-2.0.0.**


### V1.0.0
* `2014/12/06` 更改模糊图片方法名，以及重新编译JNI
* `2014/12/10` `Command` 添加新参数，可设置单个任务执行超时值
* `2014/12/10` 更改 `Command` 锁控制机制
* `2014/12/10` 更改 `Command` 销毁机制，延迟5秒后销毁
* `2014/12/10` 更改 `Command` 整体优化，进程控制更加严密
* `2014/12/10` 更改 `Command` 添加重启方法，可重启服务绑定
* `2014/12/12` 添加 `ToolKit` 新方法可设置等待主线程执行的时长
* `2014/12/14` 添加英文版本说明，同时修正文档格式
* `2014/12/25` 添加项目文档注释
* `2014/12/25` 删除 `SpeedRoad` 类
* `2014/12/25` 更新 `EclipseImport` 文档
* `2014/12/26` **Publish Version-1.0.0.**


### V0.9.0
* `2014/11/24` 微调 `Log` 中发送消息方法
* `2014/11/24` 删除掉 `UiTool` 类
* `2014/11/24` 新增 `ToolKit` 代替 `UiTool` ,完成同样工作的同时无需传入Activity，传入Runnable类即可
* `2014/11/25` 编写 `Jni FastBlur` 实现模糊效果
* `2014/11/25` `Jni` 生成 so 文件完成
* `2014/11/25` 编写 `BlurKit` 类，添加 `FastBlur` 方法用于模糊图片
* `2014/11/26` 添加图片模糊案例
* `2014/11/26` 删除 `Jni` 中加载的 `android/log` 头文件
* `2014/11/26` 重新生成 `Jni` 文件so
* `2014/11/26` 修改 `util/ToolUtils` 类名为 `Tools`
* `2014/11/26` 删除 `util/Tools` 类中不常用方法：`getDeviceId()` `isAvailablePackage()`
* `2014/11/26` 更改资源 `attrs_material` 为 `genius_attrs`
* `2014/11/26` 更改资源 `colors` 为 `genius_colors`
* `2014/11/26` 更名日志 `Log.txt` 为工作记录 `NOTES.md`
* `2014/11/26` 添加文档文件夹并添加Eclipse完全导入说明书 `Log.txt` 为工作记录 `NOTES.md`
* `2014/11/26` 更改 `LogWriter` 类中锁的释放，解决其在特定情况下出现死锁情况
* `2014/11/26` 优化 `Log` 类回调部分，更改Handle为自定义线程类实现，优化效率
* `2014/11/26` 修改测试用例部分命名，以及删除多余部分
* `2014/11/26` 删除 `MaterialRectButton`，以及删除多余属性文件
* `2014/11/26` 修改 `README` 准备发布相关
* `2014/11/26` 完善相关文档，包括 `Eclipse` 导入方法
* `2014/11/26` **Publish Version-0.9.0.**


### V0.7.9
* `2014/11/21` `Log`方法添加直接拷贝日志到外部存储方法
* `2014/11/21` 取消`Log`初始化开启日志存储时的位置指定参数
* `2014/11/21` 修改README，更正Log传参错误示例
* `2014/11/21` **Publish Version-0.7.9.**


### V0.7.6
* `2014/10/27` 修复`Material`按钮竖直情况下动画BUG
* `2014/10/27` 更改README，添加Jar包模式下配置信息
* `2014/10/27` **Publish Version-0.7.6.**


### V0.7.5
* `2014/10/9` 更改域名解析传入服务器地址参数为：InetAddress
* `2014/10/9` 更改域名解析有服务器情况下超时时间为8秒
* `2014/10/10` 更改域名解析实例化是传入服务器参数为：InetAddress
* `2014/10/10` 删除命令行执行中产生的日志信息
* `2014/10/11` `MaterialButton` 调整速度参数
* `2014/10/11` `MaterialButton` 支持近似正方形情况
* `2014/10/11` `MaterialButton` 添加新属性`AutoMove`，自动移动到中间
* `2014/10/11` 更新项目截图
* `2014/10/12` **Publish Version-0.7.5.**


### V0.6.8
* `2014/10/5` 调整属性样式
* `2014/10/5` 公布`Material Button`
* `2014/10/5` 添加截图等工作
* `2014/10/5` 更新README，更新SAMPLE
* `2014/10/5` **Publish Version-0.6.8.**


### V0.6.5
* `2014/10/2` 简化`Log`设置文件存储的方法调用
* `2014/10/2` `Log`与`Command`抛出异常语句统一化
* `2014/10/2` 修改`NetTool`中"toString"方法的`Bug`
* `2014/10/3` 添加`FixedList`固定队列
* `2014/10/4` 添加`App`相关`UiTool`与`UiModel`
* `2014/10/5` 修复`TraceRoute,Dns`解析中解析失败时结果为null时触发异常
* `2014/10/5` 更新`README`，更新SAMPLE
* `2014/10/5` **Publish Version-0.6.5.**


### V0.4.0
* `2014/9/18` 程序注释等英文化。
* `2014/9/20` `Log`精简化，删除内存缓存及通知功能。
* `2014/9/21` `ToolUtils`添加文件拷贝，或许系统唯一标识等方法。
* `2014/9/22` `Command`精炼化，添加取消任务功能。
* `2014/9/23` `Command`服务添加自动停止功能，与销毁功能。
* `2014/9/24` 添加`NetTool`模块，提供Ping/DNS等常见功能使用。
* `2014/9/24` 添加`HashUtils`模块，提供对字符串与文件计算MD5。
* `2014/9/28` 库添加初始化与销毁方法。
* `2014/9/30` **Publish Version-0.4.0.**


### V0.1.1
* `2014/9/6` 更改日志部分`Bug`。
* `2014/9/6` 修改命令行执行部分，更改了服务实现与接口释放。
* `2014/9/6` 命令行执行添加异步执行方法。
* `2014/9/6` 命令执行类删除回调方式等待，采用有次数等待方式。
* `2014/9/6` 添加新的UI项目。
* `2014/9/6` `Material Button`实现。
* `2014/9/8` **Publish Version-0.1.1.**


### V0.1.0
* `2014/9/2` 修改`GLog`方法"addLogCallbackListener()"为："addCallbackListener()"。
* `2014/9/2` 解决`GLog`回调时出现："java.lang.RuntimeException: Can't create handler inside thread that has not called Looper.prepare()" Bug。
* `2014/9/2` 修复因为日志消息传输问题导致的服务调用日志类出现的程序死掉问题。
* `2014/9/2` `GLog`与`Command`类添加"destroy()"方法用于释放资源。
* `2014/9/2` **Publish Version-0.1.0.**