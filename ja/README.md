# ビジネス向け AI エージェント書籍の練習ファイル

書籍「Codexでつくる仕事の手順」と「Claude Codeでつくる仕事の手順」で使う、架空の業務教材と個人向けの練習教材です。2冊はそれぞれ単独で進められます。実在の顧客、取引、業績は含みません。

| 読んでいる本 | 使うフォルダ |
| --- | --- |
| Codex版 | `codex/` |
| Claude Code版 | `claude-code/` |

## ダウンロード

GitHubのページで **Code → Download ZIP** を選び、ZIPファイルを展開してください。使用する本のフォルダだけを作業場所として選びます。コマンド入力やGitの操作は不要です。

各版には`personal-practice/`と、業務用の`weekly-report/`、`choice-memo/`、`meeting-followup/`、`cross-role/`があります。入力資料、依頼文、出力先の`output/`を用意し、業務用フォルダには継続する仕事のルールも置いています。配布教材を使う演習では、取得後に入力資料や出力フォルダを作る必要はありません。本文だけの入門演習では、本文で指定された空の練習フォルダを用意します。まず該当する製品別READMEを読んでください。

## 版ごとの演習の入口

Codex版は追加演習を含む24演習です。[Codex版の一覧](codex/README.md)を使ってください。以下の22演習の表はClaude Code版の案内です。保存先・前提演習・戻し方は[Claude Code版の一覧](claude-code/README.md)を参照してください。両版の演習番号は一致しません。

### Claude Code版の演習

以下の`{版}`は`claude-code`です。各演習は新しい会話で始め、依頼文を入力します。本文のメモで試す演習は、まず回答を会話で確かめます。配布教材を使う応用演習の成果物は、選んだ作業フォルダの`output/`に保存します。

| 演習 | 作業場所・入力 | 依頼文 |
| --- | --- | --- |
| 演習01 会議案内 | 本文のメモ | 本文の依頼 |
| 演習02 資料とルールの保存 | 本文のメモ・専用の練習フォルダ | 本文の依頼 |
| 演習03 活動メモの要約 | 本文のメモ | 本文の依頼 |
| 演習04 週次報告 | `{版}/weekly-report/` | `prompts/request-week-1.txt`、`prompts/request-week-2.txt` |
| 演習05 比較メモ | `{版}/choice-memo/` | `prompts/request.txt` |
| 演習06 アイデア3案 | 本文のメモ | 本文の依頼 |
| 演習07 商品企画 | `{版}/cross-role/` | `prompts/product-concept-request.txt` |
| 演習08 説明サイト | `{版}/cross-role/` | `prompts/explanation-site-request.txt` |
| 演習09 一通の返信 | 本文のメモ | 本文の依頼 |
| 演習10 会議後の対応表 | `{版}/meeting-followup/` | `prompts/request.txt` |
| 演習11 複数メールの返信・保留 | `{版}/cross-role/` | `prompts/email-reply-request.txt` |
| 演習12 専門説明の書き直し | 本文のメモ | 本文の依頼 |
| 演習13 顧客向け提案 | `{版}/cross-role/` | `prompts/technical-proposal-request.txt` |
| 演習14 要件メモ | `{版}/cross-role/` | `prompts/customer-requirements-request.txt` |
| 演習15 企画書の骨子 | `{版}/cross-role/` | `prompts/research-plan-request.txt` |
| 演習16 スライド案 | `{版}/cross-role/` | `prompts/slide-story-request.txt` |
| 演習17 作業メモの一覧化 | 本文のメモ | 本文の依頼 |
| 演習18 週明けリスト | `{版}/cross-role/` | `prompts/friday-list-request.txt`、`prompts/friday-skill-create.txt`、`prompts/friday-list-next-request.txt` |
| 演習19 朝の確認メモ | `{版}/cross-role/` | `prompts/daily-briefing-request.txt` |
| 演習20 週次振り返り | `{版}/weekly-report/` | `prompts/weekly-review-request.txt` |
| 演習21 学習課題 | `{版}/cross-role/` | `prompts/career-learning-request.txt` |
| 演習22 強みの棚卸し | `{版}/cross-role/` | `prompts/strengths-inventory-request.txt` |

演習08は07の企画案、演習16は15の骨子、演習20は04の二週分の報告を使います。先に対応する演習を済ませてください。入門2件と基本5件は教材取得なしで進められます。

## 個人の文章・制作記録で試す追加練習

以下の演習番号はClaude Code版です。Codex版の対応番号は[Codex版の案内](codex/README.md#個人向けの追加練習)を参照してください。

任意の追加練習です。文章と語学復習は本文の短い入力でも試せます。収納比較、作品紹介、手順再利用は配布教材を使います。ファイル保存と再利用まで試す場合は、業務フォルダとは別に`{版}/personal-practice/`を選んでください。

| 本文の位置 | 入力 | 依頼文 |
| --- | --- | --- |
| 演習02 編集ルール | `sample-writing.txt`、`new-note.txt` | `voice-request.txt`、`voice-correction.txt` |
| 演習12 体験文 | `experience.txt` | `article-request.txt`、`article-correction.txt` |
| 演習12 長い記事（任意） | `experience.txt` | `article-long-request.txt` |
| 演習22 強みと次の行動 | `personal-evidence.txt` | `strengths-request.txt`、`strengths-correction.txt` |
| 演習05 収納用品の比較 | `household-conditions.txt`、`shelves.csv` | `shelf-request.txt`、`shelf-correction.txt` |
| 演習08 作品紹介ページ | `works.txt` | `gallery-request.txt`、`gallery-correction.txt` |
| 演習20 手順の再利用 | `learning-log-a.txt`、`learning-log-b.txt`、`learning-review-rules.txt` | `review-a-request.txt`、`review-procedure-request.txt`、`review-procedure-correction.txt`、`review-b-request.txt` |
| 演習21 学習の復習 | `study-notes.txt` | `study-request.txt`、`study-correction.txt` |


入力は`input/`、依頼は`prompts/`にあります。短い体験文と強みの依頼には、本文と同じ架空の材料が含まれています。七つの追加練習はそれぞれ独立して試せます。見本と意図的な誤り例は`answer-key/personal-practice/`にあり、AIへ渡す作業場所には含めません。

`answer-key/`は著者作成の完成見本と誤り探し用の文書です。CodexまたはClaude Codeに指定する作業フォルダの外に置いてあります。自分の出力を確認する段階で開いてください。完成見本は両製品の実行結果ではありません。

この教材の操作手順は書籍の先行章に対応します。アプリの画面や指示ファイルの読み込み動作は出版前に確認中です。画面の表示が書籍と違うときは、現在のアプリで作業場所と権限の確認を優先してください。
