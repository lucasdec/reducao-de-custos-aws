# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 12/08/2025  
Empresa: Abstergo Industries  
Responsável: Lucas Decesares Cunha Lima

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Lucas Decesares Cunha Lima. O objetivo do projeto foi *elencar 3 serviços AWS*, com a finalidade de *realizar diminuição de custos imediatos*, aumentando a eficiência operacional por meio da computação em nuvem.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

---

### Etapa 1:
- **Amazon S3**  
- **Foco:** Armazenamento de dados com alta durabilidade e baixo custo  
- **Descrição de caso de uso:**  
  O Amazon S3 foi utilizado para armazenar históricos de vendas, relatórios gerenciais, backups e arquivos internos da empresa. Antes da migração, esses dados eram mantidos em servidores físicos locais, o que gerava custos com manutenção, energia, espaço físico e equipamentos de armazenamento.  
  **Redução de custos:**  
  - Eliminação de gastos com infraestrutura local  
  - Pagamento apenas pelo armazenamento utilizado (modelo pay-per-use)  
  - Redução de custos com backup físico e recuperação de desastres  
  **Vantagens:**  
  - Alta durabilidade (99,999999999%)  
  - Acesso seguro e remoto aos arquivos  
  - Escalabilidade automática conforme o crescimento da empresa  

---

### Etapa 2:
- **AWS Lambda**  
- **Foco:** Execução de tarefas automatizadas sob demanda, sem servidor  
- **Descrição de caso de uso:**  
  O AWS Lambda foi usado para automatizar tarefas rotineiras como envio diário de relatórios por e-mail, processamento de dados de vendas e integração entre sistemas internos (ERP e banco de dados).  
  **Redução de custos:**  
  - Sem necessidade de manter servidores ligados 24/7  
  - Custo baseado apenas no tempo de execução do código  
  - Diminuição do tempo gasto com tarefas manuais pelos funcionários  
  **Vantagens:**  
  - Totalmente gerenciado (serverless)  
  - Escalável automaticamente conforme a demanda  
  - Integração nativa com outros serviços AWS (S3, RDS, SNS, etc.)

---

### Etapa 3:
- **Amazon RDS (Aurora)**  
- **Foco:** Banco de dados relacional gerenciado com alta performance  
- **Descrição de caso de uso:**  
  O banco de dados local foi substituído pelo Amazon RDS com mecanismo Aurora. Isso garantiu performance elevada com alta disponibilidade e backups automáticos, sem necessidade de manutenção direta.  
  **Redução de custos:**  
  - Eliminação de licenças e manutenção de banco de dados local  
  - Redução de falhas e tempo de inatividade  
  - Escalabilidade vertical e horizontal conforme a necessidade  
  **Vantagens:**  
  - Backup automático incluído  
  - Suporte a failover para alta disponibilidade  
  - Custos ajustáveis com base no uso real do banco de dados

---

## Conclusão
A adoção dos serviços AWS permitiu uma significativa redução de custos operacionais na empresa, além de garantir mais segurança, escalabilidade e agilidade nos processos. A migração para a nuvem foi estratégica para modernizar a infraestrutura de TI, mantendo a empresa competitiva e preparada para o crescimento futuro.
