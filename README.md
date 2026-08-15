# Rinkaku Support

ここは、ブラウザー上の動画を WebGPU で高画質化する Chrome 拡張 **Rinkaku（輪郭）** の公開サポート窓口です。

- [不具合を報告する](https://github.com/1llum1n4t1s/Rinkaku-Support/issues/new?template=bug_report.yml)
- [機能を提案する](https://github.com/1llum1n4t1s/Rinkaku-Support/issues/new?template=feature_request.yml)
- [使い方について質問する](https://github.com/1llum1n4t1s/Rinkaku-Support/issues/new?template=question.yml)
- [既存の Issue を確認する](https://github.com/1llum1n4t1s/Rinkaku-Support/issues)
- [プライバシーポリシー](PRIVACY.md)

Rinkaku のソースコードは非公開です。このリポジトリでは、不具合報告、機能要望、使い方に関する質問を受け付けています。コード変更の Pull Request は受け付けていません。

## 投稿前の確認

1. [既存の Issue](https://github.com/1llum1n4t1s/Rinkaku-Support/issues) に同じ内容がないか確認してください。
2. `chrome://extensions` の Rinkaku 詳細画面で、使用中のバージョンを確認してください。
3. 不具合の場合は、可能であれば再現手順、期待していた動作、対象サイト、映像モードと強度を記載してください。
4. 画質や速度の問題では、GPU 名と `chrome://gpu` に表示される WebGPU の状態が分かると調査しやすくなります。レポート全体ではなく、必要な項目だけを共有してください。
5. 画像を添付する場合は、個人情報、認証情報、公開したくない動画内容が映っていないことを確認してください。

## 公開しない情報

Issue はインターネット上で誰でも閲覧できます。次の情報は投稿しないでください。

- 購入時のメールアドレス、6 桁の確認コード、購入 ID、署名済み credential
- パスワード、Cookie、アクセストークンなどの認証情報
- 公開したくない動画 URL、閲覧履歴、検索語、ページ内容
- 個人名、住所、ユーザー名、端末内のファイルパスなどの個人情報
- 人物や私的な映像、個人情報が映り込んだスクリーンショット
- `chrome://gpu` や開発者ツールから得た情報のうち、調査に不要な部分

投稿後に機密情報へ気づいた場合は、Issue の本文を編集して取り除いてください。脆弱性やセキュリティ上の問題は、公開 Issue ではなく[セキュリティ報告](https://github.com/1llum1n4t1s/Rinkaku-Support/security/advisories/new)を利用してください。

## 対応環境

Rinkaku は WebGPU が利用できる Google Chrome 113 以降に対応しています。Chrome の派生ブラウザーでは動作する場合がありますが、すべての環境での動作を保証するものではありません。

WebGPU が利用できない場合や、GPU ドライバー・動画配信方式・サイト側の構造によっては、映像処理が動作しないことがあります。

## 返信について

内容を確認したうえで、必要に応じて追加情報をお願いします。報告されたすべての要望の実装や、個別の対応期限を約束するものではありません。
