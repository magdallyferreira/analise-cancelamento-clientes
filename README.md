![Painel de Análise](Captura%20de%20tela%202026-10-16%20203547.png)

# Análise de Cancelamento de Clientes — Telecom

Projeto de análise de dados com o dataset **Telco Customer Churn (IBM)** — identificação de padrões de saída de clientes e recomendações práticas de retenção.
---

## 🎯 Objetivo
Responder: *"Quais características estão associadas a maior taxa de cancelamento e o que pode ser feito para reter clientes?"*

## 📊 Resumo Geral
- **7.043** clientes analisados
- **1.869** cancelaram → taxa de **26,54%**

## 🔍 Principais Descobertas

| Fator | Grupo com maior cancelamento | Taxa |
|---|---|---|
| Tempo de casa | 0–12 meses | 47,44% |
| Tipo de contrato | Mensal | 42,71% |
| Serviço de internet | Fibra Óptica | 41,89% |
| Forma de pagamento | Cheque Eletrônico | 45,29% |

- Quanto mais tempo o cliente permanece, menor a chance de sair — clientes com mais de 5 anos têm apenas **6,61%** de cancelamento
- Contratos de longo prazo demonstram forte fidelidade — bienal tem taxa de apenas **2,83%**

## ✅ Recomendações
1. Melhorar experiência de boas-vindas e acompanhamento nos **primeiros 90 dias**
2. Oferecer incentivos para migração de **contrato mensal → anual/bienal**
3. Revisar **qualidade e preço** do serviço de Fibra Óptica
4. Estimular adesão a **pagamento automático** para reduzir cancelamentos

## 🛠️ Ferramentas
- Power BI Desktop
- DAX para cálculo de métricas e faixas de tempo
- Fonte de dados: [Kaggle — Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

## ⚠️ Limitações
- Dados referentes a um período fechado; não acompanha tendências atuais
- Não há informação sobre concorrência e ações de mercado externas
- Causa raiz do cancelamento não está explícita — apenas correlações identificadas
