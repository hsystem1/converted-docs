**KPIs na tela de análise no HPRICE**

## **O que é a tela de KPIs**

A tela de **KPIs (Indicadores‑chave de Performance)** do **HPRICE** foi criada para ajudar o gestor a **definir, acompanhar e analisar seus objetivos de receita de forma contínua**.

Por meio dessa tela, você consegue visualizar se o desempenho do hotel está **acima, dentro ou abaixo do esperado**, acompanhando os principais indicadores do negócio de maneira clara e visual.

O acompanhamento frequente dos KPIs permite ajustes rápidos na estratégia de preços, evitando decisões tardias que possam impactar negativamente a receita.

## **Objetivo da Funcionalidade**

O principal objetivo da tela de KPIs é permitir que você saiba, de forma objetiva:

* Se está **à frente** ou **defasado** em relação às metas definidas
* Como sua estratégia de preços está performando
* Onde é necessário corrigir rota para maximizar resultados

Ter clareza sobre esses indicadores ajuda a tomar **decisões mais seguras e embasadas**, especialmente em relação à precificação.

## **Por que utilizar a tela de KPIs (Casos de Uso)**

### **Diária Média (ADR)**

A **Diária Média** mede a eficácia da sua estratégia de preços, indicando **quanto o hotel cobra, em média, pelos quartos vendidos**.

Esse indicador ajuda a entender se:

* As tarifas estão muito baixas para a demanda
* Há espaço para incremento de preços
* A estratégia promocional está impactando negativamente a receita média

### **RevPAR**

O **RevPAR (Receita por Quarto Disponível)** mede a eficiência geral do hotel em:

* Preencher seus quartos
* Maximizar a receita por meio de preços estratégicos

Esse KPI combina ocupação e tarifa, sendo um dos principais indicadores de sucesso em Revenue Management.

### **Ocupação e Receita Total**

Esses indicadores mostram **quão bem o hotel está utilizando sua capacidade máxima de hospedagem**.

Eles permitem avaliar:

* Volume de vendas
* Capacidade de absorção da demanda
* Impacto financeiro do desempenho operacional

## **Onde acessar a tela de KPIs**

Para acessar essa funcionalidade no HPRICE:

**Menu → Análises → KPIs**

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_104013_8da4/images/HPRICE_-_Ana%CC%81lises_-_image3_f6729877.png)

## **Como os dados de KPIs são alimentados**

Para que a visualização dos KPIs seja consistente, é necessário que o sistema receba dados de ocupação e receita.

Isso pode ocorrer de duas formas:

* **Integração com PMS** (automática)
* **Upload manual de planilha**, quando não há integração

## **Configuração dos Indicadores KPIs**

### **Onde configurar**

O envio das informações que alimentam os KPIs é realizado em:

**Menu → Upload → PMS KPI**

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_104013_8da4/images/HPRICE_-_Ana%CC%81lises_-_image6_1330a595.png)

**Opção 1: KPIs com integração com PMS**

* Quando o HPRICE está integrado a um PMS, os seguintes indicadores ficam disponíveis automaticamente:
* Receita
* Taxa de Ocupação
* Diária Média (ADR)
* RevPAR
* UH’s Ocupadas
* Esses dados são recebidos diretamente do sistema hoteleiro, reduzindo a necessidade de ações manuais.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_104013_8da4/images/HPRICE_-_Ana%CC%81lises_-_image9_c4a2fcf1.png)

**Opção 2: KPIs sem integração com PMS**

* Quando não há integração com PMS, o usuário pode carregar os dados manualmente por meio de planilha.
* Nesse cenário, ficam disponíveis os indicadores:
* Receita
* Taxa de Ocupação
* Room Nights

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_104013_8da4/images/HPRICE_-_Ana%CC%81lises_-_image8_c1018700.png)

### **Como realizar o upload manual de KPIs**

1. Acesse **Upload → PMS KPI**
2. Clique em **Baixar planilha modelo**
3. Preencha os seguintes campos:
   1. Datas
   2. Percentual de ocupação
   3. UH’s ocupadas
   4. Diária média
   5. RevPAR
   6. Receita do dia
4. Salve a planilha
5. Faça o upload no sistema

Esse upload pode ser realizado:

* Diariamente
* Quinzenalmente
* Mensalmente

O objetivo é criar um **histórico consistente de evolução de receita e desempenho**.

## **Visualização e Análise dos KPIs**

### **Seleção de período e tipo de gráfico**

Após os dados estarem carregados, você pode:

* Escolher o período de análise
* Definir a forma de visualização do gráfico

Com base nessas informações, é possível **definir metas mensais para cada indicador**.

### **Agrupamento de dados**

Na tela **Análises → KPIs**, você pode agrupar os dados de duas formas:

* **Por Mês**
* **Por Dia**

**Importante:** No agrupamento por dia, o sistema limita o período de análise a **60 dias**, garantindo melhor performance e clareza visual.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_104013_8da4/images/HPRICE_-_Ana%CC%81lises_-_image2_e3d6d6c6.png)

## **Filtros de Comparação**

A tela de KPIs permite diferentes formas de comparação:

* **Sem comparação**
  Apenas visualização dos dados do período selecionado.
* **Comparar com o mesmo período no ano de**
  Permite analisar a evolução do desempenho em relação a outro ano.
* **Comparar com a fotografia no dia**
  Mostra como estavam os indicadores em uma data passada, funcionando como um histórico de desempenho.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_104013_8da4/images/HPRICE_-_Ana%CC%81lises_-_image7_9a8f61bb.png)

## **Filtros de Período e Metas**

### **Mês Atual**

* Visualização do desempenho do mês vigente
* Possibilidade de comparar com o mesmo período do ano anterior
* Gráfico apresentado em **linhas**

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_104013_8da4/images/HPRICE_-_Ana%CC%81lises_-_image4_d2382093.png)

### **Ano Atual**

* Visualização consolidada do ano
* Comparação com metas anuais
* Gráfico apresentado em **barras**

Ao selecionar **Ano Atual**, o botão **Definir Metas** será exibido entre o gráfico e a tabela.

Ao clicar nesse botão:

1. Uma planilha em branco será aberta
2. Preencha as metas mensais da propriedade
3. Salve as informações

Essas metas passam a ser utilizadas nas comparações do dashboard.

### **Detalhamento avançado (sem PMS integrado)**

Para propriedades **sem integração com PMS**, a visualização de **Ano Atual** disponibiliza o botão **Detalhar**.

Ao clicar nele, você terá acesso ao padrão de comportamento de compra dos clientes, com detalhamento por:

* Segmento (direto, OTA, operadora)
* Dia da semana
* Janela de compra (antecedência da reserva)
* Canal
* Tamanho da estadia
* Tipo de quarto

Essas informações são fundamentais para ajustes finos na estratégia comercial.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_104013_8da4/images/HPRICE_-_Ana%CC%81lises_-_image_27352b9e.png)

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_104013_8da4/images/HPRICE_-_Ana%CC%81lises_-_image5_cbaf5150.png)

## **Glossário**

**HPRICE** – Produto voltado à estratégia tarifária e gestão de receitas.

**KPI (Key Performance Indicator)** – Indicador‑chave de performance.

**ADR (Diária Média)** – Valor médio das diárias vendidas.

**RevPAR** – Receita por quarto disponível.

**UH (Unidade Habitacional)** – Quarto disponível para venda.

**Room Nights** – Número total de diárias vendidas.

**PMS (Property Management System)** – Sistema de gestão hoteleira.