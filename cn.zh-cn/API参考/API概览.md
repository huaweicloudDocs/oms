# API概览<a name="oms_api_0005"></a>

对象存储迁移服务提供了版本查询接口和任务管理接口，如[表1](#table3122181416560)所示。

>![](public_sys-resources/icon-note.gif) **说明：** 
>当前v2接口仅支持华东-上海一（cn-east-3），其他区域暂正在陆续支持中，敬请期待。

**表 1**  对象存储迁移服务接口列表

<a name="table3122181416560"></a>
<table><thead align="left"><tr id="row412310143562"><th class="cellrowborder" valign="top" width="26.22%" id="mcps1.2.3.1.1"><p id="p512381418569"><a name="p512381418569"></a><a name="p512381418569"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="73.78%" id="mcps1.2.3.1.2"><p id="p10123151475619"><a name="p10123151475619"></a><a name="p10123151475619"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row636123723416"><td class="cellrowborder" valign="top" width="26.22%" headers="mcps1.2.3.1.1 "><p id="p1036193719341"><a name="p1036193719341"></a><a name="p1036193719341"></a><a href="查询API版本信息列表.md">查询API版本信息列表</a></p>
</td>
<td class="cellrowborder" valign="top" width="73.78%" headers="mcps1.2.3.1.2 "><p id="p136570207362"><a name="p136570207362"></a><a name="p136570207362"></a>查询对象存储迁移服务的API版本信息。</p>
</td>
</tr>
<tr id="row9655143323416"><td class="cellrowborder" valign="top" width="26.22%" headers="mcps1.2.3.1.1 "><p id="p9656133123419"><a name="p9656133123419"></a><a name="p9656133123419"></a><a href="查询指定API版本信息.md">查询指定API版本信息</a></p>
</td>
<td class="cellrowborder" valign="top" width="73.78%" headers="mcps1.2.3.1.2 "><p id="p16141902376"><a name="p16141902376"></a><a name="p16141902376"></a>查询对象存储迁移服务指定API版本信息。</p>
</td>
</tr>
<tr id="row212311435619"><td class="cellrowborder" valign="top" width="26.22%" headers="mcps1.2.3.1.1 "><p id="p116181541023"><a name="p116181541023"></a><a name="p116181541023"></a><a href="查询迁移任务列表.md">查询迁移任务列表</a></p>
</td>
<td class="cellrowborder" valign="top" width="73.78%" headers="mcps1.2.3.1.2 "><p id="p412634117206"><a name="p412634117206"></a><a name="p412634117206"></a>查询用户账户下的所有任务信息。</p>
</td>
</tr>
<tr id="row1727885014118"><td class="cellrowborder" valign="top" width="26.22%" headers="mcps1.2.3.1.1 "><p id="p162798501817"><a name="p162798501817"></a><a name="p162798501817"></a><a href="查询指定ID的任务详情.md">查询指定ID的任务详情</a></p>
</td>
<td class="cellrowborder" valign="top" width="73.78%" headers="mcps1.2.3.1.2 "><p id="zh-cn_topic_0245075032_p8671305"><a name="zh-cn_topic_0245075032_p8671305"></a><a name="zh-cn_topic_0245075032_p8671305"></a>查询指定ID的任务详情。</p>
</td>
</tr>
<tr id="row3123814115611"><td class="cellrowborder" valign="top" width="26.22%" headers="mcps1.2.3.1.1 "><p id="p2617441228"><a name="p2617441228"></a><a name="p2617441228"></a><a href="创建迁移任务.md">创建迁移任务</a></p>
</td>
<td class="cellrowborder" valign="top" width="73.78%" headers="mcps1.2.3.1.2 "><p id="p109710412205"><a name="p109710412205"></a><a name="p109710412205"></a>创建迁移任务。</p>
</td>
</tr>
<tr id="row852410300222"><td class="cellrowborder" valign="top" width="26.22%" headers="mcps1.2.3.1.1 "><p id="p1952493011221"><a name="p1952493011221"></a><a name="p1952493011221"></a><a href="启动迁移任务.md">启动迁移任务</a></p>
</td>
<td class="cellrowborder" valign="top" width="73.78%" headers="mcps1.2.3.1.2 "><p id="zh-cn_topic_0245075044_p58281439"><a name="zh-cn_topic_0245075044_p58281439"></a><a name="zh-cn_topic_0245075044_p58281439"></a>迁移任务暂停或失败后，调用该接口以启动任务。</p>
</td>
</tr>
<tr id="row7667203315228"><td class="cellrowborder" valign="top" width="26.22%" headers="mcps1.2.3.1.1 "><p id="p766773312216"><a name="p766773312216"></a><a name="p766773312216"></a><a href="暂停迁移任务.md">暂停迁移任务</a></p>
</td>
<td class="cellrowborder" valign="top" width="73.78%" headers="mcps1.2.3.1.2 "><p id="p1866717334221"><a name="p1866717334221"></a><a name="p1866717334221"></a>当任务正在运行中时，调用该接口停止任务。</p>
</td>
</tr>
<tr id="row52004368228"><td class="cellrowborder" valign="top" width="26.22%" headers="mcps1.2.3.1.1 "><p id="p4200133692215"><a name="p4200133692215"></a><a name="p4200133692215"></a><a href="删除迁移任务.md">删除迁移任务</a></p>
</td>
<td class="cellrowborder" valign="top" width="73.78%" headers="mcps1.2.3.1.2 "><p id="p5200536172218"><a name="p5200536172218"></a><a name="p5200536172218"></a>根据迁移任务ID，删除迁移任务。</p>
</td>
</tr>
<tr id="row0499265617"><td class="cellrowborder" valign="top" width="26.22%" headers="mcps1.2.3.1.1 "><p id="p45022616614"><a name="p45022616614"></a><a name="p45022616614"></a><a href="更新任务带宽策略.md">更新任务带宽策略</a></p>
</td>
<td class="cellrowborder" valign="top" width="73.78%" headers="mcps1.2.3.1.2 "><p id="p25015263619"><a name="p25015263619"></a><a name="p25015263619"></a>当迁移任务未执行完成时，修改迁移任务的流量控制策略。</p>
</td>
</tr>
</tbody>
</table>

