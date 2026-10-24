# Codex版の練習

2026年10月23日整備。Codex版の24演習に対応します。教材の内容照合と、Codexアプリでの全操作の実機確認は別です。実機確認は完了していません。

## 始め方

GitHubで **Code → Download ZIP** を選んで展開し、`ja/codex/`を開きます。以下の表で指定する業務フォルダ一つを、CodexのローカルProjectの主フォルダに選びます。リポジトリ全体や`ja/`を作業場所にせず、確認用見本の`ja/answer-key/`を作業場所に含めません。コマンド入力やGit操作は不要です。

`input/`は資料、`prompts/`は依頼文、`output/`は保存先です。`output/`が空に見えるのは正常です。依頼文を開いて読み、新しいチャットへ貼り付けます。計画を確認する依頼では、入力と保存先を読んでから作成を頼みます。保存後はファイルを開き、元資料と照合してください。

本文だけの演習01・02・05・08・11・14・19は、Projectに属さない新しいチャットで始めます。演習03は空の「案内ルール練習」フォルダでProjectを作り、演習04も同じProjectを使います。この二つの資料と指示は本文に沿って作るため、完成済みのAGENTS.mdを配布しません。

## 24演習の入口

依頼文のファイルは、指定フォルダの`prompts/`にあります。業務演習の成果物は原則として同じフォルダの`output/`へ保存します。

| 演習 | 作業場所 | 依頼文 | 確認する成果物 |
| --- | --- | --- | --- |
| 演習01 短い会議案内で依頼の工夫を試す | 本文 | 本文 | 会話の案内 |
| 演習02 仕事のメモから依頼文を組み立てる | 本文 | 本文 | 会話の依頼文 |
| 演習03 会議案内の資料とルールを残す | 案内ルール練習 | 本文 | AGENTS.md・meeting-note.txt |
| 演習04 確認した会議情報を残し、別の会話で続ける | 案内ルール練習 | 本文 | meeting-state.mdと再開後の案内 |
| 演習05 活動メモを3項目にまとめる | 本文 | 本文 | 会話の3項目要約 |
| 演習06 週次報告から次の打ち手を考える | weekly-report | request-week-1.txt / request-week-2.txt | week-1-report.txt / week-2-report.txt |
| 演習07 比較資料から選定条件を示す | choice-memo | request.txt | choice-memo.txt |
| 演習08 困りごとからアイデアを3案出す | 本文 | 本文 | 会話の3案 |
| 演習09 顧客の声から新商品を企画する | cross-role | product-concept-request.txt | product-concept.txt |
| 演習10 企画を説明する小さなサイトを作る | cross-role | explanation-site-request.txt | site/index.html |
| 演習11 一通のメールに返信下書きを作る | 本文 | 本文 | 会話の返信下書き |
| 演習12 会議メモを実行タスクに変える | meeting-followup | request.txt | followup.txt |
| 演習13 受信メールから返信案を用意する | cross-role | email-reply-request.txt | reply-drafts.txt |
| 演習14 専門的な説明を相手に合わせて書き直す | 本文 | 本文 | 会話の書き直し |
| 演習15 技術資料を顧客向け提案に変える | cross-role | technical-proposal-request.txt | customer-proposal.txt |
| 演習16 顧客の要望を技術チームへ渡す | cross-role | customer-requirements-request.txt | requirements-note.txt |
| 演習17 調査資料から企画書の骨子を作る | cross-role | research-plan-request.txt | plan-outline.txt |
| 演習18 提案を説明する筋道を作る | cross-role | slide-story-request.txt | slide-story.txt |
| 演習19 作業メモをやること一覧にする | 本文 | 本文 | 会話の作業一覧 |
| 演習20 週明けリストを作り、次回も使える手順にする | cross-role | friday-list-request.txt / friday-skill-create.txt / friday-list-next-request.txt | monday-start.txt / monday-next.txtとスキル |
| 演習21 毎朝の確認事項をまとめる | cross-role | daily-briefing-request.txt | daily-briefing.txt |
| 演習22 一週間の進捗を振り返る | weekly-report | weekly-review-request.txt | weekly-review.txt |
| 演習23 経験から次の学習課題を考える | cross-role | career-learning-request.txt | career-learning.txt |
| 演習24 強みを成果物から棚卸しする | cross-role | strengths-inventory-request.txt | strengths-inventory.txt |

## 先に作る成果物

- 演習04：演習03の`AGENTS.md`と`meeting-note.txt`を使い、状態を保存してから別のチャットで再開します。
- 演習10：演習09の`output/product-concept.txt`を使います。保存後に`output/site/index.html`をブラウザーで開き、表示と未確定事項を確認します。外部公開は行いません。
- 演習18：演習17の`output/plan-outline.txt`を使います。
- 演習20：最初のリストを確認し、同じ会話でスキルを作成します。保存候補は`.agents/skills/next-week-list/SKILL.md`です。本文の操作に従い、新しいチャットで呼び出して`input/next-week-close.txt`へ適用します。10月19日14時の会議、回答済みの料金と提供時期、回答待ちの編集権限を照合します。呼び出しを確認できなければ、スキル利用は未確認として残します。
- 演習22：演習06で作った二週分の報告と元資料を使います。
- 演習24：`cross-role/output/`の作成済み成果物三つを選び、依頼文末尾へファイル名、本人が判断・訂正した点と理由、借りた助けを記入します。判断の記録がなければ「未記録」と答えます。未記入やファイル不足があれば質問で止まり、回答後に保存します。

演習21は教材の2026年10月12日を対象とする手動練習です。現在の予定を取得する操作や、定期実行の登録は含みません。演習13も架空の受信メールファイルを使い、実際のメールサービスには接続しません。

## 個人向けの追加練習

業務用とは別の`personal-practice/`を使います。対応する演習は03（編集ルール）、07（収納比較）、10（作品紹介）、14（体験文）、22（手順再利用）、23（復習）、24（強み）です。依頼文は[個人練習の案内](personal-practice/README.md)を参照してください。

## うまく進まないとき

作業場所が違う場合は、依頼を送る前にProjectの主フォルダを選び直します。成果物が見つからない場合は保存先を表示させ、選択中のフォルダと照合します。既存の成果物を再検証するときは別名で保存し、元資料を変更した場合は新しく展開したZIPから入力だけを戻します。見本は出力を作ってから開き、文章の一致より数値、根拠、未確認事項を確認してください。スキル案は確認用テキストであり、自動登録されません。

週明けリストのスキルは、`cross-role/prompts/friday-skill-location.txt` で保存候補を表示させ、練習フォルダ内であることを確認してから `friday-skill-create.txt` で作成を依頼します。日付は教材内の架空の日付として扱います。
