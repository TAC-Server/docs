# 附魔
> 本页汇总 NeoEnchant+ 插件内的自定义附魔及其效果概述。
> 由gpt-5翻译，如有错误请谅解

## 中英对照表
| 英文名称 (Enchantment ID)         | 中文名称 (Chinese Name) | 英文描述 (English Description)                                  | 中文描述 (Chinese Description)                                  |
| :-------------------------------- | :---------------------- | :-------------------------------------------------------------- | :-------------------------------------------------------------- |
| `fury`      | 狂怒                    | Lowers armor, increases penetration and damage.                 | 降低护甲，提高穿透和伤害。                                      |
| `lifeplus`    | 生命+                   | Gain extra health.                                              | 获得额外生命值。                                                |
| `venom protection` | 毒素防护                | Protection from negative effects.                               | 防护负面效果。                                                  |
| `timber`      | 伐木工                  | Chops down an entire tree at once.                              | 一次性砍倒整棵树。                                              |
| `agility`     | 敏捷                    | Increases movement speed.                                       | 提高移动速度。                                                  |
| `lava walker`   | 熔岩行者                | Can walk on lava.                                               | 可以在熔岩上行走。                                              |
| `step assist`   | 步行辅助                | Easier to climb blocks.                                         | 更容易爬上方块。                                                |
| `accuracy shot` | 精准射击                | Arrows ignore gravity and fly straight.                         | 箭矢无视重力直线飞行。                                          |
| `breezing arrow`| 微风之箭                | Knocks back targets or creates an effect on the ground.         | 击退目标或在地面产生效果。                                      |
| `echo shot`     | 回声射击                | Allows every arrow to carry an echo from ancient times.         | 让你的每一发箭都带有来自远古的回声。                            |
| `eternal frost` | 永恒霜冻                | Freezes blocks and slows targets.                               | 冻结方块并减缓目标。                                            |
| `explosive arrow`| 爆炸之箭                | Arrows explode on impact.                                       | 箭矢击中时产生爆炸。                                            |
| `rebound`     | 反弹                    | Arrows bounce off walls.                                        | 箭矢会在墙壁上反弹。                                            |
| `storm arrow`   | 风暴之箭                | Summons lightning on impact.                                    | 击中时召唤闪电。                                                |
| `builder arm`   | 建筑之臂                | Extends the range for placing and breaking blocks.              | 扩大放置和破坏方块的范围。                                      |
| `curse of breaking`| 脆弱诅咒                | Increases the rate of tool durability consumption.              | 增加工具的耐久度消耗速率。                                      |
| `curse of enchant`| 附魔诅咒                | Deprives the right to enchant.                                  | 剥夺附魔权利。                                                  |
| `armored`     | 装甲强化                | Reduces elytra damage.                                          | 降低鞘翅伤害。                                                  |
| `auto feed`     | 自动进食                | Automatically eats every 3 minutes.                             | 每3分钟自动进食。                                               |
| `bright vision` | 夜视                    | Grants night vision.                                            | 获得夜视能力。                                                  |
| `voidless`    | 虚空免疫                | Floats briefly when falling into the void.                      | 掉入虚空时短暂漂浮。                                            |
| `scyther`     | 开垦者                  | Cultivates a larger area at once (left-click).                  | 一次性开垦更大的区域（左键点击）。                              |
| `dwarfed`     | 矮人化                  | Reduces size and speed, increases step assist.                  | 减小体型和速度，增加步行辅助。                                  |
| `fast swim`     | 快速游泳                | Gains the effect of Dolphin's Grace.                            | 获得海豚的恩惠效果。                                            |
| `leaping`     | 跳跃                    | Increases jumping ability.                                      | 提高跳跃能力。                                                  |
| `oversize`    | 巨人化                  | Increases body size, reduces damage and attack range.           | 增加体型，降低伤害和攻击范围。                                  |
| `striker`     | 雷击                    | Summons lightning during a thunderstorm, grants immunity.       | 在暴风雨中召唤闪电，获得免疫。                                  |
| `teluric wave`  | 地震波                  | Creates an earthquake wave when sneaking and hitting the ground.| 潜行并击地时产生地震波。                                        |
| `wind propulsion`| 风力推进                | Creates an explosion on landing, pushing you into the air.      | 落地时产生爆炸，将你推向空中。                                  |
| `bedrock breaker`| 基岩破坏者              | Can break bedrock, consuming 150 durability per block.          | 可以破坏基岩，每个方块消耗150耐久。                             |
| `spawner touch` | 刷怪笼之触              | Allows obtaining monster spawners.                              | 允许获取怪物刷怪笼。                                            |
| `vein miner`    | 连锁采集                | Mines all connected ores.                                       | 挖掘所有相连的矿石。                                            |
| `attack speed`  | 攻击速度                | Increases attack speed.                                         | 提高攻击速度。                                                  |
| `last hope`     | 最后希望                | Sacrifices items for infinite damage.                           | 牺牲物品获得无限伤害。                                          |
| `fear`        | 恐惧                    | Delays Creeper explosions.                                      | 延迟苦力怕爆炸。                                                |
| `life steal`    | 生命汲取                | Steals health from targets.                                     | 从目标吸取生命值。                                              |
| `poison aspect` | 毒素                    | Poisons targets on hit.                                         | 击中时使目标中毒。                                              |
| `pull`        | 捕捉                    | Chance to get monster eggs on kill (1%).                        | 击杀时有机会获得怪物蛋（1%）。                                  |
| `reach`       | 延伸                    | Extends attack range.                                           | 扩大攻击范围。                                                  |
| `tears of asflors`| 阿斯弗洛斯之泪          | Converts experience into damage.                                | 将经验值转化为伤害。                                            |
| `xp boost`    | 经验提升                | Increases experience gained from killing mobs.                  | 增加击杀怪物获得的经验值。                                      |
| `auto smelt`    | 自动冶炼                | Automatically smelts mined items.                               | 自动冶炼挖掘的物品。                                            |
| `miningplus`    | 采矿+                   | Mines in a 3x3 area.                                            | 在3x3范围内挖掘。                                               |
| `gungnir breath`| 冈格尼尔之息            | Freezes water and slows targets.                                | 冻结水并减缓目标。                                              |
| `ethereal leap` | 空灵跃动                | Increases mount jump height and reduces fall damage.            | 增加坐骑的跳跃高度，并减少摔落伤害。                            |
| `velocity`    | 速度                    | Increases mount movement speed.                                 | 增加坐骑的移动速度。                                            |
| `steel fang`    | 钢牙                    | Makes your mount deal more damage on attack.                    | 使你的坐骑在攻击时造成更多伤害。                                |
| `cavalier egis` | 骑士守护                | Reduces damage taken while riding a mount.                      | 骑乘坐骑时受到的伤害降低。                                      |
| `midas touch`   | 点金术                  | Transforms blocks into gold or gold ore, consuming 150 durability per block.| 将方块转化为金或金矿石，每个方块消耗150耐久。                 |
| `kinetic protection` | 动能保护                | Protects you from elytra collision damage.                      | 保护你免受鞘翅碰撞伤害。                                        |
| `harvest`     | 播种者                  | Sows a larger area at once (holding tool in off-hand).          | 一次性播种更大的区域（副手拿着工具）。                          |
| `dimensional strike` | 维度打击                | Deals more damage in other dimensions.                          | 在其他维度造成更多伤害。                                        |
| `critical hit`  | 暴击                    | Has a chance to deal true damage.                               | 有几率造成真实伤害。                                            |
| `runic despair` | 符文绝望                | Deals more damage in the Rune Dimension.                        | 在符文维度造成更多伤害。                                        |
| `death touch`   | 死亡之触                | Gives enemies the darkness effect.                              | 给予敌人黑暗效果。                                              |
| `happy boost`   | 快乐增幅                | Increases the flight speed of your Happy Ghast.                 | 增加你的快乐恶魂的飞行速度。                                    |
| `curse of clumsiness` | 卷刃诅咒                | Reduces the damage value of items.                              | 降低物品的伤害值。                                              |

