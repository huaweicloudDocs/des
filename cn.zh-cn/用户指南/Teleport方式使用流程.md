# 使用流程<a name="des_01_0011"></a>

Teleport方式数据快递服务使用流程如[图1](#fig19847027133410)和[表1](#tab01)。

**图 1**  Teleport方式使用流程图<a name="fig19847027133410"></a>  
![](figures/Teleport方式使用流程图.png "Teleport方式使用流程图")

**表 1**  使用流程简介

<a name="tab01"></a>
<table><thead align="left"><tr id="row55845053"><th class="cellrowborder" valign="top" width="23.34%" id="mcps1.2.3.1.1"><p id="p27155410"><a name="p27155410"></a><a name="p27155410"></a>操作步骤</p>
</th>
<th class="cellrowborder" valign="top" width="76.66%" id="mcps1.2.3.1.2"><p id="p52104579"><a name="p52104579"></a><a name="p52104579"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row166683414297"><td class="cellrowborder" valign="top" width="23.34%" headers="mcps1.2.3.1.1 "><p id="p947415524285"><a name="p947415524285"></a><a name="p947415524285"></a>登录DES管理控制台</p>
</td>
<td class="cellrowborder" valign="top" width="76.66%" headers="mcps1.2.3.1.2 "><p id="p1647417523284"><a name="p1647417523284"></a><a name="p1647417523284"></a>注册华为云，并开通数据快递服务。</p>
</td>
</tr>
<tr id="row1295415177240"><td class="cellrowborder" valign="top" width="23.34%" headers="mcps1.2.3.1.1 "><p id="p1295515175242"><a name="p1295515175242"></a><a name="p1295515175242"></a>创建桶</p>
</td>
<td class="cellrowborder" valign="top" width="76.66%" headers="mcps1.2.3.1.2 "><p id="p20956171713240"><a name="p20956171713240"></a><a name="p20956171713240"></a>数据快递服务的数据最终存放在OBS中，需先在OBS创建桶。</p>
</td>
</tr>
<tr id="row59721402"><td class="cellrowborder" valign="top" width="23.34%" headers="mcps1.2.3.1.1 "><p id="p5595356"><a name="p5595356"></a><a name="p5595356"></a>创建服务单</p>
</td>
<td class="cellrowborder" valign="top" width="76.66%" headers="mcps1.2.3.1.2 "><p id="p50570707"><a name="p50570707"></a><a name="p50570707"></a>就近选择华为数据中心，选择创建Teleport方式服务单。</p>
</td>
</tr>
<tr id="row52483186"><td class="cellrowborder" valign="top" width="23.34%" headers="mcps1.2.3.1.1 "><p id="p23279683"><a name="p23279683"></a><a name="p23279683"></a>接收设备并连线配置</p>
</td>
<td class="cellrowborder" valign="top" width="76.66%" headers="mcps1.2.3.1.2 "><p id="p59455556"><a name="p59455556"></a><a name="p59455556"></a>用户收到华为数据中心Teleport设备后开箱配置。</p>
</td>
</tr>
<tr id="row64345914310"><td class="cellrowborder" valign="top" width="23.34%" headers="mcps1.2.3.1.1 "><p id="p1711645419"><a name="p1711645419"></a><a name="p1711645419"></a>拷贝数据</p>
</td>
<td class="cellrowborder" valign="top" width="76.66%" headers="mcps1.2.3.1.2 "><p id="p112184240"><a name="p112184240"></a><a name="p112184240"></a>用户将本地数据拷贝至Teleport存储系统。</p>
</td>
</tr>
<tr id="row65337958"><td class="cellrowborder" valign="top" width="23.34%" headers="mcps1.2.3.1.1 "><p id="p57883273"><a name="p57883273"></a><a name="p57883273"></a>下载并导入签名文件</p>
</td>
<td class="cellrowborder" valign="top" width="76.66%" headers="mcps1.2.3.1.2 "><p id="p58033516"><a name="p58033516"></a><a name="p58033516"></a>签名文件是服务单中Teleport设备的唯一标识，Teleport设备回寄前需要将签名文件存入teleportshare根目录。</p>
</td>
</tr>
<tr id="row9488102014167"><td class="cellrowborder" valign="top" width="23.34%" headers="mcps1.2.3.1.1 "><p id="p104891620181615"><a name="p104891620181615"></a><a name="p104891620181615"></a>设备下电和封装</p>
</td>
<td class="cellrowborder" valign="top" width="76.66%" headers="mcps1.2.3.1.2 "><p id="p8489162041611"><a name="p8489162041611"></a><a name="p8489162041611"></a>用户确保本地数据已全部存入Teleport后，将Teleport下电并封装。</p>
</td>
</tr>
<tr id="row52539597"><td class="cellrowborder" valign="top" width="23.34%" headers="mcps1.2.3.1.1 "><p id="p27848947"><a name="p27848947"></a><a name="p27848947"></a>回寄设备</p>
</td>
<td class="cellrowborder" valign="top" width="76.66%" headers="mcps1.2.3.1.2 "><p id="p41172271"><a name="p41172271"></a><a name="p41172271"></a>将Teleport回寄给华为数据中心，被回寄的Teleport存储系统中需要包含签名文件。</p>
</td>
</tr>
<tr id="row35006119"><td class="cellrowborder" valign="top" width="23.34%" headers="mcps1.2.3.1.1 "><p id="p16923420"><a name="p16923420"></a><a name="p16923420"></a>启动数据上传</p>
</td>
<td class="cellrowborder" valign="top" width="76.66%" headers="mcps1.2.3.1.2 "><p id="p28619802"><a name="p28619802"></a><a name="p28619802"></a>管理员将Teleport挂载到服务器，并且用户输入了AK/SK后，会启动数据上传。</p>
</td>
</tr>
<tr id="row56251627"><td class="cellrowborder" valign="top" width="23.34%" headers="mcps1.2.3.1.1 "><p id="p60087944"><a name="p60087944"></a><a name="p60087944"></a>查看数据传输结果</p>
</td>
<td class="cellrowborder" valign="top" width="76.66%" headers="mcps1.2.3.1.2 "><p id="p35285314"><a name="p35285314"></a><a name="p35285314"></a>完成数据传输后，用户可下载数据传输报告，检查数据是否全部上传成功。</p>
</td>
</tr>
</tbody>
</table>

