---
title: 蓝图
layout: default
---
# 蓝图

蓝图（Schematic），是玩家在游戏中利用[扫描工具](../items/scantool)获取的文件，它包含所扫描的某一区域内方块和实体的信息。你可以在单人或多人游戏中，使用扫描工具获取任何建筑或结构的信息，接着就可以叫[建筑工](../../source/workers/builder)为你建造相同的建筑了。当然了，你要先为他们提供必需的材料。
- [蓝图索引](#蓝图)
  - [扫描一个新结构](#扫描一个新结构)
  - [放置结构](#放置结构)
  - [FAQ](#faq)
      - [扫描文件的文件夹是什么，它在哪里？](#扫描文件的文件夹是什么，它在哪里？)
      - [蓝图文件夹在哪里？](#蓝图文件夹在哪里？)
      - [我居然有一个“*/minecolonies/01e6a291-8a01-4763-bcae-f3a8797b1d52/cache/” 目录下的文件夹，这是干什么用的？](#我居然有一个“*%22minecolonies%2201e6a291-8a01-4763-bcae-f3a8797b1d52%22cache%22”目录下的文件夹，这是干什么用的？)
      - [我要怎么创建一个自定义的小屋？](#我要怎么创建一个自定义的小屋？)
      - [怎么重写一些内置的蓝图？](#怎么重写一些内置的蓝图？)
      - [要怎么使用自定义小屋？](#要怎么使用自定义小屋？)
      - [要怎么让我的服务器玩家在我的服务器上使用他们自己本地的小屋蓝图？](#要怎么让我的服务器玩家在我的服务器上使用他们自己本地的小屋蓝图？)
      - [要怎么让我的服务器玩家在我服务器上使用他们自己在服务器上扫描的蓝图？](#要怎么让我的服务器玩家在我服务器上使用他们自己在服务器上扫描的蓝图？)
      - [怎么完全禁止内置的结构的使用？](怎么完全禁止内置的结构的使用？)


## 扫描一个新结构

当你有一个想要扫描的结构或区域，首先要限定出需要扫描的确切区域，这样才好让你的建筑工开工。

![TestBuilding](../../assets/images/tutorial/testbuilding.png)

换上你的[扫描工具](../items/scantool)，首先鼠标左击该区域最左下的方块，接着在该区域最右上放置任一方块（可以是[占位方块](../../source/items/placeholderblocks)），然后右击它。

![ScanPoint1](../../assets/images/tutorial/scan1.png)

![ScanPoint2](../../assets/images/tutorial/scan2.png)

接着轻击空气就可以看到完整的结构被区划出来，进入结构界面。

![ScanFull](../../assets/images/tutorial/scan3.png)

设置好完整的区域以后，你可以按下ESC退出界面，但所扫描区域的白色高亮外框。绕着它走走，再检查一遍你所想要划出的区域是否都被扫描到。当一切准备就绪，再次右击空气，进入GUI界面，填写本次扫描的名字。之后按下绿色确认按钮保存。

 ../structurize/schematics/(folder)/file  。

扫描文件将被存放在 `../minecolonies/scan/new/...`中。

如果该扫描的结构是<a href="#customhuts">自定义的小屋</a>，保存好扫描文件后，得把他们移动到 `../structurize/schematics/(folder)/file` 中。

## 放置结构

扫描完结构以后，你可以使用[建筑工具](../../source/items/buildtool)来让你的[建筑工](../../source/workers/builder)们依它建造。选择建筑工具，右击，进入GUI，左侧下拉式菜单供选择“我的蓝图”，右侧下拉式菜单则显示着你的扫描文件。GUI界面还可供你更改扫描文件的名字。你也可以把你保存的扫描文件删掉。

![Schematic](../../assets/images/tutorial/schematic.png)

## FAQ

现在是关于蓝图的FAQ环节。

#### 扫描文件的文件夹是什么，它在哪里？

扫描文件文件夹，是在模拟殖民地中，使用扫描工具进行扫描之后，扫描文件储存的地方。这只存在于客户端本地目录，位于MC的文件夹 `*/structurize/scans/`下。初始扫描的蓝图位于 `*/structurize/scans/new/` ，除非它们在游戏中被重命名。这个目录是单人游戏和多人游戏共用的。

#### 蓝图文件夹在哪里？

自定义的结构的蓝图需要你将它复制到蓝图文件夹里，它在 `*\structurize\schematics\`.

不过这个位置将取决于游戏的类型（指多人和单人）：

- 对于单人游戏，它可能被存放在两个位置中的其一:
  * 在地图文件夹中: `*/minecraft/saves/(World Name)/structurize/schematics/`
    + **注意:** 当你需要你的自定义结构的蓝图仅仅局限于某一地图，请在地图文件夹中添加该目录下的蓝图文件夹。当该目录下的蓝图文件夹存在时（尽管是否为空），《模拟殖民地》将完全忽略其他可能的目录，都把蓝图存放在该文件夹中。
  * 在MC主体游戏文件夹中: `*/minecraft/structurize/schematics/`
    + **注意:** 当你需要在多个地图中用到同一个自定义结构的蓝图时，请在MC主体文件夹中添加该目录下的蓝图文件夹。
- 对于多人游戏，蓝图将一直从该地图的目录: `*/minecolonies/schematics/` 下加载。


#### 我居然有一个“*/minecolonies/01e6a291-8a01-4763-bcae-f3a8797b1d52/cache/”目录下的文件夹，这是干什么用的？

当玩家游玩服务器时，服务器需要将蓝图发送给玩家以便预览建筑工具制作的作品。这些蓝图将保存在MC主体文件夹 `*/structurize/{ServerUUID}/cache/`下，ServerUUID是一个服务器的特定标识ID。当需要被用到时，服务器将自动创建这些目录，不用到时，这些目录将一定会被删除。

#### 我要怎么创建一个<a id="customhuts">自定义</a>的小屋？

为已建造的屋子创建蓝图，你得遵守下列规则：对于相同样式/小屋类型，但不同级别的小屋来说，扫描结构必须有相同的空间体积；扫描文件必须包含特定的小屋方块，例如：对于[建筑工小屋](../../source/buildings/builder)来说，需要建筑工小屋方块；在不同级别的房屋中，小屋方块必须在扫描框架中的同一位置而且要同一个旋转角度；扫描文件的文件名要遵守命名规则：{StyleName}/{HutName}{HutLevel}.blueprint
例如，MyOwn样式的建筑工小屋，我们要这样命名

*myown/builder1.blueprint*
*myown/builder2.blueprint*
*myown/builder3.blueprint*
*myown/builder4.blueprint*
*myown/builder5.blueprint*

- **注意:**  在[建筑工具](../../source/items/buildtool)中，拓展名是被隐藏的。HutName可以是下列小屋的任意一个。最大等级是5级。

全部就绪后，将myown文件夹移入蓝图文件夹中，启动游戏。你将在建筑工具中看到你的自定义小屋。

- **注意:** 记得，你要在目录中指定确切的小屋类型，这样才可以在建筑工具中看到你的蓝图。

## 自定义小屋文件名

这是截至2020.2.9更新的全部建筑的总表。**请注意** *大小写问题*

| Level 1        | Level 2        | Level 3        | Level 4        | Level 5        | 译者注         |
| :------------- | :------------- | :------------- | :------------- | :------------- | -------------- |
| archery1       | archery2       | archery3       | archery4       | archery5       | 卫兵塔（箭台） |
| baker1         | baker2         | baker3         | baker4         | baker5         | 面包房         |
| barracks1      | barracks2      | barracks3      | barracks4      | barracks5      | 兵营           |
| barrackstower1 | barrackstower2 | barrackstower3 | barrackstower4 | barrackstower5 | 兵营塔         |
| blacksmith1    | blacksmith2    | blacksmith3    | blacksmith4    | blacksmith5    | 铁匠铺         |
| builder1       | builder2       | builder3       | builder4       | builder5       | 建筑工小屋     |
| chickenherder1 | chickenherder2 | chickenherder3 | chickenherder4 | chickenherder5 | 养鸡场         |
| citizen1       | citizen2       | citizen3       | citizen4       | citizen5       | 市民小屋       |
| combatacademy1 | combatacademy2 | combatacademy3 | combatacademy4 | combatacademy5 | 战斗研究所     |
| composter1     | composter2     | composter3     | composter4     | composter5     | 堆肥小屋       |
| cook1          | cook2          | cook3          | cook4          | cook5          | 餐厅           |
| cowboy1        | cowboy2        | cowboy3        | cowboy4        | cowboy5        | 牛仔小屋       |
| crusher1       | crusher2       | crusher3       | crusher4       | crusher5       | 粉碎机         |
| deliveryman1   | deliveryman2   | deliveryman3   | deliveryman4   | deliveryman5   | 运送员小屋     |
| enchanter1     | enchanter2     | enchanter3     | enchanter4     | enchanter5     | 附魔小屋       |
| farmer1        | farmer2        | farmer3        | farmer4        | farmer5        | 农场           |
| fisherman1     | fisherman2     | fisherman3     | fisherman4     | fisherman5     | 渔夫小屋       |
| florist1       | florist2       | florist3       | florist4       | florist5       | 花卉小屋       |
| guardtower1    | guardtower2    | guardtower3    | guardtower4    | guardtower5    | 卫兵塔         |
| library1       | library2       | library3       | library4       | library5       | 图书馆         |
| lumberjack1    | lumberjack2    | lumberjack3    | lumberjack4    | lumberjack5    | 伐木场         |
| miner1         | miner2         | miner3         | miner4         | miner5         | 矿工小屋       |
| sawmill1       | sawmill2       | sawmill3       | sawmill4       | sawmill5       | 锯木厂         |
| shepherd1      | shepherd2      | shepherd3      | shepherd4      | shepherd5      | 牧场           |
| sifter1        | sifter2        | sifter3        | sifter4        | sifter5        | 筛沙工小屋     |
| smeltery1      | smeltery2      | smeltery3      | smeltery4      | smeltery5      | 冶炼厂         |
| stonemason1    | stonemason2    | stonemason3    | stonemason4    | stonemason5    | 石匠小屋       |
| stonesmeltery1 | stonesmeltery2 | stonesmeltery3 | stonesmeltery4 | stonesmeltery5 | 石材冶炼厂     |
| swineherder1   | swineherder2   | swineherder3   | swineherder4   | swineherder5   | 养猪场         |
| townhall1      | townhall2      | townhall3      | townhall4      | townhall5      | 市政厅         |
| university1    | university2    | university3    | university4    | university5    | 大学           |
| warehouse1     | warehouse2     | warehouse3     | warehouse4     | warehouse5     | 仓库           |

## 小屋方块要求

|                        建筑                        |                             要求                             |      建议      |
| :------------------------------------------------: | :----------------------------------------------------------: | :------------: |
|      [卫兵塔](../../source/buildings/archery)      |           每一级一个射击假人（干草堆上方一个按钮）           |                |
|      [面包房](../../source/buildings/bakery)       |                           一个熔炉                           |                |
|      [兵营](../../source/buildings/barracks)       |         每一级一个兵营塔（直到4级，就是说最多四个）          |                |
|   [兵营塔](../../source/buildings/barrackstower)   |                                                              |  每一级一张床  |
|    [建筑工小屋](../../source/buildings/builder)    |                                                              | 每一级一个架子 |
|     [市民小屋](../../source/buildings/citizen)     |                         每一级一张床                         |                |
| [战斗研究所](../../source/buildings/combatacademy) |           每一级一个拳击假人（干草堆上放一个南瓜）           |                |
|    [堆肥小屋](../../source/buildings/composter)    |         每一级一个[木桶](../../source/items/barrel)          |                |
|     [餐厅](../../source/buildings/restaurant)      |                        每一级一个熔炉                        |                |
|        [染坊](../../source/buildings/dyer)         |                           一个熔炉                           |                |
|   [花卉小屋](../../source/buildings/flowershop)    |    每一级四个 [堆肥（方块）](../../source/items/compost)     |                |
|    [玻璃厂](../../source/buildings/glassblower)    |                        每一级一个熔炉                        |                |
|    [卫兵塔](../../source/buildings/guardtower)     |                                                              |  每一级一张床  |
|      [医院](../../source/buildings/hospital)       |                         每一级一张床                         |                |
|      [图书馆](../../source/buildings/library)      |                           很多书架                           |                |
|        [矿井](../../source/buildings/mine)         |                           一个矿井                           |                |
|       [学校](../../source/buildings/school)        |                        每一级两张地毯                        | 每一级四张地毯 |
|      [冶炼厂](../../source/buildings/school)       |                        每一级一个熔炉                        |                |
| [石材冶炼厂](../../source/buildings/stonesmeltery) |                        每一级一个熔炉                        |                |
|    [种植园](../../source/buildings/plantation)     | 每一级四个这样的结构：沙子下面放石砖，沙子下面放圆石，沙子靠近水方块 |                |
|       [酒馆](../../source/buildings/tavern)        | 四张床，[垂直放置](../../source/items/barrel_horizontal)或者（包括） [水平放置的木桶](../../source/items/barrel_vertical),一间就餐厅 |                |
|     [大学](../../source/buildings/university)      |                           很多书架                           |                |
|      [仓库](../../source/buildings/warehouse)      |         每一级多很多[架子](../../source/items/racks)         |                |

## 等级要求

|  Level  |  Requirements  |
| :-----: | :------------: |
| Level 1 | 非常简单- 青木 |
| Level 2 |  简单 - 黑铁   |
| Level 3 |  中等 - 下界   |
| Level 4 |  困难 - 蓝海   |
| Level 5 | 非常困难- 末地 |

<br>
<br>

## 关于建筑的小贴士

### 宜
<ul>
  <li>让所有级别的小屋有相同的空间体积（x,y,z）</li>
  <li>小屋方块必须在扫描框架中的同一位置而且要同一个旋转角度</li>
  <li>确保小屋中所有箱子和[架子](../../source/items/rack)在不同级别中保持同一位置</li>
  <li>你的结构的水平基座或低于水平面的方块应用[固体占位方块](../../source/items/placeholderblocks)来建构</li>
  <li>当你有想要不破坏原有结构/地貌的部分（包括在升级过程中），使用[轻质占位方块](../../source/items/placeholderblocks)来建构该部分。例如：在[兵营](../../source/buildings/barracks)升级为[兵营塔](../../source/buildings/barrackstower)的过程，兵营塔保留兵营结构的部分。</li>
  <li>只能使用原版方块或者结构化mod中的方块</li>
  <li>使用书与笔代替空白的书</li>
  <li>If building upgradable deco, add the deco controller with the name of your deco item, LunaDragonStar (the schematics admin) will fix the pathing that goes in it to match where she puts it in the files</li>
</ul>

### 否
<ul>
  <li>不宜在建筑中使用不可获得的方块（不要用命令方块，石化木方块，被虫蚀的方块，或者生物头颅。</li>
  <li>不要随便改变其他人的样式，除非有被特意要求这样做。</li>
</ul>

## 附加说明

#### 怎么重写一些内置的蓝图？

只要创建一个与其相同样式/名字的蓝图文件就行了。举个例子，要重写1级的[建筑工小屋](../../source/buildings/builder)，就直接创建一个地址下wooden/builder1.blueprint的文件就可以了

#### 要怎么使用自定义小屋

自定义小屋首先要先复制到蓝图文件夹内。复制完以后，像平常一样启动你的单人游戏或者多人游戏。你将会在[建筑工具](../../source/items/buildtool)中看到他们（只要你的物品栏有小屋方块）。

#### 要怎么让我的服务器玩家在我的服务器上使用他们自己本地的小屋蓝图？

你得把他们的蓝图复制到服务端的蓝图文件夹内，然后重启服务器。

#### 要怎么让我的服务器玩家在我服务器上使用他们自己在服务器上扫描的蓝图？

编辑配置文件，把allowPlayerSchematics改为true。这样就可以让玩家们去使用自己装饰的蓝图建筑了。但这不会让玩家使用自己的小屋蓝图。你也可以限制总时间内可供上传的玩家蓝图数，通过编辑maxCachedSchematics条目就可以了，（默认为100），当达到限制数，服务器将会开始删除没有被用到的蓝图。

#### 怎么完全禁止内置的结构的使用？

编辑配置文件，把ignoreSchematicsFromJar改为true。注意了，如果某些你提供的蓝图缺失了，这个规则会将会被打破，会继续引用内置的来补充。

