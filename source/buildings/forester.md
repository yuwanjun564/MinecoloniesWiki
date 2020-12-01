---
title: Forester's Hut
layout: default
---
# 林务员小屋

<div class="infobox box text-center">
    <img src="../../assets/images/buildings/lumberjack.png" alt="Forester's Hut" />
    <hr />
    <div class="row section-text text-left">
        <div class="col">
        <p><strong>工人:</strong></p>
        </div>
        <div class="col">
        <p><a href="../workers/forester">林务员</a></p>
        </div>
    </div>
    <hr />
    <recipe>lumberjack</recipe>
</div>

在砍树的间隙时间里，林务员会出入林务员小屋。林务员会砍伐在以自身为中心大约150格方块范围内的树木。在任何小屋结构内，或是下方放置圆石的树木将不会被砍伐。

**注释:** 在 Minecraft 1.16+ 中，林务员需要锄（以破坏树叶）

<br>

## 林务员小屋 GUI

右击 林务员小屋方块，你将看到有着许多选项的GUI

<div class="row">
  <div class="col-sm-12 col-md">
    <img src="../../assets/images/gui/lumberjackgui1.png" class="img-fluid mx-auto" alt="Forester's Hut GUI">
  </div>
  <div class="col-sm-12 col-md"><br>
    <br>
    <ul>
      {% for item in site.data.gui.global %}
        <li><strong>{{ item.button }}:</strong> {{ item.content }}</li>
      {% endfor %}
    </ul>
  </div>
</div>  
<br> <br>

这是林务员小屋GUI的第二页，这里展示着林务员可以进行种植的树苗，包括mod里面的（如果代码写得正确的话）。在这里你可以调整林务员可以砍伐的树的种类。（上面的黑色文本框是用于搜索树苗类型的）

<div class="row">
  <div class="col-sm-12 col-md">
    <img src="../../assets/images/gui/lumberjackgui2.png" class="img-fluid mx-auto" alt="Forester's Hut GUI 2">
  </div>
  <div class="col-sm-12 col-md">
    <ul>
      <li><strong>任务列表：</strong>你可以在这里选择你想要让林务员种植的树苗类型。点击树苗来调整是否进行种植。</li><br>

    </ul>
  </div>
</div>
<br>
这是林务员小屋GUI的第三页
<br><br>
<div class="row">
  <div class="col-sm-12 col-md">
    <img src="../../assets/images/gui/lumberjackgui3.png" class="img-fluid mx-auto" alt="Forester's Hut GUI 3">
  </div>
  <div class="col-sm-12 col-md">
    <ul>
      <li><strong>补种：</strong>这里你可以选择是否想要林务员在砍伐树木之后补种树苗。当然了，他们只会在拥有充足树苗的时候才会补种。</li><br>
      <li><strong>限制区域：</strong>这里你可以选择是否将林务员的伐木活动限制在一定区域内。请点击 给予选择工具 按钮以选择区域。</li><br>
      <li><strong>给予选择工具：</strong>点击这个按钮你将得到一个用于划定区域的工具，以此来为林务员选择一个特定的区域工作。</li>
    </ul>
  </div>
</div>
<br>
