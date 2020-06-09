[![](../static/img/logo.png?_st=20200609152346)](/)

  * [ 入门指引 ](./#README)
  * [ 做市商项目 ](./#market)
  * [ 新手教程 ](./#vedio)
  * [ 更新日志 ](./#change-change)
    * [ 2020-06-01 ](./#change-20200630)
    * [ 2020-05-15 ](./#change-20200531)
    * [ 2020-04-22 ](./#change-20200430)
    * [ 2020-03-30 ](./#change-20200331)
    * [ 2020-02-29 ](./#change-20200229)
    * [ 2019-12-31 ](./#change-20191210)
    * [ 2019-11-30 ](./#change-20191130)
    * [ 2019-10-31 ](./#change-20191031)
    * [ 2019-09-30 ](./#change-20190930)
    * [ 2019-08-31 ](./#change-20190831)
    * [ 2019-07-31 ](./#change-20190731)
    * [ 2019-06-30 ](./#change-20190630)
    * [ 2019-05-31 ](./#change-20190531)
    * [ 关于V1 API 支持交割合约梯度保证金优化 ](./#change-20190515)
    * [ 2019-05-15 ](./#change-20190516)
    * [ 2019-04-28 ](./#change-20190428)
    * [ 2019-04-26 ](./#change-20190426)
    * [ 2019-04-24 ](./#change-20190424)
    * [ 2019-04-12 ](./#change-20190412)
    * [ 2019-03-27 ](./#change-20190327)
    * [ 2019-01-21 ](./#change-20190121)
  * [ 常见问题 ](./#question-README)
    * [ APIKey问题 ](./#question-apikey)
    * [ 验签问题 ](./#question-verify)
    * [ 域名问题 ](./#question-url)
    * [ 限速问题 ](./#question-limit)
    * [ 账户问题 ](./#question-account)
    * [ 公共问题 ](./#question-public)
    * [ 接口功能问题 ](./#question-endpoint)
    * [ 币币/杠杆问题 ](./#question-spot_margin)
    * [ 合约问题 ](./#question-contract)
  * [ API概述 ](./#summary-README)
    * [ 账户体系 ](./#summary-doc)
    * [ 业务字典 ](./#summary-product)
    * [ 撮合引擎 ](./#summary-match)
    * [ 费用 ](./#summary-fees)
    * [ 服务器 ](./#summary-servers)
    * [ 请求 ](./#summary-requests)
    * [ 分页 ](./#summary-pages)
    * [ 标准规范 ](./#summary-rules)
    * [ 接口类型 ](./#summary-ports)
    * [ 访问限制 ](./#summary-limit)
    * [ 验证 ](./#summary-yan-zheng)
    * [ 测试环境 ](./#summary-testnet)
  * [ 资金账户API ](./#account-README)
    * [ 资金账户信息 ](./#account-information)
    * [ 单一币种账户信息 ](./#account-singleness)
    * [ 资金划转 ](./#account-transfer)
    * [ 提币 ](./#account-extract)
    * [ 账单流水查询 ](./#account-query)
    * [ 获取充值地址 ](./#account-deposit-address)
    * [ 获取账户资产估值 ](./#account-asset-valuation)
    * [ 获取子账户余额信息 ](./#account-sub-account)
    * [ 查询所有币种的提币记录 ](./#account-all-withdrawal-history)
    * [ 查询单个币种提币记录 ](./#account-Single-withdrawal-history)
    * [ 获取所有币种充值记录 ](./#account-all-deposit-history)
    * [ 获取单个币种充值记录 ](./#account-single-deposit-history)
    * [ 获取币种列表 ](./#account-currencies)
    * [ 提币手续费 ](./#account-charge)
  * [ 币币API ](./#spot-README)
    * [ 币币账户信息 ](./#spot-account_information)
    * [ 单一币种账户信息 ](./#spot-singleness)
    * [ 账单流水查询 ](./#spot-query)
    * [ 下单 ](./#spot-orders)
    * [ 批量下单 ](./#spot-batch)
    * [ 撤销指定订单 ](./#spot-revocation)
    * [ 批量撤销订单 ](./#spot-repeal)
    * [ 获取订单列表 ](./#spot-list)
    * [ 获取所有未成交订单 ](./#spot-orders_pending)
    * [ 获取订单信息 ](./#spot-order_information)
    * [ 获取成交明细 ](./#spot-detail)
    * [ 委托策略下单 ](./#spot-algo_order)
    * [ 委托策略撤单 ](./#spot-algo_cancel_order)
    * [ 获取当前账户费率 ](./#spot-trade_fee)
    * [ 获取委托单列表 ](./#spot-algo_list)
    * [ 公共-获取币对信息 ](./#spot-currency)
    * [ 公共-获取深度数据 ](./#spot-data)
    * [ 公共-获取全部ticker信息 ](./#spot-all)
    * [ 公共-获取某个ticker信息 ](./#spot-some)
    * [ 公共-获取成交数据 ](./#spot-deal_information)
    * [ 公共-获取K线数据 ](./#spot-line)
  * [ 币币杠杆API ](./#spot_leverage-README)
    * [ 币币杠杆账户信息 ](./#spot_leverage-account_information)
    * [ 单一币对账户信息 ](./#spot_leverage-singleness)
    * [ 账单流水查询 ](./#spot_leverage-query)
    * [ 杠杆配置信息 ](./#spot_leverage-configuration_information)
    * [ 某个杠杆配置信息 ](./#spot_leverage-some_information)
    * [ 获取借币记录 ](./#spot_leverage-record)
    * [ 某币对借币记录 ](./#spot_leverage-some_record)
    * [ 借币 ](./#spot_leverage-borrow)
    * [ 还币 ](./#spot_leverage-repay)
    * [ 下单 ](./#spot_leverage-orders)
    * [ 批量下单 ](./#spot_leverage-batch)
    * [ 撤销指定订单 ](./#spot_leverage-revocation)
    * [ 批量撤销订单 ](./#spot_leverage-repeal)
    * [ 获取订单列表 ](./#spot_leverage-list)
    * [ 获取订单信息 ](./#spot_leverage-order_information)
    * [ 获取所有未成交订单 ](./#spot_leverage-orders_pending)
    * [ 获取成交明细 ](./#spot_leverage-detail)
    * [ 获取杠杆倍数 ](./#spot_leverage-get_leverage)
    * [ 设置杠杆倍数 ](./#spot_leverage-set_leverage)
    * [ 公共-币币杠杆行情 ](./#spot_leverage-market)
    * [ 公共-获取标记价格 ](./#spot_leverage-markprice)
  * [ 交割合约API ](./#futures-README)
    * [ 所有合约持仓信息 ](./#futures-hold_information)
    * [ 单个合约持仓信息 ](./#futures-only)
    * [ 所有币种合约账户信息 ](./#futures-singleness)
    * [ 单个币种合约账户信息 ](./#futures-singleness-single)
    * [ 获取合约币种杠杆倍数 ](./#futures-leverage)
    * [ 设定合约币种杠杆倍数 ](./#futures-set_leverage)
    * [ 账单流水查询 ](./#futures-query)
    * [ 下单 ](./#futures-orders)
    * [ 批量下单 ](./#futures-batch)
    * [ 撤销指定订单 ](./#futures-revocation)
    * [ 批量撤销订单 ](./#futures-repeal)
    * [ 获取订单列表 ](./#futures-list)
    * [ 获取订单信息 ](./#futures-order_information)
    * [ 获取成交明细 ](./#futures-futuresdetail)
    * [ 设置合约币种账户模式 ](./#futures-margin_mode)
    * [ 市价全平 ](./#futures-close_all)
    * [ 撤销所有平仓挂单 ](./#futures-cancel_all)
    * [ 获取合约挂单冻结数量 ](./#futures-hold_amount)
    * [ 委托策略下单 ](./#futures-algo_order)
    * [ 委托策略撤单 ](./#futures-algo_cancel_order)
    * [ 获取委托单列表 ](./#futures-algo_list)
    * [ 获取当前手续费费率 ](./#futures-trade_fee)
    * [ 增加/减少保证金 ](./#futures-margin)
    * [ 设置逐仓自动增加保证金 ](./#futures-auto_margin)
    * [ 公共-获取合约信息 ](./#futures-contract_information)
    * [ 公共-获取深度数据 ](./#futures-data)
    * [ 公共-获取全部ticker信息 ](./#futures-all)
    * [ 公共-获取某个ticker信息 ](./#futures-some)
    * [ 公共-获取成交数据 ](./#futures-deal_data)
    * [ 公共-获取K线数据 ](./#futures-line)
    * [ 公共-获取指数信息 ](./#futures-index_information)
    * [ 公共-获取法币汇率 ](./#futures-rate)
    * [ 公共-获取预估交割价 ](./#futures-price)
    * [ 公共-获取平台总持仓量 ](./#futures-total)
    * [ 公共-获取当前限价 ](./#futures-current)
    * [ 公共-获取标记价格 ](./#futures-markprice)
    * [ 公共-获取强平单 ](./#futures-get-liquidation)
    * [ 公共-获取历史结算/交割记录 ](./#futures-settlement_history)
  * [ 永续合约API ](./#swap-README)
    * [ 所有合约持仓信息 ](./#swap-swap---hold_information)
    * [ 单个合约持仓信息 ](./#swap-swap---only)
    * [ 所有币种合约账户信息 ](./#swap-swap---singleness)
    * [ 单个币种合约账户信息 ](./#swap-swap---singleness-single)
    * [ 获取某个合约的用户配置 ](./#swap-swap---settings)
    * [ 设定某个合约的杠杆 ](./#swap-swap---leverage)
    * [ 账单流水查询 ](./#swap-swap---query)
    * [ 下单 ](./#swap-swap---orders)
    * [ 批量下单 ](./#swap-swap---batch)
    * [ 撤单 ](./#swap-swap---revocation)
    * [ 批量撤单 ](./#swap-swap---repeal)
    * [ 获取所有订单列表 ](./#swap-swap---list)
    * [ 获取订单信息 ](./#swap-swap---order_information)
    * [ 获取成交明细 ](./#swap-swap---futuresdetail)
    * [ 获取合约挂单冻结数量 ](./#swap-swap---hold_amount)
    * [ 委托策略下单 ](./#swap-swap---algo_order)
    * [ 委托策略撤单 ](./#swap-swap---algo_cancel_order)
    * [ 获取委托单列表 ](./#swap-swap---algo_list)
    * [ 获取账户手续费费率 ](./#swap-swap---trade_fee)
    * [ 市价全平 ](./#swap-swap---close_all)
    * [ 撤销所有平仓挂单 ](./#swap-swap---cancel_all)
    * [ 公共-获取合约信息 ](./#swap-swap---contract_information)
    * [ 公共-获取深度数据 ](./#swap-swap---data)
    * [ 公共-获取全部ticker信息 ](./#swap-swap---all)
    * [ 公共-获取某个ticker信息 ](./#swap-swap---some)
    * [ 公共-获取成交数据 ](./#swap-swap---deal_data)
    * [ 公共-获取K线数据 ](./#swap-swap---line)
    * [ 公共-获取指数信息 ](./#swap-swap---index_information)
    * [ 公共-获取法币汇率 ](./#swap-swap---rate)
    * [ 公共-获取平台总持仓量 ](./#swap-swap---total)
    * [ 公共-获取当前限价 ](./#swap-swap---current)
    * [ 公共-获取强平单 ](./#swap-swap---liquidation)
    * [ 公共-获取合约资金费率 ](./#swap-swap---funding_time)
    * [ 公共-获取合约标记价格 ](./#swap-swap---markprice)
    * [ 公共-获取合约历史资金费率 ](./#swap-swap---funding_rate)
  * [ 期权合约API ](./#option-README)
    * [ 单个标的指数持仓信息 ](./#option-option---position)
    * [ 单个标的物账户信息 ](./#option-option---account_underlying)
    * [ 下单 ](./#option-option---order)
    * [ 批量下单 ](./#option-option---orders)
    * [ 撤单 ](./#option-option---cancel)
    * [ 批量撤单 ](./#option-option---cancel_batch)
    * [ 修改订单 ](./#option-option---amend)
    * [ 批量修改订单 ](./#option-option---amend_batch)
    * [ 获取单个订单状态 ](./#option-option---order_information)
    * [ 获取订单列表 ](./#option-option---order_list)
    * [ 获取成交明细 ](./#option-option---fills)
    * [ 获取账单流水 ](./#option-option---ledger)
    * [ 获取手续费费率 ](./#option-option---trade_fee)
    * [ 公共-获取标的指数 ](./#option-option---underlying)
    * [ 公共-获取期权合约 ](./#option-option---instrument)
    * [ 公共-获取期权合约详细定价 ](./#option-option---instrument_summary)
    * [ 公共-获取单个期权合约详细定价 ](./#option-option---instrument_summary_byins)
    * [ 公共-获取深度数据 ](./#option-option---book)
    * [ 公共-获取成交数据 ](./#option-option---deal_data)
    * [ 公共-获取某个Ticker信息 ](./#option-option---ticker)
    * [ 公共-获取K线数据 ](./#option-option---line)
  * [ 指数 API ](./#index-restful-README)
    * [ 公共-获取指数成分 ](./#index-restful-content)
  * [ 获取系统升级状态 ](./#status-readme)
    * [ 公共-获取系统升级状态 ](./#status-status)
  * [ RestAPI 错误码 ](./#error-Error_Code)
    * [ 公共错误码 ](./#error-public)
    * [ 资金账户错误码 ](./#error-account)
    * [ 币币和杠杆错误码 ](./#error-spot)
    * [ 交割合约错误码 ](./#error-futures)
    * [ 永续错误码 ](./#error-swap)
    * [ 期权合约错误码 ](./#error-option)
  * [ WebSocketAPI ](./#swap_ws-README)
    * [ 现货 ](./#spot_ws-all)
      * [ 概述 ](./#spot_ws-general)
      * [ 指令格式 ](./#spot_ws-format)
      * [ 订阅 ](./#spot_ws-sub)
      * [ 取消订阅 ](./#spot_ws-unsub)
      * [ 登录 ](./#spot_ws-login)
      * [ 连接限制 ](./#spot_ws-limit)
      * [ 校验和机制 ](./#spot_ws-checksum)
      * [ 频道说明 ](./#spot_ws-channel)
      * [ 用户币币账户频道 ](./#spot_ws-account)
      * [ 用户杠杆账户频道 ](./#spot_ws-depress)
      * [ 用户委托策略频道 ](./#spot_ws-algo_order)
      * [ 用户交易频道 ](./#spot_ws-order)
      * [ 公共-Ticker频道 ](./#spot_ws-ticker)
      * [ 公共-K线频道 ](./#spot_ws-candel)
      * [ 公共-交易频道 ](./#spot_ws-trade)
      * [ 公共-5档深度频道 ](./#spot_ws-depth5)
      * [ 公共-400档深度频道 ](./#spot_ws-depth)
      * [ 公共-400档增量数据频道 ](./#spot_ws-full_depth)
    * [ 交割合约 ](./#futures_ws-all)
      * [ 概述 ](./#futures_ws-general)
      * [ 指令格式 ](./#futures_ws-format)
      * [ 订阅 ](./#futures_ws-sub)
      * [ 取消订阅 ](./#futures_ws-unsub)
      * [ 登录 ](./#futures_ws-login)
      * [ 连接限制 ](./#futures_ws-limit)
      * [ 校验和机制 ](./#futures_ws-checksum)
      * [ 频道说明 ](./#futures_ws-channel)
      * [ 用户持仓频道 ](./#futures_ws-position)
      * [ 用户账户频道 ](./#futures_ws-account)
      * [ 用户交易频道 ](./#futures_ws-order)
      * [ 用户委托策略频道 ](./#futures_ws-algo_order)
      * [ 公共-全量合约信息频道 ](./#futures_ws-contract)
      * [ 公共-Ticker频道 ](./#futures_ws-ticker)
      * [ 公共-K线频道 ](./#futures_ws-candel)
      * [ 公共-交易频道 ](./#futures_ws-trade)
      * [ 公共-预估交割价频道 ](./#futures_ws-forcast)
      * [ 公共-限价频道 ](./#futures_ws-range)
      * [ 公共-5档深度频道 ](./#futures_ws-depth5)
      * [ 公共-400档深度频道 ](./#futures_ws-depth)
      * [ 公共-400档增量数据频道 ](./#futures_ws-full_depth)
      * [ 公共-标记价格频道 ](./#futures_ws-mark)
    * [ 永续合约 ](./#swap_ws-all)
      * [ 概述 ](./#swap_ws-general)
      * [ 指令格式 ](./#swap_ws-format)
      * [ 订阅 ](./#swap_ws-sub)
      * [ 取消订阅 ](./#swap_ws-unsub)
      * [ 登录 ](./#swap_ws-login)
      * [ 连接限制 ](./#swap_ws-limit)
      * [ 校验和机制 ](./#swap_ws-checksum)
      * [ 频道说明 ](./#swap_ws-channel)
      * [ 用户持仓频道 ](./#swap_ws-position)
      * [ 用户账户频道 ](./#swap_ws-account)
      * [ 用户交易频道 ](./#swap_ws-order)
      * [ 用户委托策略频道 ](./#swap_ws-algo_order)
      * [ 公共-Ticker频道 ](./#swap_ws-ticker)
      * [ 公共-K线频道 ](./#swap_ws-candel)
      * [ 公共-交易频道 ](./#swap_ws-trade)
      * [ 公共-资金费率频道 ](./#swap_ws-rate)
      * [ 公共-限价频道 ](./#swap_ws-range)
      * [ 公共-5档深度频道 ](./#swap_ws-depth5)
      * [ 公共-400档深度频道 ](./#swap_ws-depth)
      * [ 公共-400档增量数据频道 ](./#swap_ws-full_depth)
      * [ 公共-标记价格频道 ](./#swap_ws-mark)
    * [ 期权合约 ](./#option_ws-all)
      * [ 频道说明 ](./#option_ws-channel)
      * [ 用户持仓频道 ](./#option_ws-position)
      * [ 用户账户频道 ](./#option_ws-account)
      * [ 用户交易频道 ](./#option_ws-order)
      * [ 公共-合约信息频道 ](./#option_ws-instrument)
      * [ 公共-期权详细定价频道 ](./#option_ws-instrument_summary)
      * [ 公共-K线频道 ](./#option_ws-candle)
      * [ 公共-最新成交频道 ](./#option_ws-trade)
      * [ 公共-Ticker频道 ](./#option_ws-ticker)
      * [ 公共-5档深度频道 ](./#option_ws-depth5)
      * [ 公共-400档深度频道 ](./#option_ws-depth400)
      * [ 公共-400档增量数据频道 ](./#option_ws-full_depth)
    * [ WS公共指数频道 ](./#Index-README)
      * [ 指数行情 ](./#Index-ticker)
      * [ 指数K线 ](./#Index-candel)
    * [ WebSocketAPI 错误码 ](./#swap_ws-error_code)
  * [ 创建我的APIKey ](./#apikey)
  * [ OpenID开发文档说明 ](OpenAPI.html)
  *   * [ 问题反馈 ](./#support-README)

#

__

__

______

中文

  * [中文](../zh)
  * [English](../en)

### 入门指引

* * *

##### 欢迎使用开发者文档。此文档目前为V3版，会继续更新，请大家及时关注。

此文档为用户提供了一整套简单而又强大的开发工具，旨在帮助用户快速、高效地将交易功能整合到自己的应用当中。  
接口是提供服务的基础，API分为账户、交易和行情三类。开发者在网站创建账号后，可以根据自身需求建立不同权限的API，并利用API进行自动交易或者提现。  
账户和交易API需要身份验证，提供下单、撤单，查询订单和帐户信息等功能。行情API提供市场的行情数据，所有行情接口都是公开的。
如果API返回值里出现文档上没有的字段，则意味着这些字段即将被弃用，请使用文档上的字段。

#### 使用流程

步骤：开发者如需使用API ，请先申请V3APIKey等信息
[点击申请APIKey](account/users/myApi)，然后根据此文档详情进行开发交易，使用过程中如有问题或者建议请及时反馈。
[可参考SDK(点击跳转SDK详情页面)](https://github.com/okex/V3-Open-API-SDK)

##### **请 使用大陆以外的IP地址访问OKEx的API，强烈建议使用香港阿里云服务器。**

#### 接口调用方式说明

为用户提供两种调用接口的方式，开发者可根据自己的使用场景和偏好选择适合自己的方式来查询行情、进行交易或提现。

##### Rest API

REST，即Representational State
Transfer的缩写，是目前最流行的一种互联网软件架构。它结构清晰、符合标准、易于理解、扩展方便，正得到越来越多网站的采用。其优点如下：

  * 在RESTful架构中，每一个URL代表一种资源；
  * 客户端和服务器之间，传递这种资源的某种表现层；
  * 建议开发者使用Rest API进行币币交易或者资产提现等操作;
  * 客户端通过四个HTTP指令，对服务器端资源进行操作，实现"表现层状态转化"；

**HTTP/2 支持**  
HTTP/2 是最新版本的HTTP 协议，通过多路复用等方式对HTTP/1.1 进行了改进，在一些场景下提高了性能：  
1）目前全站支持通过HTTP/1.1 与HTTP/2 协议访问；  
2）对于支持的客户端，HTTP/2 是自动生效的，不需要另外进行调整；  
3）对于使用较旧浏览器或程序库的客户，会保持兼容性，使用HTTP/1.1；

##### WebSocket API

WebSocket是HTML5一种新的协议（Protocol）。它实现了客户端与服务器全双工通信，使得数据可以快速地双向传播。通过一次简单的握手就可以建立客户端和服务器连接，服务器根据业务规则可以主动推送信息给客户端。其优点如下：

  * 客户端和服务器进行数据传输时，请求头信息比较小，大概2个字节;
  * 客户端和服务器皆可以主动地发送数据给对方；
  * 不需要多次创建TCP请求和销毁，节约宽带和服务器的资源。 强烈建议开发者使用WebSocket API获取市场行情和买卖深度等信息。

#### 联系我们

如需帮助请添加微信号：ApiSupport 备注：API+姓名+ok账号，拉你进API问题交流群

### 做市商项目

欢迎优秀的做市商参与长期做市项目。申请条件：用户等级 VIP2 及以上且账户资产价值>=20BTC

**提 供以下信息发送邮件至： lpservice@okex.com**

1、账户信息；

2、除邮箱外的有效联系方式；

3、提供其他交易平台maker交易量截图证明（比如30天内成交量，或者VIP等级等）；

**邮 件里需注明所申请的做市商类别 (可多选):**

• OKEx 现货做市商申请

• OKEx 交割合约做市商申请

• OKEx 永续合约做市商申请

为鼓励做市商为平台提供更好的流动性，可以享受更优的交易手续费，同时也承担相应的做市责任。具体做市责任及手续费申请成功后提供相关资料。

*OKEx保留对做市商项目的最终解释权

做市商项目不支持VIP、交易量相关活动以及任何形式的返佣活动

### 新手教程

以下为API新手教程的视频，更多教学内容持续更新中，敬请期待：

1、API交易与申请 [点击这里观看](https://www.okex.me/academy/zh/api-transactions-and-
applications-cn)

2、Web页面和API接口数据对比 [点击这里观看](https://www.okex.me/academy/zh/web-page-and-api-
excuse-data-comparison-cn)

3、Websocket API使用介绍和注意事项 [点击这里观看](https://www.okex.me/academy/zh/websocket-
api-usage-introduction-and-precautions-cn)

4、API如何获取个人数据 [点击这里观看](https://www.okex.me/academy/zh/how-api-gets-personal-
data-cn)

### 更新日志

更新日志

### 2020-06-01

以下 2020年6月已上线

  
  

1、模拟盘的交易域名、业务线以及开启交易流程更新：

**模 拟盘，用户可以通过模拟盘API请求除充提币外的所有接口，包括市场行情信息、账户余额信息、持仓信息、订单信息等。**

在您开启OKEx交易之前，可以在我们提供的模拟盘上模拟交易，测试API接口相关功能，并调试您的代码交易逻辑。

模拟盘API交易功能需要在模拟盘上创建APIKey，模拟盘创建APIKey的流程与OKEx一致。

模拟盘API交易域名如下：

**RestAPI 地址：<https://www.okex.com>**

**WebSocket 地址: wss://real.okex.com:8443/ws/v3?brokerId=9999**

模拟盘的登陆账户与OKEx登录账户是互通的，如果您已经有okex账户，可以直接登录。

以下步骤开启API模拟交易：

**注 册okex账户-->资产管理-->开始模拟盘交易-->个人中心-->创建模拟盘APIKey---->开始模拟交易**

**注 意：1）模拟盘与okex实盘API的不同：模拟盘的请求的header里面需要添加"x-simulated-trading: 1"**

    
    
    请求头示例：
    
    Content-Type: application/json
    
    OK-ACCESS-KEY: 37c541a1-****-****-****-10fe7a038418
    
    OK-ACCESS-SIGN: leaVRETrtaoEQ3yI9qEtI1CZ82ikZ4xSG5Kj8gnl3uw=
    
    OK-ACCESS-PASSPHRASE: 1****6
    
    OK-ACCESS-TIMESTAMP: 2020-03-28T12:21:41.274Z
    
    x-simulated-trading: 1
    

2）模拟盘支持币种或合约：

币币/杠杆USDT交易区：BTC、ETH、LTC、ETC、XRP、EOS、BCH、BSV、TRX

交割合约USDT本位/永续合约USDT本位：BTC、ETH、LTC、ETC、XRP、EOS、BCH、BSV、TRX

交割合约币本位/永续合约币本位/期权合约：BTC

注意：模拟盘的交易币种前均加MN以区分，例如：MNBTC-MNUSDT（币币/杠杆）、MNBTC-USD-180213(交割合约)、MNBTC-
MNUSDT-SWAP(永续合约)、MNBTC-USD-190927-5000-C(期权合约)

### 2020-05-15

以下 2020年5月已上线

  
  

1.新增API新手教程模块，为新用户提供简单易懂的API接入、使用教程视频。

### 2020-04-22

以下 2020年4月已上线

  
  

1.交割合约增加"增加/减少逐仓仓位的保证金"接口

具体接口：

`POST/api/futures/v3/position/margin`

  
2.获取系统维护状态接口文档修改：功能兼容  
当前为：GET /api/system/v3/maintenance  
修改后：GET /api/system/v3/status  
  
3.新增"业务字典"模块  
  
  
4.币币、交割合约、永续合约止盈止损新增"市价止盈止损"参数：

具体接口：

`POST /api/spot/v3/order_algo`

`POST /api/futures/v3/order_algo`

`POST /api/swap/v3/order_algo`

##### 请求参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
algo_type | String | 否 | 1:限价 2:市场价；触发价格类型，默认是限价；为市场价时，委托价格不必填；  
  
  
  
  
5.交割合约增加"逐仓自动增加保证金"接口

具体接口：

`POST /api/futures/v3/accounts/auto_margin`

  
  
  
6.永续合约

1）持仓频道增加"多仓/空仓开仓冻结张数"参数

具体接口：

`{"op": "subscribe", "args": ["swap/position:BTC-USD-SWAP"]}`

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
open_outstanding | String | 多仓/空仓开仓冻结张数  
  
2）用户账户频道增加"可用保证金"、"多仓最大可开张数"和"空仓最大可开张数"参数

`{"op": "subscribe", "args": ["swap/account:BTC-USD-SWAP"]}`

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
available_qty | String | 可用保证金  
long_open_max | string | 多仓最大可开张数  
short_open_max | string | 空仓最大可开张数  
  
3)订单列表、订单信息、交易频道增加"杠杆倍数"和"最新成交ID"参数

具体接口：

`GET/api/swap/v3/orders/<instrument_id>/<order_id>`

`GET/api/swap/v3/orders/<instrument_id>`

`{"op": "subscribe", "args": ["swap/order:BTC-USD-SWAP"]}`

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
leverage | String | 杠杆倍数  
last_fill_id | String | 最新成交ID (如果没有推0)。和trade 频道推送的trade ID一致  
  
### 2020-03-30

以下 2020年3 月已上线

  
  

#### **1. 以下接口限速更新为：10次/2秒：**

币币API：账单流水；订单列表；成交明细

1）GET/api/spot/v3/accounts//ledger

2）GET/api/spot/v3/orders

3）GET/api/spot/v3/fills

币币杠杆API：账单流水；订单列表；成交明细

4）GET/api/margin/v3/accounts//ledger

5）GET/api/margin/v3/orders

6）GET/api/margin/v3/fills

交割合约API：订单列表；成交明细

7）GET/api/futures/v3/orders/

8）GET/api/futures/v3/fills

永续合约API：订单列表；成交明细

9）GET/api/swap/v3/orders/

10）GET/api/swap/v3/fills

期权API：订单列表；成交明细

11）GET/api/option/v3/orders/

12）GET/api/option/v3/fills/;  

#### **2. 交割合约增加接口：公共-获取历史结算记录**

具体接口：

`GET/api/futures/v3/settlement/history`  

#### **3. 增加"测试环境"：**

在您开启OKEx交易之前，可以在我们提供的测试网站上模拟交易，测试API接口相关功能，并调试您的代码交易逻辑。

测试网站目前支持的业务线为：交割合约，期权交易。

测试网站逐渐会开放的业务线为：币币交易，币币杠杆，永续合约。

测试网站的API交易功能所需的APIKey，需要进行创建APIKey，测试网创建APIKey的流程与OKEx一致。

测试网站域名如下：

RestAPI Url：<https://testnet.okex.com>

WebSocket 地址: wss://real.okex.com:8443/ws/v3?brokerId=181

测试网的登陆账户与OKEx登录账户是互通的，如果您已经有okex账户，可以直接登录。

以下步骤开启API模拟交易：

注册okex账户-->登录测试网-->领取测试币-->创建测试网APIKey---->开始模拟交易

测试网站，用户可以通过API请求交割合约和期权的所有接口，包括基本合约信息、市场行情信息、账户余额信息、持仓信息、订单信息等，详细接口功能请查看测试网的API文档。  

#### **4. 交割合约、永续合约下单接口增加市价委托功能；**

具体接口：

`POST /api/futures/v3/order`

`POST /api/swap/v3/order`  

#### 5.交割合约、永续合约止盈止损下单中增加触发价格类型：

具体接口：

`POST /api/futures/v3/order_algo`

`POST /api/swap/v3/order_algo`

新增参数：

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
algo_type | String | 1:限价 2:市场价；  
  
### 2020-02-29

以下 2020年2 月已上线

  
  

1.币币用户交易频道增加"last_fill_id"，成交ID，和交易频道trade_id对应

具体接口：

{"op": "subscribe", "args": ["spot/order:LTC-USDT"]}

返回参数

参数名 | 参数类型 | 描述  
---|---|---  
last_fill_id | String | 成交ID，和交易频道trade_id对应  
  
  
  

2.币币、交割合约、永续合约、期权增加"公共-400档增量数据频道"

具体接口：

{"op": "subscribe", "args": ["spot/depth_l2_tbt:BTC-USDT"]} {"op":
"subscribe", "args": ["futures/depth_l2_tbt:BTC-USD-200327"]} {"op":
"subscribe", "args": ["swap/depth_l2_tbt:BTC-USD-SWAP"]} {"op": "subscribe",
"args": ["option/depth_l2_tbt:BTC-USD-200207-9500-C"]}

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
asks | List<String> | 卖方深度  
bids | List<String> | 买方深度  
timestamp | String | 时间戳  
instrument_id | String | 币对  
checksum | String | 检验和  
  
  
  

3.币币获取成交明细和公共-交易频道增加"成交id"：

具体接口：

GET /api/spot/v3/fills

{"op": "subscribe", "args": ["spot/trade:ETH-USDT"]}

返回参数

参数名 | 参数类型 | 描述  
---|---|---  
trade_id | String | 成交id  
  
  
  

4.增加获取现货杠杆标记价格接口：

##### 限速规则：20次/2s

##### HTTP请求

`GET/api/margin/v3/instruments/<instrument_id>/mark_price`

##### 请求示例

`GET/api/margin/v3/instruments/EOS-USDT/mark_price`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
instrument_id | String | 是 | 杠杆币对名称  
  
##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
instrument_id | String | 杠杆币对名称  
mark_price | String | 指定杠杆的标记价格  
timestamp | String | 返回请求时间  
  
5.tbt频道由首次返回市场订单簿的全部深度数据变更为：首次返回市场订单簿的400档深度数据。

6.alias 枚举值中增加：次季度 `bi_quarter`

具体接口：

`GET/api/futures/v3/instruments`

##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
alias | String | 本周 `this_week`  
次周 `next_week`  
季度 `quarter`  
次季度 `bi_quarter`  
  
### 2019-12-31

以下 12 月已上线

  
  

    
    
      1.增加获取 "当前账户交易手续等级的费率 " 接口<br>
        涉及接口：<br>GET /api/spot/v3/trade_fee,GET /api/futures/v3/trade_fee<br>
    
    
      2.增加获取子账户余额信息接口<br>
        涉及接口：<br>GET /api/account/v3/sub-account<br>
    
      3.增加获取账户总资产接口<br>
         涉及接口：<br>GET /api/account/v3/asset-valuation <br>
    
      4.币币杠杆 账户信息接口增加维持保证金率字段和借币数量档位字段<br>
         涉及接口：<br>GET /api/margin/v3/accounts<br>
                  GET/api/margin/v3/accounts/<instrument_id><br>
                  {"op": "subscribe", "args": ["spot/margin_account:ETH-USDT"]}<br>
    
      5.币币杠杆增加设置杠杆倍数接口和查询杠杆倍数接口<br>
         涉及接口：<br>POST  /api/margin/v3/accounts/<instrument_id>/leverage<br>
                  GET /api/margin/v3/accounts/<instrument_id>/leverage<br>
    
      6.wsAPI币币杠杆account频道新增强平价（liquidation_price）字段<br>
         涉及接口：{"op": "subscribe", "args": ["spot/margin_account:ETH-USDT"]}<br>
    
      7. 币币成交明细接口增加currency字段<br>
         涉及的接口：GET /api/spot/v3/fills<br>
    

  
  

### 2019-11-30

以下 11 月已上线

  
  
一：支持永续usdt保证金合约交易 1、涉及的接口： a.公共-获取合约信息 GET /api/swap/v3/instruments - - -
-返回值增加必要字段 API接口改造后，您的程序不会受影响。但是在接口中会有新的字段增加。给您带来的不便，敬请谅解！  
二：永续接口优化

    
    
      1.增加获取 "当前账户交易手续等级的费率 " 接口
        涉及接口：GET /api/swap/v3/trade_fee
    
      2.永续ws order里增加last_fill_id
        涉及接口：{"op": "subscribe", "args": ["swap/order:BTC-USD-SWAP"]}
    
      3.RestAPI永续合约深度接口，增加  合并深度 查询条件
         涉及接口：GET /api/swap/v3/instruments/<instrument_id>/depth
    
      4.永续合约，下单和撤单和持仓查询等接口的  instrumentid字段，入参支持大小写参数。
    
      5.永续合约持仓接口返回信息增加未实现盈亏字段。
         涉及接口：GET /api/swap/v3/<instrument_id>/position，GET /api/swap/v3/position，
    
      6. 永续账户信息接口，增加可划转数量字段
         涉及的接口：GET /api/futures/v3/accounts/{currency}，GET /api/futures/v3/accounts，
    

  
  

### 2019-10-31

以下 10 月已上线

  
  

改造内容如下（此公告仅涉及到API交易用户，V1 OpenAPI不支持USDT保证金合约交易）：

1、改造内容： 现状是：API接口无法通过请求参数区分'币本位保证金合约'和'USDT保证金合约'。

    
    
          端口：GET /api/futures/v3/accounts/<currency>
          示例：GET /api/futures/v3/accounts/BTC 
    

改造后： 请求参数currency更换成underlying。币本位保证金合约的传参值为BTC-USD，USDT保证金合约的传参值为BTC-USDT

    
    
         端口：GET /api/futures/v3/accounts/<underlying>
         USDT保证金合约示例：GET /api/futures/v3/accounts/BTC-USDT
         币本位保证金合约示例：GET /api/futures/v3/accounts/BTC-USD
    

改造后，仍然兼容之前的请求格式，如果传入，等价于其目前对应的（标的指数）。

    
    
         例如：GET /api/futures/v3/accounts/BTC 等价于 GET /api/futures/v3/accounts/BTC-USD   
    

注意：restAPI 中"设置账户模式接口POST
/api/futures/v3/accounts/margin_mode"不做兼容处理。使用此接口需要传相应的underlying。

2、涉及的接口：restAPI

a.单个币种合约账户信息 GET /api/futures/v3/accounts/

b.账单流水查询 GET /api/futures/v3/accounts//ledger

c.设定合约杠杆倍数（全仓） POST /api/futures/v3/accounts//leverage

d.获取合约币种杠杆倍数 GET /api/futures/v3/accounts//leverage

e.公共获取合约信息 GET /api/futures/v3/instruments - - - -返回值增加必要字段

f.设置合约账户模式 POST /api/futures/v3/accounts/margin_mode - - - -此接口不做兼容

g.获取所有币种合约账户信息 GET /api/futures/v3/accounts - - - -返回值增加必要字段

3、涉及的接口: WebSocketAPI

a.公共-全量合约信息频道 futures/instruments - - - - 返回值增加必要字段

b.个人-订阅账户信息频道 futures/account

示例：币本位保证金合约：{"op": "subscribe", "args": ["futures/account:BTC"]} USDT保证金合约：
{"op": "subscribe", "args": ["futures/account:BTC-USDT"]}

如果您不交易USDT保证金合约，您的程序不会受影响。但是在接口中会有新的字段增加。给您带来的不便，敬请谅解！

  
  

### 2019-09-30

以下 9 月已上线

  
  

1.下线币币账户信息接口里的id字段

具体接口：

GET /api/spot/v3/accounts/

GET /api/spot/v3/accounts

{"op": "subscribe", "args": ["spot/account:BTC"]}

返回参数

参数名 | 参数类型 | 描述  
---|---|---  
id | String | 账户 id  
  
  
  

2.交割合约获取所有/单个账户信息接口，全仓返回增加"强平手续费"字段。

具体接口：

GET /api/futures/v3/accounts/

GET /api/futures/v3/accounts

返回参数

参数名 | 参数类型 | 描述  
---|---|---  
liqui_fee_rate | String | 强平手续费  
  
  
  

3.永续 WebSocket ticker 频道增加"持仓量"和"24小时开盘价"：

具体接口：

{"op": "subscribe", "args": ["swap/ticker:BTC-USD-SWAP"]}

返回参数

参数名 | 参数类型 | 描述  
---|---|---  
open_interest | String | 持仓量  
open_24h | String | 24 小时开盘价  
  
  
  

4.杠杆倍数字段调整

4.1) restAPi：永续的 持仓接口 GET /api/swap/v3/position GET /api/swap/v3/position

4.2) wsAPI： 永续持仓频道 {"op": "subscribe", "args": ["swap/position:BTC-USD-SWAP"]}

4.3) rest ： 永续获取委托单列表 （策略委托） GET /api/swap/v3/order_algo

返回的leverage 之前返回的是个整数。现在是带小数的返回了。 之前 leverage ："20" ,现在 leverage："20.00"。

  
  

5.币币ws交易频道，增加一个created_at字段

涉及接口：

{"op": "subscribe", "args": ["spot/order:LTC-USDT"]}

返回参数

参数名 | 参数类型 | 描述  
---|---|---  
created_at | String | 订单创建时间  
  
### 2019-08-31

以下8月已上线。

1.请求参数和返回参数增加withdraw_id提币id字段

具体接口：

`GET /api/account/v3/withdrawal/history/<currency>`

请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
withdraw_id | String | 否 | 提币申请ID  
  
只传currency，返回这个币对下的所有的提币记录。

同时传currency和withdraw_id后，返回指定 的提币记录

返回参数

参数名 | 参数类型 | 描述  
---|---|---  
withdraw_id | String | 提币申请ID  
  
2.查询所有币种的提币记录，返回参数增加withdraw_id字段。

具体接口：

`GET /api/account/v3/withdrawal/history`

返回参数

参数名 | 参数类型 | 描述  
---|---|---  
withdraw_id | String | 提币申请ID  
  
3.币币，交割，永续的获取成交明细接口请求参数"order_id"字段改成非必须填。

具体接口：

`GET /api/spot/v3/fills，GET /api/futures/v3/fills，GET /api/swap/v3/fills`

请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
order_id | String | 否 | 订单ID  
  
4.交割合约下单时，请求参数杠杆倍数（leverage）字段改为非必填，文档已下线。

具体接口：

POST /api/futures/v3/order

POST /api/futures/v3/orders

请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
leverage | String | 否 | 杠杆倍数  
  
5.交割合约和永续合约深度接口，请求参数增加depth字段。

具体接口：

`GET /api/futures/v3/instruments/<instrument_id>/book`

`GET /api/swap/v3/instruments/<instrument_id>/depth`

请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
depth | String | 否 | 按价格合并深度，例如：`0.1`或`0.001`  
  
depth：合并的档位，与精度保持一致，

例如btc，价格精度是小数点后一位（11111.1）。合并价格精度 为 0.1时（11111.1） 为 时（1111）

例如xrp。价格精度是小数点后4为（0.4112）。合并价格精度为
0.1时（0.4），0.01时（0.41），0.001时（0.411），0.0001时（0.4112）

6.交割合约通过APi接口获取强减仓的明细信息

具体接口：

GET /api/futures/v3/accounts//ledger

请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
type | String | 否 | 20.强减空 21.强减多  
  
7.交割单个币种持仓接口和所有持仓接口和WebSocket用户持仓频道，增加"已结算收益"（多空）字段。

具体接口：

GET /api/futures/v3//position

GET /api/futures/v3/position

用户持仓频道 {"op": "subscribe", "args": ["futures/position:BTC-USD-170317"]}

返回参数

参数名 | 参数类型 | 描述  
---|---|---  
long_settled_pnl | String | 多仓已结算收益  
short_settled_pnl | String | 空仓已结算收益  
  
8.永续单个币种持仓接口和所有持仓接口和WebSocket持仓频道，增加"已结算收益"（多空）字段。

具体接口：

GET /api/swap/v3//position

GET /api/swap/v3/position

用户持仓频道{"op": "subscribe", "args": ["swap/position:BTC-USD-SWAP"]}

返回参数

参数名 | 参数类型 | 描述  
---|---|---  
settled_pnl | String | 已结算收益  
  
9.永续合约每日结算调整内容：

1）Restful：公共-获取合约下一次结算时间

具体接口：

`GET /api/swap/v3/instruments/<instrument_id>/funding_time`

返回参数

参数名 | 参数类型 | 描述  
---|---|---  
estimated_rate | String | 下一期的预测资金费率  
funding_rate | String | 当期资金费率  
  
2）WebSocket：公共-资金费率频道（swap/funding_rate）

返回参数

参数名 | 参数类型 | 描述  
---|---|---  
estimated_rate | String | 下一期的预测资金费率  
  
3）v3 现使用参数：funding_rate 取值由目前"资金费率"变为"当期资金费率"

10.OKEx关于V3 OpenAPI现货/杠杆接口手续费(Fee)字段的优化

1)获取成交明细  
GET /api/margin/v3/fills 和 GET /api/spot/v3/fills

2)获取账单流水  
GET /api/margin/v3/accounts//ledger 和 GET /api/spot/v3/accounts//ledger

返佣和扣除手续费，都用Fee参数表示，且返佣为正数，扣除手续费为负数

### 2019-07-31

以下内容预计7月上线，请用户提前做好准备。

1、交割合约和永续合约增加参数：已结算收益

具体接口：

`GET /api/futures/v3/position`

`GET /api/futures/v3/<instrument_id>/position`

ws-futures/position

`GET /api/swap/v3/position`

`GET /api/swap/v3/<instrument_id>/position`

ws-swap/position

2、下线交割合约"设置合约币种强平模式接口"

3、ws地址由：wss://real.okex.com:10442/ws/v3 变更为：wss://real.okex.com:8443/ws/v3

### 2019-06-30

以下内容预计6月上线，请用户提前做好准备。

1、分页 OKEx对返回数组的有些REST请求使用游标分页。游标分页允许在当前结果页面之前和之后获取结果，并且非常适合实时数据。端点如/ trades，/
fills，/ orders，默认返回最新100项。要检索更多结果，后续请求应根据先前返回的数据指定要分页的方向。
`before`和`after`游标可以通过响应头`OK-BEFORE`和`OK-AFTER`。在初始请求之后发出页面请求时，您的请求应使用这些游标值。

例 `GET /api/spot/v3/orders?before=2&limit=30`

参数名 | 参数类型 | 描述  
---|---|---  
after | String |
请求此id之前（更旧的数据）的分页内容，传的值为对应接口的`order_id`、`ledger_id`或`trade_id`等  
before | String |
请求此id之后（更新的数据）的分页内容，传的值为对应接口的`order_id`、`ledger_id`或`trade_id`等 |  
limit | String | 分页返回的结果集数量，最大为100，不填默认返回100条  
  
游标之前和之后 将before光标引用在结果页中的第一项和after光标引用了一组结果的最后一个数据。

headers将包含一个`OK-
BEFORE`标头，该标头将返回光标id，以便在当前页面的下一个页面请求中使用。之前的页面是一个较新的页面，而不是在按时间顺序排列之前发生的页面。
响应还将包含一个`OK-
AFTER`标头，该标头将返回光标id，以便在此页面之后的页面的下一个请求中使用。之后的页面是较旧的页面，而不是按时间顺序排在此页面之后的页面。

涉及到的接口：

`GET /api/futures/v3/accounts/<currency>/ledger`

`GET /api/futures/v3/orders/<instrument_id>`

`GET /api/futures/v3/fills`

`GET /api/futures/v3/instruments/<instrument_id>/trades`

`GET /api/spot/v3/orders_pending`

`GET /api/account/v3/ledger`

`GET /api/futures/v3/accounts/<currency>/ledger`

`GET /api/futures/v3/orders/<instrument_id>`

`GET /api/futures/v3/fills`

`GET /api/futures/v3/instruments/<instrument_id>/trades`

`GET /api/swap/v3/accounts/<instrument_id>/ledger`

`GET /api/swap/v3/orders/<instrument_id>`

`GET /api/swap/v3/fills`

`GET /api/swap/v3/instruments/<instrument_id>/trades`

2、资金账户的"资金划转"接口，增加"母账户直接划转到子账户的资金账户、币币账户、交割账户、永续账户"：

##### HTTP请求

POST /api/account/v3/transfer

##### 请求示例

POST
/api/account/v3/transfer{"amount":0.0001,"currency":"eos","from":6,"to":5,"instrument_id":"eos-
usdt"}

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
currency | String | 是 | 币种  
amount | String | 是 | 划转数量  
from | String | 是 | 转出账户  
`0`:子账户  
`1`:币币  
`3`:合约  
`4`:C2C  
`5`:币币杠杆  
`6`:资金账户  
`8`:余币宝  
`9`:永续合约  
to | String | 是 | 转入账户  
`0`:子账户  
`1`:币币  
`3`:合约  
`4`:C2C  
`5`:币币杠杆  
`6`:资金账户  
`8`:余币宝  
`9`:永续合约  
sub_account | String | 否 | 子账号登录名，`from`或`to`指定为`0`时，sub_account为必填项  
instrument_id | String | 否 | 杠杆币对，如：eos-usdt，仅限已开通杠杆的币对  
  
from或to指定为0时，sub_account为必填项。

当from为0时，to只能填6，即子账户的资金账户只能转到母账户的资金账户。

当from指定为6，to指定为1-9，且sub_account填写子账户名时，可从母账户直接划转至子账户对应的币币、合约等账户。

from或to指定为5时，instrument_id为必填项。

### 2019-05-31

1、OKEx为所有返回数据集的REST请求使用分页。分页允许在结果的当前页面之前和之后获取结果，并且非常适合于实时数据。像/ trades，/ fill，/
orders这样默认返回最新内容的请求。根据当前的返回结果，后续请求可以在他的基础之上指定请求数据的方向，可以请求在这之前的，也可以请求在这之后的数据。

`from`游标指向的是返回结果页的第一条内容，`to`游标指向的是返回结果页的最后一条内容。(页面内容是按照最新的排在最上面的顺序)

`from`、`to`后传的值为对应接口的`order_id`、`ledger_id`或`trade_id`等

`from`、`to`和`limit` 均为非必填，用户可不传此三个参数调用对应接口，返回最新的100条数据，再根据得到数据的id作为请求头，查询其他数据；

`from-to`的游标范围是左开右闭`(from, to]`，即查询的返回数据，不包括from的标识的数据；

如果查询返回的数量<`limit`指定的数量，则返回`from-to`游标查到的全部数据；

如果查询返回的数据>`limit`指定的数量，则返回从`from`开始的id，向前limit条(如limit=50就是50条）数据；

举例如果你请求返回的结果每一条内容的id是111，112，113，114，115，116，117，118，119，120

那么在返回结果里面这些内容的排列顺序是120，119，118，117，116，115，114，113，112，111

如果你想访问更新的数据，如115以前更旧的数据那么你需要使用`from`参数，如：`orders?from=115&limit=3`,则返回的是115以前更旧的3条数据，且排列顺序为：114，113，112（不包括115）

如果你想访问更新的数据，如115以后更新的数据那么你需要使用`to`参数，如：`orders?to=115&limit=3`,则返回的是115以前更旧的3条数据，且排列顺序为：117，116，115（包括115）

涉及到的接口：

`GET /api/futures/v3/accounts/<currency>/ledger`

`GET /api/futures/v3/orders/<instrument_id>`

`GET /api/futures/v3/fills`

`GET /api/futures/v3/instruments/<instrument_id>/trades`

`GET /api/spot/v3/orders_pending`

`GET /api/account/v3/ledger`

`GET /api/futures/v3/accounts/<currency>/ledger`

`GET /api/futures/v3/orders/<instrument_id>`

`GET /api/futures/v3/fills`

`GET /api/futures/v3/instruments/<instrument_id>/trades`

`GET /api/swap/v3/accounts/<instrument_id>/ledger`

`GET /api/swap/v3/orders/<instrument_id>`

`GET /api/swap/v3/fills`

`GET /api/swap/v3/instruments/<instrument_id>/trades`

2、加入一个推全量合约的频道：有新合约上线，就推一次全量合约数据；

3、【功能优化】：永续合约的账单流水查询接口的返回参数增加details、currency和balance（表示流水类型）

| details | String | 如果类型是交易产生的，则该`details`字段将包含`order_id`和`instrument_id` | |
currency | String | 币种，如：`btc` | | balance | String |
开仓平仓的张数（开仓为正数，平仓为负数，当`type`是`fee`时，`balance`为`0`） |

影响的业务线：永续合约

影响的具体接口rest接口：

GET /api/swap/v3/accounts//ledger

4、【功能优化】：币币、币币杠杆的获取订单列表和获取订单信息的返回参数增加成交均价 price_avg

| price_avg | String | 成交均价 |

影响的业务线：币币、币币杠杆

影响的具体接口rest接口：

`GET /api/spot/v3/orders`

`GET /api/spot/v3/orders/<order_id>`

`GET /api/margin/v3/orders`

`GET /api/margin/v3/orders/<order_id>`

5、【功能优化】：币币、币币杠杆、交割合约、永续合约的获取成交明细接口的请求和返回增加参数用户ID
client_oid，且将order_id改为非必填参数，即可获取当前币对的所有成交明细。

| client_oid | String | 否 | 由您设置的订单ID来识别您的订单 ,类型为字母（大小写）+数字或者纯字母（大小写），1-32位字符
| | order_id | String | 否 | 订单ID，下单失败时，此字段值为`-1` |

影响的业务线：币币、币币杠杆、交割合约、永续合约

影响的具体接口rest接口：

`GET /api/spot/v3/fills`

`GET /api/margin/v3/fills`

`GET /api/futures/v3/fills`

`GET /api/swap/v3/fills`

6、【功能优化】: 币币、币币杠杆、交割合约、永续合约的批量下单端口；：

1）币币、币币杠杆的批量下单返回，币对中的下线"_"，改为中划线"-"; 例如："btc_usdt" 改为"btc-usdt".

2）当币币、币币杠杆批量下单返回error_code 33017, 交割、永续的批量下单返回error_code 32015时，http状态码应返回400;

3） 如果下的多个单，只有部分发生了余额不足的错误，http状态码也应为400.

影响的业务线：币币、币币杠杆、交割合约、永续合约

影响的具体接口

REST接口：

`POST /api/spot/v3/batch_orders`

`POST /api/margin/v3/batch_orders`

`POST /api/futures/v3/batch_orders`

`POST /api/swap/v3/batch_orders`

7、【功能优化】：币币、交割合约、永续合约的账单流水查询接口的请求参数增加流水类型 type

币币： | type | String | 非必填 | `1` .充值  
`2` .提现  
`3` .借入  
`4` .还款  
`7` .买入  
`8` .卖出  
`9` .新手任务  
`10` .邀请好友完成新手任务  
`11` .扣除任务奖励  
`12` .邀请分成  
`13` .撤销提现  
`14` .活动送出  
`15` .活动得到  
`18` .交割合约转入  
`19` .转出至交割合约  
`20` .转入子账户  
`21` .转出至子账户  
`22` .返手续费  
`23` .接收红包  
`24` .发送红包  
`25` .otc买入  
`26` .otc卖出  
`27` .扣除  
`28` .兑换  
`29` .转出至资金账户  
`30` .资金账户转入  
`31` .转出至法币  
`32` .法币转入  
`33` .转出至杠杆  
`34` .杠杆转入  
`35` .借币  
`36` .还币  
`37` .市商计划送出  
`38` .市商计划返还  
`41` .点卡抵扣币币手续费  
`42` .购买点卡  
`43` .点卡转让  
`44` .市商计划额外送出  
`45` .市商计划返还  
`46` .币币账户转入  
`47` .转出至币币账户  
`48` .转出至组合  
`49` .组合转入  
`50` .挖矿扣除  
`51` .挖矿所得  
`52` .收益倍增  
`53` .鼓励金分配  
`55` .余币宝转入  
`56` .转出至余币宝  
`57` .永续合约转入  
`58` .转出至永续合约  
`59` .还糖果  
`60` .点卡抵扣杠杆手续费 |

交割合约： | type | String | 非必填 |1.开多 2.开空 3.平多 4.平空 5.手续费 6.转入，7.转出 8.清算已实现盈亏
9.穿仓分摊，11.强平剩余 12.剩余拨付 13-强平平多 14-强平平空 15.交割平多 16.交割平空 17.清算未实现收益-多头
18.清算未实现收益-空头 |

永续合约： | type | String | 非必填 | 1. 开多 2\. 开空 3\. 平多 4\. 平空 5.转入 6.转出 7.清算未实现
8.分摊 9.剩余拨付 10.强平多 11.强平空 14.资金费 15.手动追加 16.手动减少 17.自动追加 18.修改持仓模式 19.强减多
20.强减空 21.用户调低杠杆追加保证金 22.清算已实现 |

影响的业务线：币币、交割合约、永续合约

影响的具体接口rest接口：

`GET /api/spot/v3/accounts/<currency>/ledger`

`GET /api/futures/v3/accounts/<currency>/ledger`

`GET /api/swap/v3/accounts/<instrument_id>/ledger`

### 关于V1 API 支持交割合约梯度保证金优化

更新时间：2019年5月15日15：00(HKT)

更新内容：

推送

1）ok_sub_futureusd_positions 合约持仓信息频道

a.逐仓返回格式修改：

优化前：多空方向，返回10倍和20倍杠杆持仓信息，若没有推0；

优化后：多空方向，返回n倍和m倍杠杆持仓信息，若没有不推；

优化前前格式：

    
    
    [
        {
            "binary":0,
            "channel":"ok_sub_futureusd_positions",
            "data":{
                "symbol":"eos_usd",
                "user_id":7669455,
                "positions":[
                    {
                        "lever_rate":10,
                        "avgprice":4.849,
                        "contract_id":201906280200053,
                        "hold_amount":1,
                        "contract_name":"EOS0628",
                        "costprice":4.849,
                        "forcedprice":4.44862378,
                        "bondfreez":0,
                        "eveningup":1,
                        "fixmargin":0.20622809,
                        "balance":0.20684677,
                        "position":1,
                        "profitreal":-0.00061868,
                        "position_id":2517385395344384
                    },
                    {
                        "lever_rate":10,
                        "avgprice":0,
                        "contract_id":201906280200053,
                        "hold_amount":0,
                        "contract_name":"EOS0628",
                        "costprice":0,
                        "forcedprice":0,
                        "bondfreez":0,
                        "eveningup":0,
                        "fixmargin":0,
                        "balance":0.20684677,
                        "position":2,
                        "profitreal":-0.00061868,
                        "position_id":2517385395344384
                    },
                    {
                        "lever_rate":20,
                        "avgprice":0,
                        "contract_id":201906280200053,
                        "hold_amount":0,
                        "contract_name":"EOS0628",
                        "costprice":0,
                        "forcedprice":0,
                        "bondfreez":0,
                        "eveningup":0,
                        "fixmargin":0,
                        "balance":0.20684677,
                        "position":1,
                        "profitreal":-0.00061868,
                        "position_id":2517385395344384
                    },
                    {
                        "lever_rate":20,
                        "avgprice":5.423,
                        "contract_id":201906280200053,
                        "hold_amount":0,
                        "contract_name":"EOS0628",
                        "costprice":5.423,
                        "forcedprice":0,
                        "bondfreez":0,
                        "eveningup":0,
                        "fixmargin":0,
                        "balance":0.20684677,
                        "position":2,
                        "profitreal":-0.00061868,
                        "position_id":2517385395344384
                    }
                ]
            }
        }
    ]
    

改之后格式：

    
    
    [
        {
            "binary":0,
            "channel":"ok_sub_futureusd_positions",
            "data":{
        "symbol":"etc_usd",
        "user_id":36203808,
        "positions":[
            {
                "lever_rate":5,
                "avgprice":56.89655172,
                "contract_id":20170310446,
                "hold_amount":10,
                "contract_name":"ETC0310",
                "costprice":56.89655172,
                "forcedprice":52.5,
                "bondfreez":0,
                "eveningup":5,
                "fixmargin":0.17575758,
                "balance":0.2067697,
                "position":1,
                "longMaintainenceRatio":"0.015",
                "profitreal":-0.00070909,
                "position_id":2778972475169792
            },
            {
                "lever_rate":25,
                "avgprice":33,
                "contract_id":20170310446,
                "hold_amount":2,
                "contract_name":"ETC0310",
                "costprice":33,
                "forcedprice":34.2157,
                "bondfreez":0,
                "eveningup":1,
                "fixmargin":0.03030303,
                "balance":0.2067697,
                "shortMaintainenceRatio":"0.015",
                "position":2,
                "profitreal":-0.00070909,
                "position_id":2778972475169792
            }
        ]
    }
    

b.新增返回参数：

逐仓

| longMaintainenceRatio |String |多仓维持保证金率 |

| shortMaintainenceRatio |String |空仓维持保证金率 |

2）ok_sub_futureusd_userinfo 合约账户信息频道

新增返回参数：

逐仓

| bannerFrozen| String |冻结|

全仓

| bannerFrozen | String | 冻结 |

| maintainenceRatio | String | 维持保证金率 |

### 2019-05-15

交割合约梯度保证金同步（v3）

业务逻辑详见：OKEx关于交割合约上线梯度保证金模式、手续费等级试用功能及交易手续费调整的公告

中文链接：<https://support.okex.com/hc/zh-cn/articles/360028302371>

v3 API 同步优化如下：

1、设置合约币种强平模式

设置合约币种强平模式，注意当前仓位有挂单禁止切换账户模式。

限速规则：5次/2s

HTTP请求

`POST /api/futures/v3/accounts/liqui_mode`

请求示例

`POST
/api/futures/v3/accounts/liqui_mode{"currency":"btc","liqui_mode":"tier"}`

请求参数

| 参数名 | 参数类型 | 是否必须 | 描述 |

| currency | String | 是 | 币种，如`BTC` |

| liqui_mode | string | 是 | 强平模式  
`tier`（梯度强平）  
`legacy`（一次强平）|

返回参数

| 参数名 | 参数类型 | 描述|

| liqui_mode | string | 强平模式  
`tier`（梯度强平）  
`legacy`（一次强平）|

| currency | String | 币种，如`BTC` |

| result | String | 返回设定结果，成功或错误码 |

  

2、所有/单个账户信息：

全仓增加：维持保证金率/和获取当前强平模式

逐仓增加：获取当前强平模式

所有币种合约账户信息【单个币种合约账户信息同理】

用于获取全币种账户信息，会有大量的性能消耗，建议用户传币种获取。

限速规则：1次/10s

HTTP请求

GET /api/futures/v3/accounts

请求示例

GET /api/futures/v3/accounts

返回参数增加：

全仓

| 全仓参数名 | 参数类型 | 描述 |

| maint_margin_ratio | String | 维持保证金率 |

| liqui_mode | string | 强平模式  
`tier`（梯度强平）  
`legacy`（一次强平）|

逐仓

| 逐仓参数名 | 参数类型 | 描述 |

| liqui_mode | string | 强平模式  
`tier`（梯度强平）  
`legacy`（一次强平）|

  

3、持仓信息：

全仓增加：保证金、收益、收益率、未实现盈亏

逐仓增加：保证金率、维持保证金率、收益、未实现盈亏

合约持仓信息

获取合约账户所有的持仓信息。会有大量的性能消耗，建议用户传币种获取。

限速规则：5次/2s

HTTP请求

GET /api/futures/v3/position

请求示例

GET /api/futures/v3/position

返回参数增加：

全仓

| 全仓参数名 | 参数类型 | 描述 |

| short_margin | String | 空仓保证金 |

| short_pnl | String | 空仓收益 |

| short_pnl_ratio | String | 空仓收益率 |

| short_unrealised_pnl | String | 空仓未实现盈亏 |

| long_margin | String | 多仓保证金 |

| long_pnl | String | 多仓收益|

| long_pnl_ratio | String | 多仓收益率|

| long_unrealised_pnl | String | 多仓未实现盈亏|

逐仓

| 逐仓参数名 | 参数类型 | 描述 |

| short_margin_ratio | String | 空仓保证金率 |

| short_maint_margin_ratio | String | 空仓维持保证金率 |

| short_pnl | String | 空仓收益 |

| short_unrealised_pnl | String | 空仓未实现盈亏 |

| long_margin_ratio | String | 多仓保证金率 |

| long_maint_margin_ratio | String | 多仓维持保证金率|

| long_pnl | String | 多仓收益 |

| long_unrealised_pnl | String | 多仓未实现盈亏 |

  

4、持仓杠杆倍数调整（持仓中也能调整，1-100倍）

设定合约币种杠杆倍数

设定合约账户币种杠杆倍数，注意当前仓位有挂单禁止切换杠杆。

限速规则：5次/2s

HTTP请求

`POST /api/futures/v3/accounts/<currency>/leverage`

请求示例

`POST /api/futures/v3/accounts/btc/leverage{"leverage":"99"}`（全仓示例）

`POST /api/futures/v3/accounts/btc/leverage{"instrument_id":"BTC-
USD-180213","direction":"long","leverage":"99"}`（逐仓示例）

请求参数增加：

全仓

| 全仓参数名 | 参数类型 | 是否必须 | 描述 |

| leverage | String | 是 | 要设定的杠杆倍数，填写`1-100`的整数 |

| currency | String | 是 | 币种，如：`btc` |

逐仓

| 逐仓参数名 | 参数类型 | 是否必须 | 描述 |

| currency | String | 是 | 币种，如：`btc`|

| instrument_id | String | 是 | 合约ID，如`BTC-USD-180213`|

| direction| String| 是 | 开仓方向  
long（做多）或者short（做空）|

| leverage | String | 是| 要设定的杠杆倍数，填写`1-100`的整数|

错误码增加：

32040:当前有持仓仓位或挂单（error message："EOS-USD-180213") You have open positions or
orders.

32060:保证金不足，无法调整杠杆 Insufficient margin. Unable to adjust leverage.

  

WEBSOCKECT:

  

1、账户频道：

全仓增加维持保证金率/和获取当前强平模式

逐仓增加获取当前强平模式

用户账户频道

获取账户信息，需用用户登录

send示例

{"op": "subscribe", "args": ["futures/account:BTC"]}

其中`futures/account`为频道名，`BTC`为`token`

返回参数增加：

| 参数名（全仓）| 参数类型 | 描述|

| maint_margin_ratio| String | 维持保证金率|

| liqui_mode| string | 强平模式  
`tier`（梯度强平）  
`legacy`（一次强平）|

| 参数名（逐仓） | 参数类型 | 描述|

| liqui_mode | string| 强平模式  
`tier`（梯度强平）  
`legacy`（一次强平）|

  

2、持仓信息：

全仓增加：保证金、收益、收益率、未实现盈亏

逐仓增加：保证金率、维持保证金率、收益、未实现盈亏

用户持仓频道

获取用户持仓信息，需用用户登录

send示例

{"op": "subscribe", "args": ["futures/position:BTC-USD-170317"]}

其中`futures/position`为频道名，`BTC-USD-170317`为`instrument_id`

全仓增加：

| 全仓参数名 | 参数类型| 描述|

| short_margin | String | 空仓保证金|

| short_pnl String | 空仓收益|

| short_pnl_ratio | String | 空仓收益率 |

| short_unrealised_pnl | String | 空仓未实现盈亏|

| long_margin | String | 多仓保证金 |

| long_pnl | String | 多仓收益|

| long_pnl_ratio | String | 多仓收益率 |

| long_unrealised_pnl | String | 多仓未实现盈亏|

逐仓增加：

| 逐仓参数名 | 参数类型 | 描述 |

| short_margin_ratio | String | 空仓保证金率 |

| short_maint_margin_ratio | String | 空仓维持保证金率 |

| short_pnl | String | 空仓收益 |

| short_unrealised_pnl | String | 空仓未实现盈亏 |

| long_margin_ratio | String | 多仓保证金率 |

| long_maint_margin_ratio | String | 多仓维持保证金率 |

| long_pnl | String | 多仓收益 |

| long_unrealised_pnl | String | 多仓未实现盈亏 |

### 2019-04-28

变更1【功能下线】币币的多状态查询功能下线，将不再支持多状态查询

影响的业务线：币币

影响的具体接口：Rest API `GET /api/spot/v3/orders`

变更2【功能优化】：增加参数state（表示订单状态），将币币、交割合约、永续合约的订单状态定义统一一致。

说明：state为新增加的字段，功能等同原有status字段。短期会对这2个字段做兼容，建议原用户尽早切换成state，status的下线时会提前通知用户。

state，状态集说明："-2":失败,"-1":撤单成功,"0":等待成交 ,"1":部分成交,
"2":完全成交,"3":下单中,"4":撤单中,"6": 未完成（等待成交+部分成交），"7":已完成（撤单成功+完全成交））

影响的业务线：币币、币币杠杆、交割合约、永续合约

影响的具体接口rest接口：

`GET /api/spot/v3/orders`；

`GET /api/spot/v3/orders_pending`；

`GET /api/spot/v3/orders/<order_id>`

`GET /api/margin/v3/orders`；

`GET /api/margin/v3/orders/<order_id>`；

`GET /api/margin/v3/orders_pending`；

`GET /api/futures/v3/orders/<instrument_id>`

`GET /api/futures/v3/orders/<instrument_id>/<order_id>`；

`GET /api/swap/v3/orders/<instrument_id>`；

`GET /api/swap/v3/orders/<instrument_id>/<order_id>`

影响的具体接口WS接口：

spot/order

futures/order

swap/order

### 2019-04-26

【功能优化】：所有接口返回参数的数据类型(除Boolean以外)全部统一为String类型

影响的业务线：币币、币币杠杆、交割合约、永续合约

影响的具体接口：涉及到的接口很多，建议用户统一检查一遍，rest和ws接口均有。

### 2019-04-24

【新增接口】增加3个公共错误码

影响的业务线：币币、币币杠杆、交割合约、永续合约

具体新增的3个错误码描述如下：

错误提示 | 错误码 | HTTP状态码  
---|---|---  
接口已下线或无法使用 | 30019 | 400  
非法的json数据 | 30021 | 400  
Api已被冻结 | 30022 | 401  
  
### 2019-04-12

【新增接口】交割合约增加：设置合约币种账户模式接口

影响的业务线：交割合约

影响的具体接口：`POST /api/futures/v3/accounts/margin_mode`

设置合约币种账户模式，注意当前仓位有持仓或者挂单禁止切换账户模式。

限速规则：5次/2s

##### HTTP请求

`POST /api/futures/v3/accounts/margin_mode`

##### 请求示例

`POST
/api/futures/v3/accounts/margin_mode{"currency":"btc","margin_mode":"crossed"}`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
currency | String | 是 | 币种，如：`btc`  
margin_mode | String | 是 | 账户模式  
`crossed`:全仓  
`fixed`:逐仓  
  
##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
currency | String | 币种，如：`btc`  
margin_mode | String | 账户模式  
`crossed`:全仓  
`fixed`:逐仓  
result | String | 返回设定结果  
error_code | String | 错误码，下单成功时为`0`，下单失败时会显示相应错误码  
error_message | String | 错误信息，下单成功时为空，下单失败时会显示错误信息  
  
##### 返回示例

    
    
    {
        "result":true,
        "error_message":"",
        "error_code":"0",
        "currency":"btc",
        "margin_mode":"crossed"
    }
    

### 2019-03-27

【功能优化】: 用client_oid批量撤销订单，由之前每个币对可撤一个，优化为每个币对可撤十个。

影响的业务线：币币、币币杠杆

影响的具体接口REST接口：

`POST /api/spot/v3/cancel_batch_orders`

`POST /api/margin/v3/cancel_batch_orders`

【功能优化】：WebSocket 的order 频道的返回参数增加"最新成交价"、"最新成交数量"和"最新成交时间"

| last_fill_px | String | 最新成交价格（如果没有，推`0`） |

| last_fill_qty | String | 最新成交数量（如果没有，推`0`） |

| last_fill_time | String | 最新成交时间（如果没有，推`1970-01-01T00:00:00.000Z`） |

影响的业务线：币币、币币杠杆、交割合约和永续合约

影响的具体接口REST接口：

swap/order

futures/order

spot/order

### 2019-01-21

【功能优化】: K线接口返回格式统一为数组 【时间，开，高，低，收，交易量】

影响的业务线：币币、币币杠杆、交割合约和永续合约

影响的具体接口REST接口：

`GET /api/spot/v3/instruments/<instrument_id>/candles`

`GET /api/futures/v3/instruments/<instrument-id>/candles`

`GET /api/swap/v3/instruments/<instrument_id>/candles`

影响的具体接口WS接口：

swap/candle

futures/candle

spot/candle

### 常见问题

**若 以下内容仍未帮助到您，可加入官方微信交流群，请添加微信号：ApiSupport 备注：API+姓名+ok账号。**

### APIKey问题

**1. 如何申请APIKey？**

申请API网址 <https://www.okex.com/account/users/myApi>

在网页上申请成功后，点击"查看"，通过二次验证后，就可以获取到。

**2.APIKey 的passphrase忘记了可以找回吗？**

无法找回，只能在页面重新申请APIKey。

**3.APIKey 授权第三方有风险吗？**

APIKey授权第三方有一定的风险，为了账户资产安全建议自己保存。

**4. 没有绑定手机或者谷歌验证器，能申请APIKey吗？**

不可以，申请APIKey必须绑定手机或者谷歌验证器。

**5.V3 创建APIKey的时候，必须绑定IP地址才可以创建吗**

不是必须，申请APIKey时绑定IP这个选项是非必填的，但为了增加用户账户安全性，建议绑定IP地址。

**6. 同一个账户里的不同的APIKey，返回的账户信息数据，会不同吗？**

同一个账户下不同APIKey数据是相同的。

**7. 一个账户可以申请多少个APIKey？**

答：每个母账户可创建50组APIKey，每个APIKey可对应设置只读、交易、提币三种权限。另外，每个子用户可创建50组APIKey，每个APIKey可对应设置只读、交易两种权限。

三种权限的说明：

1）只读权限：读取权限用于对数据的查询接口，例如：订单查询、成交查询等。

2）交易权限：交易权限用于下单、撤单、资金划转类接口。

3）提币权限：提币权限用于提币接口操作。

**8. 申请APIKey时如何填写**

根据网页端提示填写，备注可根据用户需求随意填写；Pass密码要记住，调用API接口会用到；绑定ip为非必填项，为了账户安全建议填写；API权限可根据用户需求勾选。

**9.passphrase 是登录密码还是资金密码**

passphrase是APIKey的密码，查看APIKey和调用API接口都需要输入这个密码；需要注意的是，passphrase忘记之后是无法找回的，需要重新创建APIKey。

### 验签问题

**1. 请求接口的timestamp参数和到达服务器时间最大差值是多少？**

时间戳和API服务器时间前后相差30秒以上的请求将被系统视为过期并拒绝。如果用户服务器和API服务器之间存在较大的时间偏差，建议用户使用"获取服务器时间"的接口来查询API服务器时间。

**2. 请求头"OK_ACCESS_TIMESTAMP"不能为空 如何解决？时不时产生这个错误?**

首先建议用户打印一下OK_ACCESS_TIMESTAMP，出现异常时检查OK_ACCESS_TIMESTAMP是否为空，另外建议用户代码优化，每次请求前先判断OK_ACCESS_TIMESTAMP是否为空。

**3.V3API 使用的时间戳是哪里的时间？**

UTC 0时时间格式。

**4. 为什么签名认证总返回无效签名（code为30013）？**

签名不正确导致的:

1)可以使用下面的SDK，签名部分已经封装好了，可以直接调试调用：

[SDK(python java c# php node go c++ )](https://github.com/okex/V3-Open-API-
SDK)

2)如果是自己编写签名函数，请务必一步步地参照如下描述：

OK-ACCESS-SIGN的请求头是对timestamp + method + requestPath +
body字符串(+表示字符串连接)，以及SecretKey，使用HMAC SHA256方法加密，通过Base64编码输出而得到的;

检查时，可以打印出请求头信息和签名前字符串，重点有以下几点：

(1) 将您的请求头和下面的请求头示例一一对比，

    
    
    请求头示例：
    
    Content-Type: application/json
    
    OK-ACCESS-KEY: 37c541a1-****-****-****-10fe7a038418
    
    OK-ACCESS-SIGN: leaVRETrtaoEQ3yI9qEtI1CZ82ikZ4xSG5Kj8gnl3uw=
    
    OK-ACCESS-PASSPHRASE: 1****6
    
    OK-ACCESS-TIMESTAMP: 2020-03-28T12:21:41.274Z
    

(2) 是否在程序中正确地配置了APIKey，

(3) 签名前字符串是否符合标准格式，所有要素的顺序要保持一致，可以复制如下示例跟您的签名前字符串进行比对：

    
    
    GET示例： 2020-03-28T12:21:41.274ZGET/api/general/v3/time
    
    POST示例：2020-03-28T12:21:581ZPOST /api/account/v3/transfer{"currency":"usdt","amount":"1.5","from":"6","to":"3","to_instrument_id":"btc-usdt"}（usdt从资金账户划转到交割btc-usdt合约账户）`<br>
    
    
    如果是POST，务必将请求 body 拼接在签名前字符串后面;
    

(4) 签名结果（OK-ACCESS-
SIGN）的长度应为44位，如：6t56DBHUhMoCylVvGJka4S+Ac6RQO76/P4GyvjsDoXU=，如果长度为88位，是对签名结果进行了16进制编码导致，请确保签名结果为2进制后，再进行签名。

(5)
如果是websocket，签名前字符串是:1585403514.843GET/users/self/verify，不论哪个频道，路径都统一使用：/users/self/verify，同时确保时间戳有三位小数，总长度为14位，如：1585403514.843.

**5. 调用接口提示Invalid Content_Type (code为30007),是什么原因？**

POST请求头header中Content-Type设置不合适导致。请确保POST请求头header，声明了Content-
Type，并声明为：application/json.

### 域名问题

**1.www.okex.me 可以调v3的接口吗?**

OpenAPI请求地址的域名是www.okex.com，www.okex.me
的域名是提供给国内用户免费且方便登录的域名，建议用户优先使用www.okex.com 域名。

**2.OKEx 站wss地址是什么？**

wss://real.okex.com:8443/ws/v3

**3.<https://www.okex.com> 与 <https://aws.okex.com> 有什么区别？**

<https://aws.okex.com> 域名是对使用aws云服务的用户做了链路延迟优化，请求时延迟更低。另外，香港阿里云服务器用户建议使用
<https://www.okex.com>

### 限速问题

**1.API 每秒调用频率有限制吗？**

有限制，具体可以看下文档中每个接口的访问频率限制。

**2.OKEx 的API的访问频率是根据什么限制的？**

个人数据是根据UserID限制的，公共数据是根据ip限制，需要注意的是，若用户请求公共数据时传入有效的个人信息就根据UserID限制。

**3.HTTP 状态码429是怎样造成的？**

请求接口超过访问频率限制，建议降低访问频率。

**4.API 调用接口报超过访问频率会被封IP吗？封多久？**

不会的，降低访问频率就可以。

**5. 访问接口报错超频，怎么解决？**

降低访问频率，文档的每个接口下方都有频率说明，需要将请求频率降低到频率说明之下。

关于限速，

1）rest接口，公共数据根据ip限速，
私有数据根据UserID限速，公共数据传个人信息时就根据UserID限速；WebSocket所有频道，都是根据ip来限制的；

2）每个子账户是独立的UserID ,请求次数与母账户是相互独立，不会累加的；

3）超频不会封IP的，降低访问频率就可以

### 账户问题

**1. 账户里有资产，为什么不能交易？**

OKEx账户分为资金账户、交易账户和其他账户，其中交易账户包括币币账户、币币杠杆账户、交割合约账户、永续合约账户、期权合约账户和法币账户，其他账户包括余币宝账户和挖矿账户。

为了用户更方便地管理资产和控制风险，每个账户内资产是独立且可以相互划转的，若用户需要进行币币或合约交易，需要通过资金划转接口将资产划转到相应的币币或合约账户才能进行交易。

**2. 每个子账户的API请求次数都是独立计算的么？**

是的，子账户和母账户是分开计算，相互独立的。

**3. 母账户可以通过自己的API来获取子账号的账户余额信息吗？**

可以，调用"获取子账户余额信息"接口。

**4. 子账户的币，如何提到外部地址？**

需要先划转到子账户的资金账户，然后通过母账户的APIKey调用API资金划转接口，划转到母账户的资金账户，在母账户的页面上将提币地址添加为免验证，从母账户资金账户进行提币操作。

**5. 子账号和母账户的区别是什么？**

子账户不能提币,充币和进行法币交易。

**6. 如何判断 USDT 哪条链是可以充提币的？**

通过"提币手续费"、"获取充值地址"这两个接口的返回值进行判断，同时请求参数 currency 需传入USDT

1）关于提币，通过"提币手续费"接口，返回了min_fee字段（包括0）的usdt，代表可以提币，否则不可以提币；

2）关于充币，"获取充值地址"接口，返回了充值地址address的usdt，代表可以充币，否则不可以充币。

**7. 创建提币时fee字段应该怎么填？**

可以从"提币手续费"拿到"最小提币手续费数量"和"最大提币手续费数量"，在这个范围内任选一个值进行填写。

如果想提高到账速度，可以让手续费，接近最大提币手续费数量。

**8. 账户有资金，调用资金账户接口但是返回数据是空？**

用户可在页面上检查对应的业务账户是否有资产，每个业务账户的资产都需要用对应业务线的"账户信息"接口查询资产信息。

**9.API 提币地址必须是认证地址吗？**

是的，API提币地址，必须要在web页面上认证为免验证地址，才可以进行API提币。

### 公共问题

**1. 分页是怎样使用的？**  
1）用户第一次请求接口可以不用before、after参数，直接请求接口。  
2）返回该接口默认100条数据和包含一个OK-BEFORE和OK-AFTER标头的headers，OK-AFTER指向的是较旧的ID，OK-
BEFORE指向的是较新的ID。  
3）例如返回订单ID为：10，9，8，7，6，则OK-BEFORE=10，OK-
AFTER=6。再次请求接口时，可以使用before和after参数，使用after=6返回的是5，4，3等更旧的订单数据，使用before=10，返回的是11，12，13等更新的订单数据，每次请求接口想要多少条数据可以用limit参数来限制。  
**举 例**  
1）GET /api/futures/v3/orders/BTC-USD-190628?state=2（返回合约BTC-
USD-190628的最近100条全部成交订单）  
2）GET /api/futures/v3/orders/BTC-USD-190628?state=2&limit=20（返回合约BTC-
USD-190628的最近20条全部成交订单）  
3）GET /api/futures/v3/orders/BTC-
USD-190628?state=2&after=2512669605501952&limit=20（返回合约order_id=2512669605501952更旧的20条全部成交订单，不包括2512669605501952）  
4）GET /api/futures/v3/orders/BTC-
USD-190628?state=2&before2512669605501952&limit=20（返回合约order_id=2512669605501952更新的20条全部成交订单，不包括2512669605501952）

**2. 为什么WebSocket总是断开连接？**

WebSocket断连常见原因有：

（1）未添加心跳，WebSocket连接需客户端主动发送ping服务器返回pong，保证连接的稳定。

（2）网络原因造成客户端发送了ping消息，但服务端并未接收到，或其他网络原因也会导致自动断开连接。

建议用户做好WebSocket断开重连机制，在确保心跳（ping/pong）连接意外断开时，程序能够自动重新进行连接。

**3. 用户请求接口报错Time Out？**

网络无法连接服务器，建议您检查下网络是否通畅，同时建议使用香港阿里云服务器。

**4. 为什么经常出现断开、超时的情况？**

客户端服务器如在中国大陆境内，连接的稳定性很难保证，建议使用香港阿里云服务器进行访问。

建议用户使用 <https://www.okex.com> 或 <https://aws.okex.com> 域名。

**5.WebSocket 最多可以订阅多少个币对呢？是否有限制?**

用户可以选择订阅一个或者多个频道，订阅多个频道总长度不能超过4096个字节。

### 接口功能问题

**1. 在哪里能拿到平台所有的币对？**

币币的"获取币对信息"接口可以拿到，交割合约和永续合约的"获取合约信息"接口可以拿到。

**2. 行情接口是哪个？**

可以使用"获取全部ticker信息"接口，也可以使用"获取深度数据"接口。

**3.K 线能拿到历史数据吗？**

币币最多获取1440条，交割合约和永续合约最多获取1440条。

**4. 哪个接口能拿到K线图上技术指标数据？**

目前API暂不提供相关接口。

**5.API 下单撤单总的数量有限制吗？**

合约市价委托有张数限制，其他委托存在仓位档位的限制，撤单没有限制。

**6. 有可以获取账户等级/费率的API吗？**

暂无获取账户等级接口，使用"获取当前手续费费率"接口可以获取账户费率。

**7.V3 的深度频道接口，首次返回400档，后续增量怎么理解？**

首次返回400条全量数据，有深度变化100毫秒推送一次，快照这个时间段内有更改的订单簿数据。后续增量出来的是需要在400条数据基础上修改，按照价格去判断是哪一档的变化。

**8.client_oid 是什么，有什么作用？**

1）client_oid是您自定义的订单号，可以用来标识您的一笔订单，当下单完成后，可以使用client_oid调用"订单信息"接口，查看订单状态；

2）client_oid的类型为字母（大小写）+数字或者纯字母（大小写），1-32位字符
用户需要自己保证此ID不重复，我方不会进行排重提示，如有重复，撤单和查询订单时只能撤销或者查询最新的一条数据

**9. 如何获取最新成交价格？**

有两个方法可以获取：

1）可以用"获取成交数据"接口获取，最近一笔的成交价格，就是最新成交价；

2）也可以用"获取某个ticker信息"接口获取，会直接返回最新成交价；

如果要更及时地获取最新成交价，建议使用方法1获取。

**10.ticker 接口中的24小时成交量会出现负增长吗？**

会的。因为24小时成交量，为24小时滚动数据（平移窗口大小24小时），有可能会出现后一个窗口内的累计成交量、累计成交额小于前一窗口的情况。

**11.K 线是按照什么时间开始计算的？**

K线接口的开始时间，是该根K线的开始时间，因为用的是 UTC 时间，所以会与北京时间相差8小时。

**12. 如何获取平台的所有的币和配置信息，如名称、精度、最小数量等？**

不同业务线，有不同的接口。

1)资金账户："获取币种列表"接口

2)币币账户："公共-获取币对信息"接口（也适用于币币杠杆）

3)币币杠杆："杠杆配置信息"接口

4)交割合约："公共-获取合约信息"接口

5)永续合约："公共-获取合约信息"接口

6)期权合约："公共-获取期权合约"接口

### 币币/杠杆问题

**1. 为什么币币和币币杠杆的获取成交明细接口1笔交易会返回2条数据？**

因为这个接口一笔成交会返回2条数据，一个以计价货币计算的，一个是以交易货币计算的。

**2. 为什么收到订单成功成交的消息后再次进行下单，返回余额不足？**

可以稍后再试。为保证订单的及时送达以及低延时， 订单推送的结果是在撮合后直接推送，此时订单可能并未完成资产的清算。

建议使用以下方式保证资金可以正确下单：

1）使用 WebSocket 的 accounts 频道，同步接收资产变更的消息，确保资金已经完成清算。

2）收到订单推送消息时，使用rest接口调用账户余额，验证账户资金是否足够，使账户中保留相对充足的资金余额。

**3. "杠杆配置信息"返回的当前最大可借，是考虑了所有因素的么？**

是考虑了所有因素，如资金池、账户余额等，代表您当前最大可借的币数。

### 合约问题

**1.V3API 合约开单数量是以张为单位还是以币为单位？**

API合约下单的size都是以张为单位，必须是大于或等于1的整数

**2. 合约大数据里的数据接口能拿到吗？**

目前API暂无相关接口。

**3. 如何区分合约的订单是否是被强平的？**

交割合约，可以通过"账单流水"接口的type字段判断，有相关order_id的那一条记录，type为liquidation时，且流水产生在非交割时间，说明该订单是强平单;

永续合约，"获取订单信息"接口，返回参数中有trigger_price字段，说明该订单是强平单。

**4. 用户可以通过API修改永续合约和交割合约的杠杆倍数吗？**

可以通过"设定合约杠杆倍数"接口修改。

前提是没有相关挂单，不然会报错（32066：当前存在挂单，请撤销所有挂单后进行杠杆倍数修改 ）。

**5. 交割合约用户当前没有持仓；为什么调用全部合约持仓信息接口有数据返回呢？**

获取全部持仓信息接口，只要是在合约的生命周期内下过单的，这个接口都能获取到距离最近一次的仓位信息；要判断有没有持仓需要判断这个接口返回参数中long_qty和short_qty的数据。

**6.V3 合约深度频道接口 首次返回全量，后续增量这个怎么理解？**

首次返回的是全量数据，后续为节省服务器和客户端的资源，仅推送变化了的增量部分，可以按照价格去判断是哪一档的变化，与前面最近的全量进行合并。

**7. 为什么会触发了下单限价错误？**

因为下单价格在限价之外，可以从以下几个方面进行排查：

1）价格设置超过了限价范围，请重新设置下单价格，确保价格在限价内，当前限价可以通过"当前限价"接口获取；

2）若在限价内，由于行情是实时变化的，行情波动太快的情况下，是会造成这个情况的，可以重新下单；限价规则可以参考公告：<https://okexsupport.zendesk.com/hc/zh-
cn/articles/360039317072>

### API概述

市场概况和基础信息

### **一 、账户总述：**

OKEx账户分为资金账户、交易账户和其他账户，其中交易账户包括币币账户、币币杠杆账户、交割合约账户、永续合约账户、期权合约账户和法币账户，其他账户包括余币宝账户和挖矿账户。为了用户更方便地管理资产和控制风险，每个账户内资产是独立且可以相互划转的，若用户需要进行币币或合约交易，需要通过资金划转接口将资产划转到相应的币币或合约账户才能进行交易。  

资金划转接口： `POST /api/account/v3/transfer` 可以将某一账户中的资产划转到其他账户(如币币账户、交割合约账户等）:  
①由于币币杠杆、交割合约和永续合约又分为标的货币和交易货币(合约交易中叫做保证金)，因此在进行交易时，用户可以将资产从币币杠杆账户的某一杠杆币对的指定币种下划转到交割合约、永续合约的某一合约账户的相同币种下(如可将ETH从ETH/USDT杠杆账户划转到ETH/USD交割合约账户)。  
②交割合约账户和永续合约账户中，币本位合约账户中只能转入标的货币如BTC、ETH等作为保证金，USDT合约账户中只能转入USDT作为保证金。  

以下分别是各个账户的介绍和API提供的接口：  
1）资金账户

资金账户是管理出入金的账户，显示的是用户当前资金账户中的资产，空投、糖果、以及活动奖励也会发送至您的资金账户(领取需要您去web端操作)。通过充币，可以将资产充入用户的资金账户；通过提币，可以将资产提至用户个人钱包或其他平台。  

`GET/api/account/v3/wallet` 和 `GET/api/account/v3/wallet/<currency>`
分别可以查询资金账户内所有币种和单个币种的余额、冻结、和可用额度。  

2）币币账户

币币账户是进行币币交易的资产账户，显示的是用户当前币币账户中的资产。要进行币币交易，需将资产划转至币币账户中，币币账户中的资产可以用于币币交易区的所有交易对。  

`GET/api/spot/v3/accounts`和`GET/api/spot/v3/accounts/<currency>`
分别可以查询币币账户内所有币种和单个币种的余额、冻结、和可用额度。  
  
3）杠杆账户

杠杆账户是进行杠杆交易的资产账户，显示的是用户当前杠杠账户中的资产。杠杆账户是分币对的独立账户，各杠杆币对的资产互相独立，风险分币对控制。要进行某个币对的杠杆交易，需将资产转至该币对的杠杆账户中的标的货币或交易货币，且支持同币种不同杠杆币对账户之间直接划转(如可将ETH从ETH/USDT杠杆账户划转到ETH/BTC杠杆账户)。  
  
`GET/api/margin/v3/accounts` 可以查询币币杠杆账户内所有币种的余额、冻结、可用额度和风险率等信息。  
  
4）交割合约账户  
  
交割合约账户是进行交割合约交易的资产账户，显示的是用户当前交割合约账户中的资产。根据保证金类型，交割合约分为USDT保证金交割合约和币本位保证金交割合约。两种合约下，每个标的货币对应的合约都有独立的交易账户，单独核算收益和风险。币本位合约账户中只能转入标的货币如BTC、ETH等作为保证金，USDT合约账户中只能转入USDT作为保证金。  
  
`GET/api/futures/v3/accounts`和`GET/api/futures/v3/accounts/<underlying>`分别可以查询交割合约账户内所有合约和单个合约的账户权益、账户余额、已实现盈亏、未实现盈亏等信息。  
  
5）永续合约账户  
  
永续合约账户是进行永续合约交易的资产账户，显示的是用户当前永续合约账户中的资产。根据保证金类型，永续合约分为USDT保证金永续合约和币本位保证金永续合约。两种合约下，每个标的货币对应的合约都有独立的交易账户，单独核算收益和风险。币本位合约账户中只能转入标的货币如BTC、ETH等作为保证金，USDT合约账户中只能转入USDT作为保证金。  
  
`GET/api/swap/v3/accounts`和`GET/api/swap/v3/<instrument_id>/accounts`
分别可以查询永续合约账户内所有合约和单个合约的账户权益、账户余额、已实现盈亏、未实现盈亏等信息。  
  
6）期权合约账户  
  
期权合约账户是进行期权合约交易的资产账户，显示的是用户当前期权合约的账户资产。目前，OKEx上线了BTC期权，用户可以在期权合约账户中以BTC进行交易。  
  
`GET/api/option/v3/accounts/<underlying>`
可以查询期权合约账户内BTC合约的账户权益、账户余额、已实现盈亏、未实现盈亏等信息。  
  
7）法币账户  
  
法币账户是进行法币交易的资产账户，显示的是用户当前法币账户中的资产。用户可用法定货币按照一定的价格兑换为数字货币，兑换后的数字货币资产将存于法币账户中。  
  
`POST /api/account/v3/transfer`
可以将资产从法币账户划转到其他账户(如币币账户、交割合约账户），或从其他账户划转到法币账户，目前暂无支持法币余额查询或法币交易的接口。  
  
8）余币宝账户  
  
余币宝账户是使用余币宝服务的资产账户，显示的是用户当前余币宝账户的资产。用户将资产转入余币宝账户中，系统即自动开始为用户计算收益，用户将资产转出余币宝，则停止计算收益。  
  
`POST /api/account/v3/transfer`
可以将资金从余币宝账户划转到其他账户(如币币账户、交割合约账户等），或从其他账户划转到余币宝账户，目前暂无其他如查询余币宝余额等数据的接口。  
  
9）挖矿账户  
  
挖矿账户是用于OKEx矿池挖矿服务的资产账户，显示的是用户当前挖矿账户的资产余额。用户可以用挖矿账户中的余额参与锁仓挖矿等产品，用户在OKEx矿池中的挖矿收益也会打入挖矿账户中的相应币种。  
  
`POST /api/account/v3/transfer`
可以将资金从挖矿账户划转到其他账户(如币币账户、交割合约账户等），或从其他账户划转到挖矿账户，目前暂无其他如查询挖矿收益等数据的接口。  
  

10）借贷账户  
  
借贷账户是使用C2C借贷服务的资产账户，显示的是用户当前借贷账户的资产。用户将资产转入借贷账户中，用户可将资产用于借贷和投资。  
  
`POST /api/account/v3/transfer`
可以将资金从借贷账户划转到其他账户(如币币账户、交割合约账户等），或从其他账户划转到借贷账户，目前暂无其他借贷功能的接口。  
  

#### **各 账户功能对比**

| **是 否可资金划转** | **是 否可交易** | **业 务是否支持API接口**  
---|---|---|---  
**资 金账户** | 是 | 否 | 是  
**币 币账户** | 是 | 是 | 是  
**币 币杠杆账户** | 是 | 是 | 是  
**交 割合约账户** | 是 | 是 | 是  
**永 续合约账户** | 是 | 是 | 是  
**期 权合约账户** | 是 | 是 | 是  
**法 币账户** | 是 | 是 | 否  
**余 币宝账户** | 是 | 否 | 否  
**挖 矿账户** | 是 | 否 | 否  
**借 贷账户** | 是 | 否 | 否  
  
### **二 、账户结构**

  
从账户结构上讲，OKEx又分为主账户和子账户，一个主账户下可以申请个多个子账户，子账户是附属于OKEx主账户的一种账户类型。子账户具有独立的帐号和密码，可以通过主账户分权限管理，将部分资产划转到子账户中，即可独立于主账户进行币币、杠杆、合约、期权等交易。子账户不具备提现功能，可以将子账户的资金划转至主账户，然后通过主账户提现。  
  
子账户不仅可以继承主账户的费率等级和KYC信息，而且主账户和子账户的请求次数独立计算，增加用户交易频率的同时更方便管理。  
  
`POST /api/account/v3/transfer` 可以将资金从主账户划转到子账户的币币、交割合约等账户。  
  
`GET/api/account/v3/sub-account` 可以获取子账户中各个账户里的余额、冻结和可用额度等信息。  
  

#### **主 账户和子账户对比**

| **是 否可资金划转** | **是 否可交易** | **是 否独立账号密码** | **是 否独立请求频率** | **是 否独立费率标准** |
**是 否独立KYC信息**  
---|---|---|---|---|---|---  
主账户 | 是 | 是 | 是 | 是 | 是 | 是  
子账户 | 是（限制如上所述） | 是 | 是 | 是 | 否，同主账户 | 否，同主账户  
  
#### 交易

**1 ）币种**

币种是指能够转入转出的基本单位，如BTC,ETH,EOS等。

**2 ）币对**

币对是由交易货币和计价货币组成。以BTC/USDT 为例，BTC 为交易货币，USDT 为计价货币，币对主要在币币交易区和杠杆交易区使用。

**3 ）合约ID**

合约ID是合约交易的基本单位，其中包括标的货币、保证金类型和交割日期。以BTC-
USD-190328为例，BTC为标的货币，BTC为保证金类型，190328为交割日期是2019年3月28日。根据保证金类型的不同，可分币本位保证金合约和USDT保证金合约。

#### 订单、成交相关ID说明

**1 ）order_id**

订单编号，每个业务线的同一币对下的订单ID是唯一的。

**2 ）client_oid**

客户自定义编号，为下单时的非必填参数，格式是字母（区分大小写）+数字 或者
纯字母（区分大小写），1-32位字符，建议用户定义的client_oid不要重复，否则多个order_id对应同一个client_oid时，查询将返回最近一个order_id

**3 ）trade_id**

成交的唯一编号

**4 ）ledger_id**

账单流水的唯一编号

#### 订单种类:

**1 ）limit**

限价委托规定了用户愿意买的最高价格或愿意卖的最低价格。用户在设定限价后，市场会以达到对有利方向的价格优先成交。

**2 ）market**

市价委托类型订单仅需指定下单金额或下单数量，不需要指定价格，订单在进入撮合时，会直接与对手方进行成交，直至金额或数量低于最小成交金额或成交数量为止。市价委托同样受限价机制限制。

**3 ）Post only**

默认是"只做Maker（Post only）"，不会立刻在市场成交，保证用户始终为Maker；如果委托会立即与已有委托成交，那么该委托会被取消。

**4 ）FillOrKill**

如果你的委托被设置为"全部成交或立即取消（FillOrKill）"，该委托只会立即全部成交，否则将被取消。

**5 ）ImmediatelOrCancel**

如果你的委托被设置为"立即成交并取消剩余（ImmediatelOrCancel）"，任何未被成交的部分将被立即取消。

**6 ）止盈止损委托**

预先设置限价/市价委托及其触发价格，当市场上的最新成交价达到预设的触发价格时，系统将委托送入市场。

**7 ）跟踪委托**

在行情发生较大幅度回调的情况下，将客户事先设定的委托送入市场的策略。当市场的最新价格达到投资者设定该策略后最高（最低）市场价格的（1±客户设定回调幅度）后，即会触发客户设定的策略，将客户事先设定的委托以市价送入市场中。

**8 ）冰山委托**

投资者在进行大额交易时，为避免对市场造成过大冲击，将大单委托自动拆为多笔委托，根据当前的最新买一/卖一价格和客户设定的价格策略自动进行小单委托，在上一笔委托被全部成交或最新价格明显偏离当前委托价时，自动重新进行委托。

**9 ）时间加权委托**

客户希望大额交易BTC时，为避免过大冲击成本，通过策略将大单拆细为多个小额委托，根据最新的对手方委托量自动选择委托量，主动与对手方成交进行连续买入的策略。

#### 订单状态

1）失败：该状态订单由于余额不足等原因不能校验通过进入撮合队列；

2）等待成交：该状态订单已进入撮合队列当中；

3）部分成交：该状态订单在撮合队列当中，订单的部分数量已经被市场成交，等待剩余部分成交；

4）完全成交：该状态订单在撮合队列当中已与对手方完全成交；

5）下单中：该状态订单正在下单的过程中，因订单最终需挂在撮合队列中才真正下单成功，所以此状态为中间过渡态；

6）撤单中：该状态订单正在被撤销的过程中，因订单最终需在撮合队列中剔除才会被真正撤销，所以此状态为中间过渡态。

### 撮合引擎

本章节主要为撮合引擎的细节分以下四个方面：

  * 成交价
  * 订单生命周期
  * 币币交易限价规则
  * 合约交易限价规则

#### 成交价

OKEx撮合系统撮合订单的优先级按照价格优于时间的优先级来撮合，优先撮合价格更有优势的订单。当价格一致时按照下单时间顺序撮合，先下单的先撮合。

比如深度列表中目前有3笔挂单等待成交，分别为1: 9900USDT买1BTC，2: 10100USDT买2BTC，3:
9900USDT买1.5BTC。他们是按时间顺序1-2-3进入撮合系统的，根据价格优先，系统优先撮合订单2，根据时间优先，1跟3优先撮合1。所以系统撮合顺序是2-1-3。

订单撮合时成交价将按maker挂单价格成交，而非taker吃单价格。

例如：A用户在10000USDT挂了1BTC的买单，然后B用户以8000USDT的价格下了1BTC的卖单，因为A用户的订单先进入撮合系统挂在深度列表上，所以以A的价格为准，最终这笔订单最终以10000USDT成交。

#### 订单生命周期

订单进入撮合引擎后是"等待成交"状态；

如果一个订单被撮合而全部成交，那么它会变成"完全成交"状态；

一个订单被撮合可能出现部分成交，那么它的状态会变成"部分成交"状态，并且继续留在撮合队列中进行撮合；

一个未成交订单撤单成功，，那么它的状态会变成"已撤销"状态；

发起撤销到完成撤销的过程中有一个过程状态"撤单中"；

被撤销或者全部成交的订单将被从撮合队列中剔除。

#### 币币交易限价规则

为了防止用户下错大单造成市场异常波动和个人资金损失，OKEx币币交易设置了FOK限价规则：如果用户在币币交易所下的市价单/限价单可以与当前买卖盘内订单直接成交，那么系统会判断成交深度对应的价格与同方向盘口价的偏差是否超出5%。如果超过，则此订单将被系统立即全数撤销，否则此订单正常进行撮合。

例如：某用户在XRP/BTC交易区下了100BTC的市价买单(此时卖一价为0.00012)，系统判断订单完成成交后最新成交价为0.0002。此时，(0.0002-0.00012)/0.00012=66.7%>5%，用户的这笔市价买单将被立即撤销，不会和买卖盘内订单进行撮合。

#### 合约交易限价规则

**一 、交割合约限价机制调整为：**

新合约生成10分钟内：最高价=现货指数（1+5%），最低价=现货指数（1-5%）。

合约生成了10分钟后：

最高限价=Min【 Max（Index，Index _1.03+ 过去十分钟溢价均值），Index_1.25】；

最低限价=Max【Min（Index，Index _0.97+ 过去十分钟溢价均值），Index_0.75】；  
  
**二 、永续合约限价机制调整为：**

新合约生成10分钟内：最高价=现货指数（1+0.5%），最低价=现货指数（1-0.5%）。

合约生成了10分钟后：

最高限价=Min【 Max（Index，Index _1.01+ 过去十分钟溢价均值），Index_1.02】；

最低限价=Max【Min（Index，Index _0.99+ 过去十分钟溢价均值），Index_0.98】；

注：

Index：现货指数价格

过去十分钟溢价均值计算如下：

获取合约、现货指数的过去10分钟的1分钟K线数据，计算每分钟的（开盘价+收盘价）／2，并计算合约及指数的差，对过去10分钟的差值取平均值。

以上规则，适用于所有币种合约（包含USDT合约与币本位合约），合约开平仓都受限制，若开多或平空，当委托价高于最高价，则将触发限价；若开空或平多，当委托价低于最低价，则将触发限价。

### 费用

本章节主要为费用的细节分以下两个方面：

  * 交易费用
  * 充/提币费用

#### 交易费用

OKEx采用maker-taker收费规则，为鼓励挂单，maker挂单成交的手续费会比taker吃单成交的手续费低。

同时，为了鼓励成交，OKEx推出阶梯手续费政策，根据你前30天的累计交易量划分不同的手续费等级，成交量越高，手续费等级越高，手续费越低。  
除了手续费优惠，OKEx还为提供流动性的专业用户提供了市商计划。参与市商计划后，只要您能够提供稳定的深度以及盘口点差，即可获得Maker手续费返还。  
[详情请查看(点击跳转至费率详情页面)](fees.html)

#### 充/提币费用

OKEx不收取任何充币/提币费用，提现数字货币的过程中产生的矿工手续费需要用户自己承担。

### 服务器

OKEx的数据库和服务器运行在香港。为了最大限度地减少API访问延迟，建议您使用与香港通讯通畅的服务器。

### 请求

本章节主要为请求的细节分以下三个方面：

  * 介绍
  * 错误
  * 成功

#### 介绍

Rest API提供账户管理、行情查询和交易功能。

Rest API终端URL <https://www.okex.com/>

同时OKEx还提供了WebSocket流，订阅WebSocket可以获取行情数据的推送。

WebSocket地址：wss://real.okex.com:8443/ws/v3

所有请求基于Https协议，请求头信息中Content-Type需要统一设置为:'application/json'

请使用大陆以外的IP地址访问OKEx的API，强烈建议使用香港阿里云服务器。

如果你的服务器在AWS,可以尝试使用我们AWS的网关，有可能会获得更快的速度。

Rest API终端URL：<https://aws.okex.com/>

WebSocket地址 :wss://awspush.okex.com:8443/ws/v3

不建议用户通过网络代理的方式请求OKEx的api，会造成较高延迟和网络稳定差。

#### 错误

除非特殊说明，错误请求都通过HTTP
4xx或者状态码进行返回，返回内容还将包含错误原因、参数信息。您的HTTP库应配置为非2xx请求提供消息主体，以便您可以从主体读取消息字段。

##### 常见错误码

400 | Bad Request -- Invalid request fotmat  
---|---  
**401** | **Unauthorized -- Invalid APIKey**  
**403** | **Forbidden -- You do not have access to the requested resource**  
**404** | **Not Found**  
**500** | **Internal Server Error -- We had a problem with our server**  
  
#### 成功

HTTP状态码200表示成功响应，并可能包含内容。如果响应含有内容，则将显示在相应的返回内容里面。

### 分页

OKEx对返回数组的有些REST请求使用游标分页。游标分页允许在当前结果页面之前和之后获取结果，并且非常适合实时数据。端点如/ trades，/
fills，/ orders，默认返回最新100项。要检索更多结果，后续请求应根据先前返回的数据指定要分页的方向。

`before`和`after`游标可以通过响应头`OK-BEFORE`和`OK-AFTER`。在初始请求之后发出页面请求时，您的请求应使用这些游标值。

例 `GET /api/spot/v3/orders?before=2&limit=30`

参数名 | 参数类型 | 描述  
---|---|---  
after | String |
请求此id之前（更旧的数据）的分页内容，传的值为对应接口的`order_id`、`ledger_id`或`trade_id`等  
before | String |
请求此id之后（更新的数据）的分页内容，传的值为对应接口的`order_id`、`ledger_id`或`trade_id`等 |  
limit | String | 分页返回的结果集数量，最大为100，不填默认返回100条  
  
游标之前和之后 将before光标引用在结果页中的第一项和after光标引用了一组结果的最后一个数据。

headers将包含一个OK-
BEFORE标头，该标头将返回光标id，以便在当前页面的下一个页面请求中使用。之前的页面是一个较新的页面，而不是在按时间顺序排列之前发生的页面。
响应还将包含一个OK-
AFTER标头，该标头将返回光标id，以便在此页面之后的页面的下一个请求中使用。之后的页面是较旧的页面，而不是按时间顺序排在此页面之后的页面。

##### 举例

1、`GET /api/futures/v3/orders/BTC-USD-190628?state=2`（返回合约`BTC-
USD-190628`的最近100条全部成交订单）

2、`GET /api/futures/v3/orders/BTC-USD-190628?state=2&limit=20`（返回合约`BTC-
USD-190628`的最近20条全部成交订单）

3、`GET /api/futures/v3/orders/BTC-
USD-190628?state=2&after=2512669605501952&limit=20`（返回合约`order_id=2512669605501952`更旧的20条全部成交订单，不包括`2512669605501952`）

4、`GET /api/futures/v3/orders/BTC-
USD-190628?state=2&before2512669605501952&limit=20`（返回合约`order_id=2512669605501952`更新的20条全部成交订单，不包括`2512669605501952`）

### 标准规范

本章节主要为标准规范的细节分以下三个方面：

  * 时间戳
  * 数字
  * ID

#### 时间戳

除非另外指定，API中的所有时间戳均以毫秒为单位返回，符合ISO 8601标准。请确保您可以解析ISO 8601格式。

##### 例子

`2014-11-06T10:34:47.123Z`

#### 数字

为了保持跨平台时精度的完整性，十进制数字作为字符串返回。建议您在发起请求时也将数字转换为字符串以避免截断和精度错误。

整数（如交易编号和顺序）不加引号。

#### ID

除非另有说明，大多数标识符是UUID。当提出一个需要UUID的请求时，以下两个形式（有和没有破折号）都被接受。

`132fb6ae-456b-4654-b4e0-d681ac05cea1`或者`132fb6ae456b4654b4e0d681ac05cea1`

### 接口类型

本章节主要为接口类型的细节分以下两个方面：

  * 公共接口
  * 私有接口

#### 公共接口

公共接口可用于获取配置信息和行情数据。公共请求无需认证即可调用。

#### 私有接口

私有接口可用于订单管理和账户管理。每个私有请求必须使用规范的验证形式进行签名。

私有接口需要使用您的APIKey进行验证。您可以在[这里](https://www.okex.com/account/my-api)生成APIKey。

### 访问限制

本章节主要为访问限制的细节分以下两个方面：

  * Rest API
  * WebSocket

当访问超过频率限制时，将返回429状态：请求太频繁。

#### Rest API

如果传入有效的APIKey 用UserID限速；如果没有则拿公网IP限速。

限速规则：各个接口上有单独的说明，如果没有一般接口限速为 6次/秒。

特殊说明：批量下单时，若下4个币对，每个币对10个订单时，计为一次请求。

#### WebSocket

WebSocket将每个命令类型限制为每秒50条命令。

### 验证

本章节主要为验证的细节分以下五个方面：

  * 生成APIKey
  * 发起请求
  * 签名
  * 时间戳
  * 获取服务器时间

#### 生成APIKey

在对任何请求进行签名之前，您必须通过OKEx网站创建一个APIKey。创建APIKey后，您将获得3个必须记住的信息：

  * APIKey 
  * SecretKey 
  * Passphrase 

APIKey和SecretKey将由OKEx随机生成和提供，Passphrase将由您提供以确保API访问的安全性。OKEx将存储Passphrase加密后的哈希值进行验证，但如果您忘记Passphrase，则无法恢复，请您通过OKEx网站重新生成新的APIKey。

#### 发起请求

所有REST请求头都必须包含以下内容：

`OK-ACCESS-KEY`字符串类型的APIKey。

`OK-ACCESS-SIGN`使用Base64编码签名(请参阅签名)。

`OK-ACCESS-TIMESTAMP`发起请求的时间戳。

`OK-ACCESS-PASSPHRASE`您在创建API密钥时指定的Passphrase。

所有请求都应该含有application/json类型内容，并且是有效的JSON。

#### 签名

`OK-ACCESS-SIGN`的请求头是对`timestamp + method + requestPath +
body`字符串(+表示字符串连接)，以及SecretKey，使用HMAC SHA256方法加密，通过Base64编码输出而得到的。

例如：`sign=CryptoJS.enc.Base64.Stringify(CryptoJS.HmacSHA256(timestamp + 'GET' +
'/users/self/verify', SecretKey))`

其中，`timestamp`的值与`OK-ACCESS-
TIMESTAMP`请求头相同，必须是UTC时区Unix时间戳的十进制秒数格式或ISO8601标准的时间格式，精确到毫秒。

method是请求方法，字母全部大写：`GET/POST`。

requestPath是请求接口路径。例如：`/orders?before=2&limit=30`

body是指请求主体的字符串，如果请求没有主体(通常为GET请求)则body可省略。例如：`{"product_id":"BTC-
USD-0309","order_id":"377454671037440"}`

SecretKey为用户申请APIKey时所生成。例如：22582BD0CFF14C41EDBF1AB98506286D'

    
    
    public enum ContentTypeEnum {
    
        APPLICATION_JSON("application/json"),
        APPLICATION_JSON_UTF8("application/json; charset=UTF-8"),
        // The server does not support types
        APPLICATION_FORM("application/x-www-form-urlencoded; charset=UTF-8"),;
    
    
        private String contentType;
    
        ContentTypeEnum(String contentType) {
            this.contentType = contentType;
        }
    
        public String contentType() {
            return contentType;
        }
    }
    
    
    public enum HttpHeadersEnum {
    
        OK_ACCESS_KEY("OK-ACCESS-KEY"),
        OK_ACCESS_SIGN("OK-ACCESS-SIGN"),
        OK_ACCESS_TIMESTAMP("OK-ACCESS-TIMESTAMP"),
        OK_ACCESS_PASSPHRASE("OK-ACCESS-PASSPHRASE"),
    
        OK_FROM("OK-FROM"),
        OK_TO("OK-TO"),
        OK_LIMIT("OK-LIMIT"),;
    
        private String header;
    
        HttpHeadersEnum(String header) {
            this.header = header;
        }
    
        public String header() {
            return header;
        }
    }
    
    import com.okcoin.commons.okex.open.api.config.APIConfiguration;
    import com.okcoin.commons.okex.open.api.constant.APIConstants;
    import com.okcoin.commons.okex.open.api.enums.ContentTypeEnum;
    import com.okcoin.commons.okex.open.api.enums.HttpHeadersEnum;
    import com.okcoin.commons.okex.open.api.exception.APIException;
    import com.okcoin.commons.okex.open.api.utils.DateUtils;
    import com.okcoin.commons.okex.open.api.utils.HmacSHA256Base64Utils;
    import okhttp3.*;
    import okio.Buffer;
    
    public class APIHttpClient {
    
        private APIConfiguration config;
        private APICredentials credentials;
    
        public APIHttpClient(APIConfiguration config, APICredentials credentials) {
            this.config = config;
            this.credentials = credentials;
        }
    
        public OkHttpClient client() {
            OkHttpClient.Builder clientBuilder = new OkHttpClient.Builder();
            clientBuilder.connectTimeout(this.config.getConnectTimeout(), TimeUnit.SECONDS);
            clientBuilder.readTimeout(this.config.getReadTimeout(), TimeUnit.SECONDS);
            clientBuilder.writeTimeout(this.config.getWriteTimeout(), TimeUnit.SECONDS);
            clientBuilder.retryOnConnectionFailure(this.config.isRetryOnConnectionFailure());
            clientBuilder.addInterceptor((Interceptor.Chain chain) -> {
                Request.Builder requestBuilder = chain.request().newBuilder();
                String timestamp = DateUtils.getUnixTime();
                requestBuilder.headers(headers(chain.request(), timestamp));
                Request request = requestBuilder.build();
                if (this.config.isPrint()) {
                    printRequest(request, timestamp);
                }
                return chain.proceed(request);
            });
            return clientBuilder.build();
        }
    
        private Headers headers(Request request, String timestamp) {
            Headers.Builder builder = new Headers.Builder();
            builder.add(APIConstants.ACCEPT, ContentTypeEnum.APPLICATION_JSON.contentType());
            builder.add(APIConstants.CONTENT_TYPE, ContentTypeEnum.APPLICATION_JSON_UTF8.contentType());
            builder.add(APIConstants.COOKIE, getCookie());
            if (StringUtils.isNotEmpty(this.credentials.getSecretKey())) {
                builder.add(HttpHeadersEnum.OK_ACCESS_KEY.header(), this.credentials.getApiKey());
                builder.add(HttpHeadersEnum.OK_ACCESS_SIGN.header(), sign(request, timestamp));
                builder.add(HttpHeadersEnum.OK_ACCESS_TIMESTAMP.header(), timestamp);
                builder.add(HttpHeadersEnum.OK_ACCESS_PASSPHRASE.header(), this.credentials.getPassphrase());
            }
            return builder.build();
        }
    
        private String getCookie() {
            StringBuilder cookie = new StringBuilder();
            cookie.append(APIConstants.LOCALE).append(this.config.getI18n().i18n());
            return cookie.toString();
        }
    
        private String sign(Request request, String timestamp) {
            String sign;
            try {
                sign = HmacSHA256Base64Utils.sign(timestamp, method(request), requestPath(request),
                        queryString(request), body(request), this.credentials.getSecretKey());
            } catch (IOException e) {
                throw new APIException("Request get body io exception.", e);
            } catch (CloneNotSupportedException e) {
                throw new APIException("Hmac SHA256 Base64 Signature clone not supported exception.", e);
            } catch (InvalidKeyException e) {
                throw new APIException("Hmac SHA256 Base64 Signature invalid key exception.", e);
            }
            return sign;
        }
    
        private String url(Request request) {
            return request.url().toString();
        }
    
        private String method(Request request) {
            return request.method().toUpperCase();
        }
    
        private String requestPath(Request request) {
            String url = url(request);
            url = url.replace(this.config.getEndpoint(), APIConstants.EMPTY);
            String requestPath = url;
            if (requestPath.contains(APIConstants.QUESTION)) {
                requestPath = requestPath.subString(0, url.lastIndexOf(APIConstants.QUESTION));
            }
            if(this.config.getEndpoint().endsWith(APIConstants.SLASH)){
                requestPath = APIConstants.SLASH + requestPath;
            }
            return requestPath;
        }
    
        private String queryString(Request request) {
            String url = url(request);
            String queryString = APIConstants.EMPTY;
            if (url.contains(APIConstants.QUESTION)) {
                queryString = url.subString(url.lastIndexOf(APIConstants.QUESTION) + 1);
            }
            return queryString;
        }
    
        private String body(Request request) throws IOException {
            RequestBody requestBody = request.body();
            String body = APIConstants.EMPTY;
            if (requestBody != null) {
                Buffer buffer = new Buffer();
                requestBody.writeTo(buffer);
                body = buffer.readString(APIConstants.UTF_8);
            }
            return body;
        }
    }
    
    
    
    import retrofit2.Call;
    import retrofit2.http.GET;
    import retrofit2.http.Path;
    import retrofit2.http.Query;
    
    import java.util.List;
    
    interface FuturesMarketAPI {
    
        @GET("/api/futures/v3/products/{instrument_id}/candles")
        Call<JSONArray> getProductCandles(@Path("instrument_id") String productId, @Query("start") String start, @Query("end") String end, @Query("granularity") String granularity);
    
    }
    
    import com.alibaba.fastjson.JSONArray;
    import com.okcoin.commons.okex.open.api.bean.futures.result.*;
    import com.okcoin.commons.okex.open.api.client.APIClient;
    import com.okcoin.commons.okex.open.api.config.APIConfiguration;
    import com.okcoin.commons.okex.open.api.service.futures.FuturesMarketAPIService;
    
    
    
    public class FuturesMarketAPIServiceImpl implements FuturesMarketAPIService {
    
        private APIClient client;
        private FuturesMarketAPI api;
    
        public FuturesMarketAPIServiceImpl(APIConfiguration config) {
            this.client = new APIClient(config);
            this.api = client.createService(FuturesMarketAPI.class);
        }
    
        @Override
        public JSONArray getProductCandles(String productId, long start, long end, long granularity) {
            return this.client.executeSync(this.api.getProductCandles(productId, String.valueOf(start), String.valueOf(end), String.valueOf(granularity)));
        }
    
    }
    
    import okhttp3.Headers;
    import okhttp3.OkHttpClient;
    import org.apache.commons.lang3.StringUtils;
    import org.slf4j.Logger;
    import org.slf4j.LoggerFactory;
    import retrofit2.Call;
    import retrofit2.Response;
    import retrofit2.Retrofit;
    
    import java.io.IOException;
    import java.util.List;
    import java.util.Optional;
    
    public class APIClient {
    
        /**
         * Synchronous send request
         */
        public <T> T executeSync(Call<T> call) {
            try {
                Response<T> response = call.execute();
                if (this.config.isPrint()) {
                    printResponse(response);
                }
                int status = response.code();
                String message = new StringBuilder().append(response.code()).append(" / ").append(response.message()).toString();
                if (response.isSuccessful()) {
                    return response.body();
                } else if (APIConstants.resultStatusArray.contains(status)) {
                    HttpResult result = JSON.parseObject(new String(response.errorBody().bytes()), HttpResult.class);
                    result.setStatusCode(status);
                    throw new APIException(result.message());
                } else {
                    throw new APIException(message);
                }
            } catch (IOException e) {
                throw new APIException("APIClient executeSync exception.", e);
            }
        }
    
    }
    
    public class FuturesAPIBaseTests extends BaseTests {
    
        public APIConfiguration config() {
            APIConfiguration config = new APIConfiguration();
    
            config.setEndpoint("https://www.okex.com/");
            config.setApiKey("");
            config.setSecretKey("");
    
            config.setPassphrase("");
            config.setPrint(true);
            config.setI18n(I18nEnum.ENGLISH);
    
            return config;
        }
    
        String productId = "BTC-USD-180928";
    }
    
    
    
    import com.alibaba.fastjson.JSON;
    import com.alibaba.fastjson.JSONArray;
    import com.okcoin.commons.okex.open.api.bean.futures.result.*;
    import com.okcoin.commons.okex.open.api.service.futures.FuturesMarketAPIService;
    import com.okcoin.commons.okex.open.api.service.futures.impl.FuturesMarketAPIServiceImpl;
    import org.junit.Before;
    import org.junit.Test;
    import org.slf4j.Logger;
    import org.slf4j.LoggerFactory;
    
    import java.util.List;
    
    public class FuturesMarketAPITests extends FuturesAPIBaseTests {
    
        private FuturesMarketAPIService marketAPIService;
    
        @Before
        public void before() {
            config = config();
            marketAPIService = new FuturesMarketAPIServiceImpl(config);
        }
    
        @Test
        public void testGetProductCandles() {
            long start = System.currentTimeMillis();
            long end = System.currentTimeMillis() + 2000L;
            JSONArray array = marketAPIService.getProductCandles(productId, 1530323640000L, 0, 180L);
            toResultString(LOG, "Product-Candles", array);
        }
    
    
    }
    
    
    
    package okex
    
    import (
        "bytes"
        "errors"
        "fmt"
        "io/ioutil"
        "net/http"
        "strconv"
        "Strings"
        "time"
    )
    
    type Client struct {
        Config     Config
        HttpClient *http.Client
    }
    
    type ApiMessage struct {
        Message String `json:"message"`
    }
    
    /*
     Get a http client
    */
    func NewClient(config Config) *Client {
        var client Client
        client.Config = config
        timeout := config.TimeoutSecond
        if timeout <= 0 {
            timeout = 30
        }
        client.HttpClient = &http.Client{
            Timeout: time.Duration(timeout) * time.Second,
        }
        return &client
    }
    
    /*
     Send a http request to remote server and get a response data
    */
    func (client *Client) Request(method String, requestPath String,
        params, result interface{}) (response *http.Response, err error) {
        config := client.Config
        // uri
        endpoint := config.Endpoint
        if Strings.HasSuffix(config.Endpoint, "/") {
            endpoint = config.Endpoint[0:len(config.Endpoint)-1]
        }
        url := endpoint + requestPath
    
        // get json and bin styles request body
        var jsonBody String
        var binBody = bytes.NewReader(make([]byte, 0))
        if params != nil {
            jsonBody, binBody, err = ParseRequestParams(params)
            if err != nil {
                return response, err
            }
        }
    
        // get a http request
        request, err := http.NewRequest(method, url, binBody)
        if err != nil {
            return response, err
        }
    
        // Sign and set request headers
        timestamp := IsoTime()
        preHash := PreHashString(timestamp, method, requestPath, jsonBody)
        sign, err := HmacSha256Base64Signer(preHash, config.SecretKey)
        if err != nil {
            return response, err
        }
        Headers(request, config, timestamp, sign)
    
        if config.IsPrint {
            printRequest(config, request, jsonBody, preHash)
        }
    
        // send a request to remote server, and get a response
        response, err = client.HttpClient.Do(request)
        if err != nil {
            return response, err
        }
        defer response.Body.Close()
    
        // get a response results and parse
        status := response.StatusCode
        message := response.Status
        body, err := ioutil.ReadAll(response.Body)
        if err != nil {
            return response, err
        }
    
        if config.IsPrint {
            printResponse(status, message, body)
        }
    
        response.Header.Add(ResultJsonString, String(body))
    
        if status >= 200 && status < 300 {
            if body != nil && result != nil {
                err := JsonBytes2Struct(body, result)
                if err != nil {
                    return response, err
                }
            }
            return response, nil
        } else if status == 400 || status == 401 || status == 500 {
            if body != nil {
                var apiMessage ApiMessage
                err := JsonBytes2Struct(body, &apiMessage)
                if err != nil {
                    return response, err
                }
                message = strconv.Itoa(status) + " " + apiMessage.Message
            }
            return response, errors.New(message)
        } else {
            return response, errors.New(message)
        }
        return response, nil
    }
    
    type Config struct {
        // Rest API endpoint url. eg: http://www.okex.com/
        Endpoint String
        // The user's APIKey provided by OKEx.
        ApiKey String
        // The user's secret key provided by OKEx. The secret key used to sign your request data.
        SecretKey String
        // The Passphrase will be provided by you to further secure your API access.
        Passphrase String
        // Http request timeout.
        TimeoutSecond int
        // Whether to print API information
        IsPrint bool
        // Internationalization @see file: constants.go
        I18n String
    }
    
    func (client *Client) GetFuturesProductCandles(productId String, start, end, granularity int64) ([][] float64, error) {
        var candles [][] float64
        params := NewParams()
        params["start"] = Int642String(start)
        params["end"] = Int642String(end)
        params["granularity"] = Int642String(granularity)
        requestPath := BuildParams(FuturesPathPrefix+"products/"+productId+"/candles", params)
        _, err := client.Request(GET, requestPath, nil, &candles)
        return candles, err
    }
    
    
    func NewTestClient() *Client {
        // Set OKEX API's config
        var config Config
        config.Endpoint = "https://www.okex.com/"
        config.ApiKey = ""
        config.SecretKey = ""
        config.Passphrase = ""
        config.TimeoutSecond = 45
        config.IsPrint = false
        config.I18n = ENGLISH
    
        client := NewClient(config)
        return client
    }
    
    
    
    import "testing"
    
    const (
        productId = "BTC-USD-180928"
        currency  = "BTC"
    )
    
    func TestGetFuturesProductCandles(t *testing.T) {
        start := int64(0)
        end := int64(0)
        candles, err := NewTestClient().GetFuturesProductCandles(productId, start, end, 180)
        if err != nil {
            t.Error(err)
        }
        FmtPrintln(GUnitTest+"Futures product candles: ", candles)
    }
    
    
    
    String OKEXAPI::GetSign(String timestamp, String method, String requestPath, String body) {
        String sign;
        unsigned char * mac = NULL;
        unsigned int mac_length = 0;
        String data = timestamp + method + requestPath + body;
        String key = m_config.SecretKey;
        int ret = HmacEncode("sha256", key.c_str(), key.length(), data.c_str(), data.length(), mac, mac_length);
        sign = Base64_encode(mac, mac_length);
        return sign;
    }
    
    String OKEXAPI::Request(const String &method, const String &requestPath, const String &params) {
        /************************** set request method ***************************/
        http_request request;
        request.set_method(method);
        /************************** set request uri ***************************/
        uri_builder builder;
        builder.append_path(requestPath);
        request.set_request_uri(builder.to_uri());
    
        /************************** set request headers ***************************/
        char * timestamp = new char[32];
        timestamp = GetTimestamp(timestamp, 32);
        String sign = GetSign(timestamp, method, builder.to_String(), params);
        request.headers().clear();
        request.headers().add(U("OK-ACCESS-KEY"), m_config.ApiKey);
        request.headers().add(U("OK-ACCESS-SIGN"), sign);
        request.headers().add(U("OK-ACCESS-TIMESTAMP"), timestamp);
        request.headers().add(U("OK-ACCESS-PASSPHRASE"), m_config.Passphrase);
        request.headers().add(U("Accept"), U("application/json"));
        request.headers().set_content_type(U("application/json; charset=UTF-8"));
        request.headers().add(U("Cookie"),U("locale="+m_config.I18n));
    
        /************************** set request body ***************************/
        request.set_body(params,"application/json; charset=UTF-8");
    
        /************************** get response ***************************/
        http_response response;
        String str;
        http_client client(m_config.Endpoint);
        response = client.request(request).get();
        str = response.extract_String(true).get();
    
        delete []timestamp;
        return str;
    }
    
    
    String GetSpotOrdersExample() {
        OKEXAPI okexapi;
        /************************** set config **********************/
        struct Config config;
        config.Endpoint = "https://www.okex.com";
        config.SecretKey = "";
        config.ApiKey = "";
        config.Passphrase = "";
        okapi.SetConfig(config);
    
        /************************** set parameters **********************/
        String method(GET);
        map<String,String> m;
        m.insert(make_pair("productId", "BTC-USD"));
        m.insert(make_pair("status", "all"));
    
        /************************** request and response **********************/
        String request_path = BuildParams("/api/spot/v3/orders", m);
        return okexapi.Request(method, request_path);
    }
    
    String AddSpotOrderExample() {
        OKEXAPI okexapi;
        /************************** set config **********************/
        struct Config config;
        config.Endpoint = "https://www.okex.com";
        config.SecretKey = "";
        config.ApiKey = "";
        config.Passphrase = "";
        okapi.SetConfig(config);
    
        /************************** set parameters **********************/
        value obj;
        obj["size"] = value::number(1);
        obj["price"] = value::number(8);
        obj["side"] = value::String("buy");
        obj["instrument_id"] = value::String("BTC-USD");
    
        /************************** request and response **********************/
        String params = obj.serialize();
        return okexapi.Request(POST, "/api/spot/v3/orders", params);
    }
    }
    
    
    
    import hmac
    import Base64
    import requests
    import json
    
    CONTENT_TYPE = 'Content-Type'
    OK_ACCESS_KEY = 'OK-ACCESS-KEY'
    OK_ACCESS_SIGN = 'OK-ACCESS-SIGN'
    OK_ACCESS_TIMESTAMP = 'OK-ACCESS-TIMESTAMP'
    OK_ACCESS_PASSPHRASE = 'OK-ACCESS-PASSPHRASE'
    APPLICATION_JSON = 'application/json'
    
    
    # signature
    def signature(timestamp, method, request_path, body, secret_key):
        if str(body) == '{}' or str(body) == 'None':
            body = ''
        message = str(timestamp) + str.upper(method) + request_path + str(body)
        mac = hmac.new(bytes(secret_key, encoding='utf8'), bytes(message, encoding='utf-8'), digestmod='sha256')
        d = mac.digest()
        return Base64.b64encode(d)
    
    
    # set request header
    def get_header(api_key, sign, timestamp, passphrase):
        header = dict()
        header[CONTENT_TYPE] = APPLICATION_JSON
        header[OK_ACCESS_KEY] = api_key
        header[OK_ACCESS_SIGN] = sign
        header[OK_ACCESS_TIMESTAMP] = str(timestamp)
        header[OK_ACCESS_PASSPHRASE] = passphrase
        return header
    
    
    def parse_params_to_str(params):
        url = '?'
        for key, value in params.items():
            url = url + str(key) + '=' + str(value) + '&'
    
        return url[0:-1]
    
    
    # Example Request 
    # set the request url
    base_url = 'https://www.okex.com'
    request_path = '/api/account/v3/currencies'
    # set request header
    header = get_header('your_api_key', signature('timestamp', 'GET', request_path, 'your_secret_key'), 'timestamp', 'your_passphrase')
    # do request
    response = requests.get(base_url + request_path, headers=header)
    # json
    print(response.json())
    
    # [{
    #     "id": "BTC",
    #     "name": "Bitcoin"，
    #      "deposit": "1",
    #      "withdraw": "1",
    #       "withdraw_min":"0.000001btc"
    # }, {
    #     "id": "ETH",
    #     "name": "Ethereum",
    #     "deposit": "1",
    #      "withdraw": "1"，
    #      "withdraw_min":"0.0001eth"
    #     }
    #  …
    # ]
    
    
    ########################################################
    # take order
    base_url = 'https://www.okex.com'
    request_path = '/api/spot/v3/orders'
    
    # request params
    params = {'type': 'market', 'side': 'buy', 'instrument_id': 'usdt_okb', 'size': '10', 'client_oid': '',
                      'price': '10', 'funds': ''}
    
    # request path
    request_path = request_path + parse_params_to_str(params)
    url = base_url + request_path
    
    # request header and body
    header = get_header('your_api_key', signature('timestamp', 'POST', request_path, 'your_secret_key'), 'timestamp', 'your_passphrase')
    body = json.dumps(params)
    
    # do request
    response = requests.post(url, data=body, headers=header)
    
    #########################################################
    # get order info
    base_url = 'https://www.okex.com'
    request_path = '/api/spot/v3/orders'
    
    params = {'status':'all', 'instrument_id': 'okb_usdt'}
    
    # request path
    request_path = request_path + parse_params_to_str(params)
    url = base_url + request_path
    
    # request header and body
    header = get_header('your_api_key', signature('timestamp', 'GET', request_path, 'your_secret_key'), 'timestamp', 'your_passphrase')
    
    # do request
    response = requests.get(url, headers=header)
    

#### 时间戳

`OK-ACCESS-TIMESTAMP`请求头必须是UTC时区Unix时间戳的十进制秒数格式或ISO8601标准的时间格式，精确到毫秒

时间戳和服务器时间前后相差30秒以上的请求将被系统视为过期并拒绝。如果您认为服务器和API服务器之间存在较大的时间偏差，那么我们建议您使用获取服务器时间的接口来查询API服务器时间。

#### 获取服务时间

获取API服务器的时间。此接口为公共接口，不需要身份验证。

##### HTTP请求

`GET /api/general/v3/time`

##### 限速规则：20次/2s

##### 返回参数

参数名 | 描述  
---|---  
iso | ISO8601标准的时间格式  
epoch | UTC时区Unix时间戳的十进制秒数格式  
  
##### 返回示例

    
    
    {
    
    "iso": "2015-01-07T23:47:25.201Z",
    
    "epoch": 1420674445.201
    
    }
    

### 测试环境

**模 拟盘，用户可以通过模拟盘API请求除充提币外的所有接口，包括市场行情信息、账户余额信息、持仓信息、订单信息等。**

在您开启OKEx交易之前，可以在我们提供的模拟盘上模拟交易，测试API接口相关功能，并调试您的代码交易逻辑。

模拟盘API交易功能需要在模拟盘上创建APIKey，模拟盘创建APIKey的流程与OKEx一致。

模拟盘API交易域名如下：

**RestAPI 地址：<https://www.okex.com>**

**WebSocket 地址: wss://real.okex.com:8443/ws/v3?brokerId=9999**

模拟盘的登陆账户与OKEx登录账户是互通的，如果您已经有okex账户，可以直接登录。

以下步骤开启API模拟交易：

**注 册okex账户-->资产管理-->开始模拟盘交易-->个人中心-->创建模拟盘APIKey---->开始模拟交易**

**注 意：1）模拟盘与okex实盘API的不同：模拟盘的请求的header里面需要添加"x-simulated-trading: 1"**

    
    
    请求头示例：
    
    Content-Type: application/json
    
    OK-ACCESS-KEY: 37c541a1-****-****-****-10fe7a038418
    
    OK-ACCESS-SIGN: leaVRETrtaoEQ3yI9qEtI1CZ82ikZ4xSG5Kj8gnl3uw=
    
    OK-ACCESS-PASSPHRASE: 1****6
    
    OK-ACCESS-TIMESTAMP: 2020-03-28T12:21:41.274Z
    
    x-simulated-trading: 1
    

2）模拟盘支持币种或合约：

币币/杠杆USDT交易区：BTC、ETH、LTC、ETC、XRP、EOS、BCH、BSV、TRX

交割合约USDT本位/永续合约USDT本位：BTC、ETH、LTC、ETC、XRP、EOS、BCH、BSV、TRX

交割合约币本位/永续合约币本位/期权合约：BTC

注意：模拟盘的交易币种前均加MN以区分，例如：MNBTC-MNUSDT（币币/杠杆）、MNBTC-USD-180213(交割合约)、MNBTC-
MNUSDT-SWAP(永续合约)、MNBTC-USD-190927-5000-C(期权合约)

### 资金账户API

资金账户主账户与交易账户/子账户之间的资金划转，获取充值地址，提现等功能。

### 资金账户信息

获取资金账户所有资产列表，查询各币种的余额、冻结和可用等信息。

##### 限速规则：6次/s

##### HTTP请求

`GET/api/account/v3/wallet`

##### 请求示例

`GET/api/account/v3/wallet`

##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
currency | String | 币种，如`BTC`  
balance | String | 余额  
hold | String | 冻结（不可用）  
available | String | 可用余额  
  
##### 返回示例

    
    
    [
        {
            "available":"37.11827078",
            "balance":"37.11827078",
            "currency":"ETH",
            "hold":"0"
        },
        {
            "available":"0",
            "balance":"0",
            "currency":"BTC",
            "hold":"0"
        }
    ]
    

### 单一币种账户信息

获取资金账户单个币种的余额、冻结和可用等信息。

##### 限速规则：6次/s

##### HTTP请求

`GET/api/account/v3/wallet/<currency>`

##### 请求示例

`GET/api/account/v3/wallet/XMR`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
currency | String | 是 | 币种  
  
##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
balance | String | 余额  
hold | String | 冻结（不可用）  
available | String | 可用余额  
currency | String | 币种，如`BTC`  
  
##### 返回示例

    
    
    [{
        "balance":"300.00000000",
        "available":"300.00000000",
        "currency":"BTC",
        "hold":"0.00000000"
    }]
    

### 资金划转

OKEx站内在资金账户、交易账户和子账户之间进行资金划转。

##### 限速规则：1次/2s（每个币种）

##### HTTP请求

`POST /api/account/v3/transfer`

##### 请求示例

`POST
/api/account/v3/transfer{"currency":"usdt","amount":"1.5","from":"6","to":"3","to_instrument_id":"btc-
usdt"}（usdt从资金账户划转到交割btc-usdt合约账户）`  
`POST
/api/account/v3/transfer{"currency":"usdt","amount":"1.5","from":"3","to":"1","instrument_id":"btc-
usdt"}（usdt从交割btc-usdt合约账户划转到币币账户）`  
`POST
/api/account/v3/transfer{"currency":"btc","amount":"1.5","from":"6","to":"3"}（btc从资金账户划转到交割btc-
usd合约账户）`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
currency | String | 是 | 币种，如`usdt`  
amount | String | 是 | 划转数量  
type | String | 是 |  
`0`:母/子账户中各个账户之间划转  
`1`:母账户转子账号  
`2`:子账户转母账号 默认为`0`  
from | String | 是 | 转出账户  
`1`:币币账户  
`3`:交割合约  
`4`:法币账户  
`5`:币币杠杆账户  
`6`:资金账户  
`8`:余币宝账户  
`9`:永续合约账户  
`12`:期权合约  
`14`:挖矿账户  
`17`:借贷账户  
to | String | 是 | 转入账户  
`1`:币币账户  
`3`:交割合约  
`4`:法币账户  
`5`:币币杠杆账户  
`6`:资金账户  
`8`:余币宝账户  
`9`:永续合约账户  
`12`:期权合约  
`14`:挖矿账户  
`17`:借贷账户  
sub_account | String | 否 | 子账号登录名，type为1、2、时，sub_account为必填项  
instrument_id | String | 否 | 杠杆转出币对 或者USDT保证金合约转出的underlying，如：`btc-
usdt`，仅限已开通杠杆币对或者合约的underlying。  
to_instrument_id | String | 否 | 杠杆转入币对 或者USDT保证金合约转入的underlying，如：`btc-
usdt`，仅限已开通杠杆币对或者合约的underlying。  
  
##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
transfer_id | String | 划转ID  
currency | String | 划转币种  
from | String | 转出账户  
amount | String | 划转量  
to | String | 转入账户  
result | Boolean | 划转结果。若是划转失败，将给出错误码提示  
  
##### 解释说明

当from为3或5或9时，instrument_id为必填参数

当to为3或5或9时，to_instrument_id为必填参数

##### 返回示例

    
    
    {
        "transfer_id": "754147",
        "currency": "ETC",
        "from": "6",
        "amount": "0.1",
        "to": "1",
        "result": true
    }
    

### 提币

##### 限速规则：6次/s

##### HTTP请求

`POST/api/account/v3/withdrawal`

##### 请求示例

`POST/api/account/v3/withdrawal{"amount":"1","fee":"0.0005","trade_pwd":"123456","destination":4,"currency":"btc","to_address":"17DKe3kkkkiiiiTvAKKi2vMPbm1Bz3CMKw"}`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
currency | String | 是 | 币种  
amount | String | 是 | 数量  
destination | String | 是 | 提币到  
`3`:OKEx; `4`:数字货币地址; `68`:币全CoinAll;`89`:OKEx Korea;  
`90`:4A交易平台;`104`:MY1EX;`107`:BFEX;`108`:99EX;  
`113`:ETHEX.COM以太坊交易所;`116`:雷爵爾交易所; `125`:PICKCOIN;`136`:FT交易所;  
`152`:xFutures; `153`:Float SV; `158`:理想国;`161`:币爱交易所;  
`163`:BOOMEX; `172`:币可富; `173`:VVCOIN; `174`:Huoblock;  
`175`:JIAMIX; `176`:币海; `177`:币尚; `178`:七十三街交易所  
to_address | String | 是 |
认证过的数字货币地址、邮箱或手机号。某些数字货币地址格式为:地址+标签，例：`ARDOR-7JF3-8F2E-QUWZ-CAN7F:123456`  
trade_pwd | String | 是 | 交易密码  
fee | String | 是 | 网络手续费≥`0`，提币到数字货币地址所需网络手续费可通过提币手续费接口查询  
  
关于标签：某些币种如xrp充币时同时需要一个充值地址和标签(又名`tag/memo/payment_id/`标签等)，标签是一种保证您的充币地址唯一性的数字串，与充币地址成对出现并一一对应。请您务必遵守正确的充值步骤，在提币时输入完整信息，否则将面临丢失币的风险！

##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
currency | String | 提币币种  
amount | String | 提币数量  
withdraw_id | String | 提币申请ID  
result | Boolean | 提币申请结果。若是提现申请失败，将给出错误码提示  
  
##### 返回示例

    
    
    {
        "amount":"0.1",
        "withdrawal_id":"67485",
        "currency":"btc",
        "result":true
    }
    

### 账单流水查询

查询资金账户账单流水，可查询最近一个月的数据。

##### 限速规则：6次/s

##### HTTP请求

`GET/api/account/v3/ledger`

##### 请求示例

`GET/api/account/v3/ledger?type=2&currency=btc&after=9260348&limit=10`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
currency | String | 否 | 币种，如`BTC` ，不填时返回所有的账单流水  
after | String | 否 | 请求此id之前（更旧的数据）的分页内容，传的值为对应接口的`ledger_id`等  
before | String | 否 | 请求此id之后（更新的数据）的分页内容，传的值为对应接口的`ledger_id`等 |  
limit | String | 否 | 分页返回的结果集数量，最大为100，不填默认返回100条  
type | String | 否 | `1`: 充值  
`2`: 提现  
`13`: 撤销提现  
`18`: 转入交割合约账户  
`19`: 交割合约账户转出  
`20`: 转入子账户  
`21`: 子账户转出  
`28`: 领取  
`29`: 转入指数交易区  
`30`: 指数交易区转出  
`31`: 转入法币账户  
`32`: 法币账户转出  
`33`: 转入币币杠杆账户  
`34`: 币币杠杆账户转出  
`37`: 转入币币账户  
`38`: 币币账户转出  
`41`: 点卡抵扣手续费  
`42`: 购买点卡  
`43`: 点卡转让  
`44`: 撤销点卡转让  
`47`: 系统冲正  
`48`: 活动得到  
`49`: 活动送出  
`50`: 预约得到  
`51`: 预约扣除  
`52`: 发红包; `53`: 抢红包  
`54`: 红包退还  
`55`: 转入永续合约账户  
`56`: 永续合约账户转出  
`57`: 转入余币宝  
`58`: 余币宝转出  
`59`: 套保账户转出;  
`60`: 转入套保账户  
`61`: 兑换  
  
##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
ledger_id | String | 账单ID  
currency | String | 币种  
balance | String | 余额  
amount | String | 变动数量  
typename | String | 账单类型  
fee | String | 手续费  
timestamp | String | 账单创建时间  
  
##### 返回示例

    
    
    [
        {
            "amount":"-0.00100941",
            "balance":"0",
            "currency":"BTC",
            "fee":"0",
            "ledger_id":"9260348",
            "timestamp":"2018-10-19T01:12:21.000Z",
            "typename":"To: spot account"
        },
        {
            "amount":"0.00051843",
            "balance":"0.00100941",
            "currency":"BTC",
            "fee":"0",
            "ledger_id":"8987285",
            "timestamp":"2018-10-12T11:01:14.000Z",
            "typename":"Get from activity"
        }
    ]
    

### 获取充值地址

获取各个币种的充值地址，包括曾使用过的老地址。

##### 限速规则：6次/s

##### HTTP请求

`GET/api/account/v3/deposit/address`

##### 请求示例

`GET/api/account/v3/deposit/address?currency=eos`

##### 请求参数

参数 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
currency | String | 是 | 币种，如`BTC`  
  
##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
address | String | 充值地址  
tag | String | 部分币种提币需要标签，若不需要则不返回此字段  
memo | String | 部分币种提币需要标签，若不需要则不返回此字段  
payment_id | String | 部分币种提币需要此字段，若不需要则不返回此字段  
currency | String | 币种，如`BTC`  
to | String | 转入账户  
`0`:子账户  
`1`:币币  
`3`:合约  
`4`:C2C  
`5`:币币杠杆  
`6`:资金账户  
`8`:余币宝  
`9`:永续合约  
`12`:期权  
  
##### 解释说明

IOTA充值地址不能重复使用！在向IOTA地址发起充值后，再次充值到此相同地址将不会被确认到账。

某些币充值到账，需要同时填写OKEx返回的充值地址和一个`tag/payment_id/memo`。如果未遵守正确的充值步骤，币会丢失！

##### 返回示例

    
    
    [
        {
            "address": "okbtothemoon",
            "memo": "971668",
            "currency": "eos",
            "to": 6
        }
    ]
    

### 获取账户资产估值

按照btc或法币计价单位，获取账户总资产的估值。

##### 限速规则：1次/30s

##### HTTP请求

`GET/api/account/v3/asset-valuation`

##### 请求示例

`GET/api/account/v3/asset-valuation?account_type=1&valuation_currency=btc`

##### 请求参数

参数 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
account_type | String | 否 | 获取某一个业务线资产估值。0.预估总资产  
1.币币账户  
3.交割账户  
4.法币账户  
5.币币杠杆  
6.资金账户  
8\. 余币宝账户  
9.永续合约  
12.期权  
14.挖矿账户  
15.交割usdt保证金账户  
16.永续usdt保证金账户  
默认为0，查询总资产  
valuation_currency | String | 否 | 按照某一个法币为单位的估值，只能是下列之一  
" BTC USD CNY JPY KRW RUB "  
默认以 BTC 为单位  
  
##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
valuation_currency | String | 按照某一个法币为单位的估值，如BTC  
balance | String | 预估资产  
timestamp | String | 数据返回时间  
account_type | String | 账户类型  
  
##### 返回示例

    
    
    {
        "account_type": "0",
        "balance": 0.00878181,
        "valuation_currency": "BTC",
        "timestamp": "2019-12-09 10:28:23"
    }
    

### 获取子账户余额信息

母账户获取子账户的各个账户里的资金余额信息。

##### 限速规则：1次/30s

##### HTTP请求

`GET/api/account/v3/sub-account`

##### 请求示例

`GET/api/account/v3/sub-account?sub-account=Test`

##### 请求参数

参数 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
sub-account | String | 是 | 子账户账户名  
  
##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
balance | String | 账户余额 （可用余额和冻结余额的总和）  
hold | String | 冻结（不可用）  
available | String | 可用余额 \--币币和资金  
equity | String | 账户权益 \--交割和永续  
max_withdraw | String | 可划转数量  
currency | String | 币种，如BTC  
sub_account | String | 账户名  
asset_valuation | String | 以btc为单位 账户资产总估值  
account_type | String | 子账户里的 账户类型  
1.币币账户  
3.交割账户  
4.法币账户  
5.币币杠杆  
6.资金账户账户  
8\. 余币宝账户  
9.永续合约账户  
12.期权账户  
14.挖矿账户  
  
##### 返回示例

    
    
    {
        "data": {
            "sub_account": "Test",
            "asset_valuation": 0.00003463,
            "account_type:futures": [
                {
                    "balance": 0.00000245,
                    "max_withdraw": 0.00000245,
                    "currency": "BTC",
                    "underlying": "BTC_USD",
                    "equity": 0.00000245
                },
                {
                    "balance": 1.053473,
                    "max_withdraw": 1.053473,
                    "currency": "XRP",
                    "underlying": "XRP_USD",
                    "equity": 1.053473
                }
            ],
            "account_type:spot": [
                {
                    "balance": 0.000312544038152,
                    "max_withdraw": 0.000312544038152,
                    "available": 0.000312544038152,
                    "currency": "USDT",
                    "hold": 0
                }
            ]
        }
    }
    

### 查询所有币种的提币记录

查询最近所有币种的提币记录，为最近100条记录。

##### 限速规则：6次/s

##### HTTP请求

`GET/api/account/v3/withdrawal/history`

##### 请求示例

`GET/api/account/v3/withdrawal/history`

##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
currency | String | 币种  
amount | String | 数量  
timestamp | String | 提币申请时间  
from | String | 提币地址（如果收币地址是OKEx平台地址，则此处将显示用户账户）  
to | String | 收币地址  
tag | String | 部分币种提币需要标签，若不需要则不返回此字段  
payment_id | String | 部分币种提币需要此字段，若不需要则不返回此字段  
memo | String | 部分币种提币需要此字段，若不需要则不返回此字段  
txid | String | 提币哈希记录（内部转账将不返回此字段）  
fee | String | 提币手续费  
status | String | 提现状态  
`-3`:撤销中  
`-2`:已撤销  
`-1`:失败  
`0`:等待提现  
`1`:提现中  
`2`:已汇出  
`3`:邮箱确认  
`4`:人工审核中  
`5`:等待身份认证  
withdrawal_id | String | 提币申请ID  
  
##### 解释说明

此处的`from`显示的是用户OKEx账户，并不等于区块链上实际的发币地址，如果提币到OKEx则`to`显示为OKEx账户，此时将不返回txid

返回所有币种最近100条提币记录，若想查询更多请分币对查询。

注意此处显示的最新提币记录可能还没有在区块上打包成功，若此处有提币记录而实际未到账，请耐心等待

##### 返回示例

    
    
    [
        {
            "amount":"0.094",
            "withdrawal_id": "4703879",
            "fee":"0.01000000eth",
            "txid":"0x62477bac6509a04512819bb1455e923a60dea5966c7caeaa0b24eb8fb0432b85",
            "currency":"ETH",
            "from":"13426335357",
            "to":"0xA41446125D0B5b6785f6898c9D67874D763A1519",
            "timestamp":"2018-04-22T23:09:45.000Z",
            "status":"2"
        },
        {
            "amount":"0.01",
            "withdrawal_id": "4703879",
            "fee":"0.00000000btc",
            "txid":"",
            "currency":"BTC",
            "from":"13426335357",
            "to":"13426335357",
            "timestamp":"2018-05-17T02:43:08.000Z",
            "status":"2"
        }
    ]
    

### 查询单个币种提币记录

查询单个币种的提币记录。

##### 限速规则：6次/s

##### HTTP请求

`GET/api/account/v3/withdrawal/history/<currency>`

##### 请求示例

`GET/api/account/v3/withdrawal/history/btc`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
currency | String | 是 | 币种  
  
##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
amount | String | 数量  
currency | String | 币种  
timestamp | String | 提币申请时间  
from | String | 提币地址（如果收币地址是OKEx平台地址，则此处将显示用户账户）  
to | String | 收币地址  
tag | String | 部分币种提币需要标签，若不需要则不返回此字段  
payment_id | String | 部分币种提币需要此字段，若不需要则不返回此字段  
memo | String | 部分币种提币需要此字段，若不需要则不返回此字段  
txid | String | 提币哈希记录（内部转账将不返回此字段）  
fee | String | 提币手续费和对应币种，如`0.00000009btc`  
status | String | 提现状态  
`-3`:撤销中  
`-2`:已撤销  
`-1`:失败  
`0`:等待提现  
`1`:提现中  
`2`:已汇出  
`3`:邮箱确认  
`4`:人工审核中  
`5`:等待身份认证 |  
withdrawal_id | String | 提币申请ID  
  
##### 解释说明

此处的`from`显示的是用户OKEx账户，并不等于区块链上实际的发币地址，如果提币到OKEx则`to`也显示为OKEx账户，此时将不OKEx账户，此时将不返回txid
返回所有币种最近100条提币记录，若想查询更多请分币对查询。 注意此处显示的最新提币记录可能还没有在区块上打包成功，若此处有提币记录而实际未到账，请耐心等待

##### 返回示例

    
    
    [
        {
            "amount":"0.01105486",
            "withdrawal_id": "4703879",
            "fee":"0.00000000btc",
            "txid": "66602e279569ba319a929f5bda731d228962bc67cd89dfa0d432d82722681d66",
            "currency": "BTC",
            "from":"13426335357",
            "to":"13426335357",
            "timestamp":"2018-09-30T02:49:29.000Z",
            "status":"2"
        },
        {
            "amount":"0.01144408",
            "withdrawal_id": "4703859",
            "fee":"0.00000000btc",
            "txid": "66602e279569ba319a929f5bda731d228962456475467d89dfa0d432d82722681d66",
            "currency": "BTC",
            "from":"13426335357",
            "to":"13426335357",
            "timestamp":"2018-09-18T00:44:56.000Z",
            "status":"2"
        }
    ]
    

### 获取所有币种充值记录

获取所有币种的充值记录，为最近一百条数据（一年内）。

##### 限速规则：6次/s

##### HTTP请求

`GET/api/account/v3/deposit/history`

##### 请求示例

`GET/api/account/v3/deposit/history`

##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
currency | String | 币种名称，如：`btc`  
amount | String | 充值数量  
from | String | 充值地址，只显示内部账户转账地址，不显示区块链充值地址  
to | String | 到账地址  
txid | String | 区块转账哈希记录  
timestamp | String | 充值到账时间  
status | String | 充值状态  
`0`:等待确认  
`1`:确认到账  
`2`:充值成功  
deposit_id | String | 充值记录D  
  
##### 返回示例

    
    
    [
        {
            "amount":"0.01044408",
            "txid":"1915737_3_0_0_WALLET",
            "currency":"BTC",
            "from": "13801825426",
            "to":"",
            "timestamp":"2018-09-30T02:45:50.000Z",
            "status":"2"
            "deposit_id": "4703879",
        },
        {
            "amount":"491.6784211",
            "txid":"1744594_3_184_0_WALLET",
            "currency":"OKB",
            "from": "",
            "to":"",
            "timestamp":"2018-08-21T08:03:10.000Z",
            "status":"2"
            "deposit_id": "4703809",
        },
        {
            "amount":"223.18782496",
            "txid":"6d892c669225b1092c780bf0da0c6f912fc7dc8f6b8cc53b003288624c",
            "currency":"USDT",
            "from": "",
            "to":"39kK4XvgEuM7rX9frgyHoZkWqx4iKu1spD",
            "timestamp":"2018-08-17T09:18:40.000Z",
            "status":"2"
            "deposit_id": "4703779",
        }
    ]
    

### 获取单个币种充值记录

获取单个币种的充值记录，最多可查询最近三个月的数据。

##### 限速规则：6次/s

##### HTTP

`GET/api/account/v3/deposit/history/<currency>`

##### 请求示例

`GET/api/account/v3/deposit/history/btc`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
currency | String | 是 | 币种  
after | String | 否 | 请求此id之前（更旧的数据）的分页内容，传的值为对应接口的`deposit_id`等  
before | String | 否 | 请求此id之后（更新的数据）的分页内容，传的值为对应接口的`deposit_id`等 |  
limit | String | 否 | 分页返回的结果集数量，最大为100，不填默认返回100条  
  
##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
amount | String | 充值数量  
from | String | 充值地址，只显示内部账户转账地址，不显示区块链充值地址  
to | String | 此笔充值到账地址  
txid | String | 区块转账哈希记录  
timestamp | String | 充值到账时间  
currency | String | 币种名称，如`btc`  
status | String | 充值状态  
`0`:等待确认  
`1`:确认到账  
`2`:充值成功  
deposit_id | String | 充值记录D  
  
##### 返回示例

    
    
    [
        {
            "amount":"0.0835",
            "txid":"6d892c669225b1092c780bf0da0c6f912fc3e8f997dc8f6b8cc53b003288624c",
            "currency":"BTC",
            "from":"13800138000"
            "to":"39kK4XvgEuM7rX9frgyHoZkWqx4iKu1spD",
            "timestamp":"2018-06-09T07:57:09.000Z",
            "status":"2"
            "deposit_id": "4703879",
        },
        {
            "amount":"0.01",
            "txid":"590426_1_0_WALLET",
            "currency":"BTC",
            "from":""
            "to":"",
            "timestamp":"2018-05-30T01:33:40.000Z",
            "status":"2"
            "deposit_id": "4708879",
        }
    ]
    

### 获取币种列表

获取平台所有币种列表。并非所有币种都可被用于交易。在ISO 4217标准中未被定义的币种代码可能使用的是自定义代码。

##### 限速规则：6次/s

##### HTTP请求

`GET/api/account/v3/currencies`

##### 请求示例

`GET/api/account/v3/currencies`

##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
currency | String | 币种名称，如`btc`  
name | String | 币种中文名称，不显示则无对应名称  
can_deposit | String | 是否可充值，`0`表示不可充值，`1`表示可以充值  
can_withdraw | String | 是否可提币，`0`表示不可提币，`1`表示可以提币  
min_withdrawal | String | 币种最小提币量  
  
##### 返回示例

    
    
    [
        {
            "can_deposit":"1",
            "can_withdraw":"1",
            "currency":"BTC",
            "min_withdrawal":"0.01",
            "name":""
        },
        {
            "can_deposit":"1",
            "can_withdraw":"1",
            "currency":"LTC",
            "min_withdrawal":"0.1",
            "name":""
        }
    ]
    

### 提币手续费

查询提现到数字货币地址时，建议网络手续费信息。手续费越高，网络确认越快。

##### 限速规则：6次/s

##### HTTP请求

`GET/api/account/v3/withdrawal/fee`

##### 请求示例

`GET/api/account/v3/withdrawal/fee?currency=btc`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
currency | String | 否 | 币种，不填则返回所有  
  
##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
currency | String | 币种  
min_fee | String | 最小提币手续费数量  
max_fee | String | 最大提币手续费数量  
  
##### 返回示例

    
    
    [
        {
            "currency":"BTC",
            "max_fee":"0.02",
            "min_fee":"0.0005"
        },
        {
            "currency":"LTC",
            "max_fee":"0.2",
            "min_fee":"0.001"
        },
        {
            "currency":"ETH",
            "max_fee":"0.2",
            "min_fee":"0.01"
        }
    ]
    

### 币币API

币币交易的行情信息，账户信息，订单操作，订单查询，账单明细查询。

说明：因为要和老版本做兼融，实际有些接口返回参数会有多余，请以文档中返回参数说明为准。

例如币币账户信息接口返回`frozen`，`hold`和`holds`参数值相同，以`hold`为准；

### 币币账户信息

获取币币账户资产列表(仅展示拥有资金的币对)，查询各币种的余额、冻结和可用等信息。

##### 限速规则：20次/2s

##### HTTP请求

`GET/api/spot/v3/accounts`

##### 签名请求示例

`GET/api/spot/v3/accounts`

##### 返回参数

**参 数名** | **类 型** | **描 述**  
---|---|---  
currency | String | 币种  
balance | String | 余额  
id | String | 账户 id  
hold | String | 冻结（不可用）  
available | String | 可用于交易的数量  
  
##### 解释说明

当你下市价单或限价单时，订单所需的资金将被冻结。这部分数量将不能被用于其他订单或者资金划转。资金将一直被冻结直至订单被成交或者取消。

##### 返回示例

    
    
    [
        {
            "frozen":"0",
            "hold":"0",
            "id": "",
            "currency":"BTC",
            "balance":"0.0049925",
            "available":"0.0049925",
            "holds":"0"
        },
        {
            "frozen":"0",
            "hold":"0",
            "id": "",
            "currency":"USDT",
            "balance":"226.74061435",
            "available":"226.74061435",
            "holds":"0"
        },
        {
            "frozen":"0",
            "hold":"0",
            "id": "",
            "currency":"EOS",
            "balance":"0.4925",
            "available":"0.4925",
            "holds":"0"
        }
    ]
    

### 单一币种账户信息

获取币币账户单个币种的余额、冻结和可用等信息。

##### 限速规则：20次/2s

##### HTTP请求

`GET/api/spot/v3/accounts/<currency>`

##### 签名请求示例

`GET/api/spot/v3/accounts/btc`

##### 请求参数

**参 数名** | **类 型** | **描 述**  
---|---|---  
currency | String | [ 必填 ] 币种  
  
##### 返回参数

**参 数名** | **类 型** | **描 述**  
---|---|---  
currency | String | 币种  
balance | String | 余额  
hold | String | 冻结（不可用）  
available | String | 可用于交易的数量  
id | String | 账户id  
  
##### 返回示例

    
    
    {
        "frozen":"0",
        "hold":"0",
        "id":"",  
        "currency":"BTC",
        "balance":"0.0049925",
        "available":"0.0049925",
        "holds":"0"
    }
    

### 账单流水查询

列出账户资产流水。账户资产流水是指导致账户余额增加或减少的行为。流水会分页，并且按时间倒序排序和存储，最新的排在最前面。请参阅分页部分以获取第一页之后的其他记录。
本接口能查询最近3个月的数据。

##### 限速规则：10次/2s

##### HTTP请求

`GET/api/spot/v3/accounts/<currency>/ledger`

##### 签名请求示例

`GET/api/spot/v3/accounts/btc/ledger?limit=3&after=2500723297813504`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
currency | String | 是 | 币种  
after | String | 否 | 请求此id之前（更旧的数据）的分页内容，传的值为对应接口的`ledger_id`等  
before | String | 否 | 请求此id之后（更新的数据）的分页内容，传的值为对应接口的`ledger_id`等 |  
limit | String | 否 | 分页返回的结果集数量，最大为100，不填默认返回100条  
type | String | 否 | 1.充值 2.提现 7.买入 8.卖出 18.交割合约转入 19.转出至交割合约 20.转入子账户21.转出至子账户
22.返手续费 25.otc买入 26.otc卖出 29.转出至资金账户 30.资金账户转入 31.转出至法币 32.法币转入 33.转出至杠杆
34.杠杆转入 35.借币 36.还币 37.市商计划送出38.市商计划返还 39.券商手续费转入 40.券商手续费转出 41.点卡抵扣币币手续费
42.购买点卡 43.点卡转让 44.市商计划额外送出 45.市商计划返还 46.币币账户转入 47.转出 币币账户 48.转出至组合 49.组合转入
50.挖矿扣除 51.挖矿所得 52.收益倍增 53.鼓励金分配 55.余币宝转入 56.转出至余币宝 57.永续合约转入 58.转出至永续合约
59.还糖果 60.点卡抵扣杠杆手续费 61.转出至套保账户 62.套保账户转入 63.点卡抵扣杠杆利息 64.矿池账户转入 65.转出至矿池账户
66.转出至期权账户 67.期权账户转入  
  
##### 返回参数

**参 数名** | **类 型** | **描 述**  
---|---|---  
ledger_id | String | 账单ID  
balance | String | 余额  
currency | String | 币种  
amount | String | 变动数量  
type | String | 流水来源  
timestamp | String | 账单创建时间  
details | String |
如果`type`是`trade`，则会有该`details`字段将包含`order`，`instrument`信息,如果`type`是`transfer`，则会有该`details`字段将包含`from`，`to`信息  
order_id | String | 交易的ID  
instrument_id | String | 交易的币对  
from | String | 转出账户  
`1`:币币账户  
`3`:交割合约  
`4`:法币账户  
`5`:币币杠杆账户  
`6`:资金账户  
`8`:余币宝账户  
`9`:永续合约账户  
`12`:期权合约  
`14`:挖矿账户  
`17`:借贷账户  
to | String | 转入账户  
`1`:币币账户  
`3`:交割合约  
`4`:法币账户  
`5`:币币杠杆账户  
`6`:资金账户  
`8`:余币宝账户  
`9`:永续合约账户  
`12`:期权合约  
`14`:挖矿账户  
`17`:借贷账户  
  
##### 解释说明

以下内容是参数名`type`的枚举值

流水来源类型 | 描述  
---|---  
transfer | 资金转入/转出  
trade | 交易产生的资金变动  
rebate | 返佣  
  
##### 返回示例

    
    
    [
        {
            "timestamp":"2019-03-18T07:26:50.000Z",
            "ledger_id":"3995466151",
            "created_at":"2019-03-18T07:26:50.000Z",
            "currency":"BTC",
            "amount":"0.0009985",
            "balance":"0.0049925",
            "type":"trade",
            "details":{
                "instrument_id":"BTC-USDT",
                "order_id":"2500723297813504",
                "product_id":"BTC-USDT"
            }
        },
        {
            "timestamp":"2019-03-18T07:26:50.000Z",
            "ledger_id":"3995466150",
            "created_at":"2019-03-18T07:26:50.000Z",
            "currency":"BTC",
            "amount":"0.0009985",
            "balance":"0.003994",
            "type":"trade",
            "details":{
                "instrument_id":"BTC-USDT",
                "order_id":"2500723297223680",
                "product_id":"BTC-USDT"
            }
        },
        {
            "timestamp":"2019-03-18T07:08:25.000Z",
            "ledger_id":"3995334780",
            "created_at":"2019-03-18T07:08:25.000Z",
            "currency":"BTC",
            "amount":"0.0009985",
            "balance":"0.0029955",
            "type":"trade",
            "details":{
                "instrument_id":"BTC-USDT",
                "order_id":"2500650881647616",
                "product_id":"BTC-USDT"
            }
        }
    ]
    

### 下单

币币交易提供限价单和市价单和高级限价单下单模式。只有当您的账户有足够的资金才能下单。

一旦下单，您的账户资金将在订单生命周期内被冻结。被冻结的资金以及数量取决于订单指定的类型和参数。

##### 限速规则：100次/2s （不同币对之间限速不累计）

##### HTTP请求

`POST /api/spot/v3/orders`

##### 签名请求示例

`POST /api/spot/v3/orders{"type": "limit", "side": "buy", "instrument_id":
"BTC-USDT", "size":"0.001", "client_oid": "oktspot79", "price": "4638.51",
"notional": "", "order_type": "3"}`

##### 请求参数

**参 数名** | **类 型** | **是 否必填** | **描 述**  
---|---|---|---  
client_oid | String | 否 | 由您设置的订单ID来识别您的订单,格式是字母（区分大小写）+数字 或者
纯字母（区分大小写），1-32位字符 （不能重复）  
type | String | 否 |
`limit`或`market`（默认是`limit`）。当以`market`（市价）下单，`order_type`只能选择`0`（普通委托）  
side | String | 是 | `buy` 或 `sell`  
instrument_id | String | 是 | 币对名称  
order_type | String | 否 | 参数填数字  
`0`：普通委托（order type不填或填0都是普通委托）  
`1`：只做Maker（Post only）  
`2`：全部成交或立即取消（FOK）  
`3`：立即成交并取消剩余（IOC）  
  
##### 限价单特殊参数

**参 数名** | **类 型** | **是 否必填** | **描 述**  
---|---|---|---  
price | String | 是 | 价格  
size | String | 是 | 买入或卖出的数量  
  
##### 市价单特殊参数

**参 数名** | **类 型** | **是 否必填** | **描 述**  
---|---|---|---  
size | String | 是 | 卖出数量，市价卖出时必填`size`  
notional | String | 是 | 买入金额，市价买入时必填`notional`  
  
##### 返回参数

**参 数名** | **类 型** | **描 述**  
---|---|---  
order_id | String | 订单ID  
client_oid | String | 由您设置的订单ID来识别您的订单  
result | Boolean | 下单结果。若是下单失败，将给出错误码提示  
error_code | String | 错误码，下单成功时为0，下单失败时会显示相应错误码  
error_message | String | 错误信息，下单成功时为空，下单失败时会显示错误信息  
  
##### 解释说明

client_oid

`client_oid`用户需要自己保证此ID不重复，OKEx不会进行排重提示，如有重复，撤单和查询订单时只能撤销或者查询出最新的一条数据。

instrument_id

`instrument_id`必须是有效的币对。币对列表可通过/ instruments接口获取。

type

下单时，您可以指定订单类型。您指定的订单类型将决定是否需要其他订单参数以及撮合引擎如何执行您的订单。如果`type`没有指定，订单类型将默认为`limit`。限价单既是默认订单类型，也是基本订单类型。限价单需要指定`price`和`size`。`size`是买入或卖出交易货币的数量，`price`表示每个交易货币相对计价货币的价格。限价单会按指定价格或更好的价格成交。根据市场条件，卖单可以按照指定价格或者更高价格来成交，买单可以按照指定价格或更低价格成交。如果限价单不能立即成交，那么限价单将进入深度列表，直到被另一个新订单成交或被用户撤单。
市价单不同于限价单，因为它们不提供价格控制。市价单提供了一种不必指定价格，而以固定数量的货币进行买入或者卖出的方式。市价单下单后会立即撮合，而不会被挂入深度列表。市价单总是吃单方`taker`并按`taker`收取手续费用。(注：如果你计划买入卖出的数量巨大时，将会对价格产生巨大影响，此时不推荐使用市价单)

price

`price`表示买入或卖出的价格。价格必须是价格步长`tick_size`的倍数。价格步长`tick_size`是价格的最小增量，可通过instruments接口获取。

size

`size`表示买入或卖出交易货币的数量。数量必须大于`min_size`。`size_increment`是交易货币数量的最小增量。上述参数都可通过instruments接口获取。
举例：假设 okb/usdt
的`min_size`是`10`，`size_increment`是`0.0001`。那么不能交易9.9个okb，但是可以交易10.0001个okb

notional

`notional`表示被用于市价买入的计价货币的数量，市价买入时必填。例如，在`BTC-USDT`交易时，市价单指定5000 USDT表示将花费5000
USDT购买BTC。

hold

对于限价买单，系统将冻结计价货币的数量 = 限定价格 x
买入数量。对于限价卖单，系统将冻结你想卖出的交易货币的数量。对于市价买单，notional数量的计价货币将被冻结。对于市价卖单，`size`数量的交易货币将被冻结。如果您取消部分成交或未成交的订单，剩余资金将被解除冻结。

订单生命周期

HTTP请求将在订单被拒绝（资金不足，参数无效等）或下单成功（由匹配引擎接受）时作出响应。一个200响应表示该订单被接收并且进入撮合。进入撮合的订单可以部分或全部立即成交（取决于价格和市场条件）。部分成交的时候将把订单的剩余数量继续进行撮合。完全成交的订单将进入已成交状态。
监听行情数据的用户建议使用`client_oid`字段以便在接受到的信息中标识对应的数据。

响应

成功接受的订单将被分配一个订单ID。订单是否成功接受取决于撮合引擎是否接受。 未成交的订单不会过期，并将保持撮合状态，直到被成交或取消。

##### 返回示例

    
    
    {
        "client_oid":"oktspot79",
        "error_message": "",
        "error_code": "0",
        "order_id":"2510789768709120",
        "result":true
    }
    

### 批量下单

下指定币对的多个订单（每次只能下最多4个币对且每个币对可批量下10个单）

##### 限速规则：50次/2s （不同币对之间限速累计）

##### HTTP请求

`POST /api/spot/v3/batch_orders`

##### 签名请求示例

`POST
/api/spot/v3/batch_orders[{"client_oid":"ww20180728","instrument_id":"btc-
usdt","side":"sell","type":"limit","size":"0.001","price":"10001","margin_trading
":"1"},{"client_oid":"w20180728","instrument_id":"btc-
usdt","side":"sell","type":"limit","size":"0.001","price":"10002","margin_trading
":"1"}]`

##### 请求参数

**参 数名** | **类 型** | **是 否必填** | **描 述**  
---|---|---|---  
client_oid | String | 否 | 由您设置的订单ID来识别您的订单,格式是字母（区分大小写）+数字 或者
纯字母（区分大小写），1-32位字符 （不能重复）  
type | String | 否 |
`limit`或`market`（默认是`limit`），当以`market`（市价）下单，`order_type`只能选择`0`（普通委托）  
side | String | 是 | `buy` 或 `sell`  
instrument_id | String | 是 | 币对名称  
order_type | String | 否 | 参数填数字  
`0`：普通委托（`order_type`不填或填`0`都是普通委托）  
`1`：只做Maker（Post only）  
`2`：全部成交或立即取消（FOK）  
`3`：立即成交并取消剩余（IOC）  
  
##### 限价单特殊参数

**参 数名** | **类 型** | **是 否必填** | **描 述**  
---|---|---|---  
price | String | 是 | 价格  
size | String | 是 | 买入或卖出的数量  
  
##### 市价单特殊参数

**参 数名** | **类 型** | **是 否必填** | **描 述**  
---|---|---|---  
size | String | 否 | [ 非必填 ] 卖出数量，市价卖出必填`size`  
notional | String | 否 | [ 非必填 ] 买入金额，市价买入时必填`notional`  
  
##### 返回参数

**参 数名** | **类 型** | **描 述**  
---|---|---  
order_id | String | 订单ID  
client_oid | String | 由您设置的订单ID来识别您的订单  
result | Boolean | 下单结果。若是下单失败，将给出错误码提示。  
error_code | String | 错误码，下单成功时为0，下单失败时会显示相应错误码  
error_message | String | 错误信息，下单成功时为空，下单失败时会显示错误信息  
  
##### 解释说明

`client_oid`的类型为字母（大小写）+数字或者纯字母（大小写），1-32位字符
，用户需要自己保证此ID不重复，OKEx不会进行排重提示，如有重复，撤单和查询订单时只能撤销或者查询最新的一条数据。

每次最多4个币对且每个币对最多10个订单，建议用户调用批量撤单接口后，再调用获取订单列表接口确认已撤销成功。

##### 返回示例

    
    
    {
        "btc_usdt":[
            {
                "client_oid":"oktspot80",
                "error_code":"0",
                "error_message":"",
                "order_id":"2510832677159936",
                "result":true
            },
            {
                "client_oid":"oktspot81",
                "error_code":"0",
                "error_message":"",
                "order_id":"2510832677225472",
                "result":true
            },
            {
                "client_oid":"oktspot82",
                "error_code":"0",
                "error_message":"",
                "order_id":"2510832677225473",
                "result":true
            }
        ]
    }
    

### 撤销指定订单

撤销之前下的未完成订单。

##### 限速规则：100次/2s （不同币对之间限速不累计）

##### HTTP请求

`POST /api/spot/v3/cancel_orders/<order_id> or <client_oid>`

##### 签名请求示例

`2018-10-12T07:34:30.223ZPOST/api/spot/v3/cancel_orders/a123{"instrument_id":"btc-
usdt"}`

##### 请求参数

**参 数名** | **类 型** | **是 否必填** | **描 述**  
---|---|---|---  
instrument_id | String | 是 | 提供此参数则撤销指定币对的相应订单，如果不提供此参数则返回错误码  
client_oid | String | 否 | `order_id`和`client_oid`必须且只能选一个填写，由您设置的订单ID来识别您的订单 ,
类型为字母（大小写）+数字或者纯字母（大小写）1-32位字符  
order_id | String | 否 | `order_id`和`client_oid`必须且只能选一个填写，订单ID  
  
##### 返回参数

**参 数名** | **类 型** | **描 述**  
---|---|---  
order_id | String | 订单ID  
client_oid | String | 由您设置的订单ID来识别您的订单  
result | Boolean | 撤单申请结果。若是撤单失败，将给出错误码提示  
error_code | String | 错误码，撤单成功时为0，撤单失败时会显示相应错误码  
error_message | String | 错误信息，撤单成功时为空，撤单失败时会显示错误信息  
  
##### 解释说明

`order_id`和`client_oid`必须且只能选一个填写

使用`client_oid`撤单时，用户需要自己保证此ID不重复，OKEx不会进行排重提示，如有重复，撤单时只能撤销最新的一条数据

如果订单无法取消（已经成交或已取消），那么返回的报错内容里将显示相应的原因。

##### 返回示例

    
    
    {
         "client_oid": "order123",
         "error_message": "",
         "error_code": "0",
         "order_id": "4407638476788736", 
         "result": true
    
    }
    

### 批量撤销订单

撤销指定的某一种或多种币对的未完成订单（每次只能下最多4个币对且每个币对可批量下10个单）。

##### 限速规则：50次/2s （不同币对之间限速累计）

##### HTTP请求

`POST /api/spot/v3/cancel_batch_orders`

##### 签名请求示例

`2018-10-12T07:30:49.664ZPOST
/api/spot/v3/cancel_batch_orders[{"instrument_id":"btc-
usdt","client_oids":["a123","a1234"]},{"instrument_id":"eth-
usdt","client_oids":["a12345","a123456"]}]`

##### 请求参数

**参 数名** | **类 型** | **是 否必填** | **描 述**  
---|---|---|---  
order_ids | List<String> | 否 | `order_id`和`client_oid`必须且只能选一个填写，订单ID  
client_oids | List<String> | 否 |
`order_id`和`client_oid`必须且只能选一个填写，由您设置的订单ID来识别您的订单，类型为字母（大小写）+数字或者纯字母（大小写），1-32位字符  
instrument_id | String | 是 | 币种  
  
##### 返回参数

**参 数名** | **类 型** | **描 述**  
---|---|---  
order_id | String | 订单ID  
client_oid | String | 由您设置的订单ID来识别您的订单  
instrument_id | String | 币种，如`btc-usdt`  
result | Boolean | 撤单申请结果  
error_code | String | 错误码，撤单成功时为0，撤单失败时会显示相应错误码  
error_message | String | 错误信息，撤单成功时为空，撤单失败时会显示错误信息  
  
##### 解释说明

批量撤单时候，要么都是`order_id`要么都是`client_oid`，否则会提示错误

使用`client_oid`批量撤单时，目前只支持一个币对下撤一个`client_oid`
，一次4个币对，用户需要自己保证此ID不重复，OKEx不会进行排重提示，如有重复，撤单时只能撤销最新的一条数据

使用`order_id`撤单时，每次最多4个币对且每个币对最多10个订单，建议用户调用批量撤单接口后，再调用获取订单列表接口确认已撤销成功。

##### 返回示例

    
    
    {
        "btc-usdt":[
        {
            "result":true,
            "client_oid":"a123",
            "error_message": "",
            "error_code": "0",
            "order_id": "2510832677225473"
         },
       {
            "result":true,
            "client_oid":"a1234",
            "error_message": "",
            "error_code": "0",
            "order_id": "2510832677225474"
         }
    ],
    "eth-usdt":[
        {
           "result":true,
            "client_oid":"a12345",
            "error_message": "",
            "error_code": "0",
            "order_id": "2510832677225475"
         },
       {
           "result":true,
            "client_oid":"a123456",
            "error_message": "",
            "error_code": "0",
            "order_id": "2510832677225476"
         }
    ]
    }
    

### 获取订单列表

列出您当前的订单信息（本接口能查询最近3个月订单信息）。这个请求支持分页，并且按委托时间倒序排序和存储，最新的排在最前面。

##### 限速规则：10次/2s

##### HTTP请求

`GET/api/spot/v3/orders`

##### 签名请求示例

`2019-03-18T07:49:43.306ZGET/api/spot/v3/orders?instrument_id=BTC-
USDT&state=-2&after=2500723297223680`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
instrument_id | String | 是 | 币对名称  
state | String | 是 | 订单状态  
`-2`:失败  
`-1`:撤单成功  
`0`:等待成交  
`1`:部分成交  
`2`:完全成交  
`3`:下单中  
`4`:撤单中  
`6`: 未完成（等待成交+部分成交）  
`7`:已完成（撤单成功+完全成交）  
after | String | 否 | 请求此id之前（更旧的数据）的分页内容，传的值为对应接口的`order_id`  
before | String | 否 | 请求此id之后（更新的数据）的分页内容，传的值为对应接口的`order_id` |  
limit | String | 否 | 分页返回的结果集数量，最大为100，不填默认返回100条  
  
##### 返回参数

**参 数名** | **类 型** | **描 述**  
---|---|---  
order_id | String | 订单ID  
client_oid | String | 用户设置的订单ID  
price | String | 委托价格  
size | String | 委托数量（交易货币数量）  
notional | String | 买入金额，市价买入时返回  
instrument_id | String | 币对名称  
type | String | `limit`或`market`（默认是`limit`）  
side | String | `buy` 或 `sell`  
timestamp | String | 订单创建时间  
filled_size | String | 已成交数量  
filled_notional | String | 已成交金额  
order_type | String | `0`：普通委托  
`1`：只做Maker（Post only）  
`2`：全部成交或立即取消（FOK）  
`3`：立即成交并取消剩余（IOC）  
state | String | 订单状态  
`-2`：失败  
`-1`：撤单成功  
`0`：等待成交  
`1`：部分成交  
`2`：完全成交  
`3`：下单中  
`4`：撤单中  
price_avg | String | 成交均价  
  
##### 解释说明

`status`为`state`旧版参数，会短期兼容，建议尽早切换`state`。

`client_oid`的类型为字母（大小写）+数字或者纯字母（大小写），1-32位字符
，用户需要自己保证此ID不重复，OKEx不会进行排重提示，如有重复，查询订单时只能查询出最新的一条数据。

如果订单在其生命周期内没有任何成交，其记录可能被清除。这表示订单详细信息将不可用本接口来获取。

未成交的订单可能会根据市场情况在你发起请求和服务器响应之间改变状态。

##### 返回示例

    
    
    [
         {
                "client_oid":"oktspot76",
                "created_at":"2019-03-18T07:26:49.000Z",
                "filled_notional":"3.9734",
                "filled_size":"0.001",
                "funds":"",
                "instrument_id":"BTC-USDT",
                "notional":"",
                "order_id":"2500723297813504",
                "order_type":"0",
                "price":"4013",
                "price_avg": "4013",
                "product_id":"BTC-USDT",
                "side":"buy",
                "size":"0.001",
                "status":"filled",
                "state":"-2",
                "timestamp":"2019-03-18T07:26:49.000Z",
                "type":"limit"
         },
         {
                "client_oid":"oktspot75",
                "created_at":"2019-03-18T07:26:49.000Z",
                "filled_notional":"3.9734",
                "filled_size":"0.001",
                "funds":"",
                "instrument_id":"BTC-USDT",
                "notional":"",
                "order_id":"2500723297223680",
                "order_type":"0",
                "price":"4013",
                "price_avg": "4013",
                "product_id":"BTC-USDT",
                "side":"buy",
                "size":"0.001",
                "status":"filled",
                "state": "-2",    
                "timestamp":"2019-03-18T07:26:49.000Z",
                "type":"limit"
         },
         {
                "client_oid":"oktspot74",
                "created_at":"2019-03-18T07:08:24.000Z",
                "filled_notional":"3.9768",
                "filled_size":"0.001",
                "funds":"",
                "instrument_id":"BTC-USDT",
                "notional":"",
                "order_id":"2500650881647616",
                "order_type":"0",
                "price":"4016.8",
                "price_avg": "4013",
                "product_id":"BTC-USDT",
                "side":"buy",
                "size":"0.001",
                "staus":"filled",
                "state": "-2",    
                "timestamp":"2019-03-18T07:08:24.000Z",
                "type":"limit"
         }
    
    ]
    

### 获取所有未成交订单

列出您当前所有的订单信息。这个请求支持分页，并且按时间倒序排序和存储，最新的排在最前面。请参阅分页部分以获取第一页之后的其他纪录。

##### 限速规则：20次/2s

##### HTTP请求

`GET/api/spot/v3/orders_pending`

##### 签名请求示例

`2018-09-12T07:51:51.138ZGET/api/spot/v3/orders_pending?limit=2&instrument_id=BTC-
USDT&after=2500723297223680`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
instrument_id | String | 是 | 币对名称  
after | String | 否 | 请求此id之前（更旧的数据）的分页内容，传的值为对应接口的`order_id`  
before | String | 否 | 请求此id之后（更新的数据）的分页内容，传的值为对应接口的`order_id` |  
limit | String | 否 | 分页返回的结果集数量，最大为100，不填默认返回100条  
  
##### 返回参数

**参 数名** | **类 型** | **描 述**  
---|---|---  
order_id | String | 订单ID  
client_oid | String | 用户设置的订单ID  
price | String | 委托价格  
size | String | 委托数量（交易货币数量）  
notional | String | 买入金额，市价买入时返回  
order_type | String | `0`：普通委托  
`1`：只做Maker（Post only）  
`2`：全部成交或立即取消（FOK）  
`3`：立即成交并取消剩余（IOC）  
instrument_id | String | 币对名称  
side | String | `buy` 或 `sell`  
type | String | `limit`或`market`（默认是`limit`）  
timestamp | String | 订单创建时间  
filled_size | String | 已成交数量  
filled_notional | String | 已成交金额  
state | String | 订单状态  
`0`:等待成交  
  
##### 解释说明

`status`为`state`旧版参数，会短期兼容，建议尽早切换`state`。

`client_oid`的类型为字母（大小写）+数字或者纯字母类型 ，1-32位字符
，用户需要自己保证此ID不重复，OKEx不会进行排重提示，如有重复，查询订单时只能查询出最新的一条数据。

本接口只能查询所有未成交或者部分成交的订单

未成交的订单可能会根据市场情况在你发起请求和服务器响应之间改变状态。

##### 返回示例

    
    
    [
            {
                "client_oid":"oktspot86",
                "created_at":"2019-03-20T03:28:14.000Z",
                "filled_notional":"0",
                "filled_size":"0",
                "funds":"",
                "instrument_id":"BTC-USDT",
                "notional":"",
                "order_id":"2511109744100352",
                "order_type":"0",
                "price":"3594.7",
                "price_avg":"",
                "product_id":"BTC-USDT",
                "side":"buy",
                "size":"0.001",
                "status":"open",
                "state":"0",
                "timestamp":"2019-03-20T03:28:14.000Z",
                "type":"limit"
            },
            {
                "client_oid":"oktspot85",
                "created_at":"2019-03-20T03:28:10.000Z",
                "filled_notional":"0",
                "filled_size":"0",
                "funds":"",
                "instrument_id":"BTC-USDT",
                "notional":"",
                "order_id":"2511109459543040",
                "order_type":"0",
                "price":"3594.9",
                "price_avg":"",
                "product_id":"BTC-USDT",
                "side":"buy",
                "size":"0.001",
                "status":"open",
                "state":"0",
                "timestamp":"2019-03-20T03:28:10.000Z",
                "type":"limit"
            }
    ]
    

### 获取订单信息

通过订单ID获取单个订单信息。可以获取近3个月订单信息。已撤销的未成交单只保留2个小时。

##### 限速规则：20次/2s

##### HTTP请求

`GET/api/spot/v3/orders/<order_id>`

或

`GET/api/spot/v3/orders/<client_oid>`

##### 签名请求示例

`2018-09-12T07:54:01.582ZGET/api/spot/v3/orders/23356?instrument_id=BTC-USDT`

或

`2018-09-12T07:54:01.582ZGET/api/spot/v3/orders/2e3356?instrument_id=BTC-USDT`

##### 请求参数

**参 数名** | **类 型** | **描 述**  
---|---|---  
instrument_id | String | [ 必填 ] 币对  
order_id | String | [ 非必填 ] 订单ID ,order_id和client_oid必须且只能选一个填写  
client_oid | String | [ 非必填 ] order_id和client_oid必须且只能选一个填写.由您设置的订单ID来识别您的订单 ，
类型为字母（大小写）+数字或者纯字母（大小写）1-32位字符  
  
##### 返回参数

**参 数名** | **类 型** | **描 述**  
---|---|---  
order_id | String | 订单ID  
client_oid | String | 由您设置的订单ID来识别您的订单  
price | String | 委托价格  
size | String | 委托数量（交易货币数量）  
order_type | String | `0`：普通委托  
`1`：只做Maker（Post only）  
`2`：全部成交或立即取消（FOK）  
`3`：立即成交并取消剩余（IOC）  
notional | String | 买入金额，市价买入时返回  
instrument_id | String | 币对名称  
side | String | `buy` 或 `sell`  
type | String | `limit`或`market`（默认是`limit`）  
timestamp | String | 订单创建时间  
filled_size | String | 已成交数量  
filled_notional | String | 已成交金额  
state | String | 订单状态  
`-2`:失败  
`-1`:撤单成功  
`0`:等待成交  
`1`:部分成交  
`2`:完全成交  
`3`:下单中  
`4`:撤单中  
price_avg | String | 成交均价  
  
##### 解释说明

`status`为`state`旧版参数，会短期兼容，建议尽早切换`state`。

`client_oid`的类型为字母（大小写）+数字或者纯字母（大小写）类型1-32位字符
，用户需要自己保证此ID不重复，OKEx不会进行排重提示，如有重复，查询订单时只能查询出最新的一条数据。

如果订单在其生命周期内没有任何成交，其记录可能被清除，则响应可能因为没有相应的匹配而返回状态码404。

未成交的订单可能会根据市场情况在你发起请求和服务器响应之间改变状态。

##### 返回示例

    
    
    {
        "client_oid":"oktspot70",
        "created_at":"2019-03-15T02:52:56.000Z",
        "filled_notional":"3.8886",
        "filled_size":"0.001",
        "funds":"",
        "instrument_id":"BTC-USDT",
        "notional":"",
        "order_id":"2482659399697408",
        "order_type":"0",
        "price":"3927.3",
        "price_avg":"3927.3",
        "product_id":"BTC-USDT",
        "side":"buy",
        "size":"0.001",
        "status":"filled",
        "state":"2",
        "timestamp":"2019-03-15T02:52:56.000Z",
        "type":"limit"
    }
    

### 获取成交明细

获取最近的成交明细表。这个请求支持分页，并且按成交时间倒序排序和存储，最新的排在最前面。请参阅分页部分以获取第一页之后的其他记录。
本接口能查询最近3月的数据。

##### 限速规则：10次/2s

##### HTTP请求

`GET/api/spot/v3/fills`

##### 签名请求示例

`2018-09-12T07:56:11.922ZGET/api/spot/v3/fills?order_id=23212&instrument_id=btc-
usdt&limit=2&after=2&before=4`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
order_id | String | 否 | 订单ID，不填写`order_id`，返回当前`instrument_id`下的所有订单成交明细  
instrument_id | String | 是 | 币对名称  
after | String | 否 | 请求此id之前（更旧的数据）的分页内容，传的值为对应接口的`ledger_id`  
before | String | 否 | 请求此id之后（更新的数据）的分页内容，传的值为对应接口的`ledger_id` |  
limit | String | 否 | 分页返回的结果集数量，最大为100，不填默认返回100条  
  
##### 返回参数

**参 数名** | **类 型** | **描 述**  
---|---|---  
ledger_id | String | 账单ID  
trade_id | String | 成交ID  
instrument_id | String | 币对名称  
price | String | 成交价格  
size | String | 成交数量  
order_id | String | 订单ID  
timestamp | String | 订单成交时间  
exec_type | String | 流动性方向（`T` 或 `M`）  
fee | String | 手续费  
side | String | 账单方向（`buy`、`sell`）  
currency | String | 币种  
  
##### 解释说明

此接口一笔成交会返回2条数据，一个以计价货币计算的，一个是以交易货币计算的。

手续费

`fee`字段：负数的`fee`表示平台收取的手续费，正数的`fee`表示表示平台向达到指定lv交易等级的用户支付的挂单奖励（返佣）

流动性

`exec_type`字段表示该账单是maker还是taker产生的。`M`表示Maker，`T`表示Taker。

分页

返回账单列表的`ledger_id`按降序排列，从最大`ledger_id`到最小`ledger_id`。`OK-
after`都会有这样的第一笔`ledger_id`，以便将来的请求使用`OK-after`参数将获取一个更大的`ledger_id`（新的账单）。

##### 返回示例

    
    
    [
        {
            "created_at": "2019-11-25T07:45:05.000Z",
            "currency": "USDT",
            "exec_type": "M",
            "fee": "-0.01915417",
            "instrument_id": "OKB-USDT",
            "ledger_id": "8161858573",
            "liquidity": "M",
            "order_id": "3927696997697536",
            "price": "1.7793",
            "product_id": "OKB-USDT",
            "side": "buy",
            "size": "19.1541645",
            "timestamp": "2019-11-25T07:45:05.000Z"
        },
        {
            "created_at": "2019-11-25T07:45:05.000Z",
            "currency": "OKB",
            "exec_type": "M",
            "fee": "0",
            "instrument_id": "OKB-USDT",
            "ledger_id": "8161858572",
            "liquidity": "M",
            "order_id": "3927696997697536",
            "price": "1.7793",
            "product_id": "OKB-USDT",
            "side": "sell",
            "size": "10.765",
            "timestamp": "2019-11-25T07:45:05.000Z"
        }
    ]
    

### 委托策略下单

委托策略下单

提供止盈止损、跟踪委托、冰山委托和时间加权委托策略

##### 限速规则：40次/2s

##### HTTP请求

`POST /api/spot/v3/order_algo`

##### 请求示例

`POST /api/spot/v3/order_algo{"instrument_id":"BTC-
USDT","order_type":"1","mode":"1","side":"sell","size":"0.005","trigger_price":"8000","algo_price":"7500"}`（止盈止损）

##### 请求参数（通用）

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
instrument_id | String | 是 | 币对名称  
mode | String | 是 | `1`：币币  
`2`：杠杆  
order_type | String | 是 | `1`：止盈止损  
`2`：跟踪委托  
`3`：冰山委托  
`4`：时间加权  
size | String | 是 | 委托总数，填写值1\<=X\<=1000000的数  
side | String | 是 | `buy` 或 `sell`  
  
##### 止盈止损参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
trigger_price | String | 是 | 触发价格，填写值0\<X\<=1000000  
algo_price | String | 是 | 委托价格，填写值0\<X\<=1000000  
algo_type | String | 是 | 1:限价 2:市场价；触发价格类型，默认是1:限价，为2:市场价时，委托价格不必填；  
  
##### 跟踪委托参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
callback_rate | String | 是 | 回调幅度，填写值0.001（0.1%）\<=X\<=0.05（5%）  
trigger_price | String | 是 | 激活价格 ，填写值0\<X\<=1000000  
  
##### 冰山委托参数 （最多同时存在6单）

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
algo_variance | String | 是 | 委托深度，填写值0.0001(0.01%)\<=X\<=0.01（1%）  
avg_amount | String | 是 | 单笔均值，填写值 本次委托总量的1/1000\<=X\<=本次委托总量  
limit_price | String | 是 | 价格限制 ，填写值0\<X\<=1000000  
  
##### 时间加权参数 （最多同时存在6单）

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
sweep_range | String | 是 | 扫单范围，填写值0.005（0.5%）\<=X\<=0.01（1%）  
sweep_ratio | String | 是 | 扫单比例，填写值 0.01\<=X\<=1  
single_limit | String | 是 | 单笔上限，填写值 本次委托总量的1/1000\<=X\<=本次委托总量  
limit_price | String | 是 | 价格限制，填写值0\<X\<=1000000  
time_interval | String | 是 | 委托间隔，填写值5\<=X\<=120  
  
#### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
result | String | 调用接口返回结果  
algo_id | String | 订单ID，下单失败时，此字段值为`-1`  
error_code | String | 错误码，下单成功时为0，下单失败时会显示相应错误码  
error_message | String | 错误信息，下单成功时为空，下单失败时会显示错误信息  
  
##### 返回示例

    
    
    {
        "algo_id": 329967,
        "error_message": "",
        "error_code": "0",
        "result": true
    }
    

### 委托策略撤单

委托策略撤单

根据指定的algo_id撤销某个币的未完成订单，每次最多可撤6（冰山/时间）/10（计划/跟踪）个。

##### 限速规则：20 次/2s

##### HTTP请求

`POST /api/spot/v3/cancel_batch_algos`

##### 请求示例

单个撤单：`POST /api/spot/v3/cancel_batch_algos{"instrument_id": "BTC-
USDT","order_type":"1","algo_ids": ["1600593327162368"]}`

批量撤单：`POST /api/spot/v3/cancel_batch_algos{"instrument_id": "BTC-
USDT","order_type":"1","algo_ids":["1600593327162368","1600593327162369"]}`

##### 请求参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
instrument_id | String | 是 | 撤销指定的币对  
algo_ids | List<String> | 是 | 撤销指定的委托单ID  
order_type | String | 是 | `1`：止盈止损  
`2`：跟踪委托  
`3`：冰山委托  
`4`：时间加权  
  
##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
instrument_id | String | 指定的币对  
order_type | String | `1`：止盈止损  
`2`：跟踪委托  
`3`：冰山委托  
`4`：时间加权  
algo_ids | String | 撤销指定的委托单ID  
result | String | 调用接口返回结果  
error_code | String | 错误码，撤单成功时为0，撤单失败时会显示相应错误码  
error_message | String | 错误信息，撤单成功时为空，撤单失败时会显示错误信息  
  
返回参数

返回值是已发起撤销操作的委托单ID，不代表这些委托单已成功撤销，正在成交中的无法撤销，未成交的可成功撤销。

解释说明

无法保证一定会成功撤销，建议用户调用撤单接口后，再调用获取委托单列表接口确认。

##### 返回示例

    
    
    {
        "result": true,
        "error_message": "",
        "error_code": "0",
        "algo_ids": [
            "329967"
        ],
        "instrument_id": "BTC-USDT",
        "order_type": "1"
    }
    

### 获取当前账户交易手续费费率

获取您当前账户交易等级对应的手续费费率，母账户下的子账户的费率和母账户一致。每天凌晨0点更新一次

##### 限速规则：1次/10s

##### HTTP请求

`GET/api/spot/v3/trade_fee`

##### 签名请求示例

`GET/api/spot/v3/trade_fee`

##### 返回参数

**参 数名** | **类 型** | **描 述**  
---|---|---  
taker | String | 吃单手续费率  
maker | String | 挂单手续费率  
timestamp | String | 数据返回时间  
  
##### 返回示例

    
    
    {
        "maker": "0.001",
        "taker": "0.0015",
        "timestamp": "2019-12-05T09:06:20.260Z"
    }
    

### 获取委托单列表

获取委托单列表

列出您当前所有的订单信息。

##### 限速规则：20次/2s

##### HTTP请求

`GET/api/spot/v3/algo`

##### 请求示例

`GET/api/spot/v3/algo?instrument_id=BTC-USDT&order_type=1`

##### 请求参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
instrument_id | String | 是 | 指定的币对  
order_type | String | 是 | `1`：止盈止损  
`2`：跟踪委托  
`3`：冰山委托  
`4`：时间加权  
status | String | 非必填 | 【`status`和`algo_id`必填且只能填其一】  
订单状态  
`1`：待生效  
`2`：已生效  
`3`：已撤销  
`4`：部分生效  
`5`：暂停生效  
`6`：委托失败  
【只有冰山和加权有`4`、`5`状态】  
algo_id | String | 非必填 | 【`status`和`algo_id`必填且只能填其一】  
查询指定的委托单ID  
before | string | 否 | 请求此id之后（更新的数据）的分页内容  
after | string | 否 | 请求此id之前（更旧的数据）的分页内容  
limit | string | 否 | 分页返回的结果集数量，默认为`100`，最大为`100`  
  
##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
instrument_id | String | 指定的币对  
order_type | String | `1`：止盈止损  
`2`：跟踪委托  
`3`：冰山委托  
`4`：时间加权  
timestamp | String | 委托时间  
rejected_at | String | 委托失效时间  
algo_id | String | 委托单ID  
status | String | 订单状态  
`1`: 待生效  
`2`: 已生效  
`3`: 已撤销  
`4`: 部分生效  
`5`: 暂停生效  
size | String | 委托数量,填写值1\<=X\<=1000000的整数  
algo_price | String | 策略委托价格  
mode | String | `1`：币币  
`2`：杠杆  
order_id | String | 订单 ID  
side | String | `Buy` 或 `Sell`  
trigger_price | String | 策略委托触发价格  
  
止盈止损

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
trigger_price | String | 触发价格，填写值0\<X  
algo_price | String | 委托价格，填写值0\<X\<=1000000  
algo_type | String | 1:限价 2:市场价；  
  
跟踪委托

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
callback_rate | String | 回调幅度，填写值0.001（0.1%）\<=X\<=0.05（5%）  
trigger_price | String | 激活价格 ，填写值0\<X\<=1000000  
  
冰山委托

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
algo_variance | String | 委托深度，填写值0\<=X\<=0.01（1%）  
avg_amount | String | 单笔均值，填写2-500的整数（永续2-500的整数）  
limit_price | String | 价格限制 ，填写值0\<X\<=1000000  
deal_value | String | 已成交量  
  
时间加权

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
sweep_range | String | 扫单范围，填写值0.005（0.5%）\<=X\<=0.01（1%）  
sweep_ratio | String | 扫单比例，填写值 0.01\<=X\<=1  
single_limit | String | 单笔上限，填写值10\<=X\<=2000（永续2-500的整数）  
limit_price | String | 价格限制，填写值0\<X\<=1000000  
time_interval | String | 委托间隔，填写值5\<=X\<=120  
deal_value | String | 已委托量  
  
##### 返回示例

    
    
    {
        "btc_usdt": [
            {
                "algo_id": "329967",
                "algo_price": "7500",
                "instrument_id": "btc_usdt",
                "mode": "1",
                "order_id": "",
                "order_type": "1",
                "rejected_at": "2019-10-09T15:59:59.000Z",
                "side": "sell",
                "size": "0.005",
                "status": "3",
                "timestamp": "2019-10-08T09:43:56.000Z",
                "trigger_price": "8000"
            },
            {
                "algo_id": "329997",
                "algo_price": "7500",
                "instrument_id": "btc_usdt",
                "mode": "1",
                "order_id": "",
                "order_type": "1",
                "rejected_at": "2019-10-09T15:59:59.000Z",
                "side": "sell",
                "size": "0.005",
                "status": "1",
                "timestamp": "2019-10-08T10:10:44.000Z",
                "trigger_price": "8000"
            }
        ]
    }
    

### 公共-获取币对信息

获取交易币对的列表，查询各币对的交易限制和价格步长等信息。

##### 限速规则：20次/2s

##### HTTP请求

`GET/api/spot/v3/instruments`

##### 请求示例

`2018-09-12T07:56:45.645ZGET/api/spot/v3/instruments`

##### 返回参数

**参 数名** | **类 型** | **描 述**  
---|---|---  
instrument_id | String | 币对名称  
base_currency | String | 交易货币币种  
quote_currency | String | 计价货币币种  
min_size | String | 最小交易数量  
size_increment | String | 交易货币数量精度  
tick_size | String | 交易价格精度  
  
##### 解释说明

`min_size`指下单数量的最小值（交易货币）。`size_increment`（交易数量步长）是指下单数量的最小增量。例如，当`size_increment`为`0.000001`，委托数量传入`0.0000126`将被系统按截尾法修正为`0.000012`。

`tick_size`（价格步长）是指下单价格的最小增量，委托价格必须是`tick_size`的倍数。例如，当`tick_size`为0.0001，委托价格传入0.02237将被系统按截尾法修正为0.0223。

##### 返回示例

    
    
    [
        {
            "base_currency":"BTC",
            "instrument_id":"BTC-USDT",
            "min_size":"0.001",
            "quote_currency":"USDT",
            "size_increment":"0.00000001",
            "tick_size":"0.1"
        },
        {
            "base_currency":"ETH",
            "instrument_id":"ETH-USDT",
            "min_size":"0.001",
            "quote_currency":"USDT",
            "size_increment":"0.000001",
            "tick_size":"0.01"
        }
    ]
    

### 公共-获取深度数据

获取币对的深度列表。这个请求不支持分页，一个请求返回整个深度列表。

##### 限速规则：20次/2s

##### HTTP请求

`GET/api/spot/v3/instruments/<instrument_id>/book`

##### 请求示例

`2019-03-20T07:48:09.130ZGET/api/spot/v3/instruments/BTC-
USDT/book?size=5&depth=0.2`

##### 请求参数

**参 数名** | **类 型** | **描 述**  
---|---|---  
size | String | [ 非必填 ] 返回深度档位数量，最多返回`200`  
depth | String | [ 非必填 ] 按价格合并深度，例如：`0.1`或`0.001`  
instrument_id | String | [ 必填 ] 币对  
  
##### 返回参数

###### 返回数据

**参 数名** | **类 型** | **描 述**  
---|---|---  
asks | List<String> | 卖方深度  
bids | List<String> | 买方深度  
timestamp | String | 时间戳  
  
##### 解释说明

asks和bids值数组举例说明： ["411.8","10","8"] 411.8为深度价格，10为此价格数量，8为此深度由几笔订单组成。

当`size`不传时，返回200条；`size`传`0`时，返回0条；`size`最大`200`，传大于`200`的数时，返回200条。

按价格合并深度是指每个价格区间将仅返回一个数量，就像在该价格区间上只有一个订单。

`asks`: 卖方深度  
`bids`: 买方深度

##### 返回示例

    
    
    {
        "asks":[
            [
                "3993.2",
                "0.41600068",
                "1"
            ],
            [
                "3993.4",
                "1.24807818",
                "3"
            ]
        ],
        "bids":[
            [
                "3993",
                "0.15149658",
                "2"
            ],
            [
                "3992.8",
                "1.19046818",
                "1"
            ]
        ],
        "timestamp":"2019-03-20T03:55:37.888Z"
    }
    

### 公共-获取全部ticker信息

获取平台全部币对的最新成交价、买一价、卖一价和24小时交易量的快照信息。

##### 限速规则：20次/2s

##### HTTP请求

`GET/api/spot/v3/instruments/ticker`

##### 请求示例

`2018-09-12T07:57:26.537ZGET/api/spot/v3/instruments/ticker`

##### 返回参数

**参 数名** | **类 型** | **描 述**  
---|---|---  
instrument_id | String | 币对名称  
last | String | 最新成交价  
last_qty | String | 最新成交的数量  
best_ask | String | 卖一价  
best_ask_size | String | 卖一价对应的量  
best_bid | String | 买一价  
best_bid_size | String | 买一价对应的数量  
open_24h | String | 24小时开盘价  
high_24h | String | 24小时最高价  
low_24h | String | 24小时最低价  
base_volume_24h | String | 24小时成交量，按交易货币统计  
quote_volume_24h | String | 24小时成交量，按计价货币统计  
timestamp | String | 系统时间戳  
  
##### 解释说明

最高价、最低价和成交量都是按最近24小时为维度统计的。

24小时开盘价取值来自24小时前那一分钟的K线的开盘价。即
2018年7月23日08:23:45，此时的涨跌幅依靠的是开盘价是2018年7月22日08:23:00时的价格。

##### 返回示例

    
    
    {
        "best_ask": "7222.2",
        "best_bid": "7222.1",
        "instrument_id": "BTC-USDT",
        "product_id": "BTC-USDT",
        "last": "7222.2",
        "last_qty": "0.00136237",
        "ask": "7222.2",
        "best_ask_size": "0.09207739",
        "bid": "7222.1",
        "best_bid_size": "3.61314948",
        "open_24h": "7356.8",
        "high_24h": "7367.7",
        "low_24h": "7160",
        "base_volume_24h": "18577.2",
        "timestamp": "2019-12-11T07:48:04.014Z",
        "quote_volume_24h": "134899542.8"
    }
    

### 公共-获取某个ticker信息

获取币对的最新成交价、买一价、卖一价和24小时交易量的快照信息。

##### 限速规则：20次/2s

##### HTTP请求

`GET/api/spot/v3/instruments/<instrument-id>/ticker`

##### 请求示例

`2019-03-13T11:42:09.849ZGET/api/spot/v3/instruments/BTC-USDT/ticker`

##### 请求参数

**参 数名** | **类 型** | **描 述**  
---|---|---  
instrument_id | String | [ 必填 ] 币对  
  
##### 返回参数

**参 数名** | **类 型** | **描 述**  
---|---|---  
instrument_id | String | 币对名称  
last | String | 最新成交价  
last_qty | String | 最新成交的数量  
best_ask | String | 卖一价  
best_ask_size | String | 卖一价对应的量  
best_bid | String | 买一价  
best_bid_size | String | 买一价对应的数量  
open_24h | String | 24小时开盘价  
high_24h | String | 24小时最高价  
low_24h | String | 24小时最低价  
base_volume_24h | String | 24小时成交量，按交易货币统计  
quote_volume_24h | String | 24小时成交量，按计价货币统计  
timestamp | String | 系统时间戳  
  
##### 解释说明

最高价、最低价和成交量都是按最近24小时为维度统计的。

24小时开盘价取值来自24小时前那一分钟的K线的开盘价。即
2018年7月23日08:23:45，此时的涨跌幅依靠的是开盘价是2018年7月22日08:23:00时的价格。

##### 返回示例

    
    
    {
        "best_ask": "7222.2",
        "best_bid": "7222.1",
        "instrument_id": "BTC-USDT",
        "product_id": "BTC-USDT",
        "last": "7222.2",
        "last_qty": "0.00136237",
        "ask": "7222.2",
        "best_ask_size": "0.09207739",
        "bid": "7222.1",
        "best_bid_size": "3.61314948",
        "open_24h": "7356.8",
        "high_24h": "7367.7",
        "low_24h": "7160",
        "base_volume_24h": "18577.2",
        "timestamp": "2019-12-11T07:48:04.014Z",
        "quote_volume_24h": "134899542.8"
    }
    

### 公共-获取成交数据

本接口能查询最近60条数据。

##### 限速规则：20次/2s

##### HTTP请求

`GET/api/spot/v3/instruments/<instrument_id>/trades`

##### 签名请求示例

`2018-09-12T07:58:34.414ZGET/api/spot/v3/instruments/LTC-USDT/trades?limit=20`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
instrument_id | String | 是 | 币对名称  
limit | String | 否 | 分页返回的结果集数量，最大为60，不填默认返回60条  
  
##### 返回参数

**参 数名** | **类 型** | **描 述**  
---|---|---  
timestamp | String | 成交时间  
trade_id | String | 成交ID  
price | String | 成交价格  
size | String | 成交数量  
side | String | 成交方向  
  
##### 解释说明

成交方向`side`是指Taker订单的下单方向，Taker表示主动与深度列表中挂单进行成交。`buy`表示价格上涨，因为Taker是买单吃掉深度，所以价格将上行。相反，`sell`表示价格下跌。

##### 返回示例

    
    
    [
        {
            "time":"2019-04-12T02:07:30.523Z",
            "timestamp":"2019-04-12T02:07:30.523Z",
            "trade_id":"1296412902",
            "price":"4913.4",
            "size":"0.00990734",
            "side":"buy"
        },
        {
            "time":"2019-04-12T02:07:30.455Z",
            "timestamp":"2019-04-12T02:07:30.455Z",
            "trade_id":"1296412899",
            "price":"4913.2",
            "size":"0.17820096",
            "side":"sell"
        }
    ]
    

### 公共-获取K线数据

获取币对的K线数据。K线数据按请求的粒度分组返回，K线数据最多可获取最近1440条。

##### 限速规则：20次/2s

##### HTTP请求

`GET/api/spot/v3/instruments/<instrument_id>/candles`

##### 签名请求示例

`GET/api/spot/v3/instruments/BTC-
USDT/candles?granularity=86400&start=2019-03-19T16:00:00.000Z&end=2019-03-20T16:00:00.000Z`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
instrument_id | String | 是 | 币对  
start | String | 否 | 开始时间（ISO 8601标准）  
end | String | 否 | 结束时间（ISO 8601标准）  
granularity | String | 否 |
时间粒度，以秒为单位，默认值`60`。如`[60/180/300/900/1800/3600/7200/14400/21600/43200/86400/604800]`，详见下解释说明  
  
##### 返回参数

**参 数名** | **类 型** | **描 述**  
---|---|---  
time | String | 开始时间  
open | String | 开盘价格  
high | String | 最高价格  
low | String | 最低价格  
close | String | 收盘价格  
volume | String | 交易量  
  
##### 解释说明

如果用户没有提供开始时间或结束时间中的任一字段，则两个字段都将被忽略。未提供开始时间和结束时间的请求，则系统按时间粒度返回最近的200条数据。

时间粒度`granularity`必须是`[60 180 300 900 1800 3600 7200 14400 21600 43200 86400
604800 2678400 8035200 16070400 31536000]]`中的任一值，否则请求将被拒绝。这些值分别对应的是`[1min 3min
5min 15min 30min 1hour 2hour 4hour 6hour 12hour 1day 1week 1 month 3 months 6
months and 1 year]`的时间段。

K线数据可能不完整。K线数据不应该轮询调用。

单次请求的最大数据量是`200`。如果您选择的开始/结束时间和时间粒度导致超过单次请求的最大数据量，您的请求将只会返回200个数据。如果您希望在更大的时间范围内获取足够精细的数据，则需要使用多个开始/结束范围进行多次请求。

##### 返回示例

    
    
    [
        [
            "2019-03-19T16:00:00.000Z",
            "3997.3",
            "4031.9",
            "3982.5",
            "3998.7",
            "26175.21141385"
        ],
        [
            "2019-03-18T16:00:00.000Z",
            "3980.6",
            "4014.6",
            "3968.9",
            "3997.3",
            "33053.48725643"
        ]
    ]
    

### 币币杠杆API

币币杠杆交易的行情信息，账户信息，订单操作，订单查询，账单明细查询。

说明：因为要和老版本做兼融，实际有些接口返回参数会有多余，请以文档中返回参数说明为准。

例如币币账户信息接口返回`frozen`，`hold`和`holds`参数值相同，以`hold`为准；获取借币记录接口返回参数 `repay_amount`
和 `returned_amount`，`repay_interest` 和`paid_interest`
参数的值相同，`product_id`和`instrument_id`相同等等

### 币币杠杆账户信息

获取币币杠杆账户资产列表，查询各币种的余额、冻结和可用等信息。

##### 限速规则：20次/2s

##### HTTP请求

`GET/api/margin/v3/accounts`

##### 签名请求示例

`2018-09-13T02:25:41.946ZGET/api/margin/v3/accounts`

##### 返回参数

**参 数名** | **类 型** | **描 述**  
---|---|---  
instrument_id | String | 杠杆币对名称  
currency | String | 杠杆币对下的币种名称  
balance | String | 余额  
hold | String | 冻结（不可用）  
available | String | 可用于交易数量  
risk_rate | String | 风险率  
can_withdraw | String | 可划转数量  
liquidation_price | String | 强平价  
borrowed | String | 已借币（已借未还的部分）  
lending_fee | String | 利息（未还的利息）  
margin_ratio | String | 保证金率  
maint_margin_ratio | String | 维持保证金率  
tiers | String | 当前借币数量档位  
  
##### 解释说明

当你下市价单或限价单时，订单所需的资金将被冻结。这部分数量将不能被用于其他订单或者资金划转。资金将一直被冻结直至订单被成交或者取消。

##### 返回示例

    
    
    {
        "currency:BTC": {
            "available": "0",
            "balance": "0",
            "borrowed": "0",
            "can_withdraw": "0",
            "frozen": "0",
            "hold": "0",
            "holds": "0",
            "lending_fee": "0"
        },
        "currency:USDT": {
            "available": "0",
            "balance": "0",
            "borrowed": "0",
            "can_withdraw": "0",
            "frozen": "0",
            "hold": "0",
            "holds": "0",
            "lending_fee": "0"
        },
        "liquidation_price": "0",
        "maint_margin_ratio": "0.05",
        "margin_ratio": "",
        "risk_rate": "",
        "tiers": "1"
    }
    

### 单一币对账户信息

获取币币杠杆某币对账户的余额、冻结和可用等信息。

##### 限速规则：20次/2s

##### HTTP请求

`GET/api/margin/v3/accounts/<instrument_id>`

##### 签名请求示例

`2018-09-13T02:25:41.946ZGET/api/margin/v3/accounts/eos-usdt`

##### 请求参数

**参 数名** | **类 型** | **描 述**  
---|---|---  
instrument_id | String | [ 必填 ] 币对  
  
##### 返回参数

**参 数名** | **类 型** | **描 述**  
---|---|---  
balance | String | 余额  
currency | String | 该币对下的币种名称  
hold | String | 冻结（不可用）  
available | String | 可用于交易的数量  
risk_rate | String | 风险率  
can_withdraw | String | 可划转数量  
liquidation_price | String | 强平价  
borrowed | String | 已借币（已借未还的部分）  
lending_fee | String | 利息（未还的利息）  
margin_ratio | String | 保证金率  
maint_margin_ratio | String | 维持保证金率  
tiers | String | 当前借币数量档位  
  
##### 返回示例

    
    
    {
        "currency:BTC": {
            "available": "0",
            "balance": "0",
            "borrowed": "0",
            "can_withdraw": "0",
            "frozen": "0",
            "hold": "0",
            "holds": "0",
            "lending_fee": "0"
        },
        "currency:USDT": {
            "available": "0",
            "balance": "0",
            "borrowed": "0",
            "can_withdraw": "0",
            "frozen": "0",
            "hold": "0",
            "holds": "0",
            "lending_fee": "0"
        },
        "liquidation_price": "0",
        "maint_margin_ratio": "0.05",
        "margin_ratio": "",
        "risk_rate": "",
        "tiers": "1"
    }
    

### 账单流水查询

列出杠杆帐户资产流水。帐户资产流水是指导致帐户余额增加或减少的行为。流水会分页，并且按时间倒序排序和存储，最新的排在最前面。请参阅分页部分以获取第一页之后的其他纪录。
本接口能查询最近3个月的数据。

##### 限速规则：10次/2s

##### HTTP请求

`GET/api/margin/v3/accounts/<instrument_id>/ledger`

##### 签名请求示例

`2019-03-18T03:45:56.000ZGET/api/margin/v3/accounts/btc-
usdt/ledger?limit=10&type=1&after=2`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
instrument_id | String | 是 | 币对  
after | String | 否 | 请求此id之前（更旧的数据）的分页内容，传的值为对应接口的`ledger_id`  
before | String | 否 | 请求此id之后（更新的数据）的分页内容，传的值为对应接口的`ledger_id` |  
limit | String | 否 | 分页返回的结果集数量，最大为100，不填默认返回100条  
type | String | 否 | 3.借币 4.还币 5.计息 7.买入 8.卖出 9.资金账户转入 10.法币转入 11.交割合约转入
12.币币转入 13.组合转入 14.转出至资金账户 15.转出至法币 16.转出至币币 17.转出至交割合约 18.转出至组合 19.强制还息
20.余币宝转入 21.转出至余币宝 22.永续合约转入 23.转出至永续合约 24.强平费 25.转出至套保账户 26.套保账户转入 59.还糖果
60.套保费 61.币币杠杆账户转入 62.转出至币币杠杆账户 64.矿池账户转入 65.转出至矿池账户 66.转出至期权账户 67.期权账户转入  
  
##### 返回参数

**参 数名** | **类 型** | **描 述**  
---|---|---  
ledger_id | String | 账单ID  
instrument_id | String | 杠杆币对名称  
currency | String | 币种  
balance | String | 余额  
amount | String | 变动数量  
type | String | 流水来源  
timestamp | String | 账单创建时间  
details | String |
如果`type`是`trade`或者`fee`，则会有该`details`字段将包含`order`，`instrument`信息,如果`type`是`transfer`，则会有该`details`字段将包含`from`，`to`信息  
order_id | String | 交易的ID  
from | String | 转出账户  
`1`:币币账户  
`3`:交割合约  
`4`:法币账户  
`5`:币币杠杆账户  
`6`:资金账户  
`8`:余币宝账户  
`9`:永续合约账户  
`12`:期权合约  
`14`:挖矿账户  
`17`:借贷账户  
to | String | 转入账户  
`1`:币币账户  
`3`:交割合约  
`4`:法币账户  
`5`:币币杠杆账户  
`6`:资金账户  
`8`:余币宝账户  
`9`:永续合约账户  
`12`:期权合约  
`14`:挖矿账户  
`17`:借贷账户  
流水来源类型 | 描述  
---|---  
transfer | 资金转入/转出  
trade | 交易产生的资金变动  
rebate | 返佣  
  
##### 返回示例

    
    
    [
        [
            {
                "created_at":"2019-03-20T05:45:10.000Z",
                "ledger_id":"78965766",
                "timestamp":"2019-03-20T05:45:10.000Z",
                "currency":"EOS",
                "amount":"0",
                "balance":"0.59957711",
                "type":"transfer",
                "details":{
                    "instrument_id":"EOS-USDT",
                    "order_id":"787057",
                    "product_id":"EOS-USDT"
                }
            },
            {
                "created_at":"2019-03-20T04:45:07.000Z",
                "ledger_id":"78942699",
                "timestamp":"2019-03-20T04:45:07.000Z",
                "currency":"EOS",
                "amount":"0",
                "balance":"0.59957711",
                "type":"transfer",
                "details":{
                    "instrument_id":"EOS-USDT",
                    "order_id":"787057",
                    "product_id":"EOS-USDT"
                }
            },
            {
                "created_at":"2019-03-20T03:45:05.000Z",
                "ledger_id":"78918186",
                "timestamp":"2019-03-20T03:45:05.000Z",
                "currency":"EOS",
                "amount":"0",
                "balance":"0.59957711",
                "type":"transfer",
                "details":{
                    "instrument_id":"EOS-USDT",
                    "order_id":"787057",
                    "product_id":"EOS-USDT"
                }
            }
        ],
        {
            "OK-BEFORE":"78965766",
            "OK-AFTER":"78918186"
        }
    ]
    

### 杠杆配置信息

获取币币杠杆账户的借币配置信息，包括当前最大可借、借币利率、最大杠杆倍数。

##### 限速规则：20次/2s

##### HTTP请求

`GET/api/margin/v3/accounts/availability`

##### 签名请求示例

`2018-09-13T02:27:05.580ZGET/api/margin/v3/accounts/availability`

##### 返回参数

**参 数名** | **类 型** | **描 述**  
---|---|---  
instrument_id | String | 杠杆币对名称  
currency | String | 币种  
available | String | 当前最大可借  
rate | String | 借币利率  
leverage | String | 杠杆倍数  
  
##### 返回示例

    
    
    [
        {
            "currency:BTC":{
                "available":"0.09995502",
                "leverage":"5",
                "leverage_ratio":"5",
                "rate":"0.00009984"
            },
            "currency:USDT":{
                "available":"400.00000000",
                "leverage":"5",
                "leverage_ratio":"5",
                "rate":"0.00019992"
            },
            "instrument_id":"BTC-USDT",
            "product_id":"BTC-USDT"
        },
        {
            "currency:EOS":{
                "available":"1.9343",
                "leverage":"5",
                "leverage_ratio":"5",
                "rate":"0.00009984"
            },
            "currency:USDT":{
                "available":"7.1571",
                "leverage":"5",
                "leverage_ratio":"5",
                "rate":"0.00019992"
            },
            "instrument_id":"EOS-USDT",
            "product_id":"EOS-USDT"
        }
    ]
    

### 某个杠杆配置信息

获取某个币币杠杆账户的借币配置信息，包括当前最大可借、借币利率、最大杠杆倍数。

##### 限速规则：20次/2s

##### HTTP请求

`GET/api/margin/v3/accounts/<instrument_id>/availability`

##### 签名请求示例

`2019-03-18T02:27:37.723ZGET/api/margin/v3/accounts/BTC-USDT/availability`

##### 请求参数

**参 数名** | **类 型** | **描 述**  
---|---|---  
instrument_id | String | [ 必填 ] 币对  
  
##### 返回参数

**参 数名** | **类 型** | **描 述**  
---|---|---  
currency | String | 币种  
available | String | 当前最大可借  
rate | String | 借币利率  
leverage | String | 杠杆倍数  
instrument_id | String | 币对  
  
##### 返回示例

    
    
    [
        {
            "currency:BTC":{
                "available":"0.09989261",
                "leverage":"5",
                "leverage_ratio":"5",
                "rate":"0.00009984"
            },
            "currency:USDT":{
                "available":"400.00000000",
                "leverage":"5",
                "leverage_ratio":"5",
                "rate":"0.00019992"
            },
            "instrument_id":"BTC-USDT",
            "product_id":"BTC-USDT"
        }
    ]
    

### 获取借币记录

获取币币杠杆帐户的借币记录。这个请求支持分页，并且按时间倒序排序和存储，最新的排在最前面。请参阅分页部分以获取第一页之后的其他纪录。

##### 限速规则：20次/2s

##### HTTP请求

`GET/api/margin/v3/accounts/borrowed`

##### 签名请求示例

`2018-09-13T02:28:14.618ZGET/api/margin/v3/accounts/borrowed?status=0&limit=1&after=2`

##### 请求参数

**参 数名** | **类 型** | **描 述**  
---|---|---  
status | String | [ 非必填 ] 状态  
`0`：未还清  
`1`：已还清 不填默认返回`0`：未还清  
after | String | [ 非必填 ] 请求此id之前（更旧的数据）的分页内容，传的值为对应接口的`borrow_id`  
before | String | [ 非必填 ] 请求此id之后（更新的数据）的分页内容，传的值为对应接口的`borrow_id` |  
limit | String | [ 非必填 ] 分页返回的结果集数量，默认为`100`，最大为`100`（具体参见分页处的描述）  
  
##### 返回参数

**参 数名** | **类 型** | **描 述**  
---|---|---  
borrow_id | String | 借币记录ID  
instrument_id | String | 杠杆币对名称  
currency | String | 币种  
timestamp | String | 借币时间  
amount | String | 借币总数量  
interest | String | 利息总数量  
returned_amount | String | 已还借币数量  
paid_interest | String | 已还利息数量  
last_interest_time | String | 最后一次计息时间  
force_repay_time | String | 强制还息时间  
rate | String | 利率  
  
##### 返回示例

    
    
    [
            {
                "amount":"0.5",
                "borrow_id":"787057",
                "created_at":"2019-03-18T09:41:44.000Z",
                "currency":"EOS",
                "force_repay_time":"2019-03-25T09:42:19.000Z",
                "instrument_id":"EOS-USDT",
                "interest":"0.0000386883807232",
                "last_interest_time":"2019-03-20T05:45:11.000Z",
                "paid_interest":"0.00000208",
                "product_id":"EOS-USDT",
                "rate":"0.00000416",
                "repay_amount":"0.29999792",
                "repay_interest":"0.00000208",
                "returned_amount":"0.29999792",
                "timestamp":"2019-03-18T09:41:44.000Z"
            }
    ]
    

### 某币对借币记录

获取币币杠杆帐户某币对的借币记录。这个请求支持分页，并且按时间倒序排序和存储，最新的排在最前面。请参阅分页部分以获取第一页之后的其他纪录。

##### 限速规则：20次/2s

##### HTTP请求

`GET/api/margin/v3/accounts/<instrument_id>/borrowed`

##### 签名请求示例

`2018-09-13T02:29:06.610ZGET/api/margin/v3/accounts/BTC-
USDT/borrowed?limit=2&status=1&after=2`

##### 请求参数

**参 数名** | **类 型** | **描 述**  
---|---|---  
status | String | [ 非必填 ] 状态  
`0`：未还清  
`1`：已还清  
after | String | [ 非必填 ] 请求此id之前（更旧的数据）的分页内容（举例一列数：`1，2，3，4，5`。after `4`
只有`5`，to `4`有`1，2，3`）  
before | String | [ 非必填 ] 请求此id之后（更新的数据）的分页内容  
limit | String | [ 非必填 ] 分页返回的结果集数量，默认为`100`，最大为`100`（具体参见分页处的描述）  
instrument_id | String | [ 必填 ] 币对  
  
##### 返回参数

**参 数名** | **类 型** | **描 述**  
---|---|---  
borrow_id | String | 借币记录ID  
instrument_id | String | 杠杆币对名称  
currency | String | 币种  
timestamp | String | 借币时间  
amount | String | 借币总数量  
interest | String | 利息总数量  
returned_amount | String | 已还借币数量  
paid_interest | String | 已还利息数量  
last_interest_time | String | 最后一次计息时间  
force_repay_time | String | 强制还息时间  
rate | String | 利率  
  
##### 返回示例

    
    
    [
            {
                "amount":"0.5",
                "borrow_id":"787057",
                "created_at":"2019-03-18T09:41:44.000Z",
                "currency":"EOS",
                "force_repay_time":"2019-03-25T09:42:19.000Z",
                "instrument_id":"EOS-USDT",
                "interest":"0.0000386883807232",
                "last_interest_time":"2019-03-20T05:45:11.000Z",
                "paid_interest":"0.00000208",
                "product_id":"EOS-USDT",
                "rate":"0.00000416",
                "repay_amount":"0.29999792",
                "repay_interest":"0.00000208",
                "returned_amount":"0.29999792",
                "timestamp":"2019-03-18T09:41:44.000Z"
            }
    ]
    

### 借币

在某个币币杠杆账户里进行借币。

##### 限速规则：100次/2s

##### HTTP请求

`POST /api/margin/v3/accounts/borrow`

##### 签名请求示例

`2018-10-08T03:00:56.799ZPOST/api/margin/v3/accounts/borrow{"instrument_id":"ltc-
usdt","currency":"usdt","amount":"0.1"}`

##### 请求参数

**参 数名** | **类 型** | **是 否必须** | **描 述**  
---|---|---|---  
instrument_id | String | 是 | 杠杆币对名称  
client_oid | String | 否 | 由您设置的订单ID来识别您的订单  
currency | String | 是 | 币种  
amount | String | 是 | 借币数量  
  
##### 返回参数

**参 数名** | **类 型** | **描 述**  
---|---|---  
borrow_id | String | 借币记录ID  
client_oid | String | 由您设置的订单ID来识别您的订单  
result | Boolean | 结果  
  
##### 返回示例

    
    
    {
        "borrow_id":"791434",
        "client_oid":"",
        "result":true
    }
    

### 还币

在某个币币杠杆账户里进行还币。

##### 限速规则：100次/2s

##### HTTP请求

`POST /api/margin/v3/accounts/repayment`

##### 签名请求示例

`2018-10-08T03:04:52.002ZPOST/api/margin/v3/accounts/repayment{"instrument_id":"ltc-
usdt","currency":"usdt","amount":"0.1","borrow_id":"185759"}`

##### 请求参数

**参 数名** | **类 型** | **是 否必须** | **描 述**  
---|---|---|---  
borrow_id | String | 否 | 借币记录ID，不填时还整个币对的币  
client_oid | String | 否 | 由您设置的订单ID来识别您的订单  
instrument_id | String | 是 | 杠杆币对名称  
currency | String | 是 | 币种  
amount | String | 是 | 还币数量  
  
##### 返回参数

**参 数名** | **类 型** | **描 述**  
---|---|---  
repayment_id | String | 还币记录ID  
client_oid | String | 由您设置的订单ID来识别您的订单  
result | Boolean | 结果  
  
##### 返回示例

    
    
    {
        "client_oid":"",
        "repayment_id":"791434",
        "result":true
    }
    

### 下单

OKEx
API提供`limit`和`market`和高级限价委托等下单模式。只有当您的账户有足够的资金才能下单。一旦下单，您的账户资金将在订单生命周期内被冻结。被冻结的资金以及数量取决于订单指定的类型和参数。

##### 限速规则：100次/2s （不同币对之间限速不累计）

##### HTTP请求

`POST /api/margin/v3/orders`

##### 签名请求示例

`2018-09-12T07:46:47.098ZPOST/api/margin/v3/orders{"client_oid":"yt20180728","order_type":"0","instrument_id":"btc-
usdt","side":"buy","type":"market","size":"0.1","notional":"100","margin_trading":"2"}`

##### 请求参数

**参 数名** | **类 型** | **是 否必须** | **描 述**  
---|---|---|---  
client_oid | String | 否 | 由您设置的订单ID来识别您的订单 ，类型为字母（大小写）+数字或者纯字母（大小写），1-32位字符  
type | String | 否 | `limit` 或
`market`（默认是`limit`）。当以`market`（市价）下单，`order_type`只能选择`0`（普通委托）  
side | String | 是 | `buy` 或 `sell`  
instrument_id | String | 是 | 币对名称  
order_type | String | 否 | 参数填数字  
`0`：普通委托（order type不填或填0都是普通委托）  
`1`：只做Maker（Post only）  
`2`：全部成交或立即取消（FOK）  
`3`：立即成交并取消剩余（IOC）  
margin_trading | String | 是 | 下单类型（当前为币币杠杆交易，请求值为`2`）  
  
##### 限价单特殊参数

**参 数名** | **类 型** | **是 否必填** | **描 述**  
---|---|---|---  
price | String | 是 | 价格  
size | String | 是 | 买入或卖出的数量  
  
##### 市价单特殊参数

**参 数名** | **类 型** | **是 否必填** | **描 述**  
---|---|---|---  
size | String | 否 | 卖出数量，市价卖出必填`size`  
notional | String | 否 | 买入金额，市价买入时必填`notional`  
  
##### 返回参数

**参 数名** | **类 型** | **描 述**  
---|---|---  
order_id | String | 订单ID  
client_oid | String | 由您设置的订单ID来识别您的订单  
error_code | String | 错误码，下单成功时为0，下单失败时会显示相应错误码  
error_message | String | 错误信息，下单成功时为空，下单失败时会显示错误信息  
result | Boolean | 下单结果。若是下单失败，将给出错误码提示。  
  
##### 解释说明

`client_oid`的类型为字母+数字或者纯字母（大小写），1-32位字符
，用户需要自己保证此ID不重复，OKEx不会进行排重提示，如有重复，撤单和查询订单时只能撤销或者查询出最新的一条数据。

instrument_id

`instrument_id`必须是有效的币对。币对列表可通过/ instruments接口获取。

type

下单时，您可以指定订单类型。您指定的订单类型将决定是否需要其他订单参数以及撮合引擎如何执行您的订单。如果`type`没有指定，订单类型将默认为`limit`。限价单既是默认订单类型，也是基本订单类型。限价单需要指定`price`和`size`。`size`是买入或卖出交易货币的数量，`price`表示每个交易货币相对计价货币的价格。限价单会按指定价格或更好的价格成交。根据市场条件，卖单可以按照指定价格或者更高价格来成交，买单可以按照指定价格或更低价格成交。如果限价单不能立即成交，那么限价单将进入深度列表，直到被另一个新订单成交或被用户撤单。
市价单不同于限价单，因为它们不提供价格控制。市价单提供了一种不必指定价格，而以固定数量的货币进行买入或者卖出的方式。市价单下单后会立即撮合，而不会被挂入深度列表。市价单总是吃单方（taker）并承担taker费用。

price

`price`表示买入或卖出的价格。价格必须是价格步长`size_increment`的倍数。价格步长`size_increment`是价格的最小增量，可通过instruments接口获取。

size

`size`表示买入或卖出交易货币的数量。数量必须大于`min_size`。交易数量步长`size_increment`是数量的最小增量。上述参数都可通过instruments接口获取。

notional

`notional`表示被用于市价买入的计价货币的数量，市价买入时必填。例如，在`BTC-USDT`交易时，市价单指定5000 USDT表示将花费5000
USDT购买BTC。

hold

对于限价买单，系统将冻结计价货币的数量 = 限定价格 x
买入数量。对于限价卖单，系统将冻结你想卖出的交易货币的数量。对于市价买单，funds数量的计价货币将被冻结。对于市价卖单，`size`数量的交易货币将被冻结。如果您取消部分成交或未成交的订单，剩余资金将被解除冻结。

订单生命周期

HTTP请求将在订单被拒绝（资金不足，参数无效等）或下单成功（由匹配引擎接受）时作出响应。一个200响应表示该订单被接收并且进入撮合。进入撮合的订单可以部分或全部立即成交（取决于价格和市场条件）。部分成交的时候将把订单的剩余数量继续进行撮合。完全成交的订单将进入已成交状态。
监听行情数据的用户建议使用`client_oid`字段以便在接受到的信息中标识对应的数据。

响应

成功接受的订单将被分配一个订单ID。成功接受的订单表示撮合引擎已经接受的订单。 未成交的订单不会过期，并将保持撮合状态，直到被成交或取消。

##### 返回示例

    
    
    {
        "client_oid":"oktlever50",
        "error_message": "",
        "error_code": "0",
        "order_id":"2512084870235136",
        "result":true
    }
    

### 批量下单

下指定币对的多个订单（每次只能下最多4个币对且每个币对可批量下10个单）。

##### 限速规则：50次/2s （不同币对之间限速累计）

##### HTTP请求

`POST /api/margin/v3/batch_orders`

##### 签名请求示例

市价单：`POST
/api/margin/v3/batch_orders[{"client_oid":"t20180728","order_type":"1","instrument_id":"btc-
usdt","side":"sell","type":"market"," size ":"0.001"," notional
":"10001","margin_trading
":"2"},{"client_oid":"yy20180728","instrument_id":"btc-
usdt","side":"sell","type":"limit"," size
":"0.001","notional":"10002","margin_trading ":"2"}`

限价单：`POST
/api/margin/v3/batch_orders[{"client_oid":"y20180728","order_type":"1","instrument_id":"btc-
usdt","side":"sell","type":"limit","size":"0.001","price":"10001","margin_trading
":"2"},{"client_oid":"yt20180728","instrument_id":"btc-
usdt","side":"sell","type":"limit","size":"0.001","price":"10002","margin_trading
":"2"}`

##### 请求参数

**参 数名** | **类 型** | **是 否必填** | **描 述**  
---|---|---|---  
client_oid | String | 否 | 由您设置的订单ID来识别您的订单， 类型为字母（大小写）+数字或者纯字母（大小写）1-32位字符  
type | String | 否 | `limit` 或
`market`（默认是`limit`）。当以`market`（市价）下单，`order_type`只能选择`0`（普通委托）  
side | String | 是 | `buy` 或 `sell`  
instrument_id | String | 是 | 币对名称  
order_type | String | 否 | 参数填数字  
`0`：普通委托（`order_type`不填或填`0`都是普通委托）  
`1`：只做Maker（Post only）  
`2`：全部成交或立即取消（FOK）  
`3`：立即成交并取消剩余（IOC）  
margin_trading | String | 是 | 下单类型（当前为币币杠杆交易，请求值为`2`）  
  
##### 限价单特殊参数

**参 数名** | **类 型** | **是 否必填** | **描 述**  
---|---|---|---  
price | String | 是 | 价格  
size | String | 是 | 买入或卖出的数量  
  
##### 市价单特殊参数

**参 数名** | **类 型** | **是 否必填** | **描 述**  
---|---|---|---  
size | String | 否 | [ 非必填 ] 卖出数量，市价卖出必填`size`  
notional | String | 否 | [ 非必填 ] 买入金额，市价买入时必填`notional`  
  
##### 返回参数

**参 数名** | **类 型** | **描 述**  
---|---|---  
order_id | String | 订单ID  
client_oid | String | 由您设置的订单ID来识别您的订单  
error_code | String | 错误码，下单成功时为0，下单失败时会显示相应错误码  
error_message | String | 错误信息，下单成功时为空，下单失败时会显示错误信息  
result | Boolean | 下单结果。若是下单失败，将给出错误码提示。  
  
##### 解释说明

`client_oid`的类型为字母（大小写）+数字或者纯字母（大小写）1-32位字符
，用户需要自己保证此ID不重复，OKEx不会进行排重提示，如有重复，撤单和查询订单时只能撤销或者查询最新的一条数据。

每次最多4个币对且每个币对最多10个订单，建议用户调用批量撤单接口后，再调用获取订单列表接口确认已撤销成功。

##### 返回示例

    
    
    {
        "BTC-USDT":[
            {
                "client_oid":"oktlever51",
                "error_message": "",
                "error_code": "0",
                "order_id":"2512113685627904",
                "result":true
            },
            {
                "client_oid":"oktlever52",
                "error_message": "",
                "error_code": "0",
                "order_id":"2512113687135232",
                "result":true
            }
        ]
    }
    

### 撤销指定订单

撤销之前下的未完成订单。

##### 限速规则：100次/2s （不同币对之间限速不累计）

##### HTTP请求

`POST /api/margin/v3/cancel_orders/<order_id> or <client_oid>`

##### 签名请求示例

`2018-10-12T07:34:30.223ZPOST/api/margin/v3/cancel_orders/a123{"instrument_id":"btc-
usdt"}`

##### 请求参数

**参 数名** | **类 型** | **是 否必填** | **描 述**  
---|---|---|---  
instrument_id | String | 是 | 提供此参数则撤销指定币对的相应订单，如果不提供此参数则返回错误码  
client_oid | String | 非必填 | `order_id`和`client_oid`必须且只能选一个填写，由您设置的订单ID来识别您的订单
, 类型为字母（大小写）+数字或者纯字母（大小写）1-32位字符  
order_id | String | 非必填 | `order_id`和`client_oid`必须且只能选一个填写，订单ID  
  
##### 返回参数

**参 数名** | **类 型** | **描 述**  
---|---|---  
order_id | String | 订单ID  
client_oid | String | 由您设置的订单ID来识别您的订单  
error_code | String | 错误码，撤单成功时为0，撤单失败时会显示相应错误码  
error_message | String | 错误信息，撤单成功时为空，撤单失败时会显示错误信息  
result | Boolean | 撤单申请结果。若是撤单失败，将给出错误码提示  
  
##### 解释说明

`order_id`和`client_oid`必须且只能选一个填写

使用`client_oid`撤单时，用户需要自己保证此ID不重复，OKEx不会进行排重提示，如有重复，撤单时只能撤销最新的一条数据

如果订单无法取消（已经成交或已取消），那么返回的报错内容里将显示相应的原因。

##### 返回示例

    
    
    {
        "result":true,
        "client_oid":"a123",
        "order_id": "2510832677225473",
        "error_message": "",
        "error_code": "0"
    }
    

### 批量撤销订单

撤销指定的某一种或多种币对的所有未完成订单，每个币对可批量撤10个单。

##### 限速规则：50次/2s （不同币对之间限速累计）

##### HTTP请求

`POST /api/margin/v3/cancel_batch_orders`

##### 使用orderid撤单 签名请求示例

`2018-10-12T07:30:49.664ZPOST/api/margin/v3/cancel_batch_orders[{"instrument_id":"btc-
usdt","client_oids":["a123","a1234"]},{"instrument_id":"ltc-
usdt","client_oids":["a12345","a123456"]}]`

##### 请求参数

**参 数名** | **类 型** | **是 否必填** | **描 述**  
---|---|---|---  
instrument_id | String | 是 |
提供此参数则撤销指定一个或多个币对的订单，如果不提供此参数则返回错误码，此字段支持传多个值。此参数为`[''btc-usdt'',''ltc-
eth'']`，推荐使用中横线连接币种，下划线连接的方式也同时兼容  
order_ids | List<String> | 否 | `order_id`和`client_oid`必须且只能选一个填写，订单ID  
client_oids | List<String> | 否 |
`order_id`和`client_oid`必须且只能选一个填写，由您设置的订单ID来识别您的订单，类型为字母（大小写）+数字或者纯字母（大小写）1-32位字符  
  
##### 返回参数

**参 数名** | **类 型** | **描 述**  
---|---|---  
order_id | String | 订单ID  
client_oid | String | 由您设置的订单ID来识别您的订单  
instrument_id | String | 币种，如`btc-usdt`  
result | Boolean | 撤单申请结果。若是撤单失败，将给出错误码提示  
error_code | String | 错误码，撤单成功时为0，撤单失败时会显示相应错误码  
error_message | String | 错误信息，撤单成功时为空，撤单失败时会显示错误信息  
  
##### 解释说明

批量撤单一次性时候，要么都是`order_id`要么都是`client_oid`，否则会提示错误

使用`client_oid`批量撤单时，目前只支持一个币对下撤一个`client_oid`
，一次四个币对，用户需要自己保证此ID不重复，OKEx不会进行排重提示，如有重复，撤单时只能撤销最新的一条数据

使用`order_id`撤单时，每次最多4个币对且每个币对最多10个订单，建议用户调用批量撤单接口后，再调用获取订单列表接口确认已撤销成功。

##### 返回示例

    
    
    {
        "btc-usdt":[
        {
            "result":true,
            "client_oid":"a123",
            "order_id": "2510832677225473",
            "error_message": "",
            "error_code": "0"
         },
       {
           "result":true,
            "client_oid":"a1234",
            "order_id": "2510832677225474",
            "error_message": "",
            "error_code": "0"
         }
    ],
    "ltc-usdt":[
        {
           "result":true,
            "client_oid":"a12345",
            "order_id": "2510832677225475",
            "error_message": "",
            "error_code": "0"
         },
       {
           "result":true,
            "client_oid":"a123456",
            "order_id": "2510832677225476",
            "error_message": "",
            "error_code": "0"
         }
    ]
    }
    

### 获取订单列表

列出您当前所有的订单信息（本接口能查询最近3个月订单信息）。这个请求支持分页，并且按委托时间倒序排序和存储，最新的排在最前面。

##### 限速规则：10次/2s

##### HTTP请求

`GET/api/margin/v3/orders`

##### 签名请求示例

`2018-09-12T07:49:43.306ZGET/api/margin/v3/orders?instrument_id=BTC-
USDT&state=0&limit=2&after=2500723297223680`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
instrument_id | String | 是 | 币对名称  
state | String | 是 | 订单状态  
`-2`:失败  
`-1`:撤单成功  
`0`:等待成交  
`1`:部分成交  
`2`:完全成交  
`3`:下单中  
`4`:撤单中  
`6`: 未完成（等待成交+部分成交）  
`7`:已完成（撤单成功+完全成交）  
after | String | 否 | 请求此id之前（更旧的数据）的分页内容，传的值为对应接口的`order_id`  
before | String | 否 | 请求此id之后（更新的数据）的分页内容，传的值为对应接口的`order_id` |  
limit | String | 否 | 分页返回的结果集数量，最大为100，不填默认返回100条  
  
##### 返回参数

**参 数名** | **类 型** | **描 述**  
---|---|---  
order_id | String | 订单ID  
client_oid | String | 用户设置的订单ID  
price | String | 委托价格  
size | String | 委托数量（交易货币数量）  
notional | String | 买入金额，市价买入时返回  
instrument_id | String | 币对名称  
side | String | `buy` 或 `sell`  
type | String | `limit`或`market`（默认是`limit`）  
timestamp | String | 订单创建时间  
filled_size | String | 已成交数量  
filled_notional | String | 已成交金额  
order_type | String | `0`：普通委托  
`1`：只做Maker（Post only）  
`2`：全部成交或立即取消（FOK）  
`3`：立即成交并取消剩余（IOC）  
state | String | 订单状态  
`-2`：失败  
`-1`：撤单成功  
`0`：等待成交  
`1`：部分成交  
`2`：完全成交  
`3`：下单中  
`4`：撤单中  
price_avg | String | 成交均价  
  
##### 解释说明

`client_oid`的类型为字母（大小写）+数字或者纯字母（大小写），1-32位字符
，用户需要自己保证此ID不重复，OKEx不会进行排重提示，如有重复，查询订单时只能查询出最新的一条数据。

最新的定义为 先从未成交表查，如果未成交表没有，再查已成交表的最新数据。

如果订单在其生命周期内没有任何成交，其记录可能被清除。这表示订单详细信息将不可用本接口来获取。

未成交的订单可能会根据市场情况在你发起请求和服务器响应之间改变状态。

##### 返回示例

    
    
    [
            {
                "client_oid":"oktlever56",
                "created_at":"2019-03-20T08:21:49.000Z",
                "filled_notional":"0",
                "filled_size":"0",
                "funds":"",
                "instrument_id":"BTC-USDT",
                "notional":"",
                "order_id":"2512264176206848",
                "order_type":"0",
                "price":"3613.3",
                "price_avg": "3613.3",
                "product_id":"BTC-USDT",
                "side":"buy",
                "size":"0.001",
                "status":"open",
                "state":"0",
                "timestamp":"2019-03-20T08:21:49.000Z",
                "type":"limit"
            },
            {
                "client_oid":"oktlever55",
                "created_at":"2019-03-20T08:21:49.000Z",
                "filled_notional":"0",
                "filled_size":"0",
                "funds":"",
                "instrument_id":"BTC-USDT",
                "notional":"",
                "order_id":"2512264174306304",
                "order_type":"0",
                "price":"3613.3",
                "price_avg": "3613.3",
                "product_id":"BTC-USDT",
                "side":"buy",
                "size":"0.001",
                "status":"open",
                "state":"0",
                "timestamp":"2019-03-20T08:21:49.000Z",
                "type":"limit"
            }
    ]
    

### 获取订单信息

通过订单ID获取单个订单信息。已撤销的未成交单只保留2个小时。

##### 限速规则：20次/2s

##### HTTP请求

`GET/api/margin/v3/orders/<order_id>`

或者

`GET/api/margin/v3/orders/<client_oid>`

##### 签名请求示例

`2018-09-13T02:39:22.475ZGET/api/margin/v3/orders/23458?instrument_id=btc-
usdt`

或

`2018-09-13T02:39:22.475ZGET/api/margin/v3/orders/etyery8?instrument_id=btc-
usdt`

##### 请求参数

**参 数名** | **类 型** | **描 述**  
---|---|---  
instrument_id | String | [ 必填 ] 币对  
order_id | String | [非必填 ] 订单ID `order_id`和`client_oid`必须且只能选一个填写  
client_oid | String | [非必填 ] `order_id`和`client_oid`必须且只能选一个填写
由您设置的订单ID来识别您的订单 ， 类型为字母（大小写）+数字或者纯字母（大小写）1-32位字符  
  
##### 返回参数

**参 数名** | **类 型** | **描 述**  
---|---|---  
order_id | String | 订单ID  
client_oid | String | 由您设置的订单ID来识别您的订单  
price | String | 委托价格  
size | String | 委托数量（交易货币数量）  
notional | String | 买入金额，市价买入时返回  
instrument_id | String | 币对名称  
side | String | `buy` 或 `sell`  
type | String | `limit`或`market`（默认是`limit`）  
timestamp | String | 订单创建时间  
filled_size | String | 已成交数量  
filled_notional | String | 已成交金额  
order_type | String | `0`：普通委托  
`1`：只做Maker（Post only）  
`2`：全部成交或立即取消（FOK）  
`3`：立即成交并取消剩余（IOC）  
state | String | `-2`:失败  
`-1`:撤单成功  
`0`:等待成交  
`1`:部分成交  
`2`:完全成交  
`3`:下单中  
`4`:撤单中  
price_avg | String | 成交均价  
  
##### 解释说明

`status`为`state`旧版参数，会短期兼容，建议尽早切换`state`。

`order_id`和`client_oid`必须且只能选一个填写

`client_oid`的类型为字母（大小写）+数字或者纯字母（大小写），1-32位字符
，用户需要自己保证此ID不重复，OKEx不会进行排重提示，如有重复，查询订单时只能查询出最新的一条数据。

最新的定义为 先从未成交表查，如果未成交表没有，再查已成交表的最新数据。

如果订单在其生命周期内没有任何成交，其记录可能被清除，则响应可能因为没有相应的匹配而返回状态码404。

未成交的订单可能会根据市场情况在你发起请求和服务器响应之间改变状态。

##### 返回示例

    
    
    {
        "client_oid":"",
        "created_at":"2019-03-18T03:45:55.000Z",
        "filled_notional":"1.504",
        "filled_size":"0.4",
        "funds":"",
        "instrument_id":"EOS-USDT",
        "notional":"",
        "order_id":"2499854635054080",
        "order_type":"0",
        "price":"3.76",
        "price_avg":"3.76",
        "product_id":"EOS-USDT",
        "side":"buy",
        "size":"0.4",
        "status":"filled",
        "state": "0",    
        "timestamp":"2019-03-18T03:45:55.000Z",
        "type":"limit"
    }
    

### 获取所有未成交订单

列出您当前所有的订单信息。这个请求支持分页，并且按时间倒序排序和存储，最新的排在最前面。请参阅分页部分以获取第一页之后的其他纪录。

##### 限速规则：20次/2s

##### HTTP请求

`GET/api/margin/v3/orders_pending`

##### 签名请求示例

`2019-03-20T07:51:51.138ZGET/api/margin/v3/orders_pending?limit=2&instrument_id=BTC-
USDT&after=2500723297223680`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
instrument_id | String | 是 | 币对名称  
after | String | 否 | 请求此id之前（更旧的数据）的分页内容，传的值为对应接口的`order_id`  
before | String | 否 | 请求此id之后（更新的数据）的分页内容，传的值为对应接口的`order_id`等 |  
limit | String | 否 | 分页返回的结果集数量，最大为100，不填默认返回100条  
  
##### 返回参数

**参 数名** | **类 型** | **描 述**  
---|---|---  
order_id | String | 订单ID  
client_oid | String | 用户设置的订单ID  
price | String | 委托价格  
size | String | 委托数量（交易货币数量）  
notional | String | 买入金额，市价买入时返回  
instrument_id | String | 币对名称  
order_type | String | `0`：普通委托  
`1`：只做Maker（Post only）  
`2`：全部成交或立即取消（FOK）  
`3`：立即成交并取消剩余（IOC）  
side | String | `buy` 或 `sell`  
type | String | `limit`或`market`（默认是`limit`）  
timestamp | String | 订单创建时间  
filled_size | String | 已成交数量  
filled_notional | String | 已成交金额  
state | String | 订单状态  
`0`:等待成交  
  
##### 解释说明

`status`为`state`旧版参数，会短期兼容，建议尽早切换`state`。

`client_oid`的类型为字母（大小写）+数字或者纯字母（大小写）1-32位字符
，用户需要自己保证此ID不重复，OKEx不会进行排重提示，如有重复，查询订单时只能查询出最新的一条数据。

本接口只能查询所有未成交或者部分成交的订单

未成交的订单可能会根据市场情况在你发起请求和服务器响应之间改变状态。

##### 返回示例

    
    
    [
            {
                "client_oid":"oktlever56",
                "created_at":"2019-03-20T08:21:49.000Z",
                "filled_notional":"0",
                "filled_size":"0",
                "funds":"",
                "instrument_id":"BTC-USDT",
                "notional":"",
                "order_id":"2512264176206848",
                "order_type":"0",
                "price":"3613.3",
                "price_avg":"",
                "product_id":"BTC-USDT",
                "side":"buy",
                "size":"0.001",
                "status":"open",
                "state":"0",
                "timestamp":"2019-03-20T08:21:49.000Z",
                "type":"limit"
            },
            {
                "client_oid":"oktlever55",
                "created_at":"2019-03-20T08:21:49.000Z",
                "filled_notional":"0",
                "filled_size":"0",
                "funds":"",
                "instrument_id":"BTC-USDT",
                "notional":"",
                "order_id":"2512264174306304",
                "order_type":"0",
                "price":"3613.3",
                "price_avg":"",
                "product_id":"BTC-USDT",
                "side":"buy",
                "size":"0.001",
                "status":"open",
                "state":"0",
                "timestamp":"2019-03-20T08:21:49.000Z",
                "type":"limit"
            }
    ]
    

### 获取成交明细

获取最近的成交明细列表。这个请求支持分页，并且按时间倒序排序和存储，最新的排在最前面。请参阅分页部分以获取第一页之后的其他纪录。
本接口能查询最近3月的数据。

##### 限速规则：10次/2s

##### HTTP请求

`GET/api/margin/v3/fills`

##### 签名请求示例

`2018-09-13T02:44:54.823ZGET/api/margin/v3/fills?order_id=23239&instrument_id=btc-
usdt&limit=1&after=2`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
order_id | String | 否 | 订单ID，不填写`order_id`，返回当前`instrument_id`下的所有订单成交明细  
instrument_id | String | 是 | 币对名称  
after | String | 否 | 请求此id之前（更旧的数据）的分页内容，传的值为对应接口的`ledger_id`  
before | String | 否 | 请求此id之后（更新的数据）的分页内容，传的值为对应接口的`ledger_id` |  
limit | String | 否 | 分页返回的结果集数量，最大为100，不填默认返回100条  
  
##### 返回参数

**参 数名** | **类 型** | **描 述**  
---|---|---  
ledger_id | String | 账单ID  
instrument_id | String | 币对名称  
price | String | 价格  
size | String | 数量  
order_id | String | 订单ID  
timestamp | String | 订单成交时间  
exec_type | String | 流动性方向（`T` 或 `M`）  
fee | String | 手续费  
side | String | 订单方向（`buy` 或 `sell`）  
currency | String | 币种  
  
##### 解释说明

此接口一笔成交会返回2条数据，一个以计价货币计算的，一个是以交易货币计算的。

手续费

`fee`字段表示这条账单记录所收取的手续费。

流动性

`exec_type`字段表示该账单是maker还是taker产生的。`M`表示Maker，`T`表示Taker。

分页

返回账单列表的`ledger_id`按降序排列，从最大`ledger_id`到最小`ledger_id`。`OK-
AFTER`都会有这样的第一笔`ledger_id`，以便将来的请求使用`OK-after`参数将获取一个更大的`ledger_id`（新的账单）。

##### 返回示例

    
    
    [
        {
            "created_at": "2019-11-25T07:45:05.000Z",
            "currency": "USDT",
            "exec_type": "M",
            "fee": "-0.01915417",
            "instrument_id": "OKB-USDT",
            "ledger_id": "8161858573",
            "liquidity": "M",
            "order_id": "3927696997697536",
            "price": "1.7793",
            "product_id": "OKB-USDT",
            "side": "buy",
            "size": "19.1541645",
            "timestamp": "2019-11-25T07:45:05.000Z"
        },
        {
            "created_at": "2019-11-25T07:45:05.000Z",
            "currency": "OKB",
            "exec_type": "M",
            "fee": "0",
            "instrument_id": "OKB-USDT",
            "ledger_id": "8161858572",
            "liquidity": "M",
            "order_id": "3927696997697536",
            "price": "1.7793",
            "product_id": "OKB-USDT",
            "side": "sell",
            "size": "10.765",
            "timestamp": "2019-11-25T07:45:05.000Z"
        }
    ]
    

### 获取杠杆倍数

获取币币杠杆账户币种杠杆倍数

##### 限速规则：5次/2s

##### HTTP请求

`GET/api/margin/v3/accounts/<instrument_id>/leverage`

##### 请求示例

`GET/api/margin/v3/accounts/btc-usdt/leverage`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
instrument_id | String | 是 | 币对名称，如：BTC-USDT  
  
##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
instrument_id | String | 币对名称，如：BTC-USDT  
leverage | String | 杠杆倍数  
error_code | String | 错误码  
error_message | String | 错误信息  
result | Boolean | 请求结果  
  
##### 返回示例

    
    
    {
        "error_code": "",
        "error_message": "",
        "instrument_id": "btc-usdt",
        "leverage": "3",
        "result": true
    }
    

### 设置杠杆倍数

设置币币杠杆账户币对杠杆倍数。

##### 限速规则：5次/2s

##### HTTP请求

`POST /api/margin/v3/accounts/<instrument_id>/leverage`

##### 请求示例

`POST /api/margin/v3/accounts/BTC-USDT/leverage{"leverage":"10"}`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
leverage | String | 是 | 要设定的杠杆倍数，填写`2-10`的数值  
instrument_id | String | 是 | 币对，如：`BTC-USDT`,`LTC-USDT`  
  
##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
leverage | String | 已设定的杠杆倍数，`2-10`的数值  
instrument_id | String | 币对，如：BTC-USDT  
error_code | String | 错误码  
error_message | String | 错误信息  
result | Boolean | 请求结果  
  
##### 返回示例

    
    
    {
        "error_code": "",
        "error_message": "",
        "instrument_id": "BTC-USDT",
        "leverage": "7",
        "result": true
    }
    

### 公共-币币杠杆行情

要实时更新市场数据，请参阅WebSocket文档，以便获取并创建更完整的深度和交易数据。

币币杠杆交易和币币交易共享行情和深度数据，请移步币币行情查看接口。

### 公共-获取标记价格

获取现货杠杆标记价格。此接口为公共接口，不需要身份验证。

##### 限速规则：20次/2s

##### HTTP请求

`GET/api/margin/v3/instruments/<instrument_id>/mark_price`

##### 请求示例

`GET/api/margin/v3/instruments/EOS-USDT/mark_price`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
instrument_id | String | 是 | 杠杆币对名称  
  
##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
instrument_id | String | 杠杆币对名称  
mark_price | String | 指定杠杆的标记价格  
timestamp | String | 返回请求时间  
  
##### 返回示例

    
    
    {
        "mark_price":"3.591",
        "instrument_id":"EOS-USDT",
        "timestamp":"2019-06-22T06:28:53.208Z"
    }
    

### 交割合约API

交割合约交易的行情信息，账户信息，订单操作，订单查询，账单明细查询。

### 所有合约持仓信息

获取账户所有合约的持仓信息。请求此接口，会在数据库遍历所有币对下的持仓数据，有大量的性能消耗,请求频率较低。建议用户传合约ID获取持仓信息。

##### 限速规则：5次/2s （根据UserID限速）

##### HTTP请求

`GET/api/futures/v3/position`

##### 请求示例

`GET/api/futures/v3/position`

##### 返回参数

###### 全仓

全仓参数名 | 参数类型 | 描述  
---|---|---  
margin_mode | String | 账户类型  
全仓：`crossed`  
liquidation_price | String | 预估强平价  
long_qty | String | 多仓数量  
long_avail_qty | String | 多仓可平仓数量  
long_avg_cost | String | 开仓平均价  
long_settlement_price | String | 多仓结算基准价  
realised_pnl | String | 已实现盈余  
short_qty | String | 空仓数量  
short_avail_qty | String | 空仓可平仓数量  
short_avg_cost | String | 开仓平均价  
short_settlement_price | String | 空仓结算基准价  
instrument_id | String | 合约ID，如`BTC-USD-180213`  
leverage | String | 杠杆倍数  
created_at | String | 创建时间  
updated_at | String | 最近一次加减仓的更新时间  
short_margin | String | 空仓保证金  
short_pnl | String | 空仓收益  
short_pnl_ratio | String | 空仓收益率  
short_unrealised_pnl | String | 空仓未实现盈亏  
short_settled_pnl | String | 空仓已结算收益  
long_margin | String | 多仓保证金  
long_pnl | String | 多仓收益  
long_pnl_ratio | String | 多仓收益率  
long_unrealised_pnl | String | 多仓未实现盈亏  
long_settled_pnl | String | 多仓已结算收益  
last | String | 最新成交价  
  
###### 逐仓

逐仓参数名 | 参数类型 | 描述  
---|---|---  
margin_mode | String | 账户类型  
逐仓：`fixed`  
long_qty | String | 多仓数量  
long_avail_qty | String | 多仓可平仓数量  
long_margin | String | 多仓保证金  
long_liqui_price | String | 多仓强平价格  
long_pnl_ratio | String | 多仓收益率  
long_avg_cost | String | 开仓平均价  
long_settlement_price | String | 多仓结算基准价  
realised_pnl | String | 已实现盈余  
long_leverage | String | 多仓杠杆倍数  
short_qty | String | 空仓数量  
short_avail_qty | String | 空仓可平仓数量  
short_margin | String | 空仓保证金  
short_liqui_price | String | 空仓强平价格  
short_pnl_ratio | String | 空仓收益率  
short_avg_cost | String | 开仓平均价  
short_settlement_price | String | 空仓结算基准价  
short_leverage | String | 空仓杠杆倍数  
instrument_id | String | 合约ID，如`BTC-USD-180213`  
created_at | String | 创建时间  
updated_at | String | 最近一次加减仓的更新时间  
short_margin_ratio | String | 空仓保证金率  
short_maint_margin_ratio | String | 空仓维持保证金率  
short_pnl | String | 空仓收益  
short_unrealised_pnl | String | 空仓未实现盈亏  
long_margin_ratio | String | 多仓保证金率  
long_maint_margin_ratio | String | 多仓维持保证金率  
long_pnl | String | 多仓收益  
long_unrealised_pnl | String | 多仓未实现盈亏  
long_settled_pnl | String | 多仓已结算收益  
short_settled_pnl | String | 空仓已结算收益  
last | String | 最新成交价  
  
##### 返回示例

###### 全仓

    
    
    {
        "result": true,
        "holding": [
            [
                {
                    "long_qty": "0",
                    "long_avail_qty": "0",
                    "long_avg_cost": "0",
                    "long_settlement_price": "0",
                    "realised_pnl": "-0.0001318",
                    "short_qty": "0",
                    "short_avail_qty": "0",
                    "short_avg_cost": "8181.88",
                    "short_settlement_price": "8181.88",
                    "liquidation_price": "113.81",
                    "instrument_id": "BTC-USD-191018",
                    "leverage": "10",
                    "created_at": "2019-10-08T11:56:07.922Z",
                    "updated_at": "2019-10-08T14:02:06.861Z",
                    "margin_mode": "crossed",
                    "short_margin": "0.0",
                    "short_pnl": "0.0",
                    "short_pnl_ratio": "-0.027818392",
                    "short_unrealised_pnl": "0.0",
                    "long_margin": "0.0",
                    "long_pnl": "0.0",
                    "long_pnl_ratio": "0.0",
                    "long_unrealised_pnl": "0.0",
                    "long_settled_pnl": "0",
                    "short_settled_pnl": "0",
                    "last": "8202.92"
                },
                {
                    "long_qty": "2",
                    "long_avail_qty": "2",
                    "long_avg_cost": "8260",
                    "long_settlement_price": "8260",
                    "realised_pnl": "0.00020928",
                    "short_qty": "2",
                    "short_avail_qty": "2",
                    "short_avg_cost": "8259.99",
                    "short_settlement_price": "8259.99",
                    "liquidation_price": "113.81",
                    "instrument_id": "BTC-USD-191227",
                    "leverage": "10",
                    "created_at": "2019-09-25T07:58:42.129Z",
                    "updated_at": "2019-10-08T14:02:51.029Z",
                    "margin_mode": "crossed",
                    "short_margin": "0.002422",
                    "short_pnl": "6.9E-6",
                    "short_pnl_ratio": "0.002477997",
                    "short_unrealised_pnl": "6.9E-6",
                    "long_margin": "0.002422",
                    "long_pnl": "-6.92E-6",
                    "long_pnl_ratio": "-0.002478",
                    "long_unrealised_pnl": "-6.92E-6",
                    "long_settled_pnl": "0",
                    "short_settled_pnl": "0",
                    "last": "8257.65"
                }
            ]
        ]
    }
    

###### 逐仓

    
    
    {
        "result": true,
        "holding": [
            [
                {
                    "long_qty": "0",
                    "long_avail_qty": "0",
                    "long_margin": "0",
                    "long_liqui_price": "0",
                    "long_pnl_ratio": "0",
                    "long_avg_cost": "0",
                    "long_settlement_price": "0",
                    "realised_pnl": "-0.00001222",
                    "short_qty": "2",
                    "short_avail_qty": "2",
                    "short_margin": "0.00244443",
                    "short_liqui_price": "9040.9",
                    "short_pnl_ratio": "-0.06463685",
                    "short_avg_cost": "8181.88",
                    "short_settlement_price": "8181.88",
                    "instrument_id": "BTC-USD-191018",
                    "long_leverage": "0",
                    "short_leverage": "10",
                    "created_at": "2019-10-08T11:56:07.922Z",
                    "updated_at": "2019-10-08T11:56:08.002Z",
                    "margin_mode": "fixed",
                    "short_margin_ratio": "0.09410211",
                    "short_maint_margin_ratio": "0.005",
                    "short_pnl": "-1.5915E-4",
                    "short_unrealised_pnl": "-1.5915E-4",
                    "long_margin_ratio": "10000.0",
                    "long_maint_margin_ratio": "0.005",
                    "long_pnl": "0.0",
                    "long_unrealised_pnl": "0.0",
                    "long_settled_pnl": "0",
                    "short_settled_pnl": "0",
                    "last": "8237.72"
                },
                {
                    "long_qty": "4",
                    "long_avail_qty": "4",
                    "long_margin": "0.00323844",
                    "long_liqui_price": "7762.09",
                    "long_pnl_ratio": "0.10622415",
                    "long_avg_cost": "8234.43",
                    "long_settlement_price": "8234.43",
                    "realised_pnl": "-0.00000296",
                    "short_qty": "2",
                    "short_avail_qty": "2",
                    "short_margin": "0.00241105",
                    "short_liqui_price": "9166.74",
                    "short_pnl_ratio": "0.00248854",
                    "short_avg_cost": "8295.13",
                    "short_settlement_price": "8295.13",
                    "instrument_id": "BTC-USD-191227",
                    "long_leverage": "15",
                    "short_leverage": "10",
                    "created_at": "2019-09-25T07:58:42.129Z",
                    "updated_at": "2019-10-08T13:12:09.438Z",
                    "margin_mode": "fixed",
                    "short_margin_ratio": "0.1002126",
                    "short_maint_margin_ratio": "0.005",
                    "short_pnl": "5.7E-6",
                    "short_unrealised_pnl": "5.7E-6",
                    "long_margin_ratio": "0.07427591",
                    "long_maint_margin_ratio": "0.005",
                    "long_pnl": "3.4407E-4",
                    "long_unrealised_pnl": "3.4407E-4",
                    "long_settled_pnl": "0",
                    "short_settled_pnl": "0",
                    "last": "8294.07"
                }
            ]
        ]
    }
    

### 单个合约持仓信息

获取某个合约的持仓信息。

##### 限速规则：20次/2s （根据underlying，分别限速）

##### HTTP请求

`GET/api/futures/v3/<instrument_id>/position`

##### 请求示例

`GET/api/futures/v3/BTC-USD-180309/position`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
instrument_id | String | 是 | 合约ID，如`BTC-USD-180213`,`BTC-USDT-191227`  
  
##### 返回参数

###### 全仓

全仓参数名 | 参数类型 | 描述  
---|---|---  
margin_mode | String | 账户类型  
全仓：`crossed`  
liquidation_price | String | 预估强平价  
long_qty | String | 多仓数量  
long_avail_qty | String | 多仓可平仓数量  
long_avg_cost | String | 开仓平均价  
long_settlement_price | String | 结算基准价  
realised_pnl | String | 已实现盈余  
leverage | String | 杠杆倍数  
short_qty | String | 空仓数量  
short_avail_qty | String | 空仓可平仓数量  
short_avg_cost | String | 开仓平均价  
short_settlement_price | String | 结算基准价  
instrument_id | String | 合约ID，如`BTC-USD-180213`,`BTC-USDT-191227`  
created_at | String | 创建时间  
updated_at | String | 最近一次加减仓的更新时间  
short_margin | String | 空仓保证金  
short_pnl | String | 空仓收益  
short_pnl_ratio | String | 空仓收益率  
short_unrealised_pnl | String | 空仓未实现盈亏  
short_settled_pnl | String | 空仓已结算收益  
long_margin | String | 多仓保证金  
long_pnl | String | 多仓收益  
long_pnl_ratio | String | 多仓收益率  
long_unrealised_pnl | String | 多仓未实现盈亏  
long_settled_pnl | String | 多仓已结算收益  
last | String | 最新成交价  
  
###### 逐仓

逐仓参数名 | 参数类型 | 描述  
---|---|---  
margin_mode | String | 账户类型  
逐仓：`fixed`  
long_qty | String | 多仓数量  
long_avail_qty | String | 多仓可平仓数量  
long_margin | String | 多仓保证金  
long_liqui_price | String | 多仓强平价格  
long_pnl_ratio | String | 多仓盈亏比  
long_avg_cost | String | 开仓平均价  
long_settlement_price | String | 结算基准价  
realised_pnl | String | 已实现盈余  
long_leverage | String | 多仓杠杆倍数  
short_qty | String | 空仓数量  
short_avail_qty | String | 空仓可平仓数量  
short_margin | String | 空仓保证金  
short_liqui_price | String | 空仓强平价格  
short_pnl_ratio | String | 空仓盈亏比  
short_avg_cost | String | 开仓平均价  
short_settlement_price | String | 结算基准价  
short_leverage | String | 空仓杠杆倍数  
instrument_id | String | 合约ID，如`BTC-USD-180213`,`BTC-USDT-191227`  
created_at | String | 创建时间  
updated_at | String | 最近一次加减仓的更新时间  
short_margin_ratio | String | 空仓保证金率  
short_maint_margin_ratio | String | 空仓维持保证金率  
short_pnl | String | 空仓收益  
short_unrealised_pnl | String | 空仓未实现盈亏  
short_settled_pnl | String | 空仓已结算收益  
long_margin_ratio | String | 多仓保证金率  
long_maint_margin_ratio | String | 多仓维持保证金率  
long_pnl | String | 多仓收益  
long_unrealised_pnl | String | 多仓未实现盈亏  
long_settled_pnl | String | 多仓已结算收益  
last | String | 最新成交价  
  
##### 返回示例

###### 全仓

    
    
    {
        "result": true,
        "holding": [
            {
                "long_qty": "2",
                "long_avail_qty": "2",
                "long_avg_cost": "8260",
                "long_settlement_price": "8260",
                "realised_pnl": "0.00020928",
                "short_qty": "2",
                "short_avail_qty": "2",
                "short_avg_cost": "8259.99",
                "short_settlement_price": "8259.99",
                "liquidation_price": "113.81",
                "instrument_id": "BTC-USD-191227",
                "leverage": "10",
                "created_at": "2019-09-25T07:58:42.129Z",
                "updated_at": "2019-10-08T14:02:51.029Z",
                "margin_mode": "crossed",
                "short_margin": "0.00242197",
                "short_pnl": "6.63E-6",
                "short_pnl_ratio": "0.002477997",
                "short_unrealised_pnl": "6.63E-6",
                "long_margin": "0.00242197",
                "long_pnl": "-6.65E-6",
                "long_pnl_ratio": "-0.002478",
                "long_unrealised_pnl": "-6.65E-6",
                "long_settled_pnl": "0",
                "short_settled_pnl": "0",
                "last": "8257.57"
            }
        ],
        "margin_mode": "crossed"
    }
    

###### 逐仓

    
    
    {
        "result": true,
        "holding": [
            {
                "long_qty": "4",
                "long_avail_qty": "4",
                "long_margin": "0.00323844",
                "long_liqui_price": "7762.09",
                "long_pnl_ratio": "0.06052306",
                "long_avg_cost": "8234.43",
                "long_settlement_price": "8234.43",
                "realised_pnl": "-0.00000296",
                "short_qty": "2",
                "short_avail_qty": "2",
                "short_margin": "0.00241105",
                "short_liqui_price": "9166.74",
                "short_pnl_ratio": "0.03318052",
                "short_avg_cost": "8295.13",
                "short_settlement_price": "8295.13",
                "instrument_id": "BTC-USD-191227",
                "long_leverage": "15",
                "short_leverage": "10",
                "created_at": "2019-09-25T07:58:42.129Z",
                "updated_at": "2019-10-08T13:12:09.438Z",
                "margin_mode": "fixed",
                "short_margin_ratio": "0.10292507",
                "short_maint_margin_ratio": "0.005",
                "short_pnl": "7.853E-5",
                "short_unrealised_pnl": "7.853E-5",
                "long_margin_ratio": "0.07103743",
                "long_maint_margin_ratio": "0.005",
                "long_pnl": "1.9841E-4",
                "long_unrealised_pnl": "1.9841E-4",
                "long_settled_pnl": "0",
                "short_settled_pnl": "0",
                "last": "8266.99"
            }
        ],
        "margin_mode": "fixed"
    }
    

### 所有币种合约账户信息

获取合约账户所有币种的账户信息。请求此接口，会在数据库遍历所有币对下的账户数据，有大量的性能消耗,请求频率较低。建议用户传币种获取账户信息信息。

##### 限速规则：1次/10s （根据UserID限速）

##### HTTP请求

`GET/api/futures/v3/accounts`

##### 请求示例

`GET/api/futures/v3/accounts`

##### 返回参数

###### 全仓

全仓参数名 | 参数类型 | 描述  
---|---|---  
currency | String | 账户余额币种  
margin_mode | String | 账户类型  
全仓：`crossed`  
equity | String | 账户权益  
total_avail_balance | String | 账户余额  
margin | String | 保证金（挂单冻结+持仓已用）  
margin_frozen | String | 持仓已用保证金  
margin_for_unfilled | String | 挂单冻结保证金  
realized_pnl | String | 已实现盈亏  
unrealized_pnl | String | 未实现盈亏  
margin_ratio | String | 保证金率  
maint_margin_ratio | String | 维持保证金率  
liqui_mode | string | 强平模式：`tier`（梯度强平）  
can_withdraw | string | 可划转数量  
liqui_fee_rate | string | 强平手续费  
underlying | string | 标的指数，如：BTC-USD，BTC-USDT  
  
###### 逐仓

逐仓参数名 | 参数类型 | 描述  
---|---|---  
currency | String | 账户余额币种  
margin_mode | String | 账户类型  
逐仓：`fixed`  
fixed_balance | String | 逐仓账户余额  
available_qty | String | 逐仓可用余额  
margin_frozen | String | 持仓已用保证金  
margin_for_unfilled | String | 挂单冻结保证金  
instrument_id | String | 合约ID，如`BTC-USD-180213`，`BTC-USDT-191227`  
realized_pnl | String | 已实现盈亏  
unrealized_pnl | String | 未实现盈亏  
equity | String | 账户权益（账户动态权益）  
total_avail_balance | String | 账户余额（账户静态权益）  
auto_margin | String | 是否自动追加保证金  
`1`: 自动追加已开启  
`0`: 自动追加未开启  
liqui_mode | string | 强平模式：`tier`（梯度强平）  
can_withdraw | string | 可划转数量  
  
##### 解释说明

所有持仓/所有账户信息，没有持仓/持币时返回空数组；单个持仓/单个账户信息没有持仓/持币时返回各字段均为默认值；

逐仓：

1.账户权益：账户权益=账户余额+逐仓仓位账户余额+所有合约的已实现盈亏+所有合约的未实现盈亏

2.可用：可用余额=账户余额+逐仓仓位账户余额+本合约已实现盈亏\- 当前仓位的持仓所需保证金 \- 挂单冻结保证金

全仓：

1.账户权益=账户余额+所有合约的已实现盈亏+所有合约的未实现盈亏

2.可用余额=账户余额+所有合约已实现盈亏+所有合约的未实现\- 所有仓位持仓所需保证金 \- 挂单冻结保证金

##### 返回示例

###### 全仓

    
    
    {
        "info":{
            "btc":{
                "can_withdraw":"0.00994739",
                "currency":"BTC",
                "equity":"0.00994739",
                "liqui_fee_rate":"0.0005",
                "liqui_mode":"tier",
                "maint_margin_ratio":"0.005",
                "margin":"0",
                "margin_for_unfilled":"0",
                "margin_frozen":"0",
                "margin_mode":"crossed",
                "margin_ratio":"10000",
                "realized_pnl":"0",
                "total_avail_balance":"0.00994739",
                "underlying":"BTC-USD",
                "unrealized_pnl":"0"
            }
        }
    }
    

###### 逐仓

    
    
    {
        "info":{
            "bch":{
                "auto_margin":"0",
                "can_withdraw":"0.00169207",
                "contracts":[
                    {
                        "available_qty":"0.00169207",
                        "fixed_balance":"0",
                        "instrument_id":"BCH-USD-191227",
                        "margin_for_unfilled":"0",
                        "margin_frozen":"0",
                        "realized_pnl":"0",
                        "unrealized_pnl":"0"
                    }
                ],
                "currency":"BCH",
                "equity":"0.00169207",
                "liqui_mode":"tier",
                "margin_mode":"fixed",
                "total_avail_balance":"0.00169207"
            }
        }
    }
    

### 单个币种合约账户信息

获取单个币种的合约账户信息。

##### 限速规则：20次/2s （根据underlying，分别限速）

##### HTTP请求

`GET/api/futures/v3/accounts/<underlying>`

##### 请求示例

`GET/api/futures/v3/accounts/btc-usd`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
underlying | String | 是 | 标的指数，如：`btc-usd`,`btc-usdt`  
  
##### 返回参数

###### 全仓

全仓参数名 | 参数类型 | 描述  
---|---|---  
margin_mode | String | 账户类型  
全仓：`crossed`  
equity | String | 账户权益  
total_avail_balance | String | 账户余额  
margin | String | 保证金（挂单冻结+持仓已用）  
margin_frozen | String | 持仓已用保证金  
margin_for_unfilled | String | 挂单冻结保证金  
realized_pnl | String | 已实现盈亏  
unrealized_pnl | String | 未实现盈亏  
margin_ratio | String | 保证金率  
maint_margin_ratio | String | 维持保证金率  
liqui_mode | string | 强平模式：`tier`（梯度强平）  
can_withdraw | string | 可划转数量  
liqui_fee_rate | string | 强平手续费  
underlying | string | 标的指数，如：BTC-USD，BTC-USDT  
currency | string | 账户余额币种  
  
###### 逐仓

逐仓参数名 | 参数类型 | 描述  
---|---|---  
margin_mode | String | 账户类型  
逐仓：`fixed`  
fixed_balance | String | 逐仓账户余额  
available_qty | String | 逐仓可用余额  
margin_frozen | String | 持仓已用保证金  
margin_for_unfilled | String | 挂单冻结保证金  
instrument_id | String | 合约ID，如`BTC-USD-180213`,`BTC-USDT-191227`  
realized_pnl | String | 已实现盈亏  
unrealized_pnl | String | 未实现盈亏  
equity | String | 账户权益  
total_avail_balance | String | 账户余额  
auto_margin | String | 是否自动追加保证金  
`1`: 自动追加已开启  
`0`: 自动追加未开启  
liqui_mode | string | 强平模式：`tier`（梯度强平）  
can_withdraw | string | 可划转数量  
currency | string | 账户余额币种  
  
##### 解释说明

所有持仓/所有账户信息，没有持仓/持币时返回空JSON；单个持仓/单个账户信息没有持仓/持币时返回各字段均为默认值

逐仓：

1.账户权益：账户权益=账户余额+逐仓仓位账户余额+所有合约的已实现盈亏+所有合约的未实现盈亏

2.可用：可用余额=账户余额+逐仓仓位账户余额+本合约已实现盈亏\- 当前仓位的持仓所需保证金 \- 挂单冻结保证金

全仓：

1.账户权益=账户余额+所有合约的已实现盈亏+所有合约的未实现盈亏

2.可用余额=账户余额+所有合约已实现盈亏+所有合约的未实现\- 所有仓位持仓所需保证金 \- 挂单冻结保证金

##### 返回示例

###### 全仓

    
    
    {
        "equity": "0",
        "margin": "0",
        "realized_pnl": "0",
        "unrealized_pnl": "0",
        "margin_ratio": "10000",
        "margin_mode": "crossed",
        "total_avail_balance": "0",
        "margin_frozen": "0",
        "margin_for_unfilled": "0",
        "liqui_mode": "tier",
        "maint_margin_ratio": "0.005",
        "liqui_fee_rate": "0.0005",
        "can_withdraw": "0",
        "underlying": "BTC-USD",
        "currency": "BTC"
    }
    

###### 逐仓

    
    
    {
        "total_avail_balance": "0",
        "contracts": [
            {
                "available_qty": "0",
                "fixed_balance": "0",
                "instrument_id": "BTC-USD-191227",
                "margin_for_unfilled": "0",
                "margin_frozen": "0",
                "realized_pnl": "0",
                "unrealized_pnl": "0"
            }
        ],
        "equity": "0",
        "margin_mode": "fixed",
        "auto_margin": "0",
        "liqui_mode": "tier",
        "can_withdraw": "0",
        "currency": "BTC"
    }
    

### 获取合约币种杠杆倍数

获取合约账户币种杠杆倍数

##### 限速规则：5次/2s （根据underlying，分别限速）

##### HTTP请求

`GET/api/futures/v3/accounts/<underlying>/leverage`

##### 请求示例

`GET/api/futures/v3/accounts/btc-usdt/leverage`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
underlying | String | 是 | 标的指数，如：`BTC-USD`，`BTC-USDT`  
  
##### 返回参数

###### 全仓

全仓参数名 | 参数类型 | 描述  
---|---|---  
margin_mode | String | 账户类型  
全仓：`crossed`  
underlying | String | 标的指数，如：`BTC-USD`，`BTC-USDT`  
leverage | String | 杠杆倍数  
  
###### 逐仓

逐仓参数名 | 参数类型 | 描述  
---|---|---  
margin_mode | String | 账户类型  
逐仓：`fixed`  
instrument_id | String | 合约ID，如`BTC-USD-180213`,`BTC-USDT-191227`  
long_leverage | String | 多头杠杆倍数  
short_leverage | String | 空头杠杆倍数  
  
##### 解释说明

全仓同一个币种只允许有一种杠杆倍数，逐仓同一个合约同一个方向只能用一种杠杆倍数。

##### 返回示例

    
    
    1.全仓模式：
    {
        "leverage": "12",
        "margin_mode": "crossed",
        "underlying": "BTC-USD"
    }
    
    2.逐仓模式：
    {
        "BTC-USD-191227": {
            "long_leverage": "20",
            "short_leverage": "10"
        },
        "BTC-USD-191108": {
            "long_leverage": "10",
            "short_leverage": "10"
        },
        "margin_mode": "fixed",
        "BTC-USD-191101": {
            "long_leverage": "10",
            "short_leverage": "10"
        }
    }
    

### 设定合约币种杠杆倍数

设置合约账户币种杠杆倍数。当下单时，系统会按照您设置的杠杆倍数进行下单。

##### 限速规则：5次/2s （根据underlying，分别限速）

##### HTTP请求

`POST /api/futures/v3/accounts/<underlying>/leverage`

##### 请求示例

`POST /api/futures/v3/accounts/BTC-USD/leverage{"leverage":"10"}`（全仓示例）

`POST /api/futures/v3/accounts/BTC-USD/leverage{"instrument_id":"BTC-
USD-180213","direction":"long","leverage":"10"}`（逐仓示例）

##### 请求参数

###### 全仓

全仓参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
leverage | String | 是 | 要设定的杠杆倍数，填写`1-100`的数值  
underlying | String | 是 | 标的指数，如：`BTC-USD`,`BTC-USDT`  
  
###### 逐仓

逐仓参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
instrument_id | String | 是 | 合约ID，如`BTC-USD-180213` ,`BTC-USDT-191227`  
direction | String | 是 | 开仓方向  
`long`（做多）或`short`（做空）  
leverage | String | 是 | 要设定的杠杆倍数，填写`1-100`的数值  
underlying | String | 是 | 标的指数，如：`BTC-USD`,`BTC-USDT`  
  
##### 返回参数

###### 全仓

全仓参数名 | 参数类型 | 描述  
---|---|---  
margin_mode | String | 账户类型  
全仓：`crossed`  
underlying | String | 标的指数，如：`BTC-USD`，`BTC-USDT`  
leverage | String | 已设定的杠杆倍数，`1-100`的数值  
result | String | 返回设定结果，成功或错误码  
  
###### 逐仓

逐仓参数名 | 参数类型 | 描述  
---|---|---  
margin_mode | String | 账户类型  
逐仓：`fixed`  
instrument_id | String | 合约ID，如`BTC-USD-180213`  
direction | String | 开仓方向  
`long`（做多）或`short`（做空）  
leverage | String | 已设定的杠杆倍数，`1-100`的数值  
result | String | 返回设定结果，成功或错误码  
  
##### 解释说明

仓位设定：全仓，逐仓

全仓的话：传`currency` ,传杠杆倍数

逐仓的话：传`instrument_id`，传方向，传杠杆倍数

全仓同一个币种只允许有一种杠杆倍数，逐仓同一个合约同一个方向只能用一种杠杆倍数。

##### 返回示例

    
    
    1.全仓模式：
    {
        "result": true,
        "leverage": "12",
        "margin_mode": "crossed",
        "currency": "BTC",
        "underlying": "BTC-USD"
    }
    
    2.逐仓模式：
    {
        "result": true,
        "BTC-USD-191227": {
            "short": "10",
            "long": "20"
        },
        "margin_mode": "fixed"
    }
    

### 账单流水查询

列出帐户资产流水。帐户资产流水是指导致帐户余额增加或减少的行为。本接口能查询最近三个月的数据。

##### 限速规则：5次/2s （根据underlying，分别限速）

##### HTTP请求

`GET/api/futures/v3/accounts/<underlying>/ledger`

##### 请求示例

`GET/api/futures/v3/accounts/eos-usd/ledger?after=2510946217009854&limit=3`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
underlying | String | 是 | 标的指数，如：`btc-usd`,`btc-usdt`  
after | String | 否 | 请求此id之前（更旧的数据）的分页内容，传的值为对应接口的`ledger_id`  
before | String | 否 | 请求此id之后（更新的数据）的分页内容，传的值为对应接口的`ledger_id` |  
limit | String | 否 | 分页返回的结果集数量，最大为100，不填默认返回100条  
type | String | 否 | `1`.开多  
`2`.开空  
`3`.平多  
`4`.平空  
`5`.手续费  
`6`.转入，  
`7`.转出  
`8`.清算已实现盈亏  
`13`.强平平多  
`14`.强平平空  
`15`.交割平多  
`16`.交割平空  
`17`.清算未实现收益-多头  
`18`.清算未实现收益-空头  
`20`.强减空  
`21`.强减多  
  
##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
ledger_id | String | 账单ID  
underlying | String | 标的指数，如：`btc-usd`,`btc-usdt`  
amount | String | 变动数量  
type | String | 流水来源  
timestamp | String | 账单创建时间  
details | String |
如果`type`是`trade`或者`fee`，则会有该`details`字段将包含`order`，`instrument`信息,如果`type`是`transfer`，则会有该`details`字段将包含`from`，`to`信息  
order_id | String | 订单ID  
instrument_id | String | 合约ID  
from | String | 转出账户  
`1`:币币账户  
`3`:交割合约  
`4`:法币账户  
`5`:币币杠杆账户  
`6`:资金账户  
`8`:余币宝账户  
`9`:永续合约账户  
`12`:期权合约  
`14`:挖矿账户  
`17`:借贷账户  
to | String | 转入账户  
`1`:币币账户  
`3`:交割合约  
`4`:法币账户  
`5`:币币杠杆账户  
`6`:资金账户  
`8`:余币宝账户  
`9`:永续合约账户  
`12`:期权合约  
`14`:挖矿账户  
`17`:借贷账户  
balance | String | 开仓平仓的张数（开仓为正数，平仓为负数，当`type`是`fee`
和`transfer`时，`balance`为`0`）  
currency | string | 账户余额币种  
流水来源类型 | 参数类型 | 描述  
---|---|---  
transfer | String | 资金转入/转出  
match | String | 开多/开空/平多/平空  
fee | String | 手续费  
settlement | String | 清算/分摊/多结算/空结算  
liquidation | String | 强平多/强平空/交割平多/交割平空  
  
##### 返回示例

    
    
    [
        {
            "ledger_id":"3786201700599811",
            "timestamp":"2019-10-31T08:00:53.097Z",
            "amount":"0",
            "balance":"0",
            "currency":"btc-usd",
            "underlying":"BTC-USD",
            "type":"settlement",
            "details":{
                "order_id":"0",
                "instrument_id":"BTC-USD-191227"
            }
        }
    ]
    

### 下单

OKEx合约交易提供了限价单下单模式。只有当您的账户有足够的资金才能下单。一旦下单，您的账户资金将在订单生命周期内被冻结。被冻结的资金以及数量取决于订单指定的类型和参数。

当前最高可开杠杆倍数由您的持仓、挂单及开仓时新的下单张数决定，详情请见：<https://www.okex.com/derivatives/futures/position>

##### 限速规则：60次/2s
（1）不同合约之间限速不累计；2）同一合约的当周次周季度之间限速累计；3）同一合约的币本位和USDT保证金之间限速不累计）

##### HTTP请求

`POST /api/futures/v3/order`

##### 请求示例

`POST /api/futures/v3/order{"client_oid":
"12233456","order_type":"1","instrument_id":"BTC-
USD-180213","type":"1","price":"432.11","size":"2","match_price":"0"}`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
client_oid | String | 否 | 由您设置的订单ID来识别您的订单,格式是字母（区分大小写）+数字 或者
纯字母（区分大小写），1-32位字符 （不能重复）  
instrument_id | String | 是 | 合约ID，如`BTC-USD-180213` ,`BTC-USDT-191227`  
type | String | 是 | `1`:开多  
`2`:开空  
`3`:平多  
`4`:平空  
order_type | String | 否 | 参数填数字  
`0`：普通委托（order type不填或填0都是普通委托）  
`1`：只做Maker（Post only）  
`2`：全部成交或立即取消（FOK）  
`3`：立即成交并取消剩余（IOC）  
`4`：市价委托  
price | String | 否 | 委托价格  
size | String | 是 | 买入或卖出合约的数量（以张计数）  
match_price | String | 否 | 是否以对手价下单(`0`:不是;
`1`:是)，默认为`0`，当取值为`1`时，price字段无效。当以对手价下单，`order_type`只能选择`0`（普通委托）  
  
##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
order_id | String | 订单ID，下单失败时，此字段值为`-1`  
client_oid | String | 由您设置的订单ID来识别您的订单  
error_code | String | 错误码，下单成功时为0，下单失败时会显示相应错误码  
error_message | String | 错误信息，下单成功时为空，下单失败时会显示错误信息  
result | Boolean | 调用接口返回结果  
  
##### 解释说明

instrument_id

`instrument_id`必须是有效的合约ID。合约列表可通过/ instruments接口获取。

client_oid

`client_oid`的类型为字母（大小写）+数字或者纯字母（大小写），1-32位字符（此功能 2019.2.28 号正式上线）
，用户需要自己保证此ID不重复，OKEx不会进行排重提示，如有重复，撤单和查询订单时只能撤销或者查询最新的一条数据。

type

下单时，您可以指定订单类型。在您没有持仓时，只能选择开多和开空。您只能对持仓合约进行平仓。

price

`price`表示买入或卖出每张合约的价格。价格必须是价格步长`tick_size`的倍数。价格步长`tick_size`是价格的最小增量，可通过instruments接口获取。

size

`size`表示买入或卖出合约的张数。数量必须是整数。

match_price

对手价表示你希望以目前对手方的最优价格成交。如果你下的是买单，选择以对手价下单表示你用当前卖一价进行下单。如果你下的是卖单，选择以对手价下单表示你用当前买一价进行下单。

订单生命周期

HTTP请求将在订单被拒绝（资金不足，参数无效等）或下单成功（由匹配引擎接受）时作出响应。一个200响应表示该订单被接收并且进入撮合。进入撮合的订单可以部分或全部立即成交（取决于价格和市场条件）。部分成交的时候将把订单的剩余数量继续进行撮合。完全成交的订单将进入已成交状态。

监听行情数据的用户建议使用`client_oid`字段以便在接受到的信息中标识对应的数据。

响应

成功接受的订单将被分配一个订单ID。成功接受的订单表示撮合引擎已经接受的订单。

未成交的订单不会过期，并将保持撮合状态，直到被成交或取消。

##### 返回示例

    
    
    {
        "result":true,
        "error_message":"",
        "error_code":"0",
        "client_oid":"oktfuture8",
        "order_id":"2517062038154240"
    }
    

### 批量下单

批量进行合约下单操作。每个合约可批量下10个单。

##### 限速规则：30次/2s
（1）不同合约之间限速不累计；2）同一合约的当周次周季度之间限速累计；3）同一合约的币本位和USDT保证金之间限速不累计）

##### HTTP请求

`POST /api/futures/v3/orders`

##### 请求示例

`POST /api/futures/v3/orders{"instrument_id":"ETH-
USD-181228","orders_data":[{"order_type":"1","client_oid":"f379a96206fa4b778e1554c6dc969687","type":"1","price":"180.0","size":"1","match_price":"0"}]}`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
instrument_id | String | 是 | 合约ID，如`BTC-USD-180213`,`BTC-USDT-190927`  
orders_data | List<String> | 是 | JSON类型的字符串
例：`[{order_type:"0",price:"5",size:"2",type:"1",match_price:"1"},{order_type:"0",price:"2",size:"3",type:"1",match_price:"1"}]`  
最大下单量为`10`，当以对手价下单，`order_type`只能选择`0`（普通委托） 。  
`price`, `size`, `type`, `match_price` 参数参考future_trade接口中的说明  
client_oid | String | 否 | 由您设置的订单ID来识别您的订单,格式是字母（区分大小写）+数字 或者
纯字母（区分大小写），1-32位字符 （不能重复）  
order_type | String | 否 | 参数填数字  
`0`：普通委托（`order_type`不填或填`0`都是普通委托）  
`1`：只做Maker（Post only）  
`2`：全部成交或立即取消（FOK）  
`3`：立即成交并取消剩余（IOC）  
`4`：市价委托  
  
##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
order_info | String | 订单信息  
order_id | String | 订单ID，下单失败时，此字段值为`-1`  
client_oid | String | 由您设置的订单ID来识别您的订单  
error_code | String | 错误码，下单成功时为`0`，下单失败时会显示相应错误码  
error_message | String | 错误信息，下单成功时为空，下单失败时会显示错误信息  
result | String | 调用接口返回结果  
  
##### 解释说明

`client_oid`用户需要自己保证此ID不重复，OKEx不会进行排重提示，如有重复，撤单和查询订单时只能撤销或者查询最新的一条数据。

只要其中任何一单下单成功，`result`就会返回`true`，
返回的结果数据和`orders_data`提交订单数据顺序一致。如果下单失败，则`order_id`为`-1`，`error_code`是错误码提示，`error_message`是错误信息。

##### 返回示例

    
    
    {
        "result":true,
        "order_info":[
            {
                "error_message":"",
                "error_code":"0",
                "client_oid":"oktfuture18",
                "order_id":"2517748155771904"
            },
            {
                "error_message":"",
                "error_code":"0",
                "client_oid":"oktfuture19",
                "order_id":"2517748157541376"
            }
        ]
    }
    

### 撤销指定订单

撤销之前下的未完成订单。

##### 限速规则：40次/2s
（1）不同合约之间限速不累计；2）同一合约的当周次周季度之间限速累计；3）同一合约的币本位和USDT保证金之间限速不累计）

##### HTTP请求

`POST /api/futures/v3/cancel_order/<instrument_id>/<order_id> or <client_oid>`

##### 请求示例

`POST /api/futures/v3/cancel_order/BTC-USD-180309/1407616797780992`

或

`POST /api/futures/v3/cancel_order/BTC-USD-180309/1407616797780992ee`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
order_id | String | 非必填 | `order_id`和`client_oid`必须且只能选一个填写，订单ID  
instrument_id | String | 是 | 合约ID，如`BTC-USD-180213`,`BTC-USDT-191227`  
client_oid | String | 非必填 | `order_id`和`client_oid`必须且只能选一个填写，由您设置的订单ID来识别您的订单
, 类型为字母（大小写）+数字或者纯字母（大小写）1-32位字符  
  
##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
order_id | String | 订单ID  
result | String | 撤单申请结果  
instrument_id | String | 合约ID，如`BTC-USD-180213`,,`BTC-USDT-191227`  
client_oid | String | 由您设置的订单ID来识别您的订单  
error_code | String | 错误码，撤单成功时为0，撤单失败时会显示相应错误码  
error_message | String | 错误信息，撤单成功时为空，撤单失败时会显示错误信息  
  
##### 解释说明

使用`client_oid`撤单时，用户需要自己保证此ID不重复，OKEx不会进行排重提示，如有重复，撤单时只能撤销最新的一条数据

使用`client_oids`撤单时返回参数包含`order_ids`和`client_oids`,
使用`order_ids`撤单时返回参数不包含`client_oids`

这`order_id`是服务器分配的订单ID，而不是用户传的的`client_oid`

如果订单无法取消（已经成交或已取消），那么返回的报错内容里将显示相应的原因。

返回值是已发起撤销操作的订单ID，不代表这些订单已成功撤销，正在成交中的无法撤销，未成交的可成功撤销。

##### 返回示例

    
    
    1.用client_oid撤单的返回值：
    {
        "result":true,
        "error_message":"",
        "error_code":"0",
        "client_oid":"oktfuture10",
        "order_id":"2517514559122432",
        "instrument_id":"EOS-USD-190628"
    }
    
    2.用order_id撤单的返回值：
    {
        "result":true,
        "error_message":"",
        "error_code":"0",
        "order_id":"2517535534836736",
        "instrument_id":"EOS-USD-190628"
    }
    

### 批量撤销订单

根据指定的order_id撤销某个合约的未完成订单，每次最多可撤10个单。

##### 限速规则：20 次/2s
（1）不同合约之间限速不累计；2）同一合约的当周次周季度之间限速累计；3）同一合约的币本位和USDT保证金之间限速不累计）

##### HTTP请求

`POST /api/futures/v3/cancel_batch_orders/<instrument_id>`

##### 请求示例

`POST /api/futures/v3/cancel_batch_orders/BTC-USD-180309{"order_ids":[
"2517748157541376", "2517748155771904"]}`

或

`POST /api/futures/v3/cancel_batch_orders/BTC-USD-180309{"client_oids":[
"oktfuture19","oktfuture18"]}`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
instrument_id | String | 是 | 撤销指定合约品种的订单 如：`BTC-USD-180309`,`BTC-USDT-191227`  
order_ids | List<String> | 非必填 | `order_id`和`client_oid`必须且只能选一个填写，撤销指定的订单ID  
client_oids | List<String> | 非必填 |
`order_id`和`client_oid`必须且只能选一个填写，由您设置的订单ID来识别您的订单，
类型为字母（大小写）+数字或者纯字母（大小写）1-32位字符  
  
##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
instrument_id | String | 撤销指定合约品种的订单 如：`BTC-USD-180309`,`BTC-USDT-191227`  
order_ids | String | 撤销指定的订单ID  
client_oids | String | 由您设置的订单ID来识别您的订单  
result | String | 调用接口返回结果  
error_code | String | 错误码，撤单成功时为0，撤单失败时会显示相应错误码  
error_message | String | 错误信息，撤单成功时为空，撤单失败时会显示错误信息  
  
##### 返回参数

批量撤单时候，要么都是`order_id`要么都是`client_oid`s，否则会提示错误

使用`client_oids`批量撤单时，目前只支持一个币对下撤10个`client_oids`，用户需要自己保证此ID不重复，OKEx不会进行排重提示，如有重复，撤单时只能撤销最新的一条数据

`order_ids` 和`client_oids`
必须且只能选一个填写，使用`client_oids`撤单时返回参数包含`order_ids`和`client_oids`，使用`order_ids`撤单时返回参数不包含`client_oids`

返回值是已发起撤销操作的订单ID列表，不代表这些订单已成功撤销，正在成交中的无法撤销，未成交的可成功撤销。

##### 解释说明

无法保证一定会成功撤销，建议用户调用批量撤单接口后，再调用获取订单列表接口确认。

##### 返回示例

    
    
    1.用client_oids批量撤单的返回值：
    {
        "result":true,
        "error_message":"",
        "error_code":"0",
        "order_ids":[
            "2517748157541376",
            "2517748155771904"
        ],
        "instrument_id":"EOS-USD-190628",
        "client_oids":[
            "oktfuture19",
            "oktfuture18"
        ]
    }
    
    2.用order_ids批量撤单的返回值：
    {
        "result":true,
        "error_message":"",
        "error_code":"0",
        "order_ids":[
            "2517748157541376",
            "2517748155771904"
        ],
        "instrument_id":"EOS-USD-190628"
    }
    

### 获取订单列表

列出您当前所有的订单信息。本接口能查询最近三个月的数据。这个请求支持分页，并且按委托时间倒序排序和存储，最新的排在最前面。

##### 限速规则：10次/2s （根据underlying，分别限速）

##### HTTP请求

`GET/api/futures/v3/orders/<instrument_id>`

##### 请求示例

`GET/api/futures/v3/orders/BTC-
USD-190628?state=2&after=2517062044057601&limit=2`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
instrument_id | String | 是 | 合约ID，如`BTC-USD-180213` ,`BTC-USDT-191227`  
state | String | 是 | 订单状态  
`-2`:失败  
`-1`:撤单成功  
`0`:等待成交  
`1`:部分成交  
`2`:完全成交  
`3`:下单中  
`4`:撤单中  
`6`: 未完成（等待成交+部分成交）  
`7`:已完成（撤单成功+完全成交）  
after | String | 否 | 请求此id之前(更旧的数据)的分页内容，传的值为对应接口的order_id；  
before | String | 否 | 请求此id之后(更新的数据)的分页内容，传的值为对应接口的order_id； |  
limit | String | 否 | 分页返回的结果集数量，最大为100，不填默认返回100条  
  
##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
instrument_id | String | 合约ID，如`BTC-USD-180213` ,`BTC-USDT-191227`  
client_oid | String | 用户设置的订单ID  
size | String | 委托数量  
timestamp | Date | 委托时间  
filled_qty | String | 成交数量  
fee | String | 手续费  
order_id | String | 订单ID  
price | String | 委托价格  
price_avg | String | 成交均价  
type | String | 订单类型  
`1`:开多  
`2`:开空  
`3`:平多  
`4`:平空  
contract_val | String | 合约面值  
leverage | String | 杠杆倍数，`1-100`的数值  
order_type | String | `0`：普通委托  
`1`：只做Maker（Post only）  
`2`：全部成交或立即取消（FOK）  
`3`：立即成交并取消剩余（IOC）  
`4`：市价委托  
pnl | String | 收益  
state | String | 订单状态  
`-2`：失败  
`-1`：撤单成功  
`0`：等待成交  
`1`：部分成交  
`2`：完全成交  
`3`：下单中  
`4`：撤单中  
  
##### 解释说明

`status`为`state`旧版参数，会短期兼容，建议尽早切换`state`。

`client_oid`的类型为字母（大小写）+数字或者纯字母（大小写），1-32位字符
，用户需要自己保证此ID不重复，OKEx不会进行排重提示，如有重复，撤单和查询订单时只能撤销或者查询最新的一条数据。

如果订单在其生命周期内没有任何成交，其记录可能被清除。这表示订单详细信息将不可用本接口来获取。

未成交的订单可能会根据市场情况在你发起请求和服务器响应之间改变状态。

##### 返回示例

    
    
    {
        "result": true,
        "order_info": [
            {
                "instrument_id": "BTC-USD-191227",
                "size": "2",
                "timestamp": "2019-09-25T08:42:34.000Z",
                "filled_qty": "2",
                "fee": "-0.0000119",
                "order_id": "3582522429644800",
                "price": "8160.55",
                "price_avg": "8402.36",
                "status": "2",
                "state": "2",
                "type": "3",
                "contract_val": "100",
                "leverage": "10",
                "client_oid": "",
                "pnl": "-0.00011292",
                "order_type": "0"
            },
            {
                "instrument_id": "BTC-USD-191227",
                "size": "2",
                "timestamp": "2019-09-25T07:58:42.000Z",
                "filled_qty": "2",
                "fee": "-0.00001183",
                "order_id": "3582349944101888",
                "price": "8454.42",
                "price_avg": "8454.42",
                "status": "2",
                "state": "2",
                "type": "1",
                "contract_val": "100",
                "leverage": "10",
                "client_oid": "",
                "pnl": "0",
                "order_type": "0"
            }
        ]
    }
    

### 获取订单信息

通过订单ID获取单个订单信息。已撤销的未成交单只保留2个小时。

##### 限速规则：60次/2s （根据underlying，分别限速）

##### HTTP请求

`GET/api/futures/v3/orders/<instrument_id>/<order_id>`

或

`GET/api/futures/v3/orders/<instrument_id>/<client_oid>`

##### 请求示例

`GET/api/futures/v3/orders/BTC-USD-180213/888845120785408`

或

`GET/api/futures/v3/orders/BTC-USD-180213/888845120785408ee`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
order_id | String | 否 | 订单ID `order_id`和`client_oid`必须且只能选一个填写  
instrument_id | String | 是 | 合约ID，如`BTC-USD-180213`,`BTC-USDT-191227`  
client_oid | String | 否 | `order_id`和`client_oid`必须且只能选一个填写 .由您设置的订单ID来识别您的订单
, 类型为字母（大小写）+数字或者纯字母（大小写） 1-32位字符  
  
##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
instrument_id | String | 合约ID，如`BTC-USD-180213`,`BTC-USDT-191227`  
client_oid | String | 由您设置的订单ID来识别您的订单  
size | String | 委托数量  
timestamp | String | 委托时间  
filled_qty | String | 成交数量  
fee | String | 手续费  
order_id | String | 订单ID  
price | String | 委托价格  
price_avg | String | 成交均价  
type | String | 订单类型  
`1`:开多  
`2`:开空  
`3`:平多  
`4`:平空  
contract_val | String | 合约面值  
leverage | String | 杠杆倍数，`1-100`的数值  
order_type | String | `0`：普通委托  
`1`：只做Maker（Post only）  
`2`：全部成交或立即取消（FOK）  
`3`：立即成交并取消剩余（IOC）  
`4`：市价委托  
pnl | String | 收益  
state | String | 订单状态  
`-2`：失败  
`-1`：撤单成功  
`0`：等待成交  
`1`：部分成交  
`2`：完全成交  
`3`：下单中  
`4`：撤单中  
  
##### 解释说明

`status`为`state`旧版参数，会短期兼容，建议尽早切换`state`。

`client_oid`的类型为字母（大小写）+数字或者纯字母（大小写），1-32位字符
，用户需要自己保证此ID不重复，OKEx不会进行排重提示，如有重复，撤单和查询订单时只能撤销或者查询最新的一条数据。

本接口只能查询最近三个月的已成交和已撤销订单信息。

如果订单在其生命周期内没有任何成交，其记录可能被清除，则响应可能因为没有相应的匹配而返回状态码404。

未成交的订单可能会根据市场情况在你发起请求和服务器响应之间改变状态。

##### 返回示例

    
    
    {
        "instrument_id": "BTC-USD-191227",
        "size": "2",
        "timestamp": "2019-09-25T08:42:34.000Z",
        "filled_qty": "2",
        "fee": "-0.0000119",
        "order_id": "3582522429644800",
        "price": "8160.55",
        "price_avg": "8402.36",
        "status": "2",
        "state": "2",
        "type": "3",
        "contract_val": "100",
        "leverage": "10",
        "client_oid": "",
        "pnl": "-0.00011292",
        "order_type": "0"
    }
    

### 获取成交明细

获取最近的成交明细列表，本接口能查询最近7天的数据。

##### 限速规则：10次/2s （根据underlying，分别限速）

##### HTTP请求

`GET/api/futures/v3/fills`

##### 请求示例

`GET/api/futures/v3/fills?order_id=123123&instrument_id=BTC-
USD-180309&after=2517062044057601&limit=50`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
order_id | String | 否 | 订单ID，不填写`order_id`，返回当前`instrument_id`下的所有订单成交明细  
instrument_id | String | 是 | 合约ID，如`BTC-USD-180213` ,`BTC-USDT-191227`  
after | String | 否 | 请求此id之前（更旧的数据）的分页内容，传的值为对应接口的`trade_id`  
before | String | 否 | 请求此id之后（更新的数据）的分页内容，传的值为对应接口的`trade_id` |  
limit | String | 否 | 分页返回的结果集数量，最大为100，不填默认返回100条  
  
##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
trade_id | String | 账单ID  
instrument_id | String | 合约ID，如`BTC-USD-180213`,`BTC-USDT-191227`  
price | String | 价格  
order_qty | String | 数量  
order_id | String | 订单ID  
created_at | String | 订单成交时间  
exec_type | String | 流动性方向（`T` 或 `M`）  
fee | String | 手续费  
side | String | 订单方向（`buy` 或 `sell`）  
type | String | `1`:开多  
`2`:开空  
`3`:平多  
`4`:平空  
  
##### 解释说明

手续费

`fee`字段：负数的`fee`表示平台收取的手续费，正数的`fee`表示表示平台向达到指定lv交易等级的用户支付的挂单奖励（返佣）

流动性

`exec_type`字段表示该账单是maker还是taker产生的。`M`表示Maker，`T`表示Taker。

分页

返回账单列表的`trade_id`按降序排列，从最大`trade_id`到最小trade_id。`OK-
after`都会有这样的第一笔`trade_id`，以便将来的请求使用`OK-after`参数将获取一个更大的`trade_id`（新的账单）。

##### 返回示例

    
    
    [
        {
            "trade_id":"2517062044057601",
            "instrument_id":"EOS-USD-190628",
            "price":"3.692",
            "order_qty":"1",
            "order_id":"251706627555816789240",
            "created_at":"2019-03-21T04:41:58.0Z",
            "exec_type":"T",
            "fee":"-0.00081257",
            "type":"1",
            "side":"buy"
        }
    ]
    

### 设置合约币种账户模式

设置合约币种账户模式，注意：当前有仓位或者有挂单时禁止切换账户模式。

##### 限速规则：5次/2s

##### HTTP请求

`POST /api/futures/v3/accounts/margin_mode`

##### 请求示例

`POST /api/futures/v3/accounts/margin_mode{"underlying":"btc-
usd","margin_mode":"crossed"}`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
underlying | String | 是 | 标的指数，如：`BTC-USD`,`BTC-USDT`  
margin_mode | String | 是 | 账户模式  
`crossed`:全仓  
`fixed`:逐仓  
  
##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
underlying | String | 标的指数，如：`BTC-USD`,`BTC-USDT`  
margin_mode | String | 账户模式  
`crossed`:全仓  
`fixed`:逐仓  
result | String | 返回设定结果  
  
##### 返回示例

    
    
    {
        "result": true,
        "margin_mode": "fixed",
        "underlying": "BTC-USD"
    }
    

### 市价全平

市价全平接口，其中BTC合约持仓小于或等于999张时才能调用，否则报错；类似的，其他币种合约的持仓应该小于或等于9999张。

##### 限速规则：2次/2s （根据underlying，分别限速）

##### HTTP请求

`POST /api/futures/v3/close_position`

##### 请求示例

`POST /api/futures/v3/close_position{"instrument_id":"BTC-
USD-180213","direction":"long"}`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
instrument_id | String | 是 | 合约ID，如`BTC-USD-180213`,`BTC-USDT-191227`  
direction | String | 是 | 平仓方向  
`long`:平多  
`short`:平空  
  
##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
instrument_id | String | 合约ID，如`BTC-USD-180213` ,`BTC-USDT-191227`  
direction | String | 平仓方向  
`long`:平多  
`short`:平空  
error_code | String | 错误码，下单成功时为`0`，下单失败时会显示相应错误码  
error_message | String | 错误信息，下单成功时为空，下单失败时会显示错误信息  
result | String | 调用接口返回结果  
  
##### 返回示例

    
    
    {
        "result":true,
        "error_message":"",
        "error_code":"0",
        "instrument_id":"BTC-USD-180213",
        "direction":"long"
    }
    

### 撤销所有平仓挂单

此接口，仅支持撤销平仓的所有挂单。不包括开仓的挂单。

##### 限速规则：5次/2s （根据underlying，分别限速）

##### HTTP请求

`POST /api/futures/v3/cancel_all`

##### 请求示例

`POST /api/futures/v3/cancel_all{"instrument_id":"BTC-
USD-180213","direction":"long"}`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
instrument_id | String | 是 | 合约ID，如`BTC-USD-180213` ,`BTC-USDT-191227`  
direction | String | 是 | 平仓方向  
`long`:平多  
`short`:平空  
  
##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
instrument_id | String | 是 合约ID，如`BTC-USD-180213`,`BTC-USDT-191227`  
direction | String | 是 平仓方向  
`long`:平多  
`short`:平空  
error_code | String | 错误码，下单成功时为`0`，下单失败时会显示相应错误码  
error_message | String | 错误信息，下单成功时为空，下单失败时会显示错误信息  
result | String | 调用接口返回结果  
  
##### 返回示例

    
    
    {
        "result":true,
        "error_message":"",
        "error_code":"0",
        "instrument_id":"BTC-USD-180213",
        "direction":"long"
    }
    

### 获取合约挂单冻结数量

获取合约挂单冻结的数量.

##### 限速规则：5次/2s （根据underlying，分别限速）

##### HTTP请求

`GET/api/futures/v3/accounts/<instrument_id>/holds`

##### 请求示例

`GET/api/futures/v3/accounts/BTC-USD-181228/holds`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
instrument_id | String | 是 | 合约ID，如`BTC-USD-180213`,`BTC-USDT-191227`  
  
##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
instrument_id | String | 合约ID，如`BTC-USD-180213`,`BTC-USDT-191227`  
amount | String | 冻结数量  
timestamp | String | 查询时间  
  
##### 返回示例

    
    
    {
        "amount":"0.3073",
        "instrument_id":"EOS-USD-190328",
        "timestamp":"2019-03-26T03:19:48.035Z"
    }
    

### 委托策略下单

委托策略下单

提供止盈止损、跟踪委托、冰山委托和时间加权委托策略

##### 限速规则：40次/2s （根据underlying，分别限速）

##### HTTP请求

`POST /api/futures/v3/order_algo`

##### 请求示例

`POST /api/futures/v3/order_algo{"instrument_id":"BTC-
USD-190328","type":"1","trigger_price":"432.11","order_type":"1","algo_price":"341.99","size":"2"}`（止盈止损）

##### 请求参数（通用）

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
instrument_id | String | 是 | 合约ID，如`BTC-USD-190328` ,`BTC-USDT-191227`  
type | String | 是 | `1`:开多  
`2`:开空  
`3`:平多  
`4`:平空  
order_type | String | 是 | `1`：止盈止损  
`2`：跟踪委托  
`3`：冰山委托  
`4`：时间加权  
size | String | 是 | 委托总数（以张计数），填写值1\<=X\<=1000000的整数  
  
##### 止盈止损参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
trigger_price | String | 是 | 触发价格，填写值0\<X\<=1000000  
algo_price | String | 是 | 委托价格，填写值0\<X\<=1000000  
algo_type | String | 否 | 1:限价 2:市场价；触发价格类型，默认是限价；为市场价时，委托价格不必填；  
  
##### 跟踪委托参数 （最多同时存在10单）

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
callback_rate | String | 是 | 回调幅度，填写值0.001（0.1%）\<=X\<=0.05（5%）  
trigger_price | String | 是 | 激活价格 ，填写值0\<X\<=1000000  
  
##### 冰山委托参数 （最多同时存在6单）

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
algo_variance | String | 是 | 委托深度，填写值0.0001(0.01%)\<=X\<=0.01（1%）  
avg_amount | String | 是 | 单笔均值，填写2-1000的整数（永续2-500的整数）  
price_limit | String | 是 | 价格限制 ，填写值0\<X\<=1000000  
  
##### 时间加权参数 （最多同时存在6单）

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
sweep_range | String | 是 | 扫单范围，填写值0.005（0.5%）\<=X\<=0.01（1%）  
sweep_ratio | String | 是 | 扫单比例，填写值 0.01\<=X\<=1  
single_limit | String | 是 | 单笔上限，填写值10\<=X\<=2000（永续2-500的整数）  
price_limit | String | 是 | 价格限制，填写值0\<X\<=1000000  
time_interval | String | 是 | 委托间隔，填写值5\<=X\<=120  
  
#### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
result | String | 调用接口返回结果  
instrument_id | String | 合约ID，如`BTC-USD-190328`  
order_type | String | `1`：止盈止损  
`2`：跟踪委托  
`3`：冰山委托  
`4`：时间加权  
algo_id | String | 订单ID，下单失败时，此字段值为`-1`  
error_code | String | 错误码，下单成功时为0，下单失败时会显示相应错误码  
error_message | String | 错误信息，下单成功时为空，下单失败时会显示错误信息  
  
##### 返回示例

    
    
    {
        "result": true,
        "algo_id": "3003646",
        "error_message": "",
        "error_code": "0",
        "instrument_id": "EOS-USD-191227",
        "order_type": "1"
    }
    

### 委托策略撤单

委托策略撤单

根据指定的`algo_id`撤销某个合约的未完成订单，每次最多可撤6（冰山/时间）/10（计划/跟踪）个。

##### 限速规则：20 次/2s （根据underlying，分别限速）

##### HTTP请求

`POST /api/futures/v3/cancel_algos`

##### 请求示例

单个撤单：`POST /api/futures/v3/cancel_algos{"instrument_id":"BTC-
USD-190328","order_type":"1","algo_ids":["198273485"]}`

批量撤单：`POST /api/futures/v3/cancel_algos{"instrument_id":"BTC-
USD-190328","order_type":"1","algo_ids":["198273485","198273486"]}`

##### 请求参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
instrument_id | String | 是 | 撤销指定的合约品种 e.g `BTC-USDT-191227` ,`BTC-USD-190328`  
algo_ids | List<String> | 是 | 撤销指定的委托单ID  
order_type | String | 是 | `1`：止盈止损  
`2`：跟踪委托  
`3`：冰山委托  
`4`：时间加权  
  
##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
instrument_id | String | 撤销指定的合约品种  
order_type | String | `1`：止盈止损  
`2`：跟踪委托  
`3`：冰山委托  
`4`：时间加权  
algo_ids | String | 撤销指定的委托单ID  
result | String | 调用接口返回结果  
error_code | String | 错误码，撤单成功时为0，撤单失败时会显示相应错误码  
error_message | String | 错误信息，撤单成功时为空，撤单失败时会显示错误信息  
  
返回参数

返回值是已发起撤销操作的委托单ID，不代表这些委托单已成功撤销，正在成交中的无法撤销，未成交的可成功撤销。

解释说明

无法保证一定会成功撤销，建议用户调用撤单接口后，再调用获取委托单列表接口确认。

##### 返回示例

    
    
    {
        "result": true,
        "error_message": "",
        "error_code": "0",
        "algo_id": "3003646",
        "instrument_id": "EOS-USD-191227",
        "order_type": "1"
    }
    

### 获取委托单列表

获取委托单列表

列出您当前所有的订单信息。

##### 限速规则：20次/2s （根据underlying，分别限速）

##### HTTP请求

`GET/api/futures/v3/order_algo/<instrument_id>`

##### 请求示例

`GET/api/futures/v3/order_algo/BTC-USD-190328?order_type=1&status=2`

##### 请求参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
instrument_id | String | 是 | 合约ID，如`BTC-USD-190328` ,`BTC-USDT-191227`  
order_type | String | 是 | `1`：止盈止损  
`2`：跟踪委托  
`3`：冰山委托  
`4`：时间加权  
status | String | 见描述 | 【`status`和`algo_id`必填且只能填其一】  
订单状态  
`1`：待生效  
`2`：已生效  
`3`：已撤销  
`4`：部分生效  
`5`：暂停生效  
`6`：委托失败  
【只有冰山和加权有`4`、`5`状态】  
algo_id | String | 见描述 | 【`status`和`algo_id`必填且只能填其一】  
查询指定的委托单ID  
before | string | 否 | 请求此id之后（更新的数据）的分页内容  
after | string | 否 | 请求此id之前（更旧的数据）的分页内容  
limit | string | 否 | 分页返回的结果集数量，默认为`100`，最大为`100`  
  
##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
instrument_id | String | 合约ID，如`BTC-USD-190328`  
order_type | String | `1`：止盈止损  
`2`：跟踪委托  
`3`：冰山委托  
`4`：时间加权  
timestamp | String | 订单状态变化时间  
algo_ids | String | 委托单ID  
status | String | 订单状态  
`1`: 待生效  
`2`: 已生效  
`3`: 已撤销  
`4`: 部分生效  
`5`: 暂停生效  
type | String | 订单类型  
`1`:开多  
`2`:开空  
`3`:平多  
`4`:平空  
leverage | String | 杠杆倍数  
size | String | 委托数量（以张计数）,填写值1\<=X\<=1000000的整数  
order_id | String | 订单id  
  
止盈止损

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
trigger_price | String | 触发价格，填写值0\<X  
algo_price | String | 委托价格，填写值0\<X\<=1000000  
real_amount | String | 实际成交数量  
algo_type | String | 1:限价 2:市场价；  
  
跟踪委托

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
callback_rate | String | 回调幅度，填写值0.001（0.1%）\<=X\<=0.05（5%）  
trigger_price | String | 激活价格 ，填写值0\<X\<=1000000  
real_amount | String | 实际委托数量  
  
冰山委托

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
algo_variance | String | 委托深度，填写值0\<=X\<=0.01（1%）  
avg_amount | String | 单笔均值，填写2-500的整数（永续2-500的整数）  
price_limit | String | 价格限制 ，填写值0\<X\<=1000000  
deal_value | String | 已成交量  
  
时间加权

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
sweep_range | String | 扫单范围，填写值0.005（0.5%）\<=X\<=0.01（1%）  
sweep_ratio | String | 扫单比例，填写值 0.01\<=X\<=1  
single_limit | String | 单笔上限，填写值10\<=X\<=2000（永续2-500的整数）  
price_limit | String | 价格限制，填写值0\<X\<=1000000  
time_interval | String | 委托间隔，填写值5\<=X\<=120  
deal_value | String | 已委托量  
  
##### 返回示例

    
    
    [
        {
            "algo_ids": "3003719",
            "algo_price": "2",
            "instrument_id": "EOS-USD-191227",
            "leverage": "10",
            "order_type": "1",
            "real_amount": "0",
            "size": "1",
            "status": "1",
            "timestamp": "2019-10-11T07:43:41.000Z",
            "trigger_price": "2",
            "type": "1"
        },
        {
            "algo_ids": "3003718",
            "algo_price": "2",
            "instrument_id": "EOS-USD-191227",
            "leverage": "10",
            "order_type": "1",
            "real_amount": "0",
            "size": "1",
            "status": "1",
            "timestamp": "2019-10-11T07:43:39.000Z",
            "trigger_price": "2",
            "type": "1"
        }
    ]
    

### 获取当前手续费费率

获取您当前账户交易等级对应的手续费费率，母账户下的子账户的费率和母账户一致。每天凌晨0点更新一次

##### 限速规则：1次/10s

##### HTTP请求

`GET/api/futures/v3/trade_fee`

##### 请求示例

`2019-11-12T07:28:43.497ZGET/api/futures/v3/trade_fee`

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
taker | String | 吃单手续费率  
maker | String | 挂单手续费率  
delivery | String | 交割手续费率  
timestamp | String | 数据返回时间  
  
备注：maker 的值：负数，代表是返佣的费率，正数，代表平台扣除的费率。（和web页面上展示的一致）

##### 返回示例

    
    
    {
        "delivery": "0.0003",
        "maker": "0.0002",
        "taker": "0.0005",
        "timestamp": "2019-12-11T11:02:31.360Z"
    }
    

### 增加/减少保证金

增加/减少某逐仓仓位的保证金

##### 限速规则：5次/2s

##### HTTP请求

`POST/api/futures/v3/position/margin`

##### 请求示例

`POST/api/futures/v3/position/margin{"instrument_id":"BTC-
USDT-200626","direction":"long","amount":"1","type":"1"}`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
instrument_id | String | 是 | 合约ID，如BTC-USDT-200626  
direction | String | 是 | 开仓方向，long(做多)或者short(做空)  
type | String | 是 | 增加/减少：1：增加 2：减少  
amount | String | 是 | 增加或减少的保证金数量  
  
##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
instrument_id | String | 合约ID，如BTC-USDT-180213  
direction | String | 开仓方向，long(做多)或者short(做空)  
amount | String | 已增加/减少的保证金数量  
type | String | 增加/减少：1：增加 2：减少  
liquidation_price | String | 增加/减少后的最新强平价格  
result | String | 返回设定结果，成功或错误码  
  
##### 返回示例

    
    
    
    {
            "instrument_id":"BTC-USDT-200626",
            "direction": "long",
            "amount":"1",
            "type":"0x62477bac6509a04512819bb1455e923a60dea5966c7caeaa0b24eb8fb0432b85",
            "liquidation_price":"ETH",
            "result":"true"
    }
    

### 设置逐仓自动增加保证金

按币种开启逐仓增加保证金，只有逐仓模式才可开启自动追加保证金功能。

##### 限速规则：5次/2s （根据underlying，分别限速）

##### HTTP请求

`POST /api/futures/v3/accounts/auto_margin`

##### 请求示例

`POST /api/futures/v3/accounts/auto_margin{"underlying":"BTC-USD","type":"1"}`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
underlying | String | 是 | 标的指数，如：`BTC-USD`,`BTC-USDT`  
type | String | 是 | 开/关自动增加保证金：1、开 2、关  
  
##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
underlying | String | 标的指数，如：`BTC-USD`,`BTC-USDT`  
type | String | 开/关自动增加保证金：1、开 2、关  
error_code | String | 错误码，下单成功时为`0`，下单失败时会显示相应错误码  
error_message | String | 错误信息，下单成功时为空，下单失败时会显示错误信息  
result | String | 调用接口返回结果  
  
##### 返回示例

    
    
    {
        "result": true,
        "underlying": "BTC-USD",
        "error_message": "",
        "error_code": "0",
        "type": "1"
    }
    

### 公共-获取合约信息

获取可用合约的列表，查询各合约的交易限制和价格步长等信息。

##### 限速规则：20次/2s （根据ip限速）

##### HTTP请求

`GET/api/futures/v3/instruments`

##### 请求示例

`GET/api/futures/v3/instruments`

##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
instrument_id | String | 合约ID，如`BTC-USD-180213`,`BTC-USDT-191227`  
underlying | String | 标的指数，如：`BTC-USD`  
base_currency | String | 交易货币，如：`BTC-USD`中的BTC ,`BTC-USDT`中的BTC  
quote_currency | String | 计价货币币种，如：`BTC-USD`中的USD ,`BTC-USDT`中的USDT  
settlement_currency | String | 盈亏结算和保证金币种，如BTC  
contract_val | String | 合约面值(美元)  
listing | String | 上线日期  
delivery | String | 交割日期  
tick_size | String | 下单价格精度  
trade_increment | String | 下单数量精度  
alias | String | 本周 `this_week`  
次周 `next_week`  
季度 `quarter`  
次季度 `bi_quarter`  
is_inverse | String | true or false ,是否 币本位保证金合约  
contract_val_currency | String | 合约面值计价币种 如 usd，btc，ltc，etc xrp eos  
  
##### 解释说明

`tick_size`(价格精度)是指下单价格的最小增量，委托价格必须是`tick_size`的倍数。例如，当`tick_size`为`0.01`，委托价格传入`0.022`将被系统按截尾法修正为`0.02`。

##### 返回示例

    
    
        {
            "instrument_id": "TRX-USD-191108",
            "underlying_index": "TRX",
            "quote_currency": "USD",
            "tick_size": "0.00001",
            "contract_val": "10",
            "listing": "2019-10-25",
            "delivery": "2019-11-08",
            "trade_increment": "1",
            "alias": "next_week",
            "underlying": "TRX-USD",
            "base_currency": "TRX",
            "settlement_currency": "TRX",
            "is_inverse": "true",
            "contract_val_currency": "USD"
        },
        {
            "instrument_id": "TRX-USD-191227",
            "underlying_index": "TRX",
            "quote_currency": "USD",
            "tick_size": "0.00001",
            "contract_val": "10",
            "listing": "2019-09-13",
            "delivery": "2019-12-27",
            "trade_increment": "1",
            "alias": "quarter",
            "underlying": "TRX-USD",
            "base_currency": "TRX",
            "settlement_currency": "TRX",
            "is_inverse": "true",
            "contract_val_currency": "USD"
        }
        …………
    ]
    

### 公共-获取深度数据

获取合约的深度列表。这个请求不支持分页，一个请求返回整个深度列表。

##### 限速规则：20次/2s （根据underlying，分别限速）

##### HTTP请求

`GET/api/futures/v3/instruments/<instrument_id>/book`

##### 请求示例

`GET/api/futures/v3/instruments/BTC-USD-180309/book?size=50`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
instrument_id | String | 是 | 合约ID，如`BTC-USD-180213`,`BTC-USDT-191227`  
size | String | 否 | 返回深度数量，最大值可传`200`，即买卖深度共400条  
depth | String | 否 | 按价格合并深度，例如：`0.1`，`0.001`  
  
##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
asks | List<String> | 卖方深度  
bids | List<String> | 买方深度  
timestamp | String | 系统时间戳  
  
返回值数组说明

`["411.8", "10", "1", "4"]`
`411.8`为深度价格，`10`为此价格的合约张数，`1`为此价格的强平单个数，`4`为此价格的订单个数，timestamp为深度生成时间戳。

##### 解释说明

当`size`不传时，返回1条；`size`传`0`时，返回0条；`size`最大`200`，传大于`200`的数时，返回200条。

按价格合并深度是指每个价格区间将仅返回一个数量，就像在该价格区间上只有一个订单。

##### 返回示例

    
    
    {
        "bids":[
            [
                "3.596",
                "5125",
                "0",
                "15"
            ],
            [
                "3.595",
                "553",
                "0",
                "14"
            ]
        ],
        "asks":[
            [
                "3.597",
                "3181",
                "0",
                "18"
            ],
            [
                "3.598",
                "13912",
                "0",
                "31"
            ]
        ],
        "timestamp":"2019-03-22T01:59:34.707Z"
    }
    

### 公共-获取全部ticker信息

获取平台全部合约的最新成交价、买一价、卖一价和24小时交易量的快照信息。

##### 限速规则：20次/2s （根据ip限速）

##### HTTP请求

`GET/api/futures/v3/instruments/ticker`

##### 请求示例

`GET/api/futures/v3/instruments/ticker`

##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
instrument_id | String | 合约ID，如`BTC-USD-180213`,`BTC-USDT-190927`  
last | String | 最新成交价  
best_ask | String | 卖一价  
best_bid | String | 买一价  
high_24h | String | 24小时最高价  
low_24h | String | 24小时最低价  
volume_24h | String | 24小时成交量，按张数统计  
timestamp | String | 系统时间戳  
last_qty | String | 最新成交的数量  
best_ask_size | String | 卖一价对应的量  
best_bid_size | String | 买一价对应的数量  
  
##### 解释说明

最高价、最低价和成交量都是按最近24小时为维度统计的。

##### 返回示例

    
    
    [
       {
           "instrument_id": "btc-usd-200327",
           "last": "7611.21",
           "best_bid": "7612.2",
           "best_ask": "7612.21",
           "high_24h": "8018.38",
           "low_24h": "7611",
           "volume_24h": "12822186",
           "timestamp": "2020-03-12T04:30:10.494Z",
           "last_qty": "20",
           "best_ask_size": "917",
           "best_bid_size": "833"
       }
    
    ]
    

### 公共-获取某个ticker信息

获取合约的最新成交价、买一价、卖一价和24小时交易量的快照信息。

##### 限速规则：20次/2s （根据underlying，分别限速）

##### HTTP请求

`GET/api/futures/v3/instruments/<instrument_id>/ticker`

##### 请求示例

`GET/api/futures/v3/instruments/BTC-USD-180309/ticker`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
instrument_id | String | 是 | 合约ID，如`BTC-USD-180213`,`BTC-USDT-191227`  
  
##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
instrument_id | String | 合约ID，如`BTC-USD-180213`,`BTC-USDT-191227`  
last | String | 最新成交价  
best_ask | String | 卖一价  
best_bid | String | 买一价  
high_24h | String | 24小时最高价  
low_24h | String | 24小时最低价  
volume_24h | String | 24小时成交量，按张数统计  
timestamp | String | 系统时间戳  
last_qty | String | 最新成交的数量  
best_ask_size | String | 卖一价对应的量  
best_bid_size | String | 买一价对应的数量  
  
##### 解释说明

最高价、最低价和成交量都是按最近24小时为维度统计的。

##### 返回示例

    
    
    {
        "instrument_id": "btc-usd-200327",
        "last": "7611.21",
        "best_bid": "7612.2",
        "best_ask": "7612.21",
        "high_24h": "8018.38",
        "low_24h": "7611",
        "volume_24h": "12822186",
        "timestamp": "2020-03-12T04:30:10.494Z",
        "last_qty": "20",
        "best_ask_size": "917",
        "best_bid_size": "833"
    }
    

### 公共-获取成交数据

获取合约最新的300条成交列表。

##### 限速规则：20次/2s （根据underlying，分别限速）

##### HTTP请求

`GET/api/futures/v3/instruments/<instrument_id>/trades`

##### 请求示例

`GET/api/futures/v3/instruments/BTC-
USD-180309/trades?after=2517062044057601&limit=2`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
instrument_id | String | 是 | 合约ID，如`BTC-USD-180213`,`BTC-USDT-191227` |  
after | String | 否 | 请求此id之前（更旧的数据）的分页内容，传的值为对应接口的`trade_id`  
before | String | 否 | 请求此id之后（更新的数据）的分页内容，传的值为对应接口的`trade_id` |  
limit | String | 否 | 分页返回的结果集数量，最大为100，不填默认返回100条  
  
##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
timestamp | String | 成交时间  
trade_id | String | 成交ID  
price | String | 成交价格  
qty | String | 成交数量  
side | String | 成交方向  
  
##### 解释说明

成交方向`side`是指Taker订单的下单方向，Taker表示主动与深度列表中挂单进行成交。`buy`表示价格上涨，因为Taker是买单吃掉深度，所以价格将上行。相反，`sell`表示价格下跌。

`trade_id`是记录成交信息的递增ID，可能不完整。

##### 返回示例

    
    
    [
        [
            {
                "trade_id":"2522253054345222",
                "side":"sell",
                "price":"3.625",
                "qty":"24",
                "timestamp":"2019-03-22T02:42:07.323Z"
            },
            {
                "trade_id":"2522252973080580",
                "side":"buy",
                "price":"3.626",
                "qty":"6",
                "timestamp":"2019-03-22T02:42:06.081Z"
            },
            {
                "trade_id":"2522252969410561",
                "side":"buy",
                "price":"3.626",
                "qty":"6",
                "timestamp":"2019-03-22T02:42:06.026Z"
            }
        ],
        {
    
        }
    ]
    

### 公共-获取K线数据

获取合约的K线数据。K线数据按请求的粒度分组返回，K线数据最多可获取最近1440条。

##### 限速规则：20次/2s （根据underlying，分别限速）

##### HTTP请求

`GET/api/futures/v3/instruments/<instrument_id>/candles`

##### 请求示例

`GET/api/futures/v3/instruments/EOS-
USD-190628/candles?start=2019-03-18T02:31:00Z&end=2019-03-20T02:55:00Z&granularity=60`

（查询`EOS-USD-180309`的2019年3月18日02点31分到2019年3月20日02点55分的1分钟K线数据）

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
instrument_id | String | 是 | 合约ID，如`BTC-USD-180213`,`BTC-USDT-191227`  
start | String | 否 | 开始时间（ISO 8601标准，例如：`2018-06-20T02:31:00Z`）  
end | String | 否 | 结束时间（ISO 8601标准，例如：`2018-06-20T02:31:00Z`）  
granularity | String | 否 |
时间粒度，以秒为单位，默认值`60`。如`[60/180/300/900/1800/3600/7200/14400/21600/43200/86400/604800]`，详见下解释说明  
  
##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
timestamp | String | 开始时间  
open | String | 开盘价格  
high | String | 最高价格  
low | String | 最低价格  
close | String | 收盘价格  
volume | String | 交易量（张）  
currency_volume | String | 按币种折算的交易量  
  
##### 解释说明

K线衔接规则：

1）次周合约交割时：老次周合约对接新当周合约，老当周合约对接新次周合约，季度合约不变；

2）季度合约交割时：老当周合约对接新季度合约，老季度合于对接新次周合约，老次周合约对接新当周合约；

如果用户没有提供开始时间或结束时间中的任一字段，则两个字段都将被忽略。未提供开始时间和结束时间的请求，则系统按时间粒度返回最近的300条数据。

时间粒度`granularity`必须是`[60 180 300 900 1800 3600 7200 14400 21600 43200 86400
604800 2678400 8035200 16070400 31536000]]`中的任一值，否则请求将被拒绝。这些值分别对应的是`[1min 3min
5min 15min 30min 1hour 2hour 4hour 6hour 12hour 1day 1week 1 month 3 months 6
months and 1 year]`的时间段。

K线数据可能不完整。

单次请求的最大数据量是`300`。如果您选择的开始/结束时间和时间粒度导致超过单次请求的最大数据量，您的请求将只会返回300个数据。如果您希望在更大的时间范围内获取足够精细的数据，则需要使用多个开始/结束范围进行多次请求。

返回值分别为`[timestamp,open,high,low,close,volume,currency_volume]`

##### 返回示例

    
    
    [
        [
            "2019-03-20T16:00:00.000Z",
            "3.721",
            "3.743",
            "3.677",
            "3.708",
            "8422410",
            "22698348.04828491"
        ],
        [
            "2019-03-19T16:00:00.000Z",
            "3.731",
            "3.799",
            "3.494",
            "3.72",
            "24912403",
            "67632347.24399722"
        ],
        [
            "2019-03-18T16:00:00.000Z",
            "3.729",
            "3.78",
            "3.698",
            "3.731",
            "17545741",
            "46945274.21772249"
        ]
    ]
    

### 公共-获取指数信息

获取币种指数。此接口为公共接口，不需要身份验证。

##### 限速规则：20次/2s （根据underlying，分别限速）

##### HTTP请求

`GET/api/futures/v3/instruments/<instrument_id>/index`

##### 请求示例

`GET/api/futures/v3/instruments/EOS-USD-190628/index`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
instrument_id | String | 是 | 指数币对，如`BTC-USD-190628`,`BTC-USDT-191227`  
  
##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
instrument_id | String | 指数币对，如`BTC-USD-190628`,`BTC-USDT-191227`  
index | String | 指数价格  
timestamp | String | 系统时间戳  
  
##### 解释说明

指数币对"-"后面的币种表示指数价格的计价单位。

##### 返回示例

    
    
    {
        "instrument_id":"EOS-USD-190628",
        "index":"3.59125725275",
        "timestamp":"2019-03-22T05:18:05.756Z"
    }
    

### 公共-获取法币汇率

获取法币汇率。此接口为公共接口，不需要身份验证。

##### 限速规则：20次/2s （根据ip限速）

##### HTTP请求

`GET/api/futures/v3/rate`

##### 请求示例

`GET/api/futures/v3/rate`

##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
instrument_id | String | 合约ID，如`USD_CNY`  
rate | String | 汇率  
timestamp | String | 系统时间戳  
  
##### 返回示例

    
    
    {
        "instrument_id":"USD_CNY",
        "rate":"6.701",
        "timestamp":"2019-03-22T05:08:44.323Z"
    }
    

### 公共-获取预估交割价

获取合约预估交割价。交割预估价只有交割前一小时才有返回值。此接口为公共接口，不需要身份验证。

##### 限速规则：20次/2s （根据underlying，分别限速）

##### HTTP请求

`GET/api/futures/v3/instruments/<instrument_id>/estimated_price`

##### 请求示例

`GET/api/futures/v3/instruments/BTC-USD-180309/estimated_price`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
instrument_id | String | 是 | 合约ID，如`BTC-USD-180213`,`BTC-USDT-191227`  
  
##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
instrument_id | String | 合约ID，如`BTC-USD-180213`,`BTC-USDT-191227`  
settlement_price | String | 预估交割价  
timestamp | String | 系统时间戳  
  
##### 返回示例

    
    
    {
        "instrument_id":"EOS-USD-181026",
        "settlement_price":"0",
        "timestamp":"2018-10-23T10:07:44.095Z"
    }
    

### 公共-获取平台总持仓量

获取合约整个平台的总持仓量。此接口为公共接口，不需要身份验证。

##### 限速规则：20次/2s （根据underlying，分别限速）

##### HTTP请求

`GET /api/futures/v3/instruments/<instrument_id>/open_interest`

##### 请求示例

`GET/api/futures/v3/instruments/BTC-USD-180309/open_interest`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
instrument_id | String | 是 | 合约ID，如`BTC-USD-180213`,`BTC-USDT-191227`  
  
##### 返回参数

参数名 |  | 描述  
---|---|---  
instrument_id | String | 合约ID，如`BTC-USD-180213`,`BTC-USDT-191227`  
amount | String | 总持仓量  
timestamp | String | 系统时间戳  
  
##### 返回示例

    
    
    {
        "instrument_id":"EOS-USD-190628",
        "amount":"5311831",
        "timestamp":"2019-03-22T05:56:06.726Z"
    }
    

### 公共-获取当前限价

获取合约当前交易的最高买价和最低卖价。此接口为公共接口，不需要身份验证。

##### 限速规则：20次/2s （根据underlying，分别限速）

##### HTTP请求

`GET/api/futures/v3/instruments/<instrument_id>/price_limit`

##### 请求示例

`GET/api/futures/v3/instruments/BTC-USD-180309/price_limit`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
instrument_id | String | 是 | 合约ID，如`BTC-USD-180213`,`BTC-USDT-191227`  
  
##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
instrument_id | String | 合约ID，如`BTC-USD-180213`,`BTC-USDT-191227`  
highest | String | 最高买价  
lowest | String | 最低卖价  
timestamp | String | 系统时间戳  
  
##### 返回示例

    
    
    {
        "instrument_id":"EOS-USD-190628",
        "highest":"3.707",
        "lowest":"3.491",
        "timestamp":"2019-03-22T06:05:08.502Z"
    }
    

### 公共-获取标记价格

获取合约标记价格。此接口为公共接口，不需要身份验证。

##### 限速规则：20次/2s （根据underlying，分别限速）

##### HTTP请求

`GET/api/futures/v3/instruments/<instrument_id>/mark_price`

##### 请求示例

`GET/api/futures/v3/instruments/BTC-USD-180309/mark_price`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
instrument_id | String | 是 | 合约ID，如`BTC-USD-180213`,`BTC-USDT-191227`  
  
##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
instrument_id | String | 合约ID，如`BTC-USD-180213`  
mark_price | String | 指定合约品种的标记价格  
timestamp | String | 返回请求时间  
  
##### 解释说明

为了防止个别用户恶意操控市场导致合约价格波动剧烈，我们根据现货指数和合理基差设定标记价格。

##### 返回示例

    
    
    {
        "mark_price":"3.591",
        "instrument_id":"EOS-USD-190628",
        "timestamp":"2019-03-22T06:28:53.208Z"
    }
    

### 公共-获取强平单

获取合约强平单，此接口为公共接口，不需要身份验证。

##### 限速规则：20次/2s （根据underlying，分别限速）

##### HTTP请求

`GET/api/futures/v3/instruments/<instrument_id>/liquidation`

##### 请求示例

`GET/api/futures/v3/instruments/BTC-USD-180309/liquidation?status=0&limit=50`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
instrument_id | String | 是 | 合约ID，如`BTC-USD-180213`,`BTC-USDT-191227`  
status | String | 是 | 状态  
`0`：最近7天未成交  
`1`：最近7天已成交  
limit | String | 否 | 分页返回的结果集数量，默认为`100`，最大为`100`，按时间倒序排列，越晚的在前面  
from | String | 否 | 请求此id之前（更旧的数据）的分页内容，例如 2  
to | String | 否 | 请求此id之后（更新的数据）的分页内容 例如 3  
  
##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
instrument_id | String | 合约ID，如`BTC-USD-180213`,`BTC-USDT-191227`  
size | String | 数量  
created_at | Date | 强平单的委托时间  
loss | String | 穿仓用户亏损  
price | String | 订单价格  
type | String | 订单类型  
`3`:平多  
`4`:平空  
  
##### 返回示例

    
    
    [
        {
            "loss":"0.0",
            "size":"945",
            "price":"5.623",
            "created_at":"2018-10-21T01:20:18.0Z",
            "instrument_id":"EOS-USD-181026",
            "type":"1"
        },
        {
            "loss":"0",
            "size":"37",
            "price":"5.623",
            "created_at":"2018-10-21T01:20:18.0Z",
            "instrument_id":"EOS-USD-181026",
            "type":"1"
        }
    ]
    

### 公共-获取历史结算/交割记录

获取历史结算/交割记录

##### 限速规则：1次/60s

##### HTTP请求

`GET/api/futures/v3/settlement/history`

##### 请求示例

`GET/api/futures/v3/settlement/history`

##### 请求参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
instrument_id | String | 是 | 合约ID，如BTC-USD-180213  
start | String | 否 | 开始时间（ISO 8601标准，例如：2020-03-08T08:00:00Z）  
limit | String | 否 | 每一页100条  
end | String | 否 | 结束时间（ISO 8601标准，例如：2020-03-10T08:00:00Z）  
  
##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
instrument_id | String | 合约ID，如BTC-USD-180213  
type | String | 交割：delivery 结算：settlement  
settlement_price | String | 交割/结算价格  
clawback_loss | String | 穿仓用户亏损分摊  
reserve | String | 准备金分摊  
clawback_rate | String | 分摊比例 如 0 ，0.01（1%）  
timestamp | String | 交割/结算日期  
  
##### 返回示例

    
    
    [
        {
            "instrument_id": "btc-usd-180213",
            "type": "settlement",
            "settlement_price": "7923.88",
            "clawback_loss": "0.0",
            "reserve": "0.0252",
            "clawback_rate": "0.0",
            "timestamp": "2020-03-09T08:00:21.000Z"
        },
        {
            "instrument_id": "btc-usd-180213",
            "type": "settlement",
            "settlement_price": "8804.51",
            "clawback_loss": "0.0",
            "reserve": "0.0",
            "clawback_rate": "0.0",
            "timestamp": "2020-03-08T08:00:20.000Z"
        }
    ]
    

### 永续合约API

永续合约交易的行情信息，账户信息，订单操作，订单查询，账单明细查询。

### 所有合约持仓信息

获取账户所有合约的持仓信息。请求此接口，会在数据库遍历所有币对下的持仓数据，有大量的性能消耗,请求频率较低。建议用户传合约ID获取持仓信息。

##### 限速规则：1次/10s

##### HTTP请求

`GET/api/swap/v3/position`

##### 请求示例

`GET/api/swap/v3/position`

##### 返回参数

全仓

**全 仓参数名** | **参 数类型** | **描 述**  
---|---|---  
margin_mode | String | 仓位模式：全仓`crossed`  
liquidation_price | String | 预估强平价  
position | String | 持仓数量  
avail_position | String | 可平数量  
margin | String | 保证金  
avg_cost | String | 开仓平均价  
settlement_price | String | 结算基准价  
instrument_id | String | 合约名称  
leverage | String | 杠杆  
realized_pnl | String | 已实现盈亏  
side | String | 方向  
timestamp | String | 创建时间  
maint_margin_ratio | String | 维持保证金率  
settled_pnl | String | 已结算收益  
last | String | 最新成交价  
unrealized_pnl | String | 未实现盈亏  
  
逐仓

**逐 仓参数名** | **参 数类型** | **描 述**  
---|---|---  
margin_mode | String | 仓位模式：逐仓`fixed`  
liquidation_price | String | 预估强平价  
position | String | 持仓数量  
avail_position | String | 可平数量  
margin | String | 保证金  
avg_cost | String | 开仓平均价  
settlement_price | String | 结算基准价  
instrument_id | String | 合约名称  
leverage | String | 杠杆  
realized_pnl | String | 已实现盈亏  
side | String | 方向  
timestamp | String | 创建时间  
maint_margin_ratio | String | 维持保证金率  
settled_pnl | String | 已结算收益  
last | String | 最新成交价  
unrealized_pnl | String | 未实现盈亏  
  
##### 返回示例

    
    
    [
        {
            "margin_mode": "fixed",
            "timestamp": "2019-09-27T03:47:37.230Z",
            "holding": [
                {
                    "avail_position": "20",
                    "avg_cost": "8025.0",
                    "instrument_id": "BTC-USD-SWAP",
                    "last": "8099.8",
                    "leverage": "15.00",
                    "liquidation_price": "7002.6",
                    "maint_margin_ratio": "0.0050",
                    "margin": "0.0454",
                    "position": "20",
                    "realized_pnl": "-0.0001",
                    "settled_pnl": "0.0076",
                    "settlement_price": "8279.2",
                    "side": "long",
                    "timestamp": "2019-09-27T03:47:37.230Z",
                    "unrealized_pnl": "0"
                }
            ]
        },
        {
            "margin_mode": "crossed",
            "timestamp": "2019-09-27T03:49:02.018Z",
            "holding": [
                {
                    "avail_position": "3",
                    "avg_cost": "59.49",
                    "instrument_id": "LTC-USD-SWAP",
                    "last": "55.79",
                    "leverage": "10.00",
                    "liquidation_price": "4.37",
                    "maint_margin_ratio": "0.0100",
                    "margin": "0.0537",
                    "position": "3",
                    "realized_pnl": "0.0000",
                    "settled_pnl": "-0.0330",
                    "settlement_price": "55.84",
                    "side": "long",
                    "timestamp": "2019-09-27T03:49:02.018Z",
                    "unrealized_pnl": "0"
                },
            ] 
        }
    ]
    

### 单个合约持仓信息

获取某个合约的持仓信息

##### 限速规则：20次/2s

##### HTTP请求

`GET/api/swap/v3/<instrument_id>/position`

##### 请求示例

`GET/api/swap/v3/BTC-USD-SWAP/position`

##### 请求参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
instrument_id | String | 是 | 合约名称，如`BTC-USD-SWAP,BTC-USDT-SWAP`  
  
##### 返回参数

全仓

**全 仓参数名** | **参 数类型** | **描 述**  
---|---|---  
margin_mode | String | 仓位模式：全仓`crossed`  
liquidation_price | String | 预估强平价  
position | String | 持仓数量  
avail_position | String | 可平数量  
margin | String | 保证金  
avg_cost | String | 开仓平均价  
settlement_price | String | 结算基准价  
instrument_id | String | 合约名称  
leverage | String | 杠杆  
realized_pnl | String | 已实现盈亏  
side | String | 方向  
timestamp | String | 最近一次加减仓的更新时间  
maint_margin_ratio | String | 维持保证金率  
settled_pnl | String | 已结算收益  
last | String | 最新成交价  
unrealized_pnl | String | 未实现盈亏  
  
逐仓

**逐 仓参数名** | **参 数类型** | **描 述**  
---|---|---  
margin_mode | String | 仓位模式：逐仓`fixed`  
liquidation_price | String | 预估强平价  
position | String | 持仓数量  
avail_position | String | 可平数量  
margin | String | 保证金  
avg_cost | String | 开仓平均价  
settlement_price | String | 结算基准价  
instrument_id | String | 合约名称  
leverage | String | 杠杆  
realized_pnl | String | 已实现盈亏  
side | String | 方向  
timestamp | String | 最近一次加减仓的更新时间  
maint_margin_ratio | String | 维持保证金率  
settled_pnl | String | 已结算收益  
last | String | 最新成交价  
unrealized_pnl | String | 未实现盈亏  
  
##### 返回示例

    
    
    {
        "margin_mode": "fixed",
        "timestamp": "2019-09-27T03:47:37.230Z",
        "holding": [
            {
                "avail_position": "20",
                "avg_cost": "8025.0",
                "instrument_id": "BTC-USD-SWAP",
                "last": "8113.1",
                "leverage": "15.00",
                "liquidation_price": "7002.6",
                "maint_margin_ratio": "0.0050",
                "margin": "0.0454",
                "position": "20",
                "realized_pnl": "-0.0001",
                "settled_pnl": "0.0076",
                "settlement_price": "8279.2",
                "side": "long",
                "timestamp": "2019-09-27T03:47:37.230Z",
                "unrealized_pnl": "0"
            }
        ]
    }
    
    {
        "margin_mode": "crossed",
        "timestamp": "2019-09-27T03:49:02.018Z",
        "holding": [
            {
                "avail_position": "3",
                "avg_cost": "59.49",
                "instrument_id": "LTC-USD-SWAP",
                "last": "55.98",
                "leverage": "10.00",
                "liquidation_price": "4.37",
                "maint_margin_ratio": "0.0100",
                "margin": "0.0536",
                "position": "3",
                "realized_pnl": "0.0000",
                "settled_pnl": "-0.0330",
                "settlement_price": "55.84",
                "side": "long",
                "timestamp": "2019-09-27T03:49:02.018Z",
                "unrealized_pnl": "0"
            },
        ]
    }
    

### 所有币种合约账户信息

获取所有币种合约的账户信息，当用户没有持仓时，保证金率为10000

##### 限速规则：1次/10s

##### HTTP请求

`GET/api/swap/v3/accounts`

##### 请求示例

`GET/api/swap/v3/accounts`

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
currency | String | 账户余额币种  
underlying | string | 标的指数，如：BTC-USD，BTC-USDT  
equity | String | 账户权益  
total_avail_balance | String | 账户余额  
fixed_balance | String | 逐仓账户余额  
margin | String | 已用保证金  
realized_pnl | String | 已实现盈亏  
unrealized_pnl | String | 未实现盈亏  
margin_ratio | String | 保证金率  
instrument_id | String | 合约名称  
margin_frozen | String | 开仓冻结保证金  
timestamp | String | 创建时间  
margin_mode | String | 仓位模式  
全仓：`crossed`  
逐仓：`fixed`  
maint_margin_ratio | String | 维持保证金率  
max_withdraw | String | 可划转数量  
  
##### 解释说明

所有持仓/所有账户信息，没有持仓/持币时返回空数组；单个持仓/单个账户信息没有持仓/持币时返回各字段均为默认值；

逐仓：

账户权益：账户权益=账户余额+逐仓仓位账户余额+所有合约的已实现盈亏+所有合约的未实现盈亏

全仓：

账户权益=账户余额+所有合约的已实现盈亏+所有合约的未实现盈亏

##### 返回示例

    
    
    {
        "info": [
            {
                "equity": "0.0446",
                "fixed_balance": "0.0461",
                "instrument_id": "BTC-USD-SWAP",
                "maint_margin_ratio": "0.0000",
                "margin": "0.0454",
                "margin_frozen": "0.0000",
                "margin_mode": "fixed",
                "margin_ratio": "0.0000",
                "realized_pnl": "-0.0001",
                "timestamp": "2019-09-27T03:47:37.230Z",
                "total_avail_balance": "0.0033",
                "unrealized_pnl": "-0.0049"
                "max_withdraw": "0.0033"
            },
            {
                "equity": "0.1371",
                "fixed_balance": "0.0000",
                "instrument_id": "LTC-USD-SWAP",
                "maint_margin_ratio": "0.0100",
                "margin": "0.1071",
                "margin_frozen": "0.0000",
                "margin_mode": "crossed",
                "margin_ratio": "0.1280",
                "realized_pnl": "0.0000",
                "timestamp": "2019-09-27T03:49:02.018Z",
                "total_avail_balance": "0.1371",
                "unrealized_pnl": "0.0000"
                "max_withdraw": "0.0033"
            },
            {
                "equity": "0.1124",
                "fixed_balance": "0.0000",
                "instrument_id": "EOS-USD-SWAP",
                "maint_margin_ratio": "0.0100",
                "margin": "0.1367",
                "margin_frozen": "0.0000",
                "margin_mode": "crossed",
                "margin_ratio": "0.0164",
                "realized_pnl": "0.0000",
                "timestamp": "2019-08-27T02:05:29.651Z",
                "total_avail_balance": "0.1124",
                "unrealized_pnl": "0.0000"
                "max_withdraw": "0.0033"
            }
        ]
    }
    

### 单个币种合约账户信息

获取单个币种合约的账户信息，当用户没有持仓时，保证金率为10000

##### 限速规则：20次/2s

##### HTTP请求

`GET/api/swap/v3/<instrument_id>/accounts`

##### 请求示例

`GET/api/swap/v3/BTC-USD-SWAP/accounts`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
instrument_id | String | 是 | 合约名称，如`BTC-USD-SWAP,BTC-USDT-SWAP`  
  
##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
currency | String | 账户余额币种  
underlying | string | 标的指数，如：BTC-USD，BTC-USDT  
equity | String | 账户权益  
fixed_balance | String | 逐仓账户余额  
total_avail_balance | String | 账户余额  
margin | String | 已用保证金  
realized_pnl | String | 已实现盈亏  
unrealized_pnl | String | 未实现盈亏  
margin_ratio | String | 保证金率  
instrument_id | String | 合约名称  
margin_frozen | String | 开仓冻结保证金  
timestamp | String | 创建时间  
margin_mode | String | 仓位模式  
全仓：`crossed`  
逐仓：`fixed`  
maint_margin_ratio | String | 维持保证金率  
max_withdraw | String | 可划转数量  
  
##### 解释说明

所有持仓/所有账户信息，没有持仓/持币时返回空JSON；单个持仓/单个账户信息没有持仓/持币时返回各字段均为默认值

逐仓：

账户权益：账户权益=账户余额+逐仓仓位账户余额+所有合约的已实现盈亏+所有合约的未实现盈亏

全仓：

账户权益=账户余额+所有合约的已实现盈亏+所有合约的未实现盈亏

##### 返回示例

    
    
    {
        "info": {
            "equity": "0.0444",
            "fixed_balance": "0.0461",
            "instrument_id": "BTC-USD-SWAP",
            "maint_margin_ratio": "0.0000",
            "margin": "0.0454",
            "margin_frozen": "0.0000",
            "margin_mode": "fixed",
            "margin_ratio": "0.0000",
            "realized_pnl": "-0.0001",
            "timestamp": "2019-09-27T03:47:37.230Z",
            "total_avail_balance": "0.0033",
            "unrealized_pnl": "-0.0051"
            "max_withdraw": "0.0033"
        }
    }
    

### 获取某个合约的用户配置

获取某个合约的杠杆倍数，持仓模式

##### 限速规则：5次/2s

##### HTTP请求

`GET/api/swap/v3/accounts/<instrument_id>/settings`

##### 请求示例

`GET/api/swap/v3/accounts/BTC-USD-SWAP/settings`

##### 请求参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
instrument_id | String | 是 | 合约名称，如`BTC-USD-SWAP,BTC-USDT-SWAP`  
  
##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
long_leverage | String | 多仓杠杆  
margin_mode | String | 持仓模式  
short_leverage | String | 空仓杠杆  
instrument_id | String | 合约名称  
  
##### 解释说明

全仓同一个合约只允许有一种杠杆倍数，逐仓同一个合约同一个方向只能用一种杠杆倍数。

##### 返回示例

    
    
    {
        "long_leverage":"5.0000",
        "short_leverage":"5.0000",
        "margin_mode":"crossed",
        "instrument_id":"BTC-USD-SWAP"
    }
    

### 设定某个合约的杠杆

设定某个合约的杠杆倍数

##### 限速规则：5次/2s

##### HTTP请求

`POST /api/swap/v3/accounts/<instrument_id>/leverage`

##### 请求示例

`POST /api/swap/v3/accounts/BTC-USD-SWAP/leverage{"leverage": "10","side":
"1"}`

##### 请求参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
instrument_id | String | 是 | 合约名称，如`BTC-USD-SWAP,BTC-USDT-SWAP`  
leverage | String | 是 | 杠杆倍数，填写`1-100`的数值  
side | String | 是 | 方向  
`1`:逐仓-多仓  
`2`:逐仓-空仓  
`3`:全仓  
  
##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
long_leverage | String | 多仓杠杆  
margin_mode | String | 持仓模式  
short_leverage | String | 空仓杠杆  
instrument_id | String | 合约名称  
  
##### 返回示例

    
    
    {
        "long_leverage":"10.0000",
        "short_leverage":"10.0000",
        "margin_mode":"crossed",
        "instrument_id":"BTC-USD-SWAP"
    }
    

### 账单流水查询

列出账户资产流水，账户资产流水是指导致账户余额增加或减少的行为。流水会分页，每页100条数据，并且按照时间倒序排序和存储，最新的排在最前面。
本接口能查询最近7天的数据。

##### 限速规则：5次/2s

##### HTTP请求

`GET/api/swap/v3/accounts/<instrument_id>/ledger`

##### 请求示例

`GET/api/swap/v3/accounts/BTC-USD-SWAP/ledger?after=2&limit=30`

注：`after=2&limit=30`代表在第2页请求30条数据，返回结果为第2页的30条最近的数据

##### 请求参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
instrument_id | String | 是 | 合约名称，如`BTC-USD-SWAP,BTC-USDT-SWAP`  
after | String | 否 | 请求此id之前（更旧的数据）的分页内容，传的值为对应接口的`ledger_id`  
before | String | 否 | 请求此id之后（更新的数据）的分页内容，传的值为对应接口的`ledger_id` |  
limit | String | 否 | 分页返回的结果集数量，最大为100，不填默认返回100条  
type | String | 否 | `1`. 开多  
`2`. 开空  
`3`. 平多  
`4`. 平空  
`5`.转入  
`6`.转出  
`7`.清算未实现  
`8`.分摊  
`9`.剩余拨付  
`10`.强平多  
`11`.强平空  
`14`.资金费  
`15`.手动追加  
`16`.手动减少  
`17`.自动追加  
`18`.修改持仓模式  
`19`.强减多  
`20`.强减空  
`21`.用户调低杠杆追加保证金  
`22`.清算已实现  
  
##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
ledger_id | String | 账单id  
amount | String | 变动金额  
type | String | 账单类型  
fee | String | 手续费  
timestamp | String | 账单创建时间  
instrument_id | String | 合约ID  
currency | String | 币种，如：`btc`  
details | String |
如果`type`是`trade`，则会有该`details`字段将包含`order`，`instrument`信息,如果`type`是`transfer`，则会有该`details`字段将包含`from`，`to`信息  
order_id | String | 订单的ID  
from | String | 转出账户  
`1`:币币账户  
`3`:交割合约  
`4`:法币账户  
`5`:币币杠杆账户  
`6`:资金账户  
`8`:余币宝账户  
`9`:永续合约账户  
`12`:期权合约  
`14`:挖矿账户  
`17`:借贷账户  
to | String | 转入账户  
`1`:币币账户  
`3`:交割合约  
`4`:法币账户  
`5`:币币杠杆账户  
`6`:资金账户  
`8`:余币宝账户  
`9`:永续合约账户  
`12`:期权合约  
`14`:挖矿账户  
`17`:借贷账户  
balance | String | 开仓平仓的张数（开仓为正数，平仓为负数，当`type`是`fee`时，`balance`为`0`）  
**流 水来源类型** | **参 数类型** | **描 述**  
---|---|---  
transfer | String | 转入/转出  
match | String | 交易产生的资金变动  
settlement | String | 清算/分摊  
liquidation | String | 强平/减仓  
funding | String | 资金费  
margin | String | 修改保证金的资金变动  
  
##### 返回示例

    
    
    [
         {
             "amount": "0.000011",
             "balance": "0",
             "fee": "0.000000",
             "currency": "BTC",
             "details": {
                 "instrument_id": "BTC-USD-SWAP",
                 "order_id": ""
             },
             "type": "funding",
             "instrument_id": "BTC-USD-SWAP",
             "ledger_id": "336890402630811792",
             "timestamp": "2019-10-03T16:00:00.000Z"
         },
         {
             "amount": "0.001812",
             "balance": "0",
             "fee": "0.000000",
             "currency": "BTC",
             "details": {
                 "instrument_id": "BTC-USD-SWAP",
                 "order_id": ""
             },
             "type": "settlement",
             "instrument_id": "BTC-USD-SWAP",
             "ledger_id": "336648803103555621",
             "timestamp": "2019-10-03T08:00:00.000Z"
         },
    ]
    

### 下单

API交易提供限价单下单模式，只有当您的账户有足够的资金才能下单。一旦下单，您的账户资金将在订单生命周期内被冻结，被冻结的资金以及数量取决于订单指定的类型和参数。目前api下单只支持以美元为计价单位

**[永续合约委托说明](https://www.okex.me/support/hc/zh-cn/articles/360037140632)**

##### 限速规则：40次/2s （1）不同合约之间限速不累计；2）同一合约的币本位和USDT保证金之间限速不累计）

##### HTTP请求

`POST /api/swap/v3/order`

##### 请求示例

`POST
/api/swap/v3/order{"client_oid":"e12233456","size":"2","order_type":"1","type":"1","match_price":"0","price":"432.11","instrument_id":"BTC-
USD-SWAP"}`

##### 请求参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
client_oid | String | 否 | 由您设置的订单ID来识别您的订单,格式是字母（区分大小写）+数字 或者
纯字母（区分大小写），1-32位字符 （不能重复）  
size | String | 是 | 下单数量，买入或卖出合约的数量（以张计数）  
type | String | 是 | 可填参数：  
`1`:开多  
`2`:开空  
`3`:平多  
`4`:平空  
order_type | String | 否 | 参数填数字  
`0`：普通委托（`order_type`不填或填`0`都是普通委托）  
`1`：只做Maker（Post only）  
`2`：全部成交或立即取消（FOK）  
`3`：立即成交并取消剩余（IOC）  
`4`：市价委托  
match_price | String | 否 | 是否以对手价下单。  
`0`:不是; `1`:是。当以对手价下单，`order_type`只能选择`0`（普通委托）  
price | String | 否 | 委托价格  
instrument_id | String | 是 | 合约名称，如`BTC-USD-SWAP,BTC-USDT-SWAP`  
  
请求参数校验:合约名称必须是已存在合约名称；委托价格必须符合下单成交价格(不能达到溢价和强平价)；下单类型除了`1`:开多; `2`:开空; `3`:平多;
`4`:平空都会报错；数量不能小于等于零，不能大于可开张数。

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
order_id | String | 订单id，下单失败时，此字段值为`-1`  
client_oid | String | 由您设置的订单id来标识您的订单  
error_code | String | 错误码，下单成功时为0，下单失败时会显示相应错误码  
error_message | String | 错误信息，下单成功时为空，下单失败时会显示错误信息  
result | String | 调用接口返回结果  
  
##### 解释说明

如果error_code的返回值不为0，说明请求校验失败并被拒绝

instrument_id

`instrument_id`必须是有效的合约ID。合约列表可通过/ instruments接口获取。

client_oid

`client_oid`用户需要自己保证此ID不重复，OKEx不会进行排重提示，如有重复，撤单和查询订单时只能撤销或者查询最新的一条数据。

type

下单时，您可以指定订单类型。在您没有持仓时，只能选择开多和开空。您只能对持仓合约进行平仓。

price

`price`表示买入或卖出每张合约的价格。价格必须是价格步长`tick_size`的倍数。价格步长`tick_size`是价格的最小增量，可通过/instruments接口获取。

size

`size`表示买入或卖出合约的张数。数量必须是整数。

match_price

对手价表示你希望以目前对手方的最优价格成交。如果你下的是买单，选择以对手价下单表示你用当前卖一价进行下单。如果你下的是卖单，选择以对手价下单表示你用当前买一价进行下单。

订单生命周期

HTTP请求将在订单被拒绝（资金不足，参数无效等）或下单成功（由匹配引擎接受）时作出响应。一个200响应表示该订单被接收并且进入撮合。进入撮合的订单可以部分或全部立即成交（取决于价格和市场条件）。部分成交的时候将把订单的剩余数量继续进行撮合。完全成交的订单将进入已成交状态。

监听行情数据的用户建议使用`client_oid`字段以便在接受到的信息中标识对应的数据。

响应

成功接受的订单将被分配一个订单ID。成功接受的订单表示撮合引擎已经接受的订单。

未成交的订单不会过期，并将保持撮合状态，直到被成交或取消。

##### 返回示例

    
    
    {
        "error_message":"",
        "result":"true",
        "error_code":"0",
        "client_oid":"oktswap6",
        "order_id":"6a-d-54dcc6543-0"
    }
    

### 批量下单

批量进行下单请求，每个合约可批量下10个单。 **[永续合约委托说明](https://www.okex.me/support/hc/zh-
cn/articles/360037140632)**

##### 限速规则：20次/2s （1）不同合约之间限速不累计；2）同一合约的币本位和USDT保证金之间限速不累计）

##### HTTP请求

`POST /api/swap/v3/orders`

##### 请求示例

`POST /api/swap/v3/orders{"instrument_id": "EOS-USD-
SWAP","order_data":[{"client_oid": "oktswap14", "type": "1", "price":
"3.2571000000000003", "size": "1", "match_price": "0"}, {"client_oid":
"oktswap15", "type": "1", "price": "3.2571000000000003", "size": "1",
"match_price": "0"}]}`

##### 请求参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
order_data | List | 是 | JSON类型的字符串  
例：`[{"order_type":"0","client_oid": "E213","price": "5","size": "2","type":
"1","match_price": "0"},{"order_type":"0","client_oid": "243","price":
"2","size": "3","type": "2","match_price": "1"}]`  
最大下单量为20，当以对手价下单，`order_type`只能选择`0`（普通委托）  
client_oid | String | 否 | 由您设置的订单ID来识别您的订单,格式是字母（区分大小写）+数字 或者
纯字母（区分大小写），1-32位字符 （不能重复）  
size | String | 是 | 下单数量  
price | String | 是 | 委托价格  
type | String | 是 | 可填参数：  
`1`:开多  
`2`:开空  
`3`:平多  
`4`:平空  
match_price | String | 否 | 是否以对手价下单  
`0`:不是; `1`:是。当以对手价下单，`order_type`只能选择`0`（普通委托）  
order_type | String | 否 | 参数填数字  
`0`：普通委托（`order_type`不填或填`0`都是普通委托）  
`1`：只做Maker（Post only）  
`2`：全部成交或立即取消（FOK）  
`3`：立即成交并取消剩余（IOC）  
`4`：市价委托  
instrument_id | String | 是 | 合约名称，如`BTC-USD-SWAP,BTC-USDT-SWAP`  
  
请求参数的校验和单个订单一致。

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
order_id | String | 订单id，下单失败时，此字段值为`-1`  
client_oid | String | 由您设置的订单id来标识您的订单  
error_code | String | 错误码，下单成功时为0，下单失败时会显示相应错误码  
error_message | String | 错误信息，下单成功时为空，下单失败时会显示错误信息  
result | String | 调用接口返回结果  
  
##### 解释说明

如果error_code的返回值不为0，说明请求校验失败并被拒绝

`client_oid`用户需要自己保证此ID不重复，OKEx不会进行排重提示，如有重复，撤单和查询订单时只能撤销或者查询最新的一条数据。

`result`是代表服务器处理了请求，不代表下单、撤单是否成功。

返回的结果数据和`order_data`提交订单数据顺序一致。如果下单失败，则`order_id`为`-1`，`error_code`是错误码提示，`error_message`是错误信息。

##### 返回示例

    
    
    {
        "order_info":[
            {
                "client_oid":"oktswap14",
                "error_code":"0",
                "error_message":"",
                "order_id":"6a-d-54df9a2ac-0"
                "result": "true"
            },
            {
                "client_oid":"oktswap15",
                "error_code":"0",
                "error_message":"",
                "order_id":"6a-d-54df9a2ad-0"
                "result": "true"
            }
        ],
        "result":"true"
    }
    

### 撤单

撤销之前下的未完成订单。

##### 限速规则：40次/2s （1）不同合约之间限速不累计；2）同一合约的币本位和USDT保证金之间限速不累计）

##### HTTP请求

`POST /api/swap/v3/cancel_order/<instrument_id>/<order_id> or <client_oid>`

##### 请求示例

`POST /api/swap/v3/cancel_order/BTC-USD-SWAP/50072329722368`

或

`POST /api/swap/v3/cancel_order/BTC-USD-SWAP/64er`

##### 请求参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
order_id | String | 非必填 | `order_id`和`client_oid`必须且只能选一个填写，订单id  
instrument_id | String | 是 | 合约名称，如`BTC-USD-SWAP,BTC-USDT-SWAP`  
client_oid | String | 非必填 | `order_id`和`client_oid`必须且只能选一个填写，由您设置的订单ID来识别您的订单
, 类型为字母（大小写）+数字或者纯字母（大小写）1-32位字符  
  
请求参数校验：合约名称必须是已存在合约的名称；`order_id`必须是已存在的`order_id`。

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
order_id | String | 订单id  
result | String | 撤单申请结果  
client_oid | String | 由您设置的订单ID来识别您的订单  
error_code | String | 错误码，撤单成功时为0，撤单失败时会显示相应错误码  
error_message | String | 错误信息，撤单成功时为空，撤单失败时会显示错误信息  
  
##### 解释说明

使用`client_oid`撤单时，用户需要自己保证此ID不重复，OKEx不会进行排重提示，如有重复，撤单时只能撤销最新的一条数据

`order_id`和`client_oid`必须且只能选一个填写

这`order_id`是服务器分配的订单ID，而不是用户传的的`client_oid`。

返回值是已发起撤销操作的订单ID，不代表这些订单已成功撤销，正在成交中的无法撤销，未成交的可成功撤销。

`result`是代表服务器处理了请求，不代表下单、撤单是否成功。

如果订单无法取消（已经成交或已取消），那么返回的报错内容里将显示相应的原因。

##### 返回示例

    
    
    {
        "result":"true",
        "client_oid":"oktswap6",
        "order_id":"6a-d-54dcc6543-0",
        "error_message": "",
        "error_code": "0"
    }
    

### 批量撤单

撤销之前下的未完成订单，每个币对可批量撤10个单。

##### 限速规则：20次/2s （1）不同合约之间限速不累计；2）同一合约的币本位和USDT保证金之间限速不累计）

##### HTTP请求

`POST /api/swap/v3/cancel_batch_orders/<instrument_id>`

##### 请求示例

`POST /api/swap/v3/cancel_batch_orders/BTC-USD-
SWAP{"ids":["500723297223680","50072329722368","5007232972236801"]}`

或

`POST /api/swap/v3/cancel_batch_orders/BTC-USD-
SWAP{"client_oids":["6EEE33","643RE","64REE"]}`

##### 请求参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
ids | List<String> | 非必填 | `order_id`和`client_oid`必须且只能选一个填写，订单id列表  
instrument_id | String | 是 | 合约名称，如`BTC-USD-SWAP,BTC-USDT-SWAP`  
client_oids | List<String> | 非必填 |
`order_id`和`client_oid`必须且只能选一个填写，由您设置的订单ID来识别您的订单，类型为字母（大小写）+数字或者纯字母（大小写），1-32位字符  
  
请求参数校验和单个订单撤销一致。

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
instrument_id | String | 合约名称，如`BTC-USD-SWAP`  
ids | String | 订单id列表  
result | String | 撤单申请结果  
error_code | String | 错误码，撤单成功时为0，撤单失败时会显示相应错误码  
error_message | String | 错误信息，撤单成功时为空，撤单失败时会显示错误信息  
  
##### 返回参数

返回值是已发起撤销操作的订单ID列表，不代表这些订单已成功撤销，正在成交中的无法撤销，未成交的可成功撤销。

##### 解释说明

批量撤单时候，要么都是`order_id`要么都是`client_oid`，否则会提示错误

使用`client_oid`批量撤单时，目前只支持一个币对下撤一个`client_oid`
，用户需要自己保证此ID不重复，OKEx不会进行排重提示，如有重复，撤单时只能撤销最新的一条数据

`result`是代表服务器处理了请求，不代表下单、撤单是否成功。如果全部都撤单失败，`result`就为`false`。

无法保证一定会成功撤销，建议用户调用批量撤单接口后，再调用获取订单列表接口确认。

##### 返回示例

    
    
    1. 用order_ids批量撤单：
    
    {
        "client_oids":[
    
        ],
        "ids":[
            "500723297223680",
            "50072329722368"
            "5007232972236801"
        ],
        "instrument_id":"EOS-USD-SWAP",
        "result":"true",
        "error_message": "",
        "error_code": "0"
    }
    
    
    2. 用client_oids撤单:
    
    {
        "client_oids":[
            "oktswap16",
            "oktswap17"
        ],
        "ids":[
    
        ],
        "instrument_id":"EOS-USD-SWAP",
        "result":"true",
        "error_message": "",
        "error_code": "0"
    }
    

### 获取所有订单列表

列出您当前所有的订单信息。本接口能查询最近7天20000条数据。这个请求支持分页，并且按委托时间倒序排序和存储，最新的排在最前面。

##### 限速规则：20次/2s

##### HTTP请求

`GET/api/swap/v3/orders/<instrument_id>`

##### 请求示例

`GET/api/swap/v3/orders/EOS-USD-SWAP?state=2&after=1&limit=2`

##### 请求参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
instrument_id | String | 是 | 合约名称，如`BTC-USD-SWAP,BTC-USDT-SWAP`  
after | String | 否 | 请求此id之前（更旧的数据）的分页内容，传的值为对应接口的`order_id`  
before | String | 否 | 请求此id之后（更新的数据）的分页内容，传的值为对应接口的`order_id` |  
limit | String | 否 | 分页返回的结果集数量，最大为100，不填默认返回100条  
state | String | 是 | 订单状态  
`-2`:失败  
`-1`:撤单成功  
`0`:等待成交  
`1`:部分成交  
`2`:完全成交  
`3`:下单中  
`4`:撤单中  
`6`: 未完成（等待成交+部分成交）  
`7`:已完成（撤单成功+完全成交）  
  
##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
instrument_id | String | 合约名称，如`BTC-USD-SWAP`  
client_oid | String | 用户设置的订单ID  
size | String | 委托数量  
timestamp | String | 创建时间  
filled_qty | String | 成交数量  
fee | String | 手续费  
order_id | String | 订单id  
price | String | 委托价格  
price_avg | String | 成交均价  
type | String | `1`:开多  
`2`:开空  
`3`:平多  
`4`:平空  
contract_val | String | 合约面值  
order_type | String | `0`：普通委托  
`1`：只做Maker（Post only）  
`2`：全部成交或立即取消（FOK）  
`3`：立即成交并取消剩余（IOC）  
`4`：市价委托  
state | String | `-2`:失败  
`-1`:撤单成功  
`0`:等待成交  
`1`:部分成交  
`2`:完全成交  
`3`:下单中  
`4`:撤单中  
trigger_price | String | 强平的真实触发价格，仅强平单会返回此字段  
leverage | String | 杠杆倍数  
  
##### 解释说明

`status`为`state`旧版参数，会短期兼容，建议尽早切换`state`。

`client_oid`的类型为字母（大小写）+数字或者纯字母（大小写），1-32位字符
，用户需要自己保证此ID不重复，OKEx不会进行排重提示，如有重复，查询订单时只能查询出最新的一条数据。

最新的定义为 先从未成交表查，如果未成交表没有，再查已成交表的最新数据。

##### 返回示例

    
    
    {
        "order_info":[
            {
                "client_oid":"",
                "contract_val":"10",
                "fee":"-0.000551",
                "filled_qty":"1",
                "instrument_id":"EOS-USD-SWAP",
                "order_id":"6a-7-54d663a28-0",
                "order_type":"0",
                "price":"3.633",
                "price_avg":"3.633",
                "size":"1",
                "state":"2",
                "status":"2",
                "timestamp":"2019-03-25T05:56:21.674Z",
                "trigger_price": "0.0",
                "leverage": "10",
                "type":"4"
            },
            {
                "client_oid":"",
                "contract_val":"10",
                "fee":"-0.000550",
                "filled_qty":"1",
                "instrument_id":"EOS-USD-SWAP",
                "order_id":"6a-8-54cee3a3f-0",
                "order_type":"0",
                "price":"3.640",
                "price_avg":"3.640",
                "size":"1",
                "state":"2",
                "status":"2",
                "timestamp":"2019-03-25T03:45:17.376Z",
                "trigger_price": "0.0",
                "leverage": "10",
                "type":"2"
            }
        ]
    }
    

### 获取订单信息

通过订单id获取单个订单信息。本接口只能查询最近7天的已成交和已撤销订单信息。已撤销的未成交单只保留2个小时。

##### 限速规则：10次/2s

##### HTTP请求

`GET/api/swap/v3/orders/<instrument_id>/<order_id>`

或

`GET/api/swap/v3/orders/<instrument_id>/<client_oid>`

##### 请求示例

`GET/api/swap/v3/orders/BTC-USD-SWAP/64-2a-26132f931-3`

或

`GET/api/swap/v3/orders/BTC-USD-SWAP/64rt`

##### 请求参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
order_id | String | 否 | 订单id , `order_id`和`client_oid`必须且只能选一个填写  
instrument_id | String | 是 | 合约名称，如`BTC-USD-SWAP,BTC-USDT-SWAP`  
client_oid | String | 否 | `order_id`和`client_oid`必须且只能选一个填写 . 由您设置的订单ID来识别您的订单
, 类型为字母（大小写）+数字或者纯字母（大小写）1-32位字符  
  
##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
instrument_id | String | 合约名称，如`BTC-USD-SWAP`  
client_oid | String | 由您设置的订单ID来识别您的订单  
size | String | 委托数量  
timestamp | String | 创建时间  
filled_qty | String | 成交数量  
fee | String | 手续费  
order_id | String | 订单id  
price | String | 委托价格  
price_avg | String | 成交均价  
type | String | `1`:开多  
`2`:开空  
`3`:平多  
`4`:平空  
contract_val | String | 合约面值  
order_type | String | `0`：普通委托  
`1`：只做Maker（Post only）  
`2`：全部成交或立即取消（FOK）  
`3`：立即成交并取消剩余（IOC）  
`4`：市价委托  
state | String | `-2`:失败  
`-1`:撤单成功  
`0`:等待成交  
`1`:部分成交  
`2`:完全成交  
`3`:下单中  
`4`:撤单中  
trigger_price | String | 强平的真实触发价格，仅强平单会返回此字段  
leverage | String | 杠杆倍数  
  
##### 解释说明

`status`为`state`旧版参数，会短期兼容，建议尽早切换`state`。

`client_oid`的类型为字母（大小写）+数字或者纯字母（大小写），1-32位字符
，用户需要自己保证此ID不重复，OKEx不会进行排重提示，如有重复，查询订单时只能查询出最新的一条数据。

最新的定义为 先从未成交表查，如果未成交表没有，再查已成交表的最新数据。

##### 返回示例

    
    
    {
        "filled_qty":"1",
        "fee":"-0.000550",
        "client_oid":"",
        "price_avg":"3.640",
        "trigger_price": "0.0",
        "type":"2",
        "instrument_id":"EOS-USD-SWAP",
        "size":"1",
        "price":"3.640",
        "contract_val":"10",
        "order_id":"6a-8-54cee3a3f-0",
        "order_type":"0",
        "status":"2",
        "state":"2",
        "leverage": "10",
        "timestamp":"2019-03-25T03:45:17.376Z"
    }
    

### 获取成交明细

获取最近的成交明细列表，本接口能查询最近7天的数据。

##### 限速规则：10次/2s

##### HTTP请求

`GET/api/swap/v3/fills`

##### 请求示例

`GET/api/swap/v3/fills?order_id=650072329722368&instrument_id=BTC-USD-
SWAP&after=1&limit=50`

（返回`BTC-USD-SWAP`中`order_id`为`50072329722368`的订单中第1页前50笔成交信息）

##### 请求参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
order_id | String | 否 | 订单ID，不填写`order_id`，返回当前`instrument_id`下的所有订单成交明细  
instrument_id | String | 是 | 合约名称，如`BTC-USD-SWAP,BTC-USDT-SWAP`  
after | String | 否 | 请求此id之前（更旧的数据）的分页内容，传的值为对应接口的`trade_id`等  
before | String | 否 | 请求此id之后（更新的数据）的分页内容，传的值为对应接口的`trade_id`等 |  
limit | String | 否 | 分页返回的结果集数量，最大为100，不填默认返回100条  
  
##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
trade_id | String | 成交id  
instrument_id | String | 合约名称，如`BTC-USD-SWAP,BTC-USDT-SWAP`  
order_id | String | 订单id  
price | String | 成交价格  
order_qty | String | 成交数量  
fee | String | 手续费  
timestamp | String | 成交时间  
exec_type | String | 流动性方向  
`T`：taker; `M`：maker  
side | String | 订单方向  
  
##### 解释说明

手续费

`fee`字段：负数的`fee`表示平台收取的手续费，正数的`fee`表示表示平台向达到指定lv交易等级的用户支付的挂单奖励（返佣）

##### 返回示例

    
    
     [
         {
             "trade_id":"197429674631450625",
             "instrument_id":"EOS-USD-SWAP",
             "order_id":"6a-7-54d663a28-0",
             "price":"3.633",
             "order_qty":"1.0000",
             "fee":"-0.000551",
             "timestamp":"2019-03-25T05:56:31.287Z",
             "exec_type":"M",
             "side":"short"
         }
     ]
    

### 获取合约挂单冻结数量

获取合约挂单冻结数量。

##### 限速规则：5次/2s

##### HTTP请求

`GET/api/swap/v3/accounts/<instrument_id>/holds`

##### 请求示例

`GET/api/swap/v3/accounts/BTC-USD-SWAP/holds`

##### 请求参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
instrument_id | String | 是 | 合约名称，如`BTC-USD-SWAP,BTC-USDT-SWAP`  
  
##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
instrument_id | String | 合约名称，如`BTC-USD-SWAP,BTC-USDT-SWAP`  
amount | String | 开仓冻结保证金  
timestamp | String | 查询时间  
  
校验合约名称，只要和数据库中的合约名称不同，就会报错

##### 返回示例

    
    
    {
        "instrument_id":"BTC-USD-SWAP",
        "amount":"303613",
        "timestamp":"2019-03-26T02:36:22.703Z"
    }
    

### 委托策略下单

委托策略下单

提供止盈止损、跟踪委托、冰山委托和时间加权委托策略

##### 限速规则：40次/2s

##### HTTP请求

`POST /api/swap/v3/order_algo`

##### 请求示例

`POST /api/swap/v3/order_algo{"instrument_id":"BTC-USD-
SWAP","type":"1","trigger_price":"432.11","order_type":"1","algo_price":"341.99","size":"2"}`（止盈止损）

##### 请求参数（通用）

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
instrument_id | String | 是 | 合约ID，如`BTC-USD-SWAP,BTC-USDT-SWAP`  
type | String | 是 | `1`:开多  
`2`:开空  
`3`:平多  
`4`:平空  
order_type | String | 是 | `1`：止盈止损  
`2`：跟踪委托  
`3`：冰山委托  
`4`：时间加权  
size | String | 是 | 委托总数（以张计数），填写值1\<=X\<=1000000的整数  
  
##### 止盈止损参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
trigger_price | String | 是 | 触发价格，填写值0\<X\<=1000000  
algo_price | String | 是 | 委托价格，填写值0\<X\<=1000000  
algo_type | String | 否 | 1:限价 2:市场价；触发价格类型，默认是限价；为市场价时，委托价格不必填；  
  
##### 跟踪委托参数 （最多同时存在10单）

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
callback_rate | String | 是 | 回调幅度，填写值0.001（0.1%）\<=X\<=0.05（5%）  
trigger_price | String | 是 | 激活价格 ，填写值0\<X\<=1000000  
  
##### 冰山委托参数 （最多同时存在6单）

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
algo_variance | String | 是 | 委托深度，填写值0.0001(0.01%)\<=X\<=0.01（1%）  
avg_amount | String | 是 | 单笔均值，填写整数  
price_limit | String | 是 | 价格限制 ，填写值0\<X\<=1000000  
  
##### 时间加权参数 （最多同时存在6单）

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
sweep_range | String | 是 | 扫单范围，填写值0.005（0.5%）\<=X\<=0.01（1%）  
sweep_ratio | String | 是 | 扫单比例，填写值 0.01\<=X\<=1  
single_limit | String | 是 | 单笔上限，填写值2\<=X\<=500  
price_limit | String | 是 | 价格限制，填写值0\<X\<=1000000  
time_interval | String | 是 | 委托间隔，填写值5\<=X\<=120  
  
#### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
result | String | 调用接口返回结果  
instrument_id | String | 合约ID，如`BTC-USD-SWAP`  
order_type | String | `1`：止盈止损  
`2`：跟踪委托  
`3`：冰山委托  
`4`：时间加权  
algo_id | String | 订单ID，下单失败时，此字段值为`-1`  
error_code | String | 错误码，下单成功时为0，下单失败时会显示相应错误码  
error_message | String | 错误信息，下单成功时为空，下单失败时会显示错误信息  
  
##### 返回示例

    
    
    {
        "error_message": "",
        "error_code": "0",
        "data": {
            "result": "success",
            "algo_id": "340286404443709440",
            "error_message": "",
            "error_code": "0",
            "instrument_id": "BTC-USD-SWAP",
            "order_type": 1
        },
        "detailMsg": ""
    }
    

### 委托策略撤单

委托策略撤单

根据指定的`algo_id`撤销某个合约的未完成订单，每次最多可撤6（冰山/时间）/10（计划/跟踪）个。

##### 限速规则：20 次/2s

##### HTTP请求

`POST /api/swap/v3/cancel_algos`

##### 请求示例

单个撤单：`POST /api/swap/v3/cancel_algos{"instrument_id":"BTC-USD-
SWAP","order_type":"1","algo_ids":["198273485"]}`

批量撤单：`POST /api/swap/v3/cancel_algos{"instrument_id":"BTC-USD-
SWAP","order_type":"1","algo_ids":["198273485","198273486"]}`

##### 请求参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
instrument_id | String | 是 | 撤销指定的合约品种  
algo_ids | List<String> | 是 | 撤销指定的委托单ID  
order_type | String | 是 | `1`：止盈止损  
`2`：跟踪委托  
`3`：冰山委托  
`4`：时间加权  
  
##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
instrument_id | String | 撤销指定的合约品种  
order_type | String | `1`：止盈止损  
`2`：跟踪委托  
`3`：冰山委托  
`4`：时间加权  
algo_ids | String | 撤销指定的委托单ID  
result | String | 调用接口返回结果  
error_code | String | 错误码，撤单成功时为0，撤单失败时会显示相应错误码  
error_message | String | 错误信息，撤单成功时为空，撤单失败时会显示错误信息  
  
返回参数

返回值是已发起撤销操作的委托单ID，不代表这些委托单已成功撤销，正在成交中的无法撤销，未成交的可成功撤销。

解释说明

无法保证一定会成功撤销，建议用户调用撤单接口后，再调用获取委托单列表接口确认。

##### 返回示例

    
    
    {
        "error_message": "",
        "error_code": "0",
        "data": {
            "result": "success",
            "algo_ids": "[340286404443709440]",
            "instrument_id": "BTC-USD-SWAP",
            "order_type": "1"
        },
        "detailMsg": ""
    }
    

### 获取委托单列表

获取委托单列表。已完成订单最多可查7天的数据，未成交订单无查询限制。

列出您当前所有的订单信息。

##### 限速规则：20次/2s

##### HTTP请求

`GET/api/swap/v3/order_algo/<instrument_id>`

##### 请求示例

`GET/api/swap/v3/order_algo/BTC-USD-SWAP?order_type=1&status=3`

##### 请求参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
instrument_id | String | 是 | 合约ID，如`BTC-USD-SWAP,BTC-USDT-SWAP`  
order_type | String | 是 | `1`：止盈止损  
`2`：跟踪委托  
`3`：冰山委托  
`4`：时间加权  
status | String | 见描述 | 【`status`和`algo_id`必填且只能填其一】  
订单状态  
`1`：待生效  
`2`：已生效  
`3`：已撤销  
`4`：部分生效  
`5`：暂停生效  
`6`：委托失败  
【只有冰山和加权有`4`、`5`状态】  
algo_id | String | 见描述 | 【`status`和`algo_id`必填且只能填其一】  
查询指定的委托单ID  
before | string | 否 | 请求此id之后（更新的数据）的分页内容  
after | string | 否 | 请求此id之前（更旧的数据）的分页内容  
limit | string | 否 | 分页返回的结果集数量，默认为`100`，最大为`100`  
  
##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
instrument_id | String | 合约ID，如`BTC-USD-SWAP`  
order_type | String | `1`：止盈止损  
`2`：跟踪委托  
`3`：冰山委托  
`4`：时间加权  
timestamp | String | 委托时间  
real_price | String | 实际委托价格  
algo_id | String | 委托单ID  
status | String | 订单状态  
`1`: 待生效  
`2`: 已生效  
`3`: 已撤销  
`4`: 部分生效  
`5`: 暂停生效  
type | String | 订单类型  
`1`:开多  
`2`:开空  
`3`:平多  
`4`:平空  
leverage | String | 杠杆倍数  
size | String | 委托数量（以张计数）,填写值1\<=X\<=1000000的整数  
algo_price | String | 策略委托价格  
trigger_price | String | 策略委托触发价格  
order_id | String | 订单id  
  
止盈止损

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
trigger_price | String | 触发价格，填写值0\<X  
algo_price | String | 委托价格，填写值0\<X\<=1000000  
real_amount | String | 实际成交数量  
algo_type | String | 1:限价 2:市场价；  
real_amount | String | 实际委托数量  
  
跟踪委托

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
callback_rate | String | 回调幅度，填写值0.001（0.1%）\<=X\<=0.05（5%）  
trigger_price | String | 激活价格 ，填写值0\<X\<=1000000  
real_amount | String | 实际委托数量  
real_amount | String | 实际委托数量  
  
冰山委托

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
algo_variance | String | 委托深度，填写值0\<=X\<=0.01（1%）  
avg_amount | String | 单笔均值，填写2-500的整数（永续2-500的整数）  
price_limit | String | 价格限制 ，填写值0\<X\<=1000000  
deal_value | String | 已成交量  
  
时间加权

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
sweep_range | String | 扫单范围，填写值0.005（0.5%）\<=X\<=0.01（1%）  
sweep_ratio | String | 扫单比例，填写值 0.01\<=X\<=1  
single_limit | String | 单笔上限，填写值10\<=X\<=2000（永续2-500的整数）  
price_limit | String | 价格限制，填写值0\<X\<=1000000  
time_interval | String | 委托间隔，填写值5\<=X\<=120  
deal_value | String | 已委托量  
  
##### 返回示例

    
    
    {
        "orderStrategyVOS": [
            {
                "algo_id": "340286404443709440",
                "algo_price": "8300.0",
                "instrument_id": "BTC-USD-SWAP",
                "leverage": "15.00",
                "order_type": "1",
                "real_amount": "0.0000",
                "real_price": "0.0",
                "size": "1.0000",
                "status": "3",
                "timestamp": "2019-10-08T08:27:20.517Z",
                "trigger_price": "8200.0",
                "type": "1"
            },
            {
                "algo_id": "337464291111936000",
                "algo_price": "9000.0",
                "instrument_id": "BTC-USD-SWAP",
                "leverage": "15.00",
                "order_type": "1",
                "real_amount": "0.0000",
                "real_price": "0.0",
                "size": "1.0000",
                "status": "3",
                "timestamp": "2019-10-04T11:00:18.392Z",
                "trigger_price": "8500.0",
                "type": "1"
            },
        ]
    }
    

### 获取账户手续费费率

获取您当前账户交易等级对应的手续费费率，母账户下的子账户的费率和母账户一致。每天凌晨0点更新一次。

此接口返回的手续费费率只适用于(BTC,ETH,EOS,BSV,BCH,LTC,ETC,XRP,TRX)，其他币种费率，请根据您的手续费等级查询[费率说明页面确认](https://www.okex.com/fees.html)

##### 限速规则：5次/2s

##### HTTP请求

`GET/api/swap/v3/trade_fee`

##### 请求示例

`2019-11-12T07:28:43.497ZGET/api/swap/v3/trade_fee`

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
taker | String | 吃单手续费率  
maker | String | 挂单手续费率  
timestamp | String | 数据返回时间  
  
备注：maker 的值：负数，代表是返佣的费率，正数，代表平台扣除的费率。（和web页面上展示的一致）

##### 返回示例

    
    
    {
        "maker": "0.0002",
        "taker": "0.0005",
        "timestamp": "2019-11-25T12:30:50.057Z"
    }
    

### 市价全平

市价全平接口，其中BTC合约持仓小于或等于999张时才能调用，否则报错；类似的，其他币种合约的持仓应该小于或等于9999张。

##### 限速规则：2次/2s （根据underlying，分别限速）

##### HTTP请求

`POST/api/swap/v3/close_position`

##### 请求示例

`POST/api/swap/v3/close_position{"instrument_id":"BTC-USD-
SWAP","direction":"long"}`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
instrument_id | String | 是 | 合约ID，如`BTC-USD-SWAP`  
direction | String | 是 | 平仓方向  
`long`:平多  
`short`:平空  
  
##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
instrument_id | String | 合约ID，如`BTC-USD-SWAP`  
direction | String | 平仓方向  
`long`:平多  
`short`:平空  
error_code | String | 错误码，下单成功时为`0`，下单失败时会显示相应错误码  
error_message | String | 错误信息，下单成功时为空，下单失败时会显示错误信息  
result | String | 调用接口返回结果  
  
##### 返回示例

    
    
    {
        "result":true,
        "error_message":"",
        "error_code":"0",
        "instrument_id":"BTC-USD-SWAP",
        "direction":"long"
    }
    

### 撤销所有平仓挂单

此接口，仅支持撤销平仓的所有挂单。不包括开仓的挂单。

##### 限速规则：5次/2s （根据underlying，分别限速）

##### HTTP请求

`POST /api/swap/v3/cancel_all`

##### 请求示例

`POST /api/swap/v3/cancel_all{"instrument_id":"BTC-USD-
SWAP","direction":"long"}`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
instrument_id | String | 是 | 合约ID，如`BTC-USD-SWAP`  
direction | String | 是 | 平仓方向  
`long`:平多  
`short`:平空  
  
##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
instrument_id | String | 是 合约ID，如`BTC-USD-SWAP`  
direction | String | 是 平仓方向  
`long`:平多  
`short`:平空  
error_code | String | 错误码，下单成功时为`0`，下单失败时会显示相应错误码  
error_message | String | 错误信息，下单成功时为空，下单失败时会显示错误信息  
result | String | 调用接口返回结果  
  
##### 返回示例

    
    
    {
        "result":true,
        "error_message":"",
        "error_code":"0",
        "instrument_id":"BTC-USD-SWAP",
        "direction":"long"
    }
    

### 公共-获取合约信息

获取可用合约的列表，这组公开接口提供了行情数据的快照，无需认证即可调用。 获取可用合约的列表，查询各合约的交易限制和价格步长等信息。

##### 限速规则：20次/2s

##### HTTP请求

`GET/api/swap/v3/instruments`

##### 请求示例

`GET/api/swap/v3/instruments`

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
instrument_id | String | 合约名称，如`BTC-USD-SWAP,BTC-USDT-SWAP`  
underlying | String | 标的指数，如：BTC-USD  
base_currency | String | 币种，如BTC  
quote_currency | String | 计价货币，如`BTC-USD-SWAP`中的USD  
settlement_currency | String | 盈亏结算和保证金币种，BTC  
contract_val | String | 合约面值  
listing | String | 上线日期  
delivery | String | 结算时间  
size_increment | String | 数量精度  
tick_size | String | 价格精度  
is_inverse | String | true or false ,是否是反向合约  
contract_val_currency | String | 合约面值计价币种  
  
##### 返回示例

    
    
    [
        {
            "instrument_id":"BTC-USD-SWAP",
            "underlying_index":"BTC",
            "quote_currency":"USD",
            "coin":"BTC",
            "contract_val":"100",
            "listing":"2018-08-28T02:43:23.000Z",
            "delivery":"2019-11-26T08:00:00.000Z",
            "size_increment":"1",
            "tick_size":"0.1",
            "base_currency":"BTC",
            "underlying":"BTC-USD",
            "settlement_currency":"BTC",
            "is_inverse":"true",
            "contract_val_currency":"USD"
        },
        {
            "instrument_id":"LTC-USD-SWAP",
            "underlying_index":"LTC",
            "quote_currency":"USD",
            "coin":"LTC",
            "contract_val":"10",
            "listing":"2018-12-21T07:53:47.000Z",
            "delivery":"2019-11-26T08:00:00.000Z",
            "size_increment":"1",
            "tick_size":"0.01",
            "base_currency":"LTC",
            "underlying":"LTC-USD",
            "settlement_currency":"LTC",
            "is_inverse":"true",
            "contract_val_currency":"USD"
        }
       .....
    ]
    

### 公共-获取深度数据

获取合约的深度列表。

##### 限速规则：20次/2s

##### HTTP请求

`GET/api/swap/v3/instruments/<instrument_id>/depth`

##### 请求示例

`GET/api/swap/v3/instruments/BTC-USD-SWAP/depth?size=50`

##### 请求参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
instrument_id | String | 是 | 合约名称，如 `BTC-USD-SWAP,BTC-USDT-SWAP`  
depth | String | 否 | 按价格合并深度，例如：0.1,0.001  
size | String | 否 | 返回深度数量，最大值可传200，即买卖深度共400条  
  
校验合约名称，只要和数据库中的合约名称不同，就会报错

当`size`不传时，返回1条；`size`传`0`时，返回0条；`size`最大`200`，传大于`200`的数时，返回200条。

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
asks | List<String> | 卖方深度  
bids | List<String> | 买方深度  
time | String | 系统时间戳  
  
返回值数组说明

`["411.8", "10", "1", "4"]`
`411.8`为深度价格，`10`为此价格的合约张数，`1`为此价格的强平单个数，`4`为此价格的订单个数。

##### 返回示例

    
    
    {
        "asks":[
            [
                "3968.5",
                "121",
                0,
                2
            ],
            [
                "3968.6",
                "160",
                0,
                4
            ]
        ],
        "bids":[
            [
                "3968.4",
                "179",
                0,
                4
            ],
            [
                "3968",
                "914",
                0,
                3
            ]
        ],
        "time":"2019-03-25T11:12:10.601Z"
    }
    

### 公共-获取全部ticker信息

获取平台全部合约的最新成交价、买一价、卖一价和24交易量。

##### 限速规则：20次/2s

##### HTTP请求

`GET/api/swap/v3/instruments/ticker`

##### 请求示例

`GET/api/swap/v3/instruments/ticker`

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
instrument_id | String | 合约名称，如`BTC-USD-SWAP,BTC-USDT-SWAP`  
best_ask | String | 卖一价  
best_bid | String | 买一 价  
last | String | 最新成交价  
high_24h | String | 24小时最高价  
low_24h | String | 24小时最低价  
volume_24h | String | 24小时成交量，按张数统计  
timestamp | String | 系统时间戳  
last_qty | String | 最新成交的数量  
best_ask_size | String | 卖一价对应的量  
best_bid_size | String | 买一价对应的数量  
  
##### 解释说明

最高价、最低价和成交量都是按最近24小时为维度统计的。

##### 返回示例

    
    
    [
      {
        "instrument_id": "BTC-USDT-SWAP",
        "last": "7387.6",
        "high_24h": "7980",
        "low_24h": "7348.3",
        "volume_24h": "514883697",
        "best_ask": "7387.2",
        "best_bid": "7387.1",
        "timestamp": "2020-03-12T08:03:39.280Z",
        "last_qty": "3486",
        "best_bid_size": "33068",
        "best_ask_size": "9002"
      }
    ]
    

### 公共-获取某个ticker信息

获取合约的最新成交价、买一价、卖一价和24交易量。

##### 限速规则：20次/2s

##### HTTP请求

`GET/api/swap/v3/instruments/<instrument_id>/ticker`

##### 请求示例

`GET/api/swap/v3/instruments/BTC-USD-SWAP/ticker`

##### 请求参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
instrument_id | String | 是 | 合约名称，如`BTC-USD-SWAP,BTC-USDT-SWAP`  
  
校验合约名称，只要和数据库中的合约名称不同，就会报错

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
instrument_id | String | 合约名称，如`BTC-USD-SWAP`  
last | String | 最新成交价  
best_bid | String | 买一价  
best_ask | String | 卖一价  
high_24h | String | 24小时最高价  
low_24h | String | 24小时最低价  
volume_24h | String | 24小时成交量，按张数统计  
timestamp | String | 系统时间戳  
last_qty | String | 最新成交的数量  
best_ask_size | String | 卖一价对应的量  
best_bid_size | String | 买一价对应的数量  
  
##### 解释说明

最高价、最低价和成交量都是按最近24小时为维度统计的。

##### 返回示例

    
    
    {
        "instrument_id": "BTC-USDT-SWAP",
        "last": "7387.6",
        "high_24h": "7980",
        "low_24h": "7348.3",
        "volume_24h": "514883697",
        "best_ask": "7387.2",
        "best_bid": "7387.1",
        "timestamp": "2020-03-12T08:03:39.280Z",
        "last_qty": "3486",
        "best_bid_size": "33068",
        "best_ask_size": "9002"
    }
    

### 公共-获取成交数据

获取合约的成交记录，本接口能查询最近300条数据。

##### 限速规则：20次/2s

##### HTTP请求

`GET/api/swap/v3/instruments/<instrument_id>/trades`

##### 请求示例

`GET/api/swap/v3/instruments/BTC-USD-SWAP/trades?after=1&limit=50`

##### 请求参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
instrument_id | String | 是 | 合约名称，如`BTC-USD-SWAP,BTC-USDT-SWAP`  
after | String | 否 | 请求此id之前（更旧的数据）的分页内容，传的值为对应接口的`trade_id`  
before | String | 否 | 请求此id之后（更新的数据）的分页内容，传的值为对应接口的`trade_id` |  
limit | String | 否 | 分页返回的结果集数量，最大为100，不填默认返回100条  
  
校验合约名称，只要和数据库中的合约名称不同，就会报错。`after`和`before`同时传，以`after`为准

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
trade_id | String | 成交id  
price | String | 成交价格  
size | String | 成交数量  
side | String | 成交方向：`sell`或`buy`  
timestamp | String | 成交时间  
  
##### 解释说明

成交方向`side`是指 `buy` 或 `sell`，返回 `buy` 或 `sell`。

获取永续合约最新的300条成交列表

##### 返回示例

    
    
    [
        {
            "trade_id":"197610300823248897",
            "price":"3969.2",
            "size":"5",
            "side":"buy",
            "timestamp":"2019-03-25T11:55:23.569Z"
        },
        {
            "trade_id":"197608511860318209",
            "price":"3969.3",
            "size":"56",
            "side":"sell",
            "timestamp":"2019-03-25T11:51:50.308Z"
        }
    ]
    

### 公共-获取K线数据

获取合约的K线数据。K线数据最多可获取最近1440条。

##### 限速规则：20次/2s

##### HTTP请求

`GET/api/swap/v3/instruments/<instrument_id>/candles`

##### 请求示例

`GET/api/swap/v3/instruments/BTC-USD-
SWAP/candles?start=2019-03-24T02:31:00.000Z&end=2019-03-25T02:55:00.000Z&granularity=86400`

（查询`BTC-USD-SWAP`的2019年3月24日到25日的日线K线数据）

##### 请求参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
instrument_id | String | 是 | 合约名称，如`BTC-USD-SWAP,BTC-USDT-SWAP`  
start | String | 否 | 开始时间，必须是ISO 8601格式的时间  
end | String | 否 | 结束时间，必须是ISO 8601格式的时间  
granularity | String | 否 |
时间粒度，以秒为单位，默认值`60`。如`[60/180/300/900/1800/3600/7200/14400/21600/43200/86400/604800]`，详见下解释说明  
  
##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
timestamp | String | 系统时间  
open | String | 开盘价格  
high | String | 最高价格  
low | String | 最低价格  
close | String | 收盘价格  
volume | String | 交易量（按张折算）  
currency_volume | String | 交易量（按币折算）  
  
##### 解释说明

如果用户没有提供开始时间或结束时间中的任一字段，则两个字段都将被忽略。未提供开始时间和结束时间的请求，则系统按时间粒度返回最近的200条数据。

时间粒度`granularity`必须是`[60 180 300 900 1800 3600 7200 14400 21600 43200 86400
604800 2678400 8035200 16070400 31536000]]`中的任一值，否则请求将被拒绝。这些值分别对应的是`[1min 3min
5min 15min 30min 1hour 2hour 4hour 6hour 12hour 1day 1week 1 month 3 months 6
months and 1 year]`的时间段。

K线数据可能不完整。

单次请求的最大数据量是`200`。如果您选择的开始/结束时间和时间粒度导致超过单次请求的最大数据量，您的请求将只会返回200个数据。如果您希望在更大的时间范围内获取足够精细的数据，则需要使用多个开始/结束范围进行多次请求。

数组中的数据顺序分别是：时间戳，开盘价格，最高价格，最低价格，收盘价格，交易量（张），交易量（币）

即分别为`[timestamp,open,high,low,close,volume,currency_volume]`

##### 返回示例

    
    
    [
        [
            "2019-03-25T16:00:00.000Z",
            "3946.6",
            "3960",
            "3860",
            "3917.7",
            "329627",
            "8434.421"
        ],
        [
            "2019-03-24T16:00:00.000Z",
            "3971.4",
            "3977.7",
            "3942.6",
            "3946.4",
            "333780",
            "8416.0873"
        ]
    ]
    
    //["系统时间","开盘价格","最高价格","最低价格","收盘价格","交易量（按张折算）","交易量（按币折算）"]
    

### 公共-获取指数信息

获取币种指数。

##### 限速规则：20次/2s

##### HTTP请求

`GET/api/swap/v3/instruments/<instrument_id>/index`

##### 请求示例

`GET/api/swap/v3/instruments/BTC-USD-SWAP/index`

##### 请求参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
instrument_id | String | 是 | 合约名称，如`BTC-USD-SWAP,BTC-USDT-SWAP`  
  
校验合约名称，只要和数据库中的合约名称不同，就会报错

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
instrument_id | String | 合约名称，如`BTC-USD-SWAP,BTC-USDT-SWAP`  
index | String | 现货指数价格  
timestamp | String | 系统时间戳  
  
##### 解释说明

指数币对"-"后面的币种表示指数价格的计价单位。

##### 返回示例

    
    
    {
        "instrument_id":"BTC-USD-SWAP",
        "index":"3913.64749999",
        "timestamp":"2019-03-26T02:30:20.560Z"
    }
    

### 公共-获取法币汇率

获取法币汇率。

##### 限速规则：20次/2s

##### HTTP请求

`GET/api/swap/v3/rate`

##### 请求示例

`GET/api/swap/v3/rate`

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
instrument_id | String | `USD_CNY`  
rate | String | 汇率  
timestamp | String | 系统时间戳  
  
##### 返回示例

    
    
    {
        "instrument_id":"USD_CNY",
        "rate":"6.701",
        "timestamp":"2019-03-26T02:32:52.703Z"
    }
    

### 公共-获取平台总持仓量

获取合约整个平台的总持仓量。

##### 限速规则：20次/2s

##### HTTP请求

`GET/api/swap/v3/instruments/<instrument_id>/open_interest`

##### 请求示例

`GET/api/swap/v3/instruments/BTC-USD-SWAP/open_interest`

##### 请求参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
instrument_id | String | 是 | 合约名称，如`BTC-USD-SWAP,BTC-USDT-SWAP`  
  
##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
instrument_id | String | 合约名称，如`BTC-USD-SWAP`  
amount | String | 总持仓量  
timestamp | String | 系统时间戳  
  
校验合约名称，只要和数据库中的合约名称不同，就会报错

##### 返回示例

    
    
    {
        "instrument_id":"BTC-USD-SWAP",
        "amount":"303613",
        "timestamp":"2019-03-26T02:36:22.703Z"
    }
    

### 公共-获取当前限价

获取合约当前交易的最高买价和最低卖价。

##### 限速规则：20次/2s

##### HTTP请求

`GET/api/swap/v3/instruments/<instrument_id>/price_limit`

##### 请求示例

`GET/api/swap/v3/instruments/BTC-USD-SWAP/price_limit`

##### 请求参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
instrument_id | String | 是 | 合约名称，如`BTC-USD-SWAP,BTC-USDT-SWAP`  
  
校验合约名称，只要和数据库中的合约名称不同，就会报错

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
instrument_id | String | 合约名称，如`BTC-USD-SWAP,BTC-USDT-SWAP`  
highest | String | 最高买价  
lowest | String | 最低卖价  
timestamp | String | 系统时间戳  
  
##### 返回示例

    
    
    {
        "instrument_id":"BTC-USD-SWAP",
        "highest":"3953.4",
        "lowest":"3875.0",
        "timestamp":"2019-03-26T02:42:38.143Z"
    }
    

### 公共-获取强平单

获取合约强平单。

##### 限速规则：20次/2s

##### HTTP请求

`GET/api/swap/v3/instruments/<instrument_id>/liquidation`

##### 请求示例

`GET/api/swap/v3/instruments/BTC-USD-SWAP/liquidation?status=1&limit=50`

##### 请求参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
instrument_id | String | 是 | 合约名称，如`BTC-USD-SWAP,BTC-USDT-SWAP`  
status | String | 是 | 状态  
`0`：最近7天的未成交  
`1`：最近7天的已成交  
limit | String | 否 | 分页返回的结果集数量，默认为`100`，最大为`100`，按时间倒序排列，越晚的在前面  
from | String | 否 | 请求此id之前（更旧的数据）的分页内容，例如 2  
to | String | 否 | 请求此id之后（更新的数据）的分页内容 例如 3  
  
校验合约名称，只要和数据库中的合约名称不同，就会报错

`status`不是`0`或`1`，报非法参数

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
instrument_id | String | 合约名称，如`BTC-USD-SWAP`  
size | String | 数量  
created_at | String | 委托时间  
loss | String | 穿仓用户亏损  
price | String | 委托价格  
type | String | `3`:平多  
`4`:平空  
  
##### 返回示例

    
    
    [
        {
            "instrument_id":"BTC-USD-SWAP",
            "size":"4",
            "created_at":"2019-03-26T02:00:40.490Z",
            "loss":"0",
            "price":"3935.1",
            "type":"4"
        },
        {
            "instrument_id":"BTC-USD-SWAP",
            "size":"193",
            "created_at":"2019-03-25T23:28:15.922Z",
            "loss":"0",
            "price":"3932.5",
            "type":"4"
        }
    ]
    

### 公共-获取合约资金费率

获取合约下一次的结算时间。

##### 限速规则：20次/2s

##### HTTP请求

`GET/api/swap/v3/instruments/<instrument_id>/funding_time`

##### 请求示例

`GET/api/swap/v3/instruments/BTC-USD-SWAP/funding_time`

##### 请求参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
instrument_id | String | 是 | 合约名称，如`BTC-USD-SWAP,BTC-USDT-SWAP`  
  
校验合约名称，只要和数据库中的合约名称不同，就会报错

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
instrument_id | String | 合约名称，如`BTC-USD-SWAP,BTC-USDT-SWAP`  
funding_time | String | 当期资金费率时间  
funding_rate | String | 当期资金费率  
estimated_rate | String | 下一期预测资金费率  
settlement_time | String | 结算时间  
  
##### 返回示例

    
    
    {
      "instrument_id": "EOS-USD-SWAP",
      "funding_time": "2019-09-02T16:00:00.000Z",
      "funding_rate": "-0.00066983",
      "estimated_rate": "-0.00043662",
      "settlement_time": "2019-09-02T16:00:00.000Z"
    }
    

### 公共-获取合约标记价格

获取合约标记价格。

##### 限速规则：20次/2s

##### HTTP请求

`GET/api/swap/v3/instruments/<instrument_id>/mark_price`

##### 请求示例

`GET/api/swap/v3/instruments/BTC-USD-SWAP/mark_price`

##### 请求参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
instrument_id | String | 是 | 合约名称，如`BTC-USD-SWAP,BTC-USDT-SWAP`  
  
##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
instrument_id | String | 合约名称，如`BTC-USD-SWAP`  
mark_price | String | 标记价格  
timestamp | String | 系统时间戳  
  
为了防止个别用户恶意操控市场导致合约价格波动剧烈，我们根据现货指数和合理基差设定标记价格。

##### 返回示例

    
    
    {
        "instrument_id":"BTC-USD-SWAP",
        "mark_price":"3914.3",
        "timestamp":"2019-03-26T03:33:50.064Z"
    }
    

### 公共-获取合约历史资金费率

获取合约历史资金费率，本接口能查询最近1个月的数据。

##### 限速规则：20次/2s

##### HTTP请求

`GET/api/swap/v3/instruments/<instrument_id>/historical_funding_rate`

##### 请求示例

`GET/api/swap/v3/instruments/BTC-USD-SWAP/historical_funding_rate?limit=2`

##### 请求参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
instrument_id | String | 是 | 合约名称，如`BTC-USD-SWAP,BTC-USDT-SWAP`  
limit | String | 否 | 返回的结果集数量，默认为`100`，最大为`100`，按时间顺序排列，越早下单的在前面  
  
校验合约名称，只要和数据库中的合约名称不同，就会报错。

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
instrument_id | String | 合约名称，如`BTC-USD-SWAP`  
funding_rate | String | 当期资金费率  
realized_rate | String | 实际资金费率  
interest_rate | String | 利率  
funding_time | String | 结算时间  
  
##### 返回示例

    
    
    [
        {
            "instrument_id":"BTC-USD-SWAP",
            "funding_rate":"-0.00007116",
            "realized_rate":"-0.00007116",
            "interest_rate":"0.00000000",
            "funding_time":"2019-03-26T02:00:00.000Z"
        },
        {
            "instrument_id":"BTC-USD-SWAP",
            "funding_rate":"-0.00010248",
            "realized_rate":"-0.00010248",
            "interest_rate":"0.00000000",
            "funding_time":"2019-03-25T14:00:00.000Z"
        }
    ]
    

### 期权合约API

期权合约交易的行情信息，账户信息，订单操作，订单查询，账单明细查询。

期权接口中underlying, instrument_id, coin等参数值都大小写兼容，比如btc-usd, BTC-USD等价。

### 单个标的指数持仓信息

获取某个标的下的持仓信息

##### 限速规则：20次/2s

##### HTTP请求

`GET/api/option/v3/<underlying>/position`

##### 请求示例

`GET/api/option/v3/BTC-USD/position?instrument_id=BTC-USD-190927-12500-C`

##### 请求参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
underlying | String | 是 | 标的指数，如BTC-USD  
instrument_id | String | 否 | 合约ID，如BTC-USD-190927-12500-C  
  
##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
instrument_id | String | 合约ID，如BTC-USD-190927-12500-C  
position | String | 净持仓数量  
avg_cost | String | 开仓平均价  
avail_position | String | 可平仓数量  
settlement_price | String | 上期结算基准价  
total_pnl | String | 不含手续费的持仓收益，可跨期 (markPx - avgCost) _Pos_ multiplier  
pnl_ratio | String | 收益率 sideFactor * (markPx/avgCost - 1)  
realized_pnl | String | 当期已实现收益  
unrealized_pnl | String | 当期未实现收益  
pos_margin | String | 持仓保证金（即初始保证金），只有标准账户提供  
option_value | String | 期权市值  
created_at | String | 仓位建立时间，ISO 8601格式  
updated_at | String | 最后一次仓位变化时间，ISO 8601格式  
  
##### 返回示例

    
    
    成功返回：
    {
        "holding":[
            {
                "instrument_id":"BTC-USD-190927-12500-C",
                "position":"20",
                "avg_cost":"3.26",
                "avail_position":"20",
                "settlement_price":"0.017",
                "total_pnl":"50",
                "pnl_ratio":"0.3",
                "realized_pnl":"40",
                "unrealized_pnl":"10",
                "pos_margin":"100",
                "option_value":"70",
                "created_at":"2019-08-30T03:09:20.315Z",
                "updated_at":"2019-08-30T03:40:18.318Z"
            },
            {
                "instrument_id":"BTC-USD-190927-12500-P",
                "position":"20",
                "avg_cost":"3.26",
                "avail_position":"20",
                "settlement_price":"0.018",
                "total_pnl":"50",
                "pnl_ratio":"0.3",
                "realized_pnl":"40",
                "unrealized_pnl":"10",
                "pos_margin":"100",
                "option_value":"70",
                "created_at":"2019-08-30T03:09:20.315Z",
                "updated_at":"2019-08-30T03:40:18.318Z"
            }
        ]
    }
    为空返回：分两种情形
        一、不传instrument_id
        {'holding': []}
        二、传instrument_id（列举每个字段，但数值型为0，时间戳字段填1970初始时间）
        {
            "holding":[
                {
                    "instrument_id":"BTC-USD-190927-7500-C",
                    "position":"0",
                    "avg_cost":"0",
                    "avail_position":"0",
                    "settlement_price":"0",
                    "total_pnl":"0",
                    "pnl_ratio":"0",
                    "realized_pnl":"0",
                    "unrealized_pnl":"0",
                    "pos_margin":"0",
                    "option_value":"0",
                    "created_at":"1970-01-01T00:00:00.000Z",
                    "updated_at":"1970-01-01T00:00:00.000Z"
                }
            ]
        }
    失败返回：
    {
        "error_message": "Invalid underlying index",
        "error_code": "36001"
    }
    

### 单个标的物账户信息

获取单个标的物账户信息。

##### 限速规则：20次/2s

##### HTTP请求

`GET/api/option/v3/accounts/<underlying>`

##### 请求示例

`GET/api/option/v3/accounts/BTC-USD`

##### 请求参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
underlying | String | 是 | 标的指数，如BTC-USD  
  
##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
currency | String | 账户币种, 如BTC  
underlying | String | 标的指数，如BTC-USD  
equity | String | 权益  
total_avail_balance | String | 总余额  
margin_balance | String | 保证金余额  
margin_frozen | String | 已用保证金（IMR，包含挂单和持仓保证金）  
avail_margin | String | 可用保证金  
margin_for_unfilled | String | 总挂单保证金  
maintenance_margin | String | 持仓最低维持保证金  
realized_pnl | String | 当期已实现盈亏汇总  
unrealized_pnl | String | 当期未实现盈亏汇总  
option_value | String | 期权总市值  
delta | String | 账户总delta  
vega | String | 账户总vega  
gamma | String | 账户总gamma  
theta | String | 账户总theta  
risk_factor | String | 风险乘数 （目前该字段暂未启用）  
margin_multiplier | String | 规模乘数 （目前该字段暂未启用）  
account_status | String | "0": 正常，"1": 延迟减仓中，"2": 减仓中  
  
##### 返回示例

    
    
    成功返回：
    {
        "underlying": "BTC-USD",
        "equity": "0.00254188",
        "total_avail_balance": "0.00254188",
        "margin_balance": "0.00254188",
        "avail_margin": "0.00254188",
        "margin_for_unfilled": "0",
        "margin_frozen": "0",
        "maintenance_margin": "0",
        "realized_pnl": "0",
        "unrealized_pnl": "0",
        "max_withdraw": "0",
        "option_value": "0",
        "delta": "0",
        "vega": "0",
        "gamma": "0",
        "theta": "0",
        "risk_factor": "1",
        "margin_multiplier": "1",
        "account_status": "0",
        "currency": "BTC"
    }
    为空返回：
    {
        "underlying": "BTC-USD",
        "equity": "0",
        "total_avail_balance": "0",
        "margin_balance": "0",
        "avail_margin": "0",
        "margin_for_unfilled": "0",
        "margin_frozen": "0",
        "maintenance_margin": "0",
        "realized_pnl": "0",
        "unrealized_pnl": "0",
        "max_withdraw": "0",
        "option_value": "0",
        "delta": "0",
        "vega": "0",
        "gamma": "0",
        "theta": "0",
        "risk_factor": "1",
        "margin_multiplier": "1",
        "account_status": "0",
        "currency": "BTC"
    }
    失败返回：
    {'error_code': 36001, 'error_message': 'Invalid underlying index'}
    

### 下单

API交易提供限价单下单模式，只有当您的账户有足够的资金才能下单。一旦下单，您的账户资金将在订单生命周期内被冻结，被冻结的资金以及数量取决于订单指定的类型和参数

##### 限速规则：20次/s

##### HTTP请求

`POST /api/option/v3/order`

##### 请求示例

`POST /api/option/v3/order{"client_oid":"oktoption15","instrument_id":"BTC-
USD-190927-12500-C","side":"buy","order_type":"0","price":"2.15","size":"2","match_price":"0"}`

##### 请求参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
client_oid | String | 否 | 由您设置的订单ID来识别您的订单,格式是字母（区分大小写）+数字 或者
纯字母（区分大小写），1-32位字符 （不能重复）  
instrument_id | String | 是 | 合约ID，如BTC-USD-190927-5000-C  
side | String | 是 | 订单方向(buy/sell)  
order_type | String | 否 | 参数填数字，0：普通委托（默认值）  
price | String | 是 | 委托价格  
size | String | 是 | 委托数量（合约张数）  
match_price | String | 否 | 是否以对手价下单 0:不是（默认值） 1:是  
  
##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
order_id | String | 订单ID，下单失败时，此字段值为-1  
client_oid | String | 由您设置的订单ID  
error_code | String | 错误码，下单成功时为0，下单失败时会显示相应错误码  
error_message | String | 错误信息，下单成功时为空，下单失败时会显示错误信息  
result | String | 接口调用返回结果，true/false  
  
##### 解释说明

如果error_code的返回值不为0，说明请求校验失败并被拒绝

instrument_id

instrument_id必须是有效的合约ID。合约列表可通过GET/api/option/v3/instruments/接口获取。

client_oid

用户需要自己保证此ID不重复，OKEx不会进行排重提示，如有重复，撤单和查询订单时只能撤销或者查询最新的一条数据。

side

side委托订单的方向，buy或sell。

price

price表示买入或卖出每张合约的价格。价格必须是价格步长(tick_size)的倍数。价格步长(tick_size)是价格的最小增量，可通过/instruments接口获取。

size

size表示买入或卖出合约的张数。数量必须是正整数。

match_price

对手价表示你希望以目前对手方的最优价格成交。如果你下的是买单，选择以对手价下单表示你用当前卖一价进行下单。如果你下的是卖单，选择以对手价下单表示你用当前买一价进行下单。

响应

成功接受的订单将被分配一个订单ID。成功接受的订单表示撮合引擎已经接受的订单。未成交的订单不会过期，并将保持撮合状态，直到被成交或取消。

##### 返回示例

    
    
    下单成功：
    {
        "result": "true",
        "error_message": "",
        "error_code": "0",
        "client_oid": "b1234",
        "order_id": "131801215763791872"
    }
    下单失败：
    {
        "result": "true",
        "error_message": "Invalid format for client_oid",
        "error_code": "36203",
        "client_oid": "1234",
        "order_id": "-1"
    }
    

### 批量下单

批量进行下单请求，每个标的指数最多可批量下10个单。

##### 限速规则：20次/2s

##### HTTP请求

`POST /api/option/v3/orders`

##### 请求示例

`POST /api/option/v3/orders{"underlying": "BTC-USD",
"order_data":[{"instrument_id":"BTC-USD-190927-12500-C", "size": "1", "price":
"3.2571", "side": "buy", "order_type":"0", "match_price": "0"},
{"instrument_id":"BTC-USD-190927-12500-C", "size": "1", "price": "3.26",
"side": "buy", "order_type":"0", "match_price": "0"}]}`

##### 请求参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
underlying | String | 是 | 标的指数，如BTC-USD，同一批订单合约必须针对同一指数标的。  
order_data | String | 是 | 订单请求列表，每个请求与单个订单请求格式一致  
  
请求参数的校验和单个订单一致。

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
order_info | String | 批量下单结果列表，每个元素的结构与单个下单返回一致  
result | String | 接口调用返回结果, true/false  
  
##### 解释说明

如果error_code的返回值不为0，说明请求校验失败并被拒绝

client_oid 是数字+字母（大小写）或者纯字母（大小写）类型 1-32位

result是代表服务器处理了请求，不代表下单是否成功。

返回的结果数据和order_data提交订单数据顺序一致。如果下单失败，则order_id为-1，error_code是错误码提示，error_message是错误信息。

##### 返回示例

    
    
    批量下单成功：
    {
        "result": "true",
        "order_info": [
            {
                "error_message": "",
                "result": "true",
                "error_code": "0",
                "client_oid": "order1",
                "order_id": "131841003766198272"
            },
            {
                "error_message": "",
                "result": "true",
                "error_code": "0",
                "client_oid": "order2",
                "order_id": "131841003766198273"
            }
        ]
    }
    批量下单失败：
    全部失败：
    {
        "order_info":[
            {
                "client_oid":"oktoption14",
                "order_id":"-1",
                "error_code":"36211",
                "error_message":"Exceeding max batch size for order submission",
                "result":"false"
            },
            {
                "client_oid":"oktoption15",
                "order_id":"-1",
                "error_code":"36211",
                "error_message":"Exceeding max batch size for order submission",
                "result":"false"
            }
        ],
        "result":"true"
    }
    部分失败：
    {
        "order_info":[
            {
                "client_oid":"oktoption14",
                "order_id":"305512815291895606",
                "error_code":"0",
                "error_message":"",
                "result":"true"
            },
            {
                "client_oid":"oktoption15",
                "order_id":"-1",
                "error_code":"36211",
                "error_message":"Exceeding max batch size for order submission",
                "result":"false"
            }
        ],
        "result":"true"
    }
    

### 撤单

撤销之前下的未完成订单。

##### 限速规则：20次/s

##### HTTP请求

`POST /api/option/v3/cancel_order/<underlying>/<order_id or client_oid>`

##### 请求示例

`POST /api/option/v3/cancel_order/BTC-USD/305512815291895607`

or

`POST /api/option/v3/cancel_order/BTC-USD/oktoption15`

##### 请求参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
underlying | String | 是 | 标的指数，如BTC-USD  
order_id | String | 非必填 | order_id和client_oid必须且只能选一个填写。订单ID。  
client_oid | String | 非必填 | order_id和client_oid必须且只能选一个填写。在下单时由您设置的ID来识别您的订单,
类型为字母（大小写）+数字或者纯字母（大小写） 1-32位字符  
  
##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
order_id | String | 订单ID  
client_oid | String | 由您设置的订单ID来识别您的订单  
error_code | String | 错误码，撤单成功时为0，撤单失败时会显示相应错误码  
error_message | String | 错误信息，撤单成功时为空，撤单失败时会显示错误信息  
result | String | 接口调用返回结果，true/false  
  
##### 解释说明

如果error_code的返回值不为0，说明请求校验失败并被拒绝

使用client_oid撤单时，用户需要自己保证此ID不重复，OKEx不会进行排重提示，如有重复，撤单时只能撤销最新的一条数据

result是代表服务器处理了请求，不代表撤单是否成功。

如果订单无法取消(已经成交或已取消)，那么返回的报错内容里将显示相应的原因。

##### 返回示例

    
    
    {
        "order_id": "131801215763791872",
        "client_oid": "b1234",
        "result": "true",
        "error_message": "",
        "error_code": "0"
    }
    

### 批量撤单

批量撤销之前下的未完成订单，每个标的指数最多可批量撤10个单。

##### 限速规则：20次/2s

##### HTTP请求

`POST /api/option/v3/cancel_batch_orders/<underlying>`

##### 请求示例

`POST /api/option/v3/cancel_batch_orders/BTC-
USD{"order_ids":["305512815291895606","305512815291895607"]}`

OR

`POST /api/option/v3/cancel_batch_orders/BTC-
USD{"client_oids":["oktoption14","oktoption15"]}`

##### 请求参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
underlying | String | 是 | 合约标的指数，如BTC-USD，同一批量撤单必须为同一标的合约  
order_ids | List | 非必填 | order_id和client_oid必须且只能选一个填写。订单ID的列表。  
client_oids | List | 非必填 |
order_id和client_oid必须且只能选一个填写。client_oid的列表，在下单时由您设置的ID来识别您的订单,
类型为字母（大小写）+数字或者纯字母（大小写） 1-32位字符  
  
请求参数校验和单个订单撤销一致。

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
order_info | String | 批量撤单结果列表，每个元素的结构与单个撤单返回一致  
result | String | 接口调用返回结果, true/false  
  
返回值中是已发起撤销操作的订单ID列表，不代表这些订单已成功撤销，正在成交中的无法撤销，未成交的可成功撤销。

##### 解释说明

如果error_code的返回值不为0，说明请求校验失败并被拒绝.

使用client_oid批量撤单时，用户需要自己保证此ID不重复，OKEx不会进行排重提示，如有重复，撤单时只能撤销最新的一条数据

result是代表服务器处理了请求，不代表撤单是否成功。

无法保证一定会成功撤销，建议用户调用批量撤单接口后，再调用获取订单列表接口确认。

##### 返回示例

    
    
    批量撤单成功：（传入order_id）
    {
        "result": "true",
        "order_info": [
            {
                "error_message": "",
                "result": "true",
                "error_code": "0",
                "client_oid": "order1",
                "order_id": "131841003766198272"
            },
            {
                "error_message": "",
                "result": "true",
                "error_code": "0",
                "client_oid": "order2",
                "order_id": "131841003766198273"
            }
        ]
    }
    批量撤单失败：（传入order_id）
    {
        "result":"true",
        "order_info":[
            {
                "client_oid":"",  --如果能通过order_id带出来，也返回
                "order_id":"305512815291895606",
                "error_code":"36216",
                "error_message":"Order does not exist",
                "result":"false"
            },
            {
                "client_oid":"",  --如果能通过order_id带出来，也返回
                "order_id":"305512815291895607",
                "error_code":"36216",
                "error_message":"Order does not exist",
                "result":"false"
            }
        ]
    
    }
    批量撤单失败：（client_oid）
    {
        "result": "true",
        "order_info":[
            {
                "client_oid":"oktoption14",
                "order_id":"",  --如果能通过client_oid带出来，也返回
                "error_code":"36218",
                "error_message":"Order cancellation failed.",
                "result":"false"
            },
            {
                "client_oid":"oktoption15",
                "order_id":"",  ----如果能通过client_oid带出来，也返回
                "error_code":"36218",
                "error_message":"Order cancellation failed.",
                "result":"false"
            }
        ]
    }
    

### 修改订单

修改之前下的未完成订单。

##### 限速规则：20次/s

##### HTTP请求

`POST /api/option/v3/amend_order/<underlying>`

##### 请求示例

`POST /api/option/v3/amend_order/BTC-
USD{"order_id":"305512815291895607","new_size":"2"}`

or

`POST /api/option/v3/amend_order/BTC-
USD{"client_oid":"oktoption15","new_size":"2"}`

##### 请求参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
underlying | String | 是 | 标的指数，如BTC-USD  
order_id | String | 非必填 | order_id和client_oid不能同时为空。订单ID。  
client_oid | String | 非必填 | order_id和client_oid不能同时为空。在下单时由您设置的ID来识别您的订单,
类型为字母（大小写）+数字或者纯字母（大小写），1-32位字符。  
request_id | String | 否 |
客户可选择提供request_id，如果提供，在修改返回状态中，会包含相应的request_id，方便客户找到相应的修改请求。类型为字母（大小写）+数字或者纯字母（大小写），1-32位字符。  
new_size | String | 非必填 |
new_size和new_price至少要传入一个。请求修改的新数量，对于部分成交订单，该数量应包含已成交数量。  
new_price | String | 非必填 | new_size和new_price至少要传入一个。请求修改的新价格。  
  
##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
order_id | String | 订单ID  
client_oid | String | 由您设置的订单ID来识别您的订单  
request_id | String | 如果客户在修改请求中提供request_id，则返回相应request_id  
error_code | String | 错误码，请求成功时为0，请求失败时会显示相应错误码  
error_message | String | 错误信息，请求成功时为空，请求失败时会显示错误信息  
result | String | 接口调用返回结果，true/false  
  
##### 解释说明

如果error_code的返回值不为0，说明请求校验失败并被拒绝

使用client_oid修改订单时，用户需要自己保证此ID不重复，OKEx不会进行排重提示，如有重复，只能修改最新的一条数据

如果同时传入了order_id和client_oid，将使用order_id，而忽略client_oid.

result是代表服务器处理了请求，不代表修改是否成功。

如果订单无法修改，那么返回的报错内容里将显示相应的原因。

##### 返回示例

    
    
    {
        "result": "true",
        "request_id": "",
        "client_oid": "b1234",
        "order_id": "131801215763791872",
        "error_message": "",
        "error_code": "0"
    }
    

### 批量修改订单

修改之前下的未完成订单，每个标的指数最多可批量修改10个单。

##### 限速规则：20次/2s

##### HTTP请求

`POST /api/option/v3/amend_batch_orders/<underlying>`

##### 请求示例

`POST /api/option/v3/amend_batch_orders/BTC-
USD{"amend_data":[{"order_id":"305512815291895607","new_size":"2"},{"order_id":"305512815291895606","new_size":"1"}]}`

OR

`POST /api/option/v3/amend_batch_orders/BTC-
USD{"amend_data":[{"client_oid":"oktoption15","request_id":"okoptionBTCUSDmod001","new_size":"2"},{"client_oid":"oktoption14","request_id":"okoptionBTCUSDmod002","new_size":"1"}]}`

##### 请求参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
underlying | String | 是 | 合约标的指数，如BTC-USD，同一批修改必须对应同一个标的指数  
amend_data | List | 是 | 批量修改请求，每一个请求格式与单个修改相同。  
  
请求参数校验和单个订单修改一致。

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
order_info | String | 批量修改结果列表，每个元素的结构与单个修改订单返回一致  
result | String | 接口调用返回结果, true/false  
  
##### 返回参数

返回值中是已发起修改操作的订单ID列表，不代表这些订单已成功修改。

##### 解释说明

如果error_code的返回值不为0，说明请求校验失败并被拒绝

使用client_oid 批量修改订单时，用户需要自己保证此ID不重复，OKEx不会进行排重提示，如有重复，修改时只能修改最新的一条数据。

result是代表服务器处理了请求，不代表修改是否成功。

无法保证一定会成功修改，建议用户调用批量修改订单接口后，再调用获取订单列表接口确认。

##### 返回示例

    
    
    传入client_oid批量修改
    {
        "order_info":[
            {
                client_oid":"oktoption14",
                "order_id":"",
                "request_id":"okoptionBTCUSDmod002",
                "error_code":"0",
                "error_message":"",
                "result":"true"
            },
            {
                "client_oid":"oktoption15",
                "order_id":"",
                "request_id":"okoptionBTCUSDmod001",
                "error_code":"0",
                "error_message":"",
                "result":"true"
            }
        ],
        "result":"true"
    }
    

### 获取单个订单状态

查询单个订单状态。已撤销的未成交单只保留2个小时。

##### 限速规则：40次/2s

##### HTTP请求

`GET/api/option/v3/orders/<underlying>/<order_id or client_oid>`

##### 请求示例

`GET/api/option/v3/orders/BTC-USD/305512815291895606`

or

`GET/api/option/v3/orders/BTC-USD/oktoption14`

##### 请求参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
underlying | String | 是 | 合约标的指数，如BTC-USD  
order_id | String | 非必填 | order_id和client_oid必须且只能选一个填写。订单ID。  
client_oid | String | 非必填 | order_id和client_oid必须且只能选一个填写。下单时由您设置的订单ID来识别您的订单
, 类型为字母（大小写）+数字或者纯字母（大小写） 1-32位字符  
  
##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
order_id | String | 订单ID  
client_oid | String | 由您设置的订单ID来识别您的订单  
timestamp | String | 状态变更时间，ISO 8601格式  
instrument_id | String | 合约名称，如BTC-USD-190927-12500-C  
size | String | 委托数量  
price | String | 委托价格  
side | String | 订单方向(buy/sell)  
filled_qty | String | 成交数量  
price_avg | String | 成交均价（如果成交数量为0，该字段也为0）  
fee | String | 手续费  
contract_val | String | 合约面值（即合约乘数）  
last_fill_px | String | 最新成交价格（如没有成交，为0）  
last_fill_qty | String | 最新成交数量（如没有成交，为0）  
order_type | String | 0：普通委托  
type | String | 区分用户订单的属性  
1.买入，2.卖出，11.强平卖出，12.强平买入，13.减仓卖出，14.减仓买入  
state | String | 订单状态("-2":失败, "-1":撤单成功, "0":等待成交 , "1":部分成交, "2":完全成交,
"3":下单中, "4":撤单中, "5": 修改中）  
  
##### 解释说明

client_oid的类型为字母（大小写）+数字或者纯字母（大小写），1-32位字符，用户需要自己保证此ID不重复，OKEx不会进行排重提示，如有重复，查询订单时只能查询出最新的一条数据。

##### 返回示例

    
    
    成功返回：
    {
        "order_id": "131801215763791872",
        "client_oid": "b1234",
        "timestamp": "2019-12-30T08:50:58.614Z",
        "instrument_id": "BTC-USD-200103-7500-C",
        "size": "1",
        "price": "0.001",
        "side": "buy",
        "filled_qty": "0",
        "price_avg": "0",
        "fee": "0",
        "contract_val": "0.1000",
        "last_fill_px": "0",
        "last_fill_qty": "0",
        "order_type": "0",
        "state": "0",
        "type": "1"
    }
    为空返回：
    {}
    失败返回：
    {
        "error_message": "Invalid underlying index",
        "error_code": "36001"
    }
    

### 获取订单列表

获取当前所有的订单列表。本接口能查询7天内数据。

##### 限速规则：10次/2s

##### HTTP请求

`GET/api/option/v3/orders/<underlying>`

##### 请求示例

`GET/api/option/v3/orders/BTC-USD?instrument_id=BTC-
USD-190927-12500-C&after=18&before=3&state=2&limit=50`

##### 请求参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
underlying | String | 是 | 合约标的指数，如BTC-USD  
instrument_id | String | 否 | 合约ID，如BTC-
USD-190927-12500-C。如果提供的instrument_id的标的物与underlying参数不同，返回错误码。  
after | String | 否 | 请求此id之前(更旧的数据)的分页内容，传的值为对应接口的order_id  
before | String | 否 | 请求此id之后(更新的数据)的分页内容，传的值为对应接口的order_id |  
limit | String | 否 | 分页返回的结果集数量，最大为100，不填默认返回100条  
state | String | 是 | 订单状态("-2":失败,"-1":撤单成功,"0":等待成交 ,"1":部分成交,
"2":完全成交,"3":下单中,"4":撤单中,"6": 未完成（等待成交+部分成交），"7":已完成（撤单成功+完全成交））  
  
##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
order_info | List | 查询结果列表，其中每个元素的结构与"查询单个订单状态"接口返回一致。  
order_id | String | 订单ID  
client_oid | String | 由您设置的订单ID来识别您的订单  
timestamp | String | 状态变更时间，ISO 8601格式  
instrument_id | String | 合约名称，如BTC-USD-190927-12500-C  
size | String | 委托数量  
price | String | 委托价格  
side | String | 订单方向(buy/sell)  
filled_qty | String | 成交数量  
price_avg | String | 成交均价（如果成交数量为0，该字段也为0）  
fee | String | 手续费  
contract_val | String | 合约面值（即合约乘数）  
last_fill_px | String | 最新成交价格（如没有成交，为0）  
last_fill_qty | String | 最新成交数量（如没有成交，为0）  
order_type | String | 0：普通委托  
type | String | 区分用户订单的属性  
1.买入，2.卖出，11.强平卖出，12.强平买入，13.减仓卖出，14.减仓买入  
state | String | 订单状态("-2":失败, "-1":撤单成功, "0":等待成交 , "1":部分成交, "2":完全成交,
"3":下单中, "4":撤单中, "5": 修改中）  
  
##### 解释说明

client_oid 的类型为字母（大小写）+数字或者纯字母（大小写）， 1-32位字符
，用户需要自己保证此ID不重复，OKEx不会进行排重提示，如有重复，查询订单时只能查询出最新的一条数据。

##### 返回示例

    
    
    成功返回：
    {
        "order_info": [
            {
                "client_oid": "b1234",
                "contract_val": "0.1000",
                "fee": "0",
                "filled_qty": "0",
                "instrument_id": "BTC-USD-200103-7500-C",
                "last_fill_px": "0",
                "last_fill_qty": "0",
                "order_id": "131801215763791872",
                "order_type": "0",
                "price": "0.001",
                "price_avg": "0",
                "side": "buy",
                "size": "2",
                "state": "-1",
                "timestamp": "2019-12-30T08:57:44.323Z",
                "type": "1"
            }
        ]
    }
    为空返回：
    {'order_info': []}
    失败返回：
    {
        "error_message": "Invalid underlying index",
        "error_code": "36001"
    }
    

### 获取成交明细

获取最近的成交明细列表。本接口能查询7天内数据。

##### 限速规则：10次/2s

##### HTTP请求

`GET/api/option/v3/fills/<underlying>;`

##### 请求示例

`GET/api/option/v3/fills/BTC-USD?instrument_id=BTC-
USD-190927-12500-C&client_oid=oktoption15&limit=50`

##### 请求参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
underlying | String | 是 | 合约标的指数，如BTC-USD  
order_id | String | 否 | 订单ID  
instrument_id | String | 否 | 合约名称，如BTC-USD-190927-12500-C  
after | String | 否 | 请求此id之前(更旧的数据)的分页内容，传的值为对应接口的trade_id  
before | String | 否 | 请求此id之后(更新的数据)的分页内容，传的值为对应接口的trade_id |  
limit | String | 否 | 分页返回的结果集数量，最大为100，不填默认返回100条  
  
##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
trade_id | String | 成交ID  
order_id | String | 订单ID  
instrument_id | String | 合约名称，如BTC-USD-190927-12500-C  
fill_price | String | 成交价格  
fill_qty | String | 成交数量  
timestamp | String | 成交时间, ISO 8601格式  
side | String | 成交方向(buy/sell)  
exec_type | String | 流动性方向，T：taker M：maker  
fee | String | 手续费  
  
##### 返回示例

    
    
    成功返回：
    [
        {
            "trade_id": "135383019552770048",
            "order_id": "135383019066273792",
            "instrument_id": "BTC-USD-200110-6500-P",
            "fill_price": "0.001",
            "fill_qty": "1",
            "side": "buy",
            "exec_type": "taker",
            "fee": "-0.0000125",
            "timestamp": "2020-01-09T06:03:47.095Z"
        },
        {
         {
            "trade_id": "130026669872252928",
            "order_id": "130019947002728448",
            "instrument_id": "TBTC-USD-191227-8000-P",
            "fill_price": "0.011",
            "fill_qty": "27",
            "side": "buy",
            "exec_type": "maker",
            "fee": "-0.00054",
            "timestamp": "2019-12-25T11:19:33.871Z"
        }
    ]
    为空返回：
    []
    失败返回：
    {
        "error_message": "Invalid underlying index",
        "error_code": "36001"
    }
    

### 获取账单流水

列出账户资产流水，账户资产流水是指导致账户余额增加或减少的行为。流水会分页，每页100条数据，并且按照时间倒序排序和存储，最新的排在最前面。
本接口能查询最近7天的数据。

##### 限速规则：5次/2s

##### HTTP请求

`GET/api/option/v3/accounts/<underlying>/ledger`

##### 请求示例

`GET/api/option/v3/accounts/BTC-USD/ledger?after=18&before=3&limit=10`

##### 请求参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
underlying | String | 是 | 标的指数，如BTC-USD  
after | String | 否 | 请求此id之前(更旧的数据)的分页内容，传的值为对应接口的ledger_id；  
before | String | 否 | 请求此id之后(更新的数据)的分页内容，传的值为对应接口的ledger_id； |  
limit | String | 否 | 分页返回的结果集数量，最大为100，不填默认返回100条  
  
##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
ledger_id | String | 账单ID  
currency | String | 账户币种, 如BTC  
amount | String | 变动金额  
realized_pnl | String | 已实现收益，不含费用  
type | String | 流水来源类型（具体参见下表）  
timestamp | String | 账单创建时间，ISO 8601格式  
balance | String | 如果类型是交易产生的，代表成交张数  
details | String |
如果`type`是`trade`或者`fee`，则会有该`details`字段将包含`order`，`instrument`信息,如果`type`是`transfer`，则会有该`details`字段将包含`from`，`to`信息  
order_id | String | 订单ID  
instrument_id | String | 合约ID  
from | String | 转出账户  
`1`:币币账户  
`3`:交割合约  
`4`:法币账户  
`5`:币币杠杆账户  
`6`:资金账户  
`8`:余币宝账户  
`9`:永续合约账户  
`12`:期权合约  
`14`:挖矿账户  
`17`:借贷账户  
to | String | 转入账户  
`1`:币币账户  
`3`:交割合约  
`4`:法币账户  
`5`:币币杠杆账户  
`6`:资金账户  
`8`:余币宝账户  
`9`:永续合约账户  
`12`:期权合约  
`14`:挖矿账户  
`17`:借贷账户  
**流 水来源类型** | **参 数类型** | **描 述**  
---|---|---  
transfer | String | 转入/转出  
match | String | 交易  
fee | String | 手续费  
settlement | String | 交割/结算  
liquidation | String | 强平/减仓  
  
##### 返回示例

    
    
    成功返回：
    [
        {
            "ledger_id": "131798350215260160",
            "currency": "BTC",
            "amount": "0.00254188",
            "realized_pnl": "0",
            "type": "transfer",
            "timestamp": "2019-12-30T08:39:35.385Z",
            "balance": "0",
            "details": null
        }
    ]
    为空返回：
    []
    失败返回：
    {
        "error_message": "Invalid underlying index",
        "error_code": "36001"
    }
    

### 获取手续费费率

获取当前账户交易等级对应的手续费费率，母账户下的子账户的费率和母账户一致（每天凌晨0点更新）。

##### 限速规则：1次/10s

##### HTTP请求

`GET/api/option/v3/trade_fee`

##### 请求示例

`GET/api/option/v3/trade_fee`

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
timestamp | String | 当前时间，ISO 8601格式  
maker | String | 挂单手续费率  
taker | String | 吃单手续费率  
exercise | String | 行权手续费率  
  
##### 返回示例

    
    
    成功返回：
    {
        "timestamp": "2019-12-30T11:09:35.380Z",
        "maker": "0.0002",
        "taker": "0.0005",
        "exercise": "0.0002"
    }
    为空返回：
    {}
    失败返回：
    {
        "error_message": "Instrument does not exist",
        "error_code": "36002"
    }
    

### 公共-获取标的指数

获取期权交易已支持的标的指数列表。

##### 限速规则：20次/2s

##### HTTP请求

`GET/api/option/v3/underlying`

##### 请求示例

`GET/api/option/v3/underlying`

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
underlying | String | 标的指数，如BTC-USD  
  
##### 返回示例

    
    
    成功返回：
    [
        "BTC-USD"
    ]
    为空返回：
    []
    失败返回：
    {'error_code': 36101, 'error_message': 'Account does not exist'}
    

### 公共-获取期权合约

获取可用合约的列表。

##### 限速规则：20次/2s

##### HTTP请求

`GET/api/option/v3/instruments/<underlying>`

##### 请求示例

`GET/api/option/v3/instruments/BTC-USD?instrument_id=BTC-
USD-190927-8500-C&delivery=190927`

##### 请求参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
underlying | String | 是 | 标的指数，如BTC-USD  
delivery | String | 否 | 合约到期日，如果提供，只返回相应到期日的合约信息。格式为"YYMMDD"，如"190527"  
instrument_id | String | 否 | 合约ID，如果提供，只返回相应合约信息  
  
##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
instrument_id | String | 合约ID，如BTC-USD-190830-9000-C  
underlying | String | 标的指数，如BTC-USD  
settlement_currency | String | 盈亏结算和保证金币种，如BTC  
contract_val | String | 合约乘数，对BTC期权合约，该值为0.1  
option_type | String | 期权类型，`C`或`P`  
strike | String | 行权价格  
tick_size | String | 价格精度（如0.0005）  
lot_size | String | 一手合约张数  
listing | String | 上线日期，ISO 8601格式  
delivery | String | 交割日期，ISO 8601格式  
state | String | 合约状态：1-预上线, 2-已上线, 3-暂停交易, 4-结算中  
trading_start_time | String | 交易开始时间，ISO 8601格式  
timestamp | String | 合约状态变更时间，ISO 8601格式  
  
##### 返回示例

    
    
    成功返回：
    [
        {
            "instrument_id":"BTC-USD-200103-5500-C",
            "underlying":"BTC-USD",
            "settlement_currency":"BTC",
            "contract_val":"0.1000",
            "option_type":"C",
            "strike":"5500",
            "tick_size":"0.0005",
            "lot_size":"1.0000",
            "listing":"2019-12-25T08:30:36.175Z",
            "delivery":"2020-01-03T08:00:00.000Z",
            "state":"2",
            "trading_start_time":"2019-12-25T08:30:36.175Z",
            "timestamp":"2019-12-30T08:00:23.156Z"
        }
    ]
    为空返回：
    []
    失败返回：
    {
        "error_message": "Invalid underlying index",
        "error_code": "36001"
    }
    

### 公共-获取期权合约详细定价

获取同一标的下所有期权合约详细定价。

##### 限速规则：20次/2s

##### HTTP请求

`GET/api/option/v3/instruments/<underlying>/summary`

##### 请求示例

获取同一标的下所有期权合约详细定价：

`GET/api/option/v3/instruments/BTC-USD/summary?delivery=190927`

##### 请求参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
underlying | String | 是 | 标的指数，如BTC-USD  
delivery | String | 否 | 合约到期日，如果提供，只返回相应到期日的合约信息。格式为"YYMMDD"，如"190527"  
  
##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
instrument_id | String | 合约ID  
timestamp | String | 系统时间戳，ISO 8061格式  
best_bid | String | 买一价  
best_ask | String | 卖一价  
last | String | 最新成交价  
high_24h | String | 24小时最高价  
low_24h | String | 24小时最低价  
volume_24h | String | 24小时成交量，按张数统计  
open_interest | String | 持仓量  
mark_price | String | 标记价格  
highest_buy | String | 最高买价  
lowest_sell | String | 最低卖价  
delta | String | 期权价格对underlying价格的敏感度  
gamma | String | delta对underlying价格的敏感度  
vega | String | 期权价格对隐含波动率的敏感度  
theta | String | 期权价格对剩余期限的敏感度  
leverage | String | 杠杆倍数  
mark_vol | String | 标记波动率  
bid_vol | String | bid波动率  
ask_vol | String | ask波动率  
realized_vol | String | 已实现波动率（目前该字段暂未启用）  
estimated_price | String | 预估交割价  
  
##### 返回示例

    
    
    成功返回：所有期权详细定价
    [
        {
            "instrument_id":"BTC-USD-200103-5500-C",
            "best_ask":"0.25",
            "best_bid":"0.246",
            "best_ask_size":"305",
            "best_bid_size":"305",
            "delta":"0.7494223636",
            "gamma":"-0.6765419039",
            "high_24h":"0",
            "highest_buy":"0.3435",
            "realized_vol":"0",
            "bid_vol":"",
            "ask_vol":"1.5625",
            "mark_vol":"0.9987",
            "last":"0",
            "leverage":"4.0342",
            "low_24h":"0",
            "lowest_sell":"0.152",
            "mark_price":"0.24788017",
            "theta":"-0.0000809873",
            "vega":"0.0000077307",
            "volume_24h":"0",
            "open_interest":"0",
            "estimated_price":"0",
            "timestamp":"2019-12-30T10:57:31.691Z"
        }
    ]
    为空返回：所有期权详细定价
    []
    失败返回：所有期权详细定价
    {
        "error_message": "Invalid underlying index",
        "error_code": "36001"
    }
    

### 公共-获取单个期权合约详细定价

获取某个期权合约的详细定价。

##### 限速规则：20次/2s

##### HTTP请求

`GET/api/option/v3/instruments/<underlying>/summary/<instrument_id>`

##### 请求示例

`GET/api/option/v3/instruments/BTC-USD/summary/BTC-USD-190927-12500-C`

##### 请求参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
underlying | String | 是 | 标的指数，如BTC-USD  
instrument_id | String | 是 | 合约ID，如果提供，只返回相应合约信息  
  
##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
instrument_id | String | 合约ID  
timestamp | String | 系统时间戳，ISO 8061格式  
best_bid | String | 买一价  
best_ask | String | 卖一价  
last | String | 最新成交价  
high_24h | String | 24小时最高价  
low_24h | String | 24小时最低价  
volume_24h | String | 24小时成交量，按张数统计  
open_interest | String | 持仓量  
mark_price | String | 标记价格  
highest_buy | String | 最高买价  
lowest_sell | String | 最低卖价  
delta | String | 期权价格对underlying价格的敏感度  
gamma | String | delta对underlying价格的敏感度  
vega | String | 期权价格对隐含波动率的敏感度  
theta | String | 期权价格对剩余期限的敏感度  
leverage | String | 杠杆倍数  
mark_vol | String | 标记波动率  
bid_vol | String | bid波动率  
ask_vol | String | ask波动率  
realized_vol | String | 已实现波动率（目前该字段暂未启用）  
estimated_price | String | 预估交割价  
  
##### 返回示例

    
    
    成功返回：某个期权详细定价
    {
        "instrument_id": "BTC-USD-200103-7500-C",
        "best_ask": "0.011",
        "best_bid": "0.0095",
        "best_ask_size": "305",
        "best_bid_size": "305",
        "delta": "0.3110611374",
        "gamma": "6.9373354861",
        "high_24h": "0.0205",
        "highest_buy": "0.0495",
        "realized_vol": "0",
        "bid_vol": "0.4688",
        "ask_vol": "0.5078",
        "mark_vol": "0.4797",
        "last": "0.01",
        "leverage": "99.4482",
        "low_24h": "0.01",
        "lowest_sell": "0.0005",
        "mark_price": "0.01005549",
        "theta": "-0.0022838375",
        "vega": "0.0003687666",
        "volume_24h": "713",
        "open_interest": "404",
        "estimated_price": "0",
        "timestamp": "2019-12-30T11:05:19.691Z"
    }
    为空返回：某个期权详细定价
    {}
    失败返回：某个期权详细定价
    {
        "error_message": "Invalid underlying index",
        "error_code": "36001"
    }
    

### 公共-获取深度数据

获取期权合约的深度数据。

##### 限速规则：20次/2s

##### HTTP请求

`GET/api/option/v3/instruments/<instrument_id>/book`

##### 请求示例

`GET/api/option/v3/instruments/BTC-USD-190927-12500-C/book`

##### 请求参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
instrument_id | String | 是 | 合约ID，如BTC-USD-190927-12500-C  
size | String | 否 | 返回深度数量，最大值可传200  
  
当size不传时，返回200条；size传0时，返回0条；size最大200，传大于200的数时，返回200条。

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
asks | List | 卖方深度  
bids | List | 买方深度  
timestamp | String | 系统时间戳，ISO 8061格式  
  
##### 解释说明

返回的买卖方深度List中，每一个价格格式为[价格，数量， 强平单数量，订单数量]，比如["5621.8", "125", "0", "5"]

##### 返回示例

    
    
    成功返回：
    {
        "asks": [
            [
                "0.0105",
                "305",
                "0",
                "1"
            ]
        ],
        "bids": [
            [
                "0.009",
                "305",
                "0",
                "1"
            ]
        ],
        "timestamp": "2019-12-30T10:50:59.607Z"
    }
    为空返回：
    {"asks":[],"bids":[],"timestamp":"2019-12-30T10:50:59.607Z"}
    失败返回：
    {
        "error_message": "Instrument does not exist",
        "error_code": "36002"
    }
    

### 公共-获取成交数据

获取期权合约的成交记录。

##### 限速规则：20次/2s

##### HTTP请求

`GET/api/option/v3/instruments/<instrument_id>/trades`

##### 请求示例

`GET/api/option/v3/instruments/BTC-
USD-190927-12500-C/trades?after=18&before=3&limit=50`

##### 请求参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
instrument_id | String | 是 | 合约名称，如BTC-USD-190927-12500-C  
after | String | 否 | 请求此id之前(更旧的数据)的分页内容，传的值为对应的trade_id  
before | String | 否 | 请求此id之后(更新的数据)的分页内容，传的值为对应的trade_id |  
limit | String | 否 | 分页返回的结果集数量，最大为100，不填默认返回100条  
  
##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
trade_id | String | 成交id  
price | String | 成交价格  
qty | String | 成交数量  
side | String | 成交方向：buy/sell  
timestamp | String | 成交时间，ISO 8601格式  
  
##### 返回示例

    
    
    成功返回：
    [
        {
            "timestamp":"2019-12-27T00:06:19.208Z",
            "trade_id":"9",
            "price":"0.016",
            "qty":"50",
            "side":"buy"
        },
        {
            "timestamp":"2019-12-26T21:08:19.277Z",
            "trade_id":"8",
            "price":"0.017",
            "qty":"100",
            "side":"sell"
        }
    ]
    为空返回：
    []
    失败返回：
    {
        "error_message": "Instrument does not exist",
        "error_code": "36002"
    }
    

### 公共-获取某个Ticker信息

获取某个期权合约的最新成交价、买一价、卖一价和对应的量。

##### 限速规则：20次/2s

##### HTTP请求

`GET/api/option/v3/instruments/<instrument_id>/ticker`

##### 请求示例

`GET/api/option/v3/instruments/BTC-USD-190927-12500-C/ticker`

##### 请求参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
instrument_id | String | 是 | 合约名称，如BTC-USD-190927-12500-C  
  
##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
instrument_id | String | 合约名称，如BTC-USD-190927-12500-C  
best_bid | String | 买一价  
best_bid_size | String | 买一价对应的数量  
best_ask | String | 卖一价  
best_ask_size | String | 卖一价对应的数量  
last | String | 最新成交价  
last_qty | String | 最新成交数量  
open_interest | String | 持仓量  
open_24h | String | 24小时开盘价  
high_24h | String | 24小时最高价  
low_24h | String | 24小时最低价  
volume_24h | String | 24小时成交量（按张数统计）  
timestamp | String | 系统时间戳，ISO 8601格式  
  
##### 返回示例

    
    
    成功返回：
    {
        "instrument_id": "BTC-USD-200103-7500-C",
        "best_bid": "0.009",
        "best_ask": "0.0105",
        "last": "0.01",
        "best_bid_size": "305",
        "best_ask_size": "305",
        "last_qty": "0",
        "open_interest": "404",
        "open_24h": "0.0115",
        "high_24h": "0.0205",
        "low_24h": "0.01",
        "volume_24h": "713",
        "timestamp": "2019-12-30T11:08:06.122Z"
    }
    为空返回：
    {}
    失败返回：
    {
        "error_message": "Invalid underlying index",
        "error_code": "36001"
    }
    

### 公共-获取K线数据

获取期权合约的K线数据。

##### 限速规则：20次/2s

##### HTTP请求

`GET/api/option/v3/instruments/<instrument_id>/candles`

##### 请求示例

`GET/api/option/v3/instruments/BTC-
USD-190927-12500-C/candles?start=2019-03-24T02:31:00.000Z&end=2019-03-25T02:55:00.000Z&granularity=86400`

##### 请求参数

**参 数名** | **参 数类型** | **是 否必须** | **描 述**  
---|---|---|---  
instrument_id | String | 是 | 合约名称，如`BTC-USD-190927-12500-C`  
start | String | 否 | 开始时间，ISO 8601格式的时间  
end | String | 否 | 结束时间，ISO 8601格式的时间  
granularity | String | 否 | 时间粒度，以秒为单位，默认值为`60`。如`[60/180/300
900/1800/3600/7200/14400/21600/43200/86400/604800]`，详见下解释说明。  
  
`start`和`end`必须是ISO 8601格式的时间，否则报错；如未提供，默认返回200条数据。

`granularity`必须是枚举范围内的时间颗粒度，否则报错

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
timestamp | String | 开始时间，ISO 8601格式  
open | String | 开盘价格  
high | String | 最高价格  
low | String | 最低价格  
close | String | 收盘价格  
volume | String | 交易量(按张折算)  
currency_volume | String | 交易量(按币种折算)  
  
##### 解释说明

时间粒度`granularity`必须是`[60 180 300 900 1800 3600 7200 14400 21600 43200 86400
604800 2678400 8035200 16070400 31536000]]`中的任一值，否则请求将被拒绝。这些值分别对应的是`[1min 3min
5min 15min 30min 1hour 2hour 4hour 6hour 12hour 1day 1week 1 month 3 months 6
months and 1 year]`的时间段。

K线数据可能不完整。

返回值数组顺分别为是：`[timestamp,open,high,low,close,volume,currency_volume]`

##### 返回示例

    
    
    成功返回：
    [
        [
            "2019-12-30T11:07:00.000Z",
            "0.01",
            "0.01",
            "0.01",
            "0.01",
            "0",
            "0"
        ],
        [
            "2019-12-30T11:06:00.000Z",
            "0.01",
            "0.01",
            "0.01",
            "0.01",
            "0",
            "0"
        ]
    ]
    为空返回：
    []
    失败返回：
    {
        "error_message": "Instrument does not exist",
        "error_code": "36002"
    }
    

### 指数 API

指数接口

### 公共-获取指数成分

获取指数成分。此接口为公共接口，不需要身份验证。

##### 限速规则：20次/2s

##### HTTP请求

`GET/api/index/v3/<instrument_id>/constituents`

##### 请求示例

`GET/api/index/v3/BTC-USD/constituents`

##### 请求参数

参数名 | 参数类型 | 是否必须 | 描述  
---|---|---|---  
instrument_id | String | 是 | 指数币对，如BTC/USD指数则为BTC-USD，如BTC/USDT指数则为BTC-
USDT，如EOS/BTC指数则为EOS-BTC。  
  
##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
last | String | 最新指数价格  
original_price | Price | 原始价格 | 。  
weight | String | 权重  
usd_price | String | 折算成USD价格  
exchange | String | 交易所名称  
instrument_id | String | 指数币对，如BTC指数则为`BTC-USD`  
timestamp | String | 系统时间戳  
symbol | String | 交易所币对名称，如`BTC-USD`  
  
##### 解释说明

指数币对"-"后面的币种表示指数价格的计价单位。

##### 返回示例

    
    
    {
      "code": 0,
      "data": {
        "last": "5562.42250000",
        "constituents": [
          {
            "symbol": "BTC-USD",
            "original_price": "5562.75",
            "weight": "0.25",
            "usd_price": "5562.75",
            "exchange": "GEMINI"
          },
          {
            "symbol": "BTC-USD",
            "original_price": "5562.44",
            "weight": "0.25",
            "usd_price": "5562.44",
            "exchange": "Coinbase"
          },
          {
            "symbol": "BTC-USD",
            "original_price": "5564.5",
            "weight": "0.25",
            "usd_price": "5564.5",
            "exchange": "Bitstamp"
          },
          {
            "symbol": "BTC-USD",
            "original_price": "5560",
            "weight": "0.25",
            "usd_price": "5560",
            "exchange": "kraken"
          }
        ],
        "instrument_id": "BTC-USD",
        "timestamp": "2019-04-23T12:13:03.848Z"
      },
      "detailMsg": "",
      "msg": ""
    }
    

### 获取系统升级状态

获取系统升级和维护的事件状态。

### 公共-获取系统升级状态

获取系统维护的状态。

##### 限速规则：1次/5s

##### HTTP请求

`GET /api/system/v3/status`

##### 签名请求示例

`GET/api/system/v3/status?status=2`

##### 请求参数

**参 数名** | **类 型** | **是 否必填** | **描 述**  
---|---|---|---  
status | String | 否 | 系统维护的状态 0:等待中 ; 1:进行中 ; 2:已完成 不填写此参数，默认返回 status为 `0` 和
`1` 的数据  
  
##### 返回参数

**参 数名** | **类 型** | **描 述**  
---|---|---  
title | String | 系统维护说明的标题  
status | String | 系统维护的状态 0:等待中 ; 1:进行中 ; 2:已完成  
start_time | String | 系统维护的开始时间,格式为ISO 8601标准格式 如: 2020-04-03T16:30:00.000Z  
end_time | String | 系统维护的结束时间,格式为ISO 8601标准格式 如: 2020-04-03T17:40:00.000Z  
href | String | 系统维护详情的超级链接,若无返回值，默认值为空，如 href: ""  
product_type | String | 产品类型 0 :WebSocket ; 1:币币 ; 2:交割 ; 3:永续 ; 4:期权  
  
##### 返回示例

    
    
    [
        {
            "title": "Spot System Optimization",
            "href": "",
            "product_type": "1",
            "status": "2",
            "start_time": "2020-04-10T04:30:00.000Z",
            "end_time": "2020-04-10T04:40:00.000Z"
        },
        {
            "title": "Spot System Optimization",
            "href": "",
            "product_type": "1",
            "status": "2",
            "start_time": "2020-04-10T02:30:00.000Z",
            "end_time": "2020-04-10T02:40:00.000Z"
        }
    
    ]
    

### 这里是RestAPI 错误码

#### 公共错误码（30000-31000）

v3API将使用统一30000开头的错误码

公共错误码包括签名以及各个业务线统一的错误码

错误提示 | 错误码 | http状态码  
---|---|---  
成功（下单成功，撤单成功，操作成功等） | 0 | 200  
长时间没有接收到数据 | 4001 | 400  
缓冲区无法写入数据关闭 | 4002 | 400  
请求头"OK_ACCESS_KEY"不能为空 | 30001 | 400  
请求头"OK_ACCESS_SIGN"不能为空 | 30002 | 400  
请求头"OK_ACCESS_TIMESTAMP"不能为空 | 30003 | 400  
请求头"OK_ACCESS_PASSPHRASE"不能为空 | 30004 | 400  
无效的OK_ACCESS_TIMESTAMP | 30005 | 400  
无效的OK_ACCESS_KEY | 30006 | 400  
无效的Content_Type，请使用"application/json"格式 | 30007 | 400  
请求时间戳过期 | 30008 | 400  
系统错误 | 30009 | 500  
api 校验失败 | 30010 | 401  
无效的ip | 30011 | 400  
无效的授权 | 30012 | 401  
无效的sign | 30013 | 401  
请求太频繁 | 30014 | 429  
请求头"OK_ACCESS_PASSPHRASE"错误 | 30015 | 400  
APIKey所属broker ID不匹配 | 30017 | 400  
APIKey所属域名不匹配 | 30018 | 400  
接口已下线或无法使用 | 30019 | 400  
body 不能为空 | 30020 | 400  
非法的json数据 | 30021 | 400  
Api已被冻结，请联系客服处理 | 30022 | 401  
{0}参数不能为空 必填参数不能为空（各个业务接口返回各个接口的参数） | 30023 | 400  
{0}参数值填写错误（各个业务接口返回各个接口的参数） | 30024 | 400  
{0}参数类型错误（各个业务接口返回各个接口的参数） | 30025 | 400  
用户请求频率过快，超过该接口允许的限额（调用时超过频率限制） | 30026 | 429  
登录失败（操作了别人的订单） | 30027 | 401  
非本人操作（UserID错误等） | 30028 | 400  
用户被冻结 | 30029 | 400  
请求接口失败，请您重试（请求接口失败，请您重试） | 30030 | 400  
币种不存在 | 30031 | 400  
币对不存在 | 30032 | 400  
券商域名不存在（验证APIKey所属交易所，为空，报这个错误） | 30033 | 400  
券商ID不存在（验证APIKey所属交易所ID，为空，报这个错误） | 30034 | 400  
该网站暂不支持交易（该交易所请求，交易时，如果该交易已关闭，则提示报这个错误） | 30035 | 400  
查询接口时，没有相应数据可以返回（各个接口返回各个接口的内容） | 30036 | 400  
接口已下线或无法使用 | 30037 | 400  
撮合引擎正在升级，请大约1分钟后尝试 | 30038 | 400  
  
#### 资金账户错误码（34000-35000）

错误提示 | 错误码 | http状态码  
---|---|---  
提现冻结（提现接口，账户被冻结） | 34001 | 400  
请先添加提现地址（提现接口，地址未添加） | 34002 | 400  
该币种暂不支持提现至XX，敬请谅解（提现接口，地址不正确） | 34003 | 400  
提现手续费小于最小值（提现接口，手续费输入有误） | 34004 | 400  
提现手续费大于最大值（提现接口，提现手续费输入有误） | 34005 | 400  
提现金额小于最小提现金额（最小提现金额提现接口，提现金额输入有误） | 34006 | 400  
提现金额大于单笔提现最大金额（单笔提现最大金额提现接口，提现金额输入有误） | 34007 | 400  
您的余额不足（划转和提现接口，余额不足） | 34008 | 400  
今日提现金额累计超过每日限额（提现接口，提现金额超限） | 34009 | 400  
转账金额必须大于零（划转接口，金额输入不正确） | 34010 | 400  
不符合条件（划转提现接口，不符合条件，如kyc等级不够） | 34011 | 400  
NEO最小提现数量为1，且提现数量必须为整数（提现接口，某些币特殊限制） | 34012 | 400  
需要传instrument ID（划转接口，转入或转出是币币杠杆时instrument ID未传） | 34013 | 400  
划转受限（划转接口，划转资金受限） | 34014 | 400  
子账户不存在（划转接口，转入或转出是子账户时，子账户不存在） | 34015 | 400  
划转冻结（划转接口，源或目的不允许划转） | 34016 | 400  
账户冻结（划转和提现接口，源或目的不允许划转） | 34017 | 400  
交易密码错误（交易密码错误） | 34018 | 400  
您需要绑定邮箱后，才能提现（提现接口，需要先绑定邮箱） | 34019 | 400  
您需设置资金密码后，才能提现（提现接口，需要先设置资金密码） | 34020 | 400  
不是认证地址（提现接口，不是认证的地址） | 34021 | 400  
提现接口，子账号不允许提现 | 34022 | 400  
请于转账前确认已开通合约交易 | 34023 | 400  
请先开通余币宝服务 | 34025 | 400  
划转过于频繁，请降低划转频率 | 34026 | 400  
提现手续费应填写为提币数量的*% | 34027 | 400  
子主账户资金划转时，请使用主账户的APIKey | 34032 | 400  
参数不正确，请参考API文档 | 34036 | 400  
获取子账户余额，account type 不支持 | 34037 | 400  
您在法币区的交易异常，现已被限制划转功能，请您联系在线客服以解除限制 | 34038 | 400  
您在法币区的交易异常，现已被限制划转功能，请您在网页或APP进行法币划转操作以完成身份验证 | 34039 | 400  
  
#### 币币和杠杆错误码（33000-34000）

错误提示 | 错误码 | http状态码  
---|---|---  
您尚未开通此币种对应杠杆业务（没有开通该币种杠杆业务时调接口会报错） | 33001 | 400  
您的此币种对应杠杆账号已被冻结（杠杆账户被冻结） | 33002 | 400  
没有借款余额（没有足够的余额进行借币） | 33003 | 400  
借币数量不能小于最小借币数（借币时借币的数量） | 33004 | 400  
还款金额不能小于等于0（还款金额不对） | 33005 | 400  
没有该借币订单（还币或者查询的时候没有借币订单会报此错误） | 33006 | 400  
不存在该状态 | 33007 | 400  
借款数量超出可借数量（如保证金充足，可调整杠杆倍数以提高可借数量） | 33008 | 400  
用户ID为空 | 33009 | 400  
价格发现第二阶段您不可撤单（集合竞价时候不可以撤单） | 33010 | 400  
没有最新行情信息 | 33011 | 400  
撤单失败 | 33012 | 400  
下单失败 | 33013 | 400  
订单不存在（重复撤单，订单号不对等） | 33014 | 400  
批量操作超过最大数量限制（批量下单，批量撤单时候会出现） | 33015 | 400  
该币对没有开通杠杆业务 | 33016 | 400  
下单大于最大可用余额（下单余额不足） | 33017 | 400  
该参数值填写错误，要填写小于1的数值 | 33018 | 400  
暂不支持该请求（有些交易所不支持杠杆业务） | 33020 | 400  
币与币对不匹配 | 33021 | 400  
币对与订单不匹配 | 33022 | 400  
价格发现期间您只可下市价单（集合竞价时只可以下市价单） | 33023 | 400  
交易金额小于最小交易值 | 33024 | 400  
没有基准币数量（下单时上币时候币对配置不全） | 33025 | 400  
订单已完成交易（撤单时完成交易的订单不能撤单） | 33026 | 400  
订单已撤销或者撤销中（撤单时已经撤销和撤销中的订单不能撤单） | 33027 | 400  
交易价格小数位数超过限制 | 33028 | 400  
交易数量小数位数超过限制 | 33029 | 400  
当前的借币请求系统正在处理中，请稍后重试 | 33032 | 400 |  
集合竞价开始后只能下限价单 | 33034 | 400 |  
该委托类型无法进行撤单操作（fok ioc 订单无法撤销） | 33035 | 400  
超过最大限制数量 | 33036 | 400 |  
买单委托价格需小于等于触发价格的130% | 33037 | 400  
卖单委托价格需大于等于触发价格的70% | 33038 | 400  
回调幅度限制为0<x<=5% | 33039 | 400  
买单激活价格需小于最新成交价格 | 33040 | 400  
卖单激活价格需大于最新成交价格 | 33041 | 400  
委托深度限制为0<x<=1% | 33042 | 400  
委托总数需要大于0 | 33043 | 400  
单笔均值 委托总数 1/1000 <=x<=委托总数 | 33044 | 400  
价格不能为0 包括：触发价格，委托价格，激活价格，价格限制 | 33045 | 400  
扫单范围应该为 0<x<=1% | 33046 | 400  
扫单比例应该为0<x<=100% | 33047 | 400  
单笔上限：委托总数/1000<x<=委托总数 | 33048 | 400  
委托总量应为 X>0 | 33049 | 400  
委托间隔应该为 5<= x<=120s | 33050 | 400  
撤销数量不能超过限制：止盈止损和跟踪委托不超过10单，冰山委托和时间加权委托不超过6单 | 33051 | 400  
client_oid 或 order_id 至少填一个 | 33059 | 400 |  
client_oid 或 order_id 必须且只能填一个 | 33060 | 400 |  
市价委托单笔价值不能超过10万 USD | 33061 | 400  
杠杆倍数过高，借币仓位已超过该杠杆倍数的最大仓位，请重新调整杠杆倍数 | 33062 | 400  
杠杆倍数过低，账户中保证金不足，请重新调整杠杆倍数 | 33063 | 400  
杠杆倍数设置不能小于2，请重新调整杠杆倍数 | 33064 | 400  
杠杆倍数超过最大杠杆倍数，请重新调整杠杆倍数 | 33065 | 400  
  
#### 交割合约错误码（32000-33000）

错误提示 | 错误码 | http状态码  
---|---|---  
合约账户被冻结（当用户被强平后再下单时） | 32001 | 400  
用户合约账户不存在（当用户只是注册了账号没有开通合约） | 32002 | 400  
撤单中，请耐心等待（当用户反复撤单时，或当交割或结算时） | 32003 | 400  
您当前没有未成交的订单（用户撤销未成交订单时） | 32004 | 200  
超过最大下单量（当用户下单量超过规定数量会出现该异常） | 32005 | 400  
委托价格或触发价格超过100万美元（下单当用户委托价格或触发价格超过100万美元） | 32006 | 400  
合约相同方向只支持一个杠杆，当用户有10倍杠杆的持仓，在开20倍的时候等 | 32007 | 400  
当前最多可开仓位（全仓）， 当用户开仓(全仓)的时候大于最多可开仓位 | 32008 | 400  
当前最多可开仓位（逐仓），当用户开仓(逐仓)的时候大于最多可开仓位 | 32009 | 400  
当前有持仓，无法设置杠杆 | 32010 | 400  
虚拟合约状态错误，使用了过期的合约 | 32011 | 400  
合约撤单失败，系统异常时，撤单失败 | 32012 | 400  
币种类型为空 | 32013 | 400  
您的平仓张数大于该仓位的可平张数 | 32014 | 400  
开仓前保证金率低，开仓的是保证金率低于100% | 32015 | 400  
开仓后保证金率低，开仓后的是保证金率低于100% | 32016 | 400  
暂无对手价 | 32017 | 400  
下单数量不足1张，请重新选择 | 32018 | 400  
下单价格高于前一分钟的103%或低于97% | 32019 | 400  
价格不在限价范围内 | 32020 | 400  
杠杆比率错误，设置杆杆的时候不是设置的10倍或者20倍 | 32021 | 400  
根据相关法律，您所在的国家或地区不能使用该功能，有的地区不能开合约 | 32022 | 400  
账户存在借款 | 32023 | 400  
合约交割中，无法下单 | 32024 | 400  
合约清算中，无法下单，清算的时候无法下单 | 32025 | 400  
您的账户已被限制开仓操作，禁止开仓 | 32026 | 400  
撤单数量超过20 | 32027 | 400 |  
用户被强平冻结 | 32028 | 400  
client_oid 或order_id只能传一个 | 32029 | 400  
该委托类型无法进行撤单操作 | 32030 | 400  
client_oid 或者 order_id是必要的参数 | 32031 | 400  
用户不存在 | 32038 | 400  
用户存在挂单或持仓 | 32040 | 400  
当前仓位不存在 | 32041 | 400  
超过保证金最大/最小限额 | 32042 | 400  
账户模式不正确 | 32043 | 400  
下单后保证金率小于对应档位要求的最低保证金率 | 32044 | 400  
委托数量超过100万 | 32045 | 400  
每个用户最多可同时持有100笔未成交的止盈止损 | 32046 | 400  
系统错误，当合约暂停或者极端情况会出现 | 32047 | 500  
跟踪委托回调幅度错误 | 32048 | 400  
每个用户最多可同时持有10笔未成交的跟踪委托 | 32049 | 400  
回调幅度错误 | 32050 | 400  
冰山委托深度错误 | 32051 | 400  
委托数量超过10万 | 32052 | 400  
每个用户最多可同时持有6笔未成交的冰山委托 | 32053 | 400  
禁止开仓 | 32054 | 400  
撤单失败 | 32055 | 400  
冰山委托单笔均值() | 32056 | 400  
委托价为0，暂无法进行市价全平操作 | 32057 | 400  
每个用户最多可同时持有6笔未成交的时间加权 | 32058 | 400  
委托总数量需大于单笔上限 | 32059 | 400  
下单类型错误 | 32060 | 400  
时间加权单笔上限错误（时间加权单笔上线错误） | 32061 | 400  
时间加权扫单范围出错 | 32062 | 400  
时间加权扫单比例出错 | 32063 | 400  
委托间隔错误，5-120s之间 | 32064 | 400  
市价全平的数量大于阈值（BTC 最多为 999 张，其他合约未 9999 张） | 32065 | 400 |  
当前存在挂单，请撤销所有挂单后进行杠杆倍数修改 | 32066 | 400  
调整后，账户权益<所需保证金，请重新调整杠杆倍数 | 32067 | 400  
调整后本仓位保证金不足开仓所需保证金，请重新调整杠杆倍数或追加保证金后调整 | 32068 | 400  
杠杆倍数过低，账户中没有足够的可用保证金可以追加（请重新调整杠杆倍数） | 32069 | 400  
用户有持仓或者挂单（取消持仓或挂单） | 32070 | 400  
您的当前强平模型不支持此操作 | 32071 | 400  
您下单后仓位总张数所处档位的最高可用杠杆为{0}（请修改杠杆后重新下单） | 32072 | 400  
当前币种不支持此操作 | 32073 | 400  
您当前持仓、开仓挂单及本次下单张数已超过该币种最大限制可开张数 | 32074 | 400  
账户风险率过高 | 32075 | 400  
市价全平需先进行撤销平仓挂单操作（市价全平需先进行撤销平仓挂单操作） | 32076 | 400  
您该币种合约账户保证金不足，已触发强制平仓 | 32077 | 400  
您在该币种下存在挂单，请撤销所有挂单后切换 | 32078 | 400  
当前仓位风险过高，请增加保证金或减少仓位后切换 | 32079 | 400  
交割结算后30分钟内不能转出 | 32080 | 400  
您当前全仓仓位最多还可开几张 | 32081 | 400  
您当前逐仓仓位最多还可开几张 | 32082 | 400  
下单张数为整数，请重新下单。 | 32083 | 400  
时间加权单笔均值或冰山委托单笔均值超限 | 32084 | 400  
市价单价格超过限价 | 32086 | 400  
市价单下单数量超出最大值 | 32087 | 400  
订单类型填写错误 | 32088 | 400  
市价委托时不必填委托价格 | 32089 | 400  
平仓挂单撤销失败 | 32090 | 400  
  
#### 永续合约错误码（35000-36000）

错误提示 | 错误码 | http状态码  
---|---|---  
系统错误， 一般是路径参数有误 | 1 | 400  
合约不存在，用户调用不存在的合约时 | 35001 | 400  
合约正在结算时 | 35002 | 400  
合约暂停 | 35003 | 400  
合约待资金结算 | 35004 | 400  
用户不存在，用户未开通合约时 | 35005 | 400  
账户风险率过高，用户下单前后保证金率不足时 | 35008 | 400  
平仓数量大于可平数量（用户下平仓单数量大于可平数量时） | 35010 | 400  
下单数量错误（用户下单数量不足1张时） | 35012 | 400  
下单价格不在限价范围（用户下单价格不在限价范围里时） | 35014 | 400  
杠杆倍数超过允许范围（用户调整的杠杆不在范围内时） | 35015 | 400  
用户存在挂单（用户修改杠杆时） | 35017 | 400  
下单数量超过最大允许的数量（用户下单数量超过设置的最大值时） | 35019 | 400  
下单价格超过最大允许的价格（用户下单价格超过设置的最大值时） | 35020 | 400  
下单数量超过用户当前档位（用户下单数量超过当前档位的最大值时） | 35021 | 400  
合约状态错误（合约处于暂停或关闭状态时） | 35022 | 400  
该用户合约未初始化 | 35024 | 400  
用户账户余额为空 | 35025 | 400  
用户合约配置未初始化 | 35026 | 400  
订单不存在 | 35029 | 400  
批量下单时，超过最大下单数量 | 35030 | 400  
批量撤单时，超过最大撤单数量 | 35031 | 400  
用户状态无效 | 35032 | 400  
缓存中无最新成交价 | 35037 | 400  
开仓张数大于可开张数 | 35039 | 400  
无效的order type，当以对手价下单时，order_type只能选择0:普通委托 | 35040 | 400 |  
价格设置错误 | 35042 | 400  
订单已完成，无法撤单 | 35044  
账户余额是负数 | 35046 | 400  
账户余额不足 | 35047 | 400  
用户合约正在强平冻结 | 35048 | 400  
订单类型不合适 | 35049 | 400  
档位配置为空 | 35050 | 400  
全仓保证金不足 | 35052 | 400  
账户风险过高 | 35053 | 400  
账户余额不足 | 35055 | 400  
无最新成交 | 35057 | 400  
无限价 | 35058 | 400  
必传参数不能为空 | 30023 | 400  
参数错误 | 30024 | 400  
两个参数必须填一个（order id和client id 必须填一个） | 35059 | 400  
两个参数只能填一个（order id和client id 只能填一个） | 35060 | 400  
instrument_id 不正确 | 35061 | 400  
match_price 不正确 | 35062 | 400  
order_size 不正确 | 35063 | 400  
client_oid 不正确 | 35064 | 400  
结算后30分钟内不能转出 | 40029 | 400  
委托间隔错误 | 35066 | 400  
时间加权扫单比例错误 | 35067 | 400  
时间加权扫单范围错误 | 35068 | 400  
时间加权单笔上限错误 | 35069 | 400  
策略委托类型错误 | 35070 | 400  
委托总数量需大于单笔上限 | 35071 | 400  
每个用户最多可同时持有6笔未成交的时间加权单 | 35072 | 400  
委托价为0，暂无法进行市价全平操作 | 35073 | 400 |  
冰山委托单笔均值错误 | 35074 | 400  
撤单失败 | 35075 | 400  
LTC20倍杠杆、禁止开仓 | 35076 | 400  
每个用户最多可同时持有6笔未成交的冰山委托 | 35077 | 400  
委托数量超过10万 | 35078 | 400  
冰山委托深度错误 | 35079 | 400  
回调幅度错误 | 35080 | 400  
跟踪委托回调幅度错误 | 35081 | 400  
您当前持仓、开仓挂单及本次下单张数已超过该币种最大限制可开张数 | 35082 | 400  
每个用户最多可同时持有100笔未成交的止盈止损单 | 35083 | 400  
委托数量超过100万 | 35084 | 400  
委托数量不在正确范围内 | 35085 | 400  
价格超过100万 | 35086 | 400  
价格超过100万 | 35087 | 400  
单笔均值错误 | 35088 | 400  
价格超过100万 | 35089 | 400  
没有可以撤的止盈止损单 | 35090 | 400  
没有可以撤的跟踪委托单 | 35091 | 400  
没有可以撤的冰山委托单 | 35092 | 400  
没有可以撤的时间加权委托单 | 35093 | 400  
止盈止损单最新成交价错误 | 35094 | 400  
合约名非法 | 35095 | 400  
策略委托订单状态错误 | 35096 | 400  
订单状态和订单id不能同时存在 | 35097 | 400  
订单状态或订单id必须存在一个 | 35098 | 400  
策略委托订单id错误 | 35099 | 400  
市价全平操作过于频繁 | 35102 | 400  
持仓量超过市价全平最大限制 | 35103 | 400  
市价委托不支持指定价格 | 35104 | 400  
市价委托单笔数量不能超过最大限制 | 35105 | 200  
订单状态或订单id必须存在一个 | 35106 | 400  
市价止盈止损单笔委托数量不能超过最大限制 | 35107 | 400  
止盈止损市价单不能指定价格 | 35108 | 400  
  
#### 期权合约错误码（36000-37000）

消息内容 | 错误码 | HTTP状态码 | 场景  
---|---|---|---  
Invalid underlying index. | 36001 | 400 | 指数不存在  
Instrument does not exist. | 36002 | 400 | 合约不存在  
Instrument status is invalid. | 36005 | 400 | 合约状态无效  
Account does not exist. | 36101 | 400 | 用户不存在  
Account status is invalid. | 36102 | 400 | 用户状态无效  
Account is suspended due to ongoing liquidation. | 36103 | 400 | 用户处于爆仓冻结  
Account is not enabled for options trading. | 36104 | 400 | 用户未开通期权交易权限  
Please enable the account for option contract. | 36105 | 400 | 请先开通期权合约账户  
Funds cannot be transferred in or out, as account is suspended. | 36106 | 400
| 账户被冻结，暂无法转入或者转出  
Funds cannot be transferred out within 30 minutes after option exercising or
settlement. | 36107 | 400 | 行权或结算后30分钟内不能从合约转出  
Funds cannot be transferred in or out, as equity of the account is less than
zero. | 36108 | 400 | 账户权益小于0，暂无法转入或转出  
Funds cannot be transferred in or out during option exercising or settlement.
| 36109 | 400 | 行权或结算中，暂无法转入或转出  
New order function is blocked. | 36201 | 400 | 下单功能被冻结  
Account does not have permission to short option. | 36202 | 400 | 用户没有期权卖方权限  
Invalid format for client_oid. | 36203 | 400 | client_order_id 格式错误  
Invalid format for request_id. | 36204 | 400 | request_id 格式错误  
Instrument id does not match underlying index. | 36205 | 400 | 合约ID不匹配指数  
Order_id and client_oid can not be used at the same time. | 36206 | 400 |
orderId or client_order_id 只能有一个  
Either order price or fartouch price must be present. | 36207 | 400 |
对手价格和下单价格不能同时为空  
Either order price or size must be present. | 36208 | 400 | 价格和数量不能同时为空  
Either order_id or client_oid must be present. | 36209 | 400 |
order_id和client_oid不能同时为空  
Either order_ids or client_oids must be present. | 36210 | 400 |
order_ids和client_oids不能同时为空  
Exceeding max batch size for order submission. | 36211 | 400 | 超过最大下单数量  
Exceeding max batch size for oder cancellation. | 36212 | 400 | 超过最大修改订单数量  
Exceeding max batch size for order amendment. | 36213 | 400 | 超过最大撤单数量  
Instrument does not have valid bid/ask quote. | 36214 | 400 | 订单深度中无买一卖一价  
Order does not exist. | 36216 | 400 | 订单不存在  
Order submission failed. | 36217 | 400 | 订单下单失败  
Order cancellation failed. | 36218 | 400 | 订单撤销失败  
Order amendment failed. | 36219 | 400 | 订单修改失败  
Order is pending cancel. | 36220 | 400 | 订单正在撤单中  
Order qty is not valid multiple of lot size. | 36221 | 400 | 下单张数不是一手张数的倍数  
Order price is breaching highest buy limit. | 36222 | 400 | 买单高于最高买价  
Order price is breaching lowest sell limit. | 36223 | 400 | 卖单低于最低卖价  
Exceeding max order size. | 36224 | 400 | 超出单笔最大挂单张数  
Exceeding max open order count for instrument. | 36225 | 400 | 超出合约最大挂单单数  
Exceeding max open order count for underlying. | 36226 | 400 | 超出标的最大挂单单数  
Exceeding max open size across all orders for underlying | 36227 | 400 |
超出标的最大挂单张数  
Exceeding max available qty for instrument. | 36228 | 400 | 超出合约最大可开张数  
Exceeding max available qty for underlying. | 36229 | 400 | 超出标的最大可开张数  
Exceeding max position limit for underlying. | 36230 | 400 | 超出标的最大持仓张数  
Order submission failed due to insufficient margin. | 36238 | 400 |
用户保证金不足，下单失败  
Order amendment failed due to insufficient margin. | 36239 | 400 |
用户保证金不足，修改失败  
  
### WebSocketAPI

### 现货

以下是现货V3 WebscoketAPI，除了account有单独频道，其余频道数据对币币和杠杆用户通用。

### 概述

WebSocket是HTML5一种新的协议（Protocol）。它实现了客户端与服务器全双工通信，
使得数据可以快速地双向传播。通过一次简单的握手就可以建立客户端和服务器连接， 服务器根据业务规则可以主动推送信息给客户端。其优点如下：

  * 客户端和服务器进行数据传输时，请求头信息比较小，大概2个字节。
  * 客户端和服务器皆可以主动地发送数据给对方。
  * 不需要多次创建TCP请求和销毁，节约宽带和服务器的资源。

**强 烈建议开发者使用WebSocket API获取市场行情和买卖深度等信息。**

地址： _wss://real.okex.com:8443/ws/v3_

访问时需要科学上网

连接说明：

所有返回数据都进行了压缩，需要用户将接收到的数据进行解压(通过inflate算法进行压缩和解压)。

连接上ws后30s未订阅或订阅后30s内服务器未向用户推送数据，系统会自动断开连接

### 指令格式

请求格式：

    
    
    {"op": "<value>", "args": ["<value1>","<value2>"]}
    

其中 op 的取值为 1--subscribe 订阅； 2-- unsubscribe 取消订阅 ；3--login 登录

args: 取值为频道名，可以定义一个或者多个频道

成功响应格式:

    
    
      {"event": "<value>","channel":"<value>"}
      {"table":"channel","data":"[{"<value1>","<value2>"}]"}
    

其中spot/depth 频道为了区分是首次全量和后续的增量返回格式将会是

    
    
    {"table":"channel", "action":"<value>","data":"[{"<value1>","<value2>"}]"}
    

失败响应格式:

    
    
    {"event":"error","message":"<error_message>","errorCode":"<errorCode>"}
    

### 订阅

用户可以选择订阅一个或者多个频道，多个频道总长度不能超过4096个字节

    
    
    {"op": "subscribe", "args": ["<SubscriptionTopic>"]}
    

说明 ：op 的取值是 subscribe

args 数组内容为频道名称 ：`<channelname>:<filter>`

其中`channelname 是以 business/channel组成

现货推送业务business为spot， channel为此业务下每个具体的名称，如果channel的名字不能以一个字母区分将会以 " _ " 进行连接

例：

    
    
    "spot/ticker:BTC-USDT"or "spot/margin_account:BTC-USDT"
    

filter 是可筛选数据，具体参考每个频道说明

示例：

send:

    
    
    {"op": "subscribe", "args": ["spot/ticker:ETH-USDT","spot/candle60s:ETH-USDT"]}
    

response:

    
    
     {"event":"subscribe","channel":"spot/ticker:ETH-USDT"}
    
     {"event":"subscribe","channel":"spot/candle60s:ETH-USDT"}
    
     {"table":"spot/ticker","data":[{"instrument_id":"ETH-USDT","last":"8.8","best_bid":"3","best_ask":"8.1","open_24h":"5.1","high_24h":"8.8","low_24h":"3",
     "base_volume_24h":"13.77340909","quote_volume_24h":"78.49886361","timestamp":"2018-12-20T03:13:41.664Z"}]}
    
     {"table":"spot/candle60s","data":[{"candle":["2018-12-20T06:18:00.000Z","8.8","8.8","8.8","8.8","0"],"instrument_id":"ETH-USDT"}]}
    

### 取消订阅

可以取消一个或者多个频道

    
    
    {"op": "unsubscribe", "args": [<SubscriptionTopic>]}
    

例如：

请求：

    
    
    {"op": "unsubscribe", "args": ["spot/ticker:BTC-USDT", "spot/candle60s:BTC-USDT"]}
    

返回：

    
    
    {"event":"unsubscribe","channel":"spot/ticker:BTC-USDT"}
    {"event":"unsubscribe","channel":"spot/candle60s:BTC-USDT"}
    

### 登录

签名方式说明参考API概述里的验证部分

登录订阅格式：

    
    
    {"op":"login","args":["<api_key>","<passphrase>","<timestamp>","<sign>"]}
    

响应：

    
    
    {"event":"login","success":true}
    

例：

    
    
    {"op":"login","args":["985d5b66-57ce-40fb-b714-afc0b9787083","123456","1538054050.975",
    "7L+zFQ+CEgGu5rzCj4+BdV2/uUHGqddA9pI6ztsRRPs="]}
    

**api_key** :为用户申请的APIKey

**Passphrase** :为申请v3 api时所填写

**timestamp** :为时间戳 **是 Unix Epoch时间，单位是秒， 时间戳30秒后会过期** 推荐使用time endponit
查询API 服务器的时间，如果你的服务器时间和API 服务器时间有偏差的话

**sign** :为签名字符串，签名规则参照请求说明（API概述验证部分）

**其 中timestamp示例**:const timestamp = '' \+ Date.now() / 1000

**其 中sign 示例** :
sign=CryptoJS.enc.Base64.Stringify(CryptoJS.HmacSHA256(timestamp +'GET'\+
'/users/self/verify', secret))

**method** 一律默认为'GET'。

**requestPath** 一律默认为'/users/self/verify'

如果登录失败会自动断开链接

### 连接限制

**连 接限制**：1次/s

**订 阅限制**：每小时240次

连接上ws后如果一直没有数据返回，30s 后自动断开链接， 建议用户进行以下操作:

1，每次接收到消息后，用户设置一个定时器 ，定时N秒。

2，如果定时器被触发（N 秒内没有收到新消息），发送字符串 'ping'。

3，期待一个文字字符串'pong'作为回应。如果在 N秒内未收到，请发出错误或重新连接。

出现网络问题会自动断开连接

### 校验和机制

此功能可以帮助用户校验深度数据的准确性

每次推送depth频道的深度数据都有时间戳，且有checksum 校验（即checksum值）。 用户订阅depth 频道首次会接收到Example
Response深度，后续推送的都是增量数据。checksum值为：每次增量更新合并后此Example
Response深度的前25档bids和asks组成的字符串的crc32值，
用户可以拿自己的checksum的值和订阅的checksum值进行比较，如果不匹配可以重新订阅。

深度合并规则说明： 首次发送Example Response深度数据，后续每次发送增量的数据，拿增量去遍历Example
Response中的asks和bids的price ,如果发现有相同价格 则看数量，数量为0删除此深度，数量有变化则替换此数据； 无相同价格则按照顺序排序。

计算说明: checksum的值为有符号整型(32位)

checksum的字符串都是以冒号连接的ask和bid中的price和数量，例如：

例子1：bid和ask成对档的情况下，要校验的字符串为：bid:ask:bid:ask:...

    
    
    "data": [{
            "instrument_id": "BTC-USDT",
            "asks": [["3366.8", "9", 10],[ "3368","8",3]],
            "bids": [
                ["3366.1", "7", 0],[ "3366","6",3 ]
            ],
            "timestamp": "2018-12-04T09:38:36.300Z",
            "checksum": -1881014294
        }]
    

该例子对应的checksum字符串为：3366.1:7:3366.8:9:3366:6:3368:8

例子2：bid和ask不成对档的情况 ，要校验的字符串为：bid:ask:ask:ask:...

    
    
    "data": [{
            "instrument_id": "BTC-USDT",
            "asks": [["3366.8", "9", 10],[ "3368","8",3],[ "3372","8",3 ]],
            "bids": [
                ["3366.1", "7", 0]
            ],
            "timestamp": "2018-12-04T09:38:36.300Z",
            "checksum": 831078360
        }]
    

此例子对应的checksum String 将会是 3366.1:7:3366.8:9:3368:8:3372:8

depth 频道用户收到推送数据为：

首次Example Response

    
    
    {
        "table": "spot/depth",
        "action": "partial",
        "data": [{
            "instrument_id": "ETH-USDT",
            "asks": [
                ["8.8", "96.99999966", 1],
                ["9", "39", 3],
                ["9.5", "100", 1],
                ["12", "12", 1],
                ["95", "0.42973686", 3],
                ["11111", "1003.99999795", 1]
            ],
            "bids": [
                ["5", "7", 4],
                ["3", "5", 3],
                ["2.5", "100", 2],
                ["1.5", "100", 1],
                ["1.1", "100", 1],
                ["1", "1004.9998", 1]
            ],
            "timestamp": "2018-12-18T07:27:13.655Z",
            "checksum": 468410539
        }]
    }
    

增量：

    
    
    {
        "table": "spot/depth",
        "action": "update",
        "data": [{
            "instrument_id": "BTC-USDT",
            "asks": [],
            "bids": [
                ["3983", "789", 0]
            ],
            "timestamp": "2018-12-04T09:38:36.300Z",
            "checksum": -1200119424
        }]
    }
    

### 频道说明

无需登录的频道包括：行情频道，K线频道，交易数据频道，资金费率频道，限价范围频道，深度数据频道，标记价格频道

需登录的频道包括：用户账户频道，用户交易频道，用户持仓频道

无需登录的频道名称如下：

spot/ticker // 行情数据频道

spot/trade // 交易信息频道

spot/depth //深度数据频道，首次Example Response，后续增量

spot/depth5 //深度数据频道，每次返回前5档

需登录的频道如下

spot/account //用户币币账户信息频道

spot/margin_account //用户杠杆账户信息频道

spot/order //用户交易数据频道

### 用户币币账户频道

获取币币账户信息，需用用户登录

##### send示例

    
    
    {"op": "subscribe", "args": ["spot/account:BTC"]}
    

其中`spot/account`为频道名，`BTC`为`currency`

##### 返回参数

**参 数名** | **类 型** | **描 述**  
---|---|---  
currency | String | 币种  
balance | String | 余额  
hold | String | 冻结（不可用）  
available | String | 可用于交易或资金划转的数量  
  
##### 返回示例

    
    
    {
        "table":"spot/account",
        "data":[
            {
                "balance":"2.215374581132125",
                "available":"1.632774581132125",
                "currency":"USDT",
                "id":"",
                "hold":"0.5826"
            }
        ]
    }
    

### 用户杠杆账户频道

获取用户杠杆账户信息：

##### send示例

    
    
    {"op": "subscribe", "args": ["spot/margin_account:ETH-USDT"]}
    

其中`spot/margin_account`为频道名，`ETH-USDT`为`instrument_id`

##### 返回参数

**参 数名** | **类 型** | **描 述**  
---|---|---  
instrument_id | String | 杠杆币对名称  
balance | String | 余额  
hold | String | 冻结（不可用）  
available | String | 可用于交易或资金划转的数量  
borrowed | String | 已借币（已借未还的部分）  
lending_fee | String | 利息（未还的利息）  
maint_margin_ratio | String | 维持保证金率  
tiers | String | 当前借币数量档位  
liquidation_price | String | 强平价  
  
##### 返回示例

    
    
    {
        'table': 'spot/margin_account',
        'data': [{
            'currency:USDT': {
                'available': '0.00000000930213',
                'balance': '0.00000000930213',
                'borrowed': '0',
                'hold': '0',
                'lending_fee': '0'
            },
            "liquidation_price":"4.6499",
            'tiers': '1',
            'maint_margin_ratio': '0.08',
            'instrument_id': 'ETH-USDT',
            'currency:ETH': {
                'available': '0.0202516022462802',
                'balance': '0.0202516022462802',
                'borrowed': '0.01',
                'hold': '0',
                'lending_fee': '0.0000001666'
            }
        }]
    }
    

### 用户委托策略频道

用户委托策略频道

##### send示例

    
    
    {"op": "subscribe", "args": ["spot/order_algo:LTC-USDT"]}
    

其中`spot/order_algo`为频道名，`LTC-USDT`为`instrument_id`

##### 返回参数

**参 数名** | **类 型** | **描 述**  
---|---|---  
algo_id | string | 委托ID  
order_type | string | `1`：止盈止损  
`2`：跟踪委托  
`3`：冰山委托  
`4`：时间加权委托  
mode | String | 1、币币 2、杠杆  
size | string | 委托数量  
instrument_id | string | 币对名称  
side | String | buy or sell  
timestamp | string | 委托时间  
status | string | 订单状态  
`1`：待生效  
`2`：已生效  
`3`：已撤销  
`4`：部分生效  
`5`：暂停生效  
`6`：委托失败  
【只有冰山和加权有`4`、`5`状态】  
cancel_code | String | 0:委托超时撤单 1:用户主动撤单 2:余额不足撤单  
  
止盈止损

**参 数名** | **类 型** | **描 述**  
---|---|---  
algo_price | string | 委托价格  
trigger_price | string | 触发价格  
stop_type | string | 1：大于或等于触发价格 2：小于或等于触发价格  
algo_type | String | 1:限价 2:市场价；  
  
跟踪委托

**参 数名** | **类 型** | **描 述**  
---|---|---  
callback_rate | string | 回调幅度  
trigger_price | string | 激活价格  
  
冰山委托

**参 数名** | **类 型** | **描 述**  
---|---|---  
algo_variance | string | 委托深度  
avg_amount | string | 单笔均值  
price_limit | string | 价格限制  
deal_value | string | 已下单数量  
  
时间加权委托

**参 数名** | **类 型** | **描 述**  
---|---|---  
sweep_range | string | 扫单范围  
sweep_ratio | string | 扫单比例  
single_limit | string | 单笔上限  
price_limit | string | 价格限制  
time_interval | string | 委托间隔  
deal_value | string | 已下单数量  
  
##### 返回示例

    
    
    {
        "table":"spot/order_algo",
        "data":[
            {
                "algo_id":"456154",
                "algo_price":"15",
                "cancel_code":"",
                "created_at":"2020-01-08T02:42:36.791Z",
                "instrument_id":"ltc_usdt",
                "mode":"1",
                "order_id":"0",
                "order_type":"1",
                "side":"buy",
                "size":"3",
                "status":"1",
                "stop_type":"2",
                "timestamp":"2020-01-08T02:42:36.796Z",
                "trigger_price":"20"
            }
        ]
    }
    

### 用户交易频道

获取用户交易数据，需用用户登录

##### send示例

    
    
    {"op": "subscribe", "args": ["spot/order:LTC-USDT"]}
    

其中`spot/order`为频道名，`LTC-USDT`为`instrument_id`

##### 返回参数

**参 数名** | **类 型** | **描 述**  
---|---|---  
order_id | String | 订单ID  
client_oid | String | 由用户设置的订单ID  
price | String | 委托价格  
size | String | 委托数量（交易货币数量）  
notional | String | 买入金额，市价买入时返回  
instrument_id | String | 币对名称  
side | String | `buy` 或 `sell`  
type | String | `limit`或`market`（默认是`limit`）  
timestamp | String | 订单状态更新时间  
filled_size | String | 已成交数量  
filled_notional | String | 已成交金额  
margin_trading | String | `1`：币币交易订单  
`2`：杠杆交易订单  
order_type | String | `0`：普通委托  
`1`：只做Maker（Post only）  
`2`：全部成交或立即取消（FOK）  
`3`：立即成交并取消剩余（IOC）  
last_fill_px | String | 最新成交价格（如果没有，推`0`）  
last_fill_id | String | 成交ID。和交易频道trade_id对应（如果没有，推`0`）  
last_fill_qty | String | 最新成交数量（如果没有，推`0`）  
last_fill_time | String | 最新成交时间（如果没有，推`1970-01-01T00:00:00.000Z`）  
state | String | `-2`:失败  
`-1`:撤单成功  
`0`:等待成交  
`1`:部分成交  
`2`:完全成交  
`3`:下单中  
`4`:撤单中  
created_at | String | 订单创建时间  
  
##### 解释说明

`status`为`state`旧版参数，会短期兼容，建议尽早切换`state`。

##### 返回示例

    
    
    {
        "table":"spot/order",
        "data":[
            {
                "client_oid":"",
                "filled_notional":"0",
                "filled_size":"0",
                "instrument_id":"ETC-USDT",
                "last_fill_px":"0",
                "last_fill_qty":"0",
                "last_fill_time":"1970-01-01T00:00:00.000Z",
                "margin_trading":"1",
                "notional":"",
                "order_id":"3576398568830976",
                "order_type":"0",
                "price":"5.826",
                "side":"buy",
                "size":"0.1",
                "state":"0",
                "status":"open",
                "timestamp":"2019-09-24T06:45:11.394Z",
                "type":"limit",
                "created_at":"2019-09-24T06:45:11.394Z"
            }
        ]
    }
    

### 公共-Ticker频道

获取现货最新成交价、买一价、卖一价和24交易量，每100ms推送一次数据。

##### send示例

    
    
    {"op": "subscribe", "args": ["spot/ticker:ETH-USDT"]}
    

其中`spot/ticker`为频道名，`ETH-USDT`为`instrument_id`

##### 返回参数

|  |  
---|---|---  
**参 数名** | **参 数类型** | **描 述**  
instrument_id | String | 币对名称  
last | String | 最新成交价  
last_qty | String | 最新成交的数量  
best_ask | String | 卖一价  
best_ask_size | String | 卖一价对应的量  
best_bid | String | 买一价  
best_bid_size | String | 买一价对应的数量  
open_24h | String | 24小时开盘价  
high_24h | String | 24小时最高价  
low_24h | String | 24小时最低价  
base_volume_24h | String | 24小时成交量，按交易货币统计  
quote_volume_24h | String | 24小时成交量，按计价货币统计  
timestamp | String | 系统时间戳  
  
##### 返回示例

    
    
    {
        "table":"spot/ticker",
        "data":[
            {
                "instrument_id":"ETH-USDT",
                "last":"146.24",
                "last_qty":"0.082483",
                "best_bid":"146.24",
                "best_bid_size":"0.006822",
                "best_ask":"146.25",
                "best_ask_size":"80.541709",
                "open_24h":"147.17",
                "high_24h":"147.48",
                "low_24h":"143.88",
                "base_volume_24h":"117387.58",
                "quote_volume_24h":"17159427.21",
                "timestamp":"2019-12-11T02:31:40.436Z"
            }
        ]
    }
    

### 公共-K线频道

获取现货的K线数据，每500ms推送一次数据。

频道列表：

spot/candle60s // 1分钟K线数据频道

spot/candle60s // 1分钟K线数据频道

spot/candle180s // 3分钟K线数据频道

spot/candle300s // 5分钟K线数据频道

spot/candle900s // 15分钟K线数据频道

spot/candle1800s // 30分钟K线数据频道

spot/candle3600s // 1小时K线数据频道

spot/candle7200s // 2小时K线数据频道

spot/candle14400s // 4小时K线数据频道

spot/candle21600s // 6小时K线数据频道

spot/candle43200s // 12小时K线数据频道

spot/candle86400s // 1day K线数据频道

spot/candle604800s // 1week K线数据频道

##### send示例

    
    
    {"op": "subscribe", "args": ["spot/candle60s:ETH-USDT"]}
    

其中`spot/candle60s`为频道名，`ETH-USDT`为`instrument_id`

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
timestamp | String | 开始时间  
open | String | 开盘价格  
high | String | 最高价格  
low | String | 最低价格  
close | String | 收盘价格  
volume | String | 交易量  
instrument_id | String | 币对  
  
##### 返回示例

    
    
    {
        "table":"spot/candle60s",
        "data":[
            {
                "candle":[
                    "2019-04-16T10:49:00.000Z",
                    "162.03",
                    "162.04",
                    "161.96",
                    "161.98",
                    "336.452694"
                ],
                "instrument_id":"ETH-USDT"
            }
        ]
    }
    

### 公共-交易频道

获取最近的成交数据，无需用户登录，有成交数据就推送。

##### send示例

    
    
    {"op": "subscribe", "args": ["spot/trade:ETH-USDT"]}
    

其中`spot/trade`为频道名，`ETH-USDT`为`instrument_id`

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
trade_id | String | 成交id  
price | String | 成交价格  
size | String | 成交数量  
side | String | 成交方向（`buy` 或 `sell`）  
timestamp | String | 成交时间  
instrument_id | String | 币对  
  
##### 返回示例

    
    
    {
        "table": "spot/trade",
        "data": [{
            "instrument_id": "ETH-USDT",
            "price": "162.12",
            "side": "buy",
            "size": "11.085",
            "timestamp": "2019-05-06T06:51:24.389Z",
            "trade_id": "1210447366"
        }]
    }
    

### 公共-5档深度频道

每次返回前五档的深度数据，此数据为每100毫秒的快照数据，即每隔100毫秒，快照当前时刻市场订单簿的5档深度数据并推送。

##### send示例

    
    
    {"op": "subscribe", "args": ["spot/depth5:ETH-USDT"]}
    

其中`spot/depth5`为频道名，`ETH-USDT`为`instrument_id`

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
asks | List<String> | 卖方深度  
bids | List<String> | 买方深度  
timestamp | String | 时间戳  
instrument_id | String | 币对  
  
asks和bids值数组举例说明： ["411.8","10","8"] 411.8为深度价格，10为此价格数量，8为此深度由几笔订单组成。

##### 返回示例

    
    
    {
        "table":"spot/depth5",
        "data":[
            {
                "asks":[
                    [
                        "161.96",
                        "7.37567",
                        3
                    ],
                    [
                        "161.97",
                        "1.308",
                        1
                    ],
                    [
                        "161.98",
                        "2.463509",
                        1
                    ],
                    [
                        "161.99",
                        "5.185",
                        2
                    ],
                    [
                        "162",
                        "29.184592",
                        5
                    ]
                ],
                "bids":[
                    [
                        "161.94",
                        "4.552355",
                        1
                    ],
                    [
                        "161.91",
                        "7.949",
                        3
                    ],
                    [
                        "161.9",
                        "2.213",
                        1
                    ],
                    [
                        "161.89",
                        "11.999998",
                        1
                    ],
                    [
                        "161.88",
                        "6.585142",
                        3
                    ]
                ],
                "instrument_id":"ETH-USDT",
                "timestamp":"2019-04-16T11:03:03.712Z"
            }
        ]
    }
    

### 公共-400档深度频道

订阅后首次返回市场订单簿的400档深度数据并推送；然后每隔100毫秒，快照这个时间段内有更改的订单簿数据，并推送。

##### send示例

    
    
    {"op": "subscribe", "args": ["spot/depth:ETH-USDT"]}
    

其中`spot/depth`为频道名，`ETH-USDT`为`instrument_id`

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
asks | List<String> | 卖方深度  
bids | List<String> | 买方深度  
timestamp | String | 时间戳  
instrument_id | String | 币对  
checksum | String | 检验和  
  
asks和bids值数组举例说明： ["411.8","10",8"] 411.8为深度价格，10为此价格数量，8为此深度由几笔订单组成。

##### 返回示例

    
    
    首次Example Response
    {
        "table":"spot/depth",
        "action":"partial",
        "data":[
            {
                "instrument_id":"ETH-USDT",
                "asks":[
                    [
                        "162.5",
                        "14.29884",
                        2
                    ],
                    [
                        "162.51",
                        "2.084362",
                        1
                    ],
                   ...
    
                    [
                        "168.51",
                        "7.760755",
                        2
                    ],
                    [
                        "168.57",
                        "0.02",
                        1
                    ]
                ],
                "bids":[
                    [
                        "162.49",
                        "1.556106",
                        3
                    ],
                    [
                        "162.47",
                        "0.00913",
                        1
                    ],
                   ...
    
                    [
                        "155.15",
                        "70",
                        1
                    ],
                    [
                        "155.13",
                        "3",
                        1
                    ]
                ],
                "timestamp":"2019-04-16T10:17:28.507Z",
                "checksum":1141851215
            }
        ]
    }
    
    增量：
    {
        "table":"spot/depth",
        "action":"update",
        "data":[
            {
                "instrument_id":"ETH-USDT",
                "asks":[
                    [
                        "162.5",
                        "0",
                        0
                    ],
                    [
                        "162.61",
                        "1.209",
                        2
                    ],
                    [
                        "168.69",
                        "0.006",
                        1
                    ],
                    [
                        "168.73",
                        "0.002082",
                        1
                    ]
                ],
                "bids":[
                    [
                        "162.49",
                        "1.512544",
                        2
                    ],
                    [
                        "162.47",
                        "0.05333",
                        2
                    ],
                    [
                        "162.46",
                        "14.608508",
                        3
                    ],
                    [
                        "162.43",
                        "10.61874",
                        3
                    ],
                    [
                        "162.41",
                        "27.303906",
                        2
                    ],
                    [
                        "162.4",
                        "14.762929",
                        6
                    ],
                    [
                        "162.39",
                        "11.045909",
                        1
                    ],
                    [
                        "162.36",
                        "19.230907",
                        8
                    ],
                    [
                        "162.31",
                        "3.927598",
                        4
                    ],
                    [
                        "162.3",
                        "5.353085",
                        5
                    ],
                    [
                        "162.29",
                        "6.569261",
                        12
                    ],
                    [
                        "162.25",
                        "8.308575",
                        3
                    ]
                ],
                "timestamp":"2019-04-16T10:17:29.045Z",
                "checksum":227291232
            }
        ]
    }
    

### 公共-400档增量数据频道

订阅后首次返回市场订单簿的400档深度数据并推送；后续只要订单簿深度有变化就推送有更改的数据。

##### send示例

    
    
    {"op": "subscribe", "args": ["spot/depth_l2_tbt:BTC-USDT"]}
    

其中`spot/depth_l2_tbt`为频道名，`BTC-USDT`为`instrument_id`

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
asks | List<String> | 卖方深度  
bids | List<String> | 买方深度  
timestamp | String | 时间戳  
instrument_id | String | 币对 e.g `BTC-USDT`  
checksum | String | 检验和  
  
asks和bids值数组举例说明：

`["8582.97","40","0","40"]`
`8582.97`为深度价格，`40`为此价格的数量，`0`为此价格的现货杠杆强平数量，此数据暂未提供，均返回"0"，`40`为此价格的订单个数。

##### 返回示例

    
    
    {
        "table":"spot/depth_l2_tbt",
        "action":"partial",
        "data":[
            {
                "instrument_id":"BTC-USDT",
                "asks":[
                    ["9580.3","0.20939963","0","2"],
                    ["9582.7","0.33242846","0","3"],
                    ["9583.9","0.41760039","0","1"]
                ],
                "bids":[
                    ["9576.7","0.31658067","0","2"],
                    ["9574.4","0.15659893","0","2"],
                    ["9574.2","0.0105","0","1"]
                ],
                "timestamp":"2020-02-06T03:35:42.492Z"
                "checksum":-2144245240
            }
        ]
    }
    

### 交割合约

以下是交割合约V3 WebscoketAPI

### 概述

WebSocket是HTML5一种新的协议（Protocol）。它实现了客户端与服务器全双工通信，
使得数据可以快速地双向传播。通过一次简单的握手就可以建立客户端和服务器连接， 服务器根据业务规则可以主动推送信息给客户端。其优点如下：

  * 客户端和服务器进行数据传输时，请求头信息比较小，大概2个字节。
  * 客户端和服务器皆可以主动地发送数据给对方。
  * 不需要多次创建TCP请求和销毁，节约宽带和服务器的资源。

**强 烈建议开发者使用WebSocket API获取市场行情和买卖深度等信息。**

地址： _wss://real.okex.com:8443/ws/v3_

访问时需要科学上网

连接说明：

所有返回数据都进行了压缩，需要用户将接收到的数据进行解压(通过inflate算法进行压缩和解压)。

连接上ws后30s未订阅或订阅后30s内服务器未向用户推送数据，系统会自动断开连接

### 指令格式

请求格式：

    
    
    {"op": "<value>", "args": ["<value1>","<value2>"]}
    

其中 op 的取值为 1--subscribe 订阅； 2-- unsubscribe 取消订阅 ；3--login 登录

args: 取值为频道名，可以定义一个或者多个频道

成功响应格式:

    
    
      {"event": "<value>","channel":"<value>"}
      {"table":"channel","data":"[{"<value1>","<value2>"}]"}
    

其中futures/depth 频道为了区分是首次全量和后续的增量返回格式将会是

    
    
    {"table":"channel", "action":"<value>","data":"[{"<value1>","<value2>"}]"}
    

失败响应格式:

    
    
    {"event":"error","message":"<error_message>","errorCode":"<errorCode>"}
    

### 订阅

用户可以选择订阅一个或者多个频道，多个频道总长度不能超过4096个字节。

    
    
    {"op": "subscribe", "args": ["<SubscriptionTopic>"]}
    

说明 ：op 的取值是 subscribe

args 数组内容为频道名称 ：`<channelname>:<filter>`

其中`channelname 是以 business/channel组成

交割推送业务business为futures， channel为此业务下每个具体的名称，如果channel的名字不能以一个字母区分将会以 " _ "
进行连接

例：

    
    
    "futures/ticker:BTC-USD-170310"or "futures/price_range:BTC-USD-170310"
    

filter 是可筛选数据，具体参考每个频道说明

示例：

send:

    
    
    {"op": "subscribe", "args": ["futures/ticker:BTC-USD-170310", "futures/candle60s:BTC-USD-170310"]}
    

response:

    
    
     {"event":"subscribe","channel":"futures/ticker:BTC-USD-170310"}
    
     {"event":"subscribe","channel":"futures/candle60s:BTC-USD-170310"}
    
     {"table":"futures/ticker","data":[{"last":3916.9594,"best_bid":3916.508,"high_24h":3918.1759,
     "low_24h":3916.508,"volume_24h":234,"best_ask":3916.9614,"instrument_id":"BTC-USD-170310","timestamp":"2018-12-20T02:33:01.448Z"}]}
    
     {"table":"futures/candle60s","data":[{"candle":["2018-12-20T02:35:00.000Z","3916.9594",
     "3916.9594","3916.9594","3916.9594","0","0.0"],"instrument_id":"BTC-USD-170310"}]}
    

### 取消订阅

可以取消一个或者多个频道

    
    
    {"op": "unsubscribe", "args": [<SubscriptionTopic>]}
    

例如：

请求：

    
    
    {"op": "unsubscribe", "args": ["futures/ticker:BTC-USD-170310", "futures/candle60s:BTC-USD-170310"]}
    

返回：

    
    
    {"event":"unsubscribe","channel":"futures/ticker:BTC-USD-170310"}
    {"event":"unsubscribe","channel":"futures/candle60s:BTC-USD-170310"}
    

### 登录

签名方式说明参考API概述里的验证部分

登录订阅格式：

    
    
    {"op":"login","args":["<api_key>","<passphrase>","<timestamp>","<sign>"]}
    

响应：

    
    
    {"event":"login","success":true}
    

例：

    
    
    {"op":"login","args":["985d5b66-57ce-40fb-b714-afc0b9787083","123456","1538054050.975",
    "7L+zFQ+CEgGu5rzCj4+BdV2/uUHGqddA9pI6ztsRRPs="]}
    

**api_key** :为用户申请的APIKey

**passphrase** :为申请v3 api时所填写

**timestamp** :为时间戳 **是 Unix Epoch时间，单位是秒， 时间戳30秒后会过期** 推荐使用time endponit
查询API 服务器的时间，如果你的服务器时间和API 服务器时间有偏差的话

**sign** :为签名字符串，签名规则参照请求说明（API概述验证部分）

**其 中timestamp示例**:const timestamp = '' \+ Date.now() / 1000

**其 中sign 示例** :
sign=CryptoJS.enc.Base64.Stringify(CryptoJS.HmacSHA256(timestamp +'GET'\+
'/users/self/verify', secret))

**method** 一律默认为'GET'。

**requestPath** 一律默认为'/users/self/verify'

如果登录失败会自动断开链接

### 连接限制

**连 接限制**：1次/s

**订 阅限制**：每小时240次

连接上ws后如果一直没有数据返回，30s 后自动断开链接， 建议用户进行以下操作:

1，每次接收到消息后，用户设置一个定时器 ，定时N秒。

2，如果定时器被触发（N 秒内没有收到新消息），发送字符串 'ping'。

3，期待一个文字字符串'pong'作为回应。如果在 N秒内未收到，请发出错误或重新连接。

出现网络问题会自动断开连接

### 校验和机制

此功能可以帮助用户校验深度数据的准确性

每次推送depth频道的深度数据都有时间戳，且有checksum 校验（即checksum值）。 用户订阅depth
频道首次会接收到400档深度，后续推送的都是增量数据。checksum值为：每次增量更新后此400档深度的前 25档 bids 和
asks组成的字符串的crc32值， 用户可以拿自己的checksum的值和订阅的checksum值进行比较，如果不匹配可以重新订阅。

深度合并规则说明： 首次发送400档深度数据，后续每次发送增量的数据。去遍历400档中的asks和bids的price ,如果发现有相同价格
则看数量，数量为0删除此深度，数量有变化则替换此数据； 无相同价格则按照顺序排序。

计算说明: checksum的值为有符号整型(32位)

checksum的字符串都是以冒号连接的ask和bid中的price和数量，例如：

例子1：bid和ask成对档的情况下，要校验的字符串为：bid:ask:bid:ask:...

    
    
    "data": [{
            "instrument_id": "BTC-USD-181228",
            "asks": [[3366.8, 9, 10, 3],[ 3368,8,3,4 ]],
            "bids": [
                [3366.1, 7, 0, 3],[ 3366,6,3,4 ]
            ],
            "timestamp": "2018-12-04T09:38:36.300Z",
            "checksum": -1881014294
        }]
    

该例子对应的checksum字符串为：3366.1:7:3366.8:9:3366:6:3368:8

例子2：bid和ask不成对档的情况 ，要校验的字符串为：bid:ask:ask:ask:...

    
    
    "data": [{
            "instrument_id": BTC-USD-181228,
            "asks": [[3366.8, 9, 10, 3],[ 3368,8,3,4 ],[ 3372,8,3,4 ]],
            "bids": [
                [3366.1, 7, 0, 3]
            ],
            "timestamp": "2018-12-04T09:38:36.300Z",
            "checksum": 831078360
        }]
    

此例子对应的checksum String 将会是 3366.1:7:3366.8:9:3368:8:3372:8

depth 频道用户收到推送数据为：

首次400档

    
    
    {
        "table": "futures/depth",
        "action": "partial",
        "data": [{
            "instrument_id": "BTC-USD-181228",
            "asks": [[3983, 888, 10, 3],....],
            "bids": [
                [3983, 789, 0, 3],....
            ],
            "timestamp": "2018-12-04T09:38:36.300Z",
            "checksum": 200119424
        }]
    }
    

后续更新：

    
    
    {
        "table": "futures/depth",
        "action": "update",
        "data": [{
            "instrument_id": "BTC-USD-181228",
            "asks": [],
            "bids": [
                [3983, 789, 0, 3]
            ],
            "timestamp": "2018-12-04T09:38:36.300Z",
            "checksum": -1200119424
        }]
    }
    

### 频道说明

无需登录的频道包括：行情频道，K线频道，交易数据频道，资金费率频道，限价范围频道，深度数据频道，标记价格频道

需登录的频道包括：用户账户频道，用户交易频道，用户持仓频道

无需登录的频道名称如下：

futures/ticker // 行情数据频道

futures/candle60s // 1分钟K线数据频道

futures/trade // 交易信息频道

futures/estimated_price //获取预估交割价

futures/price_range //限价范围频道

futures/depth_l2_tbt //全量深度数据频道，首次全部深度数据，后续有更改的数据。

futures/depth //深度数据频道，首次Example Response，后续有更改的数据。

futures/depth5 //深度数据频道，每次返回前5档。

futures/mark_price// 标记价格频道

需登录的频道如下

futures/account //用户账户信息频道

futures/position //用户持仓信息频道

futures/order //用户交易数据频道

### 用户持仓频道

获取用户持仓信息，需用用户登录

##### send示例

    
    
    {"op": "subscribe", "args": ["futures/position:BTC-USD-170317"]}
    

其中`futures/position`为频道名，`BTC-USD-170317`为`instrument_id`

##### 返回参数

逐仓参数名 | 参数类型 | 描述  
---|---|---  
margin_mode | String | 账户类型  
逐仓:`fixed`  
long_qty | String | 多仓数量  
long_avail_qty | String | 多仓可平仓数量  
long_margin | String | 多仓保证金  
long_liqui_price | String | 多仓强平价格  
long_pnl_ratio | String | 多仓盈亏比  
long_avg_cost | String | 开仓平均价  
long_settlement_price | String | 结算基准价  
realised_pnl | String | 已实现盈余  
long_leverage | String | 多仓杠杆倍数  
short_qty | String | 空仓数量  
short_avail_qty | String | 空仓可平仓数量  
short_margin | String | 空仓保证金  
short_liqui_price | String | 空仓强平价格  
short_pnl_ratio | String | 空仓盈亏比  
short_avg_cost | String | 开仓平均价  
short_settlement_price | String | 结算基准价  
short_leverage | String | 空仓杠杆倍数  
instrument_id | String | 合约ID，如`BTC-USDT-180909`,`BTC-USDT-191227`  
created_at | String | 创建时间  
updated_at | String | 更新时间  
short_margin_ratio | String | 空仓保证金率  
short_maint_margin_ratio | String | 空仓维持保证金率  
short_pnl | String | 空仓收益  
short_unrealised_pnl | String | 空仓未实现盈亏  
short_open_outstanding | string | 空仓开仓冻结张数  
short_settled_pnl | String | 空仓已结算收益  
long_margin_ratio | String | 多仓保证金率  
long_maint_margin_ratio | String | 多仓维持保证金率  
long_pnl | String | 多仓收益  
long_unrealised_pnl | String | 多仓未实现盈亏  
long_open_outstanding | string | 多仓开仓冻结张数  
long_settled_pnl | String | 多仓已结算收益  
last | String | 最新成交价  
timestamp | String | 账户数据更新时间  
  
##### 逐仓返回示例

    
    
    {
        "table":"futures/position",
        "data":[
            {
                "long_qty":"0",
                "long_avail_qty":"0",
                "long_margin":"0",
                "long_liqui_price":"0",
                "long_pnl_ratio":"0.36112873",
                "long_avg_cost":"9840.02",
                "long_settlement_price":"9840.02",
                "realised_pnl":"0",
                "short_qty":"0",
                "short_avail_qty":"0",
                "short_margin":"0",
                "short_liqui_price":"0",
                "short_pnl_ratio":"-0.33163704",
                "short_avg_cost":"9870.15",
                "short_settlement_price":"9870.15",
                "instrument_id":"BTC-USD-190927",
                "long_leverage":"10",
                "short_leverage":"10",
                "created_at":"2019-09-06T03:39:50.019Z",
                "updated_at":"2019-09-20T10:32:56.003Z",
                "timestamp":"2019-09-20T10:32:56.003Z",
                "margin_mode":"fixed",
                "short_margin_ratio":"10000.0",
                "short_maint_margin_ratio":"0.005",
                "short_pnl":"0.0",
                "short_unrealised_pnl":"0.0",
                "long_margin_ratio":"10000.0",
                "long_maint_margin_ratio":"0.005",
                "long_pnl":"0.0",
                "long_unrealised_pnl":"0.0",
                "long_open_outstanding":"2",
                "short_open_outstanding":"0",
                "long_settled_pnl":"0",
                "short_settled_pnl":"0",
                "last":"10206.46"
            }
        ]
    }
    

##### 返回参数

全仓参数名 | 参数类型 | 描述  
---|---|---  
margin_mode | String | 账户类型  
全仓：`crossed`  
liquidation_price | String | 预估强平价  
long_qty | String | 多仓数量  
long_avail_qty | String | 多仓可平仓数量  
long_avg_cost | String | 开仓平均价  
long_settlement_price | String | 结算基准价  
realised_pnl | String | 已实现盈余  
leverage | String | 杠杆倍数  
short_qty | String | 空仓数量  
short_avail_qty | String | 空仓可平仓数量  
short_avg_cost | String | 开仓平均价  
short_settlement_price | String | 结算基准价  
instrument_id | String | 合约ID，如`BTC-USDT-180213`  
created_at | String | 创建时间  
updated_at | String | 更新时间  
short_margin | String | 空仓保证金  
short_pnl | String | 空仓收益  
short_pnl_ratio | String | 空仓收益率  
short_unrealised_pnl | String | 空仓未实现盈亏  
long_margin | String | 多仓保证金  
long_pnl | String | 多仓收益  
long_pnl_ratio | String | 多仓收益率  
long_unrealised_pnl | String | 多仓未实现盈亏  
long_open_outstanding | string | 多仓开仓冻结张数  
short_open_outstanding | string | 空仓开仓冻结张数  
long_settled_pnl | String | 多仓已结算收益  
short_settled_pnl | String | 空仓已结算收益  
last | String | 最新成交价  
timestamp | String | 账户数据更新时间  
  
##### 全仓返回示例

    
    
    {
        "table":"futures/position",
        "data":[
            {
                "long_qty":"0",
                "long_avail_qty":"0",
                "long_avg_cost":"10195.63",
                "long_settlement_price":"10195.63",
                "realised_pnl":"0",
                "short_qty":"0",
                "short_avail_qty":"0",
                "short_avg_cost":"10868.07",
                "short_settlement_price":"10868.07",
                "liquidation_price":"0.0",
                "instrument_id":"BTC-USD-190927",
                "leverage":"10",
                "created_at":"2019-09-06T03:39:50.019Z",
                "updated_at":"2019-09-19T03:54:16.570Z",
                "timestamp":"2019-09-19T03:54:16.570Z",
                "margin_mode":"crossed",
                "short_margin":"0.0",
                "short_pnl":"0.0",
                "short_pnl_ratio":"1.04333472",
                "short_unrealised_pnl":"0.0",
                "long_margin":"0.0",
                "long_pnl":"0.0",
                "long_pnl_ratio":"-0.359905739",
                "long_unrealised_pnl":"0.0",
                "long_open_outstanding":"2",
                "short_open_outstanding":"0",
                "long_settled_pnl":"0",
                "short_settled_pnl":"0",
                "last":"9840.19"
            }
        ]
    }
    

### 用户账户频道

获取账户信息，需用用户登录

##### send示例

    
    
    币本位保证金合约还是使用 目前的格式 示例：{"op": "subscribe", "args": ["futures/account:BTC"]}
    USDT保证的合约，使用underlying 示例：{"op": "subscribe", "args": ["futures/account:BTC-USDT"]}
    

其中`futures/account`为频道名，`BTC`为`币本位保证金合约账户`

##### 返回参数

**全 仓参数名** | **参 数类型** | **描 述**  
---|---|---  
currency | String | 账户余额币种，如：`BTC`,`USDT`  
margin_mode | String | 账户类型  
全仓：`crossed`  
equity | String | 账户权益  
total_avail_balance | String | 账户余额  
margin | String | 已用保证金  
realized_pnl | String | 已实现盈亏  
unrealized_pnl | String | 未实现盈亏  
margin_ratio | String | 保证金率  
margin_frozen | String | 持仓已用保证金  
margin_for_unfilled | String | 挂单冻结保证金  
maint_margin_ratio | String | 维持保证金率  
liqui_mode | string | 强平模式：`tier`（梯度强平）  
available | string | 可用保证金  
open_max | string | 最大可开张数  
can_withdraw | string | 可划转数量  
timestamp | string | 账户数据更新时间  
underlying | string | 标的指数，如：`BTC-USD`,`BTC-USDT`  
  
##### 全仓返回示例

    
    
    {
        "table":"futures/account",
        "data":[
            {
                "BTC":{
                    "available":"0.01",
                    "can_withdraw":"0.01",
                    "currency":"BTC",
                    "equity":"0.01",
                    "liqui_mode":"tier",
                    "maint_margin_ratio":"0.005",
                    "margin":"0",
                    "margin_for_unfilled":"0",
                    "margin_frozen":"0",
                    "margin_mode":"crossed",
                    "margin_ratio":"10000",
                    "open_max":"0",
                    "realized_pnl":"0",
                    "timestamp":"2019-11-01T03:34:15.896Z",
                    "total_avail_balance":"0.01",
                    "underlying":"BTC-USD",
                    "unrealized_pnl":"0"
                }
            }
        ]
    }
    

##### 返回参数

逐仓参数名 | 参数类型 | 描述  
---|---|---  
currency | String | 账户余额币种，如：`BTC`,`USDT`  
margin_mode | String | 账户类型  
逐仓：`fixed`  
instrument_id | String | 合约ID，如`BTC-USD-191227`,`BTC-USDT-191227`  
fixed_balance | String | 逐仓账户余额  
available_qty | String | 逐仓可用余额  
margin_frozen | String | 冻结的保证金(成交以后仓位所需的)  
margin_for_unfilled | String | 挂单冻结保证金  
realized_pnl | String | 已实现盈亏  
unrealized_pnl | String | 未实现盈亏  
equity | String | 账户权益（账户动态权益）  
total_avail_balance | String | 账户余额（账户静态权益）  
liqui_mode | string | 强平模式  
`tier`（梯度强平）  
long_open_max | string | 多仓最大可开张数  
short_open_max | string | 空仓最大可开张数  
can_withdraw | string | 可划转数量  
timestamp | String | 账户数据更新时间  
  
##### 逐仓返回示例

    
    
    {
        "table":"futures/account",
        "data":[
            {
                "BTC":{
                    "can_withdraw":"0.01",
                    "contracts":[
                        {
                            "available_qty":"0.01",
                            "fixed_balance":"0",
                            "instrument_id":"BTC-USD-191227",
                            "long_open_max":"18",
                            "margin_for_unfilled":"0",
                            "margin_frozen":"0",
                            "realized_pnl":"0",
                            "short_open_max":"9",
                            "timestamp":"2019-11-01T03:39:15.293Z",
                            "unrealized_pnl":"0"
                        }
                    ],
                    "currency":"BTC",
                    "equity":"0.01",
                    "liqui_mode":"tier",
                    "margin_mode":"fixed",
                    "timestamp":"2019-11-01T03:39:15.298Z",
                    "total_avail_balance":"0.01"
                }
            }
        ]
    }
    

### 用户交易频道

获取用户交易数据，需用用户登录

##### send示例

    
    
    {"op": "subscribe", "args": ["futures/order:BTC-USD-170317"]}
    

其中`futures/order`为频道名，`BTC-USD-170317`为`instrument_id`

##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
instrument_id | String | 合约ID，如`BTC-USDT-180213`,`BTC-USDT-191227`  
client_oid | String | 由用户设置的订单ID  
size | String | 委托数量  
timestamp | String | 订单状态变化时间  
filled_qty | String | 成交数量  
fee | String | 手续费  
order_id | String | 订单ID  
price | String | 委托价格  
error_code | String | 错误码  
pnl | String | 收益  
price_avg | String | 成交均价  
type | String | 订单类型  
`1`:开多  
`2`:开空  
`3`:平多  
`4`:平空  
contract_val | String | 合约面值  
leverage | String | 杠杆倍数  
order_type | String | `0`：普通委托  
`1`：只做Maker（Post only）  
`2`：全部成交或立即取消（FOK）  
`3`：立即成交并取消剩余（IOC）  
`4`：市价委托  
last_fill_px | String | 最新成交价格（如果没有，推`0`）  
last_fill_id | String | 最新成交id（如果没有，推`0`），和trade频道推送的trade_id一致  
last_fill_qty | String | 最新成交数量（如果没有，推`0`）  
last_fill_time | String | 最新成交时间（如果没有，推`1970-01-01T00:00:00.000Z`）  
state | String | `-2`:失败  
`-1`:撤单成功  
`0`:等待成交  
`1`:部分成交  
`2`:完全成交  
`3`:下单中  
`4`:撤单中  
  
##### 解释说明

`timestamp`会根据订单状态变化分别返回相应的创建时间、成交时间、撤销时间等，具体状态用户可根据state参数判断。

`status`为`state`旧版参数，会短期兼容，建议尽早切换`state`。

##### 返回示例

    
    
    {
        "table":"futures/order",
        "data":[
            {
                "leverage":"100",
                "last_fill_time":"2019-12-12T03:06:39.197Z",
                "filled_qty":"1",
                "fee":"-0.000357715",
                "price_avg":"7154.3",
                "type":"2",
                "client_oid":"",
                "last_fill_qty":"1",
                "instrument_id":"BTC-USDT-191213",
                "last_fill_px":"7154.3",
                "size":"1",
                "price":"7154.3",
                "last_fill_id":"132886",
                "error_code":"0",
                "state":"2",
                "contract_val":"0.0001",
                "order_id":"4022861767908353",
                "order_type":"0",
                "timestamp":"2019-12-12T03:06:39.197Z",
                "status":"2"
            }
        ]
    }
    

### 用户委托策略频道

用户委托策略频道

##### send示例

    
    
    {"op": "subscribe", "args": ["futures/order_algo:LTC-USD-200327"]}
    

其中`futures/order_algo`为频道名，`LTC-USD-200327`为`instrument_id`

##### 返回参数

**参 数名** | **类 型** | **描 述**  
---|---|---  
algo_id | string | 委托ID  
order_type | string | `1`：止盈止损  
`2`：跟踪委托  
`3`：冰山委托  
`4`：时间加权委托  
leverage | String | 杠杆倍数  
size | string | 委托数量  
instrument_id | string | 币对名称  
type | String | 订单类型  
`1`:开多  
`2`:开空  
`3`:平多  
`4`:平空  
timestamp | string | 委托时间  
status | string | 订单状态  
`1`：待生效  
`2`：已生效  
`3`：已撤销  
`4`：部分生效  
`5`：暂停生效  
`6`：委托失败  
【只有冰山和加权有`4`、`5`状态】  
  
止盈止损

**参 数名** | **类 型** | **描 述**  
---|---|---  
algo_price | string | 委托价格  
trigger_price | string | 触发价格  
real_amount | string | 实际委托量  
algo_type | String | 1:限价 2:市场价；  
  
跟踪委托

**参 数名** | **类 型** | **描 述**  
---|---|---  
callback_rate | string | 回调幅度  
trigger_price | string | 激活价格  
real_amount | string | 实际委托量  
  
冰山委托

**参 数名** | **类 型** | **描 述**  
---|---|---  
algo_variance | string | 委托深度  
avg_amount | string | 单笔均值  
price_limit | string | 价格限制  
deal_value | string | 已下单数量  
  
时间加权委托

**参 数名** | **类 型** | **描 述**  
---|---|---  
sweep_range | string | 扫单范围  
sweep_ratio | string | 扫单比例  
single_limit | string | 单笔上限  
price_limit | string | 价格限制  
time_interval | string | 委托间隔  
deal_value | string | 已下单数量  
  
##### 返回示例

    
    
    {
        "table":"futures/order_algo",
        "data":[
            {
                "algo_id":"409",
                "leverage":"10",
                "real_amount":"0",
                "size":"2.0",
                "trigger_price":"47",
                "algo_price":"47",
                "type":"1",
                "order_type":"1",
                "instrument_id":"LTC-USDT-200327",
                "timestamp":"2020-01-08T02:23:53.999Z",
                "status":"1"
            }
        ]
    }
    

### 公共-全量合约信息频道

全量合约订阅频道

每次交割过后有新合约上线且可交易后，就推一次所有币种的全量合约数据（无需登录）。

##### send示例

    
    
    {"op": "subscribe", "args": ["futures/instruments"]}
    

其中`futures/instruments`为频道名

##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
instrument_id | String | 合约ID，如`BTC-USD-190322` ,`BTC-USDT-191227`  
underlying | String | 标的指数，如：`BTC-USD`  
base_currency | String | 交易货币币中，如`BTC-USD`中的`BTC`  
quote_currency | String | 计价货币币种，如：`BTC-USD-190322`中的`USD`  
settlement_currency | String | 盈亏结算和保证金币种，`如BTC`  
contract_val | String | 合约面值(美元)  
listing | String | 上线日期  
delivery | String | 交割日期  
tick_size | String | 下单价格精度  
trade_increment | String | 下单数量精度  
alias | String | 本周: `this_week`  
次周: `next_week`  
季度: `quarter`  
次季度 `bi_quarter`  
is_inverse | String | true or false ,是否 币本位保证金合约  
contract_val_currency | String | 合约面值计价币种 如 USD,BTC,LTC,ETC,XRP,EOS  
  
##### 返回示例

    
    
    {
        "table":"futures/instruments",
        "data":[
            [
                {
                    "instrument_id":"BTC-USD-191115",
                    "underlying_index":"BTC",
                    "quote_currency":"USD",
                    "tick_size":"0.01",
                    "contract_val":"100",
                    "listing":"2019-11-01",
                    "delivery":"2019-11-15",
                    "trade_increment":"1",
                    "alias":"next_week",
                    "underlying":"BTC-USD",
                    "base_currency":"BTC",
                    "settlement_currency":"BTC",
                    "is_inverse":"true",
                    "contract_val_currency":"USD"
                },
                {
                    "instrument_id":"TRX-USD-191115",
                    "underlying_index":"TRX",
                    "quote_currency":"USD",
                    "tick_size":"0.00001",
                    "contract_val":"10",
                    "listing":"2019-11-01",
                    "delivery":"2019-11-15",
                    "trade_increment":"1",
                    "alias":"next_week",
                    "underlying":"TRX-USD",
                    "base_currency":"TRX",
                    "settlement_currency":"TRX",
                    "is_inverse":"true",
                    "contract_val_currency":"USD"
                }
            ]
        ]
    }
    

### 公共-Ticker频道

获取合约的最新成交价、买一价、卖一价和24交易量等信息，每100ms推送一次数据。

##### send示例

    
    
    {"op": "subscribe", "args": ["futures/ticker:BTC-USD-170310"]}
    

其中`futures/ticker`为频道名，`BTC-USD-170310`为`instrument_id`

##### 返回参数

|  |  
---|---|---  
**参 数名** | **参 数类型** | **描 述**  
instrument_id | String | 合约名称，如`BTC-USD-170310`,`BTC-USDT-191227`  
last | String | 最新成交价  
best_ask | String | 卖一价  
best_bid | String | 买一价  
high_24h | String | 24小时最高价  
low_24h | String | 24小时最低价  
volume_24h | String | 24小时成交量（按张数统计）  
timestamp | String | 系统时间戳  
open_interest | String | 持仓量  
open_24h | String | 24小时开盘价  
volume_token_24h | String | 成交量（按币统计）  
last_qty | String | 最新成交的数量  
best_ask_size | String | 卖一价对应的量  
best_bid_size | String | 买一价对应的数量  
  
##### 返回示例

    
    
    {
        "table":"futures/ticker",
        "data":[
            {
                "last":"43.259",
                "open_24h":"49.375",
                "best_bid":"43.282",
                "high_24h":"49.488",
                "low_24h":"41.649",
                "volume_24h":"11295421",
                "volume_token_24h":"2430793.6742",
                "best_ask":"43.317",
                "open_interest":"1726003",
                "instrument_id":"LTC-USD-200327",
                "timestamp":"2020-03-12T08:31:45.288Z",
                "best_bid_size":"171",
                "best_ask_size":"2",
                "last_qty":"1"
            }
        ]
    }
    

### 公共-K线频道

获取合约的K线数据，每500ms推送一次数据。

频道列表：

futures/candle60s // 1分钟K线数据频道

futures/candle180s // 3分钟K线数据频道

futures/candle300s // 5分钟K线数据频道

futures/candle900s // 15分钟K线数据频道

futures/candle1800s // 30分钟K线数据频道

futures/candle3600s // 1小时K线数据频道

futures/candle7200s // 2小时K线数据频道

futures/candle14400s // 4小时K线数据频道

futures/candle21600s // 6小时K线数据频道

futures/candle43200s // 12小时K线数据频道

futures/candle86400s // 1dayK线数据频道

futures/candle604800s // 1week K线数据频道

##### send示例

    
    
    {"op": "subscribe", "args": ["futures/candle180s:BTC-USD-191227"]}
    

其中`futures/candle180s`为频道名，`BTC-USD-191227`为`instrument_id`

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
timestamp | String | 开始时间  
open | String | 开盘价格  
high | String | 最高价格  
low | String | 最低价格  
close | String | 收盘价格  
volume | String | 交易量（张）  
currency_volume | String | 按币折算的交易量  
instrument_id | String | 合约`BTC-USD-170310`,`BTC-USDT-191227`  
  
##### 解释说明

K线衔接规则：

1）次周合约交割时：老次周合约对接新当周合约，老当周合约对接新次周合约，季度合约不变；

2）季度合约交割时：老当周合约对接新季度合约，老季度合于对接新次周合约，老次周合约对接新当周合约；

##### 返回示例

    
    
    {
        "table":"futures/candle180s",
        "data":[
            {
                "candle":[
                    "2019-09-25T10:00:00.000Z",
                    "8533.02",
                    "8553.74",
                    "8527.17",
                    "8548.26",
                    "45247",
                    "529.5858061"
                ],
                "instrument_id":"BTC-USD-191227"
            }
        ]
    }
    

### 公共-交易频道

获取最近的成交数据，无需用户登录，有成交数据就推送。

##### send示例

    
    
    {"op": "subscribe", "args": ["futures/trade:BTC-USD-170310"]}
    

其中`futures/trade`为频道名，`BTC-USD-170310`为`instrument_id`

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
trade_id | String | 成交id  
price | String | 成交价格  
qty | String | 成交数量  
side | String | 成交方向（`buy` 或 `sell`）  
timestamp | String | 成交时间  
instrument_id | String | 合约ID，如`BTC-USD-170310`,`BTC-USDT-191227`  
  
##### 返回示例

    
    
    {
        "table": "futures/trade",
        "data": [{
            "side": "buy",
            "trade_id": "2778148208082945",
            "price": "5556.91",
            "qty": "5",
            "instrument_id": "BTC-USD-190628",
            "timestamp": "2019-05-06T07:19:37.496Z"
        }]
    }
    

### 公共-预估交割价频道

获取预估交割价，交割前一小时开始推送预估交割价，有变化就会推。

##### send示例

    
    
    {"op": "subscribe", "args": ["futures/estimated_price:BTC-USD-170310"]}
    

其中`futures/estimated_price`为频道名，`BTC-USD-170310`为`instrument_id`

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
instrument_id | String | 合约名称，如`BTC-USD-170310`,`BTC-USDT-191227`  
settlement_price | String | 预估交割价格  
timestamp | String | 系统时间戳  
  
##### 返回示例

    
    
    {
            "table": "futures/estimated_price",
            "data": [{
                    "instrument_id": "BTC-USD-170310",
                    "settlement_price": "22616.58",
                    "timestamp": "2018-11-22T10:09:31.541Z"
            }]
    }
    

### 公共-限价频道

获取合约当前交易的最高买价和最低卖价。限价有变化时，5秒推送一次数据，限价没变化时，不推送数据。

##### send示例

    
    
    {"op": "subscribe", "args": ["futures/price_range:BTC-USD-170310"]}
    

其中`futures/price_range`为频道名，`BTC-USD-170310`为`instrument_id`

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
timestamp | String | 系统时间戳  
lowest | String | 最低卖价  
instrument_id | String | 合约名称，如`BTC-USD-170310`,`BTC-USDT-191227`  
highest | String | 最高买价  
  
##### 返回示例

    
    
    {
        "table": "futures/price_range",
        "data": [{
            "highest": "5729.32",
            "lowest": "5392.32",
            "instrument_id": "BTC-USD-190628",
            "timestamp": "2019-05-06T07:19:35.004Z"
        }]
    }
    

### 公共-5档深度频道

每次返回前五档的深度数据，此数据为每100毫秒的快照数据，有深度变化100毫秒推送一次，快照当前时刻市场订单簿的5档深度数据并推送。

##### send示例

    
    
    {"op": "subscribe", "args": ["futures/depth5:BTC-USD-190628"]}
    

其中`futures/depth5`为频道名，`BTC-USD-190628`为`instrument_id`

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
asks | List<String> | 卖方深度  
bids | List<String> | 买方深度  
timestamp | String | 时间戳  
instrument_id | String | 合约ID，如`BTC-USD-190628` ,`BTC-USDT-191227`  
  
asks和bids值数组举例说明：

`["411.8", "10", "1", "4"]`
`411.8`为深度价格，`10`为此价格的合约张数，`1`为此价格的强平单个数，`4`为此价格的订单个数。

##### 返回示例

    
    
    {
        "table": "futures/depth5",
        "data": [{
            "asks": [
                ["5556.82", "11", "0", "1"],
                ["5556.84", "98", "0", "4"],
                ["5556.92", "1", "0", "1"],
                ["5557.6", "4", "0", "1"],
                ["5557.85", "2", "0", "1"]
            ],
            "bids": [
                ["5556.81", "1", "0", "1"],
                ["5556.8", "2", "0", "1"],
                ["5556.79", "1", "0", "1"],
                ["5556.19", "100", "0", "1"],
                ["5556.08", "2", "0", "1"]
            ],
            "instrument_id": "BTC-USD-190628",
            "timestamp": "2019-05-06T07:19:39.348Z"
        }]
    }
    

### 公共-400档深度频道

订阅后首次返回市场订单簿的400档深度数据并推送；有深度变化100毫秒推送一次，快照这个时间段内有更改的订单簿数据，并推送。

##### send示例

    
    
    {"op": "subscribe", "args": ["futures/depth:BTC-USD-191227"]}
    

其中`futures/depth`为频道名，`BTC-USD-191227`为`instrument_id`

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
asks | List<String> | 卖方深度  
bids | List<String> | 买方深度  
timestamp | String | 时间戳  
instrument_id | String | 合约ID，如`BTC-USD-191227`,`BTC-USDT-191227`  
checksum | String | 检验和  
  
asks和bids值数组举例说明：

`["411.8", "10", "1", "4"]`
`411.8`为深度价格，`10`为此价格的合约张数，`1`为此价格的强平单个数，`4`为此价格的订单个数。

##### 返回示例

    
    
    首次400档：
    {
        "table": "futures/depth",
        "action": "partial",
        "data": [{
            "instrument_id": "BTC-USD-191227",
            "asks": [
                ["8476.98","415","0","13"],
                ["8477","7","0","2"],
                ["8477.34","85","0","1"],
                ["8477.56","1","0","1"],
                ...
                ["8505.84","8","0","1"],
                ["8506.37","85","0","1"],
                ["8506.49","2","0","1"],
                ["8506.96","100","0","2"]
            ],
            "bids": [
                ["8476.97","256","0","12"],
                ["8475.55","101","0","1"],
                ["8475.54","100","0","1"],
                ["8475.3","1","0","1"], 
                ...
                ["8447.32","6","0","1"],
                ["8447.02","246","0","1"],
                ["8446.83","24","0","1"],
                ["8446","95","0","3"]
            ],
            "timestamp": "2019-05-06T07:19:39.348Z",
            "checksum": -855196043
        }]
    }
    
    后续更新：
    {
        "table":"futures/depth",
        "action":"update",
        "data":[
            {
                "instrument_id":"BTC-USD-191227",
                "asks":[
                    ["8476.98", "375", "0", "13"],
                    ["8479.61", "0", "0", "0"],
                    ["8480.47", "0", "0", "0"],
                    ["8481.56", "12", "0", "2"],
                    ["8487.07", "0", "0", "0"],
                    ["8507", "4", "0", "2"],
                    ["8507.19", "142", "0", "2"],
                    ["8507.72", "3", "0", "1"]
                ],
                "bids":[
                    ["8470.59", "0", "0", "0"],
                    ["8467.44", "34", "0", "1"],
                    ["8465.33", "0", "0", "0"],
                    ["8463.79", "0", "0", "0"],
                    ["8447.02", "246", "0", "1"],
                    ["8446.83", "24", "0", "1"]
                ],
                "timestamp":"2019-09-26T08:47:43.730Z",
                "checksum":-253252232
            }
        ]
    }
    

### 公共-400档增量数据频道

订阅后首次返回市场订单簿的400档深度数据并推送；后续只要订单簿深度有变化就推送有更改的数据。

##### send示例

    
    
    {"op": "subscribe", "args": ["futures/depth_l2_tbt:BTC-USD-200327"]}
    

其中`futures/depth_l2_tbt`为频道名，`BTC-USD-200327`为`instrument_id`

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
asks | List<String> | 卖方深度  
bids | List<String> | 买方深度  
timestamp | String | 时间戳  
instrument_id | String | 合约ID，如`BTC-USD-200327`  
checksum | String | 检验和  
  
asks和bids值数组举例说明：

`["8582.97","40","0","40"]`
`8582.97`为深度价格，`40`为此价格的合约张数，`0`为此价格的强平单个数，`40`为此价格的订单个数。

##### 返回示例

    
    
    First all entries：
    {
        "table":"futures/depth_l2_tbt",
        "action":"partial",
        "data":[
            {
                "instrument_id":"BTC-USD-200327",
                "asks":[
                    ["9887.69","0","0","0"],
                    ["9889.25","30","0","1"],
                    ["9890.01","0","0","0"]
                ],
                "bids":[
                    [ "9888.3","0","0","0"],
                    ["9878.22","0","0","0"],
                    ["9878.06","1","0","1"]
                ],
                "timestamp":"2020-02-06T03:35:42.509Z"
                "checksum":-2144245240
            }
        ]
    }
    

### 公共-标记价格频道

获取标记价格，标记价格有变化时，200ms推送一次数据，标记价格没变化时，10s推送一次数据。

##### send示例

    
    
    {"op": "subscribe", "args": ["futures/mark_price:BTC-USD-170310"]}
    

其中`futures/mark_price`为频道名，`BTC-USD-170310`为`instrument_id`

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
instrument_id | String | 合约名称，如`BTC-USD-170310`,`BTC-USDT-191227`  
mark_price | String | 标记价格  
timestamp | String | 系统时间戳  
  
为了防止个别用户恶意操控市场导致合约价格波动剧烈，我们根据现货指数和合理基差设定标记价格。

##### 返回示例

    
    
    {
        "table": "futures/mark_price",
        "data": [{
            "instrument_id": "LTC-USD-190628",
            "mark_price": "70.557",
            "timestamp": "2019-05-06T07:19:39.835Z"
        }]
    }
    

### 永续合约

以下是永续合约V3 WebscoketAPI

### 概述

WebSocket是HTML5一种新的协议（Protocol）。它实现了客户端与服务器全双工通信，
使得数据可以快速地双向传播。通过一次简单的握手就可以建立客户端和服务器连接， 服务器根据业务规则可以主动推送信息给客户端。其优点如下：

  * 客户端和服务器进行数据传输时，请求头信息比较小，大概2个字节。
  * 客户端和服务器皆可以主动地发送数据给对方。
  * 不需要多次创建TCP请求和销毁，节约宽带和服务器的资源。

**强 烈建议开发者使用WebSocket API获取市场行情和买卖深度等信息。**

地址： _wss://real.okex.com:8443/ws/v3_

访问时需要科学上网

连接说明：

所有返回数据都进行了压缩，需要用户将接收到的数据进行解压(通过inflate算法进行压缩和解压)。

连接上ws后30s未订阅或订阅后30s内服务器未向用户推送数据，系统会自动断开连接

### 指令格式

请求格式：

    
    
    {"op": "<value>", "args": ["<value1>","<value2>"]}
    

其中 op 的取值为 1--subscribe 订阅； 2-- unsubscribe 取消订阅 ；3--login 登录

args: 取值为频道名，可以定义一个或者多个频道

成功响应格式:

    
    
      {"event": "<value>","channel":"<value>"}
      {"table":"channel","data":"[{"<value1>","<value2>"}]"}
    

其中swap/depth 频道为了区分是首次全量和后续的增量返回格式将会是

    
    
    {"table":"channel", "action":"<value>","data":"[{"<value1>","<value2>"}]"}
    

失败响应格式:

    
    
    {"event":"error","message":"<error_message>","errorCode":"<errorCode>"}
    

### 订阅

用户可以选择订阅一个或者多个频道，多个频道总长度不能超过4096个字节

    
    
    {"op": "subscribe", "args": ["<SubscriptionTopic>"]}
    

说明 ：op 的取值是 subscribe

args 数组内容为频道名称 ：`<channelname>:<filter>`

其中channelname 是以 business/channel组成

永续推送业务business为swap， channel为此业务下每个具体的名称，如果channel的名字不能以一个字母区分将会以 " _ " 进行连接

例：

    
    
    "swap/ticker:BTC-USD-SWAP"or "swap/price_range:BTC-USD-SWAP"
    

filter 是可筛选数据，具体参考每个频道说明

示例：

send:

    
    
    {"op": "subscribe", "args": ["swap/ticker:BTC-USD-SWAP", "swap/candle60s:BTC-USD-SWAP"]}
    

response:

    
    
     {"event": subscribe,"channel":"swap/ticker:BTC-USD-SWAP"}
    
     {"event": subscribe,"channel":"swap/candle60s:BTC-USD-SWAP"}
    
     {"table":"swap/ticker","data":[{"high_24h":"3369","instrument_id":"BTC-USD-SWAP","last":"3299",
     "low_24h":"3112","timestamp":"2018-12-09T08:12:04.659Z","volume_24h":"8389225"}]}
    
     {"table":"swap/candle60s","data":[{"instrument_id":"BTC-USD-SWAP","candle":["2018-12-09T08:12:00.000Z",
     "3299.8","3299.8","3299","3299","82","2.4854"]}]}
    

### 取消订阅

可以取消一个或者多个频道

    
    
    {"op": "unsubscribe", "args": [<SubscriptionTopic>]}
    

例如：

请求：

    
    
    {"op": "unsubscribe", "args": ["swap/ticker:BTC-USD-SWAP", "swap/candle60s:BTC-USD-SWAP"]}
    

返回：

    
    
    {"event":"unsubscribe","channel":"swap/ticker:BTC-USD-SWAP"}
    {"event":"unsubscribe","channel":"swap/candle60s:BTC-USD-SWAP"}
    

### 登录

签名方式说明参考API概述里的验证部分

登录订阅格式：

    
    
    {"op":"login","args":["<api_key>","<passphrase>","<timestamp>","<sign>"]}
    

响应：

    
    
    {"event":"login","success":true}
    

例：

    
    
    {"op":"login","args":["985d5b66-57ce-40fb-b714-afc0b9787083","123456","1538054050.975",
    "7L+zFQ+CEgGu5rzCj4+BdV2/uUHGqddA9pI6ztsRRPs="]}
    

**api_key** :为用户申请的APIKey

**passphrase** :为申请v3 api时所填写

**timestamp** :为时间戳 **是 Unix Epoch时间，单位是秒， 时间戳30秒后会过期** 推荐使用time endponit
查询API 服务器的时间，如果你的服务器时间和API 服务器时间有偏差的话

**sign** :为签名字符串，签名规则参照请求说明（API概述验证部分）

**其 中timestamp示例**:const timestamp = '' \+ Date.now() / 1000

**其 中sign 示例** :
sign=CryptoJS.enc.Base64.Stringify(CryptoJS.HmacSHA256(timestamp +'GET'\+
'/users/self/verify', secret))

**method** 一律默认为'GET'。

**requestPath** 一律默认为'/users/self/verify'

如果登录失败会自动断开链接

### 连接限制

**连 接限制**：1次/s

**订 阅限制**：每小时240次

连接上ws后如果一直没有数据返回，30s 后自动断开链接， 建议用户进行以下操作:

1，每次接收到消息后，用户设置一个定时器 ，定时N秒。

2，如果定时器被触发（N 秒内没有收到新消息），发送字符串 'ping'。

3，期待一个文字字符串'pong'作为回应。如果在 N秒内未收到，请发出错误或重新连接。

出现网络问题会自动断开连接

### 校验和机制

此功能可以帮助用户校验深度数据的准确性

每次推送depth频道的深度数据都有时间戳，且有checksum 校验（即checksum值）。 用户订阅depth 频道首次会接收到Example
Response深度，后续推送的都是增量数据。checksum值为：每次增量更新合并后此Example Response深度的前 25档 bids 和
asks组成的字符串的crc32值， 用户可以拿自己的checksum的值和订阅的checksum值进行比较，如果不匹配可以重新订阅。

深度合并规则说明： 首次发送Example Response深度数据，后续每次发送增量的数据。去遍历Example
Response中的asks和bids的price ,如果发现有相同价格 则看数量，数量为0删除此深度，数量有变化则替换此数据； 无相同价格则按照顺序排序。

计算说明: checksum的值为有符号整型(32位)

checksum的字符串都是以冒号连接的ask和bid中的price和数量，例如：

例子1：bid和ask成对档的情况下，要校验的字符串为：bid:ask:bid:ask:...

    
    
    "data": [{
            "instrument_id": "BTC-USD-SWAP",
            "asks": [["3366.8", "9", 10, 3],[ "3368","8",3,4 ]],
            "bids": [
                ["3366.1", "7", 0, 3],[ "3366","6",3,4 ]
            ],
            "timestamp": "2018-12-04T09:38:36.300Z",
            "checksum": -1881014294
        }]
    

该例子对应的checksum字符串为：3366.1:7:3366.8:9:3366:6:3368:8

例子2：bid和ask不成对档的情况 ，要校验的字符串为：bid:ask:ask:ask:...

    
    
    "data": [{
            "instrument_id": "BTC-USD-SWAP",
            "asks": [["3366.8", "9", 10, 3],[ "3368","8",3,4 ],[ "3372","8",3,4 ]],
            "bids": [
                ["3366.1", "7", 0, 3]
            ],
            "timestamp": "2018-12-04T09:38:36.300Z",
            "checksum": 831078360
        }]
    

此例子对应的checksum String 将会是 3366.1:7:3366.8:9:3368:8:3372:8

depth 频道用户收到推送数据为：

首次Example Response

    
    
    {
        "table": "swap/depth",
        "action": "partial",
        "data": [{
            "instrument_id": "BTC-USD-SWAP",
            "asks": [["3983", "888", 10, 3],....],
            "bids": [
                ["3983", "789", 0, 3],....
            ],
            "timestamp": "2018-12-04T09:38:36.300Z",
            "checksum": 200119424
        }]
    }
    

增量：

    
    
    {
        "table": "swap/depth",
        "action": "update",
        "data": [{
            "instrument_id": "BTC-USD-SWAP",
            "asks": [],
            "bids": [
                ["3983", "789", 0, 3]
            ],
            "timestamp": "2018-12-04T09:38:36.300Z",
            "checksum": -1200119424
        }]
    }
    

### 频道说明

无需登录的频道包括：行情频道，K线频道，交易数据频道，资金费率频道，限价范围频道，深度数据频道，标记价格频道

需登录的频道包括：用户账户频道，用户交易频道，用户持仓频道

无需登录的频道名称如下：

swap/ticker // 行情数据频道

swap/candle60s // 1分钟K线数据频道

swap/trade // 交易信息频道

swap/funding_rate//资金费率频道

swap/price_range//限价范围频道

swap/depth //深度数据频道，首次Example Response，后续增量

swap/depth5 //深度数据频道，每次返回前5档

swap/mark_price// 标记价格频道

需登录的频道如下：

swap/account //用户账户信息频道

swap/position //用户持仓信息频道

swap/order //用户交易数据频道

### 用户持仓频道

获取用户持仓信息，需用用户登录

##### send示例

    
    
    {"op": "subscribe", "args": ["swap/position:BTC-USD-SWAP"]}
    {"op": "subscribe", "args": ["swap/position:BTC-USDT-SWAP"]}
    

其中`swap/ position`为频道名，`BTC-USD-SWAP`为`instrument_id`

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
liquidation_price | String | 预估强平价  
position | String | 持仓数量  
avail_position | String | 可平数量  
avg_cost | String | 开仓平均价  
settlement_price | String | 结算基准价  
instrument_id | String | 合约名称  
leverage | String | 杠杆  
realized_pnl | String | 已实现盈亏  
side | String | 方向（`long`/`short`）  
timestamp | String | 创建时间  
margin | String | 保证金  
margin_mode | String | `fixed`:逐仓  
`crossed`:全仓  
settled_pnl | String | 已结算收益  
last | String | 最新成交价  
maint_margin_ratio | String | 维持保证金率  
open_outstanding | String | 多仓/空仓开仓冻结张数  
  
##### 解释说明

合约持仓返回信息中多仓和空仓部分的已实现盈亏字段是这一合约多空仓已实现盈亏的加总。

##### 返回示例

    
    
    {
        "table":"swap/position",
        "data":[
            {
                "holding":[
                    {
                        "avail_position":"1501",
                        "avg_cost":"231.98",
                        "last":"225.78",
                        "leverage":"50.00",
                        "liquidation_price":"154.48",
                        "maint_margin_ratio":"0.0100",
                        "margin":"1.3296",
                        "position":"1501",
                        "realized_pnl":"-0.0070",
                        "settled_pnl":"-1.9640",
                        "settlement_price":"225.15",
                        "side":"long",
                        "open_outstanding":"2",
                        "timestamp":"2019-10-11T10:43:32.261Z"
                    }
                ],
                "instrument_id":"BCH-USD-SWAP",
                "margin_mode":"crossed",
                "timestamp":"2019-10-11T10:43:32.261Z"
            }
        ]
    }
    

### 用户账户频道

获取账户信息，需用用户登录

##### send示例

    
    
    {"op": "subscribe", "args": ["swap/account:BTC-USD-SWAP"]}
    {"op": "subscribe", "args": ["swap/account:BTC-USDT-SWAP"]}
    

其中`swap/account`为频道名，`BTC-USD-SWAP`为`instrument_id`

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
equity | String | 账户权益  
instrument_id | String | 合约名称  
margin | String | 已用保证金  
margin_frozen | String | 开仓冻结保证金  
margin_ratio | String | 保证金率  
realized_pnl | String | 已实现盈亏  
timestamp | String | 账户数据更新时间  
total_avail_balance | String | 账户余额  
unrealized_pnl | String | 未实现盈亏  
fixed_balance | String | 逐仓账户余额  
margin_mode | String | 账户类型  
逐仓:`fixed`  
全仓:`crossed`  
maint_margin_ratio | String | 维持保证金率  
available_qty | String | 可用保证金  
long_open_max | string | 多仓最大可开张数  
short_open_max | string | 空仓最大可开张数  
  
##### 返回示例

    
    
    {
        "table":"swap/account",
        "data":[
            {
                "equity":"31.7190",
                "fixed_balance":"0.0000",
                "instrument_id":"BCH-USD-SWAP",
                "maint_margin_ratio":"0.0100",
                "margin":"1.3296",
                "margin_frozen":"0.0000",
                "margin_mode":"crossed",
                "margin_ratio":"0.4770",
                "realized_pnl":"-0.0070",
                "timestamp":"2019-10-11T10:43:32.255Z",
                "total_avail_balance":"31.5452",
                "unrealized_pnl":"0.1806",
                "available_qty":"0.01",                          
                "long_open_max":"18",
                "short_open_max":"9"
            }
        ]
    }
    

### 用户交易频道

获取用户交易数据，需用用户登录

##### send示例

    
    
    {"op": "subscribe", "args": ["swap/order:BTC-USD-SWAP"]}
    {"op": "subscribe", "args": ["swap/order:BTC-USDT-SWAP"]}
    

其中`swap/order`为频道名，`BTC-USD-SWAP`为`instrument_id`

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
instrument_id | String | 合约名称，如`BTC-USD-SWAP`  
size | String | 委托数量  
timestamp | String | 订单状态变化时间  
filled_qty | String | 成交数量  
fee | String | 手续费  
error_code | String | error code  
order_id | String | 订单id  
client_oid | String | 用户设置的订单id  
price | String | 委托价格  
price_avg | String | 成交均价  
type | String | `1`:开多  
`2`:开空  
`3`:平多  
`4`:平空  
contract_val | String | 合约面值  
order_type | String | `0`：普通委托  
`1`：只做Maker（Post only）  
`2`：全部成交或立即取消（FOK）  
`3`：立即成交并取消剩余（IOC）  
`4`：市价委托  
last_fill_px | String | 最新成交价格（如果没有，推`0`）  
last_fill_qty | String | 最新成交数量（如果没有，推`0`）  
last_fill_time | String | 最新成交时间（如果没有，推`1970-01-01T00:00:00.000Z`）  
last_fill_id | String | 最新成交ID (如果没有推`0`)，和trade 频道推送的trade ID一致  
state | String | `-2`:失败  
`-1`:撤单成功  
`0`:等待成交  
`1`:部分成交  
`2`:完全成交  
`3`:下单中  
`4`:撤单中  
leverage | String | 杠杆倍数  
  
##### 解释说明

`timestamp`会根据订单状态变化分别返回相应的创建时间、成交时间、撤销时间等，具体状态用户可根据state参数判断。

`status`为`state`旧版参数，会短期兼容，建议尽早切换`state`。

##### 返回示例

    
    
    {
        "table": "swap/order",
        "data": [{
            "last_fill_time": "1970-01-01T00:00:00.000Z",
            "filled_qty": "0",
            "fee": "0.000000",
            "client_oid": "",
            "last_fill_qty": "0",
            "price_avg": "0.0000",
            "type": "2",
            "instrument_id": "XRP-USD-SWAP",
            "last_fill_px": "0",
            "size": "1",
            "price": "0.2935",
            "error_code": "0",
            "contract_val": "10",
            "state": "0",
            "order_id": "6c-a-625f6f638-0",
            "order_type": "0",
            "state": "0",
            "leverage": "10",
            "timestamp": "2019-05-06T07:12:25.679Z"
        }]
    }
    

### 用户委托策略频道

用户委托策略频道

##### send示例

    
    
    {"op": "subscribe", "args": ["swap/order_algo:LTC-USD-SWAP"]}
    {"op": "subscribe", "args": ["swap/order_algo:LTC-USDT-SWAP"]}
    

其中`swap/order_algo`为频道名，`LTC-USD-SWAP`为`instrument_id`

##### 返回参数

**参 数名** | **类 型** | **描 述**  
---|---|---  
algo_id | string | 委托ID  
order_type | string | `1`：止盈止损  
`2`：跟踪委托  
`3`：冰山委托  
`4`：时间加权委托  
leverage | String | 杠杆倍数  
size | string | 委托数量  
instrument_id | string | 币对名称  
type | String | 订单类型  
`1`:开多  
`2`:开空  
`3`:平多  
`4`:平空  
timestamp | string | 委托时间  
status | string | 订单状态  
`1`：待生效  
`2`：已生效  
`3`：已撤销  
`4`：部分生效  
`5`：暂停生效  
`6`：委托失败  
【只有冰山和加权有`4`、`5`状态】  
  
止盈止损

**参 数名** | **类 型** | **描 述**  
---|---|---  
algo_price | string | 委托价格  
trigger_price | string | 触发价格  
algo_type | String | 1:限价 2:市场价；  
  
跟踪委托

**参 数名** | **类 型** | **描 述**  
---|---|---  
callback_rate | string | 回调幅度  
trigger_price | string | 激活价格  
  
冰山委托

**参 数名** | **类 型** | **描 述**  
---|---|---  
algo_variance | string | 委托深度  
avg_amount | string | 单笔均值  
price_limit | string | 价格限制  
  
时间加权委托

**参 数名** | **类 型** | **描 述**  
---|---|---  
sweep_range | string | 扫单范围  
sweep_ratio | string | 扫单比例  
single_limit | string | 单笔上限  
price_limit | string | 价格限制  
time_interval | string | 委托间隔  
  
##### 返回示例

    
    
    {
        "table":"swap/order_algo",
        "data":[
            {
                "algo_id":"342507214297841664",
                "leverage":"50.00",
                "size":"1.0000",
                "trigger_price":"280.00",
                "callback_rate":"0.020",
                "type":"1",
                "instrument_id":"BCH-USD-SWAP",
                "order_type":"2",
                "status":"1",
                "timestamp":"2019-10-11T09:59:41.688Z"
            }
        ]
    }
    

### 公共-Ticker频道

获取平台全部永续合约的最新成交价、买一价、卖一价和24交易量，无需用户登录，有成交数据就推送。

##### send示例

    
    
    {"op": "subscribe", "args": ["swap/ticker:BTC-USD-SWAP"]}
    {"op": "subscribe", "args": ["swap/ticker:BTC-USDT-SWAP"]}
    

其中`swap/ticker`为频道名，`BTC-USD-SWAP`为`instrument_id`

##### 返回参数

|  |  
---|---|---  
**参 数名** | **参 数类型** | **描 述**  
instrument_id | String | 合约名称，如`BTC-USD-SWAP`  
best_bid | String | 买一价  
best_ask | String | 卖一价  
last | String | 最新成交价  
high_24h | String | 24小时最高价  
low_24h | String | 24小时最低价  
volume_24h | String | 24小时成交量（按张数统计）  
volume_token_24h | String | 24小时成交量（按币统计）  
timestamp | String | 系统时间戳  
open_interest | string | 持仓量  
open_24h | string | 24小时开盘价  
last_qty | String | 最新成交的数量  
best_ask_size | String | 卖一价对应的量  
best_bid_size | String | 买一价对应的数量  
  
##### 返回示例

    
    
    {
        "table":"swap/ticker",
        "data":[
            {
                "last":"170.91",
                "open_24h":"198.4",
                "best_bid":"170.92",
                "high_24h":"199.03",
                "low_24h":"166",
                "volume_24h":"31943233",
                "volume_token_24h":"1730040.0174",
                "best_ask":"170.97",
                "open_interest":"4162489",
                "instrument_id":"ETH-USD-SWAP",
                "timestamp":"2020-03-12T08:30:41.738Z",
                "best_bid_size":"101",
                "best_ask_size":"2050",
                "last_qty":"1"
            }
        ]
    }
    

### 公共-K线频道

获取合约的K线数据，每500ms推送一次数据。

频道列表：

swap/candle60s // 1分钟K线数据频道

swap/candle180s // 3分钟K线数据频道

swap/candle300s // 5分钟K线数据频道

swap/candle900s // 15分钟K线数据频道

swap/candle1800s // 30分钟K线数据频道

swap/candle3600s // 1小时K线数据频道

swap/candle7200s // 2小时K线数据频道

swap/candle14400s // 4小时K线数据频道

swap/candle21600s // 6小时K线数据频道

swap/candle43200s // 12小时K线数据频道

swap/candle86400s // 1day K线数据频道

swap/candle604800s // 1week K线数据频道

##### send示例

    
    
    {"op": "subscribe", "args": ["swap/candle60s:BTC-USD-SWAP"]}
    

其中`swap/candle60s`为频道名，`BTC-USD-SWAP`为`instrument_id`

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
timestamp | String | 开始时间  
open | String | 开盘价格  
high | String | 最高价格  
low | String | 最低价格  
close | String | 收盘价格  
volume | String | 交易量（张）  
currency_volume | String | 按币折算的交易量  
instrument_id | String | 合约`BTC-USD-SWAP`  
  
##### 返回示例

    
    
    {
        "table": "swap/candle60s",
        "data": [{
            "instrument_id": "BTC-USD-SWAP",
            "candle": ["2019-05-06T06:51:00.000Z", "5613", "5613", "5611.9", "5611.9", "1218", "21.7009"]
        }]
    }
    

### 公共-交易频道

获取最近的成交数据，无需用户登录，有成交数据就推送。

##### send示例

    
    
    {"op": "subscribe", "args": ["swap/trade:BTC-USD-SWAP"]}
    {"op": "subscribe", "args": ["swap/trade:BTC-USDT-SWAP"]}
    

其中`swap/trade`为频道名，`BTC-USD-SWAP`为`instrument_id`

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
trade_id | String | 成交id  
price | String | 成交价格  
size | String | 成交数量  
side | String | 成交方向（`buy` 或 `sell`）  
timestamp | String | 成交时间  
instrument_id | String | `BTC-USD-SWAP`  
  
##### 返回示例

    
    
    {
        "table": "swap/trade",
        "data": [{
            "instrument_id": "BTC-USD-SWAP",
            "price": "5611.9",
            "side": "buy",
            "size": "2",
            "timestamp": "2019-05-06T06:51:24.389Z",
            "trade_id": "227897880202387456"
        }]
    }
    

### 公共-资金费率频道

获取合约资金费率，一分钟推送一次数据。

##### send示例

    
    
    {"op": "subscribe", "args": ["swap/funding_rate:BTC-USD-SWAP"]}
    {"op": "subscribe", "args": ["swap/funding_rate:BTC-USDT-SWAP"]}
    

其中`swap/funding_rate`为频道名，`BTC-USD-SWAP`为`instrument_id`

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
interest_rate | String | 利率  
instrument_id | String | 合约名称，如`BTC-USD-SWAP`  
funding_time | String | 当期资金费率时间  
funding_rate | String | 当期资金费率  
estimated_rate | String | 下一期预测资金费率  
settlement_time | String | 结算时间  
  
##### 返回示例

    
    
    {
        "table":"swap/funding_rate",
        "data":[
            {
                "estimated_rate":"0.00019",
                "funding_rate":"0.00022993",
                "funding_time":"2019-10-11T16:00:00.000Z",
                "instrument_id":"BTC-USD-SWAP",
                "interest_rate":"0",
                "settlement_time":"2019-10-12T08:00:00.000Z"
            }
        ]
    }
    

### 公共-限价频道

获取合约当前交易的最高买价和最低卖价，五秒钟推送一次数据。

##### send示例

    
    
    {"op": "subscribe", "args": ["swap/price_range:BTC-USD-SWAP"]}
    {"op": "subscribe", "args": ["swap/price_range:BTC-USDT-SWAP"]}
    

其中`swap/ price_range`为频道名，`BTC-USD-SWAP`为`instrument_id`

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
timestamp | String | 系统时间戳  
lowest | String | 最低卖价  
instrument_id | String | 合约名称，如`BTC-USD-SWAP`  
highest | String | 最高买价  
  
##### 返回示例

    
    
    {
        "table": "swap/price_range",
        "data": [{
            "highest": "5665.9",
            "instrument_id": "BTC-USD-SWAP",
            "lowest": "5553.6",
            "timestamp": "2019-05-06T06:51:20.012Z"
        }]
    }
    

### 公共-5档深度频道

每次返回前五档的深度数据，此数据为每100毫秒的快照数据，即每隔100毫秒，快照当前时刻市场订单簿的5档深度数据并推送。

##### send示例

    
    
    {"op": "subscribe", "args": ["swap/depth5:BTC-USD-SWAP"]}
    {"op": "subscribe", "args": ["swap/depth5:BTC-USDT-SWAP"]}
    

其中`swap/depth5`为频道名，`BTC-USD-SWAP`为`instrument_id`

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
asks | List<String> | 卖方深度  
bids | List<String> | 买方深度  
timestamp | String | 时间戳  
instrument_id | String | 合约ID  
  
asks和bids值数组举例说明： `["411.8", "10", "1", "4"]`
`411.8`为深度价格，`10`为此价格的合约张数，`1`为此价格的强平单个数，`4`为此价格的订单个数。

##### 返回示例

    
    
    {
        "table": "swap/depth5",
        "data": [{
            "asks": [
                ["5621.7", "58", "0", "2"],
                ["5621.8", "125", "0", "5"],
                ["5622", "84", "0", "2"],
                ["5622.5", "6", "0", "1"],
                ["5623", "1", "0", "1"]
            ],
            "bids": [
                ["5621.3", "287", "0", "8"],
                ["5621.2", "41", "0", "1"],
                ["5621.1", "2", "0", "1"],
                ["5621", "26", "0", "2"],
                ["5620.9", "640", "0", "1"]
            ],
            "instrument_id": "BTC-USD-SWAP",
            "timestamp": "2019-05-06T07:03:33.048Z"
        }]
    }
    

### 公共-400档深度频道

订阅后首次返回市场订单簿的Example Response深度数据并推送；然后每隔100毫秒，快照这个时间段内有更改的订单簿数据，并推送。

##### send示例

    
    
    {"op": "subscribe", "args": ["swap/depth:BTC-USD-SWAP"]}
    {"op": "subscribe", "args": ["swap/depth:BTC-USDT-SWAP"]}
    

其中`swap/depth`为频道名，`BTC-USD-SWAP`为`instrument_id`

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
asks | List<String> | 卖方深度  
bids | List<String> | 买方深度  
timestamp | String | 时间戳  
instrument_id | String | 合约ID  
checksum | String | 检验和  
  
asks和bids值数组举例说明：

`["411.8", "10", "1", "4"]`
`411.8`为深度价格，`10`为此价格的合约张数，`1`为此价格的强平单个数，`4`为此价格的订单个数。

##### 返回示例

    
    
    首次Example Response
    
    {
        "table": "swap/depth",
        "action": "update",
        "data": [{
            "instrument_id": "BTC-USD-SWAP",
            "asks": [
                ["5621.7", "58", "0", "2"],
                ["5621.8", "125", "0", "5"],
                ["5621.9", "0", "0", "0"],
                ["5622", "84", "0", "2"],
                ["5623.5", "0", "0", "0"],
                ["5624.2", "4", "0", "1"],
                ["5625.1", "0", "0", "0"],
                ["5625.9", "0", "0", "0"],
                ["5629.3", "2", "0", "1"],
                ["5650", "187", "0", "8"],
                ["5789", "1", "0", "1"]
            ],
            "bids": [
                ["5621.3", "287", "0", "8"],
                ["5621.2", "41", "0", "1"],
                ["5621.1", "2", "0", "1"],
                ["5621", "26", "0", "2"],
                ["5620.8", "194", "0", "2"],
                ["5620", "2", "0", "1"],
                ["5618.8", "204", "0", "2"],
                ["5618.4", "0", "0", "0"],
                ["5617.2", "2", "0", "1"],
                ["5609.9", "0", "0", "0"],
                ["5433", "0", "0", "0"],
                ["5430", "0", "0", "0"]
            ],
            "timestamp": "2019-05-06T07:03:33.048Z",
            "checksum": -186865074
        }]
    

### 公共-400档增量数据频道

订阅后首次返回市场订单簿的400档深度数据并推送；后续只要订单簿深度有变化就推送有更改的数据。

##### send示例

    
    
    {"op": "subscribe", "args": ["swap/depth_l2_tbt:BTC-USD-SWAP"]}
    

其中`swap/depth_l2_tbt`为频道名，`BTC-USD-SWAP`为`instrument_id`

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
asks | List<String> | 卖方深度  
bids | List<String> | 买方深度  
timestamp | String | 时间戳  
instrument_id | String | 合约ID e.g`BTC-USD-SWAP`  
checksum | String | 检验和  
  
asks和bids值数组举例说明： `["411.8", "10", "1", "4"]`
`411.8`为深度价格，`10`为此价格的合约张数，`1`为此价格的强平单个数，`4`为此价格的订单个数。

##### 返回示例

    
    
    {
        "table":"swap/depth_l2_tbt",
        "action":"partial",
        "data":[
            {
                "instrument_id":"BTC-USD-SWAP",
                "asks":[
                    ["9608.6","2","0","1"],
                    ["9614.5","8","0","1"],
                    ["9614.6","130","0","2"]
                ],
                "bids":[
                    ["9596","26","0","2"],
                    ["9595.9","23","0","1"],
                    ["9576.1","0","0","0"]
                ],
                "timestamp":"2020-02-06T03:46:52.583Z"
                "checksum":-2144245240
            }
        ]
    }
    

### 公共-标记价格频道

获取标记价格，标记价格有变化时就会推送一次数据，标记价格没变化时，一分钟推送一次数据。

##### send示例

    
    
    {"op": "subscribe", "args": ["swap/mark_price:BTC-USD-SWAP"]}
    {"op": "subscribe", "args": ["swap/mark_price:BTC-USDT-SWAP"]}
    

其中`swap/mark_price`为频道名，`BTC-USD-SWAP`为`instrument_id`

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
instrument_id | String | 合约名称，如`BTC-USD-SWAP`  
mark_price | String | 标记价格  
timestamp | String | 系统时间戳  
  
为了防止个别用户恶意操控市场导致合约价格波动剧烈，我们根据现货指数和合理基差设定标记价格。

##### 返回示例

    
    
    {
        "table": "swap/mark_price",
        "data": [{
            "instrument_id": "BTC-USD-SWAP",
            "mark_price": "5620.9",
            "timestamp": "2019-05-06T07:03:33.799Z"
        }]
    }
    

### 期权合约

以下是期权V3 WebscoketAPI

### 频道说明

无需登录的频道包括：合约信息频道，期权详细定价频道，K线频道，ticker频道，最新成交频道，5档深度频道，400档深度频道

需登录的频道包括：用户交易频道，用户持仓频道，用户账户频道

无需登录的频道名称如下：

option/instruments // 合约信息频道

option/candle60s // 1分钟K线数据频道 (其他更多时间粒度请见具体频道说明)

option/summary // 期权详细定价频道

option/trade// 最新成交频道

option/depth5 //深度数据频道，每次返回前5档

option/depth //深度数据频道，首次400档，后续增量

option/ticker //ticker频道

需登录的频道如下：

option/account //用户账户频道

option/position //用户持仓频道

option/order //用户交易频道

### 用户持仓频道

获取用户持仓信息，需要用户登录。

因为标记价格变化、期权市值等变化也会引发该频道推送。同一标的指数下多个合约的持仓，会分多次推送，每次推一个合约的持仓。

用户可以先通过REST查询持仓的全量列表，然后订阅该频道接收单个合约的持仓信息，进行本地持仓的更新维护。

##### send示例

    
    
    {"op": "subscribe", "args": ["option/position:BTC-USD"]}
    

其中option/position为频道名，BTC-USD为标的指数。

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
instrument_id | String | 合约ID，如BTC-USD-190927-12500-C  
position | String | 净持仓数量  
avg_cost | String | 开仓平均价  
avail_position | String | 可平仓数量  
settlement_price | String | 上期结算基准价  
total_pnl | String | 不含手续费的持仓收益，可跨期 (markPx - avgCost) _Pos_ multiplier  
pnl_ratio | String | 收益率 sideFactor * (markPx/avgCost - 1)  
realized_pnl | String | 当期已实现收益  
unrealized_pnl | String | 当期未实现收益  
pos_margin | String | 持仓保证金（即初始保证金），只有标准账户提供  
option_value | String | 期权市值  
created_at | String | 仓位建立时间，ISO 8601格式  
updated_at | String | 最后一次仓位变化时间，ISO 8601格式  
  
##### 返回示例

    
    
    {
        "table": "option/position",
        "data": [{
                "instrument_id":"BTC-USD-190927-12500-C",
                "position":"20",
                "avg_cost":"3.26",
                "avail_position":"20",
                "settlement_price":"0.017",
                "total_pnl":"50",
                "pnl_ratio":"0.3",
                "realized_pnl":"40",
                "unrealized_pnl":"10",
                "pos_margin":"100",
                "option_value":"70",
                "created_at":"2019-08-30T03:09:20.315Z",
                "updated_at":"2019-08-30T03:40:18.318Z"
            }
        ]
    }
    

### 用户账户频道

获取账户信息，需要用户登录。

因为标记价格变化、期权市值等变化也会引发该频道推送。

##### send示例

    
    
    {"op": "subscribe", "args": ["option/account:BTC-USD"]}
    

其中option/account为频道名，BTC-USD为标的指数。

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
currency | String | 账户币种, 如BTC  
underlying | String | 标的指数，如BTC-USD  
equity | String | 权益  
total_avail_balance | String | 总余额  
margin_balance | String | 保证金余额  
margin_frozen | String | 已用保证金（IMR，包含挂单和持仓保证金）  
avail_margin | String | 可用保证金  
margin_for_unfilled | String | 总挂单保证金  
maintenance_margin | String | 持仓最低维持保证金  
realized_pnl | String | 当期已实现盈亏汇总  
unrealized_pnl | String | 当期未实现盈亏汇总  
option_value | String | 期权总市值  
delta | String | 账户总delta  
vega | String | 账户总vega  
gamma | String | 账户总gamma  
theta | String | 账户总theta  
risk_factor | String | 风险乘数 （目前该字段暂未启用）  
margin_multiplier | String | 规模乘数 （目前该字段暂未启用）  
account_status | String | "0": 正常，"1": 延迟减仓中，"2": 减仓中  
  
##### 返回示例

    
    
    {
        "table": "option/account",
        "data": [{
                "currency":"BTC",
                "underlying":"BTC-USD",
                "equity":"108.61168",
                "total_avail_balance":"108.61168",
                "margin_for_unfilled":"0.00327",
                "margin_frozen":"0.00327",
                "maintenance_margin":"0",
                "realized_pnl":"0",
                "unrealized_pnl":"0",
                "option_value":"0",
                "delta":"0",
                "vega":"0",
                "gamma":"0",
                "theta":"0",
                "risk_factor":"1",
                "margin_multiplier":"1",
                "account_status":"0"
            }
        ]
    }
    

### 用户交易频道

获取用户交易数据，需要用户登录

##### send示例

    
    
    {"op": "subscribe", "args": ["option/order:BTC-USD"]}
    

其中option/order为频道名，BTC-USD为标的指数。

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
order_id | String | 订单ID  
client_oid | String | 由您设置的订单ID来识别您的订单  
timestamp | String | 状态变更时间，ISO 8601格式  
underlying | String | 标的指数，如BTC-USD  
instrument_id | String | 合约名称，如BTC-USD-190927-12500-C  
size | String | 委托数量  
price | String | 委托价格  
side | String | 订单方向(buy/sell)  
filled_qty | String | 成交数量  
price_avg | String | 成交均价（如果成交数量为0，该字段也为0）  
fee | String | 手续费  
contract_val | String | 合约面值（即合约乘数）  
last_fill_px | String | 最新成交价格（如没有成交，为0）  
last_fill_qty | String | 最新成交数量（如没有成交，为0）  
last_fill_id | String | 最新成交id（如果没有，推`0`），和trade频道推送的trade_id一致  
order_type | String | 0：普通委托  
last_request_id | String | 相应修改操作的request_id（如没有修改，推""）  
last_amend_result | String | 相应修改操作的结果，"-1"： 失败，"0"：
成功，"1"：自动撤单（因为修改导致的订单自动撤销）  
state | String | 订单状态("-2":失败, "-1":撤单成功, "0":等待成交 , "1":部分成交, "2":完全成交,
"3":下单中, "4":撤单中, "5": 修改中）  
type | String | 区分用户订单的属性  
1.买入，2.卖出，11.强平卖出，12.强平买入，13.减仓卖出，14.减仓买入  
  
##### 返回示例

    
    
    {
        "table":"option/order",
        "data":[
            {
                "client_oid":"",
                "contract_val":"0.1000",
                "event_code":"0",
                "event_message":"",
                "fee":"0",
                "filled_qty":"0",
                "instrument_id":"BTC-USD-200103-7500-C",
                "last_amend_result":"",
                "last_fill_id":"0",
                "last_fill_px":"0.0",
                "last_fill_qty":"0",
                "last_fill_time":"1970-01-01T00:00:00.000Z",
                "last_request_id":"",
                "order_id":"132157792098263040",
                "order_type":"0",
                "price":"0.003",
                "price_avg":"0",
                "side":"buy",
                "size":"1",
                "state":"0",
                "timestamp":"2019-12-31T08:27:53.042Z",
                "type":"1",
                "underlying":"BTC-USD"
            }
        ]
    }
    

### 公共-合约信息频道

合约信息频道，无需用户登录

每次有新合约上线或合约状态变化，就推标的指数下的全量合约数据。

##### send示例

    
    
    {"op": "subscribe", "args": ["option/instruments:BTC-USD"]}
    

其中option/instruments为频道名，BTC-USD为标的指数。

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
instrument_id | String | 合约ID，如BTC-USD-190830-9000-C  
underlying | String | 标的指数，如BTC-USD  
settlement_currency | String | 盈亏结算和保证金币种，如BTC  
contract_val | String | 合约乘数，对BTC期权合约，该值为0.1  
option_type | String | 期权类型，`C`或`P`  
strike | String | 行权价格  
tick_size | String | 价格精度（如0.0005）  
lot_size | String | 一手合约张数  
listing | String | 上线日期，ISO 8601格式  
delivery | String | 交割日期，ISO 8601格式  
state | String | 合约状态：1-预上线, 2-已上线, 3-暂停交易, 4-结算中  
trading_start_time | String | 交易开始时间，ISO 8601格式  
timestamp | String | 合约状态变更时间，ISO 8601格式  
  
##### 返回示例

    
    
    {
        "table": "option/instruments",
        "data": [{
                "instrument_id": "BTC-USD-190927-8500-P",
                "underlying": "BTC-USD",
                "settlement_currency": "BTC",
                "contract_val": "0.1000",
                "option_type": "P",
                "strike": "8500",
                "tick_size": "8",
                "lot_size": "1.0000",
                "listing": "2019-08-28T08:00:00.000Z",
                "delivery": "2019-09-27T08:00:00.000Z",
                "state": "2",
                "trading_start_time": "2019-08-28T07:30:39.678Z"
            },
            {
                "instrument_id": "BTC-USD-190927-8500-C",
                "underlying": "BTC-USD",
                "settlement_currency": "BTC",
                "contract_val": "0.1000",
                "option_type": "C",
                "strike": "8500",
                "tick_size": "8",
                "lot_size": "1.0000",
                "listing": "2019-08-28T08:00:00.000Z",
                "delivery": "2019-09-27T08:00:00.000Z",
                "state": "2",
                "trading_start_time": "2019-08-28T07:30:39.678Z"
            }
        ]
    }
    

### 公共-期权详细定价频道

合约详细定价频道，无需用户登录

推送标的指数下的所有期权合约详细定价信息，分多次推，每次一个合约。

##### send示例

    
    
    {"op": "subscribe", "args": ["option/summary:BTC-USD"]}
    

其中option/summary为频道名，BTC-USD为标的指数。

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
underlying | String | 标的指数，如BTC-USD  
instrument_id | String | 合约ID  
timestamp | String | 系统时间戳，ISO 8061格式  
best_bid | String | 买一价  
best_bid_size | String | 买一价对应的数量  
best_ask | String | 卖一价  
best_ask_size | String | 卖一价对应的数量  
last | String | 最新成交价  
high_24h | String | 24小时最高价  
low_24h | String | 24小时最低价  
volume_24h | String | 24小时成交量，按张数统计  
change_rate | String | 24小时涨跌幅  
open_interest | String | 持仓量  
mark_price | String | 标记价格  
highest_buy | String | 最高买价  
lowest_sell | String | 最低卖价  
delta | String | 期权价格对underlying价格的敏感度  
gamma | String | delta对underlying价格的敏感度  
vega | String | 期权价格对隐含波动率的敏感度  
theta | String | 期权价格对剩余期限的敏感度  
leverage | String | 杠杆倍数  
mark_vol | String | 标记波动率  
bid_vol | String | bid波动率  
ask_vol | String | ask波动率  
realized_vol | String | 已实现波动率 （目前该字段暂未启用）  
estimated_price | String | 预估交割价  
  
##### 返回示例

    
    
    {
        "table":"option/summary",
        "data":[
            {
                "instrument_id":"BTC-USD-200110-9000-P",
                "underlying":"BTC-USD",
                "best_ask":"0.2495",
                "best_bid":"0.2395",
                "best_ask_size":"35",
                "best_bid_size":"35",
                "change_rate":"0",
                "delta":"-1.204251749",
                "gamma":"1.9206755384",
                "high_24h":"0",
                "highest_buy":"0.398",
                "realized_vol":"0",
                "bid_vol":"",
                "ask_vol":"0.957",
                "mark_vol":"0.7243",
                "last":"0",
                "leverage":"4.0922",
                "low_24h":"0",
                "lowest_sell":"0.0905",
                "mark_price":"0.013",
                "theta":"-0.0005075296",
                "vega":"0.0001420339",
                "volume_24h":"0",
                "open_interest":"0",
                "estimated_price":"0",
                "timestamp":"2019-12-31T08:13:28.794Z"
            }
        ]
    }
    

### 公共-K线频道

K线频道，无需用户登录，每500ms推送一次数据。

频道列表：

option/candle60s // 1分钟K线数据频道

option/candle180s // 3分钟K线数据频道

option/candle300s // 5分钟K线数据频道

option/candle900s // 15分钟K线数据频道

option/candle1800s // 30分钟K线数据频道

option/candle3600s // 1小时K线数据频道

option/candle7200s // 2小时K线数据频道

option/candle14400s // 4小时K线数据频道

option/candle21600 // 6小时K线数据频道

option/candle43200s // 12小时K线数据频道

option/candle86400s // 1dayK线数据频道

option/candle604800s // 1week K线数据频道

##### send示例

    
    
    {"op": "subscribe", "args": ["option/candle60s:BTC-USD-190927-12500-C"]}
    

其中option/candle60s为频道名，BTC-USD-190927-12500-C为合约ID。

##### 返回参数

参数名 | 参数类型 | 描述  
---|---|---  
timestamp | String | 开始时间，ISO 8601格式  
open | String | 开盘价格  
high | String | 最高价格  
low | String | 最低价格  
close | String | 收盘价格  
volume | String | 交易量(按张折算)  
currency_volume | String | 交易量(按币种折算)  
instrument_id | String | 合约名称，如BTC-USD-190927-12500-C  
  
返回值数组顺分别为是：[timestamp,open,high,low,close,volume,currency_volume]

##### 返回示例

    
    
    {
        "table": "option/candle60s",
        "data": [{
                "candle":[
                    "2019-09-06T15:32:00.000Z",
                    "11010.54",
                    "11015",
                    "11010.5",
                    "11014.01",
                    "4638",
                    "0.62"
                ],
                "instrument_id":"BTC-USD-190927-12500-C"
            }
        ]
    }
    

### 公共-最新成交频道

获取最近的成交数据，无需用户登录，有成交数据就推送。

##### send示例

    
    
    {"op": "subscribe", "args": ["option/trade:BTC-USD-190927-12500-C"]}
    

其中option/trade为频道名，BTC-USD-190927-12500-C为合约ID。

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
instrument_id | String | 合约ID，如BTC-USD-190927-12500-C  
trade_id | String | 成交id  
price | String | 成交价格  
qty | String | 成交数量  
side | String | 成交方向：buy/sell  
timestamp | String | 成交时间，ISO 8601格式  
  
##### 返回示例

    
    
    {
        "table": "option/trade",
        "data": [{
                "instrument_id": "BTC-USD-190927-12500-C",
                "trade_id": "227897880202387456",
                "price": "0.017",
                "side": "buy",
                "qty": "2",
                "timestamp": "2019-05-06T06:51:24.389Z"
            },
            {
                "instrument_id": "BTC-USD-190927-12500-C",
                "trade_id": "227897880202387457",
                "price": "0.019",
                "side": "buy",
                "qty": "1",
                "timestamp": "2019-05-06T06:51:24.392Z"
            }
        ]
    }
    

### 公共-Ticker频道

获取平台期权合约的最新成交价、买一价、卖一价和对应的量，每100ms推送一次数据。

##### send示例

    
    
    {"op": "subscribe", "args": ["option/ticker:BTC-USD-190927-12500-C"]}
    

其中option/ticker为频道名，BTC-USD-190927-12500为instrument_id

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
instrument_id | String | 合约名称，如BTC-USD-190927-12500-C  
best_bid | String | 买一价  
best_bid_size | String | 买一价对应的数量  
best_ask | String | 卖一价  
best_ask_size | String | 卖一价对应的数量  
last | String | 最新成交价  
last_qty | String | 最新成交数量  
open_interest | String | 持仓量  
open_24h | String | 24小时开盘价  
high_24h | String | 24小时最高价  
low_24h | String | 24小时最低价  
volume_24h | String | 24小时成交量（按张数统计）  
timestamp | String | 系统时间戳，ISO 8601格式  
  
##### 返回示例

    
    
    {
        "table":"option/ticker",
        "data":[
            {
                "last":"0.0015",
                "open_24h":"0.0035",
                "best_bid":"0.001",
                "high_24h":"0.0035",
                "low_24h":"0.0015",
                "volume_24h":"18",
                "volume_token_24h":"1.8",
                "best_ask":"0.002",
                "open_interest":"668",
                "instrument_id":"BTC-USD-200103-8000-C",
                "timestamp":"2019-12-31T07:59:05.519Z",
                "best_bid_size":"1",
                "best_ask_size":"305",
                "last_qty":"0"
            }
        ]
    }
    

### 公共-5档深度频道

每次返回前五档的深度数据，此数据为每100毫秒的快照数据，即每隔100毫秒，快照当前时刻市场订单簿的5档深度数据并推送。

##### send示例

    
    
    {"op": "subscribe", "args": ["option/depth5:BTC-USD-190927-12500-C"]}
    

其中option/depth5为频道名，BTC-USD-190927-12500-C为合约ID。

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
asks | List | 卖方深度  
bids | List | 买方深度  
timestamp | String | 时间戳  
instrument_id | String | 合约ID  
  
##### 解释说明

返回的买卖方深度List中，每一个价格格式为[价格，数量， 强平单数量，订单数量]，比如["5621.8", "125", "0", "5"]

##### 返回示例

    
    
    {
        "table": "option/depth5",
        "data": [{
            "asks": [
                ["5621.7", "58", "0", "2"],
                ["5621.8", "125", "0", "5"],
                ["5622", "84", "0", "2"],
                ["5622.5", "6", "0", "1"],
                ["5623", "1", "0", "1"]
            ],
            "bids": [
                ["5621.3", "287", "0", "8"],
                ["5621.2", "41", "0", "1"],
                ["5621.1", "2", "0", "1"],
                ["5621", "26", "0", "2"],
                ["5620.9", "640", "0", "1"]
            ],
            "instrument_id": "BTC-USD-190927-12500-C",
            "timestamp": "2019-05-06T07:03:33.048Z"
        }]
    }
    

### 公共-400档深度频道

订阅后首次返回市场订单簿的400档深度数据并推送；然后每隔100毫秒，快照这个时间段内有更改的订单簿数据，并推送。

##### send示例

    
    
    {"op": "subscribe", "args": ["option/depth:BTC-USD-190927-12500-C"]}
    

其中option/depth为频道名，BTC-USD-190927-12500-C为合约ID。

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
asks | String | 卖方深度  
bids | String | 买方深度  
timestamp | String | 时间戳  
instrument_id | String | 合约ID  
checksum | String | 检验和  
  
##### 解释说明

返回的买卖方深度List中，每一个价格格式为[价格，数量， 强平单数量，订单数量]，比如["5621.8", "125", "0", "5"]

##### 返回示例

    
    
    首次400档：
    {
        "table": "option/depth",
        "action": "partial",
        "data": [{
            "instrument_id": "BTC-USD-190927-12500-C",
            "asks": [
                ["5621.7", "58", "0", "2"],
                ["5621.8", "125", "0", "5"],
                ["5621.9", "0", "0", "0"],
                ["5622", "84", "0", "2"],
                ["5623.5", "0", "0", "0"],
                ["5624.2", "4", "0", "1"],
                ...
                ["5625.1", "0", "0", "0"],
                ["5625.9", "0", "0", "0"],
                ["5629.3", "2", "0", "1"],
                ["5650", "187", "0", "8"],
                ["5789", "1", "0", "1"]
            ],
            "bids": [
                ["5621.3", "287", "0", "8"],
                ["5621.2", "41", "0", "1"],
                ["5621.1", "2", "0", "1"],
                ["5621", "26", "0", "2"],
                ["5620.8", "194", "0", "2"],
                ["5620", "2", "0", "1"],
                ...
                ["5618.8", "204", "0", "2"],
                ["5618.4", "0", "0", "0"],
                ["5617.2", "2", "0", "1"],
                ["5609.9", "0", "0", "0"],
                ["5433", "0", "0", "0"],
                ["5430", "0", "0", "0"]
            ],
            "timestamp": "2019-05-06T07:03:33.048Z",
            "checksum": -186865074
        }]
    
    增量：
    {
        "table": "option/depth",
        "action": "update",
        "data": [{
            "instrument_id": "BTC-USD-190927-12500-C",
            "asks": [],
            "bids": [
                ["5431", "0", "0", "0"]
            ],
            "timestamp": "2019-05-06T07:03:33.148Z",
            "checksum": -1200119424
        }]
    }
    

### 公共-400档增量数据频道

订阅后首次返回市场订单簿的400档深度数据并推送；后续只要订单簿深度有变化就推送有更改的数据。

##### send示例

    
    
    {"op": "subscribe", "args":["option/depth_l2_tbt:BTC-USD-200207-9500-C"]}
    

其中`option/depth_l2_tbt`为频道名，`BTC-USD-190927-12500-C`为`instrument_id`

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
asks | List<String> | 卖方深度  
bids | List<String> | 买方深度  
timestamp | String | 时间戳  
instrument_id | String | 合约ID,例如 `BTC-USD-190927-12500-C`  
checksum | String | 检验和  
  
##### 解释说明

返回的买卖方深度List中，每一个价格格式为[价格，数量， 强平单数量，订单数量]，比如["5621.8", "125", "0", "5"]

##### 返回示例

    
    
    First all entries：
    {
        "table":"option/depth_l2_tbt",
        "action":"partial",
        "data":[
            {
                "instrument_id":"BTC-USD-200207-9500-C",
                "asks":[
                    ["0.023","0","0","0"],
                    ["0.0235","100","0","1"]
                ],
                "bids":[
                    ["0.022","100","0","1"]
                ],
                "timestamp":"2020-02-06T05:03:30.354Z"
                "checksum":-2144245240
            }
        ]
    }
    

### WS公共指数频道

WebSocket API 公共指数频道

### 指数行情

公共指数频道无需登录，现货，交割合约，永续合约都可参考此频道 目前所提供的指数都是以USD计价的指数，币种列表为：BTC LTC ETH ETC XRP
EOS BTG

获取公共指数行情

##### send示例

    
    
    {"op": "subscribe", "args": ["index/ticker:BTC-USD"]}
    {"op": "subscribe", "args": ["index/ticker:BTC-USDT"]}
    

其中`index/ticker`为频道名，`BTC-USD`为币种指数

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
instrument_id | String | BTC-USD ,BTC-USDT  
last | String | 最新成交价  
high_24h | String | 24小时最高价  
low_24h | String | 24小时最低价  
timestamp | String | 系统时间戳  
open_24h | String | 24h开盘价  
  
##### 返回示例

    
    
    {"table":"index/ticker","data":[{"last":"3649.76","high_24h":"3955.4","low_24h":"10","instrument_id":"BTC-USD","open_24h":"3888.68","timestamp":"2018-11-27T10:01:23.341Z"}]}
    

### 指数K线

获取指数的K线数据

频道列表：

index/candle60s //1分钟K线数据频道

index/candle180s //3分钟K线数据频道

index/candle300s //5分钟K线数据频道

index/candle900s //15分钟K线数据频道

index/candle1800s //30分钟K线数据频道

index/candle3600s //1小时K线数据频道

index/candle7200s //2小时K线数据频道

index/candle14400s //4小时K线数据频道

index/candle21600s //6小时K线数据频道

index/candle43200s //12小时K线数据频道

index/candle86400s //1day小时K线数据频道

index/candle604800s //1 week K线数据频道

##### send示例

    
    
    {"op": "subscribe", "args": ["index/candle60s:BTC-USD"]}
    {"op": "subscribe", "args": ["index/candle60s:BTC-USDT"]}
    

其中`index/candle60s`为频道名，`BTC-USD`为币种指数

##### 返回参数

**参 数名** | **参 数类型** | **描 述**  
---|---|---  
timestamp | String | 开始时间  
open | String | 开盘价格  
high | String | 最高价格  
low | String | 最低价格  
close | String | 收盘价格  
volume | String | 交易量（张）  
instrument_id | String | BTC-USD ,BTC-USDT  
  
##### 返回示例

    
    
    {"table":"index/candle60s","data":[{"instrument_id":"BTC-USD","candle":["2018-11-27T10:01:23.341Z","3811.31","3811.31","3811.31","3811.31","0"]}]}
    

### 错误码

error message 格式：

{"event":"error"," message":" ","errorCode":""}

##### 错误码示例

错误描述 |  | Code  
---|---|---  
Url pass 无效 | Url path error | 30000  
"OK_ACCESS_KEY"不能为空 | OK_ACCESS_KEY cannot be blank | 30001  
"OK_ACCESS_SIGN"不能为空 | OK_ACCESS_SIGN cannot be blank | 30002  
"OK_ACCESS_PASSPHRASE"不能为空 | OK_ACCESS_PASSPHRASE cannot be blank | 30004  
无效的OK_ACCESS_TIMESTAMP | Invalid OK_ACCESS_TIMESTAMP | 30005  
无效的OK_ACCESS_KEY | Invalid OK_ACCESS_KEY | 30006  
请求时间戳过期 | Timestamp request expired | 30008  
无效的sign | Invalid sign | 30013  
用户请求频率过快，超过该接口允许的限额 | Requested too frequent; endpoint limit exceeded | 30026  
不合法的请求 | Login failure | 30027  
不合法的请求 | Unrecognized request | 30039  
频道不存在 | {0} Channel : {1} doesn't exist | 30040  
用户需要登录 | User not logged in / User must be logged in | 30041  
重复登录 | Already logged in | 30042  
内部系统错误 | Internal system error | 30043  
  
### 创建我的APIKey

[创建我的APIKey(点击跳转创建APIKey页面)](account/users/myApi)

### 问题反馈

如果您有任何api相关问题，意见或者建议，请点此[链接](account/users/support)反馈：(请标明是API v3 ),
我们会及时处理您的问题。

