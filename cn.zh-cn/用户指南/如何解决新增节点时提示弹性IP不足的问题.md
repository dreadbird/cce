# 如何解决新增节点时提示弹性IP不足的问题？<a name="cce_01_0081"></a>

## 问题描述<a name="s29366dd7fe2e4257bd9481f435155270"></a>

新增节点时，弹性IP选择“现在使用“，创建节点失败，提示弹性IP不足。

## 解决方法<a name="section35821611617"></a>

您可以有两种方法解决弹性IP不足的问题。

-   方法一：解绑已绑定弹性IP的虚拟机，再重新添加节点。
    1.  登录华为云控制台。
    2.  选择“网络\>  虚拟私有云“。
    3.  单击待解绑云服务器后的“解绑“，为该云服务器解绑弹性IP，单击“确定“。

        此时可看到界面提示：您还可以申请X个弹性IP，数量\>0即可。


-   方法二：提高弹性IP的配额，您需要通过“工单系统“来提交申请。

    云对用户的资源数量和容量做了限制。如果资源配额限制满足不了用户的使用需求，可以通过工单系统来提交您的申请，并告知您申请提高配额的理由。 在通过我们的审理之后，我们会更新您的配额并进行通知。


