---
lab:
  title: 实验室 5：创建仓库
  module: 'Module 1: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
ms.openlocfilehash: 919ea602b0768683acd845dd184b3bf5a0364fd0
ms.sourcegitcommit: 252458fca8e71b6e5e8b99ae4c2b47cd85461a30
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 01/27/2022
ms.locfileid: "137909298"
---
# <a name="module-1-learn-the-fundamentals-of-microsoft-dynamics-365-supply-chain-management"></a>模块 1：学习 Microsoft Dynamics 365 Supply Chain Management 的基础知识

## <a name="lab-5---create-a-warehouse"></a>实验室 5 - 创建仓库

## <a name="objectives"></a>目标
利用 Supply Chain Management 中的仓库管理系统，可以灵活定义仓库布局，以满足不断变化的需求，以便能够达到最佳仓库效率。

- 可以建立高优先级和低优先级的存储区域，以实现货物的最佳放置。
- 可以将仓库划分不同的区域，以适应各种存储需求，如温度要求或物料的各种周转率。
- 可以在任何层次上指定仓库位置（例如，场地、仓库、过道、货架、架子和仓位）。
- 可以通过使用物理容量约束设置对位置进行分组。
- 可以根据查询定义的规则，控制物料的存储和拣选方式。

要使用 Supply Chain Management 中的仓库管理，必须创建一个仓库，使其用于更高级或专门的仓库管理活动。

## <a name="lab-setup"></a>实验室教学设置

   - 预计用时：10 分钟

## <a name="instructions"></a>Instructions

1. 在 Finance and Operations 主页的右上角，验证你当前是否在对 USMF 公司执行操作。

1. 如有必要，请选择公司，然后从菜单中选择“USMF”。

1. 在左侧导航窗格中，选择“模块” > “库存管理” > “设置” > “库存细分” > “仓库”。    

    ![显示仓库模块导航的屏幕图像](./media/lp1-m3-warehouses-module-navigation.png)

1. 在“仓库”页的顶部菜单中，选择“新建”。

1. 在“仓库”字段中，输入“101”。 

1. 在“名称”字段中，输入“饱和仓库”。 

1. 选择“场地”菜单，然后选择“3 号国内泡沫生产”。 

1. 扩展“位置名称”。  
    本节中的选项定义了位置名称的默认格式。

1. 将“包括过道”和“包括货架”选项设置为“是”。  

1. 在“格式”框中，对于货架，请输入一个值。  
    例如，如果货架位置名称的格式必须包含 OVFL，应在“格式”框中输入该值。

1. 在“级别”下，将“包括架子”选项设为“是”。  

1. 在“格式”字段中，对于架子，请输入 -##。 

1. 在顶部菜单中，选择“仓库”。

    ![显示突出显示“仓库”菜单选项的屏幕图像](./media/lp1-m3-warehouses-menu-option.png)

1. 在“维护”下，选择“库位向导”。 

1. 在欢迎页，查看信息，然后在右下角选择“下一步”。

1. 清除“出货台”和“堆放库位”复选框。 

1. 选择“下一步”并查看信息。

1. 继续浏览每一页，在完成后，选择“完成”。

1. 关闭该页面并返回到主页。
