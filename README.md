# FT3: Fraud Tools, Tactics, and Techniques Framework

## Overview

Fraud Tools, Tactics, and Techniques (FT3) is Stripe's adaptation of ATT&CK-style security frameworks, specifically designed to enhance our understanding of the tactics, techniques, and procedures (TTPs) used by actors in fraudulent activities. Developed as a resource for combating financial crime and improving organizational fraud prevention, FT3 serves a variety of stakeholders across the Fraud ecosystem.

## Why FT3?

Fraud is an ever-evolving threat that necessitates a structured approach for organizations to adapt and respond effectively. By documenting the common tactics and techniques used by fraudsters, FT3 helps organizations to:

- **Understand the Fraud Landscape:** Gain insights into the tactics and techniques that fraudsters leverage.
- **Identify Security Gaps:** Discover shortcomings in current security measures to enhance defenses.
- **Develop Detection Mechanisms:** Establish precise detection capabilities tailored to counter current fraud tactics.
- **Improve Incident Response:** Enhance processes for responding to fraud incidents efficiently.
- **Foster Collaboration:** Share knowledge and insights within the fraud prevention community to strengthen collective defenses.

## Components of FT3

### 1. **Tactics**
High-level categories representing various phases or goals within the fraud lifecycle. Each tactic delineates specific objectives pursued by fraudsters.

**Example:** 
- **Initial Access:** Gaining unauthorized access to user accounts to execute fraudulent transactions.

### 2. **Techniques**
Methods or modes of operation fraudsters use to achieve their objectives under each tactic. Techniques can vary in complexity and sophistication.

**Example:** 
- **Account Takeover:** Using stolen credentials to gain control over a user's account for malicious purposes, such as transferring funds or making unauthorized purchases.

### 3. **Procedures**
Specific implementations of techniques that detail the exact methods actors use within the context of fraud, often involving unique tools and sequences of actions.

**Example:**
- **Phishing Scheme:** Crafting a fake email that appears legit to trick users into providing their login information.

### 4. **Indicators of Compromise (IOCs)**
Details that suggest fraudulent activity, such as unusual transaction patterns or changes in account behavior.

**Example:**
- **Unusual Purchase Locations:** Transactions occurring in locations that do not match the user's typical behavior, indicating potential fraud.

### 5. **Mitigations**
Proactive actions organizations can adopt to decrease the risk or impact of fraud.

**Example:**
- **Two-Factor Authentication (2FA):** Implementing extra security layers that require a second form of verification to access accounts.

### 6. **Detection**
Mechanisms for identifying potential fraud through analysis of transaction patterns and customer behaviors.

**Example:**
- **Anomaly Detection Algorithms:** Using machine learning models to identify deviations from normal purchasing behavior.

### 7. **Response**
Predefined procedures for organizational response to detected fraud events, aimed at minimizing impact and facilitating recovery.

**Example:**
- **Fraud Investigation Protocol:** Steps for initiating a fraud investigation when suspicious transactions are flagged.

This enhanced context focuses on the specific tactics, techniques, and procedures related to fraud, making it more applicable to your goals.

## Contributing

We welcome contributions to the FT3 framework from the community! Here are some ways you can help:

Please see the [CONTRIBUTING](CONTRIBUTING.md) file for further details.

## Security
Please see the [SECURITY](SECURITY.md) file for further details.

## Code of Conduct
Please see the [CODE_OF_CONDUCT](CODE_OF_CONDUCT.md), file for further details.

## Contact Information

For further inquiries about the FT3 framework, please reach out to intel [at] stripe.com

## Notice
Please see the [LICENSE](LICENSE.md), [CODE_OF_CONDUCT](CODE_OF_CONDUCT.md), [CONTRIBUTING](CONTRIBUTING.md), and [SECURITY](SECURITY.md) files for further details.

Copyright © 2024-2025 Stripe Inc. All rights reserved.
