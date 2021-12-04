# Excerpt of vulnerabilities I found in the last years

## 2019

* **cPanel** - [Unauthenticated Remote Code Execution](https://documentation.cpanel.net/display/CL/cpanel-dovecot-solr+Change+Log) (RCE) together with mwulftange in versions prior to 8.2.0-1.cp1180
* **FTAPI** - [Authenticated Remote Code Execution](https://web.archive.org/web/20200814001535/https://www.ftapi.com/Release-Notes) (RCE) in versions prior to 4.6.3
* **ManageEngine OpManager** - [Unauthenticated/Authenticated SQL injection](https://www.manageengine.com/network-monitoring/help/read-me-complete.html) in versions prior to v12.4 Build no 124089 (see also [blog post](https://medium.com/@frycos/finding-sql-injections-fast-with-white-box-analysis-a-recent-bug-example-ca449bce6c76))
* **C1 CMS** - [Authenticated Remote Code Execution](https://github.com/Orckestra/C1-CMS-Foundation/releases/tag/v6.7) in versions prior to 6.7 (see also [blog post](https://medium.com/@frycos/yet-another-net-deserialization-35f6ce048df7))
* **TinyWall** - Privilege Escalation to SYSTEM in versions prior to 2.1.13 (see also [blog post](https://codewhitesec.blogspot.com/2020/01/cve-2019-19470-rumble-in-pipe.html))

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
* **Citrix AppDNA** - Unauthenticated Path Traversal File Overwrite not fixed (0day)
* **Aternity Agent** - [Privilege Escalation to SYSTEM](https://help.aternity.com/bundle/release_news_agent_console_saas/page/release_news/topics/release_rn_agent_12.1.html) in versions prior to 12.1.3.95
* **Jedox** - [Authenticated Remote Code Execution](https://knowledgebase.jedox.com/jedox/release-notes-2021-3.htm) in versions prior to 2021.3 together with invist (even unauthenticated in older versions)
* **TIBCO JasperReports Server** - [Authenticated XML External Entity](https://www.tibco.com/support/advisories/2021/10/tibco-security-advisory-october-12-2021-tibco-jasperreports-server-2021-35496) (XXE) in versions prior to 7.9.1 (another "won't fix" RCE)
* **Eilisys Ascent ESS (Employee Self Service)** - Unauthenticated Remote Code Execution not fixed (0day)
* **PikeTec TPT** - [Unauthenticated Remote Code Execution](https://piketec.com/de/tpt-download/) in versions prior to [16u4](https://files.piketec.com/downloads/releases/TPT16u4/211128-tpt-16u4-release-notes.pdf) and [15u5](https://files.piketec.com/downloads/releases/TPT15u5/211128-tpt-15u5-release-notes.pdf) (17u1 probably still affected)
* **IBM Archive and Essence Manager** - [Unauthenticated XML External Entity](https://www.ibm.com/products/arema-archive-and-essence-manager) in latest and prior versions (0day not fixed yet)
