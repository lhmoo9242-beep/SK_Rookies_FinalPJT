# SK Shieldus Rookies Final Project - Security Assessment & Remediation

This repository documents the comprehensive web application and infrastructure vulnerability assessment project completed during the SK Shieldus Rookies cybersecurity program.

## Project Overview
The objective of this project was to design, identify, validate, and remediate critical security vulnerabilities within multi-tier web application and system environments in a controlled lab setting.

## Scope of Assessment & Target Vulnerabilities
The assessment covered diagnostic verification and mitigation for common enterprise attack vectors, including:
- **Server-Side Request Forgery (SSRF)**: Validation of URL parsing logic and internal network access restrictions.
- **Injection Vulnerabilities**: SQL Injection and OS Command Injection testing and parameterized query remediation.
- **Broken Object Level Authorization (BOLA/IDOR)**: Identification of access control flaws and attribute validation bypasses.
- **Cross-Site Scripting (XSS)**: Reflected/Stored XSS vector reproduction and contextual output encoding.
- **Infrastructure & Configuration Audits**: Permission hardening and privilege escalation verification.

## Methodology & Workflow
1. **Target Identification**: Automated and manual surface mapping across web applications and server endpoints.
2. **Controlled Verification**: Designing minimal, non-destructive validation procedures and PoCs to confirm exploitability without causing service disruption.
3. **Remediation Engineering**: Implementing source code patches, secure configurations, and defensive controls.
4. **Validation Reporting**: Documenting technical findings, reproduction steps, and architectural hardening guidelines.

## Disclaimer
All testing and vulnerability research documented here were conducted strictly within isolated lab environments and authorized target systems for educational and defensive security purposes.
