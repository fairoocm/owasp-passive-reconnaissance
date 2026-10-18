# Passive Reconnaissance — OWASP

## Project Overview

This project documents a cybersecurity learning exercise focused on passive reconnaissance and basic web technology identification using publicly observable information.

The objective was to understand how DNS records, domain registration information, HTTP response headers, and technology fingerprints can support an initial security assessment.

## Objectives

- Examine publicly available domain and DNS information.
- Identify web technology indicators.
- Review HTTP response headers and security-related configurations.
- Organize evidence into a structured technical report.
- Distinguish observations from confirmed security vulnerabilities.

## Tools Used

- Kali Linux
- WHOIS
- `dig`
- WhatWeb
- `curl`
- Browser-based public information sources

## Methodology

1. Collected publicly available domain registration information.
2. Queried relevant DNS records using `dig`.
3. Reviewed visible web technology indicators using WhatWeb.
4. Examined HTTP response headers using `curl`.
5. Organized observations and supporting evidence in a report.
6. Documented limitations and avoided treating ordinary observations as vulnerabilities without validation.

## Key Learning Outcomes

- Improved familiarity with DNS record types and domain infrastructure.
- Practised collecting HTTP response metadata.
- Learned to document technical observations with appropriate context.
- Improved evidence organization and report-writing skills.

## Report and Evidence

The full reconnaissance report, including methodology, observations, limitations, and supporting evidence, is available below.

[View the OWASP Passive Reconnaissance Report (PDF)](./OWASP_Passive_Reconnaissance_Report_With_Evidence.pdf)

## Scope and Ethics

This was a learning exercise using publicly observable information. It was not an authorized penetration test, and this project does not claim that OWASP has any verified vulnerabilities.

Active security testing should only be conducted with explicit authorization and a clearly defined scope.

## Project Status

**Report prepared — publication review pending.**

This repository is part of my ongoing cybersecurity learning portfolio.

