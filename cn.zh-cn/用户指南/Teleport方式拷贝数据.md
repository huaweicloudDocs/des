# 拷贝数据<a name="des_01_0028"></a>

Teleport在寄送给用户前，根据用户的需要，管理员会创建CIFS或NFS共享文件系统。

CIFS共享文件系统使用Windows客户端，NFS共享文件系统使用Linux或者Unix客户端，这两种方式将共享文件系统挂载到客户端，然后将数据拷贝至挂载的共享路径，相当于将数据拷贝至Teleport设备中。

## CIFS共享文件系统拷贝数据<a name="section1404134717507"></a>

介绍CIFS共享如何拷贝数据。

**前提条件**

-   已经准备好需要上传的数据。
-   已经完成Teleport连线和配置。

**操作步骤**

1.  登录Windows客户端。
2.  进入“映射网络驱动器”对话框。右键单击“计算机”，选择“映射网络驱动器”。
3.  挂载CIFS共享路径。

    在“文件夹”文本框中输入“\\\\192.168.100.10\\teleportshare”，单击“完成”。

    >![](public_sys-resources/icon-note.gif) **说明：** 
    >其中192.168.100.10为用户修改的逻辑端口IP，teleportshare是共享文件系统的共享名称，共享文件系统名称在Teleport出厂时已经创建好，用户无需自己创建。

4.  将本地数据拷贝至teleportshare共享目录。

## NFS共享文件系统拷贝数据<a name="section7320182018511"></a>

介绍NFS共享如何拷贝数据。

**前提条件**

-   已经准备好需要上传的数据。
-   已经完成Teleport连线和配置。

**操作步骤**

1.  登录Linux/Unix服务器。
2.  挂载NFS共享的文件系统。

    在Linux/Unix本地创建一个挂载点，比如mkdir -p /mnt/folder，然后执行命令mount –t nfs 192.168.100.10:/teleportshare  /mnt/folder。

    >![](public_sys-resources/icon-note.gif) **说明：** 
    >其中192.168.100.10为用户修改的逻辑端口IP，teleportshare是共享文件系统的共享名称，共享文件系统名称在Teleport出厂时已经创建好，用户无需自己创建。

3.  将本地数据拷贝至/mnt/folder目录。

