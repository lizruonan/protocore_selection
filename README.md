# 芯核的强化与筛选
*参考网络攻略的粗暴版芯核筛选方式。*

## 配套选择
  
🦈 **深海日卡套：** 首选芯核副词条【攻击+攻击加成】

🧜 **海神日卡套：** 首选芯核副词条【生命+生命加成】

思念天赋加成很小，可忽略不计。

## 加成折算
  - 芯核攻击加成% = 芯核副词条攻击 / 思念基础攻击 * 100% + 芯核副词条攻击加成
  - 芯核生命加成% = 芯核副词条生命 / 思念基础生命 * 100% + 芯核副词条生命加成

## 强化筛选
副词条强化节点为（+3， +6， +9， +12， +15） ，每强化3个节点会有随机增加或强化一个副词条。副词条达到4种后则不再增加属性。

芯核强化到12级时如果折算加成 $\geq$ 25% 可继续强化至15级。如果加成在 20%~25% 则不用继续强化，作为过渡芯核使用。如果 <20% 可分解。

## 面板计算
假设A为某属性，A可以是生命或攻击的任意一种。

- 芯核A值 = 思念基础A值 * 芯核副词条A加成% + 副词条A值 + 主词条A值

以某张卡的真实数值为例：

  卡面攻击 = 1012 + 692，其中1012是思念基础攻击，692是总芯核攻击。
  
  那么692是怎么来的？
  
  左芯核主攻击 = 180，副攻击 = 60， 攻击加成 = 21.3% $\implies$ 左芯核攻击值=  1012 * 21.3% + 180 + 60 ~= 456
  
  右芯核副攻击 = 113， 攻击加成 = 12.2% $\implies$ 右芯核攻击值 = 1012 * 12.2% + 113 ~= 236

  $\implies$ 总芯核攻击 = 左芯核攻击值 + 右芯核攻击值 = 456 + 236 = 692
