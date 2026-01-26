**Atualizações para Hoteisnet - HCORP**

**Sobre atualizações para Hoteisnet**

A **Página de Atualizações** é o centro de controle para envio de informações tarifárias e de disponibilidade para todos os canais de distribuição conectados ao sistema. É através desta página que o hotel mantém seus canais atualizados em tempo real.

**Objetivo da Funcionalidade**

Centralizar o envio de tarifas, disponibilidade e restrições para todos os canais de distribuição conectados ao hotel, garantindo sincronização automática em tempo real e eliminando erros de atualização manual.

**Casos de Uso**

**Por que usar essa funcionalidade?**

**A Página de Atualizações é dedicada ao envio de informações para os canais de distribuição. Através dela, é possível enviar:**

* Valor
* Disponibilidade **(caso não tenha PMS)**
* Estadia mínima
* Restrição de chegada
* Restrição de saída
* Fechamento de vendas

**Acesso à Funcionalidade**

**Navegação no sistema**

**Caminho:**
 **Menu → Atualizações → Atualizações**

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hcorp_-_Atualizaçõ_image2_9146a645.png)

**Opções de Configuração**

**Opção 1:** Período para ser atualizado

* Na página de atualizações a propriedade pode selecionar o período e os dias da semana para lançar atualizações.
* Podendo selecionar diferente agrupamento de dias ao clicar no sinal de **+ (Novo período)**

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hcorp_-_Atualizaçõ_image4_454a2a3b.png)

**Opção 2:** Tela de atualização

* As **atualizações** são definidas através das linhas criadas no **HUNIT** a qual representa na coluna **Tipos de Quarto**, todas as linhas de quartos criadas.
* **Para o envio de restrições** é importante que seja enviado **somente na linha principal**. As restrições não são aplicadas na categoria quando enviadas nas linhas secundárias de cada tarifa.
* Na tela de **atualizações** é possível também enviar **atualizações** para canais específicos ou enviar para todos ao mesmo tempo selecionando todos os canais na parte inferior da página.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hcorp_-_Atualizaçõ_image_f06ca688.png)

**Opção 3:** Selecionar o(s) Canal(is)

* Na seção **CANAIS**, identifique os canais de venda (OTAs) listados: BOOKING, EHTL, EXPEDIA, HBOOK, MITS, HOSTELWORLDDIRECT, **HOTEISNET**, RESTEL.
* **Marque a caixa de seleção** ao lado de cada **canal (Exemplo: HoteisNet)** para o qual você deseja que a atualização urgente seja enviada **imediatamente**.
* Depois de selecionar os **canais** e a opção **"Aplicar Imediatamente"**, execute a ação de salvar ou enviar a atualização que você preparou na tela. **A atualização será forçada a sobrepor as pendências e ser enviada imediatamente ao canal selecionado HoteisNet**

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hcorp_-_Atualizaçõ_image3_571c83fd.png)

**Variáveis Disponíveis**

**O que atualiza:**

* **Disponibilidade:** O inventario de quartos abertos para vendas
* **Tarifas:** Os preços de venda
* **Restrições**: Regras de estadia mínima/máxima e de fechamento de check-in/out
* **Stop Venda:** Bloqueio total da venda para datas especificas.

# **GLOSSÁRIO**

### **Página de Atualizações**

Tela do sistema responsável pelo envio de tarifas, disponibilidade e restrições para os canais de distribuição.

### **Canal de Distribuição**

Plataforma onde o hotel vende suas tarifas, como OTAs, operadoras e integradores.

### **Tarifa**

Preço e condições comerciais configuradas para venda da hospedagem.

### **Disponibilidade**

Quantidade de quartos disponíveis para venda em uma determinada data.

### **Restrição**

Regra que limita ou condiciona a venda, como estadia mínima ou fechamento de chegada/saída.

### **Estadia Mínima**

Número mínimo de noites exigidas para que uma reserva seja aceita.

### **Restrição de Chegada (Check-in)**

Bloqueia a entrada de hóspedes em determinadas datas.

### **Restrição de Saída (Checkout)**

Bloqueia a saída de hóspedes em determinadas datas.

### **Stop Sale (Fechamento de Vendas)**

Bloqueio total da venda de quartos em datas específicas.

### **Linha Principal**

Linha base da categoria de quarto, onde as restrições devem ser aplicadas corretamente.

### **Linha Secundária**

Tarifa derivada da linha principal. Não deve ser usada para envio de restrições.