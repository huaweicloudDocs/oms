# 查询API版本信息列表<a name="oms_api_0035"></a>

## 功能介绍<a name="zh-cn_topic_0245074948_section21679321"></a>

查询对象存储迁移服务的API版本信息。

## URI<a name="zh-cn_topic_0245074948_section60896162"></a>

GET /

## 请求消息<a name="zh-cn_topic_0245074948_section34343508"></a>

-   请求参数

    无


-   请求样例

    ```
    GET https://{oms_endpoint}/ 
    ```


## 响应消息<a name="zh-cn_topic_0245074948_section40656116"></a>

-   响应参数

    **表 1**  参数说明

    <a name="zh-cn_topic_0245074948_table923414123516"></a>
    <table><thead align="left"><tr id="zh-cn_topic_0245074948_row9235131218513"><th class="cellrowborder" valign="top" width="23.492349234923495%" id="mcps1.2.4.1.1"><p id="zh-cn_topic_0245074948_p104418214518"><a name="zh-cn_topic_0245074948_p104418214518"></a><a name="zh-cn_topic_0245074948_p104418214518"></a>参数</p>
    </th>
    <th class="cellrowborder" valign="top" width="22.492249224922492%" id="mcps1.2.4.1.2"><p id="zh-cn_topic_0245074948_p154415215516"><a name="zh-cn_topic_0245074948_p154415215516"></a><a name="zh-cn_topic_0245074948_p154415215516"></a>参数类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="54.015401540154016%" id="mcps1.2.4.1.3"><p id="zh-cn_topic_0245074948_p144116211255"><a name="zh-cn_topic_0245074948_p144116211255"></a><a name="zh-cn_topic_0245074948_p144116211255"></a>描述</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="zh-cn_topic_0245074948_row17235201216519"><td class="cellrowborder" valign="top" width="23.492349234923495%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245074948_p3679117255"><a name="zh-cn_topic_0245074948_p3679117255"></a><a name="zh-cn_topic_0245074948_p3679117255"></a>versions</p>
    </td>
    <td class="cellrowborder" valign="top" width="22.492249224922492%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245074948_p14679817458"><a name="zh-cn_topic_0245074948_p14679817458"></a><a name="zh-cn_topic_0245074948_p14679817458"></a>Array of objects</p>
    </td>
    <td class="cellrowborder" valign="top" width="54.015401540154016%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245074948_p1367918170520"><a name="zh-cn_topic_0245074948_p1367918170520"></a><a name="zh-cn_topic_0245074948_p1367918170520"></a>描述对象存储迁移服务API版本信息列表。详情请参见<a href="#zh-cn_topic_0245074948_table9555503">表2</a>。</p>
    </td>
    </tr>
    </tbody>
    </table>

    **表 2**  参数说明

    <a name="zh-cn_topic_0245074948_table9555503"></a>
    <table><thead align="left"><tr id="zh-cn_topic_0245074948_row55898385"><th class="cellrowborder" valign="top" width="23.582358235823584%" id="mcps1.2.4.1.1"><p id="zh-cn_topic_0245074948_p31475357"><a name="zh-cn_topic_0245074948_p31475357"></a><a name="zh-cn_topic_0245074948_p31475357"></a>参数</p>
    </th>
    <th class="cellrowborder" valign="top" width="22.21222122212221%" id="mcps1.2.4.1.2"><p id="zh-cn_topic_0245074948_p66476022"><a name="zh-cn_topic_0245074948_p66476022"></a><a name="zh-cn_topic_0245074948_p66476022"></a>参数类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="54.205420542054206%" id="mcps1.2.4.1.3"><p id="zh-cn_topic_0245074948_p8676909"><a name="zh-cn_topic_0245074948_p8676909"></a><a name="zh-cn_topic_0245074948_p8676909"></a>描述</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="zh-cn_topic_0245074948_row31741019"><td class="cellrowborder" valign="top" width="23.582358235823584%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245074948_p20885750"><a name="zh-cn_topic_0245074948_p20885750"></a><a name="zh-cn_topic_0245074948_p20885750"></a>id</p>
    </td>
    <td class="cellrowborder" valign="top" width="22.21222122212221%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245074948_p14024165"><a name="zh-cn_topic_0245074948_p14024165"></a><a name="zh-cn_topic_0245074948_p14024165"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="54.205420542054206%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245074948_p6296289"><a name="zh-cn_topic_0245074948_p6296289"></a><a name="zh-cn_topic_0245074948_p6296289"></a>API版本号。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0245074948_row56666602"><td class="cellrowborder" valign="top" width="23.582358235823584%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245074948_p26592044"><a name="zh-cn_topic_0245074948_p26592044"></a><a name="zh-cn_topic_0245074948_p26592044"></a>links</p>
    </td>
    <td class="cellrowborder" valign="top" width="22.21222122212221%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245074948_p6471942"><a name="zh-cn_topic_0245074948_p6471942"></a><a name="zh-cn_topic_0245074948_p6471942"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="54.205420542054206%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245074948_p49614245"><a name="zh-cn_topic_0245074948_p49614245"></a><a name="zh-cn_topic_0245074948_p49614245"></a>API的URL地址。详情请参见<a href="#zh-cn_topic_0245074948_table27491483234">表3</a>。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0245074948_row50789581"><td class="cellrowborder" valign="top" width="23.582358235823584%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245074948_p20315403"><a name="zh-cn_topic_0245074948_p20315403"></a><a name="zh-cn_topic_0245074948_p20315403"></a>status</p>
    </td>
    <td class="cellrowborder" valign="top" width="22.21222122212221%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245074948_p34934986"><a name="zh-cn_topic_0245074948_p34934986"></a><a name="zh-cn_topic_0245074948_p34934986"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="54.205420542054206%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245074948_p192251931012"><a name="zh-cn_topic_0245074948_p192251931012"></a><a name="zh-cn_topic_0245074948_p192251931012"></a>API版本状态：</p>
    <a name="zh-cn_topic_0245074948_ul102213194107"></a><a name="zh-cn_topic_0245074948_ul102213194107"></a><ul id="zh-cn_topic_0245074948_ul102213194107"><li>CURRENT：表示该版本为主推版本。</li><li>SUPPORTED：表示为老版本，但是现在还在继续支持。</li><li>DEPRECATED：表示为废弃版本，存在后续删除的可能。</li></ul>
    </td>
    </tr>
    <tr id="zh-cn_topic_0245074948_row16670523"><td class="cellrowborder" valign="top" width="23.582358235823584%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245074948_p8135151"><a name="zh-cn_topic_0245074948_p8135151"></a><a name="zh-cn_topic_0245074948_p8135151"></a>updated</p>
    </td>
    <td class="cellrowborder" valign="top" width="22.21222122212221%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245074948_p54967495"><a name="zh-cn_topic_0245074948_p54967495"></a><a name="zh-cn_topic_0245074948_p54967495"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="54.205420542054206%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245074948_p65812741"><a name="zh-cn_topic_0245074948_p65812741"></a><a name="zh-cn_topic_0245074948_p65812741"></a>API版本更新时间。</p>
    <p id="zh-cn_topic_0245074948_p209770152216"><a name="zh-cn_topic_0245074948_p209770152216"></a><a name="zh-cn_topic_0245074948_p209770152216"></a>格式为“yyyy-mm-ddThh:mm:ssZ”。</p>
    <p id="zh-cn_topic_0245074948_p11977415223"><a name="zh-cn_topic_0245074948_p11977415223"></a><a name="zh-cn_topic_0245074948_p11977415223"></a>其中，T指某个时间的开始；Z指UTC时间。例如：2018-09-30T00:00:00Z</p>
    </td>
    </tr>
    </tbody>
    </table>

    **表 3**  links字段数据结构说明

    <a name="zh-cn_topic_0245074948_table27491483234"></a>
    <table><thead align="left"><tr id="zh-cn_topic_0245074948_row12751168172318"><th class="cellrowborder" valign="top" width="23.492349234923495%" id="mcps1.2.4.1.1"><p id="zh-cn_topic_0245074948_p1543481814239"><a name="zh-cn_topic_0245074948_p1543481814239"></a><a name="zh-cn_topic_0245074948_p1543481814239"></a>参数</p>
    </th>
    <th class="cellrowborder" valign="top" width="22.39223922392239%" id="mcps1.2.4.1.2"><p id="zh-cn_topic_0245074948_p0434131816236"><a name="zh-cn_topic_0245074948_p0434131816236"></a><a name="zh-cn_topic_0245074948_p0434131816236"></a>参数类型</p>
    </th>
    <th class="cellrowborder" valign="top" width="54.11541154115411%" id="mcps1.2.4.1.3"><p id="zh-cn_topic_0245074948_p194341818142314"><a name="zh-cn_topic_0245074948_p194341818142314"></a><a name="zh-cn_topic_0245074948_p194341818142314"></a>描述</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="zh-cn_topic_0245074948_row18752482232"><td class="cellrowborder" valign="top" width="23.492349234923495%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245074948_p1986912516238"><a name="zh-cn_topic_0245074948_p1986912516238"></a><a name="zh-cn_topic_0245074948_p1986912516238"></a>href</p>
    </td>
    <td class="cellrowborder" valign="top" width="22.39223922392239%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245074948_p88693258238"><a name="zh-cn_topic_0245074948_p88693258238"></a><a name="zh-cn_topic_0245074948_p88693258238"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="54.11541154115411%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245074948_p148691225142320"><a name="zh-cn_topic_0245074948_p148691225142320"></a><a name="zh-cn_topic_0245074948_p148691225142320"></a>API的url地址。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0245074948_row775268152318"><td class="cellrowborder" valign="top" width="23.492349234923495%" headers="mcps1.2.4.1.1 "><p id="zh-cn_topic_0245074948_p168693256232"><a name="zh-cn_topic_0245074948_p168693256232"></a><a name="zh-cn_topic_0245074948_p168693256232"></a>rel</p>
    </td>
    <td class="cellrowborder" valign="top" width="22.39223922392239%" headers="mcps1.2.4.1.2 "><p id="zh-cn_topic_0245074948_p8869025152313"><a name="zh-cn_topic_0245074948_p8869025152313"></a><a name="zh-cn_topic_0245074948_p8869025152313"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="54.11541154115411%" headers="mcps1.2.4.1.3 "><p id="zh-cn_topic_0245074948_p17869172511236"><a name="zh-cn_topic_0245074948_p17869172511236"></a><a name="zh-cn_topic_0245074948_p17869172511236"></a>API的url地址依赖。取值为“self”，表示href为本地链接。</p>
    </td>
    </tr>
    </tbody>
    </table>


-   **响应样例**

    ```
    { 
      "versions" : [ { 
        "links" : [ { 
          "rel" : "self", 
          "href" : "https://oms.xxx.com/v1/" 
        } ], 
        "id" : "v1", 
        "updated" : "2020-01-01T12:00:00Z", 
        "status" : "SUPPORTED" 
      }, { 
        "links" : [ { 
          "rel" : "self", 
          "href" : "https://oms.xxx.com/v2/" 
        } ], 
        "id" : "v1", 
        "updated" : "2020-01-01T12:00:00Z", 
        "status" : "SUPPORTED" 
      } ] 
    }
    ```


## 状态码<a name="zh-cn_topic_0245074948_section43299552"></a>

状态码请参见[状态码](状态码.md)。

## 错误码<a name="zh-cn_topic_0245074948_section968175316304"></a>

状态码请参见[错误码](错误码.md)。

