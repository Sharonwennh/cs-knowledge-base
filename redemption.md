# Redemption 提现知识库

> 注意：2025-07-21 目前所有项目组都停止了 Cash App 提现功能。
> 1 sweepstakes coin = 1 USD，SC必须至少玩过1次才能提现。GC不可提现。

---

## 一、最低提现金额

| 项目组 | 说明 |
|--------|------|
| **Poker Hit** | 详见 Poker 知识库 |
| **Luck Hit** | 详见 Luckhit 知识库 |
| **Acorn / Legends** | 部分玩家最低提现金额不是1SC或0.5SC，以Redemption page显示规则为准 |

**话术：**
```
Dear Player,
Thank you for reaching out to us.
When you submit a redemption, there is a minimum limit of how much you can redeem. Please kindly check the redemption rules on the REDEEM interface for further information.
Hope you have a lovely day!
```

---

## 二、手续费

- 2025-09-09 新增：Debit Card 提现手续费固定 **$1/笔**
- Legends 和 Acorn 项目组针对不同玩家进行不同提现手续费的实验
- 所有玩家手续费根据项目组配置动态显示在 redeem page（如显示5%手续费等）
- 遇到玩家反馈手续费问题，提工单，包含：提现页面是否按收取比例显示、手续费比例是多少
- 玩家反复抱怨手续费可提交工单二线反馈给项目组看是否补偿

---

## 三、提现要求

- **KYC-ID**：所有玩家必须通过初级KYC-ID才可提现
- **KYC-POA**：已提现金额2000以上，需要通过高级KYC-POA

---

## 四、提现方式

| 方式 | 说明 | 用户信息要求 |
|------|------|-------------|
| **PayPal** | 通过合作平台向玩家PayPal账户打款 | 验证一个邮箱（PayPal邮箱） |
| **ACH** | 通过合作平台向玩家银行账户打款 | Bank Account Number + ABA Code/Routing Value（不是Card Number） |
| **Cash App** | 已停用（2025-07-21） | - |
| **Prizeout** | 第三方Gift Card兑换平台 | 验证邮箱，创建Prizeout账号 |
| **Debit Card** | 通过合作平台向玩家借记卡打款 | 无需填写信息，展示首张使用过的Debit Card（Schema+前6后4位） |
| **Refund** | 对之前充值进行退款实现等效益打款 | 无需提供信息，由支付组内部风控决定 |

**注意：** 不同产品/版本下，玩家可能只有一个提现方式，**不可向玩家透露还有另一个方式**。

**提现方式话术：**
```
Dear Player,
Thank you for reaching out to us.
You can use the available redemption method on your redeem page to redeem.
If you have any further problem, please feel free to contact us.
Thanks for your support!
```

---

## 五、ACH 用户信息收集话术

```
Dear Player,
Thank you for enquiring about the ACH redemption method.
Please rest assured that the ACH redemption method is as safe and as fast as Paypal, please kindly provide your:
1. FULL NAME
2. BANK ACCOUNT NUMBER (Please make sure not to put your card number in as this will result transaction failure)
3. ABA CODE (ROUTING VALUE: 9 DIGITS BANK CODE ON YOUR BANK STATEMENT)
4. Address details, accurate to the house number
5. ZIP CODE
6. Date of birth

After you fill in the above information, our agent will review your redemption request and send your transaction to your bank, then bank will issue you the transaction within 2-3 business days.
If your ACH redemption is succeed, an confirmation e-mail will be sent out to your game registered email address.
Please let us know if you need further assistance.
Have a great day.
```

---

## 六、提现状态处理

### 6.1 103/Pending, 106/Reviewing, 1/Pending, Luckhit 0/Pending
- 玩家成功提交提现请求，正在审核
- **可为玩家提供取消提现服务**
- 每个请求由人工审核确保账户安全

**话术：**
```
Dear Player,
Thank you for being so patient. We are sorry for the inconvenience. Each request is reviewed manually by our agents to ensure the safety of players' accounts. So it may need a little bit more time. But our agents are trying their best to work on it. It usually takes 3 days to receive the redemption.
```

