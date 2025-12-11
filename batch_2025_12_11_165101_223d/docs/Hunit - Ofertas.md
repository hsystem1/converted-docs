Documentação: Ofertas

Visão geral

Este documento descreve o processo de configuração de ofertas no sistema Hunit (Gestor de canais)

**Objetivo da funcionalidade**

A **tela de Ofertas** do Hunit Channel Manager — o espaço onde é possível **criar, visualizar e gerenciar as promoções** aplicadas aos canais de venda, como **Booking, Expedia, HBOOK** e outros.

**Caminho de acesso:**
Menu superior → **Ofertas**

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image5_3a3b3b1c.png)

Tela de Ofertas — Gerenciamento de Promoções e Descontos no Channel Manager

Logo no topo, estão as **abas de canais**, que funcionam como filtros rápidos.

Essas abas são **exibidas automaticamente conforme os canais que o hotel tem conectados** e que **possuem integração disponível para ofertas**.
 Ou seja, se o hotel trabalha com Booking e Expedia, por exemplo, apenas essas opções — além da aba “Todos” — aparecerão.

As abas normalmente são (exemplo):

* **TODOS:** mostra todas as ofertas cadastradas, de todos os canais integrados.
* **EXPEDIA:** exibe apenas as ofertas ativas e configuradas para o canal Expedia.
* **BOOKING:** exibe as promoções aplicadas no canal Booking.
* **HBOOK:** lista as ofertas criadas para o canal interno HBOOK.

*Essas abas ajudam o usuário a visualizar e gerenciar cada canal de forma individual, evitando confusão entre regras de desconto que podem ser diferentes para cada parceiro.*

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image32_0308316e.png)

**Lista de Ofertas Cadastradas**

Abaixo das abas, a tela exibe uma **tabela com todas as ofertas existentes**, mostrando as informações principais de cada uma.
 Cada linha representa uma oferta, com as seguintes colunas:

**1. Canal**

Indica em qual canal de venda a oferta está configurada — por exemplo, HBOOK, Expedia ou Booking.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image20_b1e9ea14.png)

**2. Nome da Oferta**

Nome que identifica a promoção, como *“Promo férias”* ou *“Desconto Black Friday”*.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image26_f550b576.png)

**3. Tipo da Oferta**

Mostra o tipo definido no momento da criação (exemplo: *BÁSICA*, LAST MINUTE, etc.).

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image27_9ac5dafe.png)

**4. Status**

Exibe se a oferta está **ATIVA** (em verde) ou **inativa**.
 Somente as ofertas com status ativo são aplicadas nas tarifas enviadas ao canal.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image30_a98ad984.png)

**5. Desconto**

Mostra o percentual configurado de desconto, como *10%*, *15%*, etc.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image34_04fb67d6.png)

**6. Quartos**

Lista os tipos de quarto aos quais a oferta se aplica.
 Por exemplo:

* Quarto Standard
* Quarto Família
* Quarto Duplo

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_imagec_9868af36.png)

**7. Tarifas**

Exibe quais tarifas estão vinculadas à oferta.
 Exemplo:

* Tarifa Grupo
* Carnaval 2026
* Tarifa Operadora X

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image29_7e713618.png)

**8. Filtros e Regras**

Aqui são mostradas as condições adicionais configuradas, como:

* Período em que a oferta é válida;
* Validade da promoção para compra;
* Quantidade mínima de disponibilidade exigida;
* Aplicação por noite.

Por exemplo:

Oferta aplicada de 22/05/2025 até 22/05/2025
 Validade para compra: 22/05/2025 até 22/05/2025
 Quantidade mínima de disponibilidade: 50
 Desconto aplicado em todas as noites

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image7_5877f61f.png)

**Ações de Edição e Exclusão**

À direita de cada oferta existem dois ícones de ação:

* **Ícone Azul (Editar):** abre a oferta para editar desconto, período ou regras.
* **Ícone Vermelho (Excluir):** remove a oferta da listagem.

**Importante:**
 Se a oferta foi **criada originalmente no canal de venda** (por exemplo, diretamente no Booking ou Expedia), **pode não ser possível editar ou excluir** pelo Channel Manager.
 Isso acontece porque **alguns canais possuem regras próprias** e **não permitem alterações ou exclusões via integração**, especialmente em ofertas do tipo “acordo com o canal” (como promoções automáticas ou campanhas exclusivas criadas dentro da extranet do canal).

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image9_bdbd800d.png)

**Criando uma Oferta no Channel Manager**

Agora que você já entendeu a tela principal de **Ofertas**, vamos aprender o passo a passo para **criar uma promoção** e enviar automaticamente aos canais conectados.

**Criar Nova Oferta**

No canto direito superior da tela, há o botão **“CRIAR NOVA OFERTA”**.
 Ao clicar, o sistema abre uma nova tela onde é possível configurar todos os detalhes da promoção.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image11_1d686d04.png)

**Escolhendo o Canal da Oferta**

A primeira tela exibida é uma janela simples com a pergunta:

“Escolha o canal que deseja criar uma oferta:”

Abaixo, aparecem **botões grandes com os nomes dos canais disponíveis**, como:

* **EXPEDIA**
* **BOOKING**
* **HBOOK**

💡 *Essa listagem é dinâmica*:
 O sistema mostra **somente os canais que o hotel possui integrados ao seu Channel** e que **aceitam o envio de ofertas automaticamente**.

Cada canal tem suas **regras e formatos próprios de oferta**, como tipos de desconto, critérios de validade ou restrições de tarifa.
 Por isso, **as ofertas só podem ser criadas individualmente para cada canal** — não é possível aplicar uma mesma promoção em todos ao mesmo tempo.

Basta clicar sobre o canal desejado para seguir à próxima etapa.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image1a_cbf9447d.png)

**Escolhendo o Tipo de Oferta**

Depois de selecionar o canal, o sistema exibirá a segunda etapa: **Selecione o tipo de oferta disponível para o canal**. Esses tipos variam conforme o canal, já que cada um tem suas próprias modalidades promocionais.

