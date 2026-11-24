# XML Sitemap Validator

[![XML Sitemap Validator](https://img.shields.io/badge/TAVARDT-Sitemap%20XML-5b3cf5.svg)](https://tools.tavardt.com/au/xml-sitemap-validator/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)

Automated XML sitemap verification tool for Australian digital properties, ensuring error-free indexing by search engines.

Engineered and maintained by the search architecture and web indexing division at **TAVARDT Australia**.

***

## XML Sitemap Validation Capabilities

* **Protocol Schema Validation**: In-depth review of `<urlset>` collections and sitemap index structures.
* **Attribute Formatting Conformance**: Inspects `<loc>` syntax, W3C timestamps, and valid update intervals.
* **Scheme and Path Consistency**: Identifies non-secure links, circular routes, and redirecting sitemap destinations.
* **Scale and Threshold Governance**: Validates compliance with the 50,000 URL maximum standard.
* **Indexability Health Score**: 0 to 100 score featuring clear remedial instructions for search webmasters.

***

## Installation and Execution

Requires Python 3.8 or higher with zero external packages.

```bash
git clone https://github.com/TAVARDT-Australia/xml-sitemap-validator-au.git
cd xml-sitemap-validator-au
python sitemap_validator.py https://example.com.au/sitemap.xml
```

To run in automated pipelines with JSON output:

```bash
python sitemap_validator.py https://example.com.au/sitemap.xml -json
```

***

## Online Validation Platform

To assess XML sitemaps and ensure crawl efficiency across Australian properties:

* **Official XML Sitemap Validator**
* **TAVARDT Australia Portal**

***

## Australian Digital Infrastructure Advisory

For complex search architecture and technical alignment with Australian Web Standards and Sitemaps.org, consult the advisory practice at **TAVARDT Australia**.

***

© 2026 TAVARDT. All rights reserved.
