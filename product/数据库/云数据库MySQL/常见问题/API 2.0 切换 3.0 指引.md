云数据库 MySQL 于北京时间2018年01月01日全面升级了 API 接口服务至 3.0 版本，当前基于 API 2.0 版本接口访问的时延较高且使用较复杂考虑，云数据库 MySQL 的 API 2.0 版本接口服务将不再提供技术支持，并将于北京时间2023年03月31日起下线。

如果您的业务还在使用云数据库 MySQL 的 API 2.0 版本相关接口，建议尽快将服务升级至云数据库 MySQL API 3.0 版本，以免对您的业务造成影响。

使用 API 3.0 版本接口服务时，建议使用 [云产品 SDK 中心_云产品 SDK 文档-腾讯云](https://cloud.tencent.com/document/sdk)，获取到 API 3.0 版本配套的多种编程语言的 SDK，[API Explorer](https://console.cloud.tencent.com/api/explorer?Product=cdb&Version=2017-03-20&Action=DescribeDBInstances) 可以直接生成 SDK 的调用代码，方便您实现代码调用。

请您参照下方的 API 2.0 切换 3.0 接口表找到您需要升级的新接口，完成升级。

## API 2.0 切换 3.0 接口列表
<table>
<thead><tr><th>API 2.0 接口</td><th>API 3.0 接口</td><th>API 3.0 文档</td><th>接口传参变化</td></tr></thead>
<tbody>
<tr>
<td>DescribeCdbInstances</td>
<td>DescribeDBInstances</td>
<td><a href="https://cloud.tencent.com/document/api/236/15872">单击了解</a></td>
<td>以 API 3.0 文档为准</td></tr>
<tr>
<td>QueryCdbStatisticsInfo</td>
<td>GetAppStat</td>
<td>-</td>
<td>接口传参无变化</td></tr>
<tr>
<td>DescribeDBInstancesV3</td>
<td>DescribeDBInstances</td>
<td><a href="https://cloud.tencent.com/document/api/236/15872">单击了解</a></td>
<td>接口传参无变化</td> </tr>
<tr>
<td>GetCdbExportLogUrl</td>
<td>GetDownloadUrl</td>
<td>-</td>
<td>接口传参无变化</td></tr>
<tr>
<td>RenewCdb</td>
<td>RenewDBInstance</td>
<td><a href="https://cloud.tencent.com/document/api/236/30160">单击了解</a></td>
<td>以 API 3.0 文档为准</td></tr>
</tbody></table>
