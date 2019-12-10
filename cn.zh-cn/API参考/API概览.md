# API概览<a name="ZH-CN_TOPIC_0126405303"></a>

对象存储迁移服务提供了版本查询接口和任务管理接口，如[表1](#table3122181416560)所示。

**表 1**  对象存储迁移服务接口列表

<a name="table3122181416560"></a>
<table><thead align="left"><tr id="row412310143562"><th class="cellrowborder" valign="top" width="50%" id="mcps1.2.3.1.1"><p id="p512381418569"><a name="p512381418569"></a><a name="p512381418569"></a>API</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.2.3.1.2"><p id="p10123151475619"><a name="p10123151475619"></a><a name="p10123151475619"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row212311435619"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.1 "><p id="p116181541023"><a name="p116181541023"></a><a name="p116181541023"></a><a href="查询API版本.md">查询API版本</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.2 "><p id="p412634117206"><a name="p412634117206"></a><a name="p412634117206"></a>查询对象存储迁移服务的API版本信息。</p>
</td>
</tr>
<tr id="row3123814115611"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.1 "><p id="p2617441228"><a name="p2617441228"></a><a name="p2617441228"></a><a href="创建任务.md">创建任务</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.2 "><p id="p109710412205"><a name="p109710412205"></a><a name="p109710412205"></a>添加迁移任务。</p>
</td>
</tr>
<tr id="row852410300222"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.1 "><p id="p1952493011221"><a name="p1952493011221"></a><a name="p1952493011221"></a><a href="删除任务.md">删除任务</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.2 "><p id="p1652410307224"><a name="p1652410307224"></a><a name="p1652410307224"></a>删除迁移任务。</p>
</td>
</tr>
<tr id="row7667203315228"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.1 "><p id="p766773312216"><a name="p766773312216"></a><a name="p766773312216"></a><a href="启动任务.md">启动任务</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.2 "><p id="p1866717334221"><a name="p1866717334221"></a><a name="p1866717334221"></a>任务暂停或失败后，启动任务。</p>
</td>
</tr>
<tr id="row52004368228"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.1 "><p id="p4200133692215"><a name="p4200133692215"></a><a name="p4200133692215"></a><a href="停止任务.md">停止任务</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.2 "><p id="p5200536172218"><a name="p5200536172218"></a><a name="p5200536172218"></a>当任务正在运行中时，停止任务。</p>
</td>
</tr>
<tr id="row399213132915"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.1 "><p id="p999314302913"><a name="p999314302913"></a><a name="p999314302913"></a><a href="修改流量控制策略.md">修改流量控制策略</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.2 "><p id="p79938318297"><a name="p79938318297"></a><a name="p79938318297"></a>当迁移任务未执行完成时，修改迁移任务的流量控制策略。</p>
</td>
</tr>
<tr id="row1183834618227"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.1 "><p id="p283811463227"><a name="p283811463227"></a><a name="p283811463227"></a><a href="查询某个租户的所有任务.md">查询某个租户的所有任务</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.2 "><p id="p5838114672216"><a name="p5838114672216"></a><a name="p5838114672216"></a>查询某个租户的所有任务信息。</p>
</td>
</tr>
<tr id="row1710132842216"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.1 "><p id="p10104289221"><a name="p10104289221"></a><a name="p10104289221"></a><a href="查询某个租户的任务总数.md">查询某个租户的任务总数</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.2 "><p id="p910192820223"><a name="p910192820223"></a><a name="p910192820223"></a>查询某个租户的任务总数。</p>
</td>
</tr>
<tr id="row451018391225"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.1 "><p id="p115101339182216"><a name="p115101339182216"></a><a name="p115101339182216"></a><a href="查询指定ID的任务.md">查询指定ID的任务</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.2 "><p id="p1510239162220"><a name="p1510239162220"></a><a name="p1510239162220"></a>查询租户指定ID的任务信息。</p>
</td>
</tr>
<tr id="row1619384414226"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.1 "><p id="p61931744142219"><a name="p61931744142219"></a><a name="p61931744142219"></a><a href="查询租户配额数据.md">查询租户配额数据</a></p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.2 "><p id="p20193244142211"><a name="p20193244142211"></a><a name="p20193244142211"></a>查询指定Domain的配额数据。</p>
</td>
</tr>
</tbody>
</table>

