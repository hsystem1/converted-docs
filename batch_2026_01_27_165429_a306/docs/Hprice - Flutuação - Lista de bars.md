**Lista de BARs | HPRICE**

**O que é lista de bar no Hprice**

A tela de **Lista de BARs** faz parte do módulo de **Flutuação do HPRICE** e é onde o hotel configura seus **níveis tarifários padrão**, conhecidos como **BAR (Best Available Rate)**.

Essa tela é fundamental para a estratégia de Revenue Management, pois define **o ponto de partida para todas as flutuações automáticas de preço**, tanto para aumentos quanto para reduções tarifárias.

Em termos práticos, as BARs funcionam como a **estrutura base de preços do hotel**, sobre a qual o HPRICE aplica inteligência de mercado, demanda e ocupação.

## **O que é BAR (Best Available Rate)**

**BAR** significa **Best Available Rate** (Melhor Tarifa Disponível) e representa o **tarifário base do hotel**, sem considerar descontos promocionais ou condições especiais.

No HPRICE, as BARs são utilizadas como referência para:

* Flutuações automáticas de preço
* Criação de tarifas derivadas
* Estratégias de posicionamento tarifário
* Comparações de mercado

Uma BAR bem configurada é essencial para que a flutuação funcione de forma correta e previsível.

## **Objetivo da Funcionalidade**

O objetivo da tela de Lista de BARs é permitir que o hotel:

* Cadastre seu **tarifário padrão**
* Estruture diferentes níveis de preço
* Defina a base para flutuações automáticas
* Garanta coerência e controle na estratégia tarifária

A ideia é que cada BAR represente um **nível estratégico de preço**, servindo como base para ajustes automáticos para cima ou para baixo.

## **Onde acessar a Lista de BARs**

Para acessar essa funcionalidade no HPRICE:

**Menu superior → Flutuação → Lista de BARs**

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_165429_a306/images/Hprice_-_Flutuac%CC%A7a%CC%83o_image2_0f51e566.png)

**Estrutura da Tela de Lista de BARs**

### **Botões de Ação**

* No canto superior direito da tela, você encontrará os principais botões de ação:

### **Ordenar BARs**

* O botão **Ordenar BARs** permite reorganizar a sequência em que as BARs aparecem na lista.
* Basta **arrastar e soltar** as BARs
* A ordem definida facilita a leitura e organização da estratégia tarifária

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_165429_a306/images/Hprice_-_Flutuac%CC%A7a%CC%83o_imagec_d7dab084.png)

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_165429_a306/images/Hprice_-_Flutuac%CC%A7a%CC%83o_imaged_8859e7f4.png)

### **Nova BAR (botão laranja)**

O botão **Nova BAR** é utilizado para criar níveis tarifários. Ao clicar nele, o sistema oferece **três formas diferentes de criação**.

## **ormas de Cadastro de BARs**

### **Opção 1: Criar BAR a partir do zero**

Ao escolher essa opção, você criará uma BAR totalmente nova.

Durante o cadastro, será necessário:

* Definir uma **descrição** para a BAR
* Informar um **código** (até 5 caracteres)
* Preencher manualmente os valores de tarifa

#### **Preenchimento por dia da semana**

A tela apresenta colunas referentes aos **dias da semana**.

Isso permite que o hotel:

* Aplique valores diferentes para dias específicos
* Defina, por exemplo, tarifas mais altas em finais de semana

Após preencher o valor do primeiro dia, é possível **replicar o preço para os demais dias da semana**, agilizando o processo.

Depois de preencher todas as informações, basta **salvar** para concluir a criação da tarifa base.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_165429_a306/images/Hprice_-_Flutuac%CC%A7a%CC%83o_image9_67d4858f.png)

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_165429_a306/images/Hprice_-_Flutuac%CC%A7a%CC%83o_imagea_d03a05e4.png)

### **Opção 2: Importar dados de outra BAR**

Essa opção permite criar uma BAR **com base em uma tarifa já existente**.

O processo funciona da seguinte forma:

1. Selecione a BAR de origem
2. Defina um valor de **acréscimo ou redução**
   1. Para redução, utilize o sinal de menos (**-**)
3. Escolha se o ajuste será:
   1. Em **porcentagem (%)** ou
   2. Em **valor fixo (R$)**

