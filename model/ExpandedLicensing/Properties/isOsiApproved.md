SPDX-License-Identifier: Community-Spec-1.0

# isOsiApproved

## Summary

Specifies whether the License is listed as approved by the
Open Source Initiative (OSI).

## Description

isOsiApproved specifies whether the
[Open Source Initiative (OSI)](https://opensource.org)
has listed this License as "approved" in their list of OSI Approved Licenses,
located at the time of this writing at
[OSI Approved Licenses](https://opensource.org/licenses).

A value of "true" indicates that the license is in the list of licenses that
OSI publishes as approved.

A value of "false" indicates that the license is explicitly not in the
corresponding list of OSI licenses (e.g., OSI has stated publicly that a
license is not approved).

If the isOsiApproved field is not specified, the SPDX data creator makes no
assertions about whether the License is approved by the OSI.

## Metadata

- name: isOsiApproved
- Nature: DataProperty
- Range: xsd:boolean

## Summary @ja

`License` がOpen Source Initiative(OSI、オープンソース・イニシアチブ)によって承認済みとしてリストに含まれるかどうかを指定するプロパティ

## Description @ja

`isOsiApproved` は、[Open Source Initiative (OSI、オープンソース・イニシアチブ)](https://opensource.org)がこの `License` を"承認済み"としてOSI Approved Licenses(OSI認証ライセンス)のリストに掲載しているかどうかを指定する。本稿執筆時点では、[OSI Approved Licenses(OSI承認ライセンス)](https://opensource.org/licenses) に掲載されている。

値が `true` の場合、そのライセンスはOSIが承認済みとして公開するライセンスリストに含まれることを示す。

値が `false` の場合、そのライセンスはFSFがOSIが承認済みとして公開するライセンスリストに含まれていないことを示す(例：OSIが公にライセンスを承認していないと表明している場合)。

`License`が指定されていない場合、SPDXデータ作成者は `License` がFSFの解説リストに掲載されているか否かについては断定しないことを示す。