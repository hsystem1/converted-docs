**Cancelamento de Reservas Online**

**Reserva veio da internet? Cancele na internet!**

Nunca cancele no **PMS** uma reserva que veio da Booking, Expedia, Decolar ou qualquer site de reserva.

1.Onde a reserva foi feita = Onde deve ser cancelada

**Exemplo:**

* Reserva veio do Booking – Cancele na Booking
* Reserva veio da Expedia – Cancele na Expedia
* Reserva veio da Decolar – Cancele na Decolar
* Reserva foi feita direto no hotel – Pode cancelar no PMS sistema do Hotel

**Isso porque:**

* O **PMS só recebe** do channel **informações de reservas** (novas, modificadas e canceladas).
* O PMS **não envia** nenhum tipo de alteração ou cancelamento para o channel.
* O **canal** é quem considera a reserva como ativa ou cancelada.
* O **channel apenas repassa** para o PMS aquilo que o canal envia — ele não toma decisões.

2. **Como os sistemas se comunicam**

**Quando uma reserva é feita no canal:**

* **Hospede faz uma reserva no Booking**
* **Booking envia a informação para o Channel Manager (Hunit)**
* **Channel Manager repassa para o PMS (Hbook)**
* **PMS recebe e registra a reserva**

**Atenção:**

**O PMS apenas recebe informações do canal. Ele NÃO envia nada de volta.**

**Isso significa:**

* **Se você cancelar no PMS, o canal não fica sabendo**
* **O Booking vai continuar achando que a reserva está ativa**
* **O Channel Manager não vai avisar o Booking**

**3. Por que não cancelar no PMS**

O Canal é quem manda

* A reserva nasceu no canal (Booking, Expedia, etc.)
* O Canal é o dono ‘dessa’ reserva
* Só o canal pode decidir se a reserva está ativa ou cancelada
* O PMS apenas obedece ao que o canal manda

**4. O PMS não fala com o canal**

* O PMS não tem como avisar o canal sobre cancelamentos
* A comunicação é de mão única: Canal → Channel → PMS
* Não existe o caminho contrário: PMS → Channel → Canal

Por isso, cancelar uma reserva manualmente direto no PMS pode gerar **divergências**, inventário incorreto e até **overbooking**.

## **O que acontece ao cancelar uma reserva no PMS (de forma incorreta)?**

Ao cancelar diretamente no PMS:

* O PMS entende que aquela reserva não existe mais.
* Como consequência, **libera disponibilidade**.
* Exemplo: se a categoria estava com disponibilidade **0**, passa para **1**.

Mas:

* No **canal**, a reserva continua **ativa**, pois o cancelamento não foi feito por lá.
* O **channel não cancela a reserva**, pois não recebeu essa instrução do canal.
* Logo, cada sistema passa a ter uma informação diferente.

## **O que acontece quando o canal posteriormente envia o cancelamento oficial?**

Quando o cancelamento é finalmente feito corretamente no canal (ex.: Booking), este envia ao channel:

“Reserva X cancelada — liberado 1 de disponibilidade.”

O channel repassa ao PMS — mas:

* A reserva **já foi cancelada manualmente no PMS**.
* Então o PMS **não processa a informação**, pois entende que aquela reserva não existe mais como ativa.
* Logo, **não há liberação adicional de disponibilidade** no PMS, então o mesmo não corrigi a informação para o channel repassar ao canal.

Enquanto isso:

* **O canal**, mantem a disponibilidade que ele já tinha mais a do cancelamento da reserva.
* Como o PMS não responde com essa liberação (pois o cancelamento manual já gerou isso antes), cria-se uma **diferença de inventário**.

Resultado: **disponibilidade incorreta**, podendo levar a **overbooking** caso o canal venda com base no estoque que acredita estar liberado.

## **Exemplo prático**

### **Situação inicial:**

* Categoria "Luxo": disponibilidade = **0**
* Existe 1 reserva ativa na Booking.

### **O hotel cancela manualmente no PMS (ação incorreta):**

* PMS libera disponibilidade → fica **1**
* A reserva continua ativa na Booking.

### **O cancelamento é realizado no canal de origem (Exemplo: Booking):**

* Booking envia o cancelamento ao channel.
* O channel encaminha ao PMS.
* O PMS **não localiza mais a reserva ativa**, pois já não tem a reserva registrada para cancelar.
* O **PMS não envia nenhuma resposta ao channel** sobre a disponibilidade referente ao cancelamento desta reserva.

### **Resultado do inventário — como a divergência acontece**

Ao final desse processo, temos o seguinte cenário:

* O **PMS** ficou com **1** de disponibilidade, pois a reserva foi cancelada diretamente nele.
* O **canal** (ex.: Booking) já tinha **1** de disponibilidade, porque o PMS liberou quando o cancelamento foi feito de forma incorreta no próprio PMS.
* Depois, quando o cancelamento oficial foi feito no canal, o canal enviou ao channel a instrução para liberar disponibilidade **mais uma vez**.
* Como o PMS **não retornou confirmação**, já que a reserva nem existia mais no sistema dele, o canal **não recebeu a validação** e ainda assim contabilizou essa liberação.

**Inventário final:**

* PMS: **1**
* Canal: **2** (1 pelo cancelamento indevido feito no PMS + 1 pelo cancelamento oficial enviado sem retorno)

**Resultado:** divergência de disponibilidade entre PMS e canal, com risco real de **overbooking**.

## **Conclusão**

Para evitar inconsistências e proteger o inventário do hotel:

### **Reservas de origem online devem ser canceladas somente no canal onde foram criadas.**

Cancelar no PMS:

* libera disponibilidade indevidamente,
* impede o processamento correto do cancelamento oficial,
* causa divergência entre PMS e canal,
* aumenta o risco de **overbooking**.