# **HUNIT - Atualizações em Massa**

# **Guia Completo de Gestão Centralizada de Preços, Disponibilidade e Restrições**

## **O que é a tela de Atualizações em Massa**

A tela de **Atualizações em Massa** é uma funcionalidade do sistema **Hunit** criada para facilitar o gerenciamento **centralizado** de tarifas, disponibilidade e restrições de hospedagem.

Por meio dessa tela, o hoteleiro consegue definir valores e regras para diferentes tipos de quartos e **aplicar essas informações simultaneamente em vários canais de venda**, de forma prática e organizada.

Essa funcionalidade é especialmente útil quando o hotel precisa realizar ajustes para períodos maiores, datas específicas ou aplicar a mesma regra em diversos canais ao mesmo tempo, evitando atualizações manuais repetitivas.

## **Onde localizar a tela de Atualizações em Massa**

Para acessar essa funcionalidade no sistema Hunit, siga o caminho abaixo:

**Menu superior → Atualizações → Atualizações**

Ao acessar essa opção, o sistema abrirá a tela de **Atualizações em Massa**, onde todo o gerenciamento é realizado.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_20_154550_09d9/images/Hunit_-_Atualizaçõ_image3_06ad5f54.png)

## **Para que serve a tela de Atualizações em Massa**

A tela de Atualizações em Massa serve para:

* Atualizar tarifas de venda
* Definir ou ajustar disponibilidade de quartos (quando aplicável)
* Aplicar restrições de estadia mínima, chegada, saída e venda
* Enviar essas informações para um ou vários canais de venda ao mesmo tempo

Ela é uma das principais ferramentas para manter os canais alinhados com a estratégia comercial do hotel.

## **Entendendo a estrutura da tela de Atualizações em Massa**

A tela é dividida em três grandes áreas:

1. **Períodos**
2. **Lista de Atualizações**
3. **Seleção de Canais**

Cada uma dessas áreas cumpre um papel importante no processo de atualização.

## **1. Períodos**

Na seção **Períodos**, você define **quando** as atualizações serão aplicadas.

### **Início e Fim**

* Campos de data onde você informa o período de vigência das atualizações
* Tudo o que for configurado será aplicado apenas dentro desse intervalo

### **Dias da semana**

Permite selecionar em quais dias da semana as regras serão aplicadas:

* Domingo
* Segunda
* Terça
* Quarta
* Quinta
* Sexta
* Sábado

Você pode marcar os dias manualmente ou utilizar os botões de apoio.

### **Marcar todos**

* Marca automaticamente todos os dias da semana

### **Desmarcar**

* Remove a seleção de todos os dias

### **Inverter**

* Inverte a seleção atual dos dias

**Exemplo:** Se segunda, terça, quarta e quinta estão marcados e sexta, sábado e domingo estão desmarcados, ao clicar em **Inverter**:

* Segunda, terça, quarta e quinta serão desmarcados
* Sexta, sábado e domingo serão marcados

### **Ícone de “+” (Adicionar período)**

O ícone de **mais (+)** permite criar **múltiplos períodos de atualização** dentro da mesma operação.

Essa opção é útil quando você precisa aplicar a mesma regra para datas distintas, sem sair da tela.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_20_154550_09d9/images/Hunit_-_Atualizaçõ_imagea_40b4974f.png)

## **2. Lista de Atualizações**

Na **Lista de Atualizações**, são exibidos todos os tipos de quartos cadastrados no sistema, como:

* STD (Standard)
* LX (Luxo)

Essas categorias podem aparecer com variações de tarifa, como:

* Reembolsável (Flex)
* NR (Não Reembolsável)
* Com café / Sem café

Cada linha representa uma combinação de categoria e tipo de tarifa.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_20_154550_09d9/images/Hunit_-_Atualizaçõ_image4_a57e8f98.png)

* **Campos disponíveis para atualização**

### **Tarifa de Venda**

* Valor da diária que será enviada aos canais de venda
* Deve ser preenchida com atenção, pois impacta diretamente as reservas

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_20_154550_09d9/images/Hunit_-_Atualizaçõ_image8_7ca9b27f.png)

