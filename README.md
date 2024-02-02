# BathingCardinal Pod Loot filter
Hello Pod Fans! 

Welcome to **BathingCardinal's POD Loot Filter!** 

If you find any bugs when using my filter,please open a issue and let me know 

大家好，欢迎使用BathingCardinal的PoD过滤器

发现任何BUG请填写Issues，或者联系我的QQ:33752753

## Features:
* clear almost useless trash
* add notify for item drops or vendors selling
* add mini map icons for high value items
* add name beautification to various items to make them easier to identify/distinguish
* add useful item descriptions for maps/weapons/armors/uber keys/etc
* new filter level switch, you can freely choose your favorite filtering level

* 清理掉所有无用的杂物
* 添加物品掉落/售卖NOTIFY提醒功能
* 添加高价值物品小地图图标
* 为各种物品增加名称美化，使其更容易辨认/区分
* 为各种物品添加补充描述（地图/装备/KEYs等等）
* 新增过滤等级切换，可随意挑选喜欢的过滤级别

## filter level:
| level | name | description |
| --- | --- | --- |
| 1 | L1: | Suitable for early ladder or regular use, only hide useless trash
| 2 | L2: | Used for red maps,hide some cheap WR base,hide rune(1/2/3/5),hide low level magic rings/amulets/BAR heads/AMA javelins,hide rare gloves/boots/belts/BAR & DRU heads
| 3 | L2+ | Show potions and DIY items on the basis of L2
| 4 | L3: | Used for end games,hide mor WR base,hide more runes(4/6/7/9/10/13),hide flawless gems(topaz/sapphire/emerald/diamond),hide more rare items left only Circlets/rings/amulets/arrows/ASN claws/AMA javs,hide low value set items
| 5 | L3+ | Show potions and DIY items on the basis of L3
| 6 | L4: | Caution！hide the vast majority of RW base，hide more runes(8/11/12),hide all rares,hide all flawless gems(except skull),hide unID small charms/jews,hide more set items,reduce the notification number of unique items
| 7 | L4+ | Show potions and DIY items on the basis of L4

| level | name | description |
| --- | --- | --- |
| 1 | L1: | 适合常规使用，仅屏蔽掉无用杂物
| 2 | L2: | 刷高级图用，屏蔽部分底材，屏蔽#1#2#3#5符文，屏蔽蓝色项链、戒指、BAR头、AMA标枪，屏蔽亮金手套、鞋子、腰带、职业头等
| 3 | L2+ | L2的基础上显示药水+DIY区
| 4 | L3: | 超级大后期用，屏蔽更多底材，额外屏蔽#4#6#7#9#10#13符文，屏蔽无瑕疵的黄、蓝、绿、钻，屏蔽所有亮金只剩下头环/戒指/项链/箭袋/爪/AMA标枪，屏蔽低价值套装
| 5 | L3+ | L3的基础上显示药水+DIY区
| 6 | L4: | 慎用！屏蔽绝大部分底材，额外屏蔽#8#11#12符文，屏蔽所有亮金，屏蔽无瑕疵紫、红宝石，屏蔽未鉴定SC/JEW（留GC），屏蔽中价值套装、减少暗金装备提醒数量
| 7 | L4+ | L4的基础上显示药水+DIY区

### Installation:
Download[**Bathing_Eng.filter**](https://github.com/vincent427/BathingCardinal_Pod_Lootfilter/blob/main/Bathing_Eng.filter)to*Diablo II\Path of Diablo\filters*，or right click on[**Raw**](https://raw.githubusercontent.com/vincent427/BathingCardinal_Pod_Lootfilter/main/Bathing_Eng.filter)select Save link as，then fill the link into the PoD launcher.

Start the game, open the in-game settings menu (default hotkey is H), select this filter from the drop-down menu, select the desired filter level, and then click the arrow button next to the filter file name to reload the filter

下载[**Bathing_Chi.filter**](https://github.com/vincent427/BathingCardinal_Pod_Lootfilter/blob/main/Bathing_Chi.filter)至*Diablo II\Path of Diablo\filters*，或者右键点击[**Raw**](https://raw.githubusercontent.com/vincent427/BathingCardinal_Pod_Lootfilter/main/Bathing_Chi.filter)复制链接地址，然后将复制的链接填入PoD登录器内

启动游戏，打开游戏内设置菜单（默认按键是H），下拉选择本过滤器，选择需要的过滤器等级，然后点击过滤器文件名旁边的箭头按钮即可

# Plans:
At present, the main focus is on adding filter functions for the new season, and in the future, I will consider adding an English version of **Bathing_Eng.filter**

现阶段主要是针对新赛季添加过滤器功能为主，以后会考虑添加英文版本的**Bathing_Eng.filter**

## Changelog:
### 2024/2/2
Fix some bugs

## Changelog:
### 2024/1/2
Add Engilsh version &
Fix some bugs

加入英文版本 + 
修复部分小错误

### 2023/12/29
Fix some issue of game crashes caused by Relics Map's code

修复地图代码报错引起游戏崩溃的问题

### 2023/05/25
Add fools mod to the weapon name 

添加武器愚人词缀提醒
### 2023/05/22
fix some bugs

修复天生带孔装备描述覆盖掉武器攻速描述，修复-60攻速bow的攻速被%WPNSPD%覆盖掉的问题。
### 2023/05/19
modify some item's filter level

调整部分装备的过滤等级
### 2023/05/18
modify some GC/SC naming rules

调整部分GC/SC名称提示规则
### 2023/05/17
add description for unique Jews like：Rainbow Facet[-5/+5] Fire (code temporarily not allowed, will be added description like live or die in the future)

新增暗金珠宝彩虹刻面的属性描述：【-5/+5】电 （代码暂时不允许，以后会加入死电/活电区分）
### 2023/05/16-2
add a description of monster's basic resistance and immunes on the relic map, where the * in front of the immunes indicates how many types of monsters are immune to this attribute. For example, "* * * cold 160" indicates that there are three types of monsters with cold immune,and the highest cold res is 160.

新增遗物地图怪物基础抗性及免疫情况描述，其中免疫属性前面的星号表示有多少种怪物免疫此属性，例如“＊＊＊冰160”表示有3种怪物带有冰系免疫
### 2023/05/16-1
Updated PTR version, no longer applicable to # 20 perlite

更新PTR版本，将不再适用#20珍珠岩赛季