Por exemplo:

* **Booking.com:** pode oferecer tipos como *Compra Antecipada*, *Oferta Básica e* *Promoção de Última Hora (Lest minute)*.
* **Expedia:** pode permitir *Oferta Básica*, *Compra antecipada* e *Promoção de Última Hora (Lest minute).*
* **HBOOK:** Aceita *Ofertas Básicas*.
* **Hoteisnet:** Oferta básica, *Promoção de Última Hora (Lest minute), Compra antecipada e desconto de estadia.*

💡 *O sistema mostra apenas os tipos compatíveis com o canal selecionado*, garantindo que a oferta possa ser criada e publicada com sucesso.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image1b_fe851eb7.png)

**Tela de Configuração da Oferta Básica**

Depois de escolher o canal e o tipo de oferta, o sistema abre a tela de **configuração da oferta**.
 Aqui é onde você define todos os detalhes que o Channel Manager vai enviar para o canal de venda escolhido.

**Hoteisnet**

**Dados Gerais**

A primeira seção exibe informações básicas da promoção:

* **Criando oferta para o canal:** *HOTEISNET*.
* **Tipo da oferta no canal:** tipo de oferta classificada pelo canal.
* **Nome da oferta:** campo onde você digita o nome que vai identificar essa promoção, tanto dentro do Channel quanto no canal de destino.

Exemplo: “Desconto Fim de Semana” ou “Promo Novembro”.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image2d_632ac009.png)

**Tipos de Tarifa**

Nesta seção, você define **a quais tarifas a oferta será aplicada**.

O sistema lista automaticamente as tarifas disponíveis no canal selecionado, como:

* *HS – Tarifa Flex c/ Café – Cartão*
* *HS – Tarifa Flex c/ Café – Faturamento*

Você pode marcar apenas as tarifas que devem participar da promoção.
 Há também os botões:

* **Marcar Todos:** seleciona todas as tarifas de uma vez.
* **Desmarcar:** limpa todas as seleções.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image3_623951f1.png)

**Condições de Aplicabilidade**

Aqui você define **em que período a oferta será válida** e, se quiser, adiciona **filtros adicionais**.

**Botão “Novo Filtro”**

O botão **“NOVO FILTRO”** serve para configurar **regras e condições da oferta**:

1. **Período da Compra** – define *quando* o hóspede pode reservar com essa promoção (por exemplo: válida para compras entre 01/11 e 15/11).
2. **Período da Oferta (Estadia)** – define *para quando* a hospedagem será válida (por exemplo: estadias entre 01/12 e 31/12).

Esses dois períodos ajudam a controlar campanhas sazonais, como promoções antecipadas ou ofertas relâmpagos.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image8_ab35e74f.png)

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image25_455dbe4e.png)

**Forma de Desconto**

Essa seção define **como o desconto será aplicado**:

* **Percentual de Desconto:** campo numérico onde você insere o valor do desconto em porcentagem (%).

Exemplo: digite “10” para aplicar 10% de desconto.

* **Aplicar nas seguintes noites:** menu suspenso que permite escolher se o desconto será aplicado em:
  + **Todas as noites** da estadia;
  + **Dias da semana**, pode selecionar quais dias será aplicado o desconto.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image4_11c51aed.png)

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_imageb_47e7c051.png)

Depois de preencher todas as informações, clique em:

* **SALVAR:** grava a oferta e envia para o canal.
* **CANCELAR:** descarta as alterações e retorna à listagem.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image12_2b251e94.png)

Ao salvar, o sistema validará os dados e, se estiver tudo correto, a oferta aparecerá na tela principal de listagem com o status **ATIVO**.

**HBOOK**

**Dados Gerais**

A primeira seção exibe informações básicas da promoção:

* **Criando oferta para o canal:** *HOTEISNET*.
* **Tipo da oferta no canal:** tipo de oferta classificada pelo canal.
* **Nome da oferta:** campo onde você digita o nome que vai identificar essa promoção, tanto dentro do Channel quanto no canal de destino.

Exemplo: “Desconto Fim de Semana” ou “Promo Novembro”.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image21_746efeaa.png)

**Tipos de Quarto**

Nesta seção, você define **a quais quartos a oferta será aplicada**.

O sistema lista automaticamente os quartos disponíveis no canal selecionado, como:

* *Quarto Duplo*
* *Suíte Standard*
* *Suíte Luxo*
* *Quarto família*

Você pode marcar apenas os quartos que devem participar da promoção.
 Há também os botões:

* **Marcar Todos:** seleciona todos os quartos de uma vez.
* **Desmarcar:** limpa todas as seleções.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image2b_3cef762a.png)

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image2_fc431889.png)

**Tipos de Tarifa**

Nesta seção, você define **a quais tarifas a oferta será aplicada**.

O sistema lista automaticamente as tarifas disponíveis no canal selecionado, como:

* *Tarifa Flex c/ Café*
* *Tarifa Flex c/ Café*
* *Tarifa NR (Não reembolsável)*

Você pode marcar apenas as tarifas que devem participar da promoção.
 Há também os botões:

* **Marcar Todos:** seleciona todas as tarifas de uma vez.
* **Desmarcar:** limpa todas as seleções.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_imagee_c5d1b832.png)

**Condições de Aplicabilidade**

Aqui você define **em que período a oferta será válida** e, se quiser, adiciona **filtros adicionais**.

**Botão “Novo Filtro”**

O botão **“NOVO FILTRO”** serve para configurar as **regras e condições da oferta**.

Lista de opções:

**PERÍODO DA OFERTA**
 Defina o período da estadia em que a oferta poderá ser aplicada.

**CRIANÇAS**
 Defina a quantidade e idade máxima das crianças na oferta.

**ANTECEDÊNCIA MÁXIMA**
 Defina qual a diferença máxima em dias entre a data da reserva e data do check-in.

**ANTECEDÊNCIA MÍNIMA**
 Defina qual a diferença mínima em dias entre a data da reserva e data do check-in.

