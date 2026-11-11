# Bible Puzzle Adventures

Vitrine e publicação do app **Bible Puzzle Adventures**.

O código-fonte (motor, app e assets) permanece no monorepo
[NOSTALGIA-PUZZLE-90-S](https://github.com/Asilva-01/NOSTALGIA-PUZZLE-90-S),
no tag [`bible-v0.1.0`](https://github.com/Asilva-01/NOSTALGIA-PUZZLE-90-S/releases/tag/bible-v0.1.0)
(`963362c22524115c4ba863fc886f1ae778359253`). Este repositório não duplica o motor.

Site: https://asilva-01.github.io/BIBLE-PUZZLE-ADVENTURES/

O workflow `.github/workflows/pages.yml` faz checkout desse tag, executa
`npm ci && npm run build:bible` com `VITE_BASE=/BIBLE-PUZZLE-ADVENTURES/` e
publica `apps/bible-puzzle/dist` no GitHub Pages. O deploy é manual
(`workflow_dispatch`).
