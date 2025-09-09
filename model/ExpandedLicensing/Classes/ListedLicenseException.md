SPDX-License-Identifier: Community-Spec-1.0

# ListedLicenseException

## Summary

A license exception that is listed on the SPDX Exceptions list.

## Description

A ListedLicenseException represents an exception to a License (in other words,
an exception to a license condition or an additional permission beyond those
granted in a License) which is listed on the
[SPDX License Exceptions](https://spdx.org/licenses/exceptions-index.html).

## Metadata

- name: ListedLicenseException
- SubclassOf: LicenseAddition
- Instantiability: Concrete

## Properties

- deprecatedVersion
  - type: xsd:string
  - minCount: 0
  - maxCount: 1
- listVersionAdded
  - type: xsd:string
  - minCount: 0
  - maxCount: 1

## Summary @ja

SPDX Exceptions Listに記載されているライセンス例外

## Description @ja

`ListedLicenseException` は、[SPDX License Exceptions(SPDXライセンス例外)](https://spdx.org/licenses/exceptions-index.html) に記載されているライセンスに対する例外（言い換えれば、ライセンス条件に対する例外、またはライセンスで付与された許可を超える追加の許可）を表す。