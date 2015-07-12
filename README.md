## ◆ Help Desk - 1人1アプリ開発
**ここは1人1アプリ開発の質疑応答（Q&amp;A）専用のリポジトリです。**  
ヘルプデスク担当の方は、下記の**ヘルプデスク対応に必要なツールの紹介**と、**ヘルプデスク対応マニュアル**をよく読み、社員（質問者）からの質問をこのリポジトリの issue に登録してください。
なお、issue への登録は下記の**[質問の登録](https://github.com/ncxx-sl-lab/helpdesk/issues/new?title=質問のタイトル&body=%23%23%20質問の内容%0A%0A%23%23%20何が問題なのか%0A%0A%23%23%20解決方法（質問者への対応が完了した時に記載）%0A%0A%23%23%20今後の対応%0A%0A%2a%2a★ お願い：issueの作成者は Labels と Assignee の登録を忘れないように!！%2a%2a)**のボタンをクリックしてから行ってください。
ボタンをクリックすると、質問のひな形作成された状態で issue の登録ページへ画面遷移します。

- **[質問の登録](https://github.com/ncxx-sl-lab/helpdesk/issues/new?title=質問のタイトル&body=%23%23%20質問の内容%0A%0A%23%23%20何が問題なのか%0A%0A%23%23%20解決方法（質問者への対応が完了した時に記載）%0A%0A%23%23%20今後の対応%0A%0A%2a%2a★ お願い：issueの作成者は Labels と Assignee の登録を忘れないように!！%2a%2a)**


## ◆ ヘルプデスク対応に必要なツールの紹介

#### まだGitHubのアカウントを作成していない方は、作成してから読んで下さい

#### issue
- issue とは GitHubの機能の一つで、各リポジトリのタスク管理やバグ管理に使用できる機能です
- issue には一意の番号が作成時に１番から順に自動的に振られていきます
- issue の状態は対応中の open と 対応済みの closed の二種類のみです
- issue は一意の番号で管理されるため、削除することは不可能です
- 不要な issue は closed にして管理すること
- issue のひな形については下記のQiita記事を参照 
 - http://qiita.com/yoshimikeisui/items/3e1873e3bf1bbafe8733
- またissueはmarkdown記法でレイアウトを統一しますので、markdown記法については下記を参照
 - [**markdown記法とは？**](https://github.com/ncxx-sl-lab/members/wiki/.md%E3%83%95%E3%82%A1%E3%82%A4%E3%83%AB%E3%81%AE%E6%9B%B8%E3%81%8D%E6%96%B9) 


#### Assignee
 - Assignee とは issue の機能の一つで、issue の担当者を登録できる機能です
 - ncxx-sl-lab/helpdesk の Collaborators に登録済み方が Assignee の対象者です 
 - Collaborators とは ncxx-sl-lab/helpdesk の協同管理者のことです
 - Collaborators の登録は このリポジトリの作成者が可能です
 - 回答担当者は事前に登録しておきましたのでご確認よろしくお願いします

#### [ZenHub](https://www.zenhub.io/)
- まず回答担当者の方は[ZenHub](https://www.zenhub.io/)をインストールしてください。
- [ZenHub](https://www.zenhub.io/)は Google Chrome の拡張機能で GitHub の issue をカンバン方式に機能拡張します
- また[ZenHub](https://www.zenhub.io/)をインストールするとissueに画像などの貼り付けが簡単に出来るようになります
- [ZenHub](https://www.zenhub.io/)を利用すれば、質疑応答の進捗状況が簡単かつわかりやすく表示できます
- 質疑応答の進捗状況については下記のヘルプデスク対応マニュアルに記載してあります
- [ZenHub](https://www.zenhub.io/)の詳しい情報は下記のQiita記事を参照
 - http://qiita.com/GeckoTang/items/f75b9a1c20c8e5091147 

## ◆ ヘルプデスク対応マニュアル
#### issue で質疑応答を管理
- 社員（質問者）からの質問は issue で管理 

#### 質問者の名前は記載不要
- 誰からの質問かは記載不要

#### 回答担当者の名前は記載する
- 各週によって回答者は変更されるし、issue のソートをしやすくするために登録が必要
- 回答者は issue の Assignee を利用して登録すること

#### 質疑応答の進捗状況は[ZenHub](https://www.zenhub.io/)で確認
- 進捗状況は [ZenHub](https://www.zenhub.io/)　で機能追加でした issue の Pipleine で管理します
- Piplineのは以下の5つに分類します
- **受付**：質問を issue に登録して、適切な Label（下記の後述）も登録した状態
- **対応中**：作成した issue の Assignee に回答の担当者を登録した状態
- **応答待ち**：担当者が回答をまとめて社員（質問者）に連絡して返答待ちの状態
- **Closed**：社員（質問者）から了承の連絡があった際、issue を open から closed に変更する
- **保留**：何らかの理由により質問を解決できない状態
- 流れは**受付**→**対応中**→**応答待ち**→**Closed**
- 場合によっては**対応中**↔**応答待ち**を質問が往来することもあるでしょう

#### 質問の種別はシンプルに Labels で分類
- 現状では、スマホ端末／PC環境／開発言語／その他、の4種類の Label で対応可能

#### issue の書き方
- issueのひな形は下記の画像を参照  
![画像](http://keepingblog.net/github_images/helpdesk/issue_fmt.png)

- **質問の内容**には、質問者のメール文面を要約して記述すること
- **何が問題なのか**には、問題の原因を分かり易く記述すること
- 回答までの経緯（質問への新たな情報や対応etc）は issue のコメントに随時追加すること
- 画像や参考サイトのURLなど少しでも役立ちそうな情報は遠慮せずに記述すること
- **解決方法**には、問題の原因や解決方法について記述すること
- **今後の対応**には、解決できなかった問題への対応策を記述すること
