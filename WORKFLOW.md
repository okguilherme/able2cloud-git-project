Fluxo de Branches (Trunk-Based Development): Utiliza a branch main como a base estável e protegida de produção, onde alterações entram exclusivamente via Pull Request, vindas de branches de trabalho isoladas do tipo feature/*.

Convenção de Nomes: Padroniza a criação de branches com prefixos descritivos conforme a natureza da tarefa, como feature/ para novas funcionalidades, bugfix/ para correção de erros e hotfix/ para urgências.

Mensagens de Commit (Conventional Commits): Define um histórico semântico e limpo utilizando prefixos claros para rastrear as alterações, a exemplo de feat() para novas implementações, fix() para correções e test() para adição de testes unitários.

Checklist de Pull Request: Estabelece critérios obrigatórios de qualidade antes de integrar o código à main, exigindo testes locais bem-sucedidos, branch atualizada via rebase, descrição detalhada do impacto da mudança e o vínculo com uma Issue de rastreio (ex: Closes #1).
