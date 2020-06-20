# API概览<a name="oms_api_0005"></a>

对象存储迁移服务提供了版本查询接口和任务管理接口，如[表1](#table711816643910)所示。

**表 1**  对象存储迁移服务接口列表

<a name="table711816643910"></a>
<table><thead align="left"><tr id="row511876123920"><th class="cellrowborder" valign="top" width="26.51%" id="mcps1.2.3.1.1"><p id="p1411896153912"><a name="p1411896153912"></a><a name="p1411896153912"></a>API</p>
</th>
<th class="cellrowborder" valign="top" width="73.49%" id="mcps1.2.3.1.2"><p id="p1911816153919"><a name="p1911816153919"></a><a name="p1911816153919"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row14118961396"><td class="cellrowborder" valign="top" width="26.51%" headers="mcps1.2.3.1.1 "><p id="p4118062397"><a name="p4118062397"></a><a name="p4118062397"></a><a href="查询API版本.md">查询API版本</a></p>
</td>
<td class="cellrowborder" valign="top" width="73.49%" headers="mcps1.2.3.1.2 "><p id="p4118367393"><a name="p4118367393"></a><a name="p4118367393"></a>查询对象存储迁移服务的API版本信息。</p>
</td>
</tr>
<tr id="row16118196103919"><td class="cellrowborder" valign="top" width="26.51%" headers="mcps1.2.3.1.1 "><p id="p411816620391"><a name="p411816620391"></a><a name="p411816620391"></a><a href="创建任务.md">创建任务</a></p>
</td>
<td class="cellrowborder" valign="top" width="73.49%" headers="mcps1.2.3.1.2 "><p id="p1111817673914"><a name="p1111817673914"></a><a name="p1111817673914"></a>添加迁移任务。</p>
</td>
</tr>
<tr id="row211820673916"><td class="cellrowborder" valign="top" width="26.51%" headers="mcps1.2.3.1.1 "><p id="p211816623917"><a name="p211816623917"></a><a name="p211816623917"></a><a href="删除任务.md">删除任务</a></p>
</td>
<td class="cellrowborder" valign="top" width="73.49%" headers="mcps1.2.3.1.2 "><p id="p1652410307224"><a name="p1652410307224"></a><a name="p1652410307224"></a>删除迁移任务。</p>
</td>
</tr>
<tr id="row211906163912"><td class="cellrowborder" valign="top" width="26.51%" headers="mcps1.2.3.1.1 "><p id="p4119206183910"><a name="p4119206183910"></a><a name="p4119206183910"></a><a href="启动任务.md">启动任务</a></p>
</td>
<td class="cellrowborder" valign="top" width="73.49%" headers="mcps1.2.3.1.2 "><p id="p6119663399"><a name="p6119663399"></a><a name="p6119663399"></a>任务暂停或失败后，启动任务。</p>
</td>
</tr>
<tr id="row1311976193915"><td class="cellrowborder" valign="top" width="26.51%" headers="mcps1.2.3.1.1 "><p id="p6119169391"><a name="p6119169391"></a><a name="p6119169391"></a><a href="停止任务.md">停止任务</a></p>
</td>
<td class="cellrowborder" valign="top" width="73.49%" headers="mcps1.2.3.1.2 "><p id="p1711910614395"><a name="p1711910614395"></a><a name="p1711910614395"></a>当任务正在运行中时，停止任务。</p>
</td>
</tr>
<tr id="row211956133914"><td class="cellrowborder" valign="top" width="26.51%" headers="mcps1.2.3.1.1 "><p id="p211917612391"><a name="p211917612391"></a><a name="p211917612391"></a><a href="修改流量控制策略.md">修改流量控制策略</a></p>
</td>
<td class="cellrowborder" valign="top" width="73.49%" headers="mcps1.2.3.1.2 "><p id="p31193683912"><a name="p31193683912"></a><a name="p31193683912"></a>当迁移任务未执行完成时，修改迁移任务的流量控制策略。</p>
</td>
</tr>
<tr id="row311915610390"><td class="cellrowborder" valign="top" width="26.51%" headers="mcps1.2.3.1.1 "><p id="p6119146183917"><a name="p6119146183917"></a><a name="p6119146183917"></a><a href="查询某个租户的所有任务.md">查询某个租户的所有任务</a></p>
</td>
<td class="cellrowborder" valign="top" width="73.49%" headers="mcps1.2.3.1.2 "><p id="p20119166103918"><a name="p20119166103918"></a><a name="p20119166103918"></a>查询某个租户的所有任务信息。</p>
</td>
</tr>
<tr id="row1511918611398"><td class="cellrowborder" valign="top" width="26.51%" headers="mcps1.2.3.1.1 "><p id="p81192633911"><a name="p81192633911"></a><a name="p81192633911"></a><a href="查询某个租户的任务总数.md">查询某个租户的任务总数</a></p>
</td>
<td class="cellrowborder" valign="top" width="73.49%" headers="mcps1.2.3.1.2 "><p id="p1111976163914"><a name="p1111976163914"></a><a name="p1111976163914"></a>查询某个租户的任务总数。</p>
</td>
</tr>
<tr id="row21196614392"><td class="cellrowborder" valign="top" width="26.51%" headers="mcps1.2.3.1.1 "><p id="p1911915613391"><a name="p1911915613391"></a><a name="p1911915613391"></a><a href="查询指定ID的任务.md">查询指定ID的任务</a></p>
</td>
<td class="cellrowborder" valign="top" width="73.49%" headers="mcps1.2.3.1.2 "><p id="p1510239162220"><a name="p1510239162220"></a><a name="p1510239162220"></a>查询租户指定ID的任务信息。</p>
</td>
</tr>
<tr id="row1619384414226"><td class="cellrowborder" valign="top" width="26.51%" headers="mcps1.2.3.1.1 "><p id="p61931744142219"><a name="p61931744142219"></a><a name="p61931744142219"></a><a href="查询租户配额数据.md">查询租户配额数据</a></p>
</td>
<td class="cellrowborder" valign="top" width="73.49%" headers="mcps1.2.3.1.2 "><p id="p20193244142211"><a name="p20193244142211"></a><a name="p20193244142211"></a>查询指定Domain的配额数据。</p>
</td>
</tr>
</tbody>
</table>

