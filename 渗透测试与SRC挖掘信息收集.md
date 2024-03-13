## 信息广度收集: 

### Whois信息
+ 站长之家: http://whois.chinaz.com
+ 国外在线: https://bgp.he.net

### 根域名
+ ENScan: https://github.com/wgpsec/ENScan_GO
+ 小蓝本: https://www.xiaolanben.com/pc
+ 企查查: https://www.qichacha.com
+ 天眼查: https://www.tianyancha.com
+ 爱企查: https://aiqicha.baidu.com

### 子域名
+ OneForAll: https://github.com/shmilylty/OneForAll
+ Amass: https://github.com/OWASP/Amass
+ Subfinder: https://github.com/projectdiscovery/subfinder
+ ksubdomain: https://github.com/knownsec/ksubdomain
+ subDomainsBrute: https://github.com/lijiejie/subDomainsBrute
+ Sonar: https://omnisint.io/
+ 查子域: https://chaziyu.com/ (在线)

### 端口+C段
+ Nmap: https://nmap.org
+ kscan: https://github.com/lcvvvv/kscan
+ Txportmap: https://github.com/4dogs-cn/TXPortMap
+ Masscan: https://github.com/robertdavidgraham/masscan

### 敏感信息
#### 01 谷歌语法
1. 后台地址
+ site:xxx.com intitle:管理|后台|登陆|管理员|系统|内部
+ site:xxx.com inurl:login|admin|system|guanli|denglu|manage|admin_login|auth|dev
2. 敏感文件
+ site:xxx.com (filetype:doc OR filetype:ppt OR filetype:pps OR filetype:xls OR filetype:docx OR filetype:pptx OR filetype:ppsx OR filetype:xlsx OR filetype:odt OR filetype:ods OR filetype:odg OR filetype:odp OR filetype:pdf OR filetype:wpd OR filetype:svg OR filetype:svgz OR filetype:indd OR filetype:rdp OR filetype:sql OR filetype:xml OR filetype:db OR filetype:mdb OR filetype:sqlite OR filetype:log OR filetype:conf)
3. 测试环境
+ site:xxx.com inurl:test|ceshi
+ site:xxx.com intitle:测试
4. 邮箱
+ site:xxx.com (intitle:"Outlook Web App" OR intitle:"邮件" OR inurl:"email" OR inurl:"webmail")
5. 其他
+ site:xxx.com inurl:api|uid=|id=|userid=|token|session
+ site:xxx.com intitle:index.of "server at"
#### 02 Github
+ 代码搜索: https://github.com/search?type=code&q=xxxx.com
+ @xxx.com password/secret/credentials/token/config/pass/login/ftp/ssh/pwd
+ @xxx.com security_credentials/connetionstring/JDBC/ssh2_auth_password/send_keys
#### 03 网盘引擎
+ 超能搜: https://www.chaonengsou.com
#### 04 其他知识平台
+ 语雀: https://www.yuque.com/search
+ CSDN: https://so.csdn.net/so/search
+ 简书: https://www.jianshu.com/search

### 空间引擎搜索
+ Hunter: https://hunter.qianxin.com
+ FOFA: https://fofa.so
+ Shadon: https://www.shodan.io
+ ZoomEye: https://www.zoomeye.org
+ Quake: https://quake.360.cn/quake/#/index

### 历史漏洞
+ Seebug: https://www.seebug.org
+ Exploit Database: https://www.exploit-db.com
+ Vulners: https://vulners.com
+ Sploitus: https://sploitus.com

### APP
+ 小蓝本: https://www.xiaolanben.com/pc
+ 七麦: https://www.qimai.cn
+ AppStore: https://www.apple.com/app-store

### 公众号
+ 微信直接搜索
+ 搜狗: https://weixin.sogou.com

### 小程序
+ 微信直接搜小程序
+ 支付宝直接搜小程序
+ 小蓝本: https://www.xiaolanben.com/pc

## 信息深度收集: 
### 指纹识别
+ ObserverWard:https://github.com/0x727/ObserverWard_0x727
+ 火狐插件: Wappalyzer
+ 云悉: http://www.yunsee.cn (在线)
+ EHole: https://github.com/EdgeSecurityTeam/EHole
+ TideFinger: https://github.com/TideSec/TideFinger

### Title识别
+ HTTPX: https://github.com/projectdiscovery/httpx
+ WebBatchRequest: https://github.com/ScriptKid-Beta/WebBatchRequest
+ Bscan: https://github.com/broken5/bscan

### 目录扫描
+ Dirsearch: https://github.com/maurosoria/dirsearch
+ Dirmap: https://github.com/H4ckForJob/dirmap

### JS接口
+ 插件：https://github.com/momosecurity/FindSomething
+ JSFinder: https://github.com/Threezh1/JSFinder
+ URLFinder: https://github.com/pingc0y/URLFinder
+ katana: https://github.com/projectdiscovery/katana
+ LinkFinder: https://github.com/GerbenJavado/LinkFinder
+ Packer-Fuzzer: https://github.com/rtcatc/Packer-Fuzzer (webpack)

+ 搜索关键接口
1. config/api
2. method:"get"
3. http.get("
4. method:"post"
5. http.post("
6. $.ajax
7. service.httppost
8. service.httpget

### 真实ip
+ 在线: https://ipchaxun.com
+ dns检测: https://tools.ipip.net/dns.php
+ Xcdn: https://github.com/3xp10it/xcdn

### 旁站
+ 在线: http://stool.chinaz.com/same
+ 在线: https://site.ip138.com

### WAF识别
+ WhatWaf: https://github.com/Ekultek/WhatWaf
+ wafw00f: https://github.com/EnableSecurity/wafw00f

## 信息收集平台
+ ARL: https://github.com/TophantTechnology/ARL
+ ARL-plus: https://github.com/ki9mu/ARL-plus-docker
+ ShuiZe: https://github.com/0x727/ShuiZe_0x727
+ BBOT: https://github.com/blacklanternsecurity/bbot

## 漏洞扫描工具
+ afrog: https://github.com/zan8in/afrog
+ Nuclei: https://github.com/projectdiscovery/nuclei
+ Goby: https://gobies.org
+ Xray: https://github.com/chaitin/xray
