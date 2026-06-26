# about-me
# 安全致谢记录 / Security Acknowledgement Records

Last updated: 2026-06-26

## 中文版本

本页面整理公开安全公告中的安全致谢记录，并区分三类信息：致谢归属、厂商公告内容、第三方漏洞元数据。

### 范围

* 华为消费者业务安全致谢页面列出 20 个相关 CVE。
* Apple 安全内容页面列出 1 条 Additional Recognition 记录，该记录未映射到具体 CVE。
* 主表以厂商官方致谢页面和厂商安全公告为准。
* CVSS、CWE、攻击向量等第三方漏洞元数据单独列出，不与厂商公告评级混写。

### 来源层级

| 层级       | 含义                                                     | 本页面用途                              |
| -------- | ------------------------------------------------------ | ---------------------------------- |
| 官方致谢     | 厂商在致谢页面或 recognition 段落中公开列出相关记录。                      | 用于确认致谢归属。                          |
| 厂商安全公告   | 厂商发布 CVE 描述、影响、评级、受影响版本或产品范围。                          | 用于记录漏洞详情。                          |
| 第三方漏洞元数据 | NVD、GitHub Advisory 等漏洞数据库提供 CVSS、CWE、向量、发布时间或修改时间等信息。 | 单独保存，不覆盖厂商公告字段。                    |
| 非 CVE 致谢 | 厂商公开致谢，但未映射到具体 CVE。                                    | 用于记录 Apple Additional Recognition。 |

### 组织层级

| 厂商    | 组织层级                      | 官方来源级别                      | 产品或栏目层级                                              |
| ----- | ------------------------- | --------------------------- | ---------------------------------------------------- |
| 华为    | Huawei Consumer / 华为消费者业务 | 华为消费者业务安全致谢页面；华为消费者业务安全公告   | 手机/平板安全公告；智能手表安全公告                                   |
| Apple | Apple Support 安全内容页面      | Apple security content page | iOS 26 and iPadOS 26；Additional recognition / Camera |

### 华为 CVE 记录

