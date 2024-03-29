---
{"dg-publish":true,"permalink":"/学习笔记/虚幻/0.5.资产处理相关/","dgPassFrontmatter":true}
---

> [!tip] [[学习笔记/虚幻/基础认知阶段\|基础认知阶段目录]]

我们在网络寻找或者购买的资产有一些使用率较高的格式。这些格式在导入 UE时各有作用和优势。我们需要对格式有一定的认知（[[杂/模型格式介绍\|模型格式介绍]]）。在课程里面主要使用 FBX，ABC，OBJ。

> [!NOTE]- 常见资产的格式
> FBX
>> **FBX**（Filmbox）是 Autodesk 公司于1996年开发的一种专有文件格式，最早用于其建模和动画软件 Filmbox。随后，FBX 逐渐成为业界的标准格式，并在各种三维应用中得到广泛应用，需要注意的是，尽管 FBX 在3D 软件开发中占据了主导地位，但 FBX 是一种专有格式，其规范由 Autodesk 控制，并需要使用 Autodesk 提供的 SDK 进行解析和操作，不过对于我们无需担心，因为几乎所有的3D 引擎都已经自带了 FBX 的解析 SDK。
> 
> ABC
> >**ABC**文件（Alembic）是一种用于 3D 渲染和动画的开放文件格式。它被广泛应用于电影、电视、游戏和其他媒体产业中的三维图形和特效制作。是一个强大而灵活的 3D 渲染和动画数据格式，它为各种数字媒体项目提供了高效的数据交换和共享解决方案。它在处理复杂场景和动画时提供了便利性和性能优势，并促进了多软件之间的协作和集成。
> 
> OBJ
> >**OBJ**（Wavefront Object）是在3D软件开发中仅次于FBX的模型格式，OBJ是Wavefront Technologies于1980年代开发的一种文件格式，这也是为数不多的免费开放许可的3D文件格式之一，用户可以自由解析和使用。
> >OBJ以文本形式存储数据，它支持多边形几何数据、顶点坐标、材质贴图坐标等基本数据，适用于简单的静态模型。然而，OBJ格式在存储大规模场景和复杂几何数据时可能会变得冗长和冗余，并且不支持高级的几何特性和动画，因此给人的印象总是比较笨重，更加适用于**静态建模、艺术设计、3D打印**等应用领域。
> 

> [!NOTE]- FBX，OBJ 和 ABC 的区别
>
> FBX模型可以导入模型、材质分区、贴图、动画、骨骼，<font color="#ffff00">适合于通过骨骼运动的角色</font>
> 
> ABC模型可以导入模型、材质分区、动画， 适用于点级别动画，<font color="#ffff00">对场景的损耗会比较大</font>
> 
> OBJ可以导入模型、材质分区、贴图，但贴图会有丢失的可能，<font color="#ffff00">适合于静态模型</font>
> 
> > <font color="#d83931">FBX 适合用于带骨骼的人物动画，ABC 适合用于点缓存动画</font>


> [!NOTE]- FBX 导入流程
> Contents


> [!NOTE]- ABC 导入流程
> Contents


> [!NOTE]- OBJ 导入流程
> Contents
