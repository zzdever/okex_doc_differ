导航 ![](images/navbar-cad8cdcb.png)

[ ![](https://static.coinall.ltd/cdn/assets/imgs/221/02D05B5ABB57940A.png)
](/)

  * [API接口](javascript:void\(0\);)
  * [Broker接入](javascript:void\(0\);)
  * [最佳实践](javascript:void\(0\);)
  * [更新日志](javascript:void\(0\);)

API接口 Broker接入 最佳实践 更新日志

[English](javascript:void\(0\);)

  * 概览 
    * API学习资源与技术支持 
    * 创建我的APIKey 
    * 实盘交易 
    * 模拟盘交易 
    * 基本信息 
    * 交易时效性 
      * REST 
      * WebSocket 
    * 限速 
      * 交易相关API 
      * 最佳实践 
  * 做市商申请 
  * 交互式浏览器 
    * 使用说明 
  * 大宗交易 
    * 大宗交易工作流程 
    * REST API 
      * 获取报价方信息 
      * 询价 
      * 取消询价单 
      * 批量取消询价单 
      * 取消所有询价单 
      * 执行报价
      * 获取可报价产品 
      * 设置可报价产品 
      * 重设MMP状态 
      * 报价 
      * 取消报价单 
      * 批量取消报价单 
      * 取消所有报价单 
      * 获取询价单信息 
      * 获取报价单信息 
      * 获取大宗交易信息 
      * 获取大宗交易公共成交数据 
    * WebSocket 私有频道 
      * 询价频道 
      * 报价频道 
      * 大宗交易频道 
    * WebSocket 公共频道 
      * 公共大宗交易频道 
      * 公共大宗交易单腿交易频道 
      * 大宗交易行情频道 
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
      * 获取策略委托单信息 
      * 获取未完成策略委托单列表 
      * 获取历史策略委托单列表 
      * 获取一键兑换主流币币种列表 
      * 一键兑换主流币交易 
      * 获取一键兑换主流币历史记录 
      * 获取一键还债币种列表 
      * 一键还债交易 
      * 获取一键还债历史记录 
    * 资金 
      * 获取币种列表 
      * 获取资金账户余额 
      * 获取不可交易资产 
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
      * 获取充值/提现的详细状态
      * 小额资产兑换 
    * 闪兑 
      * 获取闪兑币种列表 
      * 获取闪兑币对信息 
      * 闪兑预估询价 
      * 闪兑交易 
      * 获取闪兑交易历史 
    * 账户 
      * 查看账户余额 
      * 查看持仓信息 
      * 查看历史持仓信息 
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
      * 一键借币模式手动借币还币 
      * 获取一键借币还币历史 
      * 尊享借币还币 
      * 获取尊享借币还币历史 
      * 获取尊享借币计息记录 
      * 获取尊享借币扣息记录 
      * 尊享借币订单列表 
      * 尊享借币订单详情 
      * 获取借币利率与限额 
      * 组合保证金的虚拟持仓保证金计算 
      * 查看账户Greeks 
      * 获取组合保证金模式全仓限制 
      * 设置组合保证金账户风险对冲模式 
      * 开通期权交易 
      * 设置自动借币 
    * 子账户 
      * 查看子账户列表 
      * 重置子账户的APIKey 
      * 获取子账户交易账户余额 
      * 获取子账户资金账户余额 
      * 查询子账户转账记录 
      * 子账户间资金划转 
      * 设置子账户主动转出权限 
      * 查看被托管的子账户列表 
      * 获取用户的节点返佣信息 
    * 网格交易 
      * 网格策略委托下单 
      * 修改网格策略订单 
      * 网格策略停止 
      * 获取未完成网格策略委托单列表 
      * 获取历史网格策略委托单列表 
      * 获取网格策略委托订单详情 
      * 获取网格策略委托子订单信息 
      * 获取网格策略委托持仓 
      * 现货/天地网格提取利润 
      * 调整保证金计算 
      * 调整保证金 
      * 网格策略智能回测（公共） 
    * 余币宝 
      * 获取余币宝余额 
      * 余币宝申购/赎回 
      * 设置余币宝借贷利率 
      * 获取余币宝出借明细 
      * 获取市场借贷信息（公共）
      * 获取市场借贷历史（公共） 
    * 赚币 
      * 查看项目 
      * 申购项目 
      * 赎回项目 
      * 撤销项目申购/赎回 
      * 查看活跃订单 
      * 查看历史订单 
    * 跟单 
      * 交易员获取当前带单 
      * 交易员获取历史带单 
      * 交易员止盈止损 
      * 交易员平仓 
      * 交易员获取带单合约 
      * 交易员修改带单合约 
      * 交易员历史分润明细 
      * 交易员历史分润汇总 
      * 交易员待分润明细 
    * 行情数据 
      * 获取所有产品行情信息 
      * 获取单个产品行情信息 
      * 获取指数行情 
      * 获取产品深度 
      * 获取产品轻量深度 
      * 获取交易产品K线数据 
      * 获取交易产品历史K线数据
      * 获取指数K线数据 
      * 获取指数历史K线数据 
      * 获取标记价格K线数据 
      * 获取标记价格历史K线数据 
      * 获取交易产品公共成交数据 
      * 获取交易产品公共历史成交数据 
      * 获取期权品种公共成交数据 
      * 获取平台24小时总成交量 
      * Oracle 上链交易数据 
      * 获取法币汇率 
      * 获取指数成分数据 
      * 获取大宗交易所有产品行情信息 
      * 获取大宗交易单个产品行情信息 
      * 获取大宗交易公共成交数据 
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
      * 张币转换 
      * 获取期权公共成交数据
      * 获取期权价格梯度
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
      * 充值信息频道 
      * 提币信息频道 
      * 现货网格策略委托订单频道 
      * 合约网格策略委托订单频道 
      * 天地网格策略委托订单频道 
      * 合约网格持仓频道 
      * 网格策略子订单频道 
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
      * 期权公共成交频道 
      * 平台公共爆仓单频道
  * 错误码 
    * REST 
      * 公共 
      * 金融 
      * 闪兑 
      * 币币/币币杠杆类 
      * 交割合约类 
      * 永续合约类 
      * 期权合约类 
      * 资金类 
      * 账户类 
      * 大宗交易 
    * WebSocket 
      * 公共 

# 概览

欢迎查看 V5 API文档。我们提供完整的REST和WebSocket API以满足您的交易需求。  
V5 API只适用于[交易账户](/support/hc/zh-cn/sections/360011507312)。  

## API学习资源与技术支持

  * 学习使用V5 API交易: [V5 API使用指南](/docs-v5/trick_zh/#part1)
  * 学习使用Python交易现货: [Python 现货交易教程](https://www.okx.com/learn/spot-trading-with-jupyter-notebook)
  * 学习使用Python交易衍生品: [Python 衍生品交易教程](https://www.okx.com/learn/derivatives-trading-with-jupyter-notebook)
  * 使用Python SDK更简单地上手: [Python SDK](https://pypi.org/project/python-okx/)
  * 官方Discord社群: [OKX Official Discord Channel](https://discord.gg/ctn6hNWvQe)
  * 官方Telegram社群: [OKX API](https://t.me/OKXAPI)
  * 订阅API更新: [OKX API Announcement](https://t.me/OKExAPIChannel)
  * 请花1分钟时间帮助我们提升我们的服务: [V5 API 满意度调研](https://www.wjx.cn/vj/wFoyR0w.aspx)
  * 如有问题请咨询线上客服

## 创建我的APIKey

点击跳转至官网创建V5APIKey的页面 [创建我的APIKey](/account/my-api)  

## 实盘交易

实盘API交易地址如下：

  * REST：`https://www.okx.com/`  

  * WebSocket公共频道：`wss://ws.okx.com:8443/ws/v5/public`  

  * WebSocket私有频道：`wss://ws.okx.com:8443/ws/v5/private`

AWS 地址如下：

  * REST：`https://aws.okx.com`  

  * WebSocket公共频道：`wss://wsaws.okx.com:8443/ws/v5/public`  

  * WebSocket私有频道：`wss://wsaws.okx.com:8443/ws/v5/private`  

## 模拟盘交易

目前可以进行V5 API的模拟盘交易，用户可以通过模拟盘API请求除了`提币`、`充值`和`申购赎回`外的所有接口。

模拟盘API交易地址如下：

  * REST：`https://www.okx.com`
  * WebSocket公共频道：`wss://wspap.okx.com:8443/ws/v5/public?brokerId=9999`  

  * WebSocket私有频道：`wss://wspap.okx.com:8443/ws/v5/private?brokerId=9999`

模拟盘的账户与欧易的账户是互通的，如果您已经有欧易账户，可以直接登录。

模拟盘API交易需要在模拟盘上创建APIKey：

登录欧易账户—>交易—>模拟交易—>个人中心—>创建模拟盘APIKey—>开始模拟交易

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

  * 限价单（包括只做maker单）的最大挂单数：4,000个

  * 策略策略委托订单最大挂单数： 

    * 计划委托：500个  

    * 移动止盈止损：50个  

    * 冰山委托：100个  

    * 时间加权委托：20个  

返回数据规则如下：

  * 当返回数据中，有`code`，且没有`sCode`字段时，`code`和`msg`代表请求结果或者报错原因；

  * 当返回中有`sCode`字段时，代表请求结果或者报错原因的是`sCode`和`sMsg`，而不是`code`和`msg`。

交易品种`instFamily`参数说明：

  * 为支持USDC合约查询和订阅，新增了参数instFamily（交易品种）。  

  * 与uly的区别： 
    * "BTC-USD-SWAP"和"BTC-USDC-SWAP"的uly（指数标的）同为BTC-USD，但是"BTC-USD-SWAP"的instFamily为BTC-USD，"BTC-USDC-SWAP"的instFamily为BTC-USDC。  

    * 若请求参数指定uly为"BTC-USD"，会包含"BTC-USDC"合约和"BTC-USD"币本位合约的数据  

    * 若请求参数指定instFamily为"BTC-USD"，则只包含"BTC-USD"币本位合约的数据，"BTC-USDC"合约的数据不会包含。  

  * 您可以通过"获取交易产品基础信息"接口获取交易产品对应的instFamily。

## 交易时效性

由于网络延时或者OKX服务器繁忙会导致订单无法及时处理。如果您对交易时效性有较高的要求，可以灵活设置请求有效截止时间`expTime`以达到你的要求。

（批量）下单，（批量）改单接口请求中如果包含`expTime`，如果服务器当前系统时间超过`expTime`，则该请求不会被服务器处理。

你应跟我们服务器系统时间同步。请用[获取系统时间](/docs-v5/zh/#rest-api-public-data-get-system-
time)来获取系统时间。

### REST

请求头中设置如下参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
expTime | String | 否 | 请求有效截止时间。Unix时间戳的毫秒数格式，如 `1597026383085`  
  
目前支持如下接口：

  * [下单](/docs-v5/zh/#rest-api-trade-place-order)
  * [批量下单](/docs-v5/zh/#rest-api-trade-place-multiple-orders)
  * [修改订单](/docs-v5/zh/#rest-api-trade-amend-order)
  * [批量修改订单](/docs-v5/zh/#rest-api-trade-amend-multiple-orders)

> 请求示例
    
    
    curl -X 'POST' \
      'https://www.okx.com/api/v5/trade/order' \
      -H 'accept: application/json' \
      -H 'Content-Type: application/json' \
      -H 'OK-ACCESS-KEY: *****' \
      -H 'OK-ACCESS-SIGN: *****'' \
      -H 'OK-ACCESS-TIMESTAMP: *****'' \
      -H 'OK-ACCESS-PASSPHRASE: *****'' \
      -H 'expTime: 1597026383085' \   // 有效截止时间
      -d '{
      "instId": "BTC-USDT",
      "tdMode": "cash",
      "side": "buy",
      "ordType": "limit",
      "px": "1000",
      "sz": "0.01"
    }'
    

### WebSocket

请求中设置如下参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
expTime | String | 否 | 请求有效截止时间。Unix时间戳的毫秒数格式，如 `1597026383085`  
  
目前支持如下接口：

  * [下单](/docs-v5/zh/#websocket-api-trade-place-order)
  * [批量下单](/docs-v5/zh/#websocket-api-trade-place-multiple-orders)
  * [修改订单](/docs-v5/zh/#websocket-api-trade-amend-order)
  * [批量修改订单](/docs-v5/zh/#websocket-api-trade-amend-multiple-orders)

> 请求示例
    
    
    {
        "id": "1512",
        "op": "order",
        "expTime":"1597026383085",  // 有效截止时间
        "args": [{
            "side": "buy",
            "instId": "BTC-USDT",
            "tdMode": "isolated",
            "ordType": "market",
            "sz": "100"
        }]
    }
    

## 限速

我们的 REST 和 WebSocket API 使用限速来保护我们的 API 免受恶意使用，因此我们的交易平台可以可靠和公平地运行。  
当请求因限速而被我们的系统拒绝时，系统会返回错误代码 50011（用户请求频率过快，超过该接口允许的限额。请参考 API 文档并限制请求）。  
每个接口的限速都不同。 您可以从接口详细信息中找到每个接口的限制。 限速定义详述如下：

  * WebSocket 登录和订阅限速基于 IP 地址。

  * 公共未经身份验证的 REST 限速基于 IP 地址。

  * 私有 REST 限速基于 User ID（子帐户具有单独的 User ID）。

  * WebSocket 订单管理限速基于 User ID（子账户具有单独的 User ID）。

### 交易相关API

对于与交易相关的 API（下订单、取消订单和修改订单），以下条件适用：

  * 限速在 REST 和 WebSocket 通道之间共享。

  * 下单、修改订单、取消订单的限速相互独立。

  * 限速在 Instrument ID 级别定义（期权除外）

  * 期权的限速是根据 Instrument Family 级别定义的。 请参阅 [获取交易产品基础信息](/docs-v5/zh/#rest-api-public-data-get-instruments) 接口以查看交易品种信息。

  * 批量订单接口和单订单接口的限速也是独立的，除了只有一个订单发送到批量订单接口时，该订单将被视为一个订单并采用单订单限速。

### 最佳实践

如果您需要的请求速率高于我们的限速，您可以设置不同的子账户来批量请求限速。
我们建议使用此方法来限制或间隔请求，以最大化每个帐户的限速并避免断开连接或拒绝请求。

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

# 交互式浏览器

## 使用说明

该功能接口用户需先登录，接口只会请求模拟环境

  * Parameters 面板中点击`Try it out`按钮，编辑请求参数。

  * 点击`Execute`按钮发送请求。Responses 面板中查看请求结果。

立即体验 [交互式浏览器](/demo-trading-explorer/v5/zh)

# 大宗交易

## 大宗交易工作流程

大宗交易时指在非公开市场进行的、私下议定的、满足规定最小交易手数的期货、期权、交割、永续或混合产品的大单交易。
交易细节一经确认，此笔交易会被提交到OKX以进行保证金计算，清算和执行。

**基本概念**

  1. **询价单（RFQs） -** 询价单，由询价方发给报价方. 询价单包括询价方希望交易的一种或多种产品及其数量。
  2. **报价单 -** 报价单，由报价方发给询价方对询价单的报价。
  3. **交易** \- 当询价方接受并执行报价方的报价单，一笔交易就由此产生。

**基本工作流程**

要以询价方或报价方身份进行交易，用户需要在交易账户中存入至少100,000美元。
此外，要成为报价方[请填写表格以访问大宗交易](https://share.hsforms.com/1mYdfKtJJR3CC03IyCeC6hg3a1fq).

  1. 询价方创建一个询价单（RFQ），并选择希望收到此询价单的报价方。 
  2. 不同报价方发送报价单回应此询价单。
  3. 询价方选择执行最好的报价单产生交易。OKX收到此笔交易并做结算。
  4. 询价方和报价方收到交易执行的确认。
  5. 交易详情发布在公共市场数据频道上（不包含交易方信息）。

**询价方角度**

  1. 询价方使用POST /api/v5/rfq/create-rfq创建询价单。询价方可以可通过GET /api/v5/public/instruments查询可询价产品信息，即通过GET /api/v5/rfq/counterparties查询可选择报价方信息。
  2. 询价方可以在询价单有效时任何时候通过POST /api/v5/rfq/cancel-rfq取消询价单。
  3. 报价方，如果是询价方选择的报价方之一，会在rfqs推送频道收到询价单信息，并可作出相应报价。
  4. 询价方，在quotes推送频道收到报价信息后，可以选择最优报价并通过POST /api/v5/rfq/execute-quote执行。
  5. 询价方会在struc-block-trades推送频道收到交易成功执行确认。
  6. 询价方也会在public-struc-block-trades推送频道收到此笔交易以及其他OKX大宗交易的确认信息。

**报价方角度**

  1. 当有一个新的询价单发出，并且报价方是被选择的报价方之一时，报价方会在rfqs推送频道接收到此询价单信息。
  2. 报价方创建一个单向或者双向的报价单并通过POST /api/v5/rfq/create-quote发出。
  3. 报价方可以通过POST /api/v5/rfq/cancel-quote任意取消一个有效的报价单。
  4. 询价方选择执行最优报价单。
  5. 报价方通过quotes推送频道接收他们报价单的状态更新。
  6. 报价方会在struc-block-trades推送频道收到他们报价单的交易成功执行确认。
  7. 报价方也会在public-struc-block-trades推送频道收到此笔交易以及其他OKX大宗交易的确认信息。

## REST API

简单账户模式下不支持大宗交易

### 获取报价方信息

查询可以参与交易的报价方信息。

#### 限速: 5次/2s

#### 限速规则：UserID

#### HTTP Requests

`GET /api/v5/rfq/counterparties`

> 请求示例
    
    
    GET /api/v5/rfq/counterparties
    
    

#### 请求参数

无

> 响应示例
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
            {
                "traderName" : "Satoshi Nakamoto",
                "traderCode" : "SATOSHI",
                "type" : "" 
            }
        ]
    }
    

#### 响应参数

参数名 | 类型 | 描述  
---|---|---  
traderName | String | 报价方名称  
traderCode | String | 报价方唯一标识代码，公开可见；报价和询价的相关接口都使用该代码代表报价方。  
type | String | 报价方类型  
  
### 询价

创建一个询价单。

  
在模拟交易中询价时，请选择交易机器人“WAGMI”作为交易对手。  
交易机器人提供的报价仅供参考。

了解更多，请访问[常见问题 > 模拟交易](/support/hc/zh-cn/articles/7111923703053)

#### 限速: 5次/2s

#### 限速规则：UserID

#### HTTP Requests

`POST /api/v5/rfq/create-rfq`

> 请求示例
    
    
    POST /api/v5/rfq/create-rfq
    
    {
        "anonymous": true,
        "counterparties":[
            "Trader1",
            "Trader2"
        ],
        "allowPartialExecution":false,
        "clRfqId":"rfq01",
        "tag":"123456",
        "legs":[
            {
                "sz":"25",
                "side":"buy",
                "posSide": "long",
                "instId":"BTCUSD-221208-100000-C"
            },
            {
                "sz":"150",
                "side":"buy",
                "posSide": "long",
                "instId":"ETH-USDT",
                "tgtCcy":"base_ccy"
            }
        ]
    }
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
counterparties | Array of strings | 是 |
希望收到询价的报价方列表，可通过`/api/v5/rfq/counterparties/`获取。  
anonymous | Boolean | 否 | 是否匿名询价，`true`表示匿名询价，`false`表示公开询价，默认值为
`false`，为`true`时，即使在交易执行之后，身份也不会透露给报价方。  
clRfqId | String | 否 | 询价单自定义ID，字母（区分大小写）与数字的组合，可以是纯字母、纯数字且长度要在1-32位之间。  
tag | String | 否 | 询价单标签，与此询价单关联的大宗交易将有相同的标签。  
字母（区分大小写）与数字的组合，可以是纯字母、纯数字，且长度在1-16位之间。  
allowPartialExecution | Boolean | 否 |
RFQ是否可以被部分执行，如果腿的比例和原RFQ一致。有效值为`true`或`false`。默认为`false`。  
legs | Array of objects | 是 | 组合交易，每次最多可以提交15组交易信息  
> instId | String | 是 | 产品ID  
> sz | String | 是 | 委托数量  
> side | String | 是 | 询价单方向  
> posSide | String | 否 | 持仓方向  
单向持仓模式下默认为`net`。在双向持仓模式下仅可选择`long`或`short`。  
如未指定，则处于双向持仓模式下的用户始终会开新仓位。  
仅适用交割、永续。  
> tgtCcy | String | 否 | 委托数量的类型  
定义`sz`属性的单位。仅适用于
instType=`SPOT`。有效值为`base_ccy`和`quote_ccy`。未指定时，默认为`base_ccy`。  
  
> 返回示例
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
            {
                "cTime":"1611033737572",
                "uTime":"1611033737572",
                "traderCode":"SATOSHI",
                "tag":"123456",
                "rfqId":"22534",
                "clRfqId":"rfq01",
                "allowPartialExecution":false,
                "state":"active",
                "validUntil":"1611033857557",
                "counterparties":[
                    "Trader1",
                    "Trader2"
                ],
                "legs":[
                    {
                        "instId":"BTCUSD-221208-100000-C",
                        "sz":"25",
                        "side":"buy",
                        "posSide": "long",
                        "tgtCcy":""
                    },
                    {
                        "instId":"ETH-USDT",
                        "sz":"150",
                        "side":"buy",
                        "posSide": "long",
                        "tgtCcy":"base_ccy"     
                    }
                ]
            }
        ]
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
code | String | 结果代码，0 表示成功。  
msg | String | 错误信息，如果代码不为 0，则不为空。  
data | Array of objects | 询价单结果  
> cTime | String | 询价单创建时间，Unix时间戳的毫秒数格式。  
> uTime | String | 询价单状态更新时间，Unix时间戳的毫秒数格式。  
> state | String | 询价单的状态  
有效值为 `active` `canceled` `pending_fill` `filled` `expired` `traded_away`
`failed`  
`traded_away` 仅适用于报价方  
> counterparties | Array of strings | 报价方列表  
> validUntil | String | 询价单的过期时间，Unix时间戳的毫秒数格式。  
> clRfqId | String | 询价单自定义ID，为客户端敏感信息，不会公开，对报价方返回""。  
> tag | String | RFQ标签，与此RFQ关联的大宗交易将有相同的标签。  
> allowPartialExecution | Boolean |
> RFQ是否可以被部分执行，如果腿的比例和原RFQ一致。有效值为`true`或`false`。未指定时，默认为`false`。  
> traderCode | String | 询价方唯一标识代码。  
> rfqId | String | 询价单ID  
> legs | Array of objects | 组合交易，每个请求最多可放置15条腿  
>> instId | String | 产品ID，例如："BTC-USDT-SWAP"  
>> sz | String | 委托数量  
>> side | String | 询价单方向  
有效值为`buy`和`sell`。  
>> posSide | String | 持仓方向  
单向持仓模式下默认为`net`。如未指定，则返回""，相当于`net`。  
在双向持仓模式下仅可选择`long`或`short`。 如未指定，则返回""，对应于为交易开新仓位的方向（买入=>`long`，卖出=>`short`）。  
仅适用交割、永续。  
>> tgtCcy | String | 委托数量的类型  
定义`sz`属性的单位。仅适用于
instType=`SPOT`。有效值为`base_ccy`和`quote_ccy`。未指定时，默认为`base_ccy`。  
  
### 取消询价单

取消一个询价单。

#### 限速: 5次/2s

#### 限速规则：UserID

#### HTTP Requests

`POST /api/v5/rfq/cancel-rfq`

> 请求示例
    
    
    POST /api/v5/rfq/cancel-rfq
    {
        "rfqId":"22535",
        "clRfqId":"rfq001"
    }
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
rfqId | String | 可选 | 询价单ID  
clRfqId | String | 可选 | 询价单自定义ID，字母（区分大小写）与数字的组合，可以是纯字母、纯数字且长度要在1-32位之间。  
当 clRfqId 和 rfqId 都传时，以 rfqId 为准。  
  
> 返回示例
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
            {
                "rfqId":"22535",
                "clRfqId":"rfq001",
                "sCode":"0",
                "sMsg":""
            }
        ]
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
code | String | 结果代码，0 表示成功。  
msg | String | 错误信息，如果代码不为 0，则不为空。  
data | Array of objects | 包含结果的对象数组  
> rfqId | String | RFQ ID  
> clRfqId | String | 由用户设置的 RFQ ID  
> sCode | String | 事件执行结果的code，0代表成功  
> sMsg | String | 事件执行失败时的msg  
  
### 批量取消询价单

取消一个或多个询价单，每次最多可以撤销100个询价单。

#### 限速: 2次/2s

#### 限速规则：UserID

#### HTTP Requests

`POST /api/v5/rfq/cancel-batch-rfqs`

> 请求示例
    
    
    POST /api/v5/rfq/cancel-batch-rfqs
    {
        "rfqIds":[
            "2201",
            "2202",
            "2203"
        ],
        "clRfqIds":[
            "r1",
            "r2",
            "r3"
        ]
    }
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
rfqIds | Array of strings | 可选 | 询价单IDs  
clRfqIds | Array of strings | 可选 | 询价单自定义ID，当 clRfqIds 和 rfqIds 都传时，以 rfqIds
为准。  
  
> 全部成功示例
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
            {
                "rfqId":"2201",
                "clRfqId":"r1",
                "sCode":"0",
                "sMsg":""
            },
            {
                "rfqId":"2202",
                "clRfqId":"r2",
                "sCode":"0",
                "sMsg":""
            },
            {
                "rfqId":"2203",
                "clRfqId":"r3",
                "sCode":"0",
                "sMsg":""
            }
        ]
    }
    
    

> 部分成功示例
    
    
    {
        "code":"2",
        "msg":"Bulk operation partially ",
        "data":[
            {
                "rfqId":"2201",
                "clRfqId":"r1",
                "sCode":"70000",
                "sMsg":"RFQ does not exist."
            },
            {
                "rfqId":"2202",
                "clRfqId":"r2",
                "sCode":"0",
                "sMsg":""
            },
            {
                "rfqId":"2203",
                "clRfqId":"r3",
                "sCode":"0",
                "sMsg":""
            }
        ]
    }
    
    

> 失败示例
    
    
    {
        "code":"1",
        "msg":"Operation failed.",
        "data":[
            {
                "rfqId":"2201",
                "clRfqId":"r1",
                "sCode":"70000",
                "sMsg":"RFQ does not exist."
            },
            {
                "rfqId":"2202",
                "clRfqId":"r2",
                "sCode":"70000",
                "sMsg":"RFQ does not exist."
            },
            {
                "rfqId":"2203",
                "clRfqId":"r3",
                "sCode":"70000",
                "sMsg":"RFQ does not exist."
            }
        ]
    }
    
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
code | String | 结果代码，0 表示成功。  
msg | String | 错误信息，如果代码不为 0，则不为空。  
data | Array of objects | 包含结果的对象数组  
> rfqId | String | 询价单ID  
> clRfqId | String | 询价单自定义ID.  
> sCode | String | 事件执行结果的code，0代表成功  
> sMsg | String | 事件执行失败时的msg  
  
### 取消所有询价单

取消所有询价单

#### 限速: 2次/2s

#### 限速规则：UserID

#### HTTP Requests

`POST /api/v5/rfq/cancel-all-rfqs`

> 请求示例
    
    
    POST /api/v5/rfq/cancel-all-rfqs
    
    

#### 请求参数

无

> 返回示例
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
            {
                "ts":"1697026383085"
            }
        ]
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
code | String | 结果代码，0 表示成功。  
msg | String | 错误信息，如果代码不为 0，则不为空。  
data | Array of objects | 包含结果的对象数组  
> ts | String | 成功取消时间，Unix时间戳的毫秒数格式，例如 1597026383085。  
  
### 执行报价

执行报价，仅限询价的创建者使用

#### 限速: 2次/3s

#### 限速规则：UserID

#### HTTP Requests

`POST /api/v5/rfq/execute-quote`

> 请求示例
    
    
    POST /api/v5/rfq/execute-quote
    {
        "rfqId":"22540",
        "quoteId":"84073",
        "legs":[
        {
            "sz":"25",
            "instId":"BTC-USD-20220114-13250-C"
        },
        {
            "sz":"25",
            "instId":"BTC-USDT"
        }
         ]
    }
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
rfqId | String | 是 | 询价单ID  
quoteId | String | 是 | 报价单ID  
legs | Array of objects | 否 |
用于部分执行的腿的数量。腿的数量比例必须与原RFQ相同。注意：每条腿的`tgtCcy`和`side`和原RFQ一致，`px`和对应Quote一致。  
> instId | String | 是 | 产品ID, 如 "BTC-USDT-SWAP".  
> sz | String | 是 | 该条腿的部分执行数量  
  
> 响应示例
    
    
    {  
       "code":"0",
       "msg":"",
       "data":[
           {
                "blockTdId":"180184",
                "rfqId":"1419",
                "clRfqId":"r0001",
                "quoteId":"1046",
                "clQuoteId":"q0001",
                "tag":"123456",
                "tTraderCode":"Trader1",
                "mTraderCode":"Trader2",
                "cTime":"1649670009",
                "legs":[
                    {
                        "px":"43000",
                        "sz":"25",
                        "instId":"BTC-USD-20220114-13250-C",
                        "side":"sell",
                        "fee":"-1.001",
                        "feeCcy":"BTC",
                        "tradeId":"10211"
                    },
                    {
                        "px":"42800",
                        "sz":"25",
                        "instId":"BTC-USDT",
                        "side":"buy",
                        "fee":"-1.001",
                        "feeCcy":"BTC",
                        "tradeId":"10212"
                    }
                ]
            }
       ]
    }
    

#### 响应参数

参数名 | 类型 | 描述  
---|---|---  
code | String | 结果代码，0 表示成功。  
msg | String | 错误信息，如果代码不为 0，则不为空。  
data | Array of objects | 包含结果的对象数组  
> cTime | String | 交易执行的时间，Unix时间戳的毫秒数格式。  
> rfqId | String | 询价单ID  
> clRfqId | String | 询价单自定义ID，为客户敏感信息，不会公开，对报价方返回""。  
> quoteId | String | 报价单ID  
> clQuoteId | String | 报价单自定义ID，为客户敏感信息，不会公开，对询价方返回""。  
> blockTdId | String | 大宗交易ID  
> tag | String | 报价单标签，与此报价单关联的大宗交易将有相同的标签。  
> tTraderCode | String | 询价价方唯一标识代码。询价时 anonymous 设置为 `true` 时不可见。  
> mTraderCode | String | 报价方唯一标识代码。 报价时 anonymous 设置为 `true` 时不可见。  
> legs | Array of objects | 组合交易  
>> instId | String | 产品ID  
>> px | String | 成交价格  
>> sz | String | 成交数量  
>> side | String | 询价单方向，`buy` 或者 `sell`。  
>> fee | String | 手续费，正数代表平台返佣 ，负数代表平台扣除  
>> feeCcy | String | 手续费币种  
>> tradeId | String | 最新的成交Id.  
  
### 获取可报价产品

用于maker查询特定的接受询价和报价的产品, 以及数量和价格范围。

#### 限速: 5次/2s

#### 限速规则：UserID

#### HTTP Requests

`GET /api/v5/rfq/maker-instrument-settings`

> 请求示例
    
    
    GET /api/v5/rfq/maker-instrument-settings
    

#### 请求参数

无

> 返回示例
    
    
    {
        "code": "0",
        "msg": "",
        "data":
            [
                {"instType": "OPTION",
                 "includeALL": true,
                 "data":
                    [
                    {    
                        "uly": "BTC-USD",
                        "maxBlockSz": "10000",
                        "makerPxBand": "5"
                        },
                    {
                        "uly": "SOL-USD",
                        "maxBlockSz": "100000",
                        "makerPxBand": "15"
                        }
                    ]
                },
                {"instType": "FUTURES",
                 "includeALL": false,
                 "data":
                    [
                    {
                        "uly": "BTC-USD",
                        "maxBlockSz": "10000",
                        "makerPxBand": "5"
                    },
                    {
                        "uly": "ETH-USDT",
                        "maxBlockSz": "100000",
                        "makerPxBand": "15"
                    }
                    ]
                },
                {"instType:": "SWAP",
                 "includeALL": false,
                 "data":
                    [{
                        "uly": "BTC-USD",
                        "maxBlockSz": "10000",
                        "makerPxBand": "5"
                        },
                    {
                        "uly": "ETH-USDT"
                        }
                    ]
                },
                    {"instType:": "SPOT",
                     "includeALL": false,
                     "data":
                        [{
                            "instId": "BTC-USDT"
                            },
                        {
                            "instId": "TRX-USDT"
                            }
                        ]
    
            ]
        }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
code | String | 结果代码，`0` 表示成功  
msg | String | 错误信息，如果代码不为`0`，则不为空  
data | Array of objects | 请求返回值，包含请求结果  
instType | String | 产品类别，枚举值包括`FUTURES`,`OPTION`,`SWAP`和`SPOT`  
includeAll | Boolean | 是否接收该instType下所有产品。有效值为`true`或`false`。默认`false`。  
> data | Array of objects | instType的元素  
>> instFamily | String | 交易品种  
`交割/永续/期权`情况下必填  
>> instId | String | 产品ID，如 `BTC-USDT`。对`SPOT`产品类别有效且必须。  
>> maxBlockSz | String | 该种产品最大可交易数量。FUTURES, OPTION and SWAP
的单位是合约数量。SPOT的单位是交易货币。  
>> makerPxBand | String | 价格限制以价格精度tick为单位，以标记价格为基准。  
设置makerPxBand为1个tick代表:  
如果买一价 > 标记价格 + 1 tick, 操作将被拦截  
如果 买一价 < 标记价格 - 1 tick, 操作将被拦截  
  
### 设置可报价产品

用于maker设置特定的接受询价和报价的产品, 以及数量和价格范围。

#### 限速: 5次/2s

#### 限速规则：UserID

#### HTTP Requests

`POST /api/v5/rfq/maker-instrument-settings`

> 请求示例
    
    
    POST /api/v5/rfq/maker-instrument-settings
    [
        {
         "instType": "OPTION",
         "data":
            [{
                "instFamily": "BTC-USD",
                "maxBlockSz": "10000",
                "makerPxBand": "5"
            },
            {
                "instFamily": "SOL-USD",
                "maxBlockSz": "100000",
                "makerPxBand": "15"
            }]
        },
        {
         "instType": "FUTURES",
         "data":
            [{
                "instFamily": "BTC-USD",
                "maxBlockSz": "10000",
                "makerPxBand": "5"
            },
            {
                "instFamily": "ETH-USDT",
                "maxBlockSz": "100000",
                "makerPxBand": "15"
            }]
        },
        {
         "instType": "SWAP",
         "data":
            [{
                "instFamily": "BTC-USD",
                "maxBlockSz": "10000",
                "makerPxBand": "5"
             },
            {
                "instFamily": "ETH-USDT"
            }]
        },
        {
        "instType": "SPOT",
         "data":
            [{
                "instId": "BTC-USDT"
             },
            {
                "instId": "TRX-USDT"
            }]
        }
    ]
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instType | String | 是 | 产品类别，枚举值包括`FUTURES`,`OPTION`,`SWAP`和`SPOT`  
includeAll | Boolean | 否 | 是否接收该instType下所有产品。有效值为`true`或`false`。默认`false`。  
data | Array of objects | 是 | instType的元素  
> instFamily | String | 可选 | 交易品种  
`交割/永续/期权`情况下必填  
> instId | String | 可选 | 产品ID，如 `BTC-USDT`。对`SPOT`产品类别有效且必须。  
> maxBlockSz | String | 否 | 该种产品最大可交易数量。FUTURES, OPTION and SWAP
> 的单位是合约数量。SPOT的单位是交易货币。  
> makerPxBand | String | 否 | 价格限制以价格精度tick为单位，以标记价格为基准。  
设置makerPxBand为1个tick代表:  
如果买一价 > 标记价格 + 1 tick, 操作将被拦截  
如果 买一价 < 标记价格 - 1 tick, 操作将被拦截  
  
> 返回示例
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
            {
                "result":true
            }
        ]
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
code | String | 结果代码，`0` 表示成功  
msg | String | 错误信息，如果代码不为`0`，则不为空  
data | Array of objects | 请求返回值，包含请求结果  
> result | Boolean | 请求结果，枚举值为`true`,`false`  
  
### 重设MMP状态

重设MMP状态为无效。

#### 限速: 5次/2s

#### 限速规则：UserID

#### HTTP Requests

`POST /api/v5/rfq/mmp-reset`

> 请求示例
    
    
    POST /api/v5/rfq/mmp-reset
    
    

#### 请求参数

None

>
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

参数名 | 类型 | 描述  
---|---|---  
code | String | 结果代码，`0` 表示成功  
msg | String | 错误信息，如果代码不为`0`，则不为空  
data | Array of objects | 请求返回值，包含请求结果  
ts | String | 重设时间. Unix 时间戳的毫秒数格式，如 `1597026383085`.  
  
### 报价

允许询价单指定的报价方进行报价，需要对整个询价单报价，不允许部分报价或部分成交。

#### 限速: 50次/2s

#### 限速规则：UserID

#### HTTP Requests

`POST /api/v5/rfq/create-quote`

> 请求示例
    
    
    POST /api/v5/rfq/create-quote
    {
        "rfqId":"22539",
        "clQuoteId":"q001",
        "tag":"123456",
        "quoteSide":"buy",
        "anonymous": true,
        "expiresIn":"30",
        "legs":[
            {
                "px":"39450.0",
                "sz":"200000",
                "instId":"BTC-USDT-SWAP",
                "side":"buy",
                "posSide": "long"
            },
            {
                "px":"39450.0",
                "sz":"200000",
                "instId":"BTC-USDT-SWAP",
                "side":"buy",
                "posSide": "long"
            }
        ]
    }
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
rfqId | String | 是 | 询价单ID  
clQuoteId | String | 否 | 报价单自定义ID  
tag | String | 否 | 报价单标签，与此报价单关联的大宗交易将有相同的标签。  
字母（区分大小写）与数字的组合，可以是纯字母、纯数字，且长度在1-16位之间。  
anonymous | Boolean | 否 |
是否匿名报价，`true`表示匿名报价，`false`表示公开报价，默认值为`false`，为`true`时，即使在交易执行之后，身份也不会透露给询价方。  
quoteSide | String | 是 |
报价单方向，`buy`或者`sell`。当报价单方向为`buy`，对maker来说，执行方向与legs里的方向相同，对taker来说相反。反之同理  
expiresIn | String | 否 | 报价单的有效时长（以秒为单位）。 10到120之间的任何整数。 默认值为60  
legs | Array of objects | 是 | 组合交易  
> instId | String | 是 | 产品ID  
> sz | String | 是 | 委托数量  
> px | String | 是 | 委托价格  
> side | String | 是 | 报价单方向  
> posSide | String | 否 | 持仓方向  
单向持仓模式下默认为`net`。在双向持仓模式下仅可选择`long`或`short`。  
如未指定，则处于双向持仓模式下的用户始终会开新仓位。  
仅适用交割、永续。  
> tgtCcy | String | 否 | 委托数量的类型  
定义`sz`属性的单位。仅适用于
instType=`SPOT`。有效值为`base_ccy`和`quote_ccy`。未指定时，默认为`base_ccy`。  
  
> 返回示例
    
    
    {
        "code":"",
        "msg":"",
        "data":[
            {
                "validUntil":"1608997227834",
                "uTime":"1608267227834",
                "cTime":"1608267227834",
                "legs":[
                    {
                        "px":"46000",
                        "sz":"25",
                        "instId":"BTC-USD-220114-25000-C",
                        "side":"sell",
                        "posSide": "long",
                        "tgtCcy":""
                    },
                    {
                        "px":"4000",
                        "sz":"25",
                        "instId":"ETH-USD-220114-25000-C",
                        "side":"buy",
                        "posSide": "long",
                        "tgtCcy":""
                    }
                ],
                "quoteId":"25092",
                "rfqId":"18753",
                "tag":"123456",
                "quoteSide":"sell",
                "state":"active",
                "reason": "mmp_canceled"
                "clQuoteId":"",
                "clRfqId":"",
                "traderCode":"Aksha"
            }
        ]
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
code | String | 结果代码，0表示成功。  
msg | String | 错误信息，如果代码不为0，则不为空。  
data | Array of objects | 包含结果的对象数组  
> cTime | String | 报价单创建时间，Unix时间戳的毫秒数格式。  
> uTime | String | 报价单状态更新时间，Unix时间戳的毫秒数格式。  
> state | String | 报价单的状态  
有效值为 `active` `canceled` `pending_fill` `filled` `expired` `failed`  
> reason | String | 状态原因. 有效值包括 `mmp_canceled`.  
> validUntil | String | 报价单的过期时间，Unix时间戳的毫秒数格式。  
> rfqId | String | 询价单ID  
> clRfqId | String | 询价单自定义ID，为客户敏感信息，不会公开，对报价方返回""。  
> quoteId | String | 报价单ID  
> clQuoteId | String | 报价单自定义ID，为客户敏感信息，不会公开，对询价方返回""。  
> tag | String | 报价单标签，与此报价单关联的大宗交易将有相同的标签。  
> traderCode | String | 报价方唯一标识代码。  
> quoteSide | String |
> 报价单方向，有效值为`buy`或者`sell`。当报价单方向为`buy`，对maker来说，执行方向与legs里的方向相同，对taker来说相反。反之同理。  
> legs | Array of objects | 组合交易  
>> instId | String | 产品ID  
>> sz | String | 委托数量  
>> px | String | 委托价格  
>> side | String | 腿的方向，有效值为`buy`或者`sell`。  
>> posSide | String | 持仓方向  
单向持仓模式下默认为`net`。如未指定，则返回""，相当于`net`。  
在双向持仓模式下仅可选择`long`或`short`。 如未指定，则返回""，对应于为交易开新仓位的方向（买入=>`long`，卖出=>`short`）。  
仅适用交割、永续。  
>> tgtCcy | String | 委托数量的类型  
定义`sz`属性的单位。仅适用于
instType=`SPOT`。有效值为`base_ccy`和`quote_ccy`。未指定时，默认为`base_ccy`。  
  
### 取消报价单

取消一个报价单。

#### 限速: 50次/2s

#### 限速规则：UserID

#### HTTP Requests

`POST /api/v5/rfq/cancel-quote`

> 请求示例
    
    
    POST /api/v5/rfq/cancel-quote
    {
        "quoteId": "007",
        "clQuoteId":"Bond007"
    }
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
quoteId | String | 可选 | 报价单ID  
clQuoteId | String | 可选 | 报价单自定义ID，字母（区分大小写）与数字的组合，可以是纯字母、纯数字且长度要在1-32位之间，当
clRfqId 和 rfqId 都传时，以 rfqId 为准。  
rfqId | String | 否 | 询价单ID  
  
> 返回示例
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
            {
                "quoteId":"007",
                "clQuoteId":"Bond007",
                "sCode":"0",
                "sMsg":""
            }
        ]
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
code | String | 结果代码，0 表示成功。  
msg | String | 错误信息，如果代码不为 0，则不为空。  
data | Array of objects | 包含结果的对象数组  
> quoteId | String | 报价单ID  
> clQuoteId | String | 询价单自定义ID  
> sCode | String | 事件执行结果的code，0代表成功  
> sMsg | String | 事件执行失败时的msg  
  
### 批量取消报价单

取消一个或多个报价单，每次最多可以撤销100个订单。

#### 限速: 2次/2s

#### 限速规则：UserID

#### HTTP Requests

`POST /api/v5/rfq/cancel-batch-quotes`

> 请求示例
    
    
    POST /api/v5/rfq/cancel-batch-quotes
    {
        "quoteIds":["1150","1151","1152"],
        "clQuoteIds":["q1","q2","q3"]
    }
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
quoteIds | Array of strings | 可选 | 报价单ID  
clQuoteIds | Array of strings | 可选 | 报价单自定义ID，当 clQuoteIds 和 quoteIds 都传时，以
quoteIds 为准。  
  
> 全部成功的示例
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
            {
                "quoteId":"1150",
                "clQuoteId":"q1",
                "sCode":"0",
                "sMsg":""
            },
            {
                "quoteId":"1151",
                "clQuoteId":"q2",
                "sCode":"0",
                "sMsg":""
            },
            {
                "quoteId":"1152",
                "clQuoteId":"q3",
                "sCode":"0",
                "sMsg":""
            }
        ]
    }
    
    

> 部分成功的示例
    
    
    {
        "code":"2",
        "msg":"Bulk operation partially succeeded.",
        "data":[
            {
                "quoteId":"1150",
                "clQuoteId":"q1",
                "sCode":"0",
                "sMsg":""
            },
            {
                "quoteId":"1151",
                "clQuoteId":"q2",
                "sCode":"70001",
                "sMsg":"Quote does not exist."
            },
            {
                "quoteId":"1152",
                "clQuoteId":"q3",
                "sCode":"70001",
                "sMsg":"Quote does not exist."
            }
        ]
    }
    
    

> 失败示例
    
    
    {
        "code":"1",
        "msg":"Operation failed.",
        "data":[
            {
                "quoteId":"1150",
                "clQuoteId":"q1",
                "sCode":"70001",
                "sMsg":"Quote does not exist."
            },
            {
                "quoteId":"1151",
                "clQuoteId":"q2",
                "sCode":"70001",
                "sMsg":"Quote does not exist."
            },
            {
                "quoteId":"1151",
                "clQuoteId":"q3",
                "sCode":"70001",
                "sMsg":"Quote does not exist."
            }
        ]
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
code | String | 结果代码，0 表示成功。  
msg | String | 错误信息，如果代码不为 0，则不为空。  
data | Array of objects | 包含结果的对象数组  
> quoteId | String | 报价单ID  
> clQuoteId | String | 报价单自定义ID  
> sCode | String | 事件执行结果的code，0代表成功  
> sMsg | String | 事件执行失败时的msg  
  
### 取消所有报价单

取消所有报价单

#### 限速: 2次/2s

#### 限速规则：UserID

#### HTTP Requests

`POST /api/v5/rfq/cancel-all-quotes`

> 请求示例
    
    
    POST /api/v5/rfq/cancel-all-quotes
    
    

#### 请求参数

无

> 响应示例
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
            {
                "ts":"1697026383085"
            }
        ]
    }
    

#### 响应参数

参数名 | 类型 | 描述  
---|---|---  
code | String | 结果代码，0 表示成功。  
msg | String | 错误信息，如果代码不为 0，则不为空。  
data | Array of objects | 包含结果的对象数组  
> ts | String | 成功取消时间，Unix时间戳的毫秒数格式，例如 1597026383085。  
  
### 获取询价单信息

获取用户发出的或收到的询价单信息

#### 限速: 2次/2s

#### 限速规则：UserID

#### HTTP Requests

`GET /api/v5/rfq/rfqs`

> 请求示例
    
    
    GET /api/v5/rfq/rfqs
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
rfqId | String | 否 | 询价单ID .  
clRfqId | String | 否 | 客户询价单自定义ID，当 clRfqId 和 rfqId 都传时，以 rfqId 为准  
state | String | 否 | 询价单的状态  
`active` `canceled` `pending_fill` `filled` `expired` `failed` `traded_away`  
`traded_away` 仅适用于报价方  
beginId | String | 否 | 请求的起始询价单ID，请求此ID之后（更新的数据）的分页内容，不包括 beginId  
endId | String | 否 | 请求的结束询价单ID，请求此ID之前（更旧的数据）的分页内容，不包括 endId  
limit | String | 否 | 返回结果的数量，最大为100，默认100条  
  
> 返回示例
    
    
    {
        "code": "0",
        "msg": "",
        "data": [
            {
                "rfqId": "123456",
                "clRfqId": "",
                "tag": "123456",
                "traderCode": "VITALIK",
                "validUntil": "1650969031817",
                "allowPartialExecution": false,
                "state": "filled",
                "counterparties": [
                    "SATOSHI"
                ],
                "legs": [
                    {
                        "instId": "BTC-USDT",
                        "side": "buy",
                        "posSide": "long",
                        "sz": "25",
                        "tgtCcy": "base_ccy"
                    }
                ],
                "cTime": "1650968131817",
                "uTime": "1650968164944"
            },
            {
                "rfqId": "1234567",
                "clRfqId": "",
                "tag": "1234567",
                "traderCode": "VITALIK",
                "validUntil": "1650967623729",
                "state": "filled",
                "counterparties": [
                    "SATOSHI"
                ],
                "legs": [
                    {
                        "instId": "BTC-USDT",
                        "side": "buy",
                        "posSide": "long",
                        "sz": "1500000",
                        "tgtCcy": "quote_ccy"
                    }
                ],
                "cTime": "1650966723729",
                "uTime": "1650966816577"
            }
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
code | String | 结果代码，0 表示成功。  
msg | String | 错误信息，如果代码不为 0，则不为空。  
data | Array of objects | 包含结果的对象数组  
> cTime | String | 询价单创建时间，Unix时间戳的毫秒数格式。  
> uTime | String | 询价单状态更新时间，Unix时间戳的毫秒数格式。  
> state | String | 询价单的状态  
`active` `canceled` `pending_fill` `filled` `expired` `failed` `traded_away`  
`traded_away` 仅适用于报价方  
> counterparties | Array of srings | 报价方列表  
> validUntil | String | 询价单的过期时间，Unix时间戳的毫秒数格式。  
> clRfqId | String | 询价单自定义ID，为客户敏感信息，不会公开，对报价方返回""。  
> tag | String | 询价单标签，与此询价单关联的大宗交易将有相同的标签。  
> traderCode | String | 询价方唯一标识代码，询价时 anonymous 设置为 `true` 时不可见  
> rfqId | String | 询价单ID  
> allowPartialExecution | Boolean |
> RFQ是否可以被部分执行，如果腿的比例和原RFQ一致。有效值为`true`或`false`。未指定时，默认为`false`。  
> legs | Array of objects | 组合交易，每个请求最多可放置15条腿  
>> instId | String | 产品ID，例如："BTC-USDT-SWAP"  
>> sz | String | 委托数量  
>> side | String | 询价单方向  
有效值为`buy`和`sell`。  
>> posSide | String | 持仓方向  
单向持仓模式下默认为`net`。如未指定，则返回""，相当于`net`。  
在双向持仓模式下仅可选择`long`或`short`。 如未指定，则返回""，对应于为交易开新仓位的方向（买入=>`long`，卖出=>`short`）。  
仅适用交割、永续。  
>> tgtCcy | String | 委托数量的类型  
定义`sz`属性的单位。仅适用于
instType=`SPOT`。有效值为`base_ccy`和`quote_ccy`。未指定时，默认为`base_ccy`。  
  
### 获取报价单信息

获取用户发出的或收到的报价单信息

#### 限速: 2次/2s

#### 限速规则：UserID

#### HTTP Requests

`GET /api/v5/rfq/quotes`

> 请求示例
    
    
    GET /api/v5/rfq/quotes
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
rfqId | String | 否 | 询价单ID  
clRfqId | String | 否 | 询价单自定义ID， 当 clRfqId 和 rfqId 都传时，以 rfqId 为准。  
quoteId | String | 否 | 报价单ID  
clQuoteId | String | 否 | 报价单自定义ID，当 clRfqId 和 rfqId 都传时，以 rfqId 为准。  
state | String | 否 | 报价单的状态  
有效值为 `active` `canceled` `pending_fill` `filled` `expired` `failed`  
beginId | String | 否 | 请求的起始报价单ID，请求此ID之后（更新的数据）的分页内容，不包括 beginId  
endId | String | 否 | 请求的结束报价单ID，请求此ID之前（更旧的数据）的分页内容，不包括 endId  
limit | String | 否 | 返回结果的数量，最大为100，默认100条  
  
> 返回示例
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
            {
                "validUntil":"1608997227834",
                "uTime":"1608267227834",
                "cTime":"1608267227834",
                "legs":[
                    {
                        "px":"46000",
                        "sz":"25",
                        "instId":"BTC-USD-220114-25000-C",
                        "side":"sell",
                        "posSide": "long",
                        "tgtCcy":""
                    },
                    {
                        "px":"45000",
                        "sz":"25",
                        "instId":"BTC-USDT",
                        "side":"buy",
                        "posSide": "long",
                        "tgtCcy":"base_ccy"
                    }
                ],
                "quoteId":"25092",
                "rfqId":"18753",
                "quoteSide":"sell",
                "state":"canceled",
                "reason":"mmp_canceled",
                "clQuoteId":"cq001",
                "clRfqId":"cr001",
                "tag":"123456",
                "traderCode":"Trader1"
            }
        ]
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
code | String | 结果代码，0 表示成功。  
msg | String | 错误信息，如果代码不为 0，则不为空。  
data | Array of objects | 包含结果的数组  
> cTime | String | 报价单创建时间，Unix时间戳的毫秒数格式  
> uTime | String | 报价单状态更新时间，Unix时间戳的毫秒数格式。  
> state | String | 报价单的状态  
`active` `canceled` `pending_fill` `filled` `expired` `failed`  
> reason | String | 状态原因. 有效值包括 `mmp_canceled`.  
> validUntil | String | 报价单的过期时间，Unix时间戳的毫秒数格式。  
> rfqId | String | 询价单ID  
> clRfqId | String | 询价单自定义ID，为客户敏感信息，不会公开，对报价方返回""。  
> quoteId | String | 报价单ID  
> clQuoteId | String | 报价单自定义ID，为客户敏感信息，不会公开，对询价方返回""。  
> tag | String | 报价单标签，与此报价单关联的大宗交易将有相同的标签。  
> traderCode | String | 报价方唯一标识代码，报价时 Anonymous 设置为 `True` 时不可见。  
> quoteSide | String |
> 报价单方向，`buy`或者`sell`。当报价单方向为`buy`，对maker来说，执行方向与legs里的方向相同，对taker来说相反。反之同理  
> legs | Array of objects | 组合交易  
>> instId | String | 产品ID  
>> sz | String | 委托数量  
>> px | String | 委托价格.  
>> side | String | 报价单方向  
>> posSide | String | 持仓方向  
单向持仓模式下默认为`net`。如未指定，则返回""，相当于`net`。  
在双向持仓模式下仅可选择`long`或`short`。 如未指定，则返回""，对应于为交易开新仓位的方向（买入=>`long`，卖出=>`short`）。  
仅适用交割、永续。  
>> tgtCcy | String | 委托数量的类型  
定义`sz`属性的单位。仅适用于
instType=`SPOT`。有效值为`base_ccy`和`quote_ccy`。未指定时，默认为`base_ccy`。  
  
### 获取大宗交易信息

获取该用户大宗交易成交信息

#### 限速: 5次/2s

#### 限速规则：UserID

#### HTTP Requests

`GET /api/v5/rfq/trades`

> 请求示例
    
    
    GET /api/v5/rfq/trades
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
rfqId | String | 否 | 询价单ID  
clRfqId | String | 否 | 由用户设置的询价单ID. 如果 `clRfqId` 和 `rfqId` 都通过了，rfqId 将被视为主要  
quoteId | String | 否 | 报价单ID  
blockTdId | String | 否 | 大宗交易ID  
clQuoteId | String | 否 | 由用户设置的报价单ID。如果同时传递了 `clQuoteId` 和 `quoteId`，则 quoteId
将被视为主要标识符  
state | String | 否 | 询价单的状态  
`active` `canceled` `pending_fill` `filled` `expired` `failed` `traded_away`  
`traded_away` 仅适用于报价方  
beginId | String | 否 | 请求的起始大宗交易ID，请求此ID之后（更新的数据）的分页内容，不包括 beginId  
endId | String | 否 | 请求的结束大宗交易ID，请求此ID之前（更旧的数据）的分页内容，不包括 endId  
beginTs | String | 否 | 用开始时间戳筛选交易执行时间（UTC时区）。Unix时间戳的毫秒数格式，例如 1597026383085。  
endTs | String | 否 | 用结束时间戳筛选交易执行时间（UTC时区）。Unix时间戳的毫秒数格式，例如 1597026383085。  
limit | String | 否 | 返回结果的数量，最大为100，默认100条。  
如果请求范围内的交易数量大于100，则返回该范围内最近的100笔交易。  
  
> 返回示例
    
    
    {
        "code": "0",
        "msg": "",
        "data": [
            {
                "rfqId": "123456",
                "clRfqId": "",
                "quoteId": "0T5342O",
                "clQuoteId": "",
                "blockTdId": "439127542058958848",
                "tag": "123456",
                "legs": [
                    {
                        "instId": "BTC-USDT",
                        "side": "sell",
                        "sz": "0.666",
                        "px": "100",
                        "tradeId": "439127542058958850",
                        "fee": "-0.0333",
                        "feeCcy": "USDT"
                    }
                ],
                "cTime": "1650968164900",
                "tTraderCode": "SATS",
                "mTraderCode": "MIKE"
            },
            {
                "rfqId": "1234567",
                "clRfqId": "",
                "quoteId": "0T533T0",
                "clQuoteId": "",
                "blockTdId": "439121886014849024",
                "legs": [
                    {
                        "instId": "BTC-USDT",
                        "side": "sell",
                        "sz": "0.532",
                        "px": "100",
                        "tradeId": "439121886014849026",
                        "fee": "-0.0266",
                        "feeCcy": "USDT"
                    }
                ],
                "cTime": "1650966816550",
                "tTraderCode": "SATS",
                "mTraderCode": "MIKE"
            }
        ]
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
code | String | 结果代码，0 表示成功。  
msg | String | 错误信息，如果代码不为 0，则不为空。  
data | Array of objects | 包含结果的对象数组  
> cTime | String | 执行创建的时间，Unix时间戳的毫秒数格式。  
> rfqId | String | 询价单ID  
> clRfqId | String | 询价单自定义ID，为客户敏感信息，不会公开，对报价方返回""。  
> quoteId | String | 报价单ID  
> clQuoteId | String | 报价单自定义ID，为客户敏感信息，不会公开，对询价方返回""。  
> blockTdId | String | 大宗交易ID  
> tag | String | 交易标签，大宗交易将有与其对应的询价单或报价单相同的标签。  
> tTraderCode | String | 询价方唯一标识代码，询价时 anonymous 设置为 `true` 时不可见  
> mTraderCode | String | 报价方唯一标识代码。报价时 anonymous 设置为 `true` 时不可见  
> legs | Array of objects | 组合交易  
>> instId | String | 产品ID  
>> px | String | 成交价格  
>> sz | String | 成交数量  
>> side | String | 询价单方向，buy 或者 sell。  
>> fee | String | 手续费，正数代表平台返佣 ，负数代表平台扣除  
>> feeCcy | String | 手续费币种  
>> tradeId | String | 最新的成交Id  
  
### 获取大宗交易公共成交数据

获取最近执行的大宗交易。

#### 限速: 5次/2s

#### 限速规则：IP

#### HTTP Requests

`GET /api/v5/rfq/public-trades`

> 请求示例
    
    
    GET /api/v5/rfq/public-trades
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
beginId | String | 否 | 请求的起始大宗交易ID，请求此ID之后（更新的数据）的分页内容，不包括 beginId  
endId | String | 否 | 请求的结束大宗交易ID，请求此ID之前（更旧的数据）的分页内容，不包括 endId  
limit | String | 否 | 返回结果的数量，最大为100，默认100条  
  
> 返回示例
    
    
    {
        "code": "0",
        "msg": "",
        "data": [
            {
                "blockTdId": "439161457415012352",
                "legs": [
                    {
                        "instId": "BTC-USD-210826",
                        "side": "sell",
                        "sz": "100",
                        "px": "11000",
                        "tradeId": "439161457415012354"
                    },
                    {
                        "instId": "BTC-USD-SWAP",
                        "side": "sell",
                        "sz": "100",
                        "px": "50",
                        "tradeId": "439161457415012355"
                    },
                    {
                        "instId": "BTC-USDT",
                        "side": "buy",
                        "sz": "0.1", //for public feed, spot "sz" is in baseccy
                        "px": "10.1",
                        "tradeId": "439161457415012356"
                    },
                    {
                        "instId": "BTC-USD-210326-60000-C",
                        "side": "buy",
                        "sz": "200",
                        "px": "0.008",
                        "tradeId": "439161457415012357"
                    },
                    {
                        "instId": "BTC-USD-220930-5000-P",
                        "side": "sell",
                        "sz": "200",
                        "px": "0.008",
                        "tradeId": "439161457415012360"
                    },
                    {
                        "instId": "BTC-USD-220930-10000-C",
                        "side": "sell",
                        "sz": "200",
                        "px": "0.008",
                        "tradeId": "439161457415012361"
                    },
                    {
                        "instId": "BTC-USD-220930-10000-P",
                        "side": "sell",
                        "sz": "200",
                        "px": "0.008",
                        "tradeId": "439161457415012362"
                    },
                    {
                        "instId": "ETH-USD-220624-100100-C",
                        "side": "sell",
                        "sz": "100",
                        "px": "0.008",
                        "tradeId": "439161457415012363"
                    }
                ],
                "cTime": "1650976251241"
            }
        ]
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
code | String | 结果代码，0 表示成功。  
msg | String | 错误信息，如果代码不为 0，则不为空。  
data | Array of objects | 包含结果的对象数组.  
> cTime | String | 执行创建的时间，Unix时间戳的毫秒数格式。  
> blockTdId | String | 大宗交易ID  
> legs | Array of objects | 组合交易  
>> instId | String | 产品ID  
>> px | String | 成交价格  
>> sz | String | 成交数量  
>> side | String | 询价单方向，从 Taker的视角看  
>> tradeId | String | 最新成交ID  
  
## WebSocket 私有频道

### 询价频道

获取用户自身发送或接收的询价信息。每当用户自身发送或接收询价时，数据都将被推送。

> 请求示例
    
    
    {
      "op": "subscribe",
      "args": [
        {
          "channel": "rfqs"
        }
      ]
    }
    

#### 请求参数

参数名 | 类型 | 是否必填 | 描述  
---|---|---|---  
op | String | 是 | 操作, `subscribe` `unsubscribe`  
args | Array | 是 | 请求订阅的频道列表  
> channel | String | 是 | 频道名, `rfqs`  
  
> 成功返回示例
    
    
    {
      "event": "subscribe",
      "arg": {
        "channel": "rfqs"
      }
    }
    

> 失败返回示例
    
    
    {
      "event": "error",
      "code": "60012",
      "msg": "Invalid request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"rfqs\"}]}"
    }
    

#### 返回参数

参数名 | 类型 | 是否必填 | 描述  
---|---|---|---  
event | String | 是 | 操作, `subscribe` `unsubscribe` `error`  
arg | Object | 否 | 订阅的频道  
> channel | String | 是 | 频道名, `rfqs`  
code | String | 否 | 错误码  
msg | String | 否 | 错误消息  
  
> 推送示例
    
    
    {
        "arg":{
            "channel":"rfqs",
            "uid": "77982378738415879"
        },
        "data":[
            {
                "cTime":"1611033737572",
                "uTime":"1611033737572",
                "traderCode":"DSK2",
                "rfqId":"22534",
                "clRfqId":"",
                "tag":"123456",
                "state":"active",
                "validUntil":"1611033857557",
                "allowPartialExecution": false,
                "counterparties":[
                    "DSK4",
                    "DSK5"
                ],
                "legs":[
                    {
                        "instId":"BTCUSD-211208-36000-C",
                        "sz":"25.0",
                        "side":"buy",
                        "posSide": "long",
                        "tgtCcy":""
                    },
                    {
                        "instId":"ETHUSD-211208-45000-C",
                        "sz":"25.0",
                        "side":"sell",
                        "posSide": "long",
                        "tgtCcy":""
                    }
                ]
            }
        ]
    }
    

#### 推送数据参数

**参数名** | **类型** | **描述**  
---|---|---  
arg | Object | 订阅成功的频道  
> channel | String | 频道名  
> uid | String | 用户标识  
data | Array | 订阅的数据  
> cTime | String | 询价单创建时间，Unix时间戳的毫秒数格式。  
> uTime | String | 询价单状态更新时间，Unix时间戳的毫秒数格式。  
> state | String | 询价单的状态  
有效值为 `active` `canceled` `filled` `expired` or `failed`  
> counterparties | Array of Strings | 报价方列表  
> validUntil | String | 询价单的过期时间，Unix时间戳的毫秒数格式。  
> clRfqId | String | 询价单自定义ID，为客户敏感信息，不会公开，对报价方返回""。  
> tag | String | 询价单标签，与此询价单关联的大宗交易将有相同的标签。  
> traderCode | String | 询价方唯一标识代码，询价时 Anonymous 设置为 `True` 时不可见  
> rfqId | String | 询价单ID  
> allowPartialExecution | Boolean |
> RFQ是否可以被部分执行，如果腿的比例和原RFQ一致。>有效值为`true`或`false`。  
> legs | Array of objects | 组合交易  
>> instId | String | 产品ID  
>> sz | String | 委托数量  
>> side | String | 询价单方向  
>> posSide | String | 持仓方向  
单向持仓模式下默认为`net`。如未指定，则返回""，相当于`net`。  
在双向持仓模式下仅可选择`long`或`short`。 如未指定，则返回""，对应于为交易开新仓位的方向（买入=>`long`，卖出=>`short`）。  
仅适用交割、永续。  
>> tgtCcy | String | 委托数量的类型  
定义`sz`属性的单位。仅适用于
instType=`SPOT`。有效值为`base_ccy`和`quote_ccy`。未指定时，默认为`base_ccy`。  
  
### 报价频道

获取用户自身发送或接收的报价信息。每当用户自身发送或接收报价时，数据都将被推送。

> 请求示例
    
    
    {
      "op": "subscribe",
      "args": [
        {
          "channel": "quotes"
        }
      ]
    }
    

#### 请求参数

参数名 | 类型 | 是否必填 | 描述  
---|---|---|---  
op | String | 是 | 操作, `subscribe` `unsubscribe`  
args | Array | 是 | 请求订阅的频道列表  
> channel | String | 是 | 频道名, `quotes`  
  
> 成功返回示例
    
    
    {
      "event": "subscribe",
      "arg": {
        "channel": "quotes"
      }
    }
    

> 失败返回示例
    
    
    {
      "event": "error",
      "code": "60012",
      "msg": "Invalid request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"quotes\"}]}"
    }
    

#### 返回参数

参数名 | 类型 | 是否必填 | 描述  
---|---|---|---  
event | String | 是 | 操作, `subscribe` `unsubscribe` `error`  
arg | Object | 否 | 订阅的频道  
> channel | String | 是 | 频道名, `quotes`  
code | String | 否 | 错误码  
msg | String | 否 | 错误消息  
  
> 推送示例
    
    
    {
        "arg":{
            "channel":"quotes",
            "uid": "77982378738415879"
        },
        "data":[
            {
                "validUntil":"1608997227854",
                "uTime":"1608267227834",
                "cTime":"1608267227834",
                "legs":[
                    {
                        "px":"0.0023",
                        "sz":"25.0",
                        "instId":"BTC-USD-220114-25000-C",
                        "side":"sell",
                        "posSide": "long",
                        "tgtCcy":""
    
                    },
                    {
                        "px":"0.0045",
                        "sz":"25",
                        "instId":"BTC-USD-220114-35000-C",
                        "side":"buy",
                        "posSide": "long",
                        "tgtCcy":""
    
                    }
                ],
                "quoteId":"25092",
                "rfqId":"18753",
                "tag":"123456",
                "traderCode":"SATS",
                "quoteSide":"sell",
                "state":"canceled",
                "reason":"mmp_canceled",
                "clQuoteId":""
            }
        ]
    }
    

#### 推送数据参数

**参数名** | **类型** | **描述**  
---|---|---  
arg | Object | 订阅成功的频道  
> channel | String | 频道名  
> uid | String | 账户ID，账户uid和app上的一致  
data | Array | 订阅的数据  
> cTime | String | 报价单创建时间，Unix时间戳的毫秒数格式。  
> uTime | String | 报价单状态更新时间，Unix时间戳的毫秒数格式。  
> state | String | 报价单的状态  
有效值为 `active` `canceled` `filled` `expired` `failed`  
> reason | String | 状态原因,有效值包括`mmp_canceled`  
> validUntil | String | 报价单的过期时间，Unix时间戳的毫秒数格式。  
> rfqId | String | 询价单ID  
> clRfqId | String | 询价单自定义ID，为客户敏感信息，不会公开，对报价方返回""。  
> quoteId | String | 报价单ID  
> clQuoteId | String | 报价单自定义ID，为客户敏感信息，不会公开，对询价方返回""。  
> tag | String | 报价单标签，与此报价单关联的大宗交易将有相同的标签。  
> traderCode | String | 报价方唯一标识代码，报价时 Anonymous 设置为 `True` 时不可见。  
> quoteSide | String |
> 报价单方向，`buy`或者`sell`。当报价单方向为`buy`，对maker来说，执行方向与legs里的方向相同，对taker来说相反。反之同理。  
> legs | Array of objects | 组合交易  
>> instId | String | 产品ID  
>> sz | String | 委托数量  
>> px | String | 委托价格  
>> side | String | 报价单方向  
>> posSide | String | 持仓方向  
单向持仓模式下默认为`net`。如未指定，则返回""，相当于`net`。  
在双向持仓模式下仅可选择`long`或`short`。 如未指定，则返回""，对应于为交易开新仓位的方向（买入=>`long`，卖出=>`short`）。  
仅适用交割、永续。  
>> tgtCcy | String | 委托数量的类型  
定义`sz`属性的单位。仅适用于
instType=`SPOT`。有效值为`base_ccy`和`quote_ccy`。未指定时，默认为`base_ccy`。  
  
### 大宗交易频道

获取用户自身的大宗交易信息。同一大宗交易中的所有腿都包含在同一更新中。只要用户自身作为交易对手进行大宗交易，数据都将被推送。

> 请求示例
    
    
    {
      "op": "subscribe",
      "args": [
        {
          "channel": "struc-block-trades"
        }
      ]
    }
    

#### 请求参数

参数名 | 类型 | 是否必填 | 描述  
---|---|---|---  
op | String | 是 | 操作, `subscribe` `unsubscribe`  
args | Array | 是 | 请求订阅的频道列表  
> channel | String | 是 | 频道名, `struc-block-trades`  
  
> 成功返回示例
    
    
    {
      "event": "subscribe",
      "arg": {
        "channel": "struc-block-trades"
      }
    }
    

> 失败返回示例
    
    
    {
      "event": "error",
      "code": "60012",
      "msg": "Invalid request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"struc-block-trades\""}]}"
    }
    

#### 返回参数

参数名 | 类型 | 是否必填 | 描述  
---|---|---|---  
event | String | 是 | 操作, `subscribe` `unsubscribe` `error`  
arg | Object | 否 | 订阅的频道  
> channel | String | 是 | 频道名, `struc-block-trades`  
code | String | 否 | 错误码  
msg | String | 否 | 错误消息  
  
> 推送示例
    
    
    {
        "arg":{
            "channel":"struc-block-trades",
            "uid": "77982378738415879"
        },
        "data":[
            {
                "cTime":"1608267227834",
                "rfqId":"18753",
                "clRfqId":"",
                "quoteId":"25092",
                "clQuoteId":"",
                "blockTdId":"180184",
                "tag":"123456",
                "tTraderCode":"ANAND",
                "mTraderCode":"WAGMI",
                "legs":[
                    {
                        "px":"0.0023",
                        "sz":"25.0",
                        "instId":"BTC-USD-20220630-60000-C",
                        "side":"sell",
                        "fee":"0.1001",
                        "feeCcy":"BTC",
                        "tradeId":"10211",
                        "tgtCcy":""
    
                    },
                    {
                        "px":"0.0033",
                        "sz":"25",
                        "instId":"BTC-USD-20220630-50000-C",
                        "side":"buy",
                        "fee":"0.1001",
                        "feeCcy":"BTC",
                        "tradeId":"10212",
                        "tgtCcy":""
    
                    }
                ]
            }
        ]
    }
    

#### 推送数据参数

**参数名** | **类型** | **描述**  
---|---|---  
arg | Object | 订阅成功的频道  
> channel | String | 频道名  
> uid | String | 用户标识  
data | Array | 订阅的数据  
> cTime | String | 执行创建的时间戳，Unix 时间戳格式，以毫秒为单位。  
> rfqId | String | RFQ ID.  
> clRfqId | String | 由用户设置的 RFQ ID。 此属性被视为客户端敏感信息。 不会暴露给 Maker，只返回空字符串“”给
> Maker。  
> quoteId | String | Quote ID.  
> clQuoteId | String | 由用户设置的 Quote ID。 此属性被视为客户端敏感信息。 不会暴露给 Taker，只为 Taker
> 返回空字符串“”。  
> blockTdId | String | 大宗交易ID  
> tag | String | 交易标签，大宗交易将有与其对应的询价单或报价单相同的标签。  
> tTraderCode | String | 报价方唯一标识代码。询价时 Anonymous 设置为 `True` 时不可见。  
> mTraderCode | String | 询价方唯一标识代码。报价时 Anonymous 设置为 `True` 时不可见。  
> legs | Array of objects | 组合交易  
>> instId | String | 产品ID  
>> px | String | 成交价格  
>> sz | String | 成交数量  
>> side | String | 询价单方向  
>> tgtCcy | String | 委托数量的类型  
定义`sz`属性的单位。仅适用于
instType=`SPOT`。有效值为`base_ccy`和`quote_ccy`。未指定时，默认为`base_ccy`。  
>> fee | String | 手续费，正数代表平台返佣 ，负数代表平台扣除。  
>> feeCcy | String | 手续费币种  
>> tradeId | String | 最新成交Id  
  
## WebSocket 公共频道

### 公共大宗交易频道

获取欧易的最新大宗交易信息。同一大宗交易中的所有腿都包含在同一更新中。每当欧易有大宗交易时，数据都将被推送。

> 请求示例
    
    
    {
      "op": "subscribe",
      "args": [
        {
          "channel": "public-struc-block-trades"
        }
      ]
    }
    

#### 请求参数

参数名 | 类型 | 是否必填 | 描述  
---|---|---|---  
op | String | 是 | 操作, `subscribe` `unsubscribe`  
args | Array | 是 | 请求订阅的频道列表  
> channel | String | 是 | 频道名, `public-struc-block-trades`  
  
> 成功返回示例
    
    
    {
      "event": "subscribe",
      "arg": {
        "channel": "public-struc-block-trades"
      }
    }
    

> 失败返回示例
    
    
    {
      "event": "error",
      "code": "60012",
      "msg": "Invalid request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"public-struc-block-trades\""}]}"
    }
    

#### 返回参数

参数名 | 类型 | 是否必填 | 描述  
---|---|---|---  
event | String | 是 | 操作, `subscribe` `unsubscribe` `error`  
arg | Object | 否 | 订阅的频道  
> channel | String | 是 | 频道名, `public-struc-block-trades`  
code | String | 否 | 错误码  
msg | String | 否 | 错误消息  
  
> 推送示例
    
    
    {
        "arg":{
            "channel":"public-struc-block-trades"
        },
        "data":[
            {
    
                "cTime":"1608267227834",
                "blockTdId":"1802896",
                "legs":[
                    {
                        "px":"0.323",
                        "sz":"25.0",
                        "instId":"BTC-USD-20220114-13250-C",
                        "side":"sell",
                        "tradeId":"15102"
                    },
                    {
                        "px":"0.666",
                        "sz":"25",
                        "instId":"BTC-USD-20220114-21125-C",
                        "side":"buy",
                        "tradeId":"15103"
                    }
                ]
            }
        ]
    }
    

#### 推送数据参数

**参数名** | **类型** | **描述**  
---|---|---  
arg | Object | 订阅成功的频道  
> channel | String | 频道名  
data | Array | 订阅的数据  
> cTime | String | 执行创建的时间戳，Unix 时间戳格式，以毫秒为单位。  
> blockTdId | String | 大宗交易ID  
> legs | Array of objects | 组合交易  
>> instId | String | 产品名Id  
>> px | String | 成交价格  
>> sz | String | 成交数量  
>> side | String | 询价单方向，从 Taker的视角看  
>> tradeId | String | 最新成交Id  
  
### 公共大宗交易单腿交易频道

获取欧易的最新大宗交易单腿交易信息。大宗交易中的每条腿都在单独的更新中推送。只要有大宗交易，数据都将被推送。

> 请求示例
    
    
    {
      "op": "subscribe",
      "args": [
        {
          "channel": "public-block-trades",
          "instId": "BTC-USDT-SWAP"
        }
      ]
    }
    

#### 请求参数

参数名 | 类型 | 是否必填 | 描述  
---|---|---|---  
op | String | 是 | 操作, `subscribe` `unsubscribe`  
args | Array | 是 | 请求订阅的频道列表  
> channel | String | 是 | 频道名, `public-block-trades`  
> instId | String | 是 | 产品 ID, e.g., BTC-USDT-SWAP.  
  
> 成功返回示例
    
    
    {
      "event": "subscribe",
      "arg": {
        "channel": "public-block-trades",
        "instId": "BTC-USDT-SWAP"
      }
    }
    

> 失败返回示例
    
    
    {
      "event": "error",
      "code": "60012",
      "msg": "Invalid request: {\"op\": \"subscribe\", \"args\":[{ \"channel\" : \"public-block-trades\""}]}"
    }
    

#### 返回参数

参数名 | 类型 | 是否必需 | 描述  
---|---|---|---  
event | String | 是 | 操作, `subscribe` `unsubscribe` `error`  
arg | Object | 否 | 订阅的频道  
> channel | String | 是 | 频道名, `public-block-trades`  
> instId | String | 是 | 产品 ID, e.g., BTC-USDT-SWAP.  
code | String | 否 | 错误码  
msg | String | 否 | 错误消息  
  
> 推送示例
    
    
    {
      "arg": {
        "channel": "public-block-trades",
        "instId": "BTC-USDT-SWAP"
      },
      "data": [
        {
          "instId": "BTC-USDT-SWAP",
          "tradeId": "482866817984270338",
          "px": "21950",
          "sz": "100",
          "side": "buy",
          "ts": "1661396420687"
        }
      ]
    }
    

#### 推送数据参数

**参数名** | **类型** | **描述**  
---|---|---  
arg | Object | 订阅成功的频道  
> channel | String | 频道名  
> instId | String | 产品 ID, e.g., BTC-USDT-SWAP.  
data | Array | 公共大宗交易单腿交易信息  
> instId | String | 产品 ID, e.g., BTC-USDT-SWAP.  
> tradeId | String | 交易 ID, 由柜台提供.  
> px | String | 该单腿交易价格.  
> sz | String | 交易数量.  
> side | String | 交易方向, buy, sell, 从taker角度看.  
> ts | String | 成交时间, 时间戳格式，以毫秒为单位. e.g. 1597026383085.  
  
### 大宗交易行情频道

获取最近24小时大宗交易量  

当发生成交事件时触发推送，此外，也会根据订阅维度每隔5分钟推送一次

> 请求示例
    
    
    {
        "op": "subscribe",
        "args": [{
            "channel": "block-tickers",
            "instId": "BTC-USDT"
        }]
    }
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
op | String | 是 | 操作，`subscribe` `unsubscribe`  
args | Array | 是 | 请求订阅的频道列表  
> channel | String | 是 | 频道名，`block-tickers`  
> instId | String | 是 | 产品ID  
  
> 成功返回示例
    
    
    {
        "event": "subscribe",
        "arg": {
            "channel": "block-tickers",
            "instId": "LTC-USD-200327"
        }
    }
    

> 失败返回示例
    
    
    {
        "event": "error",
        "code": "60012",
        "msg": "Invalid request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"block-tickers\", \"instId\" : \"LTC-USD-200327\"}]}"
    }
    

#### 返回参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
event | String | 是 | 事件，`subscribe` `unsubscribe` `error`  
arg | Object | 否 | 订阅的频道  
> channel | String | 是 | 频道名 `block-tickers`  
> instId | String | 是 | 产品ID  
code | String | 否 | 错误码  
msg | String | 否 | 错误消息  
  
> 推送示例
    
    
    {
        "arg": {
            "channel": "block-tickers"
        },
        "data": [
            {
                "instType": "SWAP",
                "instId": "LTC-USD-SWAP",
                "volCcy24h": "0",
                "vol24h": "0",
                "ts": "1597026383085"
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
instId | String | 产品ID  
instType | String | 产品类型  
volCcy24h | String | 24小时成交量，以`币`为单位  
如果是`衍生品`合约，数值为交易货币的数量。  
如果是`币币/币币杠杆`，数值为计价货币的数量。  
vol24h | String | 24小时成交量，以`张`为单位  
如果是`衍生品`合约，数值为合约的张数。  
如果是`币币/币币杠杆`，数值为交易货币的数量。  
ts | String | 数据产生时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
  
# REST API

## 请求验证

### 生成APIKey

在对任何请求进行签名之前，您必须通过交易网站创建一个APIKey。创建APIKey后，您将获得3个必须记住的信息：

  * APIKey
  * SecretKey
  * Passphrase

APIKey和SecretKey将由平台随机生成和提供，Passphrase将由您提供以确保API访问的安全性。平台将存储Passphrase加密后的哈希值进行验证，但如果您忘记Passphrase，则无法恢复，请您通过交易网站重新生成新的APIKey。  
  

API key 有如下3种权限，一个 API key 可以有一个或多个权限。

  * 读取 - 查询账单和历史记录等账户信息；
  * 提现 - 可以进行提币，查询账单和历史记录等账户信息；
  * 交易 - 可以下单和撤单，查询账单和历史记录等账户信息。

每个APIKey最多可绑定20个IP地址；未绑定IP且拥有交易或提币权限的APIKey，将在闲置14天之后自动删除。

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
'/api/v5/account/balance?ccy=BTC', SecretKey))`

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
该接口支持带单合约的下单，但不支持为带单合约平仓

#### 限速：60次/2s

#### 跟单交易带单合约的限速：1次/2s

#### 限速规则（期权以外）：UserID + Instrument ID

#### 限速规则（只限期权）：UserID + Instrument Family

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
side | String | 是 | 订单方向  
`buy`：买， `sell`：卖  
posSide | String | 可选 | 持仓方向  
在双向持仓模式下必填，且仅可选择 `long` 或 `short`。 仅适用交割、永续。  
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
tgtCcy | String | 否 | 市价单委托数量`sz`的单位，仅适用于`币币`市价订单  
`base_ccy`: 交易货币 ；`quote_ccy`：计价货币  
买单默认`quote_ccy`， 卖单默认`base_ccy`  
banAmend | Boolean | 否 | 是否禁止币币市价改单，true 或 false，默认false  
为true时，余额不足时，系统不会改单，下单会失败，仅适用于币币市价单  
tpTriggerPx | String | 否 | 止盈触发价，如果填写此参数，必须填写 止盈委托价  
tpOrdPx | String | 否 | 止盈委托价，如果填写此参数，必须填写 止盈触发价  
委托价格为-1时，执行市价止盈  
slTriggerPx | String | 否 | 止损触发价，如果填写此参数，必须填写 止损委托价  
slOrdPx | String | 否 | 止损委托价，如果填写此参数，必须填写 止损触发价  
委托价格为-1时，执行市价止损  
tpTriggerPxType | String | 否 | 止盈触发价类型  
`last`：最新价格  
`index`：指数价格  
`mark`：标记价格  
默认为`last`  
slTriggerPxType | String | 否 | 止损触发价类型  
`last`：最新价格  
`index`：指数价格  
`mark`：标记价格  
默认为`last`  
quickMgnType | String | 否 | 一键借币类型，仅适用于杠杆逐仓的一键借币模式：  
`manual`：手动，`auto_borrow`： 自动借币，`auto_repay`： 自动还币  
默认是`manual`：手动  
  
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
sMsg | String | 事件执行失败或成功时的msg  
tdMode  
交易模式，下单时需要指定  
**简单交易模式：**  
\- 币币和期权买方：cash  
**单币种保证金模式：**  
\- 逐仓杠杆：isolated  
\- 全仓杠杆：cross  
\- 币币：cash  
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
clOrdId是用户自定义的唯一ID用来识别订单。如果在请求参数中传入了，那它一定会在返回参数内，并且可以用于查询订单，撤销订单，修改订单等接口。
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
对于同一产品，所有反方向挂单的张数加上当前只减仓下单张数，不能超过持仓张数  
仅适用于`单币种账户模式`和`跨币种账户模式`  
仅适用于`币币杠杆`，以及买卖模式下的`交割/永续`  tgtCcy  
市价单委托数量`sz`的单位：仅适用于币币市价下单交易。  
交易货币：base_ccy  
计价货币：quote_ccy  
您在使用交易货币买入或者计价货币卖出时，请知晓：  
1.如果您输入的数量大于当前可买或者可卖的数量，系统将按照您的最大可买或者可卖数量帮您完成交易，如果您希望按照指定数量成交，那您可以尝试使用限价单，等待市场价格波动到锁定的余额可以买入或卖出您指定的数量。  
2.如果您输入的数量不大于当前可买或者可卖的数量，那当市场价格波动过大时，锁定的余额可能没办法买入您输入的交易货币数量或卖出您输入的计价货币数量，为保证您的交易体验，我们基于【能买多少买多少】或者【能卖多少卖多少】的原则，更改下单的数量帮您完成交易。此外，我们将尽量多锁定一点余额来规避更改下单数量的情况。  
2.1 交易币买入例子：  
以市价下单 买入 10个LTC为例，用户可买为11个，此时 10 < 11，挂单成功。当LTC-USDT的市价为200，用户被锁定余额为3,000
USDT，200*10 < 3,000，最终成交10个LTC； 若市场波动过大，LTC-USDT的市价为400，此时400*10 >
3,000，当用户被锁定的余额不够买入下单指定的交易货币数量时，系統使用用户被锁定的最大余额3,000 USDT下单买入，最终成交 3,000/400 =
7.5个 LTC。  
2.2 计价币卖出例子：  
以市价下单 卖出 1,000USDT为例，用户可卖为1,200USDT，1,000 < 1,200，挂单成功。LTC-
USDT的市价为200，用户被锁定的余额为6个LTC，最终成交5个LTC； 若市场波动过大，LTC-USDT的市价为100，100*6 <
1,000，当用户被锁定的余额不够卖出下单指定的计价货币数量时，系統使用用户被锁定的最大余额6个LTC下单，最终成交 6 * 100 = 600 USDT。
px  
期权下单时，委托价格需为 tickSz 的整数倍。  
当不为整数倍时，取值规则以tickSz取 0.0005 为例：  
当委托价格对0.0005的余数大于0.00025或者委托价格小于0.0005时，向上取；  
当委托价格对0.0005的余数小于等于0.00025，且委托价格大于0.0005时，向下取。

### 批量下单

每次最多可以批量提交20个新订单。请求参数应该按数组格式传递。  
该接口支持带单合约的下单，但不支持为带单合约平仓

#### 限速：300个/2s

#### 跟单交易带单合约的限速：1个/2s

#### 限速规则（期权以外）：UserID + Instrument ID

#### 限速规则（只限期权）：UserID + Instrument Family

与其他限速按接口调用次数不同，该接口限速按订单的总个数限速。如果单次批量请求中只有一个元素，则算在单个`下单`限速中。

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
ccy | String | 否 | 保证金币种，仅适用于`单币种保证金模式`下的`全仓杠杆`订单  
clOrdId | String | 否 | 客户自定义订单ID  
字母（区分大小写）与数字的组合，可以是纯字母、纯数字且长度要在1-32位之间。  
tag | String | 否 | 订单标签  
字母（区分大小写）与数字的组合，可以是纯字母、纯数字且长度要在1-16位之间。  
side | String | 是 | 订单方向 `buy`：买， `sell`：卖  
posSide | String | 可选 | 持仓方向  
在双向持仓模式下必填，且仅可选择 `long` 或 `short`。 仅适用交割、永续。  
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
tgtCcy | String | 否 | 市价单委托数量`sz`的单位，仅适用于`币币`市价订单  
`base_ccy`: 交易货币 ；`quote_ccy`：计价货币  
买单默认`quote_ccy`， 卖单默认`base_ccy`  
banAmend | Boolean | 否 | 是否禁止币币市价改单，true 或 false，默认false  
为true时，余额不足时，系统不会改单，下单会失败，仅适用于币币市价单  
tpTriggerPx | String | 否 | 止盈触发价，如果填写此参数，必须填写 止盈委托价  
tpOrdPx | String | 否 | 止盈委托价，如果填写此参数，必须填写 止盈触发价  
委托价格为-1时，执行市价止盈  
slTriggerPx | String | 否 | 止损触发价，如果填写此参数，必须填写 止损委托价  
slOrdPx | String | 否 | 止损委托价，如果填写此参数，必须填写 止损触发价  
委托价格为-1时，执行市价止损  
tpTriggerPxType | String | 否 | 止盈触发价类型  
`last`：最新价格  
`index`：指数价格  
`mark`：标记价格  
默认为`last`  
slTriggerPxType | String | 否 | 止损触发价类型  
`last`：最新价格  
`index`：指数价格  
`mark`：标记价格  
默认为`last`  
quickMgnType | String | 否 | 一键借币类型，仅适用于杠杆逐仓的一键借币模式：  
`manual`：手动，`auto_borrow`： 自动借币，`auto_repay`： 自动还币  
默认是`manual`：手动  
  
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
sMsg | String | 事件执行失败或成功时的msg  
在组合保证金账户模式下，或者全部成功，或者全部失败。

### 撤单

撤销之前下的未完成订单。

#### 限速：60次/2s

#### 限速规则（期权以外）：UserID + Instrument ID

#### 限速规则（只限期权）：UserID + Instrument Family

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

#### 限速：300个/2s

#### 限速规则（期权以外）：UserID + Instrument ID

#### 限速规则（只限期权）：UserID + Instrument Family

与其他限速按接口调用次数不同，该接口限速按订单的总个数限速。如果单次批量请求中只有一个元素，则算在单个`撤单`限速中。

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

#### 限速：60次/2s

#### 跟单交易带单合约的限速：1次/2s

#### 限速规则（期权以外）：UserID + Instrument ID

#### 限速规则（只限期权）：UserID + Instrument Family

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

#### 限速：300个/2s

#### 跟单交易带单合约的限速：1个/2s

#### 限速规则（期权以外）：UserID + Instrument ID

#### 限速规则（只限期权）：UserID + Instrument Family

与其他限速按接口调用次数不同，该接口限速按订单的总个数限速。如果单次批量请求中只有一个元素，则算在单个`修改订单`限速中。

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

#### 限速：20次/2s

#### 限速规则（期权以外）：UserID + Instrument ID

#### 限速规则（只限期权）：UserID + Instrument Family

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
clOrdId | String | 否 | 客户自定义ID  
字母（区分大小写）与数字的组合，可以是纯字母、纯数字且长度要在1-32位之间。  
tag | String | 否 | 订单标签  
字母（区分大小写）与数字的组合，可以是纯字母、纯数字，且长度在1-16位之间。  
  
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
clOrdId | String | 客户自定义ID  
字母（区分大小写）与数字的组合，可以是纯字母、纯数字且长度要在1-32位之间。  
tag | String | 订单标签  
字母（区分大小写）与数字的组合，可以是纯字母、纯数字，且长度在1-16位之间。  
如果不自动撤单，那有任何平仓挂单的情况下，市价全平会返回错误码信息，提示用户先撤销平仓挂单  

### 获取订单信息

查订单信息

#### 限速：60次/2s

#### 限速规则（期权以外）：UserID + Instrument ID

#### 限速规则（只限期权）：UserID + Instrument Family

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
                "reduceOnly": "false",
                "cancelSource": "20",
                "cancelSourceReason": "Cancel all after triggered",
                "quickMgnType": "",
                "algoClOrdId": "",
                "algoId": "",
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
tgtCcy | String | 币币市价单委托数量`sz`的单位  
`base_ccy`: 交易货币 ；`quote_ccy`：计价货币  
仅适用于`币币`市价订单  
默认买单为`quote_ccy`，卖单为`base_ccy`  
ccy | String | 保证金币种，仅适用于`单币种保证金模式`下的全仓`币币杠杆`订单  
ordId | String | 订单ID  
clOrdId | String | 客户自定义订单ID  
tag | String | 订单标签  
px | String | 委托价格  
sz | String | 委托数量  
pnl | String | 收益，适用于有成交的平仓订单，其他情况均为0  
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
对于`币币`和`杠杆`，单位为交易货币，如 BTC-USDT, 单位为
BTC；对于市价单，无论`tgtCcy`是`base_ccy`，还是`quote_ccy`，单位均为交易货币；  
对于交割、永续以及期权，单位为张。  
fillPx | String | 最新成交价格，如果成交数量为0，该字段为""  
tradeId | String | 最新成交ID  
fillSz | String | 最新成交数量  
对于`币币`和`杠杆`，单位为交易货币，如 BTC-USDT, 单位为
BTC；对于市价单，无论`tgtCcy`是`base_ccy`，还是`quote_ccy`，单位均为交易货币；  
对于交割、永续以及期权，单位为张。  
fillTime | String | 最新成交时间  
avgPx | String | 成交均价，如果成交数量为0，该字段也为""  
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
fee | String | 手续费与返佣  
对于币币和杠杆，为订单交易累计的手续费，平台向用户收取的交易手续费，为负数。如： -0.01  
对于交割、永续和期权，为订单交易累计的手续费和返佣  
rebateCcy | String | 返佣金币种  
source | String | 订单来源  
`13`:策略委托单触发后的生成的限价单  
rebate | String |
返佣金额，仅适用于币币和杠杆，平台向达到指定lv交易等级的用户支付的挂单奖励（返佣），如果没有返佣金，该字段为“”。手续费返佣为正数，如：0.01  
category | String | 订单种类  
`normal`：普通委托  
`twap`：TWAP自动换币  
`adl`：ADL自动减仓  
`full_liquidation`：强制平仓  
`partial_liquidation`：强制减仓  
`delivery`：交割  
`ddh`：对冲减仓类型订单  
reduceOnly | String | 是否只减仓，`true` 或 `false`  
cancelSource | String | 订单取消来源的原因枚举值代码  
cancelSourceReason | String | 订单取消来源的对应具体原因  
quickMgnType | String | 一键借币类型，仅适用于杠杆逐仓的一键借币模式  
`manual`：手动，`auto_borrow`： 自动借币，`auto_repay`： 自动还币  
algoClOrdId | String | 客户自定义策略订单ID。策略订单触发，且策略单有`algoClOrdId`时有值，否则为"",  
algoId | String | 策略委托单ID，策略订单触发时有值，否则为""  
uTime | String | 订单状态更新时间，Unix时间戳的毫秒数格式，如：`1597026383085`  
cTime | String | 订单创建时间，Unix时间戳的毫秒数格式， 如 ：`1597026383085`  
  
### 获取未成交订单列表

获取当前账户下所有未成交订单信息

#### 限速：60次/2s

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
instFamily | String | 否 | 交易品种  
适用于`交割/永续/期权`  
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
limit | String | 否 | 返回结果的数量，最大为100，默认100条  
  
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
                "reduceOnly": "false",
                "quickMgnType": "",
                "algoClOrdId": "",
                "algoId": "",
                "uTime": "1618235248028"
            }
        ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
instType | String | 产品类型  
instId | String | 产品ID  
tgtCcy | String | 币币市价单委托数量`sz`的单位  
`base_ccy`: 交易货币 ；`quote_ccy`：计价货币  
仅适用于`币币`市价订单  
默认买单为`quote_ccy`，卖单为`base_ccy`  
ccy | String | 保证金币种，仅适用于`单币种保证金模式`下的全仓`币币杠杆`订单  
ordId | String | 订单ID  
clOrdId | String | 客户自定义订单ID  
tag | String | 订单标签  
px | String | 委托价格  
sz | String | 委托数量  
pnl | String | 收益，适用于有成交的平仓订单，其他情况均为0  
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
fillPx | String | 最新成交价格。如果还没成交，系统返回""。  
tradeId | String | 最新成交ID  
fillSz | String | 最新成交数量  
fillTime | String | 最新成交时间  
avgPx | String | 成交均价。如果还没成交，系统返回`0`。  
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
tpOrdPx | String | 止盈委托价  
feeCcy | String | 交易手续费币种  
fee | String | 手续费与返佣  
对于币币和杠杆，为订单交易累计的手续费，平台向用户收取的交易手续费，为负数。如： -0.01  
对于交割、永续和期权，为订单交易累计的手续费和返佣  
rebateCcy | String | 返佣金币种  
source | String | 订单来源  
`13`:策略委托单触发后的生成的限价单  
rebate | String |
返佣金额，仅适用于币币和杠杆，平台向达到指定lv交易等级的用户支付的挂单奖励（返佣），如果没有返佣金，该字段为“”。手续费返佣为`正数`，如：`0.01`  
category | String | 订单种类  
`normal`： 普通委托  
reduceOnly | String | 是否只减仓，`true` 或 `false`  
quickMgnType | String | 一键借币类型，仅适用于杠杆逐仓的一键借币模式  
`manual`：手动，`auto_borrow`： 自动借币，`auto_repay`： 自动还币  
algoClOrdId | String | 客户自定义策略订单ID。策略订单触发，且策略单有`algoClOrdId`是有值，否则为"",  
algoId | String | 策略委托单ID，策略订单触发时有值，否则为""  
uTime | String | 订单状态更新时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
cTime | String | 订单创建时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
  
### 获取历史订单记录（近七天）

获取最近7天完结的订单数据（包括7天以前挂单，但近7天才成交得订单数据）。按照订单创建时间倒序排序。  
已经撤销的未成交单 只保留2小时

#### 限速：40次/2s

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
instFamily | String | 否 | 交易品种  
适用于`交割/永续/期权`  
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
begin | String | 否 | 筛选的开始时间戳，Unix 时间戳为毫秒数格式，如 1597026383085  
end | String | 否 | 筛选的结束时间戳，Unix 时间戳为毫秒数格式，如 1597027383085  
limit | String | 否 | 返回结果的数量，最大为100，默认100条  
  
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
                "reduceOnly": "false",
                "cancelSource": "20",
                "cancelSourceReason": "Cancel all after triggered",
                "algoClOrdId": "",
                "algoId": "",
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
tgtCcy | String | 币币市价单委托数量`sz`的单位  
`base_ccy`: 交易货币 ；`quote_ccy`：计价货币  
仅适用于`币币`市价订单  
默认买单为`quote_ccy`，卖单为`base_ccy`  
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
fillPx | String | 最新成交价格，如果成交数量为0，该字段为""  
tradeId | String | 最新成交ID  
fillSz | String | 最新成交数量  
fillTime | String | 最新成交时间  
avgPx | String | 成交均价，如果成交数量为0，该字段也为""  
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
fee | String | 手续费与返佣  
对于币币和杠杆，为订单交易累计的手续费，平台向用户收取的交易手续费，为负数。如： -0.01  
对于交割、永续和期权，为订单交易累计的手续费和返佣  
rebateCcy | String | 返佣金币种  
source | String | 订单来源  
`13`:策略委托单触发后的生成的限价单  
rebate | String |
返佣金额，仅适用于币币和杠杆，平台向达到指定lv交易等级的用户支付的挂单奖励（返佣），如果没有返佣金，该字段为“”。手续费返佣为`正数`，如：`0.01`  
pnl | String | 收益，适用于有成交的平仓订单，其他情况均为0  
category | String | 订单种类  
`normal`：普通委托  
`twap`：TWAP自动换币  
`adl`：ADL自动减仓  
`full_liquidation`：强制平仓  
`partial_liquidation`：强制减仓  
`delivery`：交割  
`ddh`：对冲减仓类型订单  
reduceOnly | String | 是否只减仓，`true` 或 `false`  
cancelSource | String | 订单取消来源的原因枚举值代码  
cancelSourceReason | String | 订单取消来源的对应具体原因  
algoClOrdId | String | 客户自定义策略订单ID。策略订单触发，且策略单有`algoClOrdId`时有值，否则为"",  
algoId | String | 策略委托单ID，策略订单触发时有值，否则为""  
uTime | String | 订单状态更新时间，Unix时间戳的毫秒数格式，如`1597026383085`  
cTime | String | 订单创建时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
  
### 获取历史订单记录（近三个月）

获取最近3个月完结的订单数据（包括3个月以前挂单，但近3个月才成交的订单数据）。按照订单创建时间倒序排序。

#### 限速：20次/2s

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
instFamily | String | 否 | 交易品种  
适用于`交割/永续/期权`  
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
begin | String | 否 | 筛选的开始时间戳，Unix 时间戳为毫秒数格式，如 1597026383085  
end | String | 否 | 筛选的结束时间戳，Unix 时间戳为毫秒数格式，如 1597027383085  
limit | String | 否 | 返回结果的数量，最大为100，默认100条  
  
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
                "reduceOnly": "false",
                "cancelSource": "20",
                "cancelSourceReason": "Cancel all after triggered",
                "algoClOrdId": "",
                "algoId": "",
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
tgtCcy | String | 币币市价单委托数量`sz`的单位  
`base_ccy`: 交易货币 ；`quote_ccy`：计价货币  
仅适用于`币币`市价订单  
默认买单为`quote_ccy`，卖单为`base_ccy`  
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
fillPx | String | 最新成交价格，如果成交数量为0，该字段为""  
tradeId | String | 最新成交ID  
fillSz | String | 最新成交数量  
fillTime | String | 最新成交时间  
avgPx | String | 成交均价，如果成交数量为0，该字段也为""  
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
fee | String | 手续费与返佣  
对于币币和杠杆，为订单交易累计的手续费，平台向用户收取的交易手续费，为负数。如： -0.01  
对于交割、永续和期权，为订单交易累计的手续费和返佣  
rebateCcy | String | 返佣金币种  
rebate | String |
返佣金额，仅适用于币币和杠杆，平台向达到指定lv交易等级的用户支付的挂单奖励（返佣），如果没有返佣金，该字段为“”。手续费返佣为`正数`，如：`0.01`  
pnl | String | 收益，适用于有成交的平仓订单，其他情况均为0  
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
reduceOnly | String | 是否只减仓，`true` 或 `false`  
cancelSource | String | 订单取消来源的原因枚举值代码  
cancelSourceReason | String | 订单取消来源的对应具体原因  
algoClOrdId | String | 客户自定义策略订单ID。策略订单触发，且策略单有`algoClOrdId`是有值，否则为"",  
algoId | String | 策略委托单ID，策略订单触发时有值，否则为""  
uTime | String | 订单状态更新时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
cTime | String | 订单创建时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
该接口不包含`已撤销的完全无成交`类型订单数据，可通过`获取历史订单记录（近七天)`接口获取。  

### 获取成交明细（近三天）

获取近3天的订单成交明细信息

#### 限速：60次/2s

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
instFamily | String | 否 | 交易品种  
适用于`交割/永续/期权`  
instId | String | 否 | 产品 ID，如`BTC-USD-190927`  
ordId | String | 否 | 订单 ID  
after | String | 否 | 请求此 ID 之前（更旧的数据）的分页内容，传的值为对应接口的`billId`  
before | String | 否 | 请求此 ID 之后（更新的数据）的分页内容，传的值为对应接口的`billId`  
begin | String | 否 | 筛选的开始时间戳，Unix 时间戳为毫秒数格式，如 1597026383085  
end | String | 否 | 筛选的结束时间戳，Unix 时间戳为毫秒数格式，如 1597027383085  
limit | String | 否 | 返回结果的数量，最大为100，默认100条  
  
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
          "ts": "1597026383085",
          "fillTime": "1597026383084"
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
          "ts": "1597026383085",
          "fillTime": "1597026383084"
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
fee | String | 手续费金额或者返佣金额，手续费扣除为‘负数’，如-0.01；手续费返佣为‘正数’，如 0.01  
ts | String | 成交明细产生时间，Unix时间戳的毫秒数格式，如`1597026383085`  
fillTime | String | 成交时间，与订单频道的`fillTime`相同  
tradeId  
当成交明细所归属的订单种类（category）为
partial_liquidation：强制减仓、full_liquidation：强制平仓、adl：ADL自动减仓时，tradeId字段的值为"0"  
tag  
订单标签, 对于大宗交易总是 "sys:blocktrade" 。  
ordId  
订单ID, 对于大宗交易总是 "" 。  
clOrdId  
用户自定义订单ID, 对于大宗交易总是 "" 。

### 获取成交明细（近三个月）

获取近3个月订单成交明细信息

#### 限速：10 次/2s

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
instFamily | String | 否 | 交易品种  
适用于`交割/永续/期权`  
instId | String | 否 | 产品 ID，如`BTC-USD-190927`  
ordId | String | 否 | 订单 ID  
after | String | 否 | 请求此 ID 之前（更旧的数据）的分页内容，传的值为对应接口的`billId`  
before | String | 否 | 请求此 ID 之后（更新的数据）的分页内容，传的值为对应接口的`billId`  
begin | String | 否 | 筛选的开始时间戳，Unix 时间戳为毫秒数格式，如 1597026383085  
end | String | 否 | 筛选的结束时间戳，Unix 时间戳为毫秒数格式，如 1597027383085  
limit | String | 否 | 返回结果的数量，最大为100，默认100条  
  
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
          "ts": "1597026383085",
          "fillTime": "1597026383084"
    
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
          "ts": "1597026383085",
          "fillTime": "1597026383084"
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
ts | String | 成交明细产生时间，Unix时间戳的毫秒数格式，如`1597026383085`  
fillTime | String | 成交时间，与订单频道的`fillTime`相同  
tradeId  
当成交明细所归属的订单种类（category）为
partial_liquidation：强制减仓、full_liquidation：强制平仓、adl：ADL自动减仓时，tradeId字段的值为"0"
tag  
订单标签, 对于大宗交易总是 "sys:blocktrade" 。  
ordId  
订单ID, 对于大宗交易总是 "" 。  
clOrdId  
用户自定义订单ID, 对于大宗交易总是 "" 。  获取近3天的成交明细时，建议使用获取成交明细（近三天）接口。

### 策略委托下单

提供单向止盈止损委托、双向止盈止损委托、计划委托、冰山委托、时间加权委托、移动止盈止损委托

#### 限速：20次/2s

#### 跟单交易带单合约的限速：1次/2s

#### 限速规则（期权以外）：UserID + Instrument ID

#### 限速规则（只限期权）：UserID + Instrument Family

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
保证金模式 `isolated`：逐仓，`cross：`全仓  
非保证金模式 `cash`：非保证金  
ccy | String | 否 | 保证金币种  
仅适用于单币种保证金模式下的全仓杠杆订单  
side | String | 是 | 订单方向  
`buy`：买  
`sell`：卖  
posSide | String | 可选 | 持仓方向  
在双向持仓模式下必填，且仅可选择 `long` 或 `short`  
ordType | String | 是 | 订单类型  
`conditional`：单向止盈止损  
`oco`：双向止盈止损  
`trigger`：计划委托  
`move_order_stop`：移动止盈止损  
`iceberg`：冰山委托  
`twap`：时间加权委托  
sz | String | 可选 | 委托数量  
`sz`和`closeFraction`必填且只能填其一  
tag | String | 否 | 订单标签  
字母（区分大小写）与数字的组合，可以是纯字母、纯数字，且长度在1-16位之间  
tgtCcy | String | 否 | 委托数量的类型  
`base_ccy`: 交易货币 ；`quote_ccy`：计价货币  
仅适用于`币币`单向止盈止损市价买单  
默认买为`计价货币`，卖为`交易货币`  
reduceOnly | Boolean | 否 | 是否只减仓，`true` 或 `false`，默认`false`  
仅适用于`币币杠杆`，以及买卖模式下的`交割/永续`  
仅适用于`单币种保证金模式`和`跨币种保证金模式`  
algoClOrdId | String | 否 | 客户自定义策略订单ID  
字母（区分大小写）与数字的组合，可以是纯字母、纯数字且长度要在1-32位之间。  
closeFraction | String | 可选 | 策略委托触发时，平仓的百分比。1 代表100%  
现在系统只支持全部平仓，唯一接受参数为`1`  
仅适用于`交割`或`永续`  
仅适用于买卖模式 `posSide` = `net`  
仅适用于减仓订单 `reduceOnly` = `true`  
仅适用于止盈止损 `ordType` = `conditional` 或 `oco`  
仅适用于止盈止损市价订单  
`sz`和`closeFraction`必填且只能填其一  
quickMgnType | String | 否 | 一键借币类型，仅适用于杠杆逐仓的一键借币模式：  
`manual`：手动，`auto_borrow`： 自动借币，`auto_repay`： 自动还币  
默认是`manual`：手动  
  
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
止盈止损  
当用户进行单向止盈止损委托（ordType=conditional）时，如果用户同时传了止盈止损四个参数，只进行止损的功能校验，忽略止盈的业务逻辑校验。

计划委托

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
triggerPx | String | 是 | 计划委托触发价格  
orderPx | String | 是 | 委托价格  
委托价格为`-1`时，执行市价委托  
triggerPxType | String | 否 | 计划委托触发价格类型  
`last`：最新价格  
`index`：指数价格  
`mark`：标记价格  
默认为`last`  
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
                "clOrdId": "",
                "algoClOrdId": "",
                "sCode":"0",
                "sMsg":""
            }
        ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
algoId | String | 策略委托单ID  
clOrdId | String | 客户自定义订单ID  
algoClOrdId | String | 客户自定义策略订单ID  
sCode | String | 事件执行结果的code，0代表成功  
sMsg | String | 事件执行失败时的msg  
  
### 撤销策略委托订单

撤销策略委托订单（不包含冰山委托、时间加权、移动止盈止损等高级策略订单），每次最多可以撤销10个策略委托单

#### 限速：20次/2s

#### 限速规则（期权以外）：UserID + Instrument ID

#### 限速规则（只限期权）：UserID + Instrument Family

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

#### 限速：20次/2s

#### 限速规则（期权以外）：UserID + Instrument ID

#### 限速规则（只限期权）：UserID + Instrument Family

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
  
### 获取策略委托单信息

#### 限速：20次/2s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/trade/order-algo`

> 请求示例
    
    
    GET /api/v5/trade/order-algo?algoId=1234231231423
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
algoId | String | 可选 | 策略委托单ID  
`algoId`和`algoClOrdId`必须传一个，若传两个，以algoId为主  
algoClOrdId | String | 可选 | 客户自定义策略订单ID  
字母（区分大小写）与数字的组合，可以是纯字母、纯数字且长度要在1-32位之间。  
  
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
                "clOrdId":"",
                "algoId":"1234",
                "sz":"999",
                "closeFraction":"",
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
                "reduceOnly": "false",
                "triggerTime":"1597026383085",
                "last": "16012",
                "failCode": "",
                "algoClOrdId": "",
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
clOrdId | String | 客户自定义订单ID  
sz | String | 委托数量  
closeFraction | String | 策略委托触发时，平仓的百分比。1 代表100%  
ordType | String | 订单类型  
side | String | 订单方向  
posSide | String | 持仓方向  
tdMode | String | 交易模式  
tgtCcy | String | 币币市价单委托数量`sz`的单位  
`base_ccy`: 交易货币 ；`quote_ccy`：计价货币  
仅适用于`币币`市价订单  
默认买单为`quote_ccy`，卖单为`base_ccy`  
state | String | 订单状态  
`effective`： 已生效  
`canceled`：已撤销  
`order_failed`：委托失败  
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
triggerPx | String | 计划委托触发价格  
triggerPxType | String | 计划委托触发价格类型  
`last`：最新价格  
`index`：指数价格  
`mark`：标记价格  
ordPx | String | 订单委托价格  
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
reduceOnly | String | 是否只减仓，`true` 或 `false`  
quickMgnType | String | 一键借币类型，仅适用于杠杆逐仓的一键借币模式  
`manual`：手动，`auto_borrow`： 自动借币，`auto_repay`： 自动还币  
last | String | 下单时的最新成交价  
failCode | String | 代表策略触发失败的原因，已撤销和已生效时为""，委托失败时有值，如 51008；  
仅适用于单向止盈止损委托、双向止盈止损委托、移动止盈止损委托、计划委托。  
algoClOrdId | String | 客户自定义策略订单ID  
cTime | String | 订单创建时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
  
### 获取未完成策略委托单列表

获取当前账户下未触发的策略委托单列表

#### 限速：20次/2s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/trade/orders-algo-pending`

> 请求示例
    
    
    GET /api/v5/trade/orders-algo-pending?ordType=conditional
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
algoId | String | 否 | 策略委托单ID  
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
limit | String | 否 | 返回结果的数量，最大为100，默认100条  
algoClOrdId | String | 否 | 客户自定义策略订单ID  
字母（区分大小写）与数字的组合，可以是纯字母、纯数字且长度要在1-32位之间。  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "activePx": "",
                "actualPx": "",
                "actualSide": "",
                "actualSz": "0",
                "algoId": "492453578716610560",
                "cTime": "1663682082511",
                "callbackRatio": "",
                "callbackSpread": "",
                "ccy": "",
                "clOrdId": "hahawang",
                "instId": "BTC-USDT-SWAP",
                "instType": "SWAP",
                "lever": "3",
                "moveTriggerPx": "",
                "ordId": "0",
                "ordPx": "",
                "ordType": "conditional",
                "posSide": "long",
                "pxLimit": "",
                "pxSpread": "",
                "pxVar": "",
                "side": "buy",
                "slOrdPx": "-1",
                "slTriggerPx": "22000",
                "slTriggerPxType": "last",
                "state": "live",
                "sz": "10",
                "closeFraction": "",
                "szLimit": "",
                "tag": "",
                "tdMode": "cross",
                "tgtCcy": "",
                "timeInterval": "",
                "tpOrdPx": "",
                "tpTriggerPx": "",
                "tpTriggerPxType": "",
                "triggerPx": "",
                "triggerPxType": "",
                "reduceOnly": "false",
                "quickMgnType": "",
                "last": "16012",
                "failCode": "",
                "algoClOrdId": "",
                "triggerTime": ""
            }
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
instType | String | 产品类型  
instId | String | 产品ID  
ccy | String | 保证金币种，仅适用于单币种保证金模式下的全仓杠杆订单  
ordId | String | 订单ID  
algoId | String | 策略委托单ID  
clOrdId | String | 客户自定义订单ID  
sz | String | 委托数量  
closeFraction | String | 策略委托触发时，平仓的百分比。1 代表100%  
ordType | String | 订单类型  
side | String | 订单方向  
posSide | String | 持仓方向  
tdMode | String | 交易模式  
tgtCcy | String | 币币市价单委托数量`sz`的单位  
`base_ccy`: 交易货币 ；`quote_ccy`：计价货币  
仅适用于`币币`市价订单  
默认买单为`quote_ccy`，卖单为`base_ccy`  
state | String | 订单状态 ，`live`：待生效 `pause`：暂停生效 `partially_effective`:部分生效  
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
reduceOnly | String | 是否只减仓，`true` 或 `false`  
quickMgnType | String | 一键借币类型，仅适用于杠杆逐仓的一键借币模式  
`manual`：手动，`auto_borrow`： 自动借币，`auto_repay`： 自动还币  
last | String | 下单时的最新成交价  
failCode | String | 代表策略触发失败的原因，委托失败时有值，如 51008，对于该接口一直为""。  
algoClOrdId | String | 客户自定义策略订单ID  
cTime | String | 订单创建时间， Unix时间戳的毫秒数格式，如 `1597026383085`  
  
### 获取历史策略委托单列表

获取最近3个月当前账户下所有策略委托单列表

#### 限速：20次/2s

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
limit | String | 否 | 返回结果的数量，最大为100，默认100条  
  
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
                "clOrdId":"",
                "algoId":"1234",
                "sz":"999",
                "closeFraction":"",
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
                "reduceOnly": "false",
                "triggerTime":"1597026383085",
                "last": "16012",
                "failCode": "",
                "algoClOrdId": "",
                "cTime":"1597026383000"
            },
            {
                "instType":"FUTURES",
                "instId":"BTC-USD-200329",
                "ordId":"123445",
                "ccy":"BTC",
                "clOrdId":"",
                "algoId":"1234",
                "sz":"999",
                "closeFraction":"",
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
                "reduceOnly": "false",
                "triggerTime":"1597026383085",
                "last": "16012",
                "failCode": "",
                "algoClOrdId": "",
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
clOrdId | String | 客户自定义订单ID  
sz | String | 委托数量  
closeFraction | String | 策略委托触发时，平仓的百分比。1 代表100%  
ordType | String | 订单类型  
side | String | 订单方向  
posSide | String | 持仓方向  
tdMode | String | 交易模式  
tgtCcy | String | 币币市价单委托数量`sz`的单位  
`base_ccy`: 交易货币 ；`quote_ccy`：计价货币  
仅适用于`币币`市价订单  
默认买单为`quote_ccy`，卖单为`base_ccy`  
state | String | 订单状态  
`effective`： 已生效  
`canceled`：已撤销  
`order_failed`：委托失败  
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
reduceOnly | String | 是否只减仓，`true` 或 `false`  
quickMgnType | String | 一键借币类型，仅适用于杠杆逐仓的一键借币模式  
`manual`：手动，`auto_borrow`： 自动借币，`auto_repay`： 自动还币  
last | String | 下单时的最新成交价  
failCode | String | 代表策略触发失败的原因，已撤销和已生效时为""，委托失败时有值，如 51008；  
仅适用于单向止盈止损委托、双向止盈止损委托、移动止盈止损委托、计划委托。  
algoClOrdId | String | 客户自定义策略订单ID  
cTime | String | 订单创建时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
  
### 获取一键兑换主流币币种列表

获取小币一键兑换主流币币种列表。仅可兑换余额在 $10 以下小币币种。

#### 限速：1次/2s

#### 限速规则：UserID

#### HTTP 请求

`GET /api/v5/trade/easy-convert-currency-list`

> 请求示例
    
    
    GET /api/v5/trade/easy-convert-currency-list
    

#### 请求参数

无

> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "fromData": [
                    {
                        "fromAmt": "6.580712708344864",
                        "fromCcy": "ADA"
                    },
                    {
                        "fromAmt": "2.9970000013055097",
                        "fromCcy": "USDC"
                    }
                ],
                "toCcy": [
                    "USDT",
                    "BTC",
                    "ETH",
                    "OKB"
                ]
            }
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
fromData | Array | 当前拥有并可兑换的小币币种列表信息  
> fromCcy | String | 可兑换币种  
> fromAmt | String | 可兑换币种数量  
toCcy | Array | 可转换成的主流币币种列表  
  
### 一键兑换主流币交易

进行小币一键兑换主流币交易。仅可兑换余额在 $10 以下小币币种。

#### 限速：1次/2s

#### 限速规则：UserID

#### HTTP 请求

`POST /api/v5/trade/easy-convert`

> 请求示例
    
    
    POST /api/v5/trade/easy-convert
    body
    {
        "fromCcy": ["ADA","USDC"], //逗号分隔小币
        "toCcy": "OKB" 
    }
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
fromCcy | Array | 是 | 小币支付币种  
单次最多同时选择5个币种，如有多个币种则用逗号隔开  
toCcy | String | 是 | 兑换的主流币  
只选择一个币种，且不能和小币支付币种重复  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "fillFromSz": "6.5807127",
                "fillToSz": "0.17171580105126",
                "fromCcy": "ADA",
                "status": "running",
                "toCcy": "OKB",
                "uTime": "1661419684687"
            },
            {
                "fillFromSz": "2.997",
                "fillToSz": "0.1683755161661844",
                "fromCcy": "USDC",
                "status": "running",
                "toCcy": "OKB",
                "uTime": "1661419684687"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
status | String | 当前兑换进度/状态  
`running`: 进行中  
`filled`: 已完成  
`failed`: 失败  
fromCcy | String | 小币支付币种  
toCcy | String | 兑换的主流币  
fillFromSz | String | 小币偿还币种支付数量  
fillToSz | String | 兑换的主流币成交数量  
uTime | String | 交易时间戳，Unix时间戳为毫秒数格式，如 1597026383085  
  
### 获取一键兑换主流币历史记录

查询一键兑换主流币的历史记录与进度状态。

#### 限速：1次/2s

#### 限速规则：UserID

#### HTTP 请求

`GET /api/v5/trade/easy-convert-history`

> 请求示例
    
    
    GET /api/v5/trade/easy-convert-history
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
after | String | 否 | 查询在此之前的内容，值为时间戳，Unix时间戳为毫秒数格式，如`1597026383085`  
before | String | 否 | 查询在此之后的内容，值为时间戳，Unix时间戳为毫秒数格式，如`1597026383085`  
limit | String | 否 | 返回的结果集数量，默认为100，最大为100  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "fillFromSz": "0.1761712511667539",
                "fillToSz": "6.7342205900000000",
                "fromCcy": "OKB",
                "status": "filled",
                "toCcy": "ADA",
                "uTime": "1661313307979"
            },
            {
                "fillFromSz": "0.1722106121112177",
                "fillToSz": "2.9971018300000000",
                "fromCcy": "OKB",
                "status": "filled",
                "toCcy": "USDC",
                "uTime": "1661313307979"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
fromCcy | String | 小币支付币种  
fromSz | String | 对应的小币支付数量  
toCcy | String | 兑换到的主流币  
toSz | String | 兑换到的主流币数量  
status | String | 当前兑换进度/状态  
`running`: 进行中  
`filled`: 已完成  
`failed`: 失败  
uTime | String | 交易时间戳，Unix时间戳为毫秒数格式，如 1597026383085  
  
### 获取一键还债币种列表

查询一键还债币种列表。负债币种包括全仓负债和逐仓负债。

#### 限速：1次/2s

#### 限速规则：UserID

#### HTTP 请求

`GET /api/v5/trade/one-click-repay-currency-list`

> 请求示例
    
    
    GET /api/v5/trade/one-click-repay-currency-list
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
debtType | String | 否 | 负债类型  
`cross`: 全仓负债  
`isolated`: 逐仓负债  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "debtData": [
                    {
                        "debtAmt": "29.653478",
                        "debtCcy": "LTC"
                    },
                    {
                        "debtAmt": "237803.6828295906051002",
                        "debtCcy": "USDT"
                    }
                ],
                "debtType": "cross",
                "repayData": [
                    {
                        "repayAmt": "0.4978335419825104",
                        "repayCcy": "ETH"
                    }
                ]
            }
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
debtData | Array | 负债币种信息  
> debtCcy | String | 负债币种  
> debtAmt | String | 可负债币种数量  
包括本金和利息  
debtType | String | 负债类型  
`cross`: 全仓负债  
`isolated`: 逐仓负债  
repayData | Array | 偿还币种信息  
> repayCcy | String | 可偿还负债的币种  
> repayAmt | String | 可偿还负债的币种可用资产数量  
  
### 一键还债交易

交易一键偿还小额全仓债务。不支持逐仓负债的偿还。根据资金和交易账户的剩余可用余额为最大偿还数量。

#### 限速：1次/2s

#### 限速规则：UserID

#### HTTP 请求

`POST /api/v5/trade/one-click-repay`

> 请求示例
    
    
    POST /api/v5/trade/one-click-repay
    body
    {
        "debtCcy": ["ETH","BTC"], //逗号分隔债务币
        "repayCcy": "USDT" //用USDT偿还ETH和BTC
    }
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
debtCcy | Array | 是 | 负债币种  
单次最多同时选择5个币种，如有多个币种则用逗号隔开  
repayCcy | String | 是 | 偿还币种  
只选择一个币种，且不能和负债币种重复  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "debtCcy": "ETH", 
                "fillDebtSz": "0.01023052",
                "fillRepaySz": "30", 
                "repayCcy": "USDT", 
                "status": "filled",
                "uTime": "1646188520338"
            },
            {
                "debtCcy": "BTC", 
                "fillFromSz": "3",
                "fillToSz": "60,221.15910001",
                "repayCcy": "USDT",
                "status": "filled",
                "uTime": "1646188520338"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
status | String | 当前还债进度/状态  
`running`: 进行中  
`filled`: 已完成  
`failed`: 失败  
debtCcy | String | 负债币种  
repayCcy | String | 偿还币种  
fillDebtSz | String | 负债币种成交数量  
fillRepaySz | String | 偿还币种成交数量  
uTime | String | 交易时间戳，Unix时间戳为毫秒数格式，如 1597026383085  
  
### 获取一键还债历史记录

查询一键还债的历史记录与进度状态。

#### 限速：1次/2s

#### 限速规则：UserID

#### HTTP 请求

`GET /api/v5/trade/one-click-repay-history`

> 请求示例
    
    
    GET /api/v5/trade/one-click-repay-history
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
after | String | 否 | 查询在此之前的内容，值为时间戳，Unix时间戳为毫秒数格式，如`1597026383085`  
before | String | 否 | 查询在此之后的内容，值为时间戳，Unix时间戳为毫秒数格式，如`1597026383085`  
limit | String | 否 | 返回的结果集数量，默认为100，最大为100  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "debtCcy": "USDC",
                "fillDebtSz": "6950.4865447900000000",
                "fillRepaySz": "4.3067975995094930",
                "repayCcy": "ETH",
                "status": "filled",
                "uTime": "1661256148746"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
debtCcy | String | 负债币种  
debtSz | String | 对应的负债币种成交数量  
repayCcy | String | 偿还币种  
repaySz | String | 偿还币种实际支付数量  
status | String | 当前还债进度/状态  
`running`: 进行中  
`filled`: 已完成  
`failed`: 失败  
uTime | String | 交易时间戳，Unix时间戳为毫秒数格式，如 1597026383085  
  
## 资金

`资金`功能模块下的API接口需要身份验证。

### 获取币种列表

获取平台所有币种列表。

#### 限速：6 次/s

#### 限速规则：UserID

#### HTTP 请求

`GET /api/v5/asset/currencies`

> 请求示例
    
    
    GET /api/v5/asset/currencies
    
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
ccy | String | 否 | 币种，如 `BTC`  
支持多币种查询（不超过20个），币种之间半角逗号分隔  
  
> 返回结果
    
    
    {
      "code": "0",
      "msg": "",
      "data": [
        {
            "canDep": true,
            "canInternal": true,
            "canWd": true,
            "ccy": "BTC",
            "chain": "BTC-Bitcoin",
            "depQuotaFixed": "",
            "depQuoteDailyLayer2":"",
            "logoLink": "https://static.coinall.ltd/cdn/oksupport/asset/currency/icon/btc.png",
            "mainNet": true,
            "maxFee": "0.0004",
            "maxWd": "500",
            "minDep": "0.00005",
            "minDepArrivalConfirm": "1",
            "minFee": "0.0002",
            "minWd": "0.001",
            "minWdUnlockConfirm": "3",
            "name": "Bitcoin",
            "needTag": false,
            "usedDepQuotaFixed": "",
            "usedWdQuota": "0",
            "wdQuota": "200",
            "wdTickSz": "8"
        }
      ]
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
ccy | String | 币种名称，如 `BTC`  
name | String | 币种名称，不显示则无对应名称  
logoLink | String | 币种Logo链接  
chain | String | 币种链信息  
有的币种下有多个链，必须要做区分，如`USDT`下有`USDT-ERC20`，`USDT-TRC20`，`USDT-Omni`多个链  
canDep | Boolean | 是否可充值，`false`表示不可链上充值，`true`表示可以链上充值  
canWd | Boolean | 是否可提币，`false`表示不可链上提币，`true`表示可以链上提币  
canInternal | Boolean | 是否可内部转账，`false`表示不可内部转账，`true`表示可以内部转账  
minDep | String | 币种单笔最小充值量  
minWd | String | 币种单笔最小提币量  
maxWd | String | 币种单笔最大提币量  
wdTickSz | String | 提币精度,表示小数点后的位数。提币手续费精度与提币精度保持一致。  
内部转账提币精度为小数点后8位。  
wdQuota | String | 过去24小时内提币额度，单位为`USD`  
usedWdQuota | String | 过去24小时内已用提币额度，单位为`USD`  
minFee | String | 最小提币手续费数量  
maxFee | String | 最大提币手续费数量  
mainNet | Boolean | 当前链是否为主链  
如果是则返回`true`，否则返回`false`  
needTag | Boolean | 当前链是否需要标签（tag/memo）信息  
minDepArrivalConfirm | String | 充值到账最小网络确认数。币已到账但不可提。  
minWdUnlockConfirm | String | 提现解锁最小网络确认数  
depQuotaFixed | String | 充币固定限额，单位为`USD`  
没有充币限制则返回""  
usedDepQuotaFixed | String | 已用充币固定额度，单位为`USD`  
没有充币限制则返回""  
depQuoteDailyLayer2 | String | Layer2网络每日充值上限  
  
### 获取资金账户余额

获取资金账户所有资产列表，查询各币种的余额、冻结和可用等信息。

只返回余额大于0的币资产信息。

#### 限速：6次/s

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
frozenBal | String | 冻结余额  
availBal | String | 可用余额  
  
### 获取不可交易资产

#### 限速：6 次/s

#### 限速规则：UserID

#### HTTP 请求

`GET /api/v5/asset/non-tradable-assets`

> 请求示例
    
    
    GET /api/v5/asset/non-tradable-assets
    
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
ccy | String | 否 | 币种，如 `BTC`  
支持多币种查询（不超过20个），币种之间半角逗号分隔  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [{
            "bal": "0.9",
            "canWd": true,
            "ccy": "USD_BSC",
            "chain": "BSC",
            "ctAddr": "197955",
            "fee": "0.1",
            "logoLink": "",
            "minWd": "0",
            "name": "",
            "needTag": false,
            "wdAll": true,
            "wdTickSz": "4"
        }],
        "msg": ""
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
ccy | String | 币种名称，如 `USD_BSC`  
name | String | 币种中文名称，不显示则无对应名称  
logoLink | String | 币种Logo链接  
bal | String | 可提余额  
canWd | Boolean | 是否可提  
`false`: 不可提 `true`: 可提  
chain | String | 支持提币的链  
minWd | String | 币种单笔最小提币量  
wdAll | String | 该币种资产是否必须一次性全部提取  
fee | String | 提币固定手续费，单位是`USDT`。提币手续费精度为小数点后8位。  
ctAddr | String | 合约地址后6位  
wdTickSz | String | 提币精度,表示小数点后的位数  
needTag | Boolean | 提币的链是否需要标签（tag/memo）信息  
  
### 获取账户资产估值

查看账户资产估值

#### 限速：1次/2s

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
details | Object | 各个账户的资产估值  
> funding | String | 资金账户  
> trading | String | 交易账户  
> classic | String | 经典账户 (已废弃)  
> earn | String | 金融账户  
  
### 资金划转

调用时，API Key 需要有交易权限

支持母账户的资金账户划转到交易账户，母账户到子账户的资金账户和交易账户划转；

子账户默认可转出至母账户，划转到同一母账户下的其他子账户，需要先调用“设置子账户转出权限”接口进行授权。

请求失败不代表划转失败，建议以获取资金划转状态接口返回的状态为准。

#### 限速：1 次/s

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
    
    母账户从资金账户划转1.5USDT到子账户的资金账户
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
subAcct | String | 可选 | 子账户名称，type 为`1`，`2` 或 `4`：subAcct 为必填项  
type | String | 否 | 划转类型  
`0`：账户内划转  
`1`：母账户转子账户(仅适用于母账户APIKey)  
`2`：子账户转母账户(仅适用于母账户APIKey)  
`3`：子账户转母账户(仅适用于子账户APIKey)  
`4`：子账户转子账户(仅适用于子账户APIKey，且目标账户需要是同一母账户下的其他子账户)  
默认是`0`  
loanTrans | Boolean | 否 | 是否支持`跨币种保证金模式`或`组合保证金模式`下的借币转入/转出  
true 或 false，默认false  
clientId | String | 否 | 客户自定义ID  
字母（区分大小写）与数字的组合，可以是纯字母、纯数字且长度要在1-32位之间。  
omitPosRisk | String | 否 | 是否忽略仓位风险  
默认为`false`  
仅适用于`组合保证金模式`  
  
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

获取最近2个星期内的资金划转状态数据

#### 限速：10 次/s

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
type | String | 否 | 划转类型  
`0`：账户内划转  
`1`：母账户转子账户(仅适用于母账户APIKey)  
`2`：子账户转母账户(仅适用于母账户APIKey)  
`3`：子账户转母账户(仅适用于子账户APIKey)  
`4`：子账户转子账户(仅适用于子账户APIKey，且目标账户需要是同一母账户下的其他子账户)  
默认是`0`  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "amt": "1.5",
                "ccy": "USDT",
                "clientId": "",
                "from": "18",
                "instId": "", //已废弃
                "state": "success",
                "subAcct": "test",
                "to": "6",
                "toInstId": "", //已废弃
                "transId": "1",
                "type": "1"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
transId | String | 划转 ID  
clientId | String | 客户自定义ID  
ccy | String | 划转币种  
amt | String | 划转量  
type | String | 划转类型  
`0`：账户内划转  
`1`：母账户转子账户(仅适用于母账户APIKey)  
`2`：子账户转母账户(仅适用于母账户APIKey)  
`3`：子账户转母账户(仅适用于子账户APIKey)  
`4`：子账户转子账户(仅适用于子账户APIKey，且目标账户需要是同一母账户下的其他子账户)  
from | String | 转出账户  
`6`：资金账户 `18`：交易账户  
to | String | 转入账户  
`6`：资金账户 `18`：交易账户  
subAcct | String | 子账户名称  
instId | String | 已废弃  
toInstId | String | 已废弃  
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
`20`：转出至子账户（主体是母账户）  
`21`：从子账户转入（主体是母账户）  
`22`：转出到母账户（主体是子账户）  
`23`：母账户转入（主体是子账户）  
`28`：领取  
`47`：系统冲正  
`48`：活动得到  
`49`：活动送出  
`50`：预约得到  
`51`：预约扣除  
`52`：发红包  
`53`：抢红包  
`54`：红包退还  
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
`104`：抵押借贷手续费转入  
`105`：抵押借贷手续费转出  
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
`132`：客服冻结  
`133`：客服解冻  
`134`：客服转交  
`135`：跨链兑换  
`136`：兑换  
`137`：ETH2.0申购  
`138`：ETH2.0兑换  
`139`：ETH2.0收益  
`143`：系统退款  
`145`：系统回收  
`146`：客户回馈  
`147`：sushi 增发收益  
`150`：节点返佣  
`151`：邀请奖励  
`152`：经纪商返佣  
`153`：新手奖励  
`154`：拆盲盒奖励  
`155`：福利中心提现  
`156`：返佣卡返佣  
`157`：红包  
`160`：双币赢申购  
`161`：双币赢回款  
`162`：双币赢收益  
`163`：双币赢退款  
`169`：2022春节红包  
`172`：助力人返佣  
`173`：手续费返现  
`174`：支付  
`175`：锁定质押物  
`176`：借款转入  
`177`：添加质押物  
`178`：减少质押物  
`179`：还款  
`180`：释放质押物  
`181`：偿还空投糖果  
`182`：反馈奖励  
`183`：邀请好友奖励  
`184`：瓜分奖池奖励  
`185`：经纪商闪兑返佣  
`186`：0元领ETH  
`187`：闪兑划转  
`188`：插槽竞拍兑换  
`189`：盲盒奖励  
`193`：卡支付购买  
`195`：不可交易资产提币  
`196`：不可交易资产提币撤销  
`197`：不可交易资产充值  
`198`：无效资产减少  
`199`：有效资产增加  
`200`：买入  
`202`：价格锁定申购  
`203`：价格锁定回款  
`204`：价格锁定收益  
`205`：价格锁定退款  
`207`：双币赢精简版申购  
`208`：双币赢精简版回款  
`209`：双币赢精简版收益  
`210`：双币赢精简版退款  
`211`：投聪夺币中奖  
`212`：多币种借贷锁定质押物  
`213`：多币种质押物转出用户帐户  
`214`：多币种质押物返还用户  
`215`：多币种借贷释放质押物  
`216`：多币种借贷划转到用户帐户  
`217`：多币种借贷借款转入  
`218`：多币种借贷还款  
`219`：多币种还款由用户帐户转入  
`220`：已下架数字货币  
`221`：提币手续费支出  
`222`：提币手续费退款  
`223`：带单分润  
`224`：服务费  
`225`：鲨鱼鳍申购  
`226`：鲨鱼鳍回款  
`227`：鲨鱼鳍收益  
`228`：鲨鱼鳍退款  
`229`：空投发放  
`230`：换币完成  
`232`：利息补贴已入账  
`233`：经纪商佣金补偿  
`284`：转出交易子账户  
`285`：转出交易子账户  
`286`: 转出托管资金账户  
`287`: 转入托管资金账户  
`288`: 托管资金入金  
`289`: 托管资金出金  
clientId | String | 否 | 转账或提币的客户自定义ID  
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
clientId | String | 转账或提币的客户自定义ID  
balChg | String | 账户层面的余额变动数量  
bal | String | 账户层面的余额数量  
type | String | 账单类型  
ts | String | 账单创建时间，Unix 时间戳的毫秒数格式，如 `1597026383085`  
  
### 闪电网络充币

一个用户在最近24小时内可以生成不超过1万个不同的invoice。

#### 限速：2次/s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/asset/deposit-lightning`

> 请求示例
    
    
    GET /api/v5/asset/deposit-lightning?ccy=BTC&amt=0.01
    
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
ccy | String | 是 | 币种，仅支持`BTC`  
amt | String | 是 | 充值数量，推荐在0.000001〜0.1之间  
to | String | 否 | 资金充值到账账户  
`6`: 资金账户  
`18`: 交易账户  
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
仅针对部分用户开放此API功能服务，如果需要此功能服务请发邮件至`pablo.magro@okx.com`申请

### 获取充值地址信息

获取各个币种的充值地址，包括曾使用过的老地址。

#### 限速：6次/s

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
memo | String | 部分币种充值需要 memo，若不需要则不返回此字段  
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

#### 限速：6次/s

#### 限速规则：UserID

#### HTTP 请求

`GET /api/v5/asset/deposit-history`

> 请求示例
    
    
    查询最近的充值记录
    GET /api/v5/asset/deposit-history
    
    查询从2022年06月01日到2022年07月01日之间的BTC的充值记录
    GET /api/v5/asset/deposit-history?ccy=BTC&after=1654041600000&before=1656633600000
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
ccy | String | 否 | 币种名称，如 `BTC`  
depId | String | 否 | 充值记录 ID  
fromWdId | String | 否 | 内部转账发起者提币申请 ID  
如果该笔充值来自于内部转账，则该字段展示内部转账发起者的提币申请 ID  
txId | String | 否 | 区块转账哈希记录  
type | String | 否 | 充值方式  
`3`：内部转账  
`4`：链上充值  
state | String | 否 | 充值状态  
`0`：等待确认  
`1`：确认到账  
`2`：充值成功  
`8`：因该币种暂停充值而未到账，恢复充值后自动到账  
`11`：命中地址黑名单  
`12`：账户或充值被冻结  
`13`：子账户充值拦截  
after | String | 否 | 查询在此之前的内容，值为时间戳，Unix 时间戳为毫秒数格式，如 `1654041600000`  
before | String | 否 | 查询在此之后的内容，值为时间戳，Unix 时间戳为毫秒数格式，如 `1656633600000`  
limit | string | 否 | 返回的结果集数量，默认为100，最大为100，不填默认返回100条  
  
> 返回结果
    
    
    {
      "code": "0",
      "msg": "",
      "data": [
        {
            "actualDepBlkConfirm": "2",
            "amt": "1",
            "areaCodeFrom": "",
            "ccy": "USDT",
            "chain": "USDT-TRC20",
            "depId": "88****33",
            "from": "",
            "fromWdId": "",
            "state": "2",
            "to": "TN4hGjVXMzy*********9b4N1aGizqs",
            "ts": "1674038705000",
            "txId": "fee235b3e812********857d36bb0426917f0df1802"
        },
        {
            "actualDepBlkConfirm": "",
            "amt": "11",
            "areaCodeFrom": "86",
            "ccy": "USDT",
            "chain": "USDT-Omni",
            "depId": "53****85",
            "from": "158****5369",
            "fromWdId": "",
            "state": "2",
            "to": "",
            "ts": "1651809380000",
            "txId": "36532892_**********_0_WALLET"
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
from | String | 充值账户  
如果该笔充值来自于内部转账，则该字段展示内部转账发起者的账户信息，可以是手机号、邮箱、账户名称，其他情况返回""  
areaCodeFrom | String | 如果`from`为手机号，该字段为该手机号的区号  
to | String | 到账地址  
如果该笔充值来自于链上充值，则该字段展示链上地址，其他情况返回""  
txId | String | 区块转账哈希记录  
ts | String | 充值到账时间，Unix 时间戳的毫秒数格式，如 `1655251200000`  
state | String | 充值状态  
`0`：等待确认  
`1`：确认到账  
`2`：充值成功  
`8`：因该币种暂停充值而未到账，恢复充值后自动到账  
`11`：命中地址黑名单  
`12`：账户或充值被冻结  
`13`：子账户充值拦截  
depId | String | 充值记录 ID  
fromWdId | String | 内部转账发起者提币申请 ID  
如果该笔充值来自于内部转账，则该字段展示内部转账发起者的提币申请 ID，其他情况返回""  
actualDepBlkConfirm | String | 最新的充币网络确认数  
等待确认是没有达到充币确认数。  
确认到账是够充币确认数，且币已经到账户中，但是不可提。  
充值成功是当前账户完成到提币确认，可以提出。

### 提币

用户提币。普通子账户不支持提币。

#### 限速：6次/s

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
dest | String | 是 | 提币方式  
`3`：内部转账  
`4`：链上提币  
toAddr | String | 是 | 如果选择链上提币，`toAddr`必须是认证过的数字货币地址。某些数字货币地址格式为`地址:标签`，如
`ARDOR-7JF3-8F2E-QUWZ-CAN7F:123456`  
如果选择内部转账，`toAddr`必须是接收方地址，可以是邮箱、手机或者账户名。  
fee | String | 是 | 网络手续费≥`0`，提币到数字货币地址所需网络手续费可通过获取币种列表接口查询  
chain | String | 可选 | 币种链信息  
如`USDT`下有`USDT-ERC20`，`USDT-TRC20`，`USDT-Omni`多个链  
如果没有不填此参数，则默认为主链  
areaCode | String | 可选 | 手机区号  
当`toAddr`为手机号时，该参数必填  
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

单笔提币金额最大值为"0.1BTC"，最小值暂定为"0.000001BTC"，最近24小时内最大提币数量为"1BTC"。子账户不支持提币。

#### 限速：2次/s

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
wdId | String | 提币申请 ID  
cTime | String | 提币申请 ID生成时间  
仅针对部分用户开放此API功能服务，如果需要此功能服务请发邮件至`pablo.magro@okx.com`申请

### 撤销提币

可以撤销普通提币，但不支持撤销闪电网络上的提币。

#### 限速：6次/s

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

#### 限速：6 次/s

#### 限速规则：UserID

#### HTTP 请求

`GET /api/v5/asset/withdrawal-history`

> 请求示例
    
    
    查询最近的提币记录
    GET /api/v5/asset/withdrawal-history
    
    查询从2022年06月01日到2022年07月01日之间的BTC的提币记录
    GET /api/v5/asset/withdrawal-history?ccy=BTC&after=1654041600000&before=1656633600000
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
ccy | String | 否 | 币种名称，如 `BTC`  
wdId | String | 否 | 提币申请ID  
clientId | String | 否 | 客户自定义ID  
字母（区分大小写）与数字的组合，可以是纯字母、纯数字且长度要在1-32位之间。  
txId | String | 否 | 区块转账哈希记录  
type | String | 否 | 提币方式  
`3`：内部转账  
`4`：链上提币  
state | String | 否 | 提币状态  
`-3`：撤销中  
`-2`：已撤销  
`-1`：失败  
`0`：等待提币  
`1`：提币中  
`2`：提币成功  
`7`: 审核通过  
`10`: 等待划转  
`4`, `5`, `6`, `8`, `9`, `12`: 等待客服审核  
after | String | 否 | 查询在此之前的内容，值为时间戳，Unix 时间戳为毫秒数格式，如 `1654041600000`  
before | String | 否 | 查询在此之后的内容，值为时间戳，Unix 时间戳为毫秒数格式，如 `1656633600000`  
limit | string | 否 | 返回的结果集数量，默认为100，最大为100，不填默认返回100条  
  
> 返回结果
    
    
    {
      "code": "0",
      "msg": "",
      "data": [
        {
          "chain": "ETH-Ethereum",
          "fee": "0.007",
          "feeCcy": "ETH",
          "ccy": "ETH",
          "clientId": "",
          "amt": "0.029809",
          "txId": "0x35c******b360a174d",
          "from": "156****359",
          "areaCodeFrom": "86",
          "to": "0xa30d1fab********7CF18C7B6C579",
          "areaCodeTo": "",
          "state": "2",
          "ts": "1655251200000",
          "nonTradableAsset": false,
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
nonTradableAsset | Boolean | 是否为不可交易资产  
`true`：不可交易资产，`false`：可交易资产  
amt | String | 数量  
ts | String | 提币申请时间，Unix 时间戳的毫秒数格式，如 `1655251200000`  
from | String | 提币账户  
可以是邮箱/手机号  
areaCodeFrom | String | 如果`from`为手机号，该字段为该手机号的区号  
to | String | 收币地址  
areaCodeTo | String | 如果`to`为手机号，该字段为该手机号的区号  
tag | String | 部分币种提币需要标签，若不需要则不返回此字段  
pmtId | String | 部分币种提币需要此字段（payment_id），若不需要则不返回此字段  
memo | String | 部分币种提币需要此字段，若不需要则不返回此字段  
addrEx | Object |
提币地址备注，部分币种提币需要，若不需要则不返回此字段。如币种TONCOIN的提币地址备注标签名为comment,则该字段返回：{'comment':'123456'}  
txId | String | 提币哈希记录  
内部转账该字段返回""  
fee | String | 提币手续费数量  
feeCcy | String | 提币手续费币种，如 `USDT`  
state | String | 提币状态  
`-3`：撤销中  
`-2`：已撤销  
`-1`：失败  
`0`：等待提币  
`1`：提币中  
`2`：提币成功  
`7`: 审核通过  
`10`: 等待划转  
`4`, `5`, `6`, `8`, `9`, `12`: 等待客服审核  
wdId | String | 提币申请ID  
clientId | String | 客户自定义ID  
  
### 获取充值/提现的详细状态

获取充值与提现的详细状态信息与预估完成时间。

#### 限速：1次/2s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/asset/deposit-withdraw-status`

> 请求示例
    
    
    // 查询充值
    GET /api/v5/asset/deposit-withdraw-status?txId=xxxxxx&to=1672734730284&ccy=USDT&chain=USDT-ERC20
    
    // 查询提现
    GET /api/v5/asset/deposit-withdraw-status?wdId=200045249
    
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
wdId | String | 可选 | 提币申请ID，用于查询资金提现  
`wdId`与`txId`必传其一也仅可传其一  
txId | String | 可选 | 区块转账哈希记录ID，用于查询资金充值  
`wdId`与`txId`必传其一也仅可传其一  
ccy | String | 可选 | 币种，如`USDT`  
查询充值时必填，需要与txId一并提供  
to | String | 可选 | 资金充值到账账户地址  
查询充值时必填，需要与txId一并提供  
chain | String | 可选 | 币种链信息，例如 USDT-ERC20  
查询充值时必填，需要与txId一并提供  
  
> 返回结果
    
    
    {
        "code":"0",
        "data":[
            {
                "wdId": "200045249",
                "txId": "16f3638329xxxxxx42d988f97", //此时提现如生成了txId将一并返回
                "state": "Pending withdrawal: Wallet is under maintenance, please wait.",
                "estCompleteTime": "01/09/2023, 8:10:48 PM"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
estCompleteTime | String | 预估完成时间  
时区为 UTC+8；格式为 MM/dd/yyyy, h:mm:ss AM/PM  
estCompleteTime仅为预估完成时间，仅供参考  
state | String | 充值/提现的现处于的详细阶段提示  
冒号前面代表阶段，后面代表状态  
txId | String | 区块转账哈希记录  
如查询的是提现，则txId返回为空""，此时提现如生成了txId将一并返回  
wdId | String | 提币申请ID  
如查询的是充值，则wdId返回为空""  
阶段参考  
充值  
阶段一：监测链上交易  
阶段二：推送充值数据到入账环节  
阶段三：进行入账  
终态：充值已完成  
提现  
阶段一：等待提现  
阶段二：提现中  
终态：提现已完成 / 撤销已完成  

### 小额资产兑换

将资金账户中的小额资产转化为`OKB`。24小时之内只能兑换5次。

#### 限速：1次/s

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
ccy | Array of strings | 是 | 需要转换的币种资产，如 ["BTC","USDT"]  
  
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
details | Array of objects | 各币种资产转换详情  
> ccy | String | 币种资产,如 `BTC`  
> amt | String | 转换前币种资产数量  
> cnvAmt | String | 转换后的`OKB`数量  
> fee | String | 兑换手续费，单位为`OKB`  
  
## 闪兑

`闪兑`功能模块下的API接口需要身份验证。仅支持资金账户中的资产做闪兑交易。

### 获取闪兑币种列表

#### 限速：6次/s

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
                "min": "",  // 已废弃
                "max": "",  // 已废弃
                "ccy": "BTC"
            },
            {
                "min": "",
                "max": "",
                "ccy": "ETH"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
ccy | String | 币种名称，如 `BTC`  
min | String | 支持闪兑的最小值(已废弃)  
max | String | 支持闪兑的最大值(已废弃)  
  
### 获取闪兑币对信息

#### 限速：6次/s

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

#### 限速：10次/s

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
适用于broker用户  
  
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

#### 限速：10次/s

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
适用于broker用户  
  
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

#### 限速：6次/s

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
适用于broker用户  
  
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

#### 限速：10次/2s

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
                        "stgyEq":"0",
                        "spotInUseAmt":""
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
                        "stgyEq":"0",
                        "spotInUseAmt":""
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
适用于`简单交易模式`、`单币种保证金模式`、`跨币种保证金模式`和`组合保证金模式`  
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
> interest | String | 计息，应扣未扣利息。  
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
> spotInUseAmt | String | 现货对冲占用数量  
适用于`组合保证金模式`  
当前账户等级下无效字段返回""  币种余额小于 1e-8 的币种信息，会在 details 中过滤掉不返回。

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
> availBal | 是 | 是 | 是  
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

获取该账户下拥有实际持仓的信息。账户为单向持仓模式会显示净持仓（`net`），账户为双向持仓模式下会分别返回多头（`long`）或空头（`short`）的仓位。按照仓位创建时间倒序排列。

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
`instType`和`instId`同时传入的时候会校验`instId`与`instType`是否一致。  
instId | String | 否 | 交易产品ID，如：`BTC-USD-190927-5000-C`  
支持多个`instId`查询（不超过10个），半角逗号分隔  
posId | String | 否 | 持仓ID  
支持多个`posId`查询（不超过20个），半角逗号分割  
如果该 instId 拥有过仓位且当前持仓量为0，传 instId 时，会返回仓位信息；不传 instId 时，仓位信息不返回。
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
            "spotInUseAmt": "",
            "spotInUseCcy": "",
            "thetaBS":"",
            "thetaPA":"",
            "tradeId":"109844",
            "bizRefId": "",
            "bizRefType": "",
            "quoteBal": "0",
            "baseBal": "0",
            "baseBorrowed": "",
            "baseInterest": "",
            "quoteBorrowed": "",
            "quoteInterest": "",
            "uTime":"1619507761462",
            "upl":"-0.0000009932766034",
            "uplRatio":"-0.0025490556801078",
            "vegaBS":"",
            "vegaPA":"",
            "closeOrderAlgo":[
                {
                    "algoId":"123",
                    "slTriggerPx":"123",
                    "slTriggerPxType":"mark",
                    "tpTriggerPx":"123",
                    "tpTriggerPxType":"mark",
                    "closeFraction":"0.6"
                },
                {
                    "algoId":"123",
                    "slTriggerPx":"123",
                    "slTriggerPxType":"mark",
                    "tpTriggerPx":"123",
                    "tpTriggerPxType":"mark",
                    "closeFraction":"0.4"
                }
           ]
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
baseBal | String | 交易币余额，适用于 `币币杠杆`（逐仓自主划转模式 和 一键借币模式）  
quoteBal | String | 计价币余额 ，适用于 `币币杠杆`（逐仓自主划转模式 和 一键借币模式）  
baseBorrowed | String | 交易币已借，适用于 币币杠杆（逐仓一键借币模式）  
baseInterest | String | 交易币计息，适用于 币币杠杆（逐仓一键借币模式）  
quoteBorrowed | String | 计价币已借，适用于 币币杠杆（逐仓一键借币模式）  
quoteInterest | String | 计价币计息，适用于 币币杠杆（逐仓一键借币模式）  
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
spotInUseAmt | String | 现货对冲占用数量  
适用于`组合保证金模式`  
spotInUseCcy | String | 现货对冲占用币种，如 `BTC`  
适用于`组合保证金模式`  
closeOrderAlgo | Array | 平仓策略委托订单。调用策略委托下单，且`closeFraction`=1 时，该数组才会有值。  
> algoId | String | 策略委托单ID  
> slTriggerPx | String | 止损触发价  
> slTriggerPxType | String | 止损触发价类型  
`last`：最新价格  
`index`：指数价格  
`mark`：标记价格  
> tpTriggerPx | String | 止盈委托价  
> tpTriggerPxType | String | 止盈触发价类型  
`last`：最新价格  
`index`：指数价格  
`mark`：标记价格  
> closeFraction | String | 策略委托触发时，平仓的百分比。1 代表100%  
cTime | String | 持仓创建时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
uTime | String | 最近一次持仓更新时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
bizRefId | String | 外部业务id，e.g. 体验券id  
bizRefType | String | 外部业务类型  
PM账户下，持仓的 IMR MMR的数据是后端服务以ristUnit为最小粒度重新计算，相同riskUnit全仓仓位的imr和mmr返回值相同。

### 查看历史持仓信息

获取最近3个月有更新的仓位信息，按照仓位更新时间倒序排列。

#### 限速：1次/10s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/account/positions-history`

> 请求示例
    
    
    GET /api/v5/account/positions-history
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instType | String | 否 | 产品类型  
`MARGIN`：币币杠杆  
`SWAP`：永续合约  
`FUTURES`：交割合约  
`OPTION`：期权  
instId | String | 否 | 交易产品ID，如：`BTC-USD-SWAP`  
mgnMode | String | 否 | 保证金模式  
`cross`：全仓，`isolated`：逐仓  
type | String | 否 | 平仓类型  
`1`：部分平仓;`2`：完全平仓;`3`：强平;`4`：强减; `5`：ADL自动减仓;  
状态叠加时，以最新的平仓类型为准状态为准。  
posId | String | 否 | 持仓ID  
after | String | 否 | 查询仓位更新 (uTime) 之前的内容，值为时间戳，Unix 时间戳为毫秒数格式，如
`1597026383085`  
before | String | 否 | 查询仓位更新 (uTime) 之后的内容，值为时间戳，Unix 时间戳为毫秒数格式，如
`1597026383085`  
limit | String | 否 | 分页返回结果的数量，最大为100，默认100条  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "cTime": "1654177169995",
                "ccy": "BTC",
                "closeAvgPx": "29786.5999999789081085",
                "closeTotalPos": "1",
                "instId": "BTC-USD-SWAP",
                "instType": "SWAP",
                "lever": "10.0",
                "mgnMode": "cross",
                "openAvgPx": "29783.8999999995535393",
                "openMaxPos": "1",
                "pnl": "0.00000030434156",
                "pnlRatio": "0.000906447858888",
                "posId": "452587086133239818",
                "direction": "long",
                "triggerPx": "",
                "type": "allClose",
                "uTime": "1654177174419",
                "uly": "BTC-USD"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
instType | String | 产品类型  
instId | String | 交易产品ID  
mgnMode | String | 保证金模式  
`cross`：全仓，`isolated`：逐仓  
type | String | 平仓类型  
`1`：部分平仓;`2`：完全平仓;`3`：强平;`4`：强减; `5`：ADL自动减仓;  
状态叠加时，以最新的平仓类型为准状态为准。  
cTime | String | 仓位创建时间  
uTime | String | 仓位更新时间  
openAvgPx | String | 开仓均价  
closeAvgPx | String | 平仓均价  
posId | String | 仓位ID  
openMaxPos | String | 最大持仓量  
closeTotalPos | String | 累计平仓量  
pnl | String | 平仓收益额  
pnlRatio | String | 平仓收益率  
lever | String | 杠杆倍数  
direction | String | 持仓方向 `long`：多 `short`：空  
仅适用于 `币币杠杆/交割/永续/期权`  
triggerPx | String | 触发标记价格  
liqPx | String | 强平价  
uly | String | 标的指数  
  
### 查看账户持仓风险

查看账户整体风险。

获取同一时间切片上的账户和持仓的基础信息

#### 限速：10次/2s

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
    

币种余额小于 1e-8 的币种信息，会在 details 中过滤掉不返回。

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
> baseBal | String | 交易币余额，适用于 `币币杠杆`（逐仓自主划转模式和逐仓一键借币模式）  
> quoteBal | String | 计价币余额 ，适用于 `币币杠杆`（逐仓自主划转模式和逐仓一键借币模式）  
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
  
ccy | String | 否 | 账单币种  
mgnMode | String | 否 | 仓位类型  
`isolated`：逐仓  
`cross`：全仓  
ctType | String | 否 | `linear`： 正向合约  
`inverse`： 反向合约  
仅`交割/永续`有效  
type | String | 否 | 账单类型  
`1`：划转 `2`：交易 `3`：交割 `4`：自动换币 `5`：强平 `6`：保证金划转 `7`：扣息 `8`：资金费 `9`：自动减仓
`10`：穿仓补偿 `11`：系统换币 `12`：策略划拨 `13`：对冲减仓 `14`: 大宗交易 `15`: 一键借币 `18`: 分润 `22`:
一键还债  
subType | String | 否 | 账单子类型  
`1`：买入 `2`：卖出 `3`：开多 `4`：开空 `5`：平多 `6`：平空 `9`：市场借币扣息 `11`：转入 `12`：转出
`14`：尊享借币扣息 `160`：手动追加保证金 `161`：手动减少保证金 `162`：自动追加保证金 `114`：自动换币买入
`115`：自动换币卖出 `118`：系统换币转入 `119`：系统换币转出 `100`：强减平多 `101`：强减平空 `102`：强减买入
`103`：强减卖出 `104`：强平平多 `105`：强平平空 `106`：强平买入 `107`：强平卖出 `110`：强平换币转入
`111`：强平换币转出 `125`：自动减仓平多 `126`：自动减仓平空 `127`：自动减仓买入 `128`：自动减仓卖出 `131`：对冲买入
`132`：对冲卖出 `170`：到期行权 `171`：到期被行权 `172`：到期作废 `112`：交割平多 `113`：交割平空
`117`：交割/期权穿仓补偿 `173`：资金费支出 `174`：资金费收入 `200`:系统转入 `201`:手动转入 `202`:系统转出
`203`:手动转出 `204`: 大宗交易买 `205`: 大宗交易卖 `206`: 大宗交易开多 `207`: 大宗交易开空 `208`: 大宗交易平多
`209`: 大宗交易平空 `210`: 手动借币 `211`: 手动还币 `212`: 自动借币 `213`：自动还币" `16`：强制还币
`17`：强制借币还息 `224`: 还债转入 `225`: 还债转出 `250`: 分润支出; `251`: 分润退还; `252`: 分润收入;  
after | String | 否 | 请求此id之前（更旧的数据）的分页内容，传的值为对应接口的`billId`  
before | String | 否 | 请求此id之后（更新的数据）的分页内容，传的值为对应接口的`billId`  
begin | String | 否 | 筛选的开始时间戳，Unix 时间戳为毫秒数格式，如 1597026383085  
end | String | 否 | 筛选的结束时间戳，Unix 时间戳为毫秒数格式，如 1597027383085  
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
仅适用于`资金划转`，不是`资金划转`时，返回 ""  
  
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
  
ccy | String | 否 | 账单币种  
mgnMode | String | 否 | 仓位类型  
`isolated`：逐仓 `cross`：全仓  
ctType | String | 否 | `linear`： 正向合约  
`inverse`： 反向合约  
仅`交割/永续`有效  
type | String | 否 | 账单类型  
`1`：划转 `2`：交易 `3`：交割 `4`：自动换币 `5`：强平 `6`：保证金划转 `7`：扣息 `8`：资金费 `9`：自动减仓
`10`：穿仓补偿 `11`：系统换币 `12`：策略划拨 `13`：对冲减仓 `14`: 大宗交易 `15`: 一键借币 `22`: 一键还债 `18`:
分润  
subType | String | 否 | 账单子类型  
`1`：买入 `2`：卖出 `3`：开多 `4`：开空 `5`：平多 `6`：平空 `9`：市场借币扣息 `11`：转入 `12`：转出
`14`：尊享借币扣息 `160`：手动追加保证金 `161`：手动减少保证金 `162`：自动追加保证金 `114`：自动换币买入
`115`：自动换币卖出 `118`：系统换币转入 `119`：系统换币转出 `100`：强减平多 `101`：强减平空 `102`：强减买入
`103`：强减卖出 `104`：强平平多 `105`：强平平空 `106`：强平买入 `107`：强平卖出 `110`：强平换币转入
`111`：强平换币转出 `125`：自动减仓平多 `126`：自动减仓平空 `127`：自动减仓买入 `128`：自动减仓卖出 `131`：对冲买入
`132`：对冲卖出 `170`：到期行权 `171`：到期被行权 `172`：到期作废 `112`：交割平多 `113`：交割平空
`117`：交割/期权穿仓补偿 `173`：资金费支出 `174`：资金费收入 `200`:系统转入 `201`:手动转入 `202`:系统转出
`203`:手动转出 `204`: 大宗交易买 `205`: 大宗交易卖 `206`: 大宗交易开多 `207`: 大宗交易开空 `208`: 大宗交易平多
`209`: 大宗交易平空 `210`: 手动借币 `211`: 手动还币 `212`: 自动借币 `213`：自动还币" `16`：强制还币
`17`：强制借币还息 `224`: 还债转入 `225`: 还债转出 `250`: 分润支出; `251`: 分润退还; `252`: 分润收入;  
after | String | 否 | 请求此id之前（更旧的数据）的分页内容，传的值为对应接口的`billId`  
before | String | 否 | 请求此id之后（更新的数据）的分页内容，传的值为对应接口的`billId`  
begin | String | 否 | 筛选的开始时间戳，Unix 时间戳为毫秒数格式，如 1597026383085  
end | String | 否 | 筛选的结束时间戳，Unix 时间戳为毫秒数格式，如 1597027383085  
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
仅适用于`资金划转`，不是`资金划转`时，返回 ""  
  
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
                "level": "Lv1",
                "levelTmp": "",
                "mgnIsoMode": "automatic",
                "posMode": "net_mode",
                "spotOffsetType": "",
                "uid": "44705892343619584",
                "label": "V5 Test",
                "opAuth": "0",
                "ip": "120.255.24.182,49.245.196.13"
    
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
`quick_margin`：一键借币（对于新的账户，包括新的子账户，有些默认是开仓划转，另外的默认是一键借币）  
spotOffsetType | String | 现货对冲类型  
`1`：现货对冲模式U模式 `2`：现货对冲模式币模式 `3`：非现货对冲模式  
适用于`组合保证金模式`  
label | String | 当前请求API Key的备注名，不超过50位字母（区分大小写）或数字，可以是纯字母或纯数字。  
roleType | String | 用户角色。  
`0`：普通用户；`1`：带单者；`2`：跟单者  
traderInsts | Array | 当前账号已经设置的带单合约，仅适用于带单者  
opAuth | String | 是否开通期权交易  
`0` 未开通，`1` 已经开通  
ip | String | 绑定的ip地址，多个ip用半角逗号隔开，如：`117.37.203.58,117.37.203.57`。  
如果没有绑定ip，会返回空字符串""  
  
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

  
一个产品可以有如下9种杠杆倍数的设置场景：  
  

  1. 在`逐仓`交易模式下，设置`币币杠杆`的杠杆倍数（币对层面）；  

  2. `单币种保证金`账户在`全仓`交易模式下，设置`币币杠杆`的杠杆倍数（币对层面）；  

  3. `跨币种保证金`账户在`全仓`交易模式下，设置`币币杠杆`的杠杆倍数（币种层面）；  

  4. 在`全仓`交易模式下，设置`交割`的杠杆倍数（指数层面）；  

  5. 在`逐仓`交易模式、`买卖`持仓模式下，设置`交割`的杠杆倍数（合约层面）；  

  6. 在`逐仓`交易模式、`开平仓`持仓模式下，设置`交割`的杠杆倍数（合约与持仓方向层面）；  

  7. 在`全仓`交易模式下，设置`永续`的杠杆倍数（合约层面）；  

  8. 在`逐仓`交易模式、`买卖`持仓模式下，设置`永续`的杠杆倍数（合约层面）；  

  9. 在`逐仓`交易模式、`开平仓`持仓模式下，设置`永续`的杠杆倍数（合约与持仓方向层面）；  
  

注意请求参数 posSide 仅在`交割/永续`的`开平仓`持仓模式下才需要填写（参见场景6和9）。  
请参阅右侧对应的每个案例的请求示例。  

#### 限速：20次/2s

#### 限速规则：UserID

#### HTTP请求

`POST /api/v5/account/set-leverage`

> 请求示例
    
    
    # 1.在`逐仓`交易模式下，设置`币币杠杆`的杠杆倍数（币对层面）
    POST /api/v5/account/set-leverage
    body
    {
        "instId":"BTC-USDT",
        "lever":"5",
        "mgnMode":"isolated"
    }
    
    # 2.`单币种保证金`账户在`全仓`交易模式下，设置`币币杠杆`的杠杆倍数（币对层面）
    POST /api/v5/account/set-leverage
    body
    {
        "instId":"BTC-USDT",
        "lever":"5",
        "mgnMode":"cross"
    }
    
    # 3.`跨币种保证金`账户在`全仓`交易模式下，设置`币币杠杆`的杠杆倍数（币种层面）
    POST /api/v5/account/set-leverage
    body
    {
        "ccy":"BTC",
        "lever":"5",
        "mgnMode":"cross"
    }
    
    # 4.在`全仓`交易模式下，设置`交割`的杠杆倍数（指数层面）
    POST /api/v5/account/set-leverage
    body
    {
        "instId":"BTC-USDT-200802",
        "lever":"5",
        "mgnMode":"cross"
    }
    
    # 5.在`逐仓`交易模式、`买卖`持仓模式下，设置`交割`的杠杆倍数（合约层面）
    POST /api/v5/account/set-leverage
    body
    {
        "instId":"BTC-USDT-200802",
        "lever":"5",
        "mgnMode":"isolated"
    }
    
    # 6.在`逐仓`交易模式、`开平仓`持仓模式下，设置`交割`的杠杆倍数（合约与头寸层面）
    POST /api/v5/account/set-leverage
    body
    {
        "instId":"BTC-USDT-200802",
        "lever":"5",
        "posSide":"long",
        "mgnMode":"isolated"
    }
    
    # 7.在`全仓`交易模式下，设置`永续`的杠杆倍数（合约层面）
    POST /api/v5/account/set-leverage
    body
    {
        "instId":"BTC-USDT-SWAP",
        "lever":"5",
        "mgnMode":"cross"
    }
    
    # 8.在`逐仓`交易模式、`买卖`持仓模式下，设置`永续`的杠杆倍数（合约层面）
    POST /api/v5/account/set-leverage
    body
    {
        "instId":"BTC-USDT-SWAP",
        "lever":"5",
        "mgnMode":"isolated"
    }
    
    # 9.在`逐仓`交易模式、`开平仓`持仓模式下，设置`永续`的杠杆倍数（合约与头寸层面）
    POST /api/v5/account/set-leverage
    body
    {
        "instId":"BTC-USDT-SWAP",
        "lever":"5",
        "posSide":"long",
        "mgnMode":"isolated"
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
仅适用于逐仓`交割`/`永续`  
在双向持仓且保证金模式为逐仓条件下必填  
  
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

Portfolio Margin 账户下，衍生品的全仓模式不支持最大可买卖/开仓数量的计算。

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
unSpotOffset | Boolean | 否 | `true`：禁止现货对冲，`false`：允许现货对冲  
默认为`false`  
仅适用于`组合保证金模式`  
开启现货对冲模式下有效，否则忽略此参数。  
  
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
unSpotOffset | Boolean | 否 | `true`：禁止现货对冲，`false`：允许现货对冲  
默认为`false`  
仅适用于`组合保证金模式`  
开启现货对冲模式下有效，否则忽略此参数。  
quickMgnType | String | 否 | 一键借币类型，仅适用于杠杆逐仓的一键借币模式：  
`manual`：手动，`auto_borrow`： 自动借币，`auto_repay`： 自动还币  
默认是`manual`：手动  
  
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
`add`：增加，或者转入质押资产(一键借币)  
`reduce`：减少，或者转出质押资产（一键借币）  
amt | String | 是 | 增加或减少的保证金数量  
ccy | String | 否 | 增加或减少的保证金的币种，  
仅适用于逐仓自主划转和一键借币模式下的币币杠杆  
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
组合保证金账户下交割和永续的全仓不能获取杠杆倍数。

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
适用于`交割/永续/期权`，如 `BTC-USD`  
instFamily | String | 否 | 交易品种  
适用于`交割/永续/期权`，如 `BTC-USD`  
  
> 返回结果
    
    
    {
        "code": "0",
        "msg": "",
        "data": [{
                "category": "1", //已废弃
                "delivery": "",
                "exercise": "",
                "instType": "SPOT",
                "level": "lv1",
                "maker": "-0.0008",
                "makerU": "",
                "makerUSDC": "",
                "taker": "-0.001",
                "takerU": "",
                "takerUSDC": "",
                "ts": "1608623351857"
            }
        ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
level | String | 手续费等级  
taker | String | USDT&USDⓈ&Crypto 交易区的吃单手续费率，永续和交割合约时，为币本位合约费率  
maker | String | USDT&USDⓈ&Crypto 交易区挂单手续费率，永续和交割合约时，为币本位合约费率  
takerU | String | USDT 合约吃单手续费率，仅适用于`交割/永续`  
makerU | String | USDT 合约挂单手续费率，仅适用于`交割/永续`  
delivery | String | 交割手续费率  
exercise | String | 行权手续费率  
instType | String | 产品类型  
takerUSDC | String | USDC 交易区的吃单手续费率，包括 USDC 现货和 USDC 合约  
makerUSDC | String | USDC 交易区的挂单手续费率，包括 USDC 现货和 USDC 合约  
ts | String | 数据返回时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
category | String | 币种类别，注意：此参数已废弃  
备注：  
maker/taker的值：正数，代表是返佣的费率；负数，代表平台扣除的费率。  USDⓈ 代表除 USDT 和 USDC 之外的稳定币。

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
quick_margin:一键借币  
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
quick_margin:一键借币  
衍生品  
开仓划转：在开仓和平仓时自动占用和释放保证金
自主划转：需要手动给仓位划入保证金然后开始交易。该选项主要供专业用户使用，会有初次划入仓位资金≥10,000USDT的限制。  杠杆  
开仓划转：在开仓和平仓时自动借币和还币
自主划转：需要手动给仓位划入保证金然后交易，同时也支持手动转出借币。该选项主要供专业用户使用，会有初次划入仓位资金≥10,000USDT的限制。

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
                "maxWdEx": "125",
                "spotOffsetMaxWd": "",
                "spotOffsetMaxWdEx": ""
            },
            {
                "ccy": "ETH",
                "maxWd": "10",
                "maxWdEx": "12",
                "spotOffsetMaxWd": "",
                "spotOffsetMaxWdEx": ""
            }
        ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
ccy | String | 币种  
maxWd | String | 最大可划转数量（不包含`跨币种保证金模式`借币金额）  
maxWdEx | String | 最大可划转数量（包含`跨币种保证金模式`借币金额）  
spotOffsetMaxWd | String | 现货对冲不支持借币最大可转数量  
仅适用于`组合保证金模式`  
spotOffsetMaxWdEx | String | 现货对冲支持借币的最大可转数量  
仅适用于`组合保证金模式`  
  
### 查看账户特定风险状态

仅适用于PM账户

#### 限速：10次/2s

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
true： 当前账户为特定风险状态  
false： 当前不是特定风险状态  
atRiskIdx | Array | 衍生品的risk unit列表  
atRiskMgn | Array | 杠杆的risk unit列表  
ts | String | 接口数据返回时间 ，Unix时间戳的毫秒数格式，如 `1597026383085`  
当账户进入特定风险状态后，仅可以委托降低账户风险方向的IOC类型订单.

### 一键借币模式手动借币还币

#### 限速：5次/2s

#### 限速规则：UserID

#### HTTP请求

`POST /api/v5/account/quick-margin-borrow-repay`

> 请求示例
    
    
    POST /api/v5/account/quick-margin-borrow-repay 
    body
    {
        "instId":"BTC-USDT",
        "ccy":"USDT",
        "side":"borrow",
        "amt":"100"
    }
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instId | String | 是 | 产品ID，如BTC-USDT  
ccy | String | 是 | 借贷币种，如 `BTC`  
side | String | 是 | `borrow`：借币，`repay`：还币  
amt | String | 是 | 借/还币的数量  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "amt": "100",
                "instId":"BTC-USDT",
                "ccy": "USDT",
                "side": "borrow"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
instId | String | 产品ID，如BTC-USDT  
ccy | String | 借贷币种，如 `BTC`  
side | String | `borrow`：借币，`repay`：还币  
amt | String | 借/还币的数量  
  
### 获取一键借币还币历史

#### 限速：5次/2s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/account/quick-margin-borrow-repay-history`

> 请求示例
    
    
    GET /api/v5/account/quick-margin-borrow-repay-history
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instId | String | 否 | 产品ID，如 BTC-USDT  
ccy | String | 否 | 借贷币种，如 `BTC`  
side | String | 否 | `borrow`：借币，`repay`：还币  
after | String | 否 | 请求此 ID 之前（更旧的数据）的分页内容，传的值为对应接口的`refId`  
before | String | 否 | 请求此 ID 之后（更新的数据）的分页内容，传的值为对应接口的`refId`  
begin | String | 否 | 筛选的开始时间戳，Unix 时间戳为毫秒数格式，如 1597026383085  
end | String | 否 | 筛选的结束时间戳，Unix 时间戳为毫秒数格式，如 1597027383085  
limit | String | 否 | 返回结果的数量，最大为100，默认100条  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "instId": "BTC-USDT",
                "ccy": "USDT",
                "side": "borrow",
                "accBorrowed": "0.01",
                "amt": "0.005",
                "refId": "1637310691470124",
                "ts": "1637310691470"
            },
            {
                "instId": "BTC-USDT",
                "ccy": "USDT",
                "side": "borrow",
                "accBorrowed": "0.01",
                "amt": "0.005",
                "refId": "1637310691470123",
                "ts": "1637310691400"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
instId | String | 产品ID，如 BTC-USDT  
ccy | String | 借贷币种，如 `BTC`  
side | String | `borrow`：借币，`repay`：还币  
accBorrowed | String | 累计借币  
amt | String | 借/还币的数量  
refId | String | 对应记录ID，借币或还币的ID  
ts | String | 借/还币时间  
  
### 尊享借币还币

单个币种的借币订单数量最多为20个

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
        "amt":"100",
        "ordId":"1234113444"
    }
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
ccy | String | 是 | 借贷币种，如 `BTC`  
side | String | 是 | `borrow`：借币，`repay`：还币  
amt | String | 是 | 借/还币的数量  
ordId | String | 可选 | 借币订单ID，还币时，该字段必填  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "amt": "70809.316200",
                "ccy": "USDT",
                "ordId": "544199684697214976",
                "side": "borrow",
                "state": "1"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
ccy | String | 借贷币种，如 `BTC`  
side | String | `borrow`：借币，`repay`：还币  
amt | String | 已借/还币的数量  
ordId | String | 借币订单ID  
state | String | 订单状态  
`1`:借币申请中  
`2`:借币中  
`3`:还币申请中  
`4`:已还币  
`5`:借币失败  
  
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
  
### 获取尊享借币计息记录

#### 限速：5次/2s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/account/vip-interest-accrued`

> 请求示例
    
    
    GET /api/v5/account/vip-interest-accrued
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
ccy | String | 否 | 借贷币种，如 `BTC`，仅适用于`币币杠杆`  
ordId | String | 否 | 借币订单ID  
after | String | 否 | 请求此时间戳之前（更旧的数据）的分页内容，Unix时间戳的毫秒数格式，如 `1597026383085`  
before | String | 否 | 请求此时间戳之后（更新的数据）的分页内容，Unix时间戳的毫秒数格式，如 `1597026383085`  
limit | String | 否 | 分页返回的结果集数量，最大为100，不填默认返回100条  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "ccy": "USDT",
                "interest": "0.0003960833333334",
                "interestRate": "0.0000040833333333",
                "liab": "97",
                "ordId": "16373124000001235",
                "ts": "1637312400000"
            },
            {
                "ccy": "USDT",
                "interest": "0.0004083333333334",
                "interestRate": "0.0000040833333333",
                "liab": "100",
                "ordId": "16370496000001234",
                "ts": "1637049600000"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
ordId | String | 借币订单ID  
ccy | String | 借贷币种，如 `BTC`  
interest | String | 利息  
interestRate | String | 计息利率(小时)  
liab | String | 计息负债  
ts | String | 计息时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
  
### 获取尊享借币扣息记录

#### 限速：5次/2s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/account/vip-interest-deducted`

> 请求示例
    
    
    GET /api/v5/account/vip-interest-deducted
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
ordId | String | 否 | 借币订单ID  
ccy | String | 否 | 借贷币种，如 `BTC`，仅适用于`币币杠杆`  
after | String | 否 | 请求此时间戳之前（更旧的数据）的分页内容，Unix时间戳的毫秒数格式，如 `1597026383085`  
before | String | 否 | 请求此时间戳之后（更新的数据）的分页内容，Unix时间戳的毫秒数格式，如 `1597026383085`  
limit | String | 否 | 分页返回的结果集数量，最大为100，不填默认返回100条  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "ccy": "USDT",
                "interest": "0.0003960833333334",
                "interestRate": "0.0000040833333333",
                "liab": "97",
                "ordId": "16373124000001235",
                "ts": "1637312400000"
            },
            {
                "ccy": "USDT",
                "interest": "0.0004083333333334",
                "interestRate": "0.0000040833333333",
                "liab": "100",
                "ordId": "16370496000001234",
                "ts": "1637049600000"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
ordId | String | 借币订单ID  
ccy | String | 借贷币种，如 `BTC`  
interest | String | 利息  
interestRate | String | 计息利率(小时)  
liab | String | 计息负债  
ts | String | 计息时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
  
### 尊享借币订单列表

#### 限速：5次/2s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/account/vip-loan-order-list`

> 请求示例
    
    
    GET /api/v5/account/vip-loan-order-list
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
ordId | String | 否 | 借币订单ID  
state | String | 否 | 订单状态  
1:借币申请中  
2:借币中  
3:还币申请中  
4:已还币  
5:借币失败  
ccy | String | 否 | 借贷币种，如 BTC  
after | String | 否 | 请求此ID之前（更旧的数据）的分页内容，传的值为对应接口的`ordId`  
before | String | 否 | 请求此ID之后（更新的数据）的分页内容，传的值为对应接口的`ordId`  
limit | String | 否 | 返回结果的数量，最大为100，默认100条  
  
> 返回结果
    
    
    {
        "code": "0",
        "msg": "",
        "data": [
             {
                     "ts": "123456789",
                     "ccy": "BTC",
                     "ordId": "120.0000000000000000",
                     "state": "0",
                     "origRate": "0.00199200",
                     "curRate": "0.00199200",
                     "dueAmt": "120.0000000000000000",
                     "borrowAmt": "120.0000000000000000",
                     "repayAmt": "120.0000000000000000"
             }
       ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
ts | String | 订单创建时间  
ccy | String | 借贷币种，如 BTC  
ordId | String | 订单ID  
state | String | 订单状态  
1:借币申请中  
2:借币中  
3:还币申请中  
4:已还币  
5:业务异常，借币失败  
origRate | String | 订单原始利率  
curRate | String | 借贷币种当前利率  
dueAmt | String | 待还数量  
borrowAmt | String | 借币数量  
repayAmt | String | 还币数量  
  
### 尊享借币订单详情

#### 限速：5次/2s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/account/vip-loan-order-detail`

> 请求示例
    
    
    GET /api/v5/account/vip-loan-order-detail
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
ordId | String | 是 | 借币订单ID  
ccy | String | 否 | 借贷币种，如 BTC  
after | String | 否 | 请求此时间戳之后（更新的数据）的分页内容，Unix时间戳的毫秒数格式，如 `1597026383085`  
before | String | 否 | 请求此时间戳之前（更旧的数据）的分页内容，Unix时间戳的毫秒数格式，如 `1597026383085`  
limit | String | 否 | 返回结果的数量，最大为100，默认100条  
  
> 返回结果
    
    
    {
        "code": "0",
        "msg": "",
        "data": [
             {
                     "ts": "123456789",
                     "type":"1",
                     "ccy": "BTC",
                     "rate": "0.00199200",
                     "amt": "120.0000000000000000"
             }
       ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
ts | String | 操作时间  
ccy | String | 借贷币种，如 BTC  
type | String | 操作类型  
1:借币  
2:还币  
3:系统还币  
4:利率刷新  
rate | String | 订单当前利率  
amt | String | 借还数量  
  
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
                        "avgRate": "0.00199200",
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
> posLoan | String | 当前账户负债占用（锁定额度内）  
仅适用于`尊享借币`  
> availLoan | String | 当前账户剩余可用（锁定额度内）  
仅适用于`尊享借币`  
> usedLoan | String | 当前账户已借额度  
仅适用于`尊享借币`  
> avgRate | String | 币种已借平均利率，仅适用于`尊享借币`  
  
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
       "inclRealPos":true,
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
       "inclRealPos":true
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
spotOffsetType | String | 否 | 现货对冲模式  
1：现货对冲模式U模式 2：现货对冲模式币模式 3：衍生品模式  
默认是 3  
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
            },
            {
                "acctImr": "6847.294720745276",
                "acctMmr": "5140.116514138115"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
riskUnit | String | 账户内所有持仓的riskUnit  
ts | String | 账户信息的更新时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
mmr | String | riskUnit维度的维持保证金  
imr | String | riskUnit维度的最低初始保证金  
mr1 | String | 现货&波动率压力测试值  
mr2 | String | 时间价值压力测试值  
mr3 | String | 波动率跨期压力测试值  
mr4 | String | 基差压力测试值  
mr5 | String | 利率风险压力测试值  
mr6 | String | 极端市场波动压力测试值  
mr7 | String | 减仓成本压力测试值  
acctImr | String | 账户维度的最低初始保证金  
acctMmr | String | 账户维度的维持保证金  
posData | Array | 持仓列表  
> instId | String | 产品ID，如 `BTC-USD-180216`  
> instType | String | 产品类型  
> pos | String | 持仓量  
> notionalUsd | String | 以美金价值为单位的持仓数量  
> delta | String | 期权价格对uly价格的敏感度  
> gamma | String | delta对uly价格的敏感度  
> vega | String | 期权价格对隐含波动率的敏感度  
> theta | String | 期权价格对剩余期限的敏感度  
希腊值单位与账户设置一致，您可通过"config"接口查看。  为确保向前兼容，在 `data` 中新添加了一组 JSON 放置 acctImr 和
acctMmr 参数。

### 查看账户Greeks

获取账户资产的greeks信息。

#### 限速：10次/2s

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
  
### 获取组合保证金模式全仓限制

仅支持获取组合保证金模式下，交割、永续和期权的全仓限制。

#### 限速：10次/2s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/account/position-tiers`

> 请求示例
    
    
    查看BTC-USDT在组合保证金模式下的全仓限制
    GET /api/v5/account/position-tiers?instType=SWAP&uly=BTC-USDT
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instType | String | 是 | 产品类型  
`SWAP`：永续合约  
`FUTURES`：交割合约  
`OPTION`：期权  
  
uly | String | 可选 | 标的指数，如 `BTC-USDT`，支持多个查询（不超过3个），`uly`之间半角逗号分隔  
适用于`交割/永续/期权`  
`uly`与`instFamily`必须传一个,若传两个，以`instFamily`为主  
instFamily | String | 可选 | 交易品种，如 `BTC-
USDT`，支持多个查询（不超过5个），`instFamily`之间半角逗号分隔  
适用于`交割/永续/期权`  
`uly`与`instFamily`必须传一个,若传两个，以`instFamily`为主  
  
> 返回结果
    
    
    {
      "code": "0",
      "data": [
        {
          "instFamily": "BTC-USD",
          "maxSz": "10000",
          "posType": "",
          "uly": "BTC-USDT"
        }
      ],
      "msg": ""
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
uly | String | 标的指数  
适用于`交割/永续/期权`  
instFamily | String | 交易品种  
适用于`交割/永续/期权`  
maxSz | String | 最大持仓量  
posType | String | 限仓类型，仅适用于组合保证金模式下的期权全仓。  
`1`：所有合约挂单 + 持仓张数，`2`：所有合约总挂单张数，`3`：所有合约总挂单单数，`4`：同方向合约挂单 +
持仓张数，`5`：单一合约总挂单单数，`6`：单一合约挂单 + 持仓张数，`7`：单笔挂单张数"  
  
### 设置组合保证金账户风险对冲模式

设置 Portfolio Margin 账户风险对冲模式

#### 限速：10次/2s

#### 限速规则：UserID

#### HTTP请求

`POST /api/v5/account/set-riskOffset-type`

> 请求示例
    
    
    POST /api/v5/account/set-riskOffset-type
    body 
    {
        "type":"1"
    }
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
type | String | 是 | 风险对冲模式  
`1`：现货对冲(USDT)  
`2`:现货对冲(币)  
`3`:衍生品对冲  
  
> 返回结果
    
    
    {
        "code": "0",
        "msg": "",
        "data": [{
            "type":"1"
        }]
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
type | String | 风险对冲模式  
`1`：现货对冲(USDT)  
`2`:现货对冲(币)  
`3`:衍生品对冲  
  
### 开通期权交易

#### 限速：5次/2s

#### 限速规则：UserID

#### HTTP请求

`POST /api/v5/account/activate-option`

#### 请求参数

无

> 返回结果
    
    
    {
        "code": "0",
        "msg": "",
        "data": [{
            "ts": "1600000000000"
        }]
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
ts | String | 开通时间  
  
### 设置自动借币

仅适用于跨币种保证金模式和组合保证金模式

#### 限速：5次/2s

#### 限速规则：UserID

#### HTTP请求

`POST /api/v5/account/set-auto-loan`

> 请求示例
    
    
    POST /api/v5/account/set-auto-loan
    body
    {
        "autoLoan":true,
    }
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
autoLoan | Boolean | 否 | 是否自动借币  
有效值为`true`, `false`  
默认为 `true`  
  
> 返回结果
    
    
    {
        "code": "0",
        "msg": "",
        "data": [{
            "autoLoan": true
        }]
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
autoLoan | Boolean | 是否自动借币  
  
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
gAuth | Boolean | 子账户是否开启的登录时的谷歌验证 `true`：已开启 `false`：未开启  
canTransOut | Boolean | 是否可以主动转出  
`false`：不可转出  
`true`：可以转出  
ts | String | 子账户创建时间，Unix时间戳的毫秒数格式 ，如 `1597026383085`  
  
### 重置子账户的APIKey

仅适用于母账户,且母账户APIKey必须绑定IP

#### 限速：1次/s

#### 限速规则：UserID

#### HTTP请求

`POST /api/v5/users/subaccount/modify-apikey`

> 请求示例
    
    
    POST /api/v5/users/subaccount/modify-apikey
    body
    {
        "subAcct":"yongxu",
        "apiKey":"49e1b84b-6dee-4894-80ee-ce9eb7ad614f",
        "ip":"1.1.1.1"
    }
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
subAcct | String | 是 | 子账户名称  
apiKey | String | 是 | 子账户API的公钥  
label | String | 否 | 子账户APIKey的备注，如果填写该字段，则该字段会被重置  
perm | String | 否 | 子账户APIKey权限 `read_only`：只读 ；`trade` ：交易  
多个权限用半角逗号隔开。  
如果填写该字段，则该字段会被重置  
ip | String | 否 | 子账户APIKey绑定ip地址，多个ip用半角逗号隔开，最多支持20个ip。  
如果填写该字段，那该字段会被重置  
如果ip传""，则表示解除IP绑定  
  
> 返回结果
    
    
    {
        "code": "0",
        "msg": "",
        "data": [{
            "subAcct": "yongxu",
            "label": "v5",
            "apiKey": "arg13sdfgs",
            "perm": "read,trade",
            "ip": "1.1.1.1",
            "ts": "1597026383085"
        }]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
subAcct | String | 子账户名称  
label | String | APIKey的备注  
apiKey | String | API公钥  
perm | String | APIKey权限  
ip | String | APIKey绑定的ip地址  
ts | String | 创建时间  
  
### 获取子账户交易账户余额

获取子账户交易账户余额（适用于母账户）

#### 限速：6次/2s

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

### 获取子账户资金账户余额

获取子账户资金账户余额（适用于母账户）

#### 限速：6次/2s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/asset/subaccount/balances`

> 请求示例
    
    
    GET /api/v5/asset/subaccount/balances?subAcct=test1
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
subAcct | String | 是 | 子账户名称  
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
  
### 查询子账户转账记录

仅适用于母账户，可以获取最近3个月的转账记录

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

调用时，APIKey 需要有交易权限

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
omitPosRisk | String | 否 | 是否忽略仓位风险  
默认为`false`  
仅适用于`组合保证金模式`  
  
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
canTransOut | Boolean | 否 | 是否可以主动转出，默认为`true`  
`false`：不可转出  
`true`：可以转出  
  
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
canTransOut | Boolean | 是否可以主动转出  
`false`：不可转出  
`true`：可以转出  
  
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
  
### 获取用户的节点返佣信息

该接口用于节点查询用户的返佣信息

#### 限速：20次/2s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/users/partner/if-rebate`

> 请求示例
    
    
    GET /api/v5/users/partner/if-rebate?apiKey=86b02e93-67ab-497d-9970-8cce00a028c3
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
apiKey | String | 是 | 用户的 API key  
  
> 返回结果
    
    
    {
        "code": "0",
        "msg": "",
        "data": {
            "result": true,
            "type": "0"
        }
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
result | Boolean | 用户是否与当前节点有邀请关系。 `true`, `false`  
type | String | 是否有节点返佣  
`0` 有节点返佣  
`1` 没有节点返佣，因为调用该接口的账户不是节点身份  
`2` 没有节点返佣，因为不存在邀请/召回关系，如：api key不存在  
`4` 没有节点返佣，因为用户的手续费等级大于等于VIP3  
  
## 网格交易

`网格交易`功能模块下的API接口需要身份验证。

### 网格策略委托下单

#### 限速：20次/2s

#### 限速规则（期权以外）：UserID + Instrument ID

#### 限速规则（只限期权）：UserID + Instrument Family

#### HTTP请求

`POST /api/v5/tradingBot/grid/order-algo`

> 请求示例
    
    
    # 现货网格下单
    POST /api/v5/tradingBot/grid/order-algo
    body
    {
        "instId": "BTC-USDT",
        "algoOrdType": "grid",
        "maxPx": "5000",
        "minPx": "400",
        "gridNum": "10",
        "runType": "1",
        "quoteSz": "25"
    }
    
    # 合约网格下单
    POST /api/v5/tradingBot/grid/order-algo
    body
    {
        "instId": "BTC-USDT-SWAP",
        "algoOrdType": "contract_grid",
        "maxPx": "5000",
        "minPx": "400",
        "gridNum": "10",
        "runType": "1",
        "sz": "200", 
        "direction": "long",
        "lever": "2"
    }
    
    # 合约网格下单
    POST /api/v5/tradingBot/grid/order-algo
    body
    {
      "instId": "BTC-USDT",
      "algoOrdType": "moon_grid",
      "maxPx": "5000",          
      "minPx": "400",
      "gridNum": "10",
      "runType": "2",  
      "quoteSz": "25"             
    }
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instId | String | 是 | 产品ID，如`BTC-USDT`  
algoOrdType | String | 是 | 策略订单类型  
`grid`：现货网格委托  
`contract_grid`：合约网格委托  
`moon_grid`：天地网格委托  
maxPx | String | 是 | 区间最高价格  
minPx | String | 是 | 区间最低价格  
gridNum | String | 是 | 网格数量  
runType | String | 否 | 网格类型  
`1`：等差，`2`：等比  
默认为等差  
`天地网格`只支持`2`  
tpTriggerPx | String | 否 | 止盈触发价  
适用于`现货网格`/`合约网格`  
slTriggerPx | String | 否 | 止损触发价  
适用于`现货网格`/`合约网格`  
tag | String | 否 | 订单标签  
  
现货网格

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
quoteSz | String | 可选 | 计价币投入数量  
`quoteSz`和`baseSz`至少指定一个  
baseSz | String | 可选 | 交易币投入数量  
`quoteSz`和`baseSz`至少指定一个  
  
合约网格

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
sz | String | 是 | 投入保证金,单位为`USDT`  
direction | String | 是 | 合约网格类型  
`long`：做多，`short`：做空，`neutral`：中性  
lever | String | 是 | 杠杆倍数  
basePos | Boolean | 否 | 是否开底仓  
默认为`false`  
中性合约网格忽略该参数  
  
天地网格

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
quoteSz | String | 是 | 计价币投入数量  
您可以通过"网格策略智能回测"接口获取"天地网格"下单参数

> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "algoId": "447053782921515008",
                "sCode": "0",
                "sMsg": ""
            }
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
algoId | String | 策略订单ID  
sCode | String | 事件执行结果的code，0代表成功  
sMsg | String | 事件执行失败时的msg  
  
### 修改网格策略订单

只支持合约网格策略的修改

#### 限速：20次/2s

#### 限速规则（期权以外）：UserID + Instrument ID

#### HTTP请求

`POST /api/v5/tradingBot/grid/amend-order-algo`

> 请求示例
    
    
    POST /api/v5/tradingBot/grid/amend-order-algo
    body
    {
        "algoId":"448965992920907776",
        "instId":"BTC-USDT-SWAP",
        "slTriggerPx":"1200",
        "tpTriggerPx":""
    }
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
algoId | String | 是 | 策略订单ID  
instId | String | 是 | 产品ID，如`BTC-USDT-SWAP`  
slTriggerPx | String | 可选 | 新的止损触发价  
当值为""则代表取消止损触发价  
`slTriggerPx`、`tpTriggerPx`至少要传一个值  
tpTriggerPx | String | 可选 | 新的止盈触发价  
当值为""则代表取消止盈触发价  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "algoId": "447053782921515008",
                "sCode": "0",
                "sMsg": ""
            }
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
algoId | String | 策略订单ID  
sCode | String | 事件执行结果的code，0代表成功  
sMsg | String | 事件执行失败时的msg  
  
### 网格策略停止

每次最多可以撤销10个网格策略。

#### 限速：20次/2s

#### 限速规则（期权以外）：UserID + Instrument ID

#### 限速规则（只限期权）：UserID + Instrument Family

#### HTTP请求

`POST /api/v5/tradingBot/grid/stop-order-algo`

> 请求示例
    
    
    POST /api/v5/tradingBot/grid/stop-order-algo
    body
    [
        {
            "algoId":"198273485",
            "instId":"BTC-USDT",
            "stopType":"1",
            "algoOrdType":"grid"
        }
    ]
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
algoId | String | 是 | 策略订单ID  
instId | String | 是 | 产品ID，如`BTC-USDT`  
algoOrdType | String | 是 | 策略订单类型  
`grid`：现货网格委托  
`contract_grid`：合约网格委托  
`moon_grid`：天地网格委托  
stopType | String | 是 | 网格策略停止类型  
现货网格/天地网格 `1`：卖出交易币，`2`：不卖出交易币  
合约网格 `1`：市价全平  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "algoId": "447053782921515008",
                "sCode": "0",
                "sMsg": ""
            }
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
algoId | String | 策略订单ID  
sCode | String | 事件执行结果的code，0代表成功  
sMsg | String | 事件执行失败时的msg  
  
### 获取未完成网格策略委托单列表

#### 限速：20次/2s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/tradingBot/grid/orders-algo-pending`

> 请求示例
    
    
    GET /api/v5/tradingBot/grid/orders-algo-pending?algoOrdType=grid
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
algoOrdType | String | 是 | 策略订单类型  
`grid`：现货网格委托  
`contract_grid`：合约网格委托  
`moon_grid`：天地网格委托  
algoId | String | 否 | 策略订单ID  
instId | String | 否 | 产品ID，如`BTC-USDT`  
instType | String | 否 | 产品类型  
`SPOT`：币币  
`MARGIN`：杠杆  
`FUTURES`：交割合约  
`SWAP`：永续合约  
after | String | 否 | 请求此ID之前（更旧的数据）的分页内容，传的值为对应接口的`algoId`  
before | String | 否 | 请求此ID之后（更新的数据）的分页内容，传的值为对应接口的`algoId`  
limit | String | 否 | 返回结果的数量，最大为100，默认100条  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "actualLever": "",
                "algoId": "448965992920907776",
                "algoOrdType": "grid",
                "arbitrageNum": "0",
                "basePos": false,
                "baseSz": "0",
                "cTime": "1653313834104",
                "cancelType": "0",
                "direction": "",
                "floatProfit": "-1.3320201165712",
                "gridNum": "6",
                "gridProfit": "0",
                "instId": "BTC-USDC",
                "instType": "SPOT",
                "investment": "100",
                "lever": "",
                "liqPx": "",
                "maxPx": "33444.8",
                "minPx": "24323.5",
                "pnlRatio": "0",
                "quoteSz": "100",
                "runType": "1",
                "slTriggerPx": "",
                "state": "running",
                "stopType": "",
                "sz": "",
                "tag": "",
                "totalPnl": "-1.3320201165712",
                "tpTriggerPx": "",
                "uTime": "1653347949862",
                "uly": ""
            }
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
algoId | String | 策略订单ID  
instType | String | 产品类型  
instId | String | 产品ID  
cTime | String | 策略订单创建时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
uTime | String | 策略订单更新时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
algoOrdType | String | 策略订单类型  
`grid`：现货网格委托  
`contract_grid`：合约网格委托  
`moon_grid`：天地网格委托  
state | String | 订单状态  
`starting`：启动中  
`running`：运行中  
`stopping`：终止中  
`no_close_position`：已停止未平仓（仅适用于合约网格）  
maxPx | String | 区间最高价格  
minPx | String | 区间最低价格  
gridNum | String | 网格数量  
runType | String | 网格类型  
`1`：等差，`2`：等比  
tpTriggerPx | String | 止盈触发价  
slTriggerPx | String | 止损触发价  
arbitrageNum | String | 网格套利次数  
totalPnl | String | 总收益  
pnlRatio | String | 收益率  
investment | String | 投入金额  
现货网格如果投入了交易币则折算为计价币  
gridProfit | String | 网格利润  
floatProfit | String | 浮动盈亏  
cancelType | String | 网格策略停止原因  
`0`：无  
`1`：手动停止  
`2`：止盈停止  
`3`：止损停止  
`4`：风控停止  
`5`：交割停止  
stopType | String | 网格策略停止类型  
现货网格/天地网格 `1`：卖出交易币，`2`：不卖出交易币  
合约网格 `1`：市价全平，`2`：停止不平仓  
quoteSz | String | 计价币投入数量  
适用于`现货网格`/`天地网格`  
baseSz | String | 交易币投入数量  
适用于`现货网格`  
direction | String | 合约网格类型  
`long`：做多，`short`：做空，`neutral`：中性  
仅适用于`合约网格`  
basePos | Boolean | 是否开底仓  
适用于`合约网格`  
sz | String | 投入保证金，单位为`USDT`  
适用于`合约网格`  
lever | String | 杠杆倍数  
适用于`合约网格`  
actualLever | String | 实际杠杆倍数  
适用于`合约网格`  
liqPx | String | 预估强平价格  
适用于`合约网格`  
uly | String | 标的指数  
适用于`合约网格`  
tag | String | 订单标签  
  
### 获取历史网格策略委托单列表

#### 限速：20次/2s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/tradingBot/grid/orders-algo-history`

> 请求示例
    
    
    GET /api/v5/tradingBot/grid/orders-algo-history?algoOrdType=grid
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
algoOrdType | String | 是 | 策略订单类型  
`grid`：现货网格委托  
`contract_grid`：合约网格委托  
`moon_grid`：天地网格委托  
algoId | String | 否 | 策略订单ID  
instId | String | 否 | 产品ID，如`BTC-USDT`  
instType | String | 否 | 产品类型  
`SPOT`：币币  
`MARGIN`：杠杆  
`FUTURES`：交割合约  
`SWAP`：永续合约  
after | String | 否 | 请求此ID之前（更旧的数据）的分页内容，传的值为对应接口的`algoId`  
before | String | 否 | 请求此ID之后（更新的数据）的分页内容，传的值为对应接口的`algoId`  
limit | String | 否 | 返回结果的数量，最大为100，默认100条  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "actualLever": "",
                "algoId": "448965992920907776",
                "algoOrdType": "grid",
                "arbitrageNum": "0",
                "basePos": false,
                "baseSz": "0",
                "cTime": "1653313834104",
                "cancelType": "0",
                "direction": "",
                "floatProfit": "-1.3320201165712",
                "gridNum": "6",
                "gridProfit": "0",
                "instId": "BTC-USDC",
                "instType": "SPOT",
                "investment": "100",
                "lever": "",
                "liqPx": "",
                "maxPx": "33444.8",
                "minPx": "24323.5",
                "pnlRatio": "0",
                "quoteSz": "100",
                "runType": "1",
                "slTriggerPx": "",
                "state": "running",
                "stopResult": "0",
                "stopType": "",
                "sz": "",
                "tag": "",
                "totalPnl": "-1.3320201165712",
                "tpTriggerPx": "",
                "uTime": "1653347949862",
                "uly": ""
            }
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
algoId | String | 策略订单ID  
instType | String | 产品类型  
instId | String | 产品ID  
cTime | String | 策略订单创建时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
uTime | String | 策略订单更新时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
algoOrdType | String | 策略订单类型  
`grid`：现货网格委托  
`contract_grid`：合约网格委托  
`moon_grid`：天地网格委托  
state | String | 订单状态  
`stopped`：已停止  
maxPx | String | 区间最高价格  
minPx | String | 区间最低价格  
gridNum | String | 网格数量  
runType | String | 网格类型  
`1`：等差，`2`：等比  
tpTriggerPx | String | 止盈触发价  
slTriggerPx | String | 止损触发价  
arbitrageNum | String | 网格套利次数  
totalPnl | String | 总收益  
pnlRatio | String | 收益率  
investment | String | 投入金额  
现货网格如果投入了交易币则折算为计价币  
gridProfit | String | 网格利润  
floatProfit | String | 浮动盈亏  
cancelType | String | 网格策略停止原因  
`0`：无  
`1`：手动停止  
`2`：止盈停止  
`3`：止损停止  
`4`：风控停止  
`5`：交割停止  
stopResult | String | 网格策略停止结果  
`0`：默认，`1`：市价卖币成功 `-1`：市价卖币失败  
仅适用于`现货网格`/`天地网格`  
stopType | String | 网格策略停止类型  
现货网格 `1`：卖出交易币，`2`：不卖出交易币  
合约网格 `1`：市价全平，`2`：停止不平仓  
quoteSz | String | 计价币投入数量  
仅适用于`现货网格`/`天地网格`  
baseSz | String | 交易币投入数量  
仅适用于`现货网格`  
direction | String | 合约网格类型  
`long`：做多，`short`：做空，`neutral`：中性  
仅适用于`合约网格`  
basePos | Boolean | 是否开底仓  
仅适用于`合约网格`  
sz | String | 投入保证金，单位为`USDT`  
仅适用于`合约网格`  
lever | String | 杠杆倍数  
仅适用于`合约网格`  
actualLever | String | 实际杠杆倍数  
仅适用于`合约网格`  
liqPx | String | 预估强平价格  
仅适用于`合约网格`  
uly | String | 标的指数  
仅适用于`合约网格`  
tag | String | 订单标签  
  
### 获取网格策略委托订单详情

#### 限速：20次/2s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/tradingBot/grid/orders-algo-details`

> 请求示例
    
    
    GET /api/v5/tradingBot/grid/orders-algo-details?algoId=448965992920907776&algoOrdType=grid
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
algoOrdType | String | 是 | 策略订单类型  
`grid`：现货网格委托  
`contract_grid`：合约网格委托  
`moon_grid`：天地网格委托  
algoId | String | 是 | 策略订单ID  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "actualLever": "",
                "algoId": "448965992920907776",
                "algoOrdType": "grid",
                "annualizedRate": "0",
                "arbitrageNum": "0",
                "basePos": false,
                "baseSz": "0",
                "cTime": "1653313834104",
                "cancelType": "0",
                "curBaseSz": "0.001776289214",
                "curQuoteSz": "46.801755866",
                "direction": "",
                "eq": "",
                "floatProfit": "-1.1021682922796",
                "gridNum": "6",
                "gridProfit": "0",
                "instId": "BTC-USDC",
                "instType": "SPOT",
                "investment": "100",
                "lever": "0",
                "liqPx": "",
                "maxPx": "33444.8",
                "minPx": "24323.5",
                "perMaxProfitRate": "0.060375293181491054543",
                "perMinProfitRate": "0.0455275366818586",
                "pnlRatio": "0",
                "profit": "0",
                "quoteSz": "100",
                "runType": "1",
                "runpx": "30478.1",
                "singleAmt": "0.00059261",
                "slTriggerPx": "",
                "state": "running",
                "stopResult": "0",
                "stopType": "",
                "sz": "",
                "tag": "",
                "totalAnnualizedRate": "-5.679408376687822",
                "totalPnl": "-1.1021682922796",
                "tpTriggerPx": "",
                "tradeNum": "3",
                "uTime": "1653347949862",
                "uly": ""
            }
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
algoId | String | 策略订单ID  
instType | String | 产品类型  
instId | String | 产品ID  
cTime | String | 策略订单创建时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
uTime | String | 策略订单更新时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
algoOrdType | String | 策略订单类型  
`grid`：现货网格委托  
`contract_grid`：合约网格委托  
`moon_grid`：天地网格委托  
state | String | 订单状态  
`starting`：启动中  
`running`：运行中  
`stopping`：终止中  
`no_close_position`：已停止未平仓（仅适用于合约网格）  
`stopped`：已停止  
maxPx | String | 区间最高价格  
minPx | String | 区间最低价格  
gridNum | String | 网格数量  
runType | String | 网格类型  
`1`：等差，`2`：等比  
tpTriggerPx | String | 止盈触发价  
slTriggerPx | String | 止损触发价  
tradeNum | String | 挂单成交次数  
arbitrageNum | String | 网格套利次数  
singleAmt | String | 单网格买卖量  
perMinProfitRate | String | 预期单网格最低利润率  
perMaxProfitRate | String | 预期单网格最高利润率  
runPx | String | 启动时价格  
totalPnl | String | 总收益  
pnlRatio | String | 收益率  
investment | String | 投入金额  
现货网格如果投入了交易币则折算为计价币  
gridProfit | String | 网格利润  
floatProfit | String | 浮动盈亏  
totalAnnualizedRate | String | 总年化  
annualizedRate | String | 网格年化  
cancelType | String | 网格策略停止原因  
`0`：无  
`1`：手动停止  
`2`：止盈停止  
`3`：止损停止  
`4`：风控停止  
`5`：交割停止  
stopType | String | 网格策略停止类型  
现货网格/天地网格 `1`：卖出交易币，`2`：不卖出交易币  
合约网格 `1`：市价全平，`2`：停止不平仓  
quoteSz | String | 计价币投入数量  
仅适用于`现货网格`/`天地网格`  
baseSz | String | 交易币投入数量  
仅适用于`现货网格`  
curQuoteSz | String | 当前持有的计价币资产  
仅适用于`现货网格`/`天地网格`  
curBaseSz | String | 当前持有的交易币资产  
仅适用于`现货网格`/`天地网格`  
profit | String | 当前可提取利润,单位是计价币  
仅适用于`现货网格`/`天地网格`  
stopResult | String | 策略停止结果  
`0`：默认，`1`：市价卖币成功 `-1`：市价卖币失败  
仅适用于`现货网格`/`天地网格`  
direction | String | 合约网格类型  
`long`：做多，`short`：做空，`neutral`：中性  
仅适用于`合约网格`  
basePos | Boolean | 是否开底仓  
仅适用于`合约网格`  
sz | String | 投入保证金，单位为`USDT`  
仅适用于`合约网格`  
lever | String | 杠杆倍数  
仅适用于`合约网格`  
actualLever | String | 实际杠杆倍数  
仅适用于`合约网格`  
liqPx | String | 预估强平价格  
仅适用于`合约网格`  
uly | String | 标的指数  
仅适用于`合约网格`  
eq | String | 策略账户总权益  
仅适用于`合约网格`  
tag | String | 订单标签  
  
### 获取网格策略委托子订单信息

#### 限速：20次/2s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/tradingBot/grid/sub-orders`

> 请求示例
    
    
    GET /api/v5/tradingBot/grid/sub-orders?algoId=123456&type=live&algoOrdType=grid
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
algoId | String | 是 | 策略订单ID  
algoOrdType | String | 是 | 策略订单类型  
`grid`：现货网格委托  
`contract_grid`：合约网格委托  
`moon_grid`：天地网格委托  
type | String | 是 | 子订单状态  
`live`：未成交，`filled`：已成交  
groupId | String | 否 | 组ID  
after | String | 否 | 请求此ID之前（更旧的数据）的分页内容，传的值为对应接口的`ordId`  
before | String | 否 | 请求此ID之后（更新的数据）的分页内容，传的值为对应接口的`ordId`  
limit | String | 否 | 返回结果的数量，最大为100，默认100条  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "accFillSz": "0",
                "algoId": "448965992920907776",
                "algoOrdType": "grid",
                "avgPx": "0",
                "cTime": "1653347949771",
                "ccy": "",
                "ctVal": "",
                "fee": "0",
                "feeCcy": "USDC",
                "groupId": "3",
                "instId": "BTC-USDC",
                "instType": "SPOT",
                "lever": "0",
                "ordId": "449109084439187456",
                "ordType": "limit",
                "pnl": "0",
                "posSide": "net",
                "px": "30404.3",
                "side": "sell",
                "state": "live",    
                "sz": "0.00059213",
                "tag": "",
                "tdMode": "cash",
                "uTime": "1653347949831"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
algoId | String | 策略订单ID  
instType | String | 产品类型  
instId | String | 产品ID  
algoOrdType | String | 策略订单类型  
`grid`：现货网格委托  
`contract_grid`：合约网格委托  
`moon_grid`：天地网格委托  
groupId | String | 组ID  
ordId | String | 子订单ID  
cTime | String | 子订单创建时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
uTime | String | 子订单更新时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
tdMode | String | 子订单交易模式  
`cross`：全仓 `isolated`：逐仓 `cash`：非保证金  
ccy | String | 保证金币种  
仅适用于`单币种保证金`模式下的`全仓杠杆`订单  
ordType | String | 子订单类型  
`market`：市价单 `limit`：限价单  
sz | String | 子订单委托数量  
state | String | 子订单状态  
`canceled`：撤单成功 `live`：等待成交 `partially_filled`：部分成交 `filled`：完全成交
`cancelling`：撤单中  
side | String | 子订单订单方向  
`buy`：买 `sell`：卖  
px | String | 子订单委托价格  
fee | String | 子订单手续费数量  
feeCcy | String | 子订单手续费币种  
avgPx | String | 子订单平均成交价格  
accFillSz | String | 子订单累计成交数量  
posSide | String | 子订单持仓方向  
`long`：双向持仓多头  
`short`：双向持仓空头  
`net`：单向持仓  
pnl | String | 子订单收益  
ctVal | String | 合约面值  
仅支持`FUTURES/SWAP`  
lever | String | 杠杆倍数  
tag | String | 订单标签  
  
### 获取网格策略委托持仓

#### 限速：20次/2s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/tradingBot/grid/positions`

> 请求示例
    
    
    GET /api/v5/tradingBot/grid/positions?algoId=448965992920907776&algoOrdType=contract_grid
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
algoOrdType | String | 是 | 订单类型  
`contract_grid`：合约网格委托  
algoId | String | 是 | 策略订单ID  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "adl": "1",
                "algoId": "449327675342323712",
                "avgPx": "29215.0142857142857149",
                "cTime": "1653400065917",
                "ccy": "USDT",
                "imr": "2045.386",
                "instId": "BTC-USDT-SWAP",
                "instType": "SWAP",
                "last": "29206.7",
                "lever": "5",
                "liqPx": "661.1684795867162",
                "markPx": "29213.9",
                "mgnMode": "cross",
                "mgnRatio": "217.19370606167573",
                "mmr": "40.907720000000005",
                "notionalUsd": "10216.70307",
                "pos": "35",
                "posSide": "net",
                "uTime": "1653400066938",
                "upl": "1.674999999999818",
                "uplRatio": "0.0008190504784478"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
algoId | String | 策略订单ID  
instType | String | 产品类型  
instId | String | 产品ID，如"BTC-USDT-SWAP"  
cTime | String | 策略订单创建时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
uTime | String | 策略订单更新时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
avgPx | String | 开仓均价  
ccy | String | 保证金币种  
lever | String | 杠杆倍数  
liqPx | String | 预估强平价  
posSide | String | 持仓方向  
`net`：单向持仓  
pos | String | 持仓数量  
mgnMode | String | 保证金模式  
`cross`：全仓  
`isolated`：逐仓  
mgnRatio | String | 保证金率  
imr | String | 初始保证金  
mmr | String | 维持保证金  
upl | String | 未实现收益  
uplRatio | String | 未实现收益率  
last | String | 最新成交价  
notionalUsd | String | 仓位美金价值  
adl | String | 信号区  
分为5档，从1到5，数字越小代表adl强度越弱  
markPx | String | 标记价格  
  
### 现货/天地网格提取利润

#### 限速：20次/2s

#### 限速规则：UserID

#### HTTP请求

`POST /api/v5/tradingBot/grid/withdraw-income`

> 请求示例
    
    
    POST /api/v5/tradingBot/grid/withdraw-income
    body
    {
        "algoId":"448965992920907776"
    }
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
algoId | String | 是 | 策略订单ID  
  
> 返回结果
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
            {
                "algoId":"448965992920907776",
                "profit":"100"
            }
        ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
algoId | String | 策略订单ID  
profit | String | 提取的利润  
  
### 调整保证金计算

#### 限速：20次/2s

#### 限速规则：UserID

#### HTTP请求

`POST /api/v5/tradingBot/grid/compute-margin-balance`

> 请求示例
    
    
    POST /api/v5/tradingBot/grid/compute-margin-balance
    body {
       "algoId":"123456",
       "type":"add",
       "amt":"10"
    }
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
algoId | String | 是 | 策略订单ID  
type | String | 是 | 调整保证金类型  
`add`：增加，`reduce`：减少  
amt | String | 否 | 调整保证金数量  
  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "lever": "0.3877200981166066",
                "maxAmt": "1.8309562403342999"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
maxAmt | String | 最多可调整的保证金数量  
lever | String | 调整保证金后的杠杠倍数  
  
### 调整保证金

#### 限速：20次/2s

#### 限速规则：UserID

#### HTTP请求

`POST /api/v5/tradingBot/grid/margin-balance`

> 请求示例
    
    
    POST /api/v5/tradingBot/grid/margin-balance
    body {
       "algoId":"123456",
       "type":"add",
       "amt":"10"
    }
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
algoId | String | 是 | 策略订单ID  
type | String | 是 | 调整保证金类型  
`add`：增加，`reduce`：减少  
amt | String | 可选 | 调整保证金数量  
`amt`和`percent`必须传一个  
percent | String | 可选 | 调整保证金百分比  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "algoId": "123456"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
algoId | String | 策略订单ID  
  
### 网格策略智能回测（公共）

公共接口无须鉴权

#### 限速：20次/2s

#### 限速规则：IP

#### HTTP请求

`GET /api/v5/tradingBot/grid/ai-param`

> 请求示例
    
    
    GET /api/v5/tradingBot/grid/ai-param?instId=BTC-USDT&algoOrdType=grid
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
algoOrdType | String | 是 | 策略订单类型  
`grid`：现货网格委托  
`contract_grid`：合约网格委托  
`moon_grid`：天地网格委托  
instId | String | 是 | 产品ID，如`BTC-USDT`  
direction | String | 可选 | 合约网格类型  
`long`：做多，`short`：做空，`neutral`：中性  
合约网格必填  
duration | String | 否 | 回测周期  
`7D`：7天，`30D`：30天，`180D`：180天  
默认`现货网格`为`7D`，`天地网格`为`180D`  
合约网格只支持`7D`  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "algoOrdType": "grid",
                "annualizedRate": "1.5849",
                "ccy": "USDT",
                "direction": "",
                "duration": "7D",
                "gridNum": "5",
                "instId": "BTC-USDT",
                "lever": "0",
                "maxPx": "21373.3",
                "minInvestment": "0.89557758",
                "minPx": "15544.2",
                "perMaxProfitRate": "0.0733865364573281",
                "perMinProfitRate": "0.0561101403446263",
                "runType": "1"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
instId | String | 产品ID  
algoOrdType | String | 策略订单类型  
`grid`：现货网格委托  
`contract_grid`：合约网格委托  
`moon_grid`：天地网格委托  
duration | String | 回测周期  
`7D`：7天，`30D`：30天，`180D`：180天  
gridNum | String | 网格数量  
maxPx | String | 区间最高价格  
minPx | String | 区间最低价格  
perMaxProfitRate | String | 单网格最高利润率  
perMinProfitRate | String | 单网格最低利润率  
annualizedRate | String | 网格年化收益率  
minInvestment | String | 最小投资数量  
ccy | String | 投资币种  
runType | String | 网格类型  
`1`：等差，`2`：等比  
direction | String | 合约网格类型  
仅适用于`合约网格`  
lever | String | 杠杆倍数  
仅适用于`合约网格`  
  
## 余币宝

### 获取余币宝余额

#### 限速：6次/s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/finance/savings/balance`

> 请求示例
    
    
    GET /api/v5/finance/savings/balance?ccy=BTC
    
    

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

仅资金账户中的资产支持余币宝申购。

#### 限速：6次/s

#### 限速规则：UserID

#### HTTP请求

`POST /api/v5/finance/savings/purchase-redempt`

> 请求示例
    
    
    POST /api/v5/finance/savings/purchase-redempt
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
amt | String | 是 | 申购/赎回 数量  
side | String | 是 | 操作类型  
`purchase`：申购 `redempt`：赎回  
rate | String | 是 | 申购年利率  
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
amt | String | 申购/赎回 数量  
side | String | 操作类型  
rate | String | 申购年利率  
  
### 设置余币宝借贷利率

#### 限速：6次/s

#### 限速规则：UserID

#### HTTP请求

`POST /api/v5/finance/savings/set-lending-rate`

> 请求示例
    
    
    POST /api/v5/finance/savings/set-lending-rate
    body
    {
        "ccy":"BTC",
        "rate":"0.02"
    }
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
ccy | String | 是 | 币种名称，如 `BTC`  
rate | String | 是 | 贷出年利率  
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
rate | String | 贷出年利率  
  
### 获取余币宝出借明细

#### 限速：6次/s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/finance/savings/lending-history`

> 请求示例
    
    
    GET /api/v5/finance/savings/lending-history
    
    

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

#### 限速：6次/s

#### 限速规则：IP

#### HTTP请求

`GET /api/v5/finance/savings/lending-rate-summary`

> 请求示例
    
    
    GET /api/v5/finance/savings/lending-rate-summary
    
    

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

#### 限速：6次/s

#### 限速规则：IP

#### HTTP请求

`GET /api/v5/finance/savings/lending-rate-history`

> 请求示例
    
    
    GET /api/v5/finance/savings/lending-rate-history
    
    

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
  
## 赚币

`赚币`功能模块下的API接口需要身份验证。 仅资金账户中的资产支持赚币。

### 查看项目

#### 限速：3次/s

#### 限速规则：UserID

#### HTTP 请求

`GET /api/v5/finance/staking-defi/offers`

> 请求示例
    
    
    GET /api/v5/finance/staking-defi/offers
    
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
productId | String | 否 | 项目ID  
protocolType | String | 否 | 项目类型  
`staking`：锁仓挖矿 `defi`：DEFI  
ccy | String | 否 | 投资币种，如 `BTC`  
  
> 返回结果
    
    
    {
        "code": "0",
        "msg": "",
        "data": [
           {
                "ccy": "GLMR",  
                "productId":"1234",    
                "protocol": "glimmar",      //锁仓挖矿
                "protocolType":"staking",  
                "term":"15",
                "apy":"0.5496",
                "earlyRedeem":true,
                "investData":[
                  {
                    "ccy":"GLMR",
                    "bal":"100",
                    "minAmt":"1",
                    "maxAmt":"100"
                  }
                ],
                "earningData": [
                 {
                    "ccy": "GLMR",
                    "earningType":"1"         // 每日发放
                 }
                ],
                "state": "purchasable"
            },
            {
                "ccy": "USDT", 
                "productId":"2234",       
                "protocol": "compond",      //DEFI-loan
                "protocolType":"defi", 
                "term":"0",
                "apy":"0.12",
                "earlyRedeem":true,
                "investData":[
                  {
                    "ccy":"USDT",
                    "bal":"20",
                    "minAmt":"1",
                    "maxAmt":"20"
                  }
                ],
                "earningData": [
                 {
                    "ccy": "USDT",
                    "earningType":"0"      // 赎回发放
                 },
                 {
                    "ccy": "COMP",
                    "earningType":"1"      // 每日发放
                 }
                ],
                "state": "purchasable"
            },
            {
                "ccy": "ETH",  
                "productId":"3234",     
                "protocol": "sushiswap",      //DEFI
                "protocolType":"defi",  
                "term":"0",
                "apy":"0.12",
                "earlyRedeem":true,
                "investData":[
                  {
                    "ccy":"USDT",
                    "bal":"20",
                    "minAmt":"100",
                    "maxAmt":"0"
                  },
                  {
                    "ccy":"ETH",
                    "bal":"20",
                    "minAmt":"0.03",
                    "maxAmt":"0"
                  }
                ],
                "earningData": [
                 {
                    "ccy": "SUSHI",
                    "earningType":"1"      // 每日发放
                 }
                ],
                "state": "purchasable"
    
            },
            {
                "ccy": "LON",   
                "productId":"4234",   
                "protocol": "tokenlon",      //DEFI-pos
                "protocolType":"defi",  
                "earningCcy": ["LON"],
                "term":"7",
                "apy":"0.12",
                "earlyRedeem":true,
                "investData":[
                  {
                    "ccy":"LON",
                    "bal":"1",
                    "minAmt":"0.1",
                    "maxAmt":"1"
                  }
                ],
                "earningData": [
                 {
                    "ccy": "LON",
                    "earningType":"0"      // 赎回发放
                 }
                ],
                "state": "purchasable"
            }
        ]
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
ccy | String | 币种名称，如 `BTC`  
productId | String | 项目ID  
protocol | String | 项目名称  
protocolType | String | 项目类型  
`staking`：锁仓挖矿 `defi`：DEFI  
term | String | 项目期限  
活期为0，其他则显示定期天数  
apy | String | 预估年化  
如果年化为7% ，则该字段为0.07  
earlyRedeem | Boolean | 项目是否支持提前赎回  
investData | Array | 目前用户可用来投资的目标币种信息  
> ccy | String | 投资币种，如`BTC`  
> bal | String | 可投数量  
> minAmt | String | 最小申购量  
> maxAmt | String | 最大申购量  
earningData | Array | 收益信息  
> ccy | String | 收益币种，如`BTC`  
> earningType | String | 收益类型  
`0`: 预估收益  
`1`: 累计发放收益  
state | String | 项目状态  
`purchasable`：可申购  
`sold_out`：售罄  
`stop`：暂停申购  
  
### 申购项目

#### 限速：2次/s

#### 限速规则：UserID

#### HTTP 请求

`POST /api/v5/finance/staking-defi/purchase`

> 请求示例
    
    
    // 投资100ZIL30天的锁仓挖矿项目
    POST /api/v5/finance/staking-defi/purchase
    body 
    {
        "productId":"1234",
        "investData":[
          {
            "ccy":"ZIL",
            "amt":"100"
          }
        ],
        "term":"30"
    }
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
productId | String | 是 | 项目ID  
investData | Array | 是 | 投资信息  
> ccy | String | 是 | 投资币种，如 `BTC`  
> amt | String | 是 | 投资数量  
term | String | 可选 | 投资期限  
定期项目必须指定投资期限  
tag | String | 否 | 订单标签  
字母（区分大小写）与数字的组合，可以是纯字母、纯数字，且长度在1-16位之间  
  
> 返回结果
    
    
    {
      "code": "0",
      "msg": "",
      "data": [
        {
          "ordId": "754147",
          "tag": ""
        }
      ]
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
ordId | String | 订单ID  
tag | String | 订单标签  
  
### 赎回项目

#### 限速：2次/s

#### 限速规则：UserID

#### HTTP 请求

`POST /api/v5/finance/staking-defi/redeem`

> 请求示例
    
    
    // 提前赎回项目投资
    POST /api/v5/finance/staking-defi/redeem
    body 
    {
        "ordId":"754147",
        "protocolType":"defi",
        "allowEarlyRedeem":true
    }
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
ordId | String | 是 | 订单ID  
protocolType | String | 是 | 项目类型  
`staking`：锁仓挖矿 `defi`：DEFI  
allowEarlyRedeem | Boolean | 否 | 是否提前赎回  
默认为`false`  
  
> 返回结果
    
    
    {
      "code": "0",
      "msg": "",
      "data": [
        {
          "ordId": "754147",
          "tag": ""
        }
      ]
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
ordId | String | 订单ID  
tag | String | 订单标签  
  
### 撤销项目申购/赎回

撤销申购后的资金返回资金账户。

#### 限速：2次/s

#### 限速规则：UserID

#### HTTP 请求

`POST /api/v5/finance/staking-defi/cancel`

> 请求示例
    
    
    POST /api/v5/finance/staking-defi/cancel
    body 
    {
        "ordId":"754147",
        "protocolType":"defi"
    }
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
ordId | String | 是 | 订单ID  
protocolType | String | 是 | 项目类型  
`staking`：锁仓挖矿 `defi`：DEFI  
  
> 返回结果
    
    
    {
      "code": "0",
      "msg": "",
      "data": [
        {
          "ordId": "754147",
          "tag": ""
        }
      ]
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
ordId | String | 订单ID  
tag | String | 订单标签  
  
### 查看活跃订单

#### 限速：3次/s

#### 限速规则：UserID

#### HTTP 请求

`GET /api/v5/finance/staking-defi/orders-active`

> 请求示例
    
    
    GET /api/v5/finance/staking-defi/orders-active
    
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
productId | String | 否 | 项目ID  
protocolType | String | 否 | 项目类型  
`staking`：锁仓挖矿 `defi`：DEFI  
ccy | String | 否 | 投资币种，如 `BTC`  
state | String | 否 | 订单状态  
`8`: 待上车（预约中）  
`13`: 订单取消中  
`9`: 上链中  
`1`: 收益中  
`2`: 赎回中  
  
> 返回结果
    
    
    {
        "code": "0",
        "msg": "",
        "data": [
           {
                "ordId":"123456",
                "state":"1",
                "ccy": "GLMR",      
                "protocol": "glimmar",      //锁仓挖矿
                "protocolType":"staking",  
                "term":"15",
                "apy":"0.5496",
                "investData":[
                  {
                    "ccy":"GLMR",
                    "amt":"100"
                  }
                ],
                "earningData": [
                 {
                    "ccy": "GLMR",
                    "earningType":"1",         // 每日发放
                    "earnings":"3"
                 }
                ],
                "purchasedTime":"1597026383085",
                "estSettlementTime": "",
                "cancelRedemptionDeadline": "",
                "tag": ""
            },
            {
                "ordId":"123457",
                "state":"1",
                "ccy": "USDT",      
                "protocol": "compond",      //DEFI-loan
                "protocolType":"defi", 
                "term":"0",
                "apy":"0.12",
                "investData":[
                  {
                    "ccy":"USDT",
                    "amt":"20",
                    "minAmt":"1",
                    "maxAmt":""
                  }
                ],
                "earningData": [
                 {
                    "ccy": "USDT",
                    "earningType":"0",      // 赎回发放
                    "earnings":"3"        //预估收益
                 },
                 {
                    "ccy": "COMP",
                    "earningType":"1",      // 每日发放
                    "earnings":"3"        // 累计收益
                 }
                ],
                "purchasedTime":"1597026383085",
                "estSettlementTime": "",
                "cancelRedemptionDeadline": "",
                "tag": ""
            },
            {
                "ordId":"123458",
                "state":"1",
                "ccy": "ETH",      
                "protocol": "sushiswap",      //DEFI
                "protocolType":"defi",  
                "term":"0",
                "apy":"0.12",
                "investData":[
                  {
                    "ccy":"USDT",
                    "amt":"100"
                  },
                  {
                    "ccy":"ETH",
                    "amt":"0.03"
                  }
                ],
                "earningData": [
                 {
                    "ccy": "SUSHI",
                    "earningType":"1",      // 每日发放
                    "earnings":"3"        // 累计收益
                 }
                ],
                "purchasedTime":"1597026383085",
                "estSettlementTime": "",
                "cancelRedemptionDeadline": "",
                "tag": ""
            },
            {
                "ordId":"123458",
                "state":"3",
                "ccy": "LON",      
                "protocol": "tokenlon",      //DEFI-pos
                "protocolType":"defi",  
                "earningCcy": ["LON"],
                "term":"7",
                "apy":"0.12",
                "investData":[
                  {
                    "ccy":"LON",
                    "amt":"1"
                  }
                ],
                "earningData": [
                 {
                    "ccy": "LON",
                    "earningType":"0",      // 赎回发放
                    "earnings":"3"        // 累计收益
                 }
                ],
                "purchasedTime":"1597026383085",
                "estSettlementTime": "",
                "cancelRedemptionDeadline": "",
                "tag": ""
            }
        ]
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
ccy | String | 币种名称，如 `BTC`  
ordId | String | 订单ID  
productId | String | 项目ID  
state | String | 订单状态  
8: 待上车（预约中）  
13: 订单取消中  
9: 上链中  
1: 收益中  
2: 赎回中  
protocol | String | 项目名称  
protocolType | String | 项目类型  
`staking`：锁仓挖矿 `defi`：DEFI  
term | String | 项目期限  
活期为0，其他则显示定期天数  
apy | String | 预估年化  
如果年化为7% ，则该字段为0.07  
保留到小数点后4位（截位）  
investData | Array | 用户投资信息  
> ccy | String | 投资币种，如`BTC`  
> amt | String | 已投资数量  
earningData | Array | 收益信息  
> ccy | String | 收益币种，如`BTC`  
> earningType | String | 收益类型  
`0`: 预估收益  
`1`: 实际到账收益  
> earnings | String | 收益数量  
purchasedTime | String | 用户订单创建时间，值为时间戳，Unix时间戳为毫秒数格式，如 `1597026383085`  
purchasedTime | String | 用户订单创建时间，值为时间戳，Unix时间戳为毫秒数格式，如 `1597026383085`  
estSettlementTime | String | 预估赎回到账时间  
cancelRedemptionDeadline | String | 撤销赎回申请截止时间  
tag | String | 订单标签  
  
### 查看历史订单

#### 限速：3次/s

#### 限速规则：UserID

#### HTTP 请求

`GET /api/v5/finance/staking-defi/orders-history`

> 请求示例
    
    
    GET /api/v5/finance/staking-defi/orders-history
    
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
productId | String | 否 | 项目ID  
protocolType | String | 否 | 项目类型  
`staking`：锁仓挖矿 `defi`：DEFI  
ccy | String | 否 | 投资币种，如 `BTC`  
after | String | 否 | 请求此ID之前（更旧的数据）的分页内容，传的值为对应接口的`ordId`  
before | String | 否 | 请求此ID之后（更新的数据）的分页内容，传的值为对应接口的`ordId`  
limit | String | 否 | 返回结果的数量，默认100条,最大值为100条  
  
> 返回结果
    
    
    {
        "code": "0",
        "msg": "",
        "data": [
           {
                "ordId":"123456",
                "state":"3",
                "ccy": "GLMR",      
                "protocol": "glimmar",      //锁仓挖矿
                "protocolType":"staking",  
                "term":"15",
                "apy":"0.5496",
                "investData":[
                  {
                    "ccy":"GLMR",
                    "amt":"100"
                  }
                ],
                "earningData": [
                 {
                    "ccy": "GLMR",
                    "earningType":"1",         // 每日发放
                    "realizedEarnings":"3"
                 }
                ],
                "purchasedTime":"1597026383085",
                "redeemedTime":"1597126383085",
                "tag": ""
            },
            {
                "ordId":"123457",
                "state":"3",
                "ccy": "USDT",      
                "protocol": "compond",      //DEFI-loan
                "protocolType":"defi", 
                "term":"0",
                "apy":"0.12",
                "investData":[
                  {
                    "ccy":"USDT",
                    "amt":"20"
                  }
                ],
                "earningData": [
                 {
                    "ccy": "USDT",
                    "earningType":"0",      // 赎回发放
                    "realizedEarnings":"3"
                 },
                 {
                    "ccy": "COMP",
                    "earningType":"1",      // 每日发放
                    "realizedEarnings":"3"
                 }
                ],
                "purchasedTime":"1597026383085",
                "redeemedTime":"1597126383085",
                "tag": ""
            },
            {
                "ordId":"123458",
                "state":"3",
                "ccy": "ETH",      
                "protocol": "sushiswap",      //DEFI
                "protocolType":"defi",  
                "term":"0",
                "apy":"0.12",
                "investData":[
                  {
                    "ccy":"USDT",
                    "amt":"100",
                  },
                  {
                    "ccy":"ETH",
                    "amt":"0.03"
                  }
                ],
                "earningData": [
                 {
                    "ccy": "SUSHI",
                    "earningType":"1",      // 每日发放
                    "realizedEarnings":"3"
                 }
                ],
                "purchasedTime":"1597026383085",
                "redeemedTime":"1597126383085",
                "tag": ""
    
            },
            {
                "ordId":"123458",
                "state":"3",
                "ccy": "LON",      
                "protocol": "tokenlon",      //DEFI-pos
                "protocolType":"defi",  
                "earningCcy": ["LON"],
                "term":"7",
                "apy":"0.12",
                "investData":[
                  {
                    "ccy":"LON",
                    "amt":"1"
                  }
                ],
                "earningData": [
                 {
                    "ccy": "LON",
                    "earningType":"0",      // 赎回发放
                    "realizedEarnings":"3"
                 }
                ],
                "purchasedTime":"1597026383085",
                "redeemedTime":"1597126383085",
                "tag": ""
            }
        ]
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
ccy | String | 币种名称，如 `BTC`  
ordId | String | 订单ID  
productId | String | 项目ID  
state | String | 订单状态  
3: 订单已完成（包含撤销和已赎回两种状态）  
protocol | String | 项目名称  
protocolType | String | 项目类型  
`staking`：锁仓挖矿 `defi`：DEFI  
term | String | 项目期限  
活期为0，其他则显示定期天数  
apy | String | 预估年化  
如果年化为7% ，则该字段为0.07  
保留到小数点后4位（截位）  
investData | Array | 用户投资信息  
> ccy | String | 投资币种，如`BTC`  
> amt | String | 已投资数量  
earningData | Array | 收益信息  
> ccy | String | 收益币种，如`BTC`  
> earningType | String | 收益类型  
0: `预估收益`  
1: `实际到账收益`  
> realizedEarnings | String | 已赎回订单累计收益  
该字段只在订单处于赎回状态时有效  
purchasedTime | String | 用户订单创建时间，值为时间戳，Unix时间戳为毫秒数格式，如 `1597026383085`  
redeemedTime | String | 用户订单赎回时间，值为时间戳，Unix时间戳为毫秒数格式，如 `1597026383085`  
tag | String | 订单标签  
  
## 跟单

仅适用于带单交易员

### 交易员获取当前带单

按照开仓时间倒序排列

#### 限速：2次/2s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/copytrading/current-subpositions`

> 请求示例
    
    
    GET /api/v5/copytrading/current-subpositions?instId=BTC-USDT-SWAP
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instId | String | 否 | 产品ID ，如`BTC-USDT-SWAP`  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "algoId": "",
                "instId": "BTC-USDT-SWAP",
                "lever": "3",
                "mgnMode": "isolated",
                "openAvgPx": "17116.3",
                "openOrdId": "518560558975672320",
                "openTime": "1669906471666",
                "posSide": "short",
                "slTriggerPx": "",
                "subPos": "1",
                "subPosId": "518560559046594560",
                "tpTriggerPx": ""
            },
            {
                "algoId": "",
                "instId": "BTC-USDT-SWAP",
                "lever": "3",
                "mgnMode": "isolated",
                "openAvgPx": "17175.1",
                "openOrdId": "518541405921341440",
                "openTime": "1669901905234",
                "posSide": "long",
                "slTriggerPx": "",
                "subPos": "1",
                "subPosId": "518541406042591232",
                "tpTriggerPx": ""
            }
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
instId | String | 产品ID  
subPosId | String | 带单仓位ID  
posSide | String | 持仓方向  
long：双向持仓多头  
short：双向持仓空头  
net：单向持仓（subPos为正代表多头，subPos为负代表空头）  
mgnMode | String | 保证金模式，`isolated`：逐仓 ；`cross`：全仓  
lever | String | 杠杆倍数  
openOrdId | String | 交易员开仓订单号  
openAvgPx | String | 开仓均价  
openTime | String | 开仓时间  
subPos | String | 持仓张数  
tpTriggerPx | String | 止盈触发价，触发后以市价进行委托  
slTriggerPx | String | 止损触发价，触发后以市价进行委托  
algoId | String | 止盈止损委托单ID  
  
### 交易员获取历史带单

可获取最近三个月的已经完结状态的带单数据，按照平仓时间倒序排序。

#### 限速：2次/2s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/copytrading/subpositions-history`

> 请求示例
    
    
    GET /api/v5/copytrading/subpositions-history?instId=BTC-USDT-SWAP
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instId | String | 否 | 产品ID ，如`BTC-USDT-SWAP`  
after | String | 否 | 请求此id之前（更旧的数据）的分页内容，传的值为对应接口的`subPosId`  
before | String | 否 | 请求此id之后（更新的数据）的分页内容，传的值为对应接口的`subPosId`  
limit | String | 否 | 分页返回的结果集数量，最大为100，不填默认返回100条  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "closeAvgPx": "28.63",
                "closeTime": "1669946279797",
                "instId": "KSM-USDT-SWAP",
                "lever": "75",
                "mgnMode": "isolated",
                "openAvgPx": "28.28",
                "openOrdId": "518727217543766016",
                "openTime": "1669946206154",
                "pnl": "-0.035",
                "pnlRatio": "-0.92821782178218",
                "posSide": "short",
                "subPos": "1",
                "subPosId": "518727217715351552"
            },
            {
                "closeAvgPx": "28.22",
                "closeTime": "1669946189065",
                "instId": "KSM-USDT-SWAP",
                "lever": "75",
                "mgnMode": "isolated",
                "openAvgPx": "28.58",
                "openOrdId": "518727140142080008",
                "openTime": "1669946187697",
                "pnl": "-0.036",
                "pnlRatio": "-0.9447165850244925",
                "posSide": "long",
                "subPos": "1",
                "subPosId": "518727140221390848"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
instId | String | 产品ID  
subPosId | String | 带单仓位ID  
posSide | String | 持仓方向  
long：双向持仓多头  
short：双向持仓空头  
net：单向持仓（subPos为正代表多头，subPos为负代表空头）  
mgnMode | String | 保证金模式，`isolated`：逐仓 ；`cross`：全仓  
lever | String | 杠杆倍数  
openOrdId | String | 交易员开仓订单号  
openAvgPx | String | 开仓均价  
openTime | String | 开仓时间  
subPos | String | 持仓张数  
closeTime | String | 平仓时间(最近一次平仓的时间，即完全平仓的时间)  
closeAvgPx | String | 平仓均价  
pnl | String | 收益额  
pnlRatio | String | 收益率  
  
### 交易员止盈止损

#### 限速：1次/2s

#### 限速规则：UserID

#### HTTP请求

`POST /api/v5/copytrading/algo-order`

> 请求示例
    
    
    POST /api/v5/copytrading/algo-order
    body
    {
        "subPosId": "518541406042591232",
        "tpTriggerPx": "10000"
    }
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
subPosId | String | 是 | 带单仓位ID  
tpTriggerPx | String | 可选 | 止盈触发价，触发后以市价进行委托，tpTriggerPx 和 slTriggerPx
至少需要填写一个  
slTriggerPx | String | 可选 | 止损触发价，触发后以市价进行委托  
tpTriggerPxType | String | 否 | 止盈触发价类型  
`last`：最新价格  
`index`：指数价格  
`mark`：标记价格  
默认为last  
slTriggerPxType | String | 否 | 止损触发价类型  
`last`：最新价格  
`index`：指数价格  
`mark`：标记价格  
默认为last  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "subPosId": "518560559046594560"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
subPosId | String | 带单仓位ID  
  
### 交易员平仓

#### 限速：2次/2s

#### 限速规则：UserID

#### HTTP请求

`POST /api/v5/copytrading/close-subposition`

> 请求示例
    
    
    POST /api/v5/copytrading/close-subposition
    body
    {
        "subPosId": "518541406042591232",
    }
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
subPosId | String | 是 | 带单仓位ID  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "subPosId": "518560559046594560"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
subPosId | String | 带单仓位ID  
  
### 交易员获取带单合约

#### 限速：2次/2s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/copytrading/instruments`

> 请求示例
    
    
    GET /api/v5/copytrading/instruments
    
    

#### 请求参数

无

> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "enabled": true,
                "instId": "BTC-USDT-SWAP"
            },
            {
                "enabled": true,
                "instId": "ETH-USDT-SWAP"
            },
            {
                "enabled": false,
                "instId": "ADA-USDT-SWAP"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
instId | String | 产品ID  
enabled | Boolean | 是否设置了跟单 `true` 或 `false`  
  
### 交易员修改带单合约

#### 限速：2次/2s

#### 限速规则：UserID

#### HTTP请求

`POST /api/v5/copytrading/set-instruments`

> 请求示例
    
    
    POST /api/v5/copytrading/set-instruments
    body
    {
        "instId": "BTC-USDT-SWAP,ETH-USDT-SWAP"
    }
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instId | String | 是 | 产品ID，如 BTC-USDT-SWAP，多个产品用半角逗号隔开，最多支持31个产品ID  
如果进行多个合约带单，`instId`传值需要包括所有将要带单的合约，因为当前请求设置成功后，之前的设置会被覆盖掉  

> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "enabled": true,
                "instId": "BTC-USDT-SWAP"
            },
            {
                "enabled": true,
                "instId": "ETH-USDT-SWAP"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
instId | String | 产品id， 如 BTC-USDT-SWAP  
enabled | Boolean | `true` 或 `false`  
`true` 代表全部设置成功  
`false` 代表全部设置失败  
  
### 交易员历史分润明细

可获取所有历史分润明细

#### 限速：2次/2s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/copytrading/profit-sharing-details`

> 请求示例
    
    
    GET /api/v5/copytrading/profit-sharing-details?limit=2
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
after | String | 否 | 请求此id之前（更旧的数据）的分页内容，传的值为对应接口的`profitSharingId`  
before | String | 否 | 请求此id之后（更新的数据）的分页内容，传的值为对应接口的`profitSharingId`  
limit | String | 否 | 分页返回的结果集数量，最大为100，不填默认返回100条  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "ccy": "USDT",
                "nickName": "Potato",
                "profitSharingAmt": "0.00536",
                "profitSharingId": "148",
                "ts": "1669625700000"
            },
            {
                "ccy": "USDT",
                "nickName": "Apple",
                "profitSharingAmt": "0.00336",
                "profitSharingId": "20",
                "ts": "1669366500000"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
ccy | String | 产品ID  
profitSharingAmt | String | 分润额，没有分润时，默认返回0  
nickName | String | 跟单人的昵称  
profitSharingId | String | 分润ID  
ts | String | 分润时间  
  
### 交易员历史分润汇总

#### 限速：2次/2s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/copytrading/total-profit-sharing`

> 请求示例
    
    
    GET /api/v5/copytrading/total-profit-sharing
    
    

#### 请求参数

无

> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "ccy": "USDT",
                "totalProfitSharingAmt": "0.6584928"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
ccy | String | 分润币种  
totalProfitSharingAmt | String | 历史分润汇总  
  
### 交易员待分润明细

当有跟单仓位平仓时，待分润明细会进行更新

#### 限速：2次/2s

#### 限速规则：UserID

#### HTTP请求

`GET /api/v5/copytrading/unrealized-profit-sharing-details`

> 请求示例
    
    
    GET /api/v5/copytrading/unrealized-profit-sharing-details
    
    

#### 请求参数

无

> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "ccy": "USDT",
                "nickName": "Potato",
                "ts": "1669901824779",
                "unrealizedProfitSharingAmt": "0.455472"
            },
            {
                "ccy": "USDT",
                "nickName": "Apple",
                "ts": "1669460210113",
                "unrealizedProfitSharingAmt": "0.033608"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
ccy | String | 分润币种，e.g. `USDT`  
unrealizedProfitSharingAmt | String | 待分润额  
nickName | String | 跟单人昵称  
ts | String | 数据更新时间  
  
## 行情数据

`行情数据`功能模块下的API接口不需要身份验证。

### 获取所有产品行情信息

获取产品行情信息

#### 限速：20次/2s

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
uly | String | 否 | 标的指数  
适用于`交割/永续/期权`，如 `BTC-USD`  
instFamily | String | 否 | 交易品种  
适用于`交割/永续/期权`，如 `BTC-USD`  
  
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

#### 限速：20次/2s

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

#### 限速：20次/2s

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

#### 限速：40次/2s

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
411.8为深度价格，10为此价格的交易币的数量，0该字段已弃用(始终为0)，4为此价格的订单数量 asks和bids值数组举例说明： ["411.8",
"10", "0", "4"]  
\- 411.8为深度价格  
\- 10为此价格的数量 （合约交易为合约，现货/币币杠杆为交易币的数量）  
\- 0该字段已弃用(始终为0)  
\- 4为此价格的订单数量

### 获取产品轻量深度

可以更快地获取前25档的深度信息。

#### 限速：6次/1s

#### 限速规则：IP

#### HTTP请求

`GET /api/v5/market/books-lite`

> 请求示例
    
    
    GET /api/v5/market/books-lite?instId=BTC-USDT
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instId | String | 是 | 产品ID，如 `BTC-USDT`  
  
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
411.8为深度价格，10为此价格的交易币的数量，0该字段已弃用(始终为0)，4为此价格的订单数量 asks和bids值数组举例说明： ["411.8",
"10", "0", "4"]  
\- 411.8为深度价格  
\- 10为此价格的数量 （合约交易为合约，现货/币币杠杆为交易币的数量）  
\- 0该字段已弃用(始终为0)  
\- 4为此价格的订单数量

### 获取交易产品K线数据

获取K线数据。K线数据按请求的粒度分组返回，K线数据每个粒度最多可获取最近1,440条。

#### 限速：40次/2s

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
香港时间开盘价k线：[6H/12H/1D/2D/3D/1W/1M/3M]  
UTC时间开盘价k线：[/6Hutc/12Hutc/1Dutc/2Dutc/3Dutc/1Wutc/1Mutc/3Mutc]  
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
            "22698348.04828491",
            "12698348.04828491",
            "0"
        ],
        [
            "1597026383085",
            "3.731",
            "3.799",
            "3.494",
            "3.72",
            "24912403",
            "67632347.24399722",
            "37632347.24399722",
            "1"
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
vol | String | 交易量，以`张`为单位  
如果是`衍生品`合约，数值为合约的张数。  
如果是`币币/币币杠杆`，数值为交易货币的数量。  
volCcy | String | 交易量，以`币`为单位  
如果是`衍生品`合约，数值为交易货币的数量。  
如果是`币币/币币杠杆`，数值为计价货币的数量。  
volCcyQuote | String | 交易量，以计价货币为单位  
如：BTC-USDT 和 BTC-USDT-SWAP, 单位均是 USDT；  
BTC-USD-SWAP 单位是 USD  
confirm | String | K线状态  
`0` 代表 K 线未完结，`1` 代表 K 线已完结。  
返回的第一条K线数据可能不是完整周期k线，返回值数组顺序分别为是：[ts,o,h,l,c,vol,volCcy,volCcyQuote,confirm]  
对于当前周期的K线数据，没有成交时，开高收低默认都取上一周期的收盘价格。

### 获取交易产品历史K线数据

获取最近几年的历史k线数据

#### 限速：20次/2s

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
香港时间开盘价k线：[6H/12H/1D/2D/3D/1W/1M/3M]  
UTC时间开盘价k线：[6Hutc/12Hutc/1Dutc/2Dutc/3Dutc/1Wutc/1Mutc/3Mutc]  
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
            "22698348.04828491",
            "12698348.04828491",
            "1"
        ],
        [
            "1597026383085",
            "3.731",
            "3.799",
            "3.494",
            "3.72",
            "24912403",
            "67632347.24399722",
            "37632347.24399722",
            "1"
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
vol | String | 交易量，以`张`为单位  
如果是`衍生品`合约，数值为合约的张数。  
如果是`币币/币币杠杆`，数值为交易货币的数量。  
volCcy | String | 交易量，以`币`为单位  
如果是`衍生品`合约，数值为交易货币的数量。  
如果是`币币/币币杠杆`，数值为计价货币的数量。  
volCcyQuote | String | 交易量，以计价货币为单位  
如：BTC-USDT 和 BTC-USDT-SWAP, 单位均是 USDT；  
BTC-USD-SWAP 单位是 USD  
confirm | String | K线状态  
`0` 代表 K 线未完结，`1` 代表 K 线已完结。  
返回值数组顺序分别为是：[ts,o,h,l,c,vol,volCcy,confirm]

### 获取指数K线数据

指数K线数据每个粒度最多可获取最近1,440条。

#### 限速：20次/2s

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
香港时间开盘价k线：[6H/12H/1D/1W/1M/3M]  
UTC时间开盘价k线：[/6Hutc/12Hutc/1Dutc/1Wutc/1Mutc/3Mutc]  
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
            "0"
        ],
        [
            "1597026383085",
            "3.731",
            "3.799",
            "3.494",
            "3.72",
            "1"
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
confirm | String | K线状态  
`0` 代表 K 线未完结，`1` 代表 K 线已完结。  
返回的第一条K线数据可能不是完整周期k线，返回值数组顺序分别为是：[ts,o,h,l,c,confirm]

### 获取指数历史K线数据

获取最近几年的指数K线数据

#### 限速：10次/2s

#### 限速规则：IP

#### HTTP请求

`GET /api/v5/market/history-index-candles`

> 请求示例
    
    
    GET /api/v5/market/history-index-candles?instId=BTC-USD
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instId | String | 是 | 现货指数，如`BTC-USD`  
after | String | 否 | 请求此时间戳之前（更旧的数据）的分页内容，传的值为对应接口的`ts`  
before | String | 否 | 请求此时间戳之后（更新的数据）的分页内容，传的值为对应接口的`ts`  
bar | String | 否 | 时间粒度，默认值`1m`  
如 [1m/3m/5m/15m/30m/1H/2H/4H]  
香港时间开盘价k线：[6H/12H/1D/1W/1M]  
UTC时间开盘价k线：[/6Hutc/12Hutc/1Dutc/1Wutc/1Mutc]  
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
            "1"
        ],
        [
            "1597026383085",
            "3.731",
            "3.799",
            "3.494",
            "3.72",
            "1"
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
confirm | String | K线状态  
`0` 代表 K 线未完结，`1` 代表 K 线已完结。  
返回值数组顺序分别为是：[ts,o,h,l,c,confirm]

### 获取标记价格K线数据

标记价格K线数据每个粒度最多可获取最近1,440条。

#### 限速：20次/2s

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
香港时间开盘价k线：[6H/12H/1D/1W/1M/3M]  
UTC时间开盘价k线：[6Hutc/12Hutc/1Dutc/1Wutc/1Mutc/3Mutc]  
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
            "0"
        ],
        [
            "1597026383085",
            "3.731",
            "3.799",
            "3.494",
            "3.72",
            "1"
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
confirm | String | K线状态  
`0` 代表 K 线未完结，`1` 代表 K 线已完结。  
返回的第一条K线数据可能不是完整周期k线，返回值数组顺序分别为是：[ts,o,h,l,c,confirm]

### 获取标记价格历史K线数据

获取最近几年的标记价格K线数据

#### 限速：10次/2s

#### 限速规则：IP

#### HTTP请求

`GET /api/v5/market/history-mark-price-candles`

> 请求示例
    
    
    GET /api/v5/market/history-mark-price-candles?instId=BTC-USD-SWAP
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instId | String | 是 | 产品ID，如`BTC-USD-SWAP`  
after | String | 否 | 请求此时间戳之前（更旧的数据）的分页内容，传的值为对应接口的`ts`  
before | String | 否 | 请求此时间戳之后（更新的数据）的分页内容，传的值为对应接口的`ts`  
bar | String | 否 | 时间粒度，默认值`1m`  
如 [1m/3m/5m/15m/30m/1H/2H/4H]  
香港时间开盘价k线：[6H/12H/1D/1W/1M]  
UTC时间开盘价k线：[6Hutc/12Hutc/1Dutc/1Wutc/1Mutc]  
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
            "1"
        ],
        [
            "1597026383085",
            "3.731",
            "3.799",
            "3.494",
            "3.72",
            "1"
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
confirm | String | K线状态  
`0` 代表 K 线未完结，`1` 代表 K 线已完结。  
返回值数组顺序分别为是：[ts,o,h,l,c,confirm]

### 获取交易产品公共成交数据

查询市场上的成交信息数据

#### 限速：100次/2s

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
        "code": "0",
        "msg": "",
        "data": [
            {
                "instId": "BTC-USDT",
                "side": "sell",
                "sz": "0.00001",
                "px": "29963.2",
                "tradeId": "242720720",
                "ts": "1654161646974"
            },
            {
                "instId": "BTC-USDT",
                "side": "sell",
                "sz": "0.00001",
                "px": "29964.1",
                "tradeId": "242720719",
                "ts": "1654161641568"
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

### 获取交易产品公共历史成交数据

查询市场上的成交信息数据，可以分页获取最近3个月的数据。

#### 限速：10次/2s

#### 限速规则：IP

#### HTTP请求

`GET /api/v5/market/history-trades`

> 请求示例
    
    
    GET /api/v5/market/history-trades?instId=BTC-USDT
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instId | String | 是 | 产品ID，如 `BTC-USDT`  
type | String | 否 | 分页类型  
`1`：tradeId 分页 `2`：时间戳分页  
默认为`1`：tradeId 分页  
after | String | 否 | 请求此 ID 或 ts 之前的分页内容，传的值为对应接口的 tradeId 或 ts  
before | String | 否 | 请求此ID之后（更新的数据）的分页内容，传的值为对应接口的 tradeId。  
不支持时间戳分页。  
limit | String | 否 | 分页返回的结果集数量，最大为100，不填默认返回100条  
  
> 返回结果
    
    
    {
        "code": "0",
        "msg": "",
        "data": [
            {
                "instId": "BTC-USDT",
                "side": "sell",
                "sz": "0.00001",
                "px": "29963.2",
                "tradeId": "242720720",
                "ts": "1654161646974"
            },
            {
                "instId": "BTC-USDT",
                "side": "sell",
                "sz": "0.00001",
                "px": "29964.1",
                "tradeId": "242720719",
                "ts": "1654161641568"
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
  
### 获取期权品种公共成交数据

查询期权同一个交易品种下的成交信息数据，最多返回100条。

#### 限速：20次/2s

#### 限速规则：IP

#### HTTP请求

`GET /api/v5/market/option/instrument-family-trades`

> 请求示例
    
    
    GET /api/v5/market/option/instrument-family-trades?instFamily=BTC-USD
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instFamily | String | 是 | 交易品种，如 BTC-USD，适用于期权  
  
> 返回结果
    
    
    {
        "code": "0",
        "msg": "",
        "data": [
            {
                "vol24h": "103381",
                "tradeInfo": [
                    {
                        "instId": "BTC-USD-221111-17750-C",
                        "side": "sell",
                        "sz": "1",
                        "px": "0.0075",
                        "tradeId": "20",
                        "ts": "1668090715058"
                    },
                    {
                        "instId": "BTC-USD-221111-17750-C",
                        "side": "sell",
                        "sz": "91",
                        "px": "0.01",
                        "tradeId": "19",
                        "ts": "1668090421062"
                    }
                ],
                "optType": "C"
            },
            {
                "vol24h": "144499",
                "tradeInfo": [
                    {
                        "instId": "BTC-USD-230127-10000-P",
                        "side": "sell",
                        "sz": "82",
                        "px": "0.019",
                        "tradeId": "23",
                        "ts": "1668090967057"
                    },
                    {
                        "instId": "BTC-USD-221111-16250-P",
                        "side": "sell",
                        "sz": "102",
                        "px": "0.0045",
                        "tradeId": "24",
                        "ts": "1668090885050"
                    }
                ],
                "optType": "P"
            }
        ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
vol24h | String | 24小时成交量，以张为单位  
optType | String | 期权类型，`C`：看涨期权 `P`：看跌期权  
tradeInfo | Array | 成交数据列表  
> instId | String | 产品ID  
> tradeId | String | 成交ID  
> px | String | 成交价格  
> sz | String | 成交数量  
> side | String | 成交方向  
`buy`：买  
`sell`：卖  
> ts | String | 成交时间，Unix时间戳的毫秒数格式， 如1597026383085  
  
### 获取平台24小时总成交量

24小时成交量滚动计算，以USD为计价单位，包括大宗交易。

#### 限速：2次/2s

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
             "volCny": "230900886396766",
             "blockVolUsd": "209490",
             "volUsd": "34462818865189",
             "blockVolCny": "1403583",
             "ts": "1657856040389"
         }
      ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
volUsd | String | 24小时平台总成交量，以美元为单位  
volCny | String | 24小时平台总成交量，以人民币为单位  
blockVolUsd | String | 24小时平台场外交易总量，以美元为单位  
blockVolCny | String | 24小时平台场外交易总量，以人民币为单位  
ts | String | 接口返回数据时间  
  
### Oracle 上链交易数据

获取使用 Open Oracle 智能合约签名后加密资产价格。

#### 限速：1次/5s

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
prices | String | 价格  
signatures | String | 每个消息的以太坊兼容ECDSA签名的数组  
timestamp | String | 获取最新数据点的时间,Unix时间戳,如 `1597026387`  
欧易 Oracle公钥是 85615b076615317c80f14cbad6501eec031cd51c

### 获取法币汇率

该接口提供的是2周的平均汇率数据

#### 限速：1次/2s

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

#### 限速：20次/2s

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
  
### 获取大宗交易所有产品行情信息

获取最近24小时大宗交易量

#### 限速：20次/2s

#### 限速规则：IP

#### HTTP请求

`GET /api/v5/market/block-tickers`

> 请求示例
    
    
    GET /api/v5/market/block-tickers?instId=BTC-USD-SWAP
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instType | String | 是 | 产品类型  
`SPOT`：币币  
`SWAP`：永续合约  
`FUTURES`：交割合约  
`OPTION`：期权  
uly | String | 否 | 标的指数  
适用于`交割/永续/期权`，如 `BTC-USD`  
instFamily | String | 否 | 交易品种  
适用于`交割/永续/期权`，如 `BTC-USD`  
  
> 返回结果
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
         {
            "instType":"SWAP",
            "instId":"LTC-USD-SWAP",
            "volCcy24h":"2222",
            "vol24h":"2222",
            "ts":"1597026383085"
         },
         {
            "instType":"SWAP",
            "instId":"BTC-USD-SWAP",
            "volCcy24h":"2222",
            "vol24h":"2222",
            "ts":"1597026383085"
        }
      ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
instId | String | 产品ID  
instType | String | 产品类型  
volCcy24h | String | 24小时成交量，以`币`为单位  
如果是`衍生品`合约，数值为交易货币的数量。  
如果是`币币/币币杠杆`，数值为计价货币的数量。  
vol24h | String | 24小时成交量，以`张`为单位  
如果是`衍生品`合约，数值为合约的张数。  
如果是`币币/币币杠杆`，数值为交易货币的数量。  
ts | String | 数据产生时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
  
### 获取大宗交易单个产品行情信息

获取最近24小时大宗交易量

#### 限速：20次/2s

#### 限速规则：IP

#### HTTP请求

`GET /api/v5/market/block-ticker`

> 请求示例
    
    
    GET /api/v5/market/block-ticker?instId=BTC-USD-SWAP
    
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instId | String | 是 | 产品ID，如 `BTC-USD-SWAP`  
  
> 返回结果
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
         {
            "instType":"SWAP",
            "instId":"LTC-USD-SWAP",
            "volCcy24h":"2222",
            "vol24h":"2222",
            "ts":"1597026383085"
         }
      ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
instId | String | 产品ID  
instType | String | 产品类型  
volCcy24h | String | 24小时成交量，以`币`为单位  
如果是`衍生品`合约，数值为交易货币的数量。  
如果是`币币/币币杠杆`，数值为计价货币的数量。  
vol24h | String | 24小时成交量，以`张`为单位  
如果是`衍生品`合约，数值为合约的张数。  
如果是`币币/币币杠杆`，数值为交易货币的数量。  
ts | String | 数据产生时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
  
### 获取大宗交易公共成交数据

查询市场上的成交信息数据，根据 tradeId 倒序排序。

#### 限速：20次/2s

#### 限速规则：IP

#### HTTP请求

`GET /api/v5/market/block-trades`

> 请求示例
    
    
    GET /api/v5/market/block-trades?instId=BTC-USDT
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instId | String | 是 | 产品ID，如 `BTC-USDT`  
  
> 返回结果
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
            {
                "instId":"BTC-USDT-SWAP",
                "tradeId":"90167",
                "px":"42000",
                "sz":"100",
                "side":"sell",
                "ts":"1642670926504"
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

## 公共数据

`公共数据`功能模块下的API接口不需要身份验证。

### 获取交易产品基础信息

获取所有可交易产品的信息列表。

#### 限速：20次/2s

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
instFamily | String | 否 | 交易品种，仅适用于`交割/永续/期权`  
instId | String | 否 | 产品ID  
  
> 返回结果
    
    
    {
        "code":"0",
        "msg":"",
        "data":[
            {
                "alias": "",
                "baseCcy": "OKB",
                "category": "1",
                "ctMult": "",
                "ctType": "",
                "ctVal": "",
                "ctValCcy": "",
                "expTime": "",
                "instFamily": "",
                "instId": "OKB-USDT",
                "instType": "SPOT",
                "lever": "10",
                "listTime": "1606468571000",
                "lotSz": "0.000001",
                "maxIcebergSz": "999999999999",
                "maxLmtSz": "999999999999",
                "maxMktSz": "",
                "maxStopSz": "",
                "maxTriggerSz": "999999999999",
                "maxTwapSz": "999999999999",
                "minSz": "0.01",
                "optType": "",
                "quoteCcy": "USDT",
                "settleCcy": "",
                "state": "live",
                "stk": "",
                "tickSz": "0.001",
                "uly": ""
            }
      ]
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
instType | String | 产品类型  
instId | String | 产品id， 如 `BTC-USD-SWAP`  
uly | String | 标的指数，如 `BTC-USD`，仅适用于`交割/永续/期权`  
instFamily | String | 交易品种，如 `BTC-USD`，仅适用于`交割/永续/期权`  
category | String | 币种类别，注意：此参数已废弃  
baseCcy | String | 交易货币币种，如 `BTC-USDT` 中的 `BTC` ，仅适用于`币币/币币杠杆`  
quoteCcy | String | 计价货币币种，如 `BTC-USDT` 中的`USDT` ，仅适用于`币币/币币杠杆`  
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
对于期权来说，是梯度中的最小下单价格精度，如果想要获取期权价格梯度，请使用"获取期权价格梯度"接口  
lotSz | String | 下单数量精度，如 BTC-USDT-SWAP：`1`  
minSz | String | 最小下单数量,  
合约的数量单位是`“张”`，现货的数量单位是`“交易货币”`  
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
`test`：测试中（测试产品，不可交易）  
maxLmtSz | String | 合约或现货限价单的单笔最大委托数量,  
合约的数量单位是`“张”`，现货的数量单位是`“交易货币”`  
maxMktSz | String | 合约或现货市价单的单笔最大委托数量,  
合约的数量单位是`“张”`，现货的数量单位是`“USDT”`  
maxTwapSz | String | 合约或现货时间加权单的单笔最大委托数量,  
合约的数量单位是`“张”`，现货的数量单位是`“交易货币”`  
maxIcebergSz | String | 合约或现货冰山委托的单笔最大委托数量,  
合约的数量单位是`“张”`，现货的数量单位是`“交易货币”`  
maxTriggerSz | String | 合约或现货计划委托委托的单笔最大委托数量,  
合约的数量单位是`“张”`，现货的数量单位是`“交易货币”`  
maxStopSz | String | 合约或现货止盈止损市价委托的单笔最大委托数量,  
合约的数量单位是`“张”`，现货的数量单位是`“USDT”`  
当合约预上线时，状态变更为预上线（即新生成一个合约，新合约会处于预上线状态）；
当产品下线的时候（如交割合约被交割的时候，期权合约被行权的时候），查询不到该产品

### 获取交割和行权记录

获取3个月内的交割合约的交割记录和期权的行权记录

#### 限速：40次/2s

#### 限速规则：IP + (instrumentType + uly)

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
uly | String | 可选 | 标的指数  
`uly`与`instFamily`必须传一个,若传两个，以`instFamily`为主  
instFamily | String | 可选 | 交易品种  
`uly`与`instFamily`必须传一个,若传两个，以`instFamily`为主  
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

#### 限速：20次/2s

#### 限速规则：IP + instrumentID

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
uly | String | 可选 | 标的指数  
适用于`交割/永续/期权`  
`期权`情况下，`uly`和`instFamily`必须传一个  
instFamily | String | 可选 | 交易品种  
适用于`交割/永续/期权`  
`期权`情况下，`uly`和`instFamily`必须传一个  
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

#### 限速：20次/2s

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

#### 限速：10次/2s

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
fundingRate | String | 预计资金费率  
realizedRate | String | 实际资金费率  
fundingTime | String | 资金费时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
  
### 获取限价

查询单个交易产品的最高买价和最低卖价

#### 限速：20次/2s

#### 限速规则：IP

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
            "buyLmt":"17057.9",
            "sellLmt":"16388.9",
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

#### 限速：20次/2s

#### 限速规则：IP +uly

#### HTTP请求

`GET /api/v5/public/opt-summary`

> 请求示例
    
    
    GET /api/v5/public/opt-summary?uly=BTC-USD
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
uly | String | 可选 | 标的指数，仅适用于期权  
`uly`与`instFamily`必须传一个,若传两个，以`instFamily`为主  
instFamily | String | 可选 | 交易品种，仅适用于期权  
`uly`与`instFamily`必须传一个,若传两个，以`instFamily`为主  
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

#### 限速：10次/2s

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

#### 限速：2 次/2s

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
> maxAmt | String | 梯度区间上限（美元）， “”表示正无穷  
> minAmt | String | 梯度区间下限（美元）， 最小值是0  
  
### 获取系统时间

获取系统时间

#### 限速：10次/2s

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

最近1天的爆仓单信息。

#### 限速：40次/2s

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
`交割/永续/期权`情况下，`uly`与`instFamily`必须传一个，若传两个，以`instFamily`为主  
instFamily | String | 可选 | 交易品种  
`交割/永续/期权`情况下，`uly`与`instFamily`必须传一个，若传两个，以`instFamily`为主  
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

#### 限速：10次/2s

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
适用于`交割/永续/期权`  
instFamily | String | 否 | 交易品种  
适用于`交割/永续/期权`  
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

#### 限速：10次/2s

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
uly | String | 可选 | 标的指数，支持多uly，半角逗号分隔，最大不超过3个  
当产品类型是`永续`、`交割`、`期权` 之一时，`uly`与`instFamily`必须传一个，若传两个，以`instFamily`为主  
当产品类型是 `MARGIN` 时忽略  
instFamily | String | 可选 | 交易品种，支持多instFamily，半角逗号分隔，最大不超过5个  
当产品类型是`永续`、`交割`、`期权` 之一时，`uly`与`instFamily`必须传一个，若传两个，以`instFamily`为主  
instId | String | 可选 | 产品ID，支持多instId，半角逗号分隔，最大不超过5个  
仅适用`币币杠杆`，`instId`和`ccy`必须传一个，若传两个，以`instId`为主  
ccy | String | 可选 | 保证金币种  
仅适用杠杆全仓，该值生效时，返回的是`跨币种保证金模式`和`组合保证金模式`下的借币量  
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
                "instFamily": "",
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
适用于`交割/永续/期权`  
instFamily | String | 交易品种  
适用于`交割/永续/期权`  
instId | String | 币对  
tier | String | 仓位档位  
minSz | String | 该档位最少借币量或者持仓数量 杠杆/期权/永续/交割 最小持仓量 默认0  
当 `ccy` 参数生效时，返回 `ccy` 的最小借币量  
maxSz | String | 该档位最多借币量或者持仓数量 杠杆/期权/永续/交割  
当 `ccy` 参数生效时，返回 `ccy` 的最大借币量  
mmr | String | 维持保证金率  
imr | String | 最低初始保证金率  
maxLever | String | 最高可用杠杆倍数  
optMgnFactor | String | 期权保证金系数 （仅适用于期权）  
quoteMaxLoan | String | 计价货币 最大借币量（仅适用于杠杆，且`instId`参数生效时），例如 BTC-USDT 里的
USDT最大借币量  
baseMaxLoan | String | 交易货币 最大借币量（仅适用于杠杆，且`instId`参数生效时），例如 BTC-USDT 里的
BTC最大借币量  
  
### 获取市场借币杠杆利率和借币限额

#### 限速：2次/2s

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

#### 限速：20次/2s

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

#### 限速：10次/2s

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
uly | String | 可选 | 标的指数  
`交割/永续/期权`情况下，`uly`与`instFamily`必须传一个，若传两个，以`instFamily`为主  
instFamily | String | 可选 | 交易品种  
`交割/永续/期权`情况下，`uly`与`instFamily`必须传一个，若传两个，以`instFamily`为主  
ccy | String | 可选 | 币种， 仅适用`币币杠杆`，且必填写  
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
                "instFamily": "BTC-USD",
                "total": "883110357.6581"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
total | String | 平台风险准备金总计，单位为USD  
instFamily | String | 交易品种  
适用于`交割/永续/期权`  
details | Array of objects | 风险准备金详情  
> balance | String | 风险准备金总量  
> amt | String | 风险准备金更新数量  
> ccy | String | 风险准备金总量对应的币种  
> type | String | 风险准备金类型  
> ts | String | 风险准备金更新时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
  
### 张币转换

由币转换为张，或者张转换为币。

#### 限速：10次/2s

#### 限速规则：IP

#### HTTP请求

`GET /api/v5/public/convert-contract-coin`

> 请求示例
    
    
    GET /api/v5/public/convert-contract-coin?instId=BTC-USD-SWAP&px=35000&sz=0.888
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
type | String | 否 | 转换类型  
`1`: 币转张，当张为小数时，会进一取整  
`2`: 张转币  
默认为 1  
instId | String | 是 | 产品ID，仅适用于`交割/永续/期权`  
sz | String | 是 | 数量，币转张时，为币的数量，张转币时，为张的数量。  
张的数量，只能是正整数  
px | String | 可选 | 委托价格  
币本位合约的张币转换时必填；  
U本位合约，usdt 与张的转换时，必填；coin 与张的转换时，可不填；  
期权的张币转换时，可不填。  
unit | String | 否 | 币的单位，coin: 币，usds: usdt 或者 usdc  
仅适用于交割和永续合约的U本位合约  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "instId": "BTC-USD-SWAP",
                "px": "35000",
                "sz": "311",
                "type": "1",
                "unit": "coin"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
type | String | 转换类型  
1: 币转张，当张小数时，会进一取整  
2: 张转币  
instId | String | 产品ID  
px | String | 委托价格  
sz | String | 数量，张转币时，为币的数量，币转张时，为张的数量  
unit | String | 币的单位，coin: 币，usds: usdt 或者 usdc  
  
### 获取期权公共成交数据

最多返回最近的100条成交数据

#### 限速：20次/2s

#### 限速规则：IP

#### HTTP请求

`GET /api/v5/public/option-trades`

> 请求示例
    
    
    GET /api/v5/public/option-trades?instFamily=BTC-USDT
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instId | String | 可选 | 产品ID，如 BTC-USD-221230-4000-C，`instId` 和 `instFamily`
必须传一个，若传两个，以 `instId` 为主  
instFamily | String | 可选 | 交易品种，如 BTC-USD  
optType | String | 否 | 期权类型，`C`：看涨期权 `P`：看跌期权  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "fillVol": "0.24415013671875",
                "fwdPx": "16676.907614127158",
                "indexPx": "16667",
                "instFamily": "BTC-USD",
                "instId": "BTC-USD-221230-16600-P",
                "markPx": "0.006308943261227884",
                "optType": "P",
                "px": "0.005",
                "side": "sell",
                "sz": "30",
                "tradeId": "65",
                "ts": "1672225112048"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
instId | String | 产品ID  
instFamily | String | 交易品种  
tradeId | String | 成交ID  
px | String | 成交价格  
sz | String | 成交数量  
side | String | 成交方向  
`buy`：买  
`sell`：卖  
optType | String | 期权类型，C：看涨期权 P：看跌期权 ，仅适用于期权  
fillVol | String | 成交时的隐含波动率（对应成交价格）  
fwdPx | String | 成交时的远期价格  
indexPx | String | 成交时的指数价格  
markPx | String | 成交时的标记价格  
ts | String | 成交时间，Unix时间戳的毫秒数格式， 如`1597026383085`  
  
### 获取期权价格梯度

获取期权价格梯度信息

#### 限速：5次/2s

#### 限速规则：IP

#### HTTP请求

`GET /api/v5/public/instrument-tick-bands`

> 请求示例
    
    
    GET /api/v5/public/instrument-tick-bands?instType=OPTION
    

#### 请求参数

参数名 | 类型 | 是否必须 | 描述  
---|---|---|---  
instType | String | Yes | 产品类型  
`OPTION`：期权  
instFamily | String | No | 交易品种，仅适用于期权  
  
> 返回结果
    
    
    {
        "code": "0",
        "msg": "",
        "data": [
            {
                "instType": "OPTION",
                "instFamily": "BTC-USD",
                "tickBand": [
                    {
                        "minPx": "0",
                        "maxPx": "100",
                        "tickSz": "0.1"
                    },
                    {
                        "minPx": "100",
                        "maxPx": "10000",
                        "tickSz": "1"
                    }
                ]
            },
            {
                "instType": "OPTION",
                "instFamily": "ETH-USD",
                "tickBand": [
                    {
                        "minPx": "0",
                        "maxPx": "100",
                        "tickSz": "0.1"
                    },
                    {
                        "minPx": "100",
                        "maxPx": "10000",
                        "tickSz": "1"
                    }
                ]
            }
        ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
instType | String | 产品类型  
instFamily | String | 交易品种  
tickBand | String | 下单价格精度梯度  
> minPx | String | 最低下单价格  
> maxPx | String | 最高下单价格  
> tickSz | String | 下单价格精度，如 0.0001  
  
## 交易大数据

`交易大数据`功能模块下的API接口不需要身份验证。

### 获取交易大数据支持币种

获取支持交易大数据的币种

#### 限速：5次/2s

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
contract | Array of strings | 合约交易大数据接口功能支持的币种  
option | Array of strings | 期权交易大数据接口功能支持的币种  
spot | Array of strings | 现货交易大数据接口功能支持的币种  
  
### 获取主动买入/卖出情况

获取taker主动买入和卖出的交易量

#### 限速：5次/2s

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

#### 限速：5次/2s

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

#### 限速：5次/2s

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

#### 限速：5次/2s

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

#### 限速：5次/2s

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

#### 限速：5次/2s

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

#### 限速：5次/2s

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
expTime | String | 到期日（格式: YYYYMMDD，例如："20210623"）  
callOI | String | 看涨持仓总量（以`币`为单位）  
putOI | String | 看跌持仓总量（以`币`为单位）  
callVol | String | 看涨交易总量（以`币`为单位）  
putVol | String | 看跌交易总量（以`币`为单位）  
返回值数组顺序分别为是：[ts,expTime,callOI,putOI,callVol,putVol]

### 看涨看跌持仓总量及交易总量（按执行价格分）

获取看涨期权和看跌期权的taker主动买入和卖出的交易量。

#### 限速：5次/2s

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
callVol | String | 看涨交易总量（以`币`为单位）  
putVol | String | 看跌交易总量（以`币`为单位）  
返回值数组顺序分别为是：[ts,strike,callOI,putOI,callVol,putVol]

### 看跌/看涨期权合约 主动买入/卖出量

该指标展示某一时刻，单位时间内看跌/看涨期权的主动（taker）买入/卖出量所占总体的比例，即资金流入量和流出量的比例

#### 限速：5次/2s

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
state | String | No | 系统的状态，`scheduled`:等待中 ; `ongoing`:进行中 ;
`pre_open`:预开放；`completed`:已完成 `canceled`: 已取消  
当维护时间过长，会存在预开放时间，一般持续10分钟左右。  
不填写此参数，默认返回 等待中、进行中和预开放 的数据  
  
> 返回结果
    
    
    {
        "code": "0",
        "data": [
            {
                "begin": "1672823400000",
                "end": "1672823520000",
                "href": "",
                "preOpenBegin": "",
                "scheDesc": "",
                "serviceType": "8",
                "state": "completed",
                "system": "unified",
                "title": "Trading account system upgrade (in batches of accounts)"
            }
        ],
        "msg": ""
    }
    

#### 返回参数

参数名 | 类型 | 描述  
---|---|---  
title | String | 系统维护说明的标题  
state | String | 系统维护的状态  
begin | String | 系统维护的开始时间,Unix时间戳的毫秒数格式 如：`1617788463867`  
end | String | 交易全面开放的时间，Unix时间戳的毫秒数格式 如：`1617788463867`  
在维护完成前，是预期结束时间；维护完成后，会变更为实际结束时间。  
preOpenBegin | String | 预开放开始的时间，开放撤单、Post Only 下单和资金转入功能的时间  
href | String | 系统维护详情的超级链接,若无返回值，默认值为空，如： “”  
serviceType | String | 服务类型， `0`：WebSocket ;
`5`：交易服务；`6`：大宗交易；`7`：策略交易；`8`：交易服务 (按账户分批次)；`9`：交易服务
(按产品分批次)；`99`：其他（如：停止部分产品交易）  
system | String | 系统，`unified`：交易账户  
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
           "passphrase" :"123456",
           "timestamp" :"1538054050",
           "sign" :"7L+zFQ+CEgGu5rzCj4+BdV2/uUHGqddA9pI6ztsRRPs=" 
          },
          {
           "apiKey"    : "86126n98-57ce-40fb-b714-afc0b9787083",
           "passphrase" :"123456",
           "timestamp" :"1538054050",
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
同一个连接，可以分多次登录不同的账户，且新登录的账户默认已经订阅当前连接的频道。

**api_key** :调用API的唯一标识。需要用户手动设置一个 **passphrase** :APIKey的密码 **timestamp**
:Unix Epoch 时间戳，单位为秒 **sign** :签名字符串，签名算法如下：

先将`timestamp` 、 `method` 、`requestPath` 进行字符串拼接，再使用HMAC
SHA256方法将拼接后的字符串和SecretKey加密，然后进行Base64编码

**SecretKey:** 用户申请APIKey时所生成的安全密钥，如：22582BD0CFF14C41EDBF1AB98506286D

**其中 timestamp 示例** :const timestamp = '' \+ Date.now() / 1,000

**其中 sign 示例** :
sign=CryptoJS.enc.Base64.stringify(CryptoJS.HmacSHA256(timestamp +'GET'\+
'/users/self/verify', secret))

**method** 总是 'GET'

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

用户可以选择订阅一个或者多个频道，多个频道总长度不能超过4,096个字节。

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
  
## 交易

`WebSocket交易`需要身份验证。

### 下单

只有当您的账户有足够的资金才能下单。一旦下单，您的账户资金将在订单生命周期内被冻结。被冻结的资金以及数量取决于订单指定的类型和参数  
该频道支持带单合约的下单，但不支持为带单合约平仓

#### 限速：60次/2s

#### 跟单交易带单合约的限速：1次/2s

#### 限速规则（期权以外）：UserID + Instrument ID

#### 限速规则（只限期权）：UserID + Instrument Family

同`下单` REST API 共享限速

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
> sz | String | 是 | 委托数量  
> px | String | 否 | 委托价，仅适用于`limit`、`post_only`、`fok`、`ioc`类型的订单  
> reduceOnly | Boolean | 否 | 是否只减仓，`true` 或 `false`，默认`false`  
仅适用于`币币杠杆`，以及买卖模式下的`交割/永续`  
仅适用于`单币种保证金模式`和`跨币种保证金模式`  
> tgtCcy | String | 否 | 币币市价单委托数量`sz`的单位  
`base_ccy`: 交易货币 ；`quote_ccy`：计价货币  
仅适用于`币币`市价订单  
默认买单为`quote_ccy`，卖单为`base_ccy`  
> banAmend | Boolean | 否 | 是否禁止币币市价改单，true 或 false，默认false  
为true时，余额不足时，系统不会改单，下单会失败，仅适用于币币市价单  
> quickMgnType | String | 否 | 一键借币类型，仅适用于杠杆逐仓的一键借币模式：  
`manual`：手动，`auto_borrow`： 自动借币，`auto_repay`： 自动还币  
默认是`manual`：手动  
expTime | String | 否 | 请求有效截止时间。Unix时间戳的毫秒数格式，如 `1597026383085`  
  
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
clOrdId是用户自定义的唯一ID用来识别订单。如果在请求参数中传入了，那它一定会在返回参数内，并且可以用于查询订单，撤销订单，修改订单等接口。
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
对于同一产品，所有反方向挂单的张数加上当前只减仓下单张数，不能超过持仓张数  
仅适用于`单币种账户模式`和`跨币种账户模式`  
仅适用于`币币杠杆`，以及买卖模式下的`交割/永续`  tgtCcy  
市价单委托数量`sz`的单位：仅适用于币币市价下单交易。  
交易货币：base_ccy  
计价货币：quote_ccy  
您在使用交易货币买入或者计价货币卖出时，请知晓：  
1.如果您输入的数量大于当前可买或者可卖的数量，系统将按照您的最大可买或者可卖数量帮您完成交易，如果您希望按照指定数量成交，那您可以尝试使用限价单，等待市场价格波动到锁定的余额可以买入或卖出您指定的数量。  
2.如果您输入的数量不大于当前可买或者可卖的数量，那当市场价格波动过大时，锁定的余额可能没办法买入您输入的交易货币数量或卖出您输入的计价货币数量，为保证您的交易体验，我们基于【能买多少买多少】或者【能卖多少卖多少】的原则，更改下单的数量帮您完成交易。此外，我们将尽量多锁定一点余额来规避更改下单数量的情况。  
2.1 交易币买入例子：  
以市价下单 买入 10个LTC为例，用户可买为11个，此时 10 < 11，挂单成功。当LTC-USDT的市价为200，用户被锁定余额为3,000
USDT，200*10 < 3,000，最终成交10个LTC； 若市场波动过大，LTC-USDT的市价为400，此时400*10 >
3,000，当用户被锁定的余额不够买入下单指定的交易货币数量时，系統使用用户被锁定的最大余额3,000 USDT下单买入，最终成交 3,000/400 =
7.5个 LTC。  
2.2 计价币卖出例子：  
以市价下单 卖出 1,000USDT为例，用户可卖为1,200USDT，1,000 < 1,200，挂单成功。LTC-
USDT的市价为200，用户被锁定的余额为6个LTC，最终成交5个LTC； 若市场波动过大，LTC-USDT的市价为100，100*6 <
1,000，当用户被锁定的余额不够卖出下单指定的计价货币数量时，系統使用用户被锁定的最大余额6个LTC下单，最终成交 6 * 100 = 600 USDT。
px  
期权下单时，委托价格需为 tickSz 的整数倍。  
当不为整数倍时，取值规则以tickSz取 0.0005 为例：  
当委托价格对0.0005的余数大于0.00025或者委托价格小于0.0005时，向上取；  
当委托价格对0.0005的余数小于等于0.00025，且委托价格大于0.0005时，向下取。

### 批量下单

批量进行下单操作，每次可批量交易不同类型的产品，最多可下单20个  
该频道支持带单合约的下单，但不支持为带单合约平仓。

#### 限速：300个/2s

#### 跟单交易带单合约的限速：1个/2s

#### 限速规则（期权以外）：UserID + Instrument ID

#### 限速规则（只限期权）：UserID + Instrument Family

与其他限速按接口调用次数不同，该接口限速按订单的总个数限速。如果单次批量请求中只有一个元素，则算在单个`下单`限速中。  同`批量下单` REST API
共享限速

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
> sz | String | 是 | 委托数量  
> px | String | 否 | 委托价，仅适用于`limit`、`post_only`、`fok`、`ioc`类型的订单  
> reduceOnly | Boolean | 否 | 是否只减仓，`true` 或 `false`，默认`false`  
仅适用于`币币杠杆`，以及买卖模式下的`交割/永续`  
仅适用于`单币种保证金模式`和`跨币种保证金模式`  
> tgtCcy | String | 否 | 币币市价单委托数量`sz`的单位  
`base_ccy`: 交易货币 ；`quote_ccy`：计价货币  
仅适用于`币币`市价订单  
默认买单为`quote_ccy`，卖单为`base_ccy`  
> banAmend | Boolean | 否 | 是否禁止币币市价改单，true 或 false，默认false  
为true时，余额不足时，系统不会改单，下单会失败，仅适用于币币市价单  
> quickMgnType | String | 否 | 一键借币类型，仅适用于杠杆逐仓的一键借币模式：  
`manual`：手动，`auto_borrow`： 自动借币，`auto_repay`： 自动还币  
默认是`manual`：手动  
expTime | String | 否 | 请求有效截止时间。Unix时间戳的毫秒数格式，如 `1597026383085`  
  
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
> sMsg | String | 事件执行失败或成功时的msg  
在组合保证金账户模式下，或者全部成功，或者全部失败。

### 撤单

撤销当前未完成订单

#### 限速：60次/2s

#### 限速规则（期权以外）：UserID + Instrument ID

#### 限速规则（只限期权）：UserID + Instrument Family

同`撤单` REST API 共享限速

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

#### 限速：300个/2s

#### 限速规则（期权以外）：UserID + Instrument ID

#### 限速规则（只限期权）：UserID + Instrument Family

与其他限速按接口调用次数不同，该接口限速按订单的总个数限速。如果单次批量请求中只有一个元素，则算在单个`撤单`限速中。  同`批量撤单` REST API
共享限速

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

#### 跟单交易带单合约的限速：1次/2s

#### 限速规则（期权以外）：UserID + Instrument ID

#### 限速规则（只限期权）：UserID + Instrument Family

同`改单` REST API 共享限速

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
expTime | String | 否 | 请求有效截止时间。Unix时间戳的毫秒数格式，如 `1597026383085`  
  
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

#### 限速：300个/2s

#### 跟单交易带单合约的限速：1个/2s

#### 限速规则（期权以外）：UserID + Instrument ID

#### 限速规则（只限期权）：UserID + Instrument Family

与其他限速按接口调用次数不同，该接口限速按订单的总个数限速。如果单次批量请求中只有一个元素，则算在单个`修改订单`限速中。  同`批量改单` REST
API 共享限速

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
expTime | String | 否 | 请求有效截止时间。Unix时间戳的毫秒数格式，如 `1597026383085`  
  
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
        "msg": "Invalid request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"account\", \"ccy\" : \"BTC\"}]}"
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
        "ccy": "BTC",
        "uid": "77982378738415879"
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
              "spotInUseAmt":"",
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
        "uid": "77982378738415879"
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
              "spotInUseAmt":"",
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
              "spotInUseAmt":"",
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
适用于`简单交易模式`, `单币种保证金模式`, `跨币种保证金模式`和`组合保证金模式`  
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
> spotInUseAmt | String | 现货对冲占用数量  
适用于`组合保证金模式`  
  
如果同时成交多个订单，那么将对账户频道的推送尽量进行聚合。

首次推送，只推用户币种层面资产不为0的账户信息。币种层面资产不为0的定义：eq、availEq、availBal
中任意一个字段不为0，即币种层面资产不为0。

定时推送，只推用户币种层面资产不为0的账户信息。币种层面资产不为0的定义：eq、availEq、availBal
中任意一个字段不为0，即币种层面资产不为0。

例：按照所有币种订阅且有5个币种的余额或者权益都不为0，首次和定时推全部5个；账户下有一个币种余额或者权益改变，那么账户变更的触发只推这一个。

币种余额小于 1e-8 的币种信息，会在 details 中过滤掉不返回。

### 持仓频道

获取持仓信息，首次订阅按照订阅维度推送数据，此外，当下单、撤单等事件触发时，推送数据以及按照订阅维度定时推送数据

> 请求示例：单个
    
    
    {
        "op": "subscribe",
        "args": [{
            "channel": "positions",
            "instType": "FUTURES",
            "instFamily": "BTC-USD",
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
> instFamily | String | 否 | 交易品种  
适用于`交割/永续/期权`  
> instId | String | 否 | 产品ID  
  
> 成功返回示例：单个
    
    
    {
        "event": "subscribe",
        "arg": {
            "channel": "positions",
            "instType": "FUTURES",
            "instFamily": "BTC-USD",
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
        "msg": "Invalid request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"positions\", \"instType\" : \"FUTURES\"}]}"
    }
    

#### 返回参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
event | String | 是 | 事件，`subscribe` `unsubscribe` `error`  
arg | Object | 否 | 订阅的频道  
> channel | String | 是 | 频道名  
> instType | String | 是 | 产品类型  
`MARGIN`：币币杠杆  
`SWAP`：永续合约  
`FUTURES`：交割合约  
`OPTION`：期权  
`ANY`：全部  
> instFamily | String | 否 | 交易品种  
适用于`交割/永续/期权`  
> instId | String | 否 | 产品ID  
code | String | 否 | 错误码  
msg | String | 否 | 错误消息  
  
> 推送示例：单个
    
    
    {
        "arg":{
            "channel":"positions",
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
                "baseBorrowed": "",
                "baseInterest": "",
                "quoteBorrowed": "",
                "quoteInterest": "",
                "posCcy":"",
                "posId":"307173036051017730",
                "posSide":"long",
                "spotInUseAmt": "",
                "spotInUseCcy": "",
                "bizRefId": "",
                "bizRefType": "",
                "thetaBS":"",
                "thetaPA":"",
                "tradeId":"109844",
                "uTime":"1619507761462",
                "upl":"-0.0000009932766034",
                "uplRatio":"-0.0025490556801078",
                "vegaBS":"",
                "vegaPA":"",
                "closeOrderAlgo":[
                    {
                        "algoId":"123",
                        "slTriggerPx":"123",
                        "slTriggerPxType":"mark",
                        "tpTriggerPx":"123",
                        "tpTriggerPxType":"mark",
                        "closeFraction":"0.6"
                    },
                    {
                        "algoId":"123",
                        "slTriggerPx":"123",
                        "slTriggerPxType":"mark",
                        "tpTriggerPx":"123",
                        "tpTriggerPxType":"mark",
                        "closeFraction":"0.4"
                    }
                ]
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
        "baseBorrowed": "",
        "baseInterest": "",
        "quoteBorrowed": "",
        "quoteInterest": "",
        "posCcy":"",
        "posId":"307173036051017730",
        "posSide":"long",
        "spotInUseAmt": "",
        "spotInUseCcy": "",
        "bizRefId": "",
        "bizRefType": "",
        "thetaBS":"",
        "thetaPA":"",
        "tradeId":"109844",
        "uTime":"1619507761462",
        "upl":"-0.0000009932766034",
        "uplRatio":"-0.0025490556801078",
        "vegaBS":"",
        "vegaPA":"",
        "closeOrderAlgo":[
            {
                "algoId":"123",
                "slTriggerPx":"123",
                "slTriggerPxType":"mark",
                "tpTriggerPx":"123",
                "tpTriggerPxType":"mark",
                "closeFraction":"0.6"
            },
            {
                "algoId":"123",
                "slTriggerPx":"123",
                "slTriggerPxType":"mark",
                "tpTriggerPx":"123",
                "tpTriggerPxType":"mark",
                "closeFraction":"0.4"
            }
        ]
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
        "baseBorrowed": "",
        "baseInterest": "",
        "quoteBorrowed": "",
        "quoteInterest": "",
        "posCcy":"",
        "posId":"307173036051017730",
        "posSide":"long",
        "spotInUseAmt": "",
        "spotInUseCcy": "",
        "bizRefId": "",
        "bizRefType": "",
        "thetaBS":"",
        "thetaPA":"",
        "tradeId":"109844",
        "uTime":"1619507761462",
        "upl":"-0.0000009932766034",
        "uplRatio":"-0.0025490556801078",
        "vegaBS":"",
        "vegaPA":"",
        "closeOrderAlgo":[
            {
                "algoId":"123",
                "slTriggerPx":"123",
                "slTriggerPxType":"mark",
                "tpTriggerPx":"123",
                "tpTriggerPxType":"mark",
                "closeFraction":"0.6"
            },
            {
                "algoId":"123",
                "slTriggerPx":"123",
                "slTriggerPxType":"mark",
                "tpTriggerPx":"123",
                "tpTriggerPxType":"mark",
                "closeFraction":"0.4"
            }
        ]
    }]
    }
    

#### 推送数据参数

参数名 | 类型 | 描述  
---|---|---  
arg | Object | 订阅成功的频道  
> channel | String | 频道名  
> uid | String | 用户标识  
> instType | String | 产品类型  
> instFamily | String | 交易品种  
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
> baseBal | String | 交易币余额，适用于 `币币杠杆`（逐仓自主划转模式 和 一键借币模式）  
> quoteBal | String | 计价币余额 ，适用于 `币币杠杆`（逐仓自主划转模式 和 一键借币模式）  
> baseBorrowed | String | 交易币已借，适用于 币币杠杆（逐仓一键借币模式）  
> baseInterest | String | 交易币计息，适用于 币币杠杆（逐仓一键借币模式）  
> quoteBorrowed | String | 计价币已借，适用于 币币杠杆（逐仓一键借币模式）  
> quoteInterest | String | 计价币计息，适用于 币币杠杆（逐仓一键借币模式）  
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
> bizRefId | String | 外部业务id，e.g. 体验券id  
> bizRefType | String | 外部业务类型  
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
> spotInUseAmt | String | 现货对冲占用数量  
适用于`组合保证金模式`  
> spotInUseCcy | String | 现货对冲占用币种，如 `BTC`  
适用于`组合保证金模式`  
> closeOrderAlgo | Array | 平仓策略委托订单。调用策略委托下单，且`closeFraction`=1 时，该数组才会有值。  
>> algoId | String | 策略委托单ID  
>> slTriggerPx | String | 止损触发价  
>> slTriggerPxType | String | 止损触发价类型  
`last`：最新价格  
`index`：指数价格  
`mark`：标记价格  
>> tpTriggerPx | String | 止盈委托价  
>> tpTriggerPxType | String | 止盈触发价类型  
`last`：最新价格  
`index`：指数价格  
`mark`：标记价格  
>> closeFraction | String | 策略委托触发时，平仓的百分比。1 代表100%  
> cTime | String | 持仓创建时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
> uTime | String | 最近一次持仓更新时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
> pTime | String | 持仓信息的推送时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
  
如果同时成交多个订单，那么将持仓频道的推送尽量进行聚合。

Portfolio Margin 账户下，持仓的 IMR
MMR的数据是后端服务以ristUnit为最小粒度重新计算，相同riskUnit全仓仓位的imr和mmr返回值相同。

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
        "msg": "Invalid request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"balance_and_position\"}]}"
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
>> baseBal | String | 交易币余额，适用于 `币币杠杆`（逐仓自主划转模式和逐仓一键借币模式）  
>> quoteBal | String | 计价币余额 ，适用于 `币币杠杆`（逐仓自主划转模式和逐仓一键借币模式）  
>> posCcy | String | 持仓数量币种，只适用于币币杠杆仓位。当是交割、永续、期权持仓时，该字段返回“”  
>> uTime | String | 仓位信息的更新时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
  
只有账户余额变化，只推balData；只有持仓余额发生变化，只推posData。

首次推送，只推用户持有的仓位和币种余额不为0的信息。

例：比如按照所有币种订阅且用户有5个币种余额不为0
和20个仓位，那么首推全部5个币种余额列表和20个持仓信息列表；某个订单成交后，那么只推一个币种余额和对应的持仓信息。

币种余额小于 1e-8 的币种信息，会在 details 中过滤掉不返回。

### 订单频道

获取订单信息，首次订阅不推送，只有当下单、撤单等事件触发时，推送数据

> 请求示例：单个
    
    
    {
        "op": "subscribe",
        "args": [{
            "channel": "orders",
            "instType": "FUTURES",
            "instFamily": "BTC-USD",
            "instId": "BTC-USD-200329"
        }]
    }
    

> 请求示例
    
    
    {
        "op": "subscribe",
        "args": [{
            "channel": "orders",
            "instType": "FUTURES",
            "instFamily": "BTC-USD"
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
> instFamily | String | 否 | 交易品种  
适用于`交割/永续/期权`  
> instId | String | 否 | 产品ID  
  
> 成功返回示例：单个
    
    
    {
        "event": "subscribe",
        "arg": {
            "channel": "orders",
            "instType": "FUTURES",
            "instFamily": "BTC-USD",
            "instId": "BTC-USD-200329"
        }
    }
    

> 成功返回示例
    
    
    {
        "event": "subscribe",
        "arg": {
            "channel": "orders",
            "instType": "FUTURES",
            "instFamily": "BTC-USD"
        }
    }
    

> 失败返回示例
    
    
    {
        "event": "error",
        "code": "60012",
        "msg": "Invalid request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"orders\", \"instType\" : \"FUTURES\"}]}"
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
`ANY`：全部  
> instFamily | String | 否 | 交易品种  
适用于`交割/永续/期权`  
> instId | String | 否 | 产品ID  
code | String | 否 | 错误码  
msg | String | 否 | 错误消息  
  
> 推送示例：单个
    
    
    {
        "arg": {
            "channel": "orders",
            "instType": "SPOT",
            "instId": "BTC-USDT",
            "uid": "614488474791936"
        },
        "data": [
            {
                "accFillSz": "0.001",
                "amendResult": "",
                "avgPx": "31527.1",
                "cTime": "1654084334977",
                "category": "normal",
                "ccy": "",
                "clOrdId": "",
                "code": "0",
                "execType": "M",
                "fee": "-0.02522168",
                "feeCcy": "USDT",
                "fillFee": "-0.02522168",
                "fillFeeCcy": "USDT",
                "fillNotionalUsd": "31.50818374",
                "fillPx": "31527.1",
                "fillSz": "0.001",
                "fillTime": "1654084353263",
                "instId": "BTC-USDT",
                "instType": "SPOT",
                "lever": "0",
                "msg": "",
                "notionalUsd": "31.50818374",
                "ordId": "452197707845865472",
                "ordType": "limit",
                "pnl": "0",
                "posSide": "",
                "px": "31527.1",
                "rebate": "0",
                "rebateCcy": "BTC",
                "reduceOnly": "false",
                "reqId": "",
                "side": "sell",
                "slOrdPx": "",
                "slTriggerPx": "",
                "slTriggerPxType": "last",
                "source": "",
                "state": "filled",
                "sz": "0.001",
                "tag": "",
                "tdMode": "cash",
                "tgtCcy": "",
                "tpOrdPx": "",
                "tpTriggerPx": "",
                "tpTriggerPxType": "last",
                "tradeId": "242589207",
                "quickMgnType": "",
                "algoClOrdId": "",
                "algoId": "",
                "uTime": "1654084353264"
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
> instFamily | String | 交易品种  
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
> tgtCcy | String | 市价单委托数量`sz`的单位  
`base_ccy`: 交易货币 `quote_ccy`：计价货币  
> fillPx | String | 最新成交价格  
> tradeId | String | 最新成交ID  
> fillSz | String | 最新成交数量  
对于`币币`和`杠杆`，单位为交易货币，如 BTC-USDT, 单位为
BTC；对于市价单，无论`tgtCcy`是`base_ccy`，还是`quote_ccy`，单位均为交易货币；  
对于交割、永续以及期权，单位为张。  
> fillTime | String | 最新成交时间  
> fillFee | String | 最新一笔成交的手续费金额或者返佣金额：  
手续费扣除 为 ‘负数’，如 -0.01 ；  
手续费返佣 为 ‘正数’，如 0.01  
> fillFeeCcy | String | 最新一笔成交的手续费币种  
> execType | String | 最新一笔成交的流动性方向 T：taker M：maker  
> accFillSz | String | 累计成交数量  
对于`币币`和`杠杆`，单位为交易货币，如 BTC-USDT, 单位为
BTC；对于市价单，无论`tgtCcy`是`base_ccy`，还是`quote_ccy`，单位均为交易货币；  
对于交割、永续以及期权，单位为张。  
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
> fee | String | 订单交易累计的手续费与返佣  
对于币币和杠杆，为订单交易累计的手续费，平台向用户收取的交易手续费，为负数。如： -0.01  
对于交割、永续和期权，为订单交易累计的手续费和返佣  
> rebateCcy | String | 返佣金币种 ，如果没有返佣金，该字段为“”  
> rebate | String |
> 返佣累计金额，仅适用于币币和杠杆，平台向达到指定lv交易等级的用户支付的挂单奖励（返佣），如果没有返佣金，该字段为“”  
> pnl | String | 收益，适用于有成交的平仓订单，其他情况均为0  
> source | String | 订单来源  
`13`:策略委托单触发后的生成的限价单  
> cancelSource | String | 订单取消的来源  
有效值及对应的含义是：  
`0`: 已撤单：系统撤单  
`1`: 用户主动撤单  
`2`: 已撤单：预减仓撤单，用户保证金不足导致挂单被撤回  
`3`: 已撤单：风控撤单，用户保证金不足有爆仓风险，导致挂单被撤回  
`4`: 已撤单：币种借币量达到平台硬顶，系统已撤回该订单  
`6`: 已撤单：触发 ADL 撤单，用户保证金率较低且有爆仓风险，导致挂单被撤回  
`9`: 已撤单：扣除资金费用后可用余额不足，系统已撤回该订单  
`13`: 已撤单：FOK 委托订单未完全成交，导致挂单被完全撤回  
`14`: 已撤单：IOC 委托订单未完全成交，仅部分成交，导致部分挂单被撤回  
`17`: 已撤单：平仓单被撤单，由于仓位已被市价全平  
`20`: 系统倒计时撤单  
`21`: 已撤单：相关仓位被完全平仓，系统已撤销该止盈止损订单  
`22`, `23`: 已撤单：只减仓订单仅允许减少仓位数量，系统已撤销该订单  
`27`: 成交滑点超过5%，触发成交差价保护导致系统撤单  
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
`1`：自动撤单（因为修改失败导致订单自动撤销）  
通过API修改订单时，如果`cxlOnFail`设置为`false`且修改失败后，则`amendResult`返回 `-1`  
通过API修改订单时，如果`cxlOnFail`设置为`true`且修改失败后，则`amendResult`返回`1`  
通过Web/APP修改订单时，如果修改失败后，则`amendResult`返回`-1`  
> reduceOnly | String | 是否只减仓，`true` 或 `false`  
> quickMgnType | String | 一键借币类型，仅适用于杠杆逐仓的一键借币模式  
`manual`：手动，`auto_borrow`： 自动借币，`auto_repay`： 自动还币  
> algoClOrdId | String | 客户自定义策略订单ID。策略订单触发，且策略单有`algoClOrdId`时有值，否则为"",  
> algoId | String | 策略委托单ID，策略订单触发时有值，否则为""  
> code | String | 错误码，默认为0  
> msg | String | 错误消息，默认为""  
  
对于市价委托，订单频道推送消息会出现状态为“完全成交”，但最新成交数量 (fillSz) 为 0 的情况。

### 策略委托订单频道

获取策略委托订单，首次订阅不推送，只有当下单、撤单等事件触发时，推送数据

> 请求示例：单个
    
    
    {
        "op": "subscribe",
        "args": [{
            "channel": "orders-algo",
            "instType": "FUTURES",
            "instFamily": "BTC-USD",
            "instId": "BTC-USD-200329"
        }]
    }
    

> 请求示例
    
    
    {
        "op": "subscribe",
        "args": [{
            "channel": "orders-algo",
            "instType": "FUTURES",
            "instFamily": "BTC-USD"
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
> instFamily | String | 否 | 交易品种  
适用于`交割/永续/期权`  
> instId | String | 否 | 产品ID  
  
> 成功返回示例：单个
    
    
    {
        "event": "subscribe",
        "arg": {
            "channel": "orders-algo",
            "instType": "FUTURES",
            "instFamily": "BTC-USD",
            "instId": "BTC-USD-200329"
        }
    }
    

> 成功返回示例
    
    
    {
        "event": "subscribe",
        "arg": {
            "channel": "orders-algo",
            "instType": "FUTURES",
            "instFamily": "BTC-USD"
        }
    }
    

> 失败返回示例
    
    
    {
        "event": "error",
        "code": "60012",
        "msg": "Invalid request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"orders-algo\", \"instType\" : \"FUTURES\"}]}"
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
`ANY`：全部  
> instFamily | String | 否 | 交易品种  
适用于`交割/永续/期权`  
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
            "clOrdId": "",
            "algoId": "1234",
            "px": "999",
            "sz": "3",
            "tdMode": "cross",
            "tgtCcy": "",
            "notionalUsd": "",
            "ordType": "trigger",
            "side": "buy",
            "posSide": "long",
            "reduceOnly": "false",
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
            "code": "0",
            "msg": "",
            "actualSide": "",
            "failCode": "",
            "algoClOrdId": "",
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
> instFamily | String | 交易品种  
适用于`交割/永续/期权`  
> instId | String | 产品ID  
data | Array | 订阅的数据  
> instType | String | 产品类型  
> instId | String | 产品ID  
> ccy | String | 保证金币种，仅单币种保证金账户下的全仓币币杠杆需要选择保证金币种  
> ordId | String | 订单ID，与策略委托订单关联的订单ID  
> algoId | String | 策略委托单ID  
> clOrdId | String | 客户自定义订单ID  
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
> tgtCcy | String | 币币市价单委托数量`sz`的单位  
`base_ccy`: 交易货币 ；`quote_ccy`：计价货币  
仅适用于`币币`市价订单  
默认买单为`quote_ccy`，卖单为`base_ccy`  
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
> reduceOnly | String | 是否只减仓，`true` 或 `false`  
> failCode | String | 代表策略触发失败的原因，已撤销和已生效时为""，委托失败时有值，如 51008；  
仅适用于单向止盈止损委托、双向止盈止损委托、移动止盈止损委托、计划委托。  
> algoClOrdId | String | 客户自定义策略订单ID  
> code | String | 错误码，默认为0  
> msg | String | 错误消息，默认为""  
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
        "msg": "Invalid request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"algo-advance\", \"instType\" : \"FUTURES\"}]}"
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
                "clOrdId": "",
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
                "moveTriggerPx":"",
                "failCode": "",
                "algoClOrdId": ""
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
> clOrdId | String | 客户自定义订单ID  
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
> tgtCcy | String | 币币市价单委托数量`sz`的单位  
`base_ccy`: 交易货币 ；`quote_ccy`：计价货币  
仅适用于`币币`市价订单  
默认买单为`quote_ccy`，卖单为`base_ccy`  
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
> failCode | String | 代表策略触发失败的原因，已撤销和已生效时为""，委托失败时有值，如 51008；  
仅适用于单向止盈止损委托、双向止盈止损委托、移动止盈止损委托、计划委托。  
> algoClOrdId | String | 客户自定义策略订单ID  
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
> instFamily | String | 否 | 交易品种  
适用于`交割/永续/期权`  
> instId | String | 否 | 产品ID  
  
> 成功返回示例：单个
    
    
    {
        "event": "subscribe",
        "arg": {
            "channel": "liquidation-warning",
            "instType": "FUTURES",
            "instFamily": "BTC-USD",
            "instId": "BTC-USD-200329"
        }
    }
    

> 失败返回示例
    
    
    {
        "event": "error",
        "code": "60012",
        "msg": "Invalid request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"liquidation-warning\", \"instType\" : \"FUTURES\"}]}"
    }
    

#### 返回参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
event | String | 是 | 事件，`subscribe` `unsubscribe` `error`  
arg | Object | 否 | 订阅的频道  
> channel | String | 是 | 频道名 ，`liquidation-warning`  
> instType | String | 是 | 产品类型  
`MARGIN`：币币杠杆  
`SWAP`：永续合约  
`FUTURES`：交割合约  
`OPTION`：期权  
`ANY`： 全部  
> instFamily | String | 否 | 交易品种  
适用于`交割/永续/期权`  
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
> uid | String | 用户标识  
> instType | String | 产品类型  
> instFamily | String | 交易品种  
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
        "msg": "Invalid request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"account-greeks\", \"ccy\" : \"BTC\"}]}"
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

### 充值信息频道

该频道使用如下服务地址  
wss://ws.okx.com:8443/ws/v5/business，wss://wsaws.okx.com:8443/ws/v5/business

当发起充值或者充值状态发生变化时会触发消息推送。  
支持母账户或者子账户的订阅  

  * 如果是母账户订阅，可以同时接受母账户与子账户的充值信息的推送  

  * 如果是子账户订阅，则仅支持子账户充值信息的推送  

> 请求示例
    
    
    {
        "op": "subscribe",
        "args": [
            {
                "channel": "deposit-info"
            }
        ]
    }
    

#### 请求参数

参数名 | 类型 | 是否必填 | 描述  
---|---|---|---  
op | String | 是 | 操作, `subscribe` `unsubscribe`  
args | Array | 是 | 请求订阅的频道列表  
> channel | String | 是 | 频道名, `deposit-info`  
> ccy | String | 否 | 币种名称，如 `BTC`  
  
> 成功返回示例
    
    
    {
        "event": "subscribe",
        "arg": {
            "channel": "deposit-info"
        }
    }
    

> 失败返回示例
    
    
    {
        "event": "error",
        "code": "60012",
        "msg": "Invalid request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"deposit-info\""}]}"
    }
    

#### 返回参数

参数名 | 类型 | 是否必填 | 描述  
---|---|---|---  
event | String | 是 | 操作, `subscribe` `unsubscribe` `error`  
arg | Object | 否 | 订阅的频道  
> channel | String | 是 | 频道名, `deposit-info`  
> ccy | String | 否 | 币种名称，如 `BTC`  
code | String | 否 | 错误码  
msg | String | 否 | 错误消息  
  
> 推送示例
    
    
    {
        "arg": {
            "channel": "deposit-info",
            "uid": "289320****60975104"
        },
        "data": [{
            "actualDepBlkConfirm": "0",
            "amt": "1",
            "areaCodeFrom": "",
            "ccy": "USDT",
            "chain": "USDT-TRC20",
            "depId": "88165462",
            "from": "",
            "fromWdId": "",
            "pTime": "1674103661147",
            "state": "0",
            "subAcct": "test",
            "to": "TEhFAqpuHa3LY*****8ByNoGnrmexeGMw",
            "ts": "1674103661123",
            "txId": "bc5376817*****************dbb0d729f6b",
            "uid": "289320****60975104"
        }]
    }
    

#### 推送数据参数

**参数名** | **类型** | **描述**  
---|---|---  
arg | Object | 订阅成功的频道  
> channel | String | 频道名  
> uid | String | 用户标识  
> ccy | String | 币种名称，如 `BTC`  
data | Array | 订阅的数据  
> uid | String | (产生数据者的）用户标识  
> subAcct | String | 子账户名称  
如果是母账户产生的数据，该字段返回""  
> pTime | String | 推送时间，Unix时间戳的毫秒数格式，如 1597026383085  
> ccy | String | 币种名称，如 `BTC`  
> chain | String | 币种链信息  
有的币种下有多个链，必须要做区分，如`USDT`下有`USDT-ERC20`，`USDT-TRC20`，`USDT-Omni`多个链  
> amt | String | 充值数量  
> from | String | 充值账户，只显示内部账户转账地址，不显示区块链充值地址  
> areaCodeFrom | String | 如果`from`为手机号，该字段为该手机号的区号  
> to | String | 到账地址  
> txId | String | 区块转账哈希记录  
> ts | String | 数据更新时间，Unix 时间戳的毫秒数格式，如 `1655251200000`  
> state | String | 充值状态  
`0`：等待确认  
`1`：确认到账  
`2`：充值成功  
`8`：因该币种暂停充值而未到账，恢复充值后自动到账  
`11`：命中地址黑名单  
`12`：账户或充值被冻结  
`13`：子账户充值拦截  
> depId | String | 充值记录 ID  
> fromWdId | String | 内部转账发起者提币申请 ID  
如果该笔充值来自于内部转账，则该字段展示内部转账发起者的提币申请 ID，其他情况返回""  
> actualDepBlkConfirm | String | 最新的充币网络确认数  
  
### 提币信息频道

该频道使用如下服务地址  
wss://ws.okx.com:8443/ws/v5/business，wss://wsaws.okx.com:8443/ws/v5/business

当发起提币或者提币状态发生变化时会触发消息推送。  
支持母账户或者子账户的订阅  

  * 如果是母账户订阅，可以同时接受母账户与子账户的提币信息的推送  

  * 如果是子账户订阅，则仅支持子账户提币信息的推送  

> 请求示例
    
    
    {
        "op": "subscribe",
        "args": [
            {
                "channel": "withdrawal-info"
            }
        ]
    }
    

#### 请求参数

参数名 | 类型 | 是否必填 | 描述  
---|---|---|---  
op | String | 是 | 操作, `subscribe` `unsubscribe`  
args | Array | 是 | 请求订阅的频道列表  
> channel | String | 是 | 频道名, `withdrawal-info`  
> ccy | String | 否 | 币种名称，如 `BTC`  
  
> 成功返回示例
    
    
    {
        "event": "subscribe",
        "arg": {
            "channel": "withdrawal-info"
        }
    }
    

> 失败返回示例
    
    
    {
        "event": "error",
        "code": "60012",
        "msg": "Invalid request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"withdrawal-info\""}]}"
    }
    

#### 返回参数

参数名 | 类型 | 是否必填 | 描述  
---|---|---|---  
event | String | 是 | 操作, `subscribe` `unsubscribe` `error`  
arg | Object | 否 | 订阅的频道  
> channel | String | 是 | 频道名, `withdrawal-info`  
> ccy | String | 否 | 币种名称，如 `BTC`  
code | String | 否 | 错误码  
msg | String | 否 | 错误消息  
  
> 推送示例
    
    
    {
        "arg": {
            "channel": "withdrawal-info",
            "uid": "289320*****0975104"
        },
        "data": [{
            "addrEx": null,
            "amt": "2",
            "areaCodeFrom": "",
            "areaCodeTo": "",
            "ccy": "USDT",
            "chain": "USDT-TRC20",
            "clientId": "",
            "fee": "0.8",
            "feeCcy": "USDT",
            "from": "",
            "memo": "",
            "nonTradableAsset": false,
            "pTime": "1674103268578",
            "pmtId": "",
            "state": "0",
            "subAcct": "test",
            "tag": "",
            "to": "TN8CKTQMnpWfT******8KipbJ24ErguhF",
            "ts": "1674103268472",
            "txId": "",
            "uid": "289333*****1101696",
            "wdId": "63754560"
        }]
    }
    

#### 推送数据参数

**参数名** | **类型** | **描述**  
---|---|---  
arg | Object | 订阅成功的频道  
> channel | String | 频道名  
> uid | String | 用户标识  
> ccy | String | 币种名称，如 `BTC`  
data | Array | 订阅的数据  
> uid | String | (产生数据者的）用户标识  
> subAcct | String | 子账户名称  
如果是母账户产生的数据，该字段返回""  
> pTime | String | 推送时间，Unix时间戳的毫秒数格式，如 1597026383085  
> ccy | String | 币种  
> chain | String | 币种链信息  
有的币种下有多个链，必须要做区分，如`USDT`下有`USDT-ERC20`，`USDT-TRC20`，`USDT-Omni`多个链  
> nonTradableAsset | String | 是否为不可交易资产  
`true`：不可交易资产，`false`：可交易资产  
> amt | String | 数量  
> ts | String | 提币申请时间，Unix 时间戳的毫秒数格式，如 `1655251200000`  
> from | String | 提币账户  
可以是邮箱/手机号  
> areaCodeFrom | String | 如果`from`为手机号，该字段为该手机号的区号  
> to | String | 收币地址  
> areaCodeTo | String | 如果`to`为手机号，该字段为该手机号的区号  
> tag | String | 部分币种提币需要标签  
> pmtId | String | 部分币种提币需要此字段（payment_id）  
> memo | String | 部分币种提币需要此字段  
> addrEx | Object |
> 提币地址备注。如币种TONCOIN的提币地址备注标签名为comment,则该字段返回：{'comment':'123456'}  
> txId | String | 提币哈希记录  
内部转账该字段返回""  
> fee | String | 提币手续费数量  
> feeCcy | String | 提币手续费币种，如 `USDT`  
> state | String | 提币状态  
`-3`：撤销中  
`-2`：已撤销  
`-1`：失败  
`0`：等待提币  
`1`：提币中  
`2`：提币成功  
`7`: 审核通过  
`10`: 等待划转  
`4`, `5`, `6`, `8`, `9`, `12`: 等待客服审核  
> wdId | String | 提币申请ID  
> clientId | String | 客户自定义ID  
  
### 现货网格策略委托订单频道

支持现货网格策略订单的首次订阅推送，定时推送和事件推送

> 请求示例
    
    
    {
        "op": "subscribe",
        "args": [{
            "channel": "grid-orders-spot",
            "instType": "SPOT"
        }]
    }
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
op | String | 是 | 操作，`subscribe` `unsubscribe`  
args | Array | 是 | 请求订阅的频道列表  
> channel | String | 是 | 频道名，`grid-orders-spot`  
> instType | String | 是 | 产品类型  
`SPOT`：币币  
`ANY`：全部  
> instId | String | 否 | 产品ID  
> algoId | String | 否 | 策略ID  
  
> 成功返回示例
    
    
    {
        "event": "subscribe",
        "arg": {
            "channel": "grid-orders-spot",
            "instType": "SPOT"
        }
    }
    

> 失败返回示例
    
    
    {
        "event": "error",
        "code": "60012",
        "msg": "Invalid request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"grid-orders-spot\", \"instType\" : \"FUTURES\"}]}"
    }
    

#### 返回参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
event | String | 是 | 事件，`subscribe` `unsubscribe` `error`  
arg | Object | 否 | 订阅的频道  
> channel | String | 是 | 频道名  
> instType | String | 是 | 产品类型  
> instId | String | 否 | 产品ID  
> algoId | String | 否 | 策略ID  
code | String | 否 | 错误码  
msg | String | 否 | 错误消息  
  
> 推送示例
    
    
    {
        "arg": {
            "channel": "grid-orders-spot",
            "instType": "ANY"
        },
        "data": [{
            "algoId": "448965992920907776",
            "algoOrdType": "grid",
            "annualizedRate": "0",
            "arbitrageNum": "0",
            "baseSz": "0",
            "cTime": "1653313834104",
            "cancelType": "0",
            "curBaseSz": "0.001776289214",
            "curQuoteSz": "46.801755866",
            "floatProfit": "-0.4953878967772",
            "gridNum": "6",
            "gridProfit": "0",
            "instId": "BTC-USDC",
            "instType": "SPOT",
            "investment": "100",
            "maxPx": "33444.8",
            "minPx": "24323.5",
            "pTime": "1653476023742",
            "perMaxProfitRate": "0.060375293181491054543",
            "perMinProfitRate": "0.0455275366818586",
            "pnlRatio": "0",
            "quoteSz": "100",
            "runPx": "30478.1",
            "runType": "1",
            "singleAmt": "0.00059261",
            "slTriggerPx": "",
            "state": "running",
            "stopResult": "0",
            "stopType": "0",
            "totalAnnualizedRate": "-0.9643551057262827",
            "totalPnl": "-0.4953878967772",
            "tpTriggerPx": "",
            "tradeNum": "3",
            "triggerTime": "1653378736894",
            "uTime": "1653378736894"
        }]
    }
    

#### 推送数据参数

**参数名** | **类型** | **描述**  
---|---|---  
arg | Object | 订阅成功的频道  
> channel | String | 频道名  
> instType | String | 产品类型  
data | Array | 订阅的数据  
> algoId | String | 策略订单ID  
> instType | String | 产品类型  
> instId | String | 产品ID  
> cTime | String | 策略订单创建时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
> uTime | String | 策略订单更新时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
> triggerTime | String | 策略订单触发时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
> algoOrdType | String | 策略订单类型  
`grid`：现货网格  
> state | String | 订单状态  
`starting`：启动中  
`running`：运行中  
`stopping`：终止中  
`stopped`：已停止  
> maxPx | String | 区间最高价格  
> minPx | String | 区间最低价格  
> gridNum | String | 网格数量  
> runType | String | 网格类型  
`1`：等差，`2`：等比  
> tpTriggerPx | String | 止盈触发价  
> slTriggerPx | String | 止损触发价  
> tradeNum | String | 挂单成交次数  
> arbitrageNum | String | 网格套利次数  
> singleAmt | String | 单网格买卖量  
> perMinProfitRate | String | 预期单网格最低利润率  
> perMaxProfitRate | String | 预期单网格最高利润率  
> runPx | String | 启动时价格  
> totalPnl | String | 总收益  
> pnlRatio | String | 收益率  
> investment | String | 投入金额  
现货网格如果投入了交易币则折算为计价币  
> gridProfit | String | 网格利润  
> floatProfit | String | 浮动盈亏  
> totalAnnualizedRate | String | 总年化  
> annualizedRate | String | 网格年化  
> cancelType | String | 网格策略停止原因  
`0`：无  
`1`：手动停止  
`2`：止盈停止  
`3`：止损停止  
`4`：风控停止  
`5`：交割停止  
> stopType | String | 网格策略停止类型  
现货网格 `1`：卖出交易币，`2`：不卖出交易币  
合约网格 `1`：市价全平，`2`：停止不平仓  
> quoteSz | String | 计价币投入数量  
仅适用于`现货网格`  
> baseSz | String | 交易币投入数量  
仅适用于`现货网格`  
> curQuoteSz | String | 当前持有的计价币资产  
仅适用于`现货网格`  
> curBaseSz | String | 当前持有的交易币资产  
仅适用于`现货网格`  
> profit | String | 当前可提取利润,单位是计价币  
仅适用于`现货网格`  
> stopResult | String | 现货网格策略停止结果  
`0`：默认，`1`：市价卖币成功 `-1`：市价卖币失败  
仅适用于`现货网格`  
> tag | String | 订单标签  
> pTime | String | 网格策略的推送时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
  
### 合约网格策略委托订单频道

支持合约网格策略订单的首次订阅推送，定时推送和事件推送

> 请求示例
    
    
    {
        "op": "subscribe",
        "args": [{
            "channel": "grid-orders-contract",
            "instType": "SWAP"
        }]
    }
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
op | String | 是 | 操作，`subscribe` `unsubscribe`  
args | Array | 是 | 请求订阅的频道列表  
> channel | String | 是 | 频道名，`grid-orders-contract`  
> instType | String | 是 | 产品类型  
`SWAP`：永续  
`FUTURE`：交割  
`ANY`：全部  
> instId | String | 否 | 产品ID  
> algoId | String | 否 | 策略ID  
  
> 成功返回示例
    
    
    {
        "event": "subscribe",
        "arg": {
            "channel": "grid-orders-contract",
            "instType": "SWAP"
        }
    }
    

> 失败返回示例
    
    
    {
        "event": "error",
        "code": "60012",
        "msg": "Invalid request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"grid-orders-contract\", \"instType\" : \"FUTURES\"}]}"
    }
    

#### 返回参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
event | String | 是 | 事件，`subscribe` `unsubscribe` `error`  
arg | Object | 否 | 订阅的频道  
> channel | String | 是 | 频道名  
> instType | String | 是 | 产品类型  
> instId | String | 否 | 产品ID  
> algoId | String | 否 | 策略ID  
code | String | 否 | 错误码  
msg | String | 否 | 错误消息  
  
> 推送示例
    
    
    {
        "arg": {
            "channel": "grid-orders-contract",
            "instType": "ANY"
        },
        "data": [{
            "actualLever": "1.02",
            "algoId": "449327675342323712",
            "algoOrdType": "contract_grid",
            "annualizedRate": "0.7572437878956523",
            "arbitrageNum": "1",
            "basePos": true,
            "cTime": "1653400065912",
            "cancelType": "0",
            "direction": "long",
            "eq": "10129.419829834853",
            "floatProfit": "109.537858234853",
            "gridNum": "50",
            "gridProfit": "19.8819716",
            "instId": "BTC-USDT-SWAP",
            "instType": "SWAP",
            "investment": "10000",
            "lever": "5",
            "liqPx": "603.2149534767834",
            "maxPx": "100000",
            "minPx": "10",
            "pTime": "1653484573918",
            "perMaxProfitRate": "995.7080916791230692",
            "perMinProfitRate": "0.0946277854875634",
            "pnlRatio": "0.0129419829834853",
            "runPx": "29216.3",
            "runType": "1",
            "singleAmt": "1",
            "slTriggerPx": "",
            "state": "running",
            "stopType": "0",
            "sz": "10000",
            "tag": "",
            "totalAnnualizedRate": "4.929207431970923",
            "totalPnl": "129.419829834853",
            "tpTriggerPx": "",
            "tradeNum": "37",
            "triggerTime": "1653400066940",
            "uTime": "1653484573589",
            "uly": "BTC-USDT"
        }]
    }
    

#### 推送数据参数

**参数名** | **类型** | **描述**  
---|---|---  
arg | Object | 订阅成功的频道  
> channel | String | 频道名  
> instType | String | 产品类型  
data | Array | 订阅的数据  
> algoId | String | 策略订单ID  
> instType | String | 产品类型  
> instId | String | 产品ID  
> cTime | String | 策略订单创建时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
> uTime | String | 策略订单更新时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
> triggerTime | String | 策略订单触发时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
> algoOrdType | String | 策略订单类型  
`contract_grid`：合约网格  
> state | String | 订单状态  
`starting`：启动中  
`running`：运行中  
`stopping`：终止中  
`no_close_position`：已停止未平仓（仅适用于合约网格）  
`stopped`：已停止  
> maxPx | String | 区间最高价格  
> minPx | String | 区间最低价格  
> gridNum | String | 网格数量  
> runType | String | 网格类型  
`1`：等差，`2`：等比  
> tpTriggerPx | String | 止盈触发价  
> slTriggerPx | String | 止损触发价  
> tradeNum | String | 挂单成交次数  
> arbitrageNum | String | 网格套利次数  
> singleAmt | String | 单网格买卖量  
> perMinProfitRate | String | 预期单网格最低利润率  
> perMaxProfitRate | String | 预期单网格最高利润率  
> runPx | String | 启动时价格  
> totalPnl | String | 总收益  
> pnlRatio | String | 收益率  
> investment | String | 投入金额  
现货网格如果投入了交易币则折算为计价币  
> gridProfit | String | 网格利润  
> floatProfit | String | 浮动盈亏  
> totalAnnualizedRate | String | 总年化  
> annualizedRate | String | 网格年化  
> cancelType | String | 网格策略停止原因  
`0`：无  
`1`：手动停止  
`2`：止盈停止  
`3`：止损停止  
`4`：风控停止  
`5`：交割停止  
> stopType | String | 网格策略停止类型  
现货网格 `1`：卖出交易币，`2`：不卖出交易币  
合约网格 `1`：市价全平，`2`：停止不平仓  
> direction | String | 合约网格类型  
`long`：做多，`short`：做空，`neutral`：中性  
仅适用于`合约网格`  
> basePos | Boolean | 是否开底仓  
仅适用于`合约网格`  
> sz | String | 投入保证金，单位为`USDT`  
仅适用于`合约网格`  
> lever | String | 杠杆倍数  
仅适用于`合约网格`  
> actualLever | String | 实际杠杆倍数  
仅适用于`合约网格`  
> liqPx | String | 预估强平价格  
仅适用于`合约网格`  
> eq | String | 策略账户总权益  
仅适用于`合约网格`  
> uly | String | 标的指数  
> tag | String | 订单标签  
> pTime | String | 网格策略的推送时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
  
### 天地网格策略委托订单频道

支持天地网格策略订单的首次订阅推送，定时推送和事件推送

> 请求示例
    
    
    {
        "op": "subscribe",
        "args": [{
            "channel": "grid-orders-moon",
            "instType": "SPOT"
        }]
    }
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
op | String | 是 | 操作，`subscribe` `unsubscribe`  
args | Array | 是 | 请求订阅的频道列表  
> channel | String | 是 | 频道名，`grid-orders-moon`  
> instType | String | 是 | 产品类型  
`SPOT`：币币  
`ANY`：全部  
> instId | String | 否 | 产品ID  
> algoId | String | 否 | 策略ID  
  
> 成功返回示例
    
    
    {
        "event": "subscribe",
        "arg": {
            "channel": "grid-orders-moon",
            "instType": "SPOT"
        }
    }
    

> 失败返回示例
    
    
    {
        "event": "error",
        "code": "60012",
        "msg": "Invalid request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"grid-orders-moon\", \"instType\" : \"FUTURES\"}]}"
    }
    

#### 返回参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
event | String | 是 | 事件，`subscribe` `unsubscribe` `error`  
arg | Object | 否 | 订阅的频道  
> channel | String | 是 | 频道名  
> instType | String | 是 | 产品类型  
> instId | String | 否 | 产品ID  
> algoId | String | 否 | 策略ID  
code | String | 否 | 错误码  
msg | String | 否 | 错误消息  
  
> 推送示例
    
    
    {
        "arg": {
            "channel": "grid-orders-moon",
            "instType": "ANY"
        },
        "data": [{
            "algoId": "448965992920907776",
            "algoOrdType": "moon_grid",
            "annualizedRate": "0",
            "arbitrageNum": "0",
            "baseSz": "0",
            "cTime": "1653313834104",
            "cancelType": "0",
            "curBaseSz": "0.001776289214",
            "curQuoteSz": "46.801755866",
            "floatProfit": "-0.4953878967772",
            "gridNum": "6",
            "gridProfit": "0",
            "instId": "BTC-USDC",
            "instType": "SPOT",
            "investment": "100",
            "maxPx": "33444.8",
            "minPx": "24323.5",
            "pTime": "1653476023742",
            "perMaxProfitRate": "0.060375293181491054543",
            "perMinProfitRate": "0.0455275366818586",
            "pnlRatio": "0",
            "quoteSz": "100",
            "runPx": "30478.1",
            "runType": "1",
            "singleAmt": "0.00059261",
            "state": "running",
            "stopResult": "0",
            "stopType": "0",
            "totalAnnualizedRate": "-0.9643551057262827",
            "totalPnl": "-0.4953878967772",
            "tradeNum": "3",
            "triggerTime": "1653378736894",
            "uTime": "1653378736894"
        }]
    }
    

#### 推送数据参数

**参数名** | **类型** | **描述**  
---|---|---  
arg | Object | 订阅成功的频道  
> channel | String | 频道名  
> instType | String | 产品类型  
data | Array | 订阅的数据  
> algoId | String | 策略订单ID  
> instType | String | 产品类型  
> instId | String | 产品ID  
> cTime | String | 策略订单创建时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
> uTime | String | 策略订单更新时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
> triggerTime | String | 策略订单触发时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
> algoOrdType | String | 策略订单类型  
`moon_grid`：天地网格  
> state | String | 订单状态  
`starting`：启动中  
`running`：运行中  
`stopping`：终止中  
`stopped`：已停止  
> maxPx | String | 区间最高价格  
> minPx | String | 区间最低价格  
> gridNum | String | 网格数量  
> runType | String | 网格类型  
`1`：等差，`2`：等比  
> tradeNum | String | 挂单成交次数  
> arbitrageNum | String | 网格套利次数  
> singleAmt | String | 单网格买卖量  
> perMinProfitRate | String | 预期单网格最低利润率  
> perMaxProfitRate | String | 预期单网格最高利润率  
> runPx | String | 启动时价格  
> totalPnl | String | 总收益  
> pnlRatio | String | 收益率  
> investment | String | 投入金额  
天地网格如果投入了交易币则折算为计价币  
> gridProfit | String | 网格利润  
> floatProfit | String | 浮动盈亏  
> totalAnnualizedRate | String | 总年化  
> annualizedRate | String | 网格年化  
> cancelType | String | 网格策略停止原因  
`0`：无  
`1`：手动停止  
`2`：止盈停止  
`3`：止损停止  
`4`：风控停止  
`5`：交割停止  
> stopType | String | 网格策略停止类型  
`1`：卖出交易币，`2`：不卖出交易币  
> quoteSz | String | 计价币投入数量  
> baseSz | String | 交易币投入数量  
> curQuoteSz | String | 当前持有的计价币资产  
> curBaseSz | String | 当前持有的交易币资产  
> profit | String | 当前可提取利润,单位是计价币  
> stopResult | String | 策略停止结果  
`0`：默认，`1`：市价卖币成功 `-1`：市价卖币失败  
> tag | String | 订单标签  
> pTime | String | 网格策略的推送时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
  
### 合约网格持仓频道

支持网格策略持仓的首次订阅推送，定时推送和事件推送

> 请求示例
    
    
    {
        "op": "subscribe",
        "args": [{
            "channel": "grid-positions",
            "algoId": "449327675342323712"
        }]
    }
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
op | String | 是 | 操作，`subscribe` `unsubscribe`  
args | Array | 是 | 请求订阅的频道列表  
> channel | String | 是 | 频道名，`grid-positions`  
> algoId | String | 是 | 策略ID  
  
> 成功返回示例
    
    
    {
        "event": "subscribe",
        "arg": {
            "channel": "grid-positions",
            "algoId": "449327675342323712"
        }
    }
    

> 失败返回示例
    
    
    {
        "event": "error",
        "code": "60012",
        "msg": "Invalid request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"grid-positions\", \"instType\" : \"FUTURES\"}]}"
    }
    

#### 返回参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
event | String | 是 | 事件，`subscribe` `unsubscribe` `error`  
arg | Object | 否 | 订阅的频道  
> channel | String | 是 | 频道名  
> algoId | String | 是 | 策略ID  
code | String | 否 | 错误码  
msg | String | 否 | 错误消息  
  
> 推送示例
    
    
    {
        "arg": {
            "channel": "grid-positions",
            "uid": "44705892343619584",
            "algoId": "449327675342323712"
        },
        "data": [{
            "adl": "1",
            "algoId": "449327675342323712",
            "avgPx": "29181.4638888888888895",
            "cTime": "1653400065917",
            "ccy": "USDT",
            "imr": "2089.2690000000002",
            "instId": "BTC-USDT-SWAP",
            "instType": "SWAP",
            "last": "29852.7",
            "lever": "5",
            "liqPx": "604.7617536513744",
            "markPx": "29849.7",
            "mgnMode": "cross",
            "mgnRatio": "217.71740878394456",
            "mmr": "41.78538",
            "notionalUsd": "10435.794191550001",
            "pTime": "1653536068723",
            "pos": "35",
            "posSide": "net",
            "uTime": "1653445498682",
            "upl": "232.83263888888962",
            "uplRatio": "0.1139826489932205"
        }]
    }
    

#### 推送数据参数

**参数名** | **类型** | **描述**  
---|---|---  
arg | Object | 订阅成功的频道  
> channel | String | 频道名  
> uid | String | 用户标识  
> algoId | String | 策略订单ID  
data | Array | 订阅的数据  
> algoId | String | 策略订单ID  
> instType | String | 产品类型  
> instId | String | 产品ID  
> cTime | String | 策略订单创建时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
> uTime | String | 策略订单更新时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
> avgPx | String | 开仓均价  
> ccy | String | 保证金币种  
> lever | String | 杠杆倍数  
> liqPx | String | 预估强平价  
> posSide | String | 持仓方向  
`net`：单向持仓  
> pos | String | 持仓数量  
> mgnMode | String | 保证金模式  
`cross`：全仓  
`isolated`：逐仓  
> mgnRatio | String | 保证金率  
> imr | String | 初始保证金  
> mmr | String | 维持保证金  
> upl | String | 未实现收益  
> uplRatio | String | 未实现收益率  
> last | String | 最新成交价  
> notionalUsd | String | 仓位美金价值  
> adl | String | 信号区  
分为5档，从1到5，数字越小代表adl强度越弱  
> markPx | String | 标记价格  
> pTime | String | 订单信息的推送时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
  
### 网格策略子订单频道

支持网格策略子订单的首次订阅推送，事件推送

> 请求示例
    
    
    {
        "op": "subscribe",
        "args": [{
            "channel": "grid-sub-orders",
            "algoId": "449327675342323712"
        }]
    }
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
op | String | 是 | 操作，`subscribe` `unsubscribe`  
args | Array | 是 | 请求订阅的频道列表  
> channel | String | 是 | 频道名，`grid-sub-orders`  
> algoId | String | 是 | 策略ID  
  
> 成功返回示例
    
    
    {
        "event": "subscribe",
        "arg": {
            "channel": "grid-sub-orders",
            "algoId": "449327675342323712"
        }
    }
    

> 失败返回示例
    
    
    {
        "event": "error",
        "code": "60012",
        "msg": "Invalid request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"grid-sub-orders\", \"instType\" : \"FUTURES\"}]}"
    }
    

#### 返回参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
event | String | 是 | 事件，`subscribe` `unsubscribe` `error`  
arg | Object | 否 | 订阅的频道  
> channel | String | 是 | 频道名  
> algoId | String | 是 | 策略ID  
code | String | 否 | 错误码  
msg | String | 否 | 错误消息  
  
> 推送示例
    
    
    {
        "arg": {
            "channel": "grid-sub-orders",
            "uid": "44705892343619584",
            "algoId": "449327675342323712"
        },
        "data": [{
            "accFillSz": "0",
            "algoId": "449327675342323712",
            "algoOrdType": "contract_grid",
            "avgPx": "0",
            "cTime": "1653445498664",
            "ctVal": "0.01",
            "fee": "0",1
            "feeCcy": "USDT",
            "groupId": "-1",
            "instId": "BTC-USDT-SWAP",
            "instType": "SWAP",
            "lever": "5",
            "ordId": "449518234142904321",
            "ordType": "limit",
            "pTime": "1653486524502",
            "pnl": "",
            "posSide": "net",
            "px": "28007.2",
            "side": "buy",
            "state": "live",
            "sz": "1",
            "tag":"",
            "tdMode": "cross",
            "uTime": "1653445498674"
        }]
    }
    

#### 推送数据参数

**参数名** | **类型** | **描述**  
---|---|---  
arg | Object | 订阅成功的频道  
> channel | String | 频道名  
> uid | String | 用户标识  
> algoId | String | 策略订单ID  
data | Array | 订阅的数据  
> algoId | String | 策略订单ID  
> instType | String | 产品类型  
> instId | String | 产品ID  
> algoOrdType | String | 策略订单类型  
`grid`：现货网格委托  
`contract_grid`：合约网格委托  
`moon_grid`：天地网格委托  
> groupId | String | 组ID  
> ordId | String | 子订单ID  
> cTime | String | 子订单创建时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
> uTime | String | 子订单更新时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
> tag | String | 订单标签  
> tdMode | String | 子订单交易模式  
`cross`：全仓 `isolated`：逐仓 `cash`：非保证金  
> ordType | String | 子订单类型  
`market`：市价单 `limit`：限价单  
> sz | String | 子订单委托数量  
> state | String | 子订单状态  
`canceled`：撤单成功 `live`：等待成交 `partially_filled`：部分成交 `filled`：完全成交
`cancelling`：撤单中  
> side | String | 子订单订单方向  
`buy`：买 `sell`：卖  
> px | String | 子订单委托价格  
> fee | String | 子订单手续费数量  
> feeCcy | String | 子订单手续费币种  
> avgPx | String | 子订单平均成交价格  
> accFillSz | String | 子订单累计成交数量  
> posSide | String | 子订单持仓方向  
`long`：双向持仓多头  
`short`：双向持仓空头  
`net`：单向持仓  
> pnl | String | 子订单收益  
> ctVal | String | 合约面值  
> lever | String | 杠杆倍数  
> pTime | String | 订单信息的推送时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
  
## 公共频道

### 产品频道

当有产品状态变化时（如期货交割、期权行权、新合约/币对上线、人工暂停/恢复交易等），推送产品的增量数据。  
(2022年12月28日起不再推送全量数据，[点此查看详情](/docs-v5/log_zh/#2022-12-06))；

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
        "msg": "Invalid request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"instruments\", \"instType\" : \"FUTURES\"}]}"
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
            "instFamily": "BTC-USD",
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
            "instFamily": "BTC-USD",
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
> category | String | 币种类别，注意：此参数已废弃  
> uly | String | 标的指数，如 `BTC-USD`，仅适用于`交割/永续/期权`  
> instFamily | String | 交易品种，如 `BTC-USD`，仅适用于`交割/永续/期权`  
> baseCcy | String | 交易货币币种，如 `BTC-USDT`中`BTC`，仅适用于`币币/币币杠杆`  
> quoteCcy | String | 计价货币币种，如 `BTC-USDT`中`USDT`，仅适用于`币币/币币杠杆`  
> settleCcy | String | 盈亏结算和保证金币种，如 `BTC`，仅适用于 `交割/永续/期权`  
> ctVal | String | 合约面值  
> ctMult | String | 合约乘数  
> ctValCcy | String | 合约面值计价币种  
> optType | String | 期权类型，`C`：看涨期权 `P`：看跌期权 ，仅适用于`期权`  
> stk | String | 行权价格，仅适用于`期权`  
> listTime | String | 上线日期，仅适用于 `交割/永续/期权`  
> expTime | String | 交割日期，仅适用于 `交割/期权`  
> lever | String | 该`instId`支持的最大杠杆倍数，不适用于`币币`、`期权`。可用来分辨`币币杠杆`和`币币`  
> tickSz | String | 下单价格精度，如 `0.0001`  
对于期权来说，是梯度中的最小下单价格精度。  
> lotSz | String | 下单数量精度，如 `1`：BTC-USDT-200925 `0.001`：BTC-USDT  
> minSz | String | 最小下单数,  
合约的数量单位是`“张”`，现货的数量单位是`“交易货币”`量  
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
`preopen`：预上线  
`test`：测试中（测试产品，不可交易）  
maxLmtSz | String | 合约或现货限价单的单笔最大委托数量,  
合约的数量单位是`“张”`，现货的数量单位是`“交易货币”`  
maxMktSz | String | 合约或现货市价单的单笔最大委托数量,  
合约的数量单位是`“张”`，现货的数量单位是`“USDT”`  
maxTwapSz | String | 合约或现货时间加权单的单笔最大委托数量,  
合约的数量单位是`“张”`，现货的数量单位是`“交易货币”`  
maxIcebergSz | String | 合约或现货冰山委托的单笔最大委托数量,  
合约的数量单位是`“张”`，现货的数量单位是`“交易货币”`  
maxTriggerSz | String | 合约或现货计划委托委托的单笔最大委托数量,  
合约的数量单位是`“张”`，现货的数量单位是`“交易货币”`  
maxStopSz | String | 合约或现货止盈止损市价委托的单笔最大委托数量,  
合约的数量单位是`“张”`，现货的数量单位是`“USDT”`  
产品状态变更，是触发instrument接口推送条件： 当合约预上线时，状态变更为预上线（即新生成一个合约，新合约会处于预上线状态）；
当产品下线的时候（如交割合约被交割的时候，期权合约被行权的时候），状态变更为已过期

### 行情频道

获取产品的最新成交价、买一价、卖一价和24小时交易量等信息。  
最快100ms推送一次，没有触发事件时不推送，触发推送的事件有：成交、买一卖一发生变动。

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
        "msg": "Invalid request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"tickers\", \"instId\" : \"LTC-USD-200327\"}]}"
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
            "instId": "LTC-USD-200327",
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
        "msg": "Invalid request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"open-interest\", \"instId\" : \"LTC-USD-SWAP\"}]}"
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

获取K线数据，推送频率最快是间隔1秒推送一次数据。

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
`candle3M` `candle1M`  
`candle1W`  
`candle1D` `candle2D` `candle3D` `candle5D`  
`candle12H` `candle6H` `candle4H` `candle2H` `candle1H`  
`candle30m` `candle15m` `candle5m` `candle3m` `candle1m`  
`candle3Mutc` `candle1Mutc` `candle1Wutc` `candle1Dutc` `candle2Dutc`
`candle3Dutc` `candle5Dutc` `candle12Hutc` `candle6Hutc`  
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
        "msg": "Invalid request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"candle1D\", \"instId\" : \"BTC-USD-191227\"}]}"
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
          "166741046.22583129",
          "166741046.22583129",
          "0"
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
> volCcyQuote | String | 交易量，以计价货币为单位  
如：BTC-USDT 和 BTC-USDT-SWAP, 单位均是 USDT；  
BTC-USD-SWAP 单位是 USD  
> confirm | String | K线状态  
`0` 代表 K 线未完结，`1` 代表 K 线已完结。  
  
### 交易频道

获取最近的成交数据，有成交数据就推送，每次推送仅包含一条成交数据。

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
        "msg": "Invalid request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"trades\", \"instId\" : \"BTC-USD-191227\"}]}"
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

获取永续合约，交割合约和期权预估交割/行权价。交割/行权预估价只有交割/行权前一小时开始推送预估交割/行权价，有价格变化就推送

> 请求示例
    
    
    {
        "op": "subscribe",
        "args": [{
            "channel": "estimated-price",
            "instType": "FUTURES",
            "instFamily": "BTC-USD"
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
`SWAP`：永续合约  
`OPTION`：期权  
> instFamily | String | 可选 | 交易品种  
`instFamily`和`instId`必须指定一个  
> instId | String | 可选 | 产品ID  
`instFamily`和`instId`必须指定一个  
  
> 成功返回示例
    
    
    {
        "event": "subscribe",
        "arg": {
            "channel": "estimated-price",
            "instType": "FUTURES",
            "instFamily": "BTC-USD"
        }
    }
    

> 失败返回示例
    
    
    {
        "event": "error",
        "code": "60012",
        "msg": "Invalid request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"estimated-price\", \"instId\" : \"FUTURES\",\"instFamily\" :\"BTC-USD\"}]}"
    }
    

#### 返回参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
event | String | 是 | 事件，`subscribe` `unsubscribe` `error`  
arg | Object | 否 | 订阅的频道  
> channel | String | 是 | 频道名  
> instType | String | 是 | 产品类型  
`FUTURES`：交割合约  
`SWAP`：永续合约  
`OPTION`：期权  
> instFamily | String | 否 | 交易品种  
> instId | String | 否 | 产品ID  
code | String | 否 | 错误码  
msg | String | 否 | 错误消息  
  
> 推送示例
    
    
    {
        "arg": {
            "channel": "estimated-price",
            "instType": "FUTURES",
            "instFamily": "BTC-USD"
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
`FUTURES`：交割合约  
`SWAP`：永续合约  
`OPTION`：期权  
> instFamily | String | 交易品种  
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
        "msg": "Invalid request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"mark-price\", \"instId\" : \"LTC-USD-190628\"}]}"
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

获取标记价格的K线数据，推送频率最快是间隔1秒推送一次数据。

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
        "msg": "Invalid request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"mark-price-candle1D\", \"instId\" : \"BTC-USD-190628\"}]}"
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
            ["1597026383085", "3.721", "3.743", "3.677", "3.708", "0"],
            ["1597026383085", "3.731", "3.799", "3.494", "3.72", "1"]
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
> confirm | String | K线状态  
`0` 代表 K 线未完结，`1` 代表 K 线已完结。  
  
### 限价频道

获取衍生品交易的最高买价和最低卖价。限价有变化时，每5秒推送一次数据，限价没变化时，不推送数据

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
仅适用于`交割`/`永续`/`期权`  
  
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
        "msg": "Invalid request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"price-limit\", \"instId\" : \"LTC-USD-190628\"}]}"
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

`books` 首次推400档快照数据，以后增量推送，每100毫秒推送一次变化的数据  
`books5`首次推5档快照数据，以后定量推送，每100毫秒当5档快照数据有变化推送一次5档数据  
`bbo-tbt` 首次推1档快照数据，以后定量推送，每10毫秒当1档快照数据有变化推送一次1档数据  
`books-l2-tbt` 首次推400档快照数据，以后增量推送，每10毫秒推送一次变化的数据  
`books50-l2-tbt` 首次推50档快照数据，以后增量推送，每10毫秒推送一次变化的数据

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
        "msg": "Invalid request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"books\", \"instId\" : \"BTC-USD-191227\"}]}"
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
> checksum | Integer | 检验和 （下方注解）  
asks和bids值数组举例说明： ["411.8", "10", "0", "4"]  
\- 411.8为深度价格  
\- 10为此价格的数量 （合约交易为合约，现货/币币杠杆为交易币的数量  
\- 0该字段已弃用(始终为0)  
\- 4为此价格的订单数量  如果需要订阅多个50或400档频道，建议通过多个链接进行订阅，每个链接低于30条频道。

#### Checksum机制

此机制可以帮助用户校验深度数据的准确性。

##### 深度合并

用户订阅增量推送（如：`books`400档）深度频道成功后，首先获取初始全量深度数据，当获取到增量推送数据后，更新本地全量深度数据。

  1. 如果有相同价格，则比较数量；数量为0删除此深度，数量有变化则替换此数据。
  2. 如果没有相同价格，则按照价格优劣排序（bid为价格降序，ask为价格升序），将深度信息插入到全量数据中

##### 计算校验和

先用深度合并后前25档bids和asks组成一个字符串（其中ask和bid中的价格和数量以冒号连接），再计算其crc32值（32位有符号整型）。

> 计算校验和
    
    
    1.bid和ask超过25档
    合并后全量深度数据（在此仅展示2档数据，实际应截取25档数据）：
    
    
    
    {
        "bids": [
            ["3366.1", "7", "0", "3"],
            ["3366", "6", "3", "4"]
        ],
        "asks": [
            ["3366.8", "9", "10", "3"],
            ["3368", "8", "3", "4"]
        ]
    }
    
    
    
    校验字符串：
    "3366.1:7:3366.8:9:3366:6:3368:8"
    
    2.bid或ask不足25档  
    合并后全量深度数据：
    
    
    
    {
        "bids": [
            ["3366.1", "7", "0", "3"]
        ],
        "asks": [
            ["3366.8", "9", "10", "3"],
            ["3368", "8", "3", "4"],
            ["3372", "8", "3", "4"]
        ]
    }
    
    
    
    校验字符串：
    "3366.1:7:3366.8:9:3368:8:3372:8"
    

  1. 当bid和ask深度数据超过25档时，截取各自25档数据，要校验的字符串按照bid、ask深度数据交替方式连接。  
如：`bid[价格:数量]`:`ask[价格:数量]`:`bid[价格:数量]`:`ask[价格:数量]`...  

  2. bid或ask深度数据不足25档时，直接忽略缺失的深度。  
如：`bid[价格:数量]`:`ask[价格:数量]`:`asks[价格:数量]`:`asks[价格:数量]`...

> bbo-tbt 频道推送示例
    
    
    {
      "arg": {
        "channel": "bbo-tbt",
        "instId": "BCH-USDT-SWAP"
      },
      "data": [
        {
          "asks": [
            [
              "111.06","55154","0","2"
            ]
          ],
          "bids": [
            [
              "111.05","57745","0","2"
            ]
          ],
          "ts": "1670324386802"
        }
      ]
    }
    

> books5 频道推送示例
    
    
    {
      "arg": {
        "channel": "books5",
        "instId": "BCH-USDT-SWAP"
      },
      "data": [
        {
          "asks": [
            ["111.06","55154","0","2"],
            ["111.07","53276","0","2"],
            ["111.08","72435","0","2"],
            ["111.09","70312","0","2"],
            ["111.1","67272","0","2"]],
          "bids": [
            ["111.05","57745","0","2"],
            ["111.04","57109","0","2"],
            ["111.03","69563","0","2"],
            ["111.02","71248","0","2"],
            ["111.01","65090","0","2"]],
          "instId": "BCH-USDT-SWAP",
          "ts": "1670324386802"
        }
      ]
    }
    

### 期权定价频道

获取所有期权合约详细定价信息，一次性推送所有

> 请求示例
    
    
    {
        "op": "subscribe",
        "args": [{
            "channel": "opt-summary",
            "instFamily": "BTC-USD"
        }]
    }
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
op | String | 是 | 操作，`subscribe` `unsubscribe`  
args | Array | 是 | 请求订阅的频道列表  
> channel | String | 是 | 频道名，`opt-summary`  
> instFamily | String | 是 | 交易品种  
  
> 返回示例
    
    
    {
        "event": "subscribe",
        "arg": {
            "channel": "opt-summary",
            "instFamily": "BTC-USD"
        }
    }
    

> 失败示例
    
    
    {
        "event": "error",
        "code": "60012",
        "msg": "Invalid request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"opt-summary\", \"instFamily\" : \"BTC-USD\"}]}"
    }
    

#### 返回参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
event | String | 是 | 事件，`subscribe` `unsubscribe` `error`  
arg | Object | 否 | 订阅的频道  
> channel | String | 是 | 频道名  
> instFamily | String | 是 | 交易品种  
code | String | 否 | 错误码  
msg | String | 否 | 错误消息  
  
> 推送示例
    
    
    {
        "arg": {
            "channel": "opt-summary",
            "instFamily": "BTC-USD"
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
> instFamily | String | 交易品种  
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
        "msg": "Invalid request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"funding-rate\", \"instId\" : \"BTC-USD-SWAP\"}]}"
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
        "data": [
            {
                "fundingRate": "0.0001515",
                "fundingTime": "1622822400000",
                "instId": "BTC-USD-SWAP",
                "instType": "SWAP",
                "nextFundingRate": "0.00029",
                "nextFundingTime": "1622851200000"
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
> instType | String | 产品类型，`SWAP`  
> instId | String | 产品ID，如 `BTC-USD-SWAP`  
> fundingRate | String | 资金费率  
> fundingTime | String | 最新的到期结算的资金费时间，Unix时间戳的毫秒数格式，如 `1597026383085`  
> nextFundingRate | String | 下一期预测资金费率  
> nextFundingTime | String | 下一期资金费时间，Unix时间戳的毫秒数格式，如 `1622851200000`  
  
### 指数K线频道

获取指数的K线数据，推送频率最快是间隔1秒推送一次数据。

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
        "msg": "Invalid request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"index-candle30m\", \"instId\" : \"BTC-USD\"}]}"
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
            ["1597026383085", "3811.31", "3811.31", "3811.31", "3811.31","0"]
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
> confirm | String | K线状态  
`0` 代表 K 线未完结，`1` 代表 K 线已完结。  
返回值数组顺分别为是：[ts,o,h,l,c,confirm]

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
> instId | String | 是 | 指数，以USD、USDT、BTC 为计价货币的指数，如 `BTC-USDT`  
  
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
        "msg": "Invalid request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"index-tickers\", \"instId\" : \"BTC-USDT\"}]}"
    }
    

#### 返回参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
event | String | 是 | `subscribe` `unsubscribe` `error`  
arg | Object | 否 | 订阅的频道  
> channel | String | 是 | 频道名，`index-tickers`  
> instId | String | 是 | 指数，以USD、USDT、BTC 为计价货币的指数，如 `BTC-USDT`  
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
> instId | String | 指数  
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
        "msg": "Invalid request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"statuss\"}]}"
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
        "data": [
            {
                "begin": "1672823400000",
                "end": "1672825980000",
                "href": "",
                "preOpenBegin": "",
                "scheDesc": "",
                "serviceType": "0",
                "state": "completed",
                "system": "unified",
                "title": "Trading account WebSocket system upgrade",
                "ts": "1672826038470"
            }
        ]
    }
    

#### 推送数据参数

参数名 | 类型 | 描述  
---|---|---  
arg | Object | 订阅成功的频道  
> channel | String | 频道名  
data | Array | 订阅的数据  
> title | String | 系统维护说明的标题  
> state | String | 系统的状态，`scheduled`:等待中 ; `ongoing`:进行中 ;
> `pre_open`:预开放；`completed`:已完成 `canceled`: 已取消  
当维护时间过长，会存在预开放时间，一般持续10分钟左右。  
> begin | String | 系统维护的开始时间,Unix时间戳的毫秒数格式 如：`1617788463867`  
> end | String | 交易全面开放的时间，Unix时间戳的毫秒数格式 如：`1617788463867`  
在维护完成前，是预期结束时间；维护完成后，会变更为实际结束时间。  
> preOpenBegin | String | 预开放开始的时间，开放撤单、Post Only 下单和资金转入功能的时间  
> href | String | 系统维护详情的超级链接,若无返回值，默认值为空，如：“”  
> serviceType | String | 服务类型， `0`：WebSocket ;
> `5`：交易服务；`6`：大宗交易；`7`：策略交易；`8`：交易服务 (按账户分批次)；`9`：交易服务
> (按产品分批次)；`99`：其他（如：停止部分产品交易）  
> system | String | 系统，`unified`：交易账户  
> scheDesc | String | 改期进度说明，如： `由 2021-01-26T16:30:00.000Z 改期到
> 2021-01-28T16:30:00.000Z`  
> ts | String | 推送时间，Unix时间戳的毫秒数格式，如：`1617788463867`  
  
### 期权公共成交频道

获取最近的期权成交数据，有成交数据就推送，每次推送仅包含一条成交数据。

> 请求示例
    
    
    {
        "op": "subscribe",
        "args": [{
            "channel": "option-trades",
            "instType": "OPTION",
            "instFamily": "BTC-USD"
        }]
    }
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
op | String | 是 | 操作，`subscribe` `unsubscribe`  
args | Array | 是 | 请求订阅的频道列表  
> channel | String | 是 | 频道名, `option-trades`  
> instType | String | 是 | 产品类型，`OPTION`：期权  
> instId | String | 可选 | 产品ID，如 BTC-USD-221230-4000-C，`instId` 和 `instFamily`
> 必须传一个，若传两个，以 `instId` 为主  
> instFamily | String | 可选 | 交易品种，如 BTC-USD  
  
> 成功返回示例
    
    
    {
        "event": "subscribe",
        "arg": {
            "channel": "option-trades",
            "instType": "OPTION",
            "instFamily": "BTC-USD"
        }
    }
    
    

> 失败返回示例
    
    
    {
        "event": "error",
        "code": "60012",
        "msg": "Invalid request: {\"op\": \"subscribe\", \"argss\":[{ \"channel\" : \"statuss\"}]}"
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
            "channel": "option-trades",
            "instType": "OPTION",
            "instFamily": "BTC-USD"
        },
        "data": [
            {
                "fillVol": "0.5066007836914062",
                "fwdPx": "16469.69928595038",
                "indexPx": "16537.2",
                "instFamily": "BTC-USD",
                "instId": "BTC-USD-230224-18000-C",
                "markPx": "0.04690107010619562",
                "optType": "C",
                "px": "0.045",
                "side": "sell",
                "sz": "2",
                "tradeId": "38",
                "ts": "1672286551080"
            }
        ]
    }
    

#### 推送数据参数

参数名 | 类型 | 描述  
---|---|---  
arg | Object | 订阅成功的频道  
> channel | String | 频道名  
data | Array | 订阅的数据  
> instId | String | 产品ID  
> instFamily | String | 交易品种  
> tradeId | String | 成交ID  
> px | String | 成交价格  
> sz | String | 成交数量  
> side | String | 成交方向  
`buy`：买  
`sell`：卖  
> optType | String | 期权类型，C：看涨期权 P：看跌期权 ，仅适用于期权  
> fillVol | String | 成交时的隐含波动率（对应成交价格）  
> fwdPx | String | 成交时的远期价格  
> indexPx | String | 成交时的指数价格  
> markPx | String | 成交时的标记价格  
> ts | String | 成交时间，Unix时间戳的毫秒数格式， 如`1597026383085`  
  
### 平台公共爆仓单频道

获取爆仓单信息。

> 请求示例
    
    
    {
      "op": "subscribe",
      "args": [
        {
          "channel": "liquidation-orders",
          "instType": "SWAP"
        }
      ]
    }
    

#### 请求参数

参数 | 类型 | 是否必须 | 描述  
---|---|---|---  
op | String | 是 | 操作，`subscribe` `unsubscribe`  
args | Array | 是 | 请求订阅的频道  
> channel | String | 是 | 频道名，`liquidation-orders`  
> instType | String | 是 | 产品类型  
`SWAP`：永续合约  
`FUTURES`：交割合约  
  
> 返回结果
    
    
    {
        "arg": {
            "channel": "liquidation-orders",
            "instType": "SWAP"
        },
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
                    }
                ],
                "instId": "BTC-USDT-SWAP",
                "instType": "SWAP",
                "uly": ""
            }
        ]
    }
    

#### 返回参数

**参数名** | **类型** | **描述**  
---|---|---  
arg | Object | 订阅成功的频道  
> channel | String | 频道名  
> instType | String | 产品类型  
data | Array | 订阅的数据  
> instType | String | 产品类型  
> instId | String | 产品ID，如 `BTC-USD-SWAP`  
> uly | String | 标的指数，仅适用于`交割/永续/期权`  
> details | Array | 详细内容  
>> side | String | 订单方向  
`buy`：买  
`sell`：卖  
>> posSide | String | 持仓方向  
`long`：多  
`short`：空  
`side`和`posSide`组合方式，sell/long：强平多 ; buy/short:强平空  
>> bkPx | String | 破产价格，与系统爆仓账号委托成交的价格。  
>> sz | String | 强平数量  
>> bkLoss | String | 穿仓亏损数量  
>> ccy | String | 强平币种，仅适用于`币币杠杆`  
>> ts | String | 强平发生的时间，Unix时间戳的毫秒数格式，如 `1597026383085` /  
  
# 错误码

## REST

REST API 错误码从 50000 到 59999

### 公共

错误码从 50000 到 53999

#### 通用类

错误码 | HTTP 状态码 | 错误提示  
---|---|---  
0 | 200 |  
1 | 200 | 操作全部失败  
2 | 200 | 批量操作部分成功  
50000 | 400 | POST请求的body不能为空  
50001 | 503 | 服务暂时不可用，请稍后重试  
50002 | 400 | JSON 语法错误  
50004 | 400 | 接口请求超时（不代表请求成功或者失败，请检查请求结果）  
50005 | 410 | 接口已下线或无法使用  
50006 | 400 | 无效的 Content-Type，请使用“application/JSON”格式  
50007 | 200 | 用户被冻结  
50008 | 200 | 用户不存在  
50009 | 200 | 用户处于爆仓冻结  
50010 | 200 | 用户ID为空  
50011 | 429 | 用户请求频率过快，超过该接口允许的限额。请参考 API 文档并限制请求  
50012 | 200 | 账户状态无效，请检查帐户的状态  
50013 | 429 | 当前系统繁忙，请稍后重试  
50014 | 400 | 必填参数{param0}不能为空  
50015 | 400 | 参数{param0}和{param1}不能同时为空  
50016 | 400 | 参数{param0}和{param1}不匹配  
50017 | 200 | 当前仓位处于自动减仓 (ADL) 冻结中，无法进行相关操作，请稍后重试  
50018 | 200 | {param0} 处于自动减仓 (ADL) 冻结中，无法进行相关操作，请稍后重试  
50019 | 200 | 当前账户处于自动减仓 (ADL) 冻结中，无法进行相关操作，请稍后重试  
50020 | 200 | 当前仓位处于强平冻结中，无法进行相关操作，请稍后重试  
50021 | 200 | {param0} 处于强平冻结中，无法进行相关操作，请稍后重试  
50022 | 200 | 当前账户处于强平冻结中，无法进行相关操作，请稍后重试  
50023 | 200 | 资金费冻结，无法进行相关操作，请稍后重试  
50024 | 200 | 参数{param0}和{param1}不能同时存在  
50025 | 200 | 参数{param0}传值个数超过最大限制{param1}  
50026 | 500 | 系统错误，请稍后重试  
50027 | 200 | 当前账户已被限制交易，请联系客服处理  
50028 | 200 | 账户异常无法下单  
50029 | 200 | 你的账户已经触发风控体系，禁止交易该标的，请检查您在欧易注册的电子邮件以便我们的客服联系  
50030 | 200 | 您没有使用此 API 接口的权限  
50032 | 200 | 您的账户已设置禁止该币种交易，请确认后重试  
50033 | 200 | 您的账户已设置禁止该业务线交易，请确认后重试  
50035 | 403 | 该接口要求APIKey必须绑定IP  
50036 | 200 | expTime必须是以毫秒为单位的Unix时间戳  
50037 | 200 | 订单已过期  
50038 | 200 | 该功能模拟盘暂不支持  
50039 | 200 | 时间戳分页时，不支持使用before参数  
50041 | 200 | 用户 ID 未被列入白名单列表，请联系客服  
50044 | 200 | 必须指定一种broker类型  
50047 | 200 | {param0} 已经交割，对应的K线请使用{param1}查询  
50049 | 200 | 无仓位档位信息，该币种不支持杠杆交易  
50050 | 200 | 您已开通期权交易服务，请勿重复开通  
  
#### API 类

错误码 | HTTP 状态码 | 错误提示  
---|---|---  
50100 | 400 | Api 已被冻结，请联系客服处理  
50101 | 401 | APIKey 与当前环境不匹配  
50102 | 401 | 请求时间戳过期  
50103 | 401 | 请求头"OK-ACCESS-KEY"不能为空  
50104 | 401 | 请求头"OK-ACCESS-PASSPHRASE"不能为空  
50105 | 401 | 请求头"OK-ACCESS-PASSPHRASE"错误  
50106 | 401 | 请求头"OK-ACCESS-SIGN"不能为空  
50107 | 401 | 请求头"OK-ACCESS-TIMESTAMP"不能为空  
50108 | 401 | 券商ID不存在  
50109 | 401 | 券商域名不存在  
50110 | 401 | 您的IP{param0}不在APIKey绑定IP名单中 (您可以将您的IP加入到APIKey绑定白名单中)  
50111 | 401 | 无效的OK-ACCESS-KEY  
50112 | 401 | 无效的OK-ACCESS-TIMESTAMP  
50113 | 401 | 无效的签名  
50114 | 401 | 无效的授权  
50115 | 405 | 无效的请求类型  
50116 | 200 | Fast API 只能创建一个 API key  
50117 | 200 | 只有 API 经纪商才可以通过 Fast API 功能创建 API key  
50118 | 200 | 如需将 API key 绑定 App，经纪商需要提供 IP 才能加入白名单  
  
#### 交易类

错误码 | HTTP 状态码 | 错误提示  
---|---|---  
51000 | 400 | {param0}参数错误  
51001 | 200 | 交易产品ID不存在  
51002 | 200 | 交易产品ID不匹配指数  
51003 | 200 | ordId或clOrdId至少填一个  
51004 | 200 | 委托数量超过用户当前档位，请调低杠杆  
51005 | 200 | 委托数量大于单笔上限  
51006 | 200 | 委托价格不在限价范围内（最高买入价：{param0}，最低卖出价：{param1}）  
51007 | 200 | 委托失败，委托数量不可小于 1 张  
51008 | 200 | 委托失败，账户 {param0} 可用余额不足  
51008 | 200 | 委托失败，账户 {param0} 可用保证金不足  
51008 | 200 | 委托失败，账户 {param0} 可用余额不足，且未开启自动借币  
51008 | 200 | 委托失败，账户 {param0} 可用保证金不足，且未开启自动借币  
51008 | 200 | 委托失败，因为 {param0} 剩余的档位限额不足，导致可借不足（需借：{1}， 剩余额度{2}，限额
{3}，已用额度{4}）  
51008 | 200 | 委托失败，因为 {param0} 剩余的母账户限额不足，导致可借不足（需借 {1}，剩余额度 {2}，限额 {3}，已用额度
{4}）  
51008 | 200 | 委托失败，因为 {param0} 剩余的币对限额不足，导致可借不足  
51008 | 200 | 委托失败，因为 {param0} 剩余的借贷池限额不足，导致可借不足  
51008 | 200 | 委托失败，账户资产不足，美金层面有效保证金小于 IMR  
51008 | 200 | 委托失败，delta 校验未通过，因为若成功下单，adjEq 的变化值将小于 IMR 的变化值。建议增加 adjEq 或减少
imr 占用  
51008 | 200 | 委托失败，账户余额不足  
51009 | 200 | 下单功能被冻结，请联系客服进行处理  
51010 | 200 | 当前账户模式不支持此操作  
51011 | 200 | ordId重复  
51012 | 200 | 币种不存在  
51014 | 200 | 指数不存在  
51015 | 200 | instId和instType不匹配  
51016 | 200 | clOrdId重复  
51017 | 200 | 杠杆委托交易借币超出限额  
51018 | 200 | 期权交易账户不能有净空头持仓  
51019 | 200 | 期权全仓不能有净多头持仓  
51020 | 200 | 委托数量必须超过单笔下限  
51021 | 200 | 合约待上线  
51022 | 200 | 合约暂停中  
51023 | 200 | 仓位不存在  
51024 | 200 | 交易账户冻结  
51025 | 200 | 委托笔数超限  
51026 | 200 | 交易产品类型不匹配指数（instType和uly不匹配）  
51027 | 200 | 合约已到期  
51028 | 200 | 合约交割中  
51029 | 200 | 合约结算中  
51030 | 200 | 资金费结算中  
51031 | 200 | 委托价格不在平仓限价范围内  
51032 | 200 | 市价全平中  
51033 | 200 | 币对单笔交易已达限额  
51037 | 200 | 当前账户风险状态，仅支持降低账户风险方向的IOC订单  
51038 | 200 | 当前风险模块下已经存在降低账户风险方向的IOC类型订单  
51039 | 200 | PM账户下交割和永续的全仓不能调整杠杆倍数  
51040 | 200 | 期权逐仓的买方不能调整保证金  
51041 | 200 | PM账户仅支持买卖模式  
51044 | 200 | 当前订单类型{param0}， {param1}不支持设置止盈和止损  
51046 | 200 | 止盈触发价格应该大于委托价格  
51047 | 200 | 止损触发价格应该小于委托价格  
51048 | 200 | 止盈触发价格应该小于委托价格  
51049 | 200 | 止损触发价格应该大于委托价格  
51050 | 200 | 止盈触发价格应该大于卖一价  
51051 | 200 | 止损触发价格应该小于卖一价  
51052 | 200 | 止盈触发价格应该小于买一价  
51053 | 200 | 止损触发价格应该大于买一价  
51054 | 500 | 请求超时，请稍候重试  
51055 | 200 | 组合保证金模式暂不支持合约网格  
51056 | 200 | 当前策略不支持该操作  
51057 | 200 | 简单交易模式下不可用合约网格  
51058 | 200 | 该策略无仓位  
51059 | 200 | 策略当前状态不支持此操作  
51065 | 200 | algoClOrdId 重复  
51101 | 200 | 超出单笔最大挂单张数  
51102 | 200 | 超出合约最大挂单数量  
51103 | 200 | 超出标的最大挂单数量  
51104 | 200 | 超出标的最大挂单张数  
51105 | 200 | 超出合约最大可开张数  
51106 | 200 | 超出标的最大可开张数  
51107 | 200 | 超出标的最大持仓张数  
51108 | 200 | 持仓量超过市价全平最大限制  
51109 | 200 | 订单深度中无买一卖一价  
51110 | 200 | 集合竞价开始后方可下限价单  
51111 | 200 | 批量下单时，超过最大单数{param0}  
51112 | 200 | 平仓张数大于该仓位的可平张数  
51113 | 429 | 市价全平操作过于频繁  
51115 | 200 | 市价全平前请先撤销所有平仓单  
51116 | 200 | 委托价格或触发价格超过{param0}  
51117 | 200 | 平仓单挂单单数超过限制  
51120 | 200 | 下单数量不足{param0}张  
51121 | 200 | 下单张数应为一手张数的倍数  
51122 | 200 | 委托价格小于最小值{param0}  
51124 | 200 | 价格发现期间您只可下限价单  
51125 | 200 | 当前杠杆存在非只减仓挂单，请撤销所有非只减仓挂单后进行只减仓挂单  
51126 | 200 | 当前杠杆存在只减仓挂单，请撤销所有只减仓挂单后进行非只减仓挂单  
51127 | 200 | 仓位可用余额为0  
51128 | 200 | 跨币种账户无法进行全仓杠杆交易  
51129 | 200 | 持仓及买入订单价值已达到持仓限额，不允许继续买入  
51130 | 200 | 逐仓杠杆保证金币种错误  
51131 | 200 | 仓位可用余额不足  
51132 | 200 | 仓位正资产小于最小交易单位  
51133 | 200 | 跨币种全仓币币不支持只减仓功能  
51134 | 200 | 平仓失败，请检查持仓和挂单  
51135 | 200 | 您的平仓价格已触发限价，最高买入价格为{param0}  
51136 | 200 | 您的平仓价格已触发限价，最低卖出价格为{param0}  
51137 | 200 | 您的开仓价格已触发限价，最高买入价格为{param0}  
51138 | 200 | 您的开仓价格已触发限价，最低卖出价格为{param0}  
51139 | 200 | 交易账户下币币不支持只减仓功能  
51143 | 200 | 您的询价失败，请稍后重试  
51145 | 200 | 逐仓自主划转保证金模式不支持提前挂单  
51147 | 200 | 交易期权需要在交易账户资产总价值大于2万美元的前提下，开通期权交易服务  
51148 | 200 | 操作失败，只减仓订单仅允许减少仓位数量，请先撤销或修改原有挂单后再进行下单或改单  
51149 | 500 | 下单超时，请稍候重试  
51150 | 200 | 交易数量或价格的精度超过限制  
51201 | 200 | 市价委托单笔价值不能超过 1,000,000 USDT  
51202 | 200 | 市价单下单数量超出最大值  
51203 | 200 | 普通委托数量超出最大限制{param0}  
51204 | 200 | 限价委托单价格不能为空  
51205 | 200 | 不支持只减仓操作  
51206 | 200 | 请先撤销当前下单产品{param0}的只减仓挂单，避免反向开仓  
51250 | 200 | 策略委托价格不在正确范围内  
51251 | 200 | 创建冰山委托时，策略委托类型错误  
51252 | 200 | 策略委托数量不在正确范围内  
51253 | 200 | 冰山委托单笔均值超限  
51254 | 200 | 冰山委托单笔均值错误  
51255 | 200 | 冰山委托单笔委托超限  
51256 | 200 | 冰山委托深度错误  
51257 | 200 | 跟踪委托回调服务错误，回调幅度限制为{min}<x<={max}%  
51258 | 200 | 跟踪委托失败，卖单激活价格需大于最新成交价格  
51259 | 200 | 跟踪委托失败，买单激活价格需小于最新成交价格  
51260 | 200 | 每个用户最多可同时持有{param0}笔未成交的跟踪委托  
51261 | 200 | 每个用户最多可同时持有{param0}笔未成交的止盈止损  
51262 | 200 | 每个用户最多可同时持有{param0}笔未成交的冰山委托  
51263 | 200 | 每个用户最多可同时持有{param0}笔未成交的时间加权单  
51264 | 200 | 时间加权单笔均值超限  
51265 | 200 | 时间加权单笔上限错误  
51267 | 200 | 时间加权扫单比例出错  
51268 | 200 | 时间加权扫单范围出错  
51269 | 200 | 时间加权委托间隔错误，应为{min}<=x<={max}  
51270 | 200 | 时间加权委托深度限制为 0<x<=1%  
51271 | 200 | 时间加权委托失败，扫单比例应该为 0<x<=100%  
51272 | 200 | 时间加权委托失败，扫单范围应该为 0<x<=1%  
51273 | 200 | 时间加权委托总量应为大于 0  
51274 | 200 | 时间加权委托总数量需大于单笔上限  
51275 | 200 | 止盈止损市价单笔委托数量不能超过最大限制  
51276 | 200 | 止盈止损市价单不能指定价格  
51277 | 200 | 止盈触发价格不能大于最新成交价  
51278 | 200 | 止损触发价格不能小于最新成交价  
51279 | 200 | 止盈触发价格不能小于最新成交价  
51280 | 200 | 止损触发价格不能大于最新成交价  
51281 | 200 | 计划委托不支持使用tgtCcy参数  
51282 | 200 | 吃单价优于盘口的比例范围  
51283 | 200 | 时间间隔的范围{param0}s~{param1}s  
51284 | 200 | 单笔数量的范围{param0}~{param1}  
51285 | 200 | 委托总量的范围{param0}~{param1}  
51286 | 200 | 下单金额需大于等于{param0}  
51287 | 200 | 当前策略不支持此交易品种  
51288 | 200 | 策略正在停止中，请勿重复点击  
51289 | 200 | 策略配置不存在，请稍后再试  
51290 | 200 | 策略引擎正在升级，请稍后重试  
51291 | 200 | 策略不存在或已停止  
51292 | 200 | 策略类型不存在  
51293 | 200 | 策略不存在  
51294 | 200 | 该策略暂不能创建，请稍后再试  
51295 | 200 | PM账户不支持ordType为{param0}的策略委托单  
51298 | 200 | 交割、永续合约的买卖模式下，不支持计划委托  
51299 | 200 | 策略委托失败，用户最多可持有{param0}笔该类型委托  
51300 | 200 | 止盈触发价格不能大于标记价格  
51302 | 200 | 止损触发价格不能小于标记价格  
51303 | 200 | 止盈触发价格不能小于标记价格  
51304 | 200 | 止损触发价格不能大于标记价格  
51305 | 200 | 止盈触发价格不能大于指数价格  
51306 | 200 | 止损触发价格不能小于指数价格  
51307 | 200 | 止盈触发价格不能小于指数价格  
51308 | 200 | 止损触发价格不能大于指数价格  
51309 | 200 | 集合竞价期间不能创建策略  
51310 | 200 | 逐仓自主划转保证金模式不支持ordType为iceberg、twap的策略委托单  
51311 | 200 | 移动止盈止损委托失败，回调幅度限制为{min}<x<={max}  
51312 | 200 | 移动止盈止损委托失败，委托数量范围{min}<x<={max}  
51313 | 200 | 逐仓自主划转模式不支持策略部分  
51317 | 200 | 币币杠杆不支持计划委托  
51327 | 200 | closeFraction 仅适用于交割合约和永续合约  
51328 | 200 | closeFraction 仅适用于只减仓订单  
51329 | 200 | closeFraction 仅适用于买卖模式  
51330 | 200 | closeFraction 仅适用于止盈止损市价订单  
51340 | 200 | 投入保证金需大于{0}{1}  
51341 | 200 | 当前策略状态下暂不支持平仓  
51342 | 200 | 已有平仓单，请稍后重试  
51343 | 200 | 止盈价格需小于区间最低价格  
51344 | 200 | 止损价格需大于区间最高价格  
51345 | 200 | 策略类型不是网格策略  
51346 | 200 | 最高价格不能低于最低价格  
51347 | 200 | 暂无可提取利润  
51348 | 200 | 止损价格需小于区间最低价格  
51349 | 200 | 止盈价格需大于区间最高价格  
51350 | 200 | 暂无可推荐参数  
51351 | 200 | 单格收益必须大于0  
51370 | 200 | 杠杆倍数范围{0}~{1}  
51400 | 200 | 撤单失败，订单不存在  
51401 | 200 | 撤单失败，订单已撤销  
51402 | 200 | 撤单失败，订单已完成  
51403 | 200 | 撤单失败，该委托类型无法进行撤单操作  
51404 | 200 | 价格发现第二阶段您不可撤单  
51405 | 200 | 撤单失败，您当前没有未成交的订单  
51406 | 400 | 撤单数量超过最大允许单数{param0}  
51407 | 200 | ordIds 和 clOrdIds 不能同时为空  
51408 | 200 | 币对 id 或币对名称与订单信息不匹配  
51409 | 200 | 币对 id 或币对名称不能同时为空  
51410 | 200 | 撤单失败，订单已处于撤销中  
51411 | 200 | 用户没有执行mass cancel的权限  
51412 | 200 | 撤单超时，请稍后重试  
51416 | 200 | 委托已触发，暂不支持撤单  
51413 | 200 | 撤单失败，接口不支持该委托类型的撤单  
51415 | 200 | 下单失败，现货交易仅支持设置最新价为触发价格，请更改触发价格并重试  
51500 | 200 | 价格和数量不能同时为空  
51501 | 400 | 修改订单超过最大允许单数{param0}  
51502 | 200 | 修改订单失败，用户保证金不足  
51503 | 200 | 修改订单失败，订单不存在  
51506 | 200 | 订单类型不支持改单  
51508 | 200 | 集合竞价第一阶段和第二阶段不允许改单  
51509 | 200 | 修改订单失败，订单已撤销  
51510 | 200 | 修改订单失败，订单已完成  
51511 | 200 | 操作失败，订单价格不满足Post Only条件  
51512 | 200 | 批量修改订单失败。同一批量改单请求中不允许包含相同订单。  
51513 | 200 | 对于正在处理的同一订单，改单请求次数不得超过3次  
51600 | 200 | 查询订单的状态不存在  
51601 | 200 | 订单状态和订单id不能同时存在  
51602 | 200 | 订单状态或订单id必须存在一个  
51603 | 200 | 查询订单不存在  
51607 | 200 | 文件正在生成中  
51156 | 200 | 您当前身份为带单交易员。在开平仓模式下，对于带单合约标的不支持使用该接口平仓  
51159 | 200 | 您当前身份为带单交易员，在买卖模式下，如需使用该接口下单，委托的方向必须与现有持仓和挂单保持一致  
51162 | 200 | 您当前有 {instrument} 挂单，请撤单后重试  
51163 | 200 | 您当前有 {instrument} 持仓，请平仓后重试  
51166 | 200 | 当前产品不支持带单  
51321 | 200 | 您正在带单。暂不支持使用套利、冰山或时间加权 (TWAP) 策略带单  
51322 | 200 | 您当前身份为带单交易员。您的带单合约持仓已经市价全平，系统已撤销止盈止损委托并进行平仓  
51323 | 200 | 您当前身份为带单交易员。您的带单合约仓位已设置止盈止损，请先撤销原有止盈止损订单  
51324 | 200 | 您当前身份为带单交易员，并持有 {instrument} 仓位。平仓委托张数需要与可平张数一致  
51325 | 200 | 您当前身份为带单交易员。下止盈止损单时，请选择市价作为委托价格  
51326 | 200 | 您当前身份为带单交易员，下止盈止损单时，委托价格类型必须为市价  
59128 | 200 | 您当前身份为带单交易员。您设置的带单合约 {instrument} 杠杆倍数不能超过 {num}×  
59216 | 200 | 仓位不存在，请稍后重试  
  
#### 数据类

错误码 | HTTP 状态码 | 错误提示  
---|---|---  
52000 | 200 | 没有最新行情信息  
  
### 金融

错误码从 51700 到 51799

错误码 | HTTP 状态码 | 错误提示  
---|---|---  
51720 | 200 | 赎回失败  
51721 | 200 | 取消赎回失败  
51722 | 200 | 赎回已到账  
51723 | 200 | 不支持提前赎回  
51724 | 200 | 当前状态不支持赎回  
51725 | 200 | 当前状态不支持取消  
51726 | 200 | 该项目不支持撤销申购/赎回  
51727 | 200 | 申购数量低于最小值  
51728 | 200 | 申购数量超过最大值  
51729 | 200 | 该项目尚未到期  
51730 | 200 | 该项目已售罄  
51731 | 200 | 产品现在暂停申购  
51732 | 200 | 用户KYC等级不符合要求  
51733 | 200 | 用户被风险管理中  
51734 | 200 | 不支持用户所属KYC国家  
51735 | 200 | 不支持子帐户  
51736 | 200 | {ccy} 余额不足  
  
### 闪兑

错误码从 52900 到 52999

错误码 | HTTP 状态码 | 错误提示  
---|---|---  
52900 | 200 | 无效请求  
52901 | 200 | 无效基准货币  
52902 | 200 | 无效标价货币  
52903 | 200 | 无效的报价数量  
52904 | 200 | 无效的报价方向  
52905 | 200 | 无效的报价  
52907 | 200 | 订单找不到  
52908 | 200 | 无效的订单ID  
52909 | 200 | 客户自定义ID重复使用  
52910 | 500 | 服务端暂时不可用，请稍后重试  
52911 | 500 | 询价服务不可用，请稍后重试  
52912 | 500 | 服务端超时  
52913 | 200 | 拒绝交易  
52915 | 200 | 询价量太大，流动性不足导致无法报价，请稍后重试  
52916 | 200 | 资金账户余额不足  
52917 | 200 | 询价数量不能低于下限  
52918 | 200 | 询价数量不能超过上限  
52919 | 200 | 闪兑交易参数{param}与报价不一致  
52920 | 200 | 闪兑交易数量不能超过报价数量  
52921 | 200 | 报价已交易，请重新询价  
52922 | 200 | 报价已过期，请重新询价  
52923 | 200 | 服务异常，请稍后重试  
52924 | 200 | 下单过于频繁，请稍后重试  
  
### 币币/币币杠杆类

错误码从 54000 到 54999

错误码 | HTTP 状态码 | 错误提示  
---|---|---  
54000 | 200 | 暂不支持币币杠杆业务  
54001 | 200 | 只有跨币种全仓账户才能设置自动借币  
  
### 交割合约类

错误码从 55000 到 55999

错误码 | HTTP 状态码 | 错误提示  
---|---|---  
55000 | 200 | 交割后30分钟内不能转出  
  
### 永续合约类

暂无

### 期权合约类

暂无

### 资金类

错误码从 58000 到 58999

错误码 | HTTP 状态码 | 错误提示  
---|---|---  
58002 | 200 | 请先开通余币宝服务  
58003 | 200 | 余币宝不支持该币种  
58004 | 200 | 账户冻结  
58005 | 200 | 申购/赎回额度不可超过{0}  
58006 | 200 | 币种{0}不支持当前操作  
58007 | 200 | 资金接口服务异常，请稍后再试。  
58008 | 200 | 您没有该币种资产  
58009 | 200 | 币对不存在  
58010 | 200 | 该链{0}暂不支持  
58011 | 200 | 抱歉，由于当地法律法规，欧易无法为{region}未认证用户提供服务，请先认证身份以继续使用欧易  
58012 | 200 | 抱歉，由于当地法律法规，欧易无法为{region}未认证用户提供服务，所以您无法向该用户转账  
58100 | 200 | 行权或结算中，暂无法转入或转出  
58101 | 200 | 划转冻结  
58102 | 429 | 已达到速率限制。请参考相应的 API 文档与节流请求  
58103 | 200 | 该账户划转功能暂不可用，详情请联系客服  
58104 | 200 | 您在法币区的交易异常，现已被限制划转功能，请您联系在线客服以解除限制  
58105 | 200 | 您在法币区的交易异常，现已被限制划转功能，请您在网页或APP进行法币划  
转操作以完成身份验证  
58107 | 200 | 请先开通交割合约账户  
58108 | 200 | 请先开通期权合约账户  
58109 | 200 | 请先开通永续合约账户  
58110 | 200 | 您所交易过或者持仓的产品触发市场风控，平台已暂停您的资金转出功能，请稍后重试。如需进一步的协助，请联系客服。  
58111 | 200 | 永续合约正在收取资金费，暂时无法做资金划转，请稍后重试  
58112 | 200 | 资金划转失败，请联系客服进行处理  
58114 | 400 | 转账金额必须大于 0  
58115 | 200 | 子账户不存在  
58116 | 200 | 转出数量大于最大可转数量  
58117 | 200 | 账户划转失败，请先处理负资产后再划转  
58119 | 200 | {0} 子账户没有转出权限，请先设置  
58120 | 200 | 划转服务暂不可用，请稍后重试  
58121 | 200 | 此次划转将导致您的仓位风险水平较高，进而可能引起爆仓。您需要重新调整划转金额，确保仓位处于安全水平后，再进行划转操作。  
58122 | 200 | 您的一部分现货正用于仓位间的 Delta
对冲，若划转数量超过可用金额，可能会影响现有的现货对冲结构，进而导致维持保证金率增加，请留意您的风险水平。  
58123 | 200 | 参数from与参数to不可相同  
58124 | 200 | 资金划转中，划转id：{trId}，请通过接口(GET /api/v5/asset/transfer-state)获取最新状态  
58125 | 200 | 不可交易资产仅支持子账户转主账户  
58126 | 200 | 不可交易资产划转，只能在资金账户间互转  
58127 | 200 | 主账户 API key 不支持当前 type 划转类型参数，请参考 API 文档描述  
58128 | 200 | 子账户 API key 不支持当前 type 划转类型参数，请参考 API 文档描述  
58129 | 200 | {param}错误或{param}与type不匹配  
58200 | 200 | 该币种暂不支持从{0}提现至{1}，敬请谅解  
58201 | 200 | 今日提现金额累计超过每日限额  
58202 | 200 | NEO最小提现数量为1，且提现数量必须为整数  
58203 | 200 | 请先添加提现地址  
58204 | 200 | 因您的账户活动触发风控，暂停提现。请联系客户支持寻求帮助。  
58205 | 200 | 提现金额大于单笔提现最大金额  
58206 | 200 | 提现金额小于单笔最小提现金额  
58207 | 200 | 提币地址不在免认证白名单内  
58208 | 200 | 提现失败，邮箱未绑定  
58209 | 200 | 子账户不能充值或提现，请在主账户中进行提现。  
58210 | 200 | 提现手续费大于最大值（提现接口，提现手续费输入有误）  
58211 | 200 | 提现手续费小于最小值（提现接口，手续费输入有误）  
58212 | 200 | 提现手续费应填写为提币数量的{0}%  
58213 | 200 | 内部转账地址不合法，必须是邮箱、手机号或者账户名  
58214 | 200 | {chainName}维护中，暂停提币  
58215 | 200 | 提币申请ID不存在  
58216 | 200 | 不允许执行该操作  
58217 | 200 | 您当前的提现地址存在风险，暂时不能提现，详情请联系客服  
58218 | 200 | 内部提现失败，请检查参数toAddr与areaCode  
58219 | 200 | 为保障您的资金安全，修改手机号/邮箱/谷歌验证后24小时之内将无法提现  
58220 | 200 | 提币请求已撤销  
58221 | 200 | toAddr参数格式有误，提币地址需要加上标签，格式应该为“地址:标签”  
58222 | 200 | 无效的提币地址  
58224 | 200 | 该类型币种暂不支持链上提币到 OKX 地址，请通过内部转账进行提币  
58226 | 200 | {chainName} 已下线，不支持提币  
58227 | 200 | 不可交易资产提币只能全部提出  
58228 | 200 | 不可交易资产提币要求 API key 必须绑定 IP  
58229 | 200 | 资金账户手续费不足 {fee} USDT  
58230 | 200 | 根据法规要求，您需要完成 Lv. 1 身份认证才能继续提币  
58231 | 200 | 根据法规要求，由于您的收款人尚未完成 Lv. 1 身份认证，交易无法完成  
58300 | 200 | 创建充值地址超过上限  
58301 | 200 | 充值地址不存在  
58302 | 200 | 充值地址需要标签  
58303 | 200 | 该链{chain}充值当前不可用  
58304 | 200 | 创建invoice失败  
58305 | 200 | 找不到充币地址，请完成身份认证并生成充币地址  
58306 | 200 | 您需要完成 Lv. 1 身份认证才能继续充币  
58350 | 200 | 您的余额不足  
58351 | 200 | invoice已经过期  
58352 | 200 | invoice无效  
58353 | 200 | 充币数量需要在限额范围内  
58354 | 200 | 单日达到生成invoice 10,000 个的上限  
58355 | 200 | 用户没有使用此API接口的权限，请联系您的客户经理  
58356 | 200 | 同节点账户不支持闪电网络充币或提币  
58358 | 200 | 参数fromCcy与参数toCcy不可相同  
58370 | 200 | 小额兑换功能每日使用次数超限  
58371 | 200 | 小额资产超过最大限制  
58372 | 200 | 小额资产不足  
  
### 账户类

错误码从 59000 到 59999

错误码 | HTTP 状态码 | 错误提示  
---|---|---  
59000 | 200 | 设置失败，请在设置前关闭任何挂单或持仓  
59001 | 200 | 当前存在借币，暂不可切换  
59002 | 200 | 子账户设置失败，请在设置前关闭任何子账户挂单、持仓或策略  
59004 | 200 | 只支持同一业务线下交易产品ID  
59005 | 200 | 逐仓自主划转保证金模式，初次划入仓位的资产价值需大于 10,000 USDT  
59100 | 200 | 杠杆倍数无法修改，请撤销所有挂单后进行杠杆倍数修改  
59101 | 200 | 杠杆倍数无法修改，请撤销所有逐仓挂单后进行杠杆倍数修改  
59102 | 200 | 杠杆倍数超过最大杠杆倍数，请降低杠杆倍数  
59103 | 200 | 杠杆倍数过低，账户中没有足够的可用保证金可以追加，请提高杠杆倍数  
59104 | 200 | 杠杆倍数过高，借币仓位已超过该杠杆倍数的最大仓位，请降低杠杆倍数  
59105 | 400 | 杠杆倍数设置不能小于{0}，请提高杠杆倍数  
59106 | 200 | 您下单后仓位总张数所处档位的最高可用杠杆为{0}，请重新调整  
59107 | 200 | 杠杆倍数无法修改，请撤销所有全仓挂单后修改杠杆倍数  
59108 | 200 | 杠杆倍数过低，账户中保证金不足，请提高杠杆倍数  
59109 | 200 | 调整后，账户权益小于所需保证金，请重新调整杠杆倍数  
59110 | 200 | 该{0}对应的产品业务线不支持使用tgtCcy参数  
59111 | 200 | PM账户下衍生品全仓不支持杠杆查询  
59112 | 200 | 当前存在逐仓/全仓挂单，请撤销所有逐仓挂单后进行杠杆倍数修改  
59113 | 200 | 根据当地法律法规，您所在的地区无法使用保证金交易相关服务，如果您不是该地区居民，请进行KYC2身份认证  
59200 | 200 | 账户余额不足  
59201 | 200 | 账户余额是负数  
59300 | 200 | 追加保证金失败，指定仓位不存在  
59301 | 200 | 调整保证金超过当前最大可调整数量  
59302 | 200 | 当前仓位存在平仓挂单，请撤销平仓挂单后进行保证金修改  
59303 | 200 | 可用保证金不足，请尝试增加保证金或减少借币数量  
59304 | 200 | 借币币种权益不足，请至少留有一天的利息  
59305 | 200 | 您当前没有进行尊享借币，无法设置尊享借币优先  
59306 | 200 | 借币数量超过总额度，不可继续借币  
59307 | 200 | 当前用户不满足尊享借币条件  
59308 | 200 | 市场化借币额度不足，VIP还币失败  
59309 | 200 | 还币数量超出已借数量，还币失败  
59310 | 200 | 当前账户不支持尊享借币  
59311 | 200 | 存在尊享借币，无法设置  
59312 | 200 | {币种}不支持尊享借币  
59313 | 200 | 无法还币。在一键借币模式下，您目前没有 ${ccy} 借币（币对：${ccyPair}）  
59314 | 200 | 当前用户该订单不是借币中，不允许还币  
59315 | 200 | VIP借币功能正在升级中,稍等10分钟之后再次操作  
59316 | 200 | 当前用户该币种存在借币申请中的订单，不允许借币  
59317 | 200 | 当前用户该币种的借币中的订单数量已经超过阈值  
51152 | 200 | 一键借币模式下，不支持自动借币与自动还币和手动类型混合下单。  
59401 | 200 | 持仓价值达到持仓限制  
59402 | 200 | 查询条件中的instId的交易产品当前不是可交易状态，请填写单个instid逐个查询状态详情  
59500 | 200 | 仅主账户有操作权限  
59501 | 200 | 每个账户最多可创建 50 个 API key  
59502 | 200 | 此备注名已存在。 请输入唯一的 API key 备注名称  
59503 | 200 | 每个 API key 最多可以绑定 20 个 IP 地址  
59504 | 200 | 子账户不支持提币功能，请在主账户中进行提币  
59505 | 200 | passphrase 格式不正确，支持6-32位字母和数字组合  
（区分大小写，不支持空格符号）  
59506 | 200 | API key 不存在  
59507 | 200 | 转出账户和转入账户必须是同一个母账户下的2个不同的子账户  
59508 | 200 | {0}该子账户被冻结  
59509 | 200 | 用户没有重置做市商保护状态的权限  
59510 | 200 | 子账户不存在  
59512 | 200 | 不支持为独立经纪商子账号设置主动转出权限，所有独立经纪商子账户默认有主动转出权限  
59601 | 200 | 子账户名称已存在  
59603 | 200 | 创建的子账户数量已达到上限  
59604 | 200 | 仅母账APIkey有操作此接口的权限  
59606 | 200 | 删除失败，请将子账户中的余额划转到母账户  
59608 | 200 | 仅Broker账户有操作此接口的权限  
59609 | 200 | 经纪商已经存在  
59610 | 200 | 经纪商不存在  
59611 | 200 | 经纪商状态是未审核  
59612 | 200 | 时间参数格式转换失败  
59613 | 200 | 当前未与子账户建立托管关系  
59614 | 200 | 托管子账户不支持此操作  
59615 | 200 | 起始日期和结束日期的时间间隔不能超过180天。  
59616 | 200 | 起始日期不能大于结束日期  
59617 | 200 | 子账户创建成功，账户等级设置失败  
59618 | 200 | 创建子账户失败  
  
### 大宗交易

错误码从 70000 开始

错误码 | HTTP 状态码 | 错误提示  
---|---|---  
70000 | 200 | 询价单不存在  
70001 | 200 | 报价单不存在  
70002 | 200 | 大宗交易不存在  
70003 | 200 | 公共的大宗交易不存在  
70004 | 200 | 无效的产品ID {instId}  
70005 | 200 | 组合交易的数量不能超过最大值  
70006 | 200 | 不满足最小资产要求  
70007 | 200 | 该产品类型 {instFamily} 的标的指数 {instType} 不存在  
70008 | 200 | MMP状态下操作失败。冻结时间为 {second} 秒  
70009 | 200 | Data数组必须至少含有一个有效元素  
70010 | 200 | 时间戳参数必须是Unix时间戳的毫秒格式  
70011 | 200 | 产品类型 {instType} 存在重复设置  
70012 | 200 | 同一个instType{instType}下的instFamily/instId{instId} 存在重复设置  
70013 | 200 | endTs必须大于等于beginTs  
70014 | 200 | 不允许对所有产品类别设置includeAll=True.  
70015 | 200 | 大宗交易仅适用于通过欧易完成身份认证 2 级或以上的用户  
70016 | 200 | 交易产品设置中需选择至少一个交易品种  
70100 | 200 | 组合交易中的产品ID重复  
70101 | 200 | clRfqId重复  
70102 | 200 | 未指定对手方  
70103 | 200 | 无效的对手方  
70105 | 200 | 非全现货的RFQ总价值应该大于最小名义值{nonSpotMinNotional}  
70106 | 200 | 下单数量小于最小交易数量  
70107 | 200 | 对手方的数量不能超过最大值  
70108 | 200 | 全现货的RFQ总价值应该大于最小名义值{spotMinNotional}  
70109 | 200 | 所选产品无有效对手方  
70200 | 200 | 不能取消处于{rfqState}状态的询价单  
70203 | 200 | 取消失败，由于询价单数量超过限制数量{rfqLimit}  
70207 | 200 | 取消失败，由于您没有询价挂单  
70208 | 200 | 取消失败，由于服务暂时不可用，请稍后重试  
70301 | 200 | clQuoteId重复  
70303 | 200 | 不能对处于{rfqState}状态的询价单报价  
70304 | 200 | 价格应该是下单价格精度的整数倍  
70305 | 200 | 买入价格不能高于报价  
70306 | 200 | 报价的组合交易没有匹配{rfqId}的组合交易  
70307 | 200 | 数量应该是下单数量精度的整数倍  
70308 | 200 | 不允许对自己的询价单报价  
70309 | 200 | 不允许对相同询价单进行同一方向的报价  
70310 | 200 | instId {instId} 报价不可以超过你预设的价格限制  
70400 | 200 | 不能取消处于{quoteState}状态的报价单  
70408 | 200 | 取消失败，由于报价单数量超过限制数量{quoteLimit}  
70409 | 200 | 取消失败，由于您没有报价挂单  
70501 | 200 | 询价单{rfqId}没有被{quoteId}报价  
70502 | 200 | 组合交易没有匹配{rfqId}的组合交易  
70503 | 200 | 执行腿的价值总和小于大宗交易的最小名义值  
70504 | 200 | 执行失败，因为询价单的状态是{rfqState}  
70505 | 200 | 执行失败，因为报价单的状态是{quoteState}  
70506 | 200 | 腿的数量比例与原RFQ不一致  
70507 | 200 | 部分执行尝试失败。须设置allowPartialExecution为`true`  
70508 | 200 | 没有可用的产品设置。  
70509 | 200 | 交易执行失败：对手方相关错误  
70511 | 200 | 正在执行报价  
56000 | 200 | 大宗交易不存在  
56001 | 200 | 多腿的数量不能超过 {legLimit}  
56002 | 200 | 执行和验证的多腿数量不匹配  
56003 | 200 | 重复的clBlockTdId  
56004 | 200 | 不允许自成交  
56005 | 200 | 执行和验证的clBlockTdId 不匹配  
56006 | 200 | 执行和验证的角色不能相同  
56007 | 200 | 执行和验证的第{legNo}条腿不匹配  
56008 | 200 | 重复的产品名称  
  
## WebSocket

### 公共

错误码从 60000 到 63999

#### 通用类

错误码 | 错误消息  
---|---  
60001 | "OK-ACCESS-KEY"不能为空  
60002 | "OK-ACCESS-SIGN"不能为空  
60003 | "OK-ACCESS-PASSPHRASE"不能为空  
60004 | 无效的 OK-ACCESS-TIMESTAMP  
60005 | 无效的 OK-ACCESS-KEY  
60006 | 请求时间戳过期  
60007 | 无效的签名  
60008 | 当前服务不支持订阅{0}频道，请检查WebSocket地址  
60009 | 登录失败  
60011 | 用户需要登录  
60012 | 不合法的请求  
60013 | 无效的参数 args  
60014 | 用户请求频率过快，超过该接口允许的限额  
60015 | 30秒内没有数据通讯，连接关闭  
60016 | 缓冲区无法写入数据，连接关闭  
60017 | 无效的url path  
60018 | 频道不存在  
60019 | 无效的op{0}  
60020 | 超出最大允许订阅的APIKey数量{0}  
60021 | 该功能不支持多账户登录使用  
60022 | 批量登录部分成功  
60023 | 批量登录请求过于频繁  
60024 | passphrase不正确  
60025 | 超出最大允许订阅的token数量{0}  
60026 | 不支持APIKey和token同时登录  
60027 | 参数{0}不可为空  
60028 | 当前服务不支持交易功能，请检查WebSocket地址  
60029 | books-l2-tbt深度频道仅支持手续费等级为VIP5及以上的用户订阅使用  
60030 | books50-l2-tbt深度频道仅支持手续费等级为VIP4及以上的用户订阅使用  
63999 | 内部系统错误  
  
#### 关闭帧

状态码 | 文案  
---|---  
1009 | 用户订阅请求过大  
4001 | 登录失败  
4002 | 参数不合法  
4003 | 登录账户多于100个  
4004 | 空闲超时30秒  
4005 | 写缓冲区满  
4006 | 异常场景关闭

