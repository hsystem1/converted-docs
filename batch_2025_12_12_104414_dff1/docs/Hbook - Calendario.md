Documentação: Calendário

Visão geral

Este documento descreve o processo de configuração do calendário no sistema Hbook (Motor de reservas)

**Objetivo da funcionalidade**

Dentro da área de Calendário, existem diferentes abas que permitem gerenciar as informações de forma prática e segmentada. Cada aba possui uma função específica.

**Acesso a funcionalidade**

Acessar a ferramenta Hbook (Motor de reservas)

Caminho: Calendário

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_-_Calendario_image7_214c6965.png)

**Informações por tela:**

**Aba Grade:**

Exibe a visão geral das tarifas, disponibilidades e restrições em formato de tabela.

É a tela principal, usada para consultar rapidamente as informações.

**Campo de calendário** - Para selecionar o período que deseja verificar as informações. Após selecionar data tem que clicar em carregar.

Caso queira ver datas passada, é necessário digitar a data no campo de calendário.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_-_Calendario_image15_ecb44693.png)

**Estrutura da Tabela de Tarifas e Disponibilidade:**

**Cabeçalho (datas)** - Na parte superior estão os **dias do mês**, organizados por **dia da semana + data** (ex.: QUA 24 set, QUI 25 set).

* Isso permite visualizar **valores e disponibilidade dia a dia**.
* Avança em ordem cronológica, facilitando o planejamento.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_-_Calendario_image16_4d9654cd.png)

**Nome do Alojamento / Quarto / Cabana / Categoria** - Na primeira coluna da esquerda, aparecem os **nomes dos quartos**, que são as unidades disponíveis para reserva.

* Isso ajuda a identificar onde a tarifa está sendo aplicada

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_-_Calendario_image2_d42d8307.png)

**Plano Tarifário** - Logo abaixo do nome da acomodação, aparecem as **opções de tarifas** para reservar e quantidade de pessoas.

* Cada um pode ter regras de preço diferentes.
* Ao lado do plano tarifário, há a divisão por quantidade de pessoas (Pax):

**1 pessoa**

**2 pessoas**

**3 pessoas**

**4 pessoas**

Isso mostra que a tarifa **varia conforme a ocupação**.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_-_Calendario_image9_3d30999a.png)

**Disponibilidade (estoque de unidades)** - O número que aparece no topo de cada linha (acima das tarifas, em cinza claro) mostra a **quantidade de unidades disponíveis** na categoria.

* Quando o número está **0 em vermelho**, significa que **não há disponibilidade para reserva**.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_-_Calendario_imageb_a03d6c87.png)

**Valores Diários (tarifas)** - No corpo da tabela, aparecem os **valores cobrados por dia** para cada tipo de ocupação.

* Esses números representam o **preço por diária**.
* O que está como **0 não tem preço ainda lançado.**
* Sem preço não reflete para venda.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_-_Calendario_imagee_ad3f6b1a.png)

**Legenda:**

* **Ocultar tarifas:** Serve para “esconder” os planos tarifários, preço e Pax. Deixar **somente as disponibilidades das categorias**.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_-_Calendario_image6_03e4da88.png)

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_-_Calendario_image19_edeb2786.png)

* **Restrições:** Quando a opção **“restrições”** está marcada (check azul), aparecem campos adicionais, como:

**Estadia mínima** - Define o número mínimo de noites que o hóspede precisa reservar.

Exemplo:

Valor 2 → significa que o hóspede deve reservar pelo menos 2 noites para conseguir efetuar a reserva.

Serve para evitar reservas de apenas 1 noite em períodos estratégicos (feriados, finais de semana prolongados, alta temporada).

**Fechado para chegada** - Significa que, naquela data específica, o sistema **não permite o check-in.** O hóspede pode estar hospedado nesse dia, mas não pode **iniciar a estadia** nessa data.

Representado pela letra X.

Indica que não é permitido iniciar a reserva (check-in) nessa data.

Exemplo:

O X em 25/set mostra que ninguém pode começar a estadia nesse dia, mas hóspedes que já entraram antes podem continuar hospedados.

**Fechado para saída** - Indica que não é possível **fazer checkout** naquela data. O hóspede pode estar hospedado ou até mesmo entrar nesse dia, mas **não pode finalizar a estadia nele**.

Também marcado com X.

Significa que não é possível encerrar a reserva (checkout) nessa data.

Exemplo:

O X em 26/set mostra que os hóspedes não podem sair nesse dia, precisando ajustar sua estadia para antes ou depois.

Geralmente usado para evitar saídas no meio de pacotes ou em datas de alta movimentação.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_-_Calendario_image_64e43e37.png)

* **Preço em vermelho riscado (Stop de Vendas):** Na tabela, quando a tarifa aparece **em vermelho e com risco (tachado)**, significa que está aplicado um **stop de vendas**.

**O que isso quer dizer?**

Mesmo que haja disponibilidade (número de unidades ainda maior que 0, no topo da coluna), o sistema não permite efetuar reservas nessa data.

É uma forma de “bloquear” vendas sem precisar zerar a disponibilidade.

**Quando usar:**

Estratégia de gestão para interromper vendas em certas datas, mesmo com unidades vagas.

Usado, por exemplo, quando a hospedagem decide não vender online em uma data específica, seja para manutenção, bloqueio interno ou venda apenas via outro canal (telefone, balcão, agência).

**Diferença importante:**

Disponibilidade = 0 → significa que não existem unidades/quartos/vagas livres.

Stop de vendas (preço riscado) → significa que ainda existem unidades livres, mas o sistema foi configurado para não permitir reservas.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_-_Calendario_image3_57602d6a.png)

* **Símbolo de infinito (∞) – Tarifa Derivada:** Quando aparece o ícone de infinito (∞) ao lado da tarifa, significa que ela é uma tarifa derivada.

**O que isso quer dizer?**

O preço dessa tarifa não é definido manualmente;

Ele é calculado automaticamente a partir de outra tarifa base (tarifa master).

**Como funciona:**

Ao passar o mouse sobre o ícone, o sistema exibe:

Tarifa master → de onde o valor está sendo puxado (tarifa de referência).

Diferença em % → quanto está sendo aplicado de desconto ou acréscimo sobre a tarifa base (ex.: -10%).

Diferença em valor → ajuste fixo em moeda (ex.: +R$ 50 ou -R$ 30).

Também pode ser configurado como divisão (por exemplo, dividir o valor)

**Vantagens da tarifa derivada:**

Agilidade: você altera apenas a tarifa base, e todas as derivadas são atualizadas automaticamente.

Padronização: garante consistência entre os preços praticados em diferentes canais.

Flexibilidade: permite aplicar descontos fixos, percentuais ou regras específicas sem precisar alterar todas as tarifas manualmente.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_-_Calendario_imagec_a90e31fb.png)

**Aba Atualizar disponibilidade:**

Permite alterar o estoque de unidades/quartos/vagas disponíveis para reserva.

⚠️ **Importante:**

* Essa aba **só aparece** se o hotel **não possuir integração com Channel Manager (HUNIT) ou PMS (Gestor interno do hotel)**.
* Caso exista integração, a disponibilidade deve ser sempre controlada pelo **Channel Manager (HUNIT) ou PMS (Gestor interno do hotel)**.

**Estrutura da tela de Disponibilidade:**

**Períodos:**

Esta seção permite definir o intervalo de datas para o qual a atualização de disponibilidade será aplicada.

**Início:** Campo de calendário onde se seleciona a data inicial do período.

**Fim:** Campo de calendário para a data final do período.

**Seleção de dias da semana:** Caixas de seleção que permitem escolher os dias específicos em que a alteração de disponibilidade será aplicada (Domingo a Sábado).

**Ícone de "+" (Adicionar):** Geralmente usado para criar múltiplos períodos simultaneamente.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_-_Calendario_image12_f88889f5.png)

