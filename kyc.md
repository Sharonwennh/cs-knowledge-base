# KYC 知识库

## 一、KYC 概述

KYC (Know Your Customer) 用于验证玩家身份信息，防止欺诈和洗钱。

### KYC 字段状态说明（Overview / Redemption 模块）

| 状态码 | 含义 |
|--------|------|
| **0** | 触发了KYC |
| **1** | KYC未完成，可继续上传材料 |
| **2** | 玩家通过KYC |
| **3** | 之前上传失败，仍可继续尝试 |
| **4** | KYC失败，需要人工介入 |

**目前只看 ID 和 POA 两项即可。**

POA 包括旧POA验证方式以及新加入的 SSN（Social Security Number）验证方式。

---

## 二、KYC 等级

| 等级 | 验证内容 | 触发条件 |
|------|----------|----------|
| **KYC-age** | 验证年龄、地区（手动输入信息） | 注册时 |
| **KYC-ID** | 上传身份ID证件 + 实时人脸照片 | 提现前必须完成 |
| **KYC-POA** | 上传身份ID证件 + 实时人脸照片 + 居住证明文件 | 已提现金额2000以上 |

**2025-07-11 更新：** 新加入 SSN 验证，提现达到2000触发KYC-POA时，Sumsub 可让玩家做 SSN 验证。

---

## 三、接受的证件类型

### 3.1 身份ID（只接受美国当地ID）
- ✅ Passport（护照）
- ✅ ID card（身份证）
- ✅ Driver's license（驾照）
- ✅ Residence permit（居留许可）
- ❌ Screenshots（截图）

### 3.2 地址证明 (Proof of Address)
接受以下文件（不超过3个月）：
- ✅ Utility bill（水电费账单）
- ✅ Bank/credit card statement（银行/信用卡账单）
- ✅ Tax invoice（税务发票）
- ✅ Government-issued residential statement/certificate（政府签发的居住证明）

不接受：
- ❌ Screenshots（截图）
- ❌ Mobile phone bills（手机账单）
- ❌ Medical bills（医疗账单）
- ❌ Receipts（收据）
- ❌ Insurance statements（保险账单）
- ❌ 金融App的bank statement（如 Cash App / Chime），请让玩家提传统银行的bank statement

---

## 四、KYC 验证处理时间

| 场景 | 回复话术 |
|------|----------|
| **国内周中工作时间**（截止到下午5:30） | Thank you for your patience. We've escalated your issue to the relevant team for further review. This may take up to two hours. We'll update you as soon as there's any progress. |
| **国内非工作时间**（9:00-17:30以外） | Thank you for reaching out. Due to the time difference, the relevant team is currently unavailable. However, please rest assured that your issue has been noted, and we will get back to you with an update within 24 hours. |
| **周末KYC工单**（周五17:30到周一9:00） | We've received your message and truly appreciate your patience. Due to the time difference and the weekend schedule of the relevant team, your issue will be handled first thing on Monday. We will notify you immediately once we have an update. Thank you for your understanding. |

**注意：** Lavish Luck 产品正在实验KYC用机器人自助开单，处理到问题的同学记得把关注人改为自己。话术纳入质检范围。

---

## 五、KYC 平台

目前有两个KYC供应商：
- **Sumsub**（当前主要使用）
- **Jumio**（已停用）

玩家发过来的KYC界面会有两种，需识别。

---

## 六、常见 KYC 状态处理

### 6.1 玩家验证失败
- 发起工单，二线处理

### 6.2 多账号KYC冲突
- 玩家在其他账户做过KYC验证，当前账户验证被拒绝
- 一般出现在多账号情况
- 需查验玩家是否有多账号，按多账号处理流程让玩家只保留一个号，再处理保留账号的KYC验证

### 6.3 验证平台正在验证数据
- 让玩家耐心等待，一般只需几分钟，特殊情况可能需要几个小时

### 6.4 进度条不是全绿（红色部分）
- 红色部分就是出问题的地方
- 阅读下方文字提醒，给玩家相应指引
- 玩家可以自己操作上传新的信息

### 6.5 KYC验证成功 / Face Authentication完成
- 需玩家提供截图确认
- 否则可能是失败或玩家未按规完成人脸验证

---

## 七、SSN 验证

SSN 验证效力等同于 KYC-POA 验证。

在 Overview 或 redemption 页面，如果玩家进行了 SSN 验证，也会显示成 POA()。

### 7.1 SSN 验证方式
1. **完整SSN验证**（9位数字）
2. **后四位SSN + 玩家手机号**

### 7.2 SSN 被拒绝
- 项目组会手动给玩家切换到 POA，或让玩家联系客服

### 7.3 为什么需要 SSN
```
Dear Player,

We want to take a moment to explain why we require SSN verification for your account. This important step helps us:

-Ensure Legal Compliance - Verify you're playing from an authorized location where our games are properly licensed.
-Protect Your Account - Add an extra layer of security to prevent unauthorized access and fraud.
-Meet Financial Regulations - Comply with anti-money laundering (AML) laws that help keep gaming fair and secure for everyone.

Your information is protected with bank-level encryption and will only be used for these verification purposes. We appreciate your understanding as we work to maintain a safe and legal gaming environment for all our players.

If you have any concerns about this process, our support team is always happy to help.
Have a great day.
```

---

## 八、让玩家提供截图

