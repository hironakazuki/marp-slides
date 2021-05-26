---
marp: true
theme: gaia
# backgroundColor: "#FBF4E9"
# backgroundColor: "#C7E6D7"
---

<!--
_theme: gaia

_footer: "by ひろなか"

-->

# Hasura GraphQL Engine

---

# Hasura GraphQL Engine とは

PostgreSQL サーバーから自動的に GraphQL サーバーを建てられるツール

---

# 良いところ

- テーブルを作成するだけで CRUD の API が作られる
- firebase Auth 等(IDaas)と連携して認証、認可の設定可能
- foreign key 設定からリレーションシップの作成
- ページング、集計クエリ、ソート, upsert なども生成できる

---

![bg 75%](./public/hasura/architecture.png)

---

# リンク集

<!-- ![](./public/hasura/site.png) -->

[試しに作ったもの](https://next-firebase-auth-template-dgmrz2w8g-rukoshio.vercel.app/hasura)
※このスライド発表以降は消えてる可能性あり

[github Repository](https://github.com/hironakazuki/next-firebase/tree/with-hasura)
