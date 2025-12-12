Documentação: Promoções - Ofertas

Visão geral

Este documento descreve o processo de configuração de ofertas no sistema Hbook (Motor de reservas)

**Objetivo da funcionalidade**

Na tela **Ofertas**, o usuário pode criar promoções ou editar ofertas já existentes. Essa funcionalidade permite gerenciar de forma prática as condições comerciais do hotel, definindo o tipo de quarto, tarifa e condições de aplicabilidade relevantes para cada oferta.

**Acesso a funcionalidade**

Para criar uma oferta basta ir em PROMOÇÕES → OFERTAS – no canto inferior direito, possui um botão roxo com um +.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hbook_-_Oferta_image14_1efec826.png)

**Estrutura da tela:**

No topo, há um campo **“Como será aplicada as ofertas na reserva”**, que permite definir como a oferta será aplicada.

* **Abas de Visualização da tabela:**

**Mostrar Ofertas Ativas:** exibe somente as ofertas com a opção “Ativo” marcada.

**Mostrar Ofertas Inativas:** exibe ofertas que estão desativados, mas que ainda existem no sistema. Caso queira reativar, basta marcar o flag de “ativo” novamente.

* **Tabela de Ofertas:**

Cada linha representa um tipo de oferta e contém várias colunas:

**Nome**: Identificação da oferta configurada.

**Tipos de quarto**: Lista os tipos de quarto aos quais a oferta se aplica.

**Tipos de tarifa**: Mostra as tarifas associadas à oferta.

**Condições de aplicabilidade**: Apresenta os critérios de validade da oferta, como período específico ou estadia mínima, entre outas aplicações.

**Desconto**: Mostra o percentual ou valor configurado para desconto.

* **Ações da Categoria:**

Ícones na última coluna permitem ações rápidas:

**Editar (lápis)** → permite editar a oferta existente.

**Excluir (lixeira)** → exclui a oferta cadastrada.

**Copiar (folha duplicada)** → cria uma cópia da oferta para agilizar a criação de novas promoções semelhantes.

**Copiar link da oferta (documento sobreposto) →** Copia o link do motor que direciona para a aplicabilidade da oferta em tela pública.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hbook_-_Oferta_image6_d9b83680.png)

**Configurações:**

**Como será aplicada as ofertas na reserva:**

O campo **"Como será aplicada as ofertas na reserva?"** define a forma de cálculo das ofertas configuradas. Você pode escolher entre duas opções:

**Considerar ofertas por dia**

A aplicação da oferta ocorre em cada diária da reserva. Ou seja, o desconto ou condição promocional é avaliado dia a dia. O sistema apresentará ao cliente o melhor desconto dia a dia. Por exemplo, se a propriedade trabalha com desconto de 20% durante a semana e 10% durante os finais de semana; e o cliente realiza um reserva com check-in na Quinta e checkout no Domingo; Quinta e Sexta ele terá 20% de desconto no valor da diária e no Sábado 10%. O valor total do desconto será o mesmo que se ele fizesse 2 reservas separadas, uma para os dias da semana e outra para o final de semana.

**Considerar ofertas por período de estadia**

A aplicação da oferta leva em conta todo o período da reserva. Nesse caso, o sistema avalia o intervalo completo (check-in até checkout) para aplicar a condição promocional. Nesta configuração o cliente só terá o maior desconto disponível. Seguindo o exemplo anterior do cliente com reserva de Quinta a Domingo, ele somente ganharia o desconto de 20% na Quinta e na Sexta. Para ter acesso ao desconto do final de semana de 10% ele teria que fazer uma nova reserva exclusiva para o Sábado.

Lembrando que somente é possível configurar uma condição que será válida para todas as ofertas.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hbook_-_Oferta_image_99a1c669.png)

**Configurando a oferta:**

O primeiro passo é preencher a tela de **Dados Gerais** com as informações essenciais:

**Nome**: Nome da oferta para identificação.

**Descrição**: Descrição do que se trata a oferta, não é apresentado em tela publica, é apenas interno para o hotel.

**Flag ativo**: Se marcar ficara disponível para incluir para venda e se desmarcado não será uma opção de venda.

**Flag Exibir no website**: Quando o flag está marcado, a oferta ficará visível no site da propriedade. Ao habilitar essa opção, é aberta uma aba adicional para que o usuário configure **foto da oferta, título, texto do botão e descrição** que serão exibidos ao visitante. **Importante:** esse recurso só funciona para clientes que possuem o nosso site contratado (**Hweb**) e apenas se o site tiver habilitada a aba de **Ofertas/Promoções**.

