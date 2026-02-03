📊 XBOX GAME PASS – Subscription Sales Analysis

### **PROJETO 03 – X‑BOX**

Este projeto apresenta uma análise completa das vendas de assinaturas do **Xbox Game Pass**, incluindo dados brutos, cálculos analíticos, KPIs e um dashboard final desenvolvido no Excel.

📁 **Estrutura do Projeto**

A pasta de trabalho contém quatro planilhas principais:

**1️⃣ Assets**

Contém os elementos visuais utilizados no dashboard:

*   Paleta oficial de cores do Xbox
*   Cores complementares
*   Logos e ícones utilizados na interface visual

Esta aba funciona como o **repositório de identidade visual** do projeto.

**2️⃣ Bases (Base de Dados)**

É a tabela central contendo todas as assinaturas registradas. Campos incluídos:

| Campo                         | Descrição                                    |
| ----------------------------- | -------------------------------------------- |
| Subscriber ID                 | Identificador do assinante                   |
| Name                          | Nome do cliente                              |
| Plan                          | Tipo de plano (Core, Standard, Ultimate)     |
| Start Date                    | Data de início da assinatura                 |
| Auto Renewal                  | Assinatura com renovação automática (Yes/No) |
| Subscription Price            | Preço do plano                               |
| Subscription Type             | Periodicidade: Monthly, Quarterly, Annual    |
| EA Play Season Pass + Price   | Indica adesão e valor adicional              |
| Minecraft Season Pass + Price | Indica adesão e valor adicional              |
| Coupon Value                  | Desconto aplicado                            |
| Total Value                   | Faturamento total consolidado por assinatura |

A base cobre o período de **01/01/2024 a 31/12/2024**.

**3️⃣ Cálculos (Análises)**

Nesta aba, são respondidas **perguntas de negócio** por meio de tabelas dinâmicas e agregações:

✔ **Pergunta 1 — Faturamento total das assinaturas anuais**

Valor total gerado exclusivamente por planos do tipo **Annual**.

✔ **Pergunta 2 — Faturamento anual segmentado por Auto-Renewal**

Divide os valores entre assinaturas anuais com:

*   **Yes** → Com renovação automática
*   **No** → Sem renovação automática

✔ **Pergunta 3 — Vendas totais EA Play Season Pass**

Total de receita proveniente do add-on **EA Play**:

*   Ultimate: valor agregado
*   Core e Standard: não aderiram

✔ **Pergunta 4 — Vendas totais Minecraft Season Pass**

Total de receita proveniente do add‑on **Minecraft**:

*   Ultimate e Standard apresentam receita
*   Core não teve adesão

As análises são estruturadas em tabelas dinâmicas prontas para auditoria.

**4️⃣ Dashboard (Painel Visual)**

O painel principal apresenta:

*   KPIs chave do período:
    *   **Faturamento EA Play Season Pass**
    *   **Faturamento Minecraft Season Pass**
    *   **Faturamento total de add‑ons**
*   Mensagem de boas‑vindas e informações do período analisado
*   Identidade visual do Xbox (cores e logotipos)
*   Indicadores atualizados com última data de refresh
*   Recomendações de compatibilidade de segmentação (Excel 2010+)

🎯 **Objetivo do Projeto**

Fornecer uma análise clara e direta sobre:

*   Desempenho financeiro de assinaturas do Xbox Game Pass
*   Impacto dos add-ons EA Play e Minecraft
*   Comparação entre periodicidades de assinatura
*   Efeitos da renovação automática na receita anual
*   Consolidação de KPIs para tomada de decisão

Este projeto demonstra a aplicação de análise de dados em Excel, uso avançado de tabelas dinâmicas, criação de dashboard visual e organização profissional de uma base de assinaturas.

🛠️ **Tecnologias Utilizadas**

*   **Microsoft Excel (2010+)**
*   Tabelas dinâmicas
*   Segmentações de dados
*   Fórmulas de agregação
*   Design de dashboard
*   Paleta de cores personalizada

🚀 **Como Utilizar o Arquivo**

1.  Abra o arquivo **PROJETO 03 – X‑BOX.xlsx**
2.  Explore a aba **Bases** para visualizar os dados completos
3.  Acesse a aba **Cálculos** para entender as métricas e tabelas dinâmicas
4.  Navegue para **Dashboard** para visualizar os KPIs consolidados
5.  Utilize as segmentações (caso apareçam) para filtrar os resultados por plano, período ou tipo de assinatura

📌 **Possíveis Melhorias Futuras**

*   Automatizar cálculos via Power Query ou Power Pivot
*   Publicar o dashboard no Power BI
*   Criar um script Python para ingestão e limpeza da base
*   Adicionar análises preditivas (churn, projeção de receita)
*   Criar documentação técnica separada (data dictionary + metodologia)

📄 **Licença**

Este projeto pode ser utilizado para fins educacionais, portfólio e demonstração profissional.
