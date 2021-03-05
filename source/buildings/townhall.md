---
title: Town Hall
layout: default

---

# Town Hall

<div class="infobox box text-center">
    <img src="../../assets/images/buildings/townhall.png" alt="Town Hall's Block" />
    <hr />
    <recipe>townhall</recipe>
</div>


The Town Hall is the central part of your colony.
市政厅是你的殖民地的核心部分

**Note:** The Town Hall block **cannot** be crafted until **after** you have already placed the Town Hall you get from the [Supply Ship/Camp](../../source/items/supplycampandship). If needed, it can also be obtained in creative mode like any other block or by commands.
注释：市政厅方块不能被合成，除非你已经放置了从[补给营地或补给船](../../source/items/supplycampandship)中获得的市政厅。
如果有必要，可以从创造模式或通过命令获得。

## 开启新殖民地

### 勘测地块

Make sure you scout your area carefully before you decide where you want to place your Town Hall. Your colony will start with a 4 chunk radius (4 chunks in each direction) from the Town Hall block. Make sure this is where you want your colony to be.
在放置市政厅之前，先确保你已经详细地勘测过要开启殖民地的地块。你的殖民地将以市政厅方块为中心，以4个区块为半径向各个方向延伸。确定这是你要开荒的地方。

### 放置你的市政厅

