# 使用流程<a name="ZH-CN_TOPIC_0102348052"></a>

Teleport方式数据快递服务使用流程如[图 Teleport方式使用流程图](#fig19847027133410)和[表 Teleport方式使用流程简介](#tab01)所示。

**图 1**  Teleport方式使用流程图<a name="fig19847027133410"></a>  
![](figures/Teleport方式使用流程图.png "Teleport方式使用流程图")

**表 1**  Teleport方式使用流程简介

<a name="tab01"></a>
<table><thead align="left"><tr id="row55845053"><th class="cellrowborder" valign="top" width="24.64%" id="mcps1.2.3.1.1"><p id="p27155410"><a name="p27155410"></a><a name="p27155410"></a>操作步骤</p>
</th>
<th class="cellrowborder" valign="top" width="75.36%" id="mcps1.2.3.1.2"><p id="p52104579"><a name="p52104579"></a><a name="p52104579"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row3453113163619"><td class="cellrowborder" valign="top" width="24.64%" headers="mcps1.2.3.1.1 "><p id="p1845453117360"><a name="p1845453117360"></a><a name="p1845453117360"></a>选择数据中心</p>
</td>
<td class="cellrowborder" valign="top" width="75.36%" headers="mcps1.2.3.1.2 "><p id="p24541431193613"><a name="p24541431193613"></a><a name="p24541431193613"></a>支持就近选择华为数据中心。</p>
</td>
</tr>
<tr id="row1295415177240"><td class="cellrowborder" valign="top" width="24.64%" headers="mcps1.2.3.1.1 "><p id="p1295515175242"><a name="p1295515175242"></a><a name="p1295515175242"></a>创建桶</p>
</td>
<td class="cellrowborder" valign="top" width="75.36%" headers="mcps1.2.3.1.2 "><p id="p20956171713240"><a name="p20956171713240"></a><a name="p20956171713240"></a>数据快递服务的数据最终存放在OBS中，须先在OBS创建桶。</p>
</td>
</tr>
<tr id="row59721402"><td class="cellrowborder" valign="top" width="24.64%" headers="mcps1.2.3.1.1 "><p id="p5595356"><a name="p5595356"></a><a name="p5595356"></a>创建服务单</p>
</td>
<td class="cellrowborder" valign="top" width="75.36%" headers="mcps1.2.3.1.2 "><p id="p50570707"><a name="p50570707"></a><a name="p50570707"></a>使用数据快递服务，选择创建Teleport方式服务单。</p>
</td>
</tr>
<tr id="row52483186"><td class="cellrowborder" valign="top" width="24.64%" headers="mcps1.2.3.1.1 "><p id="p23279683"><a name="p23279683"></a><a name="p23279683"></a>Teleport连线配置</p>
</td>
<td class="cellrowborder" valign="top" width="75.36%" headers="mcps1.2.3.1.2 "><p id="p59455556"><a name="p59455556"></a><a name="p59455556"></a>用户收到华为数据中心寄出的Teleport设备后。</p>
</td>
</tr>
<tr id="row64345914310"><td class="cellrowborder" valign="top" width="24.64%" headers="mcps1.2.3.1.1 "><p id="p1711645419"><a name="p1711645419"></a><a name="p1711645419"></a>拷贝数据</p>
</td>
<td class="cellrowborder" valign="top" width="75.36%" headers="mcps1.2.3.1.2 "><p id="p112184240"><a name="p112184240"></a><a name="p112184240"></a>用户将本地数据拷贝至Teleport存储系统。</p>
</td>
</tr>
<tr id="row65337958"><td class="cellrowborder" valign="top" width="24.64%" headers="mcps1.2.3.1.1 "><p id="p57883273"><a name="p57883273"></a><a name="p57883273"></a>下载签名文件</p>
</td>
<td class="cellrowborder" valign="top" width="75.36%" headers="mcps1.2.3.1.2 "><p id="p58033516"><a name="p58033516"></a><a name="p58033516"></a>签名文件是服务单中Teleport的唯一标识，Teleport回寄前需要将签名文件存入teleportshare根目录。</p>
</td>
</tr>
<tr id="row9488102014167"><td class="cellrowborder" valign="top" width="24.64%" headers="mcps1.2.3.1.1 "><p id="p104891620181615"><a name="p104891620181615"></a><a name="p104891620181615"></a>Teleport下电封装</p>
</td>
<td class="cellrowborder" valign="top" width="75.36%" headers="mcps1.2.3.1.2 "><p id="p8489162041611"><a name="p8489162041611"></a><a name="p8489162041611"></a>用户确保本地数据已全部存入Teleport后，准备回寄Teleport。</p>
</td>
</tr>
<tr id="row52539597"><td class="cellrowborder" valign="top" width="24.64%" headers="mcps1.2.3.1.1 "><p id="p27848947"><a name="p27848947"></a><a name="p27848947"></a>回寄Teleport到华为数据中心</p>
</td>
<td class="cellrowborder" valign="top" width="75.36%" headers="mcps1.2.3.1.2 "><p id="p41172271"><a name="p41172271"></a><a name="p41172271"></a>被回寄的Teleport存储系统中需要包含签名文件。</p>
</td>
</tr>
<tr id="row35006119"><td class="cellrowborder" valign="top" width="24.64%" headers="mcps1.2.3.1.1 "><p id="p16923420"><a name="p16923420"></a><a name="p16923420"></a>输入访问密钥（AK/SK）</p>
</td>
<td class="cellrowborder" valign="top" width="75.36%" headers="mcps1.2.3.1.2 "><p id="p28619802"><a name="p28619802"></a><a name="p28619802"></a>华为数据中心管理员将Teleport挂载到服务器后，会短信通知用户上传AK/SK，启动数据上传。</p>
</td>
</tr>
<tr id="row56251627"><td class="cellrowborder" valign="top" width="24.64%" headers="mcps1.2.3.1.1 "><p id="p60087944"><a name="p60087944"></a><a name="p60087944"></a>查看数据传输结果</p>
</td>
<td class="cellrowborder" valign="top" width="75.36%" headers="mcps1.2.3.1.2 "><p id="p35285314"><a name="p35285314"></a><a name="p35285314"></a>数据传输完成后，用户可以下载数据传输报告，检查数据是否全部上传成功。</p>
</td>
</tr>
</tbody>
</table>

