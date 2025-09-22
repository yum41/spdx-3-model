SPDX-License-Identifier: Community-Spec-1.0

# isFsfLibre

## Summary

Specifies whether the License is listed as free by the
Free Software Foundation (FSF).

## Description

isFsfLibre specifies whether the
[Free Software Foundation (FSF)](https://fsf.org)
has listed this License as "free" in their commentary on licenses, located at
the time of this writing at
[Various Licenses and Comments about Them](https://www.gnu.org/licenses/license-list.en.html).

A value of "true" indicates that the license is in the list of licenses that
FSF publishes as libre.

A value of "false" indicates that the license is explicitly not in the
corresponding list of FSF libre licenses (e.g., FSF has the license on a
non-free list).

If the isFsfLibre field is not specified, the SPDX data creator makes no
assertions about whether the License is listed in the FSF's commentary.

## Metadata

- name: isFsfLibre
- Nature: DataProperty
- Range: xsd:boolean

## Summary @ja

`License` がFree Software Foundation(FSF、フリーソフトウェア財団)によってフリーソフトウェアとしてリストに載っているかどうかを指定するプロパティ 

## Description @ja

`isFsfLibre` は、[Free Software Foundation (FSF、フリーソフトウェア財団)](https://fsf.org)がライセンスに関する解説においてこの `License` を"フリー"と分類しているかどうかを指定する。本解説は執筆時点で[Various Licenses and Comments about Them(さまざまなライセンスとそれらについての解説)](https://www.gnu.org/licenses/license-list.en.html)に掲載されている。

値が `true` の場合、そのライセンスはFSFがフリーソフトウェアとして公開しているライセンスリストに含まれることを示す。

値が `false` の場合、そのライセンスはFSFがフリーソフトウェアとして公開しているライセンスリストに含まれていないことを示す(例：FSFが当該ライセンスをnon-free(非フリー)リストに掲載している場合)。

`isFsfLibre`が指定されていない場合、SPDXデータ作成者は `License` がFSFの解説リストに掲載されているか否かについては断定しないことを示す。