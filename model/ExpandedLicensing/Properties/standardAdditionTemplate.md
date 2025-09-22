SPDX-License-Identifier: Community-Spec-1.0

# standardAdditionTemplate

## Summary

Identifies the full text of a LicenseAddition, in SPDX templating format.

## Description

A standardAdditionTemplate contains a license addition template which describes
sections of the LicenseAddition text which can be varied.

See the Legacy Text Template format section of the
[SPDX License List Matching Guidelines](../../../annexes/license-matching-guidelines-and-templates.md)
for format information.

It is recommended to use [licenseXml](./licenseXml.md) instead, as it can
capture all the text and metadata associated with a license.

## Metadata

- name: standardAdditionTemplate
- Nature: DataProperty
- Range: xsd:string

## Summary @ja

`LicenseAddition` の全文をSPDXのテンプレート形式で識別するためのプロパティ

## Description @ja

`standardAdditionTemplate` には、`LicenseAddition` テキストの可変部分を記述するライセンス追加テンプレートが含まれる。

フォーマット情報については、[SPDX License List Matching Guidelines(SPDXライセンスリスト照合ガイドライン)](../../../annexes/license-matching-guidelines-and-templates.md)のLegacy Text Template format(レガシーテキストテンプレート形式)セクションを参照してください。

代替手段として、[licenseXml](./licenseXml.md)の使用が推奨される。これにより、ライセンスに関連するすべてのテキストとメタデータを取得することが可能となる。
