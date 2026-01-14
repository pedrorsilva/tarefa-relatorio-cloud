# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

- Data: 14/01/2026
- Empresa: Abstergo Industries
- Responsável: Pedro Silva

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Pedro Silva. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos, por meio de automação de desligamento de recursos ociosos, uso de computação serverless e otimização de armazenamento em camadas.
​

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos, focando em redução de custo de computação e armazenamento sem comprometer disponibilidade ou segurança. A seguir, serão descritas as etapas do projeto:
​

### Etapa 1

- **Nome da ferramenta**: AWS Lambda  
- **Foco da ferramenta**: Computação serverless com pagamento apenas pelo tempo de execução
- **Descrição de caso de uso**: Migração de tarefas agendadas e scripts de manutenção que rodavam em instâncias EC2 dedicadas para funções Lambda, eliminando servidores ociosos e permitindo pagar apenas pelas invocações efetivas das funções, reduzindo custos de infraestrutura de forma significativa.
​

### Etapa 2
- **Nome da ferramenta**: Amazon EC2 Auto Scaling  
- **Foco da ferramenta**: Ajuste automático de capacidade de computação conforme demanda
- **Descrição de caso de uso**: Configuração de grupos de Auto Scaling para as aplicações web internas da Abstergo Industries, garantindo aumento automático de instâncias em picos de acesso e redução em horários de baixa, evitando pagamento por capacidade ociosa e reduzindo o custo mensal de EC2.
​

### Etapa 3
- **Nome da ferramenta**: Amazon S3 com Intelligent-Tiering  
- **Foco da ferramenta**: Otimização de custos de armazenamento com mudança automática de classe
- **Descrição de caso de uso**: Armazenamento de relatórios, logs históricos e arquivos pouco acessados em buckets S3 configurados com Intelligent-Tiering, permitindo que objetos migrem automaticamente para camadas mais baratas quando não são acessados com frequência, reduzindo o custo de armazenamento sem necessidade de gestão manual de ciclo de vida.
​

## Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado reduzir custos com computação e armazenamento, aumentar a elasticidade da infraestrutura e minimizar recursos ociosos, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias, como AWS Cost Explorer, AWS Budgets e Savings Plans, que possam melhorar ainda mais o controle financeiro e os processos da empresa.
​

## Anexos
- Documentação e visão geral do AWS Lambda, incluindo benefícios como não gerenciar servidores, escalabilidade automática e cobrança por uso:  
  - Página de produto: https://aws.amazon.com/lambda/  
  - Documentação geral: https://docs.aws.amazon.com/lambda/latest/dg/welcome.html
- Documentação do Amazon EC2 Auto Scaling, explicando como automatizar o aumento e a redução de instâncias EC2 para evitar capacidade ociosa e controlar custos:  
  - Visão geral do serviço: https://docs.aws.amazon.com/autoscaling/ec2/userguide/what-is-amazon-ec2-auto-scaling.html  
  - Visão geral de documentação: https://www.amazonaws.cn/en/documentation-overview/ec2-autoscaling/
- Documentação do Amazon S3 Intelligent-Tiering, detalhando como o serviço otimiza automaticamente os custos de armazenamento com base no padrão de acesso aos dados:  
  - Guia oficial: https://docs.aws.amazon.com/AmazonS3/latest/userguide/intelligent-tiering.html  
  - Página de storage class: https://aws.amazon.com/s3/storage-classes/intelligent-tiering/
- Artigo sobre casos de uso e benefícios do AWS Lambda, com foco em ganhos de agilidade, alta disponibilidade e eficiência de custos em cenários event-driven:  
  - https://www.logicata.com/blog/aws-lambda-use-cases/  
  - https://dashbird.io/blog/using-aws-lambda/
- Guia sobre otimização de custos com Amazon S3 Intelligent-Tiering, descrevendo cenários de uso como logs, arquivos de compliance e datasets de machine learning com padrão de acesso variável:  
  - https://hystax.com/amazon-s3-intelligent-tiering-cost-optimization/  
  - https://awsfundamentals.com/blog/amazon-s3-intelligent-tiering


Assinatura do Responsável pelo Projeto:



Pedro Silva
