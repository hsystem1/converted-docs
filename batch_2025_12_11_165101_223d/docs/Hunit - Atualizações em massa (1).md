Documentação: Atualizações - Atualizações

Visão geral

Este documento descreve o processo de atualizações em massa no sistema Hunit (Gestor de canais)

**Objetivo da funcionalidade**

A tela de **Atualizações em Massa** tem como objetivo facilitar o gerenciamento de tarifas, disponibilidade e restrições de hospedagem para múltiplos canais de venda de forma centralizada. Através dela, o usuário pode definir valores e regras para diferentes tipos de quartos e aplicar essas informações simultaneamente em todos os canais conectados ao sistema.

**Caminho de acesso:**
 Menu superior → **Atualizações** → **Atualizações**

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Atualizaçõ_image3_06ad5f54.png)

Tela de Atualizações em Massa — Gerenciamento de Tarifas e Disponibilidade nos Canais de Venda.

**Períodos**

Nesta área, você define o intervalo de datas que será atualizado.

* **Início e Fim:** campos de data em que se determina o período de vigência das atualizações.
* **Dias da Semana:** seleção dos dias em que as regras serão aplicadas (domingo a sábado).
   Há também opções para **marcar todos**, **desmarcar** ou **inverter** as seleções dos dias.

**Marcar todos:** Marca todos os dias da semana.

**Desmarcar:** Desmarcar, remove a seleção dos dias da semana.

**Inverter:** Se os dias da semana estão marcados ele desmarcar e se estão desmarcados ele marca.
**Exemplo:** Segunda, terça, quarta e quinta estão marcados e sexta, sábado e domingo desmarcados, ao clicar em inverter, segunda, terça, quarta e quinta serão desmarcados e sexta, sábado e domingo serão marcados.

**Ícone de "+" (Adicionar):** Geralmente usado para criar múltiplos períodos simultaneamente.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Atualizaçõ_imagea_40b4974f.png)

**Lista de Atualizações**

Aqui são exibidos os **tipos de quartos** cadastrados no sistema, como STD (Standard) e LX (Luxo), com variações de tipo de tarifa (Reembolsável/Flex ou NR (Não reembolsável; com café ou sem café, entre outros)

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Atualizaçõ_image4_a57e8f98.png)

Cada linha apresenta colunas editáveis para definir:

* **Tarifa de Venda:** valor da diária que será enviada aos canais.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Atualizaçõ_image8_7ca9b27f.png)

* **Disponibilidade:** quantidade de unidades disponíveis para venda (Quantos quartos da categoria estão disponíveis).

Importante: Essa coluna só aparece se o hotel não possuir integração com PMS (Gestor interno hoteleiro) para gestão de disponibilidade.

Caso exista integração para disponibilidade, a coluna não ficar disponível, para evitar divergências.

Nesse cenário, a disponibilidade deve ser sempre controlada pelo PMS (Gestor interno hoteleiro).

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Atualizaçõ_image_098f4608.png)

* **Estadia Mínima (Est. Mín.):** número mínimo de noites exigido para reserva.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Atualizaçõ_image5_8f5b9300.png)

* **Chegada / Saída / Venda:** menus suspensos que permitem aplicar restrições, como bloquear entrada, saída ou venda em determinadas datas.

**Chegada** - Quando está **aberto**, o sistema aceita check-in normalmente.

Quando está **fechado**, significa que, naquela data específica, o sistema não permite o check-in. O hóspede pode estar hospedado nesse dia, mas não pode iniciar a estadia nessa data. Indica que não é permitido iniciar a reserva (check-in) nessa data.

**Saída** - Quando está **aberto**, o sistema aceita checkout normalmente.

Quando está **fechado**, indica que não é possível fazer checkout naquela data. O hóspede pode estar hospedado ou até mesmo entrar nesse dia, mas não pode finalizar a estadia nele. Significa que não é possível encerrar a reserva (checkout) nessa data.

**Venda** - Quando está **aberto**, o sistema aceita novas reservas normalmente.

Quando está **fechado**, as vendas ficam bloqueadas, impedindo que novas reservas sejam realizadas. Mesmo que haja disponibilidade (número de unidades ainda maior que 0, no topo da coluna), o sistema não permite efetuar reservas nessa data. É uma forma de “bloquear” vendas sem precisar zerar a disponibilidade.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Atualizaçõ_image2_dd27b23c.png)

**Função da Seta para baixo (Botão de Cópia)**

Este botão com ícone de seta para baixo, localizado no topo das colunas, permite copiar automaticamente a informação inserido para as demais.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Atualizaçõ_image6_d48ee568.png)

**Seção de Canais**

Na parte inferior da tela, você escolhe em quais canais de distribuição (OTA’s) as atualizações serão aplicadas.

Caixas de seleção: Permitem escolher individualmente os canais.

Marcar Todos / Desmarcar Todos: para selecionar ou limpar rapidamente todos os canais.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Atualizaçõ_image7_192e051b.png)

Por fim, clicar no botão **“Atualizar”**, no canto inferior direto.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Hunit_-_Atualizaçõ_image9_c1b89a77.png)

Metadados do Documento

|  |  |
| --- | --- |
| **Sistema:** | **HUNIT (Gestor de canais)** |
| **Módulo:** | Atualizações |
| **Funcionalidade:** | Atualizações |
| **Data de referência:** | 28/10/2025 |
| **Tipo de documento:** | Guia de configuração |