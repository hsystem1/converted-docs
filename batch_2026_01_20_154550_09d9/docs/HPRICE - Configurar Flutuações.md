**Configurar Flutuações HPRICE**

**O que é flutuações no Hprice**

A tela **Configurar Flutuações** é o coração da automação de preços do HPRICE. É aqui que você define como o sistema deve **reagir automaticamente às variações de demanda**, ajustando as tarifas nos canais de venda sempre que uma nova leitura de mercado ou ocupação é realizada.

Sempre que o HPRICE executa uma leitura, todas as **regras configuradas nesta tela são avaliadas**. Caso as condições sejam atendidas, o sistema recalcula as tarifas e envia automaticamente os novos valores aos canais de venda.

Por isso, esta funcionalidade deve ser utilizada com atenção e estratégia: ela substitui a necessidade de ajustes manuais constantes e garante coerência na aplicação dos seus preços.

**Objetivo da funcionalidade**

O objetivo principal da **Configuração de Flutuação** é **gerenciar o ciclo de vida das estratégias de preços dinâmicos** do hotel, definindo:

* Quando os preços devem subir
* Quando os preços devem baixar
* Para quais datas as regras são válidas
* Em quais condições de ocupação ou demanda as alterações devem ocorrer

Com isso, o HPRICE assegura que o hotel pratique sempre o **preço certo, no momento certo**, maximizando receita e reduzindo riscos de subprecificação ou perda de oportunidades.

**Casos de Uso – Por que usar Flutuação?**

### **Alta Ocupação / Picos de Demanda**

* **Garantia de Preço Máximo**
* Quando a ocupação atinge um determinado patamar (por exemplo, 80% ou 90%), a regra de flutuação pode:
* Aumentar a tarifa em **10%**, ou
* Aplicar um acréscimo fixo, como **R$ 50,00**
* Isso garante que o hotel capture o máximo valor em momentos de alta demanda, sem necessidade de monitoramento manual constante.

### **Baixa Ocupação / Vendas Lentas**

* **Estímulo à Venda**
* Em cenários de baixa demanda, a flutuação pode:
* Reduzir a tarifa em **5%**, ou
* Aplicar uma redução fixa, como **R$ 30,00**
* Essa estratégia torna o preço mais competitivo e estimula a entrada de novas reservas.

### **Sazonalidade, Eventos e Feriados**

* **Tarifa Otimizada para Datas Específicas**
* É possível criar conjuntos de regras dedicados para períodos especiais, como:
* Ano Novo
* Carnaval
* Eventos regionais
* Essas regras podem utilizar tarifas base mais altas ou flutuações mais agressivas, garantindo o melhor aproveitamento de datas com alta previsibilidade de demanda.

### **Últimas Unidades Disponíveis**

* **Captura de Valor pela Escassez**
* Quando restam poucos quartos disponíveis, a flutuação pode aumentar significativamente o preço, explorando a escassez do produto e maximizando a receita por unidade vendida.

**Importante! É nesta tela que irão constar todos os cadastros de estratégias vigentes e vencidas, também fazer bloqueios de flutuação.**

**Acesso a funcionalidade**

## **Acesso à Funcionalidade**

**Caminho no sistema:**

Menu superior → **Flutuação** → **Configurar Flutuações**

Nesta tela ficam disponíveis:

* Regras de Flutuação ativas
* Regras Vencidas
* Períodos de Flutuação Bloqueada

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_20_154550_09d9/images/HPRICE_-_Configurar__image8_1aa0f344.png)

## **Configuração de Flutuação**

### **Localização**

Acesse a aba **Regras de Flutuação**.

### **Opção 1: Criar um Novo Conjunto de Regras**

Clique em **Adicionar novo conjunto de regras de flutuação**.

Cada conjunto representa uma **estratégia específica**, aplicada a um determinado período e comportamento de demanda.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_20_154550_09d9/images/HPRICE_-_Configurar__imagee_57c51f71.png)

**Opção 2: Preenchimento do Conjunto de Regras**

#### **Descrição**

* Informe um nome claro para identificar a estratégia, por exemplo:
* REGRA GERAL – BAIXA DEMANDA
* FERIADOS 2025
* FINAIS DE SEMANA – ALTA OCUPAÇÃO

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_20_154550_09d9/images/HPRICE_-_Configurar__image3_2f1a4cd1.png)

