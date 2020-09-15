# 查询指定ID的任务详情<a name="oms_api_0039"></a>

## 功能介绍<a name="zh-cn_topic_0245075032_section50252788"></a>

查询指定ID的任务详情。

## URI<a name="zh-cn_topic_0245075032_section49621912"></a>

GET /v2/\{project\_id\}/tasks/\{task\_id\}

**表 1**  参数说明

<a name="zh-cn_topic_0245075032_table48602288"></a>
<table><thead align="left"><tr id="zh-cn_topic_0245075032_row53442317"><th class="cellrowborder" valign="top" width="19.27807219278072%" id="mcps1.2.5.1.1"><p id="zh-cn_topic_0245075032_p33860402"><a name="zh-cn_topic_0245075032_p33860402"></a><a name="zh-cn_topic_0245075032_p33860402"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="15.208479152084792%" id="mcps1.2.5.1.2"><p id="zh-cn_topic_0245075032_p58338056"><a name="zh-cn_topic_0245075032_p58338056"></a><a name="zh-cn_topic_0245075032_p58338056"></a>是否必选</p>
</th>
<th class="cellrowborder" valign="top" width="16.60833916608339%" id="mcps1.2.5.1.3"><p id="zh-cn_topic_0245075032_p3745342181017"><a name="zh-cn_topic_0245075032_p3745342181017"></a><a name="zh-cn_topic_0245075032_p3745342181017"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="48.90510948905109%" id="mcps1.2.5.1.4"><p id="zh-cn_topic_0245075032_p27762102"><a name="zh-cn_topic_0245075032_p27762102"></a><a name="zh-cn_topic_0245075032_p27762102"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="zh-cn_topic_0245075032_row34137829"><td class="cellrowborder" valign="top" width="19.27807219278072%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0245075032_p13700797"><a name="zh-cn_topic_0245075032_p13700797"></a><a name="zh-cn_topic_0245075032_p13700797"></a>project_id</p>
</td>
<td class="cellrowborder" valign="top" width="15.208479152084792%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0245075032_p14131123114107"><a name="zh-cn_topic_0245075032_p14131123114107"></a><a name="zh-cn_topic_0245075032_p14131123114107"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="16.60833916608339%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0245075032_p4745942201011"><a name="zh-cn_topic_0245075032_p4745942201011"></a><a name="zh-cn_topic_0245075032_p4745942201011"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="48.90510948905109%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0245075032_p109055560105"><a name="zh-cn_topic_0245075032_p109055560105"></a><a name="zh-cn_topic_0245075032_p109055560105"></a>项目ID。</p>
<p id="zh-cn_topic_0245075032_p4284113175219"><a name="zh-cn_topic_0245075032_p4284113175219"></a><a name="zh-cn_topic_0245075032_p4284113175219"></a>获取方式请参见<a href="获取项目ID.md">获取项目ID</a>。</p>
</td>
</tr>
<tr id="zh-cn_topic_0245075032_row721212435398"><td class="cellrowborder" valign="top" width="19.27807219278072%" headers="mcps1.2.5.1.1 "><p id="zh-cn_topic_0245075032_p92121443183913"><a name="zh-cn_topic_0245075032_p92121443183913"></a><a name="zh-cn_topic_0245075032_p92121443183913"></a>task_id</p>
</td>
<td class="cellrowborder" valign="top" width="15.208479152084792%" headers="mcps1.2.5.1.2 "><p id="zh-cn_topic_0245075032_p1121244383917"><a name="zh-cn_topic_0245075032_p1121244383917"></a><a name="zh-cn_topic_0245075032_p1121244383917"></a>是</p>
</td>
<td class="cellrowborder" valign="top" width="16.60833916608339%" headers="mcps1.2.5.1.3 "><p id="zh-cn_topic_0245075032_p738231695211"><a name="zh-cn_topic_0245075032_p738231695211"></a><a name="zh-cn_topic_0245075032_p738231695211"></a>Long</p>
</td>
<td class="cellrowborder" valign="top" width="48.90510948905109%" headers="mcps1.2.5.1.4 "><p id="zh-cn_topic_0245075032_p1221394353912"><a name="zh-cn_topic_0245075032_p1221394353912"></a><a name="zh-cn_topic_0245075032_p1221394353912"></a>迁移任务ID。</p>
<p id="zh-cn_topic_0245075032_p1792986165315"><a name="zh-cn_topic_0245075032_p1792986165315"></a><a name="zh-cn_topic_0245075032_p1792986165315"></a>请参见<a href="查询迁移任务列表.md#zh-cn_topic_0245075054_table46441279">表4</a>中获取的id。</p>
</td>
</tr>
</tbody>
</table>

## 请求消息<a name="zh-cn_topic_0245075032_section58606859"></a>

-   请求参数：

    无

-   请求样例

    查询2c0689c860ad4728a497xxxxc0844383项目下的id为191297407830872的迁移任务详情。

    ```
     GET https://{endpoint}/v2/2c0689c860ad4728a497xxxxc0844383/tasks/191297407830872
    ```


## 响应消息<a name="zh-cn_topic_0245075032_section57699690"></a>

