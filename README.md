# uzobola-portfolio

Personal AWS cloud security portfolio site — live at [uzobola-portfolio.vercel.app](https://uzobola-portfolio.vercel.app).

## Overview

This portfolio presents my work as a connected seven-layer AWS cloud security program — not a collection of isolated repositories.

The program is organized around:

1. GRC and evidence automation
2. Secure cloud architecture
3. Identity and access governance
4. Detection engineering
5. Incident response readiness
6. Policy as code
7. Security leadership and communication

The goal of this site is to show how cloud security controls, architecture, detection, governance, and business risk connect across a realistic AWS security program.

## Featured Projects

### AWS GRC Engineering Project

Automated compliance framework for AWS control validation, evidence collection, risk scoring, and multi-framework mapping.

- 16 automated controls across 6 domains
- SOC 2, NIST CSF, NIST 800-53, ISO 27001, PCI DSS, and CIS mapping
- Audit-ready JSON/CSV evidence output
- IAM governance, access review, and evidence vault modules

Repository: [aws-grc-engineering-project](https://github.com/uzobola/aws-grc-engineering-project)

### Secure Multi-Account Retail Architecture

AWS reference architecture for secure retail workloads using multi-account isolation, centralized logging, layered ingress controls, private workload placement, and documented threat modeling.

- AWS Organizations account separation
- Retail production and non-production isolation
- Centralized CloudTrail, Config, GuardDuty, Security Hub, and log archive design
- Threat model and preventive/detective/responsive/governance controls

Repository: [secure-multi-account-retail-architecture](https://github.com/uzobola/secure-multi-account-retail-architecture)

### Zero Trust Serverless CDK

Secure serverless Notes API built with AWS CDK, Cognito, API Gateway, Lambda, and DynamoDB using Zero Trust principles.

- Cognito JWT authentication
- JWT `sub` claim binding to prevent BOLA/IDOR
- Route-level least privilege with split Lambda functions
- Threat model, controls matrix, and evidence packages

Repository: [zero-trust-serverless-cdk](https://github.com/uzobola/zero-trust-serverless-cdk)

### IAM Cross-Account Detection Pipeline

Real-time AWS AssumeRole detection pipeline using CloudTrail, EventBridge, Lambda, and SNS.

- MITRE ATT&CK mapping for T1078 and T1550.001
- High/Medium/Low severity scoring
- Trusted automation role allowlist
- SOC 2 and NIST CSF compliance evidence alignment

Repository: [iam-cross-account-detection-pipeline](https://github.com/uzobola/iam-cross-account-detection-pipeline)

## Why This Portfolio Exists

This portfolio demonstrates how I think about cloud security from multiple layers:

- designing secure AWS architectures
- automating control validation and evidence collection
- governing IAM and cross-account access
- detecting suspicious activity from AWS telemetry
- mapping technical controls to business risk and compliance outcomes
- communicating security architecture clearly through diagrams, documentation, and working projects

## Built With

- HTML
- CSS
- GitHub
- Vercel

## Author

**Uzo Bolarinwa**  
AWS Security | GRC Engineering | Cloud Security Architecture | Compliance Automation
