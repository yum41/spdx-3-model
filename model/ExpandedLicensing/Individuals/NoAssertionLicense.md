SPDX-License-Identifier: Community-Spec-1.0

# NoAssertionLicense

## Summary

An Individual Value for License when no assertion can be made about its actual
value.

## Description

NoAssertionLicense should be used if

- the SPDX creator has attempted to but cannot reach a reasonable objective
  determination;
- the SPDX creator has made no attempt to determine this field; or
- the SPDX creator has intentionally provided no information (no meaning should
  be implied by doing so).

## Metadata

- name: NoAssertionLicense
- type: IndividualLicensingInfo
- IRI: https://spdx.org/rdf/3.0.1/terms/Licensing/NoAssertion

## Property Values

- name: "NOASSERTION"

## Summary @ja

実際の `Licese` について断定できない場合に用いられる固有の値

## Description @ja

`NoAssertionLicense` は以下のような場合に利用されるべきである。

- SPDX作成者が合理的な判断を試みたものの、客観的な結論に達することができなかった場合
- SPDX作成者が `License` の特定・調査を一切行っていない場合
- SPDX作成者が意図的に `License` に関する情報を提供しなかった場合(これはライセンス情報が確定していないという事実を指し、特別な意味合いが示唆されるわけではない)
