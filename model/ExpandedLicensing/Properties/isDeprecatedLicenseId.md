SPDX-License-Identifier: Community-Spec-1.0

# isDeprecatedLicenseId

## Summary

Specifies whether a license or additional text identifier has been marked as
deprecated.

## Description

The isDeprecatedLicenseId property specifies whether an identifier for a
License or LicenseAddition has been marked as deprecated. If the property
is not defined, then it is presumed to be false (i.e., not deprecated).

If the License or LicenseAddition is included on the
[SPDX License List](https://spdx.org/licenses/), then
the `deprecatedVersion` property indicates on which version release of the
License List it was first marked as deprecated.

"Deprecated" in this context refers to deprecating the use of the
_identifier_, not the underlying license. In other words, even if a License's
author or steward has stated that a particular License generally should not be
used, that would _not_ mean that the License's identifier is "deprecated."
Rather, a License or LicenseAddition operator is typically marked as
"deprecated" when it is determined that use of another identifier is
preferable.

## Metadata

- name: isDeprecatedLicenseId
- Nature: DataProperty
- Range: xsd:boolean

## Summary @ja

ライセンスまたは追加テキスト識別子が非推奨とされているかどうかを指定するプロパティ

## Description @ja

`isDeprecatedLicenseId` は、`License` または `LicenseAddition` の識別子が非推奨であるかどうかを指定する。このプロパティが定義されていない場合は、非推奨ではないとみなされる。

`License` または `LicenseAddition` が[SPDX License List(SPDXライセンスリスト)](https://spdx.org/licenses/)に含まれる場合、`deprecatedVersion` は、Lisence List(ライセンスリスト)においてどのバージョンで初めて非推奨となったかを示す。

この文脈における"非推奨"とは、 _識別子_ の使用を非推奨とすることを指し、基盤となるライセンス自体を指すものではない。言い換えれば、`License` の作成者や管理者がある特定の `License` を一般的に使用すべきでないと表明した場合でも、それはその `License` の識別子が"非推奨"であることを _意味するものではない_ 。むしろ、別の識別子の使用が望ましいと判断された場合に、通常 `License` または `LicenseAddition` の識別子は"非推奨"となる。