| 致谢年份 | CVE            | 官方来源级别        | 组织层级            | 公告                                           | 模块        | 漏洞描述      | 影响              | 华为评级     | 受影响版本                                          |
| ---- | -------------- | ------------- | --------------- | -------------------------------------------- | --------- | --------- | --------------- | -------- | ---------------------------------------------- |
| 2025 | CVE-2025-54654 | 官方致谢 + 厂商安全公告 | Huawei Consumer | Phones/Tablets, October 2025                 | 图库模块      | 权限控制漏洞    | 成功利用可能影响服务机密性。  | Medium   | HarmonyOS5.1.0, HarmonyOS5.0.1                 |
| 2025 | CVE-2025-58277 | 官方致谢 + 厂商安全公告 | Huawei Consumer | Phones/Tablets, October 2025                 | 相机应用      | 权限验证绕过漏洞  | 成功利用可能影响服务机密性。  | Medium   | HarmonyOS5.1.0, HarmonyOS5.0.1                 |
| 2025 | CVE-2025-58278 | 官方致谢 + 厂商安全公告 | Huawei Consumer | Phones/Tablets, October 2025                 | 图库应用      | 身份认证绕过漏洞  | 成功利用可能影响服务机密性。  | Medium   | HarmonyOS5.0.1                                 |
| 2025 | CVE-2025-58304 | 官方致谢 + 厂商安全公告 | Huawei Consumer | Phones/Tablets, November 2025                | 文件管理模块    | 权限控制漏洞    | 成功利用可能影响服务机密性。  | Medium   | HarmonyOS6.0.0, HarmonyOS5.1.0, HarmonyOS5.0.1 |
| 2025 | CVE-2025-58305 | 官方致谢 + 厂商安全公告 | Huawei Consumer | Phones/Tablets, November 2025                | 图库应用      | 身份认证绕过漏洞  | 成功利用可能影响服务机密性。  | Medium   | HarmonyOS5.0.1                                 |
| 2025 | CVE-2025-58312 | 官方致谢 + 厂商安全公告 | Huawei Consumer | Phones/Tablets, November 2025                | 应用锁模块     | 权限控制漏洞    | 成功利用可能影响可用性。    | Medium   | HarmonyOS6.0.0, HarmonyOS5.1.0, HarmonyOS5.0.1 |
| 2025 | CVE-2025-64311 | 官方致谢 + 厂商安全公告 | Huawei Consumer | Phones/Tablets, November 2025                | 备忘录模块     | 权限控制漏洞    | 成功利用可能影响服务机密性。  | Medium   | HarmonyOS6.0.0, HarmonyOS5.1.0, HarmonyOS5.0.1 |
| 2025 | CVE-2025-64312 | 官方致谢 + 厂商安全公告 | Huawei Consumer | Phones/Tablets, November 2025                | 文件管理模块    | 权限控制漏洞    | 成功利用可能影响服务机密性。  | Medium   | HarmonyOS6.0.0, HarmonyOS5.1.0, HarmonyOS5.0.1 |
| 2025 | CVE-2025-66330 | 官方致谢 + 厂商安全公告 | Huawei Consumer | Phones/Tablets, December 2025                | 文件管理应用    | 应用锁验证绕过漏洞 | 成功利用可能影响服务机密性。  | Medium   | HarmonyOS6.0.0, HarmonyOS5.1.0, HarmonyOS5.0.1 |
| 2026 | CVE-2025-68965 | 官方致谢 + 厂商安全公告 | Huawei Consumer | Phones/Tablets, January 2026                 | 备忘录模块     | 权限控制漏洞    | 成功利用可能影响服务机密性。  | Medium   | HarmonyOS6.0.0, HarmonyOS5.1.0                 |
| 2026 | CVE-2025-68966 | 官方致谢 + 厂商安全公告 | Huawei Consumer | Phones/Tablets, January 2026                 | 备忘录模块     | 权限控制漏洞    | 成功利用可能影响服务机密性。  | Medium   | HarmonyOS6.0.0, HarmonyOS5.1.0                 |
| 2026 | CVE-2026-24916 | 官方致谢 + 厂商安全公告 | Huawei Consumer | Phones/Tablets, February 2026                | 窗口模块      | 身份认证绕过漏洞  | 成功利用可能影响服务机密性。  | Medium   | HarmonyOS6.0.0                                 |
| 2026 | CVE-2026-28540 | 官方致谢 + 厂商安全公告 | Huawei Consumer | Phones/Tablets, March 2026                   | 蓝牙        | 越界字符读取漏洞  | 成功利用可能影响服务机密性。  | Medium   | HarmonyOS6.0.0, HarmonyOS5.1.0                 |
| 2026 | CVE-2026-34863 | 官方致谢 + 厂商安全公告 | Huawei Consumer | Phones/Tablets, April 2026                   | 文件系统      | 越界写入漏洞    | 成功利用可能影响可用性。    | Medium   | HarmonyOS6.0.0, HarmonyOS5.1.0                 |
| 2026 | CVE-2026-34864 | 官方致谢 + 厂商安全公告 | Huawei Consumer | Phones/Tablets and Smart Watches, April 2026 | 应用读取模块    | 边界限制不足漏洞  | 成功利用可能影响可用性。    | Medium   | HarmonyOS6.0.0                                 |
| 2026 | CVE-2026-34865 | 官方致谢 + 厂商安全公告 | Huawei Consumer | Smart Watches, April 2026                    | WEB 模块    | 越界写入漏洞    | 成功利用将影响可用性和机密性。 | Medium   | HarmonyOS6.0.0                                 |
| 2026 | CVE-2026-34866 | 官方致谢 + 厂商安全公告 | Huawei Consumer | Smart Watches, April 2026                    | WEB 模块    | 越界写入漏洞    | 成功利用将影响可用性和机密性。 | Medium   | HarmonyOS6.0.0                                 |
| 2026 | CVE-2026-34867 | 官方致谢 + 厂商安全公告 | Huawei Consumer | Phones/Tablets, April 2026                   | 多模输入系统    | 双重释放漏洞    | 成功利用可能影响可用性。    | Medium   | HarmonyOS6.0.0, HarmonyOS5.1.0                 |
| 2026 | CVE-2026-41962 | 官方致谢 + 厂商安全公告 | Huawei Consumer | Phones/Tablets, May 2026                     | 应用管理与控制模块 | 权限控制漏洞    | 成功利用可能影响服务机密性。  | Medium   | HarmonyOS6.1.0, HarmonyOS6.0.0                 |
| 2026 | CVE-2026-41980 | 官方致谢 + 厂商安全公告 | Huawei Consumer | Phones/Tablets, June 2026                    | 文件预览模块    | 权限控制漏洞    | 成功利用可能影响服务机密性。  | Medium   | HarmonyOS6.1.0, HarmonyOS6.0.0                 |

