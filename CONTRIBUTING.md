## 貢献 / Contributing
本ドキュメントでは、コミュニティ内の各プロジェクトに対する貢献方法を説明します。


### 開発者としてできること
もし開発にご興味を持っていただける場合はこちらをご参照ください。

#### ドキュメントの改善
README.md、導入の手順書等での、ミスの修正、わかりづらい点の補足。ソースコード上のコメントの追加等をしていただけると幸いです。

#### (バグを見つけて)Issueを立てる/改善する
何か問題を見つけたらIssueを立ててみてください。また、既存のIssueは必ずしも内容が正しくないかもしれません。より細かな再現または調査を行い、補足を行っていただけると助かります。

#### コード/CI/テスト/設計の改善
もちろん、コードを書いていただくのも大歓迎です。ただし、なるべく他の開発者が読みやすいコードになるよう配慮をお願いします。具体的には下記を配慮してください。

- コミット
  - 説明的で明確な名前
  - なるべく細かい粒度
  - 変更範囲は 最小限
  - わかりづらい処理にはコメント
- Issue
  - なるべくテンプレートに沿って具体的に
  - エラーであればエラーレポートを
    - OS、再現手順、できれば対応策の案
- Pull Request
  - なるべくテンプレートに沿って具体的に
  - 作業を行う/プルリクエストを作る前に
    - DraftPRを作る
    - Issueを立てる
    - Assignを待つ
  - **規定の**フォーマッタやリンターを使う
  - 可能な限りテストを
  - Conflict解消はPRの作成側で
- テストコード
  - 新しい処理を足したらテストコードも追加
  - 既存のテストコードはなるべく通るように
- 変更すべきでないもの
  - 全開発者に影響ある変更
  - 依存関係の更新 (Issueを見てメンテナがPR)
  - Lintルールの変更 (Issueを見てメンテナがPR)


### ユーザーとしてできること
開発者でなくてもこのコミュニティに貢献できることはたくさんあります。

#### 1. できたもので遊ぶ(感想を送る)
プレイヤーが増えて楽しんでくれることが一番です。

#### 2. 友達に教える
よければ、プレイヤーを増やすために人を呼び込んでみてください。Twitterでツイートするだけでも大きな効果があります。

#### 3. ドキュメント(Wiki)の改善 / 他言語への翻訳
Sonolusは慢性的なユーザー向けドキュメント不足であり、様々なガイドページを必要としています。もしよければ、解説等を書いてください。

#### 4. プレイ動画/創作譜面を作る
見てすぐに音と映像が動いてわかる、動画の力は絶大であり、文章より圧倒的なインパクトがあります。もしよければプレイ動画、紹介動画などをあげてみてください。ただし、紹介動画は諸刃の剣です。たとえコメント欄や概要欄に更新情報を用意しても読まないという層が一定数居ます。古くなった紹介動画はなるべく早く削除して、新しい方法のみを紹介しましょう。

#### 5. 初見の人を助ける
ここまでで既に十分助かりますが、Yahoo知恵袋、Youtube、Twitter、Tiktok、Discord等で使い方がわからず困っている初見の人々は大勢います。もし余裕があればそちらの方々を助けてあげてください。

#### 6. アイデアを提案する
よりよくする案があれば、Discord内でもGithub Issueでもどちらでも構わないので 言ってみてください。もしかしたらとてもいい案かもしれません。なお、Sonolus自体もアイデアの提案場が設けられているので、そちらにもぜひ提案してみてください。

#### 7. 支援(寄付)する
可能な限り低予算で動く構成を心がけているため、それほど費用は発生していませんが、もし面白い価値を提供していると思ってくれた方は 寄付をお願いします。Sonolus側も忘れず支援をお願いします。


### このファイルの出典
- [remarkjs/.github/contributing.md By TitusWormer](https://github.com/remarkjs/.github/blob/main/contributing.md)

### このファイルのライセンス
- [CC-BY-4.0 © Dosugamea](https://creativecommons.org/licenses/by/4.0/)