---
layout: "page"
title: "Assumed Breach Network Security Assessment"
permalink: "/services/assumed-breach-network-security-assessment/"
description: "Controlled lateral-movement exercise to validate segmentation, privilege paths, and EDR/SIEM detection—without phishing."
category: "services"
tags: ["assumed-breach", "siem", "soc"]
icon: fas fa-sitemap
order: 5
cta_text: "Book a 20‑min Fit Call"
cta_link: "{{ site.calendly_url }}"
show_in_nav: true
---


## Measure Adversarial Impacts

### Controlled lateral-movement exercise to validate segmentation, privilege paths, and XDR/NDR/SIEM detection.

Starting from a foothold you define (e.g., rogue network device, VPN/domain user creds or a test workstation), we emulate a post-compromise attacker to quantify impact. We map and validate privilege-escalation paths, segmentation gaps, and control effectiveness across AD/Windows, identity, and management planes.

Techniques may include command and control (C2) establishment, persistence mechanisms, credential harvesting/safe replay, local privilege escalation, service account abuse, fileshare enumeration, Kerberoasting/AS-REP exposure checks, AD CS misconfigurations, account delegation misconfigurations, simulated data exfiltration and insecure protocol use, all executed under strict Rules of Engagement, to protect production systems and minimize service disruptions. 

In parallel, we assess XDR/NDR/SIEM visibility and response:<br/>what tripped, why, how fast, and *was anything missed?* 

Deliverables include successful attack-path diagrams and prioritized remediation guidance for Executives and Security Teams.

## Who it’s for
Teams with cloud-first Azure, hybrid AD or on-premesis AD environments wanting evidence of real-world lateral movement risk and adversary tactics/techniques detection performance.

**Ready to put your SOC/vendors in the thunderdome?**

<a class="btn-cta" href="{{ site.calendly_url }}">Schedule a meeting with a LemurSec remote operator!</a>

| Included activities                                               |
| :---------------------------------------------------------------- |
| Segmentation & tiering validation, C2, simulated data exfil       |
| Controlled lateral-movement evaluation                            |
| XDR/NDR/SIEM visibility and response observations                 |
| Attack-path diagram and prioritized remediation (effort vs. risk) |
| Executive Summary report with a technical appendix                |
| Retest specific TTPs and publish updated report                   |

## How it works

<section class="timeline" aria-label="Assessment process">
  <ol class="timeline-list" role="list">
    <li>
      <span class="dot">1</span>
      <div class="body"><strong>ROE &amp; safety planning</strong></div>
    </li>
    <li>
      <span class="dot">2</span>
      <div class="body"><strong>Access provisioning</strong></div>
    </li>
    <li>
      <span class="dot">3</span>
      <div class="body"><strong>Recon &amp; path analysis</strong></div>
    </li>
    <li>
      <span class="dot">4</span>
      <div class="body"><strong>Controlled exploit chaining</strong></div>
    </li>
    <li>
      <span class="dot">5</span>
      <div class="body"><strong>Detection/response review</strong></div>
    </li>
    <li>
      <span class="dot">6</span>
      <div class="body"><strong>Outbrief</strong></div>
    </li>
    <li>
      <span class="dot">7</span>
      <div class="body"><strong>Retest</strong></div>
    </li>
  </ol>
</section>

<section id="faq" class="faq-section" aria-label="Frequently asked questions">
  <header class="faq-header container">
    <span class="badge">FAQ</span>
    <h2>Answers to common questions</h2>
    <p class="muted">Everything you need to know about our GRC & security assessments, from retests to safety and timelines.</p>
  </header>
  <div class="faq-grid container">
    <details class="faq-card" id="faq-1">
      <summary>
        <h3>Is this a red team or phishing test?</h3>
        <div class="chev" aria-hidden="true"></div>
      </summary>
      <div class="answer">
        <p>No. This is a scoped, remote, post-compromise security evaluation.</p>
      </div>
    </details>
    <details class="faq-card" id="faq-2">
      <summary>
        <h3>Will this impact production systems?</h3>
        <div class="chev" aria-hidden="true"></div>
      </summary>
      <div class="answer">
        <p>We design for safety (throttled, change-controlled, read-only where possible) and schedule off-hours as needed.</p>
      </div>
    </details>
    <details class="faq-card" id="faq-3">
      <summary>
        <h3>Can you test XDR/NDR/SIEM?</h3>
        <div class="chev" aria-hidden="true"></div>
      </summary>
      <div class="answer">
        <p>Yes! Our internal exploit development resources safely simulate a wide range of both high and low skill adversary techniques to evaluate alerting and response without using destructive malware.</p>
      </div>
    </details>
  </div>
  <footer class="faq-cta container">
    <a class="btn-cta" href="{{ site.calendly_url }}">Still have questions? Schedule a meeting with a LemurSec remote operator!</a>
  </footer>
</section>
