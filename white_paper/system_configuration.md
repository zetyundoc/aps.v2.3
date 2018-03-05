# 系统配置
## 大数据服务器以及网络推荐配置
大数据服务器一般需要三台以上主机作为主节点，以及数台（具体数量按照实际数据量增减）数据节点。为保证高效IO，应为不同的服务（数据量较大的服务）配置不同的硬盘。推荐配置如下：
操作系统兼容性：大数据服务器的操作系统对Linux内核版本2.6以上版本全面支持。例如发行版CentOS6.5、SUSE11SP2以上版本。
<table>
   <tr>
      <td colspan="5">系统硬件推荐配置表</td>
   </tr>
   <tr>
      <td>每天日志量</td>
      <td>500 GB</td>
      <td>1 TB</td>
      <td>3 TB</td>
      <td>10 TB</td>
   </tr>
   <tr>
      <td>日志管理主机数</td>
      <td>4</td>
      <td>8</td>
      <td>22</td>
      <td>72</td>
   </tr>
   <tr>
      <td>日志分析主机数</td>
   </tr>
   <tr>
      <td>（*仅需要开启日志分析功能时需要）</td>
      <td>2</td>
      <td>4</td>
      <td>11</td>
      <td>36</td>
   </tr>
   <tr>
      <td>总主机数</td>
      <td>6</td>
      <td>12</td>
      <td>33</td>
      <td>108</td>
   </tr>
   <tr>
      <td>单机硬盘容量</td>
      <td>33T</td>
      <td>33T</td>
      <td>35T</td>
      <td>36T</td>
   </tr>
   <tr>
      <td>硬盘数（每块1T）</td>
      <td>33</td>
      <td>33</td>
      <td>35</td>
      <td>36</td>
   </tr>
   <tr>
      <td>CPU</td>
      <td>40核以上</td>
      <td>40核以上</td>
      <td>40核以上</td>
      <td>40核以上</td>
   </tr>
   <tr>
      <td>内存（GB）</td>
      <td>256</td>
      <td>256</td>
      <td>256</td>
      <td>256</td>
   </tr>
   <tr>
      <td>网卡</td>
      <td>千兆网卡（推荐万兆网卡）</td>
      <td>万兆网卡 （推荐）</td>
      <td>万兆网卡 （推荐）</td>
      <td>万兆网卡 （推荐）</td>
   </tr>
   <tr>
      <td></td>
   </tr>
</table>
