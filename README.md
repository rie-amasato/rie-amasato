Nuxt3とPythonが好き  
最近はフロントにCloudFlare、バックとかデータベースににfly.ioやらKoyebを使って遊んでいる  
ちょっとPaaSを色々使って遊んでる  

### こんなものを作っています  
###### fAkePedia
ハルシネーションを鑑賞するページ
- 使っているもの
  - フロント: Nuxt3
    - Cloudflareにデプロイ
  - バック: flaskでGeminiのAPIを叩いて嘘を出力・ストリーミングとして取得
    - koyebにデプロイ

https://fakepedia.pages.dev

↓geminiのFree tireだもんでレート制限やら混雑時でうまく動かない時のサンプル用もとい生成履歴機能。
https://fakepedia.pages.dev/history/256

---
###### AmaSugar
TailwindみたくCSSフレームワーク。
自前で使う際に簡単に使えるようにnpmライブラリ化しています。
https://amasugar.pages.dev/ils-food-cake

↓npmjsのリンク
https://www.npmjs.com/package/amasugar

---
更新するたびに変化する迷路（緑が地面で黒が壁）
- 使っているもの
  - 壁伸ばし方(迷路の自動生成)
  - FlaskでSVGとして返すAPIにする
  - Dockerfileを使ってKoyebでホスティング、GithubのMarkdownで毎回リロードされるようにキャッシュ関連の設定を調整   
 
![svg_mage](https://secure-olimpia-shihoaka-fd09df42.koyeb.app/imgapi-mage/19.svg)

---
こうもりの群れもどき
- 使っているもの
  - アルゴリズムはBoidモデル
  - JavaScript
  - github.ioで公開

https://rie-amasato.github.io/Bat_roid/  
<img src="https://raw.githubusercontent.com/rie-amasato/Bat_roid/main/3E675A23-BCD0-445F-88A5-0C767BD47A50.jpeg" height=200>
