# Purchase 充值知识库

> 通用规则：玩家购买的是 Gold Coins，Sweepstakes Coins (SC) 是促销赠送，不能直接购买。涉及合规性，不可回复错。
> 时间标准：业务服/支付中心时间均为 UTC+0。

---

## 一、充值渠道

| 渠道 | 说明 |
|------|------|
| **PayPal** | 多个供应商收款，玩家通过PayPal付款充值 |
| **ACH Pay** | Acorn项目组 com.richesflow.casino 支持，玩家绑定银行账户直充。授权页面显示 Lucky Warrior Studio, LTD. 为合作payment agent |
| **Debit Card** | 部分借记卡可直充，建议玩家自行尝试 |
| **Credit Card** | 分为直冲和Apple Pay两种渠道 |
| **Apple Pay** | 使用绑定的信用卡充值，**不支持 Apple Cash** |
| **Cash App** | 2025-07-11起大部分项目组已停用，仅Legends部分bundles保留 |

**Cash App Biller Name：**
- ONYX GRYPHON INTERACTIVE INC
- Axiom Vortex Games INC
- Data Voyager INC

---

## 二、更换充值方式

**Poker Hit / Luck Hit：** 玩家可在游戏充值页面直接修改卡号或换方式。

**Acorn / Legends：** 只缓存信用卡号，删除App或清空缓存后需重新绑定。玩家可在充值页面删除旧卡号记录，绑定新卡。

**话术：**
```
Dear Player,
Thank you for reaching out to us.
If you wish to change another credit card for your purchase, you can kindly delete your current credit card record in the purchase page then enter your new credit card information to make a purchase.
Let us know if you need any further assistance, have a great day.
```

---

## 三、充值失败处理

### 3.1 单次失败
```
Dear Player,
We sincerely apologize for the inconvenience.
After checking, your $XX purchase on 20XX-XX-XX UTC-0 failed.
Therefore no money was taken out from your bank account.
Please kindly check if your account is in right status and has sufficient funds. If everything is normal, the money might be held by your bank. It is recommended that you change the payment method if your current transaction has failed.
We appreciate your patience and understanding. Have a good day!
```

### 3.2 多次失败
```
Dear Player,
We sincerely apologize for the inconvenience.
After checking, all your purchase actions were all failed.
Therefore no money was taken out from your payment account.

If your purchase failed, there could be a few reasons for this:
1. Insufficient balance on your credit card or other payment accounts.
2. Network connectivity issues resulting in payment failure.
3. The acquiring bank rejected your payment.
Please check your account balance, consider changing your payment method, or try using another credit card to make the payment again.

Please kindly check if your account is in right status and has sufficient funds. If your money has been deducted, this may be due to a temporary hold placed by your bank. In this case, you may need to wait longer until the bank releases the funds back to your account.
If you have any further questions or concerns, please feel free to contact us anytime.
We appreciate your patience and understanding. Have a good day!
```

### 3.3 风控导致充值失败
- **不可告知玩家是风控导致的**
- 一般不是永久的，只是暂时的，让玩家等一等再次尝试
- 换卡或换充值渠道后仍不行，填写工单

### 3.4 特殊风控 - 持卡太多 (Too Many Cards)
- 一个玩家在一个账户中使用太多卡会被风控
- 需要验证信用卡都是玩家自己的且在游戏内有充值记录
- **不能跟玩家说是我们游戏风控的**
- 提交工单让二线提供验证银行卡的链接
- 玩家需拍摄卡信息，**遮挡中间卡号**；手持卡拍照，**遮挡中间7-12位卡号**
- 验证卡上名字与KYC名字是否一致（二线验证）
- 验证通过，填工单解封

### 3.5 高风险争议玩家
- 玩家有很高的争议风险，被支付中心风控不能充值
- **不能跟玩家说是我们游戏风控的**
```
Dear Player,
Thank you for your patience.
You can wait a moment then try again. If that won't dismiss the issue. We are sorry to tell you that you may need to change to another card or method. This was operated by the bank that should RECEIVE YOUR MONEY(not your card issue bank). We don't know why either. And we are unable to change their decision.
Thank you for your patience and understanding.
```

