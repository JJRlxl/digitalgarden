---
{"dg-publish":true,"permalink":"/学习笔记/虚幻/0.3.UNREAL安装，商城和版本互导问题/","dgPassFrontmatter":true}
---


> [!tip] [[学习笔记/虚幻/基础认知阶段\|基础认知阶段目录]]

## 01.如何下载 UE?

---
1. 首先进入浏览器搜索<font color="#ffff00">Unreal</font>,或者直接在链接粘贴网页地址[虚幻引擎 | 最强大的实时3D创作平台 - Unreal Engine](https://www.unrealengine.com/zh-CN/)   进入第一个网址；![Pasted image 20240218111616.png|700](/img/user/%E5%82%A8%E5%AD%98/%E5%9B%BE%E7%89%87/Pasted%20image%2020240218111616.png)

---
2. 找到右上角小人图跟随提示标注册自己的账号 ![Pasted image 20240218111859.png](/img/user/%E5%82%A8%E5%AD%98/%E5%9B%BE%E7%89%87/Pasted%20image%2020240218111859.png)

---
3. 登录后点击下载，下载 Epic 的启动器并安装，安装过程出现问题看  [[学习笔记/疑难杂症/虚幻可能遇到的问题\|虚幻可能遇到的问题]]![Pasted image 20240218112021.png](/img/user/%E5%82%A8%E5%AD%98/%E5%9B%BE%E7%89%87/Pasted%20image%2020240218112021.png) ![Pasted image 20240218112116.png](/img/user/%E5%82%A8%E5%AD%98/%E5%9B%BE%E7%89%87/Pasted%20image%2020240218112116.png)

---
4. UE 5 在库的分栏菜单内，点加加号选择版本和存放路径即可下载 （引擎大小在 50 G 左右，注意存放硬盘容量）![Pasted image 20240218113155.png](/img/user/%E5%82%A8%E5%AD%98/%E5%9B%BE%E7%89%87/Pasted%20image%2020240218113155.png)

## 02. 怎么使用 UE 的商城
1. 点击虚幻商城按钮进入商城界面 ![Pasted image 20240218114135.png](/img/user/%E5%82%A8%E5%AD%98/%E5%9B%BE%E7%89%87/Pasted%20image%2020240218114135.png)

---
2. 虚幻提供了一些免费的资产，分成<font color="#ffff00">永久免费资产</font>和<font color="#ffff00">每月免费资产</font>。每月免费资产只要你当月添加后就可以永久使用（例如 2 月免费资产添加后，到了三月依然可以使用。但是二月没有添加，到了三月就回到付费资产，需要付费）。 ![Pasted image 20240218114328.png](/img/user/%E5%82%A8%E5%AD%98/%E5%9B%BE%E7%89%87/Pasted%20image%2020240218114328.png) ![Pasted image 20240218114353.png](/img/user/%E5%82%A8%E5%AD%98/%E5%9B%BE%E7%89%87/Pasted%20image%2020240218114353.png)

---
3. 找到一个免费资产，点击添加购物车 ![Pasted image 20240218114814.png](/img/user/%E5%82%A8%E5%AD%98/%E5%9B%BE%E7%89%87/Pasted%20image%2020240218114814.png)

---
   
4. 点击购物车，选择支付。因为是免费，所以支付金额为 0 元。 ![Pasted image 20240218114858.png](/img/user/%E5%82%A8%E5%AD%98/%E5%9B%BE%E7%89%87/Pasted%20image%2020240218114858.png)

---
  
5. 添加完成后可以在库的界面往下拉，找到保管库即可看到添加的免费资产，要使用时点击添加到工程选择想要导入的工程即可。 ![Pasted image 20240218115051.png](/img/user/%E5%82%A8%E5%AD%98/%E5%9B%BE%E7%89%87/Pasted%20image%2020240218115051.png)

---
6. 小结：
   UE 商城里面不止是有模型模型资产，还有材质球，环境，代码插件，蓝图，预设工程等等。平时可以多看看商城的更新和一些推荐。

## 03.如何进行同版本资产之间的相互转移
相同的版本，如果想要将 A 工程的一些资产转移到 B 工程。那就把对应 Content 文件夹进行直接拷贝。![Pasted image 20240218120909.png](/img/user/%E5%82%A8%E5%AD%98/%E5%9B%BE%E7%89%87/Pasted%20image%2020240218120909.png)

## 04.如何将低版本资产转移到高版本中
1. 对应 Content 文件夹进行资产拷贝（此图中 U 2 工程为 5.1 版本，D 2 工程为 5.2 版本）![Pasted image 20240218121226.png|700](/img/user/%E5%82%A8%E5%AD%98/%E5%9B%BE%E7%89%87/Pasted%20image%2020240218121226.png)
2. 直接用启动窗口打开低版本工程，会提示
3. 点击更多选项 —— 复制一份

点击更多选项 —— 就地转换

点击更多选项 —— 跳过转换

> [!tip]- 建议
> 最好的方式是复制一份，但是也要注意文件大小


## 05. 高版本的资产能否转移到低版本工程里?
低版本不能直接打开新版本创建的工程
低版本不能直接打开新版本创建的工程
低版本不能直接打开新版本创建的工程

高版本资产的模型、材质、关卡拷贝到低版本工程中存在可能会丢失的问题
高版本资产的模型、材质、关卡拷贝到低版本工程中存在可能会丢失的问题
高版本资产的模型、材质、关卡拷贝到低版本工程中存在可能会丢失的问题

<font color="#de7802"><u>**所以尽量不要把高版本资产转移到低版本工程**</u></font>


