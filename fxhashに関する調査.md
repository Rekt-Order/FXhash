# fxhashについて

## 制作に関する参考資料

入門編としては、[kusakariさんの記事「さあfxhashをはじめよう」](https://note.com/kusakari_/n/na79f93143acb)を参考。

- p5.jsライブラリも外部参照でなくfxhashにアップロードするzipファイルに含める（最新のものをindex.htlmlと同じ階層に入れておく）

- mint後のランダム性をなくす必要あり

- windowサイズ変更に対応する

- fxhashのsandboxでテストする（fxhash上で正しく動作するかをfxhashのsandboxでテストを実施）

少し技術的な記事としては、[永松歩さんの記事「Webpack+TypeScriptでfxhash」](https://qiita.com/ayumu_nagamatsu/items/9faaceb6ce62796daad2) が参考になる。

- fxhashは単純なHTMLとして開けるファイル群を用意できればNFT化できますが、各シリーズがNFTとして不変である必要があり、IPFSにホストされるという点からもCDNなど外部リソースや、APIを叩いたり、または、カメラなどデバイスのリソースにアクセスしようとするコードは動作できません。全体の作品の容量も現状15MB以内の制限があります。
