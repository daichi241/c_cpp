# c_cpp

1. PowerShell を管理者モードで起動する。
2. 次のコマンドで mingw と make をインストールする
```
cinst -y mingw make
```
3. PowerShell を終了する。

### mingwとは
[C言語開発環境の構築(Windows) - BYOD PC のセッティング(24)][1]

[1]:https://hkob.hatenablog.com/entry/2020/05/28/190000
> MinGW は "Minimalist GNU for Windows" の略で、ネイティブの Windows アプリを開発するために必要な最小限の環境を提供するツールセット

### コンパイル
```
gcc <ファイル名>
```
