README

# steps
## サービス概要
Steps（ステップス）は子供の運動機能を指定したスポーツに基づいて簡易的に評価し、経過を記録するアプリです。
得意や運動や苦手な運動を把握することで目標とする運動機能の獲得を目指します。
また、運営に目標の立て方などを相談したり、他ユーザーに対して質問することで交流を図ることが出来ます。

## サービスコンセプト
理学療法士として働いてきた中で、お子さんの運動機能について心配や疑問を持たれている親御さんが多く見られました。原因として目標の立て方や運動のやり方が分からないことなどが一因となっていると感じました。その為簡易的にお子さんの成長を評価・記録出来、他のユーザーなどと交流を図るサービスがあれば、子供達の成長や親御さんの不安や疑問解消のお役に立てるのではないかと考えてこのサービスを考案しました。
このサービスの評価は簡易的である為専門性は弱いかもしれませんが、学校などではあまり使用されないがスポーツで普遍的に必要とされる運動機能（コーディネーション）について評価が出来るものとなっています。運動機能の向上やスポーツの入門として気軽に使用して頂けるものを目指していきたいと考えています。

##　想定されるユーザー層
小学生（6歳から12歳まで）を想定しています。コーディネーションの評価自体は年齢やスポーツの熟練度に関わらず適応出来るものですので、MVPリリース後中学生や大人など広い年齢層が使えることを目指すかもしれません。
スポーツに意欲的な人に加えて、スポーツが苦手な人（初心者）も簡単に運動機能が評価出来るようなアプリを目指します。

##　サービスの利用イメージ
　スポーツをこれから始めるお子さんや既に始めているお子さん、運動が苦手なお子さんの目標の立て方を例を用いて提示します。それらを参考に自ら目標を立ててもらいます。（野球やサッカー、バスケットボールなどスポーツごとの目標例やポイントを提示します。運動が苦手なお子さん向けにも低学年や中学年といったように学年ごとに目標の立て方を提示します。）
　それらの目標に対して現在何割程度の機能を有しているか評価してもらいます。（7つ（の予定）分類について0から10の11段階評価を付けて貰います。経過を追うことが出来るように数値化が可能な目標を立てていただきます。希望があれば運営へのレビュー依頼や他のユーザーへの質問も可能となっています。）
　評価に基づいて運動や練習をして頂き、その後再評価をしてもらいます。（期間は任意です。上記と同じくレビュー依頼や他のユーザーへの質問が可能です。）
　入力して頂いたデータをグラフ化し、経過を分かりやすく提示します。

##　ユーザーの獲得について
個人はもちろんスポーツクラブや運動支援団体にも使用してもらいたいです。
SNSや直接の宣伝などが主となると思われます。
ユーザー通しの交流を図り、質問履歴を残すことでCGMの展開を目指します。

##　サービスの差別化ポイント・推しポイント
評価内容が類似しているアプリにALPHA、Quality、マイスポなどがあります。どれも腹筋運動や長座体前屈など学校の運動機能評価に基づいたサービスであり、コーディネーション能力（協調性や運動神経と言われている自身の体を思い通りに動かせる能力）の評価ではありません。その為評価内容の差別化がされていると思われます。
機能が類似しているアプリに上記に加えてExcelがありますが、Excelで書式を作るより簡易的に利用が可能です。

## 実装を予定している機能
### MVP
* 会員登録
* ログイン
* 運動機能簡易評価
* 評価結果のグラフ表示
* 運動機能評価・経過の保存、ダウンロード機能
* 他のユーザーへの質問出来るプラットフォーム
* 運営へのレビュー依頼機能

### 本リリース
* 各スポーツ、年齢に対する目標設定の見本
* 評価項目の増減機能（任意で筋力や持久力といった項目も増やせるようにしたいです。）
* 評価シートの追加機能（場合によっては野球とサッカーといったようにそれぞれで評価したいと思われる為複数のシートが使えるようにしたいです。）
* MVP実装中に追加の機能のアイディアがあればそれも実装を検討します

##　機能の実装方針予定
11/1まで　README
11/3まで　画面遷移図
11/5まで　ER図

* 11/6~12/22(卒業期限)　MVPリリース
11/8トップページの作成
11/10 ユーザー登録とログイン機能
11/12 運動評価フォームの作成
11/18 評価結果のグラフ表示機能
11/20 評価データの保存、ダウンロード機能
11/24 質問プラットフォームの作成
11/28 レビュー依頼の機能
12/6 UI/UXの改善、バグ修正など
12/15 総合テスト、デプロイ

12/22 卒業期限

12/23 本リリースに向けた実装


### 画面遷移図
Figma：https://www.figma.com/design/Rh6zI3cJzR4I3hOm0FPxfN/Untitled?node-id=0-1&node-type=canvas&t=NM5lriN3JALxY9IG-0

### READMEに記載した機能
- [ ] ユーザー登録機能
- [ ] ログイン機能
- [ ] パスワード変更機能
- [ ] メールアドレス変更機能
- [ ] 運動機能簡易評価（目標設定）
- [ ] 運動機能簡易評価（評価内容入力）
- [ ] 評価結果のグラフ表示
- [ ] 運動機能評価・経過の保存、ダウンロード機能
- [ ] 他のユーザーへの質問出来るプラットフォーム
- [ ] 運営へのレビュー依頼機能

### 未ログインでも閲覧または利用できるページ
以下の項目は適切に未ログインでも閲覧または利用できる画面遷移になっているか？
- [ ] 過去の他のユーザーへの質問結果の閲覧

### メールアドレス・パスワード変更確認項目
直接変更できるものではなく、一旦メールなどを介して専用のページで変更する画面遷移になっているか？
- [ ] メールアドレス
- [ ] パスワード

### 各画面の作り込み
画面遷移だけでなく、必要なボタンやフォームが確認できるくらい作り込めているか？
- [ ] 作り込みはある程度完了している（Figmaを見て画面の作成ができる状態にある）
