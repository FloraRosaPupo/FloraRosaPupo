# Perfil do GitHub (FloraRosaPupo)

README especial do perfil, exibido em github.com/FloraRosaPupo. Só Markdown.

## Estrutura
- `README.md`, nesta ordem: título e cargos → sobre o trabalho (front, back, dados, código, qualidade, aprendizado) → formação → projetos em destaque → links.
- `.github/workflows/main.yml`: gera a **animação de contribuições** (usa `github.repository_owner`) e publica numa branch de saída. Não precisa de secret além do `GITHUB_TOKEN`.
- `docs/REVISAO.md`: notas de revisão.

## Deploy
Push na branch principal atualiza o perfil na hora. O workflow da animação roda no agendamento ou manualmente.

## Regras
- **Consistência obrigatória** com o currículo (PDFs em `Downloads`) e com o `../Portifolio`: cargos, datas, formação e projetos não podem divergir.
- Sem métricas ou experiências inventadas. Protótipos aparecem como protótipos.
- Confira se cada link existe (LinkedIn, flora-rosa.web.app, repositórios).
- Texto curto e escaneável, com as palavras-chave das vagas-alvo: Engenharia de IA, Flutter, Node.js, Python, RAG, MCP.
- Para mudar o posicionamento profissional, sugira e mostre o diff antes de salvar.
