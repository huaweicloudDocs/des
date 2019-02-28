# 下载并导入签名文件<a name="ZH-CN_TOPIC_0098461122"></a>

## 前提条件<a name="zh-cn_topic_0097289124_section113991610015"></a>

-   已经完成Teleport方式服务单的申请。
-   已经完成Teleport连线及业务和逻辑IP地址配置。

## 操作步骤<a name="zh-cn_topic_0097289124_section257282716118"></a>

1.  登录DES管理控制台。
2.  单击“操作 \> 下载签名文件”，将签名文件下载到本地。
3.  将下载到本地的签名文件导入“teleportshare”根目录。

    签名文件是服务单与Teleport设备一一对应的唯一标识。管理员收到磁盘后，将Teleport设备挂载到服务器上，系统根据签名文件自动匹配服务单，避免人为干预带来的误操作。签名文件信息如[表1](#table196554405593)。

    **表 1**  签名文件

    <a name="table196554405593"></a>
    <table><thead align="left"><tr id="row136551640125912"><th class="cellrowborder" valign="top" width="31.31%" id="mcps1.2.3.1.1"><p id="p12655540145913"><a name="p12655540145913"></a><a name="p12655540145913"></a>参数</p>
    </th>
    <th class="cellrowborder" valign="top" width="68.69%" id="mcps1.2.3.1.2"><p id="p19655940195914"><a name="p19655940195914"></a><a name="p19655940195914"></a>说明</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row17655114095918"><td class="cellrowborder" valign="top" width="31.31%" headers="mcps1.2.3.1.1 "><p id="p1665594035917"><a name="p1665594035917"></a><a name="p1665594035917"></a>version</p>
    </td>
    <td class="cellrowborder" valign="top" width="68.69%" headers="mcps1.2.3.1.2 "><p id="p8655114035917"><a name="p8655114035917"></a><a name="p8655114035917"></a>服务版本号。</p>
    </td>
    </tr>
    <tr id="row19655140105913"><td class="cellrowborder" valign="top" width="31.31%" headers="mcps1.2.3.1.1 "><p id="p1465519404598"><a name="p1465519404598"></a><a name="p1465519404598"></a>OrderURN</p>
    </td>
    <td class="cellrowborder" valign="top" width="68.69%" headers="mcps1.2.3.1.2 "><p id="p1065514095914"><a name="p1065514095914"></a><a name="p1065514095914"></a>包括服务名称、服务区域、标识码和服务单号。</p>
    </td>
    </tr>
    </tbody>
    </table>


