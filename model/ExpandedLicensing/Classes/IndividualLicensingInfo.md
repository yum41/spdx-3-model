SPDX-License-Identifier: Community-Spec-1.0

# IndividualLicensingInfo

## Summary

A concrete subclass of AnyLicenseInfo used by Individuals in the
ExpandedLicensing profile.

## Description

Individuals, such as NoneLicense and NoAssertionLicense, need to reference a
concrete subclass of AnyLicenseInfo.

This class provides the type used by the individuals.

## Metadata

- name: IndividualLicensingInfo
- SubclassOf: /SimpleLicensing/AnyLicenseInfo
- Instantiability: Concrete

## Summary @ja

`ExpandedLicensing` プロファイルにおいて `Individuals` によって使用される `AnyLicenseInfo` の具象クラス

## Description @ja

`NonLicense` や `NoAssertionLicense` などの `Individuals` は、`AnyLicenseInfo` の具体的なサブクラスを参照する必要がある。

`IndividualLicensesingInfo` は、`Individual` が使用するタイプを提供する。