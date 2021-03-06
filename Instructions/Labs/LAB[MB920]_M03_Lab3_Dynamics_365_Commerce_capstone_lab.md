---
lab:
    title: '实验室 3： Dynamics 365 Commerce 顶点实验室'
    module: '模块 3： 学习 Microsoft Dynamics 365 Commerce 的基础知识'
---

## 实验室 3 - Dynamics 365 Commerce 顶点实验室

## 目标

在本实验室中，你将探索 Commerce Headquarters 设置的基础知识。核心功能包括设置零售渠道、创建分类和配置零售折扣。

## 实验室设置

   - **预计用时**： 30 分钟 

## 说明

## 练习 1：探索 Commerce Headquarters

### 创建新商店

1. 在登陆页面的右上角，验证是否已选中 **“USRT”** 公司。

1. 如果没有，请选择当前列出的公司，然后输入 **“USRT”**。

1. 使用导航窗格，选择 **“模块”** > **“零售和商务”** > **“渠道”** > **“商店”** > **“所有商店”**。

1. 在操作窗格中，选择 **“+ 新建”** 创建一个新商店。

1. 在“新建记录”窗口中，使用下表中的设置更新值：

    | **设置**| **值**|
    | :--- | :--- |
    | 名称| 西雅图旗舰店|
    | 商店号码| 000098|
    | 仓库| 西雅图|
    | 装运仓库| 西雅图|
    | 商店时区| (GMT-08:00) 太平洋时间|
    | 功能配置文件| FN001|
    | 库存查询| 是|
    | 通道配置文件| 默认|
    | 脱机配置文件| 默认|
    | 销售税组| WA|
    | 使用基于目的地的税| 是|
    | 客户通讯簿| 零售客户|
    | 员工通讯簿| 西雅图|
    | 默认客户| 3002|

1. 在操作窗格中，选择 **“保存”**。

1. 选择 **“报表/结算”** 快速选项卡，然后输入以下更新：

    | 设置| 值|
    | :--- | :--- |
    | 报表金额计算| 上一次|
    | 最大差异 > 过帐| 100.00|

1. 选择 **“财务维度”** 快速选项卡，然后输入以下更新：

    | 设置| 值|
    | :--- | :--- |
    | 业务部门| 004|
    | 零售渠道| 000210|

1. 选择 **“屏幕布局”** 快速选项卡。

1. 在 **“屏幕布局 ID”** 框中，输入 **“A2CP16:9C”**。

1. 在操作窗格中，选择 **“保存”**。

1. 在操作窗格中，选择 **“设置”**，然后在 **“复制”** 选项卡中选择 **“全部复制”**。

1. 在 **“全部复制”** 窗格中，选择 **“从商店”** 菜单，然后选择 **“ANNAPOL”**。

1. 如有必要，选择 **“至商店”** 菜单，然后选择 **“00098”**。

1. 选择 **“确定”**。

1. 验证是否显示成功消息，然后关闭页面。

### 将一组产品添加到分类并发布

1. 使用导航窗格，选择 **“模块”** > **“组织管理”** > **“组织”** > **“组织层次结构”**。

1. 在导航列表中，选择 **“按区域划分的零售商店”**。

1. 在操作窗格中，选择 **“查看”**。

1. 在“层次结构设计器”页面的操作窗格中，选择 **“编辑”**。

1. 在 **“西部”** 磁贴上，选择省略号 (**...**) 图标。

1. 在“层次结构设计器”页面上，选择 **“插入”** > **“零售渠道”**。

1. 在 **“零售渠道”** 窗格中，选择 **“西雅图旗舰店”**，然后选择 **“确定”**。

1. 在操作窗格中，选择 **“保存”**。

1. 在对话框中，查看信息，然后选择 **“关闭”**。

1. 在操作窗格中，选择 **“发布”**。

1. 在 **“发布更改”** 窗格的 **“生效日期”** 框中，选择当月的第一天。

1. 在 **“描述更改”** 框中，输入 **“添加西雅图旗舰店”**，然后选择 **“发布”**。

