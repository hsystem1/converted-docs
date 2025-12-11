Documentação: Propriedade - Configurações

Visão geral

Este documento descreve o processo de utilização e gerenciamento da tela de configurações no sistema HBot (Chatbot e atendimento multicanal).

**Objetivo da funcionalidade**

A funcionalidade **“Propriedade – Configurações”** tem como objetivo **centralizar todas as informações e parâmetros operacionais da propriedade cadastrada no Hbot**, permitindo que o usuário personalize o comportamento do sistema de acordo com as características e necessidades do seu negócio.

Assim que você entra nas configurações da sua propriedade dentro do Hbot, o primeiro menu que aparece é o **“Geral”**, localizado na parte superior da tela, dentro da aba de navegação principal.
 Além dele, você também verá outras abas, como **Página de Políticas**, **E-mails**, **Formulários**, **Motor de Reservas e Termos e condições**.

Caminho:

Menu superior → Propriedade → Configuração

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Propr_imageb_f91b0770.png)

**Aba Geral:**

Menu superior → Propriedade → Configuração → Aba Geral

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Propr_image16_f1c837fc.png)

### **Campos principais de identificação**

Logo no início, você encontrará os **dados cadastrais** da propriedade:

* **Código do Cliente**: um identificador único do hotel, cadastro código do cliente hsystem.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Propr_image1a_e3eeefaf.png)

* **Nome**: aqui aparece o nome comercial da sua propriedade

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Propr_image1c_dea0bbb1.png)

* **CNPJ ou CPF**: campo obrigatório onde você insere o documento fiscal da empresa, podendo se CPF ou CNPJ.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Propr_image24_56c6f426.png)

* **Telefone**: o número de contato principal da propriedade.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Propr_image25_1ab3e914.png)

* **Tipo**: define se o cadastro é usado por *Propriedade individual ou Rede*.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Propr_image29_9dd0b8c6.png)

* **Tipo de Negócio**: conforme o segmento do estabelecimento (hotel, pousada, hotel fazenda, casa etc).

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Propr_image14_ae0f4dc4.png)

### **Configurações de funcionamento**

Logo abaixo, estão as opções de personalização e comportamento da propriedade dentro do Hbot.
 Cada uma delas pode ser ativada ou desativada com o botão de alternância (toggle).

**A propriedade aceita crianças**

* 1. Quando ativado, o sistema indica que seu estabelecimento aceita hóspedes infantis.
  2. Isso pode influenciar regras e mensagens automáticas.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Propr_image1d_04cefd51.png)

**Habilitar distribuição de atendentes**

* Essa opção, quando ligada, permite que o sistema distribua os atendimentos entre diferentes operadores.
* Ideal para equipes de atendimento maiores, para que tenha uma distribuição equilibrada.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Propr_image1e_30a7dcc3.png)

**Conta Facebook verificada**

Quando a conta do Facebook é verificada.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Propr_image21_7342b69a.png)

### **Controle do robô (chatbot)**

Aqui começam as configurações relacionadas ao robô de atendimento do Hbot:

* **Reativar robô automaticamente após X minutos de inatividade**
  + Permite definir o tempo que o sistema deve aguardar antes de reativar o robô de forma automática.
  + Após o tempo definido, caso não haja resposta do atendente, o robô será reativado e responderá automaticamente a última mensagem do cliente.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Propr_image22_11beb006.png)

* **Enviar mensagem de reativação do robô e conversa assumida**
  + Quando ativado, o Hbot envia uma notificação automática informando ao cliente que o robô foi reativado ou que a conversa foi assumida por um atendente humano.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Propr_image4_3a9cd106.png)

### **Salvando as configurações**

Após realizar qualquer alteração, **não se esqueça de clicar no botão azul “Salvar”** no canto inferior direito da tela.
 Somente assim as mudanças serão aplicadas com sucesso no sistema.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Propr_imagef_138831d4.png)

**Aba Página de Políticas:**

Menu superior → Propriedade → Configuração → Página de políticas

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Propr_image28_8f68b195.png)

O campo de texto exibido nessa aba permite que você **defina o final da URL** onde serão exibidas as políticas da sua propriedade.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Propr_imagee_8772b249.png)

### **️Tudo o que for digitado nesse campo será aplicado no final do endereço padrão, formando uma URL única para sua propriedade no formato:**

**https://hbot.com.br/politicas/** + *seu-texto*

Por exemplo, se você digitar **hotel-fazenda**, a URL final será:

**https://hbot.com.br/politicas/hotel-fazenda**

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Propr_image15_8a40a4e3.png)

