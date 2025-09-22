SPDX-License-Identifier: Community-Spec-1.0

# obsoletedBy

## Summary

Specifies the licenseId that is preferred to be used in place of a deprecated
License or LicenseAddition.

## Description

An obsoletedBy value for a deprecated License or LicenseAddition specifies
the licenseId of the replacement License or LicenseAddition that is preferred
to be used in its place. It should use the same format as specified for a
licenseId.

The License's or LicenseAddition's comment value may include more information
about the reason why the licenseId specified in the obsoletedBy value is
preferred.

## Metadata

- name: obsoletedBy
- Nature: DataProperty
- Range: xsd:string

## Summary @ja

非推奨の `License` または `LicenseAddition` の代わりに推奨される `licenseId` を指定するプロパティ

## Description @ja

非推奨の `License` または `LicenseAddition` の `obsoletedBy` 値は、その代わりに使用することが推奨される `License` または `LicenseAddition` の `licenseId` を指定する。これは `licenseId` で指定されるものと同じ形式を使用する。
