# test

> 条件を評価します。
> 条件が真と評価された場合は 0 を、偽と評価された場合は 1 を返します。
> 詳しくはこちら: <https://www.gnu.org/software/coreutils/test>

- 与えられた変数が与えられた文字列と等しいかどうかをテスト:

`test "{{$変数名}}" = "{{/bin/zsh}}"`

- 与えられた変数が空であるかどうかをテスト:

`test -z "{{$変数名}}"`

- ファイルが存在するかどうかをテスト:

`test -f "{{ファイルへのパス}}"`

- ディレクトリが存在しないかどうかをテスト:

`test ! -d "{{ディレクトリへのパス}}"`

- if-else 文:

`test {{条件}} && {{echo "真"}} || {{echo "偽"}}`