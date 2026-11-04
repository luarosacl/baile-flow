# Baile Flow — V26 completa

Esta versão reúne as sete melhorias combinadas a partir da V24. Mantém a mesma chave de armazenamento local e os cinco arquivos do aplicativo.

## Mudanças
1. **Suspensão de aula**: opção disponível inclusive para datas passadas, com motivo obrigatório e registro no histórico. Uma aula suspensa sem presenças registradas deixa de contar nos ciclos afetados e a próxima aula válida assume a posição, sem mover o calendário da turma.
2. **Reprogramação**: continua permitindo novas datas (inclusive retroativas) com motivo e histórico. Se a nova data coincidir com outra aula da mesma turma e horário, oferece suspender a aula de origem, mantendo a sequência semanal existente.
3. **Ciclos**: recalcula a lista de aulas afetada por suspensão ou exclusão de aula sem registros de presença, preservando as presenças já registradas, as quatro aulas contratadas e os pagamentos.
4. **Exclusão com motivo**: solicitação de justificativa e registro auditável acessível em **Más → Seguridad de datos → Historial de clases eliminadas**. A exclusão é bloqueada quando existem registros vinculados de presença, reposição ou participação para evitar perda de informações.
5. **Reposições**: prazo-padrão de sete dias após o encerramento do ciclo e botão **Extender plazo** para exceções individuais.
6. **Compatibilidade**: aula de nível técnico não pode ser usada como reposição de samba básico nem ritmos brasileiros. Samba técnico pode recuperar em níveis inferiores e ritmos brasileiros. O seletor filtra as aulas compatíveis com a data escolhida.
7. **Antecipações**: manutenção da correção V25.1, vinculando a antecipação à última aula futura pendente do ciclo, sem acrescentar uma quinta aula.

## Antes de publicar
1. Exporte um backup JSON pelo próprio aplicativo e guarde-o em local seguro.
2. Extraia o ZIP e envie os **cinco arquivos**, incluindo `index.html`, para o mesmo diretório do repositório GitHub.
3. Teste em uma turma e uma aluna representativas a suspensão, a antecipação e a reposição antes de registrar novas movimentações.

## Limitações e cuidados
- Uma aula já associada a presenças ou reposições não pode ser suspensa ou excluída automaticamente sem antes revisar os registros: essa proteção evita alterações indevidas no histórico.
- Os testes automatizados verificaram sintaxe e fluxos básicos com dados de exemplo. A operação com o banco real da usuária ainda deve ser validada no navegador, após backup.
- Não é necessário importar o backup se o armazenamento local atual continuar intacto; o backup é uma medida preventiva.

## Ajuste V25.4
- Datas dos ciclos apresentadas em ordem cronológica real, incluindo antecipações.
- Etiqueta de antecipação mostra também a aula original substituída, por exemplo **10/10 · Anticipada del 02/11**.
- Alteração apenas visual, sem modificar presenças, faltas, pagamentos nem dados armazenados.


- **Compactação visual**: reposições e antecipações agora exibem apenas dia/mês e usam rótulos abreviados (por exemplo, `Rep. 10-10` e `Ant. 02-11`), ocupando no máximo duas linhas por botão.

## V26

Entrega renomeada para V26, com versão visível e atualização de cache para app.js e styles.css. Mantém as melhorias da V25.4.
