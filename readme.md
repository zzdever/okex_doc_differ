[![](//static.bafang.com/cdn/assets/broker/api-static/logo/okex_logo.png)](/)

  * [ 入门指引 ](./#README)
  * [ 做市商项目 ](./#market)
  * [ 新手教程 ](./#vedio)
  * [ 更新日志 __](./#change-change)
    * [ 2020-07-20 ](./#change-20200731)
    * [ 2020-06-18 ](./#change-20200630)
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
  * [ 常见问题 __](./#question-README)
    * [ APIKey问题 ](./#question-apikey)
    * [ 验签问题 ](./#question-verify)
    * [ 域名问题 ](./#question-url)
    * [ 限速问题 ](./#question-limit)
    * [ 账户问题 ](./#question-account)
    * [ 公共问题 ](./#question-public)
    * [ 接口功能问题 ](./#question-endpoint)
    * [ 币币/杠杆问题 ](./#question-spot_margin)
    * [ 合约问题 ](./#question-contract)
  * [ API概述 __](./#summary-README)
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
  * [ 资金账户API __](./#account-README)
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
  * [ 币币API __](./#spot-README)
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
    * [ 公共-获取历史K线数据 ](./#spot-line_history)
  * [ 币币杠杆API __](./#spot_leverage-README)
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
  * [ 交割合约API __](./#futures-README)
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
    * [ 修改订单 ](./#futures-amend)
    * [ 批量修改订单 ](./#futures-amend_batch)
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
    * [ 公共-获取历史K线数据 ](./#spot-line_history)
  * [ 永续合约API __](./#swap-README)
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
    * [ 修改订单 ](./#swap-swap---amend)
    * [ 批量修改订单 ](./#swap-swap---amend_batch)
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
    * [ 公共-获取历史K线数据 ](./#swap-swap---line_history)
  * [ 期权合约API __](./#option-README)
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
    * [ 公共-获取历史结算/行权记录 ](./#option-option---settlement_history)
  * [ 合约交易数据 API __](./#information-README)
    * [ 公共-多空持仓人数比 ](./#information-ratio)
    * [ 公共-持仓总量及交易量 ](./#information-volume)
    * [ 公共-主动买入卖出情况 ](./#information-taker)
    * [ 公共-多空精英趋向指标 ](./#information-sentiment)
    * [ 公共-多空精英平均持仓比例 ](./#information-margin)
  * [ 指数 API __](./#index-restful-README)
    * [ 公共-获取指数成分 ](./#index-restful-content)
  * [ 公共-获取系统升级状态 __](./#status-readme)
    * [ Rest-获取系统升级状态 ](./#status-status)
    * [ WebSocket-获取系统升级状态 ](./#status-status---ws)
  * [ RestAPI 错误码 __](./#error-Error_Code)
    * [ 公共错误码 ](./#error-public)
    * [ 资金账户错误码 ](./#error-account)
    * [ 币币和杠杆错误码 ](./#error-spot)
    * [ 交割合约错误码 ](./#error-futures)
    * [ 永续错误码 ](./#error-swap)
    * [ 期权合约错误码 ](./#error-option)
  * [ WebSocketAPI __](./#swap_ws-README)
    * [ 现货 __](./#spot_ws-all)
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
    * [ 交割合约 __](./#futures_ws-all)
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
    * [ 永续合约 __](./#swap_ws-all)
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
    * [ 期权合约 __](./#option_ws-all)
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
    * [ WS公共指数频道 __](./#Index-README)
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
[点击申请APIKey](/account/users/myApi)，然后根据此文档详情进行开发交易，使用过程中如有问题或者建议请及时反馈。
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

