# **Derivação Tarifária (Preenchimento Automático de Valores)**

### **Entendendo o recurso e como solicitar a configuração**

## **1. O que é derivação tarifária?**

A derivação tarifária funciona como um vínculo entre duas tarifas. É criada uma relação em que **uma tarifa é a principal (tarifa base ou linha mãe)** e **a outra depende dela (tarifa derivada)**.
 Sempre que a tarifa base recebe uma atualização de valor, a derivada calcula automaticamente o seu próprio valor, conforme a regra definida.

Uma configuração que permite **preencher automaticamente** o valor de uma tarifa com base no valor de outra tarifa.

Funciona por meio de uma regra:

* Uma tarifa é definida como **tarifa base** (ou *linha mãe*).
* Outra tarifa é definida como **tarifa derivada** (recebe o cálculo automático).

Sempre que a tarifa base for atualizada, a tarifa derivada é calculada automaticamente conforme a regra definida.

Nem sempre o termo “derivação tarifária” é conhecido por todos, mas se a necessidade é algo como:

* “Quero preencher valor apenas em uma linha e as outras completarem automaticamente.”
* “Quando eu lançar o preço da categoria principal, outra precisa atualizar junto.”
* “Consigo colocar uma regra para uma tarifa seguir outra automaticamente?”

## **2. Onde esse preenchimento automático é aplicado?**

A derivação normalmente é usada quando o usuário quer que a **tela de Atualizações de Preços** seja mais rápida e consistente.

Portanto, ao solicitar este tipo de automação, é importante confirmar se o objetivo é:

* Automatizar valores **na tela de Atualizações**,
   ou
* Manter tarifas sempre relacionadas dentro do próprio tarifário.

Isso garante que a configuração será feita no local correto.

## **Relação entre as tarifas (Base → Derivada)**

A derivação sempre tem duas partes:

* **Tarifa Base (Linha Mãe):**
   É a tarifa que você realmente preenche na tela de Atualizações.
   Essa tarifa recebe o valor manualmente.
* **Tarifa Derivada:**
   É a tarifa que recebe o valor automaticamente.
   Ela não precisa (e não deve) ser preenchida manualmente porque depende da base.

## **A regra da derivação (o cálculo)**

A regra determina **como** a derivada será calculada a partir da base.
 A regra pode ser:

* **Valor percentual**
   (ex.: 5%, 10%, 15%)
* **Valor absoluto (fixo)**
   (ex.: R$ 10,00, R$ 20,00)
* E sempre precisa indicar se é:
  + **Mais barata** que a base
  + **Mais cara** que a base

### **Exemplos de regra**

* *NR é 5% mais barata que reembolsável*
* *Categoria luxo 2 pax é 150 reais mais cara que a Standart 2 pax*

## **3. Aplicação automática do cálculo**

Quando você atualiza o valor da tarifa base na tela de Atualizações, o sistema faz o seguinte:

1. Lê o valor digitado na tarifa base.
2. Aplica a regra matemática definida.
3. Preenche automaticamente a tarifa derivada.

### **Exemplo real de cálculo (percentual):**

Regra:
 NR = 5% mais barata que a Reembolsável

Se você lança na tela:

* Reembolsável = R$ 500

O sistema aplica a regra:
 5% de R$ 500 = R$ 25
 500 – 25 = **R$ 475**

Então a tarifa NR automaticamente receberá **R$ 475**.

## **4. Comportamento das tarifas na tela de Atualizações de Preços**

### **✔ Tarifa Base (Linha Mãe)**

* Fica **ativa** para edição.
* O usuário digita o valor normalmente.

### **✔ Tarifa Derivada (Linha que recebe valor automático)**

* **Fica em cinza** na tela.
* **Não é possível editar manualmente**.
* O campo fica bloqueado para garantir que o valor siga a regra e não seja alterado por engano.
* Qualquer atualização na base reflete automaticamente nela.

Esse comportamento é intencional e evita:

* Valores inconsistentes
* Erros manuais
* Tarifas derivadas fora da regra configurada

### **❗ Se o cliente precisar editar manualmente**

Será necessário **remover a derivação** dessa tarifa.
 Após a remoção:

* A linha deixa de ficar cinza
* Volta a ser editável manualmente
* Os valores deixam de ser automáticos

## **5. Como saber se uma tarifa tem derivação configurada?**

* Ela aparece **em cinza** na tela de Atualizações.
* Não permite digitar valores.
* Quando você tenta clicar, o sistema não abre o campo.
* O valor muda sozinho de acordo com a tarifa mãe.

## **6. Informações necessárias para configurar a derivação**

Para que a derivação seja configurada corretamente, é necessário coletar algumas informações essenciais.
 Abaixo está a lista completa do que precisa ser informado:

### **a) Tarifa Base (Linha Mãe)**

É a tarifa que será atualizada manualmente por você.
 A partir dela, todas as derivadas são calculadas.

### **b) Tarifa Derivada**

É a tarifa que receberá o cálculo automático.
 Sempre seguirá a tarifa base conforme a regra definida.

### **c) Tipo de derivação**

A regra pode ser aplicada de dois modos:

* **Percentual** → ex.: 5%, 10%, 15%
* **Valor absoluto** → ex.: R$ 10,00, R$ 20,00

### **d) Valor da regra**

É o número exato a ser aplicado.

Exemplos:

* 5%
* 15%
* R$ 20,00
* R$ 50,00

### **e) Direção da regra: Mais ou Menos**

Indica se a tarifa derivada ficará:

* **Mais barata** que a tarifa base
   (ex.: NR 5% mais barata que a Reembolsável)
* **Mais cara** que a tarifa base
   (ex.: tarifa de feriado 10% mais cara que o BAR)

Esta informação é indispensável para evitar valores invertidos.

## **7. Modelo de coleta de dados**

Para facilitar, abaixo está o formato ideal para organizar as informações necessárias:

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| **Tarifa Base** | **Tarifa Derivada** | **Tipo** | **Valor** | **Direção (Mais/Menos)** |
| STANDARD (2 PAX) | STANDARD (2 PAX) NR | Percentual | 5% | Menos |
| Suite Familia 2 pax | Suite Familia 1 pax | Valor | R$ 20,00 | Menos |
| luxo piscina 2 pax | luxo piscina 3 pax | Percentual | 10% | Mais |

**Importante:**
**O ideal é que você envie o nome exato da tarifa exatamente como aparece no Hunit**, sem abreviações ou adaptações. Nome da tarifa Base (Linha Mãe) e Tarifa Derivada.
Isso evita erro de identificação e garante que a derivação seja aplicada na linha correta.

# **Informações Importantes Sobre a Derivação Tarifária**

Antes de configurar ou solicitar uma derivação, é fundamental entender alguns pontos que evitam erros, expectativas incorretas ou solicitações que o sistema não suporta. Abaixo estão as regras gerais e limitações do recurso:

## **1. A derivação não é aplicada a um canal específico**

A derivação **não funciona por canal**, como Booking, Expedia, motor ou qualquer outro.

➡ **A derivação é configurada diretamente nas tarifas do sistema e reflete na tela de Atualizações como um todo.**

Isso significa:

* A tarifa derivada sempre seguirá a tarifa base.
* Qualquer atualização feita será enviada para todos os canais selecionados que recebem aquela tarifa.
* Não existe “derivar só para um canal”.

## **2. A derivação é aplicada de forma global (não depende de datas específicas)**

Outro ponto essencial:

➡ **A derivação não pode ser configurada por período.**

Ou seja:

* Não é possível derivar “somente em janeiro”, ou “só nos finais de semana”, ou “apenas em alta temporada”.
* A regra configurada vale **todos os dias**, para **todos os lançamentos**, sempre que a tarifa base for atualizada.

A derivação é um vínculo contínuo entre duas tarifas.