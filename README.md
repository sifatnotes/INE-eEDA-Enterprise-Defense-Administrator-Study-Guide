# INE-eEDA-Enterprise-Defense-Administrator-Study-Guide
Practical INE eEDA study guide covering secure engineering, GRC, IAM, security administration, labs, exam preparation, and voucher information.
# INE eEDA – Enterprise Defense Administrator Study Guide

## Introduction

This repository is an independent study resource for the **INE eEDA (Enterprise Defense Administrator)** certification. It provides exam-focused study notes, official objectives, practical lab ideas, revision points, and a 30-day preparation plan.

The eEDA is a hands-on Blue Team certification focused on implementing and defending properly secured enterprise infrastructure.

## Exam Overview

| Item | Information |
|---|---|
| Vendor | INE Security |
| Certification | Enterprise Defense Administrator |
| Exam code | eEDA |
| Focus | Defensive cybersecurity and security engineering |
| Assessment | Multiple-choice questions + hands-on lab |
| Exam environment | Reproduction of a standard enterprise network |
| Prerequisites | No mandatory prerequisite; basic IT infrastructure knowledge is recommended |
| Duration | 8 hours |
| Passing score | Not publicly specified by INE |
| Credential validity | 3 years |

INE states that candidates need an INE subscription and exam voucher to take the certification. Regular vouchers currently expire 180 days after purchase; the certification itself is valid for three years after award.

## Who Should Take It?

The eEDA is designed for people beginning a defensive cybersecurity or security-engineering career, particularly:

- Systems Administrators
- IT Project Managers
- Information Security Officers
- Security Engineers/Analysts
- DevOps and Software Developers
- Managed Service Providers (MSPs)
- Managed Security Service Providers (MSSPs)

A basic understanding of IT infrastructure, networking, operating systems, and security concepts will make preparation easier.

## Exam Objectives / Domains

### 1. Secure Engineering Fundamentals — 12%

Learn defensive-security terminology and understand long-term planning and the configuration of resilient security controls.

### 2. Governance, Risk and Compliance — 24%

Study GRC principles, regulations and laws, organizational IT risk, impact assessment, structured change management, industry frameworks, and cybersecurity baselines.

### 3. Identity and Access Management — 28%

Understand IAM components, configurations, and security controls. Practice implementing fundamental identity and access-management controls.

### 4. Security Administration — 36%

The largest domain. Focus on securing IT systems, designing secure environments around business requirements, vulnerability identification and mitigation, logging, log aggregation, and alerts.

## Detailed Study Notes

### Secure Engineering

Secure engineering means designing infrastructure with security requirements included from the beginning.

Review:

- Defense-in-depth
- Secure configurations
- Security baselines
- Least privilege
- Resilience
- Attack-surface reduction
- Business requirements

A good security design should protect systems without ignoring availability and operational requirements.

### Governance, Risk and Compliance

Understand the relationship between:

**Asset → Threat → Vulnerability → Risk → Impact → Control**

Risk assessment helps organizations prioritize security work instead of treating every issue as equally important.

Study:

- Risk identification
- Risk impact
- Risk treatment
- Security policies
- Compliance requirements
- Change management
- Security baselines
- Industry frameworks

### Identity and Access Management

Important concepts include:

- Authentication
- Authorization
- Accounting
- Least privilege
- Role-based access control
- User/group management
- Access reviews
- Password and authentication policies
- Privileged accounts

Always distinguish **authentication** (who are you?) from **authorization** (what are you allowed to do?).

### Security Administration

Practice securing servers and network infrastructure through:

- Patch management
- System hardening
- Firewall configuration
- Vulnerability assessment
- Secure services
- Access controls
- Endpoint security
- Centralized logging
- Alert configuration

For logging, understand how individual system logs can be collected, centralized, correlated, and converted into useful alerts.

## Important Concepts

Before the exam, make sure you can explain and practically apply:

- Defense-in-depth
- Security baselines
- Risk and impact
- GRC
- Change management
- IAM
- Authentication vs authorization
- Least privilege
- RBAC
- Network/device hardening
- Server hardening
- Vulnerability management
- Patch management
- Firewalls
- Logging and log aggregation
- Security alerts
- Secure architecture
- Business-security requirements

