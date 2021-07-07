---
title: Builder's Hut
layout: default

---

# Builder's Hut

<div class="infobox box text-center">
    <img src="../../assets/images/buildings/builder.png" alt="Builder's Hut" />
    <hr />
    <div class="row section-text text-left">
        <div class="col">
        <p><strong>Worker:</strong></p>
        </div>
        <div class="col">
        <p><a href="../workers/builder">Builder</a></p>
        </div>
    </div>
    <hr />
    <recipe>builder</recipe>
</div>


### 对于其他*任何*建筑来说，建筑工小屋是必选项。如果你还没建造建筑工小屋，那么建筑工将不会为你建造其他类型的建筑。

建造建筑工小屋之前，你得先考虑清楚其他可能可以建造建筑的地点与其的距离，还要考虑地面上一些建筑障碍，例如水面、树木、洞穴、山丘、岩浆池等。选好地点以后，首先要合成建筑工小屋方块，并用[建筑工具](../items/buildingtool)将其放置在该地点，接下来建筑工将会自动地被委派完成任务（或者你可以手动安排一个有着最合适的[素质](../systems/workerinfo)的工人作为建筑工，在[市政厅GUI](../../source/buildings/townhall)的设置页面可以修改）

现在你可以发布建筑任务，建筑工将先建造他们的小屋。他们会先寻求所需材料，记得要检查[资源卷轴](../../source/items/resourcescroll) 或者[建筑工小屋](../../source/buildings/builder)第二页，看看要什么材料，以符合建筑/升级的需求。当材料仍然急缺时，将被用红色标出。

当建筑工小屋先搭建完成时，你就可以随心所欲建筑任何你想要建筑的东西了，像工作小屋，建筑，装饰，或者你的自定义结构。

- **注意:** 建筑工只能建筑不超过他们自己小屋级别的建筑。所以，若要升级其他建筑，要优先升级建筑工小屋。接下来建筑工才能升级其他建筑。

## 建筑工小屋GUI

当你通过右击建筑工小屋方块进行交互，你会看到有着众多不同选项的GUI：
<br>

<div class="row">
  <div class="col-sm-12 col-md">
    <img src="../../assets/images/gui/buildergui1.png" class="img-fluid mx-auto" alt="Builder GUI">
  </div>
  <br>
  <div class="col-sm-12 col-md">
    <br>
    <ul>
      {% for item in site.data.gui.global %}
        <li><strong>{{ item.button }}:</strong> {{ item.content }}</li>
      {% endfor %}
    </ul>
  </div>
</div>
 <div class="col-sm-12 col-md"><br>
    <p>当你按下顶部右角的箭头时，你将看到GUI第2页有着以下内容。</p>
  </div>

<br>

<div class="row">
  <div class="col-sm-12 col-md">
    <img src="../../assets/images/gui/buildergui2.png" class="img-fluid mx-auto" alt="Builder GUI 2">
  </div>
</div>

<br>

<li><strong>需求的资源：</strong> 这些是建筑工正在进行的建筑任务所需的资源。当建筑工放置方块时，数目会减少，这里<strong>只</strong>将显示建筑工还需要放置的方块。红色标出的是你和建筑工存储里都没有的方块。</li>

<br>

<p style="color:Blue;"><b>重要信息</b> 按下<b>建造</b>按钮后你将看到一张关于所有需要用于建筑的材料清单。表单上有许多选项，但最重要的一项是，你<i>必须确认</i>建造——通过按下<b>建造建筑</b>按钮来创建建筑命令。</p>

<p style="color:Blue;"><b>重要信息：</b>按下升级按钮后你将看到一张关于需要用于<b>升级</b>的材料清单。表单上有许多选项，但最重要的一项是，你<i>必须确认</i>升级——通过按下<b>升级建筑</b>按钮来创建升级命令。 </p>

<p>按下建造选项按钮后，你可以看到一些选项:</p>

<br>

<div class="row">
  <div class="col-sm-12 col-md">
    <img src="../../assets/images/gui/upgradebuild.png" class="img-fluid mx-auto" alt="Upgrade Building GUI">
  </div>
  <div class="col-sm-12 col-md">
    <ul>
       <ul>
      {% for item in site.data.gui.build %}
        <li><strong>{{ item.button }}:</strong> {{ item.content }}</li>
      {% endfor %}
    </ul>
    </ul>
  </div>
</div>

<br><br>

### 一些值得注意的事

在考虑建筑工小屋的地点的时候，你得想想把小屋建在你其他计划要建造的小屋之间，这样你的建筑工就可以少走一点路了。

建筑工总是先完成现有进程，再开始其他建造任务。

你可以打开[市政厅的GUI](../../source/buildings/townhall)界面，进入建造命令的标签栏中，取消现有建造进程，或是调整建造进程的优先级。如果你在建到一半的时候取消建造进程，又重新安排建造命令，建筑工将在原先的基础上继续建造。

如果建筑工在建造或升级的过程中移除了方块（泥土，原木，木板，玻璃等等），他们会将其放入背包。当建造完工后，他们将会把所有背包中的物品倾倒进建筑工小屋的存储中。
<br><br>