**VALOR MÍNIMO DO QUARTO**
 Defina o valor mínimo dos quartos para que a oferta seja aplicada.

**ESTADIA MÍNIMA**
 Defina a quantidade de noites mínimas para que a oferta seja aplicada.

**MÍNIMO DE QUARTO DISPONÍVEL NO INVENTÁRIO**
 Defina a quantidade mínima de quartos que deve haver no inventário para que a oferta seja aplicada.

**DISPOSITIVO MOBILE**
 Defina se a oferta será aplicada somente se a pesquisa for de um dispositivo mobile.

**PERÍODO DA COMPRA**
 Defina o período em que a compra deve ser realizada.

**É UM VISITANTE REGISTRADO (clientes que possuem produto HPRIME)**
 Defina se a oferta será aplicada somente para visitantes registrados.

**RESERVA ABANDONADA**
 Defina se a oferta será aplicada somente para as reservas abandonadas.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image10_0a5c2237.png)

**Forma de Desconto**

Essa seção define **como o desconto será aplicado**:

* **Percentual de Desconto:** campo numérico onde você insere o valor do desconto em porcentagem (%).

Exemplo: digite “10” para aplicar 10% de desconto.

* **Aplicar nas seguintes noites:** menu suspenso que permite escolher se o desconto será aplicado em:
  + **Todas as noites** da estadia;
  + **Dias da semana**, pode selecionar quais dias será aplicado o desconto.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image19_bbea0ba7.png)

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image1c_3dd28962.png)

Depois de preencher todas as informações, clique em:

* **SALVAR:** grava a oferta e envia para o canal.
* **CANCELAR:** descarta as alterações e retorna à listagem.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image31_cdc78c81.png)

Ao salvar, o sistema validará os dados e, se estiver tudo correto, a oferta aparecerá na tela principal de listagem com o status **ATIVO**.

**Booking**

**Dados Gerais**

A primeira seção exibe informações básicas da promoção:

* **Criando oferta para o canal:** *Booking*.
* **Tipo da oferta no canal:** tipo de oferta classificada pelo canal.
* **Nome da oferta:** campo onde você digita o nome que vai identificar essa promoção, tanto dentro do Channel quanto no canal de destino.

Exemplo: “Desconto Fim de Semana” ou “Promo Novembro”.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_imagef_177d3acb.png)

**Tipos de Quartos**

Nesta seção, você define **a quais quartos a oferta será aplicada**.

O sistema lista automaticamente os quartos disponíveis no canal selecionado, como:

* *Standard Double Room*
* *Suíte*
* *Single Room*

Você pode marcar apenas os quartos que devem participar da promoção.
 Há também os botões:

* **Marcar Todos:** seleciona todos os quartos de uma vez.
* **Desmarcar:** limpa todas as seleções.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_imaged_b23be7f6.png)

**Tipos de Tarifa**

Nesta seção, você define **a quais tarifas a oferta será aplicada**.

O sistema lista automaticamente as tarifas disponíveis no canal selecionado, como:

* *Tarifa Flex c/ Café*
* *Tarifa Flex c/ Café*
* *Tarifa NR (Não reembolsável)*

Você pode marcar apenas as tarifas que devem participar da promoção.
 Há também os botões:

* **Marcar Todos:** seleciona todas as tarifas de uma vez.
* **Desmarcar:** limpa todas as seleções.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image15_6fb10891.png)

**Condições de Aplicabilidade**

Aqui você define **em que período a oferta será válida** e, se quiser, adiciona **filtros adicionais**.

**Botão “Novo Filtro”**

O botão **“NOVO FILTRO”** serve para configurar as **regras e condições da oferta**.

Lista de opções:

**É UM VISITANTE REGISTRADO**
 Defina se a oferta será aplicada somente para visitantes registrados.

**ESTADIA MÍNIMA**
 Defina a quantidade de noites mínimas para que a oferta seja aplicada.

**OFERTA SERÁ NÃO REEMBOLSÁVEL**
 Defina se a política da oferta será Não Reembolsável.

**PERÍODO DA OFERTA**
 Defina o período da estadia em que a oferta poderá ser aplicada.

**PERÍODO DA COMPRA**
 Defina o período em que a compra deve ser realizada.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image1f_bf3a5a0b.png)

**Forma de Desconto**

Essa seção define **como o desconto será aplicado**:

* **Percentual de Desconto:** campo numérico onde você insere o valor do desconto em porcentagem (%).

Exemplo: digite “10” para aplicar 10% de desconto.

* **Aplicar nas seguintes noites:** menu suspenso que permite escolher se o desconto será aplicado em:
  + **Todas as noites** da estadia;
  + **Dias da semana**, pode selecionar quais dias será aplicado o desconto.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image2a_18669ce7.png)

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image2c_ef19afcf.png)

Depois de preencher todas as informações, clique em:

* **SALVAR:** grava a oferta e envia para o canal.
* **CANCELAR:** descarta as alterações e retorna à listagem.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image35_d7a78d11.png)

Ao salvar, o sistema validará os dados e, se estiver tudo correto, a oferta aparecerá na tela principal de listagem com o status **ATIVO**.

**Expedia**

**Dados Gerais**

A primeira seção exibe informações básicas da promoção:

* **Criando oferta para o canal:** Expedia.
* **Tipo da oferta no canal:** tipo de oferta classificada pelo canal.
* **Nome da oferta:** campo onde você digita o nome que vai identificar essa promoção, tanto dentro do Channel quanto no canal de destino.

Exemplo: “Desconto Fim de Semana” ou “Promo Novembro”.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image14_ade1e5cd.png)

**Tipos de Quartos**

Nesta seção, você define **a quais quartos a oferta será aplicada**.

O sistema lista automaticamente os quartos disponíveis no canal selecionado, como:

* *Quarto Duplo*
* *Suíte Standard*
* *Suíte Luxo*
* *Quarto família*

Você pode marcar apenas os quartos que devem participar da promoção.
 Há também os botões:

