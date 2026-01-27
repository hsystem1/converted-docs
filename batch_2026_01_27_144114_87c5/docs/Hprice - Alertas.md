# **HPRICE – Alertas Inteligentes de Mercado**

**O que é a tela de alertas no Hprice**

A tela de **Alertas** do **Hprice (Flutuação)** foi criada para que você acompanhe o mercado **sem precisar monitorar tudo manualmente**.

Aqui, você configura **alertas inteligentes** que notificam automaticamente quando acontecem mudanças relevantes nos **preços**, **ocupação** ou **disponibilidade**, tanto da sua propriedade quanto dos seus concorrentes.

Esses alertas funcionam como um **radar de mercado**, ajudando você a reagir rapidamente a oportunidades ou ameaças.

**Objetivo da funcionalidade**

Nesta tela, você aprende a configurar **alertas inteligentes de mercado**, que avisam automaticamente quando ocorrerem mudanças importantes nos preços, ocupação ou disponibilidade — tanto na sua propriedade quanto nos concorrentes.
 Esses alertas são uma ferramenta poderosa para **monitorar o comportamento do mercado em tempo real** e reagir rapidamente a oportunidades ou ameaças.

## **Objetivo da Funcionalidade**

A funcionalidade de Alertas tem como objetivo:

* Automatizar o monitoramento do mercado;
* Identificar mudanças importantes em tempo real;
* Apoiar decisões rápidas de Revenue Management;
* Reduzir riscos de perda de competitividade;
* Possibilitar ações automáticas de flutuação de preços.

Em resumo, essa tela responde à pergunta:
 **“Quando algo importante mudar no mercado, como fico sabendo imediatamente?”**

**Caminho de acesso:**
Menu superior → Alertas

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_144114_87c5/images/Hprice_-_Alertas_image_12e7445f.png)

**Entendendo a tela**

Logo no topo, há uma seção de **filtros**, que permite organizar e visualizar seus alertas de forma prática.
 Você pode filtrar por:

* **Descrição**: nome que identifica cada alerta.
* **Condições**: Filtra o tipo de situação que dispara o alerta.

Você pode escolher entre quatro tipos de filtros em **condições**:

1. **Ocupação:** monitora quando o nível de ocupação muda — ótimo para acompanhar picos de reservas.
2. **Disponibilidade:** identifica quando algum concorrente abre ou fecha quartos para venda.
3. **Alteração de Preço:** avisa quando há aumento ou diminuição nas tarifas.
4. **Comparação de Preço:** compara suas tarifas com as dos concorrentes e alerta quando há diferença percentual ou de valor.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_144114_87c5/images/Hprice_-_Alertas_image2_36c8da88.png)

* **Ações**: Filtra com base na ação, podendo ser “qualquer”, puxa todos os tipos de alertas e o “Flutuação de preço”, busca os alertas que tenham flutuações atreladas.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_144114_87c5/images/Hprice_-_Alertas_image11_4fb27b7b.png)

Abaixo, é exibida a tabela principal com as colunas:

* **Descrição:** nome do alerta criado (exemplo: “Aumento de 1%”, “Preço menor que o meu em R$5”).
* **Condições:** o tipo de monitoramento (como alteração de preço ou disponibilidade).
* **Datas:** em quais dias da semana esse alerta deve ser considerado.
* **Ações:** o que será feito quando o alerta for disparado.
* Botões de **editar**️ ou **excluir** o alerta.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_144114_87c5/images/Hprice_-_Alertas_image1a_e542b35f.png)

**Criando um alerta**

Para criar um alerta, clique no botão **“Novo alerta”** no canto superior direito.
Ao clicar em **“Novo alerta”**, o sistema abre um assistente dividido em **cinco etapas**, que você deve seguir na sequência:

1. **Período**
2. **Condições**
3. **Ações**
4. **Detalhes**
5. **Final**

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_144114_87c5/images/Hprice_-_Alertas_image1d_cfb1b095.png)

Na primeira etapa, você define **em quais datas o alerta deve ser verificado**.
 O sistema exibe duas opções:

