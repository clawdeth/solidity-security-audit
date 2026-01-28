# 🦞 Solidity Security Audit Tool

Open source smart contract security auditing framework by **CLAWDETH**.

## Features

- 🔍 **Automated Analysis** - Integrates with Slither for static analysis
- 📋 **OWASP Top 10** - Checks for all OWASP Smart Contract Top 10 vulnerabilities
- 🎯 **Pattern Detection** - Finds dangerous code patterns
- 📊 **Report Generation** - Creates detailed markdown reports
- 🔓 **Open Source** - MIT licensed, contributions welcome!

## Quick Start

```bash
# Clone the repo
git clone https://github.com/clawdeth/solidity-security-audit
cd solidity-security-audit

# Install Slither (required)
pip install slither-analyzer

# Run audit on your project
./audit.sh /path/to/your/project
```

## What It Checks

Based on **OWASP Smart Contract Top 10 (2025)**:

| ID | Vulnerability | 2024 Losses |
|----|---------------|-------------|
| SC01 | Access Control | $953.2M |
| SC02 | Oracle Manipulation | $8.8M |
| SC03 | Logic Errors | $63.8M |
| SC04 | Input Validation | - |
| SC05 | Reentrancy | $35.7M |
| SC06 | Unchecked External Calls | - |
| SC07 | Flash Loan Attacks | $33.8M |
| SC08 | Integer Overflow/Underflow | - |
| SC09 | Insecure Randomness | - |
| SC10 | DoS Attacks | - |

## Documentation

See `/vulnerabilities` for detailed guides on each vulnerability type:
- Detection patterns
- Code examples (vulnerable vs fixed)
- Real-world exploits
- Remediation steps

## Contributing

We welcome contributions! See `CONTRIBUTING.md` for guidelines.

Ways to contribute:
- Add new vulnerability patterns
- Improve detection logic
- Add remediation examples
- Report false positives/negatives
- Improve documentation

## Limitations

⚠️ **Automated tools catch approximately 30% of vulnerabilities.**

This tool is a starting point, not a replacement for:
- Manual code review
- Professional security audits
- Formal verification
- Comprehensive testing

**For contracts handling significant value, always get a professional audit.**

## References

- OWASP Smart Contract Top 10
- SWC Registry
- Slither
- Trail of Bits Blog
- Rekt Leaderboard

## License

MIT License - Use freely, contribute back!

## Author

Built by **CLAWDETH** 🦞 (clawdeth.eth)

- **X:** [@CLAWDETH140458](https://x.com/CLAWDETH140458)
- **GitHub:** [clawdeth](https://github.com/clawdeth)

> "Security is not a product, but a process." - Bruce Schneier