* **Marcar Todos:** seleciona todos os quartos de uma vez.
* **Desmarcar:** limpa todas as seleções.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image24_ca0936ef.png)

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image28_313602f6.png)

**Condições de Aplicabilidade**

Aqui você define **em que período a oferta será válida** e, se quiser, adiciona **filtros adicionais**.

**Botão “Novo Filtro”**

O botão **“NOVO FILTRO”** serve para configurar as **regras e condições da oferta**.

Lista de opções:

**DISPOSITIVO MOBILE**
 Defina se a oferta será aplicada somente se a pesquisa for de um dispositivo mobile.

**ESTADIA MÁXIMA**
 Defina a quantidade máxima de noites para que a oferta seja aplicada.

**ANTECEDÊNCIA MÍNIMA**
 Defina qual a diferença mínima em dias entre a data da reserva e data do check-in.

**ANTECEDÊNCIA MÁXIMA**
 Defina qual a diferença máxima em dias entre a data da reserva e data do check-in.

**EXCETO NAS DATAS**
 Defina períodos em que a oferta não será aplicada.

**EXCLUSIVA PARA MEMBROS**
 Defina se essa é uma oferta exclusiva para membros.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image2f_e6eb1fe6.png)

**Forma de Desconto**

Essa seção define **como o desconto será aplicado**:

* **Percentual de Desconto:** campo numérico onde você insere o valor do desconto em porcentagem (%).

Exemplo: digite “10” para aplicar 10% de desconto.

* **Valor adicional para membros:** programa de membros do canal (desconto percentual).
* **Aplicar nas seguintes noites:** menu suspenso que permite escolher se o desconto será aplicado em:
  + **Todas as noites** da estadia;
  + **Múltiplas noites:** permite especificar em quais noites o desconto será aplicado, abre o campo **“Aplicado na noite”**, é **numérico** e indica **a partir de qual noite o desconto entrará em vigor**.
     Por exemplo:
* Se você digitar **2**, o desconto será aplicado **na segunda noite** da reserva.
* Se digitar **3**, será aplicado **na terceira noite**, e assim por diante.
  + Já o campo **“Recorrente”** funciona como um **repetidor automático** desse padrão.
     Exemplo: se você informar **3** no campo “Aplicado na noite” e marcar a opção **Recorrente**, o sistema aplicará o desconto **a cada 3 noites** da estadia.
     Ou seja, em uma reserva de **10 dias**, o desconto seria aplicado **na 3ª, 6ª e 9ª noite**.
  + **Dias da semana**, pode selecionar quais dias será aplicado o desconto.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image33_e16b667e.png)

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image_9b1979d9.png)

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image13_c8504146.png)

Depois de preencher todas as informações, clique em:

* **SALVAR:** grava a oferta e envia para o canal.
* **CANCELAR:** descarta as alterações e retorna à listagem.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image16_eebc48c8.png)

Ao salvar, o sistema validará os dados e, se estiver tudo correto, a oferta aparecerá na tela principal de listagem com o status **ATIVO**.

**Tela de Configuração da Last Minute**

**Booking**

**Dados Gerais**

A primeira seção exibe informações básicas da promoção:

* **Criando oferta para o canal:** *Booking*.
* **Tipo da oferta no canal:** tipo de oferta classificada pelo canal.
* **Nome da oferta:** campo onde você digita o nome que vai identificar essa promoção, tanto dentro do Channel quanto no canal de destino.

Exemplo: “Desconto Fim de Semana” ou “Promo Novembro”.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image23_5eef9585.png)

**Tipos de Quartos**

Nesta seção, você define **a quais quartos a oferta será aplicada**.

O sistema lista automaticamente os quartos disponíveis no canal selecionado, como:

* *Standard Double Room*
* *Suíte*
* *Single Room*

Você pode marcar apenas os quartos que devem participar da promoção.
 Há também os botões:

* **Marcar Todos:** seleciona todos os quartos de uma vez.
* **Desmarcar:** limpa todas as seleções.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image18_1a53e264.png)

**Tipos de Tarifa**

Nesta seção, você define **a quais tarifas a oferta será aplicada**.

O sistema lista automaticamente as tarifas disponíveis no canal selecionado, como:

* *Tarifa Flex c/ Café*
* *Tarifa Flex c/ Café*
* *Tarifa NR (Não reembolsável)*

Você pode marcar apenas as tarifas que devem participar da promoção.
 Há também os botões:

* **Marcar Todos:** seleciona todas as tarifas de uma vez.
* **Desmarcar:** limpa todas as seleções.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image1d_c78af1ef.png)

**Condições de Aplicabilidade**

Aqui você define **em que período a oferta será válida** e, se quiser, adiciona **filtros adicionais**.

**Botão “Novo Filtro”**

O botão **“NOVO FILTRO”** serve para configurar as **regras e condições da oferta**.

Lista de opções:

**PERÍODO DA OFERTA**
 Defina o período da estadia em que a oferta poderá ser aplicada.

**É UM VISITANTE REGISTRADO**
 Defina se a oferta será aplicada somente para visitantes registrados.

**OFERTA SERÁ NÃO REEMBOLSÁVEL**
 Defina se a política da oferta será Não Reembolsável.

**ANTEDÊNCIA MÁXIMA**
 Defina qual a diferença máxima em dias entre a data da reserva e a data do check-in.

**ESTADIA MÍNIMA**
 Defina a quantidade de noites mínimas para que a oferta seja aplicada.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image2e_7a74c0ea.png)

**Forma de Desconto**

Essa seção define **como o desconto será aplicado**:

* **Percentual de Desconto:** campo numérico onde você insere o valor do desconto em porcentagem (%).

Exemplo: digite “10” para aplicar 10% de desconto.

* **Aplicar nas seguintes noites:** menu suspenso que permite escolher se o desconto será aplicado em:
  + **Todas as noites** da estadia;
  + **Dias da semana**, pode selecionar quais dias será aplicado o desconto.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image6_8e079bc2.png)

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_imagea_97f7a1b4.png)

