SPDX-License-Identifier: Community-Spec-1.0

# parameter

## Summary

Property describing a parameter used in an instance of a build.

## Description

parameter is a key-value of a build parameter and its value that
was provided to the builder for a build instance, according to the buildType.

This is different from the [environment](environment.md) property in that
the key and value are provided as command line arguments or
a configuration file to the builder.

## Metadata

- name: parameter
- Nature: ObjectProperty
- Range: /Core/DictionaryEntry

## Summary @zh-Hans

此属性描述在构建实例中使用的参数。

## Description @zh-Hans

`parameter` 是构建参数的键值对，及其根据 `buildType` 提供给构建者用于构建实例的值。

这与 [`environment`](environment.md) 属性的不同之处在于，键和值是作为命令行参数或配置文件提供给构建者的。

## Summary @ja

ビルドのインスタンスで使用されるパラメータを記述するプロパティ

## Description @ja

パラメータは、ビルドパラメータのキーと値のペアであり、ビルドタイプに応じてビルドインスタンス用にビルダーに提供された値である。

これは[`environment`](environment.md)プロパティとは異なり、キーと値はコマンドライン引数または設定ファイルとしてビルダーに提供される。