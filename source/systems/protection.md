---
title: Colony Protection System
layout: default
---
# 殖民地保护系统

我们的殖民地保护机制 （当 [市政厅](../../source/buildings/townhall) 被放置的时候就开启了） 可以在config文件里被设置。

保护机制包括开启殖民地爆炸保护（默认开启），因此苦力怕、TNT以及任何爆炸性的模组方块都不能破坏你的殖民地。默认设置只有殖民地的所有者可以在殖民地中破坏或者放置方块， 但是你可以在市政厅GUI中添加玩家许可。

该机制覆盖着Y = 0到Y = 256的范围，因此你不必担心任何从基岩到天空高度限制的恶意破坏。

**注释：** 殖民地保护系统依赖于殖民地边界系统。只有在殖民地边界内的区域会受到保护。查看[殖民地边界系统](../../source/systems/border) 获取更多信息。


### Config 文件选项

```
# 是否开启殖民地保护机制？
B:enableColonyProtection=true
```

```
# 该项独立于上述殖民地保护机制的设置，是否在殖民地内开启爆炸保护？
B:turnOffExplosionsInColonies=true
```

```
# 是否禁止玩家在现有的原版村庄上建立殖民地？
B:protectVillages=true
```
