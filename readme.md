## windows8.1再インストール後の開発環境セットアップ

### chocoratey

[Windows8.1で始めるイマドキの開発環境](http://qiita.com/koduki/items/a833d22c7d8cf6f8f55e)

`cinst packages.config -y`

### sublime text3

[Sublime Text 3 のインストールと設定](http://qiita.com/lunatea/items/53f4adcc6ea3f316e781 "Sublime Text 3 のインストールと設定")

### markdownpad 2

[MarkdownPad2のプレビューが中国語フォントになるときの対処](http://nakaji.hatenablog.com/entry/2013/12/30/232149 "MarkdownPad2のプレビューが中国語フォントになるときの対処")

### ruby

[windowsでgem installするとSSLエラー](http://qiita.com/shimoju/items/394818b4989b94680aaf)

`gem install pry`

### node.js

- kokoを導入

`npm install koko -g`

node_modules\koko\index.jsの133行目のopenをstartに変更すると、windowsでも-oオプションによるブラウザ起動ができる。

- chocolateyのnpmは後方互換性のための古いバージョンなので使ってはいけない