SPDX-License-Identifier: Community-Spec-1.0

# DisjunctiveLicenseSet

## Summary

Portion of an AnyLicenseInfo representing a set of licensing information where
only one of the elements applies.

## Description

A DisjunctiveLicenseSet indicates that _only one_ of its subsidiary
AnyLicenseInfos is required to apply. In other words, a DisjunctiveLicenseSet
of two or more licenses represents a licensing situation where _only one_ of
the specified licenses are to be complied with.

A consumer of SPDX data would typically understand this to permit the recipient
of the licensed content to choose which of the corresponding license they would
prefer to use. It is represented in the SPDX License Expression Syntax by the
`OR` operator.

## Metadata

- name: DisjunctiveLicenseSet
- SubclassOf: /SimpleLicensing/AnyLicenseInfo
- Instantiability: Concrete

## Properties

- member
  - type: /SimpleLicensing/AnyLicenseInfo
  - minCount: 2

## Summary @ja

`AnyLicenseInfo` のうち、いずれか1つの要素が適用されるライセンス情報に関するクラス

## Description @ja

`DisjunctiveLicenseSet` は、その下位にある `AnyLicenseInfos` のうち、適用に必要なのは _いずれか一つ_ であることを示す。言い換えれば、2つ以上のライセンスからなる`DisjunctiveLicenseSet` は、指定されたライセンスのうち _いずれか一つ_ に準拠すればよいというライセンス状況を表す。

SPDXデータの利用者は、この表記によって「ライセンス対象のコンテンツの受領者が対応するライセンスのうちどれを使用するかを選択することができる」と解釈するのが一般的である。また、これはSPDX License Expression Syntax(SPDXライセンス構文)において `OR` 演算子で表される。
