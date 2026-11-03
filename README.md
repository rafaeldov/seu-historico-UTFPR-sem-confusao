# UTFPR sem confusão

Site estático para estudantes da UTFPR Curitiba.

- `/` — Início
- `/historico/` — leitor do PDF do Histórico Escolar (processado no navegador)
- `/grade/` — montagem de grade do semestre (em construção)
- `/extensao/` — projetos de extensão, lidos de uma planilha do Google Sheets

## Configuração

Edite `assets/config.js` e cole em `extensaoCsv` o link da planilha publicada como CSV
(Google Sheets → Arquivo → Compartilhar → Publicar na Web → Valores separados por vírgula).
O arquivo `extensao/acoes-extensao.csv` traz as colunas esperadas e é usado enquanto a planilha não estiver conectada.

## Publicação

Cada commit na branch `main` é publicado pela Vercel.