**Datas**

* Defina:
* Data inicial e final de vigência
* Dias da semana em que a regra será aplicada
* Caso seja necessário criar múltiplos períodos dentro da mesma estratégia, utilize o botão **“+” (Adicionar períodos)**.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_20_154550_09d9/images/HPRICE_-_Configurar__imaged_c6601463.png)

**Faixa de Ocupação**

* Informe a porcentagem de ocupação em que a flutuação será acionada.
* Você pode calcular essa faixa com base:
* Na quantidade total de quartos
* No número de unidades que deseja flutuar
* Exemplo:
* De 60% a 70%
* De 71% a 85%
* Acima de 86%

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_20_154550_09d9/images/HPRICE_-_Configurar__image5_1c56d862.png)

**Preço**

* Defina a tarifa que será enviada para cada faixa de ocupação, podendo ser:
* Um valor fixo
* Um percentual de aumento ou redução

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_20_154550_09d9/images/HPRICE_-_Configurar__image7_ffc3933b.png)

**Importante:** Todas essas informações juntas formam a regra de flutuação. O HPRICE respeita exatamente o que está configurado. Não serão enviados preços para datas ou condições que não estejam cadastradas.

### **Opção 3: Integração com BARs**

Para que a flutuação funcione corretamente, é obrigatório que o hotel já tenha realizado o cadastro das **BARs (Best Available Rate)**.

Nesta etapa, o sistema utiliza as BARs como **tarifa base**, sobre a qual as regras de flutuação irão atuar, aplicando aumentos ou reduções conforme a ocupação e o período configurado.

Pontos importantes desta opção:

* A flutuação **não cria tarifas do zero**: ela sempre trabalha sobre uma BAR existente
* Qualquer alteração feita em uma BAR impacta diretamente as regras de flutuação associadas
* Caso não exista BAR cadastrada, a regra de flutuação não será aplicada

Essa opção garante consistência, padronização e rastreabilidade dos preços enviados aos canais.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_20_154550_09d9/images/HPRICE_-_Configurar__image4_b06b5c3b.png)

### **Integração com BARs**

Para que a flutuação funcione corretamente, é necessário que o hotel já tenha realizado o cadastro das **BARs (Best Available Rate)**.

As regras de flutuação sempre atuam **sobre uma BAR existente**, ajustando seus valores conforme as condições definidas.

### **Salvando a Regra**

Ao clicar em **Salvar**, um pop-up de confirmação será exibido.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_20_154550_09d9/images/HPRICE_-_Configurar__image6_23fde94a.png)

Ao confirmar em **SIM**, o HPRICE enviará imediatamente a correção das tarifas aos canais de venda.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_20_154550_09d9/images/HPRICE_-_Configurar__imagea_ef05b050.png)

## **Boas Práticas e Observações Importantes**

* Crie conjuntos diferentes para demandas **alta, média e baixa**
* Utilize conjuntos específicos para **finais de semana** ou **datas especiais**
* Não é permitido cadastrar o **mesmo período em dois conjuntos diferentes**
* O HPRICE pode enviar flutuações para até **2 anos à frente**, desde que exista disponibilidade

**Opção 4: Regras Vencidas**

### **Localização**

* Na tela **Flutuação → Configurar Flutuações**, localize e clique na aba **Regras Vencidas**.

### **O que são Regras Vencidas?**

* As **Regras Vencidas** são conjuntos de flutuação cujo período de aplicação já foi encerrado. Diferentemente da aba **Regras de Flutuação**, que exibe apenas as estratégias ativas, esta aba funciona como um **histórico estratégico** das regras que já foram utilizadas pelo hotel.
* Essa visualização é fundamental para análise de resultados, aprendizado e reaproveitamento de estratégias que tiveram bom desempenho.

### **Informações exibidas em cada regra vencida**

* Ao visualizar uma regra vencida, você terá acesso às seguintes informações:
* **Identificação da Estratégia:** Nome definido no cadastro, como por exemplo “REGRA GERAL 2024” ou “FERIADOS 2024”. Esse nome ajuda a entender rapidamente o contexto em que a regra foi utilizada.
* **Período de Ativação (Vencido):** Indica a data de início e fim em que a regra esteve ativa.
  + Exemplo: a estratégia “REGRA GERAL 2024” pode ter sido aplicada de **17/09/2024 até 11/10/2024**.