## 附魔列表与效果

* * *

### 弓类

_这些附魔用于弓与弩，可为射出的箭矢赋予特殊效果。_

*   **Breezing Arrow**：（弓）命中时在落点产生一阵气流，将附近实体推开；若命中实体，会将其短暂吹离地面。
*   **Explosive Arrow**：（弓）箭矢命中后产生爆炸，伤害周围实体并破坏方块，射手不会受到爆炸伤害。
*   **Accuracy Shot**：（弓）箭矢直线飞向目标并无视重力，长时间未命中则会消失。
*   **Echo Shot**：（弓）借用监守者的力量，命中后引发音波爆炸，只伤害实体且不破坏方块，射手免疫该爆炸。
*   **Storm Arrow**：（弓）命中方块或实体时有概率在落点召唤闪电，造成伤害并点燃方块。
*   **Eternal Frost**：（弓）命中后将地面冻结成冰并减速目标，同时生成冰刺。
*   **Rebound**：（弓）箭矢可以在墙壁间反弹，每次弹跳都会触发附魔效果。

* * *

### 剑类

_这些附魔适用于剑，使近战攻击获得额外效果。_

*   **Fear**：（剑）攻击苦力怕时延长其爆炸引信时间。
*   **Life Steal**：（剑）攻击命中时为持有者回复少量生命值。
*   **Pull**：（剑）击杀实体后有概率获得对应的刷怪蛋。
*   **Attack Speed**：（剑）提升玩家的攻击速度。
*   **Reach**：（剑）延长玩家的攻击距离。
*   **Tears of Asflors**：（剑）将玩家的经验值转化为额外伤害。
*   **Last Hope**：（剑）消耗整件武器，对目标造成无限伤害。
*   **Poison Aspect**：（剑）命中玩家时施加中毒效果，命中非玩家实体时施加凋零效果。
*   **Critical**：（剑）攻击时有概率无视部分护甲减伤。
*   **Runic Despair**：（剑）在符文维度中造成额外伤害。
*   **Death Touch**：（剑）有概率瞬间击杀目标实体。
*   **Dimensional Hit**：（剑）在主世界以外的维度造成额外伤害。

