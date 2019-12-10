# 启动数据上传<a name="des_01_0024"></a>

## 前提条件<a name="zh-cn_topic_0097288934_section9405143635612"></a>

-   已经完成Teleport方式服务单的申请。

>![](public_sys-resources/icon-note.gif) **说明：**   
>如果用户在创建完服务单后已经输入了访问密钥（AK/SK），那么此处就不用再重复输入。设备回寄后管理员会直接启动数据上传。  

## 操作步骤<a name="zh-cn_topic_0097288934_section381632945813"></a>

1.  登录DES管理控制台。
2.  选择服务单列表“待输入访问密钥（AK/SK）”状态服务单，在操作列单击“输入访问密钥（AK/SK）”。
3.  根据界面提示，将后台往OBS桶中上传数据时需要使用的访问密钥（AK/SK），输入到弹出的对话框中。如[图1](#zh-cn_topic_0097288934_fig4199122815117)。

    **图 1**  输入访问密钥（Teleport方式）<a name="zh-cn_topic_0097288934_fig4199122815117"></a>  
    ![](figures/输入访问密钥（Teleport方式）.png "输入访问密钥（Teleport方式）")

    -   Access Key ID（AK）：后台往OBS桶中上传数据时需要使用的接入证书，一个AK对应唯一用户。
    -   Secret Access Key（SK）：后台往OBS桶中上传数据时需要使用的安全证书，SK与AK一一对应，形成访问OBS时的密钥对，确保访问安全。

        >![](public_sys-resources/icon-note.gif) **说明：**   
        >若没有访问密钥（AK/SK），请通过单击右上角用户名，并在下拉列表中单击“[我的凭证](https://console.huaweicloud.com/iam/#/myCredential)”，进入“我的凭证”界面，单击“管理访问密钥”页签下方的“新增访问密钥”，创建密钥。  


4.  单击“确定”，提交AK/SK。AK/SK提交成功，且后台验证AK/SK无误后，数据便开始上传。