A política exibida no link gerado nesta aba (**Página de Políticas**) é exatamente a mesma que você configurou no **Motor de Reservas (Hbook)**.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Propr_image18_72de7fb2.png)

A parte referente à **Política Geral** está localizada no **Hbook**, na aba **Propriedade → Geral → Política Geral**.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Propr_image2b_bda94235.png)

A seção sobre **Política de Idade** está disponível no **Hbook**, na aba **Propriedade → Geral → Política de Idade**.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Propr_imagea_75e6a2c3.png)

Já a parte da política que trata da **Política Tarifária** encontra-se no **Hbook**, em **Propriedade → Tarifa → Editar a Tarifa → Aba Garantias e Cancelamento**.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Propr_imagec_a07d9a1f.png)![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Propr_image11_69557a2d.png)

**Aba e-mails:**

Menu superior → Propriedade → Configuração → E-mails

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Propr_image20_6e29b285.png)

# **1. E-mail de Notificações**

Este é o primeiro bloco da aba.
 Aqui, você define quais endereços de e-mail receberão **as notificações gerais do sistema**, como:

* Alertas desconexão do WhatsApp
* Recebimento de formulário
* Relatório conversas não entendidas

O campo **“E-mails”** permite inserir um ou vários endereços, utilizando vírgula ou ponto e vírgula como separador.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Propr_image2c_80bffd7a.png)

# **2. E-mail de Métricas Semanais**

O segundo bloco é dedicado ao envio de **relatórios semanais de desempenho** do ChatBot.
 Essas métricas podem incluir:

* Quantidade de atendimentos
* Cotações
* Reservas indiretas
* Intenções mais respondidas
* Período cm maior demanda

Basta inserir o(s) e-mail(s) da equipe que deve acompanhar esses dados.

Enviando toda segunda-feira.

Esse recurso é muito útil para monitorar resultados e apoiar decisões de melhoria contínua.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Propr_image5_85515b48.png)

Exemplo de email semanal:

# **3. E-mail de Reservas**

No terceiro bloco, você configura os e-mails que devem receber:

* **Reservas capturadas pelo bot**

Assim como nos demais campos, é possível adicionar vários destinatários, garantindo que ninguém da equipe comercial perca oportunidades.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Propr_image12_d225db9c.png)

## **Salvando as Definições**

Após preencher todos os campos desejados, basta clicar no botão **Salvar**, localizado no canto inferior direito da tela.
 Somente após salvar os ajustes o sistema começará a enviar os comunicados para os endereços definidos.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Propr_image17_8723b72f.png)

**Aba Formulários:**

Menu superior → Propriedade → Configuração → Formulários

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Propr_image1f_22177fd8.png)

Essa aba é responsável por determinar **quais informações o bot solicitará ao hóspede** durante interações que envolvem coleta de dados — como pedidos de orçamento, intenções de reserva, cadastro inicial e outros fluxos que dependem de identificação do cliente.

É aqui que você controla **quais campos aparecem no formulário** e se cada um deles deve ser **opcional ou obrigatório**.

A tela apresenta três grupos de informações principais que podem ser solicitadas ao hóspede:

* **Nome**
* **E-mail**
* **Telefone / WhatsApp**

Para cada uma delas, você encontrará dois tipos de controles:

1. **Habilitar solicitação** (ex.: *Pedir nome*)
2. **Tornar obrigatório** (ex.: *Nome é obrigatório*)

Essas opções permitem personalizar o formulário de acordo com as necessidades da sua propriedade.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Propr_image26_70e6c151.png)**1. Pedir Nome**

Ativando essa opção, o bot passa a solicitar o **nome completo do hóspede** no formulário.

### **Nome é obrigatório**

Se habilitado, o hóspede **só conseguirá enviar o formulário** após preencher o nome.
 Caso esteja desativado, o nome será opcional.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Propr_image27_205ade0c.png)**2. Pedir E-mail**

Quando ativado, o Hbot exibirá um campo de **e-mail** para o hóspede preencher.

### **E-mail é obrigatório**

Se esta opção estiver ligada, o formulário **exigirá um e-mail válido** antes de permitir o envio.
 Ideal para propriedades que utilizam confirmação por e-mail.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Propr_image7_e93ba455.png)**3. Pedir Telefone / WhatsApp**

Habilitando essa opção, o bot solicitará um número de telefone ou WhatsApp ao hóspede.

### **Telefone/WhatsApp é obrigatório**

