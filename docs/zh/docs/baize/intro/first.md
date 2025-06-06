# 首次使用

第一次进入 DCE 5.0 AI Lab 时，需要：

- [首次使用](#首次使用)
  - [选择工作空间](#选择工作空间)
  - [选择集群](#选择集群)
  - [角色](#角色)

另请参阅：

- [开发控制台快速入门](../developer/quick-start.md)
- [平台管理员运维管理](../oam/index.md)
- [AI Lab 最佳实践](../best-practice/deploy-nfs-in-worker.md)
- [AI Lab 故障排查](../troubleshoot/index.md)

## 选择工作空间

首次进入 DCE 5.0 AI Lab 时，首先必须选择一个[工作空间](../../ghippo/user-guide/workspace/workspace.md)。

![选择工作空间](../images/workspace.png)

如需更改当前所在的工作空间，可以在左侧边栏点击更换图标重新选择工作空间。

![更改工作空间](../images/change-ws.png)

!!! note

    如果当前没有可选的工作空间，需要先联系管理员创建一个工作空间。

## 选择集群

您可以选择在哪个集群部署和执行 AI Lab 相关的操作。

![选择集群](../images/cluster.png)

如果您想要的集群不在集群列表中，需要先去绑定集群和命名空间。

1. 点击左上角的图标，打开导航栏，点击 **全局管理** -> **工作空间与层级**

    ![导航栏](../images/bind01.png)

1. 从列表中找到你的工作空间（例如 `baize`），点击 **资源组** 页签，点击右侧的 **绑定资源** 按钮。

    ![点击绑定按钮](../images/bind02.png)

1. 勾选要绑定的命名空间、集群后，点击 **确定** 。

    ![绑定资源](../images/bind03.png)

1. 屏幕提示绑定成功，被绑定的集群和命名空间将显示在列表中。
   您还可以在这个页面授权给某个用户，添加更多资源组，创建共享资源等。

    ![资源组列表](../images/bind04.png)

## 角色

DCE 5.0 AI Lab 提供了两种角色，可以点击左下角的菜单项切换两种管理员角色：

- 管理员 - 开发控制台：可以处理 Notebook、训练任务和数据集等。
  参阅[开发控制台快速入门](../developer/quick-start.md)。
- 平台管理员 - [运维管理](../oam/index.md)：可以管理 GPU 资源、队列等

每个角色都有一个概览页面，通过图形仪表展示当前可以处理的数据。

![运维概览](../images/oam-overview.png)

[下载 DCE 5.0](../../download/index.md){ .md-button .md-button--primary }
[安装 DCE 5.0](../../install/index.md){ .md-button .md-button--primary }
[申请社区免费体验](../../dce/license0.md){ .md-button .md-button--primary }
