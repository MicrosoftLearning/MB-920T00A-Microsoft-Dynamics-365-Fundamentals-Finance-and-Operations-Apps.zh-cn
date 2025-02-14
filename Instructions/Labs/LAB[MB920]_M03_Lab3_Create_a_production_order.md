---
lab:
  title: 实验室 3.2：创建生产订单
  module: 'Learning Path 3: Learn the fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# 学习路径 3：学习 Microsoft Dynamics 365 Supply Chain Management 的基础知识
# 模块 4：介绍制造过程

## 实验室 3.2：创建生产订单

## 目标

生产订单有助于在 Supply Chain Management 中启动生产流程。 在本实验中，您会熟悉生产订单窗体的用户界面和功能。 此外，在练习结束时，你还将学会如何创建和处理生产订单。

## 实验步骤

1. 在 Dynamics 365 **“供应链管理”主页**右上角，验证你当前是否在对 **USMF** 公司执行操作。

2. 如有必要，请选择公司，然后从菜单中选择“USMF”。

3. 在左侧的导航窗格中，选择“模块” > “生产控制” > “生产订单” > “所有生产订单”。

4. 在顶部菜单上，选择“**新建生产订单**”并输入以下数据。

    - 物料编号：**D0002**

    - 数量：**10**

    - 场所：**1**

    - 仓库：**11**

    - 交货：[选择距离当前日期一个月后的日期]

    - BOM 编号：**D0002BOM**

    - 工艺路线编号：**000004**

5. 选择“创建”按钮。

为数量为 10 的物料 D0002 创建生产订单。

6. 选择 **“生产订单”（操作窗格菜单）&gt;“流程”&gt;“估算”。**

7. 在“**估算**”对话框的“**利润设置**”字段中选择“**标准**”，选择 **“引用”字段**，然后选择“**确定**”按钮。

生产订单的“**状态**”将更改为“**已估算**”。

8. 选择 **“排产”（操作窗格菜单）&gt;“生产订单”&gt;“排产”操作。**

9. 在“**工序级排产**”对话框的“**排产方向**”字段中，选择“**从今天起向前**”，然后选择“**确定**”按钮。

10. 选择 **“视图”（操作窗格菜单）&gt;“相关信息”&gt;“产能预留”**。

11. 验证在“**产能预留**”页上是否已创建新记录。

12. 导航回“**所有生产订单**”页。 请注意，生产订单的“**状态**”将更改为“**已排产**”。

13. 选择 **“生产订单”（操作窗格菜单）&gt;“流程”&gt;“发布”**。

14. 在“**发布**”对话框中，选择 **“引用”字段**，然后选择“**确定**”按钮。

15. 生产订单的“**状态**”将更改为“**已发布**”。

16. 选择 **“生产订单”（操作窗格菜单）&gt;“流程”&gt;“启动”**。

17. 在“**启动**”对话框中，选择“**常规**”选项卡。

18. 在“**常规**”选项卡上，输入以下详细信息。

    - 日期：**当前日期**

    - 数量：**10**

    - 启动生产：**是**

    - 立即发布工艺卡：**否**

    - 立即发布领料单：**否**

19. 选择“确定”  按钮。

生产订单的“**状态**”将更改为“**已启动**”。

20. 选择 **“视图”（操作窗格菜单）&gt;“日记帐”&gt;“领料单”**。

已创建包含三行的新领料单日记帐。

21. 发布领料单日记帐。

如果需要，请在“发布日记帐”窗口中选择“**确定**”。

22. 导航回“**所有生产订单**”页，然后选择 **“视图”（操作窗格菜单）&gt;“日记帐”&gt;“工艺卡”**。

已创建包含三行的工艺卡日记帐。

23. 在所有三行中选择**操作完成**字段，然后发布工艺卡日记帐。

24. 导航回**所有生产订单**页，然后选择**生产订单（操作窗格菜单）&gt; 流程 &gt; 完工入库**。

25. 在“完工入库”**** 对话框中，在“良品数量”**** 字段中输入 10****。 选择“结束作业”**** 字段，然后选择“确定”****。

生产订单的“状态”**** 更改为“已结束”****。 物料 D0002**** 的存货在站点 1 和仓库 11 中增加了 10 个。

26. 选择**管理成本（操作窗格菜单） &gt; 计算 &gt; 查看计算详细信息**。

请注意“成本计算概览”**** 选项卡上所制造物料的最终成本计算。

 