### 6.2 113/Queuing
- 审核通过，正在排队打款
- 金额越大排队时间越长

**PayPal 第一次询问（24小时内）：**
```
Dear Player,
Thank you so much for your patience!
Your redemption request has successfully passed the review stage and is now locked for processing — the final step before the payment is sent out.
Typically, it takes about 24 hours for the transaction to appear in your PayPal account (xxx).
We truly appreciate your understanding during this time.
Wishing you a wonderful day ahead!
```

**超过24小时再次询问：**
```
Dear Player,
Thank you for the wait.
We have escalated this issue to our supervisor, and they are taking the situation very seriously.
They are currently expediting the redemption process for you, so please wait patiently.
In the meantime, if you have any other questions, feel free to contact us, and we will be happy to assist you.
Hope you have a lovely day!
```
*此时可提工单让二线联系项目组加速，但二线不要填催打款表。*

**ACH 113状态：**
```
Dear Player,
We have reviewed your redemption and confirmed that it has passed the verification process and is currently queued for payment.
Please note that since you selected ACH as your redemption method, once we successfully send the funds to the bank, the bank may take up to 3 business days to process and deposit the amount into your bank account.
You can check the status of your redemption anytime on the redemption page.
Thank you for your patience!
```

### 6.3 116/To be Claimed (PayPal)
- 提现成功递交到第三方，需玩家手动领取

**不活跃账户（需手动领取）：**
```
Dear Player,
Thank you for your patience.
We have sent your redemption request of $xxxx (net of fees) to PayPal on xxxxxxx (UTC+0). Please check the PayPal email address you verified in the game(xxxxxx) to see if you have received an email from service@paypal.com. You will need to click [Claim your payment] in the email to collect your redemption.
Kindly note that the sender of the redemption will be either Essentials Tech, Pagsmile, Tewang Limited or Citcon USA LLC.
Please note that if you do not claim the redemption within 30 days, it will be returned to us and subsequently credited back to your game account.
If you have any further questions or concerns, please do not hesitate to reach out.
```

**ACH 116状态：**
```
Dear Player,
Sorry for the delayed response.
Please kindly note that the "need to collect" status means that we have sent your redemption transaction to bank already and they are now issuing your transaction to your bank account ending with XXXX.
Normally, bank will issue you the transaction in the next few business days.
Please kindly check later, if you have further questions, please let us know.
Hope you have a great day.
```

### 6.4 3/Redeemed (打款成功)

**PayPal：**
```
Dear Player,
Thank you for your patience.
Typically, you can expect to receive the redemption within 3 days. After our review, your redemption of $xxxxxx (net of fees) was successfully processed on xxxx (UTC+0) via PayPal.
Verified PayPal email: xxxx
Kindly note that the sender of the redemption will be either Essentials Tech, Pagsmile, Tewang Limited or Citcon USA LLC.
If you don't have a PayPal account linked to this email, please create one or add this email to your existing PayPal account.
We greatly appreciate your understanding and support.
```

**ACH：**
```
Dear player,
Thank you for your patience. We confirmed that $xxxxx (net of fees) was sent to the bank on xxxxxxxx (UTC+0). However, please be advised that the bank may require up to three business days to process the transaction and credit the funds to your bank account ending in xxxx.
Please check your transaction records. If you encounter any issues or do not receive the funds after three business days, please contact us again.
Have a nice day!
```

**Debit Card：**
```
Dear player,
Thank you for your patience. We have successfully processed your redemption request. The amount of $XXXXX (net of fees) has been sent to your Debit Card (Schema:XXXXX Bin and Last 4 Digits： XXXXXX XXXX) on XXXXXXXX (UTC+0).
Please note that while we have completed our processing, your bank may require a few minutes to fully process the transaction and reflect the funds in your Debit card.
We recommend checking your bank Statement after this period. If you do not see the funds credited after 1 Business Day, please feel free to contact us again for further assistance.
Thank you for your understanding and have a wonderful day!
```

