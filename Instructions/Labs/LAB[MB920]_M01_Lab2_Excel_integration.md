---
lab:
  title: 实验室 2：Excel 集成
  module: 'Module 1: Explore the core capabilities of Dynamics 365 finance and operations apps'
---

# 模块 1：探索 Dynamics 365 财务和运营应用的核心功能

## 实验室 2：Excel 集成

## 目标

在本实验室中，你将了解如何使用 Dynamics 数据连接器 Office 加载项应用将数据从财务和运营应用复制到 Excel。 你还将了解如何使用同一应用将数据插入 Dynamics 365 Finance and Operations。 

## 实验室教学设置

   - 预计用时：5 分钟

## Instructions

现在你已经熟悉了财务和运营应用，那么花点时间来了解 Excel 集成方案吧。 

1.  在 Finance and Operations 主页的右上角，验证你当前是否在对 USMF 公司执行操作 。 

2.  导航到“采购和寻找货源” > “设置” > “供应商” > “供应商组”。

3.  在操作窗格中，选择“在 Microsoft Office 中打开”，然后选择“在 Excel 中打开”下方的“供应商组(usmf)”  。

4.  在“在 Excel 中打开”窗格中，选择“下载” 。 

5.  将下载并保存 Excel 模板文件。 打开下载的 Excel 模板文件，根据需要跳过或允许其他标准安全提示，关闭激活，然后选择“启用编辑” 。 选择“信任此加载项”，然后登录（如果系统询问，则使用同一凭据登录）。 

    登录后，数据连接器应用会刷新“供应商组”表中的现有数据，并显示在 Excel 电子表格中。 

6.  若要创建新记录，请在“供应商组”字段中输入 `100`，在“说明”字段中输入 `Insurance vendor`，并在“付款条款”字段中输入 `Net10`  。 

7.  在 Microsoft Dynamics 数据连接器任务窗格中选择“发布”按钮。 

8.  刷新 Dynamics 365 Finance and Operations 中的“供应商组”列表，以验证是否已成功添加新记录。 

