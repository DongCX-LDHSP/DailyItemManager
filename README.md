# DailyItemManager

- 当前仅是记录一个想法，待以后有机会进行实现
- 在互联网上进行一番检索之后，发现我的想法很像是企业的**固定资产管理系统**，与当下的固定资产管理系统的不同可能就是我的想法需要被管理的物品是**可定位的**

## 想法来源

1. 在学校中丢失东西时，如果能提供一张照片，那么不说丢失的物品一定能找回，但是找回的**可能性**肯定是要增大一些的，放之社会应当也有一定的作用
2. 日常生活中，有很多物品不是常用的，但是**偶尔又可能会**使用那么几下，这种时候往往需要**花费一定的时间**去查找该物品

## 想要通过该软件解决什么问题

1. 可以在**失物招领**时提供一张**图片**
2. 可以在想要查找某件**不常用的物品**时，减少查找时间

## 初步设想

### 记录物品的以下属性

1. 名称
2. 位置
3. 图片
4. 状态（可以让用户选择状态）
5. 描述
6. 备注
7. 等有必要的属性

### 检索策略

1. 名称
2. 位置
3. 描述
4. 基于状态筛选物品
5. 等可行的检索策略

### 可能需要着重解决的问题

1. 每个物品都需要**手动逐一登记**，费时费力

### 结合物联网（长远发展）

使用物联网定位某一物品的位置，类似Apple的查找iPad，iPhone的功能

#### 定位策略

- 使用一个定位代理点，该代理点负责某一区域中的所有物品
- 想要定位某一物品时，只需向代理点发送信息，由代理点进一步进行查询
- 被代理点管理的节点可以使用**半主动标签**，以便减少能源消耗

#### 自觉存在的问题

1. 查找的物品的特点：**不常用**，所以要求物品上的物联网芯片可以**长时间发挥作用**
2. 不是所有的物品**都适合**植入物联网芯片（**半主动标签**可能是一种解决方案）

## 目标平台

1. PC端
2. 移动端
    1. 安卓
    2. 苹果
    3. 平板
