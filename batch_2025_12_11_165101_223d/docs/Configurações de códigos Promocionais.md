**Configurações de códigos Promocionais**

**Visão Geral**

Este documento descreve o processo de criação e configuração de códigos promocionais no sistema **HBOOK (Motor de Reservas)**, incluindo códigos para campanhas de marketing, orçamento internos e envio de propostas personalizadas.

**Objetivo da Funcionalidade**

A funcionalidade de **códigos promocionais** permite criar campanhas exclusivas, realizar orçamentos personalizados e facilitar acordos comerciais com parceiros e agencias, otimizando o processo de vendas e **marketing do hotel.**

**Casos de Uso**

**Por que usar essa funcionalidade?**

* **Na tela Códigos promocionais**, o usuário pode criar promoções ou editar códigos já existentes. Essa funcionalidade permite gerenciar de forma prática as condições comerciais do hotel, definindo tipo de uso, datas de aplicabilidade entre outros.
* **Campanhas exclusivas de marketing:** Criar códigos para ações promocionais, cliente **VIPS** e **parceiros estratégicos.**
* **Orçamento Personalizados:** Gerar simulações de reservas com condições especiais para enviar aos clientes via e-mail.
* **Conversão de cotações:** Transformar solicitações telefônicas em orçamentos formais com o link de pagamento.

**Acesso a Funcionalidade**

**Navegação no sistema**

Para criar uma oferta basta ir em **PROMOÇÕES → CÓDIGOS PROMOCIONAIS** – no canto inferior direito, possui um botão **ROXO** com um **+**

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Configurações_de_c_image_bd196ebe.png)

**Estrutura da Tela:**

* Essa **estrutura** permite acompanhar quais **promoções estão ativas,** quando expiram, quantas vezes foram usadas e se são visíveis ao cliente final ou apenas internas.

**Tabela de Código promocional:**

* Cada linha representa um tipo de **Código promocional** e contém várias colunas:

**Código da promoção:**

* Identificação única da promoção. É o código que o hóspede ou agente utiliza para aplicar o desconto/condição especial.

**Nome**:

* Nome descritivo da promoção, utilizado para facilitar a identificação interna no sistema.

**Data início**:

* Data a partir da qual o código promocional ou interno passa a ser válido.

**Data término**:

* Data limite de validade do código. Após essa data, a promoção deixa de funcionar.

**Estadia mínima**:

* Define o número mínimo de noites que o hóspede deve reservar para que o código seja aplicado.

**Uso**:

* Quantidade de vezes que o código já foi utilizado em reservas efetivadas no sistema.

**Tipo de uso:**

* Define quem pode utilizar o **código.**

**Ações da Categoria:**

* **Ícones** na última coluna permitem ações rápidas:
* **Editar (lápis)** → permite editar o código existente.
* **Excluir (lixeira)** → exclui o código promocional cadastrada.
* **Copiar (folha duplicada)** → cria uma cópia da oferta para agilizar a criação de novas promoções semelhantes.
* **Copiar link do código promocional (documentos sobrepostos) →** Copia o link do motor que direciona para a aplicabilidade do código em tela pública.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Configurações_de_c_image9_5ee4fd78.png)

**Configurando Código Promocional**

* Os campos e botões disponíveis permitem definir regras de uso, validade e restrições específicas de cada código.

**Gerar Link:** Gera o **link direto** deste código promocional. Esse link pode ser enviado ao hóspede e direciona para a tela pública do motor de reservas já com o código aplicado.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Configurações_de_c_imageb_7803681b.png)

**Gerar em Massa:** Permite gerar **vários códigos promocionais com a mesma configuração**. Ao selecionar esta opção, é aberta uma nova tela para definir **quantas cópias** do código deseja criar.
Os códigos gerados terão **IDs automáticos e aleatórios**, que **não podem ser editados** posteriormente.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Configurações_de_c_image6_fdfa4d83.png)

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Configurações_de_c_imagea_d2b491d7.png)

**Dados Gerais:**

* **Nome:** Campo para identificar o código promocional internamente. Pode conter o nome da campanha, evento ou promoção.
* **Código da Promoção;** Código que será utilizado pelo hóspede no momento da reserva. Após ser definido e salvo, **não pode ser alterado**.
  O botão **“Gerar código”** pode ser usado para criar automaticamente um identificador único.
* **Texto Descritivo;** Espaço opcional para inserir uma breve descrição ou observação sobre o código promocional.
* **Para agências;** quando marcado, o código será destinado para uso exclusivo de **agências parceiras**.
* **Para agente interno (usados para gerar orçamentos)**
  Habilita o uso do código por **agentes internos da propriedade**, facilitando o cálculo e simulação de orçamentos.
* **Limite máximo de uso;** Define quantas vezes o código pode ser utilizado no total. Para uso ilimitado, deve-se deixar o valor **0**.
* **Limite máximo por e-mail;** Determina quantas vezes o mesmo e-mail (cliente) pode usar o código. O valor **0** indica uso ilimitado.
* **Usado quantas vezes;** exibe a quantidade de reservas ativas (confirmadas) que utilizaram o código promocional.
  Esse número é atualizado automaticamente pelo sistema conforme novas reservas são feitas ou canceladas.

Caso uma reserva feita com o **código** seja cancelada, a quantidade exibida neste campo é reduzida, refletindo apenas as utilizações ativas no momento.![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Configurações_de_c_image7_269e9b9b.png)

