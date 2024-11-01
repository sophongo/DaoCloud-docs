# 系统角色

## 适用场景

算丰 AI 算力平台提供了预置的系统角色，帮助用户简化角色权限的使用步骤。

!!! note

   算丰 AI 算力平台提供了三种类型的系统角色，分别为平台角色、工作空间角色和文件夹角色。

    - 平台角色：对平台上所有相关资源具有相应权限，请前往用户/用户组授权。
    - 工作空间角色：对某个工作空间具有相应权限，请前往具体工作空间授权。
    - 文件夹角色：对某个文件夹、子文件夹及其工作空间下的资源具有相应权限，请前往具体文件夹授权。

## 平台角色

在用户与访问控制中预定义了 5 个系统角色，分别是：Admin、IAM Owner、Audit Owner、 Kpanda Owner 和 Workspace and Folder Owner 。这 5 个角色由系统创建，用户只能使用不能修改。角色对应的权限如下：

| 角色名称                   | 角色类型 | 所属模块       | 角色权限                                                                                                                                                      |
| -------------------------- | -------- | -------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Admin                      | 系统角色 | 全部           | 平台管理员，管理所有平台资源，代表平台的最高权限                                                                                                              |
| IAM Owner                  | 系统角色 | 用户与访问控制 | 用户与访问控制的管理员，拥有该服务下的所有权限，如管理用户/用户组及授权                                                                                       |
| Audit Owner                | 系统角色 | 审计日志       | 审计日志的管理员，拥有该服务下的所有权限，如设置审计日志策略，导出审计日志                                                                                    |
| Kpanda Owner               | 系统角色 | 容器管理       | 容器管理的管理员，拥有该服务下的所有权限，如创建/接入集群，部署应用，给用户/用户组授予集群/命名空间相关的权限                                                 |
| Workspace and Folder Owner | 系统角色 | 工作空间与层级 | 工作空间与层级管理员，拥有该服务下的所有权限，如创建文件夹/工作空间，给用户/用户组授权文件夹/工作空间的相关权限，在工作空间下使用应用工作台、微服务引擎等功能 |

## 工作空间角色

在用户与访问控制中预定义了 3 个系统角色，分别是：Workspace Admin、Workspace Editor、Workspace Viewer。这 3 个角色由系统创建，用户只能使用不能修改。角色对应的权限如下：

| 角色名称         | 角色类型 | 所属模块 | 角色权限           |
| ---------------- | -------- | -------- | ------------------ |
| Workspace Admin  | 系统角色 | 工作空间 | 工作空间的管理权限 |
| Workspace Editor | 系统角色 | 工作空间 | 工作空间的编辑权限 |
| Workspace Viewer | 系统角色 | 工作空间 | 工作空间的只读权限 |

## 文件夹角色

在用户与访问控制中预定义了 3 个系统角色，分别是：Folder Admin、Folder Editor、Folder Viewer。这 3 个角色由系统创建，用户只能使用不能修改。角色对应的权限如下：

| 角色名称      | 角色类型 | 所属模块 | 角色权限                                 |
| ------------- | -------- | -------- | ---------------------------------------- |
| Folder Admin  | 系统角色 | 工作空间 | 文件夹及其下子文件夹、工作空间的管理权限 |
| Folder Editor | 系统角色 | 工作空间 | 文件夹及其下子文件夹、工作空间的编辑权限 |
| Folder Viewer | 系统角色 | 工作空间 | 文件夹及其下子文件夹、工作空间的只读权限 |