After you have carefully decided where you want to place your Town Hall (remember, the position where you placed the Town Hall block will be the center of your colony's protected area. Once placed, the area will be set and cannot be changed), use your [build tool] (../items/buildtool) to place the Town Hall block.
考虑清楚你要放置市政厅的位置以后（记住，该位置将是你的殖民地受保护范围的中心位置，这个区域将会被固定下来，不能再改变），使用[建筑工具] (../items/buildtool)来放置市政厅方块。

Right-click the ground in the area you want to place the Town Hall. The building GUI will display showing the 3D preview of the building. You will be able to use the arrow buttons to move the building to the location you desire. 
右击你要放置市政厅方块的地面。建筑工具GUI将展示市政厅的3D预览。你可以点击箭头按钮移动建筑到你想要的位置。

**Note:** Make sure you use the + and - options in the GUI to make sure you have the ground level of the hut where you want the ground level to be. Not all hut blocks sit on the ground.
**注释:** 你要先按按GUI中的+和-按钮，确保你的小屋的地面是在你想要的水平面上。不是所有小屋的方块都会在地面上。

Once you commit to the placement of the Town Hall (green checkmark), the Town Hall block will be placed.
确定了放置位置以后（绿色勾号），市政厅方块就直接被放置下去。

### 创建你的殖民地

Once you have placed the Town Hall block you will need to right-click on it and select Create New Colony.
放置完市政厅方块以后，你需要右击，选择【创建新殖民地】。
<img src="../../assets/images/gui/th_colonycreationGUI.png" alt="Creating New Colony" />

A new colony will be created, the area of your colony will be established, and the entire area will be protected.
一个新的殖民地将被创建，殖民地的范围将被确定，整个区域将受到保护。

### 区域保护

When you start a colony, the area that is initially set also has protections added to it. The protection system includes blocking any player from placing/breaking or interacting with blocks of any kind, placing lava or water, and placing/lighting TNT. Once established it will also show in the informational screen.
当你开启一块新的殖民地的时候，初始设置中也会添加上区域保护。保护系统包括阻止任何玩家放置或者破坏方块，或者和任何种类的方块交互，或者放置岩浆或者水，还有放置和点燃TNT也会被禁止。保护系统建立后，将被展示在屏幕信息上。

The protected area of your colony (once the Town Hall has been placed) will depend on the configuration, but will be 4 chunks radius by default, measured from where you placed your Town Hall block the first time. Therefore, plan carefully where you want to place your Town Hall. Your protected colony area includes mountains, hills, lakes, oceans, caves, world generated structures, etc. from bedrock to the sky limit.
你的殖民地的保护区域（市政厅被放置后）将取决于你的设置文件，默认是4个区块为半径，以你第一次放置市政厅方块的位置为圆心。因此，你要考虑清楚你所要放置市政厅方块的位置。你的殖民地保护区域包括山地、丘陵、湖泊、海洋、洞穴，自定义世界生成的结构等，且从基岩到天空高度限制的地方都在内。

Due to the protected area of each colony, you have to carefully scout your surroundings to make sure you are clear of any other colonies nearby preventing you from placing your Town Hall or limiting your colony area in that direction.
由于每一个殖民地都有区域保护，你得仔细勘察你周围的环境以确保周围没有其他殖民地，以免处于其他殖民地的保护区域内，而阻止你放置市政厅方块，或者你的殖民地在延伸上受到该方向上的限制。

**Note:** Once you place your Town Hall block, this will be the CENTER of your Town's protected radius. If you decide that you want your actual Town Hall building to be built in a different location (within your currently set protected radius), you can break the block and place it again with your build tool. Removing and replacing the Town Hall block will NOT remove the Protected area of your Town. The only way to remove the protected area of your colony so that you can place a Town Hall somewhere else is by a person with OP or admin permission deleting your colony through [commands](../systems/command). 
**注释:** 放置市政厅方块以后，这将作为你的殖民地保护区域的【圆心】。如果你决定要让你实际的市政厅健在其他位置（在你现在设置的保护区域范围内），你可以破坏市政厅方块，然后
用建筑工具再放置一遍。移除市政厅方块后重新放置【不会】删除对你的殖民地的区域保护。删除区域保护、把市政厅挪到其他地方的唯一方法是叫有OP或者管理员权限的人用[命令](../systems/command)删除你的殖民地信息。

**Note**: You can configure your own colony area radius in the minecolonies-common.toml file inside the ```../config/``` folder of your own world/server.
**注释:**你可以定义你自己殖民地的半径，在你的world/server里的config文件夹的minecolonies-common.toml里修改。

If there is another colony too close to your current position, you won't be able to place a Town Hall.
如果已有殖民地太靠近你当前的位置，你将无法放置市政厅方块。

If you try to place another Town Hall outside of your protected area, you will get a message: <br> 
<img src="../../assets/images/gui/th_secondplace.png" alt="Placing a Second Town Hall"/>
如果你尝试在你的保护区域外放置另外的市政厅方块，你将收到一条信息如下： <br> 
<img src="../../assets/images/gui/th_secondplace.png" alt="Placing a Second Town Hall"/>

## 市政厅GUI

<i>You can use the tabs on the left side to switch between different categories.</i>
<i>你可以用左侧的标签页去切换条目</i>

<br>

### <strong>信息:</strong> 这是市政厅GUI的总体信息部分。

<div class="row">
  <div class="col-sm-12 col-md">
    <img src="../../assets/images/gui/th_information.png" class="img-fluid mx-auto" alt="TH GUI Information Tab">
  </div>
  <div class="col-sm-12 col-md">
    <ul>
      <li><strong>第一页: </strong>Here you will see some statistics on your citizens, like the number of citizens you have and if they are unemployed or workers. If they are workers, you will see what job they have.</li>
      <li><strong>第一页: </strong>在这里展示出你的市民的一些统计信息。例如市民的总数以及就业情况。如果他们有工作了，你可以在这里看到他们的职业。</li>
      <br>
      <li><strong>第二页: </strong>Here you will see the overall happiness of the colony's citizens and any events that happened within the colony (the newest events are at the bottom). You can click the button to switch to a permission log, which will show any illegal actions that happened in the colony (like if a player tried to break a block when they aren't allowed to). Clicking the plus next to an illegal action will change it to a legal action if the player tries to do it again. For more information, see the <a href="../../source/systems/protection"> Protection system</a> and the Permission tab of the Town Hall GUI.</li>
      <li><strong>第二页: </strong>在这里展示殖民地的整体幸福度以及在殖民地中发生的所有事件（最新的事件展示在最底部）。点击按钮切换到行为许可日志界面，在这里展示所有在殖民地中不符合设定的规则的行为（例如当规则是不允许破坏方块时有玩家尝试这样做）。 点击非法行为旁边的加号将会把它设置回合法的，当玩家再次发生该行为不再判定为非法。详见 <a href="../../source/systems/protection"> 殖民地保护系统</a>以及市政厅GUI中的权限页面。</li>
    </ul>
  </div>
</div>


<br>
<br>

### <strong>行动:</strong> 这是最重要的部分。

