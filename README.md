## Aplicativo de exemplo usando o Gerenciador de tags do Google

Este exemplo mostra como usar Next.js junto com Google Tag Manager. [`pages/_document.js`](pages/_document.js) é usado para injetar [base code](https://developers.google.com/tag-manager/quickstart). [`pages/_app.js`](pages/_app.js) é usado para rastrear alterações de rota e enviar visualizações de página para Google Tag Manager.

## Implante o seu próprio

Implante o exemplo usando [Vercel](https://vercel.com?utm_source=github&utm_medium=readme&utm_campaign=next-example):

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/git/external?repository-url=https://github.com/vercel/next.js/tree/canary/examples/with-google-tag-manager&project-name=with-google-tag-manager&repository-name=with-google-tag-manager)

## Como usar

Execute [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app) com [npm](https://docs.npmjs.com/cli/init), [Yarn](https://yarnpkg.com/lang/en/docs/cli/create/), ou [pnpm](https://pnpm.io) para inicializar o exemplo:

```bash
npx create-next-app --example with-google-tag-manager with-google-tag-manager-app
```

```bash
yarn create next-app --example with-google-tag-manager with-google-tag-manager-app
```

```bash
pnpm create next-app --example with-google-tag-manager with-google-tag-manager-app
```

A seguir, copie o `.env.local.example` arquivo neste diretório para `.env.local` (que será ignorado pelo Git):

```bash
cp .env.local.example .env.local
```

Coloque o `NEXT_PUBLIC_GOOGLE_TAG_MANAGER_ID` variável em `.env.local` para corresponder ao seu ID do Gerenciador de tags do Google.

Deploy para a nuvem com [Vercel](https://vercel.com/new?utm_source=github&utm_medium=readme&utm_campaign=next-example) ([Documentation](https://nextjs.org/docs/deployment)).
