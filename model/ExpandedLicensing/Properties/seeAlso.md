SPDX-License-Identifier: Community-Spec-1.0

# seeAlso

## Summary

Contains a URL where the License or LicenseAddition can be found in use.

## Description

A seeAlso defines a cross-reference with a URL where the License or
LicenseAddition can be found in use by one or a few projects.

If applicable, it should include a URL where the license text is posted by
the license steward, particularly if the license steward has made available a
"canonical" primary URL for the license text.

If the license is OSI approved, a seeAlso should be included with the URL for
the license's listing on the OSI website.

The seeAlso URL may refer to a previously-available URL for the License or
LicenseAddition which is no longer active.

Where applicable, the seeAlso URL should include the license text in its
native language. seeAlso URLs to English or other translations may be included
where multiple, equivalent official translations exist.

## Metadata

- name: seeAlso
- Nature: DataProperty
- Range: xsd:anyURI

## Summary @ja

`License` または `LicenseAddition` が使用される場所を示すURLを含むプロパティ

## Description @ja

`seeAlso` は、1つまたは複数のプロジェクトで使用されている `License` または複数のプロジェクトで使用されている `License` または `LicenseAddition` のURLを参照するための相互参照先を定義する。

該当する場合、ライセンス管理者がライセンス条文を掲載しているURLを含めるべきである。特にライセンス管理者が条文の"正規な"主要URLを公開している場合は必須である。

ライセンスがOSI承認済みの場合、 `seeAlso` 項目にOSIウェブサイト上のライセンス掲載ページURLを含める必要がある。

`seeAlso` に記載されるURLは、ライセンスまたは `LicenseAddition` の旧URL（現在無効なもの）を参照する場合がある。

該当する場合、`seeAlso` のURLにはライセンス本文を原文の言語で示すべきである。複数の同等の公式翻訳が存在する場合、英語版やその他の翻訳版への`seeAlso` のURLを含めることができる。
