# 变更ESSD云盘性能级别 {#task_810820 .task}

您可以在使用ESSD云盘的过程中，在线升级或者降配性能级别。

您在创建ECS实例时可以选择ESSD云盘作为系统盘或者数据盘，也可以单独创建一块ESSD云盘。创建ESSD云盘的详细步骤请参见[使用向导创建实例](../cn.zh-CN/实例/创建实例/使用向导创建实例.md#)和[创建按量付费云盘](cn.zh-CN/块存储/云盘/创建云盘/创建按量付费云盘.md#)。更多有关ESSD云盘的信息，请参见[ESSD云盘](cn.zh-CN/块存储/云盘/ESSD云盘.md#)。

升级和降配ESSD云盘性能级别时，您需要注意以下内容。

-   变更ESSD云盘性能级别时，ECS实例不能处于过期或者账号欠费状态。
-   新创建的ESSD云盘请您等待云盘进入**待挂载**（Available）状态后再变更ESSD云盘性能级别。
-   变更ESSD云盘性能级别后，系统按照新性能级别单价计算消费账单。降配预付费ESSD云盘后，系统会返还剩余计费周期内的差价。

1.  登录[ECS管理控制台](https://ecs.console.aliyun.com)。
2.  在左侧导航栏，选择**存储与快照** \> **云盘**。
3.  在顶部状态栏处，选择地域。
4.  找到目标ESSD云盘，在**操作**列，选择**更多** \> **修改性能级别**。 

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/655586/156161931550139_zh-CN.png)

5.  在修改性能级别窗口中，重新选择**性能级别**，单击**确定**。 

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/655586/156161931550141_zh-CN.png)


由于ESSD云盘可以选择的性能级别与存储容量有关，如果您的ESSD云盘无法选择更高性能级别，可以先[扩容云盘](cn.zh-CN/块存储/云盘/扩容云盘/扩容概述.md#)，再变更ESSD云盘性能级别。

