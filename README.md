# ☁️ AWS Cost Optimization Report - Abstergo Industries

![AWS](https://img.shields.io/badge/AWS-%23232F3E.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Cloud Computing](https://img.shields.io/badge/Cloud-Computing-blue?style=for-the-badge)
![FinOps](https://img.shields.io/badge/Focus-Cost_Reduction-green?style=for-the-badge)

## 📝 Introdução
Este repositório contém o planejamento estratégico para a implementação de serviços **AWS** na empresa **Abstergo Industries**. O projeto foca em **FinOps**, aplicando soluções que visam a redução imediata de custos sem comprometer a performance e a disponibilidade dos serviços.



## 🎯 Objetivos do Projeto
* Identificar gargalos de custos na infraestrutura atual.
* Implementar soluções de automação e escalabilidade.
* Reduzir o desperdício de recursos computacionais ociosos.



## 🛠️ Etapas de Implementação

### 1. Computação Eficiente com EC2 Spot Instances
* **Foco:** Redução de custos em instâncias de processamento.
* **Caso de Uso:** Migração dos ambientes de desenvolvimento e homologação para instâncias Spot, aproveitando a capacidade ociosa da AWS com descontos de até 90%.

### 2. Armazenamento Inteligente com S3 Intelligent-Tiering
* **Foco:** Otimização automática de custos de storage.
* **Caso de Uso:** Aplicação de políticas de tiering para backups e logs de sistema. O serviço move dados automaticamente para camadas de arquivo (Glacier) após períodos de inatividade, reduzindo o custo de armazenamento de dados frios.

### 3. Arquitetura Serverless com AWS Lambda
* **Foco:** Computação baseada em eventos (Pay-as-you-go).
* **Caso de Uso:** Substituição de tarefas agendadas (CRON jobs) e scripts de ETL que rodavam em servidores fixos por funções Lambda, garantindo cobrança apenas pelo tempo de execução.



## 📊 Benefícios Esperados

| Serviço | Economia Estimada | Impacto Operacional |
| :--- | :---: | :--- |
| **EC2 Spot** | ~70-90% | Alto (Ambientes Dev/Test) |
| **S3 Tiering** | ~30-50% | Baixo (Transparente) |
| **AWS Lambda** | ~60-80% | Médio (Mudança de Paradigma) |



## 📋 Conclusão
A implementação conjunta destas ferramentas permite à **Abstergo Industries** uma operação muito mais enxuta e eficiente. A estratégia foca no pilar de **Otimização de Custos** do *AWS Well-Architected Framework*, garantindo que o orçamento de TI seja investido em inovação e não apenas em manutenção de legado.



## 👤 Responsável
**Elizeu Lucio**
*Estudante de Ciência da Computação & Aspirante a Ciência de Dados.*


> 💡 *Este projeto faz parte do meu portfólio de estudos em Cloud Computing e Ciência de Dados.*