* **Dias da Semana Impactados:** Mostra em quais dias da semana a regra foi aplicada, representados pelas iniciais (S, T, Q, Q, S, S, D).
* **Regras Registradas:** Indica quantas condições de flutuação faziam parte daquele conjunto, como por exemplo “5 regras registradas”.
* Essas informações permitem avaliar rapidamente o escopo e a complexidade da estratégia utilizada.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_20_154550_09d9/images/HPRICE_-_Configurar__image_5159594b.png)

### **Opção 5: Ações sobre as Regras Vencidas**

Mesmo após o encerramento do período de vigência, as regras continuam com ações disponíveis no lado direito da tela:

* ️ **Editar (Lápis):** Permite visualizar as condições internas configuradas naquela estratégia. É ideal para análise de desempenho e entendimento do comportamento aplicado.
* **Duplicar / Copiar (Ícone de Documento):** Permite criar uma regra a partir de uma estratégia já existente. Por exemplo, se a regra “FERIADOS 2024” apresentou bons resultados, você pode duplicá-la e ajustá-la para “FERIADOS 2025”, economizando tempo e evitando retrabalho.
* **Excluir (Lixeira):** Remove permanentemente o histórico dessa regra vencida. Use esta opção com cautela.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_20_154550_09d9/images/HPRICE_-_Configurar__image2_481d1859.png)

## **Opção 6: Flutuação Bloqueada**

### **Localização**

Na tela **Flutuação → Configurar Flutuações**, clique na aba **Flutuação Bloqueada**.

### **O que é Flutuação Bloqueada?**

A **Flutuação Bloqueada** permite suspender temporariamente a aplicação das regras automáticas de preços em períodos específicos. Durante o bloqueio, o sistema não executa nenhuma flutuação, mesmo que existam regras ativas configuradas.

Essa opção é indicada para períodos que exigem controle manual total, como eventos específicos, negociações diretas ou ajustes estratégicos pontuais.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_20_154550_09d9/images/HPRICE_-_Configurar__image9_7e39eeb2.png)

### **Como configurar um período de bloqueio**

1. Clique no botão **+ Adicionar período de flutuação bloqueada**.
2. No campo **“De”**, informe a data de início do bloqueio manual (exemplo: 13/03/2025).
3. No campo **“Até”**, informe a data final do bloqueio (exemplo: 31/03/2025).
4. Após configurar todos os períodos desejados, clique em **Salvar Alterações** para concluir.

Durante o período bloqueado, o HPRICE respeitará apenas os valores definidos manualmente, sem aplicar regras automáticas.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_20_154550_09d9/images/HPRICE_-_Configurar__imagec_3a94f429.png)

**Variáveis disponíveis nesta tela**

* **Regras de Flutuação:** Estratégias ativas no período atual.
* **Regras Vencidas:** Histórico de estratégias já encerradas.
* **Flutuação Bloqueada:** Períodos em que a automação está temporariamente suspensa.

## **Glossário**

|  |  |
| --- | --- |
| **Termo** | **Definição** |
| **Flutuação** | Mecanismo automático do HPRICE que ajusta as tarifas com base em regras pré-configuradas, considerando ocupação, demanda e estratégia do hotel. |
| **Regras de Flutuação** | Conjunto de condições que determinam quando e como os preços devem subir ou descer automaticamente. |
| **Regras Vencidas** | Estratégias de flutuação cujo período de aplicação já foi encerrado. Servem como histórico para análise, aprendizado e reaproveitamento. |
| **Período de Ativação** | Intervalo de datas em que uma regra de flutuação esteve ativa e enviando preços aos canais. |
| **Duplicar Regra** | Ação que cria uma estratégia a partir de uma regra existente, permitindo reaproveitar configurações anteriores com novos ajustes. |
| **Flutuação Bloqueada** | Funcionalidade que suspende temporariamente a aplicação automática de flutuações em datas específicas. |
| **Bloqueio Manual** | Definição feita pelo usuário para impedir que o sistema altere preços automaticamente durante um período determinado. |
| **HPRICE** | Produto de Revenue Management responsável por apoiar a estratégia de precificação, análise de mercado e automação de tarifas do hotel. |