### CVSS 评分记录

本节记录公开漏洞数据库中显示的 CVSS 信息。该信息属于第三方漏洞元数据，不等同于华为安全公告中的厂商评级。

| CVE            |     华为评级 |                  NVD CVSS v3.1 |                  CNA CVSS | 备注                                               |
| -------------- | -------: | -----------------------------: | ------------------------: | ------------------------------------------------ |
| CVE-2025-54654 |   Medium |                     5.5 MEDIUM |                6.2 MEDIUM | NVD 与 CNA 评分不同                                   |
| CVE-2025-58277 |   Medium |                     5.5 MEDIUM |                4.0 MEDIUM | NVD 与 CNA 评分不同                                   |
| CVE-2025-58278 |   Medium |                     5.5 MEDIUM |                6.2 MEDIUM | NVD 与 CNA 评分不同                                   |
| CVE-2025-58304 |   Medium |                     5.5 MEDIUM |                4.9 MEDIUM | NVD 与 CNA 评分不同                                   |
| CVE-2025-58305 |   Medium |                     5.5 MEDIUM |                6.2 MEDIUM | NVD 与 CNA 评分不同                                   |
| CVE-2025-58312 |   Medium |                     5.5 MEDIUM |                5.1 MEDIUM | NVD 与 CNA 评分不同                                   |
| CVE-2025-64311 |   Medium |                     5.5 MEDIUM |                5.1 MEDIUM | NVD 与 CNA 评分不同                                   |
| CVE-2025-64312 |   Medium |                       7.5 HIGH |                4.9 MEDIUM | 华为公告评级为 Medium；NVD v3.1 为 HIGH                   |
| CVE-2025-66330 |   Medium |                     5.5 MEDIUM |                4.9 MEDIUM | NVD 与 CNA 评分不同                                   |
| CVE-2025-68965 |   Medium |                     5.5 MEDIUM |                4.7 MEDIUM | NVD 与 CNA 评分不同                                   |
| CVE-2025-68966 |   Medium |                     5.5 MEDIUM |                4.7 MEDIUM | NVD 与 CNA 评分不同                                   |
| CVE-2026-24916 |   Medium |                     5.5 MEDIUM |                5.9 MEDIUM | NVD 与 CNA 评分不同                                   |
| CVE-2026-28540 |   Medium |                        3.3 LOW |                4.0 MEDIUM | 华为公告评级为 Medium；NVD v3.1 为 LOW                    |
| CVE-2026-34863 |   Medium |                     5.5 MEDIUM |                6.7 MEDIUM | NVD 与 CNA 评分不同                                   |
| CVE-2026-34864 |   Medium |                     5.5 MEDIUM |                6.8 MEDIUM | NVD 与 CNA 评分不同                                   |
| CVE-2026-34865 |   Medium |                   9.1 CRITICAL | 10.0 CRITICAL (CVSS v4.0) | 华为公告评级为 Medium；NVD/CNA 评分为 CRITICAL              |
| CVE-2026-34866 |   Medium |                            N/A |                5.1 MEDIUM | NVD v3.1 未给出；CNA v3.1 给出评分                       |
| CVE-2026-34867 |   Medium |                            N/A |                5.6 MEDIUM | NVD v3.1 未给出；CNA v3.1 给出评分                       |
| CVE-2026-41962 |   Medium |                            N/A |                   3.6 LOW | NVD v3.1 未给出；CNA v3.1 给出评分                       |
| CVE-2026-41980 |   Medium | 5.5 Moderate (GitHub Advisory) |                       N/A | NVD 页面本次未稳定打开；GitHub Advisory 显示 CVSS v3.1 为 5.5 |

