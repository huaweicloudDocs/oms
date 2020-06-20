# 查询指定ID的任务<a name="oms_api_0021"></a>

## 功能介绍<a name="section50252788"></a>

查询租户指定ID的任务信息。

## URI<a name="section49621912"></a>

GET /v1/\{project\_id\}/objectstorage/task/\{task\_id\}

参数说明请参见[表1](#table48602288)。

**表 1**  参数说明

<a name="table48602288"></a>
<table><thead align="left"><tr id="row53442317"><th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.1"><p id="p33860402"><a name="p33860402"></a><a name="p33860402"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.2"><p id="p58338056"><a name="p58338056"></a><a name="p58338056"></a>是否必选</p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.3"><p id="p27762102"><a name="p27762102"></a><a name="p27762102"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row34137829"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p13700797"><a name="p13700797"></a><a name="p13700797"></a>project_id</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p14131123114107"><a name="p14131123114107"></a><a name="p14131123114107"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p109055560105"><a name="p109055560105"></a><a name="p109055560105"></a>项目ID。</p>
</td>
</tr>
<tr id="row721212435398"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p92121443183913"><a name="p92121443183913"></a><a name="p92121443183913"></a>task_id</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p1121244383917"><a name="p1121244383917"></a><a name="p1121244383917"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p1221394353912"><a name="p1221394353912"></a><a name="p1221394353912"></a>任务ID。</p>
</td>
</tr>
</tbody>
</table>

## 请求消息<a name="section2696221"></a>

**请求参数**

无。

## 响应消息<a name="section24265995"></a>

**响应参数**

响应参数如[表2](#table63691513)所示。

**表 2**  响应参数

<a name="table63691513"></a>
<table><thead align="left"><tr id="row22324024"><th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.1"><p id="p63415529"><a name="p63415529"></a><a name="p63415529"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.2"><p id="p36384226"><a name="p36384226"></a><a name="p36384226"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.3"><p id="p10683599"><a name="p10683599"></a><a name="p10683599"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row60065170"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p33440573"><a name="p33440573"></a><a name="p33440573"></a>id</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p24331897"><a name="p24331897"></a><a name="p24331897"></a>long</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p14201344171113"><a name="p14201344171113"></a><a name="p14201344171113"></a>任务ID。</p>
</td>
</tr>
<tr id="row40543448"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p62793889"><a name="p62793889"></a><a name="p62793889"></a>name</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p53140254"><a name="p53140254"></a><a name="p53140254"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p920115443111"><a name="p920115443111"></a><a name="p920115443111"></a>任务名称。</p>
</td>
</tr>
<tr id="row2638090"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p12358762"><a name="p12358762"></a><a name="p12358762"></a>src_node</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p61535683"><a name="p61535683"></a><a name="p61535683"></a>JSONObject</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p14645204716"><a name="p14645204716"></a><a name="p14645204716"></a>源端节点信息，参见<a href="#table15144322115115">表3</a>。</p>
</td>
</tr>
<tr id="row11110760"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p27556393"><a name="p27556393"></a><a name="p27556393"></a>dst_node</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p17475399"><a name="p17475399"></a><a name="p17475399"></a>JSONObject</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p4645154414"><a name="p4645154414"></a><a name="p4645154414"></a>目的端节点信息，参见<a href="#table4145422175118">表5</a>。</p>
</td>
</tr>
<tr id="row38979707"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p3239736"><a name="p3239736"></a><a name="p3239736"></a>thread_num</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p61092053"><a name="p61092053"></a><a name="p61092053"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p3645144912"><a name="p3645144912"></a><a name="p3645144912"></a>迁移线程数。</p>
</td>
</tr>
<tr id="row54777941"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p7828214"><a name="p7828214"></a><a name="p7828214"></a>status</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p30105629"><a name="p30105629"></a><a name="p30105629"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p108302511431"><a name="p108302511431"></a><a name="p108302511431"></a>任务状态。</p>
<a name="ul28301564311"></a><a name="ul28301564311"></a><ul id="ul28301564311"><li>0：初始化</li><li>1：等待调度</li><li>2：正在执行</li><li>3：停止</li><li>4：失败</li><li>5：成功</li></ul>
</td>
</tr>
<tr id="row60590285"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p8866062"><a name="p8866062"></a><a name="p8866062"></a>progress</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p47062423"><a name="p47062423"></a><a name="p47062423"></a>double</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p13831185114312"><a name="p13831185114312"></a><a name="p13831185114312"></a>任务进度，例如：0.522代表任务进度为52.2%，1代表任务进度为100%。</p>
</td>
</tr>
<tr id="row173901119101114"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p107881220101113"><a name="p107881220101113"></a><a name="p107881220101113"></a>migrate_speed</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p20788220171110"><a name="p20788220171110"></a><a name="p20788220171110"></a>long</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p77881520161110"><a name="p77881520161110"></a><a name="p77881520161110"></a>任务迁移速度（Byte/s）。</p>
</td>
</tr>
<tr id="row10358132142611"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p1630053322611"><a name="p1630053322611"></a><a name="p1630053322611"></a>enableKMS</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p030013352617"><a name="p030013352617"></a><a name="p030013352617"></a>boolean</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p10300163322619"><a name="p10300163322619"></a><a name="p10300163322619"></a>是否使用KMS加密。</p>
</td>
</tr>
<tr id="row17792611"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p31915390"><a name="p31915390"></a><a name="p31915390"></a>description</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p35009773"><a name="p35009773"></a><a name="p35009773"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p19867317124914"><a name="p19867317124914"></a><a name="p19867317124914"></a>任务描述，没有设置时为空字符串。</p>
</td>
</tr>
<tr id="row3550770"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p19176948"><a name="p19176948"></a><a name="p19176948"></a>error_reason</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p9828942"><a name="p9828942"></a><a name="p9828942"></a>JSONObject</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p12867161764913"><a name="p12867161764913"></a><a name="p12867161764913"></a>任务失败原因，参见<a href="#table2862813320539">表8</a>。</p>
</td>
</tr>
<tr id="row31783765"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p24348168"><a name="p24348168"></a><a name="p24348168"></a>total_size</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p26044600"><a name="p26044600"></a><a name="p26044600"></a>long</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p19454509"><a name="p19454509"></a><a name="p19454509"></a>任务迁移总大小。</p>
</td>
</tr>
<tr id="row61814476459"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p12245104817451"><a name="p12245104817451"></a><a name="p12245104817451"></a>complete_size</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p9245104810450"><a name="p9245104810450"></a><a name="p9245104810450"></a>long</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p624515482454"><a name="p624515482454"></a><a name="p624515482454"></a>任务迁移完成大小。</p>
</td>
</tr>
<tr id="row40872853"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p22366803"><a name="p22366803"></a><a name="p22366803"></a>start_time</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p66880658"><a name="p66880658"></a><a name="p66880658"></a>long</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p46250162"><a name="p46250162"></a><a name="p46250162"></a>任务启动时间。</p>
</td>
</tr>
<tr id="row13598275"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p27718519"><a name="p27718519"></a><a name="p27718519"></a>left_time</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p30607567"><a name="p30607567"></a><a name="p30607567"></a>long</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p26530317"><a name="p26530317"></a><a name="p26530317"></a>任务剩余时间。</p>
</td>
</tr>
<tr id="row37446265"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p13248604"><a name="p13248604"></a><a name="p13248604"></a>total_time</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p66503975"><a name="p66503975"></a><a name="p66503975"></a>long</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p57858711"><a name="p57858711"></a><a name="p57858711"></a>任务总时间。</p>
</td>
</tr>
<tr id="row12348334153349"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p17022440113649"><a name="p17022440113649"></a><a name="p17022440113649"></a>success_num</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p40079015153448"><a name="p40079015153448"></a><a name="p40079015153448"></a>long</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p25892786153448"><a name="p25892786153448"></a><a name="p25892786153448"></a>迁移成功对象数量。</p>
</td>
</tr>
<tr id="row39913237153359"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p61328195113649"><a name="p61328195113649"></a><a name="p61328195113649"></a>fail_num</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p1901641153448"><a name="p1901641153448"></a><a name="p1901641153448"></a>long</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p61532207153448"><a name="p61532207153448"></a><a name="p61532207153448"></a>迁移失败对象数量。</p>
</td>
</tr>
<tr id="row4016272515345"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p13751085113649"><a name="p13751085113649"></a><a name="p13751085113649"></a>total_num</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p7184874153448"><a name="p7184874153448"></a><a name="p7184874153448"></a>long</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p29536413153448"><a name="p29536413153448"></a><a name="p29536413153448"></a>迁移对象总数量。</p>
</td>
</tr>
<tr id="row5845758415345"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p6248626152822"><a name="p6248626152822"></a><a name="p6248626152822"></a>smnInfo</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p36376707152822"><a name="p36376707152822"></a><a name="p36376707152822"></a>JSONObject</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p28457638152822"><a name="p28457638152822"></a><a name="p28457638152822"></a>SMN消息，参见<a href="#table22451546104152">表6</a>。</p>
<div class="note" id="note54792157152822"><a name="note54792157152822"></a><a name="note54792157152822"></a><span class="notetitle"> 说明： </span><div class="notebody"><p id="p23367369152822"><a name="p23367369152822"></a><a name="p23367369152822"></a>用户可以选择是否发送SMN信息，在迁移任务已经结束的情况下才会有该字段。</p>
</div></div>
</td>
</tr>
<tr id="row18143175695914"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p3717181318017"><a name="p3717181318017"></a><a name="p3717181318017"></a>migrate_since</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p14717121318014"><a name="p14717121318014"></a><a name="p14717121318014"></a>long</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p1071710131609"><a name="p1071710131609"></a><a name="p1071710131609"></a>迁移指定时间，表示仅迁移在指定时间之后修改的源端待迁移对象。默认为0，表示不设置迁移指定时间。</p>
</td>
</tr>
<tr id="row52639611015"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p1971713131402"><a name="p1971713131402"></a><a name="p1971713131402"></a>task_type</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p1071814133020"><a name="p1071814133020"></a><a name="p1071814133020"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p1290062495512"><a name="p1290062495512"></a><a name="p1290062495512"></a>任务类型，为空则默认设置为object。</p>
<a name="ul14975428175715"></a><a name="ul14975428175715"></a><ul id="ul14975428175715"><li>list：对象列表迁移</li><li>object：文件/文件夹迁移</li><li>prefix：对象前缀迁移</li></ul>
</td>
</tr>
<tr id="row51087411014"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p8718151311012"><a name="p8718151311012"></a><a name="p8718151311012"></a>source_cdn</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p97181313100"><a name="p97181313100"></a><a name="p97181313100"></a>JSONObject</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p187188132016"><a name="p187188132016"></a><a name="p187188132016"></a>指定是否启用CDN迁移支持，参见<a href="#table66621617813">表7</a>。若包含此字段则为支持，否则为不支持。启用CDN迁移支持后，迁移时将从CDN域名获取源端对象。</p>
</td>
</tr>
<tr id="row1298923052715"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p5989330202710"><a name="p5989330202710"></a><a name="p5989330202710"></a>auto_restore</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p1398933019277"><a name="p1398933019277"></a><a name="p1398933019277"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p1827481910231"><a name="p1827481910231"></a><a name="p1827481910231"></a>是否自动解冻归档数据。开启后，如果遇到归档类型数据，会自动解冻再进行迁移。</p>
</td>
</tr>
<tr id="row6176162311552"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p337125817400"><a name="p337125817400"></a><a name="p337125817400"></a>enable_failed_object_recording</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p63091832415"><a name="p63091832415"></a><a name="p63091832415"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p10936559184112"><a name="p10936559184112"></a><a name="p10936559184112"></a>是否记录失败对象。开启后，如果有迁移失败对象，会在目的端存储失败对象信息。</p>
</td>
</tr>
<tr id="row981712685516"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p1637145812406"><a name="p1637145812406"></a><a name="p1637145812406"></a>failed_object_record</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p4309133194120"><a name="p4309133194120"></a><a name="p4309133194120"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p1193665964111"><a name="p1193665964111"></a><a name="p1193665964111"></a>数据格式为JSON格式，参见<a href="#table3822423134413">表9</a>。</p>
</td>
</tr>
<tr id="row012312221684"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p1243623415811"><a name="p1243623415811"></a><a name="p1243623415811"></a>bandwidth_policy</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p1243613414814"><a name="p1243613414814"></a><a name="p1243613414814"></a>JSONArray</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p143612341686"><a name="p143612341686"></a><a name="p143612341686"></a>流量控制策略，参见<a href="#table46231219659">表10</a>。</p>
</td>
</tr>
</tbody>
</table>

**表 3**  src\_node数据结构说明

<a name="table15144322115115"></a>
<table><thead align="left"><tr id="row5144162217516"><th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.1"><p id="p20144182214515"><a name="p20144182214515"></a><a name="p20144182214515"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.2"><p id="p101441922185110"><a name="p101441922185110"></a><a name="p101441922185110"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.3"><p id="p12145112285114"><a name="p12145112285114"></a><a name="p12145112285114"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row814572285120"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p13145122205115"><a name="p13145122205115"></a><a name="p13145122205115"></a>region</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p1014512227512"><a name="p1014512227512"></a><a name="p1014512227512"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p12145112295114"><a name="p12145112295114"></a><a name="p12145112295114"></a>源端桶所处的区域。</p>
</td>
</tr>
<tr id="row61441759115"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p157900518211"><a name="p157900518211"></a><a name="p157900518211"></a>list_file</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p9790755214"><a name="p9790755214"></a><a name="p9790755214"></a>JSONObject</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p9790115323"><a name="p9790115323"></a><a name="p9790115323"></a>数据格式为JSON格式，参见<a href="#table529111815568">表4</a>。</p>
</td>
</tr>
<tr id="row53606861114033"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p64953476114118"><a name="p64953476114118"></a><a name="p64953476114118"></a>object_key</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p26740167114118"><a name="p26740167114118"></a><a name="p26740167114118"></a>JSONArray</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p19671457114118"><a name="p19671457114118"></a><a name="p19671457114118"></a>源端桶选择的对象名称。每个元素均为对象的绝对路径。</p>
</td>
</tr>
<tr id="row6145172265110"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p514522212516"><a name="p514522212516"></a><a name="p514522212516"></a>bucket</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p31451722105120"><a name="p31451722105120"></a><a name="p31451722105120"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p8145102215112"><a name="p8145102215112"></a><a name="p8145102215112"></a>源端桶的名称。</p>
</td>
</tr>
<tr id="row31597039115441"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p44988939115443"><a name="p44988939115443"></a><a name="p44988939115443"></a>cloud_type</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p20225452115443"><a name="p20225452115443"></a><a name="p20225452115443"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p24969839115443"><a name="p24969839115443"></a><a name="p24969839115443"></a>源端云服务商。</p>
</td>
</tr>
</tbody>
</table>

**表 4**  list\_file数据结构

<a name="table529111815568"></a>
<table><thead align="left"><tr id="row12349121819565"><th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.1"><p id="p334911825614"><a name="p334911825614"></a><a name="p334911825614"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.2"><p id="p234941875615"><a name="p234941875615"></a><a name="p234941875615"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.3"><p id="p735061855612"><a name="p735061855612"></a><a name="p735061855612"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row173502018125615"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p113501918135613"><a name="p113501918135613"></a><a name="p113501918135613"></a>obs_bucket</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p183509183561"><a name="p183509183561"></a><a name="p183509183561"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p1235131817568"><a name="p1235131817568"></a><a name="p1235131817568"></a>存放对象列表文件的OBS桶名。</p>
</td>
</tr>
<tr id="row12351121814566"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p1435191817566"><a name="p1435191817566"></a><a name="p1435191817566"></a>list_file_key</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p33519189561"><a name="p33519189561"></a><a name="p33519189561"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p93511918125619"><a name="p93511918125619"></a><a name="p93511918125619"></a>对象列表文件对象名。</p>
</td>
</tr>
</tbody>
</table>

**表 5**  dst\_node数据结构说明

<a name="table4145422175118"></a>
<table><thead align="left"><tr id="row1814614223517"><th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.1"><p id="p12146122205110"><a name="p12146122205110"></a><a name="p12146122205110"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.2"><p id="p1114642218512"><a name="p1114642218512"></a><a name="p1114642218512"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.3"><p id="p1314622219511"><a name="p1314622219511"></a><a name="p1314622219511"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row4146172210512"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p111461622135118"><a name="p111461622135118"></a><a name="p111461622135118"></a>region</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p31461322145115"><a name="p31461322145115"></a><a name="p31461322145115"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p1614792275110"><a name="p1614792275110"></a><a name="p1614792275110"></a>目的端桶所处的区域。</p>
</td>
</tr>
<tr id="row214712229519"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p814717223517"><a name="p814717223517"></a><a name="p814717223517"></a>object_key</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p914782275120"><a name="p914782275120"></a><a name="p914782275120"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p1014792295117"><a name="p1014792295117"></a><a name="p1014792295117"></a>目的端桶选择的对象名称。</p>
</td>
</tr>
<tr id="row9147722125118"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p17147822115115"><a name="p17147822115115"></a><a name="p17147822115115"></a>bucket</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p16147122195117"><a name="p16147122195117"></a><a name="p16147122195117"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p1214732215117"><a name="p1214732215117"></a><a name="p1214732215117"></a>目的端桶的名称。</p>
</td>
</tr>
<tr id="row2074939811551"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p514517611554"><a name="p514517611554"></a><a name="p514517611554"></a>cloud_type</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p1410608711554"><a name="p1410608711554"></a><a name="p1410608711554"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p691561911554"><a name="p691561911554"></a><a name="p691561911554"></a>目的端云服务商。</p>
</td>
</tr>
</tbody>
</table>

**表 6**  smnInfo数据结构说明

<a name="table22451546104152"></a>
<table><thead align="left"><tr id="row22258128104152"><th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.1"><p id="p13911918105538"><a name="p13911918105538"></a><a name="p13911918105538"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.2"><p id="p53123568105538"><a name="p53123568105538"></a><a name="p53123568105538"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.3"><p id="p47401061105538"><a name="p47401061105538"></a><a name="p47401061105538"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row62342428104152"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p16571889104152"><a name="p16571889104152"></a><a name="p16571889104152"></a>notifyResult</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p145783104152"><a name="p145783104152"></a><a name="p145783104152"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p16961972104152"><a name="p16961972104152"></a><a name="p16961972104152"></a>记录迁移任务执行完毕后SMN消息是否发送成功。</p>
</td>
</tr>
<tr id="row23896932104152"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p51914120161356"><a name="p51914120161356"></a><a name="p51914120161356"></a>notifyErrorMessage</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p44294205161356"><a name="p44294205161356"></a><a name="p44294205161356"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p32899948161356"><a name="p32899948161356"></a><a name="p32899948161356"></a>记录SMN消息发送失败原因的错误码（迁移任务成功时为空）。</p>
</td>
</tr>
<tr id="row53770690161351"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p26197736161356"><a name="p26197736161356"></a><a name="p26197736161356"></a>topicName</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p41641876161356"><a name="p41641876161356"></a><a name="p41641876161356"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p12166077161356"><a name="p12166077161356"></a><a name="p12166077161356"></a>SMN Topic的名称（SMN消息发送成功时为空）。</p>
</td>
</tr>
</tbody>
</table>

**表 7**  source\_cdn数据结构

<a name="table66621617813"></a>
<table><thead align="left"><tr id="row575614171016"><th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.1"><p id="p107561017615"><a name="p107561017615"></a><a name="p107561017615"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.2"><p id="p17756717810"><a name="p17756717810"></a><a name="p17756717810"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.3"><p id="p137563178111"><a name="p137563178111"></a><a name="p137563178111"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row1075661719116"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p1475611715114"><a name="p1475611715114"></a><a name="p1475611715114"></a>protocol</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p177566171916"><a name="p177566171916"></a><a name="p177566171916"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p14756101714119"><a name="p14756101714119"></a><a name="p14756101714119"></a>协议类型：https或http。</p>
</td>
</tr>
<tr id="row117565171213"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p775611712116"><a name="p775611712116"></a><a name="p775611712116"></a>domain</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p5756151718120"><a name="p5756151718120"></a><a name="p5756151718120"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p675613171114"><a name="p675613171114"></a><a name="p675613171114"></a>从指定域名获取对象。</p>
</td>
</tr>
<tr id="row1756111719112"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p6756121718112"><a name="p6756121718112"></a><a name="p6756121718112"></a>authentication_type</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p9756131715113"><a name="p9756131715113"></a><a name="p9756131715113"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p11757617212"><a name="p11757617212"></a><a name="p11757617212"></a>鉴权方式。</p>
<a name="ul69231440182217"></a><a name="ul69231440182217"></a><ul id="ul69231440182217"><li>无需鉴权：NONE</li><li>Qiniu：QINIU_PRIVATE_AUTHENTICATION</li></ul>
</td>
</tr>
</tbody>
</table>

**表 8**  error\_reason数据结构说明

<a name="table2862813320539"></a>
<table><thead align="left"><tr id="row4639295420539"><th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.1"><p id="p6470529620539"><a name="p6470529620539"></a><a name="p6470529620539"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.2"><p id="p663765520539"><a name="p663765520539"></a><a name="p663765520539"></a>类型</p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.3"><p id="p6311080020539"><a name="p6311080020539"></a><a name="p6311080020539"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row3112629520539"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p3820197620539"><a name="p3820197620539"></a><a name="p3820197620539"></a>error_code</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p735235320539"><a name="p735235320539"></a><a name="p735235320539"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p5462974220539"><a name="p5462974220539"></a><a name="p5462974220539"></a>迁移失败的错误码。</p>
</td>
</tr>
<tr id="row2190563220539"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p2952573820539"><a name="p2952573820539"></a><a name="p2952573820539"></a>error_msg</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p4277456020539"><a name="p4277456020539"></a><a name="p4277456020539"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p6173393920539"><a name="p6173393920539"></a><a name="p6173393920539"></a>迁移失败的原因。</p>
</td>
</tr>
</tbody>
</table>

**表 9**  failed\_object\_record结构说明

<a name="table3822423134413"></a>
<table><thead align="left"><tr id="row984492304412"><th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.1"><p id="p12848223104415"><a name="p12848223104415"></a><a name="p12848223104415"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.2"><p id="p5859623154417"><a name="p5859623154417"></a><a name="p5859623154417"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.3"><p id="p98633231443"><a name="p98633231443"></a><a name="p98633231443"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row58682023104412"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p3472614184520"><a name="p3472614184520"></a><a name="p3472614184520"></a>result</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p12187162018453"><a name="p12187162018453"></a><a name="p12187162018453"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p496316314454"><a name="p496316314454"></a><a name="p496316314454"></a>是否支持失败对象重传。</p>
</td>
</tr>
<tr id="row4889112310449"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p047210146452"><a name="p047210146452"></a><a name="p047210146452"></a>list_file_key</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p201871120114520"><a name="p201871120114520"></a><a name="p201871120114520"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p596353115454"><a name="p596353115454"></a><a name="p596353115454"></a>失败对象列表文件路径。</p>
</td>
</tr>
<tr id="row14125154194515"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p124729145456"><a name="p124729145456"></a><a name="p124729145456"></a>errorCode</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p1318813204458"><a name="p1318813204458"></a><a name="p1318813204458"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p13963173124512"><a name="p13963173124512"></a><a name="p13963173124512"></a>不支持失败重传的错误码。</p>
</td>
</tr>
</tbody>
</table>

**表 10**  bandwidth\_policy数据结构

<a name="table46231219659"></a>
<table><thead align="left"><tr id="row271661919517"><th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.1"><p id="p971618192518"><a name="p971618192518"></a><a name="p971618192518"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.2"><p id="p1671610191857"><a name="p1671610191857"></a><a name="p1671610191857"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.3"><p id="p87160195516"><a name="p87160195516"></a><a name="p87160195516"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row1371619191951"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p1971616191754"><a name="p1971616191754"></a><a name="p1971616191754"></a>start</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p871791911515"><a name="p871791911515"></a><a name="p871791911515"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p44394316464"><a name="p44394316464"></a><a name="p44394316464"></a>流量控制开始时间（包含），格式为“hh:mm”。例如“10:03”表示10时03分。</p>
</td>
</tr>
<tr id="row14717161913510"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p771715191154"><a name="p771715191154"></a><a name="p771715191154"></a>end</p>
<p id="p107171019259"><a name="p107171019259"></a><a name="p107171019259"></a></p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p1671714191052"><a name="p1671714191052"></a><a name="p1671714191052"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p1743920313467"><a name="p1743920313467"></a><a name="p1743920313467"></a>流量控制结束时间（包含），格式和start参数相同。</p>
</td>
</tr>
<tr id="row12717141919511"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p17717161911510"><a name="p17717161911510"></a><a name="p17717161911510"></a>max_bandwidth</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p1971714191654"><a name="p1971714191654"></a><a name="p1971714191654"></a>int</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p147205190520"><a name="p147205190520"></a><a name="p147205190520"></a>时段内允许的最大流量带宽，单位Byte/s。</p>
</td>
</tr>
</tbody>
</table>

## 示例<a name="section17067371"></a>

**请求示例**

GET /v1/\{project\_id\}/objectstorage/task/\{task\_id\}

**响应示例**

```
{
	"id": 1,
	"name": "bucket3-bucket3-20161027211637786_544",
	"src_node": {
		"region": "us-east-1",
		"bucket": "bucket3",
		"object_key": "/",
		"cloud_type": "xxx"
	},
	"dst_node": {
		"region": "xxx",
		"bucket": "bucket3",
		"object_key": ["log/object1", "log/object2"],
		"cloud_type": "HEC"
	},
	"thread_num": 50,
	"status": 5,
	"progress": 1,
	"total_num": 2000,
	"success_num": 200,
	"fail_num": 0,
	"migrate_speed": 7213154,
	"enableKMS": true,
	"description": "ZXCZCZXCDVXVC",
	"error_reason": "",
	"total_size": 2000000000,
	"complete_size": 2000000000,
	"start_time": 1477574224062,
	"left_time": 0,
	"total_time": 88124,
	"smnInfo": {
		"notifyResult": false,
		"notifyErrorMessage": "S3M.0156",
		"topicName": "Test"
	},
	"migrate_since": 123456789,
	"source_cdn": {
		"protocol": "https",
		"domain": "xxx.xxx.xxx",
		"authentication_type": "NONE"
	},
        "bandwidth_policy": [ 
        { 
                "start": "00:00", 
                "end": "23:59", 
                "max_bandwidth": 50000000
        }
       ]
}
```

## 状态码<a name="section60897649"></a>

状态码请参见[状态码](状态码.md)。

