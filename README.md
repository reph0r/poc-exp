#  Poc-Exp-Tools
----
## Introduce:
&emsp;&emsp;&emsp;In the actual penetration, after the early information collection, if there is an EXP with the vulnerability directly, it can often save a lot of time. So I collected a lot of EXPs, hoping to speed up efficiency in my work.

## Catalogue:
- 一. CVE

- 二. 提权(windows/linux)

- 三. POC

- 四. struts2

- 五. WebLogic

- 六. CMS 

- 七. Django 

- 八. Docker 

- 九. Jenkins 

- 十. Thinkphp

- 十一. Tomcat

- 十二. ActiveMQ

- 十三. shiro

- 十四. Nginx

- 漏洞复现

- 靶场、学习笔记


<details>
<summary><font size="20" color="orange">Tools</font></summary>
<pre><code>

## (一.)科学上网
     地址：https://github.com/wms521125/freevpn
## (二.)在线工具和资源大全
### (1)信息探测收集
#### (CMS识别
| Name     |  address |
|:-------------:|:------:|
| 在线指纹识别         | http://whatweb.bugscaner.com/look/ |
|    云悉指纹          |    https://www.yunsee.cn/       |
|      whatcms           |    https://whatcms.org/    |
|      Tidersec         |  http://finger.tidesec.net/     |
|     ssl探测         |    https://myssl.com/ ， https://www.trustasia.com/    |


## (三.)Web安全工具
## (四.)逆向分析工具
## (五.)逆向分析工具

</code></pre>
</details>


----