**Data de validade para utilização do código**

* **Data Início / Data Término**
  Define o **período em que o código poderá ser utilizado** no momento da reserva.
  Após o término, o sistema não permitirá mais aplicar o código.
* **Prazo** para fazer a compra/uso e não a data que se aplica o desconto.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Configurações_de_c_imagec_6919013c.png)

**Período em que o hóspede poderá se hospedar utilizando este código:**

* **Data Início / Data Término (dentro do período de estada)**
  Define as datas em que a reserva precisa estar incluída para que o desconto seja aplicado.
  **Exemplo:** o hóspede só poderá utilizar o código se a hospedagem ocorrer entre **02/05/2024 e 02/10/2025**.
* Botão “**Novo Período”**
  Permite adicionar um ou mais intervalos de datas em que o hóspede pode se hospedar utilizando o código.
* **Flag** “**Período de estada exato?”**
  Quando habilitado, o código será válido **somente** para hospedagens dentro do período configurado abaixo. A data de início e data de término da pesquisa, tem que ser exatamente o que foi configurado para valer o desconto.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Configurações_de_c_image4_9058febd.png)

**Número de noites mínimas para que o código seja aceito**

* **Estada Mínima**
  Define o **número mínimo de noites** exigidas para que o código promocional seja aceito no momento da reserva.
  Se o hóspede selecionar menos noites do que o configurado, o código não será aplicado.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Configurações_de_c_image5_f7fc7aaf.png)

**Tarifas participantes**

* Nesta seção são configuradas as tarifas que poderão receber o desconto aplicado pelo código promocional, além de outras regras complementares como acúmulo com ofertas e restrição por dia da semana.
* **Acumular o desconto com as ofertas**
* Se marcado, o desconto do código **pode ser aplicado junto com uma oferta ativa** da tarifa. Quando desmarcado, o sistema considera o código **não cumulativo**, ou seja, o desconto promocional não será somado a eventuais ofertas já existentes.
* **Dias da semana**
* É possível restringir a aplicação do desconto apenas a determinados dias.
  Marque os dias da semana em que o desconto deve ser considerado — por exemplo, apenas de **segunda a sexta** ou somente **finais de semana**.
* O desconto será aplicado somente nos dias de semana selecionados
* Flag “**Mostrar no resultado da pesquisa de disponibilidade somente as tarifas selecionadas abaixo**”
* Ao marcar esta opção, o **motor de reservas** exibirá somente as tarifas configuradas como participantes do código promocional durante a busca de disponibilidade. Isso é útil quando o código é exclusivo para uma tarifa específica (por exemplo, “Tarifa Grupo” ou “Pacote Especial”).
* **Lista de Tarifas Participantes** na listagem exibida, cada linha representa uma tarifa ativa do sistema.
  Você pode definir para quais delas o desconto será aplicado, selecionando a caixa de marcação à esquerda.
* **Cada tarifa possui dois campos principais:**
* **Forma de Cálculo:** Define o modo como o desconto será aplicado:
  + **Percentual:** o valor configurado será considerado como **% de desconto** sobre a tarifa base.
  + **Valor Absoluto:** o valor inserido será **subtraído diretamente** do valor total da tarifa.
* **Valor**
  Indica o **percentual ou valor** do desconto, conforme a forma de cálculo selecionada. Exemplo: se a “Tarifa Grupo” tiver forma de cálculo “Percentual” e valor “10”, o hóspede terá **10% de desconto** ao aplicar o código promocional.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Configurações_de_c_image2_7bbda12e.png)

**Quartos participantes**

* **Lista de quartos:** Cada linha representa um tipo de quarto disponível. O desconto será aplicado aos tipos de quartos selecionados aqui.
* **Caixas de seleção:** Permitem escolher individualmente os quartos.
* **Botão “Marcar Todos”**: Seleciona todos os tipos de quartos.
* **Botão “Desmarcar”:** Remove a seleção de todos os quartos.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Configurações_de_c_image3_859a5936.png)

**Formas de pagamento liberadas quando utilizado o código**

* Nesta seção é possível restringir as formas de pagamento disponíveis quando o hóspede utiliza o código promocional no motor de reservas.
* As opções são apresentadas em formato de flags (caixas de seleção), e definem como o pagamento poderá ser realizado.
* **Pagamento Direto no Hotel**
  Quando marcada, permite que o hóspede selecione o pagamento diretamente no hotel, no momento do check-in ou checkout.
* **Faturado**
  Quando marcada, permite que a reserva seja feita com pagamento faturado, de acordo com a política de faturamento do estabelecimento.

**Importante:**
Se **nenhuma opção estiver marcada**, o sistema considerará as **formas de pagamento padrão configuradas na tarifa**.
Se **uma ou mais opções estiverem marcadas, somente essas formas estarão disponíveis** ao hóspede durante a reserva com o código promocional.

Após a criação do código promocional, clique em **SALVAR.**

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Configurações_de_c_image8_02267210.png)

**Encerramento:**

Pronto! Já pode utilizar seu código promocional

**Metadados de Documento**

|  |  |
| --- | --- |
| Sistema | HBOOK (MOTOR DE RESERVAS) |
| Módulo | CÓDIGO PROMOCIONAL |
| Funcionalidade | CRIAR CAMPANHAS EXCLUSIVAS |
| Data de Referência | 27/10/2025 |
| Tipo de documento | Guia de Configuração |
| Versão | 1.0 |