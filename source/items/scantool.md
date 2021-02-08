---
title: Scan Tool
layout: default
---
# Scan Tool

<div class="infobox box text-center">
    <p style="text-align:center;"><img src="../../assets/images/icons/minecolonies/sceptersteel.png" alt="Scantool"></p>
    <recipe>scantool</recipe>
</div>
<br>

扫描工具非常实用，使用它为你获取任何建筑或结构的信息，接着就可以叫[建筑工](../../source/workers/builder)为你建造相同的建筑了。所以啊，如果你想要建造一座房子，一堵墙，一架桥，一幢塔，一家店，或者任何你想要建在你的殖民地的建筑，你可以先扫描他们的原型。单人游戏和多人游戏甚至服务器都支持。所扫描的结构将保留在[蓝图](../../source/tutorials/schematics)文件里，你可以在游戏中通过建筑工具让建筑工把它盖出来。你有没有想过，你可以利用这种方式让建筑工为你平整出一块空地(顺带在工作中升级)！只要先扫描出全是空气的结构，然后用[建筑工具](../../source/items/buildtool)将它放置在你想要清空平整的地方，接下来建筑工将会帮你把这块地清空，留下的仅仅是空气！你可以观看下方的短视频：

<p class="h4">扫描工具视频</p>

<div class="embed-responsive embed-responsive-16by9">
  <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/mFIC3752o1c" allow="autoplay; encrypted-media" allowfullscreen></iframe>
</div>
<br>

**提示:** 这里有两种专门为帮助玩家扫描结构的方块。
1. [(轻质)占位方块](../../source/items/substitutionblocks): 这个位置的方块不会被扫描进结构里。放置时不会覆盖原有的方块，例如空气、草、圆石等等。
2. [固体占位方块](../../source/items/substitutionblocks): 这个位置的方块保证一定是固体方块，放置时根据结构所要放置的生物群系生成固体方块。
### 第一步

第一步是合成一个扫描工具
<br>

### 第二步

拿着扫描工具鼠标左击结构的前下角（左边和右边都一样）最低水平面的方块。
![第一点](../../assets/images/tutorial/scan1.png)

### 第三步

右击结构的顶上角相对于你刚才（左边或者右边）的位置(你可以在这个位置放置一个[(轻质)占位方块](../../source/items/placeholderblock)方便选择)，将整个结构包含在这两个角构成的框框中。

![第二点](../../assets/images/tutorial/scan2.png)

### 第四步

接下来，在空中右击，进入扫描工具GUI

![扫描工具GUI](../../assets/images/gui/scan_tool_gui.png)

在GUI中你可以看到你刚刚扫描指定的两个角的坐标，可以在这里修改。你还可以在这里为你的结构命名。按下绿色箭头保存扫描结构，红色叉叉取消本次扫描，重新再来。

你可以点击显示资源按钮，可以浏览扫描结构中的所有方块。有两个选项：

* 移除。可以移除你不想要的方块。
* 置换。把扫描中的某种方块替换成你更想要的方块。

你可以在一个方块上shift+右击以设置旋转枢纽。（你当然可以把它设置在扫描结构外，但显然没用。）枢纽是使用[建筑工具](../../source/items/buildtool)时，把结构进行旋转，所围绕的点。在结构中会被红框圈出，所以你可以把它在结构中辨别出来。默认（如果你没用shift+右击进行设置）位置是小屋方块（对于小屋来说）或结构的中心点（对于装饰来说）。你不能改变小屋的旋转枢纽。它的位置一直是小屋方块。
