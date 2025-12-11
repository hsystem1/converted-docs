**Documentação: Quartos**

**Visão Geral**

Este documento descreve o processo de configuração de quartos no sistema HBook (Motor de reservas)

**Objetivo da funcionalidade**

Nesta funcionalidade o usuário pode criar categorias de quartos para venda ou editar categorias já existentes. Essa funcionalidade permite gerenciar de forma prática a oferta de unidades do hotel, definindo nomes, descrições, capacidades, e outras características relevantes para cada tipo de quarto

**Acesso à funcionalidade**

Acessar a ferramenta Hbook (Motor de reservas)

Caminho: PROPRIEDADE -- QUARTOS

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_152118_3dd8/images/Quarto_Hbook_image8_a51d730f.png)

**Estrutura da tela:**

No topo, há um campo “Ordenar Por”, que permite organizar a lista de quartos.

Abas de Visualização da tabela:

Mostrar Quartos Ativos: exibe somente os quartos com a opção “Ativo” marcada.

Mostrar Quartos Inativos: exibe quartos que estão desativados, mas que ainda existem no sistema. Caso queira reativar, basta marcar o flag de “ativo” novamente.

Tabela de Tipos de Quarto:

Cada linha representa uma categoria de quarto e contém várias colunas:

Código: identificação única do quarto no sistema.

Nome: nome da categoria do quarto.

Ativo: checkbox que indica se o quarto está disponível ou não para reservas.

Ocupação Mín. / Máx.: número mínimo e máximo de pessoas que podem ocupar o quarto.

Adultos Máx.: limite de adultos permitidos.

Crianças Máx.: limite de crianças permitidas.

Fotos: quantidade de fotos cadastradas para o quarto.

Comodidades: número de comodidades associadas.

Tipos de Cama: quantidade de tipos de cama configurados para a categoria.

Fumante: checkbox que indica se o quarto permite fumantes.

Ações da Categoria:

Ícones na última coluna permitem ações rápidas:

Editar: modificar informações do quarto.

Símbolo infinito: copiar comodidades de outro tipo de quarto.

**Opções de configuração**

Para criar um quarto basta ir em PROPRIEDADE → QUARTOS – no canto inferior direito, possui um botão roxo com um +.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_152118_3dd8/images/Quarto_Hbook_imagec_971f8823.png)

O primeiro passo é preencher a tela de **Dados Gerais** com as informações essenciais:

* **Nome:** Identificação do quarto no sistema e na tela pública.
* **Link de Vídeo no YouTube (opcional):** Pode ser adicionado se houver, mas não é obrigatório.
* **Flag ativo:** Se marcar ficara disponível para incluir para venda e de desmarcado não será uma opção de venda.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_152118_3dd8/images/Quarto_Hbook_image_d1e8b58a.png)

* **Texto Descritivo:** Detalhes sobre características e comodidades do quarto.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_152118_3dd8/images/Quarto_Hbook_image6_eb0ccf0c.png)

* **Ocupação Mínima:** Número mínimo de hóspedes permitidos.
* **Ocupação Máxima:** Número máximo de hóspedes permitidos. Corresponde ao total de hóspedes no quarto, considerando a **soma do máximo de adultos e máximo de crianças sem ultrapassar a máxima do quarto**.

Por exemplo, imagine um quarto que aceita até 5 pessoas, configurado com **máximo de 5 adultos** e **máximo de 3 crianças**. A **ocupação máxima do quarto** é de 5 pessoas, ou seja, a soma de adultos e crianças na pesquisa publica não pode ultrapassar esse limite.

Nesse caso, as combinações possíveis de ocupação seriam:

1 adulto com 0 a 3 crianças

2 adultos com 0 a 3 crianças

3 adultos com 0 a 2 crianças

4 adultos com 0 a 1 criança

5 adultos sem crianças

* **Máximo de Adultos:** Limite de adultos no quarto.
* **Máximo de Crianças:** Limite de crianças no quarto.
* **Permite Fumante:** Indica se o quarto aceita fumantes (marcar flag se aceita).

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_152118_3dd8/images/Quarto_Hbook_imaged_0d8b29dc.png)

