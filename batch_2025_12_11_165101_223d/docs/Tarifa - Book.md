Documentação: Tarifa

Visão Geral

Este documento descreve o processo de configuração de tarifas no sistema Hbook (Motor de reservas)

Objetivo da funcionalidade

Na tela Tipos de Tarifas, o usuário pode criar tarifários para venda ou editar tarifas já existentes. Essa funcionalidade permite gerenciar de forma prática a oferta de unidades do hotel, definindo nome, políticas de cancelamento e outras características relevantes para cada tipo de tarifa.

Acesso a funcionalidade

Para criar uma tarifa basta ir em PROPRIEDADE → TARIFAS – no canto inferior direito, possui um botão roxo com um +.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Tarifa_-_Book_image13_a9b0d544.png)

**Estrutura da tela:**

* **Abas de Visualização da tabela:**
  **Mostrar Tarifas Ativos:** exibe somente as tarifas com a opção “Ativo” marcada.

**Mostrar Tarifas Inativos:** exibe as tarifas que estão desativados, mas que ainda existem no sistema. Caso queira reativar, basta marcar o flag de “ativo” novamente.

* **Tabela de Tipos de Tarifa:**
  Cada linha representa uma tarifa e contém várias colunas:

**Código:** identificação única da tarifa no sistema.

**Nome:** nome de identificação da tarifa.

**Estadia mínima:** número mínimo de noites que o hóspede precisa reservar.

**Estadia máxima:** número máximo de noites que o hóspede pode reservar.

**Janela reserva (dias):** dias tarifa antecipada.
**Last minute (dias):** tarifa de última hora.

**Extras:** quantidade de extras incluídos na tarifa.

**Tipo de Pensão:** forma de alimentação da tarifa.

**Parcelamento:** se aceita parcelamento ou não.

**Canal vinculado:** não é mais utilizado, indica se é uma tarifa do HBOOK(motor) ou HCORP(operadora), mas o HCORP não é mais configurado no HBOOK, desta forma entrou em desuso.

* **Ações da tarifa:**
  Ícones na última coluna permitem ações rápidas:

**Editar:** modificar informações da tarifa.
**Excluir:** remover a tarifa.

**Duplicar**: criar uma cópia da tarifa existente.

**Símbolo de relógio:** versões anteriores já praticadas de política de cancelamento e pré-pagamento.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Tarifa_-_Book_image7_7dc48eea.png)

No canto inferior direto, possui um botão roxo com “+”, para criar

Tarifa.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Tarifa_-_Book_imaged_046757e1.png)

Configurando a tarifa:

Importante!!!

Sempre que for editar uma tarifa já existente, é necessário salvar as informações de cada aba antes de mudar para outra.

Por exemplo: se você está editando o texto descritivo na aba Dados Gerais, antes de acessar a aba Garantias e Cancelamento é preciso salvar aquela tela, caso contrário as alterações feitas serão perdidas.

Essa regra vale para todas as abas do cadastro da tarifa.

O primeiro passo é preencher a tela de **Dados Gerais** com as informações essenciais:

**Nome:** Identificação da tarifa no sistema e na tela pública.

**Flag ativo:** Se marcar ficara disponível para incluir para venda e de desmarcado não será uma opção de venda.

**Flag Mostrar esta tarifa somente com código promocional:** Essa tarifa somente será apresentada na pesquisa pública se o cliente adicionar um código promocional durante a compra.

**Flag Exibir tarifa no calendário inteligente:** Para que a tarifa seja exibida no calendário inteligente (tela pública de consulta), é necessário que o campo esteja marcado. Caso nenhuma tarifa tenha essa opção ativada, o calendário não apresentará disponibilidade para seleção de datas, impossibilitando o hóspede de prosseguir. Portanto, é obrigatório que pelo menos uma tarifa esteja configurada com esse flag habilitado.

Outro ponto importante: quando a opção **“Mostrar esta tarifa somente com código promocional”** estiver marcada, a configuração **“Exibir tarifa no calendário inteligente”** não ficará disponível, já que essa tarifa estará restrita apenas à utilização mediante código promocional.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Tarifa_-_Book_image10_1beb33da.png)

**Tipo de pensão:** Define qual refeição está incluída na tarifa. O usuário pode selecionar entre diferentes modalidades de pensão, de acordo com o que será oferecido ao hóspede. As opções disponíveis no sistema são:

**Somente Hospedagem:** não inclui refeições.
**Café da Manhã:** inclui apenas o café da manhã.
**Meia Pensão:** inclui café da manhã e mais uma refeição (almoço ou jantar).
**Pensão Completa:** inclui café da manhã, almoço e jantar.
**All Inclusive:** inclui todas as refeições, lanches e bebidas ao longo da estadia.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Tarifa_-_Book_image16_e715325c.png)

**Configurações de disponibilidade:**

**Estadia mínima padrão:** Só é possível reservar essa tarifa se a pesquisa do hóspede contemplar o número mínimo de noites configurado.

**Estadia máxima padrão:** O máximo de dias que o hóspede pode reservar essa tarifa.

**Dias Tarifa Antecipada:** Corresponde ao número mínimo de dias que a reserva precisa ser feita antes da data de check-in para que a tarifa seja aplicada. Exemplo: se definido como 15 dias, somente reservas realizadas com pelo menos 15 dias de antecedência terão acesso a essa tarifa.

**Dias Tarifa Last Minute:** Refere-se ao limite máximo de dias para que a tarifa seja disponibilizada próximo à data de check-in. Exemplo: se definido como 2 dias, significa que essa tarifa só estará disponível para reservas feitas até 2 dias antes da chegada.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Tarifa_-_Book_image3_057daeee.png)

**Texto Descritivo:** Detalhes sobre características e informações relevantes sobre a tarifa.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Tarifa_-_Book_imagea_47e23df6.png)

Se estiver **criando uma tarifa**, o sistema **não permite avançar para as demais abas** de configuração (Garantias e cancelamento, configurações de pagamento, extras inclusos) antes de salvar os dados gerais. É necessário salvar primeiro para que a tarifa seja registrada no sistema e as outras opções sejam liberadas.

Garantias e cancelamento:

A tela **Garantias e Cancelamento** permite configurar as condições de garantia de reserva, políticas de cancelamento e faixas de penalidades aplicáveis em caso de desistência do hóspede. A seguir, detalhamos cada seção, campo e botão disponível:

**Garantias**

Nesta seção o hotel define qual será a **forma de garantia da reserva**, ou seja, qual valor ou percentual será cobrado antecipadamente para confirmar a hospedagem.

* **Selecione o tipo de garantia:** menu suspenso que permite escolher entre:
* *Nenhuma* → não há cobrança antecipada.
* *Primeira Noite* → é cobrado o valor equivalente à primeira diária.
* *Percentual da Reserva* → o hotel define um percentual sobre o valor total da reserva.
* **Percentual:** este campo só aparece quando a opção *Percentual da Reserva* é selecionada. Nele é informado o valor percentual desejado (digitar somente o número sem o “%”).

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Tarifa_-_Book_imageb_39a598c4.png)

* **Descrição:** campo de texto editável onde o hotel pode informar ao hóspede como funciona a garantia.
* **Botão “Customizar Descrição”:** permite editar livremente o texto exibido ao cliente.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Tarifa_-_Book_imagee_01126470.png)

### **Políticas de Cancelamento**

Aqui você estabelece as regras que serão aplicadas em caso de cancelamento.

* **Esta é uma tarifa não-reembolsável:** Se marcada, significa que em caso de cancelamento não haverá reembolso ao hóspede. Outro ponto, o sistema **não considera mais o campo de garantia**. Isso porque, em uma tarifa não-reembolsável, o hóspede não tem direito a devolução em caso de cancelamento. Nesse cenário, o sistema automaticamente considera pagamento de **100% do valor da reserva**.

Caso você tenha Hpay essa cobrança é automática, mas caso não tenha, será necessário a gestão manual da cobrança.

Caso marcado como não reembolsável **não considera mais o campo de penalidades**.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Tarifa_-_Book_image12_39cfee0c.png)

* **Descrição:** campo de texto para detalhar as condições de cancelamento. Assim como em garantias, há possibilidade de personalizar a descrição com o botão **“Customizar Descrição”**.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Tarifa_-_Book_image14_5b762093.png)

* **Se não for marcada como não-reembolsável:** a tarifa será considerada **flexível (reembolsável)**. Nesse caso:

O hotel pode definir faixas de penalidades progressivas para cancelamentos de acordo com a antecedência.

