# Baile Flow V24

Atualização incremental da V23. Mantém a chave de armazenamento `baile-flow`.

- Reprogramação retroativa de aulas para qualquer data livre, sem modificar as demais aulas; ciclos permanecem ligados ao mesmo ID da aula, preservando presenças e pagamentos.
- Inativação e reativação independentes por modalidade, com histórico mantido. Pendências de ciclos inativos saem do painel de ação.
- Reposições pendentes deixam de contar após 30 dias do fim do ciclo (ou prazo de extensão manual), sem eliminar o registro histórico.
- Valores padrão continuam editáveis; nenhuma mensalidade existente é alterada automaticamente.

**Antes de publicar:** exporte backup pela V23. Substitua os cinco arquivos no mesmo repositório e endereço de hospedagem; teste com uma cópia de dados antes de usar em produção.