### Apple 额外致谢

| 厂商    | 组织层级                 | 官方来源级别     | 产品                   | 段落                              | CVE | 致谢内容摘要                                                |
| ----- | -------------------- | ---------- | -------------------- | ------------------------------- | --- | ----------------------------------------------------- |
| Apple | Apple Support 安全内容页面 | 非 CVE 官方致谢 | iOS 26 and iPadOS 26 | Additional recognition / Camera | 未指定 | Apple 在 Camera 相关 Additional recognition 中列出一条协助致谢记录。 |

### 说明

* 华为致谢归属来自华为消费者业务安全致谢页面。
* 华为漏洞描述、影响、评级和受影响版本来自华为消费者业务安全公告。
* CVE-2026-34864 同时出现在华为手机/平板安全公告和智能手表安全公告中。
* CVE-2026-34865 存在明显评级差异：华为智能手表安全公告中的厂商评级为 Medium，而 NVD CVSS v3.1 为 9.1 CRITICAL，CNA CVSS v4.0 为 10.0 CRITICAL。
* Apple Additional Recognition 未给出对应 CVE 编号。

### 来源

* Huawei Consumer Security Acknowledgement: https://consumer.huawei.com/cn/support/acknowledgment/
* Huawei Phones/Tablets Security Bulletin, October 2025: https://consumer.huawei.com/en/support/bulletin/2025/10/
* Huawei Phones/Tablets Security Bulletin, November 2025: https://consumer.huawei.com/en/support/bulletin/2025/11/
* Huawei Phones/Tablets Security Bulletin, December 2025: https://consumer.huawei.com/en/support/bulletin/2025/12/
* Huawei Phones/Tablets Security Bulletin, January 2026: https://consumer.huawei.com/en/support/bulletin/2026/1/
* Huawei Phones/Tablets Security Bulletin, February 2026: https://consumer.huawei.com/en/support/bulletin/2026/2/
* Huawei Phones/Tablets Security Bulletin, March 2026: https://consumer.huawei.com/en/support/bulletin/2026/3/
* Huawei Phones/Tablets Security Bulletin, April 2026: https://consumer.huawei.com/en/support/bulletin/2026/4/
* Huawei Phones/Tablets Security Bulletin, May 2026: https://consumer.huawei.com/en/support/bulletin/2026/5/
* Huawei Phones/Tablets Security Bulletin, June 2026: https://consumer.huawei.com/en/support/bulletin/2026/6/
* Huawei Smart Watches Security Bulletin, April 2026: https://consumer.huawei.com/en/support/bulletinwearables/2026/4/
* NVD vulnerability details: https://nvd.nist.gov/vuln/
* GitHub Advisory Database, CVE-2026-41980: https://github.com/advisories/GHSA-2pp9-mf4r-4wpf
* Apple iOS 26 and iPadOS 26 security content: https://support.apple.com/en-us/125108

---

## English Version

This page tracks public security acknowledgement records and keeps acknowledgement attribution, vendor bulletin data, and third-party vulnerability metadata separate.