**Tipos de quartos:**

**Lista de quartos:** Cada linha representa um tipo de quarto disponível. A oferta será aplicada aos tipos de quartos selecionados aqui.

**Caixas de seleção:** Permitem escolher individualmente os quartos.

**Botão “Marcar Todos”**: Seleciona todos os tipos de quartos.

**Botão “Desmarcar”:** Remove a seleção de todos os quartos.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hbook_-_Oferta_image13_618cfb22.png)

**Tipos de tarifas:**

**Lista de tarifas:** Cada linha representa um tipo de tarifa disponível. A oferta será aplicada aos tipos de tarifas selecionados aqui.

**Caixas de seleção:** Permitem escolher individualmente as tarifas.

**Botão “Marcar Todos”**: Seleciona todos os tipos de tarifas.

**Botão “Desmarcar”:** Remove a seleção de todos as tarifas.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hbook_-_Oferta_image7_ce194443.png)

**Condições de aplicabilidade:**

Botão “**NOVO FILTRO**” dá acesso a tela Adicionando Filtros permite configurar condições específicas para determinar quando e como uma oferta será aplicada. É possível adicionar mais de um filtro. A seguir, a descrição de cada filtro:

**Estadia mínima**

Define a quantidade de noites mínimas necessárias para que a oferta seja aplicada.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hbook_-_Oferta_imagec_d9501efd.png)

**Antecedência mínima**

Define o número mínimo de dias entre a data da reserva e a data do check-in para a aplicação da oferta.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hbook_-_Oferta_image10_29bc9ebd.png)

**Antecedência máxima**

Define o número máximo de dias entre a data da reserva e a data do check-in para que a oferta seja válida.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hbook_-_Oferta_image3_cab75e83.png)

**Período da Oferta**

Determina em qual período de estadia a oferta será aplicada (datas de check-in e checkout válidas).

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hbook_-_Oferta_image4_6c42ac75.png)

**Período da Compra**

Define o intervalo de datas em que a reserva precisa ser realizada para que a oferta seja considerada, quando é possível realizar compra.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hbook_-_Oferta_image8_41ad6f7f.png)

**Reserva abandonada**

Permite aplicar a oferta somente em reservas abandonadas, ou seja, quando o hóspede inicia e não conclui a reserva, hóspede recebe um e-mail com o desconto incentivando a voltar.

Esse filtro é cumulativo com outras condições, oferta acumulativa.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hbook_-_Oferta_imagea_4f575a52.png)

**Dispositivo mobile**

Configura a oferta para ser aplicada apenas quando a pesquisa for feita em um dispositivo móvel.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hbook_-_Oferta_imageb_b44d1cfe.png)

**Mínimo de Quarto Disponível no Inventário**

Determina a quantidade mínima de quartos que deve haver no inventário para que a oferta seja disponibilizada.

Quando a disponibilidade atingir o que foi determinado a oferta será apresentada.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hbook_-_Oferta_imagee_5a3bdfa7.png)

**Valor Mínimo do Quarto**

Define o valor mínimo da diária dos quartos para que a oferta seja aplicada.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hbook_-_Oferta_imagef_4dd05b31.png)

**É um visitante registrado**

Configura a oferta para ser aplicada somente a visitantes que estejam previamente cadastrados no sistema (Cliente fidelidade).

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hbook_-_Oferta_image11_27dde68a.png)

**Crianças**

Permite definir a quantidade mínima de crianças na Pesquisa e a idade máxima das crianças consideradas para a oferta.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hbook_-_Oferta_image5_aca88407.png)

**Forma de desconto:**

**Forma de cálculo:**

Determina de que maneira o desconto será aplicado. Existem duas opções:

Percentual → o desconto será calculado em porcentagem (%) sobre o valor da tarifa.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hbook_-_Oferta_image12_7e6f3f19.png)

**Valor absoluto →** o desconto será um valor fixo em moeda.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hbook_-_Oferta_image2_37635ef6.png)

**➝ Comportamento dinâmico:**

Se escolher **Percentual**, o sistema habilita o campo **Percentual de desconto**.

Percentual de desconto (visível apenas quando Forma de cálculo = Percentual)

Campo numérico para informar o percentual (%) que será descontado. basta inserir o valor desejado (não é necessário colocar o sinal %)

Se escolher **Valor absoluto**, o sistema habilita o campo **Valor do desconto**.

