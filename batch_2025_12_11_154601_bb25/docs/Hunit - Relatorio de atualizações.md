Documentação: Relatório de atualizações

Visão geral

Este documento descreve o processo de uso do relatório de atualizações no sistema Hunit (Gestor de canais)

**Objetivo da funcionalidade**

A tela de Relatório de Atualizações do channel manager — o espaço onde você pode acompanhar todas as atualizações de tarifas, disponibilidade e restrições que foram enviadas para os canais de venda conectados, como Booking, Expedia, Hotelbeds e outros.

Imagine que você acabou de ajustar preços ou liberar disponibilidade na tela de Atualizações em Massa. Aqui, nesta tela, é onde você confere se essas informações foram realmente processadas com sucesso pelos canais.

**Caminho de acesso:**
Menu superior → **Atualizações** → **Relatório de atualizações**

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_154601_bb25/images/Hunit_-_Relatorio_de_image_d339c380.png)

Tela de Relatório de Atualizações — Acompanhamento das Atualizações Enviadas aos Canais de Venda

**Filtros de Consulta**

Na parte superior da tela, estão os filtros que você pode utilizar para gerar relatórios mais específicos:

1. Status da Atualização

Aqui você escolhe qual tipo de resultado deseja visualizar:

* **Todos:** mostra todas as atualizações registradas.
* **Pendente:** atualizações que ainda estão em processamento pelo canal.
* **Sucesso:** atualizações concluídas com êxito.
* **Bloqueado:** atualizações impedidas por alguma restrição do canal.
* **Cancelado:** ações que foram canceladas.
* **Somente Disponibilidade:** exibe apenas as atualizações relacionadas à disponibilidade de quartos.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_154601_bb25/images/Hunit_-_Relatorio_de_imagec_03a3ca5e.png)

**Período (Data de Submissão)**

**De / Até:** selecione o intervalo de datas em que as atualizações foram enviadas.

Isso é útil para acompanhar, por exemplo, tudo o que foi alterado durante uma semana específica. Selecionar um intervalo máximo de **2 dias** entre as datas.
 Isso garante uma consulta mais precisa e evita relatórios muito extensos, facilitando a visualização das informações.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_154601_bb25/images/Hunit_-_Relatorio_de_image5_52e9664c.png)

**Canais**

Campo para escolher um canal de venda específico (como Booking.com, Expedia, Hotelbeds etc.).

Caso queira um relatório de todos os canais, basta selecionar a opção “todos” na listagem.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_154601_bb25/images/Hunit_-_Relatorio_de_image7_4203a7ab.png)

**Tipo de Quarto**

Permite filtrar as atualizações por categoria de acomodação (ex.: Standard, Luxo, Suíte etc.).

Você pode visualizar todas ou apenas um tipo específico.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_154601_bb25/images/Hunit_-_Relatorio_de_image10_5ad41a21.png)

**Origem**

Esse campo mostra de onde partiu a atualização dentro do sistema.

As opções incluem:

**Todas**: mostra todas as origens.

**Tela Atualização:** atualizações feitas manualmente na tela de Atualizações em Massa.

**Grade de Disponibilidade:** alterações feitas diretamente na grade de disponibilidade.

**Inventário Integrado:** atualizações vindas de integrações externas, como PMS (Gestor interno hoteleiro).

Dica: se você quer confirmar uma atualização que fez manualmente, selecione “Tela Atualização” em Origem.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_154601_bb25/images/Hunit_-_Relatorio_de_image12_14e2621d.png)

**Gerar Relatório**

Depois de ajustar os filtros conforme sua necessidade, clique em **“Gerar Relatório”**.

O sistema vai listar todas as atualizações que atendem aos critérios escolhidos.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_154601_bb25/images/Hunit_-_Relatorio_de_image13_b65da342.png)

Depois que você clica em “Gerar Relatório” na tela de Listagem de Atualizações.

Esta etapa exibe o resultado detalhado de todas as atualizações enviadas aos canais de venda dentro do período selecionado — permitindo acompanhar cada requisição feita pelo sistema e confirmar se tudo foi processado corretamente.

**Visualização do Relatório**

Após clicar em Gerar Relatório, o sistema apresenta uma lista organizada com todas as atualizações correspondentes aos filtros aplicados.

Cada linha da tabela representa uma requisição enviada para um canal de venda (por exemplo, Expedia, Booking, Hotelbeds, etc.).

**Colunas da Tabela**

**1. Data da Requisição**