### Scope

* The Huawei Consumer security acknowledgement page lists 20 related CVEs.
* Apple lists 1 Additional Recognition entry. The Apple entry is not mapped to a specific CVE.
* The main table uses vendor acknowledgement pages and vendor security bulletins as primary sources.
* CVSS, CWE, attack vector, and similar third-party vulnerability metadata are listed separately and are not mixed with vendor bulletin severity.

### Source levels

| Level                              | Meaning                                                                                                        | Use on this page                                            |
| ---------------------------------- | -------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------- |
| Official acknowledgement           | The vendor publicly lists the record on an acknowledgement or recognition page.                                | Used for attribution.                                       |
| Vendor security bulletin           | The vendor publishes CVE description, impact, severity, affected versions, or product scope.                   | Used for vulnerability details.                             |
| Third-party vulnerability metadata | NVD, GitHub Advisory, or other CVE databases provide CVSS, CWE, vectors, publication dates, or modified dates. | Kept separate and does not override vendor bulletin fields. |
| Non-CVE recognition                | The vendor provides public recognition but does not map it to a specific CVE.                                  | Used for the Apple Additional Recognition record.           |

### Organization levels

| Vendor | Organization level                  | Official source level                                                        | Product or section level                                            |
| ------ | ----------------------------------- | ---------------------------------------------------------------------------- | ------------------------------------------------------------------- |
| Huawei | Huawei Consumer                     | Huawei Consumer Security Acknowledgement; Huawei Consumer Security Bulletins | Phones/Tablets security bulletins; Smart Watches security bulletins |
| Apple  | Apple Support security content page | Apple security content page                                                  | iOS 26 and iPadOS 26; Additional recognition / Camera               |

### Huawei CVE records