Depois de preencher todas as informações, clique em:

* **SALVAR:** grava a oferta e envia para o canal.
* **CANCELAR:** descarta as alterações e retorna à listagem.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image17_cb8abdf5.png)

Ao salvar, o sistema validará os dados e, se estiver tudo correto, a oferta aparecerá na tela principal de listagem com o status **ATIVO**.

**Expedia**

**Dados Gerais**

A primeira seção exibe informações básicas da promoção:

* **Criando oferta para o canal:** Expedia.
* **Tipo da oferta no canal:** tipo de oferta classificada pelo canal.
* **Nome da oferta:** campo onde você digita o nome que vai identificar essa promoção, tanto dentro do Channel quanto no canal de destino.

Exemplo: “Desconto Fim de Semana” ou “Promo Novembro”.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image1e_016ac020.png)

**Tipos de Quartos**

Nesta seção, você define **a quais quartos a oferta será aplicada**.

O sistema lista automaticamente os quartos disponíveis no canal selecionado, como:

* *Quarto Duplo*
* *Suíte Standard*
* *Suíte Luxo*
* *Quarto família*

Você pode marcar apenas os quartos que devem participar da promoção.
 Há também os botões:

* **Marcar Todos:** seleciona todos os quartos de uma vez.
* **Desmarcar:** limpa todas as seleções.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image22_f542b26a.png)

![](data:image/png;base64...)

**Condições de Aplicabilidade**

Aqui você define **em que período a oferta será válida** e, se quiser, adiciona **filtros adicionais**.

**Botão “Novo Filtro”**

O botão **“NOVO FILTRO”** serve para configurar as **regras e condições da oferta**.

Lista de opções:

**DISPOSITIVO MOBILE**
 Defina se a oferta será aplicada somente se a pesquisa for de um dispositivo mobile.

**ESTADIA MÁXIMA**
 Defina a quantidade máxima de noites para que a oferta seja aplicada.

**EXCETO NAS DATAS**
 Defina períodos em que a oferta não será aplicada.

**EXCLUSIVA PARA MEMBROS**
 Defina se essa é uma oferta exclusiva para membros.

**ESTADIA MÍNIMA**
 Defina a quantidade de noites mínimas para que a oferta seja aplicada.

**PERÍODO DA OFERTA**
 Defina o período da estadia em que a oferta poderá ser aplicada.

**PERÍODO DA COMPRA**
 Defina o período em que a compra deve ser realizada.

**HORÁRIO DE INÍCIO**
 Defina o horário de início da oferta.

![](data:image/png;base64...)

**Forma de Desconto**

Essa seção define **como o desconto será aplicado**:

* **Percentual de Desconto:** campo numérico onde você insere o valor do desconto em porcentagem (%).

Exemplo: digite “10” para aplicar 10% de desconto.

* **Aplicar nas seguintes noites:** menu suspenso que permite escolher se o desconto será aplicado em:
  + **Todas as noites** da estadia;

![](data:image/png;base64...)

Depois de preencher todas as informações, clique em:

* **SALVAR:** grava a oferta e envia para o canal.
* **CANCELAR:** descarta as alterações e retorna à listagem.

![](data:image/png;base64...)

Ao salvar, o sistema validará os dados e, se estiver tudo correto, a oferta aparecerá na tela principal de listagem com o status **ATIVO**.

**Hoteisnet**

**Dados Gerais**

A primeira seção exibe informações básicas da promoção:

* **Criando oferta para o canal:** *HOTEISNET*.
* **Tipo da oferta no canal:** tipo de oferta classificada pelo canal.
* **Nome da oferta:** campo onde você digita o nome que vai identificar essa promoção, tanto dentro do Channel quanto no canal de destino.

Exemplo: “Desconto Fim de Semana” ou “Promo Novembro”.

![](data:image/png;base64...)

**Tipos de Tarifa**

Nesta seção, você define **a quais tarifas a oferta será aplicada**.

O sistema lista automaticamente as tarifas disponíveis no canal selecionado, como:

* *HS – Tarifa Flex c/ Café – Cartão*
* *HS – Tarifa Flex c/ Café – Faturamento*

Você pode marcar apenas as tarifas que devem participar da promoção.
 Há também os botões:

* **Marcar Todos:** seleciona todas as tarifas de uma vez.
* **Desmarcar:** limpa todas as seleções.

![](data:image/png;base64...)

**Condições de Aplicabilidade**

Aqui você define **em que período a oferta será válida** e, se quiser, adiciona **filtros adicionais**.

**Botão “Novo Filtro”**

O botão **“NOVO FILTRO”** serve para configurar **regras e condições da oferta.**

**PERÍODO DA OFERTA**
 Defina o período da estadia em que a oferta poderá ser aplicada.

**PERÍODO DA COMPRA**
 Defina o período em que a compra deve ser realizada.

**ANTEDÊNCIA MÁXIMA**
 Defina qual a diferença máxima em dias entre a data da reserva e a data do check-in.

![](data:image/png;base64...)

**Forma de Desconto**

Essa seção define **como o desconto será aplicado**:

* **Percentual de Desconto:** campo numérico onde você insere o valor do desconto em porcentagem (%).

Exemplo: digite “10” para aplicar 10% de desconto.

* **Aplicar nas seguintes noites:** menu suspenso que permite escolher se o desconto será aplicado em:
  + **Todas as noites** da estadia;
  + **Dias da semana**, pode selecionar quais dias será aplicado o desconto.

![](data:image/png;base64...)

![](data:image/png;base64...)

Depois de preencher todas as informações, clique em:

* **SALVAR:** grava a oferta e envia para o canal.
* **CANCELAR:** descarta as alterações e retorna à listagem.

![](data:image/png;base64...)

Ao salvar, o sistema validará os dados e, se estiver tudo correto, a oferta aparecerá na tela principal de listagem com o status **ATIVO**.

**Tela de Configuração da Compra Antecipada**

**Booking**

**Dados Gerais**

