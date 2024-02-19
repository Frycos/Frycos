# Excerpt of vulnerabilities I found in the last years

## 2019

* **cPanel** - [Unauthenticated Remote Code Execution](https://documentation.cpanel.net/display/CL/cpanel-dovecot-solr+Change+Log) (RCE) together with mwulftange in versions prior to 8.2.0-1.cp1180
* **FTAPI** - [Authenticated Remote Code Execution](https://web.archive.org/web/20200814001535/https://www.ftapi.com/Release-Notes) (RCE) in versions prior to 4.6.3
* **ManageEngine OpManager** - [Unauthenticated/Authenticated SQL injection](https://www.manageengine.com/network-monitoring/help/read-me-complete.html) in versions prior to v12.4 Build no 124089 (see also [blog post](https://medium.com/@frycos/finding-sql-injections-fast-with-white-box-analysis-a-recent-bug-example-ca449bce6c76))
* **C1 CMS** - [Authenticated Remote Code Execution](https://github.com/Orckestra/C1-CMS-Foundation/releases/tag/v6.7) in versions prior to 6.7 (see also [blog post](https://medium.com/@frycos/yet-another-net-deserialization-35f6ce048df7))
* **TinyWall** - Privilege Escalation to SYSTEM in versions prior to 2.1.13 (see also [my blog post](https://code-white.com/blog/2020-01-cve-2019-19470-rumble-in-pipe/))

## 2020

* **Various WordPress Plugins** - Various unauthenticated vulnerabilities, e.g. [this](https://wpvulndb.com/vulnerabilities/10115), [that](https://wpvulndb.com/vulnerabilities/10162), [etc](https://wpvulndb.com/vulnerabilities/10174). 
* **SmarterTools SmarterStats** - [Unauthenticated Remote Code Execution](https://www.smartertools.com/smarterstats/release-notes/current) (RCE) in versions prior to Build 7422 (Apr 27, 2020)
* **HPE Systems Insight Manager** - [Unauthenticated Remote Code Execution](https://support.hpe.com/hpesc/public/docDisplay?docLocale=en_US&docId=hpesbhf04008en_us) (RCE) in versions prior to v7.4, v7.5, v7.6 with Hotfix 63 or lower
* **OpenNMS** - [Authenticated Remote Code Execution](https://issues.opennms.org/browse/NMS-12673) (RCE) in versions prior to 26.0.0 (write-up in tracker issue as PDF)
* **Dell EMC VxRail** - [Unauthenticated Access to encrypted credentials](https://www.dell.com/support/kbdoc/de-de/000153604/dsa-2020-136-dell-emc-vxrail-appliance-improper-authentication-vulnerability) in versions 4.7.410 and 4.7.411 and 4.7.510
* **Various ManageEngine products** - Unauthenticated change of system configurations affecting more than 10 ManageEngine products (see also [blog post](https://medium.com/@frycos/another-zoho-manageengine-story-7b472f1515f5))
* **FreePBX** - [Authenticated Stored XSS and Remote Code Execution](https://wiki.freepbx.org/display/FOP/2020-08-17+XSS+Vulnerability+In+logfiles) in versions prior to 13.0.10.10
* **Cisco Security Manager** - [Multiple](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-csm-java-rce-mWJEedcD) [Unauthenticated](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-csm-path-trav-NgeRnqgR) [Vulnerabilities](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-csm-rce-8gjUz9fW) (Remote Code Execution, Files Access etc.) in versions prior to 4.22 and 4.23
* **Graylog** - [Unauthenticated Sensitive Information Disclosure](https://www.graylog.org/post/announcing-graylog-v3-3-6) in non-standard deployment in versions prior to 3.3.6 together with invist

## 2021

* **CrushFTP** - [Authenticated Remote Code Execution](https://gist.github.com/Frycos/2015161f22827d823060a8b162bc1f89) (RCE) not fixed (0day)
* **Citrix AppDNA** - [Unauthenticated Path Traversal File Overwrite](https://twitter.com/frycos/status/1386781378612809734) not fixed (0day)
* **Aternity Agent** - [Privilege Escalation to SYSTEM](https://help.aternity.com/bundle/release_news_agent_console_saas/page/release_news/topics/release_rn_agent_12.1.html) in versions prior to 12.1.3.95
* **Jedox** - [Authenticated Remote Code Execution](https://knowledgebase.jedox.com/jedox/release-notes-2021-3.htm) in versions prior to 2021.3 together with invist (even unauthenticated in older versions)
* **TIBCO JasperReports Server** - [Authenticated XML External Entity](https://www.tibco.com/support/advisories/2021/10/tibco-security-advisory-october-12-2021-tibco-jasperreports-server-2021-35496) (XXE) in versions prior to 7.9.1 (another "won't fix" RCE)
* **Eilisys Ascent ESS (Employee Self Service)** - Unauthenticated Remote Code Execution not fixed (0day)
* **PikeTec TPT** - [Unauthenticated Remote Code Execution](https://piketec.com/de/tpt-download/) in versions prior to [16u4](https://files.piketec.com/downloads/releases/TPT16u4/211128-tpt-16u4-release-notes.pdf) and [15u5](https://files.piketec.com/downloads/releases/TPT15u5/211128-tpt-15u5-release-notes.pdf) (17u1 probably still affected)
* **IBM Archive and Essence Manager** - [Unauthenticated XML External Entity](https://www.ibm.com/products/arema-archive-and-essence-manager) in latest and prior versions (0day)

## 2022

* **Microsoft Exchange 2013/2016/2019** - [Deserialization Protection Bypass](https://msrc.microsoft.com/update-guide/vulnerability/CVE-2022-21969) in versions prior Patchday January 2022 (see also my [blog post](https://medium.com/@frycos/searching-for-deserialization-protection-bypasses-in-microsoft-exchange-cve-2022-21969-bfa38f63a62d))
* **Act! Premium** - [Unauthenticated Remote Code Execution](https://www.act.com/) (see also [my blog post](https://code-white.com/blog/2023-07-from-blackbox-dotnet-remoting-to-rce/))
* **HPE StoreEver ESL G3 Tape Library** - [Unauthenticated Remote Code Execution](https://www.hpe.com/psnow/doc/c04111556.pdf?jumpid=in_lit-psnow-getpdf&qsVersion=26&ver=26) (reported but "won't fix")
* **3CX Phone System** - [Unauthenticated Remote Code Execution](https://www.3cx.com/blog/releases/v18-update-3-final/) in Windows installations prior to version 18 update 3 (see also my [blog post](https://medium.com/@frycos/pwning-3cx-phone-management-backends-from-the-internet-d0096339dd88))
* **Starface ComfortPhoning** - [Authenticated Remote Code Execution](https://www.starface.com/) tested against latest version 7.2.0.5 (0day, see also my [blog post](https://frycos.github.io/vulns4free/2022/05/24/security-code-audit-fails.html))
* **Citrix Application Delivery Management** - [Unauthenticated Root Password Reset and License Service Control](https://support.citrix.com/article/CTX460016/citrix-application-delivery-management-security-bulletin-for-cve202227511-and-cve202227512) together with CaptnBanana in versions 13.0 before 13.0-85.19 and 13.1 before 13.1-21.53
* **SmarterTools SmarterStats** - [Unauthenticated Remote Code Execution and File Read](https://www.smartertools.com/smarterstats/release-notes/current) (RCE) in versions prior to Build 8195 (Jun 9, 2022). See my [blog post](https://frycos.github.io/vulns4free/2022/06/17/yet-another-rpc-framework.html)
* **Kerio Connect** - [Authenticated Stack Buffer Overflow with any webmail user](https://gist.github.com/Frycos/62fa664bacd19a85235be19c6e4d7599) in versions between 9.4 and 9.4.2 (patched in 10.0.0)
* **R1Soft Server Backup Manager (SBM)** - [Authentication Bypass](https://www.connectwise.com/company/trust/security-bulletins/r1soft-and-recover-security-bulletin) in versions prior to 6.16.4.
* **Skype for Business 2019** - Unauthenticated Server-side Request Forgery (see also [my blog post](https://frycos.github.io/vulns4free/2022/09/26/skype-audit-part2.html))
* **Apache Archiva** - Unauthorized User Registration (unpatched, won't fix) in latest version 2.2.9 and before
* **Sophos Mobile** - [Unauthenticated XML External Entity](https://www.sophos.com/en-us/security-advisories/sophos-sa-20221116-smc-xee) in versions between 5.0.0 and 9.7.4
* **pgAdmin Server** - [Unauthenticated Remote Code Execution](https://www.pgadmin.org/docs/pgadmin4/development/release_notes_6_17.html) in pgAdmin Servers on Windows prior to version 6.17 (see also [my blog post](https://frycos.github.io/vulns4free/2022/12/02/rce-in-20-minutes.html))

## 2023

* **Docmosis Tornado** - [Multiple Vulnerabilities](https://resources.docmosis.com/content/documentation/tornado-v2-9-5-release-notes) in versions prior to 2.9.5 (see also [my blog post](https://frycos.github.io/vulns4free/2023/01/24/0days-united-nations.html))
* **GoAnywhere MFT** - [Pre-Auth Remote Code Execution](https://github.com/rapid7/metasploit-framework/pull/17607) in versions up to 7.1.1 ([read about rediscovering my own bug](https://frycos.github.io/vulns4free/2023/02/06/goanywhere-forgotten.html))
* **install4j** - [XML External Entity in Update function](https://www.ej-technologies.com/products/install4j/overview.html) in versions prior to 10.0.5 (see also [my blog post](https://frycos.github.io/vulns4free/2023/02/12/install4j-xxe.html))
* **Fortinet FortiNAC** - Multiple Unauthenticated Vulnerabilities in versions prior to 9.4.(2|3) (see also [my blog post](https://frycos.github.io/vulns4free/2023/06/18/fortinac.html))
* **Technicolor TG670 DSL Gateway Router** - Administrative Backdoor Account by Telecom Italia (see [CERT/CC Note](https://www.kb.cert.org/vuls/id/913565))
* **MCL Technologies MCL-Net** - [Unauthenticated Arbitrary File Read as SYSTEM](https://www.mcl-mobilityplatform.com/downloads.php) in versions prior to 4.6
* **GANZ Security AI Box** - [Authentication Bypass](https://www.ganzsecurity.eu/index.php/en/products/aibox) in all versions released prior to July 2023 (see also [my blog post](https://frycos.github.io/vulns4free/2023/11/07/hacking-like-hollywood.html))

## 2024

* **Netavis CCTV with Observer** - [Pre-Auth XML External Entity](https://www.netavis.net/cctv-with-observer/) vulnerability proven for version 4.6.8 (0day)
* **Delta Dore Lifedomus** - [Pre-Auth Server-side Request Forgery and XML External Entity](https://www.deltadore.co.uk/fichier/2265) in latest (and last) version (0day)
* **Tableau Server** - Multiple Authenticated Vulnerabilities (won't fix, report [written down in my blog post](https://frycos.github.io/vulns4free/2024/02/19/tableau-server-no-vulns.html))
