# Slots 机台规则知识库

---

## 一、通用规则

### 1.1 Bgaming 第三方机台流水
- 玩家可在机台内查看自己的流水记录，每一局的pattern、赢法、下注金额都写在 round link 里
- 目前仅限 gp sms webapk web 这类bundles能打开bgaming流水功能，**iOS无法打开**

### 1.2 Buying Feature
- 部分机台可花GC或SC去buyin free spin
- 系统卡住可能导致无法正常使用free spin，可提工单查询
- 查询free spin购买记录：在game flow里根据购买花费的时间和SC/GC数额查找Spin Bet

---

## 二、Tada Gaming 机台

### 2.1 Shoot & Win 机台（如 Dino Shooter）
- 类似于捕鱼游戏，**只有美国用户可进入**
- **加强炮玩法**：实际改变了bet。如Axe显示2，点击后炮弹变成斧头，实际bet = 原bet(0.5) + 加强炮(2)
- bet越大，加强炮金额也越大
- **流水统计**：不一定按每次bet金额统计
  - 点击一次 = 单次bet金额
  - 连续快速点击 = 多次消耗一次性通知业务服扣费，奖励也一起通知。消耗显示为bet金额的整数倍
- 如果流水没标明机台供应商，无法确认是否为Shoot & Win多次消耗扣费，且玩家认为不合理扣费，**提工单让二线辅助查询**
- 2025-06-03：Tada系列机台会写明玩家昵称，如果玩家没设置昵称，位置会显示加密ID(UID)或随机ID
- 需核对玩家名字和机台内名字/UID是否一致，避免玩家用他人截图或外网视频骗人

### 2.2 Lighting Fishooter（捕鱼游戏）
- Play金额越大，炮台会升级
- 提示：Accumulate energy through shooting, then use the Thunderbolt when full
- 需要在本机台累计使用SC射击，进程完成后才能使用Thunderbolt
- 如果玩家没有SC了但Thunderbolt可使用，也会显示该reminder

### 2.3 Money Coming 机台
- **spin金额固定**：1、5、10、50
- **首次进入默认bet为1**（之前是100，2025-03改成1）
- 不同spin金额解锁不同玩法，spin越大中奖时大奖越大
- 比较难中奖，一中就中大奖（没中奖时页面没有数字，可能让玩家以为游戏出问题）

### 2.4 Golden Joker 特殊模式
- 当第二列和第三列转满小丑，可进入特殊模式
- 必须用更高押注，**必须明确点击第一列（粉色光边框起来的部分）**才进行特殊模式下注
- 点击右下角spin按钮或盘面其他位置，**不会进行特殊模式下注**，只会进行一般模式下注（且特殊模式会消失）
- 特殊模式bet下注逻辑：3(原始押注) x 10(固定倍率) x 2(上方乘倍) = 60
- 收到玩家反馈钱不见了，查看流水发现bet突然升高，通常就是误触进入特殊模式

---

## 三、其他机台规则

### 3.1 3X Diamond
- 每一个下注会被分到9条line里
- 最后计算所有line的总奖励
- 1SC奖励没问题：0.9SC/9 × 20 + 0.9SC/9 × 5 = 2SC + 0.5SC

### 3.2 Beloved Beauty / Charming Pixcels
- 易错点：玩家觉得有三个bonus scatter就能中free spin
- 实际上bonus scatter也要**符合payline的排布**才算中

### 3.3 Gorgeous Goddess
- 满足symbol payline但机台不给pay的bug，已于2025-1-3修复
- 如果看到截图情况（J列），需要玩家自己选择一个苹果（界面上有pick one），选择后才会开启free spins
- 苹果下面有图标（4种图标随机），选中的图标会在free spins中增加出现频率，提高中奖率

### 3.4 Fire Mustang
- 玩家容易觉得free spin里机台上方金额就是中奖金额，但那个金额是计入奖池的，不是中的奖
- 得到X2或X4 feature后，野马前方显示的应得中奖金额**已经乘以倍数**，不是还要再乘
- **注意点**：
  1. 5个及5个+野马币触发free spin
  2. 野马币上显示的钱需要第5列有collect币才能领取（不局限于野马币数量）
  3. 如果前面有5个野马币，第5列还有collect币，则1、2都会触发
  4. bonus win pays：指玩家在free spins过程中赢钱的总和，出现bonus win pays说明触发了free spins且有结果

### 3.5 Fire Red 7 5 Lines
- 1 bet平均分给5条line
- 算中奖要 bet÷5 再去乘以中奖倍数 + 其他lines赢得的奖励

### 3.6 Royal Fortune
- 有蓝框、金币、皇冠金币、SC金币
- 金币落在蓝框上随机触发皇冠金币或SC金币
- 触发皇冠金币：玩家可pin jackpot奖池，必然获得奖池金币。不同bet解锁不同奖池
- 触发SC金币：SC数额随机，由2500、500、200、125、100、50这6个数中任一去乘以 line-bet
- line-bet = bet ÷ payline条数（该机台payline是50条）
- 如bet=0.1，line-bet=0.1/50=0.002，则SC金币可能是：2500×0.002=5、500×0.002=1...等
- 金币变成SC金币时，会随机再乘以2、3、5倍
- 3个钻石戴冠触发6次free spin，free spin中再中2个钻石戴冠额外加3次
- 截图中有'bonus win pays' = 玩家在free spin中获得的奖励

### 3.7 Enchanting Peacock
- 中奖后可选择 **CREDIT PRIZE** 或 **FREE GAME**
- CREDIT PRIZE：必然中奖，金额有范围（动态变化），有保底数值
- FREE GAME：即free spins，不一定中奖，可能中大奖，无保底
- **已知bug**：选择CREDIT PRIZE后按CREDIT PRIZE发奖，但界面显示跳转到FREE GAME界面（案例玩家：UFTAK5R5）

### 3.8 Atlantis
- 显示问题：原本六个宝箱触发奖励，下层图标是宝箱，但实际以上层图标为准
- 客诉tag：winner_406显示bug

### 3.9 HYPERNOVA MEGAWAYS
- 显示问题：原本六个粉球触发奖励，下层图标是粉球，但实际以上层图标为准
- 客诉tag：winner_415显示bug

---

*最后更新：2025-06-03, 2025-03*