

# 主要功能

使用云安全中心可以看到用户业务可视化资产拓扑、所有已购安全产品的关键告警信息，从而避免信息散乱，错过重要安全风险，并且态势感知从全局的角度帮助用户分析网络、应用、主机的历史安全状态。使用云安全中心需要用户的主机安装agent服务。

## 1、概览

概览能够查看云安全中心的动态信息，其中包括资产基本信息、安全基本信息、安全具体信息和拓扑图的安全信息汇总。

## 2、安全威胁

安全威胁是指用户服务上存在的加以利用可能会造成入侵威胁的事件。类型包括主机漏洞、WEB漏洞、应用和系统基线、外网开放服务。

  - 主机漏洞包括用户云主机、本地服务器上的系统漏洞和安装的应用漏洞。攻击者利用漏洞进行攻击可能会获取系统访问权限、敏感信息、导致拒绝服务。
  - WEB漏洞指用户主机上部署的WEB服务存在的安全漏洞，包括XSS漏洞、SQL注入、WebShell上传、命令注入、非法HTTTP协议请求等。
  - 应用和系统基线包括系统、应用弱口令的检查和应用层软件（例如，PHP\Mangodb\Redis\mysql\nginx\httpd等）配置进行读取分析，判断配置项是否满足安全基线的配置要求。

## 3、安全事件

安全事件是指对用户服务造成实际安全影响的威胁事件，类型包括异常登录行为、木马、DDoS攻击和应用层面的WEB流量攻击。

  - 异地登录行为能够检测服务器上的异常登录行为，当发现异地登录、暴力破解。
  - 自主研发的木马检测功能，拥有代码分析、数据流分析、异常网络流量分析等多种检测手段，使用云端大数据分析和静态规则相结合的检测体系、分析恶意代码登手段，能够发现：php、jsp网站后门、勒索软件、ddos后门、botnet、以及各类常见病毒。
  - DDoS攻击通过使目标服务器填满流量，使其超负荷到无法运行的程度，从而致使网站瘫痪。
  - 应用层面的WEB流量攻击会影响应用程序的可用性、损害安全性或消耗过多的资源。

## 4、安全防护

安全防护功能从安全的角度对用户业务目前使用的安全防护措施进行评测，并根据用户业务需要指出缺乏的安全防护措施，辅助用户建立安全系统。主要包括网络DDoS攻击防护UDDoS\UClean\海外清洗、 WEB攻击防护的应用防火墙、主机入侵检测、漏洞扫描等。

## 5、等保预检

2017年6月1日开始实施的《网络安全法》，从法律层面确定了网络安全等级保护制度。目前进行安全等保认证是每个企业的责任和业务。等保预检服务通过专业安全人士对等保条目细化到具体云资产，然后实现对用户各项云资产满足情况的自动化检测，具体指出通信网络、区域边界、计算环境和管理中心的安全合规满足情况，并针对不满足情况给出具体的资产的安全建议，辅助用户无需专业安全人员情况下完成等保的前期自我审核工作。

## 6、资产拓扑

UCloud云安全中心通过在用户主机上部署agent，以自动化的方式或者用户自主选择的方式建立某业务的资产拓扑，根据服务内的真实连接情况画出该业务进程级别的访问关系拓扑图，并通过规则、大数据分析实现对拓扑内服务按照集群、功能等情况进一步实现精细化、可视化的分组，当业务由于扩容需要增加新的机器时，云安全中心可以自动化检测并添加到拓扑中，从而实现完全贴合实际业务的服务级别资源管理，并实现了创新型的拓扑图展示方式。

通过资产拓扑服务用户可以只关注某个业务的资产情况、安全防护、安全事件、风险威胁与等保情况。