**Tipos de Quarto e Tarifas:**

Esta seção mostra todos os tipos de quartos disponíveis no hotel e permite selecionar quais serão afetados pela atualização.

**Botão “Marcar Todos”:** Seleciona todos os tipos de quartos de uma vez.

**Botão “Desmarcar”:** Remove a seleção de todos os quartos.

**Lista de quartos:** Cada linha representa um tipo de quarto disponível.

**Caixas de seleção:** Permitem escolher individualmente os quartos que terão disponibilidade atualizada.

Exemplo de uso: Se a atualização de disponibilidade se aplicar apenas ao Quarto Standard e ao Quarto Família, o usuário seleciona apenas essas opções.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_-_Calendario_image8_2afb06fc.png)

**Disponibilidade:**
Informe a quantidade de unidades habitacionais (UH) disponíveis em cada categoria de quarto do hotel. Este campo permite controlar a ocupação e garantir que reservas sejam realizadas apenas quando houver quartos disponíveis na categoria selecionada.

Se aplica a disponibilidade nas categorias marcadas na lista acima, vão receber a mesma informação.

Por fim, clicar no botão **“Atualizar”**

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_-_Calendario_image10_22c74d3a.png)

Caso queira validar a atualização, basta acessar a aba “Grade” e realizar uma busca pela data atualizada ou realizando uma busca publica no motor.

Para abrir consulta pública do motor, basta clicar no símbolo de link, no canto superior direito.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_-_Calendario_image17_18fdec8b.png)

**Aba atualizar preço:**

Aba destinada à alteração dos valores das tarifas.

Permite aumentar, reduzir ou ajustar preços em datas específicas de forma manual.

**Estrutura da tela de Atualização de preços:**

**Períodos:**

Esta seção permite definir o intervalo de datas para o qual a atualização de disponibilidade será aplicada.

**Início:** Campo de calendário onde se seleciona a data inicial do período.

**Fim:** Campo de calendário para a data final do período.

**Seleção de dias da semana:** Caixas de seleção que permitem escolher os dias específicos em que a alteração de disponibilidade será aplicada (Domingo a Sábado).

**Ícone de "+" (Adicionar):** Geralmente usado para criar múltiplos períodos simultaneamente.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_-_Calendario_image1a_4d9654cd.png)

**Tipo de Tarifa:**

Neste campo, o usuário deve selecionar o tipo de tarifa que deseja atualizar valores. Trata-se de um menu suspenso contendo todas as tarifas disponíveis no sistema.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_-_Calendario_image4_ae5def73.png)

**Valores por Tipo de Quarto:**

Esta seção permite definir o valor da diária com base no número de hóspedes por quarto. Cada linha representa um tipo de quarto, e cada coluna representa a quantidade de pessoas hospedadas.

* **Cabeçalho Horizontal (Colunas)**

Cada coluna está identificada pelo número de pessoas que ocuparão o quarto:

1 Pessoa

2 Pessoas

...

8 Pessoas

⚠️ O sistema só permitirá preencher até o limite máximo de ocupação de cada tipo de quarto.

* **Tipos de Quarto (Linhas):**

Cada linha representa um tipo específico de quarto. Ao lado do nome do quarto, é exibido o número máximo de adultos permitido.

* **Campos de valor:**

Cada célula permite inserir o valor da diária para aquela combinação de tipos de quarto e número de hóspedes.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_-_Calendario_imagea_5c2491c4.png)

**Legenda:**

**Função da Seta (Botão de Cópia de Valor)**

Este botão com ícone de seta (→), localizado ao lado de um campo de valor, permite copiar automaticamente o valor inserido nesse campo para as demais quantidades de pessoas da categoria.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_-_Calendario_imaged_46109959.png)

**Digite o valor (%) que deseja atribuir:** Não obrigatório, apenas se quiser enviar um valor diferente (a mais ou a menos) do que foi digitado nos campos te preço (em porcentagem).

