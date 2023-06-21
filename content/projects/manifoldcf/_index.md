---
title: Apache ManifoldCF security advisories
description: Security information for Apache ManifoldCF
layout: single
---

# Reporting

Do you want disclose a potential security issue for Apache ManifoldCF? Send your report to the  [Apache Security Team](mailto:security@apache.org).

# Advisories

## LDAP Injection Vulnerability - ActiveDirectory Authorities ## { #CVE-2022-45910 }

[CVE-2022-45910](./CVE-2022-45910.cve.json)

### Affected

* Apache ManifoldCF versions  including 2.23


### Description

Improper neutralization of special elements used in an LDAP query ('LDAP Injection') vulnerability in ActiveDirectory and Sharepoint ActiveDirectory authority connectors of Apache ManifoldCF allows an attacker to manipulate the LDAP search queries (DoS, additional queries, filter manipulation) during user lookup, if the username or the domain string are passed to the UserACLs servlet without validation.<br><br>This issue affects Apache ManifoldCF version 2.23 and prior versions.