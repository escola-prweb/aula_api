# API LAB — Aula de APIs

Material interativo para a turma do Técnico em Desenvolvimento de Sistemas.

## Arquivos
- `index.html`: site completo da aula, com explicações, laboratório com a API ViaCEP, código copiável e pesquisa que exporta respostas em `.txt`.
- `aluno.html`: exercício inicial que os estudantes abrem ou editam no VS Code.

## Como usar no Windows
1. Abra a pasta no VS Code.
2. Abra `index.html` no navegador com duplo clique (ou use um servidor local se preferir).
3. Os estudantes criam seu próprio `aluno.html` a partir do código exibido no site, salvam e abrem no navegador.
4. As consultas reais à API ViaCEP precisam de internet. O site principal inclui demonstração identificada quando não há acesso.
5. Respostas à pesquisa podem ser baixadas como arquivo `.txt`; não são enviadas para o professor automaticamente.

## Publicar no GitHub Pages
1. Crie um repositório no GitHub.
2. Envie `index.html` para a raiz do repositório. Pode incluir `aluno.html` e `README.md`.
3. Em **Settings → Pages → Build and deployment**, selecione **Deploy from a branch**.
4. Escolha a branch principal (`main`) e a pasta `/ (root)`, depois **Save**.
5. Abra a URL de GitHub Pages que aparecer na página de configuração.

## Referências
- https://viacep.com.br/ — API pública para consulta de CEP.
- https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site — publicação no GitHub Pages.

**Observação:** HTML estático com JavaScript; não é necessário servidor backend nem chave de API.
