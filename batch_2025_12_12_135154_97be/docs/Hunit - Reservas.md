Documentação: Reservas

Visão geral

Este documento descreve o processo de uso da tela de reservas no sistema Hunit (Gestor de canais)

**Objetivo da funcionalidade**

É nesta tela que você pode **visualizar, filtrar e exportar todas as reservas** recebidas pelos canais de venda, além de acompanhar o status de integração com o PMS (sistema de gestão hoteleira).

Aqui, você consegue identificar **quem reservou, por qual canal, qual o período da estadia e o valor total**, tudo de forma rápida e organizada.

**Caminho de acesso:**
Menu superior → **Reservas**

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hunit_-_Reservas_image2_733668f0.png)

Tela de Reservas — Consulta e Gerenciamento de Reservas no Channel Manager

A tela é dividida em duas partes principais:

1. **Filtros de pesquisa** — para localizar reservas específicas.
2. **Lista de resultados** — onde são exibidos os dados das reservas filtradas.

Vamos ver como cada parte funciona

**1. Filtros de Pesquisa**

A parte superior da tela permite refinar a busca com diferentes filtros, garantindo uma consulta mais precisa.

**Status da Reserva**

Permite escolher quais tipos de reservas deseja visualizar:

* **Todas:** exibe todas as reservas, independentemente do status.
* **Ativas:** reservas confirmadas e ainda válidas.
* **Canceladas:** reservas que foram canceladas no canal.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hunit_-_Reservas_image17_741b40d6.png)

**Tipo de Coleta de Pagamento**

Define o modelo de cobrança utilizado no canal:

* **Todos:** mostra todos os tipos.
* **Hotel Collect:** pagamento realizado diretamente no hotel.
* **Canal Collect:** pagamento processado pelo próprio canal, o canal cobra do hóspede e repassar ao hotel conforme acordado previamente (acorde entre canal e hotel). (ex.: Booking ou Expedia).

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hunit_-_Reservas_imagec_aad1e32f.png)

**Status da Cobrança**

Indica a situação da cobrança associada à reserva. Este filtro somente é apesentado para clientes que possuem o produto HPAY-HUNIT.

* **Todos**: Mostra reservas independentemente do status de cobrança.
* **Cobrado**: A cobrança foi concluída com sucesso.
* **Falha na Cobrança**: Ocorreu erro ao tentar processar o pagamento.
* **Cobrança Não Efetuada**: Ainda não houve tentativa ou conclusão de cobrança.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hunit_-_Reservas_imagef_fcedc41e.png)

**Status da Integração (PMS)**

Mostra o status da comunicação da reserva com o PMS (Gestor interno hoteleiro).

* **Todas**: Inclui todos os status.
* **1 – Pendente:** Reserva aguardando PMS acatar (disponível na API).
* **2 – Sucesso:** Reserva enviada e confirmada com sucesso no PMS.
* **3 – Com Erro**: Houve falha ao enviar a reserva para o PMS.
* **4 – Não Habilitado Integração**: A integração não está ativa, não possui integração com PMS. Ou quando a reserva entrou ainda não possuía a integração com PMS.
* **5 – Cancelada**: Reserva disponibilizada 20 vezes na API e não foi acatado pelo PMS.

Dica: se uma reserva aparece com erro ou cancelada, pode acionar nosso time de suporte para análise.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hunit_-_Reservas_image11_26c3a14c.png)

**Tipo de Data (Filtros de Período)**

Permite definir o tipo de data usado na busca:

* **Data da Reserva:** Busca pela data em que a reserva foi criada, quando o hóspede comprou.
* **Data do Check-in:** Busca conforme a data de entrada do hóspede.
* **Data do Checkout:** Busca conforme a data de saída do hóspede.
* **Data do Cancelamento/Modificação:** Considera a data em que houve cancelamento ou alteração.

**Campos associados:**

De / Até: Define o intervalo de datas (inicial e final) para o filtro selecionado.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hunit_-_Reservas_image8_ebb6ad51.png)

