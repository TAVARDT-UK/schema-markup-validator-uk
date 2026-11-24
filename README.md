# Schema Markup and Structured Data Validator

[![Schema Validator](https://img.shields.io/badge/TAVARDT-Schema.org%20Validator-5b3cf5.svg)](https://tools.tavardt.com/uk/schema-markup-validator/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Technical validation tool for Schema.org structured data, inspecting JSON-LD and Microdata entities, required attributes, and rich snippets readiness.

Engineered and maintained by the semantic web and technical search engineering practice at **TAVARDT**.

***

## Semantic Validation Capabilities

* **Structured Data Extraction**: Automated parsing of embedded JSON-LD blocks (`application/ld+json`) and inline Microdata markup.
* **Schema.org Entity Auditing**: Comprehensive recognition of core entities including Organisation, LocalBusiness, WebSite, Article, Product, FAQPage, and BreadcrumbList.
* **Syntax and Schema Integrity Checks**: Detection of malformed JSON strings, missing required attributes, and broken semantic linkages.
* **Semantic Quality Benchmark**: Objective 0 to 100 rating accompanied by prioritized guidance for rich snippets eligibility.

***

## Installation and Execution

Requires Python 3.8 or higher with standard library only.

```bash
git clone https://github.com/TAVARDT-UK/schema-markup-validator-uk.git
cd schema-markup-validator-uk
python schema_validator.py example.co.uk
```

To output machine-readable JSON:

```bash
python schema_validator.py example.co.uk -json
```

***

## Online Validation Suite

For interactive testing and recurring semantic verification:

* **Official Schema Markup Validator**
* **TAVARDT Corporate Portal**

***

## Semantic Web and Structured Architecture Advisory

For enterprise entity modelling, schema implementation, and alignment with W3C Semantic Standards and Search Best Practices, contact the technical specialists at **TAVARDT**.

***

## Governance and Sovereignty

* **Sovereign Unit**: [TAVARDT United Kingdom](https://ag.tavardt.com/uk/) (`TAVARDT-UK`)
* **Core Standards**: [00-core Governance](https://github.com/TAVARDT-UK/00-core)
* **Diagnostic Portal**: **TAVARDT UK Diagnostic Suite**
* **Enterprise Security**: [TAVARDT UK Cybersecurity](https://ag.tavardt.com/uk/cybersecurity/)

***

### License
Released under the MIT License. See [LICENSE](LICENSE) for full details.

***

© 2026 TAVARDT. All rights reserved.
