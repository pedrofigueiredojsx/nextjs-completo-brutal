# Nextjs Completo

Projeto de estudo feito com **Next.js** (App Router), **TypeScript** e **Tailwind CSS**, cobrindo desde o roteamento até o backend integrado.

## Tecnologias

- Next.js
- React
- TypeScript
- Tailwind CSS

## O que foi praticado

- **Roteamento:** rotas baseadas em arquivos (File System Routing) e página personalizada de Not Found
- **SEO:** metadados estáticos e dinâmicos
- **Renderização:** Server Components e Client Components (`useState`, `useEffect`), combinados na mesma página
- **Server Actions:** formulários e lógica executados no servidor
- **Streaming e Suspense:** carregamento progressivo da interface
- **Cache e revalidação:** estratégias de cache e ISR
- **Middleware:** proteção de rotas e validação de autenticação
- **Route Handlers:** API própria, transformando o projeto em full stack

## Como rodar

```bash
git clone https://github.com/pedrofigueiredojsx/nextjs-completo-brutal
cd nextjs-completo-brutal/
npm install
npm run dev
```

Acesse [http://localhost:3000](http://localhost:3000).

## Estrutura

```
app/
├── [rotas e páginas]
├── [rotas e páginas]
├── [rotas e páginas]
├── [rotas e páginas]
├── api/            # Route Handlers
├── not-found.tsx
└── layout.tsx
middleware.ts
```

## Referência

Desenvolvido acompanhando um curso em vídeo de Next.js: [link do vídeo].