A primeira seção exibe informações básicas da promoção:

* **Criando oferta para o canal:** *Booking*.
* **Tipo da oferta no canal:** tipo de oferta classificada pelo canal.
* **Nome da oferta:** campo onde você digita o nome que vai identificar essa promoção, tanto dentro do Channel quanto no canal de destino.

Exemplo: “Desconto Fim de Semana” ou “Promo Novembro”.

![](data:image/png;base64...)

**Tipos de Quartos**

Nesta seção, você define **a quais quartos a oferta será aplicada**.

O sistema lista automaticamente os quartos disponíveis no canal selecionado, como:

* *Standard Double Room*
* Superior Double Room
* Superior Twin Room
* Superior Triple Room

Você pode marcar apenas os quartos que devem participar da promoção.
 Há também os botões:

* **Marcar Todos:** seleciona todos os quartos de uma vez.
* **Desmarcar:** limpa todas as seleções.

![](data:image/png;base64...)

**Tipos de Tarifa**

Nesta seção, você define **a quais tarifas a oferta será aplicada**.

O sistema lista automaticamente as tarifas disponíveis no canal selecionado, como:

* *Tarifa Flex c/ Café*
* *Tarifa Flex c/ Café*
* *Tarifa NR (Não reembolsável)*

Você pode marcar apenas as tarifas que devem participar da promoção.
 Há também os botões:

* **Marcar Todos:** seleciona todas as tarifas de uma vez.
* **Desmarcar:** limpa todas as seleções.

![](data:image/png;base64...)

**Condições de Aplicabilidade**

Aqui você define **em que período a oferta será válida** e, se quiser, adiciona **filtros adicionais**.

**Botão “Novo Filtro”**

O botão **“NOVO FILTRO”** serve para configurar as **regras e condições da oferta**.

Lista de opções:

**É UM VISITANTE REGISTRADO**
 Defina se a oferta será aplicada somente para visitantes registrados.

**ESTADIA MÍNIMA**
 Defina a quantidade de noites mínimas para que a oferta seja aplicada.

**PERÍODO DA OFERTA**
 Defina o período da estadia em que a oferta poderá ser aplicada.

**OFERTA SERÁ NÃO REEMBOLSÁVEL**
 Defina se a política da oferta será Não Reembolsável.

**ANTEDÊNCIA MÍNIMA**
 Defina qual a diferença mínima em dias entre a data da reserva e a data do check-in.

![](data:image/png;base64...)

**Forma de Desconto**

Essa seção define **como o desconto será aplicado**:

* **Percentual de Desconto:** campo numérico onde você insere o valor do desconto em porcentagem (%).

Exemplo: digite “10” para aplicar 10% de desconto.

* **Aplicar nas seguintes noites:** menu suspenso que permite escolher se o desconto será aplicado em:
  + **Todas as noites** da estadia;
  + **Dias da semana**, pode selecionar quais dias será aplicado o desconto.

![](data:image/png;base64...)

![](data:image/png;base64...)

Depois de preencher todas as informações, clique em:

* **SALVAR:** grava a oferta e envia para o canal.
* **CANCELAR:** descarta as alterações e retorna à listagem.

![](data:image/png;base64...)

Ao salvar, o sistema validará os dados e, se estiver tudo correto, a oferta aparecerá na tela principal de listagem com o status **ATIVO**.

**Expedia**

**Dados Gerais**

A primeira seção exibe informações básicas da promoção:

* **Criando oferta para o canal:** Expedia.
* **Tipo da oferta no canal:** tipo de oferta classificada pelo canal.
* **Nome da oferta:** campo onde você digita o nome que vai identificar essa promoção, tanto dentro do Channel quanto no canal de destino.

Exemplo: “Desconto Fim de Semana” ou “Promo Novembro”.

![](data:image/png;base64...)

**Tipos de Quartos e Tarifas**

Nesta seção, você define **em quais quartos e tarifas** a promoção será aplicada.

Aqui, você escolhe **os tipos de quarto** e **as tarifas específicas** que participarão da oferta.

A tela está dividida em **blocos**, e cada bloco representa um **tipo de quarto** disponível no seu hotel.
 Logo abaixo do nome do quarto, aparecem as **tarifas associadas a ele.**

![](data:image/png;base64...)

![](data:image/png;base64...)

Você pode marcar apenas os quartos que devem participar da promoção.
 Há também os botões:

* **Marcar Todos:** seleciona todos os quartos de uma vez.
* **Desmarcar:** limpa todas as seleções.

![](data:image/png;base64...)

![](data:image/png;base64...)

**Condições de Aplicabilidade**

Aqui você define **em que período a oferta será válida** e, se quiser, adiciona **filtros adicionais**.

**Botão “Novo Filtro”**

O botão **“NOVO FILTRO”** serve para configurar as **regras e condições da oferta**.

Lista de opções:

**DISPOSITIVO MOBILE**
 Defina se a oferta será aplicada somente se a pesquisa for de um dispositivo mobile.

**ESTADIA MÁXIMA**
 Defina a quantidade máxima de noites para que a oferta seja aplicada.

**ANTEDÊNCIA MÍNIMA**
 Defina qual a diferença mínima em dias entre a data da reserva e data do check-in.

**ANTEDÊNCIA MÁXIMA**
 Defina qual a diferença máxima em dias entre a data da reserva e data do check-in.

**EXCETO NAS DATAS**
 Defina períodos em que a oferta não será aplicada.

**EXCLUSIVA PARA MEMBROS**
 Defina se essa é uma oferta exclusiva para membros.

**ESTADIA MÍNIMA**
 Defina a quantidade de noites mínimas para que a oferta seja aplicada.

**PERÍODO DA OFERTA**
 Defina o período da estadia em que a oferta poderá ser aplicada.

**PERÍODO DA COMPRA**
 Defina o período em que a compra deve ser realizada.

![](data:image/png;base64...)

**Forma de Desconto**

Essa seção define **como o desconto será aplicado**:

