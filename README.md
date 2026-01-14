# **Relatório de Implementação e Otimização de Custos AWS**


## Descrição do Projeto
Este relatório apresenta o processo de migração estratégica de uma infraestrutura local para a nuvem AWS. O foco central foi a substituição de gastos fixos elevados (**CapEx**) por um modelo de despesas operacionais (**OpEx**), visando a diminuição imediata de custos.

---

## Ferramentas Implementadas

### 1. Amazon EC2
*   **Finalidade:** Servidores virtuais para processamento e hospedagem.
*   **Estratégia:** Substituição de servidores físicos por instâncias escaláveis, eliminando custos de manutenção de hardware.

### 2. Amazon S3
*   **Finalidade:** Armazenamento de objetos (backups e mídias).
*   **Estratégia:** Uso de buckets com alta durabilidade, eliminando a necessidade de fitas de backup ou storages físicos caros.

### 3. Amazon RDS for MySQL
*   **Finalidade:** Banco de dados relacional gerenciado.
*   **Estratégia:** Redução de carga horária técnica com automação de backups, patches e alta disponibilidade.

---

## Estimativas de Custo: AWS vs On-Premise (2026)


| Categoria | AWS (Mensal Estimado) | On-Premise (Mensal Médio) |
| :--- | :--- | :--- |
| **Infraestrutura/Hardware** | Incluso | R$ 1.500,00 - R$ 3.000,00 |
| **Manutenção/Pessoal (TI)** | Gerenciado | R$ 4.000,00 - R$ 12.000,00 |
| **Energia e Climatização** | Incluso | R$ 1.100,00 - R$ 3.200,00 |
| **Espaço Físico/Aluguel** | R$ 0,00 | R$ 500,00 - R$ 1.500,00 |
| **TOTAL** | **~R$ 961,91 (U$ 179,25)** | **R$ 7.100,00 - R$ 19.700,00** |

> **Nota:** Os custos AWS são baseados no modelo *pay-as-you-go*, permitindo que a empresa pague apenas pelo que utiliza, sem investimento inicial em hardware.

---

## Conclusão
A migração para a AWS mostrou-se financeiramente superior, reduzindo os custos operacionais mensais em mais de **85%** no cenário mínimo. Além da economia direta, a empresa ganha em segurança, escalabilidade instantânea e foco total no negócio, deixando a gestão física para o provedor de nuvem.

## Anexos e Documentação
- [Diagrama da Arquitetura](https://github.com/Ferreira3/aws-business-cost-optmiziation/blob/main/docs/diagrama_aws.png)
- [Estimativa Detalhada (PDF)](https://github.com/Ferreira3/aws-business-cost-optmiziation/blob/main/docs/estimativas-1ano.pdf)

---

## Autoria
**José Eduardo Ferreira**  
*Projeto desenvolvido para um Bootcamp de Ciência de Dados.*