-   响应参数

    **表 2**  参数说明

    <a name="zh-cn_topic_0245075032_table46441279"></a>
    <table><thead align="left"><tr id="zh-cn_topic_0245075032_row14081115"><th class="cellrowborder" valign="top" width="23.742374237423743%" id="mcps1.2.4.1.1"><p id="zh-cn_topic_0245075032_p66828554"><a name="zh-cn_topic_0245075032_p66828554"></a><a name="zh-cn_topic_0245075032_p66828554"></a>参数</p>
    </th>
    <th class="cellrowborder" valign="top" width="18.871887188718873%" id="mcps1.2.4.1.2"><p id="zh-cn_topic_0245075032_p44403789"><a name="zh-cn_topic_0245075032_p44403789"></a><a name="zh-cn_topic_0245075032_p44403789"></a>参数类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="57.38573857385738%" id="mcps1.2.4.1.3"><p id="zh-cn_topic_0245075032_p13684913"><a name="zh-cn_topic_0245075032_p13684913"></a><a name="zh-cn_topic_0245075032_p13684913"></a>描述</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="zh-cn_topic_0245075032_row20978142431113"><td class="cellrowborder" valign="top" width="23.742374237423743%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p22981929415"><a name="zh-cn_topic_0245075032_p22981929415"></a><a name="zh-cn_topic_0245075032_p22981929415"></a>bandwidth_policy</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.871887188718873%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p1329817217410"><a name="zh-cn_topic_0245075032_p1329817217410"></a><a name="zh-cn_topic_0245075032_p1329817217410"></a>JSONArray</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.38573857385738%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p42985214417"><a name="zh-cn_topic_0245075032_p42985214417"></a><a name="zh-cn_topic_0245075032_p42985214417"></a>流量控制策略，每个任务最多可设置5条限速策略。参见<a href="#zh-cn_topic_0245075032_table874721174417">表3</a>。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0245075032_row13632163410112"><td class="cellrowborder" valign="top" width="23.742374237423743%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p1234315114312"><a name="zh-cn_topic_0245075032_p1234315114312"></a><a name="zh-cn_topic_0245075032_p1234315114312"></a>complete_size</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.871887188718873%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p4234615114318"><a name="zh-cn_topic_0245075032_p4234615114318"></a><a name="zh-cn_topic_0245075032_p4234615114318"></a>long</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.38573857385738%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p18234715194311"><a name="zh-cn_topic_0245075032_p18234715194311"></a><a name="zh-cn_topic_0245075032_p18234715194311"></a>任务迁移完成大小，单位：Byte。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0245075032_row35631630201211"><td class="cellrowborder" valign="top" width="23.742374237423743%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p6578555"><a name="zh-cn_topic_0245075032_p6578555"></a><a name="zh-cn_topic_0245075032_p6578555"></a>description</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.871887188718873%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p63100926"><a name="zh-cn_topic_0245075032_p63100926"></a><a name="zh-cn_topic_0245075032_p63100926"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.38573857385738%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p10594405"><a name="zh-cn_topic_0245075032_p10594405"></a><a name="zh-cn_topic_0245075032_p10594405"></a>任务描述，没有设置时为空字符串。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0245075032_row29181594154"><td class="cellrowborder" valign="top" width="23.742374237423743%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p27217289"><a name="zh-cn_topic_0245075032_p27217289"></a><a name="zh-cn_topic_0245075032_p27217289"></a>dst_node</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.871887188718873%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p57116823"><a name="zh-cn_topic_0245075032_p57116823"></a><a name="zh-cn_topic_0245075032_p57116823"></a>JSONObject</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.38573857385738%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p920154914010"><a name="zh-cn_topic_0245075032_p920154914010"></a><a name="zh-cn_topic_0245075032_p920154914010"></a>目的端节点信息，参见<a href="#zh-cn_topic_0245075032_table365310144019">表4</a>。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0245075032_row167620193584"><td class="cellrowborder" valign="top" width="23.742374237423743%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p97132211570"><a name="zh-cn_topic_0245075032_p97132211570"></a><a name="zh-cn_topic_0245075032_p97132211570"></a>enable_failed_object_recording</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.871887188718873%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p1070227570"><a name="zh-cn_topic_0245075032_p1070227570"></a><a name="zh-cn_topic_0245075032_p1070227570"></a>Boolean</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.38573857385738%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p971722145710"><a name="zh-cn_topic_0245075032_p971722145710"></a><a name="zh-cn_topic_0245075032_p971722145710"></a>是否记录失败对象。开启后，如果有迁移失败对象，会在目的端存储失败对象信息。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0245075032_row6304113599"><td class="cellrowborder" valign="top" width="23.742374237423743%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p1771822599"><a name="zh-cn_topic_0245075032_p1771822599"></a><a name="zh-cn_topic_0245075032_p1771822599"></a>enable_kms</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.871887188718873%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p12722155910"><a name="zh-cn_topic_0245075032_p12722155910"></a><a name="zh-cn_topic_0245075032_p12722155910"></a>Boolean</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.38573857385738%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p572027598"><a name="zh-cn_topic_0245075032_p572027598"></a><a name="zh-cn_topic_0245075032_p572027598"></a>是否使用KMS加密。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0245075032_row10648171416592"><td class="cellrowborder" valign="top" width="23.742374237423743%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p16837173772511"><a name="zh-cn_topic_0245075032_p16837173772511"></a><a name="zh-cn_topic_0245075032_p16837173772511"></a>enable_restore</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.871887188718873%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p128371375258"><a name="zh-cn_topic_0245075032_p128371375258"></a><a name="zh-cn_topic_0245075032_p128371375258"></a>Boolean</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.38573857385738%" headers="mcps1.2.4.1.3 "><p id="p487664823319"><a name="p487664823319"></a><a name="p487664823319"></a>是否自动解冻归档存储数据。</p>
    <p id="zh-cn_topic_0245075054_p495114361507"><a name="zh-cn_topic_0245075054_p495114361507"></a><a name="zh-cn_topic_0245075054_p495114361507"></a>开启后，如果遇到归档存储类型数据，会自动解冻再进行迁移；默认为不开启，如果遇到归档类型的对象直接跳过相应对象，系统默认对象迁移失败并记录相关信息到失败对象列表中。</p>
    <div class="note" id="zh-cn_topic_0245075032_note41600315114"><a name="zh-cn_topic_0245075032_note41600315114"></a><a name="zh-cn_topic_0245075032_note41600315114"></a><span class="notetitle"> 说明： </span><div class="notebody"><p id="zh-cn_topic_0245075032_p1616110317118"><a name="zh-cn_topic_0245075032_p1616110317118"></a><a name="zh-cn_topic_0245075032_p1616110317118"></a>由于对象存储解冻需要源端存储等待一定时间，开启自动解冻会对迁移速度有较大影响，建议先完成归档存储数据解冻后再启动迁移。</p>
    </div></div>
    </td>
    </tr>
    <tr id="zh-cn_topic_0245075032_row114177208020"><td class="cellrowborder" valign="top" width="23.742374237423743%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p5802216"><a name="zh-cn_topic_0245075032_p5802216"></a><a name="zh-cn_topic_0245075032_p5802216"></a>error_reason</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.871887188718873%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p217508"><a name="zh-cn_topic_0245075032_p217508"></a><a name="zh-cn_topic_0245075032_p217508"></a>JSONObject</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.38573857385738%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p17789802"><a name="zh-cn_topic_0245075032_p17789802"></a><a name="zh-cn_topic_0245075032_p17789802"></a>任务失败原因，非失败状态时该字段为空字符串。参见<a href="#zh-cn_topic_0245075032_table6751171116446">表5</a>。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0245075032_row2927236015"><td class="cellrowborder" valign="top" width="23.742374237423743%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p62263462113621"><a name="zh-cn_topic_0245075032_p62263462113621"></a><a name="zh-cn_topic_0245075032_p62263462113621"></a>failed_num</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.871887188718873%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p8968449103945"><a name="zh-cn_topic_0245075032_p8968449103945"></a><a name="zh-cn_topic_0245075032_p8968449103945"></a>long</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.38573857385738%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p58166374103953"><a name="zh-cn_topic_0245075032_p58166374103953"></a><a name="zh-cn_topic_0245075032_p58166374103953"></a>迁移失败对象数量，非失败状态时该字段为空字符串。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0245075032_row19338101218418"><td class="cellrowborder" valign="top" width="23.742374237423743%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p87421611124414"><a name="zh-cn_topic_0245075032_p87421611124414"></a><a name="zh-cn_topic_0245075032_p87421611124414"></a>failed_object_record</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.871887188718873%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p074241144413"><a name="zh-cn_topic_0245075032_p074241144413"></a><a name="zh-cn_topic_0245075032_p074241144413"></a>JSONObject</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.38573857385738%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p674315119441"><a name="zh-cn_topic_0245075032_p674315119441"></a><a name="zh-cn_topic_0245075032_p674315119441"></a>失败对象列表记录结果，记录成功时提供失败对象列表存放链接，记录失败时显示失败原因。参见<a href="#zh-cn_topic_0245075032_table127514119442">表6</a>。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0245075032_row197280142411"><td class="cellrowborder" valign="top" width="23.742374237423743%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p7691251862"><a name="zh-cn_topic_0245075032_p7691251862"></a><a name="zh-cn_topic_0245075032_p7691251862"></a>group_id</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.871887188718873%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p1969118511865"><a name="zh-cn_topic_0245075032_p1969118511865"></a><a name="zh-cn_topic_0245075032_p1969118511865"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.38573857385738%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p106912511467"><a name="zh-cn_topic_0245075032_p106912511467"></a><a name="zh-cn_topic_0245075032_p106912511467"></a>迁移任务组ID，当任务由迁移任务组创建时会包含迁移任务组的id信息。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0245075032_row34736162"><td class="cellrowborder" valign="top" width="23.742374237423743%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p62165703"><a name="zh-cn_topic_0245075032_p62165703"></a><a name="zh-cn_topic_0245075032_p62165703"></a>id</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.871887188718873%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p2257160"><a name="zh-cn_topic_0245075032_p2257160"></a><a name="zh-cn_topic_0245075032_p2257160"></a>long</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.38573857385738%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p84908306114"><a name="zh-cn_topic_0245075032_p84908306114"></a><a name="zh-cn_topic_0245075032_p84908306114"></a>迁移任务ID。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0245075032_row118781840776"><td class="cellrowborder" valign="top" width="23.742374237423743%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p5573459277"><a name="zh-cn_topic_0245075032_p5573459277"></a><a name="zh-cn_topic_0245075032_p5573459277"></a>is_query_over</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.871887188718873%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p1557314591077"><a name="zh-cn_topic_0245075032_p1557314591077"></a><a name="zh-cn_topic_0245075032_p1557314591077"></a>Boolean</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.38573857385738%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p2573195919718"><a name="zh-cn_topic_0245075032_p2573195919718"></a><a name="zh-cn_topic_0245075032_p2573195919718"></a>迁移任务是否完成源端对象统计数据扫描。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0245075032_row473216447712"><td class="cellrowborder" valign="top" width="23.742374237423743%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p42658596"><a name="zh-cn_topic_0245075032_p42658596"></a><a name="zh-cn_topic_0245075032_p42658596"></a>left_time</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.871887188718873%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p32794215"><a name="zh-cn_topic_0245075032_p32794215"></a><a name="zh-cn_topic_0245075032_p32794215"></a>long</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.38573857385738%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p11832897"><a name="zh-cn_topic_0245075032_p11832897"></a><a name="zh-cn_topic_0245075032_p11832897"></a>迁移任务剩余时间，单位：毫秒。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0245075032_row18569919689"><td class="cellrowborder" valign="top" width="23.742374237423743%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p14355174719527"><a name="zh-cn_topic_0245075032_p14355174719527"></a><a name="zh-cn_topic_0245075032_p14355174719527"></a>migrate_since</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.871887188718873%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p9355347195215"><a name="zh-cn_topic_0245075032_p9355347195215"></a><a name="zh-cn_topic_0245075032_p9355347195215"></a>long</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.38573857385738%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p63551147125210"><a name="zh-cn_topic_0245075032_p63551147125210"></a><a name="zh-cn_topic_0245075032_p63551147125210"></a>迁移指定时间（时间戳，毫秒），表示仅迁移在指定时间之后修改的源端待迁移对象。默认为0，表示不设置迁移指定时间。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0245075032_row49212281787"><td class="cellrowborder" valign="top" width="23.742374237423743%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p29144511814"><a name="zh-cn_topic_0245075032_p29144511814"></a><a name="zh-cn_topic_0245075032_p29144511814"></a>migrate_speed</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.871887188718873%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p82751830397"><a name="zh-cn_topic_0245075032_p82751830397"></a><a name="zh-cn_topic_0245075032_p82751830397"></a>long</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.38573857385738%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p19914459814"><a name="zh-cn_topic_0245075032_p19914459814"></a><a name="zh-cn_topic_0245075032_p19914459814"></a>任务迁移速度（Byte/s）。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0245075032_row1935315211911"><td class="cellrowborder" valign="top" width="23.742374237423743%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p60441935"><a name="zh-cn_topic_0245075032_p60441935"></a><a name="zh-cn_topic_0245075032_p60441935"></a>name</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.871887188718873%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p63958576"><a name="zh-cn_topic_0245075032_p63958576"></a><a name="zh-cn_topic_0245075032_p63958576"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.38573857385738%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p1636493617119"><a name="zh-cn_topic_0245075032_p1636493617119"></a><a name="zh-cn_topic_0245075032_p1636493617119"></a>迁移任务名称。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0245075032_row1974155411918"><td class="cellrowborder" valign="top" width="23.742374237423743%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p46568871"><a name="zh-cn_topic_0245075032_p46568871"></a><a name="zh-cn_topic_0245075032_p46568871"></a>progress</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.871887188718873%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p13982202"><a name="zh-cn_topic_0245075032_p13982202"></a><a name="zh-cn_topic_0245075032_p13982202"></a>Double</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.38573857385738%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p66523006"><a name="zh-cn_topic_0245075032_p66523006"></a><a name="zh-cn_topic_0245075032_p66523006"></a>迁移任务进度，例如：0.522代表任务进度为52.2%，1代表任务进度为100%。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0245075032_row63438571594"><td class="cellrowborder" valign="top" width="23.742374237423743%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p84081916151111"><a name="zh-cn_topic_0245075032_p84081916151111"></a><a name="zh-cn_topic_0245075032_p84081916151111"></a>real_size</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.871887188718873%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p12408816171117"><a name="zh-cn_topic_0245075032_p12408816171117"></a><a name="zh-cn_topic_0245075032_p12408816171117"></a>Long</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.38573857385738%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p54081016131110"><a name="zh-cn_topic_0245075032_p54081016131110"></a><a name="zh-cn_topic_0245075032_p54081016131110"></a>实际迁移对象总大小（Byte），忽略对象的大小不会统计在内。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0245075032_row4428718112"><td class="cellrowborder" valign="top" width="23.742374237423743%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p13408416201118"><a name="zh-cn_topic_0245075032_p13408416201118"></a><a name="zh-cn_topic_0245075032_p13408416201118"></a>skipped_num</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.871887188718873%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p5408131615113"><a name="zh-cn_topic_0245075032_p5408131615113"></a><a name="zh-cn_topic_0245075032_p5408131615113"></a>Long</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.38573857385738%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p4745194117301"><a name="zh-cn_topic_0245075032_p4745194117301"></a><a name="zh-cn_topic_0245075032_p4745194117301"></a>迁移忽略对象数。</p>
    <p id="zh-cn_topic_0245075032_p176119587305"><a name="zh-cn_topic_0245075032_p176119587305"></a><a name="zh-cn_topic_0245075032_p176119587305"></a>存在以下两种情况会自动跳过：</p>
    <a name="zh-cn_topic_0245075032_ul1022270153113"></a><a name="zh-cn_topic_0245075032_ul1022270153113"></a><ul id="zh-cn_topic_0245075032_ul1022270153113"><li>源端对象最后修改时间在迁移指定时间前。</li><li>目的端已有该对象。</li></ul>
    </td>
    </tr>
    <tr id="zh-cn_topic_0245075032_row544975819101"><td class="cellrowborder" valign="top" width="23.742374237423743%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p24537816"><a name="zh-cn_topic_0245075032_p24537816"></a><a name="zh-cn_topic_0245075032_p24537816"></a>src_node</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.871887188718873%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p41406050"><a name="zh-cn_topic_0245075032_p41406050"></a><a name="zh-cn_topic_0245075032_p41406050"></a>JSONObject</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.38573857385738%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p8414436"><a name="zh-cn_topic_0245075032_p8414436"></a><a name="zh-cn_topic_0245075032_p8414436"></a>源端节点信息，参见<a href="#zh-cn_topic_0245075032_table20639104403">表7</a>。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0245075032_row4888719"><td class="cellrowborder" valign="top" width="23.742374237423743%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p25580392"><a name="zh-cn_topic_0245075032_p25580392"></a><a name="zh-cn_topic_0245075032_p25580392"></a>start_time</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.871887188718873%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p58745844"><a name="zh-cn_topic_0245075032_p58745844"></a><a name="zh-cn_topic_0245075032_p58745844"></a>Long</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.38573857385738%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p25281875"><a name="zh-cn_topic_0245075032_p25281875"></a><a name="zh-cn_topic_0245075032_p25281875"></a>迁移任务启动时间（Unix时间戳，毫秒）。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0245075032_row4445458"><td class="cellrowborder" valign="top" width="23.742374237423743%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p12625908"><a name="zh-cn_topic_0245075032_p12625908"></a><a name="zh-cn_topic_0245075032_p12625908"></a>status</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.871887188718873%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p16065622"><a name="zh-cn_topic_0245075032_p16065622"></a><a name="zh-cn_topic_0245075032_p16065622"></a>int</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.38573857385738%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p3977555124119"><a name="zh-cn_topic_0245075032_p3977555124119"></a><a name="zh-cn_topic_0245075032_p3977555124119"></a>迁移任务状态。</p>
    <a name="zh-cn_topic_0245075032_ul112461358104117"></a><a name="zh-cn_topic_0245075032_ul112461358104117"></a><ul id="zh-cn_topic_0245075032_ul112461358104117"><li>1：等待调度</li><li>2：正在执行</li><li>3：停止</li><li>4：失败</li><li>5：成功</li></ul>
    </td>
    </tr>
    <tr id="zh-cn_topic_0245075032_row8621060"><td class="cellrowborder" valign="top" width="23.742374237423743%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p124041925142013"><a name="zh-cn_topic_0245075032_p124041925142013"></a><a name="zh-cn_topic_0245075032_p124041925142013"></a>successful_num</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.871887188718873%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p32197839103918"><a name="zh-cn_topic_0245075032_p32197839103918"></a><a name="zh-cn_topic_0245075032_p32197839103918"></a>long</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.38573857385738%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p59661552103930"><a name="zh-cn_topic_0245075032_p59661552103930"></a><a name="zh-cn_topic_0245075032_p59661552103930"></a>迁移成功对象数量。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0245075032_row1986613317205"><td class="cellrowborder" valign="top" width="23.742374237423743%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p837625162119"><a name="zh-cn_topic_0245075032_p837625162119"></a><a name="zh-cn_topic_0245075032_p837625162119"></a>task_type</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.871887188718873%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p173764522115"><a name="zh-cn_topic_0245075032_p173764522115"></a><a name="zh-cn_topic_0245075032_p173764522115"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.38573857385738%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p737605172119"><a name="zh-cn_topic_0245075032_p737605172119"></a><a name="zh-cn_topic_0245075032_p737605172119"></a>任务类型，为空时默认设置为object。</p>
    <a name="zh-cn_topic_0245075032_ul1137617512118"></a><a name="zh-cn_topic_0245075032_ul1137617512118"></a><ul id="zh-cn_topic_0245075032_ul1137617512118"><li>list：对象列表迁移</li><li>object：文件/文件夹迁移</li><li>prefix：对象前缀迁移</li><li>url_list: url对象列表</li></ul>
    </td>
    </tr>
    <tr id="zh-cn_topic_0245075032_row8108104092018"><td class="cellrowborder" valign="top" width="23.742374237423743%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p24472248113621"><a name="zh-cn_topic_0245075032_p24472248113621"></a><a name="zh-cn_topic_0245075032_p24472248113621"></a>total_num</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.871887188718873%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p42729691103823"><a name="zh-cn_topic_0245075032_p42729691103823"></a><a name="zh-cn_topic_0245075032_p42729691103823"></a>long</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.38573857385738%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p35782861103823"><a name="zh-cn_topic_0245075032_p35782861103823"></a><a name="zh-cn_topic_0245075032_p35782861103823"></a>迁移对象总数量。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0245075032_row8983042102019"><td class="cellrowborder" valign="top" width="23.742374237423743%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p16755431"><a name="zh-cn_topic_0245075032_p16755431"></a><a name="zh-cn_topic_0245075032_p16755431"></a>total_size</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.871887188718873%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p15012662"><a name="zh-cn_topic_0245075032_p15012662"></a><a name="zh-cn_topic_0245075032_p15012662"></a>long</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.38573857385738%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p49377135"><a name="zh-cn_topic_0245075032_p49377135"></a><a name="zh-cn_topic_0245075032_p49377135"></a>迁移任务总大小。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0245075032_row866884582013"><td class="cellrowborder" valign="top" width="23.742374237423743%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p35020816113621"><a name="zh-cn_topic_0245075032_p35020816113621"></a><a name="zh-cn_topic_0245075032_p35020816113621"></a>total_time</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.871887188718873%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p50367649"><a name="zh-cn_topic_0245075032_p50367649"></a><a name="zh-cn_topic_0245075032_p50367649"></a>long</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.38573857385738%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p18100201"><a name="zh-cn_topic_0245075032_p18100201"></a><a name="zh-cn_topic_0245075032_p18100201"></a>迁移任务总时间。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0245075032_row1301716132220"><td class="cellrowborder" valign="top" width="23.742374237423743%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p176739269222"><a name="zh-cn_topic_0245075032_p176739269222"></a><a name="zh-cn_topic_0245075032_p176739269222"></a>smn_info</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.871887188718873%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p2673102692219"><a name="zh-cn_topic_0245075032_p2673102692219"></a><a name="zh-cn_topic_0245075032_p2673102692219"></a>JSONObject</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.38573857385738%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p7673726142214"><a name="zh-cn_topic_0245075032_p7673726142214"></a><a name="zh-cn_topic_0245075032_p7673726142214"></a>SMN消息通知结果，参见<a href="#zh-cn_topic_0245075032_table14756151114443">表9</a>。</p>
    <div class="note" id="zh-cn_topic_0245075032_note19673102610220"><a name="zh-cn_topic_0245075032_note19673102610220"></a><a name="zh-cn_topic_0245075032_note19673102610220"></a><span class="notetitle"> 说明： </span><div class="notebody"><p id="zh-cn_topic_0245075032_p13673102612215"><a name="zh-cn_topic_0245075032_p13673102612215"></a><a name="zh-cn_topic_0245075032_p13673102612215"></a>用户可以选择是否发送SMN信息，在迁移任务已经结束的情况下才会有该字段。</p>
    </div></div>
    </td>
    </tr>
    <tr id="zh-cn_topic_0245075032_row174915374222"><td class="cellrowborder" valign="top" width="23.742374237423743%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p03622382225"><a name="zh-cn_topic_0245075032_p03622382225"></a><a name="zh-cn_topic_0245075032_p03622382225"></a>source_cdn</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.871887188718873%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p12362938132212"><a name="zh-cn_topic_0245075032_p12362938132212"></a><a name="zh-cn_topic_0245075032_p12362938132212"></a>JSONObject</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.38573857385738%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p536214385227"><a name="zh-cn_topic_0245075032_p536214385227"></a><a name="zh-cn_topic_0245075032_p536214385227"></a>指定是否启用CDN迁移支持，参见<a href="#zh-cn_topic_0245075032_table176671419165412">表10</a>。启用CDN迁移支持后，迁移时将从CDN域名获取源端对象。若包含此字段则为支持，否则为不支持。</p>
    </td>
    </tr>
    </tbody>
    </table>

    **表 3**  bandwidth\_policy字段数据结构说明

    <a name="zh-cn_topic_0245075032_table874721174417"></a>
    <table><thead align="left"><tr id="zh-cn_topic_0245075032_row11748171110446"><th class="cellrowborder" valign="top" width="23.392339233923394%" id="mcps1.2.4.1.1"><p id="zh-cn_topic_0245075032_p974821174418"><a name="zh-cn_topic_0245075032_p974821174418"></a><a name="zh-cn_topic_0245075032_p974821174418"></a>参数</p>
    </th>
    <th class="cellrowborder" valign="top" width="19.221922192219225%" id="mcps1.2.4.1.2"><p id="zh-cn_topic_0245075032_p6748911134414"><a name="zh-cn_topic_0245075032_p6748911134414"></a><a name="zh-cn_topic_0245075032_p6748911134414"></a>参数类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="57.38573857385738%" id="mcps1.2.4.1.3"><p id="zh-cn_topic_0245075032_p16748411164413"><a name="zh-cn_topic_0245075032_p16748411164413"></a><a name="zh-cn_topic_0245075032_p16748411164413"></a>描述</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="zh-cn_topic_0245075032_row10748141110446"><td class="cellrowborder" valign="top" width="23.392339233923394%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p574861194415"><a name="zh-cn_topic_0245075032_p574861194415"></a><a name="zh-cn_topic_0245075032_p574861194415"></a>start</p>
    </td>
    <td class="cellrowborder" valign="top" width="19.221922192219225%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p18748191113445"><a name="zh-cn_topic_0245075032_p18748191113445"></a><a name="zh-cn_topic_0245075032_p18748191113445"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.38573857385738%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p67481811104410"><a name="zh-cn_topic_0245075032_p67481811104410"></a><a name="zh-cn_topic_0245075032_p67481811104410"></a>流量控制开始时间（包含），格式为“hh:mm”。例如“10:03”表示10时03分。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0245075032_row674891164416"><td class="cellrowborder" valign="top" width="23.392339233923394%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p775081115443"><a name="zh-cn_topic_0245075032_p775081115443"></a><a name="zh-cn_topic_0245075032_p775081115443"></a>end</p>
    <p id="zh-cn_topic_0245075032_p13750211194420"><a name="zh-cn_topic_0245075032_p13750211194420"></a><a name="zh-cn_topic_0245075032_p13750211194420"></a></p>
    </td>
    <td class="cellrowborder" valign="top" width="19.221922192219225%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p675019119442"><a name="zh-cn_topic_0245075032_p675019119442"></a><a name="zh-cn_topic_0245075032_p675019119442"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.38573857385738%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p14750111154419"><a name="zh-cn_topic_0245075032_p14750111154419"></a><a name="zh-cn_topic_0245075032_p14750111154419"></a>流量控制结束时间（包含），格式为“hh:mm”。例如“12:03”表示12时03分。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0245075032_row2750191184414"><td class="cellrowborder" valign="top" width="23.392339233923394%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p3750141194419"><a name="zh-cn_topic_0245075032_p3750141194419"></a><a name="zh-cn_topic_0245075032_p3750141194419"></a>max_bandwidth</p>
    </td>
    <td class="cellrowborder" valign="top" width="19.221922192219225%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p197501811114419"><a name="zh-cn_topic_0245075032_p197501811114419"></a><a name="zh-cn_topic_0245075032_p197501811114419"></a>Long</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.38573857385738%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p3750181184417"><a name="zh-cn_topic_0245075032_p3750181184417"></a><a name="zh-cn_topic_0245075032_p3750181184417"></a>时段内允许的最大流量带宽，单位Byte/s。取值范围为&gt;= 1048576Byte/s（相当于1MB/s）且&lt;=209715200Byte/s（相当于200MB/s）。</p>
    </td>
    </tr>
    </tbody>
    </table>

    **表 4**  dst\_node字段数据结构说明

    <a name="zh-cn_topic_0245075032_table365310144019"></a>
    <table><thead align="left"><tr id="zh-cn_topic_0245075032_row196561010409"><th class="cellrowborder" valign="top" width="23.57235723572357%" id="mcps1.2.4.1.1"><p id="zh-cn_topic_0245075032_p2065410114010"><a name="zh-cn_topic_0245075032_p2065410114010"></a><a name="zh-cn_topic_0245075032_p2065410114010"></a>参数</p>
    </th>
    <th class="cellrowborder" valign="top" width="19.041904190419043%" id="mcps1.2.4.1.2"><p id="zh-cn_topic_0245075032_p76551044018"><a name="zh-cn_topic_0245075032_p76551044018"></a><a name="zh-cn_topic_0245075032_p76551044018"></a>参数类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="57.38573857385738%" id="mcps1.2.4.1.3"><p id="zh-cn_topic_0245075032_p1266151004018"><a name="zh-cn_topic_0245075032_p1266151004018"></a><a name="zh-cn_topic_0245075032_p1266151004018"></a>描述</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="zh-cn_topic_0245075032_row156601012406"><td class="cellrowborder" valign="top" width="23.57235723572357%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p666510144019"><a name="zh-cn_topic_0245075032_p666510144019"></a><a name="zh-cn_topic_0245075032_p666510144019"></a>region</p>
    </td>
    <td class="cellrowborder" valign="top" width="19.041904190419043%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p46641074013"><a name="zh-cn_topic_0245075032_p46641074013"></a><a name="zh-cn_topic_0245075032_p46641074013"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.38573857385738%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p196611017401"><a name="zh-cn_topic_0245075032_p196611017401"></a><a name="zh-cn_topic_0245075032_p196611017401"></a>目的端桶所处的区域。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0245075032_row20672109403"><td class="cellrowborder" valign="top" width="23.57235723572357%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p1867810114011"><a name="zh-cn_topic_0245075032_p1867810114011"></a><a name="zh-cn_topic_0245075032_p1867810114011"></a>bucket</p>
    </td>
    <td class="cellrowborder" valign="top" width="19.041904190419043%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p1167610114018"><a name="zh-cn_topic_0245075032_p1167610114018"></a><a name="zh-cn_topic_0245075032_p1167610114018"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.38573857385738%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p367171054010"><a name="zh-cn_topic_0245075032_p367171054010"></a><a name="zh-cn_topic_0245075032_p367171054010"></a>目的端桶的名称。</p>
    <p id="zh-cn_topic_0245075032_p6743517184818"><a name="zh-cn_topic_0245075032_p6743517184818"></a><a name="zh-cn_topic_0245075032_p6743517184818"></a>请与Endpoint对应的区域保持一致。</p>
    </td>
    </tr>
    </tbody>
    </table>

    **表 5**  error\_reason字段数据结构说明

    <a name="zh-cn_topic_0245075032_table6751171116446"></a>
    <table><thead align="left"><tr id="zh-cn_topic_0245075032_row1075161174415"><th class="cellrowborder" valign="top" width="23.482348234823483%" id="mcps1.2.4.1.1"><p id="zh-cn_topic_0245075032_p975115119443"><a name="zh-cn_topic_0245075032_p975115119443"></a><a name="zh-cn_topic_0245075032_p975115119443"></a>参数</p>
    </th>
    <th class="cellrowborder" valign="top" width="18.871887188718873%" id="mcps1.2.4.1.2"><p id="zh-cn_topic_0245075032_p12751711184417"><a name="zh-cn_topic_0245075032_p12751711184417"></a><a name="zh-cn_topic_0245075032_p12751711184417"></a>参数类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="57.64576457645765%" id="mcps1.2.4.1.3"><p id="zh-cn_topic_0245075032_p375112113442"><a name="zh-cn_topic_0245075032_p375112113442"></a><a name="zh-cn_topic_0245075032_p375112113442"></a>描述</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="zh-cn_topic_0245075032_row127511711164415"><td class="cellrowborder" valign="top" width="23.482348234823483%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p1475121113449"><a name="zh-cn_topic_0245075032_p1475121113449"></a><a name="zh-cn_topic_0245075032_p1475121113449"></a>error_code</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.871887188718873%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p875114113442"><a name="zh-cn_topic_0245075032_p875114113442"></a><a name="zh-cn_topic_0245075032_p875114113442"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.64576457645765%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p375131118444"><a name="zh-cn_topic_0245075032_p375131118444"></a><a name="zh-cn_topic_0245075032_p375131118444"></a>迁移失败的错误码。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0245075032_row77511211144417"><td class="cellrowborder" valign="top" width="23.482348234823483%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p12751101118447"><a name="zh-cn_topic_0245075032_p12751101118447"></a><a name="zh-cn_topic_0245075032_p12751101118447"></a>error_msg</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.871887188718873%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p77511911174411"><a name="zh-cn_topic_0245075032_p77511911174411"></a><a name="zh-cn_topic_0245075032_p77511911174411"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.64576457645765%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p1775181112444"><a name="zh-cn_topic_0245075032_p1775181112444"></a><a name="zh-cn_topic_0245075032_p1775181112444"></a>迁移失败的原因。</p>
    </td>
    </tr>
    </tbody>
    </table>

    **表 6**  failed\_object\_record字段数据结构说明

    <a name="zh-cn_topic_0245075032_table127514119442"></a>
    <table><thead align="left"><tr id="zh-cn_topic_0245075032_row275271112448"><th class="cellrowborder" valign="top" width="23.392339233923394%" id="mcps1.2.4.1.1"><p id="zh-cn_topic_0245075032_p117521411194414"><a name="zh-cn_topic_0245075032_p117521411194414"></a><a name="zh-cn_topic_0245075032_p117521411194414"></a>参数</p>
    </th>
    <th class="cellrowborder" valign="top" width="18.961896189618958%" id="mcps1.2.4.1.2"><p id="zh-cn_topic_0245075032_p775220114441"><a name="zh-cn_topic_0245075032_p775220114441"></a><a name="zh-cn_topic_0245075032_p775220114441"></a>参数类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="57.64576457645765%" id="mcps1.2.4.1.3"><p id="zh-cn_topic_0245075032_p127521611154413"><a name="zh-cn_topic_0245075032_p127521611154413"></a><a name="zh-cn_topic_0245075032_p127521611154413"></a>描述</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="zh-cn_topic_0245075032_row875221115447"><td class="cellrowborder" valign="top" width="23.392339233923394%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p6752121124420"><a name="zh-cn_topic_0245075032_p6752121124420"></a><a name="zh-cn_topic_0245075032_p6752121124420"></a>result</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.961896189618958%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p1175291194411"><a name="zh-cn_topic_0245075032_p1175291194411"></a><a name="zh-cn_topic_0245075032_p1175291194411"></a>Boolean</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.64576457645765%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p57521411144413"><a name="zh-cn_topic_0245075032_p57521411144413"></a><a name="zh-cn_topic_0245075032_p57521411144413"></a>是否支持失败对象重传。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0245075032_row375221117447"><td class="cellrowborder" valign="top" width="23.392339233923394%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p1775251174410"><a name="zh-cn_topic_0245075032_p1775251174410"></a><a name="zh-cn_topic_0245075032_p1775251174410"></a>list_file_key</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.961896189618958%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p14752181134419"><a name="zh-cn_topic_0245075032_p14752181134419"></a><a name="zh-cn_topic_0245075032_p14752181134419"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.64576457645765%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p5753911114418"><a name="zh-cn_topic_0245075032_p5753911114418"></a><a name="zh-cn_topic_0245075032_p5753911114418"></a>失败对象列表文件路径。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0245075032_row6757195018483"><td class="cellrowborder" valign="top" width="23.392339233923394%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p13740125114489"><a name="zh-cn_topic_0245075032_p13740125114489"></a><a name="zh-cn_topic_0245075032_p13740125114489"></a>error_code</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.961896189618958%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p147401851144817"><a name="zh-cn_topic_0245075032_p147401851144817"></a><a name="zh-cn_topic_0245075032_p147401851144817"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.64576457645765%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p6740105119484"><a name="zh-cn_topic_0245075032_p6740105119484"></a><a name="zh-cn_topic_0245075032_p6740105119484"></a>失败对象列表上传失败的错误码。</p>
    </td>
    </tr>
    </tbody>
    </table>

    **表 7**  src\_node字段数据结构说明

    <a name="zh-cn_topic_0245075032_table20639104403"></a>
    <table><thead align="left"><tr id="zh-cn_topic_0245075032_row126371013400"><th class="cellrowborder" valign="top" width="23.392339233923394%" id="mcps1.2.4.1.1"><p id="zh-cn_topic_0245075032_p1863121024014"><a name="zh-cn_topic_0245075032_p1863121024014"></a><a name="zh-cn_topic_0245075032_p1863121024014"></a>参数</p>
    </th>
    <th class="cellrowborder" valign="top" width="18.61186118611861%" id="mcps1.2.4.1.2"><p id="zh-cn_topic_0245075032_p8641210154012"><a name="zh-cn_topic_0245075032_p8641210154012"></a><a name="zh-cn_topic_0245075032_p8641210154012"></a>参数类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="57.995799579957996%" id="mcps1.2.4.1.3"><p id="zh-cn_topic_0245075032_p164131019404"><a name="zh-cn_topic_0245075032_p164131019404"></a><a name="zh-cn_topic_0245075032_p164131019404"></a>描述</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="zh-cn_topic_0245075032_row129161650144914"><td class="cellrowborder" valign="top" width="23.392339233923394%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p9931111105011"><a name="zh-cn_topic_0245075032_p9931111105011"></a><a name="zh-cn_topic_0245075032_p9931111105011"></a>bucket</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.61186118611861%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p29331112505"><a name="zh-cn_topic_0245075032_p29331112505"></a><a name="zh-cn_topic_0245075032_p29331112505"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.995799579957996%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p129331117508"><a name="zh-cn_topic_0245075032_p129331117508"></a><a name="zh-cn_topic_0245075032_p129331117508"></a>源端桶的名称。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0245075032_row51471757174911"><td class="cellrowborder" valign="top" width="23.392339233923394%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p1093171111501"><a name="zh-cn_topic_0245075032_p1093171111501"></a><a name="zh-cn_topic_0245075032_p1093171111501"></a>cloud_type</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.61186118611861%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p693181125011"><a name="zh-cn_topic_0245075032_p693181125011"></a><a name="zh-cn_topic_0245075032_p693181125011"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.995799579957996%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p1293131110504"><a name="zh-cn_topic_0245075032_p1293131110504"></a><a name="zh-cn_topic_0245075032_p1293131110504"></a>源端云服务商。</p>
    <p id="zh-cn_topic_0245075032_p119361155012"><a name="zh-cn_topic_0245075032_p119361155012"></a><a name="zh-cn_topic_0245075032_p119361155012"></a>可选值有AWS、Azure、Aliyun、Tencent、HuaweiCloud、QingCloud、KingsoftCloud、Baidu、Qiniu、URLSource或UCloud。默认值为Aliyun。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0245075032_row18270359104913"><td class="cellrowborder" valign="top" width="23.392339233923394%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p129341110508"><a name="zh-cn_topic_0245075032_p129341110508"></a><a name="zh-cn_topic_0245075032_p129341110508"></a>region</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.61186118611861%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p1393111135017"><a name="zh-cn_topic_0245075032_p1393111135017"></a><a name="zh-cn_topic_0245075032_p1393111135017"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.995799579957996%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p993111175019"><a name="zh-cn_topic_0245075032_p993111175019"></a><a name="zh-cn_topic_0245075032_p993111175019"></a>源端桶所处的区域。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0245075032_row199088385013"><td class="cellrowborder" valign="top" width="23.392339233923394%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p593131119509"><a name="zh-cn_topic_0245075032_p593131119509"></a><a name="zh-cn_topic_0245075032_p593131119509"></a>app_id</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.61186118611861%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p4939116503"><a name="zh-cn_topic_0245075032_p4939116503"></a><a name="zh-cn_topic_0245075032_p4939116503"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.995799579957996%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p169311105011"><a name="zh-cn_topic_0245075032_p169311105011"></a><a name="zh-cn_topic_0245075032_p169311105011"></a>当源端为腾讯云时，会返回此参数。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0245075032_row1290715318501"><td class="cellrowborder" valign="top" width="23.392339233923394%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p093131115013"><a name="zh-cn_topic_0245075032_p093131115013"></a><a name="zh-cn_topic_0245075032_p093131115013"></a>object_key</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.61186118611861%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p293131114504"><a name="zh-cn_topic_0245075032_p293131114504"></a><a name="zh-cn_topic_0245075032_p293131114504"></a>Array of strings</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.995799579957996%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p15931811175010"><a name="zh-cn_topic_0245075032_p15931811175010"></a><a name="zh-cn_topic_0245075032_p15931811175010"></a>任务类型为对象迁移任务时，表示待迁移对象名称； 任务类型为前缀迁移任务时，表示待迁移前缀。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0245075032_row1890712375011"><td class="cellrowborder" valign="top" width="23.392339233923394%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p9944112503"><a name="zh-cn_topic_0245075032_p9944112503"></a><a name="zh-cn_topic_0245075032_p9944112503"></a>list_file</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.61186118611861%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p094131125013"><a name="zh-cn_topic_0245075032_p094131125013"></a><a name="zh-cn_topic_0245075032_p094131125013"></a>JSONObject</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.995799579957996%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p39431113506"><a name="zh-cn_topic_0245075032_p39431113506"></a><a name="zh-cn_topic_0245075032_p39431113506"></a>列表文件配置，当task_type为list或url_list时，list_file为必选参数。</p>
    </td>
    </tr>
    </tbody>
    </table>

    **表 8**  list\_file字段数据结构说明

    <a name="zh-cn_topic_0245075032_table67558119449"></a>
    <table><thead align="left"><tr id="zh-cn_topic_0245075032_row11755111114411"><th class="cellrowborder" valign="top" width="23.482348234823483%" id="mcps1.2.4.1.1"><p id="zh-cn_topic_0245075032_p117554114442"><a name="zh-cn_topic_0245075032_p117554114442"></a><a name="zh-cn_topic_0245075032_p117554114442"></a>参数</p>
    </th>
    <th class="cellrowborder" valign="top" width="18.61186118611861%" id="mcps1.2.4.1.2"><p id="zh-cn_topic_0245075032_p9755811114414"><a name="zh-cn_topic_0245075032_p9755811114414"></a><a name="zh-cn_topic_0245075032_p9755811114414"></a>参数类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="57.9057905790579%" id="mcps1.2.4.1.3"><p id="zh-cn_topic_0245075032_p16756141114418"><a name="zh-cn_topic_0245075032_p16756141114418"></a><a name="zh-cn_topic_0245075032_p16756141114418"></a>描述</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="zh-cn_topic_0245075032_row5459742144619"><td class="cellrowborder" valign="top" width="23.482348234823483%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p77561811194417"><a name="zh-cn_topic_0245075032_p77561811194417"></a><a name="zh-cn_topic_0245075032_p77561811194417"></a>list_file_key</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.61186118611861%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p14756511164420"><a name="zh-cn_topic_0245075032_p14756511164420"></a><a name="zh-cn_topic_0245075032_p14756511164420"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.9057905790579%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p1275620114445"><a name="zh-cn_topic_0245075032_p1275620114445"></a><a name="zh-cn_topic_0245075032_p1275620114445"></a>对象列表文件或URL列表文件对象名。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0245075032_row19756141111446"><td class="cellrowborder" valign="top" width="23.482348234823483%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p16756171154417"><a name="zh-cn_topic_0245075032_p16756171154417"></a><a name="zh-cn_topic_0245075032_p16756171154417"></a>obs_bucket</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.61186118611861%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p0756121116448"><a name="zh-cn_topic_0245075032_p0756121116448"></a><a name="zh-cn_topic_0245075032_p0756121116448"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.9057905790579%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p875614116441"><a name="zh-cn_topic_0245075032_p875614116441"></a><a name="zh-cn_topic_0245075032_p875614116441"></a>存放对象列表文件的OBS桶名。</p>
    </td>
    </tr>
    </tbody>
    </table>

    **表 9**  smn\_info字段数据结构说明

    <a name="zh-cn_topic_0245075032_table14756151114443"></a>
    <table><thead align="left"><tr id="zh-cn_topic_0245075032_row2757411184414"><th class="cellrowborder" valign="top" width="23.13231323132313%" id="mcps1.2.4.1.1"><p id="zh-cn_topic_0245075032_p17757201111444"><a name="zh-cn_topic_0245075032_p17757201111444"></a><a name="zh-cn_topic_0245075032_p17757201111444"></a>参数</p>
    </th>
    <th class="cellrowborder" valign="top" width="19.131913191319132%" id="mcps1.2.4.1.2"><p id="zh-cn_topic_0245075032_p775817114447"><a name="zh-cn_topic_0245075032_p775817114447"></a><a name="zh-cn_topic_0245075032_p775817114447"></a>参数类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="57.73577357735774%" id="mcps1.2.4.1.3"><p id="zh-cn_topic_0245075032_p275851174414"><a name="zh-cn_topic_0245075032_p275851174414"></a><a name="zh-cn_topic_0245075032_p275851174414"></a>描述</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="zh-cn_topic_0245075032_row27589117441"><td class="cellrowborder" valign="top" width="23.13231323132313%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p94171737155213"><a name="zh-cn_topic_0245075032_p94171737155213"></a><a name="zh-cn_topic_0245075032_p94171737155213"></a>notify_result</p>
    </td>
    <td class="cellrowborder" valign="top" width="19.131913191319132%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p20758121144416"><a name="zh-cn_topic_0245075032_p20758121144416"></a><a name="zh-cn_topic_0245075032_p20758121144416"></a>Boolean</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.73577357735774%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p147582110441"><a name="zh-cn_topic_0245075032_p147582110441"></a><a name="zh-cn_topic_0245075032_p147582110441"></a>记录迁移任务执行完毕后SMN消息是否发送成功。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0245075032_row1758201184414"><td class="cellrowborder" valign="top" width="23.13231323132313%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p2041719379522"><a name="zh-cn_topic_0245075032_p2041719379522"></a><a name="zh-cn_topic_0245075032_p2041719379522"></a>notify_error_message</p>
    </td>
    <td class="cellrowborder" valign="top" width="19.131913191319132%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p21468558104152"><a name="zh-cn_topic_0245075032_p21468558104152"></a><a name="zh-cn_topic_0245075032_p21468558104152"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.73577357735774%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p60818427104152"><a name="zh-cn_topic_0245075032_p60818427104152"></a><a name="zh-cn_topic_0245075032_p60818427104152"></a>记录SMN消息发送失败原因的错误码（迁移任务成功时为空）。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0245075032_row1663664161037"><td class="cellrowborder" valign="top" width="23.13231323132313%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p1441893710527"><a name="zh-cn_topic_0245075032_p1441893710527"></a><a name="zh-cn_topic_0245075032_p1441893710527"></a>topic_name</p>
    </td>
    <td class="cellrowborder" valign="top" width="19.131913191319132%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p33702595161057"><a name="zh-cn_topic_0245075032_p33702595161057"></a><a name="zh-cn_topic_0245075032_p33702595161057"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.73577357735774%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p66129842161057"><a name="zh-cn_topic_0245075032_p66129842161057"></a><a name="zh-cn_topic_0245075032_p66129842161057"></a>SMN Topic的名称（SMN消息发送成功时为空）。</p>
    </td>
    </tr>
    </tbody>
    </table>

    **表 10**  source\_cdn字段数据结构说明

    <a name="zh-cn_topic_0245075032_table176671419165412"></a>
    <table><thead align="left"><tr id="zh-cn_topic_0245075032_row15754119175410"><th class="cellrowborder" valign="top" width="22.96229622962296%" id="mcps1.2.4.1.1"><p id="zh-cn_topic_0245075032_p147541119145413"><a name="zh-cn_topic_0245075032_p147541119145413"></a><a name="zh-cn_topic_0245075032_p147541119145413"></a>参数</p>
    </th>
    <th class="cellrowborder" valign="top" width="19.39193919391939%" id="mcps1.2.4.1.2"><p id="zh-cn_topic_0245075032_p8754101918541"><a name="zh-cn_topic_0245075032_p8754101918541"></a><a name="zh-cn_topic_0245075032_p8754101918541"></a>参数类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="57.64576457645765%" id="mcps1.2.4.1.3"><p id="zh-cn_topic_0245075032_p1075415191544"><a name="zh-cn_topic_0245075032_p1075415191544"></a><a name="zh-cn_topic_0245075032_p1075415191544"></a>描述</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="zh-cn_topic_0245075032_row9755319165418"><td class="cellrowborder" valign="top" width="22.96229622962296%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p675513195541"><a name="zh-cn_topic_0245075032_p675513195541"></a><a name="zh-cn_topic_0245075032_p675513195541"></a>domain</p>
    </td>
    <td class="cellrowborder" valign="top" width="19.39193919391939%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p17755219105414"><a name="zh-cn_topic_0245075032_p17755219105414"></a><a name="zh-cn_topic_0245075032_p17755219105414"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.64576457645765%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p9755619185410"><a name="zh-cn_topic_0245075032_p9755619185410"></a><a name="zh-cn_topic_0245075032_p9755619185410"></a>从指定域名获取对象。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0245075032_row1972872404714"><td class="cellrowborder" valign="top" width="22.96229622962296%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p1975471911543"><a name="zh-cn_topic_0245075032_p1975471911543"></a><a name="zh-cn_topic_0245075032_p1975471911543"></a>protocol</p>
    </td>
    <td class="cellrowborder" valign="top" width="19.39193919391939%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p97547191549"><a name="zh-cn_topic_0245075032_p97547191549"></a><a name="zh-cn_topic_0245075032_p97547191549"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.64576457645765%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p1275581918545"><a name="zh-cn_topic_0245075032_p1275581918545"></a><a name="zh-cn_topic_0245075032_p1275581918545"></a>协议类型，支持http和https协议。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0245075032_row5755161914540"><td class="cellrowborder" valign="top" width="22.96229622962296%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245075032_p17755119175412"><a name="zh-cn_topic_0245075032_p17755119175412"></a><a name="zh-cn_topic_0245075032_p17755119175412"></a>authentication_type</p>
    </td>
    <td class="cellrowborder" valign="top" width="19.39193919391939%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245075032_p1675511910546"><a name="zh-cn_topic_0245075032_p1675511910546"></a><a name="zh-cn_topic_0245075032_p1675511910546"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.64576457645765%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245075032_p1875551915541"><a name="zh-cn_topic_0245075032_p1875551915541"></a><a name="zh-cn_topic_0245075032_p1875551915541"></a>鉴权方式。</p>
    <a name="zh-cn_topic_0245075032_ul68032412195"></a><a name="zh-cn_topic_0245075032_ul68032412195"></a><ul id="zh-cn_topic_0245075032_ul68032412195"><li>无需鉴权：NONE</li><li>Qiniu：<p id="zh-cn_topic_0245075032_p4790174320423"><a name="zh-cn_topic_0245075032_p4790174320423"></a><a name="zh-cn_topic_0245075032_p4790174320423"></a>QINIU_PRIVATE_AUTHENTICATION</p>
    </li></ul>
    <a name="zh-cn_topic_0245075032_ul71367240426"></a><a name="zh-cn_topic_0245075032_ul71367240426"></a><ul id="zh-cn_topic_0245075032_ul71367240426"><li>Aliyun：<p id="zh-cn_topic_0245075032_p12667164012424"><a name="zh-cn_topic_0245075032_p12667164012424"></a><a name="zh-cn_topic_0245075032_p12667164012424"></a>ALIYUN_OSS_A、ALIYUN_OSS_B、ALIYUN_OSS_C</p>
    </li><li>KingsoftCloud：KSYUN_PRIVATE_AUTHENTICATION</li><li>AZURE：AZURE_SAS_TOKEN</li></ul>
    </td>
    </tr>
    </tbody>
    </table>


