导航 ![](images/navbar-cad8cdcb.png)

[ ![](https://static.coinall.ltd/cdn/assets/imgs/221/02D05B5ABB57940A.png)
](/)

  * [API接口](javascript:void\(0\);)
  * [Broker接入](javascript:void\(0\);)
  * [最佳实践](javascript:void\(0\);)
  * [更新日志](javascript:void\(0\);)

API接口 Broker接入 最佳实践 更新日志

[English](javascript:void\(0\);)

  * 做市商申请
  * 概览 
    * 满意度调研 
    * 实盘交易 
    * 模拟盘交易 
    * 基本信息 
  * 交互式浏览器 
    * 使用说明 
  * REST API
    * 请求验证 
      * 生成APIKey 
      * 发起请求 
      * 签名 
    * 交易 
      * 下单 
      * 批量下单 
      * 撤单 
      * 批量撤单 
      * 修改订单 
      * 批量修改订单 
      * 市价仓位全平 
      * 获取订单信息 
      * 获取未成交订单列表 
      * 获取历史订单记录（近七天）
      * 获取历史订单记录（近三个月）
      * 获取成交明细（近三天） 
      * 获取成交明细（近三个月） 
      * 策略委托下单 
      * 撤销策略委托订单 
      * 撤销高级策略委托订单 
      * 获取未完成策略委托单列表 
      * 获取历史策略委托单列表 
    * 资金 
      * 获取币种列表 
      * 获取资金账户余额 
      * 获取账户资产估值 
      * 资金划转 
      * 获取资金划转状态 
      * 获取资金流水 
      * 闪电网络充币 
      * 获取充值地址信息 
      * 获取充值记录 
      * 提币 
      * 闪电网络提币 
      * 撤销提币 
      * 获取提币记录 
      * 小额资产兑换 
      * 获取余币宝余额 
      * 余币宝申购/赎回 
      * 设置余币宝借贷利率 
      * 获取余币宝出借明细 
      * 获取市场借贷信息（公共）
      * 获取市场借贷历史（公共） 
    * 闪兑 
      * 获取闪兑币种列表 
      * 获取闪兑币对信息 
      * 闪兑预估询价 
      * 闪兑交易 
      * 获取闪兑交易历史 
    * 账户 
      * 查看账户余额 
      * 查看持仓信息 
      * 查看账户持仓风险 
      * 账单流水查询（近七天）
      * 账单流水查询（近三月）
      * 查看账户配置 
      * 设置持仓模式 
      * 设置杠杆倍数 
      * 获取最大可买卖/开仓数量 
      * 获取最大可用数量 
      * 调整保证金 
      * 获取杠杆倍数 
      * 获取交易产品最大可借 
      * 获取当前账户交易手续费费率 
      * 获取计息记录 
      * 获取用户当前杠杆借币利率 
      * 期权greeks的PA/BS切换 
      * 逐仓交易设置 
      * 查看账户最大可转余额 
      * 查看账户特定风险状态 
      * 尊享借币还币 
      * 获取尊享借币还币历史 
      * 获取借币利率与限额 
      * 组合保证金的虚拟持仓保证金计算 
      * 查看账户Greeks 
    * 子账户 
      * 查看子账户列表 
      * 获取子账户资产余额 
      * 查询子账户转账记录 
      * 子账户间资金划转 
      * 设置子账户主动转出权限 
      * 查看被托管的子账户列表 
    * 行情数据 
      * 获取所有产品行情信息 
      * 获取单个产品行情信息 
      * 获取指数行情 
      * 获取产品深度 
      * 获取交易产品K线数据 
      * 获取交易产品历史K线数据
      * 获取指数K线数据 
      * 获取标记价格K线数据 
      * 获取交易产品公共成交数据 
      * 获取平台24小时总成交量 
      * Oracle 上链交易数据 
      * 获取法币汇率 
      * 获取指数成分数据 
    * 公共数据 
      * 获取交易产品基础信息 
      * 获取交割和行权记录 
      * 获取持仓总量 
      * 获取永续合约当前资金费率 
      * 获取永续合约历史资金费率 
      * 获取限价 
      * 获取期权定价 
      * 获取预估交割/行权价格 
      * 获取免息额度和币种折算率等级 
      * 获取系统时间 
      * 获取平台公共爆仓单信息 
      * 获取标记价格 
      * 获取衍生品仓位档位 
      * 获取市场借币杠杆利率和借币限额 
      * 获取尊享借币杠杆利率和借币限额 
      * 获取衍生品标的指数 
      * 获取风险准备金余额 
    * 交易大数据 
      * 获取交易大数据支持币种 
      * 获取主动买入/卖出情况 
      * 获取杠杆多空比 
      * 获取合约多空持仓人数比 
      * 获取合约持仓量及交易量 
      * 获取期权持仓量及交易量
      * 看涨/看跌期权合约 持仓总量比/交易总量比 
      * 看涨看跌持仓总量及交易总量（按到期日分） 
      * 看涨看跌持仓总量及交易总量（按执行价格分） 
      * 看跌/看涨期权合约 主动买入/卖出量 
    * Status 
  * WebSocket API
    * 概述 
    * 连接 
    * 登录 
    * 订阅 
    * 取消订阅 
    * Checksum机制 
      * 深度合并 
      * 计算校验和 
    * 交易 
      * 下单 
      * 批量下单 
      * 撤单 
      * 批量撤单 
      * 改单 
      * 批量改单 
    * 私有频道 
      * 账户频道 
      * 持仓频道 
      * 账户余额和持仓频道 
      * 订单频道 
      * 策略委托订单频道 
      * 高级策略委托订单频道 
      * 爆仓风险预警推送频道 
      * 账户greeks频道 
    * 公共频道 
      * 产品频道 
      * 行情频道 
      * 持仓总量频道 
      * K线频道 
      * 交易频道 
      * 预估交割/行权价格频道 
      * 标记价格频道 
      * 标记价格K线频道 
      * 限价频道 
      * 深度频道 
      * 期权定价频道 
      * 资金费率频道 
      * 指数K线频道 
      * 指数行情频道 
      * Status 频道 
  * 错误码 
    * REST 
      * 公共 
      * 大宗交易 
      * 币币/币币杠杆类 
      * 交割合约类 
      * 永续合约类 
      * 期权合约类 
      * 资金类 
      * 账户类 
    * WebSocket 
      * 公共 
  * 创建我的APIKey 
  * API问题反馈 

# 做市商申请

满足以下任意条件的用户即可申请加入欧易做市商计划：

  * 交易等级VIP2及以上  

  * 其他交易所达标做市商（需审核）  

提供以下信息发送邮件至：`mmcorporate@okx.com`或咨询大客户经理

  * 账户信息  

  * 除邮箱外的其他有效联系方式 
  * 邮件里需注明所申请的做市商类别 (可多选)  

    * 欧易 现货做市商申请
    * 欧易 交割合约做市商申请
    * 欧易 永续合约做市商申请

为鼓励做市商为平台提供更好的流动性，可以享受更优的交易手续费，同时也承担相应的做市责任。具体做市责任及手续费申请成功后提供相关资料。

欧易保留对做市商项目的最终解释权  做市商项目不支持VIP、交易量相关活动以及任何形式的返佣活动

# 概览

欢迎查看 V5 API文档。我们提供完整的REST和WebSocket API以满足您的交易需求。  
V5 API只适用于[交易账户](/support/hc/zh-cn/sections/360011507312)。  

## 满意度调研

为了更好的提高V5 API的接口服务用户体验，希望您将使用V5 API过程中的感受和建议告诉我们，我们非常重视每一位用户的反馈。[V5
API满意度调研](https://www.wjx.cn/vj/wFoyR0w.aspx)  

## 实盘交易

实盘API交易地址如下：

  * REST：`https://www.okx.com/`  

  * WebSocket公共频道：`wss://ws.okx.com:8443/ws/v5/public`  

  * WebSocket私有频道：`wss://ws.okx.com:8443/ws/v5/private`

AWS 地址如下：

  * REST：`https://aws.okx.com`  

  * WebSocket公共频道：`wss://wsaws.okx.com:8443/ws/v5/public`  

  * WebSocket私有频道：`wss://wsaws.okx.com:8443/ws/v5/private`  

新的域名已启用，旧的域名将择期下线，请您尽快切换到新的域名。

  * `旧的`REST：`https://www.okex.com`  

  * `旧的`WebSocket公共频道：`wss://ws.okex.com:8443/ws/v5/public`  

  * `旧的`WebSocket私有频道：`wss://ws.okex.com:8443/ws/v5/private`

`旧的AWS 地址如下`：

  * REST：`https://aws.okex.com`  

  * WebSocket公共频道：`wss://wsaws.okex.com:8443/ws/v5/public`  

  * WebSocket私有频道：`wss://wsaws.okex.com:8443/ws/v5/private`

## 模拟盘交易

目前可以进行V5 API的模拟盘交易，用户可以通过模拟盘API请求除了`提币`、`充值`和`申购赎回`外的所有接口。

模拟盘API交易地址如下：

  * REST：`https://www.okx.com`
  * WebSocket公共频道：`wss://wspap.okx.com:8443/ws/v5/public?brokerId=9999`  

  * WebSocket私有频道：`wss://wspap.okx.com:8443/ws/v5/private?brokerId=9999`  

新的域名已启用，旧的域名将择期下线，请您尽快切换到新的域名。

`旧的模拟盘API交易地址如下`：

  * REST：`https://www.okex.com`
  * WebSocket公共频道：`wss://wspap.okex.com:8443/ws/v5/public?brokerId=9999`  

  * WebSocket私有频道：`wss://wspap.okex.com:8443/ws/v5/private?brokerId=9999`

模拟盘的账户与欧易的账户是互通的，如果您已经有欧易账户，可以直接登录。

模拟盘API交易需要在模拟盘上创建APIKey：

登录欧易账户—>资产管理—>开始模拟盘交易—>个人中心—>创建模拟盘APIKey—>开始模拟交易

注意：模拟盘的请求的header里面需要添加 "x-simulated-trading: 1"。

> 请求头示例
    
    
    Content-Type: application/json
    
    OK-ACCESS-KEY: 37c541a1-****-****-****-10fe7a038418
    
    OK-ACCESS-SIGN: leaVRETrtaoEQ3yI9qEtI1CZ82ikZ4xSG5Kj8gnl3uw=
    
    OK-ACCESS-PASSPHRASE: 1****6
    
    OK-ACCESS-TIMESTAMP: 2020-03-28T12:21:41.274Z
    
    x-simulated-trading: 1
    

## 基本信息

交易所层面的下单规则如下：

限价单（包括高级限价单）的最大挂单数：4000个

策略策略委托订单最大挂单数：

  * 计划委托：5000个  

  * 移动止盈止损：50个  

  * 冰山委托：100个  

  * 时间加权委托：20个  

# 交互式浏览器

## 使用说明

该功能接口用户需先登录，接口只会请求模拟环境

  * Parameters 面板中点击`Try it out`按钮，编辑请求参数。

  * 点击`Execute`按钮发送请求。Responses 面板中查看请求结果。

立即体验 [交互式浏览器](/demo-trading-explorer/v5/zh)

# REST API

## 请求验证

### 生成APIKey

在对任何请求进行签名之前，您必须通过交易网站创建一个APIKey。创建APIKey后，您将获得3个必须记住的信息：

  * APIKey
  * SecretKey
  * Passphrase

APIKey和SecretKey将由平台随机生成和提供，Passphrase将由您提供以确保API访问的安全性。平台将存储Passphrase加密后的哈希值进行验证，但如果您忘记Passphrase，则无法恢复，请您通过交易网站重新生成新的APIKey。

每个APIKey最多可绑定20个IP地址；未绑定IP且拥有交易或提币权限的APIKey，将在闲置30天之后自动删除。

### 发起请求

所有REST私有请求头都必须包含以下内容：

  * `OK-ACCESS-KEY`字符串类型的APIKey。

  * `OK-ACCESS-SIGN`使用HMAC SHA256哈希函数获得哈希值，再使用Base-64编码（请参阅签名）。

  * `OK-ACCESS-TIMESTAMP`发起请求的时间（UTC），如：2020-12-08T09:08:57.715Z

  * `OK-ACCESS-PASSPHRASE`您在创建API密钥时指定的Passphrase。

所有请求都应该含有application/json类型内容，并且是有效的JSON。

### 签名

> 生成签名

`OK-ACCESS-SIGN`的请求头是对`timestamp + method + requestPath +
body`字符串（+表示字符串连接），以及SecretKey，使用HMAC SHA256方法加密，通过Base-64编码输出而得到的。

如：`sign=CryptoJS.enc.Base64.stringify(CryptoJS.HmacSHA256(timestamp + 'GET' +
'/users/self/verify', SecretKey))`

其中，`timestamp`的值与`OK-ACCESS-
TIMESTAMP`请求头相同，为ISO格式，如`2020-12-08T09:08:57.715Z`。

method是请求方法，字母全部大写：`GET/POST`。

requestPath是请求接口路径。如：`/api/v5/account/balance`

body是指请求主体的字符串，如果请求没有主体（通常为GET请求）则body可省略。如：`{"instId":"BTC-
USDT","lever":"5","mgnMode":"isolated"}`

GET请求参数是算作requestPath，不算body

SecretKey为用户申请APIKey时所生成。如：`22582BD0CFF14C41EDBF1AB98506286D`

## 交易

`交易`功能模块下的API接口需要身份验证。

### 下单

只有当您的账户有足够的资金才能下单。

#### 限速： 60次/2s

#### 限速规则：衍生品：UserID +(instrumentType、underlying)

#### 限速规则：币币和币币杠杆：UserID +(instrumentType、instrumentID)

#### HTTP请求

`POST /api/v5/trade/order`

> 请求示例
    
    
    币币下单：
    POST /api/v5/trade/order
    body
    {
        "instId":"BTC-USDT",
        "tdMode":"cash",
        "clOrdId":"b15",
        "side":"buy",
        "ordType":"limit",
        "px":"2.15",
        "sz":"2"
    }
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instId | String | 是 | 产品ID，如 `BTC-USD-190927-5000-C`  
tdMode | String | 是 | 交易模式  
保证金模式：`isolated`：逐仓 ；`cross`：全仓  
非保证金模式：`cash`：非保证金  
ccy | String | 否 | 保证金币种，仅适用于`单币种保证金模式`下的`全仓杠杆`订单  
clOrdId | String | 否 | 客户自定义订单ID  
字母（区分大小写）与数字的组合，可以是纯字母、纯数字且长度要在1-32位之间。  
tag | String | 否 | 订单标签  
字母（区分大小写）与数字的组合，可以是纯字母、纯数字，且长度在1-16位之间。  
side | String | 是 | 订单方向 `buy`：买 `sell`：卖  
posSide | String | 可选 | 持仓方向 在双向持仓模式下必填，且仅可选择 `long` 或 `short`  
ordType | String | 是 | 订单类型  
`market`：市价单  
`limit`：限价单  
`post_only`：只做maker单  
`fok`：全部成交或立即取消  
`ioc`：立即成交并取消剩余  
`optimal_limit_ioc`：市价委托立即成交并取消剩余（仅适用交割、永续）  
sz | String | 是 | 委托数量  
px | String | 可选 | 委托价格，仅适用于`limit`、`post_only`、`fok`、`ioc`类型的订单  
reduceOnly | Boolean | 否 | 是否只减仓，`true` 或 `false`，默认`false`  
仅适用于`币币杠杆`，以及买卖模式下的`交割/永续`  
仅适用于`单币种保证金模式`和`跨币种保证金模式`  
tgtCcy | String | 否 | 市价单委托数量的类型  
`base_ccy`: 交易货币 ；`quote_ccy`：计价货币  
仅适用于`币币`订单  
  
> 返回结果
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
            {
                "clOrdId":"oktswap6",
                "ordId":"12345689",
                "tag":"",
                "sCode":"0",
                "sMsg":""
            }
        ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
ordId | String | 订单ID  
clOrdId | String | 客户自定义订单ID  
tag | String | 订单标签  
sCode | String | 事件执行结果的code，0代表成功  
sMsg | String | 事件执行失败时的msg  
tdMode  
交易模式，下单时需要指定  
**简单交易模式：**  
\- 币币和期权买方：cash  
**单币种保证金模式：**  
\- 逐仓杠杆：isolated  
\- 全仓杠杆：cross  
\- 全仓币币：cash  
\- 全仓交割/永续/期权：cross  
\- 逐仓交割/永续/期权：isolated  
**跨币种保证金模式：**  
\- 逐仓杠杆：isolated  
\- 全仓币币：cross  
\- 全仓交割/永续/期权：cross  
\- 逐仓交割/永续/期权：isolated  
**组合保证金模式：**  
\- 逐仓杠杆：isolated  
\- 全仓币币：cross  
\- 全仓交割/永续/期权：cross  
\- 逐仓交割/永续/期权：isolated  
clOrdId  
clOrdId是用户自定义的唯一ID用来跟识别订单。如果在请求参数中传入了，那它一定会在返回参数内，并且可以用于查询订单，撤销订单，修改订单等接口。
clOrdId不能与当前所有的挂单的clOrdId重复  posSide  
持仓方向，单向持仓模式下此参数非必填，如果填写仅可以选择net；在双向持仓模式下必填，且仅可选择 long 或 short。  
双向持仓模式下，side和posSide需要进行组合  
开多：买入开多（side 填写 buy； posSide 填写 long ）  
开空：卖出开空（side 填写 sell； posSide 填写 short ）  
平多：卖出平多（side 填写 sell；posSide 填写 long ）  
平空：买入平空（side 填写 buy； posSide 填写 short ）  ordType  
订单类型，创建新订单时必须指定，您指定的订单类型将影响需要哪些订单参数和撮合系统如何执行您的订单，以下是有效的ordType：  
普通委托：  
limit：限价单，要求指定sz 和 px  
market：市价单，币币和币币杠杆，是市价委托吃单；交割合约和永续合约，是自动以最高买/最低卖价格委托，遵循限价机制；期权合约不支持市价委托  
高级委托：  
post_only：限价委托，在下单那一刻只做maker，如果该笔订单的任何部分会吃掉当前挂单深度，则该订单将被全部撤销。  
fok：限价委托，全部成交或立即取消，如果无法全部成交该笔订单，则该订单将被全部撤销。  
ioc：限价委托，立即成交并取消剩余，立即按照委托价格撮合成交，并取消该订单剩余未完成数量，不会在深度列表上展示委托数量。  
optimal_limit_ioc:市价委托，立即成交并取消剩余，仅适用于交割合约和永续合约。  sz  
交易数量，表示要购买或者出售的数量。  
当币币/币币杠杆以限价买入和卖出时，指交易货币数量。  
当币币/币币杠杆以市价买入时，指计价货币的数量。  
当币币/币币杠杆以市价卖出时，指交易货币的数量。  
当交割、永续、期权买入和卖出时，指合约张数。  reduceOnly  
只减仓，下单时，此参数设置为 true 时，表示此笔订单具有减仓属性，只会减少持仓数量，不会增加新的持仓仓位  
仅适用于`单币种账户模式`和`跨币种账户模式`  
仅适用于`币币杠杆`，以及买卖模式下的`交割/永续`  tgtCcy  
市价单委托数量的类型：仅适用于币币市价下单交易。  
交易货币：base_ccy  
计价货币：quote_ccy  
您在使用交易货币买入或者计价货币卖出时，请知晓：  
1.如果您输入的数量大于当前可买或者可卖的数量，系统将按照您的最大可买或者可卖数量帮您完成交易，如果您希望按照指定数量成交，那您可以尝试使用限价单，等待市场价格波动到锁定的余额可以买入或卖出您指定的数量。  
2.如果您输入的数量不大于当前可买或者可卖的数量，那当市场价格波动过大时，锁定的余额可能没办法买入您输入的交易货币数量或卖出您输入的计价货币数量，为保证您的交易体验，我们基于【能买多少买多少】或者【能卖多少卖多少】的原则，更改下单的数量帮您完成交易。此外，我们将尽量多锁定一点余额来规避更改下单数量的情况。  
2.1 交易币买入例子：  
以市价下单 买入 10个LTC为例，用户可买为11个，此时 10 < 11，挂单成功。当市价为200USDT/LTC，用户被锁定余额为3000
USDT，200*10 < 3000，最终成交10个LTC；
若市场波动过大，市价为400USDT/LTC，400*10>3000，当用户被锁定的余额不够买入下单指定的交易货币数量时，使用用户被锁定的最大余额3000
USDT下单买入，最终成交 3000/400 = 7.5个 LTC。  
2.2 计价币卖出例子：  
以市价下单 卖出 1000USDT为例，用户可卖为1200USDT，1000 <
1200，挂单成功。市价为200USDT/LTC，用户被锁定的余额为6个LTC，最终成交5个LTC；
若市场波动过大，市价为100USDT/LTC，100*6 < 1000，当用户被锁定的余额不够卖出下单指定的计价货币数量时，使用用户被锁定的最大余额
6个LTC下单，最终成交 6 * 100 = 600 USDT。

### 批量下单

每次最多可以批量提交20个新订单。请求参数应该按数组格式传递。

#### 限速： 300次/2s

#### 限速规则：币币和币币杠杆：UserID +(instrumentType、instrumentID)

#### 限速规则：批量请求中包含几个元素，限速计数就加几次，总的限制是`300次/2s`

#### HTTP请求

`POST /api/v5/trade/batch-orders`

> 请求示例
    
    
     币币批量下单：
     POST：/api/v5/trade/batch-orders
     body
     [
        {
            "instId":"BTC-USDT",
            "tdMode":"cash",
            "clOrdId":"b15",
            "side":"buy",
            "ordType":"limit",
            "px":"2.15",
            "sz":"2"
        },
        {
            "instId":"BTC-USDT",
            "tdMode":"cash",
            "clOrdId":"b15",
            "side":"buy",
            "ordType":"limit",
            "px":"2.15",
            "sz":"2"
        }
    ]
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instId | String | 是 | 产品ID，如 `BTC-USD-190927-5000-C`  
tdMode | String | 是 | 交易模式  
保证金模式：`isolated`：逐仓 ；`cross`：全仓  
非保证金模式：`cash`：非保证金  
ccy | String | 否 | 保证金币种，仅适用于单币种保证金模式下的全仓杠杆订单  
clOrdId | String | 否 | 客户自定义订单ID  
字母（区分大小写）与数字的组合，可以是纯字母、纯数字且长度要在1-32位之间。  
tag | String | 否 | 订单标签  
字母（区分大小写）与数字的组合，可以是纯字母、纯数字且长度要在1-16位之间。  
side | String | 是 | 订单方向 `buy`：买 `sell`：卖  
posSide | String | 可选 | 持仓方向 在双向持仓模式下必填，且仅可选择 `long` 或 `short`  
ordType | String | 是 | 订单类型  
`market`：市价单  
`limit`：限价单  
`post_only`：只做maker单  
`fok`：全部成交或立即取消  
`ioc`：立即成交并取消剩余  
`optimal_limit_ioc`：市价委托立即成交并取消剩余（仅适用交割、永续）  
sz | String | 是 | 委托数量  
px | String | 否 | 委托价格，仅适用于`limit`、`post_only`、`fok`、`ioc`类型的订单  
reduceOnly | Boolean | 否 | 是否只减仓，`true` 或 `false`，默认`false`  
仅适用于`币币杠杆`，以及买卖模式下的`交割/永续`  
仅适用于`单币种保证金模式`和`跨币种保证金模式`  
tgtCcy | String | 否 | 市价单委托数量的类型  
`base_ccy`: 交易货币 ；`quote_ccy`：计价货币  
仅适用于`币币`订单  
默认买为`计价货币`，卖为`交易货币`  
  
> 返回结果
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
            {
                "clOrdId":"oktswap6",
                "ordId":"12345689",
                "tag":"",
                "sCode":"0",
                "sMsg":""
            },
            {
                "clOrdId":"oktswap7",
                "ordId":"12344",
                "tag":"",
                "sCode":"0",
                "sMsg":""
            },
         .......
        ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
ordId | String | 订单ID  
clOrdId | String | 客户自定义订单ID  
tag | String | 订单标签  
sCode | String | 事件执行结果的code，0代表成功  
sMsg | String | 事件执行失败时的msg  
在组合保证金账户模式下，或者全部成功，或者全部失败。

### 撤单

撤销之前下的未完成订单。

#### 限速： 60次/2s

#### 限速规则：衍生品：UserID +(instrumentType、underlying)

#### 限速规则：币币和币币杠杆：UserID +(instrumentType、instrumentID)

#### HTTP请求

`POST /api/v5/trade/cancel-order`

> 请求示例
    
    
    POST /api/v5/trade/cancel-order
    body
    {
        "ordId":"2510789768709120",
        "instId":"BTC-USD-190927"
    }
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instId | String | 是 | 产品ID，如 `BTC-USD-190927`  
ordId | String | 可选 | 订单ID， `ordId`和`clOrdId`必须传一个，若传两个，以`ordId`为主  
clOrdId | String | 可选 | 用户自定义ID  
  
> 返回结果
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
            {
                "clOrdId":"oktswap6",
                "ordId":"12345689",
                "sCode":"0",
                "sMsg":""
            }
        ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
ordId | String | 订单ID  
clOrdId | String | 客户自定义订单ID  
sCode | String | 事件执行结果的code，0代表成功  
sMsg | String | 事件执行失败时的msg  
撤单返回sCode等于0不能严格认为该订单已经被撤销，只表示您的撤单请求被系统服务器所接受，撤单结果以订单频道推送的状态或者查询订单状态为准  

### 批量撤单

撤销未完成的订单，每次最多可以撤销20个订单。请求参数应该按数组格式传递。

#### 限速： 300次/2s

#### 限速规则：衍生品：UserID +(instrumentType、underlying)

#### 限速规则：币币和币币杠杆：UserID +(instrumentType、instrumentID)

#### 限速规则：批量请求中包含几个元素，限速计数就加几次，总的限制是`300次/2s`

#### HTTP请求

`POST /api/v5/trade/cancel-batch-orders`

> 请求示例
    
    
    POST /api/v5/trade/cancel-batch-orders
    body
    [
        {
            "instId":"BTC-USDT",
            "ordId":"12312"
        },
        {
            "instId":"BTC-USDT",
            "ordId":"1212"
        }
    ]
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instId | String | 是 | 产品ID，如 `BTC-USD-190927`  
ordId | String | 可选 | 订单ID， `ordId`和`clOrdId`必须传一个，若传两个，以`ordId`为主  
clOrdId | String | 可选 | 用户自定义ID  
  
> 返回结果
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
            {
                "clOrdId":"oktswap6",
                "ordId":"12345689",
                "sCode":"0",
                "sMsg":""
            },
            {
                "clOrdId":"oktswap7",
                "ordId":"12344",
                "sCode":"0",
                "sMsg":""
            },
         .......
        ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
ordId | String | 订单ID  
clOrdId | String | 客户自定义订单ID  
sCode | String | 事件执行结果的code，0代表成功  
sMsg | String | 事件执行失败时的msg  
  
### 修改订单

修改当前未成交的挂单

#### 限速： 60次/2s

#### 限速规则：衍生品：UserID +(instrumentType、underlying)

#### 限速规则：币币和币币杠杆：UserID +(instrumentType、instrumentID)

#### HTTP请求

`POST /api/v5/trade/amend-order`

> 请求示例
    
    
    POST /api/v5/trade/amend-order
    body
    {
        "ordId":"2510789768709120",
        "newSz":"2",
        "instId":"BTC-USDT"
    }
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instId | String | 是 | 产品ID  
cxlOnFail | Boolean | 否 | `false`：不自动撤单 `true`：自动撤单
当订单修改失败时，该订单是否需要自动撤销。默认为`false`  
ordId | String | 可选 | 订单ID， `ordId`和`clOrdId`必须传一个，若传两个，以`ordId`为主  
clOrdId | String | 可选 | 用户自定义order ID  
reqId | String | 否 | 用户自定义修改事件ID  
字母（区分大小写）与数字的组合，可以是纯字母、纯数字且长度要在1-32位之间。  
newSz | String | 可选 | 修改的新数量，`newSz`和`newPx`不可同时为空。对于部分成交订单，该数量应包含已成交数量。  
newPx | String | 可选 | 修改的新价格  
newSz  
修改的数量<=该笔订单已成交数量时，该订单的状态会修改为完全成交状态。  

> 返回结果
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
            {
             "clOrdId":"",
             "ordId":"12344",
             "reqId":"b12344",
             "sCode":"0",
             "sMsg":""
            }
        ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
ordId | String | 订单ID  
clOrdId | String | 用户自定义ID  
reqId | String | 用户自定义修改事件ID  
sCode | String | 事件执行结果的code，0代表成功  
sMsg | String | 事件执行失败时的msg  
修改订单返回sCode等于0不能严格认为该订单已经被修改，只表示您的修改订单请求被系统服务器所接受，改单结果以订单频道推送的状态或者查询订单状态为准  

### 批量修改订单

修改未完成的订单，一次最多可批量修改20个订单。请求参数应该按数组格式传递。

#### 限速： 300次/2s

#### 限速规则：衍生品：UserID +(instrumentType、underlying)

#### 限速规则：币币和币币杠杆：UserID +(instrumentType、instrumentID)

#### 限速规则：批量请求中包含几个元素，限速计数就加几次，总的限制是`300次/2s`

#### HTTP请求

`POST /api/v5/trade/amend-batch-orders`

> 请求示例
    
    
    POST /api/v5/trade/amend-batch-orders
    body
    [
        {
            "ordId":"2510789768709120",
            "newSz":"2",
            "instId":"BTC-USDT"
        },
        {
            "ordId":"2510789768709121",
            "newSz":"2",
            "instId":"BTC-USDT"
        }
    ]
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instId | String | 是 | 产品ID  
cxlOnFail | Boolean | 否 | `false` ：不自动撤单 `true`：自动撤单
当订单修改失败时，该订单是否需要自动撤销，默认为`false`  
ordId | String | 可选 | 订单ID， `ordId`和`clOrdId`必须传一个，若传两个，以`ordId`为主  
clOrdId | String | 可选 | 用户自定义order ID  
reqId | String | 否 | 用户自定义修改事件ID  
字母（区分大小写）与数字的组合，可以是纯字母、纯数字且长度要在1-32位之间。  
newSz | String | 可选 | 修改的新数量，`newSz`和`newPx`不可同时为空。对于部分成交订单，该数量应包含已成交数量。  
newPx | String | 可选 | 修改的新价格  
newSz  
修改的数量<=该笔订单已成交数量时，该订单的状态会修改为完全成交状态。  

> 返回结果
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
            {
                "clOrdId":"oktswap6",
                "ordId":"12345689",
                "reqId":"b12344",
                "sCode":"0",
                "sMsg":""
            },
            {
                "clOrdId":"oktswap7",
                "ordId":"12344",
                "reqId":"b12344",
                "sCode":"0",
                "sMsg":""
            },
         .......
        ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
ordId | String | 订单ID  
clOrdId | String | 用户自定义ID  
reqId | String | 用户自定义修改事件ID  
sCode | String | 事件执行结果的code，0代表成功  
sMsg | String | 事件执行失败时的msg  
  
### 市价仓位全平

市价平掉指定交易产品的持仓

#### 限速： 20次/2s

#### 限速规则：衍生品：UserID +(instrumentType、underlying)

#### 限速规则：币币和币币杠杆：UserID +(instrumentType、instrumentID)

#### HTTP请求

`POST /api/v5/trade/close-position`

> 请求示例
    
    
    POST /api/v5/trade/close-position
    body
    {
        "instId":"BTC-USDT-SWAP",
        "mgnMode":"cross"
    }
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instId | String | 是 | 产品ID  
posSide | String | 可选 | 持仓方向  
单向持仓模式下：可不填写此参数，默认值net，如果填写，仅可以填写net  
双向持仓模式下： 必须填写此参数，且仅可以填写 `long`：平多 ，`short`：平空  
mgnMode | String | 是 | 保证金模式  
`cross`：全仓 ； `isolated`：逐仓  
ccy | String | 可选 | 保证金币种，单币种保证金模式的全仓币币杠杆平仓必填  
autoCxl | Boolean | 否 | 当市价全平时，平仓单是否需要自动撤销,默认为false.  
`false`：不自动撤单 `true`：自动撤单  
  
> 返回结果
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
               {
                "instId":"BTC-USDT-SWAP",
                "posSide":"long"
              }
        ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
instId | String | 产品ID  
posSide | String | 持仓方向  
如果不自动撤单，那有任何平仓挂单的情况下，市价全平会返回错误码信息，提示用户先撤销平仓挂单  

### 获取订单信息

查订单信息

#### 限速： 60次/2s

#### 限速规则：衍生品：UserID +(instrumentType、underlying)

#### 限速规则：币币和币币杠杆：UserID +(instrumentType、instrumentID)

#### HTTP请求

`GET /api/v5/trade/order`

> 请求示例
    
    
    GET /api/v5/trade/order?ordId=2510789768709120&instId=BTC-USDT
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instId | String | 是 | 产品ID ，如`BTC-USD-190927`  
ordId | String | 可选 | 订单ID ， `ordId`和`clOrdId`必须传一个，若传两个，以`ordId`为主  
clOrdId | String | 可选 | 用户自定义ID  
  
> 返回结果
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
            {
                "instType":"FUTURES",
                "instId":"BTC-USD-200329",
                "ccy":"",
                "ordId":"123445",
                "clOrdId":"b1",
                "tag":"",
                "px":"999",
                "sz":"3",
                "pnl":"5",
                "ordType":"limit",
                "side":"buy",
                "posSide":"long",
                "tdMode":"isolated",
                "accFillSz":"0",
                "fillPx":"0",
                "tradeId":"0",
                "fillSz":"0",
                "fillTime":"0",
                "source": "",
                "state":"live",
                "avgPx":"0",
                "lever":"20",
                "tpTriggerPx":"",
                "tpTriggerPxType":"last",
                "tpOrdPx":"",
                "slTriggerPx":"",
                "slTriggerPxType":"last",
                "slOrdPx":"",
                "feeCcy":"",
                "fee":"",
                "rebateCcy":"",
                "rebate":"",
                "tgtCcy":"",
                "category":"",
                "uTime":"1597026383085",
                "cTime":"1597026383085"
            }
        ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
instType | String | 产品类型  
`SPOT`：币币  
`MARGIN`：币币杠杆  
`SWAP`：永续合约  
`FUTURES`：交割合约  
`OPTION`：期权  
instId | String | 产品ID  
tgtCcy | String | 市价单委托数量的类型  
`base_ccy`: 交易货币 ；`quote_ccy`：计价货币  
ccy | String | 保证金币种，仅适用于`单币种保证金模式`下的全仓`币币杠杆`订单  
ordId | String | 订单ID  
clOrdId | String | 客户自定义订单ID  
tag | String | 订单标签  
px | String | 委托价格  
sz | String | 委托数量  
pnl | String | 收益  
ordType | String | 订单类型  
`market`：市价单  
`limit`：限价单  
`post_only`：只做maker单  
`fok`：全部成交或立即取消  
`ioc`：立即成交并取消剩余  
`optimal_limit_ioc`：市价委托立即成交并取消剩余（仅适用交割、永续）  
side | String | 订单方向  
posSide | String | 持仓方向  
tdMode | String | 交易模式  
accFillSz | String | 累计成交数量  
fillPx | String | 最新成交价格  
tradeId | String | 最新成交ID  
fillSz | String | 最新成交数量  
fillTime | String | 最新成交时间  
avgPx | String | 成交均价  
state | String | 订单状态  
`canceled`：撤单成功  
`live`：等待成交  
`partially_filled`：部分成交  
`filled`：完全成交  
lever | String | 杠杆倍数，0.01到125之间的数值，仅适用于 `币币杠杆/交割/永续`  
tpTriggerPx | String | 止盈触发价  
tpTriggerPxType | String | 止盈触发价类型  
`last`：最新价格  
`index`：指数价格  
`mark`：标记价格  
tpOrdPx | String | 止盈委托价  
slTriggerPx | String | 止损触发价  
slTriggerPxType | String | 止损触发价类型  
`last`：最新价格  
`index`：指数价格  
`mark`：标记价格  
slOrdPx | String | 止损委托价  
feeCcy | String | 交易手续费币种  
fee | String | 订单交易手续费，平台向用户收取的交易手续费，手续费扣除为`负数`。如： `-0.01`  
rebateCcy | String | 返佣金币种  
source | String | 订单来源  
`13`:策略委托单触发后的生成的限价单  
rebate | String |
返佣金额，平台向达到指定lv交易等级的用户支付的挂单奖励（返佣），如果没有返佣金，该字段为“”。手续费返佣为`正数`，如：`0.01`  
category | String | 订单种类  
`normal`：普通委托  
`twap`：TWAP自动换币  
`adl`：ADL自动减仓  
`full_liquidation`：强制平仓  
`partial_liquidation`：强制减仓  
`delivery`：交割  
`ddh`：对冲减仓类型订单  
uTime | String | 订单状态更新时间，Unix时间戳的毫秒数格式，如：`1597026383085`  
cTime | String | 订单创建时间，Unix时间戳的毫秒数格式， 如 ：`1597026383085`  
  
### 获取未成交订单列表

获取当前账户下所有未成交订单信息

#### 限速： 60次/2s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/trade/orders-pending`

> 请求示例
    
    
    GET /api/v5/trade/orders-pending?ordType=post_only,fok,ioc&instType=SPOT
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instType | String | 否 | 产品类型  
`SPOT`：币币  
`MARGIN`：币币杠杆  
`SWAP`：永续合约  
`FUTURES`：交割合约  
`OPTION`：期权  
uly | String | 否 | 标的指数  
instId | String | 否 | 产品ID，如`BTC-USD-200927`  
ordType | String | 否 | 订单类型  
`market`：市价单  
`limit`：限价单  
`post_only`：只做maker单  
`fok`：全部成交或立即取消  
`ioc`：立即成交并取消剩余  
`optimal_limit_ioc`：市价委托立即成交并取消剩余（仅适用交割、永续）  
state | String | 否 | 订单状态  
`live`：等待成交  
`partially_filled`：部分成交  
after | String | 否 | 请求此ID之前（更旧的数据）的分页内容，传的值为对应接口的`ordId`  
before | String | 否 | 请求此ID之后（更新的数据）的分页内容，传的值为对应接口的`ordId`  
limit | String | 否 | 返回结果的数量，默认100条  
  
> 返回结果
    
    
    {
        "code": "0",
        "msg": "",
        "data": [
            {
                "accFillSz": "0",
                "avgPx": "",
                "cTime": "1618235248028",
                "category": "normal",
                "ccy": "",
                "clOrdId": "",
                "fee": "0",
                "feeCcy": "BTC",
                "fillPx": "",
                "fillSz": "0",
                "fillTime": "",
                "instId": "BTC-USDT",
                "instType": "SPOT",
                "lever": "5.6",
                "ordId": "301835739059335168",
                "ordType": "limit",
                "pnl": "0",
                "posSide": "net",
                "px": "59200",
                "rebate": "0",
                "rebateCcy": "USDT",
                "side": "buy",
                "slOrdPx": "",
                "slTriggerPx": "",
                "slTriggerPxType": "last",
                "source": "",
                "state": "live",
                "sz": "1",
                "tag": "",
                "tdMode": "cross",
                "tgtCcy": "",
                "tpOrdPx": "",
                "tpTriggerPx": "",
                "tpTriggerPxType": "last",
                "tradeId": "",
                "uTime": "1618235248028"
            }
        ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
instType | String | 产品类型  
instId | String | 产品ID  
tgtCcy | String | 市价单委托数量的类型  
`base_ccy`: 交易货币 ；`quote_ccy`：计价货币  
ccy | String | 保证金币种，仅适用于`单币种保证金模式`下的全仓`币币杠杆`订单  
ordId | String | 订单ID  
clOrdId | String | 客户自定义订单ID  
tag | String | 订单标签  
px | String | 委托价格  
sz | String | 委托数量  
pnl | String | 收益  
ordType | String | 订单类型  
`market`：市价单  
`limit`：限价单  
`post_only`：只做maker单  
`fok`：全部成交或立即取消  
`ioc`：立即成交并取消剩余  
`optimal_limit_ioc`：市价委托立即成交并取消剩余（仅适用交割、永续）  
side | String | 订单方向  
posSide | String | 持仓方向  
tdMode | String | 交易模式  
accFillSz | String | 累计成交数量  
fillPx | String | 最新成交价格  
tradeId | String | 最新成交ID  
fillSz | String | 最新成交数量  
fillTime | String | 最新成交时间  
avgPx | String | 成交均价  
state | String | 订单状态  
`live`：等待成交  
`partially_filled`：部分成交  
  
lever | String | 杠杆倍数，0.01到125之间的数值，仅适用于 `币币杠杆/交割/永续`  
tpTriggerPx | String | 止盈触发价  
tpTriggerPxType | String | 止盈触发价类型  
`last`：最新价格  
`index`：指数价格  
`mark`：标记价格  
slTriggerPx | String | 止损触发价  
slTriggerPxType | String | 止损触发价类型  
`last`：最新价格  
`index`：指数价格  
`mark`：标记价格  
slOrdPx | String | 止损委托价  
feeCcy | String | 交易手续费币种  
fee | String | 订单交易手续费，平台向用户收取的交易手续费，手续费扣除为`负数`。如： `-0.01`  
rebateCcy | String | 返佣金币种  
source | String | 订单来源  
`13`:策略委托单触发后的生成的限价单  
rebate | String |
返佣金额，平台向达到指定lv交易等级的用户支付的挂单奖励（返佣），如果没有返佣金，该字段为“”。手续费返佣为`正数`，如：`0.01`  
category | String | 订单种类  
`normal`： 普通委托  
uTime | String | 订单状态更新时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
cTime | String | 订单创建时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
  
### 获取历史订单记录（近七天）

获取最近7天的已经完结状态的订单数据，已经撤销的未成交单 只保留2小时

#### 限速： 40次/2s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/trade/orders-history`

> 请求示例
    
    
    GET /api/v5/trade/orders-history?ordType=post_only,fok,ioc&instType=SPOT
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instType | String | 是 | 产品类型  
`SPOT`：币币  
`MARGIN`：币币杠杆  
`SWAP`：永续合约  
`FUTURES`：交割合约  
`OPTION`：期权  
uly | String | 否 | 标的指数  
instId | String | 否 | 产品ID，如`BTC-USD-190927`  
ordType | String | 否 | 订单类型  
`market`：市价单  
`limit`：限价单  
`post_only`：只做maker单  
`fok`：全部成交或立即取消  
`ioc`：立即成交并取消剩余  
`optimal_limit_ioc`：市价委托立即成交并取消剩余（仅适用交割、永续）  
state | String | 否 | 订单状态  
`canceled`：撤单成功  
`filled`：完全成交  
category | String | 否 | 订单种类  
`twap`：TWAP自动换币  
`adl`：ADL自动减仓  
`full_liquidation`：强制平仓  
`partial_liquidation`：强制减仓  
`delivery`：交割  
`ddh`：对冲减仓类型订单  
after | String | 否 | 请求此ID之前（更旧的数据）的分页内容，传的值为对应接口的`ordId`  
before | String | 否 | 请求此ID之后（更新的数据）的分页内容，传的值为对应接口的`ordId`  
limit | String | 否 | 返回结果的数量，默认100条  
  
> 返回结果
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
            {
                "instType":"FUTURES",
                "instId":"BTC-USD-200329",
                "ccy":"",
                "ordId":"123445",
                "clOrdId":"b1",
                "tag":"",
                "px":"999",
                "sz":"3",
                "ordType":"limit",
                "side":"buy",
                "posSide":"long",
                "tdMode":"isolated",
                "accFillSz":"0",
                "fillPx":"0",
                "tradeId":"0",
                "fillSz":"0",
                "fillTime":"0",
                "source": "",
                "state":"filled",
                "avgPx":"0",
                "lever":"20",
                "tpTriggerPx":"",
                "tpTriggerPxType":"last",
                "tpOrdPx":"",
                "slTriggerPx":"",
                "slTriggerPxType":"last",
                "slOrdPx":"",
                "feeCcy":"",
                "fee":"",
                "rebateCcy":"",
                "rebate":"",
                "tgtCcy":"",
                "pnl":"",
                "category":"",
                "uTime":"1597026383085",
                "cTime":"1597026383085"
            }
        ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
instType | String | 产品类型  
instId | String | 产品ID  
tgtCcy | String | 市价单委托数量的类型  
`base_ccy`: 交易货币 ；`quote_ccy`：计价货币  
ccy | String | 保证金币种，仅适用于`单币种保证金模式`下的全仓`币币杠杆`订单  
ordId | String | 订单ID  
clOrdId | String | 客户自定义订单ID  
tag | String | 订单标签  
px | String | 委托价格  
sz | String | 委托数量  
ordType | String | 订单类型  
`market`：市价单  
`limit`：限价单  
`post_only`：只做maker单  
`fok`：全部成交或立即取消  
`ioc`：立即成交并取消剩余  
`optimal_limit_ioc`：市价委托立即成交并取消剩余（仅适用交割、永续）  
side | String | 订单方向  
posSide | String | 持仓方向  
tdMode | String | 交易模式  
accFillSz | String | 累计成交数量  
fillPx | String | 最新成交价格  
tradeId | String | 最新成交ID  
fillSz | String | 最新成交数量  
fillTime | String | 最新成交时间  
avgPx | String | 成交均价  
state | String | 订单状态  
`canceled`：撤单成功  
`filled`：完全成交  
lever | String | 杠杆倍数，0.01到125之间的数值，仅适用于 `币币杠杆/交割/永续`  
tpTriggerPx | String | 止盈触发价  
tpTriggerPxType | String | 止盈触发价类型  
`last`：最新价格  
`index`：指数价格  
`mark`：标记价格  
tpOrdPx | String | 止盈委托价  
slTriggerPx | String | 止损触发价  
slTriggerPxType | String | 止损触发价类型  
`last`：最新价格  
`index`：指数价格  
`mark`：标记价格  
slOrdPx | String | 止损委托价  
feeCcy | String | 交易手续费币种  
fee | String | 订单交易手续费，平台向用户收取的交易手续费，手续费扣除为`负数`。如： `-0.01`  
rebateCcy | String | 返佣金币种  
source | String | 订单来源  
`13`:策略委托单触发后的生成的限价单  
rebate | String |
返佣金额，平台向达到指定lv交易等级的用户支付的挂单奖励（返佣），如果没有返佣金，该字段为“”。手续费返佣为`正数`，如：`0.01`  
pnl | String | 收益  
category | String | 订单种类  
`normal`：普通委托  
`twap`：TWAP自动换币  
`adl`：ADL自动减仓  
`full_liquidation`：强制平仓  
`partial_liquidation`：强制减仓  
`delivery`：交割  
`ddh`：对冲减仓类型订单  
uTime | String | 订单状态更新时间，Unix时间戳的毫秒数格式，如`1597026383085`  
cTime | String | 订单创建时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
  
### 获取历史订单记录（近三个月）

获取最近3个月的已经完结状态的订单数据

#### 限速： 20次/2s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/trade/orders-history-archive`

> 请求示例
    
    
    GET /api/v5/trade/orders-history-archive?ordType=post_only,fok,ioc&instType=SPOT
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instType | String | 是 | 产品类型  
`SPOT`：币币  
`MARGIN`：币币杠杆  
`SWAP`：永续合约  
`FUTURES`：交割合约  
`OPTION`：期权  
uly | String | 否 | 标的指数  
instId | String | 否 | 产品ID，如`BTC-USD-200927`  
ordType | String | 否 | 订单类型  
`market`：市价单  
`limit`：限价单  
`post_only`：只做maker单  
`fok`：全部成交或立即取消  
`ioc`：立即成交并取消剩余  
`optimal_limit_ioc`：市价委托立即成交并取消剩余（仅适用交割、永续）  
state | String | 否 | 订单状态  
`canceled`：撤单成功  
`filled`：完全成交  
category | String | 否 | 订单种类  
`twap`：TWAP自动换币  
`adl`：ADL自动减仓  
`full_liquidation`：强制平仓  
`partial_liquidation`：强制减仓  
`delivery`：交割  
`ddh`：对冲减仓类型订单  
after | String | 否 | 请求此ID之前（更旧的数据）的分页内容，传的值为对应接口的`ordId`  
before | String | 否 | 请求此ID之后（更新的数据）的分页内容，传的值为对应接口的`ordId`  
limit | String | 否 | 返回结果的数量，默认100条  
  
> 返回结果
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
            {
                "instType":"FUTURES",
                "instId":"BTC-USD-200329",
                "ccy":"",
                "ordId":"123445",
                "clOrdId":"b1",
                "tag":"",
                "px":"999",
                "sz":"3",
                "ordType":"limit",
                "side":"buy",
                "posSide":"long",
                "tdMode":"isolated",
                "accFillSz":"0",
                "fillPx":"0",
                "tradeId":"0",
                "fillSz":"0",
                "fillTime":"0",
                "source": "",
                "state":"filled",
                "avgPx":"0",
                "lever":"20",
                "tpTriggerPx":"",
                "tpTriggerPxType":"last",
                "tpOrdPx":"",
                "slTriggerPx":"",
                "slTriggerPxType":"last",
                "slOrdPx":"",
                "feeCcy":"",
                "fee":"",
                "rebateCcy":"",
                "rebate":"",
                "tgtCcy":"",
                "pnl":"",
                "category":"",
                "uTime":"1597026383085",
                "cTime":"1597026383085"
            }
        ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
instType | String | 产品类型  
instId | String | 产品ID  
tgtCcy | String | 市价单委托数量的类型  
`base_ccy`: 交易货币 ；`quote_ccy`：计价货币  
ccy | String | 保证金币种，仅适用于`单币种保证金模式`下的全仓`币币杠杆`订单  
ordId | String | 订单ID  
clOrdId | String | 客户自定义订单ID  
tag | String | 订单标签  
px | String | 委托价格  
sz | String | 委托数量  
ordType | String | 订单类型  
`market`：市价单  
`limit`：限价单  
`post_only`：只做maker单  
`fok`：全部成交或立即取消  
`ioc`：立即成交并取消剩余  
`optimal_limit_ioc`：市价委托立即成交并取消剩余（仅适用交割、永续）  
side | String | 订单方向  
posSide | String | 持仓方向  
tdMode | String | 交易模式  
accFillSz | String | 累计成交数量  
fillPx | String | 最新成交价格  
tradeId | String | 最新成交ID  
fillSz | String | 最新成交数量  
fillTime | String | 最新成交时间  
avgPx | String | 成交均价  
state | String | 订单状态  
`canceled`：撤单成功  
`filled`：完全成交  
lever | String | 杠杆倍数，0.01到125之间的数值，仅适用于 `币币杠杆/交割/永续`  
tpTriggerPx | String | 止盈触发价  
tpTriggerPxType | String | 止盈触发价类型  
`last`：最新价格  
`index`：指数价格  
`mark`：标记价格  
tpOrdPx | String | 止盈委托价  
slTriggerPx | String | 止损触发价  
slTriggerPxType | String | 止损触发价类型  
`last`：最新价格  
`index`：指数价格  
`mark`：标记价格  
slOrdPx | String | 止损委托价  
feeCcy | String | 交易手续费币种  
fee | String | 订单交易手续费，平台向用户收取的交易手续费，手续费扣除为`负数`。如： `-0.01`  
rebateCcy | String | 返佣金币种  
rebate | String |
返佣金额，平台向达到指定lv交易等级的用户支付的挂单奖励（返佣），如果没有返佣金，该字段为“”。手续费返佣为`正数`，如：`0.01`  
pnl | String | 收益  
source | String | 订单来源  
`13`:策略委托单触发后的生成的限价单  
category | String | 订单种类  
`normal`：普通委托  
`twap`：TWAP自动换币  
`adl`：ADL自动减仓  
`full_liquidation`：强制平仓  
`partial_liquidation`：强制减仓  
`delivery`：交割  
`ddh`：对冲减仓类型订单  
uTime | String | 订单状态更新时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
cTime | String | 订单创建时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
该接口不包含`已撤销的完全无成交`类型订单数据，可通过`获取历史订单记录（近七天)`接口获取。  

### 获取成交明细（近三天）

获取近3天的订单成交明细信息

#### 限速： 60 次/2s

#### 限速规则：UserID

#### HTTP 请求

`GET /api/v5/trade/fills`

> 请求示例
    
    
    GET /api/v5/trade/fills
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instType | String | 否 | 产品类型  
`SPOT`：币币  
`MARGIN`：币币杠杆  
`SWAP`：永续合约  
`FUTURES`：交割合约  
`OPTION`：期权  
uly | String | 否 | 标的指数  
instId | String | 否 | 产品 ID，如`BTC-USD-190927`  
ordId | String | 否 | 订单 ID  
after | String | 否 | 请求此 ID 之前（更旧的数据）的分页内容，传的值为对应接口的`billId`  
before | String | 否 | 请求此 ID 之后（更新的数据）的分页内容，传的值为对应接口的`billId`  
limit | String | 否 | 返回结果的数量，默认 100 条  
  
> 返回结果
    
    
    {
      "code": "0",
      "msg": "",
      "data": [
        {
          "instType": "FUTURES",
          "instId": "BTC-USD-200329",
          "tradeId": "123",
          "ordId": "312269865356374016",
          "clOrdId": "b16",
          "billId": "1111",
          "tag": "",
          "fillPx": "999",
          "fillSz": "3",
          "side": "buy",
          "posSide": "long",
          "execType": "M",
          "feeCcy": "",
          "fee": "",
          "ts": "1597026383085"
        },
        {
          "instType": "FUTURES",
          "instId": "BTC-USD-200329",
          "tradeId": "123",
          "ordId": "312269865356374016",
          "clOrdId": "b16",
          "billId": "1111",
          "tag": "",
          "fillPx": "999",
          "fillSz": "3",
          "side": "buy",
          "posSide": "long",
          "execType": "M",
          "feeCcy": "",
          "fee": "",
          "ts": "1597026383085"
        }
      ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
instType | String | 产品类型  
instId | String | 产品 ID  
tradeId | String | 最新成交 ID  
ordId | String | 订单 ID  
clOrdId | String | 用户自定义订单ID  
billId | String | 账单 ID  
tag | String | 订单标签  
fillPx | String | 最新成交价格  
fillSz | String | 最新成交数量  
side | String | 订单方向 `buy`：买 `sell`：卖  
posSide | String | 持仓方向 `long`：多 `short`：空 单向持仓模式返回 `net`  
execType | String | 流动性方向 `T`：taker `M`：maker  
feeCcy | String | 交易手续费币种或者返佣金币种  
fee | String | 手续费金额或者返佣金额 ，手续费扣除 为 ‘负数’，如 -0.01 ； 手续费返佣 为 ‘正数’，如 0.01  
ts | String | 成交明细产生时间，Unix 时间戳的毫秒数格式，如 `1597026383085`  
tradeId  
当成交明细所归属的订单种类（category）为 delivery：交割
、partial_liquidation：强制减仓、full_liquidation：强制平仓、adl：ADL自动减仓时，tradeId字段的值为"0"

### 获取成交明细（近三个月）

获取近3个月订单成交明细信息

#### 限速： 10 次/2s

#### 限速规则：UserID

#### HTTP 请求

`GET /api/v5/trade/fills-history`

> 请求示例
    
    
    GET /api/v5/trade/fills-history
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instType | String | 是 | 产品类型  
`SPOT`：币币  
`MARGIN`：币币杠杆  
`SWAP`：永续合约  
`FUTURES`：交割合约  
`OPTION`：期权  
uly | String | 否 | 标的指数  
instId | String | 否 | 产品 ID，如`BTC-USD-190927`  
ordId | String | 否 | 订单 ID  
after | String | 否 | 请求此 ID 之前（更旧的数据）的分页内容，传的值为对应接口的`billId`  
before | String | 否 | 请求此 ID 之后（更新的数据）的分页内容，传的值为对应接口的`billId`  
limit | String | 否 | 返回结果的数量，默认 100 条  
  
> 返回结果
    
    
    {
      "code": "0",
      "msg": "",
      "data": [
        {
          "instType": "FUTURES",
          "instId": "BTC-USD-200329",
          "tradeId": "123",
          "ordId": "312269865356374016",
          "clOrdId": "b16",
          "billId": "1111",
          "tag": "",
          "fillPx": "999",
          "fillSz": "3",
          "side": "buy",
          "posSide": "long",
          "execType": "M",
          "feeCcy": "",
          "fee": "",
          "ts": "1597026383085"
        },
        {
          "instType": "FUTURES",
          "instId": "BTC-USD-200329",
          "tradeId": "123",
          "ordId": "312269865356374016",
          "clOrdId": "b16",
          "billId": "1111",
          "tag": "",
          "fillPx": "999",
          "fillSz": "3",
          "side": "buy",
          "posSide": "long",
          "execType": "M",
          "feeCcy": "",
          "fee": "",
          "ts": "1597026383085"
        }
      ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
instType | String | 产品类型  
instId | String | 产品 ID  
tradeId | String | 最新成交 ID  
ordId | String | 订单 ID  
clOrdId | String | 用户自定义订单ID  
billId | String | 账单 ID  
tag | String | 订单标签  
fillPx | String | 最新成交价格  
fillSz | String | 最新成交数量  
side | String | 订单方向 `buy`：买 `sell`：卖  
posSide | String | 持仓方向 `long`：多 `short`：空 单向持仓模式返回 `net`  
execType | String | 流动性方向 `T`：taker `M`：maker  
feeCcy | String | 交易手续费币种或者返佣金币种  
fee | String | 手续费金额或者返佣金额 ，手续费扣除 为 ‘负数’，如 -0.01 ； 手续费返佣 为 ‘正数’，如 0.01  
ts | String | 成交明细产生时间，Unix 时间戳的毫秒数格式，如 `1597026383085`  
tradeId  
当成交明细所归属的订单种类（category）为 delivery：交割
、partial_liquidation：强制减仓、full_liquidation：强制平仓、adl：ADL自动减仓时，tradeId字段的值为"0"

### 策略委托下单

提供单向止盈止损委托、双向止盈止损委托、计划委托、冰山委托、时间加权委托、移动止盈止损委托

#### 限速： 20次/2s

#### 限速规则：衍生品：UserID +(instrumentType、underlying)

#### 限速规则：币币和币币杠杆：UserID +(instrumentType、instrumentID)

#### HTTP请求

`POST /api/v5/trade/order-algo`

> 请求示例
    
    
    POST /api/v5/trade/order-algo
    body
    {
        "instId":"BTC-USDT",
        "tdMode":"cross",
        "side":"buy",
        "ordType":"conditional",
        "sz":"2",
        "tpTriggerPx":"15",
        "tpOrdPx":"18"
    }
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instId | String | 是 | 产品ID，如 `BTC-USD-190927-5000-C`  
tdMode | String | 是 | 交易模式  
保证金模式：`isolated`：逐仓 ；`cross：`全仓  
非保证金模式：`cash`：非保证金  
ccy | String | 否 | 保证金币种，仅适用于单币种保证金模式下的全仓杠杆订单  
side | String | 是 | 订单方向 `buy`：买 `sell`：卖  
posSide | String | 否 | 持仓方向 在双向持仓模式下必填，且仅可选择 `long` 或 `short`  
ordType | String | 是 | 订单类型  
`conditional`：单向止盈止损  
`oco`：双向止盈止损  
`trigger`：计划委托  
`move_order_stop`：移动止盈止损  
`iceberg`：冰山委托  
`twap`：时间加权委托  
sz | String | 是 | 委托数量  
tag | String | 否 | 订单标签  
字母（区分大小写）与数字的组合，可以是纯字母、纯数字，且长度在1-16位之间。  
tgtCcy | String | 否 | 委托数量的类型  
`base_ccy`: 交易货币 ；`quote_ccy`：计价货币  
仅适用于`币币`单向止盈止损买单  
默认买为`计价货币`，卖为`交易货币`  
reduceOnly | Boolean | 否 | 是否只减仓 `true` 或 `false`  
  
止盈止损

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
tpTriggerPx | String | 否 | 止盈触发价，如果填写此参数，必须填写 止盈委托价  
tpTriggerPxType | String | 否 | 止盈触发价类型  
`last`：最新价格  
`index`：指数价格  
`mark`：标记价格  
默认为`last`  
tpOrdPx | String | 否 | 止盈委托价，如果填写此参数，必须填写 止盈触发价  
委托价格为-1时，执行市价止盈  
slTriggerPx | String | 否 | 止损触发价，如果填写此参数，必须填写 止损委托价  
slTriggerPxType | String | 否 | 止损触发价类型  
`last`：最新价格  
`index`：指数价格  
`mark`：标记价格  
默认为`last`  
slOrdPx | String | 否 | 止损委托价，如果填写此参数，必须填写 止损触发价  
委托价格为-1时，执行市价止损  
  
计划委托

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
triggerPx | String | 否 | 计划委托触发价格  
triggerPxType | String | 否 | 计划委托触发价格类型  
`last`：最新价格  
`index`：指数价格  
`mark`：标记价格  
默认为`last`  
orderPx | String | 否 | 委托价格  
委托价格为-1时，执行市价委托  
交割、永续合约的买卖模式下，不支持计划委托

移动止盈止损

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
callbackRatio | String | 可选 | 回调幅度的比例，如 `0.05`  
`callbackRatio`和`callbackSpread`只能传入一个  
callbackSpread | String | 可选 | 回调幅度的价距  
activePx | String | 否 | 激活价格  
  
冰山委托

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
pxVar | String | 可选 | 挂单价距离盘口的比例  
`pxVar`和`pxSpread`只能传入一个  
pxSpread | String | 可选 | 挂单价距离盘口的价距  
szLimit | String | 是 | 单笔数量  
pxLimit | String | 是 | 挂单限制价  
  
时间加权

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
pxVar | String | 可选 | 吃单价优于盘口的比例  
`pxVar`和`pxSpread`只能传入一个  
pxSpread | String | 可选 | 吃单单价优于盘口的价距  
szLimit | String | 是 | 单笔数量  
pxLimit | String | 是 | 挂单限制价  
timeInterval | String | 是 | 下单间隔  
  
了解更多关于[冰山委托和时间加权委托](/support/hc/zh-cn/articles/4408404800781)

> 返回结果
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
            {
                "algoId":"12345689",
                "sCode":"0",
                "sMsg":""
            }
        ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
algoId | String | 策略委托单ID  
sCode | String | 事件执行结果的code，0代表成功  
sMsg | String | 事件执行失败时的msg  
止盈止损  
当用户进行单向止盈止损委托（ordType=conditional）时，如果用户同时传了止盈止损四个参数，只进行止损的功能校验，忽略止盈的业务逻辑校验。

### 撤销策略委托订单

撤销策略委托订单（不包含冰山委托、时间加权、移动止盈止损等高级策略订单），每次最多可以撤销10个策略委托单

#### 限速： 20次/2s

#### 限速规则：衍生品：UserID +(instrumentType、underlying)

#### 限速规则：币币和币币杠杆：UserID +(instrumentType、instrumentID)

#### HTTP请求

`POST /api/v5/trade/cancel-algos`

> 请求示例
    
    
    POST /api/v5/trade/cancel-algos
    body
    [
        {
            "algoId":"198273485",
            "instId":"BTC-USDT"
        },
        {
            "algoId":"198273485",
            "instId":"BTC-USDT"
        }
    ]
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
algoId | String | 是 | 策略委托单ID  
instId | String | 是 | 产品ID 如 `BTC-USDT`  
  
> 返回结果
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
            {
                "algoId":"1234",
                "sCode":"0",
                "sMsg":""
            }
        ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
algoId | String | 订单ID  
sCode | String | 事件执行结果的code，0代表成功  
sMsg | String | 事件执行失败时的msg  
  
### 撤销高级策略委托订单

撤销冰山委托、时间加权、移动止盈止损委托订单，每次最多可以撤销10个策略委托单

#### 限速： 20次/2s

#### 限速规则：衍生品：UserID +(instrumentType、underlying)

#### 限速规则：币币和币币杠杆：UserID +(instrumentType、instrumentID)

#### HTTP请求

`POST /api/v5/trade/cancel-advance-algos`

> 请求示例
    
    
    POST /api/v5/trade/cancel-advance-algos
    body
    [
        {
            "algoId":"198273485",
            "instId":"BTC-USDT"
        },
        {
            "algoId":"198273485",
            "instId":"BTC-USDT"
        }
    ]
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
algoId | String | 是 | 策略委托单ID  
instId | String | 是 | 产品ID 如 `BTC-USDT`  
  
> 返回结果
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
            {
                "algoId":"1234",
                "sCode":"0",
                "sMsg":""
            }
        ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
algoId | String | 订单ID  
sCode | String | 事件执行结果的code，0代表成功  
sMsg | String | 事件执行失败时的msg  
  
### 获取未完成策略委托单列表

获取当前账户下未触发的策略委托单列表

#### 限速： 20次/2s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/trade/orders-algo-pending`

> 请求示例
    
    
    GET /api/v5/trade/orders-algo-pending?ordType=conditional
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
algoId | String | 可选 | 策略委托单ID  
instType | String | 否 | 产品类型  
`SPOT`：币币  
`SWAP`：永续合约  
`FUTURES`：交割合约  
`MARGIN`：杠杆  
instId | String | 否 | 产品ID，`BTC-USD-190927`  
ordType | String | 是 | 订单类型  
`conditional`：单向止盈止损  
`oco`：双向止盈止损  
`trigger`：计划委托  
`move_order_stop`：移动止盈止损  
`iceberg`：冰山委托  
`twap`：时间加权委托  
after | String | 否 | 请求此ID之前（更旧的数据）的分页内容，传的值为对应接口的`algoId`  
before | String | 否 | 请求此ID之后（更新的数据）的分页内容，传的值为对应接口的`algoId`  
limit | String | 否 | 返回结果的数量，默认100条  
  
> 返回结果
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
            {
                "instType":"FUTURES",
                "instId":"BTC-USD-200329",
                "ordId":"123445",
                "ccy":"BTC",
                "algoId":"1234",
                "sz":"999",
                "ordType":"oco",
                "side":"buy",
                "posSide":"long",
                "tdMode":"cross",
                "tgtCcy": "",
                "state":"1",
                "lever":"20",
                "tpTriggerPx":"",
                "tpTriggerPxType":"",
                "tpOrdPx":"",
                "slTriggerPx":"",
                "slTriggerPxType":"",
                "triggerPx":"99",
                "triggerPxType": "last",
                "ordPx":"12",
                "actualSz":"",
                "actualPx":"",
                "actualSide":"",
                "pxVar":"",
                "pxSpread":"",
                "pxLimit":"",
                "szLimit":"",
                "tag": "adadadadad",
                "timeInterval":"",
                "triggerTime":"1597026383085",
                "callbackRatio":"",
                "callbackSpread":"",
                "activePx":"",
                "moveTriggerPx":"",
                "cTime":"1597026383000"
            },
            {
                "instType":"FUTURES",
                "instId":"BTC-USD-200329",
                "ordId":"123445",
                "ccy":"BTC",
                "algoId":"1234",
                "sz":"999",
                "ordType":"oco",
                "side":"buy",
                "posSide":"long",
                "tdMode":"cross",
                "tgtCcy": "",
                "state":"1",
                "lever":"20",
                "tpTriggerPx":"",
                "tpTriggerPxType":"",
                "tpOrdPx":"",
                "slTriggerPx":"",
                "slTriggerPxType":"",
                "triggerPx":"99",
                "triggerPxType": "last",
                "ordPx":"12",
                "actualSz":"",
                "actualPx":"",
                "actualSide":"",
                "pxVar":"",
                "pxSpread":"",
                "pxLimit":"",
                "szLimit":"",
                "tag": "adadadadad",
                "timeInterval":"",
                "triggerTime":"1597026383085",
                "callbackRatio":"",
                "callbackSpread":"",
                "activePx":"",
                "moveTriggerPx":"",
                "cTime":"1597026383000"
            }
        ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
instType | String | 产品类型  
instId | String | 产品ID  
ccy | String | 保证金币种，仅适用于单币种保证金模式下的全仓杠杆订单  
ordId | String | 订单ID  
algoId | String | 策略委托单ID  
sz | String | 委托数量  
ordType | String | 订单类型  
side | String | 订单方向  
posSide | String | 持仓方向  
tdMode | String | 交易模式  
tgtCcy | String | 市价单委托数量的类型  
`base_ccy`: 交易货币 ；`quote_ccy`：计价货币  
state | String | 订单状态 ，`live`：待生效 `pause`：暂停生效 `partially_effective`:部分生效  
lever | String | 杠杆倍数  
tpTriggerPx | String | 止盈触发价  
tpTriggerPxType | String | 止盈触发价类型  
`last`：最新价格  
`index`：指数价格  
`mark`：标记价格  
tpOrdPx | String | 止盈委托价  
slTriggerPx | String | 止损触发价  
slTriggerPxType | String | 止损触发价类型  
`last`：最新价格  
`index`：指数价格  
`mark`：标记价格  
slOrdPx | String | 止损委托价  
triggerPx | String | 计划委托触发价格  
triggerPxType | String | 计划委托触发价类型  
`last`：最新价格  
`index`：指数价格  
`mark`：标记价格  
ordPx | String | 计划委托委托价格  
actualSz | String | 实际委托量  
actualPx | String | 实际委托价  
actualSide | String | 实际触发方向， `tp`：止盈 `sl`： 止损  
triggerTime | String | 策略委托触发时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
pxVar | String | 价格比例  
仅适用于`冰山委托`和`时间加权委托`  
pxSpread | String | 价距  
仅适用于`冰山委托`和`时间加权委托`  
szLimit | String | 单笔数量  
仅适用于`冰山委托`和`时间加权委托`  
tag | String | 订单标签  
字母（区分大小写）与数字的组合，可以是纯字母、纯数字，且长度在1-16位之间。  
pxLimit | String | 挂单限制价  
仅适用于`冰山委托`和`时间加权委托`  
timeInterval | String | 下单间隔  
仅适用于`时间加权委托`  
callbackRatio | String | 回调幅度的比例  
仅适用于`移动止盈止损`  
callbackSpread | String | 回调幅度的价距  
仅适用于`移动止盈止损`  
activePx | String | 移动止盈止损激活价格  
仅适用于`移动止盈止损`  
moveTriggerPx | String | 移动止盈止损触发价格  
仅适用于`移动止盈止损`  
cTime | String | 订单创建时间， Unix时间戳的毫秒数格式，如 `1597026383085`  
  
### 获取历史策略委托单列表

获取最近3个月当前账户下所有策略委托单列表

#### 限速： 20次/2s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/trade/orders-algo-history`

> 请求示例
    
    
    GET /api/v5/trade/orders-algo-history?state=effective&ordType=conditional
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
ordType | String | 是 | 订单类型  
`conditional`：单向止盈止损  
`oco`：双向止盈止损  
`trigger`：计划委托  
`move_order_stop`：移动止盈止损  
`iceberg`：冰山委托  
`twap`：时间加权委托  
state | String | 可选 | 订单状态  
  
`effective`：已生效  
`canceled`：已经撤销  
`order_failed`：委托失败  
【state和algoId必填且只能填其一】  
algoId | String | 可选 | 策略委托单ID 【`state`和`algoId`必填且只能填其一】  
instType | String | 否 | 产品类型  
`SPOT`：币币  
`SWAP`：永续合约  
`FUTURES`：交割合约  
`MARGIN`：杠杆  
instId | String | 否 | 产品ID，`BTC-USD-190927`  
after | String | 否 | 请求此ID之前（更旧的数据）的分页内容，传的值为对应接口的`algoId`  
before | String | 否 | 请求此ID之后（更新的数据）的分页内容，传的值为对应接口的`algoId`  
limit | String | 否 | 返回结果的数量，默认100条  
  
> 返回结果
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
            {
                "instType":"FUTURES",
                "instId":"BTC-USD-200329",
                "ordId":"123445",
                "ccy":"BTC",
                "algoId":"1234",
                "sz":"999",
                "ordType":"oco",
                "side":"buy",
                "posSide":"long",
                "tdMode":"cross",
                "tgtCcy": "",
                "state":"effective",
                "lever":"20",
                "tpTriggerPx":"",
                "tpTriggerPxType":"",
                "tpOrdPx":"",
                "slTriggerPx":"",
                "slTriggerPxType":"",
                "triggerPx":"99",
                "triggerPxType":"last",
                "ordPx":"12",
                "actualSz":"",
                "actualPx":"",
                "actualSide":"",
                "pxVar":"",
                "pxSpread":"",
                "pxLimit":"",
                "szLimit":"",
                "tag": "adadadadad",
                "timeInterval":"",
                "callbackRatio":"",
                "callbackSpread":"",
                "activePx":"",
                "moveTriggerPx":"",
                "triggerTime":"1597026383085",
                "cTime":"1597026383000"
            },
            {
                "instType":"FUTURES",
                "instId":"BTC-USD-200329",
                "ordId":"123445",
                "ccy":"BTC",
                "algoId":"1234",
                "sz":"999",
                "ordType":"oco",
                "side":"buy",
                "posSide":"long",
                "tdMode":"cross",
                "tgtCcy": "",
                "state":"effective",
                "lever":"20",
                "tpTriggerPx":"",
                "tpTriggerPxType":"",
                "tpOrdPx":"",
                "slTriggerPx":"",
                "slTriggerPxType":"",
                "triggerPx":"99",
                "triggerPxType":"last",
                "ordPx":"12",
                "actualSz":"",
                "actualPx":"",
                "actualSide":"",
                "pxVar":"",
                "pxSpread":"",
                "pxLimit":"",
                "szLimit":"",
                "tag": "adadadadad",
                "timeInterval":"",
                "callbackRatio":"",
                "callbackSpread":"",
                "activePx":"",
                "moveTriggerPx":"",
                "triggerTime":"1597026383085",
                "cTime":"1597026383000"
            }
        ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
instType | String | 产品类型  
instId | String | 产品ID  
ccy | String | 保证金币种，仅适用于单币种保证金模式下的全仓杠杆订单  
ordId | String | 订单ID  
algoId | String | 策略委托单ID  
sz | String | 委托数量  
ordType | String | 订单类型  
side | String | 订单方向  
posSide | String | 持仓方向  
tdMode | String | 交易模式  
tgtCcy | String | 市价单委托数量的类型  
`base_ccy`: 交易货币 ；`quote_ccy`：计价货币  
state | String | 订单状态  
`effective`： 已生效  
`canceled`：已撤销  
`order_failed`：委托失败  
lever | String | 杠杆倍数  
tpTriggerPx | String | 止盈触发价  
tpTriggerPxType | String | 止盈触发价类型  
`last`：最新价格  
`index`：指数价格  
`mark`：标记价格  
tpOrdPx | String | 止盈委托价  
slTriggerPx | String | 止损触发价  
slTriggerPxType | String | 止损触发价类型  
`last`：最新价格  
`index`：指数价格  
`mark`：标记价格  
slOrdPx | String | 止损委托价  
triggerPx | String | 计划委托触发价格  
triggerPxType | String | 计划委托触发价格  
ordPx | String | 计划委托委托价格类型  
`last`：最新价格  
`index`：指数价格  
`mark`：标记价格  
actualSz | String | 实际委托量  
actualPx | String | 实际委托价  
actualSide | String | 实际触发方向 `tp`：止盈 `sl`： 止损  
triggerTime | String | 策略委托触发时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
pxVar | String | 价格比例  
仅适用于`冰山委托`和`时间加权委托`  
pxSpread | String | 价距  
仅适用于`冰山委托`和`时间加权委托`  
szLimit | String | 单笔数量  
仅适用于`冰山委托`和`时间加权委托`  
pxLimit | String | 挂单限制价  
仅适用于`冰山委托`和`时间加权委托`  
tag | String | 订单标签  
字母（区分大小写）与数字的组合，可以是纯字母、纯数字，且长度在1-16位之间。  
timeInterval | String | 下单间隔  
仅适用于`时间加权委托`  
callbackRatio | String | 回调幅度的比例  
仅适用于`移动止盈止损`  
callbackSpread | String | 回调幅度的价距  
仅适用于`移动止盈止损`  
activePx | String | 移动止盈止损激活价格  
仅适用于`移动止盈止损`  
moveTriggerPx | String | 移动止盈止损触发价格  
仅适用于`移动止盈止损`  
cTime | String | 订单创建时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
  
## 资金

`资金`功能模块下的API接口需要身份验证。

### 获取币种列表

获取平台所有币种列表。

#### 限速： 6 次/s

#### 限速规则：UserID

#### HTTP 请求

`GET /api/v5/asset/currencies`

> 请求示例
    
    
    GET /api/v5/asset/currencies
    
    

#### 请求参数

无

> 返回结果
    
    
    {
      "code": "0",
      "msg": "",
      "data": [
        {
          "canDep": true,
          "canInternal": true,
          "canWd": true,
          "ccy": "USDT",
          "chain": "USDT-ERC20",
          "logoLink": "https://static.coinall.ltd/cdn/announce/20200522/159014965610216037408-525c-4143-8eef-003e2edf6859.png",
          "mainNet": false,
          "maxFee": "18.6742688",
          "maxWd": "21720100",
          "minFee": "9.3371344",
          "minWd": "2",
          "name": "Tether",
          "usedWdQuota": "0",
          "wdQuota": "500",
          "wdTickSz": "3"
        }
      ]
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
ccy | String | 币种名称，如 `BTC`  
name | String | 币种中文名称，不显示则无对应名称  
logoLink | String | 币种Logo链接  
chain | String | 币种链信息  
有的币种下有多个链，必须要做区分，如`USDT`下有`USDT-ERC20`，`USDT-TRC20`，`USDT-Omni`多个链  
canDep | Boolean | 是否可充值，`false`表示不可链上充值，`true`表示可以链上充值  
canWd | Boolean | 是否可提币，`false`表示不可链上提币，`true`表示可以链上提币  
canInternal | Boolean | 是否可内部转账，`false`表示不可内部转账，`true`表示可以内部转账  
minWd | String | 币种单笔最小提币量  
maxWd | String | 币种单笔最大提币量  
wdTickSz | String | 提币精度,表示小数点后的位数  
wdQuota | String | 过去24小时内提币额度，单位为`BTC`  
usedWdQuota | String | 过去24小时内已用提币额度，单位为`BTC`  
minFee | String | 最小提币手续费数量  
maxFee | String | 最大提币手续费数量  
mainNet | Boolean | 当前链是否为主链  
如果是则返回`true`，否则返回`false`  
  
### 获取资金账户余额

获取资金账户所有资产列表，查询各币种的余额、冻结和可用等信息。

只返回余额大于0的币资产信息。

#### 限速： 6次/s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/asset/balances`

> 请求示例
    
    
    GET /api/v5/asset/balances
    
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
ccy | String | 否 | 币种，如 `BTC`  
支持多币种查询（不超过20个），币种之间半角逗号分隔  
  
> 返回结果
    
    
    {
        "code": "0",
        "msg": "",
        "data": [{
                "availBal": "37.11827078",
                "bal": "37.11827078",
                "ccy": "ETH",
                "frozenBal": "0"
            }
        ]
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
ccy | String | 币种，如 `BTC`  
bal | String | 余额  
frozenBal | String | 冻结（不可用）  
availBal | String | 可用余额  
  
### 获取账户资产估值

查看账户资产估值

#### 限速： 1次/2s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/asset/asset-valuation`

> 请求示例
    
    
    GET /api/v5/asset/asset-valuation
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
ccy | String | 否 | 资产估值对应的单位  
BTC 、USDT  
USD 、CNY 、JPY、KRW、RUB、EUR  
VND 、IDR 、INR、PHP、THB、TRY  
AUD 、SGD 、ARS、SAR、AED、IQD  
默认为 BTC 为单位的估值  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "details": {
                    "classic": "124.6",
                    "earn": "1122.73",
                    "funding": "0.09",
                    "trading": "2544.28"
                },
                "totalBal": "3790.09",
                "ts": "1637566660769"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
totalBal | String | 账户总资产估值  
ts | String | 数据更新时间，Unix时间戳的毫秒数格式，如 1597026383085  
details | Array | 各个账户的资产估值  
> funding | String | 资金账户  
> trading | String | 交易账户  
> classic | String | 经典账户  
> earn | String | 金融账户  
  
### 资金划转

支持母账户的资金账户划转到交易账户，母账户到子账户的资金账户和交易账户划转；

子账户默认可转出至母账户，划转到同一母账户下的其他子账户，需要先调用“设置子账户转出权限”接口进行授权。

#### 限速： 1 次/s

#### 限速规则：UserID + Currency

#### HTTP 请求

`POST /api/v5/asset/transfer`

> 请求示例
    
    
    母账户USDT从资金账户划转1.5USDT到交易账户
    POST /api/v5/asset/transfer
    body 
    {
        "ccy":"USDT",
        "amt":"1.5",
        "from":"6",
        "to":"18"
    }
    
    母账户从资金账户划转1.5USDT到子账户的交易账户
    POST /api/v5/asset/transfer
    body 
    {
        "ccy":"USDT",
        "type":"1",
        "amt":"1.5",
        "from":"6",
        "to":"6",
        "subAcct":"mini"
    }
    
    子账户从资金账户划转1.5USDT到另一子账户的资金账户
    POST /api/v5/asset/transfer
    body 
    {
        "ccy":"USDT",
        "type":"4",
        "amt":"1.5",
        "from":"6",
        "to":"6",
        "subAcct":"mini"
    }
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
ccy | String | 是 | 币种，如 `USDT`  
amt | String | 是 | 划转数量  
from | String | 是 | 转出账户  
`6`：资金账户 `18`：交易账户  
to | String | 是 | 转入账户  
`6`：资金账户 `18`：交易账户  
subAcct | String | 可选 | 子账户名称，type 为`1`或`2`：subAcct 为必填项  
type | String | 否 | `0`：账户内划转  
`1`：母账户转子账户(仅适用于母账户APIKey)  
`2`：子账户转母账户(仅适用于母账户APIKey)  
`3`：子账户转母账户(仅适用于子账户APIKey)  
`4`：子账户转子账户(仅适用于子账户APIKey，且目标账户需要是同一母账户下的其他子账户)  
loanTrans | Boolean | 否 | 是否支持`跨币种保证金模式`或`组合保证金模式`下的借币转入/转出  
true 或 false，默认false  
clientId | String | 否 | 客户自定义ID  
字母（区分大小写）与数字的组合，可以是纯字母、纯数字且长度要在1-32位之间。  
  
> 返回结果
    
    
    {
      "code": "0",
      "msg": "",
      "data": [
        {
          "transId": "754147",
          "ccy": "USDT",
          "clientId": "",
          "from": "6",
          "amt": "0.1",
          "to": "18"
        }
      ]
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
transId | String | 划转 ID  
ccy | String | 划转币种  
from | String | 转出账户  
amt | String | 划转量  
to | String | 转入账户  
clientId | String | 客户自定义ID  
  
### 获取资金划转状态

#### 限速： 10 次/s

#### 限速规则：UserID

#### HTTP 请求

`GET /api/v5/asset/transfer-state`

> 请求示例
    
    
    GET /api/v5/asset/transfer-state?transId=1&type=1
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
transId | String | 可选 | 划转ID  
transId和clientId必须传一个，若传两个，以transId为主  
clientId | String | 可选 | 客户自定义ID  
type | String | 否 | `0`：账户内划转  
`1`：母账户转子账户  
`2`：子账户转母账户  
默认为`0`。  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "amt": "1.5",
                "ccy": "USDT",
                "clientId": "",
                "from": "18",
                "instId": "",
                "state": "success",
                "subAcct": "test",
                "to": "6",
                "toInstId": "",
                "transId": "1",
                "type": "1"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
type | String | `0`：账户内划转  
`1`：母账户转子账户  
`2`：子账户转母账户  
transId | String | 划转 ID  
clientId | String | 客户自定义ID  
ccy | String | 划转币种  
from | String | 转出账户  
amt | String | 划转量  
to | String | 转入账户  
subAcct | String | 子账户名称  
instId | String | 币币杠杆转出币对（如 `BTC-USDT`）或者转出合约的 underlying（如 `BTC-USD`）  
toInstId | String | 币币杠杆转入币对（如 `BTC-USDT`）或者转入合约的 underlying（如 `BTC-USD`）  
state | String | 转账状态  
成功：`success`，处理中：`pending`，失败：`failed`  
  
### 获取资金流水

查询资金账户账单流水，可查询最近一个月的数据。

#### 限速：6 次/s

#### 限速规则：UserID

#### HTTP 请求

`GET /api/v5/asset/bills`

> 请求示例
    
    
    GET /api/v5/asset/bills
    
    GET /api/v5/asset/bills?type=1
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
ccy | String | 否 | 币种  
type | String | 否 | 账单类型  
`1`：充值  
`2`：提现  
`13`：撤销提现  
`20`：转出至子账户  
`21`：从子账户转入  
`28`：领取  
`41`：点卡抵扣手续费  
`42`：购买点卡  
`47`：系统冲正  
`48`：活动得到  
`49`：活动送出  
`50`：预约得到  
`51`：预约扣除  
`52`：发红包  
`53`：抢红包  
`54`：红包退还  
`59`：从套保账户转入  
`60`：转出至套保账户  
`61`：兑换  
`68`：领取卡券权益  
`69`：发送卡券权益  
`72`：收币  
`73`：送币  
`74`：送币退还  
`75`：申购余币宝  
`76`：赎回余币宝  
`77`：派发  
`78`：锁定  
`79`：节点投票  
`80`：锁仓挖矿  
`81`：投票赎回  
`82`：锁仓赎回  
`83`：锁仓挖矿收益  
`84`：违约金  
`85`：算力挖矿收益  
`86`：云算力支付  
`87`：云算力收益  
`88`：补贴收益  
`89`：存币收益  
`90`：挖矿申购  
`91`：挖矿赎回  
`92`：补充质押物  
`93`：赎回质押物  
`94`：投资  
`95`：借款人借款  
`96`：投资本金转入  
`97`：借款人借款转出  
`98`：借款人借款利息转出  
`99`：投资人投资利息转入  
`102`：提前还款违约金转入  
`103`：提前还款违约金转出  
`104`：手续费转入  
`105`：手续费转出  
`106`：逾期手续费转入  
`107`：逾期手续费转出  
`108`：逾期利息转出  
`109`：借款还款逾期利息转入  
`110`：平仓质押物转入到系统账号  
`111`：平仓质押物转出到系统账号  
`112`：爆仓质押物转入到系统账号  
`113`：爆仓质押物转出到系统账号  
`114`：风险准备金转入  
`115`：风险准备金转出  
`116`：创建订单  
`117`：完成订单  
`118`：取消订单  
`119`：商家解冻保证金  
`120`：商家添加保证金  
`121`：FiatGateway 创建订单  
`122`：FiatGateway 取消订单  
`123`：FiatGateway 完成订单  
`124`：Jumpstart 解锁  
`125`：手动注入  
`126`：利息注入  
`127`：投资手续费转入  
`128`：投资手续费转出  
`129`：奖励转入  
`130`：从交易账户转入  
`131`：转出至交易账户  
`150`：节点返佣  
`151`：邀请奖励  
`198`：无效资产减少  
`199`：有效资产增加  
clientId | String | 否 | 客户自定义ID  
字母（区分大小写）与数字的组合，可以是纯字母、纯数字且长度要在1-32位之间。  
after | String | 否 | 查询在此之前的内容，值为时间戳，Unix 时间戳为毫秒数格式，如 `1597026383085`  
before | String | 否 | 查询在此之后的内容，值为时间戳，Unix 时间戳为毫秒数格式，如 `1597026383085`  
limit | String | 否 | 分页返回的结果集数量，最大为 100，不填默认返回 100 条  
  
> 返回结果
    
    
    {
      "code": "0",
      "msg": "",
      "data": [
        {
          "billId": "12344",
          "ccy": "BTC",
          "clientId": "",
          "balChg": "2",
          "bal": "12",
          "type": "1",
          "ts": "1597026383085"
        }
      ]
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
billId | String | 账单 ID  
ccy | String | 账户余额币种  
clientId | String | 客户自定义ID  
balChg | String | 账户层面的余额变动数量  
bal | String | 账户层面的余额数量  
type | String | 账单类型  
ts | String | 账单创建时间，Unix 时间戳的毫秒数格式，如 `1597026383085`  
  
### 闪电网络充币

一个用户在最近24小时内可以生成不超过1万个不同的invoice。

#### 限速： 2次/s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/asset/deposit-lightning`

> 请求示例
    
    
    GET /api/v5/asset/deposit-lightning
    
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
ccy | String | 是 | 币种，仅支持`BTC`  
amt | String | 是 | 充值数量，推荐在0.000001〜0.05之间  
to | String | 否 | 资金充值到账账户  
6:资金账户  
18:交易账户  
不填写此参数，默认到账资金账户  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "cTime": "1631171307612",
                "invoice": "lnbc100u1psnnvhtpp5yq2x3q5hhrzsuxpwx7ptphwzc4k4wk0j3stp0099968m44cyjg9sdqqcqzpgxqzjcsp5hzzdszuv6yv6yw5svctl8kc8uv6y77szv5kma2kuculj86tk3yys9qyyssqd8urqgcensh9l4zwlwr3lxlcdqrlflvvlwldutm6ljx486h7lylqmd06kky6scas7warx69sregzrx20ffmsr4sp865x3wasrjd8ttgqrlx3tr"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
invoice | String | invoice 号码  
cTime | String | 生成invoice时间  
仅针对部分用户开放此API功能服务，如果需要此功能服务请发邮件至`liz.jensen@okg.com`申请

### 获取充值地址信息

获取各个币种的充值地址，包括曾使用过的老地址。

IOTA充值地址不能重复使用！在向IOTA地址发起充值后，再次充值到此相同地址将不会被确认到账。

#### 限速： 6次/s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/asset/deposit-address`

> 请求示例
    
    
    GET /api/v5/asset/deposit-address?ccy=BTC
    
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
ccy | String | 是 | 币种，如`BTC`  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "chain": "BTC-Bitcoin",
                "ctAddr": "",
                "ccy": "BTC",
                "to": "6",
                "addr": "39XNxK1Ryqgg3Bsyn6HzoqV4Xji25pNkv6",
                "selected": true
            },
            {
                "chain": "BTC-OKC",
                "ctAddr": "",
                "ccy": "BTC",
                "to": "6",
                "addr": "0x66d0edc2e63b6b992381ee668fbcb01f20ae0428",
                "selected": true
            },
            {
                "chain": "BTC-ERC20",
                "ctAddr": "5807cf",
                "ccy": "BTC",
                "to": "6",
                "addr": "0x66d0edc2e63b6b992381ee668fbcb01f20ae0428",
                "selected": true
            }
        ],
        "msg": ""
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
addr | String | 充值地址  
tag | String | 部分币种充值需要标签，若不需要则不返回此字段  
memo | String | 部分币种充值需要标签，若不需要则不返回此字段  
pmtId | String | 部分币种充值需要此字段（payment_id），若不需要则不返回此字段  
addrEx | Object | 充值地址备注，部分币种充值需要，若不需要则不返回此字段  
如币种`TONCOIN`的充值地址备注标签名为`comment`,则该字段返回：{'comment':'123456'}  
ccy | String | 币种，如`BTC`  
chain | String | 币种链信息  
有的币种下有多个链，必须要做区分，如`USDT`下有`USDT-ERC20`，`USDT-TRC20`，`USDT-Omni`多个链  
to | String | 转入账户  
`6`：资金账户 `18`：交易账户  
selected | Boolean | 该地址是否为页面选中的地址  
ctAddr | String | 合约地址后6位  
  
### 获取充值记录

根据币种，充值状态，时间范围获取充值记录，按照时间倒序排列，默认返回 100 条数据。

#### 限速： 6 次/s

#### 限速规则：UserID

#### HTTP 请求

`GET /api/v5/asset/deposit-history`

> 请求示例
    
    
    查询最近的充值记录
    GET /api/v5/asset/deposit-history
    
    查询从2018年09月29日到2018年10月30日之间的BTC的充值记录
    GET /api/v5/asset/deposit-history?ccy=BTC&after=1597026383085&before=1597026383085
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
ccy | String | 否 | 币种名称，如 `BTC`  
depId | String | 否 | 充值记录 ID  
txId | String | 否 | 区块转账哈希记录  
state | String | 否 | 充值状态  
`0`：等待确认 `1`：确认到账 `2`：充值成功  
after | String | 否 | 查询在此之前的内容，值为时间戳，Unix 时间戳为毫秒数格式，如 `1597026383085`  
before | String | 否 | 查询在此之后的内容，值为时间戳，Unix 时间戳为毫秒数格式，如 `1597026383085`  
limit | string | 否 | 返回的结果集数量，默认为100，最大为100，不填默认返回100条  
  
> 返回结果
    
    
    {
      "code": "0",
      "msg": "",
      "data": [
        {
          "amt": "0.01044408",
          "txId": "1915737_3_0_0_asset",
          "ccy": "BTC",
          "chain":"BTC-Bitcoin",
          "from": "13801825426",
          "to": "",
          "ts": "1597026383085",
          "state": "2",
          "depId": "4703879"
        }
      ]
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
ccy | String | 币种名称，如 `BTC`  
chain | String | 币种链信息  
有的币种下有多个链，必须要做区分，如`USDT`下有`USDT-ERC20`，`USDT-TRC20`，`USDT-Omni`多个链  
amt | String | 充值数量  
from | String | 充值地址，只显示内部账户转账地址，不显示区块链充值地址  
to | String | 到账地址  
txId | String | 区块转账哈希记录  
ts | String | 充值到账时间，Unix 时间戳的毫秒数格式，如 `1597026383085`  
state | String | 充值状态  
`0`：等待确认  
`1`：确认到账  
`2`：充值成功  
`8`：因该币种暂停充值而未到账，恢复充值后自动到账  
`8`：账户或充值被冻结  
depId | String | 充值记录 ID  
等待确认是没有达到充币确认数。 确认到账是够充币确认数，且币已经到账户中，但是不可提。 充值成功是当前账户完成到提币确认，可以提出。

### 提币

用户提币。

#### 限速： 6次/s

#### 限速规则：UserID

#### HTTP请求

`POST /api/v5/asset/withdrawal`

> 请求示例
    
    
    POST /api/v5/asset/withdrawal
    body
    {
        "amt":"1",
        "fee":"0.0005",
        "dest":"4",
        "ccy":"BTC",
        "chain":"BTC-Bitcoin",
        "toAddr":"17DKe3kkkkiiiiTvAKKi2vMPbm1Bz3CMKw"
    }
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
ccy | String | 是 | 币种，如 `USDT`  
amt | String | 是 | 数量  
dest | String | 是 | 提币到  
`3`：OKX  
`4`：数字货币地址  
toAddr | String | 是 | 认证过的数字货币地址、邮箱或手机号。  
某些数字货币地址格式为:地址+标签，如 `ARDOR-7JF3-8F2E-QUWZ-CAN7F:123456`  
fee | String | 是 | 网络手续费≥`0`，提币到数字货币地址所需网络手续费可通过获取币种列表接口查询  
chain | String | 可选 | 币种链信息  
如`USDT`下有`USDT-ERC20`，`USDT-TRC20`，`USDT-Omni`多个链  
如果没有不填此参数，则默认为主链  
clientId | String | 否 | 客户自定义ID  
字母（区分大小写）与数字的组合，可以是纯字母、纯数字且长度要在1-32位之间。  
关于标签：某些币种如XRP充币时同时需要一个充值地址和标签（又名memo/payment_id），标签是一种保证您的充币地址唯一性的数字串，与充币地址成对出现并一一对应。请您务必遵守正确的充值步骤，在提币时输入完整信息，否则将面临丢失币的风险！

> 返回结果
    
    
    {
        "code": "0",
        "msg": "",
        "data": [{
            "amt": "0.1",
            "wdId": "67485",
            "ccy": "BTC",
            "clientId": "",
            "chain": "BTC-Bitcoin"
        }]
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
ccy | String | 提币币种  
chain | String | 币种链信息  
有的币种下有多个链，必须要做区分，如`USDT`下有`USDT-ERC20`，`USDT-TRC20`，`USDT-Omni`多个链  
amt | String | 提币数量  
wdId | String | 提币申请ID  
clientId | String | 客户自定义ID  
  
### 闪电网络提币

单笔提币金额最大值为"0.1BTC"，最小值暂定为"0.000001BTC"，最近24小时内最大提币数量为"1BTC"。

#### 限速： 2次/s

#### 限速规则：UserID

#### HTTP请求

`POST /api/v5/asset/withdrawal-lightning`

> 请求示例
    
    
    POST /api/v5/asset/withdrawal-lightning
    body
    {
        "ccy":"BTC",
        "invoice":"lnbc100u1psnnvhtpp5yq2x3q5hhrzsuxpwx7ptphwzc4k4wk0j3stp0099968m44cyjg9sdqqcqzpgxqzjcsp5hz"
    }
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
ccy | String | 是 | 币种，如 `BTC`  
invoice | String | 是 | invoice 号码  
memo | String | 否 | 闪电网络提币的备注  
  
> 返回结果
    
    
    {
            "code": "0",
            "msg": "",
            "data": [{
                    "wdId": "121212",
                    "cTime": "1597026383085"
            }]
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
wdId | String | 提币申请ID  
cTime | String | 提币ID生成时间  
仅针对部分用户开放此API功能服务，如果需要此功能服务请发邮件至`liz.jensen@okg.com`申请

### 撤销提币

撤销用户提币。

#### 限速： 6次/s

#### 限速规则：UserID

#### HTTP请求

`POST /api/v5/asset/cancel-withdrawal`

> 请求示例
    
    
    POST /api/v5/asset/cancel-withdrawal
    body {
       "wdId":"1123456"
    }
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
wdId | String | 是 | 提币申请ID  
  
> 返回结果
    
    
    {
      "code": "0",
      "msg": "",
      "data": [
        {
          "wdId": "1123456"   
        }
      ]
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
wdId | String | 提币申请ID  
接口返回code等于0不能严格认为提币已经被撤销，只表示您的请求被系统服务器所接受，实际结果以获取提币记录中的状态为准。

### 获取提币记录

根据币种，提币状态，时间范围获取提币记录，按照时间倒序排列，默认返回100条数据。

#### 限速： 6 次/s

#### 限速规则：UserID

#### HTTP 请求

`GET /api/v5/asset/withdrawal-history`

> 请求示例
    
    
    查询最近的提币记录
    GET /api/v5/asset/withdrawal-history
    
    查询从2018年09月29日到2018年10月30日之间的BTC的提币记录
    GET /api/v5/asset/withdrawal-history?ccy=BTC&after=1597026383085&before=1597026383085
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
ccy | String | 否 | 币种名称，如 `BTC`  
wdId | String | 否 | 提币申请ID  
clientId | String | 否 | 客户自定义ID  
字母（区分大小写）与数字的组合，可以是纯字母、纯数字且长度要在1-32位之间。  
txId | String | 否 | 区块转账哈希记录  
state | String | 否 | 提币状态  
`-3`：撤销中 `-2`：已撤销 `-1`：失败  
`0`：等待提现 `1`：提现中 `2`：已汇出  
`3`：邮箱确认 `4`：人工审核中 `5`：等待身份认证  
after | String | 否 | 查询在此之前的内容，值为时间戳，Unix 时间戳为毫秒数格式，如 `1597026383085`  
before | String | 否 | 查询在此之后的内容，值为时间戳，Unix 时间戳为毫秒数格式，如 `1597026383085`  
limit | string | 否 | 返回的结果集数量，默认为100，最大为100，不填默认返回100条  
  
> 返回结果
    
    
    {
      "code": "0",
      "msg": "",
      "data": [
        {
          "chain": "ETH-Ethereum",
          "fee": "0.007",
          "ccy": "ETH",
          "clientId": "",
          "amt": "0.029809",
          "txId": "0x35c******b360a174d",
          "from": "156****359",
          "to": "0xa30d1fab********7CF18C7B6C579",
          "state": "2",
          "ts": "1622******2000",
          "wdId": "15447421"
        }
      ]
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
ccy | String | 币种  
chain | String | 币种链信息  
有的币种下有多个链，必须要做区分，如`USDT`下有`USDT-ERC20`，`USDT-TRC20`，`USDT-Omni`多个链  
amt | String | 数量  
ts | String | 提币申请时间，Unix 时间戳的毫秒数格式，如 `1597026383085`  
from | String | 提币地址（如果收币地址是 OKX 平台地址，则此处将显示用户账户）  
to | String | 收币地址  
tag | String | 部分币种提币需要标签，若不需要则不返回此字段  
pmtId | String | 部分币种提币需要此字段（payment_id），若不需要则不返回此字段  
memo | String | 部分币种提币需要此字段，若不需要则不返回此字段  
txId | String | 提币哈希记录（内部转账将不返回此字段）  
fee | String | 提币手续费  
state | String | 提币状态  
`-3`：撤销中 `-2`：已撤销 `-1`：失败  
`0`：等待提现 `1`：提现中 `2`：已汇出  
`3`：邮箱确认 `4`：人工审核中 `5`：等待身份认证  
wdId | String | 提币申请ID  
clientId | String | 客户自定义ID  
  
### 小额资产兑换

将资金账户中的小额资产转化为`OKB`。24小时之内只能兑换一次。

#### 限速： 6次/s

#### 限速规则：UserID

#### HTTP请求

`POST /api/v5/asset/convert-dust-assets`

> 请求示例
    
    
    POST /api/v5/asset/convert-dust-assets
    body {
       "ccy":["BTC","USDT"]
    }
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
ccy | Array | 是 | 需要转换的币种资产  
  
> 返回结果
    
    
    {
      "code": "0",
      "data": [
        {
          "details": [
            {
                "amt": "1",
                "ccy": "USDT",
                "cnvAmt": "0.04771642808422",
                "fee": "0.00097380465478"
            }
          ],
          "totalCnvAmt": "0.04771642"
        }
      ],
      "msg": ""
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
totalCnvAmt | String | 兑换后总`OKB`数量  
details | Array | 各币种资产转换详情  
> ccy | String | 币种资产,如 `BTC`  
> amt | String | 转换前币种资产数量  
> cnvAmt | String | 转换后的`OKB`数量  
> fee | String | 兑换手续费，单位为`OKB`  
  
### 获取余币宝余额

#### 限速： 6次/s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/asset/saving-balance`

> 请求示例
    
    
    GET /api/v5/asset/saving-balance?ccy=BTC
    
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
ccy | String | 否 | 币种，如 `BTC`  
  
> 返回结果
    
    
    {
        "code": "0",
        "msg":"",
        "data": [
            {
                "earnings": "0.0010737388791526",
                "redemptAmt": "0.0000000000000000",
                "rate": "0.0100000000000000",
                "ccy": "USDT",
                "amt": "11.0010737453457821",
                "loanAmt": "11.0010630707982819",
                "pendingAmt": "0.0000106745475002"
            }
        ]
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
ccy | String | 币种，如 `BTC`  
amt | String | 币种数量  
earnings | String | 币种持仓收益  
rate | String | 最新出借利率  
loanAmt | String | 已出借数量  
pendingAmt | String | 未出借数量  
redemptAmt | String | 赎回中的数量  
  
### 余币宝申购/赎回

#### 限速： 6次/s

#### 限速规则：UserID

#### HTTP请求

`POST /api/v5/asset/purchase_redempt`

> 请求示例
    
    
    POST /api/v5/asset/purchase_redempt
    body
    {
        "ccy":"BTC",
        "amt":"1",
        "side":"purchase",
        "rate":"0.01"
    }
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
ccy | String | 是 | 币种名称，如 `BTC`  
amt | String | 是 | 申购（赎回）数量  
side | String | 是 | 操作类型  
`purchase`：申购 `redempt`：赎回  
rate | String | 是 | 申购利率  
仅适用于申购，新申购的利率会覆盖上次申购的利率  
参数取值范围在1%到365%之间  
  
> 返回结果
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
            {
                "ccy":"BTC",
                "amt":"1",
                "side":"purchase",
                "rate":"0.01"
            }
        ]
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
ccy | String | 币种名称  
amt | String | 申购（赎回）数量  
side | String | 操作类型  
rate | String | 申购利率  
  
### 设置余币宝借贷利率

#### 限速： 6次/s

#### 限速规则：UserID

#### HTTP请求

`POST /api/v5/asset/set-lending-rate`

> 请求示例
    
    
    POST /api/v5/asset/set-lending-rate
    body
    {
        "ccy":"BTC",
        "rate":"0.02"
    }
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
ccy | String | 是 | 币种名称，如 `BTC`  
rate | String | 是 | 贷出利率  
参数取值范围在1%到365%之间  
  
> 返回结果
    
    
    {
        "code": "0",
        "msg": "",
        "data": [{
            "ccy": "BTC",
            "rate": "0.02"
        }]
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
ccy | String | 币种名称，如 `BTC`  
rate | String | 贷出利率  
  
### 获取余币宝出借明细

#### 限速： 6次/s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/asset/lending-history`

> 请求示例
    
    
    GET /api/v5/asset/lending-history
    
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
ccy | String | 否 | 币种，如 `BTC`  
after | String | 否 | 查询在此之前的内容，值为时间戳，Unix 时间戳为毫秒数格式，如 `1597026383085`  
before | String | 否 | 查询在此之后的内容，值为时间戳，Unix 时间戳为毫秒数格式，如 `1597026383085`  
limit | String | 否 | 分页返回的结果集数量，最大为 100，不填默认返回 100 条  
  
> 返回结果
    
    
    {
        "code": "0",
        "msg": "",
        "data": [{
                "ccy": "BTC",
                "amt": "0.01",
                "earnings": "0.001",
                "rate": "0.01",
                "ts": "1597026383085"
            },
            {
                "ccy": "ETH",
                "amt": "0.2",
                "earnings": "0.001",
                "rate": "0.01",
                "ts": "1597026383085"
            }
        ]
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
ccy | String | 币种，如 `BTC`  
amt | String | 出借数量  
earnings | String | 已赚取利息  
rate | String | 出借年利率  
ts | String | 出借时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
  
### 获取市场借贷信息（公共）

公共接口无须鉴权

#### 限速： 6次/s

#### 限速规则：IP

#### HTTP请求

`GET /api/v5/asset/lending-rate-summary`

> 请求示例
    
    
    GET /api/v5/asset/lending-rate-summary
    
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
ccy | String | 否 | 币种，如 `BTC`  
  
> 返回结果
    
    
    {
        "code": "0",
        "msg": "",
        "data": [{
            "ccy": "BTC",
            "avgAmt": "10000",
            "avgAmtUsd": "10000000000",
            "avgRate": "0.03",
            "preRate": "0.02",
            "estRate": "0.01"
        }]
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
ccy | String | 币种，如 `BTC`  
avgAmt | String | 过去24小时平均借贷量  
avgAmtUsd | String | 过去24小时平均借贷美元价值  
avgRate | String | 过去24小时平均借出利率  
preRate | String | 上一次借贷年利率  
estRate | String | 下一次预估借贷年利率  
  
### 获取市场借贷历史（公共）

公共接口无须鉴权

#### 限速： 6次/s

#### 限速规则：IP

#### HTTP请求

`GET /api/v5/asset/lending-rate-history`

> 请求示例
    
    
    GET /api/v5/asset/lending-rate-history
    
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
ccy | String | 否 | 币种，如 `BTC`  
after | String | 否 | 查询在此之前的内容，值为时间戳，Unix 时间戳为毫秒数格式，如 `1597026383085`  
before | String | 否 | 查询在此之后的内容，值为时间戳，Unix 时间戳为毫秒数格式，如 `1597026383085`  
limit | String | 否 | 分页返回的结果集数量，最大为100，不填默认返回100条  
  
> 返回结果
    
    
    {
        "code": "0",
        "msg": "",
        "data": [{
            "ccy": "BTC",
            "amt": "0.01",
            "rate": "0.001",
            "ts": "1597026383085"
        }]
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
ccy | String | 币种，如 `BTC`  
amt | String | 市场总出借数量  
rate | String | 出借年利率  
ts | String | 时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
  
## 闪兑

`闪兑`功能模块下的API接口需要身份验证。仅支持资金账户中的资产做闪兑交易。

### 获取闪兑币种列表

#### 限速： 6次/s

#### 限速规则：UserID

#### HTTP 请求

`GET /api/v5/asset/convert/currencies`

> 请求示例
    
    
    GET /api/v5/asset/convert/currencies
    
    

#### 请求参数

无

> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "min": 0.0001,
                "max": 0.5,
                "ccy": "BTC"
            },
            {
                "min": 0.001,
                "max": 10.0,
                "ccy": "ETH"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
ccy | String | 币种名称，如 `BTC`  
min | String | 支持闪兑的最小值  
max | String | 支持闪兑的最大值  
  
### 获取闪兑币对信息

#### 限速： 6次/s

#### 限速规则：UserID

#### HTTP 请求

`GET /api/v5/asset/convert/currency-pair`

> 请求示例
    
    
    GET /api/v5/asset/convert/currency-pair?fromCcy=USDT&toCcy=BTC
    
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
fromCcy | String | 是 | 消耗币种，如 `USDT`  
toCcy | String | 是 | 获取币种，如 `BTC`  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "baseCcy": "BTC",
                "baseCcyMax": "0.5",
                "baseCcyMin": "0.0001",
                "instId": "BTC-USDT",
                "quoteCcy": "USDT",
                "quoteCcyMax": "10000",
                "quoteCcyMin": "1"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
instId | String | 币对，如 `BTC-USDT`  
baseCcy | String | 交易货币币种，如 `BTC-USDT`中的`BTC`  
baseCcyMax | String | 交易货币支持闪兑的最大值  
baseCcyMin | String | 交易货币支持闪兑的最小值  
quoteCcy | String | 计价货币币种，如 `BTC-USDT`中的`USDT`  
quoteCcyMax | String | 计价货币支持闪兑的最大值  
quoteCcyMin | String | 计价货币支持闪兑的最小值  
  
### 闪兑预估询价

#### 限速： 2次/s

#### 限速规则：UserID

#### HTTP请求

`POST /api/v5/asset/convert/estimate-quote`

> 请求示例
    
    
    POST /api/v5/asset/convert/estimate-quote
    body
    {
        "baseCcy": "ETH",
        "quoteCcy": "USDT",
        "side": "buy",
        "rfqSz": "30",
        "rfqSzCcy": "USDT"
    }
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
baseCcy | String | 是 | 交易货币币种，如 `BTC-USDT`中的`BTC`  
quoteCcy | String | 是 | 计价货币币种，如 `BTC-USDT`中的`USDT`  
side | String | 是 | 交易方向  
买：`buy` 卖：`sell`  
描述的是对于baseCcy的交易方向  
rfqSz | String | 是 | 询价数量  
rfqSzCcy | String | 是 | 询价币种  
clQReqId | String | 否 | 客户端自定义的订单标识  
字母（区分大小写）与数字的组合，可以是纯字母、纯数字且长度要在1-32位之间。  
tag | String | 否 | 订单标签  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "baseCcy": "ETH",
                "baseSz": "0.01023052",
                "clQReqId": "",
                "cnvtPx": "2932.40104429",
                "origRfqSz": "30",
                "quoteCcy": "USDT",
                "quoteId": "quoterETH-USDT16461885104612381",
                "quoteSz": "30",
                "quoteTime": "1646188510461",
                "rfqSz": "30",
                "rfqSzCcy": "USDT",
                "side": "buy",
                "ttlMs": "10000"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
quoteTime | String | 生成报价时间，Unix时间戳的毫秒数格式  
ttlMs | String | 报价有效期，单位为毫秒  
clQReqId | String | 客户端自定义的订单标识  
quoteId | String | 报价ID  
baseCcy | String | 交易货币币种，如 BTC-USDT 中BTC  
quoteCcy | String | 计价货币币种，如 BTC-USDT 中USDT  
side | String | 交易方向  
买：`buy` 卖：`sell`  
origRfqSz | String | 原始报价的数量  
rfqSz | String | 实际报价的数量  
rfqSzCcy | String | 报价的币种  
cnvtPx | String | 闪兑价格，单位为计价币  
baseSz | String | 闪兑交易币数量  
quoteSz | String | 闪兑计价币数量  
  
### 闪兑交易

#### 限速： 2次/s

#### 限速规则：UserID

#### HTTP请求

`POST /api/v5/asset/convert/trade`

> 请求示例
    
    
    POST /api/v5/asset/convert/trade
    body
    {
        "baseCcy": "ETH",
        "quoteCcy": "USDT",
        "side": "buy",
        "sz": "30",
        "szCcy": "USDT",
        "quoteId": "quoterETH-USDT16461885104612381"
    }
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
quoteId | String | 是 | 报价ID  
baseCcy | String | 是 | 交易货币币种，如 `BTC-USDT`中的`BTC`  
quoteCcy | String | 是 | 计价货币币种，如 `BTC-USDT`中的`USDT`  
side | String | 是 | 交易方向  
买：`buy` 卖：`sell`  
描述的是对于baseCcy的交易方向  
sz | String | 是 | 用户报价数量  
报价数量应不大于预估询价中的询价数量  
szCcy | String | 是 | 用户报价币种  
clTReqId | String | 否 | 用户自定义的订单标识  
字母（区分大小写）与数字的组合，可以是纯字母、纯数字且长度要在1-32位之间。  
tag | String | 否 | 订单标签  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "baseCcy": "ETH",
                "clTReqId": "",
                "fillBaseSz": "0.01023052",
                "fillPx": "2932.40104429",
                "fillQuoteSz": "30",
                "instId": "ETH-USDT",
                "quoteCcy": "USDT",
                "quoteId": "quoterETH-USDT16461885104612381",
                "side": "buy",
                "state": "fullyFilled",
                "tradeId": "trader16461885203381437",
                "ts": "1646188520338"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
tradeId | String | 成交ID  
quoteId | String | 报价ID  
clTReqId | String | 用户自定义的订单标识  
state | String | `fullyFilled`：交易成功  
`rejected`：交易失败  
instId | String | 币对，如 `BTC-USDT`  
baseCcy | String | 交易货币币种，如 `BTC-USDT`中`BTC`  
quoteCcy | String | 计价货币币种，如 `BTC-USDT`中`USDT`  
side | String | 交易方向  
买：`buy` 卖：`sell`  
fillPx | String | 成交价格，单位为计价币  
fillBaseSz | String | 成交的交易币数量  
fillQuoteSz | String | 成交的计价币数量  
ts | String | 闪兑交易时间，值为时间戳，Unix时间戳为毫秒数格式，如 `1597026383085`  
  
### 获取闪兑交易历史

#### 限速： 6次/s

#### 限速规则：UserID

#### HTTP 请求

`GET /api/v5/asset/convert/history`

> 请求示例
    
    
    GET /api/v5/asset/convert/history
    
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
after | String | 否 | 查询在此之前的内容，值为时间戳，Unix时间戳为毫秒数格式，如 `1597026383085`  
before | String | 否 | 查询在此之后的内容，值为时间戳，Unix时间戳为毫秒数格式，如 `1597026383085`  
limit | String | 否 | 返回的结果集数量，默认为100，最大为100  
tag | String | 否 | 订单标签  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "instId": "ETH-USDT",
                "side": "buy",
                "fillPx": "2932.401044",
                "baseCcy": "ETH",
                "quoteCcy": "USDT",
                "fillBaseSz": "0.01023052",
                "state": "fullyFilled",
                "tradeId": "trader16461885203381437",
                "fillQuoteSz": "30",
                "ts": "1646188520000"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
tradeId | String | 成交ID  
state | String | `fullyFilled`：交易成功  
`rejected`：交易失败  
instId | String | 币对，如 `BTC-USDT`  
baseCcy | String | 交易货币币种，如 `BTC-USDT`中的`BTC`  
quoteCcy | String | 计价货币币种，如 `BTC-USDT`中的`USDT`  
side | String | 交易方向  
买：`buy` 卖：`sell`  
fillPx | String | 成交价格，单位为计价币  
fillBaseSz | String | 成交的交易币数量  
fillQuoteSz | String | 成交的计价币数量  
ts | String | 闪兑交易时间，值为时间戳，Unix时间戳为毫秒数格式，如 `1597026383085`  
  
## 账户

`账户`功能模块下的API接口需要身份验证。

### 查看账户余额

获取交易账户中资金余额信息。

免息额度和折算率都是公共数据，不在账户接口内展示

#### 限速： 10次/2s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/account/balance`

> 请求示例
    
    
    获取账户中所有资产余额
    GET /api/v5/account/balance
    
    获取账户中BTC、ETH两种资产余额
    GET /api/v5/account/balance?ccy=BTC,ETH
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
ccy | String | 否 | 币种，如 `BTC`  
支持多币种查询（不超过20个），币种之间半角逗号分隔  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "adjEq": "10679688.0460531643092577",
                "details": [
                    {
                        "availBal": "",
                        "availEq": "9930359.9998",
                        "cashBal": "9930359.9998",
                        "ccy": "USDT",
                        "crossLiab": "0",
                        "disEq": "9439737.0772999514",
                        "eq": "9930359.9998",
                        "eqUsd": "9933041.196999946",
                        "frozenBal": "0",
                        "interest": "0",
                        "isoEq": "0",
                        "isoLiab": "0",
                        "isoUpl":"0",
                        "liab": "0",
                        "maxLoan": "10000",
                        "mgnRatio": "",
                        "notionalLever": "",
                        "ordFrozen": "0",
                        "twap": "0",
                        "uTime": "1620722938250",
                        "upl": "0",
                        "uplLiab": "0",
                        "stgyEq":"0"
                    },
                    {
                        "availBal": "",
                        "availEq": "33.6799714158199414",
                        "cashBal": "33.2009985",
                        "ccy": "BTC",
                        "crossLiab": "0",
                        "disEq": "1239950.9687532129092577",
                        "eq": "33.771820625136023",
                        "eqUsd": "1239950.9687532129092577",
                        "frozenBal": "0.0918492093160816",
                        "interest": "0",
                        "isoEq": "0",
                        "isoLiab": "0",
                        "isoUpl":"0",
                        "liab": "0",
                        "maxLoan": "1453.92289531493594",
                        "mgnRatio": "",
                        "notionalLever": "",
                        "ordFrozen": "0",
                        "twap": "0",
                        "uTime": "1620722938250",
                        "upl": "0.570822125136023",
                        "uplLiab": "0",
                        "stgyEq":"0"
                    }
                ],
                "imr": "3372.2942371050594217",
                "isoEq": "0",
                "mgnRatio": "70375.35408747017",
                "mmr": "134.8917694842024",
                "notionalUsd": "33722.9423710505978888",
                "ordFroz": "0",
                "totalEq": "11172992.1657531589092577",
                "uTime": "1623392334718"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
uTime | String | 账户信息的更新时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
totalEq | String | 美金层面权益  
isoEq | String | 美金层面逐仓仓位权益  
适用于`单币种保证金模式`和`跨币种保证金模式`和`组合保证金模式`  
adjEq | String | 美金层面有效保证金  
适用于`跨币种保证金模式`和`组合保证金模式`  
ordFroz | String | 美金层面全仓挂单占用保证金  
适用于`跨币种保证金模式`和`组合保证金模式`  
imr | String | 美金层面占用保证金  
适用于`跨币种保证金模式`和`组合保证金模式`  
mmr | String | 美金层面维持保证金  
适用于`跨币种保证金模式`和`组合保证金模式`  
mgnRatio | String | 美金层面保证金率  
适用于`跨币种保证金模式` 和`组合保证金模式`  
notionalUsd | String | 以美金价值为单位的持仓数量，即仓位美金价值  
适用于`跨币种保证金模式`和`组合保证金模式`  
details | Array | 各币种资产详细信息  
> ccy | String | 币种  
> eq | String | 币种总权益  
> cashBal | String | 币种余额  
> uTime | String | 币种余额信息的更新时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
> isoEq | String | 币种逐仓仓位权益  
适用于`单币种保证金模式`和`跨币种保证金模式`和`组合保证金模式`  
> availEq | String | 可用保证金  
适用于`单币种保证金模式`和`跨币种保证金模式`和`组合保证金模式`  
> disEq | String | 美金层面币种折算权益  
> availBal | String | 可用余额  
适用于`简单交易模式`  
> frozenBal | String | 币种占用金额  
> ordFrozen | String | 挂单冻结数量  
> liab | String | 币种负债额  
适用于`跨币种保证金模式`和`组合保证金模式`  
> upl | String | 未实现盈亏  
适用于`单币种保证金模式`和`跨币种保证金模式`和`组合保证金模式`  
> uplLiab | String | 由于仓位未实现亏损导致的负债  
适用于`跨币种保证金模式`和`组合保证金模式`  
> crossLiab | String | 币种全仓负债额  
适用于`跨币种保证金模式`和`组合保证金模式`  
> isoLiab | String | 币种逐仓负债额  
适用于`跨币种保证金模式`和`组合保证金模式`  
> mgnRatio | String | 保证金率  
适用于`单币种保证金模式`  
> interest | String | 计息  
适用于`跨币种保证金模式`和`组合保证金模式`  
> twap | String | 当前负债币种触发系统自动换币的风险  
0、1、2、3、4、5其中之一，数字越大代表您的负债币种触发自动换币概率越高  
适用于`跨币种保证金模式`和`组合保证金模式`  
> maxLoan | String | 币种最大可借  
适用于`跨币种保证金模式`和`组合保证金模式`  
> eqUsd | String | 币种权益美金价值  
> notionalLever | String | 币种杠杆倍数  
适用于`单币种保证金模式`  
> stgyEq | String | 策略权益  
> isoUpl | String | 逐仓未实现盈亏  
适用于`单币种保证金模式`和`跨币种保证金模式`和`组合保证金模式`  
当前账户等级下无效字段返回""

各账户等级下有效字段分布

参数 | 简单交易模式 | 单币种保证金模式 | 跨币种保证金模式  
---|---|---|---  
uTime | 是 | 是 | 是  
totalEq | 是 | 是 | 是  
isoEq |  | 是 | 是  
adjEq |  |  | 是  
ordFroz |  |  | 是  
imr |  |  | 是  
mmr |  |  | 是  
mgnRatio |  |  | 是  
notionalUsd |  |  | 是  
details |  |  |  
> ccy | 是 | 是 | 是  
> eq | 是 | 是 | 是  
> cashBal | 是 | 是 | 是  
> uTime | 是 | 是 | 是  
> isoEq |  | 是 | 是  
> availEq |  | 是 | 是  
> disEq | 是 | 是 | 是  
> availBal | 是 |  |  
> frozenBal | 是 | 是 | 是  
> ordFrozen | 是 | 是 | 是  
> liab |  |  | 是  
> upl |  | 是 | 是  
> uplLiab |  |  | 是  
> crossLiab |  |  | 是  
> isoLiab |  |  | 是  
> mgnRatio |  | 是 |  
> interest |  |  | 是  
> twap |  |  | 是  
> maxLoan |  |  | 是  
> eqUsd | 是 | 是 | 是  
> notionalLever |  | 是 |  
> stgyEq | 是 | 是 |  
> isoUpl |  | 是 | 是  
  
### 查看持仓信息

获取该账户下拥有实际持仓的信息。账户为单向持仓模式会显示净持仓（`net`），账户为双向持仓模式下会分别返回多头（`long`）或空头（`short`）的仓位。

#### 限速：10次/2s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/account/positions`

> 请求示例
    
    
    查看BTC-USDT的持仓信息
    GET /api/v5/account/positions?instId=BTC-USDT
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instType | String | 否 | 产品类型  
`MARGIN`：币币杠杆  
`SWAP`：永续合约  
`FUTURES`：交割合约  
`OPTION`：期权  
`instType`和`instId`同时传入的时候会校验`instId`与`instType`是否一致，结果返回`instId`的持仓信息  
instId | String | 否 | 交易产品ID，如：`BTC-USD-190927-5000-C`  
支持多个`instId`查询（不超过10个），半角逗号分隔  
posId | String | 否 | 持仓ID  
支持多个`posId`查询（不超过20个），半角逗号分割  
如果该instId拥有过的仓位，将返回持仓信息，不管持仓量是否为0；否则不返回
逐仓交易设置中，如果设置为自主划转模式，逐仓转入保证金后，会生成一个持仓量为0的仓位

> 返回结果
    
    
    {
        "code": "0",
        "msg": "",
        "data": [{
            "adl":"1",
            "availPos":"1",
            "avgPx":"2566.31",
            "cTime":"1619507758793",
            "ccy":"ETH",
            "deltaBS":"",
            "deltaPA":"",
            "gammaBS":"",
            "gammaPA":"",
            "imr":"",
            "instId":"ETH-USD-210430",
            "instType":"FUTURES",
            "interest":"0",
            "last":"2566.22",
            "usdPx":"",
            "lever":"10",
            "liab":"",
            "liabCcy":"",
            "liqPx":"2352.8496681818233",
            "markPx":"2353.849",
            "margin":"0.0003896645377994",
            "mgnMode":"isolated",
            "mgnRatio":"11.731726509588816",
            "mmr":"0.0000311811092368",
            "notionalUsd":"2276.2546609009605",
            "optVal":"",
            "pTime":"1619507761462",
            "pos":"1",
            "posCcy":"",
            "posId":"307173036051017730",
            "posSide":"long",
            "thetaBS":"",
            "thetaPA":"",
            "tradeId":"109844",
            "quoteBal": "0",
            "baseBal": "0",
            "uTime":"1619507761462",
            "upl":"-0.0000009932766034",
            "uplRatio":"-0.0025490556801078",
            "vegaBS":"",
            "vegaPA":""
        }]
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
instType | String | 产品类型  
mgnMode | String | 保证金模式  
`cross`：全仓  
`isolated`：逐仓  
posId | String | 持仓ID  
posSide | String | 持仓方向  
`long`：双向持仓多头  
`short`：双向持仓空头  
`net`：单向持仓（`交割/永续/期权`：`pos`为正代表多头，`pos`为负代表空头。`币币杠杆`：`posCcy`为交易货币时，代表多头；`posCcy`为计价货币时，代表空头。）  
pos | String | 持仓数量，逐仓自主划转模式下，转入保证金后会产生pos为`0`的仓位  
baseBal | String | 交易币余额，适用于 `币币杠杆`（逐仓自主划转模式）  
quoteBal | String | 计价币余额 ，适用于 `币币杠杆`（逐仓自主划转模式）  
posCcy | String | 仓位资产币种，仅适用于`币币杠杆`仓位  
availPos | String | 可平仓数量，适用于 `币币杠杆`,`交割/永续`（开平仓模式），`期权`（交易账户及保证金账户逐仓）。  
avgPx | String | 开仓平均价  
upl | String | 未实现收益  
uplRatio | String | 未实现收益率  
instId | String | 产品ID，如 `BTC-USD-180216`  
lever | String | 杠杆倍数，不适用于`期权`  
liqPx | String | 预估强平价  
不适用于`期权`  
markPx | String | 标记价格  
imr | String | 初始保证金，仅适用于`全仓`  
margin | String | 保证金余额，可增减，仅适用于`逐仓`  
mgnRatio | String | 保证金率  
mmr | String | 维持保证金  
liab | String | 负债额，仅适用于`币币杠杆`  
liabCcy | String | 负债币种，仅适用于`币币杠杆`  
interest | String | 利息，已经生成的未扣利息  
tradeId | String | 最新成交ID  
optVal | String | 期权市值，仅适用于`期权`  
notionalUsd | String | 以美金价值为单位的持仓数量  
adl | String | 信号区  
分为5档，从1到5，数字越小代表adl强度越弱  
ccy | String | 占用保证金的币种  
last | String | 最新成交价  
usdPx | String | 美金价格  
deltaBS | String | 美金本位持仓仓位delta，仅适用于`期权`  
deltaPA | String | 币本位持仓仓位delta，仅适用于`期权`  
gammaBS | String | 美金本位持仓仓位gamma，仅适用于`期权`  
gammaPA | String | 币本位持仓仓位gamma，仅适用于`期权`  
thetaBS | String | 美金本位持仓仓位theta，仅适用于`期权`  
thetaPA | String | 币本位持仓仓位theta，仅适用于`期权`  
vegaBS | String | 美金本位持仓仓位vega，仅适用于`期权`  
vegaPA | String | 币本位持仓仓位vega，仅适用于`期权`  
cTime | String | 持仓创建时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
uTime | String | 最近一次持仓更新时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
PM账户下，持仓的 IMR MMR的数据是后端服务以ristUnit为最小粒度重新计算，相同riskUnit全仓仓位的imr和mmr返回值相同。

### 查看账户持仓风险

查看账户整体风险。

获取同一时间切片上的账户和持仓的基础信息

#### 限速： 10次/2s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/account/account-position-risk`

> 请求示例
    
    
    GET /api/v5/account/account-position-risk
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instType | String | 否 | 产品类型  
`MARGIN`：币币杠杆  
`SWAP`：永续合约  
`FUTURES`：交割合约  
`OPTION`：期权  
  
  
> 返回结果
    
    
    {
        "code":"0",
        "data":[
            {
                "adjEq":"174238.6793649711331679",
                "balData":[
                    {
                        "ccy":"BTC",
                        "disEq":"78846.7803721021362242",
                        "eq":"1.3863533369419636"
                    },
                    {
                        "ccy":"USDT",
                        "disEq":"73417.2495112863300127",
                        "eq":"73323.395564963177146"
                    }
                ],
                "posData":[
                    {
                        "baseBal": "0.4",
                        "ccy": "",
                        "instId": "BTC-USDT",
                        "instType": "MARGIN",
                        "mgnMode": "isolated",
                        "notionalCcy": "0",
                        "notionalUsd": "0",
                        "pos": "0",
                        "posCcy": "",
                        "posId": "310388685292318723",
                        "posSide": "net",
                        "quoteBal": "0"
                    }
                ],
                "ts":"1620282889345"
            }
        ],
        "msg":""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
ts | String | 获取账户信息数据的时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
adjEq | String | 美金层面有效保证金  
适用于`跨币种保证金模式` 和`组合保证金模式`  
balData | Array | 币种资产信息  
> ccy | String | 币种  
> eq | String | 币种总权益  
> disEq | String | 美金层面币种折算权益  
posData | Array | 持仓详细信息  
> instType | String | 产品类型  
> mgnMode | String | 保证金模式  
`cross`：全仓  
`isolated`：逐仓  
> posId | String | 持仓ID  
> instId | String | 产品ID，如 `BTC-USD-180216`  
> pos | String | 以`张`为单位的持仓数量，逐仓自主划转模式下，转入保证金后会产生pos为`0`的仓位  
> baseBal | String | 交易币余额，适用于 `币币杠杆`（逐仓自主划转模式）  
> quoteBal | String | 计价币余额 ，适用于 `币币杠杆`（逐仓自主划转模式）  
> posSide | String | 持仓方向  
`long`：双向持仓多头  
`short`：双向持仓空头  
`net`：单向持仓（`交割/永续/期权`：`pos`为正代表多头，`pos`为负代表空头。`币币杠杆`：`posCcy`为交易货币时，代表多头；`posCcy`为计价货币时，代表空头。）  
> posCcy | String | 仓位资产币种，仅适用于`币币杠杆`仓位  
> ccy | String | 占用保证金的币种  
> notionalCcy | String | 以`币`为单位的持仓数量  
> notionalUsd | String | 以`美金价值`为单位的持仓数量  
  
### 账单流水查询（近七天）

帐户资产流水是指导致帐户余额增加或减少的行为。本接口可以查询最近7天的账单数据。

#### 限速：5次/s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/account/bills`

> 请求示例
    
    
    GET /api/v5/account/bills
    
    GET /api/v5/account/bills?instType=MARGIN
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instType | String | 否 | 产品类型  
`SPOT`：币币  
`MARGIN`：币币杠杆  
`SWAP`：永续合约  
`FUTURES`：交割合约  
`OPTION`：期权  
  
ccy | String | 否 | 保证金币种  
mgnMode | String | 否 | 仓位类型  
`isolated`：逐仓  
`cross`：全仓  
ctType | String | 否 | `linear`： 正向合约  
`inverse`： 反向合约  
仅`交割/永续`有效  
type | String | 否 | 账单类型  
`1`：划转 `2`：交易 `3`：交割 `4`：自动换币 `5`：强平 `6`：保证金划转 `7`：扣息 `8`：资金费 `9`：自动减仓
`10`：穿仓补偿 `11`：系统换币 `12`：策略划拨 `13`：对冲减仓  
subType | String | 否 | 账单子类型  
`1`：买入 `2`：卖出 `3`：开多 `4`：开空 `5`：平多 `6`：平空 `9`：市场借币扣息 `11`：转入 `12`：转出
`14`：尊享借币扣息 `160`：手动追加保证金 `161`：手动减少保证金 `162`：自动追加保证金 `114`：自动换币买入
`115`：自动换币卖出 `118`：系统换币转入 `119`：系统换币转出 `100`：强减平多 `101`：强减平空 `102`：强减买入
`103`：强减卖出 `104`：强平平多 `105`：强平平空 `106`：强平买入 `107`：强平卖出 `110`：强平换币转入
`111`：强平换币转出 `125`：自动减仓平多 `126`：自动减仓平空 `127`：自动减仓买入 `128`：自动减仓卖出 `131`：对冲买入
`132`：对冲卖出 `170`：到期行权 `171`：到期被行权 `172`：到期作废 `112`：交割平多 `113`：交割平空
`117`：交割/期权穿仓补偿 `173`：资金费支出 `174`：资金费收入 `200`:系统转入 `201`:手动转入 `202`:系统转出
`203`:手动转出  
after | String | 否 | 请求此id之前（更旧的数据）的分页内容，传的值为对应接口的`billId`  
before | String | 否 | 请求此id之后（更新的数据）的分页内容，传的值为对应接口的`billId`  
limit | String | 否 | 分页返回的结果集数量，最大为100，不填默认返回100条  
  
> 返回结果
    
    
    {
        "code": "0",
        "msg": "",
        "data": [{
                "bal": "256.27611382",
                "balChg": "256.27611382",
                "billId": "374241568911437826",
                "ccy": "GODS",
                "execType": "",
                "fee": "",
                "from": "1",
                "instId": "",
                "instType": "",
                "mgnMode": "",
                "notes": "From 币币账户",
                "ordId": "",
                "pnl": "",
                "posBal": "",
                "posBalChg": "",
                "subType": "11",
                "sz": "256.27611382",
                "to": "18",
                "ts": "1635498143100",
                "type": "1"
            }
        ]
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
instType | String | 产品类型  
billId | String | 账单ID  
type | String | 账单类型  
subType | String | 账单子类型  
ts | String | 账单创建时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
balChg | String | 账户层面的余额变动数量  
posBalChg | String | 仓位层面的余额变动数量  
bal | String | 账户层面的余额数量  
posBal | String | 仓位层面的余额数量  
sz | String | 数量  
ccy | String | 账户余额币种  
pnl | String | 收益  
fee | String | 手续费  
正数代表平台返佣 ，负数代表平台扣除  
mgnMode | String | 保证金模式  
`isolated`：逐仓 `cross`：全仓  
账单不是由仓位变化产生的，该字段返回 ""  
instId | String | 产品ID，如 `BTC-USD-190927-5000-C`  
ordId | String | 订单ID  
当type为`2`：交易时，返回相应订单id。无订单时，该字段返回 ""  
execType | String | 流动性方向 `T`：taker `M`：maker  
from | String | 转出账户  
`6`：资金账户 `18`：交易账户  
仅适用于`资金划转`，不是`资金划转`时，返回 ""  
to | String | 转入账户  
`6`：资金账户 `18`：交易账户  
仅适用于`资金划转`，不是`资金划转`时，返回 ""  
notes | String | 备注  
  
### 账单流水查询（近三月）

帐户资产流水是指导致帐户余额增加或减少的行为。本接口可以查询最近3个月的账单数据。

#### 限速：5次/2s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/account/bills-archive`

> 请求示例
    
    
    GET /api/v5/account/bills-archive
    
    GET /api/v5/account/bills-archive?instType=MARGIN
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instType | String | 否 | 产品类型  
`SPOT`：币币  
`MARGIN`：币币杠杆  
`SWAP`：永续合约  
`FUTURES`：交割合约  
`OPTION`：期权  
  
ccy | String | 否 | 保证金币种  
mgnMode | String | 否 | 仓位类型  
`isolated`：逐仓 `cross`：全仓  
ctType | String | 否 | `linear`： 正向合约  
`inverse`： 反向合约  
仅`交割/永续`有效  
type | String | 否 | 账单类型  
`1`：划转 `2`：交易 `3`：交割 `4`：自动换币 `5`：强平 `6`：保证金划转 `7`：扣息 `8`：资金费 `9`：自动减仓
`10`：穿仓补偿 `11`：系统换币 `12`：策略划拨 `13`：对冲减仓  
subType | String | 否 | 账单子类型  
`1`：买入 `2`：卖出 `3`：开多 `4`：开空 `5`：平多 `6`：平空 `9`：市场借币扣息 `11`：转入 `12`：转出
`14`：尊享借币扣息 `160`：手动追加保证金 `161`：手动减少保证金 `162`：自动追加保证金 `114`：自动换币买入
`115`：自动换币卖出 `118`：系统换币转入 `119`：系统换币转出 `100`：强减平多 `101`：强减平空 `102`：强减买入
`103`：强减卖出 `104`：强平平多 `105`：强平平空 `106`：强平买入 `107`：强平卖出 `110`：强平换币转入
`111`：强平换币转出 `125`：自动减仓平多 `126`：自动减仓平空 `127`：自动减仓买入 `128`：自动减仓卖出 `131`：对冲买入
`132`：对冲卖出 `170`：到期行权 `171`：到期被行权 `172`：到期作废 `112`：交割平多 `113`：交割平空
`117`：交割/期权穿仓补偿 `173`：资金费支出 `174`：资金费收入 `200`:系统转入 `201`:手动转入 `202`:系统转出
`203`:手动转出  
after | String | 否 | 请求此id之前（更旧的数据）的分页内容，传的值为对应接口的`billId`  
before | String | 否 | 请求此id之后（更新的数据）的分页内容，传的值为对应接口的`billId`  
limit | String | 否 | 分页返回的结果集数量，最大为100，不填默认返回100条  
  
> 返回结果
    
    
    {
        "code": "0",
        "msg": "",
        "data": [{
                "bal": "256.27611382",
                "balChg": "256.27611382",
                "billId": "374241568911437826",
                "ccy": "GODS",
                "execType": "",
                "fee": "",
                "from": "1",
                "instId": "",
                "instType": "",
                "mgnMode": "",
                "notes": "From 币币账户",
                "ordId": "",
                "pnl": "",
                "posBal": "",
                "posBalChg": "",
                "subType": "11",
                "sz": "256.27611382",
                "to": "18",
                "ts": "1635498143100",
                "type": "1"
            }
        ]
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
instType | String | 产品类型  
billId | String | 账单ID  
type | String | 账单类型  
subType | String | 账单子类型  
ts | String | 账单创建时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
balChg | String | 账户层面的余额变动数量  
posBalChg | String | 仓位层面的余额变动数量  
bal | String | 账户层面的余额数量  
posBal | String | 仓位层面的余额数量  
sz | String | 数量  
ccy | String | 账户余额币种  
pnl | String | 收益  
fee | String | 手续费  
正数代表平台返佣 ，负数代表平台扣除  
mgnMode | String | 保证金模式  
`isolated`：逐仓 `cross`：全仓  
无仓位类型字段，该字段返回 ""  
instId | String | 产品ID，如 `BTC-USD-190927-5000-C`  
ordId | String | 订单ID  
当type为`2`：交易时，返回相应订单id。无订单时，该字段返回 ""  
execType | String | 流动性方向 `T`：taker `M`：maker  
from | String | 转出账户  
`6`：资金账户 `18`：交易账户  
仅适用于`资金划转`，不是`资金划转`时，返回 ""  
to | String | 转入账户  
`6`：资金账户 `18`：交易账户  
仅适用于`资金划转`，不是`资金划转`时，返回 ""  
notes | String | 备注  
  
### 查看账户配置

查看当前账户的配置信息。

#### 限速：5次/2s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/account/config`

> 请求示例
    
    
    GET /api/v5/account/config
    
    

#### 请求参数

无

> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "acctLv": "3",
                "autoLoan": true,
                "ctIsoMode": "automatic",
                "greeksType": "PA",
                "level": "Lv3",
                "levelTmp": "",
                "mgnIsoMode": "autonomy",
                "posMode": "net_mode",
                "uid": "781767883763712"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
uid | String | 账户ID，账户uid和app上的一致  
acctLv | String | 账户层级  
`1`：简单交易模式，`2`：单币种保证金模式 ，`3`：跨币种保证金模式 ，`4`：组合保证金模式  
posMode | String | 持仓方式  
`long_short_mode`：双向持仓 `net_mode`：单向持仓  
仅适用`交割/永续`  
autoLoan | Boolean | 是否自动借币  
`true`：自动借币 `false`：非自动借币  
greeksType | String | 当前希腊字母展示方式  
`PA`：币本位 `BS`：美元本位  
level | String | 当前在平台上真实交易量的用户等级，例如 `lv1`  
levelTmp | String | 特约用户的临时体验用户等级，例如 `lv3`  
ctIsoMode | String | 衍生品的逐仓保证金划转模式  
`automatic`：开仓划转 `autonomy`：自主划转  
mgnIsoMode | String | 币币杠杆的逐仓保证金划转模式  
`automatic`：开仓划转 `autonomy`：自主划转  
  
### 设置持仓模式

单币种账户和跨币种账户模式：交割和永续合约支持双向持仓模式和单向持仓模式。单向持仓只会有一个方向的仓位；双向持仓可以分别持有多、空2个方向的仓位。  
组合保证金模式：交割和永续仅支持单向持仓模式

#### 限速：5次/2s

#### 限速规则：UserID

#### HTTP请求

`POST /api/v5/account/set-position-mode`

> 请求示例
    
    
    POST /api/v5/account/set-position-mode
    body 
    {
        "posMode":"long_short_mode"
    }
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
posMode | String | 是 | 持仓方式  
`long_short_mode`：双向持仓 `net_mode`：单向持仓  
仅适用`交割/永续`  
  
> 返回结果
    
    
    {
        "code": "0",
        "msg": "",
        "data": [{
            "posMode": "long_short_mode"
        }]
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
posMode | String | 持仓方式  
  
### 设置杠杆倍数

一个产品可以有如下几种杠杆倍数的设置场景：

`币币杠杆`逐仓杠杆倍数（币对层面）；

`币币杠杆`单币种保证金模式下全仓杠杆倍数（币对层面）；

`币币杠杆`跨币种保证金模式下全仓杠杆倍数（币种层面）；

`交割/永续`逐仓/全仓杠杆倍数（合约/指数层面）。

#### 限速：20次/2s

#### 限速规则：UserID

#### HTTP请求

`POST /api/v5/account/set-leverage`

> 请求示例
    
    
    设置逐仓杠杆倍数（币币杠杆），币对层面
    POST /api/v5/account/set-leverage 
    body
    {
        "instId":"BTC-USDT",
        "lever":"5",
        "mgnMode":"isolated"
    }
    
    设置单币种保证金模式下全仓杠杆倍数（币币杠杆），币对层面
    POST /api/v5/account/set-leverage 
    body
    {
        "instId":"BTC-USDT",
        "lever":"5",
        "mgnMode":"cross"
    }
    
    设置跨币种保证金模式下全仓杠杆倍数（币币杠杆），币种层面
    POST /api/v5/account/set-leverage 
    body
    {
        "ccy":"BTC",
        "lever":"5",
        "mgnMode":"cross"
    }
    
    设置交割合约BTC-USDT-200802多头逐仓杠杆倍数，合约层面
    POST /api/v5/account/set-leverage 
    body
    {
        "instId":"BTC-USDT-200802",
        "lever":"5",
        "posSide":"long",
        "mgnMode":"isolated"
    }
    
    设置交割合约的全仓杠杆倍数，指数层面
    POST /api/v5/account/set-leverage 
    body
    {
        "instId":"BTC-USDT-200802",
        "lever":"5",
        "mgnMode":"cross"
    }
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instId | String | 可选 | 产品ID：币对、合约  
`instId`和`ccy`至少要传一个；如果两个都传，默认使用`instId`  
ccy | String | 可选 | 保证金币种  
仅适用于`跨币种保证金模式`的`全仓` `币币杠杆`。设置自动借币的杠杆倍数时必填  
lever | String | 是 | 杠杆倍数  
mgnMode | String | 是 | 保证金模式  
`isolated`：逐仓 `cross`：全仓  
如果`ccy`有效传值，该参数值只能为`cross`。  
posSide | String | 可选 | 持仓方向  
`long`：双向持仓多头  
`short`：双向持仓空头  
`net`：单向持仓  
仅适用于逐仓`交割`/`永续`  
在双向持仓且保证金模式为逐仓条件下必填，且仅可选择 `long`或`short`，默认`net`  
  
> 返回结果
    
    
    {
        "code": "0",
        "msg": "",
        "data": [{
            "lever": "30",
            "mgnMode": "isolated",
            "instId": "BTC-USDT-SWAP",
            "posSide": "long"
        }]
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
lever | String | 杠杆倍数  
mgnMode | String | 保证金模式  
`isolated`：逐仓 `cross`：全仓  
instId | String | 产品ID  
posSide | String | 持仓方向  
当希望在指数层面设置交割/永续的全仓杠杆倍数时，传入任意产品ID 和保证金模式（全仓）即可。  组合保证金账户下交割和永续的全仓不能调整杠杆倍数。

### 获取最大可买卖/开仓数量

PM账户下，衍生品的全仓模式不支持最大可买卖/开仓数量的计算。

#### 限速：20次/2s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/account/max-size`

> 请求示例
    
    
    GET /api/v5/account/max-size?instId=BTC-USDT&tdMode=isolated
    
    

#### 请求参数

**参数名** | **类型** | **是否必须** | **描述**  
---|---|---|---  
instId | String | 是 | 产品ID，如 `BTC-USDT`  
支持多产品ID查询（不超过5个），半角逗号分隔  
tdMode | String | 是 | 交易模式  
`cross`：全仓 `isolated`：逐仓 `cash`：非保证金  
ccy | String | 可选 | 保证金币种，仅适用于单币种保证金模式下的全仓杠杆订单  
px | String | 否 | 委托价格  
当不填委托价时会按当前最新成交价计算  
当指定多个产品ID查询时，忽略该参数，按当前最新成交价计算  
leverage | String | 否 | 开仓杠杆倍数  
默认为当前杠杆倍数  
仅适用于`币币杠杆/交割/永续`  
  
> 返回结果
    
    
    {
        "code": "0",
        "msg": "",
        "data": [{
            "ccy": "BTC",
            "instId": "BTC-USDT",
            "maxBuy": "0.0500695098559788",
            "maxSell": "64.4798671570072269"
        }]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
instId | String | 产品ID  
ccy | String | 保证金币种  
maxBuy | String | `币币/币币杠杆`：最大可买的交易币数量  
单币种保证金模式下的全仓杠杆订单，为交易币数量  
`交割`/`永续`/`期权`：最大可开多的合约张数  
maxSell | String | `币币/币币杠杆`：最大可卖的计价币数量  
单币种保证金模式下的全仓杠杆订单，为交易币数量  
`交割`/`永续`/`期权`：最大可开空的合约张数  
  
### 获取最大可用数量

#### 限速：20次/2s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/account/max-avail-size`

> 请求示例
    
    
    获取BTC-USDT全仓币币杠杆指定BTC作为保证金最大可用数量
    GET /api/v5/account/max-avail-size?instId=BTC-USDT&tdMode=cross&ccy=BTC
    
    获取BTC-USDT币币最大可用数量
    GET /api/v5/account/max-avail-size?instId=BTC-USDT&tdMode=cash
    
    

#### 请求参数

**参数名** | **类型** | 是否必须 | 描述  
---|---|---|---  
instId | String | 是 | 产品ID，如 `BTC-USDT`  
支持多产品ID查询（不超过5个），半角逗号分隔  
tdMode | String | 是 | 交易模式  
`cross`：全仓 `isolated`：逐仓 `cash`：非保证金  
ccy | String | 可选 | 保证金币种，仅适用于单币种保证金模式下的全仓杠杆订单  
reduceOnly | Boolean | 否 | 是否为只减仓模式，仅适用于`币币杠杆`  
px | String | 否 | 委托价格  
当不填委托价时会按当前最新成交价计算  
当指定多个产品ID查询时，忽略该参数，按当前最新成交价计算  
  
> 返回结果
    
    
    {
        "code": "0",
        "msg": "",
        "data": [{
            "instId": "BTC-USDT-200802",
            "availBuy": "1",
            "availSell": "1"
        }]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
instId | String | 产品ID  
availBuy | String | 最大买入可用数量  
availSell | String | 最大卖出可用数量  
币币/币币杠杆时availBuy为计价货币，availSell为交易货币。  
全仓币币杠杆时，availBuy和availSell均为指定保证金的币种。

### 调整保证金

增加或者减少逐仓保证金。减少保证金可能会导致实际杠杆倍数发生变化。

#### 限速：20次/2s

#### 限速规则：UserID

#### HTTP请求

`POST /api/v5/account/position/margin-balance`

> 请求示例
    
    
    POST /api/v5/account/position/margin-balance 
    body
    {
        "instId":"BTC-USDT-200626",
        "posSide":"short",
        "type":"add",
        "amt":"1"
    }
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instId | String | 是 | 产品ID  
posSide | String | 是 | 持仓方向，默认值是`net`  
`long`：双向持仓多头  
`short`：双向持仓空头  
`net`：单向持仓  
type | String | 是 | 增加/减少保证金  
`add`：增加  
`reduce`：减少  
amt | String | 是 | 增加或减少的保证金数量  
ccy | String | 否 | 增加或减少的保证金的币种，  
仅适用于逐仓自主划转保证金模式下的币币杠杆  
auto | Boolean | 否 | 是否自动借币转 true 或 false，默认false  
仅适用于逐仓自主划转保证金模式下的币币杠杆  
loanTrans | Boolean | 否 | 是否支持`跨币种保证金模式`或`组合保证金模式`下的借币转入/转出  
true 或 false，默认false  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "amt": "0.3",
                "ccy": "BTC",
                "instId": "BTC-USDT",
                "leverage": "",
                "posSide": "net",
                "type": "add"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
instId | String | 产品ID  
posSide | String | 持仓方向  
amt | String | 已增加/减少的保证金数量  
type | String | 增加/减少保证金  
leverage | String | 调整保证金后的实际杠杆倍数  
ccy | String | 增加或减少的保证金的币种  
自主划转模式  
初始划入逐仓仓位的保证金价值必须大于等于1万USDT,账户上会产生一个仓位。

### 获取杠杆倍数

#### 限速：20次/2s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/account/leverage-info`

> 请求示例
    
    
    GET /api/v5/account/leverage-info?instId=BTC-USDT-200626&mgnMode=cross
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instId | String | 是 | 产品ID  
支持多个instId查询，半角逗号分隔。instId个数不超过20个  
mgnMode | String | 是 | 保证金模式  
`isolated`：逐仓 `cross`：全仓  
  
> 返回结果
    
    
    {
        "code": "0",
        "msg": "",
        "data": [{
            "instId": "BTC-USDT-200626",
            "mgnMode": "cross",
            "posSide": "long",
            "lever": "10"
        },{
            "instId": "BTC-USDT-200626",
            "mgnMode": "cross",
            "posSide": "short",
            "lever": "10"
        }]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
instId | String | 产品ID  
mgnMode | String | 保证金模式  
posSide | String | 持仓方向  
`long`：双向持仓多头  
`short`：双向持仓空头  
`net`：单向持仓  
双向持仓模式下会返回两个方向的杠杆倍数  
lever | String | 杠杆倍数  
  
### 获取交易产品最大可借

#### 限速：20 次/2s

#### 限速规则：UserID

#### HTTP 请求

`GET /api/v5/account/max-loan`

> 请求示例
    
    
    单币种逐仓账户获取币币杠杆最大可借
    GET  /api/v5/account/max-loan?instId=BTC-USDT&mgnMode=isolated
    
    单币种全仓账户获取币币杠杆最大可借（指定保证金为BTC）
    GET  /api/v5/account/max-loan?instId=BTC-USDT&mgnMode=cross&mgnCcy=BTC
    
    跨币种全仓账户获取币币杠杠最大可借
    GET  /api/v5/account/max-loan?instId=BTC-USDT&mgnMode=cross
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instId | String | 是 | 产品 ID，如 `BTC-USDT`  
支持多产品ID查询（不超过5个），半角逗号分隔  
mgnMode | String | 是 | 仓位类型  
`isolated`：逐仓  
`cross`：全仓  
mgnCcy | String | 可选 | 保证金币种，如 `BTC`  
币币杠杆单币种全仓情况下必须指定保证金币种  
  
> 返回结果
    
    
    {
      "code": "0",
      "msg": "",
      "data": [
        {
          "instId": "BTC-USDT",
          "mgnMode": "isolated",
          "mgnCcy": "",
          "maxLoan": "0.1",
          "ccy": "BTC",
          "side": "sell"
        },
        {
          "instId": "BTC-USDT",
          "mgnMode": "isolated",
          "mgnCcy": "",
          "maxLoan": "0.2",
          "ccy": "USDT",
          "side": "buy"
        }
      ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
instId | String | 产品 ID  
mgnMode | String | 仓位类型  
mgnCcy | String | 保证金币种  
maxLoan | String | 最大可借  
ccy | String | 币种  
side | String | 订单方向  
  
### 获取当前账户交易手续费费率

#### 限速：5次/2s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/account/trade-fee`

> 请求示例
    
    
    获取币币BTC-USDT交易手续费率  
    GET /api/v5/account/trade-fee?instType=SPOT&instId=BTC-USDT
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instType | String | 是 | 产品类型  
`SPOT`：币币  
`MARGIN`：币币杠杆  
`SWAP`：永续合约  
`FUTURES`：交割合约  
`OPTION`：期权  
instId | String | 否 | 产品ID，如 `BTC-USDT`  
仅适用于instType为`币币/币币杠杆`  
uly | String | 否 | 标的指数  
仅适用于instType为`交割/永续/期权`，如 `BTC-USD`  
  
> 返回结果
    
    
    {
        "code": "0",
        "msg": "",
        "data": [{
                "category": "1",
                "delivery": "",
                "exercise": "",
                "instType": "SPOT",
                "level": "lv1",
                "maker": "-0.0008",
                "makerU": "",
                "taker": "-0.001",
                "takerU": "",
                "ts": "1608623351857"
            }
        ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
category | String | 币种手续费类别  
taker | String | 吃单手续费率，永续和交割合约时，为币本位合约费率  
maker | String | 挂单手续费率，永续和交割合约时，为币本位合约费率  
takerU | String | U本位合约吃单手续费率，仅适用于`交割/永续`  
makerU | String | U本位合约挂单手续费率，仅适用于`交割/永续`  
delivery | String | 交割手续费率  
exercise | String | 行权手续费率  
level | String | 手续费等级  
instType | String | 产品类型  
ts | String | 数据返回时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
备注：  
maker的值：正数，代表是返佣的费率；负数，代表平台扣除的费率。

### 获取计息记录

#### 限速：5次/2s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/account/interest-accrued`

> 请求示例
    
    
    GET /api/v5/account/interest-accrued
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
type | String | 否 | 借币类型  
`1`：尊享借币  
`2`：市场借币  
默认为`市场借币`  
ccy | String | 否 | 借贷币种，如 `BTC`  
仅适用于`市场借币`  
仅适用于`币币杠杆`  
instId | String | 否 | 产品ID，如 `BTC-USDT`  
仅适用于`市场借币`  
mgnMode | String | 否 | 保证金模式  
`cross`：全仓  
`isolated`：逐仓  
仅适用于`市场借币`  
after | String | 否 | 请求此时间戳之前（更旧的数据）的分页内容，Unix时间戳的毫秒数格式，如 `1597026383085`  
before | String | 否 | 请求此时间戳之后（更新的数据）的分页内容，Unix时间戳的毫秒数格式，如 `1597026383085`  
limit | String | 否 | 分页返回的结果集数量，最大为100，不填默认返回100条  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "ccy": "USDT",
                "instId": "",
                "interest": "0.0003960833333334",
                "interestRate": "0.0000040833333333",
                "liab": "97",
                "mgnMode": "",
                "ts": "1637312400000",
                "type": "1"
            }
            {
                "ccy": "USDT",
                "instId": "",
                "interest": "0.0004083333333334",
                "interestRate": "0.0000040833333333",
                "liab": "100",
                "mgnMode": "",
                "ts": "1637049600000",
                "type": "1"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
type | String | 类型  
`1`：尊享借币  
`2`：市场借币  
ccy | String | 借贷币种，如 `BTC`  
instId | String | 产品ID，如 `BTC-USD-180216`  
仅适用于`市场借币`  
mgnMode | String | 保证金模式  
`cross`：全仓  
`isolated`：逐仓  
interest | String | 利息  
interestRate | String | 计息利率(小时)  
liab | String | 计息负债  
ts | String | 计息时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
  
### 获取用户当前杠杆借币利率

#### 限速：5次/2s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/account/interest-rate`

> 请求示例
    
    
    GET /api/v5/account/interest-rate
    
    

#### 请求参数

**参数名** | **类型** | 是否必须 | 描述  
---|---|---|---  
ccy | String | 否 | 币种  
  
> 返回结果
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
            {
                "ccy":"BTC",
                "interestRate":"0.0001"
            },
            {
                "ccy":"LTC",
                "interestRate":"0.0003"
            }
        ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
interestRate | String | 杠杆借币利率  
ccy | String | 币种  
  
### 期权greeks的PA/BS切换

设置greeks的展示方式。

#### 限速：5次/2s

#### 限速规则：UserID

#### HTTP请求

`POST /api/v5/account/set-greeks`

> 请求示例
    
    
    POST /api/v5/account/set-greeks 
    body
    {
        "greeksType":"PA"
    }
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
greeksType | String | 是 | 希腊字母展示方式  
`PA`：币本位，`BS`：美元本位  
  
> 返回结果
    
    
    {
        "code": "0",
        "msg": "",
        "data": [{
            "greeksType": "PA"
        }]
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
greeksType | String | 当前希腊字母展示方式  
  
### 逐仓交易设置

可以通过该接口设置币币杠杆和交割、永续的逐仓仓位保证金的划转模式

#### 限速：5次/2s

#### 限速规则：UserID

#### HTTP请求

`POST /api/v5/account/set-isolated-mode`

> 请求示例
    
    
    POST /api/v5/account/set-isolated-mode
    body
    {
        "isoMode":"automatic",
        "type":"MARGIN"
    }
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
isoMode | String | 是 | 逐仓保证金划转模式  
automatic:开仓自动划转  
autonomy:自主划转  
type | String | 是 | 业务线类型  
  
MARGIN:币币杠杆  
CONTRACTS:合约  
当前账户内有持仓和挂单时，不能调整逐仓保证金划转模式。

> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "isoMode": "autonomy"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
isoMode | String | 逐仓保证金划转模式  
automatic:开仓自动划转  
autonomy:自主划转  
衍生品  
开仓划转：在开仓和平仓时自动占用和释放保证金
自主划转：需要手动给仓位划入保证金然后开始交易。该选项主要供专业用户使用，会有初次划入仓位资金≥10000USDT的限制。  杠杆  
开仓划转：在开仓和平仓时自动借币和还币
自主划转：需要手动给仓位划入保证金然后交易，同时也支持手动转出借币。该选项主要供专业用户使用，会有初次划入仓位资金≥10000USDT的限制。

### 查看账户最大可转余额

当指定币种时会返回该币种的交易账户到资金账户的最大可划转数量，不指定币种会返回所有拥有的币种资产可划转数量。

#### 限速：20次/2s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/account/max-withdrawal`

> 请求示例
    
    
    GET /api/v5/account/max-withdrawal
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
ccy | String | 否 | 币种，如 `BTC`  
支持多币种查询（不超过20个），币种之间半角逗号分隔  
  
> 返回结果
    
    
    {
        "code": "0",
        "msg": "",
        "data": [{
                "ccy": "BTC",
                "maxWd": "124",
                "maxWdEx": "125"
            },
            {
                "ccy": "ETH",
                "maxWd": "10",
                "maxWdEx": "12"
            }
        ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
ccy | String | 币种  
maxWd | String | 最大可划转数量（不支持`跨币种保证金模式`借币转出）  
maxWdEx | String | 最大可划转数量（支持`跨币种保证金模式`借币转出）  
  
### 查看账户特定风险状态

仅适用于PM账户

#### 限速： 10次/2s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/account/risk-state`

> 请求示例
    
    
    GET /api/v5/account/risk-state
    
    

> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "atRisk": false,
                "atRiskIdx": [],
                "atRiskMgn": [],
                "ts": "1635745078794"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
atRisk | String | 自动借币模式下的账户风险状态  
true:当前账户为特定风险状态  
当前不是特定风险状态  
atRiskIdx | Array | 衍生品的risk unit列表  
atRiskMgn | Array | 杠杆的risk unit列表  
ts | String | 接口数据返回时间 ，Unix时间戳的毫秒数格式，如 `1597026383085`  
当账户进入特定风险状态后，仅可以委托降低账户风险方向的IOC类型订单.

### 尊享借币还币

#### 限速：6次/s

#### 限速规则：UserID

#### HTTP请求

`POST /api/v5/account/borrow-repay`

> 请求示例
    
    
    POST /api/v5/account/borrow-repay 
    body
    {
        "ccy":"USDT",
        "side":"borrow",
        "amt":"100"
    }
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
ccy | String | 是 | 借贷币种，如 `BTC`  
side | String | 是 | `borrow`：借币，`repay`：还币  
amt | String | 是 | 借/还币的数量  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "amt": "102",
                "availLoan": "97",
                "ccy": "USDT",
                "loanQuota": "6000000",
                "posLoan": "0",
                "side": "repay",
                "usedLoan": "97"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
ccy | String | 借贷币种，如 `BTC`  
side | String | `borrow`：借币，`repay`：还币  
amt | String | 借/还币的数量  
loanQuota | String | 借币限额  
posLoan | String | 当前账户开仓占用  
availLoan | String | 当前账户剩余可用  
usedLoan | String | 当前账户已借额度  
  
### 获取尊享借币还币历史

#### 限速：5次/2s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/account/borrow-repay-history`

> 请求示例
    
    
    GET /api/v5/account/borrow-repay-history
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
ccy | String | 否 | 借贷币种，如 `BTC`  
after | String | 否 | 请求此时间戳之前（更旧的数据）的分页内容，Unix时间戳的毫秒数格式，如 `1597026383085`  
before | String | 否 | 请求此时间戳之后（更新的数据）的分页内容，Unix时间戳的毫秒数格式，如 `1597026383085`  
limit | String | 否 | 分页返回的结果集数量，最大为100，不填默认返回100条  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "ccy": "USDT",
                "tradedLoan": "102",
                "ts": "1637310691470",
                "type": "2",
                "usedLoan": "97"
            },
            {
                "ccy": "USDT",
                "tradedLoan": "102",
                "ts": "1637050435058",
                "type": "2",
                "usedLoan": "199"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
ccy | String | 借贷币种，如 `BTC`  
type | String | 类型  
`1`：借币  
`2`：还币  
`3`：扣息失败系统还币  
tradedLoan | String | 借/还币数量  
usedLoan | String | 当前账户已借额度  
ts | String | 借/还币时间  
  
### 获取借币利率与限额

#### 限速：5次/2s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/account/interest-limits`

> 请求示例
    
    
    GET /api/v5/account/interest-limits?type=1&ccy=BTC
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
type | String | 否 | 借币类型  
`1`：尊享借币  
`2`：市场借币  
默认为`市场借币`  
ccy | String | 否 | 借贷币种，如 `BTC`  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "debt": "97.06402000000000000000000000000000",
                "interest": "",
                "nextDiscountTime": "1637312400000",
                "nextInterestTime": "1637312400000",
                "records": [
                    {
                        "availLoan": "0.0000000000000000",
                        "ccy": "BTC",
                        "interest": "",
                        "loanQuota": "120.0000000000000000",
                        "posLoan": "0",
                        "rate": "0.00199200",
                        "surplusLmt": "120.0000000000000000",
                        "usedLmt": "0",
                        "usedLoan": "0.0000000000000000"
                    }
                ]
            }
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
debt | String | 当前负债，单位为`USDT`  
interest | String | 当前记息，单位为`USDT`  
仅适用于`市场借币`  
nextDiscountTime | String | 下次扣息时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
nextInterestTime | String | 下次计息时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
records | Array | 各币种详细信息  
> ccy | String | 借贷币种，如 `BTC`  
> rate | String | 日利率  
> loanQuota | String | 借币限额  
> surplusLmt | String | 剩余可借  
> usedLmt | String | 已借额度  
> interest | String | 已计未扣利息  
仅适用于`市场借币`  
> posLoan | String | 当前账户开仓占用  
仅适用于`尊享借币`  
> availLoan | String | 当前账户剩余可用  
仅适用于`尊享借币`  
> usedLoan | String | 当前账户已借额度  
仅适用于`尊享借币`  
  
### 组合保证金的虚拟持仓保证金计算

计算用户的模拟头寸或当前头寸的投资组合保证金信息，一次请求最多添加200个虚拟仓位

#### 限速：2次/2s

#### 限速规则：UserID

#### HTTP请求

`POST /api/v5/account/simulated_margin`

> 请求示例
    
    
    计算指定业务线已有真实仓位和虚拟仓位的投资组合保证金
    POST /api/v5/account/simulated_margin
    body
    {
       "instType":"SWAP",
       "inclRealPos":"true",
       "simPos":[
         {
              "pos":"10",
              "instId":"BTC-USDT-SWAP"
         },
         {
              "pos":"10",
              "instId":"LTC-USDT-SWAP"
         }
       ]
    }
    
    只计算已有真实仓位
    POST /api/v5/account/simulated_margin
    body
    {
       "inclRealPos":"true"
    }
    
    
    只计算虚拟仓位
    POST /api/v5/account/simulated_margin
    body
    {
       "inclRealPos":"false",
       "simPos":[
         {
              "pos":"10",
              "instId":"BTC-USDT-SWAP"
         },
         {
              "pos":"10",
              "instId":"LTC-USDT-SWAP"
         }
       ]
    }
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instType | String | 否 | 产品类型  
`SWAP`：永续合约  
`FUTURES`：交割合约  
`OPTION`：期权  
inclRealPos | Boolean | 否 | 是否代入已有仓位  
`true`：调整被代入的已有仓位信息  
`false`：不代入已有仓位，仅使用simPos里新增的模拟仓位进行计算,默认为True  
simPos | Array | 否 | 调整持仓列表  
> instId | String | 否 | 交易产品ID  
> pos | String | 否 | 持仓量  
代入的仅是单币种账户、跨币种账户、PM账户里的衍生品买卖模式下的全仓仓位，不包含杠杆仓位。

> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "imr": "0.005432310199023",
                "mmr": "0.0041787001530946",
                "mr1": "0.0041787001530946",
                "mr2": "0.0000734347499275",
                "mr3": "0",
                "mr4": "0",
                "mr5": "0",
                "mr6": "0.0028031968471",
                "mr7": "0.0022",
                "posData": [
                    {
                        "delta": "-0.008926024905498",
                        "gamma": "-0.0707804093543001",
                        "instId": "BTC-USD-220325-50000-C",
                        "instType": "OPTION",
                        "notionalUsd": "3782.9800000000005",
                        "pos": "-1",
                        "theta": "0.000093015207115",
                        "vega": "-0.0000382697346669"
                    }
                ],
                "riskUnit": "BTC-USD",
                "ts": "1646639497536"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
riskUnit | String | 账户内所有持仓的riskUnit  
ts | String | 账户信息的更新时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
mmr | String | riskUnit维度的初始保证金  
imr | String | riskUnit维度的占用保证金  
mr1 | String | 现货&波动率压力测试值  
mr2 | String | 时间价值压力测试值  
mr3 | String | 波动率跨期压力测试值  
mr4 | String | 基差压力测试值  
mr5 | String | 利率风险压力测试值  
mr6 | String | 极端市场波动压力测试值  
mr7 | String | 减仓成本压力测试值  
posData | Array | 持仓列表  
> instId | String | 产品ID，如 `BTC-USD-180216`  
> instType | String | 产品类型  
> pos | String | 持仓量  
> notionalUsd | String | 以美金价值为单位的持仓数量  
> delta | String | 期权价格对uly价格的敏感度  
> gamma | String | delta对uly价格的敏感度  
> vega | String | 权价格对隐含波动率的敏感度  
> theta | String | 期权价格对剩余期限的敏感度  
希腊值单位与账户设置一致，您可通过"config"接口查看。

### 查看账户Greeks

获取账户资产的greeks信息。

#### 限速： 10次/2s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/account/greeks`

> 请求示例
    
    
    获取账户中所有资产的greeks
    GET /api/v5/account/greeks
    
    获取账户中BTC的greeks
    GET /api/v5/account/greeks?ccy=BTC
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
ccy | String | 否 | 币种，如 `BTC`  
  
> 返回结果
    
    
    {
        "code":"0",
        "data":[
            {            
               "thetaBS": "",
               "thetaPA":"",
               "deltaBS":"",
               "deltaPA":"",
               "gammaBS":"",
               "gammaPA":"",
               "vegaBS":"",    
               "vegaPA":"",
               "ccy":"BTC"，
               "ts":"1620282889345"
            }
        ],
        "msg":""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
deltaBS | String | 美金本位账户资产delta  
deltaPA | String | 币本位账户资产delta  
gammaBS | String | 美金本位账户资产gamma，仅适用于`期权`  
gammaPA | String | 币本位账户资产gamma，仅适用于`期权`  
thetaBS | String | 美金本位账户资产theta，仅适用于`期权`  
thetaPA | String | 币本位账户资产theta，仅适用于`期权`  
vegaBS | String | 美金本位账户资产vega，仅适用于`期权`  
vegaPA | String | 币本位账户资产vega，仅适用于`期权`  
ccy | String | 币种  
ts | String | 获取greeks的时间，Unix时间戳的毫秒数格式，如 1597026383085  
  
## 子账户

`子账户`功能模块下的API接口需要身份验证。

### 查看子账户列表

仅适用于母账户

#### 限速：2次/2s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/users/subaccount/list`

> 请求示例
    
    
    GET /api/v5/users/subaccount/list
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
enable | String | 否 | 子账户状态，`true`：正常使用 `false`：冻结  
subAcct | String | 否 | 子账户名称  
after | String | 否 | 查询在此之前的内容，值为时间戳，Unix时间戳为毫秒数格式  
before | String | 否 | 查询在此之后的内容，值为时间戳，Unix时间戳为毫秒数格式  
limit | String | 否 | 分页返回的结果集数量，最大为100，不填默认返回100条  
  
> 返回结果
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
           {
              "enable":true,
              "subAcct":"test-1",
              "type":"1",
              "label":"trade futures",
              "mobile":"1818181",
              "gAuth":true,
              "canTransOut": true,
              "ts":"1597026383085"
           },
           {
              "enable":false,
              "subAcct":"test-2",
              "type":"1",
              "label":"trade spot",
              "mobile":"1818199",
              "gAuth":true,
              "canTransOut": false,
              "ts":"1597026383082"
           }
    
        ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
type | String | 子账户类型，`1`:普通子账户 `2`:托管子账户  
enable | Boolean | 子账户状态，`true`：正常使用 `false`：冻结  
subAcct | String | 子账户名称  
label | String | 子账户备注  
mobile | String | 子账户绑定手机号  
gAuth | String | 子账户是否开启的登录时的谷歌验证 `true`：已开启 `false`：未开启  
canTransOut | Boolean | 是否可以主动转出，`false`：不可转出，`true`：可以转出  
ts | String | 子账户创建时间，Unix时间戳的毫秒数格式 ，如 `1597026383085`  
  
### 获取子账户资产余额

获取子账户资产余额（适用于母账户）

#### 限速：2次/2s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/account/subaccount/balances`

> 请求示例
    
    
    GET /api/v5/account/subaccount/balances?subAcct=test1
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
subAcct | String | 是 | 子账户名称  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "adjEq": "10679688.0460531643092577",
                "details": [
                    {
                        "availBal": "",
                        "availEq": "9930359.9998",
                        "cashBal": "9930359.9998",
                        "ccy": "USDT",
                        "crossLiab": "0",
                        "disEq": "9439737.0772999514",
                        "eq": "9930359.9998",
                        "eqUsd": "9933041.196999946",
                        "frozenBal": "0",
                        "interest": "0",
                        "isoEq": "0",
                        "isoLiab": "0",
                        "liab": "0",
                        "maxLoan": "10000",
                        "mgnRatio": "",
                        "notionalLever": "",
                        "ordFrozen": "0",
                        "twap": "0",
                        "uTime": "1620722938250",
                        "upl": "0",
                        "uplLiab": "0"
                    },
                    {
                        "availBal": "",
                        "availEq": "33.6799714158199414",
                        "cashBal": "33.2009985",
                        "ccy": "BTC",
                        "crossLiab": "0",
                        "disEq": "1239950.9687532129092577",
                        "eq": "33.771820625136023",
                        "eqUsd": "1239950.9687532129092577",
                        "frozenBal": "0.0918492093160816",
                        "interest": "0",
                        "isoEq": "0",
                        "isoLiab": "0",
                        "liab": "0",
                        "maxLoan": "1453.92289531493594",
                        "mgnRatio": "",
                        "notionalLever": "",
                        "ordFrozen": "0",
                        "twap": "0",
                        "uTime": "1620722938250",
                        "upl": "0.570822125136023",
                        "uplLiab": "0"
                    }
                ],
                "imr": "3372.2942371050594217",
                "isoEq": "0",
                "mgnRatio": "70375.35408747017",
                "mmr": "134.8917694842024",
                "notionalUsd": "33722.9423710505978888",
                "ordFroz": "0",
                "totalEq": "11172992.1657531589092577",
                "uTime": "1623392334718"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
uTime | String | 获取账户信息的最新时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
totalEq | String | 美金层面权益  
isoEq | String | 美金层面逐仓仓位权益  
适用于`单币种保证金模式`和`跨币种保证金模式`和`组合保证金模式`  
adjEq | String | 美金层面有效保证金  
适用于`跨币种保证金模式`和`组合保证金模式`  
ordFroz | String | 美金层面全仓挂单占用保证金  
适用于`跨币种保证金模式`和`组合保证金模式`  
imr | String | 美金层面占用保证金  
适用于`跨币种保证金模式`和`组合保证金模式`  
mmr | String | 美金层面维持保证金  
适用于`跨币种保证金模式`和`组合保证金模式`  
mgnRatio | String | 美金层面保证金率  
适用于`跨币种保证金模式`和`组合保证金模式`  
notionalUsd | String | 以美金价值为单位的持仓数量，即仓位美金价值  
适用于`跨币种保证金模式`和`组合保证金模式`  
details | Array | 各币种资产详细信息  
> ccy | String | 币种  
> eq | String | 币种总权益  
> cashBal | String | 币种余额  
> uTime | String | 币种余额信息的更新时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
> isoEq | String | 币种逐仓仓位权益  
适用于`单币种保证金模式`和`跨币种保证金模式`  
> availEq | String | 可用保证金  
适用于`单币种保证金模式`和`跨币种保证金模式`  
> disEq | String | 美金层面币种折算权益  
> availBal | String | 可用余额  
适用于`简单交易模式`  
> frozenBal | String | 币种占用金额  
> ordFrozen | String | 挂单冻结数量  
> liab | String | 币种负债额  
适用于`跨币种保证金模式`和`组合保证金模式`  
> upl | String | 未实现盈亏  
适用于`单币种保证金模式`和`跨币种保证金模式`和`组合保证金模式`  
> uplLiab | String | 由于仓位未实现亏损导致的负债  
适用于`跨币种保证金模式`和`组合保证金模式`  
> crossLiab | String | 币种全仓负债额  
适用于`跨币种保证金模式`和`组合保证金模式`  
> isoLiab | String | 币种逐仓负债额  
适用于`跨币种保证金模式`和`组合保证金模式`  
> mgnRatio | String | 保证金率  
适用于`单币种保证金模式`  
> interest | String | 计息  
适用于`跨币种保证金模式`和`组合保证金模式`  
> twap | String | 当前负债币种触发系统自动换币的风险  
0、1、2、3、4、5其中之一，数字越大代表您的负债币种触发自动换币概率越高  
适用于`跨币种保证金模式`和`组合保证金模式`  
> maxLoan | String | 币种最大可借  
适用于`跨币种保证金模式`和`组合保证金模式`  
> eqUsd | String | 币种权益美金价值  
> notionalLever | String | 币种杠杆倍数  
适用于`单币种保证金模式`  
当前账户等级下无效字段返回""

### 查询子账户转账记录

仅适用于母账户

#### 限速：6次/s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/asset/subaccount/bills`

> 请求示例
    
    
    GET /api/v5/asset/subaccount/bills
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
ccy | String | 否 | 币种，如 BTC  
type | String | 否 | `0`: 母账户转子账户 ；`1` : 子账户转母账户  
subAcct | String | 否 | 子账户名称  
after | String | 否 | 查询在此之前的内容，值为时间戳，Unix时间戳为毫秒数格式  
before | String | 否 | 查询在此之后的内容，值为时间戳，Unix时间戳为毫秒数格式  
limit | String | 否 | 分页返回的结果集数量，最大为100，不填默认返回100条  
  
> 返回结果
    
    
    {
            "code": "0",
            "msg": "",
            "data": [{
                    "billId": "12344",
                    "type":"1",
                    "ccy": "BTC",
                    "amt":"2",
                    "subAcct":"test-1",
                    "ts":"1597026383085"
            }]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
billId | String | 账单ID  
ccy | String | 账户余额币种  
amt | String | 划转金额  
type | String | 账单类型  
subAcct | String | 子账户名称  
ts | String | 子账户创建时间，Unix时间戳的毫秒数格式 ，如 `1597026383085`  
  
### 子账户间资金划转

母账户控制子账户与子账户之间划转（仅适用于母账户）

#### 限速：1次/s

#### 限速规则：UserID

#### HTTP请求

`POST /api/v5/asset/subaccount/transfer`

> 请求示例
    
    
    POST /api/v5/asset/subaccount/transfer
    body
    {
        "ccy":"USDT",
        "amt":"1.5",
        "from":"6",
        "to":"6",
        "fromSubAccount":"test-1",
        "toSubAccount":"test-2"
    }
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
ccy | String | 是 | 币种  
amt | String | 是 | 划转数量  
from | String | 是 | `6`：资金账户 `18`：交易账户  
to | String | 是 | `6`：资金账户 `18`：交易账户  
fromSubAccount | String | 是 | 转出子账户的子账户名称  
toSubAccount | String | 是 | 转入子账户的子账户名称  
loanTrans | Boolean | 否 | 是否支持`跨币种保证金模式`或`组合保证金模式`下的借币转入/转出  
true 或 false，默认false  
  
> 返回结果
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
            {
                "transId":"12345",
            }
        ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
transId | String | 划转ID  
  
### 设置子账户主动转出权限

设置子账户转出权限（仅适用于母账户），默认可转出至母账户。

#### 限速：1次/s

#### 限速规则：UserID

#### HTTP请求

`POST /api/v5/users/subaccount/set-transfer-out`

> 请求示例
    
    
    POST /api/v5/users/subaccount/set-transfer-out
    body
    {
        "subAcct":"test-1",
        "canTransOut":true
    }
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
subAcct | String | 是 | 子账户名称，支持设置多个（不超过20个），子账户名称之间半角逗号分隔  
canTransOut | Boolean | 否 | 是否可以主动转出，`false`：不可转出，`true`：可以转出，默认为`true`  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "subAcct": "test-1",
                "canTransOut": true
            }
        ],
        "msg": ""
    }
    
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
subAcct | String | 子账户名称  
canTransOut | Boolean | 是否可以主动转出，`false`：不可转出，`true`：可以转出  
  
### 查看被托管的子账户列表

交易团队使用该接口查看当前托管中的子账户列表

#### 限速：1次/s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/users/entrust-subaccount-list`

> 请求示例
    
    
    GET /api/v5/users/entrust-subaccount-list
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
subAcct | String | 否 | 子账户名称  
  
> 返回结果
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
                       {
                          "subAcct":"test-1"
                       },
                       {
                          "subAcct":"test-2"
                       }
    
        ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
subAcct | String | 子账户名称  
  
## 行情数据

`行情数据`功能模块下的API接口不需要身份验证。

### 获取所有产品行情信息

获取产品行情信息

#### 限速： 20次/2s

#### 限速规则：IP

#### HTTP请求

`GET /api/v5/market/tickers`

> 请求示例
    
    
    GET /api/v5/market/tickers?instType=SWAP
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instType | String | 是 | 产品类型  
`SPOT`：币币  
`SWAP`：永续合约  
`FUTURES`：交割合约  
`OPTION`：期权  
uly | String | 否 | 标的指数，仅适用于`交割/永续/期权` ，如 `BTC-USD`  
  
> 返回结果
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
         {
            "instType":"SWAP",
            "instId":"LTC-USD-SWAP",
            "last":"9999.99",
            "lastSz":"0.1",
            "askPx":"9999.99",
            "askSz":"11",
            "bidPx":"8888.88",
            "bidSz":"5",
            "open24h":"9000",
            "high24h":"10000",
            "low24h":"8888.88",
            "volCcy24h":"2222",
            "vol24h":"2222",
            "sodUtc0":"0.1",
            "sodUtc8":"0.1",
            "ts":"1597026383085"
         },
         {
            "instType":"SWAP",
            "instId":"BTC-USD-SWAP",
            "last":"9999.99",
            "lastSz":"0.1",
            "askPx":"9999.99",
            "askSz":"11",
            "bidPx":"8888.88",
            "bidSz":"5",
            "open24h":"9000",
            "high24h":"10000",
            "low24h":"8888.88",
            "volCcy24h":"2222",
            "vol24h":"2222",
            "sodUtc0":"0.1",
            "sodUtc8":"0.1",
            "ts":"1597026383085"
        }
      ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
instType | String | 产品类型  
instId | String | 产品ID  
last | String | 最新成交价  
lastSz | String | 最新成交的数量  
askPx | String | 卖一价  
askSz | String | 卖一价的挂单数数量  
bidPx | String | 买一价  
bidSz | String | 买一价的挂单数量  
open24h | String | 24小时开盘价  
high24h | String | 24小时最高价  
low24h | String | 24小时最低价  
volCcy24h | String | 24小时成交量，以`币`为单位  
如果是`衍生品`合约，数值为交易货币的数量。  
如果是`币币/币币杠杆`，数值为计价货币的数量。  
vol24h | String | 24小时成交量，以`张`为单位  
如果是`衍生品`合约，数值为合约的张数。  
如果是`币币/币币杠杆`，数值为交易货币的数量。  
sodUtc0 | String | UTC 0 时开盘价  
sodUtc8 | String | UTC+8 时开盘价  
ts | String | ticker数据产生时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
  
### 获取单个产品行情信息

获取产品行情信息

#### 限速： 20次/2s

#### 限速规则：IP

#### HTTP请求

`GET /api/v5/market/ticker`

> 请求示例
    
    
    GET /api/v5/market/ticker?instId=BTC-USD-SWAP
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instId | String | 是 | 产品ID，如 `BTC-USD-SWAP`  
  
> 返回结果
    
    
    {
        "code": "0",
        "msg": "",
        "data": [
            {
                "instType": "SWAP",
                "instId": "BTC-USD-SWAP",
                "last": "56956.1",
                "lastSz": "3",
                "askPx": "56959.1",
                "askSz": "10582",
                "bidPx": "56959",
                "bidSz": "4552",
                "open24h": "55926",
                "high24h": "57641.1",
                "low24h": "54570.1",
                "volCcy24h": "81137.755",
                "vol24h": "46258703",
                "ts": "1620289117764",
                "sodUtc0": "55926",
                "sodUtc8": "55926"
            }
        ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
instType | String | 产品类型  
instId | String | 产品ID  
last | String | 最新成交价  
lastSz | String | 最新成交的数量  
askPx | String | 卖一价  
askSz | String | 卖一价对应的数量  
bidPx | String | 买一价  
bidSz | String | 买一价对应的数量  
open24h | String | 24小时开盘价  
high24h | String | 24小时最高价  
low24h | String | 24小时最低价  
volCcy24h | String | 24小时成交量，以`币`为单位  
如果是`衍生品`合约，数值为交易货币的数量。  
如果是`币币/币币杠杆`，数值为计价货币的数量。  
vol24h | String | 24小时成交量，以`张`为单位  
如果是`衍生品`合约，数值为合约的张数。  
如果是`币币/币币杠杆`，数值为交易货币的数量。  
sodUtc0 | String | UTC 0 时开盘价  
sodUtc8 | String | UTC+8 时开盘价  
ts | String | ticker数据产生时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
  
### 获取指数行情

获取指数行情数据

#### 限速： 20次/2s

#### 限速规则：IP

#### HTTP请求

`GET /api/v5/market/index-tickers`

> 请求示例
    
    
    GET /api/v5/market/index-tickers?instId=BTC-USDT
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
quoteCcy | String | 可选 | 指数计价单位， 目前只有
`USD/USDT/BTC`为计价单位的指数，`quoteCcy`和`instId`必须填写一个  
instId | String | 可选 | 指数，如 `BTC-USD`  
  
> 返回结果
    
    
    {
        "code": "0",
        "msg": "",
        "data": [
            {
                "instId": "BTC-USDT",
                "idxPx": "43350",
                "high24h": "43649.7",
                "sodUtc0": "43444.1",
                "open24h": "43640.8",
                "low24h": "43261.9",
                "sodUtc8": "43328.7",
                "ts": "1649419644492"
            }
        ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
instId | String | 指数  
idxPx | String | 最新指数价格  
high24h | String | 24小时指数最高价格  
low24h | String | 24小时指数最低价格  
open24h | String | 24小时指数开盘价格  
sodUtc0 | String | UTC 0 时开盘价  
sodUtc8 | String | UTC+8 时开盘价  
ts | String | 指数价格更新时间，Unix时间戳的毫秒数格式，如`1597026383085`  
  
### 获取产品深度

获取产品深度列表

#### 限速： 20次/2s

#### 限速规则：IP

#### HTTP请求

`GET /api/v5/market/books`

> 请求示例
    
    
    GET /api/v5/market/books?instId=BTC-USDT
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instId | String | 是 | 产品ID，如 `BTC-USDT`  
sz | String | 否 | 深度档位数量，最大值可传400，即买卖深度共800条  
不填写此参数，默认返回`1`档深度数据  
  
> 返回结果
    
    
    {
        "code": "0",
        "msg": "",
        "data": [
            {
                "asks": [
                    [
                        "41006.8",
                        "0.60038921",
                        "0",
                        "1"
                    ]
                ],
                "bids": [
                    [
                        "41006.3",
                        "0.30178218",
                        "0",
                        "2"
                    ]
                ],
                "ts": "1629966436396"
            }
        ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
asks | Array | 卖方深度  
bids | Array | 买方深度  
ts | String | 深度产生的时间  
合约的asks和bids值数组举例说明： ["411.8","10", "0","4"]
411.8为深度价格，10为此价格的合约张数，0该字段已弃用(始终为0)，4为此价格的订单数量  
现货/币币杠杆的asks和bids值数组举例说明： ["411.8","10", "0","4"]
411.8为深度价格，10为此价格的币的数量，0该字段已弃用(始终为0)，4为此价格的订单数量

### 获取交易产品K线数据

获取K线数据。K线数据按请求的粒度分组返回，K线数据每个粒度最多可获取最近1440条。

#### 限速： 20次/2s

#### 限速规则：IP

#### HTTP请求

`GET /api/v5/market/candles`

> 请求示例
    
    
    GET /api/v5/market/candles?instId=BTC-USD-190927-5000-C
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instId | String | 是 | 产品ID，如`BTC-USD-190927-5000-C`  
bar | String | 否 | 时间粒度，默认值`1m`  
如 [1m/3m/5m/15m/30m/1H/2H/4H]  
香港时间开盘价k线：[6H/12H/1D/2D/3D/1W/1M/3M/6M/1Y]  
UTC时间开盘价k线：[/6Hutc/12Hutc/1Dutc/2Dutc/3Dutc/1Wutc/1Mutc/3Mutc/6Mutc/1Yutc]  
after | String | 否 | 请求此时间戳之前（更旧的数据）的分页内容，传的值为对应接口的`ts`  
before | String | 否 | 请求此时间戳之后（更新的数据）的分页内容，传的值为对应接口的`ts`  
limit | String | 否 | 分页返回的结果集数量，最大为300，不填默认返回100条  
  
> 返回结果
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
         [
            "1597026383085",
            "3.721",
            "3.743",
            "3.677",
            "3.708",
            "8422410",
            "22698348.04828491"
        ],
        [
            "1597026383085",
            "3.731",
            "3.799",
            "3.494",
            "3.72",
            "24912403",
            "67632347.24399722"
        ]
        ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
ts | String | 数据生成的时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
o | String | 开盘价格  
h | String | 最高价格  
l | String | 最低价格  
c | String | 收盘价格  
vol | String | 交易量，以`张`为单位  
如果是`衍生品`合约，数值为合约的张数。  
如果是`币币/币币杠杆`，数值为交易货币的数量。  
volCcy | String | 交易量，以`币`为单位  
如果是`衍生品`合约，数值为交易货币的数量。  
如果是`币币/币币杠杆`，数值为计价货币的数量。  
返回的第一条K线数据可能不是完整周期k线，返回值数组顺序分别为是：[ts,o,h,l,c,vol,volCcy]

### 获取交易产品历史K线数据

获取最近几年的历史k线数据

#### 限速： 20次/2s

#### 限速规则：IP

#### HTTP请求

`GET /api/v5/market/history-candles`

> 请求示例
    
    
    GET /api/v5/market/history-candles?instId=BTC-USD-190927
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instId | String | 是 | 产品ID，如`BTC-USD-200927`  
after | String | 否 | 请求此时间戳之前（更旧的数据）的分页内容，传的值为对应接口的`ts`  
before | String | 否 | 请求此时间戳之后（更新的数据）的分页内容，传的值为对应接口的`ts`  
bar | String | 否 | 时间粒度，默认值`1m`  
如 [1m/3m/5m/15m/30m/1H/2H/4H]  
香港时间开盘价k线：[6H/12H/1D/2D/3D/1W/1M/3M/6M/1Y]  
UTC时间开盘价k线：[6Hutc/12Hutc/1Dutc/2Dutc/3Dutc/1Wutc/1Mutc/3Mutc/6Mutc/1Yutc]  
limit | String | 否 | 分页返回的结果集数量，最大为100，不填默认返回100条  
  
> 返回结果
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
         [
            "1597026383085",
            "3.721",
            "3.743",
            "3.677",
            "3.708",
            "8422410",
            "22698348.04828491"
        ],
        [
            "1597026383085",
            "3.731",
            "3.799",
            "3.494",
            "3.72",
            "24912403",
            "67632347.24399722"
        ]
        ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
ts | String | 数据生成的时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
o | String | 开盘价格  
h | String | 最高价格  
l | String | 最低价格  
c | String | 收盘价格  
vol | String | 交易量，以`张`为单位  
如果是`衍生品`合约，数值为合约的张数。  
如果是`币币/币币杠杆`，数值为交易货币的数量。  
volCcy | String | 交易量，以`币`为单位  
如果是`衍生品`合约，数值为交易货币的数量。  
如果是`币币/币币杠杆`，数值为计价货币的数量。  
返回值数组顺序分别为是：[ts,o,h,l,c,vol,volCcy]

### 获取指数K线数据

指数K线数据每个粒度最多可获取最近1440条。

#### 限速： 20次/2s

#### 限速规则：IP

#### HTTP请求

`GET /api/v5/market/index-candles`

> 请求示例
    
    
    GET /api/v5/market/index-candles?instId=BTC-USD
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instId | String | 是 | 现货指数，如`BTC-USD`  
after | String | 否 | 请求此时间戳之前（更旧的数据）的分页内容，传的值为对应接口的`ts`  
before | String | 否 | 请求此时间戳之后（更新的数据）的分页内容，传的值为对应接口的`ts`  
bar | String | 否 | 时间粒度，默认值`1m`  
如 [1m/3m/5m/15m/30m/1H/2H/4H]  
香港时间开盘价k线：[6H/12H/1D/1W/1M/3M/6M/1Y]  
UTC时间开盘价k线：[/6Hutc/12Hutc/1Dutc/1Wutc/1Mutc/3Mutc/6Mutc/1Yutc]  
limit | String | 否 | 分页返回的结果集数量，最大为100，不填默认返回100条  
  
> 返回结果
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
         [
            "1597026383085",
            "3.721",
            "3.743",
            "3.677",
            "3.708"
        ],
        [
            "1597026383085",
            "3.731",
            "3.799",
            "3.494",
            "3.72"
        ]
        ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
ts | String | 开始时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
o | String | 开盘价格  
h | String | 最高价格  
l | String | 最低价格  
c | String | 收盘价格  
返回的第一条K线数据可能不是完整周期k线，返回值数组顺序分别为是：[ts,o,h,l,c]

### 获取标记价格K线数据

标记价格K线数据每个粒度最多可获取最近1440条。

#### 限速： 20次/2s

#### 限速规则：IP

#### HTTP请求

`GET /api/v5/market/mark-price-candles`

> 请求示例
    
    
    GET /api/v5/market/mark-price-candles?instId=BTC-USD-SWAP
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instId | String | 是 | 产品ID，如`BTC-USD-SWAP`  
after | String | 否 | 请求此时间戳之前（更旧的数据）的分页内容，传的值为对应接口的`ts`  
before | String | 否 | 请求此时间戳之后（更新的数据）的分页内容，传的值为对应接口的`ts`  
bar | String | 否 | 时间粒度，默认值`1m`  
如 [1m/3m/5m/15m/30m/1H/2H/4H]  
香港时间开盘价k线：[6H/12H/1D/1W/1M/3M/6M/1Y]  
UTC时间开盘价k线：[6Hutc/12Hutc/1Dutc/1Wutc/1Mutc/3Mutc/6Mutc/1Yutc]  
limit | String | 否 | 分页返回的结果集数量，最大为100，不填默认返回100条  
  
> 返回结果
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
         [
            "1597026383085",
            "3.721",
            "3.743",
            "3.677",
            "3.708"
        ],
        [
            "1597026383085",
            "3.731",
            "3.799",
            "3.494",
            "3.72"
        ]
        ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
ts | String | 开始时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
o | String | 开盘价格  
h | String | 最高价格  
l | String | 最低价格  
c | String | 收盘价格  
返回的第一条K线数据可能不是完整周期k线，返回值数组顺序分别为是：[ts,o,h,l,c]

### 获取交易产品公共成交数据

查询市场上的成交信息数据

#### 限速： 20次/2s

#### 限速规则：IP

#### HTTP请求

`GET /api/v5/market/trades`

> 请求示例
    
    
    GET /api/v5/market/trades?instId=BTC-USDT
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instId | String | 是 | 产品ID，如 `BTC-USDT`  
limit | String | 否 | 分页返回的结果集数量，最大为500，不填默认返回100条  
  
> 返回结果
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
         {
            "instId":"BTC-USDT",
            "tradeId":"9",
            "px":"0.016",
            "sz":"50",
            "side":"buy",
            "ts":"1597026383085"
        },
        {
            "instId":"BTC-USDT",
            "tradeId":"9",
            "px":"0.016",
            "sz":"50",
            "side":"buy",
            "ts":"1597026383085"
        }
      ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
instId | String | 产品ID  
tradeId | String | 成交ID  
px | String | 成交价格  
sz | String | 成交数量  
side | String | 成交方向  
`buy`：买  
`sell`：卖  
ts | String | 成交时间，Unix时间戳的毫秒数格式， 如`1597026383085`  
最多获取最近500条历史公共成交数据

### 获取平台24小时总成交量

24小时成交量滚动计算，以USD为计价单位。

#### 限速： 2次/2s

#### 限速规则：IP

#### HTTP请求

`GET /api/v5/market/platform-24-volume`

> 请求示例
    
    
    GET /api/v5/market/platform-24-volume
    
    

> 返回结果
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
         {
            "volUsd":"2222",
            "volCny":"14220.8",
            "ts": "1597026383085"
         }
      ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
volUsd | String | 24小时平台总成交量，以美元为单位  
volCny | String | 24小时平台总成交量，以人民币为单位  
ts | String | 接口返回数据时间  
  
### Oracle 上链交易数据

获取使用 Open Oracle 智能合约签名后加密资产价格。

#### 限速： 1次/5s

#### 限速规则：IP

#### HTTP请求

`GET /api/v5/market/open-oracle`

> 请求示例
    
    
    GET /api/v5/market/open-oracle
    

> 返回结果
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
            {
                "messages":[
                    "0x000000000000000000000000000000000000000000000000000000000000008000000000000000000000000000000000000000000000000000000000616d3b1400000000000000000000000000000000000000000000000000000000000000c00000000000000000000000000000000000000000000000000000000e70528b800000000000000000000000000000000000000000000000000000000000000006707269636573000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000034254430000000000000000000000000000000000000000000000000000000000"
                ],
                "prices":{
                    "BTC":"62014"
                },
                "signatures":[
                    "0xf18330e59eaf42373c2c40f1f9e24113ba21d4ed734dd3ed3bc1d12290fa74ba5623fca1113c5d245a1202dc065e333615b90f810f12132ce4a1ecacb8c6b24a000000000000000000000000000000000000000000000000000000000000001b"
                ],
                "timestamp":"1634548500"
            }
        ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
messages | String | 数组包含对[
kind，timestamp，key，value]进行ABI编码的值，其中kind恒等于`prices`，timestamp是获取价格的时间戳，key是加密资产（例如，`ETH`），value是资产价格  
price | String | 价格  
signatures | String | 每个消息的以太坊兼容ECDSA签名的数组  
timestamp | String | 获取最新数据点的时间,Unix时间戳,如 `1597026387`  
欧易 Oracle公钥是 85615b076615317c80f14cbad6501eec031cd51c

### 获取法币汇率

该接口提供的是2周的平均汇率数据

#### 限速： 1次/2s

#### 限速规则：IP

#### HTTP请求

`GET /api/v5/market/exchange-rate`

> 请求示例
    
    
    GET /api/v5/market/exchange-rate
    

> 返回结果
    
    
    {
        "code": "0",
        "msg": "",
        "data": [ {
                "usdCny": "6.44"
    }]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
usdCny | String | 人民币兑美元汇率  
  
### 获取指数成分数据

查询市场上的指数成分信息数据

#### 限速： 20次/2s

#### 限速规则：IP

#### HTTP请求

`GET /api/v5/market/index-components`

> 请求示例
    
    
    GET /api/v5/market/index-components?index=BTC-USD
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
index | String | 是 | 指数，如 `BTC-USDT`  
  
> 返回结果
    
    
    {
        "code": "0",
        "msg": "",
        "data": {
            "components": [
                {
                    "symbol": "BTC/USDT",
                    "symPx": "52733.2",
                    "wgt": "0.250",
                    "cnvPx": "52733.2",
                    "exch": "OKEx"
                },
                {
                    "symbol": "BTC/USDT",
                    "symPx": "52739.87000000",
                    "wgt": "0.250",
                    "cnvPx": "52739.87000000",
                    "exch": "Binance"
                },
                {
                    "symbol": "BTC/USDT",
                    "symPx": "52729.1",
                    "wgt": "0.250",
                    "cnvPx": "52729.1",
                    "exch": "Huobi"
                },
                {
                    "symbol": "BTC/USDT",
                    "symPx": "52739.47929397",
                    "wgt": "0.250",
                    "cnvPx": "52739.47929397",
                    "exch": "Poloniex"
                }
            ],
            "last": "52735.4123234925",
            "index": "BTC-USDT",
            "ts": "1630985335599"
        }
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
index | String | 指数名称  
last | String | 最新指数价格  
ts | String | 数据产生时间，Unix时间戳的毫秒数格式， 如`1597026383085`  
components | String | 成分  
> exch | String | 交易所名称  
> symbol | String | 采集的币对名称  
> symPx | String | 采集的币对价格  
> wgt | String | 权重  
> cnvPx | String | 换算成指数后的价格  
  
## 公共数据

`公共数据`功能模块下的API接口不需要身份验证。

### 获取交易产品基础信息

获取所有可交易产品的信息列表。

#### 限速： 20次/2s

#### 限速规则：IP +instType

#### HTTP请求

`GET /api/v5/public/instruments`

> 请求示例
    
    
    GET /api/v5/public/instruments?instType=SPOT
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instType | String | 是 | 产品类型  
`SPOT`：币币  
`MARGIN`：币币杠杆  
`SWAP`：永续合约  
`FUTURES`：交割合约  
`OPTION`：期权  
uly | String | 可选 | 标的指数，仅适用于`交割/永续/期权`，期权必填  
instId | String | 否 | 产品ID  
  
> 返回结果
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
        {
            "instType":"SWAP",
            "instId":"LTC-USD-SWAP",
            "uly":"LTC-USD",
            "category":"1",
            "baseCcy":"",
            "quoteCcy":"",
            "settleCcy":"LTC",
            "ctVal":"10",
            "ctMult":"1",
            "ctValCcy":"USD",
            "optType":"C",
            "stk":"",
            "listTime":"1597026383085",
            "expTime":"1597026383085",
            "lever":"10",
            "tickSz":"0.01",
            "lotSz":"1",
            "minSz":"1",
            "ctType":"inverse",
            "alias":"this_week",
            "state":"live",
            "maxLmtSz":"10000",
            "maxMktSz":"99999",
            "maxTwapSz":"99999",
            "maxIcebergSz":"99999",
            "maxTriggerSz":"9999",
            "maxStopSz":"9999"
        }
      ]
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
instType | String | 产品类型  
instId | String | 产品id， 如 `BTC-USD-SWAP`  
uly | String | 标的指数，如 `BTC-USD`，仅适用于`交割/永续/期权`  
category | String | 手续费档位，每个交易产品属于哪个档位手续费  
baseCcy | String | 交易货币币种，如 `BTC-USDT` 中的 `BTC` ，仅适用于`币币`  
quoteCcy | String | 计价货币币种，如 `BTC-USDT` 中的`USDT` ，仅适用于`币币`  
settleCcy | String | 盈亏结算和保证金币种，如 `BTC` 仅适用于`交割/永续/期权`  
ctVal | String | 合约面值，仅适用于`交割/永续/期权`  
ctMult | String | 合约乘数，仅适用于`交割/永续/期权`  
ctValCcy | String | 合约面值计价币种，仅适用于`交割/永续/期权`  
optType | String | 期权类型，`C`或`P` 仅适用于`期权`  
stk | String | 行权价格，仅适用于`期权`  
listTime | String | 上线日期  
Unix时间戳的毫秒数格式，如 `1597026383085`  
expTime | String | 交割/行权日期，仅适用于`交割` 和 `期权`  
Unix时间戳的毫秒数格式，如 `1597026383085`  
lever | String | 该`instId`支持的最大杠杆倍数，不适用于`币币`、`期权`  
tickSz | String | 下单价格精度，如 `0.0001`  
  
lotSz | String | 下单数量精度，如 BTC-USDT-SWAP：`1`  
minSz | String | 最小下单数量  
ctType | String | `linear`：正向合约  
`inverse`：反向合约  
仅适用于`交割/永续`  
alias | String | 合约日期别名  
`this_week`：本周  
`next_week`：次周  
`quarter`：季度  
`next_quarter`：次季度  
仅适用于`交割`  
state | String | 产品状态  
`live`：交易中  
`suspend`：暂停中  
`preopen`：预上线  
`settlement`：资金费结算  
maxLmtSz | String | 合约或现货限价单的单笔最大委托数量  
maxMktSz | String | 合约或现货市价单的单笔最大委托数量  
maxTwapSz | String | 合约或现货时间加权单的单笔最大委托数量  
maxIcebergSz | String | 合约或现货冰山委托的单笔最大委托数量  
maxTriggerSz | String | 合约或现货计划委托委托的单笔最大委托数量  
maxStopSz | String | 合约或现货止盈止损委托的单笔最大委托数量  
当有系统升级，或者产品升级，或者故障问题时，产品的状态变更为暂停中；
当恢复时，状态变更为交易中；当合约预上线时，状态变更为预上线（即新生成一个合约，新合约会处于预上线状态）；
当产品下线的时候（如交割合约被交割的时候，期权合约被行权的时候），查询不到该产品

### 获取交割和行权记录

获取3个月内的交割合约的交割记录和期权的行权记录

#### 限速： 40次/2s

#### 限速规则：IP +(instrumentType、uly)

#### HTTP请求

`GET /api/v5/public/delivery-exercise-history`

> 请求示例
    
    
    GET /api/v5/public/delivery-exercise-history?instType=OPTION&uly=BTC-USD
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instType | String | 是 | 产品类型  
`FUTURES`：交割合约  
`OPTION`：期权  
uly | String | 是 | 标的指数，仅适用于`交割/期权`  
after | String | 否 | 请求此时间戳之前（更旧的数据）的分页内容，传的值为对应接口的`ts`  
before | String | 否 | 请求此时间戳之后（更新的数据）的分页内容，传的值为对应接口的`ts`  
limit | String | 否 | 分页返回的结果集数量，最大为100，不填默认返回100条  
  
> 返回结果
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
            {
                "ts":"1597026383085",
                "details":[
                    {
                        "type":"delivery",
                        "instId":"BTC-USD-190927",
                        "px":"0.016"
                    }
                ]
            },
            {
                "ts":"1597026383085",
                "details":[
                    {
                        "instId":"BTC-USD-200529-6000-C",
                        "type":"exercised",
                        "px":"0.016"
                    },
                    {
                        "instId":"BTC-USD-200529-8000-C",
                        "type":"exercised",
                        "px":"0.016"
                    }
                ]
            }
        ]
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
ts | String | 交割/行权日期，Unix时间戳的毫秒数格式，如 `1597026383085`  
details | String | 详细数据  
> instId | String | 交割/行权的合约ID  
> px | String | 交割/行权的价格  
> type | String | 类型  
`delivery`：交割  
`exercised`：实值已行权  
`expired_otm`：虚值已过期  
  
### 获取持仓总量

查询单个交易产品的市场的持仓总量

#### 限速： 20次/2s

#### 限速规则：IP +instrumentID

#### HTTP请求

`GET /api/v5/public/open-interest`

> 请求示例
    
    
    GET /api/v5/public/open-interest?instType=SWAP
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instType | String | 是 | 产品类型  
`SWAP`：永续合约  
`FUTURES`：交割合约  
`OPTION`：期权  
uly | String | 否 | 标的指数，仅适用于`交割/永续/期权`，期权必填  
instId | String | 否 | 产品ID，如 `BTC-USD-180216`  
仅适用于`交割/永续/期权`  
  
> 返回结果
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
        {
            "instType":"SWAP",
            "instId":"BTC-USDT-SWAP",
            "oi":"5000",
            "oiCcy":"555.55",
            "ts":"1597026383085"
        }
      ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
instType | String | 产品类型  
instId | String | 产品ID  
oi | String | 持仓量（按`张`折算）  
oiCcy | String | 持仓量（按`币`折算）  
ts | String | 数据返回时间，Unix时间戳的毫秒数格式 ，如 `1597026383085`  
  
### 获取永续合约当前资金费率

获取当前资金费率

#### 限速： 20次/2s

#### 限速规则：IP +instrumentID

#### HTTP请求

`GET /api/v5/public/funding-rate`

> 请求示例
    
    
    GET /api/v5/public/funding-rate?instId=BTC-USD-SWAP
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instId | String | 是 | 产品ID ，如 `BTC-USD-SWAP`  
仅适用于`永续`  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "fundingRate": "0.0001515",
                "fundingTime": "1622822400000",
                "instId": "BTC-USD-SWAP",
                "instType": "SWAP",
                "nextFundingRate": "0.00029",
                "nextFundingTime": "1622851200000"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
instType | String | 产品类型 `SWAP`：永续合约  
instId | String | 产品ID，如`BTC-USD-SWAP`  
fundingRate | String | 资金费率  
nextFundingRate | String | 下一期预测资金费率  
fundingTime | String | 资金费时间 ，Unix时间戳的毫秒数格式，如 `1597026383085`  
nextFundingTime | String | 下一期资金费时间 ，Unix时间戳的毫秒数格式，如 `1622851200000`  
  
### 获取永续合约历史资金费率

获取最近3个月的历史资金费率

#### 限速： 10次/2s

#### 限速规则：IP +instrumentID

#### HTTP请求

`GET /api/v5/public/funding-rate-history`

> 请求示例
    
    
    GET /api/v5/public/funding-rate-history?instId=BTC-USD-SWAP
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instId | String | 是 | 产品ID ，如 `BTC-USD-SWAP`  
仅适用于`永续`  
before | String | 否 | 请求此时间戳之后（更新的数据）的分页内容，传的值为对应接口的`fundingTime`  
after | String | 否 | 请求此时间戳之前（更旧的数据）的分页内容，传的值为对应接口的`fundingTime`  
limit | String | 否 | 分页返回的结果集数量，最大为100，不填默认返回100条  
  
> 返回结果
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
         {
            "instType":"SWAP",
            "instId":"BTC-USDT-SWAP",
            "fundingRate":"0.018",
            "realizedRate":"0.017",
            "fundingTime":"1597026383085"
        },
        {
            "instType":"SWAP",
            "instId":"BTC-USDT-SWAP",
            "fundingRate":"0.018",
            "realizedRate":"0.017",
            "fundingTime":"1597026383085"
        }
      ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
instType | String | 产品类型  
`SWAP`：永续合约  
instId | String | 产品ID，如 `BTC-USD-SWAP`  
fundingRate | String | 资金费率  
realizedRate | String | 实际资金费率  
fundingTime | String | 资金费时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
  
### 获取限价

查询单个交易产品的最高买价和最低卖价

#### 限速： 20次/2s

#### HTTP请求

`GET /api/v5/public/price-limit`

> 请求示例
    
    
    GET /api/v5/public/price-limit?instId=BTC-USDT-SWAP
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instId | String | 是 | 产品ID，如 `BTC-USDT-SWAP`  
仅适用于`交割/永续/期权`  
  
> 返回结果
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
        {
            "instType":"SWAP",
            "instId":"BTC-USDT-SWAP",
            "buyLmt":"200",
            "sellLmt":"300",
            "ts":"1597026383085"
        }
      ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
instType | String | 产品类型  
`SWAP`：永续合约  
`FUTURES`：交割合约  
`OPTION`：期权  
instId | String | 产品ID ，如 `BTC-USDT-SWAP`  
buyLmt | String | 最高买价  
sellLmt | String | 最低卖价  
ts | String | 限价数据更新时间 ，Unix时间戳的毫秒数格式，如 `1597026383085`  
  
### 获取期权定价

查询期权详细信息

#### 限速： 20次/2s

#### 限速规则：IP +uly

#### HTTP请求

`GET /api/v5/public/opt-summary`

> 请求示例
    
    
    GET /api/v5/public/opt-summary?uly=BTC-USD
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
uly | String | 是 | 标的指数，仅适用于期权  
expTime | String | 否 | 合约到期日，格式为"YYMMDD"，如 "200527"  
  
> 返回结果
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
          {
                "askVol": "3.7207056835937498",
                "bidVol": "0",
                "delta": "0.8310206676289528",
                "deltaBS": "0.9857332101544538",
                "fwdPx": "39016.8143629068452065",
                "gamma": "-1.1965483553276135",
                "gammaBS": "0.000011933182397798109",
                "instId": "BTC-USD-220309-33000-C",
                "instType": "OPTION",
                "lever": "0",
                "markVol": "1.5551965233045728",
                "realVol": "0",
                "theta": "-0.0014131955002093717",
                "thetaBS": "-66.03526900575946",
                "ts": "1646733631242",
                "uly": "BTC-USD",
                "vega": "0.000018173851073258973",
                "vegaBS": "0.7089307622132419"
            },
            {
                "askVol": "1.7968814062499998",
                "bidVol": "0",
                "delta": "-0.014668822072611904",
                "deltaBS": "-0.01426678984554619",
                "fwdPx": "39016.8143629068452065",
                "gamma": "0.49483062407551576",
                "gammaBS": "0.000011933182397798109",
                "instId": "BTC-USD-220309-33000-P",
                "instType": "OPTION",
                "lever": "0",
                "markVol": "1.5551965233045728",
                "realVol": "0",
                "theta": "-0.0014131955002093717",
                "thetaBS": "-54.93377294845015",
                "ts": "1646733631242",
                "uly": "BTC-USD",
                "vega": "0.000018173851073258973",
                "vegaBS": "0.7089307622132419"
            }
      ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
instType | String | 产品类型  
`OPTION`：期权  
instId | String | 产品ID，如 `BTC-USD-200103-5500-C`  
uly | String | 标的指数  
delta | String | 期权价格对`uly`价格的敏感度  
gamma | String | delta对`uly`价格的敏感度  
vega | String | 权价格对隐含波动率的敏感度  
theta | String | 期权价格对剩余期限的敏感度  
deltaBS | String | BS模式下期权价格对`uly`价格的敏感度  
gammaBS | String | BS模式下delta对`uly`价格的敏感度  
vegaBS | String | BS模式下期权价格对隐含波动率的敏感度  
thetaBS | String | BS模式下期权价格对剩余期限的敏感度  
lever | String | 杠杆倍数  
markVol | String | 标记波动率  
bidVol | String | bid波动率  
askVol | String | ask波动率  
realVol | String | 已实现波动率（目前该字段暂未启用）  
fwdPx | String | 远期价格  
ts | String | 数据更新时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
  
### 获取预估交割/行权价格

获取交割合约和期权预估交割/行权价。交割/行权预估价只有交割/行权前一小时才有返回值

#### 限速： 10次/2s

#### 限速规则：IP +instrumentID

#### HTTP请求

`GET /api/v5/public/estimated-price`

> 请求示例
    
    
    GET /api/v5/public/estimated-price?instId=BTC-USDT-191227
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instId | String | 是 | 产品ID， 如 `BTC-USD-200214`  
仅适用于`交割/期权`  
  
> 返回结果
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
        {
            "instType":"FUTURES",
            "instId":"BTC-USDT-201227",
            "settlePx":"200",
            "ts":"1597026383085"
        }
      ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
instType | String | 产品类型  
`FUTURES`：交割合约  
`OPTION`：期权  
instId | String | 产品ID， 如 `BTC-USD-180216`  
settlePx | String | 预估交割、行权价格  
ts | String | 数据返回时间 ，Unix时间戳的毫秒数格式，如 `1597026383085`  
  
### 获取免息额度和币种折算率等级

获取免息额度和币种折算率等级

#### 限速： 2 次/2s

#### 限速规则：IP

#### HTTP 请求

`GET /api/v5/public/discount-rate-interest-free-quota`

> 请求示例
    
    
    GET /api/v5/public/discount-rate-interest-free-quota?ccy=BTC
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
ccy | String | 否 | 币种  
discountLv | String | 否 | 折算率等级  
`1`:第一档  
`2`:第二档  
`3`:第三档  
`4`:第四档  
`5`:第五档  
  
> 返回结果
    
    
    {
      "code": "0",
      "msg": "",
      "data": [
        {
                "amt": "1",
                "ccy": "LTC",
                "discountInfo": [
                    {
                        "discountRate": "0.95",
                        "maxAmt": "2000000",
                        "minAmt": "0"
                    },
                    {
                        "discountRate": "0.85",
                        "maxAmt": "4000000",
                        "minAmt": "2000000"
                    },
                    {
                        "discountRate": "0.5",
                        "maxAmt": "8000000",
                        "minAmt": "4000000"
                    },
                    {
                        "discountRate": "0",
                        "maxAmt": "",
                        "minAmt": "8000000"
                    }
                ],
                "discountLv": "2"
            }
      ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
ccy | String | 币种  
amt | String | 免息金额  
discountLv | String | 折算率等级  
[折算率等级说明](/support/hc/zh-
cn/articles/360054690531-%E5%9B%9B-%E8%B7%A8%E5%B8%81%E7%A7%8D%E4%BF%9D%E8%AF%81%E9%87%91%E6%A8%A1%E5%BC%8F-%E5%85%A8%E4%BB%93%E4%BA%A4%E6%98%93%E4%BB%8B%E7%BB%8D)  
discountInfo | Array | 币种折算率详情  
> discountRate | String | 折算率  
> maxAmt | String | 梯度区间上限（美元），“” 表示正无穷  
> minAmt | String | 梯度区间下限（美元），最小值是0  
  
### 获取系统时间

获取系统时间

#### 限速： 10次/2s

#### 限速规则：IP

#### HTTP请求

`GET /api/v5/public/time`

> 请求示例
    
    
    GET /api/v5/public/time
    

> 返回结果
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
        {
            "ts":"1597026383085"
        }
      ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
ts | String | 系统时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
  
### 获取平台公共爆仓单信息

最近1天的爆仓单信息

#### 限速： 2次/2s

#### 限速规则：IP

#### HTTP请求

`GET /api/v5/public/liquidation-orders`

> 请求示例
    
    
    GET /api/v5/public/liquidation-orders?instType=MARGIN
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instType | String | 是 | 产品类型  
`MARGIN`：币币杠杆  
`SWAP`：永续合约  
`FUTURES`：交割合约  
`OPTION`：期权  
mgnMode | String | 否 | 保证金模式  
`cross`：全仓  
`isolated`：逐仓  
instId | String | 否 | 产品ID，仅适用于`币币杠杆`  
ccy | String | 否 | 币种 ，仅适用于`币币杠杆`（全仓）  
uly | String | 可选 | 标的指数  
`交割/永续/期权`合约情况下，该参数必填  
alias | String | 可选 | `this_week`：本周  
`next_week`：次周  
`quarter`：季度  
`next_quarter`：次季度  
`交割`合约情况下，该参数必填  
state | String | 否 | 状态  
`unfilled`：未成交  
`filled`：已成交  
默认为`unfilled`  
`交割/永续`合约情况下，该参数必填  
before | String | 否 | 请求此时间戳之后（更新的数据）的分页内容，传的值为对应接口的`ts`  
after | String | 否 | 请求此时间戳之前（更旧的数据）的分页内容，传的值为对应接口的`ts`  
limit | String | 否 | 分页返回的结果集数量，最大为100，不填默认返回100条  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "details": [
                    {
                        "bkLoss": "0",
                        "bkPx": "",
                        "ccy": "USDT",
                        "posSide": "",
                        "side": "",
                        "sz": "989.9123170781309932",
                        "ts": "1629962347000"
                    },
                    {
                        "bkLoss": "0",
                        "bkPx": "",
                        "ccy": "USDT",
                        "posSide": "",
                        "side": "",
                        "sz": "10.1066764750370217",
                        "ts": "1629961447000"
                    }
                ],
                "instId": "BTC-USDT",
                "instType": "MARGIN",
                "totalLoss": "0",
                "uly": ""
            }
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
instType | String | 产品类型  
totalLoss | String | 当前`underlying`下，当期内的总穿仓亏损  
以`USDT`为单位，每天16:00（UTC+8）清零  
instId | String | 产品ID，如 `BTC-USD-SWAP`  
uly | String | 标的指数，仅适用于`交割/永续/期权`  
details | Array | 详细内容  
>side | String | 订单方向  
`buy`：买  
`sell`：卖  
>posSide | String | 持仓方向  
`long`：多  
`short`：空  
`side`和`posSide`组合方式，sell/long：强平多 ; buy/short:强平空  
>bkPx | String | 破产价格，与系统爆仓账号委托成交的价格。  
>sz | String | 强平数量  
>bkLoss | String | 穿仓亏损数量  
>ccy | String | 强平币种，仅适用于`币币杠杆`  
>ts | String | 强平发生的时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
  
### 获取标记价格

为了防止个别用户恶意操控市场导致合约价格波动剧烈，我们根据现货指数和合理基差设定标记价格。

#### 限速： 10次/2s

#### 限速规则：IP +instrumentID

#### HTTP请求

`GET /api/v5/public/mark-price`

> 请求示例
    
    
    GET /api/v5/public/mark-price?instType=SWAP
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instType | String | 是 | 产品类型  
`MARGIN`：币币杠杆  
`SWAP`：永续合约  
`FUTURES`：交割合约  
`OPTION`：期权  
uly | String | 否 | 标的指数  
instId | String | 否 | 产品ID，如 `BTC-USD-SWAP`  
  
> 返回结果
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
        {
            "instType":"SWAP",
            "instId":"BTC-USDT-SWAP",
            "markPx":"200",
            "ts":"1597026383085"
        }
      ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
instType | String | 产品类型  
`MARGIN`：币币杠杆  
`SWAP`：永续合约  
`FUTURES`：交割合约  
`OPTION`：期权  
instId | String | 产品ID，如 `BTC-USD-200214`  
markPx | String | 标记价格  
ts | String | 接口数据返回时间，Unix时间戳的毫秒数格式，如`1597026383085`  
  
### 获取衍生品仓位档位

全部仓位档位对应信息，当前最高可开杠杆倍数由您的借币持仓和保证金率决定。

#### 限速： 10次/2s

#### 限速规则：IP

#### HTTP请求

`GET /api/v5/public/position-tiers`

> 请求示例
    
    
    GET /api/v5/public/position-tiers
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instType | String | 是 | 产品类型  
`MARGIN`：币币杠杆  
`SWAP`：永续合约  
`FUTURES`：交割合约  
`OPTION`：期权  
tdMode | String | 是 | 保证金模式  
`isolated`：逐仓 ；`cross`：全仓  
uly | String | 可选 | 标的指数， 当产品类型是 `永续`、`交割`、`期权` 之一时必填，当产品类型是 `MARGIN` 时忽略  
instId | String | 可选 | 产品ID， 仅适用`币币杠杆`，且必填写  
tier | String | 否 | 查指定档位  
  
> 返回结果
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
        {
                "baseMaxLoan": "50",
                "imr": "0.1",
                "instId": "BTC-USDT",
                "maxLever": "10",
                "maxSz": "50",
                "minSz": "0",
                "mmr": "0.03",
                "optMgnFactor": "0",
                "quoteMaxLoan": "500000",
                "tier": "1",
                "uly": ""
            }
      ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
uly | String | 标的指数  
instId | String | 币对  
tier | String | 仓位档位  
minSz | String | 该档位最少持仓数量 期权/永续/交割 最小持仓量 默认0  
maxSz | String | 该档位最多持仓数量 期权/永续/交割  
mmr | String | 维持保证金率  
imr | String | 最低初始保证金率  
maxLever | String | 最高可用杠杆倍数  
optMgnFactor | String | 期权保证金系数 （仅适用于期权）  
quoteMaxLoan | String | 计价货币 最大借币量（仅适用于杠杆），例如 BTC-USDT 里的 USDT最大借币量  
baseMaxLoan | String | 交易货币 最大借币量（仅适用于杠杆），例如 BTC-USDT 里的 BTC最大借币量  
  
### 获取市场借币杠杆利率和借币限额

#### 限速： 2次/2s

#### 限速规则：IP

#### HTTP请求

`GET /api/v5/public/interest-rate-loan-quota`

> 请求示例
    
    
    GET /api/v5/public/interest-rate-loan-quota
    

> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "basic": [
                    {
                        "ccy": "USDT",
                        "quota": "500000",
                        "rate": "0.00043728"
                    },
                    {
                        "ccy": "BTC",
                        "quota": "10",
                        "rate": "0.00019992"
                    }
                ],
                "vip": [
                    {
                        "irDiscount": "0.7",
                        "loanQuotaCoef": "6",
                        "level": "VIP1"
                    },
                    {
                        "irDiscount": "0.65",
                        "loanQuotaCoef": "7",
                        "level": "VIP2"
                    }
                ],
                "regular": [
                    {
                        "irDiscount": "1",
                        "loanQuotaCoef": "1",
                        "level": "Lv1"
                    },
                    {
                        "irDiscount": "0.95",
                        "loanQuotaCoef": "2",
                        "level": "Lv2"
                    }
                ]
            }
        ],
        "msg": ""
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
basic | Array | 基础利率和借币限额  
> ccy | String | 币种  
> rate | String | 基础杠杆日利率  
> quota | String | 基础借币限额  
vip | Array | 专业用户  
> level | String | 账户交易手续费等级，如 `VIP1`  
> loanQuotaCoef | String | 借币限额系数  
> irDiscount | String | 利率的折扣率  
regular | Array | 普通用户  
> level | String | 账户交易手续费等级，如 `Lv1`  
> loanQuotaCoef | String | 借币限额系数  
> irDiscount | String | 利率的折扣率  
  
### 获取尊享借币杠杆利率和借币限额

#### 限速：2次/2s

#### 限速规则：IP

#### HTTP请求

`GET /api/v5/public/vip-interest-rate-loan-quota`

> 请求示例
    
    
    GET /api/v5/public/vip-interest-rate-loan-quota
    
    

> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "ccy": "ENJ",
                "levelList": [
                    {
                        "level": "VIP5",
                        "loanQuota": "100000.00000000"
                    },
                    {
                        "level": "VIP6",
                        "loanQuota": "110000.00000000"
                    },
                    {
                        "level": "VIP7",
                        "loanQuota": "120000.00000000"
                    },
                    {
                        "level": "VIP8",
                        "loanQuota": "130000.00000000"
                    }
                ],
                "quota": "10000.0000",
                "rate": "0.00048000"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
ccy | String | 币种  
rate | String | 基础杠杆日利率  
quota | String | 基础借币限额  
levelList | Array | 不同VIP等级下的限额信息  
> level | String | 用户VIP等级，如 `VIP5`  
> loanQuota | String | 借币限额  
  
### 获取衍生品标的指数

#### 限速： 20次/2s

#### 限速规则：IP

#### HTTP请求

`GET /api/v5/public/underlying`

> 请求示例
    
    
    GET /api/v5/public/underlying?instType=FUTURES
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instType | String | 是 | 产品类型  
`SWAP`：永续合约  
`FUTURES`：交割合约  
`OPTION`：期权  
  
> 返回结果
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
            [
                "LTC-USDT",
                "BTC-USDT",
                "ETC-USDT"
            ]
        ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
uly | Array | 标的指数 如：BTC-USDT  
  
### 获取风险准备金余额

通过该接口获取系统风险准备金余额信息

#### 限速： 10次/2s

#### 限速规则：IP

#### HTTP请求

`GET /api/v5/public/insurance-fund`

> 请求示例
    
    
    GET /api/v5/public/insurance-fund?instType=SWAP&uly=BTC-USD
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instType | String | 是 | 产品类型  
`MARGIN`：币币杠杆  
`SWAP`：永续合约  
`FUTURES`：交割合约  
`OPTION`：期权  
type | String | 否 | 风险准备金类型  
`liquidation_balance_deposit`：强平注入 ；`bankruptcy_loss`：穿仓亏损
；`platform_revenue`：平台收入注入  
默认返回全部类型  
uly | String | 否 | 标的指数， 仅适用于`交割/永续/期权`，且必填写  
ccy | String | 否 | 币种， 仅适用`币币杠杆`，且必填写  
before | String | 否 | 请求此时间戳之后（更新的数据）的分页内容，传的值为对应接口的`ts`  
after | String | 否 | 请求此时间戳之前（更旧的数据）的分页内容，传的值为对应接口的`ts`  
limit | String | 否 | 分页返回的结果集数量，最大为100，不填默认返回100条  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "details": [
                    {
                        "amt": "0.2465",
                        "balance": "3228.0732",
                        "ccy": "BTC",
                        "ts": "1646726421082",
                        "type": "liquidation_balance_deposit"
                    }
                ],
                "total": "883110357.6581"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
total | String | 平台风险准备金总计，单位为USD  
> balance | String | 风险准备金总量  
> amt | String | 风险准备金更新数量  
> ccy | String | 风险准备金总量对应的币种  
> type | String | 风险准备金类型  
> ts | String | 风险准备金更新时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
  
## 交易大数据

`交易大数据`功能模块下的API接口不需要身份验证。

### 获取交易大数据支持币种

获取支持交易大数据的币种

#### 限速： 5次/2s

#### 限速规则：IP

#### HTTP请求

`GET /api/v5/rubik/stat/trading-data/support-coin`

> 请求示例
    
    
    GET /api/v5/rubik/stat/trading-data/support-coin
    

> 返回结果
    
    
    {
        "code": "0",
        "data": {
            "contract": [
                "ADA",
                "BTC",
            ],
            "option": [
                "BTC"
            ],
            "spot": [
                "ADA",
                "BTC",
            ]
        },
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
contract | Array | 合约交易大数据接口功能支持的币种  
option | Array | 期权交易大数据接口功能支持的币种  
spot | Array | 现货交易大数据接口功能支持的币种  
  
### 获取主动买入/卖出情况

获取taker主动买入和卖出的交易量

#### 限速： 5次/2s

#### 限速规则：IP

#### HTTP请求

`GET /api/v5/rubik/stat/taker-volume`

> 请求示例
    
    
    GET /api/v5/rubik/stat/taker-volume?ccy=BTC&instType=SPOT
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
ccy | String | 是 | 币种  
instType | String | 是 | 产品类型，币币："SPOT" , 衍生品："CONTRACTS"  
begin | String | 否 | 开始时间，例如：`1597026383085`  
end | String | 否 | 结束时间，例如：`1597026383011`  
period | String | 否 | 时间粒度，默认值`5m`。支持[5m/1H/1D]  
`5m`粒度最多只能查询两天之内的数据  
`1H`粒度最多只能查询30天之内的数据  
`1D`粒度最多只能查询180天之内的数据  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            [
                "1630425600000",
                "7596.2651",
                "7149.4855"
            ],
            [
                "1630339200000",
                "5312.7876",
                "7002.7541"
            ]
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
ts | String | 数据产生时间  
sellVol | String | 卖出量  
buyVol | String | 买入量  
返回值数组顺序分别为是：[ts,sellVol,buyVol]

### 获取杠杆多空比

获取借入计价货币与借入交易货币的累计数额比值。

#### 限速： 5次/2s

#### 限速规则：IP

#### HTTP请求

`GET /api/v5/rubik/stat/margin/loan-ratio`

> 请求示例
    
    
    GET /api/v5/rubik/stat/margin/loan-ratio?ccy=BTC
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
ccy | String | 是 | 币种  
begin | String | 否 | 开始时间，例如：`1597026383085`  
end | String | 否 | 结束时间，例如：`1597026383011`  
period | String | 否 | 时间粒度，默认值`5m`。支持[5m/1H/1D]  
`5m`粒度最多只能查询两天之内的数据  
`1H`粒度最多只能查询30天之内的数据  
`1D`粒度最多只能查询180天之内的数据  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            [
                "1630492800000",
                "0.4614"
            ],
            [
                "1630492500000",
                "0.5767"
            ]
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
ts | String | 数据产生时间  
ratio | String | 多空比值  
返回值数组顺序分别为是：[ts,ratio]

### 获取合约多空持仓人数比

获取交割永续净多头持仓用户数与净空头持仓用户数的比值。

#### 限速： 5次/2s

#### 限速规则：IP

#### HTTP请求

`GET /api/v5/rubik/stat/contracts/long-short-account-ratio`

> 请求示例
    
    
    GET /api/v5/rubik/stat/contracts/long-short-account-ratio?ccy=BTC
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
ccy | String | 是 | 币种  
begin | String | 否 | 开始时间，例如：`1597026383085`  
end | String | 否 | 结束时间，例如：`1597026383011`  
period | String | 否 | 时间粒度，默认值`5m`。支持[5m/1H/1D]  
`5m`粒度最多只能查询两天之内的数据  
`1H`粒度最多只能查询30天之内的数据  
`1D`粒度最多只能查询180天之内的数据  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            [
                "1630502100000",
                "1.25"
            ]
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
ts | String | 数据产生时间  
ratio | String | 多空人数比  
返回值数组顺序分别为是：[ts,ratio]

### 获取合约持仓量及交易量

获取交割永续的持仓量和交易量。

#### 限速： 5次/2s

#### 限速规则：IP

#### HTTP请求

`GET /api/v5/rubik/stat/contracts/open-interest-volume`

> 请求示例
    
    
    GET /api/v5/rubik/stat/contracts/open-interest-volume?ccy=BTC
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
ccy | String | 是 | 币种  
begin | String | 否 | 开始时间，例如：`1597026383085`  
end | String | 否 | 结束时间，例如：`1597026383011`  
period | String | 否 | 时间粒度，默认值`5m`。支持[5m/1H/1D]  
`5m`粒度最多只能查询两天之内的数据  
`1H`粒度最多只能查询30天之内的数据  
`1D`粒度最多只能查询180天之内的数据  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            [
                "1630502400000",
                "1713028741.6898",
                "39800873.554"
            ]
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
ts | String | 数据产生时间  
oi | String | 持仓总量（USD）  
vol | String | 交易总量（USD）  
返回值数组顺序分别为是：[ts,oi,vol]

### 获取期权持仓量及交易量

获取期权的持仓量和交易量。

#### 限速： 5次/2s

#### 限速规则：IP

#### HTTP请求

`GET /api/v5/rubik/stat/option/open-interest-volume`

> 请求示例
    
    
    GET /api/v5/rubik/stat/option/open-interest-volume?ccy=BTC
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
ccy | String | 是 | 币种  
period | String | 否 | 时间粒度，默认值`8H`。支持[`8H/1D`]  
每个粒度最多只能查询72条数据  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            [
                "1630368000000",
                "3458.1000",
                "78.8000"
            ]
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
ts | String | 数据产生时间  
oi | String | 持仓总量（USD）  
vol | String | 交易总量（USD）  
返回值数组顺序分别为是：[ts,oi,vol]

### 看涨/看跌期权合约 持仓总量比/交易总量比

获取看涨期权和看跌期权的持仓量比值，以及交易量比值。

#### 限速： 5次/2s

#### 限速规则：IP

#### HTTP请求

`GET /api/v5/rubik/stat/option/open-interest-volume-ratio`

> 请求示例
    
    
    GET /api/v5/rubik/stat/option/open-interest-volume-ratio?ccy=BTC
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
ccy | String | 是 | 币种  
period | String | 否 | 时间粒度，默认值`8H`。支持[`8H/1D`]  
每个粒度最多只能查询72条数据  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            [
                "1630512000000",
                "2.7261",
                "2.3447"
            ],
            [
                "1630425600000",
                "2.8101",
                "2.3438"
            ]
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
ts | String | 数据产生时间  
oiRatio | String | 看涨/看跌 持仓总量比  
volRatio | String | 看涨/看跌 交易总量比  
返回值数组顺序分别为是：[ts,oiRatio,volRatio]

### 看涨看跌持仓总量及交易总量（按到期日分）

获取每个到期日上看涨期权和看跌期权的持仓量和交易量。

#### 限速： 5次/2s

#### 限速规则：IP

#### HTTP请求

`GET /api/v5/rubik/stat/option/open-interest-volume-expiry`

> 请求示例
    
    
    GET /api/v5/rubik/stat/option/open-interest-volume-expiry?ccy=BTC
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
ccy | String | 是 | 币种  
period | String | 否 | 时间粒度，默认值`8H`。支持[`8H/1D`]  
每个粒度最多只能查询72条数据  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            [
                "1630540800000",
                "20210902",
                "6.4",
                "18.4",
                "0.7",
                "0.4"
            ],
            [
                "1630540800000",
                "20210903",
                "47",
                "36.6",
                "1",
                "10.7"
            ]
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
ts | String | 数据产生时间  
expTime | String | 到期日（格式: YYYYMMdd，例如："20210623"）  
callOI | String | 看涨持仓总量（以`币`为单位）  
putOI | String | 看跌持仓总量（以`币`为单位）  
callVolume | String | 看涨交易总量（以`币`为单位）  
putVolume | String | 看跌交易总量（以`币`为单位）  
返回值数组顺序分别为是：[ts,expTime,callOI,putOI,callVolume,putVolume]

### 看涨看跌持仓总量及交易总量（按执行价格分）

获取看涨期权和看跌期权的taker主动买入和卖出的交易量。

#### 限速： 5次/2s

#### 限速规则：IP

#### HTTP请求

`GET /api/v5/rubik/stat/option/open-interest-volume-strike`

> 请求示例
    
    
    GET /api/v5/rubik/stat/option/open-interest-volume-strike?ccy=BTC&expTime=20210901
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
ccy | String | 是 | 币种  
expTime | String | 是 | 到期日（格式: YYYYMMdd，例如："20210623"）  
period | String | 否 | 时间粒度，默认值`8H`。支持[`8H/1D`]  
每个粒度最多只能查询72条数据  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            [
                "1630540800000",
                "10000",
                "0",
                "0.5",
                "0",
                "0"
            ],
            [
                "1630540800000",
                "14000",
                "0",
                "5.2",
                "0",
                "0"
            ]
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
ts | String | 数据产生时间  
strike | String | 执行价格  
callOI | String | 看涨持仓总量（以`币`为单位）  
putOI | String | 看跌持仓总量（以`币`为单位）  
callVolume | String | 看涨交易总量（以`币`为单位）  
putVolume | String | 看跌交易总量（以`币`为单位）  
返回值数组顺序分别为是：[ts,strike,callOI,putOI,callVolume,putVolume]

### 看跌/看涨期权合约 主动买入/卖出量

该指标展示某一时刻，单位时间内看跌/看涨期权的主动（taker）买入/卖出量所占总体的比例，即资金流入量和流出量的比例

#### 限速： 5次/2s

#### 限速规则：IP

#### HTTP请求

`GET /api/v5/rubik/stat/option/taker-block-volume`

> 请求示例
    
    
    GET /api/v5/rubik/stat/option/taker-block-volume?ccy=BTC
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
ccy | String | 是 | 币种  
period | String | 否 | 时间粒度，默认值`8H`。支持[`8H/1D`]  
每个粒度最多只能查询72条数据  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            "1630512000000",
            "8.55",
            "67.3",
            "16.05",
            "16.3",
            "126.4",
            "40.7"
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
ts | String | 数据产生时间  
callBuyVol | String | 看涨买入量 以结算货币为单位  
callSellVol | String | 看涨卖出量 以结算货币为单位  
putBuyVol | String | 看跌买入量 以结算货币为单位  
putSellVol | String | 看跌卖出量 以结算货币为单位  
callBlockVol | String | 看涨大单  
putBlockVol | String | 看跌大单  
返回值数组顺序分别为是：[ts,callBuyVol,callSellVol,putBuyVol,putSellVol,callBlockVol,putBlockVol]

## Status

获取系统升级事件的状态。

#### 限速：1次/5s

#### HTTP请求

`GET /api/v5/system/status`

> 请求示例
    
    
    GET /api/v5/system/status
    
    GET /api/v5/system/status?state=canceled
    
    

#### 请求参数

#### 请求示例

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
state | String | No | 系统的状态，`scheduled`:等待中 ; `ongoing`:进行中 ; `completed`:已完成
`canceled`: 已取消  
不填写此参数，默认返回 等待中和进行中 的数据  
  
> 返回结果
    
    
    {
        "code": "0",
        "msg": "",
        "data": [{
            "title": "Spot System Upgrade",
            "state": "scheduled",
            "begin": "1620723600000",
            "end": "1620724200000",
            "href": "",
            "serviceType": "1",
            "system": "classic",
            "scheDesc": ""    
        }]
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
title | String | 系统维护说明的标题  
state | String | 系统维护的状态  
begin | String | 系统维护的开始时间,Unix时间戳的毫秒数格式 如：`1617788463867`  
end | String | 系统维护的结束时间,Unix时间戳的毫秒数格式 如：`1617788463867`  
href | String | 系统维护详情的超级链接,若无返回值，默认值为空，如： “”  
serviceType | String | 服务类型， `0`：WebSocket ; `1`：币币 ; `2`：交割 ; `3`：永续 ; `4`：期权
`5`：交易服务  
system | String | 系统，`classic`：经典账户， `unified`：交易账户  
scheDesc | String | 改期进度说明，如： `由 2021-01-26T16:30:00.000Z 改期到
2021-01-28T16:30:00.000Z`  
  
# WebSocket API

## 概述

WebSocket是HTML5一种新的协议（Protocol）。它实现了用户端与服务器全双工通信，
使得数据可以快速地双向传播。通过一次简单的握手就可以建立用户端和服务器连接， 服务器根据业务规则可以主动推送信息给用户端。其优点如下：

  * 用户端和服务器进行数据传输时，请求头信息比较小，大概2个字节。
  * 用户端和服务器皆可以主动地发送数据给对方。
  * 不需要多次创建TCP请求和销毁，节约宽带和服务器的资源。

强烈建议开发者使用WebSocket API获取市场行情和买卖深度等信息。

## 连接

**连接说明** ：

**连接限制** ：1次/秒

当订阅公有频道时，使用公有服务的地址；当订阅私有频道时，使用私有服务的地址

**订阅限制** ：240次/小时

如果出现网络问题，系统会自动断开连接

如果连接成功后30s未订阅或订阅后30s内服务器未向用户推送数据，系统会自动断开连接

为了保持连接有效且稳定，建议您进行以下操作：

1\. 每次接收到消息后，用户设置一个定时器，定时N秒，N 小于30。

2\. 如果定时器被触发（N 秒内没有收到新消息），发送字符串 'ping'。

3\. 期待一个文字字符串'pong'作为回应。如果在 N秒内未收到，请发出错误或重新连接。

## 登录

限速: 1次/1s `适用于单账户登录`  
限速: 1次/15s `适用于多账户批量登录`

> 请求示例
    
    
    {
     "op": "login",
     "args":
      [
         {
           "apiKey"    : "985d5b66-57ce-40fb-b714-afc0b9787083",
           "passphrase" :"123456"    ,
           "timestamp" :"1538054050"    ,
           "sign" :"7L+zFQ+CEgGu5rzCj4+BdV2/uUHGqddA9pI6ztsRRPs=" 
          },
          {
           "apiKey"    : "86126n98-57ce-40fb-b714-afc0b9787083",
           "passphrase" :"123456"    ,
           "timestamp" :"1538054050"    ,
           "sign" :"7L+zFQ+CEgGu5rzCj4+BdV2/uUHGqddA9pI6ztsRRPs=" 
          }
       ]
    }
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
op | String | 是 | 操作，`login`  
args | Array | 是 | 账户列表，最多100组  
> apiKey | String | 是 | APIKey  
> passphrase | String | 是 | APIKey 的密码  
> timestamp | String | 是 | 时间戳，Unix Epoch时间，单位是秒  
> sign | String | 是 | 签名字符串  
  
> 全部成功返回示例
    
    
    {
    "event": "login",
    "code": "0",
    "msg": ""
    }
    

> 全部失败返回示例
    
    
    {
    "event": "error",
    "code": "60009",
    "msg": "Login failed."
    }
    

> 部分成功返回示例
    
    
    {
        "event": "login",
        "code": "60022",
        "msg": "Bulk login partially succeeded",
        "data":[
            {"apiKey": "86126n98-57ce-40fb-b714-afc0b9787083"}
        ]
    }
    

#### 返回参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
event | String | 是 | 操作，`login` `error`  
code | String | 否 | 错误码  
msg | String | 否 | 错误消息  
data | Object | 否 | 登陆失败后返回的数据  
> apiKey | String | 是 | 登陆失败后返回的APIKey  
  
多账户批量登录的用户只能订阅 WebSocket 频道，不能使用 WebSocket 交易

**sign** :签名字符串，签名算法如下：

先将`timestamp` 、 `method` 、`requestPath` 、 `body`进行字符串拼接，再使用HMAC
SHA256方法将拼接后的字符串和SecretKey加密，然后进行Base64编码

**SecretKey:** 用户申请APIKey时所生成的安全密钥，如：22582BD0CFF14C41EDBF1AB98506286D

**其中 timestamp 示例** :const timestamp = '' \+ Date.now() / 1000

**其中 sign 示例** :
sign=CryptoJS.enc.Base64.stringify(CryptoJS.HmacSHA256(timestamp +'GET'\+
'/users/self/verify', secret))

**method** 总是 'GET'。

**requestPath** 总是 '/users/self/verify'

请求在时间戳之后30秒会失效，如果您的服务器时间和API服务器时间有偏差，推荐使用 REST API查询API服务器的时间，然后设置时间戳

## 订阅

**订阅说明**

> 请求格式说明
    
    
    {
        "op": "subscribe",
        "args": ["<SubscriptionTopic> "]
    }
    

WebSocket 频道分成两类： `公共频道` 和 `私有频道`

`公共频道`无需登录，包括行情频道，K线频道，交易数据频道，资金费率频道，限价范围频道，深度数据频道，标记价格频道等。

`私有频道`需登录，包括用户账户频道，用户交易频道，用户持仓频道等。

用户可以选择订阅一个或者多个频道，多个频道总长度不能超过4096个字节。

> 请求示例
    
    
    {
        "op":"subscribe",
        "args":[
            {
                "channel":"tickers",
                "instId":"LTC-USD-200327"
            },
            {
                "channel":"candle1m",
                "instId":"LTC-USD-200327"
            }
        ]
    }
    
    

**请求参数**

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
op | String | 是 | 操作，`subscribe`  
args | Array | 是 | 请求订阅的频道列表  
> channel | String | 是 | 频道名  
> instType | String | 否 | 产品类型  
`SPOT`：币币  
`MARGIN`：币币杠杆  
`SWAP`：永续合约  
`FUTURES`：交割合约  
`OPTION`：期权  
`ANY`： 全部  
> uly | String | 否 | 标的指数  
> instId | String | 否 | 产品ID  
  
> 返回示例
    
    
    {
        "event": "subscribe",
        "arg": {
            "channel": "tickers",
            "instId": "LTC-USD-200327"
        }
    }
    

**返回参数**

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
event | String | 是 | 事件，`subscribe` `error`  
arg | Object | 否 | 订阅的频道  
> channel | String | 是 | 频道名  
> instType | String | 否 | 产品类型  
`SPOT`：币币  
`MARGIN`：币币杠杆  
`SWAP`：永续合约  
`FUTURES`：交割合约  
`OPTION` ： 期权  
`ANY`： 全部  
> uly | String | 否 | 标的指数  
> instId | String | 否 | 产品ID  
code | String | 否 | 错误码  
msg | String | 否 | 错误消息  
  
## 取消订阅

可以取消一个或者多个频道

> 请求格式说明
    
    
    {
        "op": "unsubscribe",
        "args": ["< SubscriptionTopic > "]
    }
    

> 请求示例
    
    
    {
     "op": "unsubscribe",
     "args":
      [
          {
           "channel"   : "tickers",
           "instId":"LTC-USD-200327"
          },
          {
           "channel"   : "candle1m",
           "instId":"LTC-USD-200327"
          }
       ]
    }
    

**请求参数**

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
op | String | 是 | 操作，`unsubscribe`  
args | Array | 是 | 取消订阅的频道列表  
> channel | String | 是 | 频道名  
> instType | String | 否 | 产品类型  
`SPOT`：币币  
`MARGIN`：币币杠杆  
`SWAP`：永续合约  
`FUTURES`：交割合约  
`OPTION`：期权  
`ANY`： 全部  
> uly | String | 否 | 标的指数  
> instId | String | 否 | 产品ID  
  
> 返回示例
    
    
    {
        "event": "unsubscribe",
        "arg": {
            "channel": "tickers",
            "instId": "LTC-USD-200327"
        }
    }
    

**返回参数**

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
event | String | 是 | 事件，`unsubscribe` `error`  
arg | Object | 否 | 取消订阅的频道  
> channel | String | 是 | 频道名  
> instType | String | 否 | 产品类型  
`SPOT`：币币  
`MARGIN`：币币杠杆  
`SWAP`：永续合约  
`FUTURES`：交割合约  
`OPTION`：期权  
`ANY`： 全部  
> uly | String | 否 | 标的指数  
> instId | String | 否 | 产品ID  
code | String | 否 | 错误码  
msg | String | 否 | 错误消息  
  
## Checksum机制

此机制可以帮助用户校验深度数据的准确性。

### 深度合并

用户订阅增量推送（如：`books`400档）深度频道成功后，首先获取初始全量深度数据，当获取到增量推送数据后，更新本地全量深度数据。

  1. 如果有相同价格，则比较数量；数量为0删除此深度，数量有变化则替换此数据。
  2. 如果没有相同价格，则按照价格优劣排序（bid为价格降序，ask为价格升序），将深度信息插入到全量数据中

### 计算校验和

先用深度合并后前25档bids和asks组成一个字符串（其中ask和bid中的价格和数量以冒号连接），再计算其crc32值（32位有符号整型）。

> 计算校验和
    
    
    1.bid和ask超过25档
    合并后全量深度数据（在此仅展示2档数据，实际应截取25档数据）：
    "bids": [
        [ 3366.1, 7, 0, 3 ],
        [ 3366  , 6, 3, 4 ]
    ]
    "asks": [
        [ 3366.8, 9, 10, 3 ],
        [ 3368  , 8,  3, 4 ]
    ]
    校验字符串：
    "3366.1:7:3366.8:9:3366:6:3368:8"
    
    2.bid或ask不足25档  
    合并后全量深度数据：
    "bids": [
        [ 3366.1, 7, 0, 3]
    ]
    "asks": [
        [ 3366.8, 9, 10, 3],
        [ 3368  , 8, 3, 4 ],
        [ 3372  , 8, 3, 4 ]
    ]
    校验字符串：
    "3366.1:7:3366.8:9:3368:8:3372:8"
    

  1. 当bid和ask深度数据超过25档时，截取各自25档数据，要校验的字符串按照bid、ask深度数据交替方式连接。  
如：`bid[价格:数量]`:`ask[价格:数量]`:`bid[价格:数量]`:`ask[价格:数量]`...  

  2. bid或ask深度数据不足25档时，直接忽略缺失的深度。  
如：`bid[价格:数量]`:`ask[价格:数量]`:`asks[价格:数量]`:`asks[价格:数量]`...  

## 交易

`WebSocket交易`需要身份验证。

### 下单

只有当您的账户有足够的资金才能下单。一旦下单，您的账户资金将在订单生命周期内被冻结。被冻结的资金以及数量取决于订单指定的类型和参数

#### 限速：60次/2s

#### 限速规则：衍生品：UserID +(instrumentType、underlying)

#### 限速规则：币币和币币杠杆：UserID +(instrumentType、instrumentID)

#### 同restAPI共享限速

> 请求示例
    
    
    {
        "id": "1512",
        "op": "order",
        "args": [{
            "side": "buy",
            "instId": "BTC-USDT",
            "tdMode": "isolated",
            "ordType": "market",
            "sz": "100"
        }]
    }
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
id | String | 是 | 消息的唯一标识  
用户提供，返回参数中会返回以便于找到相应的请求。  
字母（区分大小写）与数字的组合，可以是纯字母、纯数字且长度必须要在1-32位之间。  
op | String | 是 | 支持的业务操作，如 `order`  
args | Array | 是 | 请求参数  
> instId | String | 是 | 产品ID，如 `BTC-USD-190927-5000-C`  
> tdMode | String | 是 | 交易模式  
保证金模式 `isolated`：逐仓 `cross`： 全仓  
非保证金模式 `cash`：现金  
> ccy | String | 否 | 保证金币种，仅适用于单币种保证金账户下的全仓杠杆订单  
> clOrdId | String | 否 | 由用户设置的订单ID  
字母（区分大小写）与数字的组合，可以是纯字母、纯数字且长度要在1-32位之间。  
> tag | String | 否 | 订单标签  
字母（区分大小写）与数字的组合，可以是纯字母、纯数字且长度要在1-16位之间。  
> side | String | 是 | 订单方向，`buy` `sell`  
> posSide | String | 否 | 持仓方向  
在单向持仓模式下，默认 `net`  
在双向持仓模式下必填，且仅可选择 `long` 或 `short`，仅适用于`交割/永续`  
> ordType | String | 是 | 订单类型  
`market`：市价单  
`limit`：限价单  
`post_only`：只做maker单  
`fok`：全部成交或立即取消  
`ioc`：立即成交并取消剩余  
`optimal_limit_ioc`：市价委托立即成交并取消剩余（仅适用交割、永续）  
> sz | String | 是 | 当type为limit时，表示买入或卖出的数量  
当type为market时，现货交易买入时，表示买入的总金额，而  
当其他产品买入或卖出时，表示数量  
> px | String | 否 | 委托价，仅适用于`limit`、`post_only`、`fok`、`ioc`类型的订单  
> reduceOnly | Boolean | 否 | 是否只减仓，`true` 或 `false`，默认`false`  
仅适用于`币币杠杆`，以及买卖模式下的`交割/永续`  
仅适用于`单币种保证金模式`和`跨币种保证金模式`  
> tgtCcy | String | 否 | 市价单委托数量的类型  
`base_ccy`: 交易货币 ；`quote_ccy`：计价货币  
仅适用于`币币`订单  
  
> 成功返回示例
    
    
    {
        "id": "1512",
        "op": "order",
        "data": [{
            "clOrdId": "",
            "ordId": "12345689",
            "tag": "",
            "sCode": "0",
            "sMsg": ""
        }],
        "code": "0",
        "msg": ""
    }
    

> 失败返回示例
    
    
    {
        "id": "1512",
        "op": "order",
        "data": [{
            "clOrdId": "",
            "ordId": "",
            "tag": "",
            "sCode": "5XXXX",
            "sMsg": "not exist"
        }],
        "code": "1",
        "msg": ""
    }
    

> 格式错误返回示例
    
    
    {
        "id": "1512",
        "op": "order",
        "data": [],
        "code": "60013",
        "msg": "Invalid args"
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
id | String | 消息的唯一标识  
op | String | 业务操作  
code | String | 代码  
msg | String | 消息  
data | Array | 请求成功后返回的数据  
> ordId | String | 订单ID  
> clOrdId | String | 由用户设置的订单ID  
> tag | String | 订单标签  
> sCode | String | 订单状态码，0 代表成功  
> sMsg | String | 订单状态消息  
tdMode  
交易模式，下单时需要指定  
**交易账户：**  
\- 币币和期权买方：cash  
**单币种保证金账户：**  
\- 逐仓杠杆：isolated  
\- 全仓杠杆：cross  
\- 全仓币币：cash  
\- 全仓交割/永续/期权：cross  
\- 逐仓交割/永续/期权：isolated  
**跨币种保证金账户：**  
\- 逐仓杠杆：isolated  
\- 全仓币币：cross  
\- 全仓交割/永续/期权：cross  
\- 逐仓交割/永续/期权：isolated  
clOrdId  
clOrdId是用户自定义的唯一ID用来跟识别订单。如果在请求参数中传入了，那它一定会在返回参数内，并且可以用于查询订单，撤销订单，修改订单等接口。
clOrdId不能与当前所有的挂单的clOrdId重复  持仓方向，单向持仓模式下此参数非必填，如果填写仅可以选择net；在双向持仓模式下必填，且仅可选择
long 或 short。  
双向持仓模式下，side和posSide需要进行组合  
开多：买入开多（side 填写 buy； posSide 填写 long ）  
开空：卖出开空（side 填写 sell； posSide 填写 short ）  
平多：卖出平多（side 填写 sell；posSide 填写 long ）  
平空：买入平空（side 填写 buy； posSide 填写 short ）  ordType  
订单类型，创建新订单时必须指定，您指定的订单类型将影响需要哪些订单参数和撮合系统如何执行您的订单，以下是有效的ordType：  
普通委托：  
limit：限价单，要求指定sz 和 px  
market：市价单，币币和币币杠杆，是市价委托吃单；交割合约和永续合约，是自动以最高买/最低卖价格委托，遵循限价机制；期权合约不支持市价委托  
高级委托：  
post_only：限价委托，在下单那一刻只做maker，如果该笔订单的任何部分会吃掉当前挂单深度，则该订单将被全部撤销。  
fok：限价委托，全部成交或立即取消，如果无法全部成交该笔订单，则该订单将被全部撤销。  
ioc：限价委托，立即成交并取消剩余，立即按照委托价格撮合成交，并取消该订单剩余未完成数量，不会在深度列表上展示委托数量。  
optimal_limit_ioc:市价委托，立即成交并取消剩余，仅适用于交割合约和永续合约。  sz  
交易数量，表示要购买或者出售的数量。  
当币币/币币杠杆以限价买入和卖出时，指交易货币数量。  
当币币/币币杠杆以市价买入时，指计价货币的数量。  
当币币/币币杠杆以市价卖出时，指交易货币的数量。  
当交割、永续、期权买入和卖出时，指合约张数。  reduceOnly  
只减仓，下单时，此参数设置为 true 时，表示此笔订单具有减仓属性，只会减少持仓数量，不会增加新的持仓仓位  
仅适用于`单币种账户模式`和`跨币种账户模式`  
仅适用于`币币杠杆`，以及买卖模式下的`交割/永续`  tgtCcy  
市价单委托数量的类型：仅适用于币币市价下单交易。  
交易货币：base_ccy  
计价货币：quote_ccy  
您在使用交易货币买入或者计价货币卖出时，请知晓：  
1.如果您输入的数量大于当前可买或者可卖的数量，系统将按照您的最大可买或者可卖数量帮您完成交易，如果您希望按照指定数量成交，那您可以尝试使用限价单，等待市场价格波动到锁定的余额可以买入或卖出您指定的数量。  
2.如果您输入的数量不大于当前可买或者可卖的数量，那当市场价格波动过大时，锁定的余额可能没办法买入您输入的交易货币数量或卖出您输入的计价货币数量，为保证您的交易体验，我们基于【能买多少买多少】或者【能卖多少卖多少】的原则，更改下单的数量帮您完成交易。此外，我们将尽量多锁定一点余额来规避更改下单数量的情况。  
2.1 交易币买入例子：  
以市价下单 买入 10个LTC为例，用户可买为11个，此时 10 < 11，挂单成功。当市价为200USDT/LTC，用户被锁定余额为3000
USDT，200*10 < 3000，最终成交10个LTC；
若市场波动过大，市价为400USDT/LTC，400*10>3000，当用户被锁定的余额不够买入下单指定的交易货币数量时，使用用户被锁定的最大余额3000
USDT下单买入，最终成交 3000/400 = 7.5个 LTC。  
2.2 计价币卖出例子：  
以市价下单 卖出 1000USDT为例，用户可卖为1200USDT，1000 <
1200，挂单成功。市价为200USDT/LTC，用户被锁定的余额为6个LTC，最终成交5个LTC；
若市场波动过大，市价为100USDT/LTC，100*6 < 1000，当用户被锁定的余额不够卖出下单指定的计价货币数量时，使用用户被锁定的最大余额
6个LTC下单，最终成交 6 * 100 = 600 USDT。

### 批量下单

批量进行下单操作，每次可批量交易不同类型的产品，最多可下单20个

#### 限速：300次/2s

#### 限速规则：衍生品：UserID +(instrumentType、underlying)

#### 限速规则：币币和币币杠杆：UserID +(instrumentType、instrumentID)

#### 限速规则：批量请求中包含几个元素，限速计数就加几次，总的限制是`300次/2s`

#### 同restAPI共享限速

> 请求示例
    
    
    {
        "id": "1513",
        "op": "batch-orders",
        "args": [{
            "side": "buy",
            "instId": "BTC-USDT",
            "tdMode": "isolated",
            "ordType": "market",
            "sz": "100"
        }, {
            "side": "buy",
            "instId": "BTC-USD-200925",
            "tdMode": "isolated",
            "ordType": "limit",
            "sz": "1"
        }]
    } 
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
id | String | 是 | 消息的唯一标识  
用户提供，返回参数中会返回以便于找到相应的请求。  
字母（区分大小写）与数字的组合，可以是纯字母、纯数字且长度必须要在1-32位之间。  
op | String | 是 | 支持的业务操作，如 `batch-orders`  
args | Array | 是 | 请求参数  
> instId | String | 是 | 产品ID，如 `BTC-USDT`  
> tdMode | String | 否 | 交易模式  
保证金模式 `cross`：全仓 `isolated`：逐仓  
非保证金模式 `cash`：现金  
> ccy | String | 否 | 保证金币种，仅适用于单币种保证金账户下的全仓杠杆订单  
> clOrdId | String | 否 | 用户提供的订单ID  
字母（区分大小写）与数字的组合，可以是纯字母、纯数字且长度要在1-32位之间。  
> tag | String | 否 | 订单标签  
字母（区分大小写）与数字的组合，可以是纯字母、纯数字且长度要在1-16位之间。  
> side | String | 是 | 订单方向， `buy` `sell`  
> posSide | String | 否 | 持仓方向  
在单向持仓模式下，默认 `net`  
在双向持仓模式下必填，且仅可选择 `long` 或 `short`，仅适用于`交割/永续`  
> ordType | String | 是 | 订单类型  
`market`： 市价单  
`limit`：限价单  
`post_only`：只做maker单  
`fok`：全部成交或立即取消单  
`ioc`：立即成交并取消剩余单  
`optimal_limit_ioc`：市价委托立即成交并取消剩余（仅适用交割、永续）  
> sz | String | 是 | 买入或卖出的数量  
当type为limit时，表示买入或卖出的数量  
当type为market时，表示买入或卖出的总金额，而  
当其他产品买入或卖出时，表示数量  
> px | String | 否 | 委托价，仅适用于`limit`、`post_only`、`fok`、`ioc`类型的订单  
> reduceOnly | Boolean | 否 | 是否只减仓，`true` 或 `false`，默认`false`  
仅适用于`币币杠杆`，以及买卖模式下的`交割/永续`  
仅适用于`单币种保证金模式`和`跨币种保证金模式`  
> tgtCcy | String | 否 | 市价单委托数量的类型  
`base_ccy`: 交易货币 ；`quote_ccy`：计价货币  
仅适用于`币币`订单  
  
> 全部成功返回示例
    
    
    {
        "id": "1513",
        "op": "batch-orders",
        "data": [{
            "clOrdId": "",
            "ordId": "12345689",
            "tag": "",
            "sCode": "0",
            "sMsg": ""
        }, {
            "clOrdId": "",
            "ordId": "12344",
            "tag": "",
            "sCode": "0",
            "sMsg": ""
        }],
        "code": "0",
        "msg": ""
    }
    

> 部分成功返回示例
    
    
    {
        "id": "1513",
        "op": "batch-orders",
        "data": [{
            "clOrdId": "",
            "ordId": "12345689",
            "tag": "",
            "sCode": "0",
            "sMsg": ""
        }, {
            "clOrdId": "",
            "ordId": "",
            "tag": "",
            "sCode": "5XXXX",
            "sMsg": "Insufficient margin"
        }],
        "code": "2",
        "msg": ""
    }
    

> 全部失败返回示例
    
    
    {
        "id": "1513",
        "op": "batch-orders",
        "data": [{
            "clOrdId": "oktswap6",
            "ordId": "",
            "tag": "",
            "sCode": "5XXXX",
            "sMsg": "Insufficient margin"
        }, {
            "clOrdId": "oktswap7",
            "ordId": "",
            "tag": "",
            "sCode": "5XXXX",
            "sMsg": "Insufficient margin"
        }],
        "code": "1",
        "msg": ""
    }
    

> 格式错误返回示例
    
    
    {
        "id": "1513",
        "op": "batch-orders",
        "data": [],
        "code": "60013",
        "msg": "Invalid args"
    }
    

#### 返回参数

参数 | 类型 | 描述  
---|---|---  
id | String | 消息的唯一标识  
op | String | 业务操作  
code | String | 代码  
msg | String | 消息  
data | Array | 请求成功后返回的数据  
> ordId | String | 订单ID  
> clOrdId | String | 由用户设置的订单ID  
> tag | String | 订单标签  
> sCode | String | 订单状态码，0 代表成功  
> sMsg | String | 订单状态消息  
在组合保证金账户模式下，或者全部成功，或者全部失败。

### 撤单

撤销当前未完成订单

#### 限速：60次/2s

#### 限速规则：衍生品：UserID +(instrumentType、underlying)

#### 限速规则：币币和币币杠杆：UserID +(instrumentType、instrumentID)

#### 同restAPI共享限速

> 请求示例
    
    
    {
        "id": "1514",
        "op": "cancel-order",
        "args": [{
            "instId": "BTC-USDT",
            "ordId": "2510789768709120"
        }]
    }
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
id | String | 是 | 消息的唯一标识  
用户提供，返回参数中会返回以便于找到相应的请求。  
字母（区分大小写）与数字的组合，可以是纯字母、纯数字且长度必须要在1-32位之间。  
op | String | 是 | 支持的业务操作，如 `cancel-order`  
args | Array | 是 | 请求参数  
> instId | String | 是 | 产品ID  
> ordId | String | 可选 | 订单ID  
ordId和clOrdId必须传一个，若传两个，以 ordId 为主  
> clOrdId | String | 可选 | 用户提供的订单ID  
字母（区分大小写）与数字的组合，可以是纯字母、纯数字，且长度要在1-32位之间。  
  
> 成功返回示例
    
    
    {
        "id": "1514",
        "op": "cancel-order",
        "data": [{
            "clOrdId": "",
            "ordId": "2510789768709120",
            "sCode": "0",
            "sMsg": ""
        }],
        "code": "0",
        "msg": ""
    }
    

> 失败返回示例
    
    
    {
        "id": "1514",
        "op": "cancel-order",
        "data": [{
            "clOrdId": "",
            "ordId": "2510789768709120",
            "sCode": "5XXXX",
            "sMsg": "Order not exist"
        }],
        "code": "1",
        "msg": ""
    }
    

> 格式错误返回示例
    
    
    {
        "id": "1514",
        "op": "cancel-order",
        "data": [],
        "code": "60013",
        "msg": "Invalid args"
    }
    

#### 返回参数

参数 | 类型 | 描述  
---|---|---  
id | String | 消息的唯一标识  
op | String | 业务操作  
code | String | 代码  
msg | String | 消息  
data | Array | 请求成功后返回的数据  
> ordId | String | 订单ID  
> clOrdId | String | 由用户设置的订单ID  
> sCode | String | 订单状态码，0 代表成功  
> sMsg | String | 订单状态消息  
撤单返回sCode等于0不能严格认为该订单已经被撤销，只表示您的撤单请求被系统服务器所接受，撤单结果以订单频道推送的状态或者查询订单状态为准  

### 批量撤单

批量进行撤单操作，每次可批量撤销不同类型的产品，最多撤销20个

#### 限速：300次/2s

#### 限速规则：衍生品：UserID +(instrumentType、underlying)

#### 限速规则：币币和币币杠杆：UserID +(instrumentType、instrumentID)

#### 限速规则：批量请求中包含几个元素，限速计数就加几次，总的限制是`300次/2s`

#### 同restAPI共享限速

> 请求示例
    
    
    {
        "id": "1515",
        "op": "batch-cancel-orders",
        "args": [{
            "instId": "BTC-USDT",
            "ordId": "2517748157541376"
        }, {
            "instId": "LTC-USDT",
            "ordId": "2517748155771904"
        }]
    }
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
id | String | 是 | 消息的唯一标识  
用户提供，返回参数中会返回以便于找到相应的请求。  
字母（区分大小写）与数字的组合，可以是纯字母、纯数字且长度必须要在1-32位之间。  
op | String | 是 | 支持的业务操作，如 `batch-cancel-orders`  
args | Array | 是 | 请求参数  
> instId | String | 是 | 产品ID  
> ordId | String | 可选 | 订单ID  
ordId和clOrdId必须传一个，若传两个，以ordId 为主  
> clOrdId | String | 可选 | 用户提供的订单ID  
字母（区分大小写）与数字的组合，可以是纯字母、纯数字，且长度要在1-32位之间。  
  
> 全部成功返回示例
    
    
    {
        "id": "1515",
        "op": "batch-cancel-orders",
        "data": [{
            "clOrdId": "oktswap6",
            "ordId": "2517748157541376",
            "sCode": "0",
            "sMsg": ""
        }, {
            "clOrdId": "oktswap7",
            "ordId": "2517748155771904",
            "sCode": "0",
            "sMsg": ""
        }],
        "code": "0",
        "msg": ""
    }
    

> 部分成功的返回示例
    
    
    {
        "id": "1515",
        "op": "batch-cancel-orders",
        "data": [{
            "clOrdId": "oktswap6",
            "ordId": "2517748157541376",
            "sCode": "0",
            "sMsg": ""
        }, {
            "clOrdId": "oktswap7",
            "ordId": "2517748155771904",
            "sCode": "5XXXX",
            "sMsg": "order not exist"
        }],
        "code": "2",
        "msg": ""
    }
    

> 全部失败的返回示例
    
    
    {
        "id": "1515",
        "op": "batch-cancel-orders",
        "data": [{
            "clOrdId": "oktswap6",
            "ordId": "2517748157541376",
            "sCode": "5XXXX",
            "sMsg": "order not exist"
        }, {
            "clOrdId": "oktswap7",
            "ordId": "2517748155771904",
            "sCode": "5XXXX",
            "sMsg": "order not exist"
        }],
        "code": "1",
        "msg": ""
    }
    

> 格式错误示例
    
    
    {
        "id": "1515",
        "op": "batch-cancel-orders",
        "data": [],
        "code": "60013",
        "msg": "Invalid args"
    }
    

#### 返回参数

参数 | 类型 | 描述  
---|---|---  
id | String | 消息的唯一标识  
op | String | 业务操作  
code | String | 代码  
msg | String | 消息  
data | Array | 请求成功后返回的数据  
> ordId | String | 订单ID  
> clOrdId | String | 由用户设置的订单ID  
> sCode | String | 订单状态码，0 代表成功  
> sMsg | String | 订单状态消息  
  
### 改单

修改当前未成交的订单

#### 限速：60次/2s

#### 限速规则：衍生品：UserID +(instrumentType、underlying)

#### 限速规则：币币和币币杠杆：UserID +(instrumentType、instrumentID)

#### 同restAPI共享限速

> 请求示例
    
    
    {
        "id": "1512",
        "op": "amend-order",
        "args": [{
            "instId": "BTC-USDT",
            "ordId": "2510789768709120",
            "newSz": "2"
        }]
    }
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
id | String | 是 | 消息的唯一标识  
用户提供，返回参数中会返回以便于找到相应的请求。  
字母（区分大小写）与数字的组合，可以是纯字母、纯数字且长度必须要在1-32位之间。  
op | String | 是 | 支持的业务操作，如 `amend-order`  
args | Array | 是 | 请求参数  
> instId | String | 是 | 产品ID  
> cxlOnFail | Boolean | 否 | 当订单修改失败时，该订单是否需要自动撤销  
`false`：不自动撤单 `true`：自动撤单 ，默认为 `false`  
> ordId | String | 可选 | 订单ID  
ordId和clOrdId必须传一个，若传两个，以 ordId 为主  
> clOrdId | String | 可选 | 用户提供的订单ID  
> reqId | String | 否 | 用户提供的reqId  
如果提供，那在返回参数中返回reqId，方便找到相应的修改请求。  
字母（区分大小写）与数字的组合，可以是纯字母、纯数字且长度要在1-32位之间。  
> newSz | String | 可选 | 请求修改的新数量，`newSz`和`newPx`不可同时为空。对于部分成交订单，该数量应包含已成交数量。  
> newPx | String | 可选 | 请求修改的新价格  
  
> 成功返回示例
    
    
    {
        "id": "1512",
        "op": "amend-order",
        "data": [{
            "clOrdId": "",
            "ordId": "2510789768709120",
            "reqId": "b12344",
            "sCode": "0",
            "sMsg": ""
        }],
        "code": "0",
        "msg": ""
    } 
    

> 失败返回示例
    
    
    {
        "id": "1512",
        "op": "amend-order",
        "data": [{
            "clOrdId": "",
            "ordId": "2510789768709120",
            "reqId": "b12344",
            "sCode": "5XXXX",
            "sMsg": "order not exist"
        }],
        "code": "1",
        "msg": ""
    }
    

> 格式错误返回示例
    
    
    {
        "id": "1512",
        "op": "amend-order",
        "data": [],
        "code": "60013",
        "msg": "Invalid args"
    }
    

#### 返回参数

参数 | 类型 | 描述  
---|---|---  
id | String | 消息的唯一标识  
op | String | 业务操作  
code | String | 代码  
msg | String | 消息  
data | Array | 请求成功后返回的数据  
> ordId | String | 订单ID  
> clOrdId | String | 用户提供的订单ID  
> reqId | String | 用户提供的reqId  
如果用户在请求中提供reqId，则返回相应reqId  
> sCode | String | 订单状态码，0 代表成功  
> sMsg | String | 订单状态消息  
  
newSz : 当修改已经部分成交的订单时，新的委托数量必须大于等于已成交数量

修改订单返回sCode等于0不能严格认为该订单已经被修改，只表示您的修改订单请求被系统服务器所接受，改单结果以订单频道推送的状态或者查询订单状态为准  

### 批量改单

批量进行改单操作，每次可批量修改不同类型的产品，最多改20个

#### 限速：300次/2s

#### 限速规则：衍生品：UserID +(instrumentType、underlying)

#### 限速规则：币币和币币杠杆：UserID +(instrumentType、instrumentID)

#### 限速规则：批量请求中包含几个元素，限速计数就加几次，总的限制是`300次/2s`

#### 同restAPI共享限速

> 请求示例
    
    
    {
        "id": "1513",
        "op": "batch-amend-orders",
        "args": [{
            "instId": "BTC-USDT",
            "ordId": "12345689",
            "newSz": "2"
        }, {
            "instId": "BTC-USDT",
            "ordId": "12344",
            "newSz": "2"
        }]
    }
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
id | String | 是 | 消息的唯一标识  
用户提供，返回参数中会返回以便于找到相应的请求。  
字母（区分大小写）与数字的组合，可以是纯字母、纯数字且长度必须要在1-32位之间。  
op | String | 是 | 支持的业务操作，如 `batch-amend-orders`  
args | Array | 是 | 请求参数  
> instId | String | 是 | 产品ID  
> cxlOnFail | Boolean | 否 | 当订单修改失败时，该订单是否需要自动撤销  
`false`：不自动撤单 `true`：自动撤单 ，默认为false  
> ordId | String | 可选 | 订单ID  
ordId 和 clOrdId 必须传一个，若传两个，以order id 为主  
> clOrdId | String | 可选 | 用户提供的订单ID  
> reqId | String | 否 | 用户提供的请求ID  
如果提供，那在返回参数中返回reqId，方便找到相应的修改请求。  
字母（区分大小写）与数字的组合，可以是纯字母、纯数字且长度要在1-32位之间。  
> newSz | String | 可选 | 修改后的新数量，`newSz`和`newPx`不可同时为空。对于部分成交订单，该数量应包含已成交数量。  
> newPx | String | 可选 | 修改后的新价格  
  
> 全部成功返回示例
    
    
    {
        "id": "1513",
        "op": "batch-amend-orders",
        "data": [{
            "clOrdId": "oktswap6",
            "ordId": "12345689",
            "reqId": "b12344",
            "sCode": "0",
            "sMsg": ""
        }, {
            "clOrdId": "oktswap7",
            "ordId": "12344",
            "reqId": "b12344",
            "sCode": "0",
            "sMsg": ""
        }],
        "code": "0",
        "msg": ""
    }
    

> 全部失败返回示例
    
    
    {
        "id": "1513",
        "op": "batch-amend-orders",
        "data": [{
            "clOrdId": "",
            "ordId": "12345689",
            "reqId": "b12344",
            "sCode": "5XXXX",
            "sMsg": "order not exist"
        }, {
            "clOrdId": "oktswap7",
            "ordId": "",
            "reqId": "b12344",
            "sCode": "5XXXX",
            "sMsg": "order not exist"
        }],
        "code": "1",
        "msg": ""
    }
    

> 部分成功返回示例
    
    
    {
        "id": "1513",
        "op": "batch-amend-orders",
        "data": [{
            "clOrdId": "",
            "ordId": "12345689",
            "reqId": "b12344",
            "sCode": "0",
            "sMsg": ""
        }, {
            "clOrdId": "oktswap7",
            "ordId": "",
            "reqId": "b12344",
            "sCode": "5XXXX",
            "sMsg": "order not exist"
        }],
        "code": "2",
        "msg": ""
    }
    

> 格式错误返回示例
    
    
    {
        "id": "1513",
        "op": "batch-amend-orders",
        "data": [],
        "code": "60013",
        "msg": "Invalid args"
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
id | String | 消息的唯一标识  
op | String | 业务操作  
code | String | 代码  
msg | String | 消息  
data | Array | 请求成功后返回的数据  
> ordId | String | 订单ID  
> clOrdId | String | 由用户设置的订单ID  
> reqId | String | 用户提供的请求ID  
如果用户在请求中提供reqId，则返回相应reqId  
> sCode | String | 订单状态码，0 代表成功  
> sMsg | String | 订单状态消息  
  
## 私有频道

### 账户频道

获取账户信息，首次订阅按照订阅维度推送数据，此外，当下单、撤单、成交等事件触发时，推送数据以及按照订阅维度定时推送数据

> 请求示例：单个
    
    
    {
        "op": "subscribe",
        "args": [{
            "channel": "account",
            "ccy": "BTC"
        }]
    }
    

> 请求示例
    
    
    {
        "op": "subscribe",
        "args": [{
            "channel": "account"
        }]
    }
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
op | String | 是 | 操作，`subscribe` `unsubscribe`  
args | Array | 是 | 请求订阅的频道列表  
> channel | String | 是 | 频道名，`account`  
> ccy | String | 否 | 币种  
  
> 成功返回示例：单个
    
    
    {
        "event": "subscribe",
        "arg": {
            "channel": "account",
            "ccy": "BTC"
        }
    }
    

> 成功返回示例
    
    
    {
        "event": "subscribe",
        "arg": {
            "channel": "account"
        }
    }
    

> 失败返回示例
    
    
    {
        "event": "error",
        "code": "60012",
        "msg": "Unrecognized request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"account\", \"ccy\" : \"BTC\"}]}"
    }
    

#### 返回参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
event | String | 是 | 操作，`subscribe` `unsubscribe` `error`  
arg | Object | 否 | 订阅的频道  
> channel | String | 是 | 频道名，`account`  
> ccy | String | 否 | 币种  
code | String | 否 | 错误码  
msg | String | 否 | 错误消息  
  
> 推送示例：单个
    
    
    {
      "arg": {
        "channel": "account",
        "ccy": "BTC"
      },
      "data": [
        {
          "uTime": "1597026383085",
          "totalEq": "41624.32",
          "isoEq": "3624.32",
          "adjEq": "41624.32",
          "ordFroz": "0",
          "imr": "4162.33",
          "mmr": "4",
          "notionalUsd": "",
          "mgnRatio": "41624.32",
          "details": [
            {
              "availBal": "",
              "availEq": "1",
              "ccy": "BTC",
              "cashBal": "1",
              "uTime": "1617279471503",
              "disEq": "50559.01",
              "eq": "1",
              "eqUsd": "45078.3790756226851775",
              "frozenBal": "0",
              "interest": "0",
              "isoEq": "0",
              "liab": "0",
              "maxLoan": "",
              "mgnRatio": "",
              "notionalLever": "0.0022195262185864",
              "ordFrozen": "0",
              "upl": "0",
              "uplLiab": "0",
              "crossLiab": "0",
              "isoLiab": "0",
              "coinUsdPrice": "60000",
              "stgyEq":"0",
              "isoUpl":""
            }
          ]
        }
      ]
    }
    

> 推送示例
    
    
    {
      "arg": {
        "channel": "account",
        "uid": "77982378738415879",
      },
      "data": [
        {
          "uTime": "1614846244194",
          "totalEq": "91884.8502560037982063",
          "adjEq": "91884.8502560037982063",
          "isoEq": "0",
          "ordFroz": "0",
          "imr": "0",
          "mmr": "0",
          "notionalUsd": "",
          "mgnRatio": "100000",
          "details": [{
              "availBal": "",
              "availEq": "1",
              "ccy": "BTC",
              "cashBal": "1",
              "uTime": "1617279471503",
              "disEq": "50559.01",
              "eq": "1",
              "eqUsd": "45078.3790756226851775",
              "frozenBal": "0",
              "interest": "0",
              "isoEq": "0",
              "liab": "0",
              "maxLoan": "",
              "mgnRatio": "",
              "notionalLever": "0.0022195262185864",
              "ordFrozen": "0",
              "upl": "0",
              "uplLiab": "0",
              "crossLiab": "0",
              "isoLiab": "0",
              "coinUsdPrice": "60000",
              "stgyEq":"0",
              "isoUpl":""
            },
            {
              "availBal": "",
              "availEq": "41307.251992607125",
              "ccy": "USDT",
              "cashBal": "41307.251992607125",
              "uTime": "1617279471503",
              "disEq": "41325.8402560037982063",
              "eq": "41307.251992607125",
              "eqUsd": "45078.3790756226851775",
              "frozenBal": "0",
              "interest": "0",
              "isoEq": "0",
              "liab": "0",
              "maxLoan": "",
              "mgnRatio": "",
              "notionalLever": "0.0022195262185864",
              "ordFrozen": "0",
              "upl": "0",
              "uplLiab": "0",
              "crossLiab": "0",
              "isoLiab": "0",
              "coinUsdPrice": "1.00007",
              "stgyEq":"0",
              "isoUpl":""
            }
          ]
        }
      ]
    }
    

#### 推送数据参数

**参数名** | **类型** | **描述**  
---|---|---  
arg | Object | 请求订阅的频道  
> channel | String | 频道名  
> uid | String | 用户标识  
> ccy | String | 币种  
data | Array | 订阅的数据  
uTime | String | 获取账户信息的最新时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
totalEq | String | 美金层面权益  
isoEq | String | 美金层面逐仓仓位权益  
适用于`单币种保证金模式`和`跨币种保证金模式`和`组合保证金模式`  
adjEq | String | 美金层面有效保证金  
适用于`跨币种保证金模式`和`组合保证金模式`  
ordFroz | String | 美金层面全仓挂单占用保证金  
适用于`跨币种保证金模式`和`组合保证金模式`  
imr | String | 美金层面占用保证金  
适用于`跨币种保证金模式`和`组合保证金模式`  
mmr | String | 美金层面维持保证金  
适用于`跨币种保证金模式`和`组合保证金模式`  
mgnRatio | String | 美金层面保证金率  
适用于`跨币种保证金模式`和`组合保证金模式`  
notionalUsd | String | 以美金价值为单位的持仓数量，即仓位美金价值  
适用于`跨币种保证金模式`和`组合保证金模式`  
details | Array | 各币种资产详细信息  
> ccy | String | 币种  
> eq | String | 币种总权益  
> cashBal | String | 币种余额  
> uTime | String | 币种余额信息的更新时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
> isoEq | String | 币种逐仓仓位权益  
适用于`单币种保证金模式`和`跨币种保证金模式`和`组合保证金模式`  
> availEq | String | 可用保证金  
适用于`单币种保证金模式`和`跨币种保证金模式`和`组合保证金模式`  
> disEq | String | 美金层面币种折算权益  
> availBal | String | 可用余额  
适用于`简单交易模式`  
> frozenBal | String | 币种占用金额  
> ordFrozen | String | 挂单冻结数量  
> liab | String | 币种负债额  
适用于`跨币种保证金模式`和`组合保证金模式`  
> upl | String | 未实现盈亏  
适用于`单币种保证金模式`和`跨币种保证金模式`和`组合保证金模式`  
> uplLiab | String | 由于仓位未实现亏损导致的负债  
适用于`跨币种保证金模式`和`组合保证金模式`  
> crossLiab | String | 币种全仓负债额  
适用于`跨币种保证金模式`和`组合保证金模式`  
> isoLiab | String | 币种逐仓负债额  
适用于`跨币种保证金模式`和`组合保证金模式`  
> mgnRatio | String | 保证金率  
适用于`单币种保证金模式`  
> interest | String | 计息  
适用于`跨币种保证金模式`和`组合保证金模式`  
> twap | String | 当前负债币种触发系统自动换币的风险  
0、1、2、3、4、5其中之一，数字越大代表您的负债币种触发自动换币概率越高  
适用于`跨币种保证金模式`和`组合保证金模式`  
> maxLoan | String | 币种最大可借  
适用于`跨币种保证金模式`和`组合保证金模式`  
> eqUsd | String | 币种权益美金价值  
> notionalLever | String | 币种杠杆倍数  
适用于`单币种保证金模式`  
> coinUsdPrice | String | 币种美元指数  
> stgyEq | String | 策略权益  
> isoUpl | String | 逐仓未实现盈亏  
适用于`单币种保证金模式`和`跨币种保证金模式`和`组合保证金模式`  
  
如果同时成交多个订单，那么将对账户频道的推送尽量进行聚合。

首次推送，只推用户币种层面资产不为0的账户信息。币种层面资产不为0的定义：eq、availEq、availBal
中任意一个字段不为0，即币种层面资产不为0。

定时推送，只推用户币种层面资产不为0的账户信息。币种层面资产不为0的定义：eq、availEq、availBal
中任意一个字段不为0，即币种层面资产不为0。

例：按照所有币种订阅且有5个币种的余额或者权益都不为0，首次和定时推全部5个；账户下有一个币种余额或者权益改变，那么账户变更的触发只推这一个。

### 持仓频道

获取持仓信息，首次订阅按照订阅维度推送数据，此外，当下单、撤单等事件触发时，推送数据以及按照订阅维度定时推送数据

> 请求示例：单个
    
    
    {
        "op": "subscribe",
        "args": [{
            "channel": "positions",
            "instType": "FUTURES",
            "uly": "BTC-USD",
            "instId": "BTC-USD-200329"
        }]
    }
    

> 请求示例
    
    
    {
        "op": "subscribe",
        "args": [{
            "channel": "positions",
            "instType": "ANY"
        }]
    }
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
op | String | 是 | 操作，`subscribe` `unsubscribe`  
args | Array | 是 | 请求订阅的频道列表  
> channel | String | 是 | 频道名，`positions`  
> instType | String | 是 | 产品类型  
`MARGIN`：币币杠杆  
`SWAP`：永续合约  
`FUTURES`：交割合约  
`OPTION`：期权  
`ANY`：全部  
> uly | String | 否 | 标的指数  
> instId | String | 否 | 产品ID  
  
> 成功返回示例：单个
    
    
    {
        "event": "subscribe",
        "arg": {
            "channel": "positions",
            "instType": "FUTURES",
            "uly": "BTC-USD",
            "instId": "BTC-USD-200329"
        }
    }
    

> 成功返回示例
    
    
    {
        "event": "subscribe",
        "arg": {
            "channel": "positions",
            "instType": "ANY"
        }
    }
    

> 失败返回示例
    
    
    {
        "event": "error",
        "code": "60012",
        "msg": "Unrecognized request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"positions\", \"instType\" : \"FUTURES\"}]}"
    }
    

#### 返回参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
event | String | 是 | 事件，`subscribe` `unsubscribe` `errror`  
arg | Object | 否 | 订阅的频道  
> channel | String | 是 | 频道名  
> instType | String | 是 | 产品类型  
`MARGIN`：币币杠杆  
`SWAP`：永续合约  
`FUTURES`：交割合约  
`OPTION`：期权  
`ANY`： 全部  
> uly | String | 否 | 标的指数  
> instId | String | 否 | 产品ID  
code | String | 否 | 错误码  
msg | String | 否 | 错误消息  
  
> 推送示例：单个
    
    
    {
        "arg":{
            "channel":"positions",
            "instType":"FUTURES"
        },
        "data":[
            {
                "adl":"1",
                "availPos":"1",
                "avgPx":"2566.31",
                "cTime":"1619507758793",
                "ccy":"ETH",
                "deltaBS":"",
                "deltaPA":"",
                "gammaBS":"",
                "gammaPA":"",
                "imr":"",
                "instId":"ETH-USD-210430",
                "instType":"FUTURES",
                "interest":"0",
                "last":"2566.22",
                "lever":"10",
                "liab":"",
                "liabCcy":"",
                "liqPx":"2352.8496681818233",
                "markPx":"2353.849",
                "margin":"0.0003896645377994",
                "mgnMode":"isolated",
                "mgnRatio":"11.731726509588816",
                "mmr":"0.0000311811092368",
                "notionalUsd":"2276.2546609009605",
                "optVal":"",
                "pTime":"1619507761462",
                "pos":"1",
                "posCcy":"",
                "posId":"307173036051017730",
                "posSide":"long",
                "thetaBS":"",
                "thetaPA":"",
                "tradeId":"109844",
                "uTime":"1619507761462",
                "upl":"-0.0000009932766034",
                "uplRatio":"-0.0025490556801078",
                "vegaBS":"",
                "vegaPA":""
            }
        ]
    }
    

> 推送示例
    
    
    {
        "arg": {
            "channel": "positions",
            "uid": "77982378738415879",
            "instType": "ANY"
        },
        "data": [{
        "adl":"1",
        "availPos":"1",
        "avgPx":"2566.31",
        "cTime":"1619507758793",
        "ccy":"ETH",
        "deltaBS":"",
        "deltaPA":"",
        "gammaBS":"",
        "gammaPA":"",
        "imr":"",
        "instId":"ETH-USD-210430",
        "instType":"FUTURES",
        "interest":"0",
        "last":"2566.22",
        "usdPx":"",
        "lever":"10",
        "liab":"",
        "liabCcy":"",
        "liqPx":"2352.8496681818233",
        "markPx":"2353.849",
        "margin":"0.0003896645377994",
        "mgnMode":"isolated",
        "mgnRatio":"11.731726509588816",
        "mmr":"0.0000311811092368",
        "notionalUsd":"2276.2546609009605",
        "optVal":"",
        "pTime":"1619507761462",
        "pos":"1",
        "posCcy":"",
        "posId":"307173036051017730",
        "posSide":"long",
        "thetaBS":"",
        "thetaPA":"",
        "tradeId":"109844",
        "uTime":"1619507761462",
        "upl":"-0.0000009932766034",
        "uplRatio":"-0.0025490556801078",
        "vegaBS":"",
        "vegaPA":""
    }, {
        "adl":"1",
        "availPos":"1",
        "avgPx":"2566.31",
        "cTime":"1619507758793",
        "ccy":"ETH",
        "deltaBS":"",
        "deltaPA":"",
        "gammaBS":"",
        "gammaPA":"",
        "imr":"",
        "instId":"ETH-USD-SWAP",
        "instType":"SWAP",
        "interest":"0",
        "last":"2566.22",
        "usdPx":"",
        "lever":"10",
        "liab":"",
        "liabCcy":"",
        "liqPx":"2352.8496681818233",
        "markPx":"2353.849",
        "margin":"0.0003896645377994",
        "mgnMode":"isolated",
        "mgnRatio":"11.731726509588816",
        "mmr":"0.0000311811092368",
        "notionalUsd":"2276.2546609009605",
        "optVal":"",
        "pTime":"1619507761462",
        "pos":"1",
        "posCcy":"",
        "posId":"307173036051017730",
        "posSide":"long",
        "thetaBS":"",
        "thetaPA":"",
        "tradeId":"109844",
        "uTime":"1619507761462",
        "upl":"-0.0000009932766034",
        "uplRatio":"-0.0025490556801078",
        "vegaBS":"",
        "vegaPA":""
    }]
    }
    

#### 推送数据参数

参数名 | 类型 | 描述  
---|---|---  
arg | Object | 订阅成功的频道  
> channel | String | 频道名  
> uid | String | 用户标识  
> instType | String | 产品类型  
> uly | String | 标的指数  
> instId | String | 产品ID  
data | Array | 订阅的数据  
> instType | String | 产品类型  
> mgnMode | String | 保证金模式， `cross`：全仓 `isolated`：逐仓  
> posId | String | 持仓ID  
> posSide | String | 持仓方向  
`long`：双向持仓多头  
`short`：双向持仓空头  
`net`：单向持仓（`交割/永续/期权`：`pos`为正代表多头，`pos`为负代表空头。`币币杠杆`：`posCcy`为交易货币时，代表多头；`posCcy`为计价货币时，代表空头。）  
> pos | String | 持仓数量，逐仓自主划转模式下，转入保证金后会产生pos为`0`的仓位  
> baseBal | String | 交易币余额，适用于 `币币杠杆`（逐仓自主划转模式）  
> quoteBal | String | 计价币余额 ，适用于 `币币杠杆`（逐仓自主划转模式）  
> posCcy | String | 持仓数量币种，仅适用于`币币杠杆`  
> availPos | String | 可平仓数量  
适用于 `币币杠杆`,`交割/永续`（开平仓模式），`期权`（交易账户及保证金账户逐仓）。  
> avgPx | String | 开仓平均价  
> upl | String | 未实现收益  
> uplRatio | String | 未实现收益率  
> instId | String | 产品ID，如 BTC-USD-180216  
> lever | String | 杠杆倍数，不适用于`期权卖方`  
> liqPx | String | 预估强平价  
不适用于`期权`  
> markPx | String | 标记价格  
> imr | String | 初始保证金，仅适用于`全仓`  
> margin | String | 保证金余额，仅适用于`逐仓`，可增减  
> mgnRatio | String | 保证金率  
> mmr | String | 维持保证金  
> liab | String | 负债额，仅适用于`币币杠杆`  
> liabCcy | String | 负债币种，仅适用于`币币杠杆`  
> interest | String | 利息，已经生成未扣利息  
> tradeId | String | 最新成交ID  
> notionalUsd | String | 以美金价值为单位的持仓数量  
> optVal | String | 期权价值，仅适用于`期权`  
> adl | String | 信号区，分为5档，从1到5，数字越小代表adl强度越弱  
> ccy | String | 占用保证金的币种  
> last | String | 最新成交价  
> usdPx | String | 美金价格  
> deltaBS | String | 美金本位持仓仓位delta，仅适用于`期权`  
> deltaPA | String | 币本位持仓仓位delta，仅适用于`期权`  
> gammaBS | String | 美金本位持仓仓位gamma，仅适用于`期权`  
> gammaPA | String | 币本位持仓仓位gamma，仅适用于`期权`  
> thetaBS | String | 美金本位持仓仓位theta，仅适用于`期权`  
> thetaPA | String | 币本位持仓仓位theta，仅适用于`期权`  
> vegaBS | String | 美金本位持仓仓位vega，仅适用于`期权`  
> vegaPA | String | 币本位持仓仓位vega，仅适用于`期权`  
> cTime | String | 持仓创建时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
> uTime | String | 最近一次持仓更新时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
> pTime | String | 持仓信息的推送时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
  
如果同时成交多个订单，那么将持仓频道的推送尽量进行聚合。

PM账户下，持仓的 IMR MMR的数据是后端服务以ristUnit为最小粒度重新计算，相同riskUnit全仓仓位的imr和mmr返回值相同。

逐仓交易设置里是自主划转模式，转入保证金后会推送持仓量为0的仓位

首次推送，只推用户持有的仓位。用户持仓仓位定义：持逐仓自主划转模式下的逐仓仓位pos=0，pos>0或者pos<0都认为持有仓位。

定时推送，只推用户持有的仓位。用户持仓仓位定义：持逐仓自主划转模式下的逐仓仓位pos=0，pos>0或者pos<0都认为持有仓位。

例：按underlying订阅且该underlying下有20个持仓，首次和定时推全部20个；持仓下有一个成交改变其中的一个持仓，那么持仓变更只推这一个。

### 账户余额和持仓频道

获取账户余额和持仓信息，首次订阅按照订阅维度推送数据，此外，当成交、资金划转等事件触发时，推送数据。

该频道适用于尽快获取账户现金余额和仓位资产变化的信息。

> 请求示例
    
    
    {
        "op": "subscribe",
        "args": [{
            "channel": "balance_and_position"
        }]
    }
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
op | String | 是 | 操作，`subscribe` `unsubscribe`  
args | Array | 是 | 请求订阅的频道列表  
> channel | String | 是 | 频道名，`balance_and_position`  
  
> 成功返回示例
    
    
    {
        "event": "subscribe",
        "arg": {
            "channel": "balance_and_position"
        }
    }
    

> 失败返回示例
    
    
    {
        "event": "error",
        "code": "60012",
        "msg": "Unrecognized request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"balance_and_position\"}]}"
    }
    

#### 返回参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
event | String | 是 | 操作，`subscribe` `unsubscribe` `error`  
arg | Object | 否 | 订阅的频道  
> channel | String | 是 | 频道名，`balance_and_position`  
code | String | 否 | 错误码  
msg | String | 否 | 错误消息  
  
> 推送示例
    
    
    {
        "arg": {
            "channel": "balance_and_position",
            "uid": "77982378738415879"
        },
        "data": [{
            "pTime": "1597026383085",
            "eventType": "snapshot",
            "balData": [{
                "ccy": "BTC",
                "cashBal": "1",
                "uTime": "1597026383085"
            }],
            "posData": [{
                "posId": "1111111111",
                "tradeId": "2",
                "instId": "BTC-USD-191018",
                "instType": "FUTURES",
                "mgnMode": "cross",
                "posSide": "long",
                "pos": "10",
                "ccy": "BTC",
                "posCcy": "",
                "avgPx": "3320",
                "uTime": "1597026383085"
            }]
        }]
    }
    

#### 推送数据参数

**参数名** | **类型** | **描述**  
---|---|---  
arg | Object | 请求订阅的频道  
> channel | String | 频道名  
> uid | String | 用户标识  
data | Array | 订阅的数据  
> pTime | String | 推送时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
> eventType | String | 事件类型，枚举值：`snapshot`：首推快照  
`delivered`：交割 `exercised`：行权 `transferred`：划转  
`filled`：成交 `liquidation`：强平 `claw_back`：穿仓补偿  
`adl`：ADL自动减仓 `funding_fee`：资金费 `adjust_margin`：调整保证金  
`set_leverage`：设置杠杆 `interest_deduction`：扣息  
> balData | String | 余额数据  
>> ccy | String | 币种  
>> cashBal | String | 币种余额  
>> uTime | String | 币种余额信息的更新时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
> posData | String | 持仓数据  
>> posId | String | 持仓ID  
>> tradeId | String | 最新成交ID  
>> instId | String | 交易产品ID，如 `BTC-USD-180213`  
>> instType | String | 交易产品类型， `MARGIN`：币币杠杆 `SWAP`：永续合约 `FUTURES`：交割合约
`OPTION`：期权  
>> mgnMode | String | 保证金模式， `isolated`, `cross`  
>> avgPx | String | 开仓平均价  
>> ccy | String | 占用保证金的币种  
>> posSide | String | 持仓方向：`long`, `short`, `net`  
>> pos | String | 持仓数量，逐仓自主划转模式下，转入保证金后会产生pos为`0`的仓位  
>> baseBal | String | 交易币余额，适用于 `币币杠杆`（逐仓自主划转模式）  
>> quoteBal | String | 计价币余额 ，适用于 `币币杠杆`（逐仓自主划转模式）  
>> posCcy | String | 持仓数量币种，只适用于币币杠杆仓位。当是交割、永续、期权持仓时，该字段返回“”  
>> uTime | String | 仓位信息的更新时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
  
只有账户余额变化，只推balData；只有持仓余额发生变化，只推posData。

首次推送，只推用户持有的仓位和币种余额不为0的信息。

例：比如按照所有币种订阅且用户有5个币种余额不为0
和20个仓位，那么首推全部5个币种余额列表和20个持仓信息列表；某个订单成交后，那么只推一个币种余额和对应的持仓信息。

### 订单频道

获取订单信息，首次订阅不推送，只有当下单、撤单等事件触发时，推送数据

> 请求示例：单个
    
    
    {
        "op": "subscribe",
        "args": [{
            "channel": "orders",
            "instType": "FUTURES",
            "uly": "BTC-USD",
            "instId": "BTC-USD-200329"
        }]
    }
    

> 请求示例
    
    
    {
        "op": "subscribe",
        "args": [{
            "channel": "orders",
            "instType": "FUTURES",
            "uly": "BTC-USD"
        }]
    }
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
op | String | 是 | 操作，`subscribe` `unsubscribe`  
args | Array | 是 | 请求订阅的频道列表  
> channel | String | 是 | 频道名， `orders`  
> instType | String | 是 | 产品类型  
`SPOT`：币币  
`MARGIN`：币币杠杆  
`SWAP`：永续合约  
`FUTURES`：交割合约  
`OPTION`：期权  
`ANY`：全部  
> uly | String | 否 | 标的指数  
> instId | String | 否 | 产品ID  
  
> 成功返回示例：单个
    
    
    {
        "event": "subscribe",
        "arg": {
            "channel": "orders",
            "instType": "FUTURES",
            "uly": "BTC-USD",
            "instId": "BTC-USD-200329"
        }
    }
    

> 成功返回示例
    
    
    {
        "event": "subscribe",
        "arg": {
            "channel": "orders",
            "instType": "FUTURES",
            "uly": "BTC-USD"
        }
    }
    

> 失败返回示例
    
    
    {
        "event": "error",
        "code": "60012",
        "msg": "Unrecognized request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"orders\", \"instType\" : \"FUTURES\"}]}"
    }
    

#### 返回参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
event | String | 是 | 事件，`subscribe` `unsubscribe` `errror`  
arg | Object | 否 | 订阅的频道  
> channel | String | 是 | 频道名  
> instType | String | 是 | 产品类型  
`SPOT`：币币  
`MARGIN`：币币杠杆  
`SWAP`：永续合约  
`FUTURES`：交割合约  
`OPTION`：期权  
`ANY`： 全部  
> uly | String | 否 | 标的指数  
> instId | String | 否 | 产品ID  
code | String | 否 | 错误码  
msg | String | 否 | 错误消息  
  
> 推送示例：单个
    
    
    {
        "arg": {
            "channel": "orders",
            "uid": "77982378738415879",
            "instType": "FUTURES",
            "instId": "BTC-USD-200329"
        },
        "data": [{
            "instType": "FUTURES",
            "instId": "BTC-USD-200329",
            "ordId": "312269865356374016",
            "clOrdId": "b1",
            "tag": "",
            "px": "999",
            "sz": "333",
            "notionalUsd": "",
            "ordType": "limit",
            "side": "buy",
            "posSide": "long",
            "tdMode": "cross",
            "tgtCcy": "",
            "fillSz": "0",
            "fillPx": "long",
            "tradeId": "0",
            "accFillSz": "323",
            "fillNotionalUsd": "",
            "fillTime": "0",
            "fillFee": "0.0001",
            "fillFeeCcy": "BTC",
            "execType": "T",
            "source": "",
            "state": "canceled",
            "avgPx": "0",
            "lever": "20",
            "tpTriggerPx": "0",
            "tpTriggerPxType": "last",
            "tpOrdPx": "20",
            "slTriggerPx": "0",
            "slTriggerPxType": "last",
            "slOrdPx": "20",
            "feeCcy": "",
            "fee": "",
            "rebateCcy": "",
            "rebate": "",
            "tgtCcy":"",
            "pnl": "",
            "category": "",
            "uTime": "1597026383085",
            "cTime": "1597026383085",
            "reqId": "",
            "amendResult": "",
            "code": "0",
            "msg": ""
        }]
    }
    

#### 推送数据参数

**参数名** | **类型** | **描述**  
---|---|---  
arg | Object | 订阅成功的频道  
> channel | String | 频道名  
> uid | String | 用户标识  
> instType | String | 产品类型  
> uly | String | 标的指数  
> instId | String | 产品ID  
data | Array | 订阅的数据  
> instType | String | 产品类型  
> instId | String | 产品ID  
> ccy | String | 保证金币种，仅适用于`单币种保证金账户`下的全仓`币币杠杆`订单  
> ordId | String | 订单ID  
> clOrdId | String | 由用户设置的订单ID来识别您的订单  
> tag | String | 订单标签  
> px | String | 委托价格  
> sz | String | 原始委托数量，`币币/币币杠杆`，以币为单位；`交割/永续/期权` ，以张为单位  
> notionalUsd | String | 委托单预估美元价值  
> ordType | String | 订单类型  
`market`：市价单  
`limit`：限价单  
`post_only`： 只做maker单  
`fok`：全部成交或立即取消单  
`ioc`：立即成交并取消剩余单  
`optimal_limit_ioc`：市价委托立即成交并取消剩余（仅适用交割、永续）  
> side | String | 订单方向，`buy` `sell`  
> posSide | String | 持仓方向  
`long`：双向持仓多头  
`short`：双向持仓空头  
`net`：单向持仓  
> tdMode | String | 交易模式  
保证金模式 `isolated`：逐仓 `cross`：全仓  
非保证金模式 `cash`：现金  
> tgtCcy | String | 市价单委托数量的类型  
`base_ccy`: 交易货币 `quote_ccy`：计价货币  
> fillPx | String | 最新成交价格  
> tradeId | String | 最新成交ID  
> fillSz | String | 最新成交数量  
> fillTime | String | 最新成交时间  
> fillFee | String | 最新一笔成交的手续费  
> fillFeeCcy | String | 最新一笔成交的手续费币种  
> execType | String | 最新一笔成交的流动性方向 T：taker M：maker  
> accFillSz | String | 累计成交数量  
> fillNotionalUsd | String | 委托单已成交的美元价值  
> avgPx | String | 成交均价，如果成交数量为0，该字段也为0  
> state | String | 订单状态  
`canceled`：撤单成功  
`live`：等待成交  
`partially_filled`： 部分成交  
`filled`：完全成交  
> lever | String | 杠杆倍数，0.01到125之间的数值，仅适用于 `币币杠杆/交割/永续`  
> tpTriggerPx | String | 止盈触发价  
> tpTriggerPxType | String | 止盈触发价类型  
`last`：最新价格  
`index`：指数价格  
`mark`：标记价格  
> tpOrdPx | String | 止盈委托价，止盈委托价格为`-1`时，执行市价止盈  
> slTriggerPx | String | 止损触发价  
> slTriggerPxType | String | 止损触发价类型  
`last`：最新价格  
`index`：指数价格  
`mark`：标记价格  
> slOrdPx | String | 止损委托价，止损委托价格为`-1`时，执行市价止损  
> feeCcy | String | 交易手续费币种  
`币币/币币杠杆`：如果是买的话，收取的就是BTC；如果是卖的话，收取的就是USDT  
`交割/永续/期权` 收取的就是保证金  
> fee | String | 订单交易手续费，平台向用户收取的交易手续费  
> rebateCcy | String | 返佣金币种 ，如果没有返佣金，该字段为“”  
> rebate | String | 返佣金额，平台向达到指定lv交易等级的用户支付的挂单奖励（返佣），如果没有返佣金，该字段为“”  
> pnl | String | 收益  
> source | String | 订单来源  
`13`:策略委托单触发后的生成的限价单  
> category | String | 订单种类分类  
`normal`：普通委托订单种类  
`twap`：TWAP订单种类  
`adl`：ADL订单种类  
`full_liquidation`：爆仓订单种类  
`partial_liquidation`：减仓订单种类  
`delivery`：交割  
`ddh`：对冲减仓类型订单  
> uTime | String | 订单更新时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
> cTime | String | 订单创建时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
> reqId | String | 修改订单时使用的request ID，如果没有修改，该字段为""  
> amendResult | String | 修改订单的结果  
`-1`： 失败  
`0`：成功  
`1`：自动撤单（因为修改成功导致订单自动撤销）  
通过API修改订单时，如果`cxlOnFail`设置为`false`且修改失败后，则`amendResult`返回 `-1`  
通过API修改订单时，如果`cxlOnFail`设置为`true`且修改失败后，则`amendResult`返回`1`  
通过Web/APP修改订单时，如果修改失败后，则`amendResult`返回`-1`  
> code | String | 错误码，默认为0  
> msg | String | 错误消息，默认为""  
  
### 策略委托订单频道

获取策略委托订单，首次订阅不推送，只有当下单、撤单等事件触发时，推送数据

> 请求示例：单个
    
    
    {
        "op": "subscribe",
        "args": [{
            "channel": "orders-algo",
            "instType": "FUTURES",
            "uly": "BTC-USD",
            "instId": "BTC-USD-200329"
        }]
    }
    

> 请求示例
    
    
    {
        "op": "subscribe",
        "args": [{
            "channel": "orders-algo",
            "instType": "FUTURES",
            "uly": "BTC-USD"
        }]
    }
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
op | String | 是 | 操作，`subscribe` `unsubscribe`  
args | Array | 是 | 请求订阅的频道列表  
> channel | String | 是 | 频道名，`orders-algo`  
> instType | String | 是 | 产品类型  
`SPOT`：币币  
`MARGIN`：币币杠杆  
`SWAP`：永续合约  
`FUTURES`：交割合约  
`ANY`：全部  
> uly | String | 否 | 标的指数  
> instId | String | 否 | 产品ID  
  
> 成功返回示例：单个
    
    
    {
        "event": "subscribe",
        "arg": {
            "channel": "orders-algo",
            "instType": "FUTURES",
            "uly": "BTC-USD",
            "instId": "BTC-USD-200329"
        }
    }
    

> 成功返回示例
    
    
    {
        "event": "subscribe",
        "arg": {
            "channel": "orders-algo",
            "instType": "FUTURES",
            "uly": "BTC-USD"
        }
    }
    

> 失败返回示例
    
    
    {
        "event": "error",
        "code": "60012",
        "msg": "Unrecognized request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"orders-algo\", \"instType\" : \"FUTURES\"}]}"
    }
    

#### 返回参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
event | String | 是 | 事件，`subscribe` `unsubscribe` `errror`  
arg | Object | 否 | 订阅的频道  
> channel | String | 是 | 频道名  
> instType | String | 是 | 产品类型  
`SPOT`：币币  
`MARGIN`：币币杠杆  
`SWAP`：永续合约  
`FUTURES`：交割合约  
`ANY`：全部  
> uly | String | 否 | 标的指数  
> instId | String | 否 | 产品ID  
code | String | 否 | 错误码  
msg | String | 否 | 错误消息  
  
> 推送示例：单个
    
    
    {
        "arg": {
            "channel": "orders-algo",
            "uid": "77982378738415879",
            "instType": "FUTURES",
            "instId": "BTC-USD-200329"
        },
        "data": [{
            "instType": "FUTURES",
            "instId": "BTC-USD-200329",
            "ordId": "312269865356374016",
            "ccy": "BTC",
            "algoId": "1234",
            "px": "999",
            "sz": "3",
            "tdMode": "cross",
            "tgtCcy": "",
            "notionalUsd": "",
            "ordType": "trigger",
            "side": "buy",
            "posSide": "long",
            "state": "live",
            "lever": "20",
            "tpTriggerPx": "",
            "tpTriggerPxType": "",
            "tpOrdPx": "",
            "slTriggerPx": "",
            "slTriggerPxType": "",
            "triggerPx": "99",
            "triggerPxType": "last",
            "ordPx": "12",
            "tag": "adadadadad",
            "actualSz": "",
            "actualPx": "",
            "actualSide": "",
            "triggerTime": "1597026383085",
            "cTime": "1597026383000"
        }]
    }
    

#### 推送数据参数

**参数名** | **类型** | **描述**  
---|---|---  
arg | Object | 订阅成功的频道  
> channel | String | 频道名  
> uid | String | 用户标识  
> instType | String | 产品类型  
> uly | String | 标的指数  
> instId | String | 产品ID  
data | Array | 订阅的数据  
> instType | String | 产品类型  
> instId | String | 产品ID  
> ccy | String | 保证金币种，仅单币种保证金账户下的全仓币币杠杆需要选择保证金币种  
> ordId | String | 订单ID，与策略委托订单关联的订单ID  
> algoId | String | 策略委托单ID  
> sz | String | 委托数量，`币币/币币杠杆` 以币为单位；`交割/永续/期权` 以张为单位  
> ordType | String | 订单类型  
`conditional`：单向止盈止损  
`oco`：双向止盈止损  
`trigger`：计划委托  
> side | String | 订单方向，`buy` `sell`  
> posSide | String | 持仓方向  
`long`：双向持仓多头  
`short`：双向持仓空头  
`net`：单向持仓  
> tdMode | String | 交易模式  
保证金模式 `cross`：全仓 `isolated`：逐仓  
非保证金模式 `cash`：现金  
> tgtCcy | String | 市价单委托数量的类型  
`base_ccy`: 交易货币 ；`quote_ccy`：计价货币  
> lever | String | 杠杆倍数，0.01到125之间的数值，仅适用于 `币币杠杆/交割/永续`  
> state | String | 订单状态  
`live`：待生效  
`effective`：已生效  
`canceled`：已撤销  
`order_failed`：委托失败  
> tpTriggerPx | String | 止盈触发价  
> tpTriggerPxType | String | 止盈触发价类型  
`last`：最新价格  
`index`：指数价格  
`mark`：标记价格  
> tpOrdPx | String | 止盈委托价，委托价格为`-1`时，执行市价止盈  
> slTriggerPx | String | 止损触发价  
> slTriggerPxType | String | 止损触发价类型  
`last`：最新价格  
`index`：指数价格  
`mark`：标记价格  
> slOrdPx | String | 止损委托价委托价格为`-1`时，执行市价止损  
> triggerPx | String | 计划委托单的触发价格  
> triggerPxType | String | 计划委托单的触发价类型  
`last`：最新价格  
`index`：指数价格  
`mark`：标记价格  
> ordPx | String | 计划委托单的委托价格  
> actualSz | String | 实际委托量  
> actualPx | String | 实际委价  
> tag | String | 订单标签  
字母（区分大小写）与数字的组合，可以是纯字母、纯数字，且长度在1-16位之间。  
> notionalUsd | String | 委托单预估美元价值  
> actualSide | String | 实际触发方向，`sl`：止损 `tp`：止盈  
> triggerTime | String | 策略委托触发时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
> cTime | String | 订单创建时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
  
### 高级策略委托订单频道

获取高级策略委托订单（冰山、时间加权、移动止盈止损），首次订阅推送，当下单、撤单等事件触发时，推送数据

> 请求示例：单个
    
    
    {
        "op": "subscribe",
        "args": [{
            "channel": "algo-advance",
            "instType": "SPOT",
            "instId": "BTC-USDT"
        }]
    }
    

> 请求示例
    
    
    {
        "op": "subscribe",
        "args": [{
            "channel": "algo-advance",
            "instType": "SPOT",
        }]
    }
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
op | String | 是 | 操作，`subscribe` `unsubscribe`  
args | Array | 是 | 请求订阅的频道列表  
> channel | String | 是 | 频道名，`algo-advance`  
> instType | String | 是 | 产品类型  
`SPOT`：币币  
`MARGIN`：币币杠杆  
`SWAP`：永续合约  
`FUTURES`：交割合约  
`ANY`：全部  
> instId | String | 否 | 产品ID  
> algoId | String | 否 | 策略ID  
  
> 成功返回示例：单个
    
    
    {
        "event": "subscribe",
        "arg": {
            "channel": "algo-advance",
            "instType": "SPOT",
            "instId": "BTC-USDT"
        }
    }
    

> 成功返回示例
    
    
    {
        "event": "subscribe",
        "arg": {
            "channel": "algo-advance",
            "instType": "SPOT"
        }
    }
    

> 失败返回示例
    
    
    {
        "event": "error",
        "code": "60012",
        "msg": "Unrecognized request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"algo-advance\", \"instType\" : \"FUTURES\"}]}"
    }
    

#### 返回参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
event | String | 是 | 事件，`subscribe` `unsubscribe` `errror`  
arg | Object | 否 | 订阅的频道  
> channel | String | 是 | 频道名  
> instType | String | 是 | 产品类型  
`SPOT`：币币  
`MARGIN`：币币杠杆  
`SWAP`：永续合约  
`FUTURES`：交割合约  
`ANY`：全部  
> instId | String | 否 | 产品ID  
> algoId | String | 否 | 策略ID  
code | String | 否 | 错误码  
msg | String | 否 | 错误消息  
  
> 推送示例：单个
    
    
    {
        "arg":{
            "channel":"algo-advance",
            "uid": "77982378738415879",
            "instType":"SPOT",
            "instId":"BTC-USDT"
        },
        "data":[
            {
                "actualPx":"",
                "actualSide":"",
                "actualSz":"0",
                "algoId":"355056228680335360",
                "cTime":"1630924001545",
                "ccy":"",
                "count":"1",
                "instId":"BTC-USDT",
                "instType":"SPOT",
                "lever":"0",
                "notionalUsd":"",
                "ordPx":"",
                "ordType":"iceberg",
                "pTime":"1630924295204",
                "posSide":"net",
                "pxLimit":"10",
                "pxSpread":"1",
                "pxVar":"",
                "side":"buy",
                "slOrdPx":"",
                "slTriggerPx":"",
                "state":"pause",
                "sz":"0.1",
                "szLimit":"0.1",
                "tag": "adadadadad",
                "tdMode":"cash",
                "timeInterval":"",
                "tpOrdPx":"",
                "tpTriggerPx":"",
                "triggerPx":"",
                "triggerTime":"",
                "callbackRatio":"",
                "callbackSpread":"",
                "activePx":"",
                "moveTriggerPx":""
            }
        ]
    }
    

#### 推送数据参数

**参数名** | **类型** | **描述**  
---|---|---  
arg | Object | 订阅成功的频道  
> channel | String | 频道名  
> uid | String | 用户标识  
> instType | String | 产品类型  
> instId | String | 产品ID  
> algoId | String | 策略ID  
data | Array | 订阅的数据  
> instType | String | 产品类型  
> instId | String | 产品ID  
> ccy | String | 保证金币种，仅单币种保证金账户下的全仓币币杠杆需要选择保证金币种  
> ordId | String | 订单ID，与策略委托订单关联的订单ID  
> algoId | String | 策略委托单ID  
> sz | String | 委托数量，`币币/币币杠杆` 以币为单位；`交割/永续/期权` 以张为单位  
> ordType | String | 订单类型  
`iceberg`：冰山委托  
`twap`：时间加权委托  
`move_order_stop`：移动止盈止损  
> side | String | 订单方向，`buy` `sell`  
> posSide | String | 持仓方向  
`long`：双向持仓多头  
`short`：双向持仓空头  
`net`：单向持仓  
> tdMode | String | 交易模式  
保证金模式 `cross`：全仓 `isolated`：逐仓  
非保证金模式 `cash`：现金  
> tgtCcy | String | 市价单委托数量的类型  
`base_ccy`: 交易货币 ；`quote_ccy`：计价货币  
> lever | String | 杠杆倍数，0.01到125之间的数值，仅适用于 `币币杠杆/交割/永续`  
> state | String | 订单状态  
`live`：待生效  
`effective`：已生效  
`canceled`：已撤销  
`order_failed`：委托失败  
> tpTriggerPx | String | 止盈触发价  
> tpOrdPx | String | 止盈委托价，委托价格为`-1`时，执行市价止盈  
> slTriggerPx | String | 止损触发价  
> slOrdPx | String | 止损委托价委托价格为`-1`时，执行市价止损  
> triggerPx | String | 计划委托单的触发价格  
> ordPx | String | 计划委托单的委托价格  
> actualSz | String | 实际委托量  
> actualPx | String | 实际委价  
> tag | String | 订单标签  
字母（区分大小写）与数字的组合，可以是纯字母、纯数字，且长度在1-16位之间。  
> notionalUsd | String | 委托单预估美元价值  
> actualSide | String | 实际触发方向，`sl`：止损 `tp`：止盈  
> triggerTime | String | 策略委托触发时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
> cTime | String | 订单创建时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
> pxVar | String | 价格比例  
仅适用于`冰山委托`和`时间加权委托`  
> pxSpread | String | 价距  
仅适用于`冰山委托`和`时间加权委托`  
> szLimit | String | 单笔数量  
仅适用于`冰山委托`和`时间加权委托`  
> pxLimit | String | 挂单限制价  
仅适用于`冰山委托`和`时间加权委托`  
> timeInterval | String | 下单间隔  
仅适用于`时间加权委托`  
> count | String | 策略订单计数  
仅适用于`冰山委托`和`时间加权委托`  
> callbackRatio | String | 回调幅度的比例  
仅适用于`移动止盈止损`  
> callbackSpread | String | 回调幅度的价距  
仅适用于`移动止盈止损`  
> activePx | String | 移动止盈止损激活价格  
仅适用于`移动止盈止损`  
> moveTriggerPx | String | 移动止盈止损触发价格  
仅适用于`移动止盈止损`  
> pTime | String | 订单信息的推送时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
  
### 爆仓风险预警推送频道

此推送频道仅作为风险提示，不建议作为策略交易的风险判断  
在行情剧烈波动的情况下，可能会出现此消息推送的同时仓位已经被强平的可能性。  

> 请求示例
    
    
    {
        "op": "subscribe",
        "args": [{
            "channel": "liquidation-warning",
            "instType": "ANY"
        }]
    }
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
op | String | 是 | 操作，`subscribe` `unsubscribe`  
args | Array | 是 | 请求订阅的频道列表  
> channel | String | 是 | 频道名，`liquidation-warning`  
> instType | String | 是 | 产品类型  
`MARGIN`：币币杠杆  
`SWAP`：永续合约  
`FUTURES`：交割合约  
`OPTION`：期权  
`ANY`：全部  
> uly | String | 否 | 标的指数  
> instId | String | 否 | 产品ID  
  
> 成功返回示例：单个
    
    
    {
        "event": "subscribe",
        "arg": {
            "channel": "liquidation-warning",
            "instType": "FUTURES",
            "uly": "BTC-USD",
            "instId": "BTC-USD-200329"
        }
    }
    

> 失败返回示例
    
    
    {
        "event": "error",
        "code": "60012",
        "msg": "Unrecognized request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"liquidation-warning\", \"instType\" : \"FUTURES\"}]}"
    }
    

#### 返回参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
event | String | 是 | 事件，`subscribe` `unsubscribe` `errror`  
arg | Object | 否 | 订阅的频道  
> channel | String | 是 | 频道名 ，`liquidation-warning`  
> instType | String | 是 | 产品类型  
`MARGIN`：币币杠杆  
`SWAP`：永续合约  
`FUTURES`：交割合约  
`OPTION`：期权  
`ANY`： 全部  
> uly | String | 否 | 标的指数  
> instId | String | 否 | 产品ID  
code | String | 否 | 错误码  
msg | String | 否 | 错误消息  
  
> 推送示例：单个
    
    
    {
        "arg":{
            "channel":"liquidation-warning",
            "uid": "77982378738415879",
            "instType":"FUTURES"
        },
        "data":[
            {
                "adl":"1",
                "availPos":"1",
                "avgPx":"2566.31",
                "cTime":"1619507758793",
                "ccy":"ETH",
                "deltaBS":"",
                "deltaPA":"",
                "gammaBS":"",
                "gammaPA":"",
                "imr":"",
                "instId":"ETH-USD-210430",
                "instType":"FUTURES",
                "interest":"0",
                "last":"2566.22",
                "lever":"10",
                "liab":"",
                "liabCcy":"",
                "liqPx":"2352.8496681818233",
                "markPx":"2353.849",
                "margin":"0.0003896645377994",
                "mgnMode":"isolated",
                "mgnRatio":"11.731726509588816",
                "mmr":"0.0000311811092368",
                "notionalUsd":"2276.2546609009605",
                "optVal":"",
                "pTime":"1619507761462",
                "pos":"1",
                "posCcy":"",
                "posId":"307173036051017730",
                "posSide":"long",
                "thetaBS":"",
                "thetaPA":"",
                "tradeId":"109844",
                "uTime":"1619507761462",
                "upl":"-0.0000009932766034",
                "uplRatio":"-0.0025490556801078",
                "vegaBS":"",
                "vegaPA":""
            }
        ]
    }
    

#### 推送数据参数

参数名 | 类型 | 描述  
---|---|---  
arg | Object | 订阅成功的频道  
> channel | String | 频道名  
> uly | String | 用户标识  
> instType | String | 产品类型  
> uly | String | 标的指数  
> instId | String | 产品ID  
data | Array | 订阅的数据  
> instType | String | 产品类型  
> mgnMode | String | 保证金模式， `cross`：全仓 `isolated`：逐仓  
> posId | String | 持仓ID  
> posSide | String | 持仓方向  
`long`：双向持仓多头  
`short`：双向持仓空头  
`net`：单向持仓（`交割/永续/期权`：`pos`为正代表多头，`pos`为负代表空头。`币币杠杆`：`posCcy`为交易货币时，代表多头；`posCcy`为计价货币时，代表空头。）  
> pos | String | 持仓数量  
> posCcy | String | 持仓数量币种，仅适用于`币币杠杆`  
> availPos | String | 可平仓数量  
适用于 `币币杠杆`,`交割/永续`（开平仓模式），`期权`（交易账户及保证金账户逐仓）。  
> avgPx | String | 开仓平均价  
> upl | String | 未实现收益  
> uplRatio | String | 未实现收益率  
> instId | String | 产品ID，如 BTC-USD-180216  
> lever | String | 杠杆倍数，不适用于`期权卖方`  
> liqPx | String | 预估强平价  
不适用于`期权`  
> markPx | String | 标记价格  
> imr | String | 初始保证金，仅适用于`全仓`  
> margin | String | 保证金余额，仅适用于`逐仓`，可增减  
> mgnRatio | String | 保证金率  
> mmr | String | 维持保证金  
> liab | String | 负债额，仅适用于`币币杠杆`  
> liabCcy | String | 负债币种，仅适用于`币币杠杆`  
> interest | String | 利息，已经生成未扣利息  
> tradeId | String | 最新成交ID  
> notionalUsd | String | 以美金价值为单位的持仓数量  
> optVal | String | 期权价值，仅适用于`期权`  
> adl | String | 信号区，分为5档，从1到5，数字越小代表adl强度越弱  
> ccy | String | 占用保证金的币种  
> last | String | 最新成交价  
> deltaBS | String | 美金本位持仓仓位delta，仅适用于`期权`  
> deltaPA | String | 币本位持仓仓位delta，仅适用于`期权`  
> gammaBS | String | 美金本位持仓仓位gamma，仅适用于`期权`  
> gammaPA | String | 币本位持仓仓位gamma，仅适用于`期权`  
> thetaBS | String | 美金本位持仓仓位theta，仅适用于`期权`  
> thetaPA | String | 币本位持仓仓位theta，仅适用于`期权`  
> vegaBS | String | 美金本位持仓仓位vega，仅适用于`期权`  
> vegaPA | String | 币本位持仓仓位vega，仅适用于`期权`  
> cTime | String | 持仓创建时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
> uTime | String | 最近一次持仓更新时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
> pTime | String | 持仓信息的推送时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
  
触发推送逻辑：爆仓预警和爆仓短信的触发逻辑一致

### 账户greeks频道

获取账户资产的greeks信息，首次订阅按照订阅维度推送数据，此外，当增加或者减少币种余额、持仓数量等事件触发时，推送数据以及按照订阅维度定时推送数据

> 请求示例：单个
    
    
    {
        "op": "subscribe",
        "args": [{
            "channel": "account-greeks",
            "ccy": "BTC"
        }]
    }
    

> 请求示例
    
    
    {
        "op": "subscribe",
        "args": [{
            "channel": "account-greeks"
        }]
    }
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
op | String | 是 | 操作，`subscribe` `unsubscribe`  
args | Array | 是 | 请求订阅的频道列表  
> channel | String | 是 | 频道名，`account-greeks`  
> ccy | String | 否 | 币种  
  
> 成功返回示例：单个
    
    
    {
        "event": "subscribe",
        "arg": {
            "channel": "account-greeks",
            "ccy": "BTC"
        }
    }
    

> 成功返回示例
    
    
    {
        "event": "subscribe",
        "arg": {
            "channel": "account-greeks"
        }
    }
    

> 失败返回示例
    
    
    {
        "event": "error",
        "code": "60012",
        "msg": "Unrecognized request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"account-greeks\", \"ccy\" : \"BTC\"}]}"
    }
    

#### 返回参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
event | String | 是 | 操作，`subscribe` `unsubscribe` `error`  
arg | Object | 否 | 订阅的频道  
> channel | String | 是 | 频道名，`account-greeks`  
> ccy | String | 否 | 币种  
code | String | 否 | 错误码  
msg | String | 否 | 错误消息  
  
> 推送示例：单个
    
    
    {
      "arg": {
        "channel": "account-greeks",
        "uid": "77982378738415879",
        "ccy": "BTC"
      },
      "data": [
        {           
          "thetaBS": "",
          "thetaPA":"",
          "deltaBS":"",
          "deltaPA":"",
          "gammaBS":"",
          "gammaPA":"",
          "vegaBS":"",    
          "vegaPA":"",
          "ccy":"BTC"，
          "ts":"1620282889345"
        }
      ]
    }
    

> 推送示例
    
    
    {
      "arg": {
        "channel": "account-greeks",
        "uid": "77982378738415879",
        "ccy": "BTC"
      },
      "data": [
        {           
          "thetaBS": "",
          "thetaPA":"",
          "deltaBS":"",
          "deltaPA":"",
          "gammaBS":"",
          "gammaPA":"",
          "vegaBS":"",    
          "vegaPA":"",
          "ccy":"BTC"，
          "ts":"1620282889345"
        },
        {           
          "thetaBS": "",
          "thetaPA":"",
          "deltaBS":"",
          "deltaPA":"",
          "gammaBS":"",
          "gammaPA":"",
          "vegaBS":"",    
          "vegaPA":"",
          "ccy":"USDT"，
          "ts":"1620282889345"
        }
      ]
    }
    

#### 推送数据参数

**参数名** | **类型** | **描述**  
---|---|---  
arg | Object | 请求订阅的频道  
> channel | String | 频道名  
> uid | String | 用户标识  
data | Array | 订阅的数据  
> deltaBS | String | 美金本位账户资产delta  
> deltaPA | String | 币本位账户资产delta  
> gammaBS | String | 美金本位账户资产gamma，仅适用于`期权`  
> gammaPA | String | 币本位账户资产gamma，仅适用于`期权`  
> thetaBS | String | 美金本位账户资产theta，仅适用于`期权`  
> thetaPA | String | 币本位账户资产theta，仅适用于`期权`  
> vegaBS | String | 美金本位账户资产vega，仅适用于`期权`  
> vegaPA | String | 币本位账户资产vega，仅适用于`期权`  
> ccy | String | 币种  
> ts | String | 获取greeks的时间，Unix时间戳的毫秒数格式，如 1597026383085  
  
首次推送，只推账户资产不为0的greeks数据。

定时推送，只推账户资产不为0的greeks数据。

例：按照所有币种订阅且有5个币种资产都不为0，首次和定时推全部5个；账户的某个币种资产改变，那么账户greeks变更的触发只推这一个。

## 公共频道

### 产品频道

首次订阅推送产品的全量数据；后续当有产品状态变化时（如期货交割、期权行权、新合约/币对上线、人工暂停/恢复交易等），推送产品的增量数据。

> 请求示例
    
    
    { 
      "op": "subscribe",  
      "args":   [    
        {     
          "channel" : "instruments",
          "instType": "FUTURES"
        }
      ] 
    }
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
op | String | 是 | 操作，`subscribe` `unsubscribe`  
args | Array | 是 | 请求订阅的频道列表  
> channel | String | 是 | 频道名，`instruments`  
> instType | String | 是 | 产品类型  
`SPOT`：币币  
`MARGIN`：币币杠杆  
`SWAP`：永续合约  
`FUTURES`：交割合约  
`OPTION`：期权  
  
> 成功返回示例
    
    
    {
        "event": "subscribe",
        "arg": {
            "channel": "instruments",
            "instType": "FUTURES"
        }
    }
    

> 失败返回示例
    
    
    {
        "event": "error",
        "code": "60012",
        "msg": "Unrecognized request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"instruments\", \"instType\" : \"FUTURES\"}]}"
    }
    

#### 返回参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
event | String | 是 | 事件，`subscribe` `unsubscribe` `error`  
arg | Object | 否 | 订阅的频道  
> channel | String | 是 | 频道名  
> instType | String | 是 | 产品类型  
`SPOT`：币币  
`MARGIN`：币币杠杆  
`SWAP`：永续合约  
`FUTURES`：交割合约  
`OPTION`：期权  
code | String | 否 | 错误码  
msg | String | 否 | 错误消息  
  
> 推送示例
    
    
    {
        "arg": {
            "channel": "instruments",
            "instType": "FUTURES"
        },
        "data": [{
            "instType": "FUTURES",
            "instId": "BTC-USD-191115",
            "uly": "BTC-USD",
            "category":"1",
            "baseCcy": "",
            "quoteCcy": "",
            "settleCcy": "BTC",
            "ctVal": "10",
            "ctMult": "1",
            "ctValCcy": "USD",
            "optType": "",
            "stk": "",
            "listTime": "",
            "expTime": "",
            "tickSz": "0.01",
            "lotSz": "1",
            "minSz": "1",
            "ctType": "linear",
            "alias": "this_week",
            "state": "live",
            "maxLmtSz":"10000",
            "maxMktSz":"99999",
            "maxTwapSz":"99999",
            "maxIcebergSz":"99999",
            "maxTriggerSz":"9999",
            "maxStopSz":"9999"
        }, {
            "instType": "FUTURES",
            "instId": "BTC-USD-201115",
            "uly": "BTC-USD",
            "category":"1",
            "baseCcy": "",
            "quoteCcy": "",
            "settleCcy": "BTC",
            "ctVal": "10",
            "ctMult":   "1",
            "ctValCcy": "USD",
            "optType": "",
            "stk": "",
            "listTime": "",
            "expTime": "",
            "tickSz": "0.01",
            "lotSz": "1",
            "minSz": "1",
            "ctType": "linear",
            "alias": "this_week",
            "state": "live",
            "maxLmtSz":"10000",
            "maxMktSz":"99999",
            "maxTwapSz":"99999",
            "maxIcebergSz":"99999",
            "maxTriggerSz":"9999",
            "maxStopSz":"9999"
        }]
    }
    

#### 推送数据参数

参数名 | 类型 | 描述  
---|---|---  
arg | Object | 订阅的频道  
> channel | String | 频道名  
> instType | String | 产品类型  
data | Array | 订阅的数据  
> instType | String | 产品类型  
> instId | String | 产品ID，如 `BTC-USD-SWAP`  
> category | String | 手续费档位，每个交易产品属于哪个档位手续费  
> uly | String | 标的指数，如 `BTC-USD` ，仅适用于`交割/永续/期权`  
> baseCcy | String | 交易货币币种，如 `BTC-USDT` 中`BTC` ，仅适用于`币币`  
> quoteCcy | String | 计价货币币种，如 `BTC-USDT` 中 `USDT` ，仅适用于`币币`  
> settleCcy | String | 盈亏结算和保证金币种，如 `BTC` ，仅适用于 `交割/永续/期权`  
> ctVal | String | 合约面值  
> ctMult | String | 合约乘数  
> ctValCcy | String | 合约面值计价币种  
> optType | String | 期权类型，`C`：看涨期权 `P`：看跌期权 ，仅适用于`期权`  
> stk | String | 行权价格， 仅适用于`期权`  
> listTime | String | 上线日期， 仅适用于 `交割/永续/期权`  
> expTime | String | 交割日期， 仅适用于 `交割/期权`  
> lever | String | 该`instId`支持的最大杠杆倍数，不适用于`币币`、`期权`  
> tickSz | String | 下单价格精度，如 `0.0001`  
> lotSz | String | 下单数量精度，如 `1`：BTC-USDT-200925 `0.001`：BTC-USDT  
> minSz | String | 最小下单数量  
> ctType | String | 合约类型，`linear`：正向合约 `inverse`：反向合约 ，仅适用于 `交割/永续`  
> alias | String | 合约日期别名  
`this_week`：本周  
`next_week`：次周  
`quarter`：季度  
`next_quarter`：次季度  
  
仅适用于`交割`  
> state | String | 产品状态  
`live`：交易中  
`suspend`：暂停中  
`expired`：已过期  
`preopen`：预上线  
`settlement`：资金费结算  
> maxLmtSz | String | 合约或现货限价单的单笔最大委托数量  
> maxMktSz | String | 合约或现货市价单的单笔最大委托数量  
> maxTwapSz | String | 合约或现货时间加权单的单笔最大委托数量  
> maxIcebergSz | String | 合约或现货冰山委托的单笔最大委托数量  
> maxTriggerSz | String | 合约或现货计划委托委托的单笔最大委托数量  
> maxStopSz | String | 合约或现货止盈止损委托的单笔最大委托数量  
产品状态变更，是触发instrument接口推送条件： 当有系统升级，或者产品升级，或者故障问题时，产品的状态变更为暂停中；
当恢复时，状态变更为交易中；当合约预上线时，状态变更为预上线（即新生成一个合约，新合约会处于预上线状态）；
当产品下线的时候（如交割合约被交割的时候，期权合约被行权的时候），状态变更为已过期

### 行情频道

获取产品的最新成交价、买一价、卖一价和24小时交易量等信息，每100ms有成交就推送一次数据。

> 请求示例
    
    
    {
        "op": "subscribe",
        "args": [{
            "channel": "tickers",
            "instId": "LTC-USD-200327"
        }]
    }
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
op | String | 是 | 操作，`subscribe` `unsubscribe`  
args | Array | 是 | 请求订阅的频道列表  
> channel | String | 是 | 频道名，`tickers`  
> instId | String | 是 | 产品ID  
  
> 成功返回示例
    
    
    {
        "event": "subscribe",
        "arg": {
            "channel": "tickers",
            "instId": "LTC-USD-200327"
        }
    }
    

> 失败返回示例
    
    
    {
        "event": "error",
        "code": "60012",
        "msg": "Unrecognized request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"tickers\", \"instId\" : \"LTC-USD-200327\"}]}"
    }
    

#### 返回参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
event | String | 是 | 事件，`subscribe` `unsubscribe` `error`  
arg | Object | 否 | 订阅的频道  
> channel | String | 是 | 频道名  
> instId | String | 是 | 产品ID  
code | String | 否 | 错误码  
msg | String | 否 | 错误消息  
  
> 推送示例
    
    
    {
        "arg": {
            "channel": "tickers",
            "instId": "LTC-USD-200327"
        },
        "data": [{
            "instType": "SWAP",
            "instId": "LTC-USD-SWAP",
            "last": "9999.99",
            "lastSz": "0.1",
            "askPx": "9999.99",
            "askSz": "11",
            "bidPx": "8888.88",
            "bidSz": "5",
            "open24h": "9000",
            "high24h": "10000",
            "low24h": "8888.88",
            "volCcy24h": "2222",
            "vol24h": "2222",
            "sodUtc0": "2222",
            "sodUtc8": "2222",
            "ts": "1597026383085"
        }]
    }
    

#### 推送数据参数

**参数名** | **类型** | **描述**  
---|---|---  
arg | Object | 订阅成功的频道  
> channel | String | 频道名  
> instId | String | 产品ID  
data | Array | 订阅的数据  
instType | String | 产品类型  
instId | String | 产品ID  
last | String | 最新成交价  
lastSz | String | 最新成交的数量  
askPx | String | 卖一价  
askSz | String | 卖一价对应的量  
bidPx | String | 买一价  
bidSz | String | 买一价对应的数量  
open24h | String | 24小时开盘价  
high24h | String | 24小时最高价  
low24h | String | 24小时最低价  
volCcy24h | String | 24小时成交量，以`币`为单位  
如果是`衍生品`合约，数值为交易货币的数量。  
如果是`币币/币币杠杆`，数值为计价货币的数量。  
vol24h | String | 24小时成交量，以`张`为单位  
如果是`衍生品`合约，数值为合约的张数。  
如果是`币币/币币杠杆`，数值为交易货币的数量。  
sodUtc0 | String | UTC 0 时开盘价  
sodUtc8 | String | UTC+8 时开盘价  
ts | String | 数据产生时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
  
### 持仓总量频道

获取持仓总量，每3s有数据更新推送一次数据

> 请求示例
    
    
    {
        "op": "subscribe",
        "args": [{
            "channel": "open-interest",
            "instId": "LTC-USD-SWAP"
        }]
    }
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
op | String | 是 | 操作，`subscribe` `unsubscribe`  
args | Array | 是 | 请求订阅的频道列表  
> channel | String | 是 | 频道名，`open-interest`  
> instId | String | 是 | 产品ID  
  
> 成功返回示例
    
    
    {
        "event": "subscribe",
        "arg": [{
            "channel": "open-interest",
            "instId": "LTC-USD-SWAP"
        }]
    }
    

> 失败返回示例
    
    
    {
        "event": "error",
        "code": "60012",
        "msg": "Unrecognized request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"open-interest\", \"instId\" : \"LTC-USD-SWAP\"}]}"
    }
    

#### 返回参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
event | String | 是 | 事件，`subscribe` `unsubscribe` `error`  
arg | Object | 否 | 订阅的频道  
> channel | String | 是 | 频道名  
> instId | String | 是 | 产品ID  
code | String | 否 | 错误码  
msg | String | 否 | 错误消息  
  
> 推送示例
    
    
    {
        "arg": {
            "channel": "open-interest",
            "instId": "LTC-USD-SWAP"
        },
        "data": [{
            "instType": "SWAP",
            "instId": "LTC-USD-SWAP",
            "oi": "5000",
            "oiCcy": "555.55",
            "ts": "1597026383085"
        }]
    }
    

#### 推送数据参数

**参数名** | **类型** | **描述**  
---|---|---  
arg | Object | 订阅成功的频道  
> channel | String | 频道名  
> instId | String | 产品ID  
data | Array | 订阅的数据  
> instType | String | 产品类型  
> instId | String | 产品ID，如 `BTC-USD-18021`  
> oi | String | 持仓量，按张为单位，open interest  
> oiCcy | String | 持仓量，按币为单位  
> ts | String | 数据更新的时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
  
### K线频道

获取K线数据，推送频率最快是间隔500ms推送一次数据。

> 请求示例
    
    
    {
        "op": "subscribe",
        "args": [{
            "channel": "candle1D",
            "instId": "BTC-USDT"
        }]
    }
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
op | String | 是 | 操作，`subscribe` `unsubscribe`  
args | Array | 是 | 请求订阅的频道列表  
> channel | String | 是 | 频道名，  
`candle1Y`  
`candle6M` `candle3M` `candle1M`  
`candle1W`  
`candle1D` `candle2D` `candle3D` `candle5D`  
`candle12H` `candle6H` `candle4H` `candle2H` `candle1H`  
`candle30m` `candle15m` `candle5m` `candle3m` `candle1m`  
`candle1Yutc` `candle3Mutc` `candle1Mutc` `candle1Wutc` `candle1Dutc`
`candle2Dutc` `candle3Dutc` `candle5Dutc` `candle12Hutc` `candle6Hutc`  
> instId | String | 是 | 产品ID  
  
> 成功返回示例
    
    
    {
        "event": "subscribe",
        "arg": {
            "channel": "candle1D",
            "instId": "BTC-USDT"
        }
    }
    

> 失败返回示例
    
    
    {
        "event": "error",
        "code": "60012",
        "msg": "Unrecognized request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"candle1D\", \"instId\" : \"BTC-USD-191227\"}]}"
    }
    

#### 返回参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
event | String | 是 | 事件，`subscribe` `unsubscribe` `error`  
arg | Object | 否 | 订阅的频道  
> channel | String | 是 | 频道名  
> instId | String | 是 | 产品ID  
code | String | 否 | 错误码  
msg | String | 否 | 错误消息  
  
> 推送示例
    
    
    {
      "arg": {
        "channel": "candle1D",
        "instId": "BTC-USDT"
      },
      "data": [
        [
          "1629993600000",
          "42500",
          "48199.9",
          "41006.1",
          "41006.1",
          "3587.41204591",
          "166741046.22583129"
        ]
      ]
    }
    

#### 推送数据参数

**参数名** | **类型** | **描述**  
---|---|---  
arg | Object | 订阅成功的频道  
> channel | String | 频道名  
> instId | String | 产品ID  
data | Array | 订阅的数据  
> ts | String | 开始时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
> o | String | 开盘价格  
> h | String | 最高价格  
> l | String | 最低价格  
> c | String | 收盘价格  
> vol | String | 交易量，以`张`为单位  
如果是`衍生品`合约，数值为合约的张数。  
如果是`币币/币币杠杆`，数值为交易货币的数量。  
> volCcy | String | 交易量，以`币`为单位  
如果是`衍生品`合约，数值为交易货币的数量。  
如果是`币币/币币杠杆`，数值为计价货币的数量。  
  
### 交易频道

获取最近的成交数据，有成交数据就推送

> 请求示例
    
    
    {
        "op": "subscribe",
        "args": [{
            "channel": "trades",
            "instId": "BTC-USDT"
        }]
    }
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
op | String | 是 | 操作，`subscribe` `unsubscribe`  
args | Array | 是 | 请求订阅的频道列表  
> channel | String | 是 | 频道名，`trades`  
> instId | String | 是 | 产品ID  
  
> 成功返回示例
    
    
    {
        "event": "subscribe",
        "arg": {
            "channel": "trades",
            "instId": "BTC-USDT"
        }
    }
    

> 失败返回示例
    
    
    {
        "event": "error",
        "code": "60012",
        "msg": "Unrecognized request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"trades\", \"instId\" : \"BTC-USD-191227\"}]}"
    }
    

#### 返回参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
event | String | 是 | 事件，`subscribe` `unsubscribe` `error`  
arg | Object | 否 | 订阅的频道  
> channel | String | 是 | 频道名  
> instId | String | 是 | 产品ID  
code | String | 否 | 错误码  
msg | String | 否 | 错误消息  
  
> 推送示例
    
    
    {
      "arg": {
        "channel": "trades",
        "instId": "BTC-USDT"
      },
      "data": [
        {
          "instId": "BTC-USDT",
          "tradeId": "130639474",
          "px": "42219.9",
          "sz": "0.12060306",
          "side": "buy",
          "ts": "1630048897897"
        }
      ]
    }
    

#### 推送数据参数

**参数名** | **类型** | **描述**  
---|---|---  
arg | Object | 订阅成功的频道  
> channel | String | 频道名  
> instId | String | 产品ID  
data | Array | 订阅的数据  
> instId | String | 产品ID，如 `BTC-USD-180216`  
> tradeId | String | 成交ID  
> px | String | 成交价格  
> sz | String | 成交数量  
> side | String | 成交方向，`buy` `sell`  
> ts | String | 成交时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
  
### 预估交割/行权价格频道

获取交割合约和期权预估交割/行权价。交割/行权预估价只有交割/行权前一小时开始推送预估交割/行权价，有价格变化就推送

> 请求示例
    
    
    {
        "op": "subscribe",
        "args": [{
            "channel": "estimated-price",
            "instType": "FUTURES",
            "uly": "BTC-USD"
        }]
    }
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
op | String | 是 | 操作，`subscribe` `unsubscribe`  
args | Array | 是 | 请求订阅的频道列表  
> channel | String | 是 | 频道名，`estimated-price`  
> instType | String | 是 | 产品类型  
`FUTURES`：交割合约  
`OPTION`：期权  
`SWAP`：永续  
> uly | String | 可选 | 标的指数  
`uly`和`instId`必须指定一个  
> instId | String | 可选 | 产品ID  
  
> 成功返回示例
    
    
    {
        "event": "subscribe",
        "arg": {
            "channel": "estimated-price",
            "instType": "FUTURES",
            "uly": "BTC-USD"
        }
    }
    

> 失败返回示例
    
    
    {
        "event": "error",
        "code": "60012",
        "msg": "Unrecognized request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"estimated-price\", \"instId\" : \"FUTURES\",\"uly\" :\"BTC-USD\"}]}"
    }
    

#### 返回参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
event | String | 是 | 事件，`subscribe` `unsubscribe` `error`  
arg | Object | 否 | 订阅的频道  
> channel | String | 是 | 频道名  
> instType | String | 是 | 产品类型  
`FUTURES`：交割合约  
`OPTION`：期权  
`SWAP`：永续  
> uly | String | 否 | 标的指数  
> instId | String | 否 | 产品ID  
code | String | 否 | 错误码  
msg | String | 否 | 错误消息  
  
> 推送示例
    
    
    {
        "arg": {
            "args": "estimated-price",
            "instType": "FUTURES",
            "uly": "BTC-USD"
        },
        "data": [{
            "instType": "FUTURES",
            "instId": "BTC-USD-170310",
            "settlePx": "200",
            "ts": "1597026383085"
        }]
    }
    

#### 推送数据参数

**参数名** | **类型** | **描述**  
---|---|---  
arg | Object | 订阅成功的频道  
> channel | String | 频道名  
> instType | String | 产品类型  
`OPTION`：期权  
`FUTURES`：交割  
`SWAP`：永续  
> uly | String | 标的指数  
> instId | String | 产品ID  
data | Array | 订阅的数据  
> instType | String | 产品类型  
> instId | String | 产品ID，如 `BTC-USD-170310`  
> settlePx | String | 预估交割/行权价  
> ts | String | 数据更新时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
  
### 标记价格频道

获取标记价格，标记价格有变化时，每200ms推送一次数据，标记价格没变化时，每10s推送一次数据

> 请求示例
    
    
    {
        "op": "subscribe",
        "args": [{
            "channel": "mark-price",
            "instId": "BTC-USDT"
        }]
    }
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
op | String | 是 | 操作，`subscribe` `unsubscribe`  
args | Array | 是 | 请求订阅的频道列表  
> channel | String | 是 | 频道名，`mark-price`  
> instId | String | 是 | 产品ID  
  
> 成功返回示例
    
    
    {
        "event": "subscribe",
        "arg": {
            "channel": "mark-price",
            "instId": "BTC-USDT"
        }
    }
    

> 失败返回示例
    
    
    {
        "event": "error",
        "code": "60012",
        "msg": "Unrecognized request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"mark-price\", \"instId\" : \"LTC-USD-190628\"}]}"
    }
    

#### 返回参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
event | String | 是 | 事件，`subscribe` `unsubscribe` `error`  
arg | Object | 否 | 订阅的频道  
> channel | String | 是 | 频道名  
> instId | String | 否 | 产品ID  
code | String | 否 | 错误码  
msg | String | 否 | 错误消息  
  
> 推送示例
    
    
    {
      "arg": {
        "channel": "mark-price",
        "instId": "BTC-USDT"
      },
      "data": [
        {
          "instType": "MARGIN",
          "instId": "BTC-USDT",
          "markPx": "42310.6",
          "ts": "1630049139746"
        }
      ]
    }
    

#### 推送数据参数

参数名 | 类型 | 描述  
---|---|---  
arg | Object | 订阅成功的频道  
> channel | String | 频道名  
> instId | String | 产品ID  
data | Array | 订阅的数据  
> instType | String | 交易品种  
> instId | String | 产品ID  
> markPx | String | 标记价格  
> ts | String | 标记价格数据更新时间 ，Unix时间戳的毫秒数格式，如 `1597026383085`  
  
### 标记价格K线频道

获取标记价格的K线数据，每500ms推送一次数据

> 请求示例
    
    
    {
        "op": "subscribe",
        "args": [{
            "channel": "mark-price-candle1D",
            "instId": "BTC-USD-190628"
        }]
    }
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
op | String | 是 | 操作，`subscribe` `unsubscribe`  
args | Array | 是 | 请求订阅的频道列表  
> channel | String | 是 | 频道名  
`mark-price-candle1Y`  
`mark-price-candle6M`  
`mark-price-candle3M`  
`mark-price-candle1M`  
`mark-price-candle1W`  
`mark-price-candle1D`  
`mark-price-candle2D`  
`mark-price-candle3D`  
`mark-price-candle5D`  
`mark-price-candle12H`  
`mark-price-candle6H`  
`mark-price-candle4H`  
`mark-price-candle2H`  
`mark-price-candle1H`  
`mark-price-candle30m`  
`mark-price-candle15m`  
`mark-price-candle5m`  
`mark-price-candle3m`  
`mark-price-candle1m`  
`mark-price-candle1Yutc`  
`mark-price-candle3Mutc`  
`mark-price-candle1Mutc`  
`mark-price-candle1Wutc`  
`mark-price-candle1Dutc`  
`mark-price-candle2Dutc`  
`mark-price-candle3Dutc`  
`mark-price-candle5Dutc`  
`mark-price-candle12Hutc`  
`mark-price-candle6Hutc`  
> instId | String | 是 | 产品ID  
  
> 成功返回示例
    
    
    {
        "event": "subscribe",
        "arg": {
            "channel": "mark-price-candle1D",
            "instId": "BTC-USD-190628"
        }
    }
    
    

> 失败返回示例
    
    
    {
        "event": "error",
        "code": "60012",
        "msg": "Unrecognized request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"mark-price-candle1D\", \"instId\" : \"BTC-USD-190628\"}]}"
    }
    

#### 返回参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
event | String | 是 | 事件，`subscribe` `unsubscribe` `error`  
arg | Object | 否 | 订阅的频道  
> channel | String | 是 | 频道名  
> instId | String | 是 | 产品ID  
code | String | 否 | 错误码  
msg | String | 否 | 错误消息  
  
> 推送示例
    
    
    {
        "arg": {
            "channel": "mark-price-candle1D",
            "instId": "BTC-USD-190628"
        },
        "data": [
            ["1597026383085", "3.721", "3.743", "3.677", "3.708"],
            ["1597026383085", "3.731", "3.799", "3.494", "3.72"]
        ]
    }
    

#### 推送数据参数

参数名 | 类型 | 描述  
---|---|---  
arg | Object | 订阅成功的频道  
> channel | String | 频道名  
> instId | String | 产品ID  
data | Array | 订阅的数据  
> ts | String | 开始时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
> o | String | 开盘价格  
> h | String | 最高价格  
> l | String | 最低价格  
> c | String | 收盘价格  
  
### 限价频道

获取交易的最高买价和最低卖价。限价有变化时，每5秒推送一次数据，限价没变化时，不推送数据

> 请求示例
    
    
    {
        "op": "subscribe",
        "args": [{
            "channel": "price-limit",
            "instId": "LTC-USD-190628"
        }]
    }
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
op | String | 是 | 操作，`subscribe` `unsubscribe`  
args | Array | 是 | 请求订阅的频道列表  
> channel | String | 是 | 频道名，`price-limit`  
> instId | String | 是 | 产品ID  
  
> 成功返回示例
    
    
    {
        "event": "subscribe",
        "arg": {
            "channel": "price-limit",
            "instId": "LTC-USD-190628"
        }
    }
    

> 失败返回示例
    
    
    {
        "event": "error",
        "code": "60012",
        "msg": "Unrecognized request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"price-limit\", \"instId\" : \"LTC-USD-190628\"}]}"
    }
    

#### 返回参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
event | String | 是 | 事件，`subscribe` `unsubscribe` `error`  
arg | Object | 否 | 订阅的频道  
> channel | String | 是 | 频道名  
> instId | String | 是 | 产品ID  
code | String | 否 | 错误码  
msg | String | 否 | 错误消息  
  
> 推送示例
    
    
    {
        "arg": {
            "channel": "price-limit",
            "instId": "LTC-USD-190628"
        },
        "data": [{
            "instId": "LTC-USD-190628",
            "buyLmt": "200",
            "sellLmt": "300",
            "ts": "1597026383085"
        }]
    }
    

#### 推送数据参数

**参数名** | **类型** | **描述**  
---|---|---  
arg | Object | 订阅成功的频道  
> channel | String | 频道名  
> instId | String | 产品ID  
data | Array | 订阅的数据  
> instType | String | 产品类型  
> instId | String | 产品ID，如 `BTC-USD-SWAP`  
> buyLmt | String | 最高买价  
> sellLmt | String | 最低卖价  
> ts | String | 数据更新时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
  
### 深度频道

获取深度数据，`books`是400档频道，`books5`是5档频道， `bbo-
tbt`是先1档后实时推送的频道，`books-l2-tbt`是先400档后实时推送的频道，`books50-l2-tbt`是先50档后实时推的频道；

`books` 首次推400档快照数据，以后增量推送，即每100毫秒有深度变化推送一次变化的数据  
`books5`首次推5档快照数据，以后定量推送，每100毫秒有深度变化推送一次5档数据，即每次都推送5档数据  
`bbo-tbt` 首次推1档快照数据，以后定量推送，每10毫秒有深度变化推送一次1档数据，即每次都推送1档数据  
`books-l2-tbt` 首次推400档快照数据，以后增量推送，即每10毫秒有深度有变化推送一次变化的数据  
`books50-l2-tbt` 首次推50档快照数据，以后增量推送，即每10毫秒有深度有变化推送一次变化的数据。若`asks` 和 `bids`
为空数组，那说明50档没有变化，仅代表400档内有变化，若您在本地维护深度数据，请您忽略这样的数据。

books-l2-tbt400档深度频道，只允许交易手续费等级VIP5及以上的API用户订阅。  
books50-l2-tbt50档深度频道，只允许交易手续费等级VIP4及以上的API用户订阅.  

身份认证参考[登录](/docs-v5/zh/#websocket-api-login)功能

> 请求示例
    
    
    {
        "op": "subscribe",
        "args": [{
            "channel": "books",
            "instId": "BTC-USDT"
        }]
    }
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
op | String | 是 | 操作，`subscribe` `unsubscribe`  
args | Array | 是 | 请求订阅的频道列表  
> channel | String | 是 | 频道名，`books` `books5` `books-l2-tbt` `books50-l2-tbt`  
> instId | String | 是 | 产品ID  
  
> 返回示例
    
    
    {
        "event": "subscribe",
        "arg": {
            "channel": "books",
            "instId": "BTC-USDT"
        }
    }
    

> 失败示例
    
    
    {
        "event": "error",
        "code": "60012",
        "msg": "Unrecognized request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"books\", \"instId\" : \"BTC-USD-191227\"}]}"
    }
    

#### 返回参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
event | String | 是 | 事件，`subscribe` `unsubscribe` `error`  
arg | Object | 否 | 订阅的频道  
> channel | String | 是 | 频道名  
> instId | String | 是 | 产品ID  
msg | String | 否 | 错误消息  
code | String | 否 | 错误码  
  
> 推送示例 ：全量
    
    
    {
        "arg": {
            "channel": "books",
            "instId": "BTC-USDT"
        },
        "action": "snapshot",
        "data": [{
            "asks": [
                ["8476.98", "415", "0", "13"],
                ["8477", "7", "0", "2"],
                ["8477.34", "85", "0", "1"],
                ["8477.56", "1", "0", "1"],
                ["8505.84", "8", "0", "1"],
                ["8506.37", "85", "0", "1"],
                ["8506.49", "2", "0", "1"],
                ["8506.96", "100", "0", "2"]
            ],
            "bids": [
                ["8476.97", "256", "0", "12"],
                ["8475.55", "101", "0", "1"],
                ["8475.54", "100", "0", "1"],
                ["8475.3", "1", "0", "1"],
                ["8447.32", "6", "0", "1"],
                ["8447.02", "246", "0", "1"],
                ["8446.83", "24", "0", "1"],
                ["8446", "95", "0", "3"]
            ],
            "ts": "1597026383085",
            "checksum": -855196043
        }]
    }
    

> 推送示例：增量
    
    
    {
        "arg": {
            "channel": "books",
            "instId": "BTC-USDT"
        },
        "action": "update",
        "data": [{
            "asks": [
                ["8476.98", "415", "0", "13"],
                ["8477", "7", "0", "2"],
                ["8477.34", "85", "0", "1"],
                ["8477.56", "1", "0", "1"],
                ["8505.84", "8", "0", "1"],
                ["8506.37", "85", "0", "1"],
                ["8506.49", "2", "0", "1"],
                ["8506.96", "100", "0", "2"]
            ],
            "bids": [
                ["8476.97", "256", "0", "12"],
                ["8475.55", "101", "0", "1"],
                ["8475.54", "100", "0", "1"],
                ["8475.3", "1", "0", "1"],
                ["8447.32", "6", "0", "1"],
                ["8447.02", "246", "0", "1"],
                ["8446.83", "24", "0", "1"],
                ["8446", "95", "0", "3"]
            ],
            "ts": "1597026383085",
            "checksum": -855196043
        }]
    }
    

#### 推送数据参数

**参数名** | **类型** | **描述**  
---|---|---  
arg | Object | 订阅成功的频道  
> channel | String | 频道名  
> instId | String | 产品ID  
action | String | 推送数据动作，增量推送数据还是全量推送数据  
`snapshot`：全量  
`update`：增量  
data | Array | 订阅的数据  
> asks | Array | 卖方深度  
> bids | Array | 买方深度  
> ts | String | 数据更新时间戳，Unix时间戳的毫秒数格式，如 `1597026383085`  
> checksum | Integer | 检验和  
合约的asks和bids值数组举例说明： ["411.8","10", "0","4"]
411.8为深度价格，10为此价格的合约张数，0该字段已弃用(始终为0)，4为此价格的订单数量  
现货/币币杠杆的asks和bids值数组举例说明： ["411.8","10", "0","4"]
411.8为深度价格，10为此价格的币的数量，0该字段已弃用(始终为0)，4为此价格的订单数量

### 期权定价频道

获取所有期权合约详细定价信息，一次性推送所有

> 请求示例
    
    
    {
        "op": "subscribe",
        "args": [{
            "channel": "opt-summary",
            "uly": "BTC-USD"
        }]
    }
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
op | String | 是 | 操作，`subscribe` `unsubscribe`  
args | Array | 是 | 请求订阅的频道列表  
> channel | String | 是 | 频道名，`opt-summary`  
> uly | String | 是 | 标的指数  
  
> 返回示例
    
    
    {
        "event": "subscribe",
        "arg": {
            "channel": "opt-summary",
            "uly": "BTC-USD"
        }
    }
    

> 失败示例
    
    
    {
        "event": "error",
        "code": "60012",
        "msg": "Unrecognized request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"opt-summary\", \"uly\" : \"BTC-USD\"}]}"
    }
    

#### 返回参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
event | String | 是 | 事件，`subscribe` `unsubscribe` `error`  
arg | Object | 否 | 订阅的频道  
> channel | String | 是 | 频道名  
> uly | String | 是 | 标的指数  
code | String | 否 | 错误码  
msg | String | 否 | 错误消息  
  
> 推送示例
    
    
    {
        "arg": {
            "channel": "opt-summary",
            "uly": "BTC-USD"
        },
        "data": [{
            "instType": "OPTION",
            "instId": "BTC-USD-200103-5500-C",
            "uly": "BTC-USD",
            "delta": "0.7494223636",
            "gamma": "-0.6765419039",
            "theta": "-0.0000809873",
            "vega": "0.0000077307",
            "deltaBS": "0.7494223636",
            "gammaBS": "-0.6765419039",
            "thetaBS": "-0.0000809873",
            "vegaBS": "0.0000077307",
            "realVol": "0",
            "bidVol": "",
            "askVol": "1.5625",
            "markVol": "0.9987",
            "lever": "4.0342",
            "fwdPx": "4.0342",
            "ts": "1597026383085"
        }]
    }
    

#### 推送数据参数

**参数名** | **类型** | **描述**  
---|---|---  
arg | Object | 订阅成功的频道  
> channel | String | 频道名  
> uly | String | 标的指数  
data | Array | 订阅的数据  
> instType | String | 产品类型， `OPTION`  
> instId | String | 产品ID  
> uly | String | 标的指数  
> delta | String | 期权价格对`uly`价格的敏感度  
> gamma | String | delta对`uly`价格的敏感度  
> vega | String | 期权价格对隐含波动率的敏感度  
> theta | String | 期权价格对剩余期限的敏感度  
> deltaBS | String | BS模式下期权价格对`uly`价格的敏感度  
> gammaBS | String | BS模式下delta对`uly`价格的敏感度  
> vegaBS | String | BS模式下期权价格对隐含波动率的敏感度  
> thetaBS | String | BS模式下期权价格对剩余期限的敏感度  
> lever | String | 杠杆倍数  
> markVol | String | 标记波动率  
> bidVol | String | bid波动率  
> askVol | String | ask波动率  
> realVol | String | 已实现波动率，目前该字段暂未启用  
> fwdPx | String | 远期价格  
> ts | String | 数据更新时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
  
### 资金费率频道

获取永续合约资金费率，30秒到90秒内推送一次数据

> 请求示例
    
    
    {
        "op": "subscribe",
        "args": [{
            "channel": "funding-rate",
            "instId": "BTC-USD-SWAP"
        }]
    }
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
op | String | 是 | 操作，`subscribe` `unsubscribe`  
args | Array | 是 | 请求订阅的频道列表  
> channel | String | 是 | 频道名，`funding-rate`  
> instId | String | 是 | 产品ID  
  
> 成功返回示例
    
    
    {
        "event": "subscribe",
        "arg": {
            "channel": "funding-rate",
            "instId": "BTC-USD-SWAP"
        }
    }
    

> 失败返回示例
    
    
    {
        "event": "error",
        "code": "60012",
        "msg": "Unrecognized request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"funding-rate\", \"instId\" : \"BTC-USD-SWAP\"}]}"
    }
    

#### 返回参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
event | String | 是 | 事件，`subscribe` `unsubscribe` `error`  
arg | Object | 否 | 订阅的频道  
> channel | String | 是 | 频道名  
> instId | String | 否 | 产品ID  
code | String | 否 | 错误码  
msg | String | 否 | 错误消息  
  
> 推送示例
    
    
    {
        "arg": {
            "channel": "funding-rate",
            "instId": "BTC-USD-SWAP"
        },
        "data": [{
            "instType": "SWAP",
            "instId": "BTC-USD-SWAP",
            "fundingRate": "0.018",
            "nextFundingRate": "",
            "fundingTime": "1597026383085"
        }]
    }
    

#### 推送数据参数

**参数名** | **类型** | **描述**  
---|---|---  
arg | Object | 订阅成功的频道  
> channel | String | 频道名  
> instId | String | 产品ID  
data | Array | 订阅的数据  
> instType | String | 产品类型，`SWAP`  
> instId | String | 产品ID，如 `BTC-USD-SWAP`  
> fundingRate | String | 资金费率  
> nextFundingRate | String | 下一期预测资金费率  
> fundingTime | String | 最新的到期结算的资金费时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
  
### 指数K线频道

获取指数的K线数据，推送频率最快是间隔500ms推送一次数据。

> 请求示例
    
    
    {
        "op": "subscribe",
        "args": [{
            "channel": "index-candle30m",
            "instId": "BTC-USD"
        }]
    }
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
op | String | 是 | 操作，`subscribe` `unsubscribe`  
args | Array | 是 | 请求订阅的频道列表  
> channel | String | 是 | 频道名，  
`index-candle1Y`  
`index-candle6M`  
`index-candle3M`  
`index-candle1M`  
`index-candle1W`  
`index-candle1D`  
`index-candle2D`  
`index-candle3D`  
`index-candle5D`  
`index-candle12H`  
`index-candle6H`  
`index-candle4H`  
`index -candle2H`  
`index-candle1H`  
`index-candle30m`  
`index-candle15m`  
`index-candle5m`  
`index-candle3m`  
`index-candle1m`  
`index-candle1Yutc`  
`index-candle3Mutc`  
`index-candle1Mutc`  
`index-candle1Wutc`  
`index-candle1Dutc`  
`index-candle2Dutc`  
`index-candle3Dutc`  
`index-candle5Dutc`  
`index-candle12Hutc`  
`index-candle6Hutc`  
> instId | String | 是 | 现货指数，如 `BTC-USD`  
  
> 成功返回示例
    
    
    {
        "event": "subscribe",
        "arg": {
            "channel": "index-candle30m",
            "instId": "BTC-USD"
        }
    }
    

> 失败返回示例
    
    
    {
        "event": "error",
        "code": "60012",
        "msg": "Unrecognized request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"index-candle30m\", \"instId\" : \"BTC-USD\"}]}"
    }
    

#### 返回参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
event | String | 是 | `subscribe` `unsubscribe`  
arg | Object | 否 | 订阅的频道  
> channel | String | 是 | 频道名  
> instId | String | 否 | 现货指数  
code | String | 否 | 错误码  
msg | String | 否 | 错误消息  
  
> 推送示例
    
    
    {
        "arg": {
            "channel": "index-candle30m",
            "instId": "BTC-USD"
        },
        "data": [
            ["1597026383085", "3811.31", "3811.31", "3811.31", "3811.31"]
        ]
    }
    

#### 推送数据参数

参数名 | 类型 | 描述  
---|---|---  
arg | Object | 订阅成功的频道  
> channel | String | 频道名  
> instId | String | 现货指数  
data | Array | 订阅的数据  
> ts | String | 开始时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
> o | String | 开盘价格  
> h | String | 最高价格  
> l | String | 最低价格  
> c | String | 收盘价格  
返回值数组顺分别为是：[ts,o,h,l,c]

### 指数行情频道

获取指数的行情数据。每100ms有变化就推送一次数据，否则一分钟推一次。

> 请求示例
    
    
    {
        "op": "subscribe",
        "args": [{
            "channel": "index-tickers",
            "instId": "BTC-USDT"
        }]
    }
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
op | String | 是 | `subscribe` `unsubscribe`  
args | Array | 是 | 请求订阅的频道列表  
> channel | String | 是 | 频道名，`index-tickers`  
> instId | String | 是 | 指数  
  
> 成功返回示例
    
    
    {
        "event": "subscribe",
        "arg": {
            "channel": "index-tickers",
            "instId": "BTC-USDT"
        }
    }
    

> 失败返回示例
    
    
    {
        "event": "error",
        "code": "60012",
        "msg": "Unrecognized request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"index-tickers\", \"instId\" : \"BTC-USDT\"}]}"
    }
    

#### 返回参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
event | String | 是 | `subscribe` `unsubscribe` `error`  
arg | Object | 否 | 订阅的频道  
> channel | String | 是 | 频道名，`index-tickers`  
> instId | String | 否 | 产品ID  
code | String | 否 | 错误码  
msg | String | 否 | 错误消息  
  
> 推送示例
    
    
    {
        "arg": {
            "channel": "index-tickers",
            "instId": "BTC-USDT"
        },
        "data": [{
            "instId": "BTC-USDT",
            "idxPx": "0.1",
            "high24h": "0.5",
            "low24h": "0.1",
            "open24h": "0.1",
            "sodUtc0": "0.1",
            "sodUtc8": "0.1",
            "ts": "1597026383085"
        }]
    }
    

#### 推送数据参数

参数名 | 类型 | 描述  
---|---|---  
arg | Object | 订阅成功的频道  
> channel | String | 频道名  
> instId | String | 产品ID  
data | Array | 订阅的数据  
> instId | String | 指数，以USD、USDT、BTC 为计价货币的指数，如 `BTC-USDT`  
> idxPx | String | 最新指数价格  
> open24h | String | 24小时开盘价  
> high24h | String | 24小时指数最高价格  
> low24h | String | 24小时指数最低价格  
>sodUtc0 | String | UTC 0 时开盘价  
>sodUtc8 | String | UTC+8 时开盘价  
> ts | String | 指数价格更新时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
  
### Status 频道

获取系统维护的状态，当系统维护状态改变时推送。首次订阅：”推送最新一条的变化数据“；后续每次有状态变化，推送变化的内容。

> 请求示例
    
    
    {
        "op": "subscribe",
        "args": [{
            "channel": "status"
        }]
    }
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
op | String | 是 | 操作，`subscribe` `unsubscribe`  
args | Array | 是 | 请求订阅的频道列表  
> channel | String | 是 | 频道名, `status`  
  
> 成功返回示例
    
    
    {
        "event": "subscribe",
        "arg": {
            "channel": "status"
        }
    }
    
    

> 失败返回示例
    
    
    {
        "event": "error",
        "code": "60012",
        "msg": "Unrecognized request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"statuss\"}]}"
    }
    

#### 返回参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
event | String | 是 | 事件，`subscribe` `unsubscribe` `error`  
arg | Object | 否 | 订阅的频道  
> channel | String | 是 | 频道名  
code | String | 否 | 错误码  
msg | String | 否 | 错误消息  
  
> 推送示例
    
    
    {
        "arg": {
            "channel": "status"
        },
        "data": [{
            "title": "Spot System Upgrade",
            "state": "scheduled",
            "begin": "1610019546",
            "href": "",
            "end": "1610019546",
            "serviceType": "1",
            "system": "classic",
            "scheDesc": "",
            "ts": "1597026383085"
        }]
    }
    

#### 推送数据参数

参数名 | 类型 | 描述  
---|---|---  
arg | Object | 订阅成功的频道  
> channel | String | 频道名  
data | Array | 订阅的数据  
> title | String | 系统维护说明的标题  
> state | String | 系统维护的状态，`scheduled`：等待中 ; `ongoing`：进行中 ; `completed`：已完成 ;
> `canceled`：已取消  
> begin | String | 系统维护的开始时间,Unix时间戳的毫秒数格式 如：`1617788463867`  
> end | String | 系统维护的结束时间,Unix时间戳的毫秒数格式 如：`1617788463867`  
> href | String | 系统维护详情的超级链接,若无返回值，默认值为空，如：“”  
> serviceType | String | 服务类型， `0`：WebSocket ; `1`：币币 ; `2`：交割 ; `3`：永续 ;
> `4`：期权 `5`：交易服务  
> system | String | 系统，`classic`：经典账户， `unified`：交易账户  
> scheDesc | String | 改期进度说明，如： `由 2021-01-26T16:30:00.000Z 改期到
> 2021-01-28T16:30:00.000Z`  
> ts | String | 推送时间，Unix时间戳的毫秒数格式，如：`1617788463867`  
  
# 错误码

## REST

REST API 错误码从 50000 到 59999

### 公共

错误码从 50000 到 53999

#### 通用类

错误提示 | HTTP 状态码 | 错误码  
---|---|---  
操作成功 | 200 | 0  
操作全部失败 | 200 | 1  
批量操作部分成功 | 200 | 2  
body不能为空 | 400 | 50000  
服务暂时不可用，请稍后重试 | 503 | 50001  
非法的json数据 | 400 | 50002  
接口请求超时（不代表请求成功或者失败，请检查请求结果） | 400 | 50004  
接口已下线或无法使用 | 410 | 50005  
无效的Content_Type，请使用"application/json"格式 | 400 | 50006  
用户被冻结 | 200 | 50007  
用户不存在 | 200 | 50008  
用户处于爆仓冻结 | 200 | 50009  
用户ID为空 | 200 | 50010  
用户请求频率过快，超过该接口允许的限额 | 429 | 50011  
用户状态无效 | 200 | 50012  
当前系统繁忙，请稍后重试 | 429 | 50013  
必填参数{0}不能为空 | 400 | 50014  
参数{0}和{1}不能同时为空 | 400 | 50015  
参数{0}和{1}不匹配 | 400 | 50016  
当前仓位处于ADL冻结中，无法进行相关操作 | 200 | 50017  
{0}币种处于ADL冻结中，无法进行相关操作 | 200 | 50018  
当前账户处于ADL冻结中，无法进行相关操作 | 200 | 50019  
当前仓位处于强平冻结中，无法进行相关操作 | 200 | 50020  
{0}币种处于强平冻结中，无法进行相关操作 | 200 | 50021  
当前账户处于强平冻结中，无法进行相关操作 | 200 | 50022  
资金费冻结，无法进行相关操作 | 200 | 50023  
参数{0}和{1}不能同时存在 | 200 | 50024  
参数{0}传值个数超过最大限制{1} | 200 | 50025  
系统错误，请稍后重试 | 500 | 50026  
当前账户已被限制交易 | 200 | 50027  
账户异常无法下单 | 200 | 50028  
你的账户已经触发风控体系，禁止该标的{0}交易，请联系客服进行处理 | 200 | 50029  
用户没有使用此API接口的权限 | 200 | 50030  
设置币种数量不能大于100个 | 200 | 50031  
您的账户已设置禁止该币种交易，请确认后重试 | 200 | 50032  
您的账户已设置禁止该业务线交易，请确认后重试 | 200 | 50033  
您当前不在白名单列表，请联系客服 | 200 | 50034  
该接口要求APIKey必须绑定IP | 403 | 50035  
  
#### API 类

错误提示 | HTTP 状态码 | 错误码  
---|---|---  
Api 已被冻结，请联系客服处理 | 400 | 50100  
APIKey 与当前环境不匹配 | 401 | 50101  
请求时间戳过期 | 401 | 50102  
请求头"OK_ACCESS_KEY"不能为空 | 401 | 50103  
请求头"OK_ACCESS_PASSPHRASE"不能为空 | 401 | 50104  
请求头"OK_ACCESS_PASSPHRASE"错误 | 401 | 50105  
请求头"OK_ACCESS_SIGN"不能为空 | 401 | 50106  
请求头"OK_ACCESS_TIMESTAMP"不能为空 | 401 | 50107  
券商ID不存在 | 401 | 50108  
券商域名不存在 | 401 | 50109  
无效的ip | 401 | 50110  
无效的OK_ACCESS_KEY | 401 | 50111  
无效的OK_ACCESS_TIMESTAMP | 401 | 50112  
无效的签名 | 401 | 50113  
无效的授权 | 401 | 50114  
无效的请求类型 | 405 | 50115  
  
#### 交易类

错误提示 | HTTP 状态码 | 错误码  
---|---|---  
{0}参数错误 | 400 | 51000  
交易产品ID不存在 | 200 | 51001  
交易产品ID不匹配指数 | 200 | 51002  
ordId或clOrdId至少填一个 | 200 | 51003  
委托数量超过用户当前档位 | 200 | 51004  
委托数量大于单笔上限 | 200 | 51005  
委托价格不在限价范围内 | 200 | 51006  
委托失败，委托数量不可小于 1 张（用户下单数量不足 1 张时） | 200 | 51007  
委托失败，账户可用余额不足 | 200 | 51008  
下单功能被平台冻结 | 200 | 51009  
当前账户模式不支持此操作 | 200 | 51010  
ordId重复 | 200 | 51011  
币种不存在 | 200 | 51012  
指数不存在 | 200 | 51014  
instId和instType不匹配 | 200 | 51015  
clOrdId重复 | 200 | 51016  
杠杆委托交易借币超出限额 | 200 | 51017  
期权交易账户不能有净空头持仓 | 200 | 51018  
期权全仓不能有净多头持仓 | 200 | 51019  
委托数量必须超过单笔下限 | 200 | 51020  
合约待上线 | 200 | 51021  
合约暂停中 | 200 | 51022  
仓位不存在 | 200 | 51023  
交易账户冻结 | 200 | 51024  
委托笔数超限 | 200 | 51025  
交易产品类型不匹配指数（instType和uly不匹配） | 200 | 51026  
合约已到期 | 200 | 51027  
合约交割中 | 200 | 51028  
合约结算中 | 200 | 51029  
资金费结算中 | 200 | 51030  
委托价格不在平仓限价范围内 | 200 | 51031  
市价全平中 | 200 | 51032  
币对单笔交易已达限额 | 200 | 51033  
PM账户仅支持买卖模式 | 200 | 51041  
当前订单类型{0}， {1}不支持设置止盈和止损 | 200 | 51044  
止盈触发价格应该大于委托价格 | 200 | 51046  
止损触发价格应该小于委托价格 | 200 | 51047  
止盈触发价格应该小于委托价格 | 200 | 51048  
止损触发价格应该大于委托价格 | 200 | 51049  
止盈触发价格应该大于卖一价 | 200 | 51050  
止损触发价格应该小于卖一价 | 200 | 51051  
止盈触发价格应该小于买一价 | 200 | 51052  
止损触发价格应该大于买一价 | 200 | 51053  
获取信息超时，请稍候重试 | 500 | 51054  
超出单笔最大挂单张数 | 200 | 51101  
超出合约最大挂单数量 | 200 | 51102  
超出标的最大挂单数量 | 200 | 51103  
超出标的最大挂单张数 | 200 | 51104  
超出合约最大可开张数 | 200 | 51105  
超出标的最大可开张数 | 200 | 51106  
超出标的最大持仓张数 | 200 | 51107  
持仓量超过市价全平最大限制 | 200 | 51108  
订单深度中无买一卖一价 | 200 | 51109  
集合竞价开始后方可下限价单 | 200 | 51110  
批量下单时，超过最大单数{0} | 200 | 51111  
平仓张数大于该仓位的可平张数 | 200 | 51112  
市价全平操作过于频繁 | 429 | 51113  
市价全平前请先撤销所有平仓单 | 200 | 51115  
委托价格或触发价格超过{0}美元 | 200 | 51116  
平仓单挂单单数超过限制 | 200 | 51117  
下单数量不足{0}张 | 200 | 51120  
下单张数应为一手张数的倍数 | 200 | 51121  
委托价格小于最小值{0} | 200 | 51122  
价格发现期间您只可下限价单 | 200 | 51124  
当前杠杆存在非只减仓挂单，请撤销所有非只减仓挂单后进行只减仓挂单 | 200 | 51125  
当前杠杆存在只减仓挂单，请撤销所有只减仓挂单后进行非只减仓挂单 | 200 | 51126  
仓位可用余额为0 | 200 | 51127  
跨币种账户无法进行全仓杠杆交易 | 200 | 51128  
持仓及买入订单价值已达到持仓限额，不允许继续买入 | 200 | 51129  
逐仓杠杆保证金币种错误 | 200 | 51130  
仓位可用余额不足 | 200 | 51131  
仓位正资产小于最小交易单位 | 200 | 51132  
跨币种全仓币币不支持只减仓功能 | 200 | 51133  
平仓失败，请检查持仓和挂单 | 200 | 51134  
您的平仓价格已触发限价，最高买入价格为{0} | 200 | 51135  
您的平仓价格已触发限价，最低卖出价格为{0} | 200 | 51136  
您的开仓价格已触发限价，最高买入价格为{0} | 200 | 51137  
您的开仓价格已触发限价，最低卖出价格为{0} | 200 | 51138  
交易账户下币币不支持只减仓功能 | 200 | 51139  
逐仓自主划转保证金模式不支持提前挂单 | 200 | 51145  
交易账户资产总价值需要大于5万美元来交易期权 | 200 | 51147  
只减仓委托仅允许减少仓位数量，确保你的仓位不会增加 | 200 | 51148  
下单超时，请稍候重试 | 500 | 51149  
交易数量或价格的精度超过限制 | 200 | 51150  
市价委托单笔价值不能超过 1,000,000 USDT | 200 | 51201  
市价单下单数量超出最大值 | 200 | 51202  
普通委托数量超出最大限制{0} | 200 | 51203  
限价委托单价格不能为空 | 200 | 51204  
不支持只减仓操作 | 200 | 51205  
策略委托价格不在正确范围内 | 200 | 51250  
策略委托类型错误 | 200 | 51251  
策略委托数量不在正确范围内 | 200 | 51252  
冰山委托单笔均值超限 | 200 | 51253  
冰山委托单笔均值错误 | 200 | 51254  
冰山委托单笔委托超限 | 200 | 51255  
冰山委托深度错误 | 200 | 51256  
跟踪委托回调服务错误，回调幅度限制为{0}<x<={1}% | 200 | 51257  
跟踪委托失败，卖单激活价格需大于最新成交价格 | 200 | 51258  
跟踪委托失败，买单激活价格需小于最新成交价格 | 200 | 51259  
每个用户最多可同时持有{0}笔未成交的跟踪委托 | 200 | 51260  
每个用户最多可同时持有{0}笔未成交的止盈止损 | 200 | 51261  
每个用户最多可同时持有{0}笔未成交的冰山委托 | 200 | 51262  
每个用户最多可同时持有{0}笔未成交的时间加权单 | 200 | 51263  
时间加权单笔均值超限 | 200 | 51264  
时间加权单笔上限错误 | 200 | 51265  
时间加权扫单比例出错 | 200 | 51267  
时间加权扫单范围出错 | 200 | 51268  
时间加权委托间隔错误，应为{0}<=x<={1} | 200 | 51269  
时间加权委托深度限制为 0<x<=1% | 200 | 51270  
时间加权委托失败，扫单比例应该为 0<x<=100% | 200 | 51271  
时间加权委托失败，扫单范围应该为 0<x<=1% | 200 | 51272  
时间加权委托总量应为大于 0 | 200 | 51273  
时间加权委托总数量需大于单笔上限 | 200 | 51274  
止盈止损市价单笔委托数量不能超过最大限制 | 200 | 51275  
止盈止损市价单不能指定价格 | 200 | 51276  
止盈触发价格不能大于最新成交价 | 200 | 51277  
止损触发价格不能小于最新成交价 | 200 | 51278  
止盈触发价格不能小于最新成交价 | 200 | 51279  
止损触发价格不能大于最新成交价 | 200 | 51280  
计划委托不支持使用tgtCcy参数 | 200 | 51281  
吃单价优于盘口的比例范围 | 200 | 51282  
时间间隔的范围{0}s~{1}s | 200 | 51283  
单笔数量的范围{0}~{1} | 200 | 51284  
委托总量的范围{0}~{1} | 200 | 51285  
下单金额需大于等于{0} | 200 | 51286  
策略不支持此合约 | 200 | 51287  
策略正在停止中，请勿重复点击 | 200 | 51288  
策略配置不存在，请稍后再试 | 200 | 51289  
策略引擎正在升级，请稍后重试 | 200 | 51290  
策略不存在或已停止 | 200 | 51291  
策略类型不存在 | 200 | 51292  
策略不存在 | 200 | 51293  
该策略暂不能创建，请稍后再试 | 200 | 51294  
PM账户不支持ordType为{0}的策略委托单 | 200 | 51295  
交割、永续合约的买卖模式下，不支持计划委托 | 200 | 51298  
止盈触发价格不能大于标记价格 | 200 | 51300  
止损触发价格不能小于标记价格 | 200 | 51302  
止盈触发价格不能小于标记价格 | 200 | 51303  
止损触发价格不能大于标记价格 | 200 | 51304  
止盈触发价格不能大于指数价格 | 200 | 51305  
止损触发价格不能小于指数价格 | 200 | 51306  
止盈触发价格不能小于指数价格 | 200 | 51307  
止损触发价格不能大于指数价格 | 200 | 51308  
集合竞价期间不能创建策略 | 200 | 51309  
逐仓自主划转保证金模式不支持ordType为iceberg、twap的策略委托单 | 200 | 51310  
移动止盈止损委托失败，回调幅度限制为{0}<x<={1} | 200 | 51311  
移动止盈止损委托失败，委托数量范围{0}<x<={1} | 200 | 51312  
逐仓自主划转模式不支持策略部分 | 200 | 51313  
当前账户风险状态，仅支持降低账户风险方向的IOC订单 | 200 | 51037  
当前风险模块下已经存在降低账户风险方向的IOC类型订单 | 200 | 51038  
PM账户下交割和永续的全仓不能调整杠杆倍数 | 200 | 51039  
期权逐仓的买方不能调整保证金 | 200 | 51040  
撤单失败，订单不存在 | 200 | 51400  
撤单失败，订单已撤销 | 200 | 51401  
撤单失败，订单已完成 | 200 | 51402  
撤单失败，该委托类型无法进行撤单操作 | 200 | 51403  
价格发现第二阶段您不可撤单 | 200 | 51404  
撤单失败，您当前没有未成交的订单 | 200 | 51405  
撤单数量超过最大允许单数{0} | 400 | 51406  
ordIds 和 clOrdIds 不能同时为空 | 200 | 51407  
币对 id 或币对名称与订单信息不匹配 | 200 | 51408  
币对 id 或币对名称不能同时为空 | 200 | 51409  
撤单失败，订单已处于撤销中 | 200 | 51410  
用户没有执行mass cancel的权限 | 200 | 51411  
委托已触发，暂不支持撤单 | 200 | 51412  
价格和数量不能同时为空 | 200 | 51500  
修改订单超过最大允许单数{0} | 400 | 51501  
修改订单失败，用户保证金不足 | 200 | 51502  
修改订单失败，订单不存在 | 200 | 51503  
订单类型不支持改单 | 200 | 51506  
集合竞价第一阶段和第二阶段不允许改单 | 200 | 51508  
修改订单失败，订单已撤销 | 200 | 51509  
修改订单失败，订单已完成 | 200 | 51510  
修改订单失败，订单价格不满足Post Only条件 | 200 | 51511  
修改订单失败，批量改单不允许一批量请求中包含相同的订单 | 200 | 51512  
对于正在处理的同一订单，改单请求次数不得超过3次 | 200 | 51513  
查询订单的状态不存在 | 200 | 51600  
订单状态和订单id不能同时存在 | 200 | 51601  
订单状态或订单id必须存在一个 | 200 | 51602  
查询订单不存在 | 200 | 51603  
  
#### 数据类

错误提示 | HTTP 状态码 | 错误码  
---|---|---  
没有最新行情信息 | 200 | 52000  
  
### 大宗交易

错误码从 52900 到 52900

错误提示 | HTTP 状态码 | 错误码  
---|---|---  
无效请求 | 200 | 52900  
无效基准货币 | 200 | 52901  
无效标价货币 | 200 | 52902  
无效的报价数量 | 200 | 52903  
无效的报价方向 | 200 | 52904  
无效的报价 | 200 | 52905  
无效渠道名 | 200 | 52906  
订单找不到 | 200 | 52907  
无效的订单ID | 200 | 52908  
客户自定义ID重复使用 | 200 | 52909  
服务端暂时不可用，请重试 | 500 | 52910  
询价服务不可用，请重试 | 500 | 52911  
服务端超时 | 500 | 52912  
拒绝交易（失败的原因可能是资金不足，clTReqId重复，quoteId过期等） | 200 | 52913  
询价量超过有效范围 | 200 | 52914  
询价量太大流动性不足无法报价 | 200 | 52915  
  
### 币币/币币杠杆类

错误码从 54000 到 54999

错误提示 | HTTP 状态码 | 错误码  
---|---|---  
暂不支持币币杠杆业务 | 200 | 54000  
只有跨币种全仓账户才能设置自动借币 | 200 | 54001  
  
### 交割合约类

错误码从 55000 到 55999

错误提示 | HTTP 状态码 | 错误码  
---|---|---  
交割后30分钟内不能转出 | 200 | 55000  
  
### 永续合约类

暂无

### 期权合约类

暂无

### 资金类

错误码从 58000 到 58999

错误提示 | HTTP 状态码 | 错误码  
---|---|---  
获取母账户余额，{0}不支持 | 200 | 58000  
交易密码错误 | 200 | 58001  
请先开通余币宝服务 | 200 | 58002  
余币宝不支持该币种 | 200 | 58003  
账户冻结 | 200 | 58004  
申购/赎回额度不可超过{0} | 200 | 58005  
币种{0}不支持当前操作 | 200 | 58006  
资金接口服务异常，请稍后再试。 | 200 | 58007  
您没有该币种资产 | 200 | 58008  
币对不存在 | 200 | 58009  
行权或结算中，暂无法转入或转出 | 200 | 58100  
划转冻结 | 200 | 58101  
划转过于频繁，请降低划转频率 | 429 | 58102  
您在法币区的交易异常，现已被限制划转功能，请您联系在线客服以解除限制 | 200 | 58104  
您在法币区的交易异常，现已被限制划转功能，请您在网页或APP进行法币划  
转操作以完成身份验证 | 200 | 58105  
请先开通币币杠杆账户 | 200 | 58106  
请先开通交割合约账户 | 200 | 58107  
请先开通期权合约账户 | 200 | 58108  
请先开通永续合约账户 | 200 | 58109  
当前交易产品触发市场风控，平台已暂停相关用户的资金转出功能，请耐心等待 | 200 | 58110  
永续合约正在收取资金费，暂时无法做资金划转，请稍后重试 | 200 | 58111  
资金划转失败，请稍后重试 | 200 | 58112  
转账金额必须大于零（划转接口，金额输入不正确） | 400 | 58114  
子账户不存在 | 200 | 58115  
转出数量大于最大可转数量 | 200 | 58116  
账户资产异常，请先处理负资产后再划转 | 200 | 58117  
{0} 子账户没有转出权限，请先设置 | 200 | 58119  
该币种暂不支持从{0}提现至{1}，敬请谅解 | 200 | 58200  
今日提现金额累计超过每日限额 | 200 | 58201  
NEO最小提现数量为1，且提现数量必须为整数 | 200 | 58202  
请先添加提现地址 | 200 | 58203  
提现冻结 | 200 | 58204  
提现金额大于单笔提现最大金额（单笔提现最大金额提现接口，提现金额输入有误） | 200 | 58205  
提现金额小于最小提现金额（最小提现金额提现接口，提现金额输入有误） | 200 | 58206  
提现失败，认证地址错误 | 200 | 58207  
提现失败，邮箱未绑定 | 200 | 58208  
子账户不能充值或提现 | 200 | 58209  
提现手续费大于最大值（提现接口，提现手续费输入有误） | 200 | 58210  
提现手续费小于最小值（提现接口，手续费输入有误） | 200 | 58211  
提现手续费应填写为提币数量的{0}% | 200 | 58212  
提现前请先设置交易密码 | 200 | 58213  
{chainName}维护中，暂停提币 | 200 | 58214  
提币申请ID不存在 | 200 | 58215  
不允许执行该操作 | 200 | 58216  
创建充值地址超过上限 | 200 | 58300  
您的余额不足 | 200 | 58350  
invoice已经过期 | 200 | 58351  
invoice无效 | 200 | 58352  
充币数量需要在限额范围内 | 200 | 58353  
单日达到生成invoice10000个的上限 | 200 | 58354  
用户没有使用此API接口的权限 | 200 | 58355  
同节点账户不支持闪电网络充币或提币 | 200 | 58356  
币种{0}不允许创建充值地址 | 200 | 58357  
fromCcy与toCcy不可相同 | 200 | 58358  
小额兑换功能每日使用次数超限 | 200 | 58370  
小额资产超过最大限制 | 200 | 58371  
小额资产不足 | 200 | 58372  
  
### 账户类

错误码从 59000 到 59999

错误提示 | HTTP 状态码 | 错误码  
---|---|---  
挂单或持仓存在，无法设置 | 200 | 59000  
当前存在借币，暂不可切换 | 200 | 59001  
只支持同一业务线下交易产品ID | 200 | 59004  
逐仓自主划转保证金模式，初次划入仓位的资产价值需大于10000USDT | 200 | 59005  
当前存在持仓，请撤销所有挂单后进行杠杆倍数修改 | 200 | 59100  
当前业务存在逐仓挂单，请撤销所有挂单后进行杠杆倍数修改 | 200 | 59101  
杠杆倍数超过最大杠杆倍数，请重新调整杠杆倍数 | 200 | 59102  
杠杆倍数过低，账户中没有足够的可用保证金可以追加，请重新调整杠杆倍数 | 200 | 59103  
杠杆倍数过高，借币仓位已超过该杠杆倍数的最大仓位，请重新调整杠杆倍数 | 200 | 59104  
杠杆倍数设置不能小于{0}，请重新调整杠杆倍数 | 400 | 59105  
您下单后仓位总张数所处档位的最高可用杠杆为{0}，请重新调整 | 200 | 59106  
当前业务存在全仓挂单，请撤销所有挂单后进行杠杆倍数修改 | 200 | 59107  
杠杆倍数过低，账户中保证金不足，请重新调整杠杆倍数 | 200 | 59108  
调整后，账户权益小于所需保证金，请重新调整杠杆倍数 | 200 | 59109  
该{0}对应的产品业务线不支持使用tgtCcy参数 | 200 | 59110  
PM账户下衍生品全仓不支持杠杆查询 | 200 | 59111  
当前存在逐仓/全仓挂单，请撤销所有逐仓挂单后进行杠杆倍数修改 | 200 | 59112  
账户余额不足 | 200 | 59200  
账户余额是负数 | 200 | 59201  
追加保证金失败，指定仓位不存在 | 200 | 59300  
调整保证金超过当前最大可调整数量 | 200 | 59301  
当前仓位存在平仓挂单，请撤销平仓挂单后进行保证金修改 | 200 | 59302  
可用保证金不足，请尝试增加保证金或减少借币数量 | 200 | 59303  
借币币种权益不足，请至少留有一天的利息 | 200 | 59304  
您当前没有进行尊享借币，无法设置尊享借币优先 | 200 | 59305  
借币数量超过总额度，不可继续借币 | 200 | 59306  
当前用户不满足尊享借币条件 | 200 | 59307  
市场化借币额度不足，VIP还币失败 | 200 | 59308  
还币数量超出已借数量，还币失败 | 200 | 59309  
当前账户不支持尊享借币 | 200 | 59310  
存在尊享借币，无法设置 | 200 | 59311  
{币种}不支持尊享借币 | 200 | 59312  
持仓价值达到持仓限制 | 200 | 59401  
查询条件中的instId的交易产品当前不是可交易状态，请填写单个instid逐个查询状态详情 | 200 | 59402  
仅母账户有操作权限 | 200 | 59500  
每个账户最多可创建 50个APIKey | 200 | 59501  
备注名不可以与当前已创建的APIKey备注名重复 | 200 | 59502  
每个 APIKey 最多可以绑定20个IP地址 | 200 | 59503  
子账户不支持提币功能 | 200 | 59504  
passphrase 格式不正确，支持6-32位字母和数字组合  
（区分大小写，不支持空格符号） | 200 | 59505  
APIKey 不存在 | 200 | 59506  
转出账户和转入账户必须是同一个母账户下的2个不同的子账户 | 200 | 59507  
用户没有重置做市商保护状态的权限 | 200 | 59508  
{0}该子账户被冻结 | 200 | 59509  
子账户不存在 | 200 | 59510  
子账户名称已存在 | 200 | 59601  
创建的APIkey数量超过上限 | 200 | 59602  
创建子账户超过上限时 | 200 | 59603  
仅母账APIkey有操作此接口的权限 | 200 | 59604  
子账户的APIkey不存在 | 200 | 59605  
删除失败，请将子账户中的余额划转到母账户 | 200 | 59606  
仅Broker账户有操作此接口的权限 | 200 | 59608  
经纪商已经存在 | 200 | 59609  
经纪商不存在 | 200 | 59610  
经纪商状态是未审核 | 200 | 59611  
时间参数格式转换失败 | 200 | 59612  
当前未与子账户建立托管关系 | 200 | 59613  
托管子账户不支持此操作 | 200 | 59614  
起始日期和结束日期的时间间隔不能超过180天。 | 200 | 59615  
起始日期不能大于结束日期 | 200 | 59616  
子账户创建成功，账户等级设置失败 | 200 | 59617  
创建子账户失败 | 200 | 59618  
  
## WebSocket

### 公共

错误码从 60000 到 63999

#### 通用类

错误消息 | 错误码  
---|---  
"OK_ACCESS_KEY"不能为空 | 60001  
"OK_ACCESS_SIGN"不能为空 | 60002  
"OK_ACCESS_PASSPHRASE"不能为空 | 60003  
无效的 OK_ACCESS_TIMESTAMP | 60004  
无效的 OK_ACCESS_KEY | 60005  
请求时间戳过期 | 60006  
无效的签名 | 60007  
公共频道不支持登录 | 60008  
登录失败 | 60009  
用户需要登录 | 60011  
不合法的请求 | 60012  
无效的参数 args | 60013  
用户请求频率过快，超过该接口允许的限额 | 60014  
30秒内没有数据通讯，连接关闭 | 60015  
缓冲区无法写入数据，连接关闭 | 60016  
无效的url path | 60017  
频道不存在 | 60018  
无效的op{0} | 60019  
超出最大允许订阅的APIKey数量{0} | 60020  
该功能不支持多账户登录使用 | 60021  
批量登录部分成功 | 60022  
批量登录请求过于频繁 | 60023  
passphrase不正确 | 60024  
超出最大允许订阅的token数量{0} | 60025  
不支持APIKey和token同时登录 | 60026  
参数{0}不可为空 | 60027  
TBT深度频道仅支持手续费等级为VIP5及以上的用户订阅使用 | 60029  
TBT深度频道仅支持手续费等级为VIP4及以上的用户订阅使用 | 60030  
内部系统错误 | 63999  
  
# 创建我的APIKey

点击跳转至官网创建V5APIKey的页面 [创建我的APIKey](/account/my-api)  

# API问题反馈

添加官方API技术支持QQ社群，QQ号：1905481750，180731406 备注：API+姓名+账号，与专业量化人员交流。  

