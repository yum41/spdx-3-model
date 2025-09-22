SPDX-License-Identifier: Community-Spec-1.0

# additionText

## Summary

Identifies the full text of a LicenseAddition.

## Description

An additionText contains the plain text of the LicenseAddition, without
templating or other similar markup.

Users of the additionText for a License can apply the
[SPDX License List Matching Guidelines](../../../annexes/license-matching-guidelines-and-templates.md)
when comparing it to another text for matching purposes.

## Metadata

- name: additionText
- Nature: DataProperty
- Range: xsd:string

## Summary @ja

`LicenseAddition` の全文を特定するプロパティ

## Description @ja

`additionText` は、テンプレートやその他の類似したマークアップを含まない、`LicenseAddition` のプレーンテキストが含まれる。

`additionText` を利用するユーザーは他のテキストと比較する際、[SPDX License List Matching Guidelines(SPDXライセンスリスト照合ガイドライン)](../../../annexes/license-matching-guidelines-and-templates.md) を適用することができる。