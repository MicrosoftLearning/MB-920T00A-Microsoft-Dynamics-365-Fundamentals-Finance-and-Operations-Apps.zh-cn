---
lab:
  title: 实验室 3：创建盘点日记帐
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# <a name="module-3-learn-the-fundamentals-of-microsoft-dynamics-365-supply-chain-management"></a>模块 3：学习 Microsoft Dynamics 365 Supply Chain Management 的基础知识

## <a name="lab-3---create-a-counting-journal"></a>实验室 3 - 创建盘点日记帐

1. On the Finance and Operations home page, in the top right, verify you are working with the <bpt id="p1">**</bpt>USMF<ept id="p1">**</ept> company. If necessary, select the company, and from the drop down, select <bpt id="p1">**</bpt>USMF<ept id="p1">**</ept>.

2. 在左侧导航窗格中，选择“模块” > “库存管理” > “日记帐分录” > “物料盘点” > “盘点”。    

3. Select the <bpt id="p1">**</bpt>+New<ept id="p1">**</ept> button in the action pane. The <bpt id="p1">**</bpt>Create inventory journal<ept id="p1">**</ept> dialog form will appear with the <bpt id="p2">**</bpt>OK<ept id="p2">**</ept> button in the bottom. Select the <bpt id="p1">**</bpt>OK<ept id="p1">**</ept> button.

4. 库存盘点日记帐窗体将显示标题和详细信息

![库存盘点日记帐窗体的屏幕截图，其中填写了标题和详细信息。](../media/lp-scm-m-002-warehouse-inventory-mgmt-06.png)

5. 在操作窗格中选择“创建行 -&gt; 联机”。

6. 在“创建现有量盘点日记帐”对话框窗格中，将“仓库”、“库存状态”、“位置”和“牌照”字段设置为“是”。 

![“创建现有量盘点日记帐”对话框窗格的屏幕截图，其中设置了如下所述字段。](../media/lp-scm-m-002-warehouse-inventory-mgmt-07.png)

7. Expand the <bpt id="p1">**</bpt>Record to include<ept id="p1">**</ept> section and select the <bpt id="p2">**</bpt>Filter<ept id="p2">**</ept> link. In the <bpt id="p1">**</bpt>Item number<ept id="p1">**</ept> field, select <bpt id="p2">**</bpt>A0001<ept id="p2">**</ept>, and then select <bpt id="p3">**</bpt>OK<ept id="p3">**</ept>.

8. 在“创建现有量盘点日记帐”对话框窗体底部选择“确定” 。

物料 A0001 的现有量将显示在“日记帐行”部分，其中分拆了网站、仓库、位置和牌照。

9. In the <bpt id="p1">**</bpt>Counted<ept id="p1">**</ept> column of the <bpt id="p2">**</bpt>Journal line<ept id="p2">**</ept> section, enter the numbers counted in each Site/Warehouse/Location/License plate. Note the following:

    - 如果“现有”量与“盘点”量相同，则“数量”字段将为空。

    - 如果“盘点”字段的值大于“现有”字段，则“数量”字段将包含正值。

    - 如果“盘点”字段的值小于“现有”字段，则“数量”字段将包含负值。

10. 在操作窗格中选择“验证”按钮，然后选择“发布”按钮。

11. 关闭该页面并返回到主页。
