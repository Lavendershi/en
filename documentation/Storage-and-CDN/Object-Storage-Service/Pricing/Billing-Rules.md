# Billing Rules

## Billing Items

<table border=0 cellpadding=0 cellspacing=0 width=840 style='border-collapse:
 collapse;table-layout:fixed;width:632pt'>
 <col class=xl65 width=110 style='mso-width-source:userset;mso-width-alt:3520;
 width:83pt'>
 <col class=xl65 width=106 style='mso-width-source:userset;mso-width-alt:3392;
 width:80pt'>
 <col class=xl65 width=216 style='mso-width-source:userset;mso-width-alt:6912;
 width:162pt'>
 <col class=xl65 width=339 style='mso-width-source:userset;mso-width-alt:10858;
 width:255pt'>
 <col class=xl65 width=69 style='width:52pt'>
 <tr height=19 style='height:14.0pt'>
  <td colspan=2 height=19 class=xl66 width=216 style='height:14.0pt;width:163pt'>Billing Items</td>
  <td class=xl66 width=216 style='border-left:none;width:162pt'>Explanation</td>
  <td class=xl66 width=339 style='border-left:none;width:255pt'><span
  style='mso-spacerun:yes'>&nbsp;</span>Billing Formula</td>
  <td class=xl66 width=69 style='border-left:none;width:52pt'><span
  style='mso-spacerun:yes'>&nbsp;</span>Description</td>
 </tr>
 <tr height=56 style='height:42.0pt'>
  <td rowspan=2 height=131 class=xl67 width=110 style='height:98.0pt;
  border-top:none;width:83pt'><span style='font-variant-ligatures: normal;
  font-variant-caps: normal;orphans: 2;text-align:start;widows: 2;-webkit-text-stroke-width: 0px;
  text-decoration-style: initial;text-decoration-color: initial'>Storage Capacity</span></td>
  <td class=xl68 width=106 style='border-top:none;border-left:none;width:80pt'><span
  style='font-variant-ligatures: normal;font-variant-caps: normal;orphans: 2;
  text-align:start;widows: 2;-webkit-text-stroke-width: 0px;text-decoration-style: initial;
  text-decoration-color: initial'>Actual Bucket Usage</span></td>
  <td class=xl69 width=216 style='border-top:none;border-left:none;width:162pt'>Actual Bucket Usage includes:<br>
    1. Usage of standard storage type data<br>
    2. Usage of low redundant type data</td>
  <td class=xl68 width=339 style='border-top:none;border-left:none;width:255pt'><span
  style='font-variant-ligatures: normal;font-variant-caps: normal;orphans: 2;
  text-align:start;widows: 2;-webkit-text-stroke-width: 0px;text-decoration-style: initial;
  text-decoration-color: initial'>current storage capacity (GB)* every day’s unit price of corresponding storage type</span></td>
  <td class=xl70 width=69 style='border-top:none;border-left:none;width:52pt'><span
  style='font-variant-ligatures: normal;font-variant-caps: normal;orphans: 2;
  text-align:start;widows: 2;-webkit-text-stroke-width: 0px;text-decoration-style: initial;
  text-decoration-color: initial'>See Price Overview for specific prices</span></td>
 </tr>
 <tr height=75 style='height:56.0pt'>
  <td height=75 class=xl68 width=106 style='height:56.0pt;border-top:none;
  border-left:none;width:80pt'><span style='font-variant-ligatures: normal;
  font-variant-caps: normal;orphans: 2;text-align:start;widows: 2;-webkit-text-stroke-width: 0px;
  text-decoration-style: initial;text-decoration-color: initial'>Data getting back amount</span></td>
  <td class=xl71 width=216 style='border-top:none;border-left:none;width:162pt'><span
  style='font-variant-ligatures: normal;font-variant-caps: normal;orphans: 2;
  text-align:start;widows: 2;-webkit-text-stroke-width: 0px;text-decoration-style: initial;
  text-decoration-color: initial'>For access of low redundant storage type data, the data getting back amount will be calculated by the size of read files, without differentiating intranet and Internet. </span></td>
  <td class=xl69 width=339 style='border-top:none;border-left:none;width:255pt'>cost of data getting back amount
  = data getting back amount (GB) * unit price per GB<br>
    E.g.: if you need to download 10 files from Bucket of low redundant storage type and the size of each file is 10GB, then the cost of data getting back amount = 10 * 10 unit price of data getting back amount per GB</td>
  <td class=xl72 width=69 style='border-top:none;border-left:none;width:52pt'>It is free now</td>
 </tr>
 <tr height=56 style='height:42.0pt'>
  <td rowspan=6 height=317 class=xl67 width=110 style='height:238.0pt;
  border-top:none;width:83pt'><span style='font-variant-ligatures: normal;
  font-variant-caps: normal;orphans: 2;text-align:start;widows: 2;-webkit-text-stroke-width: 0px;
  text-decoration-style: initial;text-decoration-color: initial'>Access Traffic</span></td>
  <td class=xl73 width=106 style='border-top:none;border-left:none;width:80pt'>Intranet Input Traffic</td>
  <td class=xl73 width=216 style='border-top:none;border-left:none;width:162pt'>Uplink traffic generated by uploading data from internal service such as virtual machines to Object Storage Service via JD Cloud Intranet</td>
  <td class=xl73 width=339 style='border-top:none;border-left:none;width:255pt'>-</td>
  <td class=xl74 width=69 style='border-top:none;border-left:none;width:52pt'>Free</td>
 </tr>
 <tr height=56 style='height:42.0pt'>
  <td height=56 class=xl73 width=106 style='height:42.0pt;border-top:none;
  border-left:none;width:80pt'>Intranet Output Traffic</td>
  <td class=xl73 width=216 style='border-top:none;border-left:none;width:162pt'>Downlink traffic generated by downloading data from Object Storage Service to internal service such as virtual machines via JD Cloud Intranet</td>
  <td class=xl73 width=339 style='border-top:none;border-left:none;width:255pt'>-</td>
  <td class=xl74 width=69 style='border-top:none;border-left:none;width:52pt'>Free</td>
 </tr>
 <tr height=37 style='height:28.0pt'>
  <td height=37 class=xl73 width=106 style='height:28.0pt;border-top:none;
  border-left:none;width:80pt'>Internet Input Traffic</td>
  <td class=xl73 width=216 style='border-top:none;border-left:none;width:162pt'>Uplink traffic generated by uploading data from local end to Object Storage Service via public network</td>
  <td class=xl73 width=339 style='border-top:none;border-left:none;width:255pt'>-</td>
  <td class=xl74 width=69 style='border-top:none;border-left:none;width:52pt'>Free</td>
 </tr>
 <tr height=56 style='height:42.0pt'>
  <td height=56 class=xl73 width=106 style='height:42.0pt;border-top:none;
  border-left:none;width:80pt'>Internet Output Traffic</td>
  <td class=xl73 width=216 style='border-top:none;border-left:none;width:162pt'>Downlink traffic generated by downloading data from Object Storage Service to local end via public network</td>
  <td class=xl73 width=339 style='border-top:none;border-left:none;width:255pt'>Every day’s accumulative Internet output traffic (GB)
  * unit price per GB</td>
  <td class=xl74 width=69 style='border-top:none;border-left:none;width:52pt'>See Price Overview for specific prices</td>
 </tr>
 <tr height=56 style='height:42.0pt'>
  <td height=56 class=xl73 width=106 style='height:42.0pt;border-top:none;
  border-left:none;width:80pt'>CDN back-to-source output traffic</td>
  <td class=xl73 width=216 style='border-top:none;border-left:none;width:162pt'>Back-to-source downlink traffic generated by downloading via CND
  Back-to-origin downlink traffic generated by downloading OSS data</td>
  <td class=xl73 width=339 style='border-top:none;border-left:none;width:255pt'>CDN Back-to-source output traffic
  accumulated everyday (GB) * unit price of cross-region replication traffic per GB</td>
  <td class=xl74 width=69 style='border-top:none;border-left:none;width:52pt'>See Price Overview for specific prices</td>
 </tr>
 <tr height=56 style='height:42.0pt'>
  <td height=56 class=xl73 width=106 style='height:42.0pt;border-top:none;
  border-left:none;width:80pt'>Cross-region replication traffic</td>
  <td class=xl73 width=216 style='border-top:none;border-left:none;width:162pt'>Output traffic generated by synchronizing and replicating data from source
  Bucket to target Bucket via cross-region replication function</td>
  <td class=xl73 width=339 style='border-top:none;border-left:none;width:255pt'>Every day’s accumulative cross-region replication traffic (GB)
  * unit price per GB</td>
  <td class=xl74 width=69 style='border-top:none;border-left:none;width:52pt'>It is free now</td>
 </tr>
 <tr height=37 style='height:28.0pt'>
  <td rowspan=2 height=74 class=xl66 width=110 style='height:56.0pt;border-top:
  none;width:83pt'>Number of request</td>
  <td class=xl73 width=106 style='border-top:none;border-left:none;width:80pt'>GET Request</td>
  <td class=xl73 width=216 style='border-top:none;border-left:none;width:162pt'>All GET requests from Object Storage Service OPEN
  All GET requests from API</td>
  <td class=xl73 width=339 style='border-top:none;border-left:none;width:255pt'>Total number of every day’s accumulative GET requests/10000
  * request unit price per 10000 times</td>
  <td class=xl74 width=69 style='border-top:none;border-left:none;width:52pt'>It is free now</td>
 </tr>
 <tr height=37 style='height:28.0pt'>
  <td height=37 class=xl73 width=106 style='height:28.0pt;border-top:none;
  border-left:none;width:80pt'>PUT Request</td>
  <td class=xl73 width=216 style='border-top:none;border-left:none;width:162pt'>All GET requests from Object Storage Service OPEN
  All PUT requests from API</td>
  <td class=xl73 width=339 style='border-top:none;border-left:none;width:255pt'>Total number of every day’s accumulative PUT requests/10000
  * request unit price per 10000 times</td>
  <td class=xl74 width=69 style='border-top:none;border-left:none;width:52pt'>It is free now</td>
 </tr>
