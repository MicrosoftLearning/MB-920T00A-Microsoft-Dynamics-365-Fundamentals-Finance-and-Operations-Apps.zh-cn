---
lab:
  title: 实验室 2：Excel 集成
  module: 'Module 1: Explore the core capabilities of Dynamics 365 finance and operations apps'
ms.openlocfilehash: e5929571477cfcdbb1b2e81c72ebc566a96c56a4
ms.sourcegitcommit: 8e5a278c6e08abdcc3fb719796f79842e868606b
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/14/2022
ms.locfileid: "147116257"
---
# <a name="module-1-explore-the-core-capabilities-of-dynamics-365-finance-and-operations-apps"></a>模块 1：探索 Dynamics 365 财务和运营应用的核心功能

## <a name="lab-2---excel-integration"></a>实验室 2 - Excel 集成

现在你已经熟悉了财务和运营应用，那么花点时间来了解 Excel 集成方案吧。

### <a name="task-1-create-template"></a>任务 #1：创建模板

1. 打开财务和运营主页。 

2. 导航到“模块” > “通用” > “通用” > “Office 集成” > “Excel 工作簿”“设计器”。 请注意，大多数导航都是通过模块进行的，因此通常不会说明。

3. 在筛选器中搜索“VendorGroup”。

4. 从可用字段列表中，选择“供应商组”、“说明”和“付款方式”字段，然后通过选择向右箭头将其移动到所选字段框。

5. 在操作窗格中，选择“创建工作簿”按钮。

6. 在右侧的“保存到”面板中，选择“下载”按钮。

7. 选择“另存为”并将其存储在“下载”文件夹中来下载文件。

8. 导航到“常见” > “Office 集成” > “文档”“模板”。

9. 选择“新建”。

10. 在右侧面板中，在“上传模板”部分，选择“浏览”按钮，然后选择之前下载的文件（如果使用的是默认名称，则为 DynamicsWorkbook）。

11. 在“模板名称”字段中，输入“CustomVendorGroup”。

12. 选择“确定”，然后选择“保存” 。

### <a name="task-2-open-in-excel"></a>任务 #2：在 Excel 中打开

1. 导航到“采购和寻找货源” > “设置” > “供应商” > “供应商组”。

2. 选择“在 Microsoft Office 中打开” > “在 EXcel 中打开”以查找已上传的新模板 CustomVendorGroup。

3. 选择“CustomVendorGroup”并下载 Excel 模板。

4. 保存并打开下载的 Excel 模板，根据需要允许它，关闭激活，然后选择“启用编辑”。 信任此加载项，然后登录（如果系统询问，则使用同一凭据登录）。

供应商组表的所有现有数据都将显示在 Excel 电子表格中。

5. 输入新记录。

6. 在“供应商组”字段中输入“100”、“说明”字段中输入“保险供应商”，并在“付款条款”字段中输入“Net10”。     

7. 在 Microsoft Dynamics Office 加载项应用中选择“发布”按钮。

8. 打开”供应商组”窗体，验证是否添加了新记录。

