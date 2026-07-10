**Bloqueio de Processamento**

**O que é?** Quando uma atualização enviada aos canais não é aceita, o sistema registra um **bloqueio de processamento**. Isso significa que o canal retornou um erro informando que não foi possível aplicar aquela atualização — seja por configuração incorreta, divergência de dados ou política específica da OTA.

A tela de bloqueios apresenta todas as tentativas, mensagens de erro, possíveis soluções e o motivo exato retornado pelo canal.

# **Como o Bloqueio é Apresentado na Tela**

A estrutura da tela inclui:

* **Canal**
* **Número do pacote**
* **Quantidade de tentativas**
* **Quem fez a atualização**
* **Datas de requisição, envio e retorno**
* **Tabela com erros por tentativa**

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_07_10_165628_9c06/images/Bloqueio_de_Processa_image_749c4b5a.png)

# **Estrutura da Lista de Bloqueios**

Cada linha representa uma tentativa com falha e contém:

### **1️⃣ Nº do Envio**

Contagem de tentativas.

Tentativas que o Hunit fez de envio da atualização ao canal.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_07_10_165628_9c06/images/Bloqueio_de_Processa_image_749c4b5a.png)

### **2️⃣ Código do Erro**

Identifica o tipo de erro interno

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_07_10_165628_9c06/images/Bloqueio_de_Processa_image_749c4b5a.png)

### **3️⃣ Mensagem de Erro**

Descrição geral do problema encontrado.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_07_10_165628_9c06/images/Bloqueio_de_Processa_image_749c4b5a.png)

### **4️⃣ Solução para o Erro**

Sugestão de onde revisar (ex.: usuário e senha, configuração no canal, etc.).

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_07_10_165628_9c06/images/Bloqueio_de_Processa_image_749c4b5a.png)

### **5️⃣ Código do Canal**

Identificação interna da conexão.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_07_10_165628_9c06/images/Bloqueio_de_Processa_image_749c4b5a.png)

### **6️⃣ Mensagem do Canal**

A coluna mais importante:
Aqui aparece o **motivo** pelo qual o canal não aceitou a atualização.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_07_10_165628_9c06/images/Bloqueio_de_Processa_image_749c4b5a.png)

# **Exemplos de Motivos Comuns de Bloqueio de Processamento**

Essa lista é extremamente útil para entender rapidamente o porquê do canal rejeitar uma atualização:

## **🔸 1. Valor acima ou abaixo do permitido**

Alguns canais trabalham com **contratos de valores** ou **margens de segurança**, que impedem que o hotel pratique preços:

* **acima do máximo permitido**, ou
* **abaixo do mínimo aceito**, conforme acordado com a OTA.

Quando o preço enviado ultrapassa o limite configurado na OTA, ela devolve erro, resultando em bloqueio de processamento.

**Exemplo de inicio de mensagem do canal:**
 “At least one rate exceeds maximum bound...”

**Como resolver:**

* Caso o valor enviado seja **incorreto**, você pode **editar o bloqueio** e ajustar o preço para dentro do permitido.
* Caso o valor enviado seja **o desejado**, o hotel deve **contatar o canal** e solicitar a alteração da margem contratada, para que o canal passe a aceitar esse novo valor.

## **🔸 2. Divergência de configuração entre o canal e o Hunit**

Isso inclui:

* Quantidade de adultos (pax) configurada no canal diferente do valor configurado no Hunit (ex.: Hunit envia 3 adultos, mas o canal aceita apenas 2).
* Alterações feitas direto no extranet **sem solicitar ajuste no channel**
* Tarifa alterada/excluída no canal sem atualizar no Hunit.

Essas divergências fazem com que o canal recuse a atualização por inconsistência de dados.

**Exemplo de mensagem do canal:**
 “The number of base guests informed (3) does not match the one for the room (2).”

## **3. Se o cliente não conseguir identificar o motivo do erro:**

Recomenda-se **acionar o suporte**, informando que precisa de ajuda com bloqueio de processamento.

## **️Atenção: Bloqueio de Processamento nas Atualizações**

**É muito importante destacar:** enquanto houver um bloqueio de processamento, **nenhuma atualização posterior será enviada ao canal**. Isso inclui tarifas, restrições e até disponibilidade. Dessa forma, existe o risco de o canal continuar vendendo períodos que já possam estar sem disponibilidade no sistema.