-   响应示例

    ```
    { 
      "bandwidth_policy" : [ { 
        "end" : "23:59", 
        "max_bandwidth" : 0, 
        "start" : "00:00" 
      } ], 
      "complete_size" : 0, 
      "description" : "test log", 
      "dst_node" : { 
        "bucket" : "dst_bucket", 
        "region" : "cn-north-1" 
      }, 
      "enable_failed_object_recording" : true, 
      "enable_kms" : true, 
      "enable_restore" : false, 
      "error_reason" : { 
        "error_code" : "string", 
        "error_msg" : "string" 
      }, 
      "failed_num" : 0, 
      "failed_object_record" : { 
        "result" : true, 
        "list_file_key" : "string", 
        "error_code" : "string" 
      }, 
      "group_id" : "string", 
      "id" : 0, 
      "is_query_over" : true, 
      "left_time" : 0, 
      "migrate_since" : 0, 
      "migrate_speed" : 0, 
      "name" : "string", 
      "progress" : 0, 
      "real_size" : 0, 
      "skipped_num" : 0, 
      "src_node" : { 
        "bucket" : "src_bucket", 
        "cloud_type" : "AWS", 
        "region" : "cn-north-1", 
        "app_id" : "string", 
        "object_key" : [ "string", "string" ], 
        "list_file" : { 
          "list_file_key" : "object_list_file.txt", 
          "obs_bucket" : "obs_bucket" 
        } 
      }, 
      "start_time" : 0, 
      "status" : 0, 
      "successful_num" : 0, 
      "task_type" : "list", 
      "total_num" : 0, 
      "total_size" : 0, 
      "total_time" : 0, 
      "smn_info" : { 
        "notify_result" : true, 
        "notify_error_message" : "string", 
        "topic_name" : "string" 
      }, 
      "source_cdn" : { 
        "domain" : "xxx.xxx.xxx", 
        "protocol" : "http", 
        "authentication_type" : "string" 
      } 
    }
    ```


## 状态码<a name="zh-cn_topic_0245074948_section43299552"></a>

状态码请参见[状态码](状态码.md)。

## 错误码<a name="zh-cn_topic_0245074948_section968175316304"></a>

状态码请参见[错误码](错误码.md)。

