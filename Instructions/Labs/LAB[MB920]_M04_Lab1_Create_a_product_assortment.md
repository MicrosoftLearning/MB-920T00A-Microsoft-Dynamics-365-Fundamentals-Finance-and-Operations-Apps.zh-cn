---
lab:
  title: 实验室 1：创建产品分类
  module: 'Module 4: Learn the Fundamentals of Microsoft Dynamics 365 Commerce'
---

## <a name="lab-1---create-a-product-assortment"></a>实验室 1 - 创建产品分类

## <a name="objectives"></a>目标

你需要创建分配给特定商业渠道的相关产品的分类，并在将来提供该分类。

## <a name="lab-setup"></a>实验室教学设置

   - 预计用时：10 分钟

## <a name="instructions"></a>Instructions

1. 在“财务和运营”页面的左上角，选择“展开导航窗格”汉堡菜单。

1. 在导航窗格中，选择“零售和商务” > “目录和分类” > “分类”  。

1. 等待页面加载。

1. 在“分类”页面，选择“+ 新建”。

1. 在“新建记录”窗格中，展开“常规”。

1. 选择“生效日期”框，然后选择将来的某个日期。

1. In the <bpt id="p1">**</bpt>Assortment name<ept id="p1">**</ept> box, enter a name for the new assortment. For example, <bpt id="p1">**</bpt>New Spring Season<ept id="p1">**</ept>.

1. 将“到期日期”设置为“永不” 。

1. 到期日期可用于自动停用已发布的分类。

1. 展开“商业渠道”。

1. 在“商业渠道”菜单上，选择“+ 添加行”。

1. 在“选择组织节点”中，选择“组织层次结构”菜单，然后选择“按类型划分的零售商店(Fabrikam)” 。

1. 在“可用组织节点”列表中，选择“在线”，然后选择“添加”![右箭头图标](./media/d365-fo-add-org-node-icon.png)图标将其添加到“所选组织节点”。  
  这将添加父节点和所有子节点。

1. 添加“购物中心”父节点，然后选择“确定” 。

1. 验证这两种节点是否已添加到商业渠道。

1. 展开“产品”。

1. 在“产品”菜单上，选择“+ 添加系列”。

1. 选择“类别”菜单，选择“团队运动”，然后选择“确定”  。

1. 这将添加父类别的所有子项。

1. Review the last column named <bpt id="p1">**</bpt>Line type<ept id="p1">**</ept>. By default, all items will be included.

1. 选择“+ 添加系列”，选择“类别”菜单，展开“团队运动”，选择“棒球”，然后选择“确定”    。

1. 要从已包含的较大类别（在本例中为“团队运动”）中排除某个项，在“系列类型”列中，将值更改为“排除”。

1. 使用“棒球”类别行，选择“产品”菜单。

1. When products within a category are defined, you can select a specific product to include or exclude. Select <bpt id="p1">**</bpt>AdultBaseballInfield<ept id="p1">**</ept>.

1. 要删除添加的产品，请删除“产品”框中的内容，然后按键盘上的 Tab 键或选择页面的其他区域。

1. 在顶部菜单中，选择“保存”。

1. 在顶部菜单中，选择“发布”。

1. 查看对话框中的信息，然后选择“是”。

1. 新创建的产品分类将在生效日期可用。