</table>

## Billing Cases

**Case background 1 (use standard storage)**

Company A is a media enterprise which stores a huge number of picture material files on the Object Storage Service. It adopts standard storage method. There are about 100GB picture files. The monthly Internet downlink traffic of picture files is about 500GB. It does not use CDN acceleration and the number of read or write requests is about 2 million per month.

Cost Composition

Storage capacity cost: 100(GB) * RMB 0.00427/GB/day * 30(days) = RMB12.81

Internet downlink traffic cost: 500(GB) * RMB 0.50/GB = RMB 250.00

Number of request cost: it is free temporarily, if it becomes a charge item, then the cost of this part is 2(million times) / 10000 * unit price/10000 times

Total monthly consumption = storage capacity cost + Internet downlink traffic cost = RMB 12.81 + RMB 250.00 = RMB 262.81

**Case background 2 (use Object Storage Service+CDN)**

Company B is a video website enterprise which stores a huge number of video files on the Object Storage Service. It adopts standard storage method. There are about 200GB video files. In each month, the video files use CDN acceleration, with the CDN Internet traffic being about 4TB, CDN back-to-source traffic being about 800GB (if the files to be accessed are not hit in the CDN nodes, then the files will be fetched from the Object Storage Service by back-to-source) and the number of read or write requests being 5 million.