**Cash App 3/Redeemed：**
```
Dear Player,
Thank you for contacting us about your Redemption request.
As you've selected Cash App as your Redemption method, we've successfully processed your Redemption to your Cash App account. Important Note: Some Redemptions may appear as "Pending" in your Cash App and will require your manual acceptance.

Steps to Accept Your Redemption:
1. Open your Cash App and tap the Activity tab (clock icon)
2. Look for the pending Redemption from us (labeled as "Pending" or similar)
3. Select the transaction and tap "Accept" to complete your Redemption

Please Remember:
• You must accept within 14 days or the Redemption will be canceled, please claim your pending payment in time.

If you have any other questions, feel free to contact us, and we will be happy to assist you.
Hope you have a lovely day!
```

### 6.5 4/Failed (打款失败)

**PayPal 失败（Acorn/Legends）：**
```
Dear Player,
Sorry for the delayed response.
We have tried to send you the money several times but have failed due to compliance restrictions. You may need to contact PayPal to make sure that your account's status is normal. We have sent the money back to your game account. You can redeem again after your PayPal account is in the right status.
Please note that the email that you need to verify when you are trying to redeem should be the email of your PayPal account. Please fill in your PayPal email for verification, and then we will send the cash to your PayPal account.
If you need to change the email account for the redemption, please let us know so we can generate a Face Authentication Link for you to verify your identity. After you finished your Face Authentication Verification, kindly let us know that your verification is finished and our relevant team will help you reset the redemption email so you can bind a new one.
Looking forward to hearing from you soon.
```

**PayPal 失败（Poker Hit / Luck Hit）：**
```
Dear Player,
Sorry for the delayed response.
We have tried to send you the money several times but have failed due to compliance restrictions. You may need to contact PayPal to make sure that your account's status is normal. We have sent the money back to your game account. You can redeem again after your PayPal account is in the right status.
Please note that the email that you need to verify when you are trying to redeem should be the email of your PayPal account. Please fill in your PayPal email for verification, and then we will send the cash to your PayPal account.

Please kindly note that for security purposes, players who want to change the bonded redemption email need to finish the Face Authentication to prevent other people use your account to redeem your balance.
After you pass the face Authentication, please let us know the new valid Paypal email you want to bind to your game account so we can help you to revise:

Link address

Looking forward to hearing from you soon.
Have a great day.
```

**ACH 失败：**
```
Dear Player,
Apologies for the delayed response.
We have found that the failed redemption via ACH (bank account with ending xxx ) may be due to incorrect information provided by the player.
Please pay special attention to the fact that the Bank Account Number is not the Card Number.
As a result, the redemption SC xxx has been returned to your game account on xxx (UTC+0).
Also, kindly refrain from initiating new redemption requests to the same account to avoid payments being sent to the unintended account or consecutive redemption failures.
If we assist you with unbinding your current account, you will not be able to rebind it as each bank account can only be linked once.
Kindly advise us whether you would like us to assist you to update your ACH account.
```

### 6.6 5/Canceled (取消提现)

**Acorn / Legends 取消话术：**
```
Dear Player,
Thank you for your patience.
We have submitted a request to cancel your redemption.
However, please note that if the redemption is processed before the cancellation request is approved, the transaction may still go through. Therefore, we cannot guarantee that the redemption will be successfully canceled.
If the redemption is successfully canceled, the SC amount will be returned to your account within 24 hours.
Please keep an eye on the redemption status on the redemption page as well as any changes in your account balance.
```

**Poker Hit / Luck Hit 取消话术：**
```
Dear Player,
Please kindly note that you can cancel your redemption on your redemption history page. If you have not cancelled your redemption in time, the redemption might been sent to your incorrect email.
If you need to change the email account for the redemption, please let us know so we can generate a Face Authentication Link for you to verify your identity.
After you pass the face Authentication, please let us know the new valid Paypal email you want to bind to your game account so we can help you to revise:

Link address

Looking forward to hearing from you soon.
Have a great day.
```

### 6.7 105/Problematic (可疑提现)
- 该笔提现被视为可疑
- 填写工单说明提现情况，二线向项目组咨询

