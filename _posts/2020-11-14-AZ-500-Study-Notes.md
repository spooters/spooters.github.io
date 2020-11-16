---
layout: post
title:  AZ-500 Study Notes 
categories: [Azure]
---

My Study Notes for the AZ-500 Microsoft Azure Security Technologies exam.

## Introduction

Today's security posture is to assume breach and use the Zero Trust model.

- No longer focus on perimeter defense
- Modern organisations have to support access to data and services evenly from both inside and outside the corporate firewall
- Focus on defense-in-depth approach 
- Secure Identity management

## Zero Trust model

The Zero Trust model relies on verifiable user and device trust claims to grant access to organizational resources.  No longer is trust assumed based on the location inside an organizations permimeter. 

### Defense in depth

Defense in depth is a layered approach to security.  The common principles that help define a security posture are **confidentiality**, **integrity**, and **availability**.  

These are known collectiviely as CIA.  Each of these princciples can be applied to the 7 layers of security.

1. Data
1. Application
1. Compute
1. Network
1. Perimeter
1. Identity and access
1. Physical security

### Infrastructure Protection

- Role-based access control (RBAC)
- Roles and management groups
- Privileged Identity Management
- Service principles 
- Managed identityes for Azure Resource