**Filtros Adicionais**

* **Nº da Reserva:** para buscar uma reserva específica.
* **Nome do Hóspede:** pesquisa pelo nome informado no canal.

Ícone de ajuda ao lado exibe orientações sobre a forma de busca.

Orientação: Para realizar o filtro por nome é necessário o preenchimento de pelo menos 3 caracteres.

Para otimizar a consulta, utilize também o filtro por datas.

* **Nº Integração PMS:** busca a reserva com base no código de integração do PMS.
* **Canais:** filtra por canal de venda (ex.: Booking, HBOOK, Expedia, etc.).
* **Tipo de Quarto:** permite selecionar a categoria da acomodação (ex.: Suíte, Luxo, Standard).

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hunit_-_Reservas_image19_09ca5887.png)

**Botões de Ação**

* **Filtrar:** aplica os filtros definidos e atualiza a listagem.
* **Exportar Reservas:** exporta as informações em CSV para planilha, facilitando relatórios e análises.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hunit_-_Reservas_image3_d6ab273d.png)

**2. Lista de Reservas**

Após aplicar o filtro, o sistema apresenta os resultados em formato de tabela, com todas as informações detalhadas da reserva.

**Campos apresentados:**

* **Reserva Nº:** número original da reserva no canal (clicável para detalhes).

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hunit_-_Reservas_imagea_b019182d.png)

* **Hóspede:** nome do cliente.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hunit_-_Reservas_image18_c452e3f7.png)

* **Canal:** origem da reserva (ex.: *HBOOK, Booking, Expedia*).

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hunit_-_Reservas_image5_528ba9fc.png)

* **Tipo de Quarto:** categoria e nome da acomodação reservada.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hunit_-_Reservas_imageb_0f68bee6.png)

* **Reservado:** data e hora em que a reserva foi registrada.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hunit_-_Reservas_image10_f8ad03fa.png)

* **Período da Estadia:** datas de check-in e checkout.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hunit_-_Reservas_image12_c15f610c.png)

* **Nº Integração PMS:** identifica o vínculo com o PMS. Dependendo do PMS gera um código de integração, quando a reserva está confirmada o recebimento por eles é gerado esse código.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hunit_-_Reservas_image15_12626a2e.png)

* **Integração:** mostra o status da integração com PMS.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hunit_-_Reservas_image4_aec56d42.png)

* **Última Modificação:** data e hora da última atualização recebida.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hunit_-_Reservas_image6_0b5c5e31.png)

* **Status:** exibe o estado da reserva (ex.: *Ativa*, *Cancelada*).
* ![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hunit_-_Reservas_image7_6da6648c.png)
* **Pagamento:** método de pagamento registrado.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hunit_-_Reservas_image14_89e27365.png)

* **Cartão:** Apresentado quando possui o produto HPAY-HUNIT. O desenho de cartão representa o status de cobrança.

As cores representam o status do processamento:

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hunit_-_Reservas_image9_548f6c4d.png) Processado

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hunit_-_Reservas_imaged_f71c31d8.png) Negado

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hunit_-_Reservas_imagee_01ecbad5.png) Não processado

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hunit_-_Reservas_image13_50ac0e0f.png)

* **Total:** valor total da reserva.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hunit_-_Reservas_image16_e974d7b7.png)

**Totais e Resumo**

Na parte inferior da tabela, o sistema exibe os **totais consolidados**:

* **Totais da Página:** soma apenas as reservas exibidas na tela.
* **Totais Gerais:** soma de todas as reservas filtradas, mesmo que em múltiplas páginas.
   São mostrados separadamente os valores de **canceladas**, **ativas**, **total geral** e **comissão**.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hunit_-_Reservas_image_68f286b4.png)

Metadados do Documento

|  |  |
| --- | --- |
| **Sistema:** | **HUNIT (Gestor de canais)** |
| **Módulo:** | Reservas |
| **Funcionalidade:** | Reservas |
| **Data de referência:** | 29/10/2025 |
| **Tipo de documento:** | Guia de configuração |