Valor do desconto (visível apenas quando Forma de cálculo = Valor absoluto)

Campo numérico para definir o valor fixo que será descontado do total ou da diária configurada.

**Aplicar nas seguintes noites:**

Define em quais noites da reserva o desconto será aplicado.

**Opções disponíveis:**

**Todas as noites →** desconto aplicado em todas as noites da estadia.

**Maior preço →** desconto aplicado apenas na diária de maior valor.

**Menor preço →** desconto aplicado apenas na diária de menor valor.

**Primeira noite →** desconto aplicado somente na primeira noite da reserva.

**Última noite →** desconto aplicado somente na última noite da reserva.

**Dias da semana →** permite configurar o desconto apenas para noites específicas (ex.: somente de segunda a quinta).

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hbook_-_Oferta_image9_1276ac0e.png)

**Funcionamento da Exibição de Descontos na Tela Pública:**

Os descontos configurados no sistema podem ser aplicados em **percentual** ou em **valor absoluto**.
Entretanto, **na tela pública (motor)**, sempre serão apresentados em **forma de porcentagem sobre o valor total da reserva**.

### **Como o desconto é calculado**

* Se a configuração for **Percentual**, o sistema aplica o percentual definido sobre os valores da reserva.
* Se a configuração for **Valor absoluto**, o sistema converte esse valor em um percentual equivalente em relação ao total da reserva, exibindo-o ao cliente também em porcentagem.

* **Datas que contemplam o desconto:** o percentual ou valor configurado será aplicado normalmente.
* **Datas que não contemplam o desconto:** o sistema mantém o valor integral da diária, sem aplicar desconto.
* **Reservas que incluem períodos mistos (com e sem desconto):** o sistema calcula a **média do desconto efetivo** sobre o valor total da reserva, e é essa média percentual que será exibida ao cliente.
* **Mais de uma oferta no mesmo período:** caso o hotel crie várias ofertas que se apliquem às mesmas datas, o sistema sempre apresentará automaticamente a **mais vantajosa para o hóspede**. As ofertas **não se acumulam entre si,** exceção a oferta de reserva abandonada, que pode ser adicionada a partir da tela Adicionando Filtros.
* **Ofertas podem acumular com código promocional**: Ofertas podem ser combinadas com códigos promocionais.

O acúmulo de **ofertas + código promocional** só ocorre quando, na configuração do **código promocional**, a opção de acúmulo estiver **explicitamente habilitada**.

Os percentuais não se somam diretamente (ex.: 10% da oferta + 5% código promocional ≠ 15% de desconto).

O sistema aplica primeiro a oferta configurada e, sobre o valor resultante, aplica o desconto do código promocional.

Isso gera um percentual efetivo diferenciado.

**Exemplo prático oferta + código promocional**

Valor da reserva: R$ 1.000,00

Oferta de 10% → novo valor: R$ 900,00

Código promocional de 5% aplicado sobre R$ 900,00 → R$ 855,00

Percentual final efetivo: 14,5%

### **Exemplo prático períodos mistos**

Um cliente pesquisa uma estadia de **5 noites**:

* 3 noites têm desconto de **20%**.
* 2 noites não possuem desconto.
* O sistema irá aplicar o desconto apenas nas 3 noites configuradas e, no resultado, exibirá ao cliente uma **percentagem média de desconto sobre o total da reserva**.

* Período da oferta: **30/09/2025 até 28/02/2026**
* Regra: **Desconto de 85% em todas as noites dentro do período**

1. Se o cliente buscar uma estadia **inteiramente dentro do período da oferta** (ex.: 26/02/2026 a 28/02/2026), o desconto aplicado e exibido será **85%**.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hbook_-_Oferta_imaged_7222c581.png)

2. Se o cliente buscar uma estadia que **abrange datas dentro e fora do período** (ex.: 26/02/2026 a 02/03/2026), o sistema aplicará **85% de desconto apenas nas noites válidas até 28/02/2026** e cobrará o valor integral das noites de março.

Nesse caso, o cliente verá na tela um **percentual médio de desconto**, calculado considerando as noites com e sem desconto.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hbook_-_Oferta_image15_4d5dc7e4.png)

Metadados do Documento

|  |  |
| --- | --- |
| **Sistema:** | **HBook (Motor de Reservas)** |
| **Módulo:** | Promoções |
| **Funcionalidade:** | Ofertas |
| **Data de referência:** | 27/10/2025 |
| **Tipo de documento:** | Guia de configuração |