# 查询API版本<a name="oms_api_0013"></a>

## 功能介绍<a name="section21679321"></a>

查询对象存储迁移服务的API版本信息。

## URI<a name="section60896162"></a>

GET /v1/\{project\_id\}/objectstorage/version

GET /

GET /\{version\}

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
<tr id="row1965181018116"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p176541020112"><a name="p176541020112"></a><a name="p176541020112"></a>version</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p15661110121111"><a name="p15661110121111"></a><a name="p15661110121111"></a>否</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p0661910141113"><a name="p0661910141113"></a><a name="p0661910141113"></a>API版本号。</p>
</td>
</tr>
</tbody>
</table>

## 请求消息<a name="section34343508"></a>

**请求参数**

无。

## 响应消息<a name="section40656116"></a>

**响应参数**

响应参数如[表2](#table9555503)所示。

**表 2**  响应参数

<a name="table9555503"></a>
<table><thead align="left"><tr id="row55898385"><th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.1"><p id="p31475357"><a name="p31475357"></a><a name="p31475357"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.2"><p id="p66476022"><a name="p66476022"></a><a name="p66476022"></a>参数类型</p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.3"><p id="p8676909"><a name="p8676909"></a><a name="p8676909"></a>描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row31741019"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p20885750"><a name="p20885750"></a><a name="p20885750"></a>id</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p14024165"><a name="p14024165"></a><a name="p14024165"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p6296289"><a name="p6296289"></a><a name="p6296289"></a>API版本号。</p>
</td>
</tr>
<tr id="row56666602"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p26592044"><a name="p26592044"></a><a name="p26592044"></a>links</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p6471942"><a name="p6471942"></a><a name="p6471942"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p49614245"><a name="p49614245"></a><a name="p49614245"></a>API的URL地址。</p>
</td>
</tr>
<tr id="row43875021"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p64215808"><a name="p64215808"></a><a name="p64215808"></a>version</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p34097968"><a name="p34097968"></a><a name="p34097968"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p42925989"><a name="p42925989"></a><a name="p42925989"></a>API支持的最高版本号。</p>
</td>
</tr>
<tr id="row50789581"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p20315403"><a name="p20315403"></a><a name="p20315403"></a>status</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p34934986"><a name="p34934986"></a><a name="p34934986"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p31678442"><a name="p31678442"></a><a name="p31678442"></a>版本状态。</p>
</td>
</tr>
<tr id="row16670523"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p8135151"><a name="p8135151"></a><a name="p8135151"></a>updated</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p54967495"><a name="p54967495"></a><a name="p54967495"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p65812741"><a name="p65812741"></a><a name="p65812741"></a>版本更新时间。</p>
</td>
</tr>
<tr id="row94291718693"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p05198251690"><a name="p05198251690"></a><a name="p05198251690"></a>min_version</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p165198251596"><a name="p165198251596"></a><a name="p165198251596"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p2519125395"><a name="p2519125395"></a><a name="p2519125395"></a>API支持的最低版本号。</p>
</td>
</tr>
</tbody>
</table>

## 示例<a name="section30360724"></a>

**请求示例**

GET /v1/\{project\_id\}/objectstorage/version

**响应示例**

```
{
    "versions": [
        {
            "id": "v1.0",
            "links": [
                {
                    "href": "https://oms.cn-north-1.myhuaweicloud.com/v1/",
                    "rel": "self"
                }
            ],
            "min_version": "",
            "status": "SUPPORTED",
            "updated": "2016-12-09T00:00:00Z",
            "version": "",
        },
        {
            "id": "v2.0",
            "links": [
                {
                    "href": "https://oms.cn-north-1.myhuaweicloud.com/v1/",
                    "rel": "self"
                }
            ],
            "min_version": "",
            "status": "CURRENT",
            "updated": "2016-12-09T00:00:00Z",
            "version": "",
        }
    ]
}
```

## 状态码<a name="section43299552"></a>

状态码请参见[状态码](状态码.md)。

