# Kanon Cloud Sync

## English

Public website repository for **Kanon Cloud Sync**, a personal cloud synchronization setup used by its owner.

This repository publishes the public application information and privacy policy used for Google OAuth configuration.

### Website

- Homepage: https://oauth.kanon3574.bid/
- Privacy Policy: https://oauth.kanon3574.bid/privacy.html

### Purpose

Kanon Cloud Sync is used for personal file synchronization and backup between services such as Google Drive and Microsoft OneDrive, and for uploading selected images from the owner's personal archive to Google Photos.

This repository contains only the small public-facing static website used to describe that purpose and publish the privacy policy.

### Relationship to the Cloud Sync project

This repository is the **public companion repository** for the Kanon Cloud Sync project. The private operations repository remains canonical for synchronization code, automation, configuration snapshots, and internal operational documentation. This public repository is canonical only for the OAuth-facing website, Privacy Policy, GitHub Pages, and custom-domain content.

Review or update this repository when public OAuth-facing information changes, such as the application purpose description, Privacy Policy, public URL/CNAME, or wording needed for Google OAuth configuration/review. Internal implementation-only changes do not require a website update.

### Repository contents

- `index.html` — public application homepage
- `privacy.html` — privacy policy
- `CNAME` — custom domain configuration for GitHub Pages
- `.nojekyll` — serves the repository as a plain static site
- `404.html` — fallback page for unknown paths

### What is not stored here

This repository does **not** contain the synchronization scripts, OAuth client secrets, access or refresh tokens, local state databases, file inventories, image archives, or other private operational data.

The implementation source code is maintained separately in a private repository.

### Hosting

The site is hosted with GitHub Pages and a custom domain.

### Usage

This application and website are intended for personal use by the owner and are not offered as a public synchronization service.

---

## 日本語訳

**Kanon Cloud Sync** の公開Webサイト用リポジトリです。

Kanon Cloud Syncは、所有者本人が個人利用するクラウド同期・バックアップ環境です。

このリポジトリでは、Google OAuth設定で使用する公開アプリ情報とPrivacy Policyを掲載しています。

### Webサイト

- Homepage: https://oauth.kanon3574.bid/
- Privacy Policy: https://oauth.kanon3574.bid/privacy.html

### 用途

Kanon Cloud Syncは、Google DriveとMicrosoft OneDriveなどの間で個人ファイルの同期・バックアップを行い、所有者の個人アーカイブから選択した画像をGoogle Photosへアップロードするために使用しています。

このリポジトリに含まれるのは、その用途を説明しPrivacy Policyを公開するための、小規模な公開静的Webサイトだけです。

### Cloud Syncプロジェクトとの関係

このリポジトリは、Kanon Cloud Syncプロジェクトの **公開用companion repository** です。同期スクリプト、自動化、設定snapshot、内部の運用ドキュメントは別のPrivate運用リポジトリを正本とし、このPublicリポジトリはOAuth向けWebサイト、Privacy Policy、GitHub Pages、custom domainの公開内容だけを正本として扱います。

アプリ用途説明、Privacy Policy、公開URL/CNAME、Google OAuth設定・審査に必要な公開文言などが変わる場合は、このリポジトリも確認・更新します。内部実装だけの変更ではWebサイト更新は不要です。

### リポジトリの内容

- `index.html` — 公開アプリのホームページ
- `privacy.html` — Privacy Policy
- `CNAME` — GitHub Pagesのカスタムドメイン設定
- `.nojekyll` — Jekyllを使用せず静的サイトとして配信するための設定
- `404.html` — 存在しないURLへアクセスした場合の案内ページ

### このリポジトリに保存しないもの

このPublicリポジトリには、次のような非公開情報・運用データは保存しません。

- 実際の同期・自動化スクリプト
- OAuth Client Secret
- access token / refresh token
- ローカルstateデータ
- ファイル一覧・ハッシュ台帳
- 画像アーカイブ
- その他の個人用運用データ

実際の処理コードは、別のPrivateリポジトリで管理しています。

### ホスティング

このサイトはGitHub Pagesとカスタムドメインを使用して公開しています。

### 利用範囲

このアプリケーションとWebサイトは所有者本人の個人利用を目的としており、一般向けの公開クラウド同期サービスとして提供しているものではありません。
