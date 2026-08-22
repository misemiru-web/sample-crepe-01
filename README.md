# sample-crepe-01

架空のクレープ店「Crepe Sample 01」のランディングページ（公開用の制作サンプル）を管理するリポジトリです。コード、Git設定から確認できる事実を記録し、業務状態や公開状態が未確認の項目は `要確認` としています。

## 1. 基本情報・現在の状態

- 案件名: sample-crepe-01（匿名化済みの架空制作サンプル）
- 内容: 猫モチーフのクレープ店を想定した、店舗情報を掲載する静的ランディングページ
- robots設定: `noindex, nofollow`
- 現在の契約・制作・承認・公開・保守状態: 要確認
- README最終更新日: 2026-08-22

このリポジトリは、実在店舗を掲載していた別リポジトリを元に、店名・住所・電話・SNS・地図・営業時間・価格・メニュー等の実店舗固有情報を匿名化し、新規Git履歴で作成した制作サンプルです。旧リポジトリの履歴は引き継いでいません。

## 2. Repository

- GitHub: https://github.com/misemiru-web/sample-crepe-01
- 基準branch: `main`
- 公開済み安定版を示すcommit / tag: 要確認

## 3. 技術構成

- HTML / CSS / JavaScript
- CSSとJavaScriptは `index.html` 内に記述
- package manager: なし
- `package.json`: なし
- Node.js指定: なし
- 専用build工程: なし

## 4. セットアップ・確認方法

依存関係のインストールは不要です。専用の開発起動・buildコマンドはありません。ルートの `index.html` と関連アセットを静的サイトとして確認します。

### Build

- buildコマンド: なし
- build出力先: なし

存在しないnpmコマンドを追加・実行しないでください。

## 5. 主な構成と更新箇所

- `index.html`: 店舗情報、メニュー、本文、スタイル、JavaScript、主要リンク
- `assets/cat/`: 猫関連素材
- `assets/decorative/`: 装飾素材
- `assets/icons/`: アイコン
- `assets/images/`: サイトで実際に使用している画像
- `assets/logo/`: ロゴ素材
- `assets/menu/`: メニュー画像
- `assets/titles/`: 見出し素材
- `assets/ui/`: UI素材

単一HTML内にCSSとJavaScriptもあるため、小さな変更でもページ全体への副作用を確認し、一括整形を避けます。

## 6. 外部サービス・フォーム・解析

- Google Fonts
- リポジトリ内で送信処理を持つフォーム: なし
- Instagramと表示されるボタンは `#news` への内部リンクです（外部URLは設定していません）
- Search Console / GA4等の計測タグ: なし

## 7. SEO

- `title`、description、robots等は `index.html` で管理
- 現在のrobots: `noindex, nofollow`（サンプルのため検索対象外）
- canonical: 未設定

## 8. 公開・ホスティング・ドメイン

- 公開方法: GitHub Pages（`main` / root）
- 独自ドメイン: なし
- 正式な公開URL: https://misemiru-web.github.io/sample-crepe-01/

## 9. 匿名化について

- 実在店舗名・表記揺れ、実在の地名・住所・駅名・電話・SNS・地図・営業時間・価格・メニュー等の実店舗固有情報は、架空の情報を新たに作らず「サンプルのため非掲載」等の一般表記に置き換えています。
- ロゴおよび画像内に写り込んでいた実店舗名・看板テキストは、汎用素材への差し替え、または画像編集によるテキスト除去で対応しています。
- デザイン・配色・レイアウトは元の制作サンプルを可能な限り維持しています。

## 10. 認証情報

パスワード、APIキー、秘密トークン、個人情報をREADMEやGitへ保存しないでください。
