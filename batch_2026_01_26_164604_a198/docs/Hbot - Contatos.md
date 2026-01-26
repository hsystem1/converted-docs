**Tela de Contatos**

**HBOT**

1. **O que é a tela de contatos hbot?**

* A tela de contatos funciona como uma agenda automática. Nela, ficam guardados os dados de todos os "leads" (potenciais hóspedes) que interagiram com o seu chatbot ou com sua equipe, seja para pedir informações ou fazer uma cotação.

1. **Como Acessar:**

Menu superior → Contatos

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hbot_-_Contatos_imageb_2f6270d9.png)

### **3.Filtros e busca de contatos**

Na parte superior da tela, estão disponíveis os **filtros de pesquisa**, que ajudam você a localizar contatos específicos ou analisar períodos de interesse.

Você pode filtrar pelos seguintes campos:

* **Período (De / Até):** selecione o intervalo de datas para visualizar apenas os contatos gerados nesse período.![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hbot_-_Contatos_imagee_d5828397.png)
* **Canal:** escolha o canal de origem do contato, como WhatsApp, chat online ou outros integrados.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hbot_-_Contatos_image8_89662548.png)

* **Tags:** filtre por tags associadas, como *cotação*, *sem disponibilidade* ou *reserva concluída*.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hbot_-_Contatos_image13_243135ea.png)

* **Nome, telefone ou e-mail:** busque diretamente por informações específicas do cliente.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hbot_-_Contatos_image2_25f7e1de.png)

Após definir os filtros desejados, clique em **“Filtrar”** para visualizar os resultados.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hbot_-_Contatos_image4_e2683343.png)

### **4.Exportação dos dados**

Todos os contatos listados podem ser **exportados em formato de planilha (.csv)**.
 Para isso, basta clicar no botão **“Exportar”** — uma ótima opção para análise externa, acompanhamento de desempenho ou ações de marketing.![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hbot_-_Contatos_image9_0b308aa6.png)

### **5.Colunas da Tabela**

A tabela é organizada em 8 colunas principais, cada uma contendo informações específicas sobre o contato:

**Criação (possui ícone de seta dupla para ordenação):**

**Uso prático:**

* Identificar leads mais recentes
* Ordenar por data de primeiro contato
* Análise temporal de captação de leads

**Observação:** Este é o momento em que o cliente enviou a primeira mensagem e foi registrado no sistema, não necessariamente quando a conversa foi concluída.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hbot_-_Contatos_image10_46a9bdc3.png)

**6.Canal:**

Identifica por qual plataforma o cliente entrou em contato.

**Diferenças entre canais:**

* **Web:** Cliente está navegando no site/motor.
* **WhatsApp:** Contato mais direto.
* **Instagram/Facebook:** Cliente vem de redes sociais.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hbot_-_Contatos_image11_cac4f29d.png)

**7.Nome:**

Exibe o nome do cliente conforme cadastrado no perfil.

* Nome fornecido durante conversa com bot
* Preenchido no formulário de contato
* Atualizado manualmente por atendente
* Campo "Apelido" do perfil do cliente
* Não apesenta cadastro que ainda constam como “visitantes”

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hbot_-_Contatos_image7_d606a845.png)

**8.E-mail:**

Armazena e-mail do cliente para comunicações futuras.

* Nome fornecido durante conversa com bot
* Preenchido no formulário de contato
* Atualizado manualmente por atendente
* Campo "E-mail" do perfil do cliente

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hbot_-_Contatos_imagea_9fcc0801.png)

**9.Telefone:**

Armazena telefone do cliente para contato direto.

Quando a origem é WhatsApp, aparece ícone verde do WhatsApp ao lado do número.

* Fornecido durante conversa
* Preenchido em formulário (contato ou finalização da reserva)
* Automaticamente capturado (se conversa veio do WhatsApp)
* Perfil do cliente (Atualizado manualmente por atendente)

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hbot_-_Contatos_imaged_aaa2e025.png)

**10. Abriu cotação?**

Indica se cliente realizou o processo de cotação/reserva.

Coluna “Abriu cotação?”: Essa coluna tem a função de informar se o cliente realizou uma cotação durante a conversa com o robô. Quando o atendimento é automatizado (feito pelo Hbot) e o hóspede efetua uma cotação dentro do fluxo do robô, a coluna exibirá “Sim”, indicando que a cotação foi aberta diretamente pelo chatbot. Já quando o atendimento é realizado por um atendente humano, mesmo que o cliente tenha feito uma cotação manualmente durante a conversa, a coluna exibirá “Não” — pois esse registro não é contabilizado como cotação automática do robô.

* Sim - Cliente solicitou cotação e preencheu o formulário.
  Cliente respondeu o formulário com: data, quantidade de adultos e criança se houver, que são informações necessárias para fazer a contação, sem isso não é possível seguir.
* Não - Cliente não chegou a cotar, não respondeu o formulário com as informações para cotação.

**Quando marca "Sim":**

* Cliente usou intenção “Cotação” e respondeu o formulário enviado pelo robô.
* Cliente perguntou sobre disponibilidade e respondeu o formulário enviado pelo robô.
* Cliente solicitou preços e respondeu o formulário enviado pelo robô.

**Quando marca "Não":**