| Acknowledgement year | CVE            | Official source level                               | Organization level | Bulletin                                     | Component                         | Vulnerability description                    | Impact                                                                | Huawei severity                  | Affected versions                              |
| -------------------- | -------------- | --------------------------------------------------- | ------------------ | -------------------------------------------- | --------------------------------- | -------------------------------------------- | --------------------------------------------------------------------- | -------------------------------- | ---------------------------------------------- |
| 2025                 | CVE-2025-54654 | Official acknowledgement + Vendor security bulletin | Huawei Consumer    | Phones/Tablets, October 2025                 | Gallery module                    | Permission control vulnerability             | Successful exploitation may affect service confidentiality.           | Medium                           | HarmonyOS5.1.0, HarmonyOS5.0.1                 |
| 2025                 | CVE-2025-58277 | Official acknowledgement + Vendor security bulletin | Huawei Consumer    | Phones/Tablets, October 2025                 | Camera app                        | Permission verification bypass vulnerability | Successful exploitation may affect service confidentiality.           | Medium                           | HarmonyOS5.1.0, HarmonyOS5.0.1                 |
| 2025                 | CVE-2025-58278 | Official acknowledgement + Vendor security bulletin | Huawei Consumer    | Phones/Tablets, October 2025                 | Gallery app                       | Identity authentication bypass vulnerability | Successful exploitation may affect service confidentiality.           | Medium                           | HarmonyOS5.0.1                                 |
| 2025                 | CVE-2025-58304 | Official acknowledgement + Vendor security bulletin | Huawei Consumer    | Phones/Tablets, November 2025                | File management module            | Permission control vulnerability             | Successful exploitation may affect service confidentiality.           | Medium                           | HarmonyOS6.0.0, HarmonyOS5.1.0, HarmonyOS5.0.1 |
| 2025                 | CVE-2025-58305 | Official acknowledgement + Vendor security bulletin | Huawei Consumer    | Phones/Tablets, November 2025                | Gallery app                       | Identity authentication bypass vulnerability | Successful exploitation may affect service confidentiality.           | Medium                           | HarmonyOS5.0.1                                 |
| 2025                 | CVE-2025-58312 | Official acknowledgement + Vendor security bulletin | Huawei Consumer    | Phones/Tablets, November 2025                | App Lock module                   | Permission control vulnerability             | Successful exploitation may affect availability.                      | Medium                           | HarmonyOS6.0.0, HarmonyOS5.1.0, HarmonyOS5.0.1 |
| 2025                 | CVE-2025-64311 | Official acknowledgement + Vendor security bulletin | Huawei Consumer    | Phones/Tablets, November 2025                | Notepad module                    | Permission control vulnerability             | Successful exploitation may affect service confidentiality.           | Medium                           | HarmonyOS6.0.0, HarmonyOS5.1.0, HarmonyOS5.0.1 |
| 2025                 | CVE-2025-64312 | Official acknowledgement + Vendor security bulletin | Huawei Consumer    | Phones/Tablets, November 2025                | File management module            | Permission control vulnerability             | Successful exploitation may affect service confidentiality.           | Medium                           | HarmonyOS6.0.0, HarmonyOS5.1.0, HarmonyOS5.0.1 |
| 2025                 | CVE-2025-66330 | Official acknowledgement + Vendor security bulletin | Huawei Consumer    | Phones/Tablets, December 2025                | File management app               | App lock verification bypass vulnerability   | Successful exploitation may affect service confidentiality.           | Medium                           | HarmonyOS6.0.0, HarmonyOS5.1.0, HarmonyOS5.0.1 |
| 2026                 | CVE-2025-68965 | Official acknowledgement + Vendor security bulletin | Huawei Consumer    | Phones/Tablets, January 2026                 | Notepad module                    | Permission control vulnerability             | Successful exploitation may affect service confidentiality.           | Medium                           | HarmonyOS6.0.0, HarmonyOS5.1.0                 |
| 2026                 | CVE-2025-68966 | Official acknowledgement + Vendor security bulletin | Huawei Consumer    | Phones/Tablets, January 2026                 | Notepad module                    | Permission control vulnerability             | Successful exploitation may affect service confidentiality.           | Medium                           | HarmonyOS6.0.0, HarmonyOS5.1.0                 |
| 2026                 | CVE-2026-24916 | Official acknowledgement + Vendor security bulletin | Huawei Consumer    | Phones/Tablets, February 2026                | Window module                     | Identity authentication bypass vulnerability | Successful exploitation may affect service confidentiality.           | Medium                           | HarmonyOS6.0.0                                 |
| 2026                 | CVE-2026-28540 | Official acknowledgement + Vendor security bulletin | Huawei Consumer    | Phones/Tablets, March 2026                   | Bluetooth                         | Out-of-bounds character read vulnerability   | Successful exploitation may affect service confidentiality.           | Medium                           | HarmonyOS6.0.0, HarmonyOS5.1.0                 |
| 2026                 | CVE-2026-34863 | Official acknowledgement + Vendor security bulletin | Huawei Consumer    | Phones/Tablets, April 2026                   | File system                       | Out-of-bounds write vulnerability            | Successful exploitation may affect availability.                      | Medium                           | HarmonyOS6.0.0, HarmonyOS5.1.0                 |
| 2026                 | CVE-2026-34864 | Official acknowledgement + Vendor security bulletin | Huawei Consumer    | Phones/Tablets and Smart Watches, April 2026 | Application read module           | Improper boundary restriction vulnerability  | Successful exploitation may affect availability.                      | Medium                           | HarmonyOS6.0.0                                 |
| 2026                 | CVE-2026-34865 | Official acknowledgement + Vendor security bulletin | Huawei Consumer    | Smart Watches, April 2026                    | WEB module                        | Out-of-bounds write vulnerability            | Successful exploitation will affect availability and confidentiality. | Medium                           | HarmonyOS6.0.0                                 |
| 2026                 | CVE-2026-34866 | Official acknowledgement + Vendor security bulletin | Huawei Consumer    | Smart Watches, April 2026                    | WEB module                        | Out-of-bounds write vulnerability            | Successful exploitation will affect availability and confidentiality. | Medium                           | HarmonyOS6.0.0                                 |
| 2026                 | CVE-2026-34867 | Official acknowledgement + Vendor security bulletin | Huawei Consumer    | Phones/Tablets, April 2026                   | Multi-mode input system           | Double free vulnerability                    | Successful exploitation may affect availability.                      | Medium                           | HarmonyOS6.0.0, HarmonyOS5.1.0                 |
| 2026                 | CVE-2026-41962 | Official acknowledgement + Vendor security bulletin | Huawei Consumer    | Phones/Tablets, May 2026                     | App management and control module | Permission control vulnerability             | Successful exploitation may affect service confidentiality.           | Medium                           | HarmonyOS6.1.0, HarmonyOS6.0.0                 |
| 2026                 | CVE-2026-41980 | Official acknowledgement + Vendor security bulletin | Huawei Consumer    | Phones/Tablets, June 2026                    | File preview module               | Permission control vulnerability             | Successful exploitation may affect service confidentiality.           | Medium                           | HarmonyOS6.1.0, HarmonyOS6.0.0                 |

