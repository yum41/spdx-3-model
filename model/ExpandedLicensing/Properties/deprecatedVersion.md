SPDX-License-Identifier: Community-Spec-1.0

# deprecatedVersion

## Summary

Specifies the SPDX License List version in which this license or exception
identifier was deprecated.

## Description

A deprecatedVersion, for a ListedLicense on the
[SPDX License List](https://spdx.org/licenses/)
or a ListedLicenseException on the
[SPDX License Exceptions](https://spdx.org/licenses/exceptions-index.html),
specifies which version release of the License List was the first
one in which it was marked as deprecated.

## Metadata

- name: deprecatedVersion
- Nature: DataProperty
- Range: xsd:string

## Summary @ja

非推奨となるライセンス、または例外識別子のSPDX License List(SPDXライセンスリスト)のバージョンを指定するプロパティ

## Description @ja

[SPDX License List(SPDXライセンスリスト)](https://spdx.org/licenses/) に掲載されている `ListedLicense` または [SPDX License Exceptions(SPDXライセンス例外)](https://spdx.org/licenses/exceptions-index.html) に掲載されている `ListedLicenseException` における `deprecatedVersion` は、ライセンスが非推奨となる場合、非推奨となる最初のLicense List(ライセンスリスト)のバージョンを指定する。