# 職種を越える仕事の練習

第4〜8章の新商品企画、説明サイト、返信案などの演習で使います。Claude DesktopのCode画面でこの`cross-role/`を業務フォルダに選びます。入力は`input/`、完成物は`output/`に置きます。主要な演習の依頼文は`prompts/product-concept-request.txt`などにあります。演習ごとに新しいセッションを始め、本文に示した成果物と確認条件を指定してください。`AGENTS.md`は継続ルールの文案です。公開、メール送信、実在データの入力は行いません。週次レビューの演習では別の`weekly-report/`を使います。

## 演習18：週明けリストとスキル

1. `input/week-close.txt`と`prompts/friday-list-request.txt`で`output/monday-start.txt`を作り、月曜10時の会議と確認待ちの条件を照合します。
2. 同じセッションで、本文にある保存候補`.claude/skills/next-week-list/SKILL.md`を確認してから`prompts/friday-skill-create.txt`を使います。初回の訂正も手順へ含め、日付や案件の状態を固定しません。
3. 同じ作業フォルダの新しいセッションで、本文の手順でスキルを呼び出し、`prompts/friday-list-next-request.txt`を添えます。入力は`input/next-week-close.txt`、保存先は`output/monday-next.txt`です。
4. 対象日2026年10月19日、会議14時、料金と提供時期は回答済み、編集権限は回答待ちと照合します。期限や公開日を補っていたら本文の手順で訂正し、`output/monday-next-recheck.txt`へ別名で再確認します。

確認用見本は作業場所の外の`ja/answer-key/cross-role/`にある`monday-start.txt`、`monday-next.txt`、`next-week-list-skill.txt`です。スキル案は照合用テキストであり、自動登録しません。呼び出せたか不明なら、結果ができてもスキル利用は未確認です。今回は教材を準備しただけで、アプリでの作成・保存・探索・呼び出し・再利用は確認していません。