O valor(preço) aplicado irá para venda com a porcentagem inserida, ou seja, aumenta ou diminui o valor que foi digitado.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_-_Calendario_image13_3480e4de.png)

Por fim, clicar no botão **“Atualizar”**

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_-_Calendario_image14_1662b3fd.png)

**Aba Atualizar restrições:**

Usada para definir regras de reserva, como:

* Estadia mínima (número de noites obrigatórias);
* Fechado para chegada (impede check-in);
* Fechado para saída (impede checkout).
* Stop de venda: bloqueia a tarifa para reservas, mesmo havendo disponibilidade.
* Essas restrições ajudam a implementar estratégias em períodos de alta demanda e controlar melhor a ocupação do hotel.

**Exemplo prático:** podem ser utilizadas para criar pacotes especiais, como "mínimo de 3 noites no feriado" ou "final de semana fechado para saída no sábado", incentivando reservas mais longas e otimizando a rentabilidade.

**Estrutura da tela de Atualização de restrições:**

**Períodos:**

Esta seção permite definir o intervalo de datas para o qual a atualização de disponibilidade será aplicada.

**Início:** Campo de calendário onde se seleciona a data inicial do período.

**Fim:** Campo de calendário para a data final do período.

**Seleção de dias da semana:** Caixas de seleção que permitem escolher os dias específicos em que a alteração de disponibilidade será aplicada (Domingo a Sábado).

**Ícone de "+" (Adicionar):** Geralmente usado para criar múltiplos períodos simultaneamente.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_-_Calendario_image11_4094faf1.png)

**Tipos de Quarto e Tarifas:**

Esta seção mostra todos os tipos de quartos e tarifas disponíveis no hotel e permite selecionar quais serão afetados pela atualização de restrição.

Possui a coluna de quartos e tarifas separadamente.

**Botão “Marcar Todos”:** Seleciona todos os tipos de quartos e tarifas de uma vez.

**Botão “Desmarcar”:** Remove a seleção de todos os quartos e tarifas.

**Lista de quartos:** Cada linha representa um tipo de quarto disponível.

**Lista de tarifas:** Cada linha representa um tipo de tarifa disponível.

**Caixas de seleção:** Permitem escolher individualmente os quartos, tarifas ou pacotes que terão restrição atualizada.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_-_Calendario_image18_48472c60.png)

**Restrições de tarifas:**

**Estadia mínima** - Define o número mínimo de noites que o hóspede precisa reservar.

**Venda** - Quando está **aberto**, o sistema aceita novas reservas normalmente.

Quando está **fechado**, as vendas ficam bloqueadas, impedindo que novas reservas sejam realizadas. Mesmo que haja disponibilidade (número de unidades ainda maior que 0, no topo da coluna), o sistema não permite efetuar reservas nessa data. É uma forma de “bloquear” vendas sem precisar zerar a disponibilidade.

**Chegada** - Quando está **aberto**, o sistema aceita check-in normalmente.

Quando está **fechado**, significa que, naquela data específica, o sistema não permite o check-in. O hóspede pode estar hospedado nesse dia, mas não pode iniciar a estadia nessa data. Indica que não é permitido iniciar a reserva (check-in) nessa data.

**Saída** - Quando está **aberto**, o sistema aceita checkout normalmente.

Quando está **fechado**, indica que não é possível fazer checkout naquela data. O hóspede pode estar hospedado ou até mesmo entrar nesse dia, mas não pode finalizar a estadia nele. Significa que não é possível encerrar a reserva (checkout) nessa data.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_-_Calendario_image5_df3abc32.png)

Por fim, clicar no botão **“Atualizar”**

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_-_Calendario_imagef_9ac18c70.png)

Metadados do Documento

|  |  |
| --- | --- |
| **Sistema:** | **HBook (Motor de Reservas)** |
| **Módulo:** | Calendário |
| **Funcionalidade:** | Calendário |
| **Data de referência:** | 28/10/2025 |
| **Tipo de documento:** | Guia de configuração |