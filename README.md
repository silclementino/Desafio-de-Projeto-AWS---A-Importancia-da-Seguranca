# RELATÓRIO DE IMPLEMENTAÇÃO DE MEDIDAS DE SEGURANÇA

Data: 01/09/2024
Empresa: Bolinha Tech
Responsável: Silmara Clementino

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa [nome da empresa], realizado por Silmara Clementino. O objetivo do projeto foi elencar 3 medidas de segurança em conjunto dos serviços da AWS, com a finalidade de realizar aumentar a segurança na empresa.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 medidas de segurança. A seguir, serão descritas as etapas da implementação:

Medida 1: Implementação de AWS Identity and Access Management (IAM) com Políticas de Least Privilege
Para garantir que os colaboradores da Bolinha Tech tenham apenas as permissões mínimas necessárias para realizar suas funções, foi implementado o AWS Identity and Access Management (IAM) com políticas de least privilege. Esta medida envolveu a criação de grupos de usuários com políticas de acesso restrito, baseadas nas funções de cada grupo dentro da empresa e habilitado o 2FA para evitar que acessos indevidos sejam realizado por terceiros.

Benefícios:
- Redução do risco de acessos não autorizados a recursos críticos.
- Controle granular sobre quem pode acessar e modificar recursos específicos na AWS.
- Melhoria na auditoria e no monitoramento de atividades de usuários.

Medida 2:Implementação de AWS Key Management Service (KMS) para Criptografia de Dados
Foi implementado o AWS Key Management Service (KMS) para criptografar dados em repouso e em trânsito. O KMS permite a criação e o gerenciamento de chaves de criptografia, que são usadas para proteger informações sensíveis da empresa, como dados de clientes e registros financeiros.

Benefícios:
- Garantia de que os dados armazenados estão protegidos contra acesso não autorizado.
- Simplificação do processo de criptografia e gerenciamento de chaves.
- Conformidade com regulamentos de segurança e proteção de dados.

Medida 3: 
Implementação de AWS CloudTrail e AWS Config para Monitoramento e Auditoria de Recursos
A Bolinha Tech implementou o AWS CloudTrail e o AWS Config para monitoramento contínuo e auditoria das atividades dentro da infraestrutura AWS. O CloudTrail registra todas as chamadas de API realizadas na conta AWS, enquanto o AWS Config rastreia mudanças nos recursos, permitindo a avaliação contínua da conformidade com as políticas internas de segurança.

Benefícios:
- Monitoramento em tempo real de atividades e alterações de recursos.
- Capacidade de realizar auditorias detalhadas para identificar e remediar atividades suspeitas.
- Aumento da visibilidade sobre a conformidade de segurança da infraestrutura.


## Conclusão
A implementação de ferramentas na empresa *Bolinha Tech tem como esperado o aumento da proteção dos dados corporativos, a mitigação de riscos relacionados ao acesso não autorizado e a melhoria da capacidade de monitoramento e auditoria de atividades*, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

[lista de anexos, como manuais, documentos, planilhas, entre outros]

Assinatura do Responsável pelo Projeto:

Silmara Clementino