1. 在对话框中，查看信息，然后选择 **“关闭”**。

1. 在操作窗格中，选择 **“保存”**。

1. 在对话框中，查看信息，然后选择 **“关闭”**。

1. 关闭页面。

1. 使用导航窗格，选择 **“模块”** > **“零售和商务”** > **“目录和分类”** > **“分类”**。

1. 在“分类”页面，选择 **“AW-Outlet”**。

1. 在操作窗格中，选择 **“编辑”**。

1. 在对话框中，选择 **“是”** 确认编辑选择。

1. 在“AW-Outlet”页面，选择 **“商业渠道”** 快速选项卡。

1. 在工具栏中选择 **“+ 添加行”**。

1. 在 **“选择组织节点”** 窗格中，选择 **“组织层次结构”** 菜单，然后选择 **“按区域划分的零售商店”**。

1. 在 **“可用组织节点”** 下，选择 **“西雅图旗舰店”**，然后选择 **“添加”** 右箭头图标将其添加到 **“所选组织节点”**。

1. 选择 **“确定”**。

1. 在操作窗格中，选择 **“发布”**。

1. 在对话框中，查看信息，然后选择 **“是”**。

1. 在操作窗格中，选择 **“编辑”**。

1. 在**确认**对话框中，选择 **“是”**。

1. 在“AW-Outlet”页面，选择 **“产品”** 选项卡。

1. 在“AW-Outlet”页面，选择 **“+ 添加系列”**。

1. 选择 **“类别”** 菜单，选择 **“团队运动”**，然后选择 **“确定”**。

1. 在操作窗格中，选择 **“发布”**。  

### 运行产品的零售计划程序作业

1. 使用导航窗格，选择 **“模块”** > **“零售和商务”** > **“零售和商务 IT”** > **“配送计划”**。

1. 在导航列表中，选择 **“1040 (产品)”**。

1. 在操作窗格中，选择 **“立即运行”**。

1. 在 **“与计划'1040'增量同步”** 窗格中，查看信息，然后选择 **“确定”**。

### 创建新的产品折扣

1. 使用导航窗格，选择 **“模块”** > **“零售和商务”** > **“定价和折扣”** > **“所有折扣”**。

1. 在操作窗格中，选择 **“新建”** > **“折扣”**。

1. 在“折扣”页面的 **“名称”** 框中，输入 **“商店开业”**。

1. 在 **“详细信息”** 快速选项卡的 **“描述”** 框中，输入 **“商店开业 20% 折扣”**。

1. 在 **“价格/折扣”** 快速选项卡上的 **“折扣百分比”** 框中，输入 **“20.00”**。

1. 在 **“有效期”** 快速选项卡上的 **“生效日期”** 框中，输入上个月的某个日期。

1. 在 **“到期日期”** 框中，输入距当前日期一个星期的未来日期。

1. 在 **“系列”** 快速选项卡上的工具栏上，选择 **“+ 添加”**。

1. 在 **“类别”** 列下，选择菜单，选择 **“团队运动”**，然后选择 **“确定”**。

1. 在操作窗格中，选择 **“保存”**。

1. 在操作窗格中，选择 **“价格组”**。

1. 在“价格组”页面，选择 **“价格组”** 菜单，然后选择 **“西部”**。

1. 在操作窗格中，选择 **“保存”**。

1. 使用导航窗格，选择 **“模块”** > **“零售和商务”** > **“定价和折扣”** > **“所有折扣”**。

1. 在导航列表中，选择 **“ST100101”**。

1. 在 **“常规”** 快速选项卡上，选择 **“状态”** 菜单，然后选择 **“启用”**。

1. 在操作窗格中，选择 **“保存”**。

1. 关闭表单。

1. 使用导航窗格，选择 **“模块”** > **“零售和商务”** > **“零售和商务 IT”** > **“配送计划”**。

1. 在导航列表中，选择 **“1020 (产品)”**。

1. 在操作窗格中，选择 **“立即运行”**。

1. 在 **“与计划'1020'增量同步”** 窗格中，查看信息，然后选择 **“确定”**。
