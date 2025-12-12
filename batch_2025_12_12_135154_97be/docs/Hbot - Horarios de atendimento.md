Documentação: horários de atendimento

Visão geral

Este documento descreve o processo de utilização e gerenciamento da aba de horarios de atendimento no sistema HBot (Chatbot e atendimento multicanal).

**Objetivo da funcionalidade**

Esta é a área onde você ajusta o horário comercial da sua propriedade e define as regras para desligamento automático do robô de atendimento.

Caminho: Menu superior → Propriedade → Horários de atendimento

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hbot_-_Horarios_de_a_image5_f7a9228b.png)

Nesta primeira seção, você configura o horário oficial de funcionamento da sua propriedade.

**Possui intervalo?**

Logo no topo, aparece uma chave seletora.

* Quando ativada, habilita os campos para configurar horários com intervalo — ideal para empresas com pausa para almoço.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hbot_-_Horarios_de_a_imagea_4812a434.png)

### **Horário de entrada**

Aqui você define a hora em que o atendimento **começa**.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hbot_-_Horarios_de_a_imageb_adaa7c17.png)

### **Horário de Saida**

Aqui você define a hora em que o atendimento **termina**.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hbot_-_Horarios_de_a_image7_1b9801e0.png)

### **Horário de intervalo**

Caso tenha intervalo, insira:

* **Horário de intervalo** (início do intervalo)
* **Horário de retorno** (fim do intervalo)

Essa configuração ajuda o HBot a entender quando o atendimento humano está disponível.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hbot_-_Horarios_de_a_imagec_7771ad27.png)

# **Desligar o Robô Conforme Regra**

Essa segunda área é uma das mais importantes: aqui você define **quando o robô deve ser desligado automaticamente**, permitindo que o atendimento humano assuma ou que o sistema pause temporariamente.

### **Fuso Horário**

No topo desta seção você encontra uma lista de fusos.

Certifique-se de estar usando o fuso correto para evitar desencontros nos horários.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hbot_-_Horarios_de_a_image_c008df87.png)

## **Aba “Por Dia da Semana”**

Esta aba permite configurar horários específicos de desligamento do robô para cada dia da semana.

Você verá a lista:

* Domingo
* Segunda
* Terça
* Quarta
* Quinta
* Sexta
* Sábado

Cada dia possui uma chave seletora para ativar a configuração.

### **Exemplo:**

Apenas **Segunda** está ativado, e possui uma faixa de horário definida:

* **Das 09:00 até 10:00**

Isso significa que, toda segunda-feira, o robô será desligado nesse intervalo.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hbot_-_Horarios_de_a_imagee_bd5fd185.png)

Há também um **botão de +** para adicionar múltiplos períodos no mesmo dia, caso necessário.

Os demais dias aparecem desativados, aguardando configuração.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hbot_-_Horarios_de_a_image6_04c867d1.png)

Aba “Feriados / Dias Avulsos”

## **Visão Geral da Aba**

Logo ao entrar, você vê um aviso destacado em azul:

**“Essa regra sobrepõe a regra por dia da semana”**

Isso significa que, quando você cadastrar um feriado ou uma data específica, o HBot vai seguir **exatamente** o que você definir aqui, ignorando a configuração padrão daquele dia.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hbot_-_Horarios_de_a_image9_f74b2485.png)

# **Adicionando novas datas**

No canto direito da tela, você encontra um botão circular com o sinal **+**.

Ao clicar nele, uma nova linha de configuração é adicionada.

Você pode cadastrar **quantas datas desejar**, criando regras bem detalhadas para feriados nacionais, recessos, eventos internos ou qualquer exceção no atendimento.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hbot_-_Horarios_de_a_imaged_66090ada.png)

**Como cadastrar um feriado ou data avulsa**

Você verá uma lista de itens, cada um representando uma data configurada. Cada item possui:

### **Campo de Data**

Um espaço onde você escolhe, através do calendário, o dia desejado.![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hbot_-_Horarios_de_a_image2_215cdc84.png)

# **Escolher a ação para o robô**

Ao lado da data, há duas opções de comportamento:

### **Desligar robô**

Use quando você **não quer** que o robô atenda naquele dia.
 Ideal para feriados em que o atendimento está fechado ou será totalmente manual.

### **Ligar robô**

Use quando deseja **ativar** o robô naquele dia, mesmo que este não faça parte da rotina normal.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hbot_-_Horarios_de_a_image3_dfb9df2b.png)

# **Excluindo uma data**

Ao lado direito de cada linha, há o ícone de lixeira.
 Clicando nele, você **remove** aquela data da lista.

Isso é útil caso um feriado tenha sido cancelado, alterado, ou simplesmente se você cadastrou algo errado.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hbot_-_Horarios_de_a_image4_1e26492f.png)

Depois de ajustar todos os horários – seja no **Horário Comercial**, na seção de **Por dia da semana**, ou na aba **Feriados / Dias Avulsos** – ao fim da página tem o botão de Salvar.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hbot_-_Horarios_de_a_image8_f2219327.png)

Metadados do Documento

|  |  |
| --- | --- |
| **Sistema:** | **HBot (Chatbot e atendimento multicanal)** |
| Módulo: | Propriedade |
| Funcionalidade: | Horários de atendimento |
| Data de referência: | 17/11/2025 |
| Tipo de documento: | Guia de utilização |