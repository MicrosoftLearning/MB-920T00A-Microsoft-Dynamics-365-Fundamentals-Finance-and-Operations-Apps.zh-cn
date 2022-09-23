---
lab:
  title: 实验室 4：创建生产订单
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

## <a name="lab-4---create-a-production-order"></a>实验室 4 - 创建生产订单

## <a name="objectives"></a>目标

The production order contains information about what will be produced, the quantity to produce, and the planned finish date. It also contains information about which materials to consume and which process to follow to produce the item.

你需要为你的公司创建一个新的生产订单。

## <a name="lab-setup"></a>实验室教学设置

   - 预计用时：5 分钟

## <a name="instructions"></a>Instructions

1. 在 Finance and Operations 主页的右上角，验证你当前是否在对 USMF 公司执行操作。

1. 如有必要，请选择公司，然后从菜单中选择“USMF”。

1. 在左侧的导航窗格中，选择“模块” >“生产控制” > “生产订单” > “所有生产订单”。   

1. 在顶部菜单中，选择“新建生产订单”。

1. 在“标识”下的“物料编号”框中，输入“D0001”，然后选择已标识的物料  。

1. 在“生产”下的“交货”框中，选择从当前日期开始再过一个月的日期 。  
    The delivery date indicates when the production order should end in order to deliver on time. This date can be used in the scheduling process. For example, you can schedule the order backward from the delivery date.

1. 在“数量”框中，输入“20”。 

1. Under <bpt id="p1">**</bpt>BOM/ROUTE<ept id="p1">**</ept>, the BOM number field automatically displays the number of any active BOM for the current item, but you can change the BOM for the production order by selecting an active BOM from the list of approved BOM versions. The Route number field automatically displays the number of any active Route for the current item, but you can change the Route for the production order by selecting an active Route from the list of approved Route versions.

    ![显示完整“创建生产订单”窗格的屏幕图像](./media/lp1-m4-new-production-order-pane.png)

1. 选择“创建”。
