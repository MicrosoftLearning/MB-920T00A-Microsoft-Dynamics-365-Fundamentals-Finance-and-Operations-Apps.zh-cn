---
lab:
  title: 实验室 3：创建盘点日记帐
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
ms.openlocfilehash: 5e61646d33f284bb7e30b6f63a7db4778f58b47c
ms.sourcegitcommit: 8e5a278c6e08abdcc3fb719796f79842e868606b
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/14/2022
ms.locfileid: "147116262"
---
# <a name="module-3-learn-the-fundamentals-of-microsoft-dynamics-365-supply-chain-management"></a>模块 3：学习 Microsoft Dynamics 365 Supply Chain Management 的基础知识

## <a name="lab-3---create-a-counting-journal"></a>实验室 3 - 创建盘点日记帐

1. 在 Finance and Operations 主页的右上角，验证你当前是否在对 USMF 公司执行操作。 如有必要，请选择公司，然后从下拉列表中选择“USMF”。

2. 在左侧导航窗格中，选择“模块” > “库存管理” > “日记帐分录” > “物料盘点” > “盘点”。    

3. 在操作窗格中选择“+新建”按钮。 “创建库存日记帐”对话框窗体随即显示，底部有“确定”按钮。 选择“确定”按钮。

4. 库存盘点日记帐窗体将显示标题和详细信息

![库存盘点日记帐窗体的屏幕截图，其中填写了标题和详细信息。](../media/lp-scm-m-002-warehouse-inventory-mgmt-06.png)

5. 在操作窗格中选择“创建行 -&gt; 联机”。

6. 在“创建现有量盘点日记帐”对话框窗格中，将“仓库”、“库存状态”、“位置”和“牌照”字段设置为“是”。 

![“创建现有量盘点日记帐”对话框窗格的屏幕截图，其中设置了如下所述字段。](../media/lp-scm-m-002-warehouse-inventory-mgmt-07.png)

7. 展开“要包含的记录”部分并选择“筛选”链接。 在“物料编号”字段中，选择“A0001”，然后选择“确定”。

8. 在“创建现有量盘点日记帐”对话框窗体底部选择“确定” 。

物料 A0001 的现有量将显示在“日记帐行”部分，其中分拆了网站、仓库、位置和牌照。

9. 在“日记帐行”部分的“盘点”列中，输入每个站点/仓库/位置/牌照中盘点的数字。 注意以下事项：

    - 如果“现有”量与“盘点”量相同，则“数量”字段将为空。

    - 如果“盘点”字段的值大于“现有”字段，则“数量”字段将包含正值。

    - 如果“盘点”字段的值小于“现有”字段，则“数量”字段将包含负值。

10. 在操作窗格中选择“验证”按钮，然后选择“发布”按钮。

11. 关闭该页面并返回到主页。
