# ビジネス向け AI エージェント書籍の練習ファイル

書籍「Codexでつくる仕事の手順」と「Claude Codeでつくる仕事の手順」で使う、架空の業務教材です。2冊はそれぞれ単独で進められます。実在の顧客、取引、業績は含みません。

| 読んでいる本 | 使うフォルダ |
| --- | --- |
| Codex版 | `codex/` |
| Claude Code版 | `claude-code/` |

## ダウンロード

GitHubのページで **Code → Download ZIP** を選び、ZIPファイルを展開してください。使用する本のフォルダだけを作業場所として選びます。コマンド入力やGitの操作は不要です。

各版には`weekly-report/`、`choice-memo/`、`meeting-followup/`、`cross-role/`があります。それぞれに入力資料、依頼文、継続する仕事のルール、出力先の`output/`を用意しています。取得後にフォルダを作ったり資料をコピーしたりする必要はありません。まず該当する製品別READMEを読んでください。

## 演習の入口

読んでいる本に合わせ、以下の`{版}`を`codex`または`claude-code`に置き換えてください。各演習は新しい会話で始め、依頼文を入力します。成果物は選んだ作業フォルダの`output/`に保存します。

| 演習 | 作業フォルダ | 依頼文 |
| --- | --- | --- |
| CASE01 週次報告 | `{版}/weekly-report/` | `prompts/request-week-1.txt`、`request-week-2.txt` |
| CASE02 比較メモ | `{版}/choice-memo/` | `prompts/request.txt` |
| CASE03 商品企画 | `{版}/cross-role/` | `prompts/product-concept-request.txt` |
| CASE04 説明サイト | `{版}/cross-role/` | `prompts/explanation-site-request.txt` |
| CASE05 会議後の対応表 | `{版}/meeting-followup/` | `prompts/request.txt` |
| CASE06 返信案 | `{版}/cross-role/` | `prompts/email-reply-request.txt` |
| CASE07 顧客向け提案 | `{版}/cross-role/` | `prompts/technical-proposal-request.txt` |
| CASE08 技術チーム向け要件 | `{版}/cross-role/` | `prompts/customer-requirements-request.txt` |
| CASE09 企画書の骨子 | `{版}/cross-role/` | `prompts/research-plan-request.txt` |
| CASE10 スライド案 | `{版}/cross-role/` | `prompts/slide-story-request.txt` |
| CASE11 週明けリスト | `{版}/cross-role/` | `prompts/friday-list-request.txt` |
| CASE12 朝の確認メモ | `{版}/cross-role/` | `prompts/daily-briefing-request.txt` |
| CASE13 週次レビュー | `{版}/weekly-report/` | `prompts/weekly-review-request.txt` |
| CASE14 学習課題 | `{版}/cross-role/` | `prompts/career-learning-request.txt` |
| CASE15 強みの棚卸し | `{版}/cross-role/` | `prompts/strengths-inventory-request.txt` |

CASE04はCASE03の企画案、CASE10はCASE09の骨子、CASE13はCASE01の二週分の報告を使います。先に対応する演習を済ませてください。

`answer-key/`は著者作成の完成見本と誤り探し用の文書です。CodexまたはClaude Codeに指定する作業フォルダの外に置いてあります。自分の出力を確認する段階で開いてください。完成見本は両製品の実行結果ではありません。

この教材の操作手順は書籍の先行章に対応します。アプリの画面や指示ファイルの読み込み動作は出版前に確認中です。画面の表示が書籍と違うときは、現在のアプリで作業場所と権限の確認を優先してください。
