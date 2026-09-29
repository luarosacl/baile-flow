# Baile Flow V18

Versão baseada na V17, com preservação não destrutiva dos dados existentes.

## Principais recursos desta versão
- Duração individual por estilo.
- Presença diretamente nas datas/quadrados do ciclo, sem “Ver classes”.
- Reposição vinculada à falta original e à aula/data de reposição.
- Perfil da aluna permanece aberto após registrar pagamento.
- Bloqueio de turmas ativas no mesmo dia e horário.
- Encerramento de turma por data, preservando histórico e permitindo nova turma no mesmo horário depois.
- Seleção de turmas ativas em ordem alfabética.
- Clase suelta independente de ciclo.
- Ciclo particular com datas/horários individuais.
- Aniversariantes dos próximos 30 dias clicáveis para abrir o perfil.
- Lista de alunas mostra modalidade, nível e dia abreviado da turma.
- Excluir ciclo não exclui pagamentos nem aulas oficiais da turma.
- Exportação e importação de backup JSON de todos os dados.

## Backup
Use **Más → Seguridad de datos → Exportar backup** antes de qualquer migração ou troca de hospedagem.

Use **Importar backup** somente para restaurar um arquivo de backup válido do Baile Flow. A importação substitui os dados atuais pelos dados do arquivo e pede confirmação antes de executar.

## Preservação
A aplicação usa a mesma chave de armazenamento `baile-flow` e a migração V18 não faz reset dos registros existentes.
