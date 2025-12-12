Documentação: Lista de bars

Visão geral

Este documento descreve as informações da tela de lista de bars na aba de flutuações no sistema Hprice (Flutuação).

**Objetivo da funcionalidade**

Nesta tela você vai conhecer como funciona a flutuação tarifária pelos níveis tarifários pré definidos, que chamamos de ***BAR (Best Available Rate).***

A ideia é cadastrar seu tarifário padrão para que ele seja o ponto de partida para flutuações de preço, seja para baixo ou para cima.

**Caminho de acesso:**
Menu superior → Flutuação → Lista de Bars

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hprice_-_Flutuação_image2_0f51e566.png)

**Cadastro de BARs: Estrutura**

**Botões de Ação**

No canto superior direito, você tem duas opções:

* **Ordenar Bars**: Permite reorganizar a sequência das suas BARs, pode arrastar as BARs para reordenar.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hprice_-_Flutuação_imagec_d7dab084.png)

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hprice_-_Flutuação_imaged_8859e7f4.png)

* **Nova Bar** (botão laranja): Para criar uma BAR, podendo ser:

A partir do zero: Neste formato você terá as opções de adicionar uma descrição, um código (de até 5 caracteres) e preencher as colunas de forma manual. Podemos observar que na criação desta tarifa nós temos a descrição dos dias da semana, então, se para a propriedade é aplicada um valor diferente para algum dia da semana, essa diferença já deve ser aplicada no momento deste preenchimento dos valores. Após preencher a primeira coluna, é possível replicarmos esse preço para o restante da semana. Depois de preencher todas as informações necessárias, podemos salvar, e então, concluímos a criação de uma tarifa base.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hprice_-_Flutuação_image9_67d4858f.png)

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hprice_-_Flutuação_imagea_d03a05e4.png)

Importando dados de outra: A opção de importar dados de outra lhe permite puxar os preços já cadastrados em uma tarifa base, somar ou subtrair em porcentagem (para reduzir basta adicionar um sinal de menos “-” na frente no número) e, depois de convertido, trazer esses valores em uma nova configuração de tarifa para que você preencha o restante das informações de descrição e código. Neste formato também é possível editar as informações e preço, mesmo que já estejam preenchidas. Após salvar, ela será criada também como uma tarifa base.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hprice_-_Flutuação_image5_5b26077e.png)

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hprice_-_Flutuação_image6_248aa506.png)

- Derivada de outra: Nas tarifas derivadas nós devemos selecionar uma tarifa base (nova ou importada) em “Derivada de”, e em “com uma diferença de”, definir o quanto ela vai ter de acréscimo

ou redução (para redução basta adicionar um sinal de menos “-” na frente no número), também é possível determinar se a unidade será em porcentagem ou em reais. Adicione também no nome e código uma informação que lhe ajude a identificar de forma mais rápida os valores dessa tarifa. Nos cadastros das derivadas não é possível editar manualmente algum preço específico nas colunas, as únicas alterações que podem ser feitas são nos preenchimentos do cabeçalho. Após salvar, podemos observas que as tarifas derivadas vêm com uma descrição na lateral, de qual tarifa ela está derivando, em quanto, e sua unidade (porcentagem ou reais.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hprice_-_Flutuação_imagee_9dab5397.png)

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hprice_-_Flutuação_image3_77d8ab31.png)

Observações: O código é bem importante ter em todos os cadastros, pois é a partir dele que você irá identificar posteriormente qual tarifa está vigente para cada dia. Não é possível criar uma tarifa derivada de outra derivada, somente de uma importada ou do zero

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hprice_-_Flutuação_imageb_db20e720.png)

**A Tabela de BARs**

A tabela é organizada em três colunas principais:

**Nome**: Aqui você vê o nome da BAR e seu código.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hprice_-_Flutuação_image_7544d4d9.png)

**Descrição/Derivação (Coluna Central)**: Ela mostra como cada BAR se relaciona com uma BAR principal.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hprice_-_Flutuação_image8_60f91c5b.png)

**Última Atualização**: Mostra quando cada BAR foi modificada pela última vez.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hprice_-_Flutuação_image4_4ffc702d.png)

**Ações por BAR**

Ao lado de cada BAR, você encontra dois ícones:

* **(Lápis)**: Para editar a BAR
* **(Lixeira)**: Para excluir a BAR

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hprice_-_Flutuação_image7_0bf421dd.png)

Metadados do Documento

|  |  |
| --- | --- |
| **Sistema:** | **HPRICE (Flutuação)** |
| **Módulo:** | Flutuação |
| **Funcionalidade:** | Lista de BARs |
| **Data de referência:** | 04/11/2025 |
| **Tipo de documento:** | Guia de configuração |