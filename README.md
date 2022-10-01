#  Poc-Exp-Tools
----
Introduce:

    In the actual penetration, after the early information collection, 
    if there is an EXP with the vulnerability directly, 
    it can often save a lot of time. So I collected a lot of EXPs, hoping to speed up efficiency in my work.

----

## CVE && 利用 && EXP && 复现
| 年份        | ID        | 名称/CVE|   类型  | 
|:----------:|:----------:|:------------- |:------------------- |
|     2014      |           |       |            |
|           |     1      |  心脏滴血漏洞(CVE-2014-0160)     |         /CVE/心脏滴血漏洞(CVE-2014-0160)   |
|     2015      |           |       |            |
|           |     1      |  (CVE-2015-1635)Microsoft Windows HTTP.sys     |         /CVE/Microsoft Windows HTTP.sys(CVE-2015-1635)   |
|     2017      |           |       |            |
|           |     1      |  Windows COM 特权提升漏洞漏洞(CVE-2017-0213)     |         /提权/windows/Windows COM 特权提升漏洞漏洞(CVE-2017-0213)   |
|           |     2      |  Office 远程代码执行漏洞（缓冲区溢出）(CVE-2017-11882 )     |         /CVE/Office 远程代码执行漏洞（缓冲区溢出）(CVE-2017-11882 )   |
|     2018      |           |       |            |
|           |     1      |  栈溢出漏洞(CVE-2018-0802)     |          /CVE/CVE-2018-0802栈溢出漏洞 |
|     2019      |           |       |            |
|           |     1      |  Django JSONField/HStoreField SQL注入(CVE-2019-14234)     |         复现：https://juejin.cn/post/7086263713908391944  |
|     2021      |           |       |            |
|           |     1      |  Windows本地提权漏洞(CVE-2021-1732)      |         (/提权/Windows本地提权漏洞(CVE-2021-1732)  |
|           |     2      |  缓冲区错误提权漏洞(CVE-2021-26868)      |         (/提权/缓冲区错误提权漏洞(CVE-2021-26868) |
|     2022      |           |       |            |
|           |     1      |  HTTP 协议栈远程代码执行漏洞(CVE-2022-21907)      |         (/CVE/HTTP 协议栈远程代码执行漏洞(CVE-2022-21907) )(复现:)  |


| ID        | windows/linux提权|   地址  | 
|:----------:|:------------- |:------------------- |
|     1      |  栈溢出漏洞(CVE-2018-0802)     |          /CVE/CVE-2018-0802栈溢出漏洞 |
|     2      |  Windows COM 特权提升漏洞漏洞(CVE-2017-0213)     |         /提权/windows/Windows COM 特权提升漏洞漏洞(CVE-2017-0213)   |
|     3      |  Windows本地提权漏洞(CVE-2021-1732)      |         (/提权/Windows本地提权漏洞(CVE-2021-1732)  |
|     4      |  缓冲区错误提权漏洞(CVE-2021-26868)      |         (/提权/缓冲区错误提权漏洞(CVE-2021-26868) |


| ID        | 名称/POC|   地址  | 
|:----------:|:------------- |:------------------- |
|   1      |       ms17-010    |    /POC/ms17-010/        |
|      2     |         |          |

| ID        | 名称/struts2|   地址  | 
|:----------:|:------------- |:------------------- |
|   1      |       struts2-045-exp    |    /struts2/struts2-045-exp        |
|      2     |     struts2-048-exp     |     /struts2/struts2-048-exp     |
|      3    |     struts2 通用漏洞利用工具     |     /struts2/struts2 通用漏洞利用工具(使用范围：S2-DevMode、S2-005、S2-009、S2-016、S2-019、S2-032、S2-037、S2-045-1、S2-045-3、S2-046)     |


## 漏洞复现
| ID        | 名称/CVE|   地址  |
|----------|------------- |------------------- |
|     1      |  Django JSONField/HStoreField SQL注入(CVE-2019-14234)     |     https://juejin.cn/post/7086263713908391944  |
|     2      |  ms17-010(永恒之蓝)复现      |  https://juejin.cn/post/7075975855909896228  |

## 靶场通关
| ID         | 靶场名称/CVE       |   地址                                     | 
|:----------:|:-------------     |:-------------------                       |
| 1          |  pikachu靶场      |https://juejin.cn/post/7119111677383032846  |
| 2          |  DVWA靶场-low      |  https://juejin.cn/post/7123844618092806152  |
| 3          |  xss-labs-master靶场      |  https://juejin.cn/post/7122071201068875789  |
| 4          |  DVWA-Medium&High       |  https://juejin.cn/post/7125723811718103053  |
|5   |  upload-labs|    https://juejin.cn/post/7128017494593241096            |





