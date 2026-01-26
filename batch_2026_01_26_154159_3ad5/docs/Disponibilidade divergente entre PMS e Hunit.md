### **Disponibilidade divergente entre PMS e Hunit**

## **1. Sobre divergência de informações entre PMS e Hunit (channel)**

Há **disponibilidade no PMS**, mas essa informação **não está refletindo no HUNIT**.

Nesses casos, existem algumas verificações que você mesmo pode realizar antes de solicitar análise ao suporte.

Este guia vai ajudar você a identificar a causa do problema e reunir as informações necessárias para uma análise completa.

## **2. Verificação 1: Conferir a Disponibilidade no HUNIT**

Primeiro, você precisa confirmar que realmente há divergência entre os sistemas.

### **Passo 1: Acessar a Grade de Disponibilidade**

Acesse o **HUNIT** e siga os passos:

1. No menu, clique em **Calendários**
2. Depois clique em **Grade de disponibilidade**

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_154159_3ad5/images/Disponibilidade_dive_image_4e21f1db.png)

### **Passo 2: Verificar a Disponibilidade**

Verifique se a categoria realmente aparece com disponibilidade na data desejada.

**Perguntas a responder:**

* A categoria aparece na grade?
* Qual é o número de disponibilidade mostrado?
* Está zerada ou negativa?

### **Passo 3: Ação Se Não Aparecer Disponível**

Se **não aparecer disponível** no HUNIT:

Confirme com seu PMS se ele pode **reenviar a disponibilidade** para o HUNIT.

**Como fazer:**

* Entre em contato com o suporte do seu PMS
* Solicite o reenvio da disponibilidade para a categoria e data específicas
* Aguarde alguns minutos e verifique novamente no HUNIT

## **3. Verificação 2: Avaliar Limitações do PMS**

Entre em contato com o suporte do seu PMS e confirme os seguintes pontos:

### **Pergunta 1: Existe Limitador de Envio?**

Verifique se existe **limitador de envio de disponibilidade**, como porcentagem ou quantidade limitada para venda online.

**O que isso significa:**

Alguns PMS têm configurações que limitam quantos quartos podem ser vendidos online. Por exemplo:

* Apenas 80% da disponibilidade é enviada aos canais
* Máximo de 5 quartos por categoria para venda online
* Reserva de quartos para venda direta

**Se houver limitador:**

Isso pode explicar por que a disponibilidade no HUNIT é menor do que no PMS.

### **Pergunta 2: Há Bloqueio de Data ou Restrição?**

Verifique se há algum **bloqueio de data ou restrição** no PMS que impede o envio da disponibilidade.

**Exemplos de bloqueios:**

* Data marcada como "fechada para vendas online"
* Restrição de canal específico
* Bloqueio temporário por manutenção

### **Pergunta 3: O PMS Está Enviando Corretamente?**

Confirme se o PMS está **enviando corretamente as informações para o HUNIT**.

**O que verificar:**

* O PMS confirma que está enviando?
* Há algum erro nos logs de envio?
* A integração está ativa?

### **Passo Importante: Solicitar Logs**

Caso o PMS confirme que está enviando, peça os **logs de envio da categoria e da data**.

**Por que os logs são importantes:**

Os logs mostram exatamente o que foi enviado pelo PMS ao HUNIT, incluindo:

* Data e hora do envio
* Quantidade enviada
* Código da categoria
* Status do envio (sucesso ou erro)

Esses logs serão essenciais para o suporte do HUNIT analisar o problema.

## **4. Verificação 3: Confirmar o Código de Integração**

A comunicação com PMS utiliza **códigos específicos da categoria** (também chamado de ID de integração).

### **O Que É o Código de Integração**

É um código único que identifica cada categoria na comunicação entre o PMS e o HUNIT.

**Exemplos:**

* STD (Standard)
* LUX (Luxo)
* 12345 (código numérico)

### **Por Que Isso É Importante**

Se o código de integração estiver errado ou inconsistente, a disponibilidade pode estar sendo enviada para a categoria errada.

### **Como Verificar**

Se possível, verifique com seu PMS:

Qual é o **código de integração da categoria** em questão?

Esse código ajuda o suporte do channel manager a confirmar se a disponibilidade está sendo enviada corretamente para a categoria correspondente.