* * *

### 三叉戟与重锤

_这些附魔适用于三叉戟与重锤，提供独特的战斗能力。_

*   **Breath of Gungnir**：（三叉戟）命中后将地面冻结成冰并减速目标，同时生成冰刺。
*   **Striker**：（重锤）重锤猛击实体时，有概率在落点生成闪电。
*   **Wind Propulsion**：（重锤）在地面上用重锤砸地可将玩家抛向空中。
*   **Telluric Wave**：（重锤）潜行攻击时掀起震波，将目标击飞。

* * *

### 镐

_这些附魔专用于镐子。_

*   **Vein Miner**：（镐）破坏矿石方块时，会同时破坏与之相连的同类矿石。
*   **Bedrock Breaker**：（镐）允许玩家破坏基岩，但需要持有带有该附魔的镐。
*   **Spawner Touch**：（镐）可以挖掘刷怪笼并将其收集，适用于试炼刷怪笼与普通刷怪笼。

* * *

### 工具

_这些附魔可用于多种工具。_

*   **Timber**：（斧）破坏单个木头方块时，会一并砍倒相连的所有木头。
*   **Scyther**：（锄）左键草方块可按附魔等级在一定范围内转换为耕地。
*   **Harvest**：（锄）提升农作物收获效率，使耕作更加顺畅。
*   **Auto Smelt**：（镐）破坏方块后直接获得熔炼后的掉落物。
*   **Mining+**：（镐）按照玩家朝向一次性开采 3×3 区域。

* * *

### 盔甲

_这些附魔适用于所有盔甲部件（头盔、胸甲、护腿、靴子）。_

*   **Life+**：（头盔）提升玩家最大生命值，获得更多心。
*   **Venom Protection**：（盔甲）抵御中毒效果，高等级时还能免疫凋零。
*   **Fury**：（盔甲）降低护甲值但提升攻击力，并附加护甲穿透。

* * *

### 头盔

_这些附魔仅适用于头盔。_

*   **Voidless**：（头盔）令玩家免疫虚空伤害，坠入虚空时会获得短暂漂浮效果。
*   **Bright Vision**：（头盔）赋予夜视效果，使玩家在黑暗中视线清晰。
*   **Auto Feed**：（头盔）每分钟自动补充少量饱和度，但不足以完全依赖该附魔。

* * *

### 胸甲与鞘翅

_这些附魔主要用于胸甲，部分适用于鞘翅。_

*   **Builder Arm**：（胸甲）延长放置与破坏方块的距离。
*   **Magnet**：（胸甲）自动吸附附近掉落物。
*   **Armored**：（鞘翅）为鞘翅提供额外护甲值，降低所受伤害。
*   **Kinetic Protection**：（鞘翅）减少飞行时撞击墙壁或障碍物造成的伤害。

* * *

### 护腿

_这些附魔仅适用于护腿。_

*   **Dwarfed**：（护腿）缩小实体体型。
*   **Fast Swim**：（护腿）提升玩家的游泳速度。
*   **Leaping**：（护腿）提高玩家的跳跃高度。
*   **Oversize**：（护腿）增大实体体型。

* * *

### 靴子

_这些附魔仅适用于靴子。_

*   **Lava Walker**：（靴子）在熔岩上行走时脚下生成岩浆块，并使玩家免疫熔岩与岩浆块伤害。
*   **Step Assist**：（靴子）提高玩家的踏步高度，让攀越方块更加轻松。
*   **Agility**：（靴子）提升玩家的移动速度。

* * *

### 坐骑

_这些附魔适用于马匹护甲及其他坐骑装备。_

*   **Rider Egis**：（坐骑）为坐骑提供减伤，降低其受到的大多数伤害。
*   **Ethereal Leap**：（坐骑）提高坐骑的跳跃高度并减少坠落伤害。
*   **Velocity**：（坐骑）显著提升坐骑的移动速度。
*   **Steel Fang**：（犬类）增强被驯服狼的攻击力。

* * *

### 其他

_这些附魔具有特殊效果或可用于多种物品。_

*   **XP Boost**：（通用）提升玩家击杀实体时获得的经验值。
*   **Curse of Breaking**：（通用）与 **Unbreaking** 效果相反，会加速物品耐久损耗。
*   **Curse of Enchant**：（通用）使物品无法再进行附魔。
*   **Midas Touch**：（通用）攻击方块时将其转化为金矿石或金块，但会大量消耗耐久。
