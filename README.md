# Rotina vocal

App de treino vocal: escalas tocadas no teclado, metrônomo, cronômetro de respiração, histórico de progresso e gravações. Funciona no navegador do celular e pode ser instalado na tela inicial.

Rotinas incluídas:
- **Técnica + melismas difíceis** (padrão): respiração e apoio, staccato do zero, canudo + messa di voce, fechamento leve, agudos limpos, 6 melismas difíceis com bpm progressivo, aplicação em Open Arms e desaquecimento.
- **Rotina completa** e **Dia de show** (as originais).

Os dados ficam salvos no próprio aparelho (localStorage e IndexedDB).

## Publicar no GitHub Pages

1. Crie um repositório novo no GitHub (por exemplo, `rotina-vocal`).
2. Envie todos os arquivos desta pasta para a raiz do repositório (botão **Add file → Upload files**).
3. Vá em **Settings → Pages**, em *Source* escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`, e salve.
4. Em 1 ou 2 minutos o app estará em `https://SEU-USUARIO.github.io/rotina-vocal/`.
5. No celular, abra esse link e use **Adicionar à tela inicial**.

## Arquivos

| Arquivo | Para quê |
|---|---|
| `index.html` | O app inteiro |
| `manifest.webmanifest` | Permite instalar como app |
| `sw.js` | Funciona offline depois da primeira visita |
| `icon-192.png`, `icon-512.png` | Ícones |
| `.nojekyll` | Faz o GitHub Pages servir os arquivos como estão |

## Atualizar exercícios

Dentro do app: **✎ Editar** em cada exercício, ou **✨ IA** para gerar ajustes com o Claude e colar a resposta.
