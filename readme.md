# clone-tabnews

Projeto de estudo em Next.js inspirado no fluxo de desenvolvimento do TabNews. A base atual contém uma página inicial, uma rota de status e um exemplo de domínio testado com Jest.

## Requisitos

- versão do Node.js indicada em `.nvmrc`;
- npm.

## Desenvolvimento

```powershell
npm ci
npm run dev
```

Abra `http://localhost:3000`. A API de status fica em `http://localhost:3000/api/status`.

## Verificação

```powershell
npm run lint:check
npm test
```

`lint:check` apenas verifica a formatação; use `npm run lint:fix` para aplicar as correções localmente.