Cost Composition

Storage capacity cost: 200(GB) * RMB 0.00427/GB/day * 30(days) = RMB 25.62

CDN back-to-source traffic cost: 800(GB) * RMB 0.14/GB = RMB 112.00

CDN public network traffic cost: 4 * 1024(GB) * RMB 0.35/GB = RMB 1433.60

Number of requests cost: it is temporarily free, if it becomes a charge item, then the cost of this part is 5(million times) / 10000  * unit price/10000 times

Total monthly consumption = storage capacity cost + CDN back-to-source cost + CDN public network traffic cost = RMB 25.62 + RMB 112.00 + RMB 1433.60 = RMB 1571.22

**Case background 3 (use reduced redundancy storage)**

Company C is an E-commerce enterprise which stores a huge number of electronic invoice files on the Object Storage Service as cold standby of data. It adopts low frequency access type storage method. There are about 500TB electronic invoice files, with access volume being little. In the current stage, both the Internet downlink traffic and the number of requests may be estimated as 0.

Cost Composition

Storage capacity cost: 500(TB) * 1024 *  RMB 0.00233/GB/day * 30(days) = RMB 35788.80

Internet downlink traffic cost: RMB 0.00

Number of request cost: temporarily free

Total monthly consumption = storage capacity cost + Internet downlink traffic cost = RMB 35788.80 + RMB 0.00 = RMB 35788.80