### 6.8 200/Refund (退款方式提现)
```
Dear Player,
Sorry for the delayed response.
We have tried to send you the money several times but failed due to the system update, the redemption could not arrive in time, so we sent the redemption to the payment method you used for the purchase in the form of a refund.
Your redemption of in total of $XX after the transaction fee is charged since 20xx-xx-xx UTC-0 has been sent to the original payment you used to make the purchase ( Apple Pay/ Credit card:XXXX/ Paypal).
The transactions are paid separately in XX payments, please kindly check:
Apple Pay：X Transactions in total $XX
Credit card:XXXX: X Transactions in total $XX
........
We have sent out the refunds. But the refunds sent to your credit card may take some time to be credited since the banks need some time to process them. It usually take about a week.
If you don't receive the refunds within a week, please feel free to contact us.
Have a great day!
```

---

## 七、提现时间说明

### 7.1 一般处理时间
- **PayPal**：通常24小时内到账，最长不超过3天
- **ACH**：银行处理通常需要最多3个工作日（非即时到账）
- **Cash App**：通常24小时内到账
- **Prizeout**：通常3小时内到账
- **Debit Card**：即时到账

### 7.2 非ACH周末延迟
- 银行周末不工作，周五之后发起的ACH提现需等到下一个工作日处理
```
Dear Player,
Thank you for your patience.
Kindly note bank will need a few business days to issue the transfer to your bank account. Because during the weekend banks are not working, so the waiting time will be a little bit longer than weekdays.
Please kindly wait for another 1-2 business days for bank to send the transactions to your bank account if you redeem during the weekend.
If you need further assistance, please let us know.
Hope you have a wonderful day.
```

### 7.3 自动审核打款
- 部分打款不需要人工审核，会更快
- 不需要告诉玩家有自动审核机制，只告诉这是正常现象
- 如果三天之内没有收到，请联系客服

---

## 八、PayPal 提现限制

- 单笔PayPal redemption不能超过 **1500SC** 或 **500SC**（超过会被手动标记失败，退回账户让玩家重新提现）
- 单日累积PayPal redemption限额（UTC-8时区计算）：
  - 没有通过PayPal充值的：每日限额 **1500SC**
  - 之前有过PayPal充值记录的：每日限额 **5000SC**
- 超过限额只能选择第二天再次PayPal提现，或尝试ACH提现
- **不需要跟玩家说明原因**，让玩家尝试ACH提现即可

---

## 九、Redemption Account 管理

### 9.1 PayPal 唯一性
- 一个PayPal邮箱只能供一个账号提现使用
- 如果在另一个账号上使用同一个redemption email，会提示 "Email bound to another account"
- **Luckhit 玩家**：在一个产品里已注册过提现邮箱，在别的Luckhit产品里无法使用同一个PayPal邮箱

### 9.2 PayPal 绑定
- 玩家在 Verify Email Address 输入PayPal Email → 点击Verify → 发送验证链接邮件 → 点击链接绑定成功
- 如果玩家说没收到验证邮件，先让玩家检查邮箱是否已满或验证邮件归入Spam

**未收到验证邮件话术：**
```
Dear Player,
Thank you for your patience. We apologize for the inconvenience this may cause. It is possible that the emails are automatically determined to be spam, so please check your spam and whether your mailbox is full. Then please click resend to verify again. If you still can't receive emails, please contact us and provide us with your email address for further checking.
```

### 9.3 PayPal 充值邮箱验证（Acorn/Legends）
- 如果用PayPal充值过的玩家，提现时验证的邮箱不是PayPal充值邮箱，会提示
- 点击Confirm → 需输入充值所用的PayPal邮箱
- 点击Cancel → 可继续验证当前提现邮箱（非充值PayPal邮箱）

