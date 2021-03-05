---
title: Command System
layout: default
---
# 命令系统


命令系统现在可以用了。大多数命令要求有OP权限，单人游戏要开启允许作弊。

- [命令](#命令)
  - [基础命令](#基础命令)
  - [殖民地命令](#殖民地命令)
  - [市民命令](#市民命令)
  - [Kill 命令](#kill-命令)

**命令语法**

|      这个标识       |       指的是       |
| :-----------------: | :----------------: |
|     `plaintext`     |    按照给的输入    |
| `<angle brackets>`  | **必要**输入的参数 |
| `[square brackets]` | **可选**输入的参数 |
|     `x | y | z`     |  选择其中一个输入  |

## 基础命令

/minecolonies (or /mc)  `<backup | help | home | raid-all-now | raid-all-tonight | resetsupplies | rtp | wheremai | whoami | citizens | colony | kill>`

<table class="table">
  <thead>
    <tr>
      <th class="w-50">命令</th>
      <th class="d-none d-lg-table-cell w-50">命令描述</th>
    </tr>
  </thead>
  <tbody>
    <tr class="d-block d-lg-table-row">
      <td class="d-block d-lg-table-cell"><code>/mc backup</code><br>默认权限等级：OP<br></td>
      <td class="d-block d-lg-table-cell">备份所有殖民地数据</td>
    </tr>
    <tr class="d-block d-lg-table-row">
      <td class="d-block d-lg-table-cell"><code>/mc help</code><br>默认权限等级：所有人<br></td>
      <td class="d-block d-lg-table-cell">在聊天栏中列出wiki和<a href="https://discord.minecolonies.com">Discord</a>的链接</td>
    </tr>
    <tr class="d-block d-lg-table-row">
      <td class="d-block d-lg-table-cell"><code>/mc home</code><br>默认权限等级：所有人</td>
      <td class="d-block d-lg-table-cell">将殖民地主人传送回他们的殖民地的 <a href="../../source/buildings/townhall">市政厅</a>.</td>
    </tr>
    <tr class="d-block d-lg-table-row">
      <td class="d-block d-lg-table-cell"><code>/mc raid-All-now</code><br>默认权限等级：OP</td>
      <td class="d-block d-lg-table-cell">马上给所有殖民地安排一场袭击</td>
    </tr>
    <tr class="d-block d-lg-table-row">
      <td class="d-block d-lg-table-cell"><code>/mc raid-All-tonight</code><br>默认权限等级：OP</td>
      <td class="d-block d-lg-table-cell">给所有殖民地安排一场夜幕降临开始的袭击</td>
    </tr>
    <tr class="d-block d-lg-table-row">
      <td class="d-block d-lg-table-cell"><code>/mc resetsupplies &lt;online player's username&gt;</code><br>默认权限等级：OP</td>
      <td class="d-block d-lg-table-cell">重设能够放置放置补给船或补给营地的机会</td>
    </tr>
    <tr class="d-block d-lg-table-row">
      <td class="d-block d-lg-table-cell"><code>/mc rtp</code><br>默认权限等级：所有人</td>
      <td class="d-block d-lg-table-cell">随机传送。 将会把你传送到其他人殖民地外的某个地方</td>
    </tr>
    <tr class="d-block d-lg-table-row">
      <td class="d-block d-lg-table-cell"><code>/mc whereami</code><br>默认权限等级：所有人</td>
      <td class="d-block d-lg-table-cell">将输出周围有没有殖民地，如果有，则会输出玩家与最近的殖民地距离多远</td>
    </tr>
    <tr class="d-block d-lg-table-row">
      <td class="d-block d-lg-table-cell"><code>/mc whoami</code><br>默认权限等级：OP</td>
      <td class="d-block d-lg-table-cell">将输出你的名字，殖民地的名字和殖民地中心点的坐标</td>
    </tr>
  </tbody>
</table>

## 殖民地命令

/minecolonies (or /mc) colony  `<addOfficer | canSpawnRaiders | claim | delete | home | info | list | loadAllColoniesFromBackup | loadBackup | raid-now | raid-tonight | requestsystem-reset | requestsystem-reset-all | setAbandoned | setDeleteable | setowner | teleport>`

<table class="table">
  <thead>
    <tr>
      <th class="w-50">Command</th>
      <th class="d-none d-md-table-cell w-50">命令描述</th>
    </tr>
  </thead>
  <tbody>
    <tr class="d-block d-md-table-row">
      <td class="d-block d-md-table-cell"><code>/mc colony addOfficer &lt;colony id&gt; &lt;online player's username&gt;</code><br>默认权限等级：所有人</td>
      <td class="d-block d-md-table-cell">为殖民地添加一名长官。长官这一地位等级的详细信息见A<a href="../../source/buildings/townhall">市政厅</a> 一页关于GUI的权限部分。<br>例：<br><code>/mc colony addofficer 1 Steve</code></td>
    </tr>
    <tr class="d-block d-md-table-row">
      <td class="d-block d-md-table-cell"><code>/mc colony canSpawnRaiders &lt;colony id&gt; &lt;canSpawn&gt;</code><br>默认权限等级：OP</td>
      <td class="d-block d-md-table-cell">添加或者移除殖民地生成入侵者的规则。<br>例：<br><code>/mc colony canSpawnRaiders 1 true</code></td>
    </tr>
    <tr class="d-block d-md-table-row">
      <td class="d-block d-md-table-cell"><code>/mc colony claim &lt;colony id&gt; &lt;[number in chunks] [true | false]</code><br>默认权限等级：OP</td>
      <td class="d-block d-md-table-cell">以玩家位置为基准点，为殖民地宣称一定数量的区块（或者移除宣传区块）。<br>例：<br><code>/mc colony claim 1 8 true</code></td>
    </tr>
    <tr class="d-block d-md-table-row">
      <td class="d-block d-md-table-cell"><code>/mc colony delete &lt;colony id&gt; [delete Buildings]</code><br>默认权限等级：所有人</td>
      <td class="d-block d-md-table-cell">删除指定殖民地及其所有殖民地建筑（建筑指的是只要小屋方块还在）。<br>例：<br><code>/mc colony delete 1 false keep buildings</code><br><code>/mc colony delete 1 true delete buildings</code></td>
    </tr>
    <tr class="d-block d-md-table-row">
      <td class="d-block d-md-table-cell"><code>/mc colony home</code><br>默认权限等级：所有人</td>
      <td class="d-block d-md-table-cell">将殖民地的拥有者传送回<a href="../../source/buildings/townhall">市政厅</a>。<br>例：<br><code>/mc colony home</code></td>
    </tr>
    <tr class="d-block d-md-table-row">
      <td class="d-block d-md-table-cell"><code>/mc colony info &lt;[colony id]&gt;</code><br>默认权限等级：所有人</td>
      <td class="d-block d-md-table-cell">显示指定殖民地的基础信息(ID，名称，市长，市民，坐标，与玩家的最后交互，殖民地是否可以删除)。<br>例：<br><code>/mc colony info 1</code></td>
    </tr>
    <tr class="d-block d-md-table-row">
      <td class="d-block d-md-table-cell"><code>/mc colony list &lt;[startpage]&gt;</code><br>默认权限等级：所有人</td>
      <td class="d-block d-md-table-cell">显示地图中所有殖民地列表，包括殖民地ID、名称以及坐标。<br>例：<br><code>/mc colony list</code></td>
    </tr>
    <tr class="d-block d-md-table-row">
      <td class="d-block d-md-table-cell"><code>/mc colony loadAllColoniesFromBackup</code><br>默认权限等级：OP</td>
      <td class="d-block d-md-table-cell">从备份文件中加载所有殖民地。<br>例：<br><code>/mc colony loadAllColoniesFromBackup</code></td>
    </tr>
    <tr class="d-block d-md-table-row">
      <td class="d-block d-md-table-cell"><code>/mc colony loadBackup &lt;[colony id]&gt;</code><br>默认权限等级：OP</td>
      <td class="d-block d-md-table-cell">从备份文件中加载指定的殖民地。<br>例：<br><code>/mc colony loadBackup 1</code></td>
    </tr>
    <tr class="d-block d-md-table-row">
      <td class="d-block d-md-table-cell"><code>/mc colony raid-now &lt;colony id&gt;</code><br>默认权限等级：OP</td>
      <td class="d-block d-md-table-cell">为指定殖民地安排一个野蛮人入侵事件，事件立即发生。<br>例：<br><code>/mc colony raid-now 1</code></td>
    </tr>
    <tr class="d-block d-md-table-row">
      <td class="d-block d-md-table-cell"><code>/mc colony raid-tonight &lt;colony id&gt;</code><br>默认权限等级：OP</td>
      <td class="d-block d-md-table-cell">为指定殖民地安排一个野蛮人入侵事件，在下一个夜晚事件发生。<br>例：<br><code>/mc colony raid-tonight 1</code></td>
    </tr>
    <tr class="d-block d-md-table-row">
      <td class="d-block d-md-table-cell"><code>/mc colony requestsystem-reset &lt;[colony id]&gt;</code><br>默认权限等级：所有人</td>
      <td class="d-block d-md-table-cell">更新指定殖民地的要求系统，让该殖民地所有工人重新提交要求。<br>例：<br><code>/mc colony requestsystem-reset 1</code></td>
    </tr>
    <tr class="d-block d-md-table-row">
      <td class="d-block d-md-table-cell"><code>/mc colony requestsystem-reset-all</code><br>默认权限等级：OP</td>
      <td class="d-block d-md-table-cell">更新所有殖民地的要求系统，让所有殖民地中的所有工人重新提交要求。<br>例：<br><code>/mc colony requestsystem-reset-all</code></td>
    </tr>
    <tr class="d-block d-md-table-row">
      <td class="d-block d-md-table-cell"><code>/mc colony setAbandoned &lt;colony id&gt;</code><br>默认权限等级：所有人</td>
      <td class="d-block d-md-table-cell">设置是否将该殖民地遗弃，不再有市长。<br>例：<br><code>/mc colony setAbandoned 1</code></td>
    </tr>
    <tr class="d-block d-md-table-row">
      <td class="d-block d-md-table-cell"><code>/mc colony setDeletable &lt;colony id&gt; &lt;deleteable&gt;</code><br>默认权限等级：OP</td>
      <td class="d-block d-md-table-cell">Sets whether a colony can be marked for auto-deletion or not.<br>例：<br><code>/mc colony setDeletable 1 false</code></td>
    </tr>
    <tr class="d-block d-md-table-row">
      <td class="d-block d-md-table-cell"><code>/mc colony setowner &lt;colony id&gt; &lt;online-player's username&gt;</code><br>默认权限等级：所有人</td>
      <td class="d-block d-md-table-cell">更改殖民地的所有者<br>例：<br><code>/mc colony setowner 1 Steve</code></td>
    </tr>
    <tr class="d-block d-md-table-row">
      <td class="d-block d-md-table-cell"><code>/mc colony teleport &lt;colony id&gt;</code><br>默认权限等级：所有人</td>
      <td class="d-block d-md-table-cell">将玩家传送到指定的殖民地<br>例：<br><code>/mc colony teleport 1</code></td>
    </tr>
  </tbody>
</table>


## 市民命令

/minecolonies (or /mc) citizens `<info | kill | list | reload | spawnNew | teleport | walk>`

<table class="table">
  <thead>
    <tr>
      <th class="w-50">命令</th>
      <th class="d-none d-md-table-cell w-50">命令描述</th>
    </tr>
  </thead>
  <tbody>
    <tr class="d-block d-md-table-row">
      <td class="d-block d-md-table-cell"><code>/mc citizens info &lt;colony id&gt; &lt;citizen id&gt;</code><br>默认权限等级：所有人</td>
      <td class="d-block d-md-table-cell">显示殖民地中指定的市民的基本信息，比如ID和名字<br>例：<br><code>/mc citizens info 1 1</code></td>
    </tr>
    <tr class="d-block d-md-table-row">
      <td class="d-block d-md-table-cell"><code>/mc citizens kill &lt;colony id&gt; &lt;citizen id&gt;</code><br>默认权限等级：所有人</td>
      <td class="d-block d-md-table-cell">杀死殖民地中指定的市民.<br>例：<br><code>/mc citizens kill 1 1</code></td>
    </tr>
    <tr class="d-block d-md-table-row">
      <td class="d-block d-md-table-cell"><code>/mc citizens list &lt;colony id&gt; [page number]</code><br>默认权限等级：所有人</td>
      <td class="d-block d-md-table-cell">列出一个殖民地中所有市民的ID和名字 (每一页9项记录).<br>Examples:<br><code>/mc citizens list 1</code><br><code>/mc citizens list 1 3</code></td>
    </tr>
    <tr class="d-block d-md-table-row">
      <td class="d-block d-md-table-cell"><code>/mc citizens reload &lt;colony id&gt; &lt;citizen id&gt;</code><br>默认权限等级：所有人</td>
      <td class="d-block d-md-table-cell">重新加载在殖民地中指定的市民<br>例：<br><code>/mc citizens reload 1 1</code></td>
    </tr>
    <tr class="d-block d-md-table-row">
      <td class="d-block d-md-table-cell"><code>/mc citizens spawnNew &lt;colony id&gt;</code><br>默认权限等级：所有人</td>
      <td class="d-block d-md-table-cell">在殖民地中生成一个新的市民<br>例：<br><code>/mc citizens spawnNew 1</code></td>
    </tr>
    <tr class="d-block d-md-table-row">
      <td class="d-block d-md-table-cell"><code>/mc citizens teleport &lt;colony id&gt; &lt;citizen id&gt;&lt;location (x y z)&gt;</code><br>默认权限等级：所有人</td>
      <td class="d-block d-md-table-cell">将指定的市民传送到给定的位置<br>例：<br><code>/mc citizens teleport 1 1 -50 62 128</code></td>
    </tr>
    <tr class="d-block d-md-table-row">
      <td class="d-block d-md-table-cell"><code>/mc citizens walk &lt;colony id&gt; &lt;citizen id&gt;&lt;location (x y z)&gt;</code><br>默认权限等级：所有人</td>
      <td class="d-block d-md-table-cell">命令指定的市民走到给定的位置<br>例：<br><code>/mc citizens walk 1 1 -50 62 128</code></td>
    </tr>
  </tbody>
</table>

## Kill 命令

/minecolonies kill `<raider | animals | monster | chicken | cow | pig | sheep>`

<table class="table">
  <thead>
    <tr>
      <th class="w-50">命令</th>
      <th class="d-none d-md-table-cell w-50">命令描述</th>
    </tr>
  </thead>
  <tbody>
    <tr class="d-block d-md-table-row">
      <td class="d-block d-md-table-cell"><code>/mc kill raider</code><br>默认权限等级：OP</td>
      <td class="d-block d-md-table-cell">在所有殖民地里杀死全部的袭击者 (barbarians, pirates, vikings, or egyptian raiders).<br>例：<br><code>/mc kill raider</code></td>
    </tr>
    <tr class="d-block d-md-table-row">
      <td class="d-block d-md-table-cell"><code>/mc kill animals</code><br>默认权限等级：OP</td>
      <td class="d-block d-md-table-cell">在所有殖民地里杀死全部的动物 (和平型生物).<br>例：<br><code>/mc kill animals</code></td>
    </tr>
    <tr class="d-block d-md-table-row">
      <td class="d-block d-md-table-cell"><code>/mc kill monster</code><br>默认权限等级：OP</td>
      <td class="d-block d-md-table-cell">在所有殖民地里杀死全部的怪物 (敌对生物).<br>例：<br><code>/mc kill monster</code></td>
    </tr>
    <tr class="d-block d-md-table-row">
      <td class="d-block d-md-table-cell"><code>/mc kill chicken</code><br>默认权限等级：OP</td>
      <td class="d-block d-md-table-cell">在所有殖民地里杀死全部的鸡.<br>例：<br><code>/mc kill chicken</code></td>
    </tr>
    <tr class="d-block d-md-table-row">
      <td class="d-block d-md-table-cell"><code>/mc kill cow</code><br>默认权限等级：OP</td>
      <td class="d-block d-md-table-cell">在所有殖民地里杀死全部的牛.<br>例：<br><code>/mc kill cow</code></td>
    </tr>
    <tr class="d-block d-md-table-row">
      <td class="d-block d-md-table-cell"><code>/mc kill pig</code><br>默认权限等级：OP</td>
      <td class="d-block d-md-table-cell">在所有殖民地里杀死全部的猪.<br>例：<br><code>/mc kill pig</code></td>
    </tr>
    <tr class="d-block d-md-table-row">
      <td class="d-block d-md-table-cell"><code>/mc kill sheep</code><br>默认权限等级：OP</td>
      <td class="d-block d-md-table-cell">在所有殖民地里杀死全部的羊.<br>例：<br><code>/mc kill sheep</code></td>
    </tr>
  </tbody>
</table>
