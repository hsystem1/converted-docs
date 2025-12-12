# **Análise de Últimas Atualizações na Grade de Informações**

A tela de **Grade de Informações** (ou a grade de disponibilidade do canal) é a principal ferramenta que você possui para visualizar e confirmar o envio de dados para as operadoras ou **OTAs.** Tire dúvidas sobre **divergências** de preço ou **falha de restrição.**

## **CAMINHO DE ACESSO E FILTROS**

Siga o passo a passo abaixo para acessar a tela de análise de dados enviados, que exibe o último dado transmitido:

### **Navegação no Sistema**

**Caminho:** HUNIT > **CALENDÁRIOS** > **GRADE DE INFORMAÇÕES**

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_143158_8dd4/images/Case_-_Análise_de_H_image2_c2e83b06.png)

### **Filtros de Visualização (Topo da Tela)**

A utilização correta dos filtros é essencial para isolar o problema:

* **Seleção de Canal:** Clique na aba do canal específico (Ex: Booking, Expedia) você deve visualizar o canal exato onde ocorreu a divergência para validar o dado enviado.
* **Carregar todos os canais:** Use para uma checagem geral de todos os canais de forma consolidada.
* **Seleção da data:** Use o campo de calendário: Navegue diretamente para a data da reserva ou do preço incorreto para uma análise pontual.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_143158_8dd4/images/Case_-_Análise_de_H_image3_df761b7c.png)

## **ANÁLISE E INTERPRETAÇÃO DOS DADOS ENVIADOS**

A **seção da Grade de Informações é a "última palavra" do HUNIT**. Ela mostra o dado que foi efetivamente transmitido para o canal.

* **Dado Principal:** Se a célula está mostrando um preço (785, 1029), este é o valor da diária enviada. Se mostra um número pequeno (0,1, 2,), é a **disponibilidade.**

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_143158_8dd4/images/Case_-_Análise_de_H_image4_d622cdee.png)

* **Caixas em vermelho:** Data com Stop de venda ou com disponibilidade de venda zerado
* **Triangulo Amarelo (ou Número) na Restrição.** Restrição Ativa nesta data

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_143158_8dd4/images/Case_-_Análise_de_H_image_e24a325f.png)

### **Botões de Ação Rápida e Suas Funções**

Estes botões podem ser usados para tentar corrigir divergências antes de acionar o suporte.

* **Exibir Restrições:** Usado para **confirmar** se as regras (Min Nights, CTA) estão visíveis e ativas na data.
* **Carregar Grade:** Carrega a grade do canal
* **Calcular tarifas derivadas:** Usado se a tarifa derivada estiver incorreta, para garantir que o cálculo automático seja reprocessado.
* **Sincronizar com canal:** Usado quando a Grade mostra o dado CORRETO, mas o canal (OTA) não está refletindo.
* **Replicar Canal**: Uso em **configuração inicial** ou alinhamento completo de dados entre canais.

## **CHECKLIST PARA ESCALONAMENTO AO SUPORTE N2**

O suporte deve ser acionado apenas se a Grade de Informações confirmar que o HUNIT enviou o dado correto e o canal de venda (OTA) falhou em recebê-lo.

|  |  |  |
| --- | --- | --- |
| **Situação** | **Ação do cliente na Grade** | **Status para suporte** |
| Overbooking | A disponibilidade na grade está em 0?  A disponibilidade na grade está em >0 | **Sim:** O problema é na OTA. Abrir atendimento com suporte.  **Não:** O hunit enviou disponibilidade. Verifique gestão interna **(PMS/Extranet)** |
| Tarifa incorreta | O preço na grade está **correto**? | **SIM:** Tentar **Sincronizar Canal**. Se persistir, problema na OTA. Abrir ticket |
| Tarifa Incorreta | O preço na grade está **Errado/Vazio?** | **Não**: O dado não foi enviado corretamente. O cliente deve lançar a tarifa novamente |

## **⚠️ PONTO DE ATENÇÃO**

A solicitação de atendimento deve incluir **obrigatoriamente** o **Canal**, a **Data** e a **Categoria/Tarifa** afetada, além da **Confirmação** de que o dado correto está visível na Grade de Informações.