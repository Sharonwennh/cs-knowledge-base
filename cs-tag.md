# CS-TAG 客服标签体系

> 最后更新：2026-06-17
> 使用方法：按一级分类 → 二级分类 → 标签代码 层级查阅

---

## Purchase / 充值

### Purchase Error / 充值错误

| Tag | 英文描述 | 中文描述 |
|-----|----------|----------|
| **P-No-Credit** | Charged but purchase package not received | 已扣款但充值礼包未到账 |
| **UA-P** | Unable to purchase (all channels failed, not blacklisted/fraud blocked) | 无法充值（所有渠道均失败，非黑名单/欺诈拦截） |
| **P-Fail** | Purchase shows "failed" or stays pending | 充值显示"失败"或一直处于pending状态 |
| **P-Dup-Charge** | Duplicate charge (player reports one purchase but charged multiple times) | 重复扣款（玩家只购买一次但被扣多次） |
| **P-Actum** | Actum bad debt order (unable to purchase / failed, requires escalation) | Actum坏账订单（无法充值/失败，需升级） |
| **P-Bonus-NR** | Purchased bonus spins not received (NR: Not Received) | 购买的bonus spins未到账（NR: Not Received） |
| **Sutton** | Specific Card BIN-Related Purchase Failure (BIN 403163 or 440393) | 特定卡BIN相关充值失败（BIN为403163或440393，发卡行问题） |
| **P-Extra-Fee** | Extra fees charged (e.g., bank tax, service fees) | 额外费用（如银行税、服务费等） |

### Purchase Inquiry / 充值咨询