```
Dear Player,
We sincerely apologize for any inconvenience you may have experienced.
To assist you more effectively, please provide the following information:

Technical Issues: If you encountered technical difficulties completing the verification steps, kindly share a screen recording of the entire process.
Document Verification: If you are facing challenges with document verification, please provide a screenshot of the specific error message or result displayed by the verification platform or the game,

We are committed to resolving your issue promptly. Please feel free to contact our support team for further assistance.
Thank you for your understanding.
```

---

## 九、为什么要做KYC

```
Dear player,
Thank you for your patience.
Due to the laws and regulations, we must do our due diligence to prevent money laundering in our app. By finishing the KYC Verification, we can confirm your account is owned by yourself, this is also a way to avoid any unnecessary loss of your game account assets. Please complete the identity verification, after you finish the verification, we will process your redemption as soon as possible. If your current device can not work, please kindly change another device and try again. Please note we don't accept screenshots. Please upload a live photo of the document.
If you have issues with the verification, please feel free to contact us.
Have a wonderful day.
```

---

## 十、KYC链接

目前仅 **Sumsub** 支持给玩家发送链接，让玩家主动做 KYC-ID、KYC-POA 或验证人脸。

如有需要，需填工单来申请。

### Face Authentication（人脸验证）
- 只针对已经做过 Sumsub KYC-ID 或 KYC-POA 的玩家
- 可只扫脸验证当前人脸和之前做验证的人脸是否为同一人
- 玩家需要更换 Account email、redemption email、ACH 时，需提交工单让二线提供 Face Authentication link 完成验证后，才可帮助换绑或解绑

---

## 十一、删除KYC个人信息

玩家要求删除个人KYC验证信息时：

1. 告知玩家账号已在删除流程中，系统流程走完后会彻底删除，账号信息都会被删除
2. KYC信息我们不会删除，原因：

```
We understand your concerns about data privacy and would like to assure you that we handle your information with the utmost care and in compliance with applicable laws and regulations. Due to Anti-Money Laundering (AML) requirements, we are obligated to retain your KYC information for a period of five years from the date of collection. Unfortunately, this means we are unable to fulfill your request for immediate deletion.
However, we want to reassure you that your KYC information is securely stored and will not be used for any other purposes beyond legal and compliance obligations. Specifically:
Your information will not be transferred, copied, or sold to any third parties.
It will not be used for marketing or any other non-compliance purposes.
Once the mandatory five-year retention period has expired, we will ensure that your KYC information is securely deleted in accordance with applicable laws.
We appreciate your understanding and cooperation in this matter. If you have any further questions or concerns, please don't hesitate to contact us.
```

---

## 十二、无法完成KYC

需确认是无法做KYC（技术性问题）还是无法通过KYC。

### 12.1 无法做KYC（技术问题）
- 让玩家提供操作录屏，提交工单给二线
- 无法提供录屏，提供截图

### 12.2 无法通过KYC
- 让玩家提供验证截图
- 如果提供截图后24h仍处于该界面，提交工单
- 查看KYC模块状态，如果是4或没有显示，提交工单给二线
- 结合图中提示给玩家指引，多次指引后仍无法成功，提交工单

---

## 十三、KYC不通过 / 非法州玩家

如果项目组反馈玩家KYC不通过，或玩家经核验确实在非法州：

1. **Freeze 玩家账号**
2. **填写邮件退款表**退玩家全部充值金额（退款金额：历史充值全额退款）
3. **填写Ban list**
4. **按话术劝退玩家**
5. **确认无其他问题且退款完成后**，更新工单让二线彻底删号

**话术：**
```
Dear Player

Thank you for your patience throughout the verification process.
After carefully reviewing your submission, we regret to inform you that your KYC verification could not be approved at this time. However, we want to assure you that we will process a full refund of your purchase amount back to your original payment method within a few business days.

We truly appreciate your understanding and cooperation as we work to maintain a secure and compliant platform for all players. If you have any questions about the refund, our support team is always here to help.

Thank you for being part of our community.

Have a lovely day.
```

---

## 十四、处理KYC客诉工单注意事项

1. **工单Title**：凡是跟KYC验证相关的，一定要写全'KYC'描述
2. **问题详情**：描述KYC相关问题尽量详细，如有KYC截图请在问题详情里贴上截图
3. **多账号问题**：
   - 二线会告知相关多账号，如果是数字ID会回复数字ID，非纯数字ID会对应回复非纯数字ID
   - 玩家做出删号保留选择后，将选择删号的账号状态改为 **Banned** + 填写 **Ban list**
   - 做完封号动作后，更新工单告知二线保留账号和删号详情，**一定要写明ID**

**以上操作纳入质检范围，请务必遵守。**

**多账号话术：**
```
Dear Player,
Thank you for your patience.
We have identified that you have XX accounts associated with the email addresses:

Current account AAAAAAAA: xxx@xxx.com
Other account 1 BBBBBBBB: xxx@xxx.com
Other account 2 CCCCCCCC: xxx@xxx.com
...........

Please kindly note that our policy only allows each player to maintain one unique account, creating multiple accounts is not permitted.
To resolve this issue,please choose the account you wish to keep, and we will deactivate the other.
Kindly refrain from creating any new accounts, otherwise your new account may be automatically banned by the system.
Looking forward to your response.
Have a great day.
```

---

*最后更新：2025-07-11 (SSN验证新增)*