## 一. CVE
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
|           |     2   |  OGNL注入漏洞(CVE-2022-26134)      |         (/CVE/OGNL注入漏洞(CVE-2022-26134)  |


## 二. 提权(windows/linux)
| ID        | windows/linux提权|   地址  | 
|:----------:|:------------- |:------------------- |
|     1      |  栈溢出漏洞(CVE-2018-0802)     |          /CVE/CVE-2018-0802栈溢出漏洞 |
|     2      |  Windows COM 特权提升漏洞漏洞(CVE-2017-0213)     |         /提权/windows/Windows COM 特权提升漏洞漏洞(CVE-2017-0213)   |
|     3      |  Windows本地提权漏洞(CVE-2021-1732)      |         (/提权/Windows本地提权漏洞(CVE-2021-1732)  |
|     4      |  缓冲区错误提权漏洞(CVE-2021-26868)      |         (/提权/缓冲区错误提权漏洞(CVE-2021-26868) |
|     5      |  CVE-2017-8464      |         (/提权/windows/CVE-2017-8464 |
|     6      |  CVE-2018-0833      |         (/提权/windows/CVE-2018-0833 |
|     7      |  CVE-2018-8120      |         (/提权/windows/CVE-2018-8120 |
|     8      |  CVE-2020-1472      |         (/提权/windows/CVE-2020-1472 |
|     9      |  MS03-026      |         (/提权/windows/MS03-026 |
|     10      |  MS05-039      |         (/提权/windows/MS05-039 |
|     11      |  MS06-040      |         (/提权/windows/MS06-040 |
|     12      |  MS08-025      |         (/提权/windows/MS08-025 |
|     13      |  MS08-066      |         (/提权/windows/MS08-066 |
|     14      |  MS08-067      |         (/提权/windows/MS08-067 |
|     15      |  MS08-068      |         (/提权/windows/MS08-068 |
|     16      |  MS09-012      |         (/提权/windows/MS09-012 |
|     17      |  MS09-020     |         (/提权/windows/MS09-020 |
|     18      |  MS09-050      |         (/提权/windows/MS09-050 |
|     19      |  MS10-012      |         (/提权/windows/MS10-012 |
|     20      |  MS10-015      |         (/提权/windows/MS10-015 |
|     21      |  MS10-048      |         (/提权/windows/MS10-048 |
|     22      |  MS10-059     |         (/提权/windows/MS10-059  |
|     23      |  MS10-065      |         (/提权/windows/MS10-065 |
|     24     |  MS10-092      |         (/提权/windows/MS10-092 |
|     25      |  MS11-011      |         (/提权/windows/MS11-011 |
|     26      |  MS11-046      |         (/提权/windows/MS11-046 |
|     27      |  MS11-062      |         (/提权/windows/MS11-062 |
|     28      |  MS11-080      |         (/提权/windows/MS11-080 |
|     31      |  MS12-020      |         (/提权/windows/MS12-020 |
|     32      |  MS12-042      |         (/提权/windows/MS12-042  |
|     33     |  MS13-005      |         (/提权/windows/MS13-005 |
|     34      |  MS13-046     |         (/提权/windows/MS13-046 |
|     35      |  MS13-053      |         (/提权/windows/MS13-053 |
|     36      |  MS14-002      |         (/提权/windows/MS14-002 |
|     37     |  MS14-040      |         (/提权/windows/MS14-040 |
|     38      |  MS14-058      |         (/提权/windows/MS14-058 |
|     39      |  MS14-066      |         (/提权/windows/MS14-066 |
|     40      |  MS14-068      |         (/提权/windows/MS14-068 |
|     41      |  MS14-070      |         (/提权/windows/MS14-070 |
|     42      |  MS15-001      |         (/提权/windows/MS15-001 |
|     43      |  MS15-010      |         (/提权/windows/MS15-010 |
|     44      |  MS15-015     |         (/提权/windows/MS15-015 |
|     45      |  MS15-051      |         (/提权/windows/MS15-051 |
|     46      |  MS15-061      |         (/提权/windows/MS15-061 |
|     47     |  MS15-076      |         (/提权/windows/MS15-076 |
|     48      |  MS15-077      |         (/提权/windows/MS15-077 |
|     49      |  MS15-097      |         (/提权/windows/MS15-097 |
|     50      |  MS16-014      |         (/提权/windows/MS16-014 |
|     51      |  MS16-016      |         (/提权/windows/MS15-016 |
|     52      |  MS16-032      |         (/提权/windows/MS16-032 |
|     53      |  MS16-034      |         (/提权/windows/MS16-034 |
|     54      |  MS16-075      |         (/提权/windows/MS16-075 |
|     55      |  MS16-098      |         (/提权/windows/MS16-098 |
|     56     |  MS16-111      |         (/提权/windows/MS16-111 |
|     57      |  MS16-135      |         (/提权/windows/MS16-135 |
|     58      |  MS17-010      |         (/提权/windows/MS17-010 |
|     59      |  MS17-017      |         (/提权/windows/MS17-017 |




## 三. POC
| ID        | 名称/POC|   地址  | 
|:----------:|:------------- |:------------------- |
|   1      |       ms17-010    |    /POC/ms17-010/        |
|      2     |         |          |



## 四. struts2
| ID        | 名称/struts2|   地址  | 
|:----------:|:------------- |:------------------- |
|   1      |       struts2-045-exp    |    /struts2/struts2-045-exp        |
|      2     |     struts2-048-exp     |     /struts2/struts2-048-exp     |
|      3    |     struts2 通用漏洞利用工具     |     /struts2/struts2 通用漏洞利用工具(使用范围：S2-DevMode、S2-005、S2-009、S2-016、S2-019、S2-032、S2-037、S2-045-1、S2-045-3、S2-046)     |

## 五. WebLogic
| ID        | 名称/WebLogic|   地址  | 
|:----------:|:------------- |:------------------- |
|   1      |       CVE-2018-2628 weblogic 反序列化漏洞    |    /WebLogic/CVE-2018-2628 weblogic 反序列化漏洞        |
|      2     |    CVE-2019-2618 弱口令&任意文件上传漏洞    |    /WebLogic/CVE-2019-2618 弱口令&任意文件上传漏洞      |
|      3     |    CVE-2020-14882权限绕过、代码执行     |    /WebLogic/CVE-2020-14882权限绕过、代码执行      |


## 六. CMS 


## 七. Django 
| ID        | 名称/Django|   地址  | 
|:----------:|:------------- |:------------------- |
|   1      |        （CVE-2017-12794）Django debug page XSS漏洞    |    /Django/（CVE-2017-12794）Django debug page XSS漏洞         |
|      2     |    （CVE-2018-14574）Django  2.0.8 任意URL跳转漏洞  |    /Django/（CVE-2018-14574）Django  2.0.8 任意URL跳转漏洞    |
|      3     |    （CVE-2019-14234）Django JSONField sql注入漏洞     |    /Django/（CVE-2019-14234）Django JSONField sql注入漏洞       |
|      4     |    （CVE-2020-7471）Django sql注入漏洞     |    /Django/（CVE-2020-7471）Django sql注入漏洞     |
|      5     |    （CVE-2020-9402）Django Geo sql注入     |    /Django/（CVE-2020-9402）Django Geo sql注入      |

## 八. Docker 
| ID        | 名称/Docker|   地址  | 
|:----------:|:------------- |:------------------- |
|   1      |       Docker 容器逃逸漏洞 (CVE-2020-15257)复现     |    /Docker/Docker 容器逃逸漏洞 (CVE-2020-15257)复现        |
|      2     |    Docker 未授权访问   |    /Docker/Docker 未授权访问      |
|      3     |    （CVE-2019-14271）Docker copy漏洞     |    /Docker/（CVE-2019-14271）Docker copy漏洞      |

## 九. Jenkins 
| ID        | 名称/Jenkins|   地址  | 
|:----------:|:------------- |:------------------- |
|   1      |        Jenkins 功能未授权访问导致的远程命令执行漏洞    |    /Jenkins/Jenkins 功能未授权访问导致的远程命令执行漏洞        |
|      2     |    （CVE-2017-1000353）Jenkins-CI 远程代码执行漏洞   |    /Jenkins/（CVE-2017-1000353）Jenkins-CI 远程代码执行漏洞     |
|      3     |    （CVE-2018-1000861）Jenkins 远程命令执行漏洞     |    /Jenkins/（CVE-2018-1000861）Jenkins 远程命令执行漏洞       |
|      4     |    （CVE-2019-1003000）Jenkins 远程代码执行漏洞     |    /Jenkins/（CVE-2019-1003000）Jenkins 远程代码执行漏洞       |
|      5     |    （CVE-2019-10475）反射xss     |    /Jenkins/（CVE-2019-10475）反射xss       |



## 十. Thinkphp


## 十一. Tomcat


## 十二. ActiveMQ


## 十三. shiro

## 十四. Nginx
| ID        | 名称|   地址  |
|----------|------------- |------------------- |
|     1      |  Nginx 1.20.0 - Denial of Service (DOS)     |     Nginx/Nginx 1.20.0 - Denial of Service (DOS)  |

<details>
<summary><font size="20" color="orange">漏洞复现</font></summary>
<pre><code>

## 漏洞复现
| ID        | 名称|   地址  |
|----------|------------- |------------------- |
|     1      |  Django JSONField/HStoreField SQL注入(CVE-2019-14234)     |     https://juejin.cn/post/7086263713908391944  |
|     2      |  ms17-010(永恒之蓝)复现      |  https://juejin.cn/post/7075975855909896228  |

</code></pre>
</details>



<details>
<summary><font size="20" color="orange">靶场、学习笔记</font></summary>
<pre><code>

## 靶场笔记
| ID         | 靶场名称      |   地址                                     | 
|:----------:|:-------------     |:-------------------                       |
| 1          |  pikachu靶场      |https://juejin.cn/post/7119111677383032846  |
| 2          |  DVWA靶场-low      |  https://juejin.cn/post/7123844618092806152  |
| 3          |  xss-labs-master靶场      |  https://juejin.cn/post/7122071201068875789  |
| 4          |  DVWA-Medium&High       |  https://juejin.cn/post/7125723811718103053  |
|5   |  upload-labs|    https://juejin.cn/post/7128017494593241096            |

</code></pre>
</details>