* Cliente apenas fez perguntas gerais
* Cliente solicitou informações
* Cliente pediu atendimento humano direto
* Conversa foi abandonada antes da cotação
* Cliente não respondeu o formulário enviado pelo bot sobre a cotação.
* Apenas automação do bot (aviso de reserva concluída, cancelada, check-in e checkout)

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hbot_-_Contatos_image3_b8dae9f7.png)

**11.Tags:**

Categoriza e segmenta contatos por características ou comportamentos.

É possível identificar cotações feitas durante atendimentos humanos por meio das tags.

Essas tags podem ser:

Inseridas manualmente pelo atendente, conforme o andamento da conversa; ou

Geradas automaticamente pelo sistema, quando o atendente envia uma cotação manual ao cliente dentro do chat.

**Como tags são aplicadas:**

* Automaticamente pelo bot (configurado nas intenções)
* Manualmente por atendentes humanos
* Por ações do cliente (realizar cotação, reservar, cancelar)

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hbot_-_Contatos_imagef_ac4cdbb9.png)

### **12. Exemplo prático**

Imagine o seguinte cenário na sua tela de contatos:

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| **Nome do Cliente** | **Canal** | **Data do Primeiro Contato** | **Abriu cotação?** | **Tags** |
| **Maria Fernandes** | WhatsApp | 08/11/2025 | **Não** | **cotação** |

**Nesse exemplo**:

* Na coluna **“Abriu cotação?”** aparece **“Não”**, pois **a cotação não foi feita pelo robô** (ou seja, não foi gerada automaticamente durante o fluxo do chatbot).
* No entanto, na coluna **“Tags”** aparece a **tag “cotação”**, indicando que **durante o atendimento humano**, o atendente enviou manualmente uma proposta de cotação ao cliente.

**Essa tag pode ter sido:**

* **Adicionada automaticamente** pelo sistema, quando o atendente enviou a cotação; ou
* **Inserida manualmente** pelo atendente, para registrar que houve uma cotação durante a conversa.

Assim, mesmo que o campo **“Abriu cotação?”** esteja como “Não”, você ainda consegue identificar que o cliente **recebeu uma proposta de reserva** — apenas por meio do **atendimento humano**, e não via automação do robô.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hbot_-_Contatos_image_418fac5a.png)

**13. Ver conversa:**

Abre o histórico completo da conversa com o cliente na tela de Chat Online com o histórico completo da interação selecionada, permitindo revisar mensagens, analisar contexto etc.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hbot_-_Contatos_image5_a970fd97.png)

Menu lateral esquerdo tem o botão "VER TODAS AS CONVERSAS" retorna à lista completa de conversas do Chat Online.

* Sair da visualização individual
* Navegar entre diferentes conversas
* Voltar para gerenciar múltiplos atendimentos

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hbot_-_Contatos_image6_6ed93475.png)

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hbot_-_Contatos_imagec_7d9db0fd.png)

### **14. Ordenação de colunas**

Na tela de **Contatos**, você pode **organizar as informações** clicando nos títulos de algumas colunas. Isso facilita localizar registros específicos ou analisar os dados de forma mais rápida e prática.

As colunas que permitem ordenação são:

* **Criação**
* **Canal**
* **Nome**
* **E-mail**
* **Telefone**
* **Abriu cotação?**

**Como funciona:**
 Ao clicar no cabeçalho de uma dessas colunas, o sistema alterna automaticamente a ordem de exibição dos resultados.

* Para colunas de **data** (**Criação**) e **telefone**:
  + O primeiro clique exibe os **mais recentes primeiro** (ordem **descendente**).
  + O segundo clique inverte para **mais antigos primeiro** (ordem **ascendente**).
* Para colunas **alfabéticas** (**Canal**, **Nome, abriu cotação** e **E-mail**):
  + O primeiro clique organiza em **ordem alfabética crescente (A–Z)**.
  + O segundo clique inverte para **ordem alfabética decrescente (Z–A)**.

**15. Exemplo prático:**
 Se você clicar sobre **“Nome”**, a lista será organizada de **A a Z**. Clicando novamente, os nomes serão exibidos de **Z a A**.
 Já ao clicar em **“Criação”**, os contatos mais recentes aparecerão no topo, e ao clicar novamente, os mais antigos virão primeiro.

Essa funcionalidade é ideal para quando você precisa revisar contatos mais novos, ou localizar um cliente específico rapidamente dentro da sua base.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hbot_-_Contatos_image12_348f9ab2.png)

Glossário

|  |  |
| --- | --- |
| **Termo** | **O que significa** |
| **HBot** | O sistema de chatbot e atendimento por onde seus clientes conversam |
| **Lead/Contato** | Qualquer pessoa que iniciou uma conversa ou demonstrou interesse no seu hotel |
| **Canal** | O meio por onde cliente te chamou (WhatsApp ou o chat do site) |
| **Cotação** | Quando o cliente pergunta o preço e a disponibilidade para uma data específica. |
| **Tags** | Etiquetas usadas para categorizar os contatos (ex. Cotação) |
| **Exportar** | Atro de baixar as informações do sistema para um arquivo no seu computador. |
| **Ordem Ascendente** | Organização que vai do menor para o maior (de A a Z, ou do mais antigo para o novo). |
| **Ordem Descendente** | Organização que vai do maior para o menor (de Z a A, ou do mais novo para o antigo). |