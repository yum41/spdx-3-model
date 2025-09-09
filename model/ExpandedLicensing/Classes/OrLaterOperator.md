SPDX-License-Identifier: Community-Spec-1.0

# OrLaterOperator

## Summary

Portion of an AnyLicenseInfo representing this version, or any later version,
of the indicated License.

## Description

An OrLaterOperator indicates that this portion of the AnyLicenseInfo
represents either (1) the specified version of the corresponding License, or
(2) any later version of that License. It is represented in the SPDX License
Expression Syntax by the `+` operator.

It is context-dependent, and unspecified by SPDX, as to what constitutes a
"later version" of any particular License. Some Licenses may not be versioned,
or may not have clearly-defined ordering for versions. The consumer of SPDX
data will need to determine for themselves what meaning to attribute to a
"later version" operator for a particular License.

## Metadata

- name: OrLaterOperator
- SubclassOf: ExtendableLicense
- Instantiability: Concrete

## Properties

- subjectLicense
  - type: License
  - minCount: 1
  - maxCount: 1

## Summary @ja

`AnyLicenseInfo` のうち、指定されたライセンスの表記されているバージョン、またはそれ以降のバージョンの情報を表すクラス

## Description @ja

`OrLaterOperator` は、`AnyLicenseInfo` のバージョン情報が (1) 対応するライセンスの指定バージョン、または (2) そのライセンスのそれ以降のいずれかのバージョンを表すことを示す。これはSPDX License Expression Syntax(SPDXライセンス構文)において `+` 演算子で表される。

特定のライセンスにおける"後続バージョン"の定義は文脈依存であり、SPDXでは規定されていない。`License`によってはバージョン管理が行われていない場合や、バージョン順序が明確に定義されていない場合がある。SPDXデータの利用者は、特定のライセンスにおける"後続バージョン"の演算子にどのような意味を付与するかを自ら判断する必要がある。