**Observação importante:**
Se estiver **criando um quarto**, o sistema **não permite avançar para as demais abas** de configuração (Fotos, Comodidades, Tipos de cama) **antes de salvar os dados gerais**. É necessário salvar primeiro para que o quarto seja registrado no sistema e as outras opções sejam liberadas. APÓS SALVAR PABSTA CLICAR PARA EDITAR NOVAMENTE ESSA CATEGORIA/QUARTO E SEGUIR COM DAS DEMAIS CONFIGURAÇÕES.

**Aba para adicionar foto:** Fotos de apresentação do quarto.

Botão para incluir imagem **“Adicionar nova foto”.**

**Dimensão recomendada**
 Garanta que as imagens estejam no tamanho recomendado de **960px x 720px** para uma visualização perfeita no motor de reservas.

Caso queira remover alguma imagem em específico, tem o botão **“Remover”** abaixo de cada foto**.**

Para alterar a ordem das imagens, basta arrastar cada foto para a posição desejada e, em seguida, clicar em **“Salvar Ordem”**

Botão **“definir como padrão”** abaixo de cada imagem, serve para o hotel escolher qual será a foto de capa do quarto na tela publica, só é possível escolher uma como capa e a escolhida fica escrito **“Foto padrão”** abaixo da imagem**.**

**Baixar todas imagens:** exporta os arquivos já carregados

**Excluir todas imagens:** remove todo o conteúdo da galeria de uma vez.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_152118_3dd8/images/Quarto_Hbook_image2_d73214e4.png)

Tela de Comodidades:

Essa tela corresponde à configuração de comodidades disponíveis no quarto, que permite selecionar quais serviços e facilidades estão disponíveis para os hóspedes.

**Estrutura da tela:**

**Id:** identificação interna de cada item.

**Disponível:** botão seletor (ativar/desativar) para indicar se a comodidade deve ser exibida ao hóspede.

**Comodidades:** lista de comodidades disponíveis para seleção (também aparece um resumo de quantos já tem selecionados).

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_152118_3dd8/images/Quarto_Hbook_imagee_4be6ba67.png)

**Como funciona:**

* O hotel pode marcar apenas as comodidades que realmente oferece no quarto.
* Essas informações aparecem no motor de reservas, ajudando o hóspede a conhecer melhor a estrutura antes da reserva.
* Possui o botão **“Mostrar apenas comodidades selecionadas”**, que filtra a lista exibindo somente os itens já ativados. Isso facilita a conferência do que será apresentado no motor de reservas, evitando que o hotel precise percorrer toda a lista.
* **Campo de filtro:** permite pesquisar comodidades específicas dentro da lista, agilizando a configuração.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_152118_3dd8/images/Quarto_Hbook_image7_82601487.png)

Tela tipos de cama:

Na tela de **Configuração da Montagem de Camas do Quarto**, é possível definir quais tipos e quantidades de camas estão disponíveis em cada unidade habitacional. Essa configuração ajuda a detalhar melhor a acomodação para o hóspede, permitindo mostrar diferentes possibilidades de arrumação do quarto.

O sistema permite **criar mais de uma montagem de camas**, oferecendo combinações diferentes conforme a estrutura do quarto.

#### **Estrutura da tela:**

* **Quantidade**: define quantas camas daquele tipo existirão na montagem.
* **Tipo de Cama**: seleção do modelo, que pode variar entre cama de solteiro, cama de casal, beliche, sofá-cama, berço, entre outros.
* **Remover:** exclui a linha de quantidade e tipo de cama inserido.
* **Botão + Tipo de cama:** adicionar mais um tipo de cama a montagem do quarto.
* **Remover Montagem**: exclui a montagem criada.
* **Adicionar Montagem**: possibilita incluir uma nova configuração de camas, criando diferentes cenários para o mesmo quarto.

#### **Exemplo:**

Um quarto com **ocupação máxima de 5 pessoas** pode ter mais de uma configuração de camas:

* Montagem 1: 5 camas de solteiro.
* Montagem 2: 2 camas de casal + 1 cama de solteiro.
* Montagem 3: 1 cama de casal + 3 camas de solteiro.