### **Disponibilidade**

* Quantidade de unidades disponíveis para venda naquela categoria

⚠️ **Importante:**

Essa coluna **só aparece** para hotéis que **não possuem integração com PMS** para controle de disponibilidade.

* Se o hotel possui PMS conectado, essa coluna não ficará disponível
* Isso evita divergências entre o PMS e o Hunit

Nesse cenário, a disponibilidade deve ser sempre gerenciada diretamente no PMS.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_20_154550_09d9/images/Hunit_-_Atualizaçõ_image_098f4608.png)

### **Estadia Mínima (Est. Mín.)**

* Define o número mínimo de noites exigido para que uma reserva seja aceita
* Exemplo: Estadia mínima 2 = o hóspede precisa reservar pelo menos 2 noites

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_20_154550_09d9/images/Hunit_-_Atualizaçõ_image5_8f5b9300.png)

### **Restrições: Chegada, Saída e Venda**

Esses campos permitem aplicar regras específicas para cada data.

#### **Chegada**

* **Aberto**: o sistema aceita check-in normalmente
* **Fechado**: não permite iniciar a estadia (check-in) nessa data

O hóspede pode estar hospedado nesse dia, mas não pode começar a reserva nele.

#### **Saída**

* **Aberto**: o sistema aceita checkout normalmente
* **Fechado**: não permite finalizar a estadia (checkout) nessa data

O hóspede pode entrar ou estar hospedado, mas não pode encerrar a reserva nesse dia.

#### **Venda**

* **Aberto**: novas reservas são aceitas normalmente
* **Fechado**: bloqueia novas reservas

Mesmo que exista disponibilidade (quantidade maior que 0), o sistema não permitirá vendas nessa data. Essa opção é usada para bloquear vendas sem zerar a disponibilidade.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_20_154550_09d9/images/Hunit_-_Atualizaçõ_image2_dd27b23c.png)

## **Função da seta para baixo (botão de cópia)**

O botão com **ícone de seta para baixo**, localizado no topo das colunas, permite **copiar automaticamente o valor inserido** para as demais linhas.

Essa função agiliza o preenchimento quando a mesma informação deve ser aplicada a várias categorias ou tarifas.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_20_154550_09d9/images/Hunit_-_Atualizaçõ_image6_d48ee568.png)

## **3. Seleção de Canais**

Na parte inferior da tela, está a **seção de canais**.

Aqui você define **em quais canais de venda (OTAs)** as atualizações serão aplicadas.

### **Caixas de seleção**

* Permitem selecionar os canais individualmente

### **Marcar Todos / Desmarcar Todos**

* Facilitam a seleção ou remoção de todos os canais de uma só vez

Essa etapa é essencial, pois somente os canais selecionados receberão as atualizações.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_20_154550_09d9/images/Hunit_-_Atualizaçõ_image7_192e051b.png)

## **Finalizando a atualização**

Após revisar todas as informações:

1. Confira o período selecionado
2. Revise tarifas, restrições e disponibilidade
3. Verifique os canais marcados

Por fim, clique no botão **Atualizar**, localizado no canto inferior direito da tela.

Somente após essa ação as informações serão enviadas aos canais.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_20_154550_09d9/images/Hunit_-_Atualizaçõ_image9_c1b89a77.png)

## **Glossário**

|  |  |
| --- | --- |
| **Termo** | **Definição** |
| **Atualizações em Massa** | Tela do Hunit que permite aplicar tarifas, disponibilidade e restrições em vários canais ao mesmo tempo. |
| **Canal de venda (OTA)** | Plataforma onde as diárias são comercializadas, como Booking ou Expedia. |
| **Categoria** | Tipo de acomodação do hotel (Standard, Luxo, etc.). |
| **Disponibilidade** | Quantidade de quartos disponíveis para venda. |
| **Estadia mínima** | Número mínimo de noites exigido para uma reserva. |
| **PMS (Property Management System)** | Sistema de gestão interna do hotel. |
| **Restrição** | Regra que limita vendas, como bloqueio de chegada, saída ou venda. |