### 3.6 高频充值限制
- 因充值频率过高自动触发，一般时效仅1小时
- **不能跟玩家说是我们游戏风控的**
- Tag：【高频充值限制】
- 过了限制时间仍有问题，提工单让二线协助

### 3.7 "Limited, Try Later" 提示
- 短时间内多次重复尝试充值触发
- 1小时内无法充值
- 告知玩家1小时后尝试，避免短时间内重复尝试

---

## 四、充值未到账

### 4.1 有订单详细信息
- 支付中心查询是否成功支付
  - **成功**：查询业务服是否到账 → 到账则查询流水回复玩家；未到账填工单
  - **不成功**：红色pay failed → 告知支付失败游戏未收到钱款，银行后续会退回

**到账话术：**
```
Dear Player,
Thank you very much for your patience.
After checking you have made four $XX worth purchase and all of them has successfully credited to your game account on 20XX-XX-XX UTC-0.
There might be some delay of the purchase because of your bank was processing the transaction.
Hope you have a lovely day.
```

### 4.2 没有订单详细信息
- 询问订单截图，需包含：Transaction time, Transaction amount, Transaction ID, Transaction Status, Biller Name

**索要截图话术：**
```
Dear Player,
Thank you for your patience.
Could you please kindly help us take a screenshot of your transaction record in which you mentioned you did not receive credit in our game?
Kindly include the transaction ID, transaction time, transaction amount, biller name, and transaction status in the screenshot to help us locate the record faster.
Looking forward to hearing from you soon.
```

### 4.3 Pending/Processing 状态
- 订单还在处理中，我们没有收到钱
- 如果订单失败，钱会由银行/PayPal退回
```
Dear Player,
We are sorry for the inconvenience.
As you can see from your transaction screenshot, the payment is still pending. This means that we didn't receive the money. If the payment didn't go through the system, the money should be sent back to your account by your bank or Paypal.
Your understanding is much appreciated, please let us know if you need any further assistance, we are here to help.
Have a lovely day.
```

---

## 五、特殊卡号风控

如果玩家反馈充值失败，查看玩家卡bin（卡号前六位）是不是 **403163** 或 **440393**。
- 如果是，告知玩家这是发卡行原因无法充值，建议换其他银行的卡
- 确认后打上标签 **Sutton**

---

## 六、退款规则

### 6.1 可退款条件
- 充值的item不是周期类充值项目
- 该笔充值的90%余额都没有使用
- 一线先冻结玩家账户，填工单让二线操作扣除余额
- 二线反馈扣余额成功后解封账户

**不可退款：** 周期类充值（周订阅、每日挑战豪华战令等），因涉及活动开启。

**话术：**
```
Dear Player,
Thank you for your request regarding a refund.
We will freeze your account first and submit your refund request to the relevant department for processing.
Kindly noted that the final decision is not guaranteed.
If you have any further questions, please feel free to contact us.
Hope you have a lovely day.
```

### 6.2 非法州退款
- 首次反馈在非法州要求退款：先回复玩家关闭VPN/代理，回居住地后可正常游戏
- 如果玩家说一直在非法州：询问州属，提交工单让二线确认是否真为非法州玩家，再做退款封号
- **不可玩家说在非法州就立即填写邮件退款表**

**首次话术：**
```
Dear Player,
We'd like to inform you that due to regional licensing regulations, our game services are currently unavailable in certain locations. Please note:
X If you're physically located in a restricted region
X Or if you're using VPN/proxy services
Our system automatically detects your actual location when accessing the game. You'll be able to enjoy the game when:
✓ You're in a supported region
✓ And not using VPN/proxy services
We sincerely appreciate your understanding and support. If you have any further questions, our support team is happy to help.
Happy gaming!
```

