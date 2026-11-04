# Baile Flow — V27.1

Versão baseada na V26, preservando as melhorias anteriores e a chave local `baile-flow`.

## Novidades

- Lista de reposições ordenada por vencimento, nome ou data da falta.
- Pendências permanecem visíveis após o prazo regular de sete dias.
- Professora pode prorrogar, registrar retroativamente ou encerrar a reposição com motivo.
- Encerramento automático após mais 30 dias sem ação, preservando a falta e o histórico da reposição.
- Extensões autorizadas posteriormente preservam a pendência até o novo prazo.
- Nome V27.1 no aplicativo, exportação de backup e arquivos sem cache.

## Publicação no GitHub

1. Exporte um backup do aplicativo antes de atualizar.
2. Envie os cinco arquivos extraídos para a mesma pasta do GitHub.
3. Confirme que o cabeçalho mostra V27 e teste as reposições antigas.

**Nota:** o encerramento automático se executa quando o aplicativo é aberto ou o painel de reposições é consultado, não por um processo de servidor contínuo. A falta e o histórico não são apagados.

## Correção V27.1

- Reconcilia faltas antigas marcadas como `Faltó` que não tenham vínculo de reposição.
- Não reabre pendências já usadas, encerradas ou expiradas, nem aulas substituídas por antecipação.
- Mantém o prazo regular e o fechamento automático definidos na V27.
- Não altera presenças, pagamentos ou datas dos ciclos.
