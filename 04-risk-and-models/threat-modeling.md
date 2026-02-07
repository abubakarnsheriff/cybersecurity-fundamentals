## Threat Modeling

Threat modeling is the process of identifying, analyzing, and prioritizing potential threats to a system.

## Core Questions
- What are we protecting?
- Who might attack?
- How could they succeed?
- What is the impact?

## Why it matters
Security without threat modeling is blind.

## My Insight
Every system is secure until you clearly define its attacker.


## Example: Web Application

### Assets
- User credentials
- Personal data
- Application availability

### Potential Attackers
- External attackers
- Malicious insiders

### Attack Paths
- Credential phishing
- SQL injection
- Weak authentication

### Impact
- Data breaches
- Financial loss
- Reputational damage

## Practical Example

**Scenario:** Public-facing login portal for a financial application.

- Spoofing: Credential stuffing attacks using leaked passwords
- Tampering: Parameter manipulation in login requests
- Repudiation: Lack of audit logs for failed login attempts
- Information Disclosure: Verbose error messages leaking account status
- Denial of Service: Automated login flooding
- Elevation of Privilege: Broken role checks after authentication
