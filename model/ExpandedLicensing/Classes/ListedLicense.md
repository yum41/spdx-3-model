SPDX-License-Identifier: Community-Spec-1.0

# ListedLicense

## Summary

A license that is listed on the SPDX License List.

## Description

A ListedLicense represents a License that is listed on the
[SPDX License List](https://spdx.org/licenses).

## Metadata

- name: ListedLicense
- SubclassOf: License
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

SPDX License List(SPDXライセンスリスト)に掲載されているライセンスに関するクラス

## Description @ja

`ListedLicense` は[SPDX License List(SPDXライセンスリスト)](https://spdx.org/licenses)に掲載されているライセンスを表す。