### 9.4 修改 Redemption Email
- **Poker Hit**：详见 Poker 知识库
- **Acorn / Legends / Luckhit**：需完成 Face Authentication 验证后，二线帮忙重置或换绑
- 流程：
  1. 搜索是否有可取消的提现，如有则取消避免打款到错误账号
  2. 填写工单向二线索取 Face Authentication 链接
  3. 玩家完成验证后，业务服解绑或二线解绑ACH、Cash App账户绑定

**Face Authentication 话术：**
```
Dear Player,
Thank you for your patience, please kindly note that for security purposes, players who want to change the bonded redemption email need to finish the Face Authentication to prevent other people use your account to redeem your balance.
After you pass the face Authentication, please let us know that your verification is finished and our relevant team will help you reset the redemption email so you can bind a new one.

Link address

Looking forward to hearing from you soon.
Have a great day.
```

**验证成功话术：**
```
Dear Player,
Sorry for the delayed response. Your redemption email has been reset. You can now bind a new valid redemption mail for your future redemption.
Please let us know if you need further assistance.
Hope you have a lovely day.
```

### 9.5 Cash App 修改
- 已停用（2025-07-21）
- 如需修改历史绑定，需 Face Authentication 验证

### 9.6 ACH 修改
- 需 Face Authentication 验证
- 验证通过后二线重置ACH profile，玩家自行更新正确ACH信息

### 9.7 Debit Card 修改
- 目前不提供更换Debit Card功能，建议玩家先用其他redemption method

---

## 十、取消提现 (Cancel Redemption)

| 状态 | Acorn/Legends | Poker Hit / Luck Hit |
|------|---------------|---------------------|
| **103/106/1/0 Pending** | 填写Cancel Redemption表格帮玩家取消 | 玩家可自行在游戏内取消 |
| **113/Queuing** | 无法取消，已锁定准备打款 | 无法取消 |
| **116/To be Claimed** | 无法取消，已发送给第三方 | 无法取消 |
| **3/Redeemed** | 无法取消，已成功打款 | 无法取消 |

**Acorn/Legends 取消话术：**
```
Dear Player,
Thank you for your patience.
We have submitted a request to cancel your redemption.
However, please note that if the redemption is processed before the cancellation request is approved, the transaction may still go through. Therefore, we cannot guarantee that the redemption will be successfully canceled.
If the redemption is successfully canceled, the SC amount will be returned to your account within 24 hours.
Please keep an eye on the redemption status on the redemption page as well as any changes in your account balance.
```

---

## 十一、索要 Transaction ID / 打款凭证

### 11.1 PayPal 116状态要Transaction ID
- 先按116未收到Claim Redemption email流程引导玩家查看
- 如果玩家坚持说没收到，需要玩家提供录屏：
  - 展示邮箱收件箱中规定时间段内确实没有兑换邮件
  - 搜索 "Pagsmile" 和 "Essentials" 查找我们发送的邮件
- 确认录屏符合要求后，提交工单让二线问支付组索要Transaction ID

### 11.2 PayPal 3/Redeemed状态要Transaction ID
- 先引导玩家去PayPal查看流水
- 如果玩家坚持说没收到，需要玩家提供录屏：
  - 录屏到PayPal email确认为游戏内绑定的redemption email
  - 提供规定时间段（3/redeemed后10天内UTC-0）PayPal流水完整录屏
- 确认后提交工单让二线索要Transaction ID

### 11.3 Cash App 3/Redeemed要凭证
- 先引导玩家去Cash App查看流水
- 如果玩家坚持说没收到，需要玩家提供录屏：
  - 录屏到Cash App Account确认为游戏内绑定的账户
  - Activity页面Payment记录
  - 规定时间段（3/redeemed后2天内UTC-0）Cash App流水完整录屏
- 确认后提交工单让二线索要打款凭证

### 11.4 ACH 3/Redeemed要凭证
- 先引导玩家去ACH账户查看流水
- 如果玩家坚持说没收到，需要玩家提供录屏：
  - 录屏到正确的ACH账号
  - 规定时间段（3/redeemed后10天内UTC-0）ACH账号流水完整录屏
- 确认后提交工单让二线索要打款凭证

