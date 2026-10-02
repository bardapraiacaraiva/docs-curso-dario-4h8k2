# Curso DARIO — Biblioteca dos Sócios

Site estático do curso DARIO para Bernardo e Lelê, servido por GitHub Pages.

- **URL:** https://bardapraiacaraiva.github.io/docs-curso-dario-4h8k2/
- **Acesso:** portão em JS (mesmo padrão da Bíblia — proteção cosmética, afasta curiosos; não é segurança real)

## Conteúdo

- Módulos 0–7: as 75 lições do curso (espelho do dashboard, 02/10/2026)
- Volume 2: Trilha DARIO Orchestrator (S10–S17 + projeto final)
- Apêndice: auditoria das 75 lições com as correções pendentes

## Como atualizar

1. Editar/substituir `data.js` (o conteúdo vive todo em `window.COURSE_DATA`).
2. `git add -A && git commit -m "atualiza curso" && git push`
3. O Pages republica em ~1 minuto.

Para regenerar as lições a partir do dashboard do Bernardo, repetir o download
via `GET /api/tree` e `GET /api/lesson?m=<dir>&f=<file>` e reconstruir `data.js`.
