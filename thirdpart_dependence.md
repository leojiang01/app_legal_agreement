# UCloud APP授权合作伙伴

### SDK

#### 支付宝支付 SDK
* 第三方名称：支付宝（中国）网络技术有限公司
* 功能：帮助用户使用支付宝提供的支付功能
* 处理方式：采取去标识、加密等方式进行传输和处理
* 收集个人信息类型：
    * 设备状态权限
        * 1.为了保障您的账户和资金安全以及支付服务的安全稳定运行。
        * 2.为履行反洗钱、反恐怖融资、反电信网络诈骗等法定义务。
    * 网络连接权限
        * 1.允许程序使用网络连接，进行数据传输。
        * 2.允许程序获取当前网络信息。
* 隐私说明：[https://opendocs.alipay.com/open/54/01g6qm?pathHash=01459d85](https://opendocs.alipay.com/open/54/01g6qm?pathHash=01459d85)
* 隐私政策链接：[https://render.alipay.com/p/yuyan/180020010001196791/preview.html?agreementId=AG00000132](https://render.alipay.com/p/yuyan/180020010001196791/preview.html?agreementId=AG00000132)

<br>

#### 微信支付 SDK
* 第三方名称：财付通支付科技有限公司
* 功能：帮助用户使用微信支付服务及防范支付欺诈风险
* 处理方式：采取去标识、加密等方式进行传输和处理
* 收集个人信息类型：
    * 支付订单标识
    * 用户标识信息
    * IP地址
    * 订单金额
    * 订单时间
    * 商品信息（包括商品名称、商品描述等）
* 隐私政策链接：[https://www.tenpay.com/v3/helpcenter/low/privacy.shtml](https://www.tenpay.com/v3/helpcenter/low/privacy.shtml)

<br>

#### 极验 SDK
* 第三方名称：武汉极意网络科技有限公司
* 功能：在敏感行为操作前进行行为验证
* 收集个人信息类型：
    * 设备信息：设备系统信息、设备厂商信息、设备型号、设备品牌、设备内存大小、设备系统语言等信息；这些信息脱敏处理后用来建立异常流量识别模型，实现流量反欺诈技术；
    * 设备网络信息：IP、设备联网状态和类型等信息；这些信息脱敏处理后用来建立异常、虚拟设备识别模型，实现流量反欺诈技术；
    * 设备环境信息：设备屏幕尺寸、设备电池充电状态、设备电量、设备越狱标识、设备调试标识、设备模拟器标识、设备代码篡改标识、浏览器UA、浏览器默认语言、网页请求 referer 等信息；这些信息脱敏处理后用来建立异常、虚拟设备识别模型，实现流量反欺诈技术；
    * 用户生物轨迹信息：此类信息不是指用户从一个页面跳转到另一个页面所产生的业务跳转轨迹信息，是指用户在操作验证过程中所产生的滑动、点击、鼠标移动的轨迹等信息；这些信息脱敏处理后用来建立模拟、暴力、伪造轨迹识别模型，实现流量反欺诈技术；
    * 其他信息：验证时间戳、安装包名等信息；这些信息用来建立基础的异常辅助识别模型，实现流量反欺诈技术
* 隐私政策链接：[https://www.geetest.com/Private](https://www.geetest.com/Private)

<br>

#### 人脸认证FaceID SDK
* 第三方名称：北京旷视科技有限公司
* 功能：用于账号实名认证、备案等功能的活体检测
* 收集个人信息类型：人脸信息，含人脸照片、活体检测短视频
* 隐私政策链接：[https://assets.faceid.com/faceidopen/privacy-policy.html?ts=1643080025](https://assets.faceid.com/faceidopen/privacy-policy.html?ts=1643080025)

<br>

#### 小米推送（MiPush）SDK
* 第三方名称：北京小米移动软件有限公司
* 功能：用于向MIUI用户推送消息
* 收集个人信息类型：
    * 设备标识OAID和加密的Android ID，以及使用推送服务的应用信息如应用包名、版本号和运行状态；
    * 设备厂商、设备型号、设备内存、操作系统版本、小米推送SDK版本、设备归属地（国家或地区）、SIM卡运营商名称、当前网络类型。其中当前网络类型、SIM卡运营商名称仅在设备本地读取，不会上传至小米服务器；
    * 通知栏设置信息，包括是否屏蔽通知栏、是否设置锁屏弹出消息等；
* 隐私政策链接：[https://dev.mi.com/console/doc/detail?pId=1822](https://dev.mi.com/console/doc/detail?pId=1822)

<br>

#### 极光推送 SDK
* 第三方名称：深圳市和讯华谷信息技术有限公司
* 功能：向用户设备推送通知消息（活动信息、账户安全消息、财务类消息等）
* 收集个人信息类型：
    * 设备参数及系统信息(设备类型、设备型号、系统版本、及相关硬件信息)：用于识别用户的设备类型、设备型号、系统版本等，确保消息准确下发；
    * 设备标识符（IMEI、IDFA、Android ID、GID、 MAC、OAID、VAID、AAID、IMSI、MEID、UAID、SN、ICCID、SIM信息）：用于识别唯一用户，保证推送的精准送达及推送信息的准确统计；
    * 网络信息(IP 地址、WiFi 信息、基站信息、DNS地址、DHCP地址、SSID、BSSID)与位置信息（经纬度）：用于优化SDK与极光服务器的网络连接请求，保证服务的稳定性和连续性，同时实现区域推送功能；
    * 应用列表信息(应用崩溃信息、通知开关状态、APP 应用列表及活跃状态、APP 应用页面信息、APP 功能事件相关信息)：当一个设备有多个 APP 的推送链路同时活跃时，我们采用合并链路技术，随机合并成一条链路，以达到为用户节省电省流量的目的；
    * 推送日志信息：以便开发者查询使用推送服务记录，了解推送信息送达的情况，调整推送策略。
    * 数据处理方式：通过去标识化、加密传输及其他安全方式
    
* 隐私政策引导：[https://docs.jiguang.cn/jpush/client/jghgzy_a_i_h#sdk隐私政策披露要求与示例](https://docs.jiguang.cn/jpush/client/jghgzy_a_i_h#sdk%E9%9A%90%E7%A7%81%E6%94%BF%E7%AD%96%E6%8A%AB%E9%9C%B2%E8%A6%81%E6%B1%82%E4%B8%8E%E7%A4%BA%E4%BE%8B)
* 隐私政策链接：[https://www.jiguang.cn/license/privacy](https://www.jiguang.cn/license/privacy)


<br>

#### 华为HMS Core SDK
* 第三方名称：华为软件技术有限公司
* 功能：用于向华为手机用户推送消息
* 个人数据处理说明：[https://developer.huawei.com/consumer/cn/doc/development/HMSCore-Guides/personal-data-0000001050166427](https://developer.huawei.com/consumer/cn/doc/development/HMSCore-Guides/personal-data-0000001050166427)
* 隐私政策链接：[https://developer.huawei.com/consumer/cn/doc/development/HMSCore-Guides/sdk-data-security-0000001050042177](https://developer.huawei.com/consumer/cn/doc/development/HMSCore-Guides/sdk-data-security-0000001050042177)


<br>

#### VIVO推送 SDK
* 第三方名称：维沃移动通信有限公司及其关联公司
* 功能：用于向VIVO手机用户推送消息
* 收集个人信息类型：
    * 设备标识信息（如IMEI、EmmCID、UFSID、ANDROIDID、GUID、GAID、OPENID、VAID、OAID、RegID、加密的Android ID）；
    * 使用推送服务的应用软件信息（如应用包名、版本号、APPID、安装、卸载、恢复出厂设置、运行状态）；
    * 设备制造商；
    * 网络类型；
    * 国家码；
    * 设备类型
* 隐私政策链接：[https://dev.vivo.com.cn/documentCenter/doc/652](https://dev.vivo.com.cn/documentCenter/doc/652)


<br>

#### OPPO Push SDK
* 第三方名称：广东欢太科技有限公司
* 功能：用于向OPPO及一加手机用户推送消息
* 收集个人信息类型：
    * 设备相关信息（如IMEI或OAID，Serial Number，IMSI，User ID，Android ID，Google Advertising ID, 手机Region设置，设备型号，手机电量，手机操作系统版本及语言）；
    * 使用推送服务的应用信息（如APP包名及版本号，运行状态）、推送SDK版本号；
    * 网络相关信息（如IP或域名连接结果，当前网络类型）；
    * 消息发送结果、通知栏状态（如通知栏权限、用户点击行为）；
    * 锁屏状态（如是否锁屏，是否允许锁屏通知）
* 隐私政策链接：[https://open.oppomobile.com/new/developmentDoc/info?id=10288](https://open.oppomobile.com/new/developmentDoc/info?id=10288)


<br><br>
**更新日期：2025年10月24日**