Após a conversão, os valores são trazidos para a nova BAR, onde você poderá:

* Ajustar preços manualmente
* Preencher descrição e código

Ao salvar, essa BAR também passa a ser considerada uma **tarifa base**.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_165429_a306/images/Hprice_-_Flutuac%CC%A7a%CC%83o_image5_5b26077e.png)

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_165429_a306/images/Hprice_-_Flutuac%CC%A7a%CC%83o_image6_248aa506.png)

### **Opção 3: Criar BAR derivada de outra**

As **BARs derivadas** são tarifas calculadas automaticamente a partir de uma BAR base.

Nesse formato, você deve:

* Selecionar a tarifa base em **“Derivada de”**
* Definir a diferença de valor:
  + Acréscimo ou redução (utilizando **-** para reduzir)
* Escolher a unidade:
  + Porcentagem (%) ou
  + Valor em reais (R$)

#### **Importante sobre BARs derivadas**

* Não é possível editar manualmente os valores por dia da semana
* As únicas edições permitidas são no **cabeçalho** (nome e código)
* A tarifa é recalculada automaticamente com base na BAR origem

Após salvar, a BAR derivada exibirá uma descrição lateral indicando:

* De qual tarifa ela deriva
* Qual o valor da diferença aplicada
* Qual a unidade utilizada (R$ ou %)

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_165429_a306/images/Hprice_-_Flutuac%CC%A7a%CC%83o_imagee_9dab5397.png)

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_165429_a306/images/Hprice_-_Flutuac%CC%A7a%CC%83o_image3_77d8ab31.png)

## **Observações Importantes**

* O **código da BAR** é essencial para identificar posteriormente qual tarifa está vigente em cada data
* Não é possível criar uma BAR derivada de outra BAR derivada
* BARs derivadas só podem ser criadas a partir de:
  + BARs criadas do zero
  + BARs importadas

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_165429_a306/images/Hprice_-_Flutuac%CC%A7a%CC%83o_imageb_db20e720.png)

## **A Tabela de BARs**

A lista de BARs é apresentada em formato de tabela, organizada em três colunas principais:

### **Nome**

Exibe o **nome da BAR** e seu respectivo **código**, facilitando a identificação.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_165429_a306/images/Hprice_-_Flutuac%CC%A7a%CC%83o_image_7544d4d9.png)

### **Descrição / Derivação**

Mostra como cada BAR se relaciona com uma tarifa principal, indicando se:

* É uma tarifa base
* É uma tarifa importada
* É uma tarifa derivada (e de qual BAR)

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_165429_a306/images/Hprice_-_Flutuac%CC%A7a%CC%83o_image8_60f91c5b.png)

### **Última Atualização**

Indica a **data e hora da última modificação** realizada na BAR.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_165429_a306/images/Hprice_-_Flutuac%CC%A7a%CC%83o_image4_4ffc702d.png)

**Ações por BAR**

* Ao lado de cada BAR, existem dois ícones de ação:
* **Editar (Lápis)** – Permite editar a BAR
* **Excluir (Lixeira)** – Permite excluir a BAR
* Essas ações facilitam ajustes rápidos na estratégia tarifária.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_165429_a306/images/Hprice_-_Flutuac%CC%A7a%CC%83o_image7_0bf421dd.png)

## **Importância da Lista de BARs no HPRICE**

A Lista de BARs é a base de toda a estratégia de flutuação do HPRICE.

Uma configuração bem estruturada garante:

* Flutuações mais precisas
* Menor risco de erro de preço
* Maior controle sobre a estratégia tarifária
* Coerência entre tarifas, mercado e demanda

## **Glossário**

|  |  |
| --- | --- |
| **Termo** | **Definição** |
| **HPRICE** | Produto de Revenue Management focado em precificação, ocupação e estratégia tarifária. |
| **BAR (Best Available Rate)** | Melhor Tarifa Disponível, base para a estratégia de preços. |
| **Tarifa Base** | Valor inicial da diária, utilizado como referência para flutuações. |
| **Tarifa Derivada** | Tarifa calculada automaticamente a partir de uma tarifa base. |
| **Flutuação** | Ajuste automático de preços conforme regras e comportamento de mercado. |
| **Revenue Management** | Estratégia de maximização de receita por meio de preços e disponibilidade. |