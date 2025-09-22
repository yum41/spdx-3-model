SPDX-License-Identifier: Community-Spec-1.0

# isDeprecatedAdditionId

## Summary

Specifies whether an additional text identifier has been marked as deprecated.

## Description

The isDeprecatedAdditionId property specifies whether an identifier for a
LicenseAddition has been marked as deprecated. If the property is not defined,
then it is presumed to be false (i.e., not deprecated).

If the LicenseAddition is included on the
[SPDX License Exceptions](https://spdx.org/licenses/exceptions-index.html),
then the `deprecatedVersion` property indicates on which version release of the
Exceptions List it was first marked as deprecated.

"Deprecated" in this context refers to deprecating the use of the
_identifier_, not the underlying license addition. In other words, even if a
LicenseAddition's author or steward has stated that a particular
LicenseAddition generally should not be used, that would _not_ mean that the
LicenseAddition's identifier is "deprecated." Rather, a LicenseAddition
operator is typically marked as "deprecated" when it is determined that use of
another identifier is preferable.

## Metadata

- name: isDeprecatedAdditionId
- Nature: DataProperty
- Range: xsd:boolean

## Summary @ja

追加のテキスト識別子が非推奨であるかどうかを指定するプロパティ

## Description @ja

`isDeprecatedAdditionId` は、`LicenseAddition` の識別子が非推奨であるかどうかを指定する。このプロパティが定義されていない場合は、非推奨ではないとみなされる。

`LicenseAddition` が[SPDX License Exceptions(SPDXライセンス例外)](https://spdx.org/licenses/exceptions-index.html)に含まれる場合、`deprecatedVersion` は、Exceptions List(例外リスト)においてどのバージョンで初めて非推奨となったかを示す。

この文脈における"非推奨"とは、 _識別子_ の使用を非推奨とすることを指し、基盤となるライセンス追加条項自体を指すものではない。言い換えれば、`LicenseAddition` の作成者や管理者がある特定の `LicenseAddition` を一般的に使用すべきでないと表明した場合でも、それはその `LicenseAddition` の識別子が"非推奨"であることを _意味するものではない_ 。むしろ、別の識別子の使用が望ましいと判断された場合に、通常 `LicenseAddition` の識別子は"非推奨"となる。