Quando ligado, o hóspede deve informar o telefone para concluir o formulário.
 Recomendado para propriedades que fazem contato comercial principalmente via WhatsApp.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Propr_image8_7bce3b5f.png)**Salvando as Alterações**

Depois de selecionar os campos desejados, clique no botão **Salvar** para aplicar as configurações.
 A partir desse momento, todos os formulários gerados pelo Hbot seguirão o padrão definido nesta tela.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Propr_image9_31f27fb0.png)

**Como será solicitado aos clientes**

Esses dados vão ser pedidos aos seus clientes no ato de uma cotação, ou seja: Ao ser acionada a intenção de "Reservar / Cotação" e depois das informações de datas de check-in e checkout e quantidade de pessoas, veja que legal:

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Propr_image10_58ec1b06.png)

**-Onde essas informações serão apresentadas para** **você?**

Serão apresentadas em duas telas diferentes:

**1-Na tela do Chat Online**, dentro da conversa estará de forma simples o nome do hóspede.
![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Propr_imaged_000d723e.png)

Já ao clicar em "perfil do cliente" nos três pontinhos dentro da conversa trazemos o nome, e-mail e telefone (quando solicitado), além da região do cliente.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Propr_image23_0a87382e.png)

**2- Na tela de "contatos"** que é específica para isso e tem funcionalidades muito interessantes:

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Propr_image_6447e1ac.png)

Nessa tela teremos todos os contatos (leads) e é possível filtrar por datas, canais e tags (cotação, sem dispo). Também é possível exportar esse relatório em formato de planilha ou abrir uma conversa em questão para entender melhor o fluxo de mensagens e datas procuradas; com isso você pode fazer uma ação mais direta e ativa com esses clientes para fechar ainda mais reservas!

**Aba Motor de reservas:**

Menu superior → Propriedade → Configuração → Motor de reservas

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Propr_image2_0ba12c35.png)

A aba **Motor de Reservas** permite configurar como o sistema irá se integrar ao motor de reservas utilizado pelo estabelecimento. Nela, o usuário pode:

* **Selecionar o integrador:** Selecionar o sistema, podendo ser o motor de reservas Hbook da HSystem ou o motor da Omnibees.Responsável por conectar o sistema ao mecanismo de reservas do site.
* **Informar o HBook ID:** Que identifica a conta do estabelecimento dentro do integrador (Hbook).
* **Cadastrar um código promocional:** Caso a pousada ofereça cupons de desconto para reservas.
* **Ativar ou desativar a exibição de opções de cama**, permitindo que o hóspede escolha configurações específicas de leito no momento da reserva, montagem de cama da categoria.

## **Salvando**

Depois de preencher os campos desejados, clique no botão **Salvar** para aplicar as configurações.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Propr_image3_6fc8e3b9.png)

### **Aba “Termos e Condições” – Configurações**

Menu superior → Propriedade → Configuração → Termos e condições

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Propr_image6_e4ac77fb.png)

Nessa aba, o hotel define como os **termos e condições** serão apresentados ao hóspede durante o fluxo do bot ou no formulário.

O campo **“Tipo”** permite duas opções:

1. **Editor de Texto**
   1. Ao selecionar essa opção, é exibido um editor de texto completo.
   2. O hotel pode **escrever manualmente** seus termos e condições diretamente na plataforma.
   3. É possível formatar o texto (negrito, itálico, listas, cores, links etc.), deixando o conteúdo exatamente como deseja.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Propr_image13_7818b8ed.png)

1. **Link Externo**
   1. Quando essa opção é escolhida, o editor de texto é substituído por um campo simples de URL.
   2. O hotel deve inserir o **link direto** para uma página externa onde seus termos e condições já estejam publicados.
   3. O hóspede será direcionado para esse link sempre que solicitar ou necessitar visualizar os termos.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Propr_image1b_ffd03c42.png)

Essa flexibilidade permite que o hotel escolha entre **manter tudo centralizado no sistema** ou **usar uma página institucional própria**.

Após preencher ou alterar qualquer informação, o hotel deve clicar no botão **Salvar**, localizado ao final da página, para garantir que as mudanças sejam aplicadas.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Propr_image2a_1fc9ed0d.png)![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_165101_223d/images/Documentação_Propr_image19_2d08b04c.png)

Metadados do Documento

|  |  |
| --- | --- |
| **Sistema:** | **HBot (Chatbot e atendimento multicanal)** |
| Módulo: | Propriedade |
| Funcionalidade: | Configurações |
| Data de referência: | 17/11/2025 |
| Tipo de documento: | Guia de utilização |