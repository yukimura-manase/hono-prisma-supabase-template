# Hono ✖️ Prisma ✖️ Supabase Template

## 開発環境

```bash
yarn install

yarn dev
```

Server 起動後は、
http://localhost:8787 で local Server にアクセス可能

## 環境変数

- Cloudflare Workers の場合は、`wrangler.toml`に環境変数を管理する

- Cloudflare Workers の以外の場合は、`.env`を作成して環境変数を管理する

## Deploy

```bash
yarn deploy
```

## Prisma Migration

```bash
npx prisma migrate dev --name init
```