### CVSS rating records

This section records CVSS information shown in public vulnerability databases. CVSS data is third-party vulnerability metadata and is not the same field as Huawei's vendor severity.

| CVE            |         Huawei severity |                  NVD CVSS v3.1 |                  CNA CVSS | Notes                                                                                |
| -------------- | ----------------------: | -----------------------------: | ------------------------: | ------------------------------------------------------------------------------------ |
| CVE-2025-54654 |                  Medium |                     5.5 MEDIUM |                6.2 MEDIUM | NVD and CNA scores differ                                                            |
| CVE-2025-58277 |                  Medium |                     5.5 MEDIUM |                4.0 MEDIUM | NVD and CNA scores differ                                                            |
| CVE-2025-58278 |                  Medium |                     5.5 MEDIUM |                6.2 MEDIUM | NVD and CNA scores differ                                                            |
| CVE-2025-58304 |                  Medium |                     5.5 MEDIUM |                4.9 MEDIUM | NVD and CNA scores differ                                                            |
| CVE-2025-58305 |                  Medium |                     5.5 MEDIUM |                6.2 MEDIUM | NVD and CNA scores differ                                                            |
| CVE-2025-58312 |                  Medium |                     5.5 MEDIUM |                5.1 MEDIUM | NVD and CNA scores differ                                                            |
| CVE-2025-64311 |                  Medium |                     5.5 MEDIUM |                5.1 MEDIUM | NVD and CNA scores differ                                                            |
| CVE-2025-64312 |                  Medium |                       7.5 HIGH |                4.9 MEDIUM | Huawei bulletin severity is Medium; NVD v3.1 is HIGH                                 |
| CVE-2025-66330 |                  Medium |                     5.5 MEDIUM |                4.9 MEDIUM | NVD and CNA scores differ                                                            |
| CVE-2025-68965 |                  Medium |                     5.5 MEDIUM |                4.7 MEDIUM | NVD and CNA scores differ                                                            |
| CVE-2025-68966 |                  Medium |                     5.5 MEDIUM |                4.7 MEDIUM | NVD and CNA scores differ                                                            |
| CVE-2026-24916 |                  Medium |                     5.5 MEDIUM |                5.9 MEDIUM | NVD and CNA scores differ                                                            |
| CVE-2026-28540 |                  Medium |                        3.3 LOW |                4.0 MEDIUM | Huawei bulletin severity is Medium; NVD v3.1 is LOW                                  |
| CVE-2026-34863 |                  Medium |                     5.5 MEDIUM |                6.7 MEDIUM | NVD and CNA scores differ                                                            |
| CVE-2026-34864 |                  Medium |                     5.5 MEDIUM |                6.8 MEDIUM | NVD and CNA scores differ                                                            |
| CVE-2026-34865 |                  Medium |                   9.1 CRITICAL | 10.0 CRITICAL (CVSS v4.0) | Huawei bulletin severity is Medium; NVD/CNA scores are CRITICAL                      |
| CVE-2026-34866 |                  Medium |                            N/A |                5.1 MEDIUM | NVD v3.1 score not provided; CNA v3.1 score is shown                                 |
| CVE-2026-34867 |                  Medium |                            N/A |                5.6 MEDIUM | NVD v3.1 score not provided; CNA v3.1 score is shown                                 |
| CVE-2026-41962 |                  Medium |                            N/A |                   3.6 LOW | NVD v3.1 score not provided; CNA v3.1 score is shown                                 |
| CVE-2026-41980 |                  Medium | 5.5 Moderate (GitHub Advisory) |                       N/A | NVD page was not stable during this check; GitHub Advisory shows CVSS v3.1 score 5.5 |