* **Qualquer Data:**
   O alerta será válido continuamente, para todos os dias do calendário.
   Essa opção é ideal para monitoramentos permanentes, como “alertar quando um concorrente baixar o preço”.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_144114_87c5/images/Hprice_-_Alertas_image21_54462ed2.png)

* **Período Específico:**
   Permite determinar um intervalo de datas exato, como um feriado, evento ou temporada.
   Excelente para acompanhar movimentações de preço em períodos estratégicos, como “Réveillon” ou “Carnaval”.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_144114_87c5/images/Hprice_-_Alertas_image16_097339c8.png)

Para avançar para a próxima etapa, é **obrigatório selecionar uma das duas opções**.
 Somente após escolher o tipo de período o botão **“Continuar”** será habilitado.

Na segunda etapa, é a área onde você construirá a lógica do seu alerta.

No canto superior direito, você encontra o botão **"Nova condição +"** que, ao ser clicado, revela um dropdown com **6 tipos de condições**:

1. Alteração de preço

Monitora mudanças nos valores da concorrência.

2. Comparação de preço

Compara seus preços com outras fontes (como OTAs ou concorrentes).

3. Disponibilidade na praça

Verifica a disponibilidade de quartos no mercado.

4. Ocupação da sua propriedade

Monitora seus níveis de ocupação.

5. Antecedência da data

Define alertas baseados em quanto tempo falta para a data de check-in. Esta é a única condição que **NÃO pode ser usada sozinha**. Ela sempre deve ser combinada com pelo menos uma das outras condições.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_144114_87c5/images/Hprice_-_Alertas_imagea_4460d590.png)

**Estrutura Geral das condições**

Cada condição selecionada aparece como uma linha editável com campos específicos. Você pode adicionar múltiplas condições que trabalham em conjunto.

1. Alteração de preço

Primeiro campo de preenchimento, selecionar se houve “aumento no preço” ou “diminuição do preço”.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_144114_87c5/images/Hprice_-_Alertas_imagee_a3822fe9.png)

Em seguida qual o valor e se em reais ou porcentagem.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_144114_87c5/images/Hprice_-_Alertas_image19_303be938.png)

Por fim, qual a categoria ou todas.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_144114_87c5/images/Hprice_-_Alertas_image1c_a3778100.png)

2. Comparação de preço

Primeiro campo de preenchimento é de quando o preço for “maior que o meu” ou “menor que o meu”

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_144114_87c5/images/Hprice_-_Alertas_image1e_5949ab95.png)

Em seguida qual o valor e se em reais ou porcentagem.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_144114_87c5/images/Hprice_-_Alertas_image3_ab43a074.png)

Por fim, qual a categoria ou todas.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_144114_87c5/images/Hprice_-_Alertas_image7_28c8b44f.png)

Campos complementares (Para a seguinte combinação de quarto/tarifa):

Número de pessoas (Qualquer, 1 pessoa, 2 pessoas, ..., 5 pessoas)

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_144114_87c5/images/Hprice_-_Alertas_image8_f861e0bd.png)
Pensão (Todos, Café, sem refeição, meia pensão, pensão completa)

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_144114_87c5/images/Hprice_-_Alertas_imagec_20a9ee55.png)

Cancelamento (Todos, Flex, NR, parcial)

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_144114_87c5/images/Hprice_-_Alertas_image5_9fd5d75b.png)

3. Disponibilidade na praça

Primeiro campo de preenchimento é de quando houver “aumento de disponibilidade” ou “redução de disponibilidade”

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_144114_87c5/images/Hprice_-_Alertas_image6_918c4baa.png)

Em seguida qual o valor e se em quartos ou porcentagem.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_144114_87c5/images/Hprice_-_Alertas_imageb_3872cd01.png)

Por fim, qual a categoria ou todas.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_144114_87c5/images/Hprice_-_Alertas_image13_fb5f804f.png)

4. Ocupação da sua propriedade

Primeiro campo de preenchimento quando a taxa de ocupação estiver “acima de” ou “abaixo de”

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_144114_87c5/images/Hprice_-_Alertas_image9_3237ec3b.png)

