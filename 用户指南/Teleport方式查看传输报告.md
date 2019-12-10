# 查看传输报告<a name="des_01_0025"></a>

## 前提条件<a name="zh-cn_topic_0094556687_gen-id1.7.6.12.2"></a>

数据已传输完成。

## 背景信息<a name="zh-cn_topic_0094556687_gen-id1.7.6.12.4.2"></a>

数据传输完成后，用户可以下载数据传输报告检查数据是否全部上传成功。

## 操作步骤<a name="zh-cn_topic_0094556687_section32325424"></a>

1.  登录DES管理控制台。
2.  选择服务单列表中“已完成”状态服务单，单击操作列的“更多  \> 下载传输报告”。如[图1](#zh-cn_topic_0094556687_fig11222155451114)。

    **图 1**  下载传输报告（Teleport方式）<a name="zh-cn_topic_0094556687_fig11222155451114"></a>  
    ![](figures/下载传输报告（Teleport方式）.png "下载传输报告（Teleport方式）")

3.  查看数据传输报告，传输报告包含如[表1](#zh-cn_topic_0094556687_d0e3814)信息。

    **表 1**  数据传输报告参数

    <a name="zh-cn_topic_0094556687_d0e3814"></a>
    <table><thead align="left"><tr id="zh-cn_topic_0094556687_row36709949"><th class="cellrowborder" valign="top" width="39.34%" id="mcps1.2.3.1.1"><p id="p20715931"><a name="p20715931"></a><a name="p20715931"></a>参数</p>
    </th>
    <th class="cellrowborder" valign="top" width="60.660000000000004%" id="mcps1.2.3.1.2"><p id="p268861"><a name="p268861"></a><a name="p268861"></a>说明</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="zh-cn_topic_0094556687_row21777804"><td class="cellrowborder" valign="top" width="39.34%" headers="mcps1.2.3.1.1 "><p id="p19171695"><a name="p19171695"></a><a name="p19171695"></a>CapacityByteSize</p>
    </td>
    <td class="cellrowborder" valign="top" width="60.660000000000004%" headers="mcps1.2.3.1.2 "><p id="p9403471"><a name="p9403471"></a><a name="p9403471"></a>传输的总字节数</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0094556687_row17522377"><td class="cellrowborder" valign="top" width="39.34%" headers="mcps1.2.3.1.1 "><p id="p10026414"><a name="p10026414"></a><a name="p10026414"></a>SuccessByteSize</p>
    </td>
    <td class="cellrowborder" valign="top" width="60.660000000000004%" headers="mcps1.2.3.1.2 "><p id="p6833220"><a name="p6833220"></a><a name="p6833220"></a>传输成功的字节数</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0094556687_row61498985"><td class="cellrowborder" valign="top" width="39.34%" headers="mcps1.2.3.1.1 "><p id="p15361866"><a name="p15361866"></a><a name="p15361866"></a>FailByteSize</p>
    </td>
    <td class="cellrowborder" valign="top" width="60.660000000000004%" headers="mcps1.2.3.1.2 "><p id="p36351665"><a name="p36351665"></a><a name="p36351665"></a>传输失败的字节数</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0094556687_row58729529"><td class="cellrowborder" valign="top" width="39.34%" headers="mcps1.2.3.1.1 "><p id="p59471393"><a name="p59471393"></a><a name="p59471393"></a>TotalWrittenFiles</p>
    </td>
    <td class="cellrowborder" valign="top" width="60.660000000000004%" headers="mcps1.2.3.1.2 "><p id="p52453505"><a name="p52453505"></a><a name="p52453505"></a>传输成功的文件个数</p>
    </td>
    </tr>
    <tr id="row16540192834317"><td class="cellrowborder" valign="top" width="39.34%" headers="mcps1.2.3.1.1 "><p id="p5367175017387"><a name="p5367175017387"></a><a name="p5367175017387"></a>TotalFiles</p>
    </td>
    <td class="cellrowborder" valign="top" width="60.660000000000004%" headers="mcps1.2.3.1.2 "><p id="p554082814312"><a name="p554082814312"></a><a name="p554082814312"></a>传输的总文件个数</p>
    </td>
    </tr>
    </tbody>
    </table>

    >![](public_sys-resources/icon-note.gif) **说明：**   
    >Teleport挂载上传数据时，生成“xxx/deshare/_DES服务单_/_数据源目录_”的挂载前缀做传输密钥，比数据源目录层级多2级。但不影响数据在OBS目录结构，会保留Teleport设备中数据源目录结构。  


