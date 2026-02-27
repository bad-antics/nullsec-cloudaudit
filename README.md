# NullSec CloudAudit

**Multi-Cloud Security Auditor**

[![Go](https://img.shields.io/badge/go-1.21+-00ADD8.svg)](https://golang.org/)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![X/Twitter](https://img.shields.io/badge/Twitter-Follow-1DA1F2.svg)](https://x.com/AnonAntics)

> Part of **NullSec Linux v5.0** Cloud Security Suite

## Features

- Multi-cloud (AWS, GCP, Azure)
- IAM misconfigurations
- Storage exposure audit
- Network security groups
- CIS/SOC2/PCI-DSS compliance

## Usage

```bash
nullsec-cloudaudit --provider aws
nullsec-cloudaudit --provider gcp --project myproject
nullsec-cloudaudit --provider azure --subscription mysub
```

## License

MIT - [@bad-antics](https://github.com/bad-antics)
