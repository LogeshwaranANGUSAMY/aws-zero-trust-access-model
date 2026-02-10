# AWS Zero Trust Access Control Model

## Overview
This project demonstrates the design and implementation of a Zero Trust access control model in a cloud-native environment using AWS services.

The architecture enforces identity-centric security, least-privilege access, temporary credentials, and continuous monitoring in alignment with NIST SP 800-207.

## Technologies Used
- AWS IAM
- AWS STS
- Amazon S3
- AWS CloudTrail
- Zero Trust Architecture

## Architecture
![Zero Trust Architecture](architecture/zero-trust-architecture.png)

## Key Features
- Role-based access control (RBAC)
- Temporary session-based authorization
- No standing privileges
- Explicit resource access policies
- Continuous logging and auditability

## Testing & Validation
- Unauthorized access attempts blocked
- Privilege escalation prevented
- All actions logged via CloudTrail

## Security Notice
All policies and configurations are sanitized. No real credentials or account identifiers are included.

## Author
Logeshwaran Angusamy  
MSc Cyber Security
# aws-zero-trust-access-model
Design and implementation of a Zero Trust access control model using AWS IAM, STS, S3, and CloudTrail.
