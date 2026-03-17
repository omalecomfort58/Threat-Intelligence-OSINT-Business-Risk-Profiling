# Threat-Intelligence-OSINT-Business-Risk-Profiling
**Project Overview**

This project focuses on using Open Source Intelligence (OSINT) techniques to assess the external attack surface of an organization (GitLab). The objective was to identify potential risks related to phishing, infrastructure exposure, and brand impersonation.

**Objectives**

Identify publicly exposed assets

Analyze email security posture

Detect potential phishing risks

Assess infrastructure exposure

Provide actionable security recommendations

**Tools & Technologies**

Shodan (Infrastructure discovery)

theHarvester (Email & subdomain enumeration)

VirusTotal (Reputation analysis)

AbuseIPDB (IP reputation)

MXToolbox (Email security analysis)

WHOIS (Domain metadata)

**Methodology**

Data Collection (OSINT sources)

Data Validation and Correlation

Threat Analysis (attacker perspective)

Risk Assessment

Reporting and Recommendations

**Key Findings**

Weak email authentication (DMARC/DKIM failures)

27 publicly exposed IP addresses identified

Multiple subdomains increasing attack surface

Malicious sender IP linked to phishing activity

Potential for brand impersonation attacks

**Threat Scenarios**

Phishing attacks using spoofed emails

Fake login portals for credential harvesting

Infrastructure reconnaissance by attackers

Social engineering using public data

**Risk Assessment**

High risk: Email spoofing and phishing

Medium risk: Infrastructure exposure & subdomains

Low risk: No breach exposure detected

**Recommendations**

Enforce strong DMARC, DKIM, SPF policies

Monitor and block malicious IPs

Detect and remove phishing domains

Reduce exposed infrastructure footprint

Conduct continuous OSINT monitoring
