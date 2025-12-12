### **Como criar pacotes sazonais usando restrições (Natal, Ano Novo, Feriados e Eventos)**

Se você deseja vender pacotes completos para períodos especiais, como **Natal, Ano Novo, feriados prolongados ou eventos**, é possível configurar pelo **Hunit**, utilizando **restrições de chegada, saída e estadia mínima**. Essas configurações garantem que os hóspedes reservem o pacote completo, evitando check-ins ou checkouts fora das datas desejadas.

### **🚀 Onde configurar o pacote?**

As configurações devem ser feitas **na tela de Atualizações**, onde você envia as restrições e valores para o sistema e canais.

Acesse:
 **Menu superior → Atualizações → Atualizações**

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_143158_8dd4/images/Como_criar_pacotes_s_image2_9c43b508.png)

### **Selecione o período antes de aplicar as restrições**

Na **parte superior esquerda da tela**, selecione:

🗓️ As **datas do pacote** (início e fim desejados para o pacote)

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_143158_8dd4/images/Como_criar_pacotes_s_image5_efb92cf9.png)

### **Ordem recomendada para configurar o pacote**

Para evitar falhas ou conflitos na atualização, **recomenda-se fazer em etapas**, nesta ordem:

1️⃣ **Primeiro: Estadia mínima (Min Stay)**
 – Lançar apenas a regra de estadia mínima para exigir a quantidade mínima de noites do pacote.

2️⃣ **Depois: Fechamento de chegada (Bloqueio de Check-in)**
 – Aplicar as datas em que o hóspede **não pode iniciar a reserva**.

3️⃣ **Por último: Fechamento de saída (Bloqueio de Checkout)**
 – Aplicar as datas em que o hóspede **não pode finalizar a reserva**.

⚠️ **Importante:**

* O ideal é **fazer cada restrição em lançamentos separados**, um por vez.
* **Somente quando os fechamentos de chegada e saída forem exatamente nas mesmas datas**, é possível atualizar os dois juntos no mesmo lançamento.

Você pode aplicar as seguintes configurações:

#### **✔️ Estadia mínima (Min Stay)**

Define o número mínimo de noites que o hóspede deve ficar.

Exemplo: Pacote de Natal com 3 noites (Check-in 24 e Checkout 27)
 Configure **Estadia mínima = 3 noites**

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_143158_8dd4/images/Como_criar_pacotes_s_image6_b38db945.png)

#### **✔️ Fechamento de Chegada (Bloqueio de Check-in)**

Impede que o hóspede inicie a estadia em datas fora do pacote.

Exemplo: Pacote de Ano Novo com Check-in apenas dia 28/12
 Bloqueie chegada nos dias 29, 30, 31 e 01.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_143158_8dd4/images/Como_criar_pacotes_s_image_f4d81291.png)

#### **✔️ Fechamento de Saída (Bloqueio de Checkout)**

Impede que o hóspede faça o checkout antes do final do pacote.

Exemplo: Para garantir hospedagem até 02/01
 Bloqueie saída nos dias 29, 30, 31 e 01.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_143158_8dd4/images/Como_criar_pacotes_s_image3_2b7cd913.png)

### **🧾 Exemplo prático – Pacote de Ano Novo (28/12 a 02/01)**

|  |  |
| --- | --- |
| **Data** | **Configuração** |
| 28/12 | Check-in permitido / Estadia mínima = 5 noites |
| 29/12 | Bloquear chegada e saída (C / S) |
| 30/12 | Bloquear chegada e saída (C / S) |
| 31/12 | Bloquear chegada e saída (C / S) |
| 01/01 | Bloquear chegada e saída (C / S) |
| 02/01 | Saída permitida (Checkout) |

### **Selecione os canais que irão receber a atualização**

Após inserir as restrições:

✔️ Vá até a **parte inferior da tela**
✔️ Marque os **canais de vendas (Booking, Expedia, Airbnb, Decolar...)** que devem receber essa atualização
✔️ Clique em **Atualizar** para enviar os dados, no canto inferior direito.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_143158_8dd4/images/Como_criar_pacotes_s_image4_23dfc857.png)

Sem essa etapa, a configuração não será enviada para os canais.

### **Como verificar se está configurado corretamente?**

Após enviar a atualização, acesse a tela para confirmar se as informações estão sendo enviadas corretamente aos canais:

**Menu Calendários → Grade de informações**

1️⃣ Busque a **data do pacote** (canto superior direito)
 2️⃣ Selecione o **canal e a categoria**
 3️⃣ Clique para **carregar a grade**

Verifique:

✔ Se os preços estão preenchidos
 ✔ Se as restrições aplicadas (C / S / Estadia mínima) aparecem conforme configurado
 ✔ Se não está mostrando stop de venda (preço em vermelho) ou valor “-” (sem tarifa configurada)

### **🕒 Também é possível acompanhar o envio**

Acesse:

**Menu superior → Atualizações → Relatório de atualizações**

* 📗 **Sucesso**: canal já recebeu a informação
* 🔄 **Em processamento**: aguarde o canal aceitar
* ❌ **Bloqueado**: será necessário acionar o suporte