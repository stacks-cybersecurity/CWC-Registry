# The Clarity Weakness Classification Registry

In an attempt to create an equivalent to the excellent [SWC Registry](https://swcregistry.io) security vulnerabilty classification standard, applicable to the Stacks blockchain and Clarity programming language, the Stacks Foundation has developed the Clarity Weakness Classification Registry. The CWC Registry will categorize any and all weaknesses involving the blockchain or Clarity into a single comprehensive reference document. This allows for faster triaging and analysis, provides an up-to-date resource for vulnerability remediation, a standardized language for discussing security issues, and a way to track and protect against attack trends.

## The Classification

| Category | Subcategory |
| --- | --- |
| 51% Attack | Control of mining power via paused RBF calls | 
| Authentication & Authorization | Use of tx.sender |
| | Pool or app access issues |
| | Unrestricted owner privileges  |
| Business Logic Flaws & Bad Coding Practices | Wrong token, address, or contract used | 
| | Use or activation of inactive contract |
| | Lack or failed implementation of enforced governance mechanisms |
| | Deposit, transfer, or withdraw issues | 
| | Validation issues and error handling | 
| | General logic flaws |
| Chain Splits & Reorgs | Accepting blocks under flawed conditions |
| | Creation of a new chain | 
| | Double spending | 
| Code Cleanliness & Readability | Best practice issues |
| | Dead code | 
| | Code inefficiency |
| | Comments | 
| Denial of Service | Error Handling | 
| | Logic |
| Frozen Assets | Transaction issues | 
| | Locking and unlocking issues |
| | Distribution and burning issues |
| | Crashes
| Funds Theft | Frontrunning | 
| | Fees |
| | Race conditions | 
| | Math and logic errors leading to funds theft |
| | Authentication and authorization issues leading to funds theft |
| Gas Optimization | Overpaying gas | 
| | Underpaying gas | 
| Math Errors | Rounding, fractions, and decimals | 
| | Arithmetic overflows and underflows | 
| | Randomness and cryptographic security |
| Remote Code Execution | Malicious contract usage |
| | Malicious owners and operators | 
| Social Engineering | Name squatting, copying, and duplication |
| | Phishing and user manipulation |


### Remediation Guidelines

*WIP.*