A cobrança também é realizada conforme o que foi configurado no campo de **garantia**.

### **Faixas de Penalidades de Cancelamento**

Essa parte possibilita configurar **regras progressivas de penalidade**, de acordo com a antecedência do cancelamento. Nas **tarifas flexíveis (reembolsáveis)**, o hotel pode configurar faixas de penalidades para diferentes prazos de cancelamento, permitindo ao hóspede maior flexibilidade e ao mesmo tempo protegendo o hotel de cancelamentos de última hora.

### **Como funciona:**

* **Cancelando em até X dias antes da data de check-in:**
  O hotel pode definir que não haverá cobrança (*Nenhuma Penalidade*) ou aplicar uma penalidade reduzida. Isso costuma servir como incentivo para que o hóspede cancele com antecedência.
* **Cancelando entre X e Y dias antes da data de check-in:**
  Nesse intervalo, a política já pode prever cobrança parcial, como *Percentual da Reserva* ou *Primeira Noite*. Dessa forma, o hotel cobre possíveis perdas pela proximidade do check-in.
* **Cancelando a 0 dias ou em caso de não comparecimento (no-show):**
  Normalmente a penalidade aplicada é maior, podendo ser *Valor Total da Reserva*, já que o hotel provavelmente não terá tempo hábil para revender a acomodação.

### **Opções de Penalidade disponíveis:**

* *Nenhuma Penalidade* → o hóspede recebe reembolso total.
* *Valor Fixo* → cobra-se um valor definido em moeda (Reais).
* *Percentual da Reserva* → cobra-se uma porcentagem sobre o valor total (digitar somente o número sem o “%”).
* *Valor Total da Reserva* → 100% do valor reservado é cobrado.
* *Primeira Noite* → apenas a primeira diária é cobrada.

### **Exemplo prático de configuração em tarifa flexível:**

* Cancelamentos até **15 dias antes do check-in** → Nenhuma Penalidade.
* Cancelamentos entre **14 e 7 dias antes do check-in** → 50% da reserva.
* Cancelamentos entre **6 e 0 dias antes do check-in** → 100% da reserva.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Tarifa_-_Book_image5_8e0bb27b.png)

**Configurações de pagamento:**

A tela **Configurações de Pagamento** permite ao hotel definir quais formas de pagamento serão aceitas para determinada tarifa e, caso desejado, configurar regras de parcelamento.

**Formas de Pagamento Liberadas:**

**Todas as formas de pagamento são aceitas para esta tarifa:** ao selecionar essa opção, o sistema libera automaticamente todas as formas de pagamento habilitadas no hotel.

**Apenas as formas de pagamento selecionadas abaixo são aceitas para esta tarifa:** permite escolher individualmente quais métodos estarão disponíveis.

Essas opções aparecem conforme previamente habilitadas na tela **Meios de Pagamento**. Dentro de cada tarifa, o hoteleiro pode escolher se aceita todas as formas ou apenas algumas delas.

Basta marcar ou desmarcar cada opção conforme a política desejada.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Tarifa_-_Book_image6_b1ed9669.png)

**Dados de Parcelamento:**

Se o hotel aceitar cartão de crédito, é possível configurar o parcelamento da reserva.

**Permite Parcelamento:** habilita o recurso de parcelamento.

**Ocultar % de juros para o hóspede:** ao marcar, o sistema aplica os juros, mas não exibe essa informação diretamente ao cliente.

**Aplicar percentual de juros de 1 parcela também para garantia:** garante que, mesmo em caso de cobrança de apenas 1 parcela (como em pagamento de garantia), o percentual de juros configurado será aplicado.

**Tipo de parcelamento:** define em qual meio o parcelamento será aplicado, cartão de crédito ou no hotel.

**Valor mínimo da parcela:** campo numérico para definir um valor mínimo que cada parcela deve ter.

**Número máximo de parcelas:** define até quantas vezes a reserva poderá ser dividida.

**Configuração por parcela:**
**Parcelas / Taxa de Juros:** o hotel pode configurar parcela a parcela, definindo a quantidade e o respectivo percentual de juros.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Tarifa_-_Book_image8_e91fc368.png)

Extras inclusos:

A aba Extras Inclusos dentro da configuração de tarifas tem como objetivo permitir que o hotel associe à tarifa itens adicionais que já estão embutidos no valor da diária.

Lista de Extras Disponíveis:

Essa área apresenta os itens adicionais que o hotel já cadastrou previamente na tela de Extras.

Cada extra aparece em formato de caixa de seleção (checkbox), permitindo que o hoteleiro escolha quais serão incorporados à tarifa.

Como Funciona na Prática:

Quando o hotel marca um item nesta tela, o sistema considera que esse extra já está incluso no valor da tarifa.

Isso significa que o hóspede não verá um custo adicional por ele, mas sim o benefício como parte do pacote.

Caso nenhum extra seja selecionado, a tarifa é apresentada apenas com os serviços básicos já configurados.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Tarifa_-_Book_image17_24f423b7.png)

Por fim, clique no botão roxo, no canto inferior direto, para salvar.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Tarifa_-_Book_image2_2ad446fe.png)

Após criar uma tarifa é necessário fazer a combinação quarto/tarifa, se não for realizado o vínculo ao quarto, não reflete para venda.

Para acessar a tela basta acessar o Hbook, ir em PROPRIEDADE → COMBINAÇÕES QUARTO/TARIFA

A tela Combinações Quarto/Tarifa é utilizada para realizar a vinculação das tarifas aos quartos. Nela é possível associar mais de uma tarifa a um mesmo quarto, permitindo diferentes opções de venda para o hóspede.

Sem essa vinculação, a tarifa não será refletida para venda, mesmo que esteja criada.

Estrutura da tela

**Botão Configurar em Massa**

Permite aplicar vínculos de tarifas em vários quartos de uma só vez, agilizando a configuração. O que for configurado nesta tela será aplicado exatamente igual para todos os quartos existentes.

**Sem derivação tarifária:** As tarifas serão associadas sem nenhum cálculo adicional. será considerado uma tarifa principal (independente).

**Com derivação tarifária:** Ao preencher esse campo, são exibidas as opções de configuração de **Percentual (%), Em valor e Em divisão**, que permitem ajustar a tarifa secundária em relação à tarifa master.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Tarifa_-_Book_image_8bb3291e.png)

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Tarifa_-_Book_image9_3b955afe.png)

**Seção por Quarto**
Cada quarto listado na tela mostra as tarifas que já estão associadas a ele e possibilita incluir novas combinações. Também é possível ver qual é as combinações e derivações de tarifas já realizada.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Tarifa_-_Book_imagec_aaf4080a.png)

**Opção "Vincular Tarifa"**

Permiti adicionar novas tarifas e/ou combinações. Disponível para quando o quarto ainda não possui a tarifa desejada vinculada.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Tarifa_-_Book_imagef_0c07cde7.png)

**Lista suspensa de seleção de tarifa**
Permite escolher uma nova tarifa para vincular ao quarto. Caso não preencha o campo **tarifa master,** será considerado uma tarifa principal (independente).

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Tarifa_-_Book_image11_e4ded9de.png)

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Tarifa_-_Book_image18_81965595.png)

* **Campo Tarifa Master**
  Define a tarifa principal sobre a qual a preenchida no campo a cima vai se basear. Caso esse campo não seja preenchido, a tarifa escolhida no primeiro campo será considerada uma **tarifa independente**. Ao preencher esse campo, são exibidas as opções de configuração de **Percentual (%), Em valor e Em divisão**, que permitem ajustar a tarifa secundária em relação à tarifa master.

**Campos de Ajuste**

**Percentual (%)**: Define acréscimo ou desconto em percentual sobre o valor da tarifa master.

**Em valor**: Ajusta a tarifa em um valor fixo, seja adicionando ou subtraindo.

**Em divisão**: Configura o rateio ou divisão do valor da tarifa em condições específicas.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Tarifa_-_Book_image4_6f5fbe89.png)

### **Informativo importante**

* Para **acréscimo**, basta inserir o valor desejado (não é necessário colocar o sinal **+**).
* Para **desconto**, é necessário inserir o valor acompanhado do sinal de menos (**-)**.

* **Ícones de Ação (✔ - ✖- 🗑️)**

**✔ (Confirmar)**: Salva a vinculação da tarifa escolhida ao quarto.

**✖ (Cancelar)**: Descarta a inclusão da tarifa antes de salvar.

🗑️**(Lixeira):** Deletar a configuração de tarifa vinculada e combinações.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Tarifa_-_Book_image15_9eeb3cba.png)