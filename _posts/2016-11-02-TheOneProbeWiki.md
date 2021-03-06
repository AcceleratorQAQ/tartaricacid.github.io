---
layout: post
title: The One Probe 教程文案
tags: [wiki]
description: >
  The One Probe 是由McJty制作的一个在MC中实时信息高亮的模组
---


## 1. 作者简介  

一个做MC模组的老油条，据说连他儿子`(what？我离有儿子还差一个女朋友)`都在做模组，详情可以戳他本人的 [GitHub](https://github.com/McJty)，有什么情况还可以关注他的[推特](https://twitter.com/McJty)。

![McJty](https://github.com/TartaricAcid/Some-mods-wiki/blob/master/TheOneProbe/picture/McJty.png?raw=true)

### 代表作  

* #### 模组
  * [RFTools](https://minecraft.curseforge.com/projects/rftools)
  * [RFTools Control](https://minecraft.curseforge.com/projects/rftools-control)
  * [RFTools Dimensions](https://minecraft.curseforge.com/projects/rftools-dimensions)
  * [Immersive Craft](https://minecraft.curseforge.com/projects/immersive-craft)（请大声告诉我这东西怎么翻译）
  * [Deep Resonance](https://minecraft.curseforge.com/projects/deep-resonance)
  * [Elemental Dimensions](https://minecraft.curseforge.com/projects/elemental-dimensions)
  * [The One Probe](https://minecraft.curseforge.com/projects/the-one-probe)
  * [Combat Help](https://minecraft.curseforge.com/projects/combathelp)
  * [Gear Swapper](https://minecraft.curseforge.com/projects/gear-swapper)

* #### 整合包
  * [On The Edge](https://minecraft.curseforge.com/projects/on-the-edge)  （1.7.10的整合）
  * [McJty's Lets Play Pack](https://minecraft.curseforge.com/projects/mcjtys-lets-play-pack)  （1.9.4的整合）
  * [McJty's Lets Play, Episode 10](https://minecraft.curseforge.com/projects/mcjtys-lets-play-episode-10)  （1.9.4的整合）

* #### 视频实况
  * 傻了吧，爷还会做[实况](https://www.youtube.com/channel/UCYMg1JQw3syJBgPeW6m68lA)。

* #### 模组开发教程
  * [戳这里](https://github.com/McJty/ModTutorials)

* #### 特点
  * 质量优良，更新速度快，GUI制作精良
  * 严重缺乏本地化：[详情请戳这里](https://github.com/McJty/RFTools/issues/744#)
  * 严重缺乏本地化
  * 严重缺乏本地化，重要的事情说三遍


## 2. The One Probe说明

The One Probe简称TOP，是一个类似于Waila的模组，但是其信息显示必须要持有相关物品才能显示，最开始时候还错误百出，现在经过McJty的改良，已经成为一个很精良的模组。其拥有极佳的可视化界面，并且对EIO和作者自己本身的一堆mod都有极佳的兼容性，甚至EIO的玄钢头盔还可以直接在铁砧中附加上TOP的检测器  

![1](https://github.com/TartaricAcid/Some-mods-wiki/blob/master/TheOneProbe/picture/2016-10-31_12.42.01.png?raw=true)  
【图中显示了EIO和TOP的兼容】

接下来几张图说明了EIO以及McJty的其他模组对TOP的兼容  

![1](https://github.com/TartaricAcid/Some-mods-wiki/blob/master/TheOneProbe/picture/2016-10-31_12.32.24.png?raw=true)  
【图中显示了Deep Resonance共振水晶的属性】  

![1](https://github.com/TartaricAcid/Some-mods-wiki/blob/master/TheOneProbe/picture/2016-10-31_12.32.32.png?raw=true)  
【图中显示了草方块的正确采掘工具，采掘等级以及当前是否能采掘信息】  

![1](https://github.com/TartaricAcid/Some-mods-wiki/blob/master/TheOneProbe/picture/2016-10-31_12.33.48.png?raw=true)  
【图中摁下shift键显示了更多的箱子信息，注意里面相同的东西并没有自动合并，这一条可以在配置文件中更改而使其更加整齐】  

![1](https://github.com/TartaricAcid/Some-mods-wiki/blob/master/TheOneProbe/picture/2016-10-31_12.40.53.png?raw=true)  
【图中显示了拉杆的开关状态】  

![1](https://github.com/TartaricAcid/Some-mods-wiki/blob/master/TheOneProbe/picture/2016-10-31_12.41.03.png?raw=true)  
【图中显示了当前的红石信号强度】  

![1](https://github.com/TartaricAcid/Some-mods-wiki/blob/master/TheOneProbe/picture/2016-10-31_12.39.37.png?raw=true)  
【图中显示了RF工具的音序器的详细信息，甚至连音序器的内部音序图都显示了出来，非常方便玩家调试】  

![1](https://github.com/TartaricAcid/Some-mods-wiki/blob/master/TheOneProbe/picture/2016-10-31_12.42.13.png?raw=true)  
【图中显示了检测器的几种合成方式，利用这个合成方式，玩家可以不需手持检测器，只需要带上这些头盔就能看到信息高亮显示】


## 3. The One Probe 的指令

The One Probe提供了几条指令用于方便玩家调整信息框的位置，这样玩家不需要对config文件或者调节具体的数字就能达到想要的效果  

#### 总计有18条指令  

  |指令|效果|  
  |:--------|:-------:|
  |topcfg center/centerleft/centerright | 将信息框显示在屏幕 正中间/中左侧/中右侧 |  
  |topcfg topleft/topcenter/topright | 将信息框显示在屏幕 顶中间/顶左侧/顶右侧 |  
  |topcfg bottomleft/bottomcenter/bottomright | 将信息框显示在屏幕 底中间/底左侧/底右侧 |
  |topcfg transparent | 将信息框背景显示为透明的 |
  |topcfg setpos [int] [int] [int] [int] | 将信息框设置为指定数字大小 |
  |topcfg opaque | 将信息框设置为不透明背景 |
  |topcfg defult | 将信息框设置为默认颜色 |
  |topcfg liquids/noliquids | 打开/关闭 液体显示 |
  |topcfg compactequalstacks/dontcompactequalstacks | 打开/关闭 箱子物品显示的自动合并 |
  |topcfg extendedinmain/defaultinmain | 打开/关闭 显示更多信息功能 |


## 4. The One Probe Addon 的说明  

 The One Probe仍然缺乏对很多mod的支持，所以有个叫做DrMathiasDJ的作者做了一个叫做[TOP Addon](https://minecraft.curseforge.com/projects/top-addons)的模组，主要增加了对以下mod的支持与修改  
 
* Forge
  * 拥有FluidHandler的方块，显示其容积
* Forestry
  * 修正林业所有带GUI的方块的错误显示
  * 显示蜂箱和蜂房的养蜂进度
  * 喷水器和多方块农场的信息显示
  * 显示果树的成熟度以及树叶是否被受过粉（必须穿戴眼镜或者养蜂员帽子）
  * 养蜂员帽子以及眼镜可以附加检测器
* Tinkers' Construct
  * 按住Shift键指向冶炼炉控制器，可以显示冶炼炉内液体
  * 显示铸造台和铸造盆的进度
* Blood Magic: Alchemical Wizardry
  * 显示祭坛的等级和其中源质的数量（必须玩家手持见解印记或者占卜印记）
  * 显示祭坛合成进度（玩家必须手持见解印记）
  * 显示熏香祭坛的静谧数值和效益数值（必须玩家手持见解印记或者占卜印记）
  * 显示路由节点的过滤设置
* Storage Drawers
  * 显示更加详细的物品数量显示
  * 显示容量上限
* IndustrialCraft 2
  * 显示大多数设备的存储的EU
  * 显示大多数设备的工作进度
  * 显示相连接的传送器
  * 热量显示
  * 地形转换模板显示
* 其他  
  * 检测器可以附加在多个mod的头盔上面
    * Botania：可以附加在魔钢头盔，源制钢头盔，泰拉钢头盔以及魔源头蓬上面
    * Forestry：可以附加在眼镜，养蜂员帽子上面
    * Blood Magic ：可以附加在束灵头盔和感知头盔上面
    * IC²：可以附加在量子头盔，纳米头盔，以及防化服帽子上面


## 5.The One Probe 配置文件翻译说明

```javascript
# Configuration file

##########################################################################################################
# client
#--------------------------------------------------------------------------------------------------------#
# Client-side settings
# 客户端配置
##########################################################################################################

client {
    # Color of the border of the box (0 to disable) [default: ff999999]
    # 高亮显示框的边框颜色（设置为0将不显示边框）
    S:boxBorderColor=ff999999
    I:boxBottomY=-1

    # Color of the box (0 to disable) [default: 55006699]
    # 高亮显示框的背景色（设置为0将不显示边框）
    S:boxFillColor=55006699
    I:boxLeftX=-1
    I:boxRightX=-1

    # Thickness of the border of the box (0 to disable) [range: 0 ~ 20, default: 2]
    # 高亮显示框的边框线宽（设置为0将不显示边框）
    I:boxThickness=2
    I:boxTopY=5

    # If true equal stacks will be compacted in the chest contents overlay [default: true]
    # 如果设置为true，指向箱子时候，会自动显示合并相同物品
    B:compactEqualStacks=false

    # If true the probe will automatically show extended information if it is in your main hand (so not required to sneak) [default: false]
    # 如果设置为true，只要玩家主手有检测器，就会始终显示拓展信息（所以玩家并不需要摁下shift键来显示拓展信息）
    B:extendedInMain=false

    # If true then the probe hotkey must be held down to show the tooltip [default: false]
    # 如果设置为true，只有按下指定快捷键才能显示文本信息
    B:holdKeyToMakeVisible=false

    # Toggle default probe visibility (client can override) [default: true]
    # 是否默认显示高亮信息（客户端可覆盖）
    B:isVisible=true

    # If true show liquid information when the probe hits liquid first [default: false]
    # 是否显示流体信息
    B:showLiquids=false

    # The scale of the tooltips, 1 is default, 2 is smaller [range: 0.4 ~ 5.0, default: 1.0]
    # 文本信息的显示比例，1是默认大小，2是小比例，【范围：0.4～5.0】
    S:tooltipScale=1.0
}


##########################################################################################################
# providers
#--------------------------------------------------------------------------------------------------------#
# Provider configuration
# 源设置
##########################################################################################################

providers {
    # Entity providers that should be excluded [default: ]
    # 实体源黑名单
    S:excludedEntityProviders <
     >

    # Providers that should be excluded [default: ]
    # 源黑名单
    S:excludedProviders <
     >

    # Order in which entity providers should be used [default: [theoneprobe:entity.default], [theoneprobe:entity.debug], [theoneprobe:entity.entity]]
    # 哪些实体源可以被使用
    S:sortedEntityProviders <
        theoneprobe:entity.default
        theoneprobe:entity.debug
        theoneprobe:entity.entity
     >

    # Order in which providers should be used [default: [theoneprobe:default], [theoneprobe:debug], [theoneprobe:block], [mcjtylib:default], [enderio:default]]
    # 定义哪些源应该被使用
    S:sortedProviders <
        theoneprobe:default
        theoneprobe:debug
        theoneprobe:block
     >
}


##########################################################################################################
# theoneprobe
#--------------------------------------------------------------------------------------------------------#
# The One Probe configuration
# 服务端配置
##########################################################################################################

theoneprobe {
    # If true equal stacks will be compacted in the chest contents overlay [default: true]
    # 如果设置为true，指向箱子时候，会自动显示合并相同物品
    B:compactEqualStacks=true

    # If true the probe will automatically show extended information if it is in your main hand (so not required to sneak) [default: false]
    # 如果设置为true，只要玩家主手有检测器，就会始终显示拓展信息（所以玩家并不需要摁下shift键来显示拓展信息）
    B:extendedInMain=false

    # How much time (ms) to wait before reporting an exception again [range: 1 ~ 10000000, default: 20000]
    # 抛出错误之前的等待响应时间（毫秒）
    I:loggingThrowableTimeout=20000

    # Is the probe needed to show the tooltip? 0 = no, 1 = yes, 2 = yes and clients cannot override [range: 0 ~ 2, default: 1]
    # 检测器是否能显示文本信息？0=不可以，1=可以，2=可以并且客户端不能覆盖服务端
    I:needsProbe=1

    # Distance at which the probe works [range: 0.1 ~ 200.0, default: 6.0]
    # 检测器的工作距离【范围：0.1～200.0】
    S:probeDistance=6.0

    # The amount of milliseconds to wait before showing a 'fetch from server' info on the client (if the server is slow to respond) (-1 to disable this feature) [range: -1 ~ 100000, default: 500]
    # 在客户端显示“正在读取服务器”之前的等待时间（毫秒）（如果服务器响应速度很慢）（填写-1表示禁止这个功能）【范围：-1～100000】
    I:renderTimeout=500

    # Format for displaying RF: 0 = full, 1 = compact, 2 = comma separated [range: 0 ~ 2, default: 1]
    # RF能量的显示格式：0=全显示模式，1=缩写模式，2=逗号分隔模式
    I:rfFormat=1

    # Alternate color for the RF bar [default: ff430000]
    # RF能量条的背景色
    S:rfbarAlternateFilledColor=ff430000

    # Color for the RF bar border [default: ff555555]
    # RF能量条的边线颜色
    S:rfbarBorderColor=ff555555

    # Color for the RF bar [default: ffdd0000]
    # RF能量条的颜色
    S:rfbarFilledColor=ffdd0000

    # Show if the block can be harvested (0 = not, 1 = always, 2 = sneak) [range: 0 ~ 2, default: 1]
    # 是否显示方块可被采掘信息（0=不显示，1=显示，2=摁下shift键显示）
    I:showCanBeHarvested=1

    # Show chest contents (0 = not, 1 = always, 2 = sneak) [range: 0 ~ 2, default: 2]
    # 是否显示箱子的内部物品
    I:showChestContents=2

    # Show the growth level of crops (0 = not, 1 = always, 2 = sneak) [range: 0 ~ 2, default: 1]
    # 是否显示作物的生长情况
    I:showCropPercentage=1

    # If true show debug info with creative probe [default: true]
    # 设置为true，用创造模式检测器会显示调试信息
    B:showDebugInfo=true

    # Show harvest level (0 = not, 1 = always, 2 = sneak) [range: 0 ~ 2, default: 1]
    # 是否显示采掘等级（0=不显示，1=显示，2=摁下shift键显示）
    I:showHarvestLevel=1

    # Show lever setting (0 = not, 1 = always, 2 = sneak) [range: 0 ~ 2, default: 1]
    # 显示工具设置（0=不显示，1=显示，2=摁下shift键显示）
    I:showLeverSetting=1

    # Show mob health (0 = not, 1 = always, 2 = sneak) [range: 0 ~ 2, default: 1]
    # 显示生物血量值（0=不显示，1=显示，2=摁下shift键显示）
    I:showMobHealth=1

    # Show mob potion effects (0 = not, 1 = always, 2 = sneak) [range: 0 ~ 2, default: 2]
    # 显示生物所受到的药水效果（0=不显示，1=显示，2=摁下shift键显示）
    I:showMobPotionEffects=2

    # Show mod name (0 = not, 1 = always, 2 = sneak) [range: 0 ~ 2, default: 1]
    # 显示生物名字（0=不显示，1=显示，2=摁下shift键显示）
    I:showModName=1

    # How to display RF: 0 = do not show, 1 = show in a bar, 2 = show as text [range: 0 ~ 2, default: 1]
    # 如何显示RF：0=不显示，1=用能量条形式显示，2=用文字形式显示
    I:showRF=1

    # Show redstone (0 = not, 1 = always, 2 = sneak) [range: 0 ~ 2, default: 1]
    # 是否显示红石信号（0=不显示，1=显示，2=摁下shift键显示）
    I:showRedstone=1

    # How to display tank contents: 0 = do not show, 1 = show in a bar, 2 = show as text [range: 0 ~ 2, default: 1]
    # 是否显示容量槽：0=不显示，1=用能量条形式显示，2=用文字形式显示
    I:showTank=1

    # Format for displaying tank contents: 0 = full, 1 = compact, 2 = comma separated [range: 0 ~ 2, default: 1]
    # 容量槽的显示格式：0=全显示模式，1=缩写模式，2=逗号分隔模式
    I:tankFormat=1

    # Alternate color for the tank bar [default: ff000043]
    # 容量槽的背景色
    S:tankbarAlternateFilledColor=ff000043

    # Color for the tank bar border [default: ff555555]
    # 容量槽的边线颜色
    S:tankbarBorderColor=ff555555

    # Color for the tank bar [default: ff0000dd]
    # 容量槽的颜色
    S:tankbarFilledColor=ff0000dd

    # The amount of milliseconds to wait before updating probe information from the server [range: 10 ~ 100000, default: 200]
    # 服务端和客户端数据同步的时间间隔（毫秒）【范围：10～100000】
    I:timeout=200
}

```