Em seguida qual o valor em porcentagem.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_144114_87c5/images/Hprice_-_Alertas_imagef_eb89d383.png)

5. Antecedência da data

Preencher se a antecedência é “maior” ou “menor” e quantos dias.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_144114_87c5/images/Hprice_-_Alertas_image10_cc5f425e.png)

Na Etapa 3 – Ações, é onde você define o que o sistema deve fazer quando as condições configuradas forem atendidas.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_144114_87c5/images/Hprice_-_Alertas_image15_79bd04b9.png)

Nessa etapa, o sistema apresenta **duas opções de ação**:

1. **Mostrar no calendário**
   1. Essa opção já vem **marcada automaticamente** e **não pode ser alterada**.
   2. Significa que, sempre que o alerta for ativado, ele será exibido no **calendário de tarifas**, permitindo que você visualize diretamente quando e por que ele foi disparado.
   3. É apresentado também na tela de histórico (Flutuação --> Histórico – aba flutuações e marca o flag “Mostrar apenas flutuação feita por alertas”

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_144114_87c5/images/Hprice_-_Alertas_image1b_77789ccb.png)

**2 Flutuar preço**

* 1. Essa é a opção que **ativa uma ação automática de ajuste tarifário**.
  2. Quando o sistema identifica que as condições do alerta foram atingidas (por exemplo: “concorrente baixou o preço em 5%”), ele **toma a decisão de flutuar o preço** da sua tarifa conforme a regra que você configurar aqui.

Ao habilitar a ação **Flutuar preço**, surgem novas opções de configuração:

* **Escolher a base da flutuação (BAR):**
   Você pode selecionar **uma BAR existente** como referência para o novo preço.
   O sistema aplicará a variação automaticamente com base nela.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_144114_87c5/images/Hprice_-_Alertas_image1f_946f8eaf.png)

* **Preço customizado:**
   Se preferir, você pode optar por **definir valores manuais** para cada categoria de acomodação.
   Isso dá total controle sobre o preço aplicado quando o alerta é acionado.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_144114_87c5/images/Hprice_-_Alertas_image20_9f2527c9.png)

* **Carregar preços de BARs com diferença percentual:**
   Essa opção permite **usar os preços de outra BAR como base**, mas aplicando **um percentual de ajuste** (para cima ou para baixo).
   Exemplo: usar a “BAR Flexível” e aplicar um desconto de 10%

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_144114_87c5/images/Hprice_-_Alertas_imaged_8b464e19.png)

**Etapa 4 – Detalhes**.
 Essa é a parte onde você **dá identidade e foco ao seu alerta**, definindo como ele será exibido e **para quais concorrentes ele deve ser aplicado**.

Descrição do Alerta

O primeiro campo dessa etapa é o **campo de descrição**.

* Ele é **obrigatório** e serve para **nomear o alerta**, facilitando a identificação depois na lista geral de alertas.
* Aqui você pode colocar um nome curto e direto, que descreva bem o objetivo do alerta.

*Exemplo:*

* “Concorrente baixou preço em 5%”
* “Aumento de tarifa em fim de semana”

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_144114_87c5/images/Hprice_-_Alertas_image17_bd839bdf.png)

Analisar os seguintes concorrentes

O segundo campo define **quais concorrentes serão monitorados** por esse alerta.

Você terá duas opções principais:

1. **Todos os concorrentes**
   1. O sistema vai analisar automaticamente **todas as propriedades configuradas como concorrentes** do seu hotel.
   2. Ideal quando o alerta é genérico e vale para o comportamento de todo o mercado.
2. **Selecionar concorrentes específicos**
   1. Aqui você pode **escolher manualmente** quais concorrentes o sistema deve observar.
   2. Essa opção é útil quando você quer acompanhar **apenas concorrentes diretos ou estratégicos**, por exemplo: um hotel com o mesmo perfil ou nível de tarifa que o seu.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_144114_87c5/images/Hprice_-_Alertas_image4_0acdfbe1.png)

