SPDX-License-Identifier: Community-Spec-1.0

# CustomLicenseAddition

## Summary

A license addition that is not listed on the SPDX Exceptions List.

## Description

A CustomLicenseAddition represents an addition to a License that is not listed
on the
[SPDX License Exceptions](https://spdx.org/licenses/exceptions-index.html),
and is therefore defined by an SPDX data creator.

It is intended to represent additional language which is meant to be added to
a License, but which is not itself a standalone License.

## Metadata

- name: CustomLicenseAddition
- SubclassOf: LicenseAddition
- Instantiability: Concrete

## Summary @ja

SPDX Exceptions List(SPDX例外リスト)に記載されていないライセンス追加条項に関するクラス

## Description @ja

`CustomLicenseAddition` は、[SPDX License Exceptions(SPDXライセンス例外)](https://spdx.org/licenses/exceptions-index.html)に記載されていないライセンスへの追加条項を表す。このため追加事項はSPDXデータ作成者によって定義される。