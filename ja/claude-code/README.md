# Claude Code版の練習

2026年10月23日整備。Claude Code版の22演習に対応します。教材の内容照合は行っていますが、Claudeアプリでの実行確認は行っていません。

## 始め方

GitHubで **Code → Download ZIP** を選んで展開し、`ja/claude-code/`を開きます。本文に従ってClaude DesktopのCode画面でLocalを選び、以下の表で指定する作業フォルダ一つを選びます。リポジトリ全体や`ja/`を作業場所にせず、確認用見本の`ja/answer-key/`を含めません。コマンド入力やGit操作は不要です。

`input/`は入力資料、`prompts/`は依頼文、`output/`は保存先です。`output/`が空に見えるのは正常です。依頼文を読み、新しいセッションへ貼り付けます。計画の確認が必要な演習では、本文に従い入力と保存先を確認してから作成を頼みます。保存後はOSでファイルを開き、元資料と照合します。

演習01は空の「案内練習」、演習02は空の「案内ルール練習」、基本演習03・06・09・12・17は空の「基本練習」フォルダをOSで用意します。これらの主課題は本文の材料で進めるため、配布教材は不要です。演習02の資料とAGENTS.mdも本文に沿って作り、新しいセッションで利用します。完成済みの指示ファイルは追加しません。

## 22演習の入口

依頼文は指定フォルダの`prompts/`にあります。業務演習の成果物は同じフォルダの`output/`へ保存します。スキルの保存候補だけは後述の別の場所です。

| 演習 | 作業場所 | 依頼文 | 確認する成果物 |
| --- | --- | --- | --- |
| 演習01 短い会議案内で依頼の工夫を試す | 案内練習（空） | 本文 | 会話の案内 |
| 演習02 会議案内の資料とルールを残す | 案内ルール練習 | 本文 | AGENTS.md・meeting-note.txt・新しいセッションの案内 |
| 演習03 活動メモを3項目にまとめる | 基本練習（空） | 本文 | 会話の3項目要約 |
| 演習04 週次報告から次の打ち手を考える | weekly-report | request-week-1.txt / request-week-2.txt | week-1-report.txt / week-2-report.txt |
| 演習05 比較資料から選定条件を示す | choice-memo | request.txt | choice-memo.txt |
| 演習06 困りごとからアイデアを3案出す | 基本練習（空） | 本文 | 会話の3案 |
| 演習07 顧客の声から新商品を企画する | cross-role | product-concept-request.txt | product-concept.txt |
| 演習08 企画を説明する小さなサイトを作る | cross-role | explanation-site-request.txt | site/index.html |
| 演習09 一通のメールに返信下書きを作る | 基本練習（空） | 本文 | 会話の返信下書き |
| 演習10 会議メモを実行タスクに変える | meeting-followup | request.txt | followup.txt |
| 演習11 受信メールから返信案を用意する | cross-role | email-reply-request.txt | reply-drafts.txt |
| 演習12 専門的な説明を相手に合わせて書き直す | 基本練習（空） | 本文 | 会話の書き直し |
| 演習13 技術資料を顧客向け提案に変える | cross-role | technical-proposal-request.txt | customer-proposal.txt |
| 演習14 顧客の要望を技術チームへ渡す | cross-role | customer-requirements-request.txt | requirements-note.txt |
| 演習15 調査資料から企画書の骨子を作る | cross-role | research-plan-request.txt | plan-outline.txt |
| 演習16 提案を説明する筋道を作る | cross-role | slide-story-request.txt | slide-story.txt |
| 演習17 作業メモをやること一覧にする | 基本練習（空） | 本文 | 会話の作業一覧 |
| 演習18 週明けリストを作り、次回も使える手順にする | cross-role | friday-list-request.txt / friday-skill-create.txt / friday-list-next-request.txt | monday-start.txt / monday-next.txtとスキル |
| 演習19 毎朝の確認事項をまとめる | cross-role | daily-briefing-request.txt | daily-briefing.txt |
| 演習20 一週間の進捗を振り返る | weekly-report | weekly-review-request.txt | weekly-review.txt |
| 演習21 経験から次の学習課題を考える | cross-role | career-learning-request.txt | career-learning.txt |
| 演習22 強みを成果物から棚卸しする | cross-role | strengths-inventory-request.txt | strengths-inventory.txt |

## 前提となる成果物と入力

- 演習04の2週目は、前週比の計算に`input/week-1.csv`も使います。1週目の報告は残します。
- 演習08：演習07の`output/product-concept.txt`と`input/product-brief.txt`を使います。保存後に`output/site/index.html`をブラウザーで開きます。外部公開はしません。
- 演習16：演習15の`output/plan-outline.txt`を使います。
- 演習18：最初のリストを確認してから、同じセッションで訂正を含むスキル作成を依頼します。翌週は同じ作業フォルダの新しいセッションで再利用します。詳しくは[cross-roleの案内](cross-role/README.md)を参照してください。
- 演習20：演習04で作った`output/week-1-report.txt`と`output/week-2-report.txt`、二週分のCSV・メモを使います。
- 演習22：`cross-role/output/`の作成済み成果物三つを選び、依頼文末尾へファイル名、本人が判断・訂正した点と理由、借りた助けを記入します。判断の記録がなければ「未記録」と答えます。未記入やファイル不足があれば質問で止まり、回答後に保存します。

演習19は教材の2026年10月12日を対象とする手動練習です。現在の予定取得や定期実行の登録は含みません。演習11も架空の受信メールを使い、メールサービスへ接続・送信しません。

## 個人向けの追加練習

業務用とは別の`personal-practice/`を使います。対応する演習は02（編集ルール）、05（収納比較）、08（作品紹介）、12（体験文）、20（手順再利用）、21（復習）、22（強み）です。[個人練習の案内](personal-practice/README.md)で入力と依頼文を確認してください。本文だけで試せる短い入力もあります。

## 確認と戻し方

完成後に[確認用見本の一覧](../answer-key/README.md)を開きます。見本は著者作成で、Claude Codeの実行結果ではありません。独立した見本ファイルがない演習は、本文と一覧の確認条件を使います。文章の一致より数値、根拠、未確認事項を照合します。

作業場所が違う場合は依頼を送る前に選び直します。成果物が見つからなければ保存先を表示させ、選択中のフォルダと比べます。既存の成果物を再確認するときは別名で保存し、入力を変更した場合は新しく展開したZIPから入力だけを戻します。AGENTS.mdは継続ルールの文案です。読み込み・保存・スキル利用の動作は未確認として区別してください。

週明けリストのスキルは、`cross-role/prompts/friday-skill-location.txt` で保存候補を表示させ、練習フォルダ内であることを確認してから `friday-skill-create.txt` で作成を依頼します。日付は教材内の架空の日付として扱います。