<div class="row">
  <div class="col-sm-12 col-md">
    <img src="../../assets/images/gui/th_actions.png" class="img-fluid mx-auto" alt="TH GUI Actions Tab">
  </div>
  <div class="col-sm-12 col-md">
    <p><strong>第一页: </strong>Here you will see the name of your colony as well as the building level of the Town Hall. And the buttons:</p>
    <ul>
      <li><strong>Build Options-</strong>Lets you create a build, upgrade, reposition, or repair build order for the Town Hall. To learn more about the building system, please visit the <a href="../../source/workers/builder"> Builder</a> page.</li><br>
      <li><strong>Rename Colony-</strong>To change the name of your colony (from Your Username's Colony, which is the default) to anything you want.</li><br>
      <li><strong>Hire Mercenaries-</strong>Here you can hire mercenaries to help defend your colony. Be warned, they're mean and will steal from citizens!</li>
    </ul>
    <br>  
    <p><strong>第二页: </strong>This is only enabled if PVP is turned on in the config file. Here you have:</p>
    <ul>
      <li><strong>Allies-</strong>Other colonies that you have added as allies and that have confirmed your colony as an ally as well.</li>
      <br>
      <li><strong>Feuds-</strong>Other colonies that you have added as a feud and that have confirmed your colony as a feud as well.</li>
    </ul>
  </div>
</div>
<div class="row">
  <div class="col-sm-12 col-md">
    <img src="../../assets/images/gui/th_actions.png" class="img-fluid mx-auto" alt="TH GUI Actions Tab">
  </div>
  <div class="col-sm-12 col-md">
    <p><strong>第一页: </strong>在这一页你可以看到你的殖民地的名称，市政厅的等级以及一些按钮：</p>
    <ul>
      <li><strong>Build Options 建筑选项-</strong>点击该按钮为你的市政厅下达建造、升级、移动、修复等建筑指令。想要了解更多有关建造系统的信息，请查阅<a href="../../source/workers/builder">建筑工</a>页面。</li><br>
      <li><strong>Rename Colony 重命名殖民地-</strong>更改你的殖民地的名字（默认为 你的ID+'s Colony）。</li><br>
      <li><strong>Hire Mercenaries 雇佣兵-</strong>雇佣雇佣兵来保卫殖民地，不过他们可都是些流氓，是会偷你的村民的物品的！</li>
    </ul>
    <br>  
    <p><strong>第二页: </strong>当且仅当PVP在设置文件中被开启，本页才生效。在这里你可以：</p>
    <ul>
      <li><strong>Allies 盟友-</strong>这里会显示和你结盟的殖民地。（结盟是双向的）</li>
      <br>
      <li><strong>Feuds 敌人-</strong>这里会显示和你敌对的殖民地。（敌对是双向的）</li>
    </ul>
  </div>
</div>


<br>
<br>

### <strong>权限:</strong> 在这里邀请你的好友合作开发殖民地

<p><strong>Permissions Pg. 1 & 2: </strong>You can add a player and give them a rank in your colony. Each rank will have certain privileges in the changeable protection system.</p>

<p><strong>权限页面 第一页和第二页：</strong>你可以设置其他玩家在殖民地中的地位，不同的地位等级会在殖民地保护系统中有不同的特权。</p>

<div class="row">
  <div class="col-sm-12 col-md">
    <img src="../../assets/images/gui/th_permissions.png" class="img-fluid mx-auto" alt="TH GUI Permissions Tab">
  </div>
  <div class="col-sm-12 col-md">
    <ul>
      <li><strong>第一页: </strong>Here you type the name of the player you want to add.</li>
      <br>
      <li><strong>第二页: </strong>Shows the list of players that have ben added as well as their current rank. You can click on the "-" or "+" to give them a higher rank or lower rank.</li>
    </ul>
  </div>
</div>  
<div class="row">
  <div class="col-sm-12 col-md">
    <img src="../../assets/images/gui/th_permissions.png" class="img-fluid mx-auto" alt="TH GUI Permissions Tab">
  </div>
  <div class="col-sm-12 col-md">
    <ul>
      <li><strong>第一页: </strong>在这里输入你想要添加权限的玩家的ID</li>
      <br>
      <li><strong>第二页: </strong>显示你已添加的玩家列表，以及他们的地位等级。你可以点击“+”或“-”来调整他们的地位。</li>
    </ul>
  </div>
</div>  



---

<p><strong>Permissions Pg. 3 & 4: </strong>Here you can manage the permissions for each rank.</p>

<p><strong>权限界面 第三页和第四页：</strong>你可以在这设置各个地位等级的权限。</p>

<div class="row">
  <div class="col-sm-12 col-md">
    <img src="../../assets/images/gui/th_permissions2.png" class="img-fluid mx-auto" alt="TH GUI Permissions Tab Pg.2">
  </div>
  <div class="col-sm-12 col-md">
    <ul>
      <li><strong>第三页: </strong>在这选择你要设置权限的地位等级。</li>
      <br>
      <li><strong>第四页: </strong>这里显示各项权限（给你在前一页选中的地位等级），调节 <i>开</i> 或 <i>关</i>， 以给予你想要给的权限</li> 
    </ul>
  </div>
</div>  
<div class="row">
  <div class="col-sm-12 col-md">
    <img src="../../assets/images/gui/th_permissions2.png" class="img-fluid mx-auto" alt="TH GUI Permissions Tab Pg.2">
  </div>
  <div class="col-sm-12 col-md">
    <ul>
      <li><strong>Page 3: </strong>Here you can select the rank that you would like to manage.</li>
      <br>
      <li><strong>Page 4: </strong>Here are the individual permissions (for the rank you have selected on the previous page) that you can toggle <i>ON</i> or <i>OFF</i>, giving each rank the permission you want.</li> 
    </ul>
  </div>
</div>  



---

<p><strong>Permissions Pg. 5 & 6: </strong>In this section, you can add a certain block's position that will bypass the protection system for interaction. Any player will be able to interact with that block as long as their rank includes the permission 'Access Free-Blocks.'</p>

<p><strong>权限界面 第五页和第六页: </strong>在这一部分，你可以添加一个确定的方块坐标，该方块将绕过殖民地保护系统，提供给大家进行交互。只要玩家所在的地位等级包括权限“交互自由方块”，他们就可以和该方块进行交互了。</p>

<div class="row">
  <div class="col-sm-12 col-md">
    <img src="../../assets/images/gui/th_permissions3.png" class="img-fluid mx-auto" alt="TH GUI Permissions Tab Pg.3">
  </div>
  <div class="col-sm-12 col-md">
    <ul><br>
      <li><strong>Page 5: </strong>Where you enter the position (X, Y, Z) of the block that you want to make free for interaction.</li>
      <br>
      <li><strong>Page 6: </strong>Here you will see the list of block positions that you have added as free for interaction and can remove them.</li>
    </ul>
  </div>
</div>
<div class="row">
  <div class="col-sm-12 col-md">
    <img src="../../assets/images/gui/th_permissions3.png" class="img-fluid mx-auto" alt="TH GUI Permissions Tab Pg.3">
  </div>
  <div class="col-sm-12 col-md">
    <ul><br>
      <li><strong>第五页: </strong>这里键入你想要让玩家自由交互的方块的位置（X,Y,Z）。</li>
      <br>
      <li><strong>第六页: </strong>这里显示能够自由交互的方块位置列表，你可以在这里移除他们。</li>
    </ul>
  </div>
</div>


<br>
<br>

### <strong>市民: </strong>这个部分将展示你的殖民地中所有市民的名字和技能，以及技能的等级

<div class="row">
  <div class="col-sm-12 col-md">
    <img src="../../assets/images/gui/th_citizens.png" class="img-fluid mx-auto" alt="TH GUI Citizens Tab">
  </div>
  <div class="col-sm-12 col-md">
    <ul>
     <br>
      <li><strong>第一页: </strong>When you select a citizen, their stats and job will appear here. You can also recall them to the Town Hall block on this page.</li>
      <br>
      <li><strong>第二页: </strong>Here you will see a list of the citizens in your colony. Select a citizen to see their skills.</li>
    </ul>
  </div>
</div>
<div class="row">
  <div class="col-sm-12 col-md">
    <img src="../../assets/images/gui/th_citizens.png" class="img-fluid mx-auto" alt="TH GUI Citizens Tab">
  </div>
  <div class="col-sm-12 col-md">
    <ul>
     <br>
      <li><strong>第一页: </strong>当你选定一个公民后，关于他的统计信息就会出现在这一页。你也可以在这里单独将公民召集回市政厅。</li>
      <br>
      <li><strong>第二页: </strong>这你可以看到你的公民列表，选择一个公民来查看具体的技能信息。</li>
    </ul>
  </div>
</div>


<br>
<br>

### <strong>设置: </strong>这一部分是你调整市民的工作、安排殖民地住宅的地方，以及另外一些事情

<div class="row">
  <div class="col-sm-12 col-md">
    <img src="../../assets/images/gui/th_settings.png" class="img-fluid mx-auto" alt="TH GUI Settings Tab">
  </div>
  <div class="col-sm-12 col-md">
      <p><strong>第一页: </strong>There are four buttons here:</p>
        <ul>
          <li><strong>Worker hiring mode: </strong>Clicking on this button lets you switch between automatic or manual. If it's in automatic mode, you can't fire or hire any citizen from any worker hut and the best unemployed citizen will be hired for you. In manual mode you will be able to <i>hire</i> and <i>fire</i> whichever citizen you want at any time.</li>
          <br>
          <li><strong>Housing assignment mode: </strong>Clicking on this button lets you switch between automatic or manual. If it's in automatic mode, citizens will be assigned a house as soon as they spawn (if housing is available). In manual mode, you can select which citizens will be housed in each <a href="../../source/buildings/house"> House</a> or <a href="../../source/buildings/tavern"> Tavern</a>. This is better if you have a large colony and many workers spread out in a large area so you can house your citizens as close as possible to their workplace.</li>
          <br>
          <li><strong>Print help messages: </strong>Clicking on this button lets you choose whether MineColonies help messages will appear in the chat. It is recommended that this be turned on for first-time players.</li>
          <br>
          <li><strong>Kids will be born: </strong>Clicking on this button lets you choose whether new kids will be born in your colony.</li>p
        </ul>
		<br>
            <p><strong>第二页: </strong>There are two buttons here:</p>
        <ul>
            <li><strong>Pick Team Color: </strong>Whatever color you pick from here, your Guards will have a glow of this color around them when you put them in follow mode at their <a href="../../source/buildings/guardtower"> Guard Tower</a> or <a href="../../source/buildings/barrackstower"> Barracks Tower</a>. This is for the PVP system, so you know which Guards are yours when you are fighting. Your citizens' names will also be in this color.</li>
			<br>
            <li><strong>Edit Colony Flag: </strong>Clicking this button will open up a banner designer where you can design your colony banner. Your <a href="../../source/workers/guard"> Knights</a> will wear the finished design on their shields, and it is also used in some schematics.</li>
            <div class="col-sm-12 col-md">
			<img src="../../assets/images/gui/th_colonybannerdesigner.png" class="img-fluid mx-auto" alt="TH GUI Banner Designer">
			</div>
		</ul>
  </div>
</div>


<div class="row">
  <div class="col-sm-12 col-md">
    <img src="../../assets/images/gui/th_settings.png" class="img-fluid mx-auto" alt="TH GUI Settings Tab">
  </div>
  <div class="col-sm-12 col-md">
      <p><strong>第一页: </strong>这里有四个按钮:</p>
        <ul>
            <li><strong>Worker hiring mode 雇佣模式: </strong>点击这里可以切换自动与手动模式，自动模式下会为你自动选择最合适的工人，但你不可以在工作小屋中对任何市民进行解雇和雇佣。手动模式下，你可以在任何时候手动<i>雇佣</i>或<i>解雇</i>你想要的人选。</li>
          <br>
          <li><strong>Housing assignment mode 住宅安排模式: </strong>点击这个按钮可以切换自动模式与手动模式。若是选择了自动模式，那么公民只要一生成就会被分配一个住房（如果有可用的房屋的话）。若是选择了手动模式，那你就要自己决定公民是要住在哪一座<a href="../../source/buildings/house"> 住宅</a> 或 <a href="../../source/buildings/tavern"> 酒馆</a>里了。如果说你的殖民地足够大的话，那你就能将公民安排在最靠近其工作岗位的地方，这样就能让他快速上工了。</li>
          <br>
          <li><strong>Print help messages 输出教程信息: </strong>点击这个按钮可以决定是否在聊天栏里输出教程信息，建议初次游玩的玩家把它开启。</li>
          <br>
          <li><strong>Kids will be born 婴儿降生: </strong>点击这个按钮可以选择是否允许孩子出生在你的殖民地里。</li>p
        </ul>
		<br>
            <p><strong>第二页: </strong>这里有两个按钮:</p>
        <ul>
            <li><strong>Pick Team Color 选择队伍颜色: </strong>不管你选择了什么颜色，当你的士兵在<a href="../../source/buildings/guardtower"> 卫兵塔</a> 或 <a href="../../source/buildings/barrackstower"> 兵营塔</a>中设置为跟随模式时，他的身上都会散发相应颜色的光芒。这个选项是为PVP系统准备的，以此你可以知道在战斗的时候，哪些士兵是忠于你的。不仅如此，你的公民的名字也会变成相应的颜色。</li>
			<br>
            <li><strong>Edit Colony Flag 编织殖民地旗帜: </strong>点击这个按钮将会打开旗帜设计器，你可以在这里设计你的殖民地专有的旗帜。你的<a href="../../source/workers/guard"> 骑士</a>的盾牌上会刻画出你最终设计的图案。旗帜也会被用在其他的蓝图结构中。</li>
            <div class="col-sm-12 col-md">
			<img src="../../assets/images/gui/th_colonybannerdesigner.png" class="img-fluid mx-auto" alt="TH GUI Banner Designer">
			</div>
		</ul>
  </div>
</div>

<br>

<br>

### <strong>施工顺序: </strong>在这里你可以看到<a href="../../source/workers/builder">建筑工</a>的被安排的施工顺序。当且仅当最上面的任务顺利完成了，建筑工才会进行下一个任务

<div class="row">
  <div class="col-sm-12 col-md">
    <img src="../../assets/images/gui/th_workorders.png" class="img-fluid mx-auto" alt="TH GUI Work Orders Tab">
  </div>
  <div class="col-sm-12 col-md">
    <ul>
      <li><strong>第一页: </strong>Blank page except for the header (future use).</li>
      <br>
      <li><strong>第二页: </strong>Here are all the build orders for this colony (including decorations and your own schematics as well as huts). Your Builders will complete the builds from top to bottom, and you can change the priority of the builds by moving them up or down in the list. You can also delete work orders. When you delete a work order that is currently being built, the Builder will stop building and will continue where they left off if you create the work order again.</li>
    </ul>
  </div>
</div>

<div class="row">
  <div class="col-sm-12 col-md">
    <img src="../../assets/images/gui/th_workorders.png" class="img-fluid mx-auto" alt="TH GUI Work Orders Tab">
  </div>
  <div class="col-sm-12 col-md">
    <ul>
      <li><strong>第一页: </strong>仅显示了标题的空白页码，留作备用。</li>
      <br>
      <li><strong>第二页: </strong>这里是殖民地所有的施工任务的列表（包括装饰，你的自定义蓝图以及各种小屋），你的工人将会按照从上往下的顺序进行建造，你可以通过拖拽来改变建造的先后。你也可以对施工任务进行撤销。当你撤销正在进行的施工任务后，你的工人将会中止建筑，若是你再次安排该任务，那么工人就会在旧址继续进行建造。</li>
    </ul>
  </div>
</div>

<br>
<br>

### <strong>幸福: </strong>这一部分显示你的殖民地的总体幸福度，以此你可以看到哪些地方需要多加关注以提升幸福水平

<div class="row">
  <div class="col-sm-12 col-md">
    <img src="../../assets/images/gui/th_happiness.png" class="img-fluid mx-auto" alt="TH GUI Work Orders Tab">
  </div>
  <div class="col-sm-12 col-md">
    <ul>
      <br>
      <li><strong>第一页: </strong>The happiness indices. You can keep track of the areas that will lower or raise the happiness of your citizens here. The colors, in order from best to worst, are: green (positive), blue (neutral), yellow (slightly negative), and red (negative). There's also black, which will show up if something went wrong.</li>
      <br>
      <li><strong>第二页: </strong>Blank for now (future use).</li>
    </ul>
  </div>
</div>  
<div class="row">
  <div class="col-sm-12 col-md">
    <img src="../../assets/images/gui/th_happiness.png" class="img-fluid mx-auto" alt="TH GUI Work Orders Tab">
  </div>
  <div class="col-sm-12 col-md">
    <ul>
      <br>
      <li><strong>第一页: </strong>幸福度的指标。你可以在这里查看哪些东西会影响公民的幸福度。关于颜色（由好到坏）：绿色（积极）、蓝色（素净）、黄色（沉闷）、红色（消极）。除此之外，还有黑色，显示的时候代表某事出现问题了。</li>
      <br>
      <li><strong>第二页: </strong>空白，留作备用</li>
    </ul>
  </div>
</div>  


<br>
