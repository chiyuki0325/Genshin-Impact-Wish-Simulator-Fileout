﻿# Genshin-Impact-Wish-Simulator-Fileout

[![License](https://img.shields.io/badge/Licence-GPL-blue.svg)](https://github.com/Jirehlov/GenshinImpactWishSimulatorCLI/blob/master/LICENSE)

## Library
[libgiwscli](https://github.com/Jirehlov/libgiwscli)

## Other versions

CLI: [Genshin Impact Wish Simulator CLI](https://github.com/Jirehlov/Genshin-Impact-Wish-Simulator-CLI)

## English

This is a Wish Simulator that output results to a file for Genshin Impact players.

### Features:

Unlimited number of wishes in one go;\
Statistics;

### How to build:

```
g++ -s -o3 main.cpp lib/giwscli.cpp lib/random_gen.cpp -o giwsfo
```
Or Visual Studio, etc.

### How to use:

```
giwsfo <chosen_banner> <chosen_event> <wishes_number>
```
For exmaple, if you want to pull 100 wishes in Sparkling Steps/20201020-20201110 which is a Character Event Wish, type:
```
giwsfo 1 2 100
```
If no argument is provided, the program will quit.\
**!!!!!It's not recommended to pull too large wishes!!!!!**

No. of banners and events seen as follows:

I Character Event Wish\
1: Ballad in Goblets/20200928-20201018 (Venti, Barbara, Fischl, Xiangling)\
2: Sparkling Steps/20201020-20201110 (Klee, Xingqiu, Noelle, Sucrose)\
3: Farewell of Snezhnaya/20201111-20201201 (Tartaglia, Diona, Beidou, Ningguang)\
4: Gentry of Hermitage/20201201-20201222 (Zhongli, Xinyan, Razor, Chongyun)\
5: Secretum Secretorum/20201223-20210112 (Albedo, Fischl, Sucrose, Bennett)\
6: Adrift in the Harbor/20210112-20210202 (Ganyu, Xiangling, Xingqiu, Noelle)\
7: Invitation to Mundane Life/20210203-20210217 (Xiao, Diona, Beidou, Xinyan)\
8: Dance of Lanterns/20210217-20210302 (Keqing, Ningguang, Bennett, Barbara)\
9: Moment of Bloom/20210302-20210316 (Hu Tao, Xingqiu, Xiangling, Chongyun)\
10: Ballad in Goblets/20210317-20210406 (Venti, Sucrose, Razor, Noelle)\
11: Farewell of Snezhnaya/20210406-20210427 (Tartaglia, Rosaria, Barbara, Fischl)\
12: Gentry of Hermitage/20210428-20210518 (Zhongli, Yanfei, Noelle, Diona)\
13: Born of Ocean Swell/20210518-20210608 (Eula, Xinyan, Xingqiu, Beidou)\
14: Sparkling Steps/20210609-20210629 (Klee, Sucrose, Fischl, Barbara)\
15: Leaves in the Wind/20210629-20210720 (Kaedehara Kazuha, Rosaria, Bennett, Razor)\
16: The Heron's Court/20210721-20210810 (Kamisato Ayaka, Yanfei, Ningguang, Chongyun)\
17: Tapestry of Golden Flames/20210810-20210831 (Yoimiya, Sayu, Diona, Xinyan)\
18: Reign of Serenity/20210901-20210921 (Raiden Shogun, Kujo Sara, Xiangling, Sucrose)\
19: Drifting Luminescence/20210921-20211012 (Sangonomiya Kokomi, Rosaria, Beidou, Xingqiu)\
20: Farewell of Snezhnaya/20211013-20211102 (Tartaglia, Ningguang, Chongyun, Yanfei)\
21: Moment of Bloom/20211102-20211123 (Hu Tao, Thoma, Diona, Sayu)\
22: Secretum Secretorum/20211124-20211214 (Albedo, Rosaria, Noelle, Bennett)\
23: Oni's Royale/20211214-20220104 (Arataki Itto, Gorou, Xiangling, Barbara)\
24: The Transcendent One Returns/20220105-20220125 (Shenhe, Yun Jin, Ningguang, Chongyun)\
25: Gentry of Hermitage/20220125-20220215 (Zhongli, Yanfei, Xingqiu, Beidou)\
26: Everbloom Violet/20220216-20220308 (Yae Miko, Fischl, Diona, Thoma)\
27: Reign of Serenity/20220308-20220329 (Raiden Shogun, Bennett, Xinyan, Kujo Sara)\
28: Azure Excursion/20220330-20220419 (Kamisato Ayato, Yun Jin, Sucrose, Xiangling)

II Character Event Wish-2\
1: Born of Ocean Swell/20211124-20211214 (Eula, Rosaria, Noelle, Bennett)\
2: Invitation to Mundane Life/20220105-20220125 (Xiao, Yun Jin, Ningguang, Chongyun)\
3: Adrift in the Harbor/20220125-20220215 (Ganyu, Yanfei, Xingqiu, Beidou)\
4: Drifting Luminescence/20220308-20220329 (Sangonomiya Kokomi, Bennett, Xinyan, Kujo Sara)\
5: Ballad in Goblets/20220330-20220419 (Venti, Yun Jin, Sucrose, Xiangling)

III Weapon Event Wish\
1: Epitome Invocation/20200928-20201018 (Aquila Favonia, Amos' Bow, The Flute, The Bell, The Widsith, The Stringless, Favonius Lance)\
2: Epitome Invocation/20201020-20201109 (Lost Prayer to the Sacred Winds, Wolf's Gravestone, Sacrificial Sword, Sacrificial Bow, Sacrificial Greatsword, Sacrificial Fragments, Dragon's Bane)\
3: Epitome Invocation/20201111-20201201 (Memory of Dust, Skyward Harp, Rainslasher, Eye of Perception, Rust, Favonius Lance, The Flute)\
4: Epitome Invocation/20201201-20201222 (Vortex Vanquisher, The Unforged, Lion's Roar, The Bell, Favonius Codex, Favonius Warbow, Dragon's Bane)\
5: Epitome Invocation/20201223-20210112 (Summit Shaper, Skyward Atlas, Favonius Sword, Favonius Greatsword, Favonius Lance, Sacrificial Fragments, The Stringless)\
6: Epitome Invocation/20210112-20210202 (Skyward Pride, Amos' Bow, Sacrificial Sword, The Bell, Dragon's Bane, Eye of Perception, Favonius Warbow)\
7: Epitome Invocation/20210203-20210223 (Primordial Jade Cutter, Primordial Jade Winged-Spear, Rust, Eye of Perception, Favonius Lance, Sacrificial Greatsword, The Flute)\
8: Epitome Invocation/20210223-20210316 (Staff of Homa, Wolf's Gravestone, Lithic Blade, Lithic Spear, Sacrificial Bow, The Widsith, Lion's Roar)\
9: Epitome Invocation/20210317-20210406 (Elegy for the End, Skyward Blade, The Alley Flash, Wine and Song, Favonius Greatsword, Favonius Warbow, Dragon's Bane)\
10: Epitome Invocation/20210406-20210427 (Skyward Harp, Lost Prayer to the Sacred Winds, Alley Hunter, Favonius Sword, Sacrificial Greatsword, Favonius Codex, Favonius Lance)\
11: Epitome Invocation/20210428-20210518 (Summit Shaper, Memory of Dust, The Flute, Lithic Blade, Lithic Spear, Eye of Perception, Sacrificial Bow)\
12: Epitome Invocation/20210518-20210608 (Song of Broken Pines, Aquila Favonia, Sacrificial Sword, Rainslasher, Dragon's Bane, Sacrificial Fragments, Rust)\
13: Epitome Invocation/20210609-20210629 (Skyward Pride, Lost Prayer to the Sacred Winds, Mitternachts Waltz, Lion's Roar, The Bell, Favonius Lance, The Widsith)\
14: Epitome Invocation/20210629-20210720 (Freedom-Sworn, Skyward Atlas, The Alley Flash, Wine and Song, Alley Hunter, Favonius Greatsword, Dragon's Bane)\
15: Epitome Invocation/20210721-20210810 (Mistsplitter Reforged, Skyward Spine, The Stringless, Favonius Sword, Favonius Lance, Favonius Codex, Sacrificial Greatsword)\
16: Epitome Invocation/20210810-20210831 (Thundering Pulse, Skyward Blade, Favonius Warbow, Sacrificial Sword, Dragon's Bane, Rainslasher, Sacrificial Fragments)\
17: Epitome Invocation/20210901-20210921 (Engulfing Lightning, The Unforged, Sacrificial Bow, Lion's Roar, The Widsith, Favonius Lance, The Bell)\
18: Epitome Invocation/20210921-20211012 (Everlasting Moonglow, Primordial Jade Cutter, The Flute, Favonius Greatsword, Dragon's Bane, Favonius Codex, The Stringless)\
19: Epitome Invocation/20211013-20211102 (Polar Star, Memory of Dust, Akuoumaru, Favonius Sword, Favonius Lance, Eye of Perception, Rust)\
20: Epitome Invocation/20211102-20211123 (Staff of Homa, Elegy for the End, Wavebreaker's Fin, Mouun's Moon, Sacrificial Sword, Rainslasher, The Widsith)\
21: Epitome Invocation/20211124-20211214 (Freedom Sworn, Song of Broken Pines, Alley Hunter, Lion's Roar, Dragon's Bane, Wine and Song, Sacrificial Greatsword)\
22: Epitome Invocation/20211214-20210104 (Redhorn Stonethresher, Skyward Harp, The Alley Flash, Mitternachts Waltz, Favonius Lance, Sacrificial Fragments, The Bell)\
23: Epitome Invocation/20220105-20220125 (Calamity Queller, Primordial Jade Winged-Spear, Lithic Spear, The Flute, Favonius Warbow, The Widsith, Favonius Greatsword)\
24: Epitome Invocation/20220125-20220215 (Vortex Vanquisher, Amos' Bow, Lithic Blade, Favonius Sword, Dragon's Bane, Favonius Codex, Sacrificial Bow)\
25: Epitome Invocation/20220216-20220308 (Kagura's Verity, Primordial Jade Cutter, Wavebreaker's Fin, Stringless, Sacrificial Sword, Eye of Perception, Rainslasher)\
26: Epitome Invocation/20220308-20220329 (Engulfing Lightning, Everlasting Moonglow, Akuoumaru, Mouun's Moon, Dragon's Bane, Favonius Lance, Sacrificial Fragments)\
27: Epitome Invocation/20220330-20220419 (Haran Tsukishiro Futsu, Elegy of the End, Rust, The Flute, The Widsith, Dragon's Bane, Sacrificial Greatsword)

IV Permanent Wish\
1: Wanderlust Invocation/20200928-20201222 (Released)\
2: Wanderlust Invocation/20201223-20210427 (Adds Diona and Xinyan)\
3: Wanderlust Invocation/20210428-20210608 (Adds Rosaria)\
4: Wanderlust Invocation/20210609-20210901 (Adds Yanfei)\
5: Wanderlust Invocation/20210901-20211012 (Adds Sayu)\
6: Wanderlust Invocation/20211013-20211123 (Adds Kujo Sara)\
7: Wanderlust Invocation/20211124-20220104 (Adds Thoma)\
8: Wanderlust Invocation/20220105-20220215 (Adds Gorou)\
9: Wanderlust Invocation/20220216- (Adds Yun Jin)

V Novice Wish\
1: Beginners' wish


### About Hidden Possibilities

This simulator includes no hidden possibilities.


## 中文

这是文件输出的无窗口的原神祈愿模拟器。

### 主要功能：

任意数量抽卡、简略统计信息反馈等

### 如何编译:

```
g++ -s -o3 main.cpp lib/giwscli.cpp lib/random_gen.cpp -o giwsfo
```
或者Visual Studio等其他方法。

### 如何使用:

```
giwsfo <卡池类型编号> <活动类型编号> <祈愿数量>
```
比如，你想在 角色活动祈愿 中的 闪焰的驻足/20201020-20201110 中抽取100次，可以键入:
```
giwsfo 1 2 100
```
如果没有arguments，模拟器将退出。\
**!!!!!不建议一次性抽取太多次!!!!!**

卡池类型编号与活动类型编号如下:

一、角色活动祈愿\
1: 杯装之诗/20200928-20201018 (温迪, 芭芭拉, 菲谢尔, 香菱)\
2: 闪焰的驻足/20201020-20201110 (可莉, 行秋, 诺艾尔, 砂糖)\
3: 暂别冬都/20201111-20201201 (达达利亚, 迪奥娜, 北斗, 凝光)\
4: 陵薮市朝/20201201-20201222 (钟离, 辛焱, 雷泽, 重云)\
5: 深秘之息/20201223-20210112 (阿贝多, 菲谢尔, 砂糖, 班尼特)\
6: 浮生孰来/20210112-20210202 (甘雨, 香菱, 行秋, 诺艾尔)\
7: 烟火之邀/20210203-20210217 (魈, 迪奥娜, 北斗, 辛焱)\
8: 鱼龙灯昼/20210217-20210302 (刻晴, 凝光, 班尼特, 芭芭拉)\
9: 赤团开时/20210302-20210316 (胡桃, 行秋, 香菱, 重云)\
10: 杯装之诗/20210317-20210406 (温迪, 砂糖, 雷泽, 诺艾尔)\
11: 暂别冬都/20210406-20210427 (达达利亚, 罗莎莉亚, 芭芭拉, 菲谢尔)\
12: 陵薮市朝/20210428-20210518 (钟离, 烟绯, 诺艾尔, 迪奥娜)\
13: 浪涌之瞬/20210518-20210608 (优菈, 辛焱, 行秋, 北斗)\
14: 闪焰的驻足/20210608-20210629 (可莉, 砂糖, 菲谢尔, 芭芭拉)\
15: 叶落风随/20210629-20210720 (枫原万叶, 罗莎莉亚, 班尼特, 雷泽)\
16: 白鹭之庭/20210721-20210810 (神里绫华, 烟绯, 凝光, 重云)\
17: 焰色天河/20210810-20210831 (宵宫, 早柚, 迪奥娜, 辛焱)\
18: 影寂天下人/20210901-20210921 (雷电将军, 九条裟罗, 香菱, 砂糖)\
19: 浮岳虹珠/20210921-20211012 (珊瑚宫心海, 罗莎莉亚, 北斗, 行秋)\
20: 暂别冬都/20211013-20211102 (达达利亚, 凝光, 重云, 烟绯)\
21: 赤团开时/20211102-20211123 (胡桃, 托马, 迪奥娜, 早柚)\
22: 深秘之息/20211124-20211214 (阿贝多, 罗莎莉亚, 诺艾尔, 班尼特)\
23: 鬼门斗宴/20211214-20220104 (荒泷一斗, 五郎, 香菱, 芭芭拉)\
24: 出尘入世/20220105-20220125 (申鹤, 云堇, 凝光, 重云)\
25: 陵薮市朝/20220125-20220215 (钟离, 烟绯, 行秋, 北斗)\
26: 华紫樱绯/20220216-20220308 (八重神子, 菲谢尔, 迪奥娜, 托马)\
27: 影寂天下人/20220308-20220329 (雷电将军, 班尼特, 辛焱, 九条裟罗)\
28: 苍流踏花/20220330-20220419 (神里绫人, 云堇, 砂糖, 香菱)

二、角色活动祈愿-2\
1: 浪涌之瞬/20211124-20211214 (优菈, 罗莎莉亚, 诺艾尔, 班尼特)\
2: 烟火之邀/20220105-20220125 (魈, 云堇, 凝光, 重云)\
3: 浮生孰来/20220125-20220215 (甘雨, 烟绯, 行秋, 北斗)\
4: 浮岳虹珠/20220308-20220329 (珊瑚宫心海, 班尼特, 辛焱, 九条裟罗)\
5: 杯装之诗/20220330-20220419 (温迪, 云堇, 砂糖, 香菱)

三、武器活动祈愿\
1: 神铸赋形/20200928-20201018 (风鹰剑, 阿莫斯之弓, 笛剑, 钟剑, 流浪乐章, 绝弦, 西风长枪)\
2: 神铸赋形/20201020-20201109 (四风原典, 狼的末路, 祭礼剑, 祭礼弓, 祭礼大剑, 祭礼残章, 匣里灭辰)\
3: 神铸赋形/20201111-20201201 (尘世之锁, 天空之翼, 雨裁, 昭心, 弓藏, 西风长枪, 笛剑)\
4: 神铸赋形/20201201-20201222 (贯虹之槊, 无工之剑, 匣里龙吟, 钟剑, 西风秘典, 西风猎弓, 匣里灭辰)\
5: 神铸赋形/20201223-20210112 (斫峰之刃, 天空之卷, 西风剑, 西风大剑, 西风长枪, 祭礼残章, 绝弦)\
6: 神铸赋形/20210112-20210202 (天空之傲, 阿莫斯之弓, 祭礼剑, 钟剑, 匣里灭辰, 昭心, 西风猎弓)\
7: 神铸赋形/20210203-20210223 (磐岩结绿, 和璞鸢, 弓藏, 昭心, 西风长枪, 祭礼大剑, 笛剑)\
8: 神铸赋形/20210223-20210316 (护摩之杖, 狼的末路, 千岩古剑, 千岩长枪, 祭礼弓, 流浪乐章, 匣里龙吟)\
9: 神铸赋形/20210317-20210406 (终末嗟叹之诗, 天空之刃, 暗巷闪光, 暗巷的酒与诗, 西风大剑, 西风猎弓, 匣里灭辰)\
10: 神铸赋形/20210406-20210427 (天空之翼, 四风原典, 暗巷猎手, 西风剑, 祭礼大剑, 西风秘典, 西风长枪)\
11: 神铸赋形/20210428-20210518 (斫峰之刃, 尘世之锁, 笛剑, 千岩古剑, 千岩长枪, 昭心, 祭礼弓)\
12: 神铸赋形/20210518-20210608 (松籁响起之时, 风鹰剑, 祭礼剑, 雨裁, 匣里灭辰, 祭礼残章, 弓藏)\
13: 神铸赋形/20210609-20210629 (天空之傲, 四风原典, 幽夜华尔兹, 匣里龙吟, 钟剑, 西风长枪, 流浪乐章)\
14: 神铸赋形/20210629-20210720 (苍古自由之誓, 天空之卷, 暗巷闪光, 暗巷的酒与诗, 暗巷猎手, 西风大剑, 匣里灭辰)\
15: 神铸赋形/20210721-20210810 (雾切之回光, 天空之脊, 绝弦, 西风剑, 西风长枪, 西风秘典, 祭礼大剑)\
16: 神铸赋形/20210810-20210831 (飞雷之弦振, 天空之刃, 西风猎弓, 祭礼剑, 匣里灭辰, 雨裁, 祭礼残章)\
17: 神铸赋形/20210901-20210921 (薙草之稻光, 无工之剑, 祭礼弓, 匣里龙吟, 流浪乐章, 西风长枪, 钟剑)\
18: 神铸赋形/20210921-20211012 (不灭月华, 磐岩结绿, 笛剑, 西风大剑, 匣里灭辰, 西风秘典, 绝弦)\
19: 神铸赋形/20211013-20211102 (冬极白星, 尘世之锁, 恶玉丸, 西风剑, 西风长枪, 昭心, 弓藏)\
20: 神铸赋形/20211102-20211123 (护摩之杖, 终末嗟叹之诗, 断浪长鳍, 曚云之月, 祭礼剑, 雨裁, 流浪乐章)\
21: 神铸赋形/20211124-20211214 (苍古自由之誓, 松籁响起之时, 暗巷猎手, 匣里龙吟, 匣里灭辰, 暗巷的酒与诗, 祭礼大剑)\
22: 神铸赋形/20211214-20210104 (赤角石溃杵, 天空之翼, 暗巷闪光, 幽夜华尔兹, 西风长枪, 祭礼残章, 钟剑)\
23: 神铸赋形/20220105-20220125 (息灾, 和璞鸢, 千岩长枪, 笛剑, 西风猎弓, 流浪乐章, 西风大剑)\
24: 神铸赋形/20220125-20220215 (贯虹之槊, 阿莫斯之弓, 千岩古剑, 西风剑, 匣里灭辰, 西风秘典, 祭礼弓)\
25: 神铸赋形/20220216-20220308 (神乐之真意, 磐岩结绿, 断浪长鳍, 绝弦, 祭礼剑, 昭心, 雨裁)\
26: 神铸赋形/20220308-20220329 (薙草之稻光, 不灭月华, 恶玉丸, 曚云之月, 匣里龙吟, 西风长枪, 祭礼残章)\
27: 神铸赋形/20220330-20220419 (波乱月白经津, 终末嗟叹之诗, 弓藏, 笛剑, 流浪乐章, 匣里灭辰, 祭礼大剑)

四、常驻祈愿\
1: 奔行世间/20200928-20201222 (公测)\
2: 奔行世间/20201223-20210427 (新增迪奥娜和辛焱)\
3: 奔行世间/20210428-20210608 (新增罗莎莉亚)\
4: 奔行世间/20210609-20210901 (新增烟绯)\
5: 奔行世间/20210901-20211012 (新增早柚)\
6: 奔行世间/20211013-20211123 (新增九条裟罗)\
7: 奔行世间/20211124-20220104 (新增托马)\
8: 奔行世间/20220105-20220215(新增五郎)\
9: 奔行世间/20220216- (新增云堇)

五、新手祈愿\
1: 新手祈愿


### 关于隐藏概率（仓检）

本模拟器不考虑仓检。


## Credits

[原神抽卡全机制总结](https://www.bilibili.com/read/cv10468091)\
[原神抽卡记录数据集](https://github.com/OneBST/GI_gacha_dataset)\
by [一棵平衡树](https://space.bilibili.com/6165300) aka [OneBST](https://github.com/OneBST)

[uzair-ashraf's simulator](https://github.com/uzair-ashraf/genshin-impact-wish-simulator)\
by [uzair-ashraf](https://github.com/uzair-ashraf/)

[Genshin Wishes](https://genshin-wishes.com)

[非小酋](https://feixiaoqiu.com)
