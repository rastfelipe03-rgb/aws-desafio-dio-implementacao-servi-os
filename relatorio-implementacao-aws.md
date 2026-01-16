# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 16/01/2026  
**Empresa:** Abstergo Industries  
**Responsável:** Felipe Feitoza Nicolichi  

---

# 1. Introdução

Este relatório apresenta a implementação de três serviços AWS na Abstergo Industries, com foco na redução imediata de custos operacionais.  
O projeto foi conduzido por Felipe Feitoza Nicolichi.

---

# 2. Descrição do Projeto

A implementação foi dividida em três etapas:

---

## 🔹 Etapa 1 – Amazon S3
- **Foco:** Armazenamento barato e seguro  
- **Caso de uso:**  
  A empresa utilizava um servidor físico local para armazenar documentos.  
  O ambiente foi migrado para o Amazon S3 Standard-IA, resultando em redução média de **47%** nos custos de storage e backup.

**Principais ganhos:**  
- Durabilidade 11x9 (99.999999999%)  
- Pagamento somente pelo uso  
- Backup automático  

---

## 🔹 Etapa 2 – AWS Lambda  
- **Foco:** Execução de código sob demanda (sem servidor)  
- **Caso de uso:**  
  Scripts executados em um servidor dedicado foram migrados para funções AWS Lambda.  
  O servidor foi desligado, gerando economia de aproximadamente R$ 250/mês.

**Tarefas automatizadas com Lambda:**  
- Processamento de arquivos do S3  
- Notificações internas  
- Validação de logs

---

## 🔹 Etapa 3 – Amazon Aurora Serverless v2  
- **Foco:** Banco de dados relacional escalável e econômico  
- **Caso de uso:**  
  A empresa mantinha um banco MySQL em EC2; migramos para Aurora Serverless, que escala dinamicamente.  

**Resultados obtidos:**  
- Economia estimada de até **65%** ao mês  
- Zero necessidade de gerenciamento manual  
- Latência muito menor  

---

# 3. Conclusão

A implantação reduziu custos e melhorou a estabilidade da infraestrutura da Abstergo Industries.  
Os serviços escolhidos proporcionaram:

- Economia imediata  
- Escalabilidade  
- Menos servidores ligados 24h  
- Processos automatizados  
- Infra mais confiável  

Recomenda-se continuidade no uso das soluções e expansão para outras áreas da empresa.

---

# 4. Anexos

- Diagrama de Arquitetura  
- Prints da Console AWS  
- Script Lambda  
- PDF do relatório (opcional)

---

**Assinatura:**  
**Felipe Feitoza Nicolichi**  
Analista de Monitoramento Jr
