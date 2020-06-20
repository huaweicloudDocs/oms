# 创建用户并使用OMS<a name="oms_01_0022"></a>

如果您需要对您所拥有的OMS进行精细的权限管理，您可以使用[统一身份认证服务](https://support.huaweicloud.com/usermanual-iam/iam_01_0001.html)（Identity and Access Management，简称IAM），通过IAM，您可以：

-   根据企业的业务组织，在您的华为云账号中，给企业中不同职能部门的员工创建IAM用户，让员工拥有唯一安全凭证，并使用OMS。
-   根据企业用户的职能，设置不同的访问权限，以达到用户之间的权限隔离。
-   将OMS委托给更专业、高效的其他华为云账号或者云服务，这些账号或者云服务可以根据权限进行代运维。

如果华为云账号已经能满足您的要求，不需要创建独立的IAM用户，您可以跳过本章节，不影响您使用OMS的其它功能。

本章节为您介绍对用户授权的方法，操作流程如[图1](#fig22491610111212)所示。

## 前提条件<a name="section667633414252"></a>

给用户组授权之前，请您了解用户组可以添加的OMS权限，并结合实际需求进行选择，OMS支持的系统权限，请参见：[OMS系统权限](https://support.huaweicloud.com/productdesc-oms/oms_01_0020.html)。若您需要对除OMS之外的其它服务授权，IAM支持服务的所有权限请参见[权限策略](https://support.huaweicloud.com/permissions/policy_list.html?product=oms)。

## 示例流程<a name="section0134123631120"></a>

**图 1**  给用户授权OMS权限流程<a name="fig22491610111212"></a>  
![](figures/给用户授权OMS权限流程.png "给用户授权OMS权限流程")

1.  <a name="li922818215321"></a>[创建用户组并授权](https://support.huaweicloud.com/usermanual-iam/iam_03_0001.html)

    在IAM控制台创建用户组，并授予对象存储迁移服务“OMS Administrator”与“OBS OperateAccess”。

2.  [创建用户并加入用户组](https://support.huaweicloud.com/usermanual-iam/iam_02_0001.html)

    在IAM控制台创建用户，并将其加入[1](#li922818215321)中创建的用户组。

3.  [用户登录](https://support.huaweicloud.com/usermanual-iam/iam_01_0552.html)并验证权限

    新创建的用户登录控制台，切换至授权区域，验证权限：

    -   在“服务列表”中选择对象存储迁移服务，进入对象存储迁移服务主界面，单击右上角“创建迁移任务”，如果可以创建迁移任务，表示“OMS Administrator”已生效。
    -   在“服务列表”中选择除对象存储迁移服务外（假设当前策略仅包含OMS Administrator）的任一服务，若提示权限不足，表示“OMS Administrator”已生效。


