---
title: "主机"
---

登录 KubeSphere 管理控制台，访问左侧菜单栏，在**资源**菜单下，点击**主机管理**按钮，进入主机列表页面。作为集群管理员，可以查看当前集群下所有主机信息。  
## Taints 管理      
1. 点击右上角 **Taints 管理**按钮，进入集群主机 Taints 统一管理页面  
2. 在左侧节点列表中可以看到各个主机节点已有的 Taints 状态，选中相应节点，在右侧可以对其完成 Taints 的添加、删除、更新操作。 
![](/node_taints.png)  
3. 当对所需一个或者多个主机节点完成相应 Taints 编辑操作后，点击**应用**按钮，完成 Taints 配置的更新。
  

## 查看主机详情  
在主机列表页，点击某个主机节点打开其详情页，可以看到当前主机下所有资源的概况，点击相应资源，可以打开对应资源的详情页面查看更多细节信息。  
![](/node_detail.png)  

## 停用/启用主机（cordon/uncordon） 
在主机详情页面，点击左侧**停用（cordon）**按钮，主机状态变为**无法调度**，当前按钮变为**启用（uncordon）**，当有新的工作负载被创建时将不会被调度到此节点，如想回复为可调度状态，点击**启用（uncordon）**按钮。  
![](/node_uncordon.png)  

## 更新主机的标签（Labels） 
进入项目详情页面，点击左侧项目操作菜单, 点击**编辑标签**按钮当前主机上的标签。  
![](/node_labels_edit.png)  
最后点击**确认**按钮完成修改。  