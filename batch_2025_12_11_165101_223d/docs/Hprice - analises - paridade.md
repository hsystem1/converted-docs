Documentação: Paridade

Visão geral

Este documento descreve as informações da tela de paridade na aba de análises no sistema Hprice (Flutuação).

**Objetivo da funcionalidade**

Aqui é onde monitoramos se o seu motor de reservas está com as tarifas em paridade com os canais de venda, mesmo que ele tenha uma promoção de venda direta.

Essa tela é essencial para verificar se os preços exibidos no **motor de reservas da sua propriedade** estão alinhados com os preços publicados na **Booking.com**, garantindo consistência e evitando problemas de disparidade tarifária.

Para acessar esta funcionalidade, siga o caminho:

**HPrice → Análises → Paridade**.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hprice_-_analises_-__image5_4aa50ee4.png)

**Configurando a Visualização**

No topo da tela, você encontra diversos filtros que permitem personalizar sua análise:

* **PESSOAS**: Aqui você define quantas pessoas considerar na busca (1 pessoa, 2 pessoas, 3 pessoas, ..., 10 pessoas)
* **PENSÃO**: Selecione o tipo de pensão (Todos, meia pensão, pensão completa etc.)
* **CANCELAMENTO**: Filtre por política de cancelamento (Todos, NR, Flex, Parcial)
* **FAIXA DE DIAS**: Este é um filtro importante! Você pode escolher entre 7, 15 ou 30 dias de visualização de preço para analisar como suas tarifas se comparam em diferentes janelas de reserva
* **TAMANHO DA ESTADIA**: Defina para qual duração de estadia você quer fazer a análise (Qualquer, 1 noite, 2 noites, 3 noites)

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hprice_-_analises_-__image6_8069c7df.png)

No canto superior direito da tela, é exibida a **data e hora da última pesquisa**, indicando quando as informações foram atualizadas pela última vez.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hprice_-_analises_-__image_0d567aac.png)

**O Gráfico Principal: Sua Bússola Visual**

O gráfico no centro da tela é onde a mágica acontece! Ele mostra duas linhas:

* **Linha azul clara (Booking.com)**: Representa suas tarifas praticadas na Booking
* **Linha roxa (Motor de reservas)**: Suas tarifas configuradas no sistema

No exemplo que estamos vendo, note um ponto interessante em 05 de novembro:

* Booking.com: 179
* Motor de reservas: 680

Veja como as linhas se comportam ao longo do tempo. Quando a linha roxa está muito acima da azul, pode significar que você está menos competitivo. Quando estão próximas, há paridade.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hprice_-_analises_-__image2_8fbb1aad.png)

**A Tabela de Valores Diários**

Logo abaixo do gráfico, você encontra uma tabela detalhada com três linhas principais:

**1. BOOKING.COM**

Mostra as suas tarifas praticadas pela OTA dia a dia. Os valores em vermelho claro indicam os preços específicos para cada data.

**2. MOTOR DE RESERVAS**

Exibe suas tarifas configuradas. Caso em algum dia apareça como "S/D" (Sem Dados), pode indicar falta de configuração.

**3. DIFERENÇA**

Ela mostra em percentual a diferença entre suas tarifas do motor de reservas e as da OTA. Percentuais negativos indicam que o Motor de Reservas está com tarifas significativamente mais altas que o Booking.com

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hprice_-_analises_-__image4_33aa5dd5.png)

Quando você **passa o mouse sobre os valores** na tabela de Valores Diários, uma janela pop-up aparece com informações detalhadas. No exemplo abaixo, ao posicionar o cursor sobre o valor do Booking.com, você pode ver:

**Informações Exibidas no Tooltip:**

**SUÍTE** (Nome da categoria do quarto)

**👤 2** | **SOMENTE CAMA** | **PARCIAL**

Estes detalhes revelam:

* **Número de pessoas**: 2 hóspedes
* **Tipo de pensão**: Somente cama (sem refeições incluídas)
* **Política de cancelamento**: Parcial

Também apresenta um aviso contextual aparece quando há uma discrepância significativa, ajudando você a identificar rapidamente situações que precisam de atenção imediata.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hprice_-_analises_-__image3_d4a64bf3.png)

Metadados do Documento

|  |  |
| --- | --- |
| **Sistema:** | **HPRICE (Flutuação)** |
| **Módulo:** | Análises |
| **Funcionalidade:** | Paridade |
| **Data de referência:** | 03/11/2025 |
| **Tipo de documento:** | Guia de configuração |