## Practical Examples / Labs

Use only systems you own or are explicitly authorized to administer.

1. Build a small Windows/Linux lab and create a secure baseline.
2. Configure local users, groups, permissions, and least-privilege access.
3. Apply firewall rules and document the security rationale.
4. Identify outdated packages and create a patch-management workflow.
5. Perform a vulnerability scan against your own lab environment.
6. Centralize logs from multiple systems into a test logging platform.
7. Create alerts for selected security events.
8. Design a secure enterprise network diagram based on business requirements.
9. Create a change request for a security configuration change.
10. Map selected security controls to an appropriate industry framework.

## Study Strategy

Start with the official eEDA learning path and combine theory with hands-on labs.

Recommended approach:

1. Learn each domain's terminology.
2. Read the official objectives.
3. Build or use a controlled lab environment.
4. Practice configuration rather than only reading.
5. Document why each security control is necessary.
6. Review vulnerability and logging scenarios.
7. Practice IAM and secure-configuration tasks.
8. Perform a complete defensive administration exercise.
9. Use legitimate practice questions only.
10. Recheck the current official objectives before the exam.

## 30-Day Study Plan

**Days 1–4:** IT infrastructure, networking, defensive-security fundamentals.

**Days 5–8:** Secure engineering, hardening, defense-in-depth, security baselines.

**Days 9–14:** GRC, risk assessment, impact, compliance, frameworks, and change management.

**Days 15–19:** IAM, authentication, authorization, RBAC, least privilege, privileged access.

**Days 20–25:** Security administration, system hardening, vulnerabilities, patching, firewalls, and secure architecture.

**Days 26–27:** Logging, aggregation, monitoring, alerts, and investigation workflows.

**Day 28:** Complete an end-to-end enterprise-defense lab.

**Day 29:** Review weak objectives and repeat difficult practical tasks.

**Day 30:** Final revision, lab checklist, official requirements, and exam preparation.

## Common Mistakes

- Memorizing security terms without practicing configurations
- Ignoring business requirements when designing security controls
- Confusing authentication with authorization
- Applying excessive privileges
- Treating vulnerability scanning as the same as remediation
- Ignoring centralized logging
- Failing to document configuration changes
- Studying only multiple-choice theory
- Neglecting practical lab work
- Using outdated exam objectives

## Exam-Day Tips

- Read every task carefully before making changes.
- Understand the required business/security outcome first.
- Keep track of configuration changes.
- Avoid unnecessary modifications.
- Verify that security controls actually work after implementation.
- Prioritize tasks according to the exam instructions.
- Leave time to review your work.
- Follow INE's current exam and technical requirements.

## Final Checklist

- [ ] Reviewed all four official domains
- [ ] Understand secure engineering fundamentals
- [ ] Can assess basic security risk and impact
- [ ] Understand GRC and change management
- [ ] Can configure fundamental IAM controls
- [ ] Can harden systems and network devices
- [ ] Understand vulnerability management
- [ ] Can work with logs and alerts
- [ ] Completed hands-on defensive labs
- [ ] Reviewed current official exam information

## Official Resources

- INE eEDA Certification: https://ine.com/security/certifications/eeda-certification
- INE Security: https://ine.com/security
- INE Security Learning: https://learn.ine.com/ine-security
- INE Learning Paths: https://my.ine.com/
- INE Certification Portal: https://my.ine.com/

Always verify current exam requirements, objectives, delivery details, and policies directly with INE before registering.

## Voucher / Discount

**Learn SecByte provides certification voucher options and discounts where available.**

eEDA voucher:

https://learn.secbyte.org/vouchers/eeda-eeda

Check the current voucher availability, pricing, terms, and redemption conditions before purchasing. Voucher availability and pricing may change.

## Disclaimer

This is an **independent/community study guide** and is not an official INE certification document. INE, eEDA, and related trademarks belong to their respective owners.

Candidates should verify current certification information with INE before taking the exam. Voucher pricing and availability may change.

This repository does **not** contain exam dumps, leaked questions, or recalled exam questions. It is intended solely for legitimate education, hands-on learning, and certification preparation.