* **Percentual de Desconto:** campo numérico onde você insere o valor do desconto em porcentagem (%).

Exemplo: digite “10” para aplicar 10% de desconto.

* **Valor adicional para membros:** programa de membros do canal (desconto percentual).
* **Aplicar nas seguintes noites:** menu suspenso que permite escolher se o desconto será aplicado em:
  + **Todas as noites** da estadia;
  + **Múltiplas noites:** permite especificar em quais noites o desconto será aplicado, abre o campo **“Aplicado na noite”**, é **numérico** e indica **a partir de qual noite o desconto entrará em vigor**.
     Por exemplo:
* Se você digitar **2**, o desconto será aplicado **na segunda noite** da reserva.
* Se digitar **3**, será aplicado **na terceira noite**, e assim por diante.
  + Já o campo **“Recorrente”** funciona como um **repetidor automático** desse padrão.
     Exemplo: se você informar **3** no campo “Aplicado na noite” e marcar a opção **Recorrente**, o sistema aplicará o desconto **a cada 3 noites** da estadia.
     Ou seja, em uma reserva de **10 dias**, o desconto seria aplicado **na 3ª, 6ª e 9ª noite**.
  + **Dias da semana**, pode selecionar quais dias será aplicado o desconto.

![](data:image/png;base64...)

![](data:image/png;base64...)

![](data:image/png;base64...)

Depois de preencher todas as informações, clique em:

* **SALVAR:** grava a oferta e envia para o canal.
* **CANCELAR:** descarta as alterações e retorna à listagem.

![](data:image/png;base64...)

Ao salvar, o sistema validará os dados e, se estiver tudo correto, a oferta aparecerá na tela principal de listagem com o status **ATIVO**.

**Hoteisnet**

**Dados Gerais**

A primeira seção exibe informações básicas da promoção:

* **Criando oferta para o canal:** *HOTEISNET*.
* **Tipo da oferta no canal:** tipo de oferta classificada pelo canal.
* **Nome da oferta:** campo onde você digita o nome que vai identificar essa promoção, tanto dentro do Channel quanto no canal de destino.

Exemplo: “Desconto Fim de Semana” ou “Promo Novembro”.

![](data:image/png;base64...)

**Tipos de Tarifa**

Nesta seção, você define **a quais tarifas a oferta será aplicada**.

O sistema lista automaticamente as tarifas disponíveis no canal selecionado, como:

* *HS – Tarifa Flex c/ Café – Cartão*
* *HS – Tarifa Flex c/ Café – Faturamento*

Você pode marcar apenas as tarifas que devem participar da promoção.
 Há também os botões:

* **Marcar Todos:** seleciona todas as tarifas de uma vez.
* **Desmarcar:** limpa todas as seleções.

![](data:image/png;base64...)

**Condições de Aplicabilidade**

Aqui você define **em que período a oferta será válida** e, se quiser, adiciona **filtros adicionais**.

**Botão “Novo Filtro”**

O botão **“NOVO FILTRO”** serve para configurar **regras e condições da oferta.**

**PERÍODO DA OFERTA**
 Defina o período da estadia em que a oferta poderá ser aplicada.

**PERÍODO DA COMPRA**
 Defina o período em que a compra deve ser realizada.

**ANTEDÊNCIA MÁXIMA**
 Defina qual a diferença máxima em dias entre a data da reserva e a data do check-in.

![](data:image/png;base64...)

**Forma de Desconto**

Essa seção define **como o desconto será aplicado**:

* **Percentual de Desconto:** campo numérico onde você insere o valor do desconto em porcentagem (%).

Exemplo: digite “10” para aplicar 10% de desconto.

* **Aplicar nas seguintes noites:** menu suspenso que permite escolher se o desconto será aplicado em:
  + **Todas as noites** da estadia;
  + **Dias da semana**, pode selecionar quais dias será aplicado o desconto.

![](data:image/png;base64...)

![](data:image/png;base64...)

Depois de preencher todas as informações, clique em:

* **SALVAR:** grava a oferta e envia para o canal.
* **CANCELAR:** descarta as alterações e retorna à listagem.

![](data:image/png;base64...)

Ao salvar, o sistema validará os dados e, se estiver tudo correto, a oferta aparecerá na tela principal de listagem com o status **ATIVO**.

**Tela de Configuração da Desconto de Estadia**

**Hoteisnet**

**Dados Gerais**

A primeira seção exibe informações básicas da promoção:

* **Criando oferta para o canal:** *HOTEISNET*.
* **Tipo da oferta no canal:** tipo de oferta classificada pelo canal.
* **Nome da oferta:** campo onde você digita o nome que vai identificar essa promoção, tanto dentro do Channel quanto no canal de destino.

Exemplo: “Desconto Fim de Semana” ou “Promo Novembro”.

![](data:image/png;base64...)

**Tipos de Tarifa**

Nesta seção, você define **a quais tarifas a oferta será aplicada**.

O sistema lista automaticamente as tarifas disponíveis no canal selecionado, como:

* *HS – Tarifa Flex c/ Café – Cartão*
* *HS – Tarifa Flex c/ Café – Faturamento*

Você pode marcar apenas as tarifas que devem participar da promoção.
 Há também os botões:

* **Marcar Todos:** seleciona todas as tarifas de uma vez.
* **Desmarcar:** limpa todas as seleções.

![](data:image/png;base64...)

**Condições de Aplicabilidade**

Aqui você define **em que período a oferta será válida** e, se quiser, adiciona **filtros adicionais**.

**Botão “Novo Filtro”**

O botão **“NOVO FILTRO”** serve para configurar **regras e condições da oferta.**

**PERÍODO DA OFERTA**
 Defina o período da estadia em que a oferta poderá ser aplicada.

**PERÍODO DA COMPRA**
 Defina o período em que a compra deve ser realizada.

**ANTEDÊNCIA MÁXIMA**
 Defina qual a diferença máxima em dias entre a data da reserva e a data do check-in.

![](data:image/png;base64...)

**Forma de Desconto**

