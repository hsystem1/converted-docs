**Documentação: Lista de reservas**

**Visão geral**

Este documento descreve o processo de uso da tela de lista de reservas no sistema Hbook (Motor de reservas)

**Objetivo da funcionalidade**

A tela de listagem de reservas foi desenvolvida para oferecer ao cliente uma visão completa e detalhada das reservas realizadas em seu motor de reservas, permitindo consultas rápidas, aplicação de filtros, geração de relatórios personalizados e acesso às informações do voucher de cada reserva.

Essa estrutura permite ao cliente filtrar e segmentar as reservas conforme a necessidade, seja para fins operacionais, financeiros, de marketing ou atendimento ao cliente. Além disso, os resultados podem ser usados para exportações, geração de relatórios ou simplesmente para acesso rápido às informações do voucher.

**Filtros disponíveis para busca personalizada:**

**Status da Reserva:** Qual status a reserva se encontra.

* **Ativas**: Reserva confirmada;
* **Canceladas**: Reserva foi cancelada;
* **NoShow**: Reserva foi cancelada por não comparecimento do hospede;
* **Abandonadas**: Cliente abandonou o carrinho antes de concluir (clicar em "reservar");
* **Erro no pagamento**: Caso tenha HPay, ao inserir dados de cartão invalidas vai acusar erro de pagamento, esse filtro traz as tentativas de reservas, que não foram concluídas por erro no pagamento;
* **Orçamentos**: Reservas ainda não concluídas, que foram enviadas como orçamento para o cliente;
* **Recuperadas**: Reservas que constavam como abandonadas e viraram ativas.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Lista_image_cfe3de1a.png)

**Dispositivos da reserva:** Por qual aparelho foi realizado a reserva do hospede.

* **Desktop**: Reserva feita por computador/notebook/pc;
* **Mobile**: Reserva feita por celular

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Lista_imagea_f256b4ad.png)

**Somente reservas de:**

* **Hóspedes estrangeiros**: Busca pela localização identificada, todas as reservas feitas de fora do Brasil. Aquelas reservas que não foi identificado uma localidade também são apresentadas na busca;
* **Código promocional**: Reservas efetivadas com uso de código promocional;
* **Hóspede aceitou a política de privacidade**: Quando o hotel possui política de privacidade e o hóspede dá aceite para concluir a reserva;
* **Via ChatBot**: Quando o hotel possui o produto HBOT contratado, filtra as reservas que vieram por meio da finalização com o Bot;
* **Somente reserva com extras**: Reservas que o hospede selecionou extras/adicionais na reserva.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Lista_image11_3c4befe0.png)

**Período:** Filtro de datas.

* **Data da Reserva**: Corresponde o dia em que o hóspede comprou, filtro quando quer consultar quando a reserva foi realizada;
* **Data do Check-in:** Corresponde a data de entrada do hóspede no hotel, filtro quando quer consultar as reservas por entradas;
* **Data do Checkout**: Corresponde a data de saída do hóspede do hotel, filtro quando quer consultar as reservas por saídas;
* Campo de inserir datas (Calendário) pode ser consultado datas passadas e futuras.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Lista_image3_887ca194.png)

**Forma de pagamento:** Como o hóspede escolheu pagar a reserva.

* **Todas as Formas de Pagamento**: Filtra todas as reservas feitas independente da forma de pagamento;
* **Pagamento com Cartão de Crédito:** Filtra todas as reservas feitas como cartão de crédito;
* **Pagamento por Depósito:** Filtra todas as reservas feitas como depósito bancário;
* **Pagamento via PIX**: Filtra todas as reservas feitas como pagamento pix;
* **Pagamento Direto no Hotel:** Filtra todas as reservas feitas como pagamento direto no hotel (pagamento balcão/check-in).

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Lista_image4_b0eff850.png)

**Dados da Reserva:**

* **Nº da Reserva:** Número identificador da reserva, gerado após a conclusão pelo hóspede;
* **Código Promocional:** O nome do código promocional que foi utilizado pelo hóspede para efetivar a reserva;
* **Nº de Autorização:** Cliente que tem HPAY, número gerado pela adquirente do hotel, que registrou a transação, é um código identificador da transação;
* **Nome do Hóspede:** Busca pelo nome do hóspede, quem realizou a reserva.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Lista_image6_7f3ab2b7.png)

**Parâmetros UTM:** Eles servem basicamente para rastrear através de qual meio o hóspede chegou ao motor de reservas. Caso o hotel possua uma empresa de marketing, ela pode criar campanhas atreladas ao link do motor, e o campo de UTM serve justamente para rastrear a origem do tráfego.

**Exemplo UTM**: https://hbook.hsystem.com.br/BookingcompanyId=58a4751dc19a3b2270600723&checkin=25/09/2025&checkout=27/09/2025&adults=2&children=0&language=pt&**utm\_source**=googlehotel (parte destacada indica a origem).

