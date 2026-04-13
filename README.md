> [!CAUTION]
> **本プロジェクトは提供を終了しました**
>
> 2026年4月13日をもって、本リポジトリはアーカイブされました。  
> 本プロジェクトはすでにメンテナンスを終了しており、  
> 今後、機能追加、バグ修正、ならびにセキュリティアップデートは一切提供されません。
>
> 本プロジェクトの新規利用および継続利用は推奨されません。

# addlicense

The program ensures source code files have copyright license headers
by scanning directory patterns recursively.

It modifies all source files in place and avoids adding a license header
to any file that already has one.

## install

    go get -u github.com/google/addlicense

## usage

    addlicense [flags] pattern [pattern ...]

    -c copyright holder (defaults to "Google LLC")
    -f custom license file (no default)
    -l license type: apache, bsd, mit (defaults to "apache")
    -y year (defaults to current year)

The pattern argument can be provided multiple times, and may also refer
to single files.

## license

Apache 2.0

This is not an official Google product.
