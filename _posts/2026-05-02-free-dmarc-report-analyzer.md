---
layout: post
title:  "Lemur Security - DMARC report analyzer webapp launch"
fancy_title: true
description: "Tool drop! Secure and free DMARC report analyzer."
author: lemursec
date:   2026-05-02 09:00:00 -0400
categories: updates
tags: [launch, announcement, tools, threat-intel]
pin: true
math: true
mermaid: true
---

**Does your team struggle to interpret raw DMARC telemetry?**

Administrators managing email infrastructure often find daily aggregate reports unusable. DMARC provides the primary defense for protecting your domain against spoofing and phishing, the reports are delivered in raw XML format—often compressed in `.zip` or `.gz` files.

Manual parsing wastes technical resources and delays incident response.

LemurSec released the **DMARC Report Threat Analyzer** to convert XML data into clear intelligence without cost.

### Technical Capabilities

The analyzer automates the extraction and analysis of aggregate reports.

The interface accepts single files or bulk uploads. The engine processes one-to-many .xml, .gz, and .zip file uploads. The tool also ingests .mbox exports directly and parses the inline fiile attachment data automatically.

The dashboard converts raw XML into deduplicated tables.

Users identify spoofing IPs and verify SPF or DKIM alignment immediately. The tool enriches failed checks with direct links to AbuseIPDB, Shodan, and VirusTotal.


### Data Privacy and Ephemeral Processing

As security professionals, we know that your email routing data is highly sensitive. You shouldn't have to surrender your company's telemetry to a third-party marketing database just to read your own reports.

Email routing data constitutes sensitive corporate telemetry. Reading these reports shouldn't require surrendering data to third-party databases.

We prioritize data sovereignty. The analyzer operates entirely within ephemeral memory. The system maintains no databases, file uploads, or persistent generated report records. The server wipes all uploaded archives the moment the system generates the HTML report.

## Access the Analyzer

Convert your DMARC reports into usable intelligence. The tool requires no registration and carries no cost.

<div style="text-align: center; margin-top: 30px; margin-bottom: 30px;">
  <a class="btn-primary" target="_blank" href="https://dmarc-report-analyzer.lemursec.com/">Launch DMARC Report Threat Analyzer</a>
</div>
