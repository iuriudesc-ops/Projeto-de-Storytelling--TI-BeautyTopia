# 🦋 Guia de Estruturação de Dashboards: Beautytopia
**Projeto:** Arquitetura Visual e Relatórios - SIMULARE
Este documento estabelece o escopo visual e estrutural para a criação dos dashboards e do relatório executivo da Beautytopia.

---

## 🎨 Identidade Visual (Design System)
As cores corporativas da Beautytopia devem ser aplicadas de forma estratégica para manter a sobriedade exigida em apresentações executivas.

| Cor | Hex Code | Aplicação no Dashboard |
| :--- | :--- | :--- |
| **Rosa Utopia** | `#D81B60` | Destaque de KPIs primários, barras principais em gráficos de receita e linhas de tendência do carro-chefe. |
| **Lilás Suave** | `#F3E5F5` | Fundos de tabelas, áreas de respiro, barras secundárias e bordas de divisões (cards). |
| **Chumbo Executivo**| `#212121` | Títulos, textos corridos, legendas e eixos X/Y dos gráficos (substitui o preto absoluto). |
| **Off-White** | `#FAFAFA` | Cor de fundo geral das lâminas e do dashboard para contrastar e ressaltar os gráficos. |

---

## 📊 1. Lâmina: Fundamentos de Marketing
**Objetivo da Tela:** Apresentar a performance comercial, o impacto das estratégias adotadas e a posição competitiva.

### Estrutura do Dashboard
* **KPIs (Cards Superiores):** * Market Share Atual (%)
  * Preço Médio Praticado vs. Média do Mercado
  * Índice de Demanda Atendida (%)
* **Gráfico Principal:** Gráfico de Linhas/Barras combinadas mostrando a evolução da Demanda Prevista vs. Vendas Realizadas ao longo dos períodos.
* **Área de Relatório (Caixa de Texto / Resumo Executivo):**
  * *Síntese Estratégica:* Espaço para descrever as decisões de Preço, Diferenciação e Propaganda.
  * *Análise de Impacto:* Breve texto justificando se o resultado da rodada foi positivo ou negativo.
  * *Posicionamento Final:* Card destacando a posição da empresa no ranking ao final do período.

---

## 🛒 2. Lâmina: Gestão de Compras e Adm. de Materiais
**Objetivo da Tela:** Demonstrar a eficiência na aquisição de insumos e saúde do estoque.

### Estrutura do Dashboard
* **KPIs (Cards Superiores):**
  * Saving/Economia de Compras (%)
  * Giro de Estoque
  * Índice de Compras Compulsórias/Emergenciais (%)
* **Gráficos:**
  * *Gráfico de Barras:* Custo Médio Unitário dos Insumos por fornecedor vs. Preço Base.
  * *Gráfico de Rosca:* Composição do Estoque atual (Quais insumos têm maior volume armazenado).
* **Tabela de Decisões:** Uma tabela simples evidenciando a relação entre os prazos de pagamento escolhidos e as taxas de juros evitadas/assumidas.

---

## 💰 3. Lâmina: Planejamento e Controle Financeiro
**Objetivo da Tela:** Traduzir a operação em indicadores econômicos e saúde financeira (foco na rentabilidade e insolvência).

### Estrutura do Dashboard (Indicadores Operacionais)
* **Gráfico de Barra C/Linha :** Composição da Receita Líquida (Participação % de cada serviço no total do período).
* **Gráfico de Barras Empilhadas:** Margem Bruta Geral (Receita total subtraindo Custo de Produtos Vendidos e Fretes).
* **Múltiplos Gráficos de Linha (Um para cada serviço):** Evolução de "Preço vs. Custo vs. Margem" ao longo das rodadas.

### Estrutura do Dashboard (Indicadores Econômico-Financeiros)
* **Cards de Alerta Rápido (KPIs):**
  * Liquidez Corrente (LC)
  * Endividamento Geral (EG)
  * Margem Operacional (MO) - *Com nota de rodapé comparando com a alíquota da RFB (8%).*
  * ROE (Retorno sobre o Patrimônio Líquido)
* **Gráficos de Evolução (Linha/Área):**
  * Evolução do EBITDA ao longo dos períodos.
  * Evolução do ROIC ao longo dos períodos.

---

## 👥 4. Lâmina: Fundamentos de Gestão de Pessoas
**Objetivo da Tela:** Analisar a eficiência do capital humano, as decisões de contratação e seus reflexos diretos na produção.

### Estrutura do Dashboard
* **KPIs (Cards Superiores):**
  * Índice de Satisfação/Motivação da Equipe
  * Produtividade (Horas Trabalhadas vs. Horas Ociosas)
  * Custo da Mão de Obra vs. Faturamento (%)
* **Gráfico Principal:** Gráfico de termômetro ou velocímetro medindo o "Gargalo Operacional" (Capacidade Máxima Instalada vs. Demanda Exigida).

