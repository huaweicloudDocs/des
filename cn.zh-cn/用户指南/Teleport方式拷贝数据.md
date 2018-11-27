# 拷贝数据<a name="ZH-CN_TOPIC_0098461123"></a>

Teleport在寄送给用户前，根据用户的需要，创建CIFS或NFS共享文件系统。

CIFS共享文件系统使用Windows客户端，NFS共享文件系统使用Linux或者Unix客户端，这两种方式将共享文件系统挂载到客户端，然后将数据拷贝至挂载的共享路径，相当于将数据拷贝至Teleport箱子中的存储设备中。

## CIFS共享文件系统拷贝数据<a name="section1404134717507"></a>

介绍cifs共享如何拷贝数据。

## 前提条件<a name="section19914716548"></a>

-   已经准备好需要上传华为云的用户数据。
-   已经完成Teleport连线及业务和逻辑IP地址配置。

## 操作步骤<a name="section19463103615498"></a>

1.  登录Windows客户端。
2.  进入“映射网络驱动器”对话框。右键单击“计算机”，选择“映射网络驱动器”。
3.  挂载CIFS共享路径。

    在“文件夹”文本框中输入“\\\\192.168.100.10\\teleportshare”，单击“完成”。

    >![](public_sys-resources/icon-note.gif) **说明：**   
    >其中192.168.100.10为[修改逻辑IP地址](修改逻辑IP地址.md)章节用户修改的逻辑IP，teleportshare是共享文件系统的共享名称，共享文件系统名称在Teleport出厂时已经创建好，用户无需自己创建。  

4.  将本地数据拷贝至teleportshare共享目录。

## NFS共享文件系统拷贝数据<a name="section7320182018511"></a>

介绍NFS共享如何拷贝数据。

## 前提条件<a name="zh-cn_topic_0097288785_section7579185019489"></a>

-   已经准备好需要上华为云的用户数据。
-   已经完成Teleport连线及业务和逻辑IP地址配置。

## 操作步骤<a name="section1862314507"></a>

1.  登录Linux/Unix服务器。
2.  挂载NFS共享的文件系统。

    在Linux/Unix本地创建一个挂载点，比如mkdir -p /mnt/folder，然后执行命令mount –t nfs 192.168.100.10:/teleportshare  /mnt/folder。

    >![](public_sys-resources/icon-note.gif) **说明：**   
    >其中192.168.100.10为[修改逻辑IP地址](修改逻辑IP地址.md)章节用户修改的逻辑IP，teleportshare是共享文件系统的共享名称，共享文件系统名称在Teleport出厂时已经创建好，用户无需自己创建。  

3.  将本地数据拷贝至/mnt/folder目录。

