---
copyright:
  years: 1994, 2017
lastupdated: "2017-06-09"
---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# 添加和除去监视器

<table>
   <CAPTION>表 1. 添加和除去设备监视器</CAPTION>
   <THEAD>
   <TR>
   <th>如果要执行的操作是...</th>
   <th>请执行以下操作...</th>
   </TR>
   </THEAD>
   <TBODY>
   <tr>
   <td>添加监视器</td>
   <td>
   <ol>
   <li>在“设备详细信息”页面的<b>监视</b>选项卡中，单击页面右侧的<b>管理监视器</b>以管理与此设备相关联的监视器。</li>
   <li>在“监视器”页面上，单击<b>添加监视器</b>选项卡。
   * **注：**可以对公共 IP 地址和专用 IP 地址进行监视。在**服务器信息**选项卡上可找到每个 IP 地址。</li>
   <li>从 <b>IP 地址</b>下拉列表中，选择要监视的 IP 地址。</li>
   <li>从<b>监视器类型</b>下拉列表中，选择监视器类型。</li>
   <li>设置通知选项。从<b>通知？</b>下拉列表中，选择<b>通知用户</b>以向用户通知相关问题，或选择<b>不执行任何操作</b>以绕过用户通知。</li>
   <li>从使用<b>通知等待</b>下拉列表中，选择用户通知的时间范围。</li>
   <li>单击<b>添加监视器</b>来为设备添加监视器。新监视器会显示在屏幕的<b>编辑现有监视器</b>部分中。</li>
   </ol>
   </td>
   </tr>
   <tr>
   <td>除去监视器</td>
   <td>
   <ol>
   <li>在“监视器”页面上的<b>编辑现有监视器</b>标题下，单击监视器详细信息旁边的“除去”图标。</li>
   <li>单击<b>是</b>以除去监视器。单击<b>否</b>可取消该操作。</li>
   </ol>
   </td>
   </tr>
   </TBODY>
   </table>


## 后续步骤

- 如果添加了新监视器，该监视器会显示在**监视**选项卡上。该监视器每 5 分钟向设备发送一次 ping，并期望在所选 ping 类型的时间设置内收到响应。如果未收到所期望的响应，那么会在指定的时间范围内向帐户的通知电子邮件地址发送一封电子邮件，前提是已选择通知。

- 如果除去了监视器，该监视器将不会再对设备起作用。与除去的监视器相关联的所有监视都将停止，并且该监视器将不再显示在“监视”选项卡上。