### 6.3 误下注要求退款
- 先查询玩家反馈的对应Spin/Spins是否正常（正常Spin时间间隔5秒以上可能是玩家自己下注后反悔）
- 将查询到的金额及game flow时间反馈在工单里，让二线判断或反馈给项目组
- **不要玩家要求退款就不查询流水直接提交工单**

---

## 七、Extra Fee 额外费用

### 7.1 Cash App Cards 国际费用
- 不是我们收取的，是Cash App收取的国际交易费
- 建议玩家换其他支付方式
- Cash App接收超过$300/月可能免除下月国际交易费（需玩家先联系Cash App确认）

### 7.2 NSF Fee 超支费用
- 不是我们收取的，由信用卡发卡公司或银行收取
- 需要玩家自己向发卡方确认

### 7.3 国际费用 Cross-border fees
- 不是我们收取的，是发卡方收取（通常几毛钱）
- 信用卡可能把费用单独显示并标上biller name，导致玩家误以为是我们double charge
- 建议玩家换一张信用卡充值避免费用
- 如果通过Apple Pay绑定高国际费信用卡支付，同样会被收取，建议换绑其他信用卡

---

## 八、Unauthorized Transactions / 未成年人充值

### 8.1 非本人操作
- 先冻结玩家账户，避免再次充值
- 查看支付中心记录，如果绝大多数通过Apple Pay充值，大概率是玩家自己authorized（需密码/Face ID）
- 告知玩家查询事实，说明Apple Pay需验证，且充值后正常使用balance，按policy已使用的充值款项不可退款
- 如果玩家坚持账号被盗或查询到大部分是信用卡/Cash App充值，提交工单让二线处理

### 8.2 未成年人充值
- 先冻结玩家账户
- 如果绝大多数通过Apple Pay充值，大概率不是未成年人（需密码/Face ID）
- 如果KYC状态通过，进一步佐证不是未成年人
- 如果玩家坚持未成年孩子充值，提交工单二线处理

---

## 九、充值咨询

### 只获得GC没有获得SC
- **Luck Hit / Poker Hit：** 不给予任何补偿，商店显示足够清楚
- **Acorn / Legends：** 补偿规则见各项目组知识库

### 充值话术参考
```
Dear Player,
Thank you for your patience.
Please kindly note that currently we only support Credit card, Debit Card, Paypal and Apple pay as purchase method in our game.
Have a great day.
```

---

## 十、ACTUM 坏账

- ACH充值扣款不是即时的，可能出现坏账（玩家充值成功但后续扣款失败）
- 所有发生坏账的玩家都会被封禁该充值渠道
- 如需解封充值渠道，提工单让二线转交风控组
- 坏账、未到账订单查询方式还在沟通中
- 之前Legends对坏账玩家进行账户封禁，现已全部解封，但充值渠道封禁未解除
- 处理核心：追回损失（扣回余额、扣提现、充值被立即扣除等），项目组正在开发功能

---

## 十一、Dispute / Chargeback / Fraud

### 11.1 Dispute
- 玩家充值后可通过各种理由对交易发起争议
- 一旦发起争议，需提交相关资料给供应商抗辩
- 赢了不用退款，输了需退款
- 所有payment gateway供应商监控争议率，超过数值可能停止提供该渠道充值
- 发现玩家发起争议，给客诉打上 **dispute** 标签，分配给Chris处理

### 11.2 Fraud
- 类似dispute但程度轻微，没有抗辩环节，不用退款
- 供应商监控Fraud率，超过数值可能停止提供渠道
- 发现玩家发起Fraud，给客诉打上 **CKO_FRAUD** 标签，分配给Chris处理

### 11.3 退款规则补充
- Fully refund的订单用户仍可能因时间差发起争议
- Partially refund的订单用户依然可以发起争议，所以一般不部分退款
- 充值时间超过半年的订单一般无法发起争议

---

*最后更新：2025-07-11 (Cash App停用), 2025-09-09 (Debit Card新增)*