### Apple Additional Recognition

| Vendor | Organization level                  | Official source level        | Product              | Section                         | CVE           | Acknowledgement summary                                                                        |
| ------ | ----------------------------------- | ---------------------------- | -------------------- | ------------------------------- | ------------- | ---------------------------------------------------------------------------------------------- |
| Apple  | Apple Support security content page | Non-CVE official recognition | iOS 26 and iPadOS 26 | Additional recognition / Camera | Not specified | Apple lists one assistance acknowledgement under Camera in the Additional recognition section. |

### Notes

* Huawei acknowledgement attribution comes from the Huawei Consumer security acknowledgement page.
* Huawei vulnerability descriptions, impacts, severities, and affected versions come from Huawei Consumer security bulletins.
* CVE-2026-34864 appears in both Huawei Phones/Tablets and Smart Watches security bulletins.
* CVE-2026-34865 has a clear severity discrepancy: Huawei's Smart Watches bulletin lists the vendor severity as Medium, while NVD CVSS v3.1 is 9.1 CRITICAL and CNA CVSS v4.0 is 10.0 CRITICAL.
* Apple Additional Recognition does not provide a CVE mapping.

### Sources

* Huawei Consumer Security Acknowledgement: https://consumer.huawei.com/cn/support/acknowledgment/
* Huawei Phones/Tablets Security Bulletin, October 2025: https://consumer.huawei.com/en/support/bulletin/2025/10/
* Huawei Phones/Tablets Security Bulletin, November 2025: https://consumer.huawei.com/en/support/bulletin/2025/11/
* Huawei Phones/Tablets Security Bulletin, December 2025: https://consumer.huawei.com/en/support/bulletin/2025/12/
* Huawei Phones/Tablets Security Bulletin, January 2026: https://consumer.huawei.com/en/support/bulletin/2026/1/
* Huawei Phones/Tablets Security Bulletin, February 2026: https://consumer.huawei.com/en/support/bulletin/2026/2/
* Huawei Phones/Tablets Security Bulletin, March 2026: https://consumer.huawei.com/en/support/bulletin/2026/3/
* Huawei Phones/Tablets Security Bulletin, April 2026: https://consumer.huawei.com/en/support/bulletin/2026/4/
* Huawei Phones/Tablets Security Bulletin, May 2026: https://consumer.huawei.com/en/support/bulletin/2026/5/
* Huawei Phones/Tablets Security Bulletin, June 2026: https://consumer.huawei.com/en/support/bulletin/2026/6/
* Huawei Smart Watches Security Bulletin, April 2026: https://consumer.huawei.com/en/support/bulletinwearables/2026/4/
* NVD vulnerability details: https://nvd.nist.gov/vuln/
* GitHub Advisory Database, CVE-2026-41980: https://github.com/advisories/GHSA-2pp9-mf4r-4wpf
* Apple iOS 26 and iPadOS 26 security content: https://support.apple.com/en-us/125108
