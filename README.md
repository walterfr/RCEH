# RCEH — Revista Cearense de Estudos Históricos

Projeto em Quarto para publicação do site oficial da **RCEH** no GitHub Pages (`https://walterfr.github.io/RCEH/`).

## Como publicar no GitHub
1. Extraia os arquivos deste pacote na raiz do repositório `https://github.com/walterfr/RCEH`.
2. Em `submissoes.qmd`, substitua `[INSERIR_LINK_DO_FORMULARIO_1]` e `[INSERIR_LINK_DO_FORMULARIO_3]` pelos links públicos dos Formulários 1 e 3.
3. Em `expediente.qmd`, adicione os nomes do Conselho Editorial antes de solicitar o ISSN ao CBISSN/IBICT.
4. No GitHub, acesse **Settings > Pages**, selecione **Deploy from a branch** e escolha a branch `gh-pages` (pasta `/(root)`).
5. A cada `git push` na branch `main`, o GitHub Actions renderiza e atualiza o site automaticamente.
