# LOQ — Locação de máquinas

Projeto da disciplina de Gestão de Projetos — 8º semestre da Faculdade Impacta.

A LOQ é uma plataforma de locação inteligente de máquinas, conectando clientes, proprietários, transportadoras e operadores.

## Desenvolvimento

React / Express / tRPC / Drizzle starter, adaptado do template web-db-user.

- `pnpm dev`: servidor de desenvolvimento; respeita `PORT` (padrão 3000).
- `pnpm build` / `pnpm start`: gera e serve `dist/index.js` e `dist/public/`.
- `pnpm db:migrate`: aplica as migrações versionadas.
- `pnpm db:push`: gera e aplica alterações intencionais de schema.
- `pnpm check` / `pnpm test`: valida tipagem e testes.

O MVP inclui visões demo para Locatário/Cliente, Proprietário/Locador, Transportadora e Operador, além de um login fictício para troca de persona.

A configuração de plataforma é legível e editável por `webdev.config`. O login demo não persiste dados nem envia informações para serviços externos.
