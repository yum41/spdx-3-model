SPDX-License-Identifier: Community-Spec-1.0

# ConjunctiveLicenseSet

## Summary

Portion of an AnyLicenseInfo representing a set of licensing information
where all elements apply.

## Description

A ConjunctiveLicenseSet indicates that _each_ of its subsidiary
AnyLicenseInfos apply. In other words, a ConjunctiveLicenseSet of two or
more licenses represents a licensing situation where _all_ of the specified
licenses are to be complied with. It is represented in the SPDX License
Expression Syntax by the `AND` operator.

It is syntactically correct to specify a ConjunctiveLicenseSet where the
subsidiary AnyLicenseInfos may be "incompatible" according to a particular
interpretation of the corresponding Licenses.
The
[SPDX License Expression Syntax](../../../annexes/spdx-license-expressions.md)
does not take into account interpretation of license texts, which is
left to the consumer of SPDX data to determine for themselves.

## Metadata

- name: ConjunctiveLicenseSet
- SubclassOf: /SimpleLicensing/AnyLicenseInfo
- Instantiability: Concrete

## Properties

- member
  - type: /SimpleLicensing/AnyLicenseInfo
  - minCount: 2

## Summary @ja

`AnyLicenseInfo` のうち、すべての要素が適用されるライセンス情報に関するクラス

## Description @ja

`ConjunctiveLicenseSet` は、その下位にある _それぞれの_ `AnyLicenseInfo` がすべて適用されることを示す。言い換えれば、2つ以上のライセンスからなる `ConjunctiveLicenseSet` は、指定された _すべての_ ライセンスを遵守する必要があるというライセンス状況を表す。これはSPDX License Expression Syntax(SPDXライセンス構文)において `AND` 演算子で表される。

特定の解釈において、関連するライセンスに基づき下位の `AnyLicenseInfos` が"互換性がない"場合でも、 `ConjunctiveLicenseSet` を指定することは構文的に正しい。[SPDX License Expression Syntax (SPDXライセンス表記構文)](../../../annexes/spdx-license-expressions.md) はライセンス本文の解釈を考慮しておらず、これはSPDXデータの利用者が自ら判断するものとされている。