Mostra o **dia e horário exato** em que a atualização foi enviada ao canal.
 Isso permite identificar quando o sistema fez o envio e se corresponde ao momento da sua ação manual.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_154601_bb25/images/Hunit_-_Relatorio_de_image8_5f9b5269.png)

**2. Período**

Exibe o **intervalo de datas** ao qual a atualização se refere — por exemplo, tarifas e disponibilidade aplicadas de *01/11/2025 até 16/12/2025*.
 Logo abaixo, o sistema também mostra **os dias da semana** incluídos (Dom, Seg, Ter, Qua, Qui, Sex, Sáb).

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_154601_bb25/images/Hunit_-_Relatorio_de_imagea_e15c0ed3.png)

3. Canal

Informa **para qual canal de venda** a atualização foi enviada — como *Expedia*, *Booking.com*, *Hotelbeds*, entre outros.
 Esse campo é útil para conferir se o envio foi feito para o canal correto.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_154601_bb25/images/Hunit_-_Relatorio_de_imagef_357bed3e.png)

**4. Tipo de Quarto**

Indica a **categoria de acomodação** afetada pela atualização (ex.: *Stand Twin 2 Pax*, *Stand Twin 1 Pax – Sem Café*, *FAT*, *Cartão*, etc.).
Assim, o usuário consegue confirmar exatamente qual quarto e tarifa foram atualizados.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_154601_bb25/images/Hunit_-_Relatorio_de_image11_8e545e0b.png)

5. Tarifa Venda / Tarifa Net

Essas colunas exibem, quando aplicável, os valores de **tarifa pública (venda)** e **tarifa líquida (net)** que foram enviados ao canal.
 Se deixadas em branco, significa que o envio se referiu a outro tipo de atualização (como disponibilidade ou restrição).

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_154601_bb25/images/Hunit_-_Relatorio_de_image4_964317ea.png)

**6. Estadia Mínima (Est. Mín.)**

Mostra se houve definição ou alteração do número mínimo de noites exigido para reservas no período selecionado.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_154601_bb25/images/Hunit_-_Relatorio_de_image6_1c6d1392.png)

**7. Disponibilidade**

Indica a **quantidade de unidades disponíveis** enviadas para o canal, refletindo o estoque atualizado do tipo de quarto.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_154601_bb25/images/Hunit_-_Relatorio_de_imaged_7070af77.png)

**8. Data de Chegada e Partida**

Essas colunas mostram eventuais restrições aplicadas às **datas de check-in (chegada)** e **check-out (partida)**.
 São usadas, por exemplo, quando o hotel bloqueia entradas ou saídas em dias específicos.

O sistema exibe as opções **“Sim”** ou **“Não”**, da mesma forma que no campo *Venda Parada*:

* **Sim:** existe restrição configurada (bloqueio de chegada ou saída).
* **Não:** sem restrição; as reservas são permitidas normalmente.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_154601_bb25/images/Hunit_-_Relatorio_de_imagee_b331b659.png)

**9. Venda Parada**

Campo que mostra se a venda foi **bloqueada (Sim)** ou **mantida aberta (Não)** naquele canal e período.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_154601_bb25/images/Hunit_-_Relatorio_de_image2_058aedef.png)

**10. Usuário**

Identifica **quem realizou a atualização**, permitindo rastrear qual usuário fez o envio.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_154601_bb25/images/Hunit_-_Relatorio_de_image9_be5628fa.png)

**11. Origem**

Aponta **de onde a atualização foi gerada** dentro do sistema.
 No exemplo, todas vieram da **Tela Atualização**, indicando que foram feitas manualmente.
 Outras origens possíveis incluem: *Grade de Disponibilidade e Serviço Integração.*

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_154601_bb25/images/Hunit_-_Relatorio_de_image3_ffabfc74.png)

**12. Status**

Mostra o **resultado da atualização**:

* ✅ **Sucesso:** a informação foi enviada e processada corretamente pelo canal.
* ⚠️ **Pendente:** atualização ainda em processamento, aguardando canal receber.
* ❌ **Bloqueado ou Cancelado:** falha ou impedimento no envio

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_154601_bb25/images/Hunit_-_Relatorio_de_imageb_9af14912.png)

Metadados do Documento

|  |  |
| --- | --- |
| **Sistema:** | **HUNIT (Gestor de canais)** |
| **Módulo:** | Atualizações |
| **Funcionalidade:** | Relatório de atualizações |
| **Data de referência:** | 28/10/2025 |
| **Tipo de documento:** | Guia de configuração |