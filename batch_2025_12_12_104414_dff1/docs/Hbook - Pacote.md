Documentação: Promoções - Pacotes

Visão geral

Este documento descreve o processo de configuração de pacotes no sistema Hbook (Motor de reservas)

**Objetivo da funcionalidade**

Na tela Pacotes, o usuário pode criar novas pacotes ou editar os já existentes. Essa funcionalidade permite gerenciar de forma prática as condições comerciais do hotel, definindo tipo de uso, datas de aplicabilidade entre outros.

O pacote funciona de forma semelhante a uma tarifa, porém com uma diferença importante: ele possui data de entrada e saída pré-determinadas, ou seja, o hóspede só pode reservar no exato período configurado.

Além disso, é possível adicionar uma imagem (banner) para destacar o pacote visualmente, tornando-o mais atrativo na tela pública de reservas.

Esses pacotes aparecem com maior destaque no site da propriedade, diferenciando-se das tarifas comuns justamente por possuírem período fixo e apresentação personalizada.

**Acesso a funcionalidade**

Acessar a ferramenta Hbook (Motor de reservas)

Caminho: Promoções - Pacotes

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_-_Pacote_image11_2811e626.png)

Para criar uma oferta basta ir em PROMOÇÕES → PACOTES – no canto inferior direito, possui um botão roxo com um +.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_-_Pacote_image9_79b11a51.png)

**Estrutura da tela:**

* **Abas de Visualização da tabela:**

**Mostrar Pacotes Ativos:** exibe somente os pacotes com a opção “Ativo” marcada.

**Mostrar Pacotes Inativos:** exibe os pacotes que estão desativados, mas que ainda existem no sistema. Caso queira reativar, basta marcar o flag de “ativo” novamente.

* **Tabela de Pacote:**

Cada linha representa um tipo de pacote e contém várias colunas:

**Código**: Identificação única do pacote no sistema.

**Nome**: Nome de identificação do pacote. Também tem a data de check-in e checkout do pacote.

**Estadia mínima**: Quantidade mínima de noites exigidas para reserva dentro desse pacote. **(Não se aplica para pacotes)**

**Estadia máxima**: Quantidade máxima de noites permitidas (valor “0” indica que não há limite). **(Não se aplica para pacotes)**

**Janela reservas(dias)**: Define o prazo em dias de antecedência para permitir reservas dentro do pacote. “0” significa que não há restrição. **(Não se aplica para pacotes)**

**Last minute(dias)**: Intervalo em dias para aceitar reservas de última hora (last minute). **(Não se aplica para pacotes)**

**Extras**: Indica o número de extras vinculados ao pacote.

**Tipo de pensão:** Informa o tipo de regime de alimentação incluso no pacote, como Café da Manhã, Somente Hospedagem ou Pensão Completa.

**Parcelamento**: Indica se o pagamento pode ser parcelado (Sim ou Não).

**Canal vinculado:** Não é mais utilizado, indica se é uma tarifa do HBOOK(motor) ou HCORP(operadora), mas o HCORP não é mais configurado no HBOOK, desta forma entrou em desuso.

* **Ações do pacote:**
  Ícones na última coluna permitem ações rápidas:

**Editar:** modificar informações do pacote.
**Excluir:** remover o pacote.

**Duplicar**: criar uma cópia do pacote existente.

**Símbolo de relógio:** versões anteriores já praticadas de política de cancelamento e pré-pagamento.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_-_Pacote_imagea_ef435cb9.png)

O primeiro passo é preencher a tela de **Dados Gerais** com as informações essenciais:

**Nome:** Identificação da tarifa no sistema e na tela pública.

**Flag ativo:** Se marcar ficara disponível para incluir para venda e de desmarcado não será uma opção de venda.

**Flag Mostrar esta tarifa somente com código promocional:** Esse pacote somente será apresentado na pesquisa pública se o cliente adicionar um código promocional durante a compra.

**Flag Exibir tarifa no calendário inteligente:** Para que a tarifa seja exibida no calendário inteligente (tela pública de consulta), é necessário que o campo esteja marcado. Caso nenhuma tarifa tenha essa opção ativada, o calendário não apresentará disponibilidade para seleção de datas, impossibilitando o hóspede de prosseguir. Portanto, é obrigatório que pelo menos uma tarifa esteja configurada com esse flag habilitado.

Outro ponto importante: quando a opção **“Mostrar esta tarifa somente com código promocional”** estiver marcada, a configuração **“Exibir tarifa no calendário inteligente”** não ficará disponível, já que essa tarifa estará restrita apenas à utilização mediante código promocional.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_-_Pacote_imageb_9270a788.png)

**Tipo de pensão**

Define qual refeição está incluída no pacote. O usuário pode selecionar entre diferentes modalidades de pensão, de acordo com o que será oferecido ao hóspede. As opções disponíveis no sistema são:

**Somente Hospedagem:** não inclui refeições.
**Café da Manhã:** inclui apenas o café da manhã.
**Meia Pensão:** inclui café da manhã e mais uma refeição (almoço ou jantar).
**Pensão Completa:** inclui café da manhã, almoço e jantar.
**All Inclusive:** inclui todas as refeições, lanches e bebidas ao longo da estadia.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_-_Pacote_imagee_80d2fe46.png)

**Configurações de disponibilidade:**

No campo **Configurações de disponibilidade** — que inclui **Estadia mínima padrão, Estadia máxima padrão, Dias Tarifa Antecipada e Dias Tarifa Last Minute** — **não** **realizar preenchimento**.

Esses parâmetros não se aplicam a pacotes, pois o **pacote é uma venda fechada**, com **datas de entrada e saída pré-determinadas**.
**Ao preencher esses campos, o sistema pode interpretar restrições adicionais e prejudicar a visualização ou disponibilidade do pacote** na tela pública.

Como **o hóspede é obrigado a se hospedar exatamente nas datas definidas** no pacote, não há necessidade de configurar regras de estadia mínima, máxima ou de antecedência de reserva.

**Dados para pacote**

**Data de Check-in**: Define o dia de **entrada obrigatória** do hóspede no pacote, essa data marca o início da hospedagem.

**Data de Checkout**: Define o dia de **saída obrigatória** do hóspede. O pacote é sempre fechado, ou seja, o hóspede deve entrar e sair exatamente nessas datas.

**Visível a partir de**: Indica a partir de qual data o pacote ficará **disponível para visualização e venda** na tela pública (motor de reservas). Antes dessa data, o pacote não será exibido.

**Até**: Define até quando o pacote ficará **visível para venda**. Após essa data, ele deixa de aparecer para o público, mesmo que as datas de check-in e checkout ainda estejam dentro do período configurado.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_-_Pacote_image10_a318e276.png)

**Foto para pacote**

Permite adicionar uma imagem ilustrativa do pacote

* Botão **“Adicionar Foto”** abre a seleção de arquivos.

**Importante:** Ao criar um **pacote**, é importante primeiro preencher **todas as informações** **e salvar** o registro. Somente após salvar o pacote é que será possível adicionar uma **foto**. Para isso, localize o pacote criado, clique em **Editar** e inclua a imagem desejada.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_-_Pacote_image_819a5277.png)

**Texto Descritivo**

Detalhes sobre características e informações relevantes sobre o pacote.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_-_Pacote_image8_ac0b2695.png)

**Observação importante:**
Se estiver **criando um pacote**, o sistema **não permite avançar para as demais abas** de configuração (Garantias e cancelamento, configurações de pagamento, extras inclusos) antes de salvar os dados gerais. É necessário salvar primeiro para que a tarifa seja registrada no sistema e as outras opções sejam liberadas.

Botão roxo no canto inferior direto, para salvar.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_-_Pacote_image7_833156a4.png)

A tela **Garantias e Cancelamento** permite configurar as condições de garantia de reserva, políticas de cancelamento e faixas de penalidades aplicáveis em caso de desistência do hóspede. A seguir, detalhamos cada seção, campo e botão disponível:

**Garantias**

Nesta seção o hotel define qual será a **forma de garantia da reserva**, ou seja, qual valor ou percentual será cobrado antecipadamente para confirmar a hospedagem.

* **Selecione o tipo de garantia:** menu suspenso que permite escolher entre:
* *Nenhuma* → não há cobrança antecipada.
* *Primeira Noite* → é cobrado o valor equivalente à primeira diária.
* *Percentual da Reserva* → o hotel define um percentual sobre o valor total da reserva.
* **Percentual:** este campo só aparece quando a opção *Percentual da Reserva* é selecionada. Nele é informado o valor percentual desejado (digitar somente o número sem o “%”).

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_-_Pacote_imaged_185f3f74.png)

* **Descrição:** campo de texto editável onde o hotel pode informar ao hóspede como funciona a garantia.
* **Botão “Customizar Descrição”:** permite editar livremente o texto exibido ao cliente.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_-_Pacote_image2_9339eee8.png)

### **Políticas de Cancelamento**

Aqui o hotel estabelece as regras que serão aplicadas em caso de cancelamento.

* **Esta é uma tarifa não-reembolsável:** Se marcada, significa que em caso de cancelamento não haverá reembolso ao hóspede. Outro ponto, o sistema **não considera mais o campo de garantia**. Isso porque, em uma tarifa não-reembolsável, o hóspede não tem direito a devolução em caso de cancelamento. Nesse cenário, o sistema automaticamente considera pagamento de **100% do valor da reserva**.

Caso o cliente tenha Hpay essa cobrança é automática, mas caso não tenha, será necessário a gestão manual da cobrança.