Chegamos à última etapa da criação de um alerta no HPrice: a **Etapa 5 – Final**.
 Aqui é o momento de **revisar todas as informações** que você configurou nas etapas anteriores antes de salvar o alerta definitivamente.

**Revisando o resumo do alerta**

Na tela, o sistema apresenta um **resumo completo** do seu alerta, com todos os detalhes preenchidos.
 É importante conferir cada item para garantir que está tudo correto — afinal, é com base nessas informações que o sistema vai identificar os movimentos de mercado e reagir automaticamente.

Você verá algo assim:

Exemplo de revisão:

**Confirme seu alerta:**

* **Descrição:** Aumento de R$0
* **Condições:** Alteração de preço
* **Ações:** Mostrar no calendário
* **Concorrentes:** Hotel Guarulhos, Hotel Paulista
* **Período:** Qualquer data
* **Nos dias:**
   Seg
   Ter
   Qua
   Qui
   Sex
   Sáb
   Dom

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_144114_87c5/images/Hprice_-_Alertas_image12_be7ac34e.png)

Botão “Criar +”

Depois de validar as informações, basta clicar no botão **“Criar +”**, que aparece em **laranja** no canto inferior direito da tela.
 Esse botão **salva e finaliza a criação do alerta**, tornando-o ativo no sistema.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_144114_87c5/images/Hprice_-_Alertas_image14_07e75188.png)

Assim que o alerta for criado com sucesso, ele será exibido na **tela de Configuração de Alertas**, junto com os demais que você já possui.

**Gerenciando Prioridades de Alertas de Flutuação no Sistema HPrice**

Vamos explorar agora uma funcionalidade crucial quando você trabalha com **múltiplos alertas de flutuação**: o sistema de **Prioridades**. Esta ferramenta resolve um desafio comum: o que acontece quando mais de um alerta é acionado para a mesma data?

Quando o Botão "Prioridade" Aparece?

O botão **"Prioridade"** (com ícone de lápis) surge automaticamente ao lado do botão **"Novo alerta"** (laranja) quando você possui **mais de um alerta configurado** com ações de flutuação de preço.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_144114_87c5/images/Hprice_-_Alertas_image18_8870170a.png)

**A Tela de Prioridade dos Alertas**

Ao clicar no botão "Prioridade", uma janela modal se abre com o título:

"Prioridade dos alertas de flutuação" ⓘ

O ícone ⓘ ao lado do título fornece informações adicionais sobre como funciona o sistema de prioridades.

Aviso Importante

No topo da modal, há uma mensagem explicativa em um banner cinza:

"Quando houver mais de um alerta na mesma data, será realizada a ação do alerta superior na lista. Arraste os alertas para reordenar."

**A Tabela de Prioridades**

A tabela possui 5 colunas principais:

1. Prioridade (com ícone de ordenação ≡)

Mostra a ordem numérica dos alertas

O ícone **≡** (três linhas horizontais) indica que você pode **arrastar e soltar** as linhas para reordenar.

2. Descrição

Nome ou descrição personalizada do alerta

3. Ações

Descreve o que o alerta fará quando acionado

4. Condições

Mostra as condições que acionam o alerta

5. Datas

Período de validade do alerta

**Como Reordenar as Prioridades**

Passo a Passo:

1. **Clique e segure** no ícone **≡** da linha que deseja mover
2. **Arraste** a linha para cima ou para baixo
3. **Solte** na nova posição
4. Os números de prioridade se **ajustam automaticamente**
5. Clique em **"Salvar"** para confirmar as mudanças

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_144114_87c5/images/Hprice_-_Alertas_image22_9319cc9c.png)

## **Glossário**

**Alerta**
 Regra automática que monitora o mercado.

**Flutuação de Preço**
 Ajuste automático de tarifas baseado em regras.

**BAR**
 Best Available Rate – tarifa base.

**Disponibilidade na Praça**
 Oferta pública de quartos no mercado.

**Ocupação**
 Percentual de quartos vendidos.

**Antecedência**
 Dias entre hoje e a data de check-in.