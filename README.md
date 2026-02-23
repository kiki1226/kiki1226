# Portfolio（kiki1226）

## What（できること）
LaravelでWebアプリ開発（認証/CRUD/DB設計/画像/テスト）を学習・開発しています。
Docker（Nginx + PHP + MySQL）環境で動作させ、READMEに手順もまとめています。

## Works（制作物）
### 勤怠管理アプリ
- Repo： https://github.com/kiki1226/kintai
- 概要：出退勤・休憩・申請/承認・月次集計まで行える勤怠管理アプリ
- 主な機能：
  - 出勤/退勤の打刻、休憩開始/終了
  - 休憩時間・合計時間（HH:MM）の自動計算、勤怠一覧表示
  - 申請（例：休暇/修正など）〜承認フロー
  - 月次集計（勤務時間の集計）
  - テスト（Featureテスト / 回帰テスト）
- 使用技術：Laravel / PHP / MySQL / Docker（Nginx + PHP + MySQL）/ PHPUnit / Laravel Dusk

### フリマアプリ
- Repo： https://github.com/kiki1226/coachtech-flema
- 概要：商品一覧→詳細→購入までの導線を備えたフリマアプリ（MVP）
- 主な機能：
  - 会員登録/ログイン、メール認証、初回プロフィール設定
  - 商品一覧/詳細、検索
  - いいね（マイリスト）、コメント
  - 出品（画像アップロード、編集、削除）
  - 購入フロー（住所入力、支払い方法選択、決済）
- 使用技術：Laravel / PHP / MySQL / Docker / Fortify（認証）/ Stripe（決済）

### ジム予約管理アプリ（ミニ版）
- Repo： https://github.com/kiki1226/asset-crud
- 概要：会員・トレーナー・予約を管理できるCRUDミニアプリ
- 主な機能：
  - 会員／トレーナー／予約の一覧・登録・編集・削除
  - 予約のキャンセル（キャンセル済み表示の切り替え）
  - 検索（キーワードで絞り込み）
  - ローディング表示／エラー表示
- 使用技術：React（フロント） / Node.js（API）
