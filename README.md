# windowsTerminal settings.json

## キー設定の変更

| 表記              | キー                                |
|-------------------|-------------------------------------|
|`Alt+c`            | コピー                              |
|`Alt+v`            | ペースト                            |
|`Ctrl+Shift+f`     | 検索                                |
|`Ctrl+Shift+Tab`   | 前のタブ                            |
|`Ctrl+Tab`         | 次のタブ                            |
|`Alt+t`            | 新しい接続                          |
|`Ctrl+F4`          | 現在のタブを閉じる                   |
|`Alt+e`            | 現在のタブを垂直分割してペイン追加    |
|`Alt+Shift+e`      | 現在のタブを水平分割してペイン追加    |

## フォント

以下がおすすめ。Cica だとどうもうまく表示されないことがある。

* PlemolJP Console NF
* HackGen35Nerd Console

## ColorScheme

以下から気に入ったものを追加してある。

https://github.com/mbadolato/iTerm2-Color-Schemes

ただし、Ubuntu テーマのみ、background を #6A1917 に変更してある

## profiles

* Ubuntu-18.04Prod はプロダクション環境用に作成した
* たとえば以下のようにしてコマンドラインから起動できる
  * 開発環境では wt.exe -p Ubuntu-18.04 -d c:\ wsl ssh ....
  * 本番環境では wt.exe -p Ubuntu-18.04Prod -d c:\ wsl ssh ....

