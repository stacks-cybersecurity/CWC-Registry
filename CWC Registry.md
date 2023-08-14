In an attempt to create an equivalent to the excellent [SWC Registry](https://swcregistry.io) security vulnerabilty classification standard, applicable to the Stacks blockchain and Clarity programming language, the Stacks Foundation has developed the Clarity Weakness Classification Registry. The CWC Registry will categorize any and all weaknesses involving the blockchain or Clarity into a single comprehensive reference document. This allows for faster triaging and analysis, provides an up-to-date resource for vulnerability remediation, a standardized language for discussing security issues, and a way to track and protect against attack trends.

## The Classification

| Category | Subcategory | Recommended Severity Score | CVE Equivalent |
| --- | --- | --- | --- |
| 51% Attack | Control of mining power via paused RBF calls | Critical | |
| Authentication & Authorization | Use of tx.sender | Medium | |
| | Pool or app access issues | High | |
| | Unrestricted owner privileges  | Critical | |
| Business Logic Flaws & Bad Coding Practices | Wrong token, address, or contract used | Critical | |
| | Use or activation of inactive contract | Critical | |
| | Lack or failed implementation of enforced governance mechanisms | High | |
| | Deposit, transfer, or withdraw issues | High | |
| | Validation issues and error handling | Medium | |
| | General logic flaws | Medium | |
| Chain Splits & Reorgs | Accepting blocks under flawed conditions | Critical | |
| | Creation of a new chain | Critical | |
| | Double spending | Critical | |
| Code Cleanliness & Readability | Best practice issues | Low | |
| | Dead code | Low | |
| | Code inefficiency | Low | |
| | Comments | Low | |
| Denial of Service | Error Handling | High | |
| | Logic | High | |
| Frozen Assets | Transaction issues | Critical | |
| | Locking and unlocking issues | Critical | |
| | Distribution and burning issues | High | |
| | Crashes | Critical | |
| Funds Theft | Frontrunning | Critical | |
| | Fees | Critical | |
| | Race conditions | High | |
| | Math and logic errors leading to funds theft | Critical | |
| | Authentication and authorization issues leading to funds theft | Critical | |
| Gas Optimization | Overpaying gas | Medium | |
| | Underpaying gas | Medium | |
| Math Errors | Rounding, fractions, and decimals | Medium | |
| | Arithmetic overflows and underflows | Medium | |
| | Randomness and cryptographic security | Medium | |
| Remote Code Execution | Malicious contract usage | Critical | |
| | Malicious owners and operators | Critical | |
| Social Engineering | Name squatting, copying, and duplication | Low | |
| | Phishing and user manipulation | Medium | |


### Remediation Guidelines

*WIP.*