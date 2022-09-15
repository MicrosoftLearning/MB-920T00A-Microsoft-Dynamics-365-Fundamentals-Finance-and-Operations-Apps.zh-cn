---
demo:
  title: 演示 3：了解项目成本
  module: 'Module 5: Learn the Fundamentals of Microsoft Dynamics 365 Project Operations'
---

## <a name="demo-3---explore-project-costs"></a>演示 3 - 了解项目成本

In this demo, we will walk through the creation of a time and expense entry that will be charged to the Contoso Consulting project. We'll explore the entries in formats optimized for web and mobile presentation, and we'll see how a workflow is used to manage the approval process.

1. 在 Dynamics 365 for Finance and Operations 的导航窗格中，选择“模块”>“项目管理和会计”>“时间表”>“我的时间表(移动设备优化版)” 。  
    首先，虽然我现在没有使用移动设备，但在选择“我的时间表(移动设备优化版)”之后，你会发现这些表单可用于移动设备。

    ![“项目管理和会计”菜单的屏幕截图，其中突出显示了“我的时间表(移动设备优化版)”。](./media/projops_costs_1_select_my_timesheets.png)  

    此优化是 Microsoft 业务应用程序的一个关键区别，有助于确保最大限度地缩短 Web 和移动设备用户之间的学习曲线。

1. In the top right company picker, verify the legal entity you are connecting to is <bpt id="p1">**</bpt>USSI<ept id="p1">**</ept>. If it's not, change the legal entity to <bpt id="p1">**</bpt>USSI<ept id="p1">**</ept>.

1. 在“我的时间表”页上，选择“新建” 。  
    现在，我们将基于配置的设置创建一个新的时间表。

1. 在“新建时间表”窗格中，点击“日期”框 。  
    输入的日期将确定时间表周期。

1. 点击“从收藏夹创建”。  
    如果你保存了收藏夹，则可以选择从中创建以节省时间。

1. 完成后选择“确定”。

1. 在“我的时间表详细信息”页上，选择“新建 +”图标 。

1. 在“新时间表项”窗格中，点击“法人”框 。  
    The new timesheet line will be opened, with details such as the customer, the project, the category, the line properties, and tax parameters. You can also select a different legal entity if the time entry is on behalf of another company within your organization.

1. 选择“项目 ID”菜单。

1. 选择一个可用的项目，例如“Contoso Consulting”项目。

1. 完成后选择“确定”。  
    随即将打开时间条目的针对移动设备进行了优化的屏幕，你可以开始针对该项目和类别（在本例中为“服务”）预订每天的时间。

1. 在“时间条目”页面的“星期一”框中，输入 8  。  
    这代表一天的小时数条目。

    ![“时间条目”页面的屏幕截图。](./media/projops_costs_2_mon_box.png)

1. 在此演示中，我们将详细介绍将记入 Contoso Consulting 项目的时间和费用条目的创建过程。  
    你还可以针对项目输入内部评论和外部评论，以确保各方都了解所记录的时间的性质。

1. 我们将探索其采用的格式针对 Web 和移动设备演示而进行了优化的条目，并了解如何使用工作流来管理审批过程。

1. 在导航栏中，选择“保存”。

1. 在左侧导航菜单的“时间表”下，选择“我的时间表” 。

1. 在“我的时间表”页面上，选择之前创建的时间条目。

1. 在“时间表”选项卡上，点击“类别”列。  
    Now assume we've returned to a computer and are reviewing our time from within the web timesheet form. We can still see the same information, such as the category and the hours.

1. 在“项详细信息”下，点击“内部评论”和“外部评论”  。  
    We can also review the comments we entered earlier. The information is there, but the layout format is just a bit different. This format is often used for final review because it can be easier for people to review and validate their time, especially when someone is assigned to multiple projects or categories.

1. 在导航栏中，选择“工作流”选项卡。  
    If we're satisfied with the timesheet, we can submit it. The approvals required will be determined by each organization during the implementation phase based on their own company policies.

1. 在“审阅时间表工作流”窗格中，选择“提交” 。

1. 在“审阅时间表工作流 - 提交”窗格中，添加所有其他评论。

1. 选择“提交”。 

1. Browse to the <bpt id="p1">**</bpt>Hour transactions<ept id="p1">**</ept> page. If the <bpt id="p1">**</bpt>Hour transactions<ept id="p1">**</ept> tab is grayed out, browse to the <bpt id="p2">**</bpt>My timesheets page<ept id="p2">**</ept>, and select the previously created timesheet.

1. 在“时间事务”页面上，查看该页面。  
    Upon approval, the results will be posted and will be visible in the Hour transactions page. We can see all the relevant information, such as the legal entity, project, category, hours, and in this case, even a view of the cost price and the sales price.  

接下来，我们可以深入到凭证交易。

1. 在导航栏中，选择“凭证”。

1. 在“凭证交易”页面上，点击“分类帐帐户”和“帐户名称”部分  。  
    在这些部分中，我们可以看到对总分类帐的影响，以及将要使用的帐户。  

现在，让我们针对同一个 Contoso Consulting 项目创建一个费用条目。

1. 在导航窗格中，依次选择“模块”>“费用管理”>“我的费用”>“费用报告”。

1. 在“费用管理”页面上的“报告”选项卡中，选择“+ 新建费用报告”  。

1. 在右上方的公司选择器中，验证你要连接的法人是否是“USSI”。

1. 选择“确定”。

1. 在“费用”页面中，选择“+ 新建费用” 。  
此时会显示一个新的费用项。

1. 在“费用类别”列中，从下拉“类别”菜单中选择“燃料”  。  
我们可以在此处输入新费用及其详细信息。

1. 在“交易金额”列中，输入 25.00 。

1. 在“货币”列中，选择“美元” 。

1. 如果不是，请将法人更改为“USSI”。  
    输入所有详细信息后，便可以保存该费用。

1. 选择“保存”  。

1. 在左侧导航菜单的“工作区”下，选择“费用管理” 。

1. 在“费用管理”页面上，选择刚创建的费用报告。

1. 在“费用报告”页面上，选择“项目 ID”框，然后选择“00000093 Contoso Consulting”  。  

接下来，我们可以指示该燃料将计入 Contoso Consulting 项目，以及有关该费用的其他信息。

1. 点击“其他信息”框。

1. 在屏幕的右下角，选择“保存并继续”。

1. 在屏幕右侧，选择“提交”。

1. 在“评论”框中，添加所有其他评论。

1. 选择“提交”。 

1. 在“费用管理”页面上，点击“批准状态”列 。  
    At this time, travel policies and expense approval flow will be activated. The costs have been posted and applied to the Contoso Consulting project and will be available later for invoicing if chargeable.

In this demo, we have processed a time and expense entry that was charged to the Contoso Consulting project. We saw samples in web and mobile formats and were able to see how workflows are used to manage the approvals required by the USSI organization.
