# ZhiZe Rebalance Minecraft Datapack and Resourcepack

## Overview

* 更合理的小麦：成熟后的小麦方块不再掉落小麦种子。小麦种子可以通过小麦无序合成得到。打草掉落小麦种子的机制保持原样。
* 更合理的动物掉落：（尚未完成）

## Blocks

* 小麦
  * 移除了小麦不成熟时必然的种子掉落。同时剩余掉落列表中的小麦种子全部被替换为小麦（物品）。
  * 增加了小麦到小麦种子的无序合成。

## Items

* 兔子皮更改显示名称为“轻皮革”。

## Entites Loot

* 猪
  * 掉落骨头，掉落率与骷髅一致。
  * 掉落皮革，但平均产出小于牛。
* 牛
  * 掉落骨头，掉落率与骷髅一致。
* 哞菇
  * 掉落骨头，掉落率与骷髅一致。
* 羊
  * 掉落骨头，掉落率与骷髅一致。
  * 掉落皮革，但平均产出小于牛。
* 马
  * 掉落骨头，掉落率与骷髅一致。

## 设计思路说明

### 动物掉落

* 将动物分类两类：猪牛羊等属于大型动物，猫鸡等属于小型动物。
* 大型动物都有比较全面的皮、毛、骨、肉的掉落。但根据常识中皮革的质量将皮的产出分为不同等级。常识中没有毛的动物不掉落毛。
* 小型动物不一定有非常全的掉落，例如鸡和鹦鹉可以没有骨头掉落。

## ToDo

* [ ] 哞菇根据种类死亡时掉落同种类蘑菇，平均收益小于修剪。

* [ ] 完成驴、骡子、羊驼等的修改。

* [ ] 让蝙蝠更有用。

* [x] 把废物小麦种子改得有用一点，而且小麦和小麦种子分开掉落太蠢了。

* [ ] 移除原有的皮革和轻皮革的转化，利用其他工作台完成转化。考虑皮革经过切石台产生轻皮革。轻皮革取代皮革用于制作书籍。

* [ ] 让燧石更有用一点，可以合成加强版的石质工具（目前原版的配方输出不支持）

* [ ] 移除所有台阶和半砖的合成台配方，所有此类方块都通过切石台处理

  