* **Origem (utm\_source)**: Origem do tráfego (ex: google hotel, facebook, newsletter);
* **Campanha (utm\_campaign)**: Nome da campanha (ex: black\_friday, promocao\_julho);
* **Meio (utm\_medium):** Meio/canal (ex: cpc, social, email, referral);
* **Term(utm\_term)**: Usado para palavras-chave (em campanhas de pesquisa paga);
* **Conteúdo (utm\_content)**: Diferenciar links dentro da mesma campanha (ex: banner1, banner2).

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Lista_imagee_07263f34.png)

Botão **“pesquisar”** = Após realizar os filtros desejados, tem que clicar neste botão para que gere a lista de reservas de acordo com o que foi inserido nos filtros.

Botão **“Exportar Emails”** = É possível extrair das reservas apenas uma listagem de email, geralmente para campanha de marketing.

Botão **“Exportar Reservas”** = Após realizar os filtros desejados e pesquisar, é possível extrair um relatório com as informações do voucher como CSV.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Lista_image7_318415e9.png)

**Detalhe:** O Downloads da reserva é por página gerada, ou seja, se a pesquisa gerar mais de uma página é preciso mudar para outra para extrair a informação.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Lista_image8_c8be2d22.png)

**Entendendo os Resultados da Busca:**

Assim que você realiza uma pesquisa no HBOOK — por exemplo, filtrando por data, status ou nome do hóspede — os resultados aparecem na parte inferior da tela.

É ali que você encontra um resumo claro e organizado de cada reserva.

### **Informações principais da reserva**

Cada linha da tabela representa uma **reserva individual**.
 Vamos ver o que aparece em cada coluna:

* **Reserva Nº**: mostra o número identificador único da reserva.

Clicando sobre o número da reserva (em azul), você pode **abrir os detalhes completos** da hospedagem — ver histórico, valores e forma de pagamento.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Lista_imageb_b78abe2d.png)

* **Hóspede**: nome e e-mail da pessoa que fez a reserva.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Lista_image13_74b74cfa.png)

* **Localidade**: país ou cidade de origem do hóspede.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Lista_image14_2abb5b23.png)

* **Tipo de Quarto**: categoria do quarto reservado, como “Suíte Standard Twin”.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Lista_image12_dc84ae1f.png)

* **Reservado**: data e hora em que a reserva foi feita.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Lista_image2_fc5e8cfb.png)

* **Período da Estadia**: mostra as datas de check-in e checkout.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Lista_image5_caf99c05.png)

* **Código Promocional**: campo usado caso o hóspede tenha aplicado um cupom de desconto.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Lista_image9_946f89b0.png)

* **Status**: indica se a reserva está *ativa ou cancelada*.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Lista_imagec_fe30feec.png)

* **Ícone de dispositivo – Desktop ou Mobile:** Esse ícone indica **de qual dispositivo a reserva foi feita**:

Ícone de computador → Reserva realizada via **desktop** (computador).

Ícone de celular → Reserva realizada via **mobile** (smartphone ou tablet).

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Lista_imagef_ff5b880b.png)

* **Total**: valor total da reserva.

Obs.: O VALOR CONSIDERA TOTAL DA RESERVA, CONSIDERANDO DIÁRIAS, TAXAS E EXTRAS.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Lista_image10_b1bd054b.png)

### **Resumo de Reservas**

Na parte inferior da tela, o HBOOK apresenta o **Resumo de Reservas** — um painel que mostra os **totais referentes à pesquisa que você realizou**.
 Ou seja, ele considera **apenas os resultados filtrados** na busca atual.

* A primeira coluna (**Nº de Reservas**) mostra **quantas reservas** foram encontradas.
* As demais colunas exibem **valores em reais (R$)**, como:
  + **No-shows** – valor correspondente às reservas em que o hóspede não compareceu;
  + **Ativas** – soma das reservas vigentes;
  + **Abandonadas –** Abandono de carrinho
  + **Erro no Pagamento –** pagamento não processado/negado
  + **Canceladas –** reservas caneladas pelo hotel ou hospede.
  + **Recuperadas** – reservas recuperadas do abandono de carrinho.
* **Importante:**
   Esse resumo serve tanto para visualizar os **totais da página exibida** quanto os **totais gerais da busca**, facilitando a análise financeira e operacional das reservas.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Lista_imaged_5c60868e.png)

Metadados do Documento

|  |  |
| --- | --- |
| **Sistema:** | **HBook (Motor de Reservas)** |
| **Módulo:** | Reservas |
| **Funcionalidade:** | Lista de reservas |
| **Data de referência:** | 28/10/2025 |
| **Tipo de documento:** | Guia de configuração |