Assim, o hotel consegue exibir opções variadas para o mesmo quarto, respeitando sempre a **ocupação máxima permitida**.

Exemplo da imagem tem 2 tipos de montagem:

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_152118_3dd8/images/Quarto_Hbook_image9_f13f2a6a.png)

Ao finalizar o cadastro clicar no botão roxo no canto inferior direto.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_152118_3dd8/images/Quarto_Hbook_image5_97c72096.png)

Ao criar um quarto/categoria e possui conexão com Hunit (Gestor de canais) e/ou PMS (Gestor hoteleiro/gestão de disponibilidade de UH’s), você deve contatar nossa equipe de suporte para pedir mapeio do novo quarto.

Para editar um quarto basta ir em PROPRIEDADE → QUARTOS – na última coluna possui um ícone de editar.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_152118_3dd8/images/Quarto_Hbook_imagea_73709cfb.png)

**Importante!!!**

Sempre que for editar um **quarto já existente**, é necessário **salvar as informações de cada aba** antes de mudar para outra.

**Por exemplo:** se você está editando o texto descritivo na aba **Dados Gerais**, antes de acessar a aba **tipos de cama** é preciso salvar aquela tela, caso contrário as alterações feitas serão perdidas.

Essa regra vale para todas as abas do cadastro do quarto.

Editando quartos já existentes: As edições nos seguintes campos, **impactam no mapeio**, se possui conexão com Hunit (Gestor de canais) e/ou PMS (Gestor hoteleiro/gestão de disponibilidade de UH’s), então após editar qualquer um desses campos abaixo, **você deve contatar nossa equipe de suporte para pedir o ajuste no HUNIT.**

* Ocupação Mínima
* Ocupação Máxima
* Máximo Adultos
* Máximo Crianças

Configurações de ordem:

**Ordenar Por:** permite organizar a lista de quartos

**Menor preço -** Permite ordenar a apresentação das categorias pelo menor preço de diária. A aplicação não reflete na listagem da tela “tipos de quarto”, irá apresentar somente na tela pública para o hóspede.

**Alfabética (A-Z) -** Permite ordenar a apresentação das categorias por ordem alfabética (Campo nome). A aplicação não reflete na listagem da tela “tipos de quarto”, irá apresentar somente na tela pública para o hóspede.

**Manual -** Permite que o hotel defina a ordem exata em que deseja que os quartos apareçam para os hóspedes na página pública. Ou seja, a sequência que o hotel organiza na listagem interna será a mesma exibida ao cliente final.

Na última coluna da tabela, há o ícone de **engrenagem**, onde é possível ajustar a posição de cada categoria de quarto. As opções disponíveis para reorganização são:

**Ordenar em primeiro:** move a categoria para o topo da lista.

**Ordenar antes:** posiciona a categoria antes de outra à cima.

**Ordenar depois:** posiciona a categoria após outra à baixo.

**Ordenar em último:** move a categoria para o final da lista.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_152118_3dd8/images/Quarto_Hbook_imageb_68cc2494.png)

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_152118_3dd8/images/Quarto_Hbook_image3_2904f2a7.png)

Variáveis disponíveis:

Bandeiras nas caixas de texto: Corresponde a configuração de idiomas por bandeira.

Cada bandeira representa um idioma (português, inglês e espanhol).

O hotel precisa escrever o conteúdo manualmente no idioma correspondente à bandeira escolhida.

O sistema não faz tradução automática — portanto, se o hotel deseja que o texto apareça em inglês ou espanhol, deve inserir a versão traduzida para o idioma em questão.

Esse conteúdo será exibido no motor de reservas público, permitindo que o hóspede selecione o idioma desejado e veja as informações já traduzidas.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_152118_3dd8/images/Quarto_Hbook_image4_8a0cc18f.png)

Metadados do Documento

|  |  |
| --- | --- |
| **Sistema:** | **HBook (Motor de Reservas)** |
| **Módulo:** | Quartos |
| **Funcionalidade:** | Quartos |
| **Data de referência:** | 24/10/2025 |
| **Tipo de documento:** | Guia de configuração |