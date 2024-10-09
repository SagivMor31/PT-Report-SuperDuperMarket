# SuperDuperMarket - Penetration Testing Report

## Overview
This repository contains the penetration testing report for SuperDuperMarket. The assessment identified two critical vulnerabilities: Cross-Site Scripting (XSS) and negative value transaction manipulation.

## Key Findings
- **Cross-Site Scripting (XSS)**: Script injection revealing admin authentication token.
- **Negative Value Transactions**: Exploiting the system to make unauthorized credit transactions.

## Remediation
- Implement input validation and output encoding.
- Strengthen server-side checks for financial transactions.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