Essa seção define **como o desconto será aplicado**:

* **Percentual de Desconto:** campo numérico onde você insere o valor do desconto em porcentagem (%).

Exemplo: digite “10” para aplicar 10% de desconto.

* **Aplicar nas seguintes noites:** menu suspenso que permite escolher se o desconto será aplicado em:
  + **Todas as noites** da estadia;
  + **Dias da semana**, pode selecionar quais dias será aplicado o desconto.

![](data:image/png;base64...)

![](data:image/png;base64...)

Depois de preencher todas as informações, clique em:

* **SALVAR:** grava a oferta e envia para o canal.
* **CANCELAR:** descarta as alterações e retorna à listagem.

![](data:image/png;base64...)

Ao salvar, o sistema validará os dados e, se estiver tudo correto, a oferta aparecerá na tela principal de listagem com o status **ATIVO**.

---

## Imagens do Documento

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image5_3a3b3b1c.png)

*Fonte: Hunit - Ofertas.docx - image5.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image32_0308316e.png)

*Fonte: Hunit - Ofertas.docx - image32.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image20_b1e9ea14.png)

*Fonte: Hunit - Ofertas.docx - image20.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image26_f550b576.png)

*Fonte: Hunit - Ofertas.docx - image26.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image27_9ac5dafe.png)

*Fonte: Hunit - Ofertas.docx - image27.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image30_a98ad984.png)

*Fonte: Hunit - Ofertas.docx - image30.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image34_04fb67d6.png)

*Fonte: Hunit - Ofertas.docx - image34.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_imagec_9868af36.png)

*Fonte: Hunit - Ofertas.docx - imagec.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image29_7e713618.png)

*Fonte: Hunit - Ofertas.docx - image29.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image7_5877f61f.png)

*Fonte: Hunit - Ofertas.docx - image7.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image9_bdbd800d.png)

*Fonte: Hunit - Ofertas.docx - image9.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image11_1d686d04.png)

*Fonte: Hunit - Ofertas.docx - image11.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image1a_cbf9447d.png)

*Fonte: Hunit - Ofertas.docx - image1a.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image1b_fe851eb7.png)

*Fonte: Hunit - Ofertas.docx - image1b.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image2d_632ac009.png)

*Fonte: Hunit - Ofertas.docx - image2d.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image3_623951f1.png)

*Fonte: Hunit - Ofertas.docx - image3.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image8_ab35e74f.png)

*Fonte: Hunit - Ofertas.docx - image8.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image25_455dbe4e.png)

*Fonte: Hunit - Ofertas.docx - image25.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image4_11c51aed.png)

*Fonte: Hunit - Ofertas.docx - image4.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_imageb_47e7c051.png)

*Fonte: Hunit - Ofertas.docx - imageb.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image12_2b251e94.png)

*Fonte: Hunit - Ofertas.docx - image12.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image21_746efeaa.png)

*Fonte: Hunit - Ofertas.docx - image21.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image2b_3cef762a.png)

*Fonte: Hunit - Ofertas.docx - image2b.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image2_fc431889.png)

*Fonte: Hunit - Ofertas.docx - image2.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_imagee_c5d1b832.png)

*Fonte: Hunit - Ofertas.docx - imagee.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image10_0a5c2237.png)

*Fonte: Hunit - Ofertas.docx - image10.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image19_bbea0ba7.png)

*Fonte: Hunit - Ofertas.docx - image19.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image1c_3dd28962.png)

*Fonte: Hunit - Ofertas.docx - image1c.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image31_cdc78c81.png)

*Fonte: Hunit - Ofertas.docx - image31.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_imagef_177d3acb.png)

*Fonte: Hunit - Ofertas.docx - imagef.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_imaged_b23be7f6.png)

*Fonte: Hunit - Ofertas.docx - imaged.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image15_6fb10891.png)

*Fonte: Hunit - Ofertas.docx - image15.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image1f_bf3a5a0b.png)

*Fonte: Hunit - Ofertas.docx - image1f.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image2a_18669ce7.png)

*Fonte: Hunit - Ofertas.docx - image2a.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image2c_ef19afcf.png)

*Fonte: Hunit - Ofertas.docx - image2c.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image35_d7a78d11.png)

*Fonte: Hunit - Ofertas.docx - image35.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image14_ade1e5cd.png)

*Fonte: Hunit - Ofertas.docx - image14.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image24_ca0936ef.png)

*Fonte: Hunit - Ofertas.docx - image24.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image28_313602f6.png)

*Fonte: Hunit - Ofertas.docx - image28.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image2f_e6eb1fe6.png)

*Fonte: Hunit - Ofertas.docx - image2f.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image33_e16b667e.png)

*Fonte: Hunit - Ofertas.docx - image33.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image_9b1979d9.png)

*Fonte: Hunit - Ofertas.docx - image.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image13_c8504146.png)

*Fonte: Hunit - Ofertas.docx - image13.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image16_eebc48c8.png)

*Fonte: Hunit - Ofertas.docx - image16.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image23_5eef9585.png)

*Fonte: Hunit - Ofertas.docx - image23.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image18_1a53e264.png)

*Fonte: Hunit - Ofertas.docx - image18.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image1d_c78af1ef.png)

*Fonte: Hunit - Ofertas.docx - image1d.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image2e_7a74c0ea.png)

*Fonte: Hunit - Ofertas.docx - image2e.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image6_8e079bc2.png)

*Fonte: Hunit - Ofertas.docx - image6.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_imagea_97f7a1b4.png)

*Fonte: Hunit - Ofertas.docx - imagea.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image17_cb8abdf5.png)

*Fonte: Hunit - Ofertas.docx - image17.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image1e_016ac020.png)

*Fonte: Hunit - Ofertas.docx - image1e.png*

### Imagem de 54a09d31_Hunit - Ofertas.docx

![Imagem de 54a09d31_Hunit - Ofertas.docx](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Ofertas_image22_f542b26a.png)

*Fonte: Hunit - Ofertas.docx - image22.png*

