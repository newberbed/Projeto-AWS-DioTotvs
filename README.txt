# RELATÓRIO DE IMPLEMENTAÇÃ DE SERVIÇOS AWS

Data: 04/05/2026
Empresa: Abstergo Industries 
Responsável: Newber Araújo Fonseca

## Introdução
Este relatório detalha o plano de migração da infraestrutura local para o ambiente de computação em nuvem AWS da Abstergo Industries. Como uma distribuidora de grande porte que atende outras empresas, a Abstergo necessita de uma arquitetura que garanta alta disponibilidade, segurança de dados e eficiência logística, eliminando as limitações físicas de hardware local.

## Descrição do Projeto
O processo de migração foi desenhado em 3 etapas fundamentais para garantir que a transição não interrompa o fluxo de vendas para os parceiros comerciais:

Etapa 1: 
Nome da ferramenta: Amazon S3 (Simple Storage Service).
Foco da ferramenta: Armazenamento de dados e documentos fiscais.
Descrição de caso de uso: Armazenamento centralizado de catálogos de produtos, tabelas de preços dinâmicas e backups de XMLs de notas fiscais de saída. O uso do S3 permite que os parceiros acessem ativos digitais (como imagens de produtos para seus próprios sites) com alta velocidade e baixo custo de transferência.

Etapa 2: 
Nome da ferramenta: Amazon EC2 (Elastic Compute Cloud).
Foco da ferramenta: Servidores virtuais escaláveis.
Descrição de caso de uso: Migração do sistema de gestão de estoque e ERP que rodava localmente. Com o EC2, a Abstergo pode utilizar o "Auto Scaling" para aumentar a capacidade do servidor em dias de fechamento de mês ou promoções sazonais, garantindo que o sistema de pedidos dos parceiros nunca fique lento ou fora do ar.
Etapa 3: 
Nome da ferramenta: Amazon RDS (Relational Database Service).
Foco da ferramenta: Banco de dados relacional gerenciado.
Descrição de caso de uso: Hospedagem do banco de dados de clientes, inventário e transações financeiras. O RDS permite a replicação em múltiplas zonas de disponibilidade, garantindo que, se um datacenter falhar, a distribuidora continue operando sem perda de dados, algo crítico para uma operação de atacado.

## Conclusão
A migração da Abstergo Industries para a AWS transformará a TI de um centro de custos e manutenção física em um motor de crescimento. A elasticidade da nuvem permitirá que a empresa adicione novos parceiros à sua rede de distribuição sem precisar investir em novos servidores físicos, reduzindo o custo operacional e aumentando a confiabilidade da entrega de dados para o cliente final.

## Anexos
1. Arquitetura de Conectividade: Modelo de integração ERP Cloud com parceiros B2B.
2. Tabela Comparativa: Custos de On-Premise vs. Cloud AWS.
3. Plano de Migração.

Assinatura do Responsável pelo Projeto:

Newber Araújo Fonseca
