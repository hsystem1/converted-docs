# **Grade de Informações – Calendário Hunit**

## **O que é a Grade de Informações**

A **Grade de Informações** é uma tela localizada dentro do módulo **Calendário** do sistema **Hunit**. Ela foi criada para permitir que o hoteleiro **acompanhe todas as informações que foram atualizadas e enviadas para os canais de venda**, como tarifas, disponibilidade de quartos e restrições.

Essa tela funciona como um painel completo de conferência. Diferente da **Grade de Informações (Nova)**, aqui **não é necessário selecionar previamente quais canais deseja visualizar**. A Grade de Informações já apresenta, em formato de lista, **todos os canais que o hotel possui conectados ao channel manager**.

Apesar dessa diferença de visualização, **ambas as telas têm a mesma finalidade**: garantir que o usuário consiga verificar e analisar o que está sendo praticado em cada canal de venda.

## **Onde localizar a Grade de Informações no sistema**

Para acessar essa tela no Hunit, siga o caminho abaixo:

**Menu superior → Calendário → Grade de Informações**

Ao clicar nessa opção, o sistema abrirá diretamente o calendário, já carregando a lista com todos os canais conectados.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_165429_a306/images/Hunit_-_Calendario_-_image_1ff80e2c.png)

## **Para que serve a Grade de Informações**

A Grade de Informações tem como principal objetivo **permitir o acompanhamento e a conferência das informações enviadas aos canais**.

Por meio dessa tela, o hoteleiro consegue:

* Conferir tarifas publicadas em cada canal
* Verificar a disponibilidade de quartos por data
* Identificar restrições aplicadas
* Confirmar se as atualizações realizadas foram corretamente processadas

Ela é uma tela essencial para o controle operacional do hotel.

## **Como funciona a visualização da Grade de Informações**

Ao acessar a tela, o usuário visualiza um calendário organizado por datas.

* Cada **coluna** representa um dia
* Cada **linha** representa uma categoria e tarifa
* Os **canais aparecem listados**, permitindo visualizar as informações enviadas para cada um deles

Nessa grade, são exibidos:

* Valores (tarifas)
* Disponibilidade
* Indicadores de restrições

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_165429_a306/images/Hunit_-_Calendario_-_image2_34cd898e.png)

## **Como interpretar as informações exibidas**

### **Fundo branco – Venda aberta**

Quando as células aparecem com fundo branco, significa que:

* A venda está aberta
* Existe disponibilidade
* O canal está apto a receber reservas

### **Fundo vermelho – Venda fechada**

O fundo vermelho indica que a venda está fechada naquela data. Isso pode ocorrer quando:

* A disponibilidade está zerada (valor 0)
* A venda foi fechada manualmente

Para entender o motivo exato, o usuário pode clicar sobre o valor e consultar o histórico de atualizações.

### **Triângulo amarelo – Existência de restrições**

O triângulo amarelo indica que existe alguma restrição aplicada naquela data.

Para visualizar o detalhe:

1. Clique no botão **Exibir Restrições** no menu superior
2. Uma linha adicional aparecerá abaixo dos valores

Os tipos de restrição podem ser:

* **Número**: indica estadia mínima (ex.: 2 = mínimo de 2 noites)
* **C**: fechamento de chegada (não permite check-in)
* **S**: fechamento de saída (não permite checkout)

## **Menu superior da Grade de Informações**

Na parte superior da tela, o usuário encontra ações importantes para conferência e controle.

### **Exibir Restrições**

Permite mostrar ou ocultar as restrições aplicadas no calendário.

**Quando utilizar:** sempre que houver um triângulo amarelo visível na grade.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_165429_a306/images/Hunit_-_Calendario_-_image3_c0b8c8cd.png)

### **Imprimir**

Gera um arquivo para impressão com exatamente as informações exibidas na tela.

Essa opção é útil para auditoria, conferência manual ou controle interno.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_165429_a306/images/Hunit_-_Calendario_-_image5_af88aed8.png)

### **Carregar Grade**

Sempre que o calendário é aberto, as informações podem aparecer em branco.

Isso é um comportamento padrão do sistema.

Ao clicar em **Carregar Grade**, o Hunit busca e exibe as informações atualizadas dos canais conectados.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_27_165429_a306/images/Hunit_-_Calendario_-_image4_e92e394c.png)

## **Quando utilizar a Grade de Informações**

A Grade de Informações deve ser utilizada sempre que o hoteleiro precisar:

* Conferir se tarifas e disponibilidades foram corretamente enviadas aos canais
* Acompanhar informações de todos os canais ao mesmo tempo
* Identificar divergências entre canais
* Validar atualizações recentes

Ela é especialmente indicada para uma **visão geral e conferência operacional diária**.

## **Glossário**

|  |  |
| --- | --- |
| **Termo** | **Descrição** |
| **Calendário** | Módulo do Hunit onde são gerenciadas tarifas, disponibilidades e restrições. |
| **Canal de venda** | Plataforma onde as diárias são comercializadas (Booking, Expedia, entre outros). |
| **Channel Manager** | Sistema que centraliza a distribuição das informações do hotel para os canais de venda. |
| **Categoria** | Tipo de acomodação do hotel. |
| **Disponibilidade** | Quantidade de quartos disponíveis para venda. |
| **Grade de Informações** | Tela do Hunit que exibe, em lista, todos os canais conectados e suas respectivas informações. |
| **Restrição** | Regra que limita vendas, como estadia mínima ou bloqueio de chegada e/ou saída. |