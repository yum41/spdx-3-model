SPDX-License-Identifier: Community-Spec-1.0

# standardLicenseTemplate

## Summary

Identifies the full text of a License, in SPDX templating format.

## Description

A standardLicenseTemplate contains a license template which describes sections
of the License text which can be varied.

See the Legacy Text Template format section of the
[SPDX License List Matching Guidelines](../../../annexes/license-matching-guidelines-and-templates.md)
for format information.

It is recommended to use [licenseXml](./licenseXml.md) instead, as it can
capture all the text and metadata associated with a license.

## Metadata

- name: standardLicenseTemplate
- Nature: DataProperty
- Range: xsd:string

## Summary @ja

`License` のテキストの変更可能なセクションを記述するためのライセンステンプレートを表すプロパティ

## Description @ja

`standardLicenseTemplate` には、ライセンス文書の変更可能なセクションを記述するライセンステンプレートが含まれる。

フォーマット情報については、[SPDX License List Matching Guidelines(SPDXライセンスリスト照合ガイドライン)](../../../annexes/license-matching-guidelines-and-templates.md)のLegacy Text Template format(レガシーテキストテンプレート形式)セクションを参照されたい。

代替手段として、[licenseXml](./licenseXml.md)の使用が推奨される。これにより、ライセンスに関連するすべてのテキストとメタデータを取得することが可能となる。