## **5. Informações Para Enviar ao Suporte**

Após verificar todos os pontos acima, se ainda houver divergência, envie as seguintes informações para análise do suporte:

### **Informação 1: Nome do PMS**

Informe qual PMS você utiliza.

**Exemplos:**

* Desbravador
* Newhotel
* Hits
* Hospedin
* Outros

### **Informação 2: Categoria Afetada**

Informe o nome da categoria com problema de disponibilidade.

**Exemplos:**

* Standard
* Superior
* Luxo
* Suíte Premium

### **Informação 3: Código de Integração**

Se tiver, informe o código de integração dessa categoria.

**Exemplos:**

* STD
* LUX
* 13253
* SUITE\_PREM

### **Informação 4: Data ou Período**

Informe a data ou período específico da divergência.

**Exemplos:**

* 12/03/2025
* 12/03 a 15/03
* Todo o mês de abril/2025

### **Informação 5: Reenvio Solicitado**

Informe se já solicitou reenvio da disponibilidade ao PMS.

**Resposta:** Sim / Não

**Se sim, informe:**

* Quando solicitou
* Se o PMS confirmou o reenvio
* Se houve alguma mudança após o reenvio

### **Informação 6: Logs do PMS**

Informe se possui os logs de envio do PMS.

**Resposta:** Sim / Não

**Se sim:** Anexe os logs ao e-mail para o suporte.

### **Informação 7: Disponibilidade no PMS**

Informe como está a disponibilidade no PMS.

**Formas de informar:**

* Print da tela
* Valor numérico (exemplo: 5 quartos disponíveis)
* Quantidade exata

### **Informação 8: Disponibilidade no HUNIT**

Informe como está a disponibilidade no HUNIT.

**Formas de informar:**

* Print da grade de disponibilidade
* Valor numérico (exemplo: 0 quartos disponíveis)
* Quantidade exata

## **6. O Que o Suporte Fará**

Após receber todas as informações, o suporte irá:

### **Etapa 1: Análise dos Logs**

Verificar os logs de recebimento no HUNIT para confirmar se a disponibilidade foi enviada pelo PMS.

### **Etapa 2: Verificação do Código**

Conferir se o código de integração está correto e se a disponibilidade está sendo direcionada para a categoria certa.

### **Etapa 3: Análise de Restrições**

Verificar se há restrições ou configurações no HUNIT que estejam bloqueando a atualização.

### **Etapa 4: Contato com PMS (se necessário)**

Se identificar problema na comunicação, o suporte pode entrar em contato com o PMS para resolver.

### **Etapa 5: Correção**

Implementar a correção necessária e validar se a disponibilidade foi normalizada.

### **Etapa 6: Retorno**

Informar você sobre a causa do problema e a solução aplicada.

## **Glossário de Termos**

|  |  |
| --- | --- |
| **Termo** | **Definição** |
| **PMS** | Property Management System. Sistema de gestão interna do hotel que controla reservas, check-in, checkout e disponibilidade. |
| **HUNIT** | Sistema de channel manager da Hsystem que sincroniza disponibilidade e preços entre o PMS e os canais de venda. |
| **Disponibilidade** | Quantidade de quartos livres disponíveis para venda em uma data específica. |
| **Divergência** | Diferença entre a disponibilidade mostrada no PMS e a mostrada no HUNIT. |
| **Grade de Disponibilidade** | Visualização no HUNIT que mostra a disponibilidade de todas as categorias por período. |
| **Categoria** | Tipo de acomodação (Quarto Standard, Suíte Premium, etc.). |
| **Código de Integração** | Identificador único usado na comunicação entre PMS e HUNIT para cada categoria. |
| **ID de Integração** | Mesmo que código de integração. |
| **Logs de Envio** | Registro de todas as informações enviadas pelo PMS ao HUNIT, com data, hora e status. |
| **Reenvio** | Processo de enviar novamente a disponibilidade do PMS para o HUNIT. |
| **Limitador de Envio** | Configuração no PMS que limita quantos quartos são enviados para venda online. |
| **Bloqueio de Data** | Configuração que impede o envio de disponibilidade para datas específicas. |
| **Integração** | Conexão automática entre PMS e HUNIT para troca de informações. |
| **Sincronização** | Processo de manter as informações iguais em ambos os sistemas. |