| Tag | 英文描述 | 中文描述 |
|-----|----------|----------|
| **P-Inquiry** | Payment method inquiries (change card, available methods, why can't purchase via Apple Pay/PayPal, unbind card etc.) | 充值方式咨询（换卡、可用方式、为何不能用Apple Pay/PayPal、解绑卡等） |
| **P-Limit** | Game Play limit requests (RSG weekly/monthly limit, unable to purchase after limit) | 游戏充值限额（RSG周/月限额，达到限额后无法充值） |
| **P-Limit-Daily** | Daily purchase cap (e.g., Jackpot Spinning 777, Lucky Legends Web2Apk users) | 每日充值上限（如Jackpot Spinning 777、Lucky Legends Web2Apk用户） |
| **P-Restrict-HF** | Temporarily blacklisted in payment center (1-hour duration, reason: high-frequency purchase limit) | 支付中心临时黑名单（1小时，原因：高频充值限制） |
| **P-Restrict-HR** | Blacklisted in payment center (reason: too many cards) | 支付中心黑名单（原因：too many cards） |
| **P-Event-Rules** | Event-related purchase inquiries (cashback, rebate, subscriptions, etc.) | 充值活动相关咨询（cashback、rebate、subscription等） |

### Purchase Refund / 充值退款

| Tag | 英文描述 | 中文描述 |
|-----|----------|----------|
| **P-Refund** | Refund request with no reason given (must tag reason after identified) | 退款请求（未说明原因，确认原因后需补标签） |
| **P-Unauth** | Unauthorized purchase (player denies purchase / not made by them) | 未经授权的充值（玩家否认/非本人操作） |
| **P-Mistake** | Wrong purchase (player admits mistake, requests refund) | 充错（玩家承认操作错误，要求退款） |
| **P-As-R** | Purchase mistaken for redemption, refund requested | 把充值当成提现，要求退款 |
| **P-Cko-Fraud** | CKO fraud-related purchase dispute | CKO欺诈相关充值争议 |
| **Dispute** | Dispute filed against a successful purchase | 对成功充值发起争议 |

---

## Account / 账号

### Account Login / 账号登录

| Tag | 英文描述 | 中文描述 |
|-----|----------|----------|
| **E-Case** | Player cannot log in. After providing email/screenshot, found to be case-sensitive input error | 玩家无法登录。提供邮箱/截图后，发现是大小写输入错误 |
| **G-Load-Stuck** | Player cannot load into the game | 玩家无法加载进入游戏 |
| **A-Lost** | Player reports account lost, or created a new one after logging in. Needs help to recover original account | 玩家报告账号丢失，或登录后创建了新的。需要帮助找回原账号 |
| **A-Login-UA** | Player login failure without reason. Anonymous tickets with unlogged tag, or ticket shows UID but player claims unable to log in | 玩家无原因登录失败。匿名工单+未登录标签，或工单显示UID但玩家声称无法登录 |

### Account Inquiry / 账号咨询

| Tag | 英文描述 | 中文描述 |
|-----|----------|----------|
| **A-Multi** | Player created multiple accounts. Guide player to keep only one account; others require suspension | 玩家创建多账号。引导玩家只保留一个；其他需封禁 |
| **A-Inquiry** | All Account Related Issue: forgot password, needs reset, sees "account already registered," asks how to create account, how to bind email/phone, what is current email/phone number | 账号相关问题：忘记密码、需重置、显示"账号已注册"、问如何创建账号、如何绑定邮箱/手机、当前邮箱/手机号是什么 |
| **A-KYC** | General Account KYC request, KYC rejected, KYC cannot complete, etc. | 账号KYC相关：KYC申请、被拒、无法完成等 |

### Account Suspension / 账号封禁/冻结

| Tag | 英文描述 | 中文描述 |
|-----|----------|----------|
| **A-Freeze-LT** | Account suspended (Freeze or Banned) due to low turnover ratio; purchases fully refunded, required by producer | 账号被冻结/封禁（低流水比例；充值全额退款，项目组要求） |
| **A-Freeze-Multi** | Account suspended (Freeze or Banned) due to multiple accounts, as instructed by project team | 账号被冻结/封禁（多账号，项目组要求） |
| **A-Freeze-minor** | Player reported underage minor, or system detected underage in registration, redemption, or KYC. Must suspend account, notify player, and record in Ban Notice table | 玩家举报未成年，或系统在注册/提现/KYC中检测到未成年。必须封号、通知玩家、记录在Ban Notice表 |
| **A-Freeze-PP** | Account suspended (Freeze or Banned) after player contacted PayPal/payment group for refund | 玩家联系PayPal/支付组要求退款后账号被冻结/封禁 |
| **A-Freeze-Dispute** | Account suspended (Freeze or Banned) due to unresolved dispute | 未解决争议导致账号被冻结/封禁 |
| **A-Freeze-P-Exp** | Account suspended (Freeze or Banned) due to malicious exploitation of Purchase loophole | 恶意利用充值漏洞导致账号被冻结/封禁 |
| **A-Unfreeze-DTS** | Player previously wants delete account / Take a Break / Self Exclusion now demand unfreeze account (DTS: delete account / Take a Break / Self Exclusion) | 玩家之前要求删号/休息/自我排除，现在要求解冻（DTS: delete account / Take a Break / Self Exclusion） |
| **A-Unfreeze-Unauth** | Player previously reported Unauthorized purchase or unauthorized login. Now demand unfreeze the account | 玩家之前举报未经授权充值/登录，现在要求解冻账号 |
| **A-Ban-TZ** | Account suspended because player changed device time zone or traveled abroad (e.g., UTC+8). TZ: Time Zone | 玩家修改设备时区或出国（如UTC+8）导致账号被封禁（TZ: Time Zone） |
| **A-Ban-HighRisk** | Player has Banned Due to High-Risk Controversial | 高争议风险玩家被封禁 |

### Account Modification / 账号修改

| Tag | 英文描述 | 中文描述 |
|-----|----------|----------|
| **A-KYC-Merge** | When player inquires about an account issue, account has a KYC Merge record (Legends Games) or an "Account Transfer" record (Acorn Games) in Gameflow or Action Records | 玩家咨询账号问题，发现账号有KYC合并记录（Legends）或"账号转移"记录（Acorn） |
| **A-E-Mod** | Player requests to modify email due to stolen, invalid, or incorrect email | 玩家因邮箱被盗/无效/错误要求修改邮箱 |
| **A-Del** | Player requests to delete account | 玩家要求删除账号 |
| **A-Del-Error** | Account shows deletion reason "user self-deletion." Backend shows no agent operation | 账号显示删除原因为"用户自行删除"，后台无客服操作记录 |
| **Self Exclusion** | Player reports gambling problem and requests permanent deletion, or temporary pause to stop playing | 玩家报告赌博问题，要求永久删除或临时暂停游戏 |

---

## Redemption / 提现

### Redemption General Inquiry / 提现通用咨询

| Tag | 英文描述 | 中文描述 |
|-----|----------|----------|
| **R-General** | General redemption inquiries (methods, eligibility, how to receive funds, etc.) | 通用提现咨询（方式、资格、如何收款等） |
| **R-Cancel** | Redemption Cancellation request | 取消提现请求 |
| **R-KYC** | KYC-related inquiries (failure reasons, how to verify, whether passed, acceptable documents, etc.) | KYC相关咨询（失败原因、如何验证、是否通过、可接受文件等） |
| **R-Fee** | Complaints about high fees or sudden fee increase | 手续费高或突然涨价投诉 |
| **R-A** | Redemption Account inquiries (basic redemption account inquire method, where sent to, check if it's correct redemption account) | 提现账户咨询（基本信息、发到哪里、核对账户是否正确） |
| **R-A-Change** | Redemption Account Change (Paypal, ACH, Venmo) | 更改提现账户（PayPal/ACH/Venmo） |
| **R-A-BadInfo** | Before Binding actual Redemption Accounts, a pop-up window will sometimes shows up that requires players to verify redemption information. This tag is specific to this information input error | 绑定提现账户前弹窗要求验证提现信息，此标签专用于信息输入错误 |

### Redemption Account Inquiry / 提现账户咨询

| Tag | 英文描述 | 中文描述 |
|-----|----------|----------|
| **R-PP-info** | Paypal account authentication inquiries, how to use this method etc. | PayPal账户认证咨询、如何使用等 |
| **R-ACH-info** | ACH account authentication inquiries, how to use this method etc. | ACH账户认证咨询、如何使用等 |
| **R-PO-info** | Prizeout account authentication inquiries, how to use this method etc. | Prizeout账户认证咨询、如何使用等 |
| **R-DC-info** | Debit Card account authentication inquiries, how to use this method etc. | Debit Card账户认证咨询、如何使用等 |
| **R-VM-info** | Venmo account authentication inquiries, how to use this method etc. | Venmo账户认证咨询、如何使用等 |
| **R-PP-gone** | Players don't have access to their Paypal account anymore | 玩家无法访问PayPal账户 anymore |
| **R-ACH-gone** | Players don't have access to their ACH account anymore | 玩家无法访问ACH账户 anymore |
| **R-DC-gone** | Players don't have access to their Debit Card anymore | 玩家无法访问Debit Card anymore |
| **R-VM-gone** | Players don't have access to their Venmo account anymore | 玩家无法访问Venmo账户 anymore |
| **R-E-PP** | Paypal Redemption Email Verification | PayPal提现邮箱验证 |
| **R-E-PO** | Prizeout Redemption Email Verification | Prizeout提现邮箱验证 |

### Redemption Timeframe Inquiry / 提现时效咨询

| Tag | 英文描述 | 中文描述 |
|-----|----------|----------|
| **R-Time-Pending** | Inquiry during normal redemption processing time (player asks why funds have not been received yet) | 正常处理时间内，玩家问为什么还没收到钱 |
| **R-Time-Sent** | Player inquires about receiving time (e.g., submitted on May 15, sent on May 17, player asks on May 18; When not OT) | 玩家询问具体到账时间（非超时情况） |
| **R-OT-PP-XXX** | Paypal Redemption pending over 24hours + Current Backend Redemption Status. eg.:R-OT-PP-113 | PayPal提现超过24小时未到账+后台状态码（如R-OT-PP-113） |
| **R-OT-ACH-XXX** | ACH Redemption pending over 3 Days + Current Backend Redemption Status. eg.:R-OT-ACH-106 | ACH提现超过3天未到账+后台状态码（如R-OT-ACH-106） |
| **R-OT-PO-XXX** | Prizeout Redemption pending over 3 Hours + Current Backend Redemption Status. eg.:R-OT-PO-103 | Prizeout提现超过3小时未到账+后台状态码（如R-OT-PO-103） |
| **R-OT-DC-XXX** | Debit Card Redemption pending over 24hours + Current Backend Redemption Status. eg.:R-OT-DC-1 | Debit Card提现超过24小时未到账+后台状态码（如R-OT-DC-1） |
| **R-OT-VM-XXX** | Venmo Redemption pending over 24hours + Current Backend Redemption Status. eg.:R-OT-VM-1 | Venmo提现超过24小时未到账+后台状态码（如R-OT-VM-1） |
| **R-OT-104/105** | Redemption status 104/105 pending >3hours. | 状态码104/105且pending超过3小时 |
| **R-OT-2/Lock** | Redemption lock-in status pending >7days. | 提现锁定状态超过7天 |
| **R-GC** | Golden Acorns/Gold Coins inquiries (why not redeemable, whether convertible to cash, etc.) | 金猪/GC咨询（为什么不可提现、能否换现金等） |
| **R-PP-Limit** | PayPal redemption limit (≤$1500 per transaction, ≤$5000 per day, UTC-8 refreshed) | PayPal提现限额（单笔≤$1500，每日≤$5000，UTC-8刷新） |
| **R-PP-Reset** | PayPal redemption weekly maintenance. Maintenance is scheduled to be completed every Thursday at 00:00 UTC+0. Players can retry using PayPal for Redemptions after this time. | PayPal每周维护（周四00:00 UTC+0完成，维护后重试） |

### Redemption Issue / 提现问题

| Tag | 英文描述 | 中文描述 |
|-----|----------|----------|
| **Unable to Redeem** | Unable to redeem (no specific reason provided, follow-up needed to identify cause). Correct info entered but unable to submit redemption. | 无法提现（无具体原因，需跟进确认）。信息正确但无法提交提现。 |
| **R-Fail-PP** | Paypal Redemption failed | PayPal提现失败 |
| **R-Fail-ACH** | ACH Redemption failed | ACH提现失败 |
| **R-Fail-PO** | Prizeout Redemption failed | Prizeout提现失败 |
| **R-Fail-VM** | Venmo Redemption failed | Venmo提现失败 |
| **R-Fail-DC** | Debit Card Redemption failed | Debit Card提现失败 |
| **R-Cheat** | Redemption pending, no payout for now. Project team provided reason: [Pending, suspected cheating requires verification] (mainly seen in Legends project) | 提现pending，暂未打款。项目组反馈：疑似作弊需验证（多见于Legends） |
| **R-AML** | Redemption pending, no payout for now. Project team provided reason: [Pending, suspected money laundering requires verification]. AML stands for Anti Money Laundering | 提现pending，暂未打款。项目组反馈：疑似洗钱需验证（AML: Anti Money Laundering） |

### Other Redemption Issue / 其他提现问题

| Tag | 英文描述 | 中文描述 |
|-----|----------|----------|
| **R-CAN-CAP** | Currently, the only redemption channel available for Canadian (CA) players is PayPal. However, PayPal has a daily total redemption limit. If the daily limit is fully exhausted, players will not receive any response when clicking the "Redeem" button. Players try redeeming again after the daily refresh at 00:00 UTC-8. | 加拿大玩家唯一可用提现渠道为PayPal，但有每日限额。限额耗尽后点击Redeem无反应。UTC-8 00:00刷新后重试。 |
| **R-F-Free-169** | Jackpot go ios Player join Free-fee Tuesday, but redemption fee was not waived | Jackpot Go iOS玩家参加周二免手续费活动，但手续费未免除 |
| **0203-R-DC-Failed** | When players contact to ask about the reason for their failed redemptions, first check the table: 2026-02-03 Debit Card Redemption Failed Player List. | 玩家询问提现失败原因，先查2026-02-03 Debit Card提现失败名单 |

---

## Verification Email / 验证邮件

### Verification Email Inquiry / 验证邮件咨询

| Tag | 英文描述 | 中文描述 |
|-----|----------|----------|
| **V-E-Inquiry** | Player reports not receiving account, redemption, or reset password verification email | 玩家未收到账号/提现/重置密码验证邮件 |

### Email Error / 邮件错误

| Tag | 英文描述 | 中文描述 |
|-----|----------|----------|
| **Sub-Cancel** | Player reports not receiving various emails. Records show the player unsubscribed | 玩家未收到各类邮件，记录显示玩家已退订 |
| **E-Not-Sent** | Player reports clicking to verify but did not receive verification email. This tag need to added to ticket when Tier 2 inform in task email was not sent out by system | 玩家点击验证但未收到邮件。Tier 2确认系统未发出时添加此标签 |

---

## Game Session / 游戏会话

### Game Session Error / 游戏会话错误

| Tag | 英文描述 | 中文描述 |
|-----|----------|----------|
| **G-Crash** | Game crashes back to lobby (either during a round or before entering the slot). Game keeps spinning without stopping. | 游戏崩溃回大厅（游戏中或进入机台前）。游戏一直spin不停。 |

### Game Session Inquiry / 游戏会话咨询

| Tag | 英文描述 | 中文描述 |
|-----|----------|----------|
| **G-No-Reward** | Round reward not received (confirmed missing → compensate or escalate). (If later found already received → belongs to G-Gameflow Tag.) | 未收到局内奖励（确认缺失→补偿或升级；若后来发现已收到→转G-Gameflow） |

---

## Game Bug / 游戏Bug

### Game Bug / 游戏Bug

| Tag | 英文描述 | 中文描述 |
|-----|----------|----------|
| **G-Lag** | Game freezes, temporarily freezes then recovers, Glitches or completely stuck. | 游戏卡顿、暂时冻结后恢复、完全卡住 |
| **G-App-Crash** | Crash on game main screen; in-session crashes are categorized under "session crash" | 游戏主屏幕崩溃（局内崩溃归类于G-Crash） |
| **G-Crash-Freq** | Repeated game crashes. Freq:Frequent | 频繁游戏崩溃（Freq: Frequent） |
| **G-Con-Lost** | Forced exit after "lost connection" prompt. Con:Connection | "连接丢失"提示后强制退出（Con: Connection） |
| **G-Scr-BW** | Black screen / white screen. Scr:Scr-BW: Black/White | 黑屏/白屏（Scr: Screen, BW: Black/White） |
| **G-Con-Err** | Connection error or network error. Con: Connection, Err: Error | 连接错误或网络错误（Con: Connection, Err: Error） |
| **G-Net-Err** | Player unable to enter game, stuck on loading screen. Net: Network, Err: Error | 玩家无法进入游戏，卡在加载界面（Net: Network, Err: Error） |
| **Display Error** | Interface display anomalies | 界面显示异常 |
| **Text Error** | In-game text errors | 游戏内文字错误 |
| **Sound Error** | Sudden loss of music/audio in-game; cannot toggle music & sound. | 游戏内突然丢失音乐/音频；无法切换音乐和声音 |
| **G-Slot-Load-Stuck** | Player unable to enter slot/game, stuck on loading screen. | 玩家无法进入机台/游戏，卡在加载界面 |
| **G-Slot-Region-UA** | Some individual slot machines are inaccessible due to regional restrictions, showing the error:"Sorry, this game is not available in your location / region". This occurs because certain third-party slot machines cannot operate in some regions, making them unplayable for players. | 某些机台因地区限制无法访问，显示"Sorry, this game is not available in your location/region"（第三方机台在某些地区无法运营） |
| **UA-Freeze** | Special tag for backend unable to submit freeze request (currently Poker & Luckhit). | 后台无法提交冻结请求的特殊标签（目前Poker & Luckhit） |
| **R-Unplayed SC-Ded** | Unplayed SC deducted during redemption. Ded: Deducted | 提现时Unplayed SC被扣除（Ded: Deducted） |
| **Winner_415-Bug** | Slot display issues: HYPERNOVAMEGAWAYS | 机台显示问题：HYPERNOVAMEGAWAYS |
| **Winner_406-Bug** | Slot display issues: Atlantis. | 机台显示问题：Atlantis |
| **G-SC-NR 347** | 2025-10-29 Acorn project team App ID: 347. Event or purchase SC balance not credited to players' game accounts | 2025-10-29 Acorn项目App ID: 347，活动或购买SC余额未到账 |

### Other Bug / 其他Bug

| Tag | 英文描述 | 中文描述 |
|-----|----------|----------|
| **7.10 Login Disappeared** | App ID 136 7-day login rewards disappeared. | App ID 136 的7天登录奖励消失 |
| **725RP** | 2025-07-25, payout platform sent duplicate redemption. | 2025-07-25，支付平台发送了重复redemption |
| **825AcornError** | 2025-08-25, player topped up $300 but transaction record shows only 20SC reward. | 2025-08-25，玩家充值$300但交易记录只显示20SC奖励 |
| **12-15 CA-UA** | For players from CA (California) reporting login failures. Add the corresponding ticket tag: 12-15 CA-UA for California players. Submit a task and escalate it to Tier 2. | 加州（CA）玩家登录失败专用标签。提交任务升级给Tier 2 |
| **12-15 NY-UA** | For players from NY (New York) reporting login failures. Add the corresponding ticket tag: 12-15 NY-UA for New York players. Submit a task and escalate it to Tier 2. | 纽约（NY）玩家登录失败专用标签。提交任务升级给Tier 2 |
| **260227-Gleam-RefSpin** | Bug: Referral spin issues – players unable to spin after clicking the spin button. Game: Gleaming Series games. After clicking the Spin button, the wheel does not spin and spin attempts are not deducted. | 推荐spin问题：Gleaming Series游戏，点击Spin按钮后转盘不转且次数不扣除 |
| **4-1 Booming** | There is a bug Last night on the Booming series slot machines: spins do not consume SC, but rewards are issued normally. The Acorn Project team has temporarily Banned all affected players' accounts. | Booming系列机台bug：spin不消耗SC但奖励正常发放。Acorn项目组已临时封禁受影响玩家 |
| **4.21-Invitation Reward spin bug** | Malfunction of Friend Invitation Reward Wheel. Due to a bug, players were able to perform the Reward spin an unlimited number of times after successfully inviting a friend. | 好友邀请奖励转盘故障：成功邀请后可无限次奖励spin |

---

## General Inquiry / 通用咨询

### Ad Inquiry / 广告咨询

| Tag | 英文描述 | 中文描述 |
|-----|----------|----------|
| **Ad-No-Reward** | Ad reward not received after watching. | 看完广告未收到奖励 |
| **Ad-Net-Error** | Ad shows network error. | 广告显示网络错误 |
| **Ad-Black** | Black screen or crash after clicking ad. | 点击广告后黑屏或崩溃 |
| **Ad-Mislead** | False/misleading ads. | 虚假/误导性广告 |
| **Ad-Bonus-Spin** | 62/290 Ads in these two games contain promotional content for the HowlingWolves slot. If the player can provide a screenshot showing the 20 free bonus rounds, a reward can be issued. | 62/290两款游戏广告包含HowlingWolves机台推广内容，玩家提供截图证明20次免费bonus rounds可发放奖励 |
| **Ad-Down-Reward** | Promo ad reward not received (download/redemption). Down: Download | 推广广告奖励未收到（下载/提现相关。Down: Download） |
| **SoM-Inquiry** | For all subsequent player inquiries regarding social media platform-related issues (eg. campaigns on Facebook or Instagram). SoM stands For Social Media | 社交媒体平台相关问题（如Facebook或Instagram活动。SoM: Social Media） |

### Event Inquiry / 活动咨询

| Tag | 英文描述 | 中文描述 |
|-----|----------|----------|
| **EVE-Inquiry** | Non-purchase event inquiries, player had concern on how event works (event rules etc) | 非充值活动咨询，玩家问活动规则等 |
| **EVE-LF** | Lucky Flip event inquiries. | Lucky Flip活动咨询 |
| **EVE-MR** | Money Return event inquiries. | Money Return活动咨询 |
| **G-Invitation** | Invitation function inquiries (whether available, how to invite). | 邀请功能咨询（是否可用、如何邀请） |
| **Promo Code** | Promo code inquiries (availability, usage). | 兑换码咨询（可用性、使用方法） |
| **G-Download** | Download issues (where/how to download). | 下载问题（哪里下载/如何下载） |
| **G-Update** | Game update inquiries (next update, content). | 游戏更新咨询（下次更新、内容） |
| **G-Rules** | Game rules inquiries (how to play, slot rules, bet settings). | 游戏规则咨询（怎么玩、机台规则、下注设置） |
| **G-Gameflow** | Gameflow record inquiries (daily reward, comeback reward, match reward, SC/GC balance, etc.). | 游戏流程记录咨询（每日奖励、回归奖励、对局奖励、SC/GC余额等） |
| **A-LT-HR** | Acorn: low turnover/high redemption ratio players cannot see some in-game events. LT for Low Turnover, HR for High Redemption | Acorn：低流水/高提现比例玩家看不到某些游戏内活动（LT: Low Turnover, HR: High Redemption） |
| **A-LR** | Legends : low Rollover ratio players cannot see some in-game events. LR for low Rollover ratio | Legends：低流水比例玩家看不到某些游戏内活动（LR: Low Rollover） |

### General Question / 通用问题

| Tag | 英文描述 | 中文描述 |
|-----|----------|----------|
| **Integrity** | Fairness complaints (game is scam, fraud, etc.). | 公平性投诉（游戏是骗局、欺诈等） |
| **G-General** | Inquiries about gameplay and settings (can win real money?, playing without purchase, free SC/GC, how to win, change avatar, change name, sound settings, etc.) | 游戏玩法和设置咨询（能否赢真钱、不充值怎么玩、免费SC/GC、如何获胜、改头像、改名字、声音设置等） |
| **A-Region Restrict** | Player located in restricted state (via IP check or player self-report). | 玩家位于限制州（通过IP检测或玩家自报） |
| **A-KYC-Restrict States** | KYC shows player in restricted state. | KYC显示玩家在限制州 |
| **Unsubscription** | Unsubscribe from emails inquiries. | 退订邮件咨询 |
| **P-To win** | Complaints about needing purchase to win. | 投诉需要充值才能赢 |
| **AMOE** | Any AMOE related inquiries | 任何AMOE相关咨询 |

---

## AI Help Operate / 系统操作

### Reassign Ticket / 转派工单

| Tag | 英文描述 | 中文描述 |
|-----|----------|----------|
| **W-AI** | This tag is only needed if an error occurs during the initial system allocation and the order needs to be transferred. However, if the player later raises other issues, such as initially raising redemption and then purchasing, the W-AI tag is not required. | 初始系统分配错误需转派时使用。若玩家后续提出其他问题（如先问提现后问充值），则不需要此标签 |
| **OFS-A-Event** | Out-of-Scope: player initially asks about a topic within your job scope but later raises questions that belong to Acorn Event queue. | 超范围：玩家最初问职责范围内问题，后转问Acorn活动队列问题 |
| **OFS-L-Event** | Out-of-Scope: player initially asks about a topic within your job scope but later raises questions that belong to Legends Event queue. | 超范围：玩家最初问职责范围内问题，后转问Legends活动队列问题 |
| **OFS-Redemption** | Out-of-Scope: player initially asks about a topic within your job scope but later raises questions that belong to Redemption queue. | 超范围：玩家最初问职责范围内问题，后转问提现队列问题 |
| **OFS-Purchase** | Out-of-Scope: player initially asks about a topic within your job scope but later raises questions that belong to Purchase queue. | 超范围：玩家最初问职责范围内问题，后转问充值队列问题 |

### Need Reply / 需回复

| Tag | 英文描述 | 中文描述 |
|-----|----------|----------|
| **Need Reply** | Escalation cases: Waiting for reply from Tier 2 or player. Transfer ticket: Waiting for other team to handle. Ticket will not auto-close after added this tag. | 升级案例：等待Tier 2或玩家回复。转派工单：等待其他团队处理。加此标签后工单不会自动关闭 |

### UID cannot be found / 后台找不到UID

| Tag | 英文描述 | 中文描述 |
|-----|----------|----------|
| **No ID-Re** | For any subsequent cases where the UID cannot be found in the Backend, please explain to the player that due to a system issue, they need to close the game, restart it, and then submit a support ticket. After replying, you may mark the ticket as "Resolved". | 后台找不到UID。告知玩家因系统问题需关闭游戏、重启、重新提交工单。回复后可标记为"Resolved" |

### In-Game Channel Agents / 游戏内渠道客服

| Tag | 英文描述 | 中文描述 |
|-----|----------|----------|
| **A-event** | For Transferred tickets concerning in-game events under the Acorn Project Team. | 转派工单：Acorn项目组游戏内活动 |
| **L-event** | For Transferred tickets concerning in-game events under the Legends Project Team. | 转派工单：Legends项目组游戏内活动 |
| **Machine** | For tickets related to in-game slots machines (e.g., machine malfunctions, gameplay issues on specific machines). | 转派工单：游戏内机台问题（机台故障、特定机台玩法问题） |

---

## First Response / 首次回复

### Transferring Ticket Tag / 转派标签

| Tag | 英文描述 | 中文描述 |
|-----|----------|----------|
| **F-R** | First response Agent confirms Ticket issue belongs to Redemption Queue. Then transfer to redemption Queue Agent | 首次回复客服确认工单属于Redemption队列，转给提现队列客服 |
| **F-P** | First response Agent confirms Ticket issue belongs to Purchase Queue. Then transfer to Purchase Queue Agent | 首次回复客服确认工单属于Purchase队列，转给充值队列客服 |
| **F-A-event** | First response Agent confirms Ticket issue belongs to Acorn Event Queue. Then transfer to Acorn Event Queue Agent | 首次回复客服确认工单属于Acorn Event队列，转给Acorn活动队列客服 |
| **F-L-event** | First response Agent confirms Ticket issue belongs to Legends Event Queue. Then transfer to Legends Event Queue Agent | 首次回复客服确认工单属于Legends Event队列，转给Legends活动队列客服 |
| **F-Ingame** | First response Agents confirm Ticket issue does not belong to their own job scope and does not belong to redemption+Purchase+Acorn event+Legends event Queue. Then transfer to Ingame Channel Queue Agent | 首次回复客服确认工单不属于自己工作范围，也不属于提现+充值+Acorn活动+Legends活动队列，转给Ingame Channel队列客服 |

---

## In-game Agent / 游戏内客服

### Transferring Ticket Tag / 转派标签

| Tag | 英文描述 | 中文描述 |
|-----|----------|----------|
| **I-F** | In-game Channel Agent confirms Ticket issue belongs to FRA Queue. Then transfer to FRA Queue Agent | 游戏内渠道客服确认工单属于FRA队列，转给FRA队列客服 |
| **I-R** | In-game Channel Agent confirms Ticket issue belongs to Redemption Queue. Then transfer to redemption Queue Agent | 游戏内渠道客服确认工单属于Redemption队列，转给提现队列客服 |
| **I-P** | In-game Channel Agent confirms Ticket issue belongs to Purchase Queue. Then transfer to Purchase Queue Agent | 游戏内渠道客服确认工单属于Purchase队列，转给充值队列客服 |
| **I-A-event** | In-game Channel Agent confirms Ticket issue belongs to Acorn Event Queue. Then transfer to Acorn Event Queue Agent | 游戏内渠道客服确认工单属于Acorn Event队列，转给Acorn活动队列客服 |
| **I-L-event** | In-game Channel Agent confirms Ticket issue belongs to Legends Event Queue. Then transfer to Legends Event Queue Agent | 游戏内渠道客服确认工单属于Legends Event队列，转给Legends活动队列客服 |

---

## Sumsub Applicant / Sumsub KYC

### KYC Handling Tag / KYC处理标签

| Tag | 英文描述 | 中文描述 |
|-----|----------|----------|
| **SA-Approve** | When you click "Approve" to pass the player's KYC via Sumsub. | 点击"Approve"通过玩家KYC（Sumsub） |
| **SA-Reset** | When you reset the player's KYC process via Sumsub. | 通过Sumsub重置玩家KYC流程 |
| **SA-Dup** | For the multi-account Tickets that T1 agents can process directly using the Sumsub Applicant feature, without the need to create a task for T2. | 多账号工单，T1客服可直接使用Sumsub Applicant功能处理，无需为T2创建任务 |
| **SA-T2-BLACKLIST** | When you can't handle the KYC ticket due to BLACKLIST Tag in sumsub applicant backend and need to submit it to Tier 2. | Sumsub后台有BLACKLIST标签，无法处理，需提交Tier 2 |
| **SA-T2-BLOCKLIST** | When you can't handle the KYC ticket due to BLOCKLIST Tag in sumsub applicant backend and need to submit it to Tier 2. | Sumsub后台有BLOCKLIST标签，无法处理，需提交Tier 2 |
| **SA-T2-DUP** | When you can't handle the KYC ticket due to Duplicate Tag in sumsub applicant backend and need to submit it to Tier 2. | Sumsub后台有Duplicate标签，无法处理，需提交Tier 2 |
| **SA-T2-FORGERY** | When you can't handle the KYC ticket due to FORGERY Tag in sumsub applicant backend and need to submit it to Tier 2. | Sumsub后台有FORGERY标签，无法处理，需提交Tier 2 |
| **SA-T2-WUR** | When you can't handle the KYC ticket due to WRONG_USER_REGION Tag in sumsub applicant backend and need to submit it to Tier 2. | Sumsub后台有WRONG_USER_REGION标签，无法处理，需提交Tier 2 |
| **SA-T2-Unsat-Age** | When you can't handle the KYC ticket due to Unsatisfactory age Tag in sumsub applicant backend and need to submit it to Tier 2. | Sumsub后台有Unsatisfactory age标签，无法处理，需提交Tier 2 |
| **SA-T2-Image-limit** | When you can't handle the KYC ticket due to Images limit reached Tag in sumsub applicant backend and need to submit it to Tier 2. | Sumsub后台有Images limit reached标签，无法处理，需提交Tier 2 |
| **SA-T2-Other** | When you can't handle the KYC ticket And the sumsub applicant tag does not belong to Below 7 scenarios (BLACKLIST, BLOCKLIST, DUP, FORGERY, WUR, Unsat-Age, Image-limit). | 无法处理KYC工单，且Sumsub applicant标签不属于以上7种场景（BLACKLIST/BLOCKLIST/DUP/FORGERY/WUR/Unsat-Age/Image-limit） |
| **SA-IR** | When no Sumsub button is needed; just tell the player to continue KYC. Or Player is KYC-rejected need to freeze. | 不需要Sumsub按钮时；只需告诉玩家继续KYC。或玩家KYC被拒需要冻结 |

---

## Others / 其他

### Feedback / 反馈

| Tag | 英文描述 | 中文描述 |
|-----|----------|----------|
| **Feedback** | Escalate to Tier 2 with recommendation | 反馈（升级给Tier 2并附建议） |

### Report Violation / 举报违规

| Tag | 英文描述 | 中文描述 |
|-----|----------|----------|
| **G-Violation** | Player avatar/nickname violation | 玩家头像/昵称违规 |
| **Ad-Content** | Report inappropriate ad content | 举报不当广告内容 |

### Later / 稍后回复

| Tag | 英文描述 | 中文描述 |
|-----|----------|----------|
| **Later** | Reply later | 稍后回复 |

### Tier 2 / Tier 2

| Tag | 英文描述 | 中文描述 |
|-----|----------|----------|
| **Tier 2** | Ticket transferred from Tier 1, Tier 2 agent needs to add this tag | 从Tier 1转派的工单，Tier 2客服需添加此标签 |

### Device Incompatibility / 设备不兼容

| Tag | 英文描述 | 中文描述 |
|-----|----------|----------|
| **Device-error** | Player reports game interface cannot display fullscreen. | 玩家报告游戏界面无法全屏显示 |

### Lawsuit Risk / 诉讼风险

| Tag | 英文描述 | 中文描述 |
|-----|----------|----------|
| **LGL** | Ticket with yellow-highlighted text, This player may have lawsuit risk against Company | 黄标高亮文本，玩家可能有诉讼风险 |
| **Suicide** | Players Making Suicide Threats | 玩家有自杀威胁 |

### Closeable / 可关闭

| Tag | 英文描述 | 中文描述 |
|-----|----------|----------|
| **Closeable** | Player's question has all been answered, and currently has no other issues that need to be resolved. This ticket can be tagged with the Closeable tag | 玩家问题已全部回答，当前无其他待解决问题 |

---

## Rejected Tickets / 无效工单

### Blank Ticket / 空白工单

| Tag | 英文描述 | 中文描述 |
|-----|----------|----------|
| **Blank Ticket** | Empty email content or empty ticket submission. | 空邮件或空工单提交 |

### Spam / 垃圾信息

| Tag | 英文描述 | 中文描述 |
|-----|----------|----------|
| **Spam** | Pornographic content, images, or unreadable characters (if player replies with garbled content after first response). | 色情内容、图片或乱码（首次回复后玩家回复乱码内容） |

### Ad-Promo / 广告推广

| Tag | 英文描述 | 中文描述 |
|-----|----------|----------|
| **Ad-Promo** | Advertising, promotional messages. | 广告、推广信息 |

---
