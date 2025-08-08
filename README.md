# MyBarn

用于纪录钱粮收支统筹的我的粮仓
|
My barn for count the money and grain.

## 快速开始

待补充

## 技术栈
版本一只有app端，数据存本地sqlite和json文件，主要使用flutter，必须带导出成CSV表格的功能
版本二会整自部署的服务端，主要使用go web相关技术

## 概念
一些暂定的概念名词
- 账户: 活期，定期，贷款
  - 活期：银行储蓄卡，支付宝微信余额等能随时支出的账户
  - 定期：银行大额存单等无法随时支出的账户
- 支出：花出去的钱，也叫出仓，资金流向：粮仓 => 外界
- 收入：赚的钱，也叫入仓，资金流向：外界 => 粮仓
- 分类：支出或者收入的细分
- 转账：从一个账户转入另一个账户的钱，资金流向：粮仓A账户=>粮仓B账户，资金在粮仓里打转，但是一般会伴随手续费这类的支出（比如微信余额提现手续费）
- 账单：资金流转的纪录
- 附件：账单附带的文件，比如图片或者视频或者文档等
- 预算：针对一个时间段的支出计划金额
- 目标：针对一个时间段的对收入支出的目标计划



## 编译环境
```text
[√] Flutter (Channel stable, 3.29.2, on Microsoft Windows [版本 10.0.26100.4652], locale zh-CN)
[√] Windows Version (11 家庭中文版 64-bit, 24H2, 2009)
[√] Android toolchain - develop for Android devices (Android SDK version 35.0.0)
[√] Chrome - develop for the web
[√] Visual Studio - develop Windows apps (Visual Studio Community 2022 17.12.4)
[√] Android Studio (version 2023.3)
[√] IntelliJ IDEA Community Edition (version 2024.3)
[√] VS Code (version 1.102.3)
[√] Connected device (3 available)
[√] Network resources
```
## 页面

- 首页：
- 账单
- 统计
- 我的
    - 账户
    - 预算
    - 存钱
    - 其它
