# curso.dev-ia

Página simples do curso.dev construída com [Next.js](https://nextjs.org) (App Router) e TypeScript.

## Requisitos

- Node.js **>= 20.9.0**
- npm

## Como rodar

```bash
npm install
npm run dev
```

Acesse [http://localhost:3000](http://localhost:3000).

## Scripts

| Script | Descrição |
| --- | --- |
| `npm run dev` | Servidor de desenvolvimento |
| `npm run build` | Build de produção |
| `npm run start` | Serve o build de produção |
| `npm run typecheck` | Checagem de tipos (`tsc --noEmit`) |

## Deploy

Publicado na Vercel: <https://curso-dev-ia-puce.vercel.app>

Cada push na branch `main` dispara um deploy de produção automático.

## Versões

- React **19.3.1**
- Next.js **16.4.6**
- TypeScript **6.0.3**

## Estrutura

```
app/
  layout.tsx    # layout raiz e metadados
  page.tsx      # página inicial
  globals.css   # estilos globais
```
