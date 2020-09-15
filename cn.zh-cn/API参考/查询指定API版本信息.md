# 查询指定API版本信息<a name="oms_api_0036"></a>

## 功能介绍<a name="zh-cn_topic_0249657614_section623353612136"></a>

查询对象存储迁移服务指定API版本信息。

## URI<a name="zh-cn_topic_0249657614_section192344360133"></a>

GET /\{version\}

## 请求消息<a name="zh-cn_topic_0249657614_section223413611315"></a>

-   请求参数

    无。


-   请求样例

    ```
    GET https://{oms_endpoint}/v2
    ```


## 响应消息<a name="zh-cn_topic_0249657614_section16234136151316"></a>

-   响应参数

    **表 1**  参数说明

    <a name="zh-cn_topic_0249657614_table3234183613139"></a>
    <table><thead align="left"><tr id="zh-cn_topic_0249657614_row723415364137"><th class="cellrowborder" valign="top" width="23.582358235823584%" id="mcps1.2.4.1.1"><p id="zh-cn_topic_0249657614_p0234163691317"><a name="zh-cn_topic_0249657614_p0234163691317"></a><a name="zh-cn_topic_0249657614_p0234163691317"></a>参数</p>
    </th>
    <th class="cellrowborder" valign="top" width="22.222222222222225%" id="mcps1.2.4.1.2"><p id="zh-cn_topic_0249657614_p14234143615130"><a name="zh-cn_topic_0249657614_p14234143615130"></a><a name="zh-cn_topic_0249657614_p14234143615130"></a>参数类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="54.1954195419542%" id="mcps1.2.4.1.3"><p id="zh-cn_topic_0249657614_p1235636131312"><a name="zh-cn_topic_0249657614_p1235636131312"></a><a name="zh-cn_topic_0249657614_p1235636131312"></a>描述</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="zh-cn_topic_0249657614_row823503620139"><td class="cellrowborder" valign="top" width="23.582358235823584%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0249657614_p1123518366135"><a name="zh-cn_topic_0249657614_p1123518366135"></a><a name="zh-cn_topic_0249657614_p1123518366135"></a>id</p>
    </td>
    <td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0249657614_p10235133618136"><a name="zh-cn_topic_0249657614_p10235133618136"></a><a name="zh-cn_topic_0249657614_p10235133618136"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="54.1954195419542%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0249657614_p10235193613133"><a name="zh-cn_topic_0249657614_p10235193613133"></a><a name="zh-cn_topic_0249657614_p10235193613133"></a>API版本号，例如v2</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0249657614_row023513613136"><td class="cellrowborder" valign="top" width="23.582358235823584%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0249657614_p6235153691318"><a name="zh-cn_topic_0249657614_p6235153691318"></a><a name="zh-cn_topic_0249657614_p6235153691318"></a>links</p>
    </td>
    <td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0249657614_p7235103612135"><a name="zh-cn_topic_0249657614_p7235103612135"></a><a name="zh-cn_topic_0249657614_p7235103612135"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="54.1954195419542%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0249657614_p1723520364131"><a name="zh-cn_topic_0249657614_p1723520364131"></a><a name="zh-cn_topic_0249657614_p1723520364131"></a>API的URL地址。详情请参见<a href="#zh-cn_topic_0249657614_table27491483234">表2</a>。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0249657614_row19235183611316"><td class="cellrowborder" valign="top" width="23.582358235823584%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0249657614_p52358366131"><a name="zh-cn_topic_0249657614_p52358366131"></a><a name="zh-cn_topic_0249657614_p52358366131"></a>status</p>
    </td>
    <td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0249657614_p6235143616133"><a name="zh-cn_topic_0249657614_p6235143616133"></a><a name="zh-cn_topic_0249657614_p6235143616133"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="54.1954195419542%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0249657614_p192251931012"><a name="zh-cn_topic_0249657614_p192251931012"></a><a name="zh-cn_topic_0249657614_p192251931012"></a>API版本状态：</p>
    <a name="zh-cn_topic_0249657614_ul102213194107"></a><a name="zh-cn_topic_0249657614_ul102213194107"></a><ul id="zh-cn_topic_0249657614_ul102213194107"><li>CURRENT：表示该版本为主推版本。</li><li>SUPPORTED：表示为老版本，但是现在还在继续支持。</li><li>DEPRECATED：表示为废弃版本，存在后续删除的可能。</li></ul>
    </td>
    </tr>
    <tr id="zh-cn_topic_0249657614_row9235536101316"><td class="cellrowborder" valign="top" width="23.582358235823584%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0249657614_p6235236191315"><a name="zh-cn_topic_0249657614_p6235236191315"></a><a name="zh-cn_topic_0249657614_p6235236191315"></a>updated</p>
    </td>
    <td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0249657614_p1423512364135"><a name="zh-cn_topic_0249657614_p1423512364135"></a><a name="zh-cn_topic_0249657614_p1423512364135"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="54.1954195419542%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0249657614_p0235836181316"><a name="zh-cn_topic_0249657614_p0235836181316"></a><a name="zh-cn_topic_0249657614_p0235836181316"></a>API版本更新时间。</p>
    <p id="zh-cn_topic_0249657614_p209770152216"><a name="zh-cn_topic_0249657614_p209770152216"></a><a name="zh-cn_topic_0249657614_p209770152216"></a>格式为“yyyy-mm-ddThh:mm:ssZ”。</p>
    <p id="zh-cn_topic_0249657614_p11977415223"><a name="zh-cn_topic_0249657614_p11977415223"></a><a name="zh-cn_topic_0249657614_p11977415223"></a>其中，T指某个时间的开始；Z指UTC时间。例如：2018-09-30T00:00:00Z</p>
    </td>
    </tr>
    </tbody>
    </table>

    **表 2**  links字段数据结构说明

    <a name="zh-cn_topic_0249657614_table27491483234"></a>
    <table><thead align="left"><tr id="zh-cn_topic_0249657614_row12751168172318"><th class="cellrowborder" valign="top" width="23.492349234923495%" id="mcps1.2.4.1.1"><p id="zh-cn_topic_0249657614_p1543481814239"><a name="zh-cn_topic_0249657614_p1543481814239"></a><a name="zh-cn_topic_0249657614_p1543481814239"></a>参数</p>
    </th>
    <th class="cellrowborder" valign="top" width="22.39223922392239%" id="mcps1.2.4.1.2"><p id="zh-cn_topic_0249657614_p0434131816236"><a name="zh-cn_topic_0249657614_p0434131816236"></a><a name="zh-cn_topic_0249657614_p0434131816236"></a>参数类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="54.11541154115411%" id="mcps1.2.4.1.3"><p id="zh-cn_topic_0249657614_p194341818142314"><a name="zh-cn_topic_0249657614_p194341818142314"></a><a name="zh-cn_topic_0249657614_p194341818142314"></a>描述</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="zh-cn_topic_0249657614_row18752482232"><td class="cellrowborder" valign="top" width="23.492349234923495%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0249657614_p1986912516238"><a name="zh-cn_topic_0249657614_p1986912516238"></a><a name="zh-cn_topic_0249657614_p1986912516238"></a>href</p>
    </td>
    <td class="cellrowborder" valign="top" width="22.39223922392239%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0249657614_p88693258238"><a name="zh-cn_topic_0249657614_p88693258238"></a><a name="zh-cn_topic_0249657614_p88693258238"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="54.11541154115411%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0249657614_p148691225142320"><a name="zh-cn_topic_0249657614_p148691225142320"></a><a name="zh-cn_topic_0249657614_p148691225142320"></a>API的url地址。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0249657614_row775268152318"><td class="cellrowborder" valign="top" width="23.492349234923495%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0249657614_p168693256232"><a name="zh-cn_topic_0249657614_p168693256232"></a><a name="zh-cn_topic_0249657614_p168693256232"></a>rel</p>
    </td>
    <td class="cellrowborder" valign="top" width="22.39223922392239%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0249657614_p8869025152313"><a name="zh-cn_topic_0249657614_p8869025152313"></a><a name="zh-cn_topic_0249657614_p8869025152313"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="54.11541154115411%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0249657614_p17869172511236"><a name="zh-cn_topic_0249657614_p17869172511236"></a><a name="zh-cn_topic_0249657614_p17869172511236"></a>API的url地址依赖。取值为“self”，表示href为本地链接。</p>
    </td>
    </tr>
    </tbody>
    </table>


-   响应样例

    ```
    { 
        "links" : [ { 
          "rel" : "self", 
          "href" : "https://oms.xxx.com/v2/" 
        } ], 
        "id" : "v2", 
        "updated" : "2020-01-01T12:00:00Z", 
        "status" : "SUPPORTED" 
    }
    ```


## 状态码<a name="zh-cn_topic_0245074948_section43299552"></a>

状态码请参见[状态码](状态码.md)。

## 错误码<a name="zh-cn_topic_0245074948_section968175316304"></a>

状态码请参见[错误码](错误码.md)。

