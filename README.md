﻿# sDRAC

## Description

sDRAC, or the Simple Dependencies Risk Assessment Checklist, is a checklist to help you start triaging vulnerabilities (CVEs, BDSCs, GHSAs, ...) in dependencies.

**Note:** This is not a comprehensive list.

## Checklist

- [ ] Is the vulnerable package included in your Software Bill of Materials (SBOM) / project?
- [ ] Does the version of the package you're using fall within the vulnerable range specified?
- [ ] Is the vulnerable package actively used in your application?
- [ ] Are you utilizing the specific method or configuration is affected by the vulnerability?
- [ ] Does your application's usage of the package match the conditions described in the vulnerability disclosure?
