# odhackathon_metro_tokyo_service

# 資料

- https://docs.google.com/spreadsheets/d/1oMsow40EWqibW40t2rS6KyfIuFwJxdI1tneNZ1yRgG8/edit?gid=787165291#gid=787165291

# 開発方法

## 準備

```bash
npm i
npm run dev
# macのみ iphone
npx cap run ios (別のターミナル)
# android シミュレーター
npx cap run android (別のターミナル)
```

# 以下元々の情報

Everything you need to build a Svelte project, powered by [`create-svelte`](https://github.com/sveltejs/kit/tree/main/packages/create-svelte).

## Creating a project

If you're seeing this, you've probably already done this step. Congrats!

```bash
# create a new project in the current directory
npm create svelte@latest

# create a new project in my-app
npm create svelte@latest my-app
```

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an [adapter](https://kit.svelte.dev/docs/adapters) for your target environment.