### 11.5 Debit Card 3/Redeemed要凭证
- 先引导玩家去Debit Card查看Bank Statement
- 如果玩家坚持说没收到，需要玩家提供录屏：
  - 打开手机银行App，点击对应Debit Card查看Bank Statement
  - 展示Debit Card前六位后四位，确认是玩家的提现Debit Card
  - 规定时间段（3/redeemed后10天内UTC-0）Debit Card bank statement完整录屏
- 确认后提交工单让二线索要打款凭证

---

## 十二、退款方式提现 (Refund Redemption)

### 12.1 原路径退回
- 玩家用账户A通过第三方B充值了$10 → 退款只能通过第三方B退回账户A

### 12.2 退款时效
- PayPal和Cash App退款：即时性，状态变为200/Refund后玩家立即收到
- 信用卡和ACH退款：需银行处理时间，一般告诉玩家一周以内

### 12.3 退款上限
- 退款历史额度之和 = 玩家历史充值额度之和
- 如果玩家生涯只充值过$1000，最多只能退款$1000

### 12.4 多笔退款
- 如果玩家生涯充值$100共20笔$5，发起$40提现 → 需退款8笔$5
- 由于可能多平台退款，到账时间不一致
- 需从支付中心查出所有对应退款明细：每笔多少钱、退到哪里、一共多少笔、退款总额

### 12.5 不足额退款
- 如果充值总额不足以覆盖提现金额，剩余部分返回玩家账户
- 玩家可立即再次提现，但会再次被收取手续费
- 如果玩家要求补偿手续费，可填写工单交给二线处理

### 12.6 过量退款
- 退款只退订单金额，不进行部分退款
- 例如充值20笔$5，提现$99 → 可能退全部20笔$5=100，而不是19笔+退回4SC

### 12.7 查找某笔提现对应的退款清单
- Payment Center → 款项管理 → 退款管理
- 输入玩家ID搜索
- 对比退款记录的确认时间与提现的Paid/打款时间（同一天即为对应）
- 如果同一天有多笔提现被退款，只能汇总给玩家说明

### 12.8 Apple Pay 退款查不到的情况
- Apple Pay退款会原路退回绑定的credit card或debit card
- 玩家需查看：
  1. 绑定的信用卡/借记卡流水
  2. Apple Wallet里每张卡片的交易记录
- 提供refund list（金额、状态、原因、货币、时间UTC-0）
- 如果玩家仍无法找到，要求提供Apple Wallet录屏（10天内UTC-0）
- 提交工单让二线问支付组索要Refund Transaction Screenshots

---

## 十三、Prizeout 提现

### 13.1 提现流程
```
Dear Player,
Thank you for choosing Prizeout for your redemptions! Here's how to redeem your funds for gift cards:

How to Redeem via Prizeout:
1. Select "Redeem Gift Cards" during the redemption process.
2. Verify your redemption email - A verification code will be sent for security confirmation.
3. Enter your redemption amount - After verification, input the amount you wish to redeem.
   Minimum redemption: 5 SC (after redemption fee is charged).
   We'll automatically create a Prizeout account for you to manage redemptions.
4. Redemption completed!
   Your Prizeout account balance will be updated with the redeemed amount (after redemption fee is charged).
   You can then use this balance to purchase for gift cards.

Need Help?
For Prizeout-related questions (gift card redemption/usage), contact Prizeout Support.
For game-related issues, our team is happy to assist.

We appreciate you being part of our community. Happy Gaming!
```

### 13.2 Prizeout 到账时间
- 第一次询问（3小时内）：通常3小时内到账
- 超过3小时：提交工单让二线联系项目组加速

### 13.3 Prizeout 使用
- 兑换成功后，玩家Prizeout账户获得Credits
- 在Prizeout网站兑换各种Gift Cards
- 兑换5美元礼品卡可能得到超过5美元面额的礼品卡（具体优惠根据礼品卡种类）
- 兑换后显示Order Pending，通常几分钟内完成
- Wallet里可查看兑换记录

---

*最后更新：2025-07-21 (Cash App停用), 2025-09-09 (Debit Card新增)*