Caso marcado como não reembolsável **não considera mais o campo de penalidades**.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_-_Pacote_image3_3b9f6811.png)

* **Descrição:** campo de texto para detalhar as condições de cancelamento. Assim como em garantias, há possibilidade de personalizar a descrição com o botão **“Customizar Descrição”**.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_-_Pacote_image4_e895b8ee.png)

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
* *Valor Fixo* → cobra-se um valor definido em moeda(Reais).
* *Percentual da Reserva* → cobra-se uma porcentagem sobre o valor total (digitar somente o número sem o “%”).
* *Valor Total da Reserva* → 100% do valor reservado é cobrado.
* *Primeira Noite* → apenas a primeira diária é cobrada.

### **Exemplo prático de configuração em tarifa flexível:**

* Cancelamentos até **15 dias antes do check-in** → Nenhuma Penalidade.
* Cancelamentos entre **14 e 7 dias antes do check-in** → 50% da reserva.
* Cancelamentos entre **6 e 0 dias antes do check-in** → 100% da reserva.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_-_Pacote_imagec_5a75d329.png)

A tela **Configurações de Pagamento** permite ao hotel definir quais formas de pagamento serão aceitas para determinada tarifa e, caso desejado, configurar regras de parcelamento.

**Formas de Pagamento Liberadas:**

**Todas as formas de pagamento são aceitas para esta tarifa:** ao selecionar essa opção, o sistema libera automaticamente todas as formas de pagamento habilitadas no hotel.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_-_Pacote_image5_8d69b356.png)

**Apenas as formas de pagamento selecionadas abaixo são aceitas para esta tarifa:** permite escolher individualmente quais métodos estarão disponíveis.

Essas opções aparecem conforme previamente habilitadas na tela **Meios de Pagamento.** Dentro de cada pacote, você pode escolher se aceita todas as formas ou apenas algumas delas.

Basta marcar ou desmarcar cada opção conforme a política desejada.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_-_Pacote_image6_93b3c027.png)

**Dados de Parcelamento:**

Se o hotel aceitar cartão de crédito, é possível configurar o parcelamento da reserva.

**Permite Parcelamento:** habilita o recurso de parcelamento.

**Ocultar % de juros para o hóspede:** ao marcar, o sistema aplica os juros mas não exibe essa informação diretamente ao cliente.

**Aplicar percentual de juros de 1 parcela também para garantia:** garante que, mesmo em caso de cobrança de apenas 1 parcela (como em pagamento de garantia), o percentual de juros configurado será aplicado.

**Tipo de parcelamento:** define em qual meio o parcelamento será aplicado, cartão de crédito ou no hotel.

**Valor mínimo da parcela:** campo numérico para definir um valor mínimo que cada parcela deve ter.

**Número máximo de parcelas:** define até quantas vezes a reserva poderá ser dividida.

**Configuração por parcela:**
**Parcelas / Taxa de Juros:** o hotel pode configurar parcela a parcela, definindo a quantidade e o respectivo percentual de juros.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_-_Pacote_imagef_f8a25bc1.png)

A aba **Extras Inclusos** dentro da configuração de tarifas tem como objetivo permitir que o hotel associe à tarifa itens adicionais que já estão embutidos no valor da diária.

**Lista de Extras Disponíveis:**
Essa área apresenta os itens adicionais que o hotel já cadastrou previamente na tela de **Extras.**

Cada extra aparece em formato de caixa de seleção (*checkbox*), permitindo que o hoteleiro escolha quais serão incorporados à tarifa.

**Como Funciona na Prática:**
Quando o hotel marca um item nesta tela, o sistema considera que esse extra já está incluso no valor da tarifa.
Isso significa que o hóspede não verá um custo adicional por ele, mas sim o benefício como parte do pacote.
Caso nenhum extra seja selecionado, a tarifa é apresentada apenas com os serviços básicos já configurados.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_-_Pacote_image12_6ba5bf3b.png)

**Variáveis disponíveis:**

Bandeiras: Corresponde a configuração de idiomas por bandeira.

Cada bandeira representa um idioma (português, inglês e espanhol).

O cliente (hotel) precisa escrever o conteúdo manualmente no idioma correspondente à bandeira escolhida.

O sistema não faz tradução automática — portanto, se o hotel deseja que o texto apareça em inglês ou espanhol, ele mesmo deve inserir a versão traduzida.

Esse conteúdo será exibido no motor de reservas público, permitindo que o hóspede selecione o idioma desejado e veja as informações já traduzidas.

Metadados do Documento

|  |  |
| --- | --- |
| **Sistema:** | **HBook (Motor de Reservas)** |
| **Módulo:** | Promoções |
| **Funcionalidade:** | Pacotes |
| **Data de referência:** | 27/10/2025 |
| **Tipo de documento:** | Guia de configuração |