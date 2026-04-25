# 🎮 Xbox Game Pass — Dashboard de Vendas

Dashboard de vendas interativo desenvolvido no **Microsoft Excel**, com foco na organização e visualização de dados de assinaturas do Xbox Game Pass ao longo de 2024. O projeto transforma dados brutos em informações visuais claras, permitindo análise eficaz do desempenho de vendas e tomada de decisões baseadas em dados.

> Projeto desenvolvido como entrega do desafio **"Criando um Dashboard de Vendas no Excel"** da plataforma [DIO — Digital Innovation One](https://www.dio.me/).

---

## 🎯 Objetivo

Responder a perguntas de negócio relevantes a partir de dados de assinantes, utilizando tabelas dinâmicas, gráficos e indicadores visuais organizados em um painel único e interativo.

---

## ❓ Perguntas de Negócio Respondidas

O dashboard foi construído para responder às seguintes perguntas:

| # | Pergunta de Negócio |
|---|---|
| 1 | Qual o **faturamento total** de vendas de planos mensais (incluindo todas as assinaturas agregadas)? |
| 2 | Qual o faturamento total de vendas de planos mensais, **separado por Auto Renovação** (ativa vs. inativa)? |
| 3 | Qual o **total de vendas de assinaturas do EA Play** Season Pass? |
| 4 | Qual o **total de vendas de assinaturas do Minecraft** Season Pass? |

---

## 🗂️ Estrutura do Arquivo

O arquivo `DashboardXboX.xlsx` é organizado em **4 abas**:
Essas abas podem ou não estar **ocultas**

| Aba | Função |
|---|---|
| **Assets** | Paleta de cores e identidade visual baseada no Xbox |
| **Bases** | Base de dados brutos com os 295 registros de assinantes |
| **Cálculos** | Tabelas dinâmicas com as análises por pergunta de negócio |
| **Dashboard** | Painel visual final com gráficos e indicadores |

---

## 📋 Dicionário de Dados

A aba **Bases** contém os seguintes campos para cada assinante:

| Campo | Descrição |
|---|---|
| `Subscriber ID` | Identificador único do assinante |
| `Name` | Nome do assinante |
| `Plan` | Plano contratado: **Ultimate**, **Standard** ou **Core** |
| `Start Date` | Data de início da assinatura |
| `Auto Renewal` | Renovação automática ativa (`Yes` / `No`) |
| `Subscription Price` | Preço base mensal da assinatura ($) |
| `Subscription Type` | Ciclo de cobrança: **Monthly**, **Quarterly** ou **Annual** |
| `EA Play Season Pass` | Add-on EA Play ativo (`Yes` / `No`) |
| `EA Play Season Pass Price` | Preço do add-on EA Play ($) |
| `Minecraft Season Pass` | Add-on Minecraft ativo (`Yes` / `No`) |
| `Minecraft Season Pass Price` | Preço do add-on Minecraft ($) |
| `Coupon Value` | Valor de desconto aplicado via cupom ($) |
| `Total Value` | Receita total gerada pelo assinante ($) |

---

## 📊 Principais Métricas

| Indicador | Valor |
|---|---|
| Total de Assinantes | **295** |
| Receita Total (Planos Mensais) | **$3.571** |
| — Com Auto Renovação | $747 |
| — Sem Auto Renovação | $2.824 |
| Vendas EA Play (Mensal) | **$1.350** |
| Vendas Minecraft (Mensal) | **$1.800** |

---

## 🎨 Identidade Visual

O dashboard segue a paleta de cores oficial do Xbox:

| Cor | Hex | Uso |
|---|---|---|
| Xbox Green | `#9BC848` | Destaques e KPIs |
| Xbox Green (escuro) | `#22C55E` | Elementos secundários |
| Negative Zone | `#E8E6E9` | Indicadores negativos |

---

## 🛠️ Tecnologias Utilizadas

- **Microsoft Excel** — Tabelas dinâmicas, gráficos, segmentações de dados (slicers) e formatação condicional

---

## 🚀 Como Usar

1. **Clone ou baixe** este repositório
2. Abra o arquivo `DashboardXboX.xlsx` no **Microsoft Excel** (versão 2016 ou superior recomendada)
3. Acesse a aba **Dashboard** para visualizar o painel completo
4. Utilize os **slicers (segmentadores)** para filtrar os dados por plano, tipo de assinatura ou período
5. Explore a aba **Cálculos** para entender as análises por pergunta de negócio

> ⚠️ **Atenção:** Para melhor experiência, abra o arquivo no Excel para desktop. Algumas funcionalidades de slicers e gráficos podem ter renderização limitada no Excel Online ou Google Sheets.

---

## 👤 Autor

Realizado como parte da trilha de **Análise de Dados com Excel** na [DIO](https://www.dio.me/).
