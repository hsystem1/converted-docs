# **HUNIT - Reservas**

# **Guia Completo da Tela de Reservas**

## **1. Sobre a tela de reservas no gestor de canais (Hunit)**

A tela de Reservas do HUNIT é o centro de controle de todas as suas vendas online. É aqui que você acompanha, em tempo real, cada reserva que chega dos canais de venda como Booking.com, Expedia, Airbnb e do seu próprio motor de reservas (HBOOK).

Imagine ter um painel único onde você pode ver quem reservou, quando reservou, por qual canal, qual tipo de quarto foi escolhido, quanto o cliente vai pagar e se essa reserva já foi integrada com o seu sistema de gestão interna. É exatamente isso que a tela de Reservas oferece: visibilidade total e controle completo sobre todas as suas vendas.

Neste guia, vamos explorar cada funcionalidade em detalhes, mostrando como você pode usar os filtros avançados para encontrar exatamente o que precisa, como interpretar cada informação apresentada e como exportar relatórios para análises mais profundas.

## **2. Como Acessar a Tela de Reservas**

Para acessar a tela de Reservas, é muito simples. Basta fazer login no sistema HUNIT e, no menu superior da tela, clicar na opção **Reservas**. Você será direcionado imediatamente para o painel principal de reservas.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hunit_-_Reservas_image2_733668f0.png)

## **3. Entendendo a Estrutura da Tela**

A tela de Reservas foi projetada para ser intuitiva e eficiente. Ela está dividida em duas áreas principais que trabalham juntas para facilitar sua busca e análise:

**A área de filtros**, localizada na parte superior da tela, é onde você define exatamente quais reservas deseja visualizar. Pense nela como um centro de comando onde você configura os critérios de busca. Quer ver apenas as reservas do Booking.com? Ou talvez apenas as reservas com check-in previsto para amanhã? Ou ainda, precisa identificar reservas que apresentaram erro ao integrar com seu PMS? Tudo isso é configurado nesta área.

**A área de resultados**, logo abaixo dos filtros, é onde as reservas aparecem em formato de tabela. Cada linha representa uma reserva e cada coluna traz uma informação específica: número da reserva, nome do hóspede, canal de origem, tipo de quarto reservado, datas, valores, status de integração e muito mais. É uma visão completa e organizada de todas as informações que você precisa.

Vamos explorar cada uma dessas áreas em detalhes para que você possa aproveitar todo o potencial da ferramenta.

## **4. Dominando os Filtros de Pesquisa**

Os filtros são o coração da tela de Reservas. Eles permitem que você navegue por centenas ou até milhares de reservas de forma rápida e precisa, encontrando exatamente o que precisa em poucos cliques. Vamos conhecer cada filtro disponível e entender quando e como usá-los.

### **Filtro: Status da Reserva**

O primeiro filtro que você vai encontrar permite selecionar o status das reservas que deseja visualizar. Este é um dos filtros mais utilizados porque permite separar rapidamente as reservas que estão ativas daquelas que foram canceladas.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hunit_-_Reservas_image17_741b40d6.png)

**Quando selecionar "Todas":** Use esta opção quando precisar de uma visão completa, incluindo tanto reservas ativas quanto canceladas. É útil para fazer relatórios mensais ou análises de cancelamento, onde você quer ver o panorama completo das vendas.

**Quando selecionar "Ativas":** Esta é provavelmente a opção que você mais usará no dia a dia. Mostra apenas as reservas confirmadas e válidas, ou seja, aquelas que realmente vão gerar ocupação no hotel. Use esta opção quando estiver planejando a operação, verificando ocupação ou preparando a chegada dos hóspedes.

**Quando selecionar "Canceladas":** Use esta opção quando precisar analisar cancelamentos. É útil para entender padrões: será que há muitos cancelamentos de um canal específico? Há mais cancelamentos em determinados períodos? Esta análise pode revelar informações valiosas sobre seu negócio.

### **Filtro: Tipo de Coleta de Pagamento**

Este filtro é importante para a gestão financeira do hotel porque define como o pagamento foi processado pelos canais.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hunit_-_Reservas_imagec_aad1e32f.png)

**Entendendo Hotel Collect:** Quando uma reserva é do tipo Hotel Collect, significa que o hóspede vai pagar diretamente para o hotel, seja no check-in ou de acordo com a política estabelecida. O canal apenas intermediou a venda, mas não processa o pagamento. Você tem controle direto sobre o recebimento e pode usar os métodos de pagamento que seu hotel aceita: cartão, dinheiro, transferência, etc.

**Entendendo Canal Collect:** Já no Canal Collect, o canal (como Booking.com ou Expedia) é quem processa o pagamento do hóspede. O hóspede paga para o canal, e depois o canal repassa o valor para você, descontando a comissão acordada. Geralmente esse repasse acontece após o checkout do hóspede, em datas específicas definidas no contrato com o canal ou cartão virtual na reserva no período de check-in.

**Como usar este filtro:** Se você está fazendo o fechamento financeiro do dia e quer saber quanto receberá diretamente dos hóspedes, filtre por Hotel Collect. Se está conferindo os repasses dos canais ou analisando comissões, filtre por Canal Collect. Para uma visão completa das vendas, mantenha em "Todos".

### **Filtro: Status da Cobrança**

Este é um filtro especial que aparece apenas se você contratou o produto HPAY-HUNIT, que é a solução de pagamentos integrada da Hsystem. Se você não tem este produto, este filtro não aparecerá na sua tela, e isso é completamente normal.

O HPAY-HUNIT permite que você processe cobranças de cartão de crédito diretamente pelo sistema, garantindo segurança dos dados e um pagamento mais automatizado.

**Status "Cobrado":** Indica que a cobrança foi processada com sucesso. O valor foi aprovado pela operadora do cartão e será creditado na sua conta conforme o prazo do seu contrato com a adquirente.

**Status "Falha na Cobrança":** Aqui você precisa prestar atenção. A cobrança foi tentada, mas não foi aprovada pela operadora do cartão. Isso pode acontecer por diversos motivos: cartão sem limite, cartão vencido, dados incorretos, bloqueio por segurança, entre outros. Quando vir este status, é recomendável entrar em contato com o hóspede ou canal para atualizar os dados de pagamento ou oferecer uma forma alternativa de garantir a reserva.

**Status "Cobrança Não Efetuada":** Significa que ainda não houve tentativa de processar o pagamento. Ainda falta uma ação sua para cobrar a reserva, pendente de pagamento.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hunit_-_Reservas_imagef_fcedc41e.png)

### **Filtro: Status da Integração com PMS**

Este é um dos filtros mais importantes para hotéis que possuem um PMS integrado ao HUNIT. Ele permite monitorar se as reservas estão chegando corretamente ao seu sistema de gestão interna. Vamos entender cada status possível:

**Status "Pendente":** Este é o status inicial. A reserva chegou ao HUNIT e foi disponibilizada na API para que seu PMS a busque. É como se a reserva estivesse em uma fila aguardando ser coletada pelo PMS. Normalmente, este status dura apenas alguns segundos ou minutos, dependendo da configuração de sincronização do seu PMS. Se uma reserva permanece muito tempo como pendente, pode indicar que o PMS não está buscando as reservas corretamente.

**Status "Sucesso":** Perfeito! A reserva foi enviada, o PMS confirmou o recebimento e gerou um código de integração. Tudo funcionou como esperado. Este é o status ideal que você quer ver em todas as suas reservas. Quando uma reserva está com este status, você pode ter certeza de que ela está registrada tanto no HUNIT quanto no seu sistema de gestão interna.

**Status "Com Erro":** Aqui temos um problema que precisa de atenção. A tentativa de enviar a reserva ao PMS falhou. Isso pode acontecer por diversos motivos técnicos: o PMS estava temporariamente indisponível, houve um erro de mapeamento de categoria, algum campo obrigatório não foi preenchido corretamente, entre outros. Quando você vê este status, é hora de acionar o suporte para investigação. A reserva existe e é válida, mas precisa ser corrigida no PMS para evitar problemas operacionais.

**Status "Não Habilitado Integração":** Este status aparece em duas situações. Primeira: você não possui integração com PMS ativa, então todas as suas reservas terão este status, e isso é normal. Segunda: você ativou a integração recentemente, e este status aparece em reservas antigas que entraram antes da integração estar ativa. Essas reservas antigas precisariam ser lançadas manualmente no PMS.

**Status "Cancelada":** Este é um status que indica uma falha na comunicação. A reserva foi disponibilizada 20 vezes seguidas para o PMS, mas ele nunca confirmou o recebimento. Após 20 tentativas, o sistema desiste e marca como cancelada. Se você vê reservas com este status, precisa ser analisado com o suporte técnico do HUNIT e do seu PMS o que ocorreu.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hunit_-_Reservas_image11_26c3a14c.png)

### **Filtro: Tipo de Data**

Este filtro é extremamente versátil e muda completamente o tipo de análise que você pode fazer. Ele permite escolher qual data você quer usar como referência para filtrar as reservas. Vamos entender cada opção e seus usos práticos:

**Data da Reserva:** Esta é a data em que o hóspede efetivamente fez a compra, o momento em que ele clicou em "confirmar reserva" no site do canal. Use este filtro quando quiser fazer análises de vendas. Por exemplo: "Quantas reservas vendemos em dezembro?" ou "Qual foi nosso faturamento de vendas na última semana?". É uma visão comercial, focada no momento da venda.

Um exemplo prático: você quer saber quantas vendas foram feitas durante uma campanha promocional que rodou entre os dias 10 e 15 de janeiro. Configure o filtro para "Data da Reserva" e defina o período de 10/01 a 15/01. Você verá todas as reservas vendidas naqueles dias, independentemente de quando o hóspede vai se hospedar.

**Data do Check-in:** Esta é a data de entrada do hóspede no hotel. Use este filtro para operação e planejamento. É a resposta para perguntas como: "Quem chega hoje?" ou "Quantos hóspedes teremos na próxima semana?" ou "Precisamos preparar quantos quartos para o check-in de amanhã?".

Exemplo prático: hoje é dia 20 de março e você quer saber quem chega hoje. Configure o filtro para "Data do Check-in" e coloque 20/03 tanto no campo "De" quanto no campo "Até". Você verá todas as reservas com entrada prevista para hoje, permitindo que a recepção se prepare adequadamente.

**Data do Checkout:** Esta é a data de saída do hóspede. Use para organizar a operação de limpeza e para entender quando os quartos ficarão disponíveis novamente. Também é útil para o financeiro, especialmente em reservas Hotel Collect, onde o pagamento costuma ser finalizado no checkout.

Exemplo prático: a governanta precisa saber quantos quartos serão liberados amanhã. Configure o filtro para "Data do Checkout" com a data de amanhã em ambos os campos. Você verá quantos hóspedes fazem checkout e pode planejar a equipe de limpeza adequadamente.

**Data do Cancelamento/Modificação:** Este filtro é especializado para análises de cancelamento. Ele mostra reservas que foram canceladas ou modificadas em um período específico. Use para entender padrões de cancelamento, fazer estudos de sazonalidade de cancelamentos ou identificar se mudanças nas suas políticas afetaram a taxa de cancelamento.

Exemplo prático: você alterou sua política de cancelamento no início de fevereiro e quer saber se isso afetou a quantidade de cancelamentos. Configure o filtro para "Data do Cancelamento/Modificação", defina o período de fevereiro inteiro e compare com o mesmo período do ano anterior.

**Campos "De" e "Até":** Estes campos definem o intervalo de datas para o tipo de filtro que você escolheu. Se você quer um dia específico, coloque a mesma data em ambos os campos. Se quer um período, coloque a data inicial em "De" e a data final em "Até".

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hunit_-_Reservas_image8_ebb6ad51.png)

### **Filtros Adicionais para Buscas Específicas**

Além dos filtros principais que acabamos de ver, há uma série de filtros adicionais que permitem buscas ainda mais específicas. Vamos entender cada um deles:

**Filtro: Nº da Reserva**

Este é o filtro mais direto de todos. Você já tem o número da reserva e quer encontrá-la rapidamente no sistema. Basta digitar o número completo e clicar em filtrar. O sistema vai mostrar exatamente aquela reserva.

Quando usar: O hóspede ligou e mencionou o número da reserva. Você recebeu um e-mail do canal sobre uma reserva específica. Você precisa verificar detalhes de uma reserva que alguém mencionou. A recepção está fazendo check-in e quer confirmar os dados da reserva.

**Filtro: Nome do Hóspede**

Este filtro permite buscar reservas pelo nome do cliente. É extremamente útil quando você não tem o número da reserva, mas sabe o nome de quem reservou.

**Importante:** O sistema exige que você digite pelo menos 3 caracteres do nome para realizar a busca. Isso evita que o sistema fique lento processando buscas muito genéricas. Além disso, é altamente recomendável combinar este filtro com um filtro de datas para otimizar a busca.

Exemplo prático: Um hóspede chamado João Silva ligou dizendo que tem uma reserva para daqui a duas semanas, mas não sabe o número. Configure o filtro de "Data do Check-in" para daqui a 10 a 20 dias, digite "João Silva" no campo de nome e filtre. Você provavelmente encontrará a reserva dele rapidamente.

**Filtro: Nº Integração PMS**

Este é um filtro técnico, usado principalmente quando você está conferindo informações com seu PMS ou resolvendo questões de integração. Há PMS’s que geram um código único para cada reserva que recebe e esse código é enviado ao channel como uma validação que a reserva foi recebida. Este código é o "Nº Integração PMS".

**Filtro: Canais**

Este filtro permite visualizar reservas de um canal específico ou de múltiplos canais. É extremamente útil para análises comparativas e para gestão individualizada de cada canal.

Quando usar: Você quer analisar o desempenho de vendas do Booking.com separadamente. Precisa conferir se todas as reservas do Airbnb estão integrando corretamente. Quer comparar a performance de diferentes canais. Está em negociação com um canal específico e precisa de dados sobre as vendas dele.

**Filtro: Tipo de Quarto**

Este filtro permite selecionar uma categoria específica de acomodação. É útil para análises de performance por tipo de quarto e para gestão operacional.

Quando usar: Você quer saber quantas reservas tem para a Suíte Premium no próximo mês. Precisa analisar qual categoria vende mais. Quer verificar se alguma categoria específica está com problemas de integração. Está planejando uma reforma e quer saber qual será o impacto na ocupação.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hunit_-_Reservas_image19_09ca5887.png)

## **5. Executando a Busca e Exportando Dados**

Depois de configurar todos os filtros desejados, você tem duas ações principais disponíveis:

### **Botão: Filtrar**

Após configurar os filtros, clique neste botão para aplicar os critérios e atualizar a lista de reservas. O sistema processará sua solicitação e mostrará apenas as reservas que atendem aos critérios definidos.

O tempo de processamento varia conforme a quantidade de filtros e o volume de reservas, mas geralmente é questão de segundos.

### **Botão: Exportar Reservas**

Esta é uma funcionalidade poderosa que permite extrair todos os dados das reservas filtradas para um arquivo CSV (um formato que pode ser aberto em Excel, Google Sheets ou qualquer planilha).

Como funciona: Configure os filtros para selecionar exatamente as reservas que você quer exportar. Clique em "Filtrar" para carregar essas reservas na tela. Clique em "Exportar Reservas". O sistema gera um arquivo CSV com todas as reservas (não apenas as da página atual, mas todas que atendem aos filtros). O arquivo é baixado automaticamente para seu computador.

O que você pode fazer com a exportação: Criar relatórios personalizados em Excel com gráficos e análises. Cruzar dados com outras planilhas da empresa. Fazer análises estatísticas mais complexas. Compartilhar dados com outros departamentos. Manter um histórico mensal para análises de longo prazo. Criar apresentações para reuniões gerenciais.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hunit_-_Reservas_image3_d6ab273d.png)

## **6. Entendendo Cada Informação da Lista de Reservas**

Agora que você já sabe como filtrar e encontrar as reservas que precisa, vamos entender em detalhes cada coluna da tabela de resultados. Cada campo traz uma informação específica que ajuda você a gerenciar suas reservas de forma completa.

### **Coluna: Reserva Nº**

Esta é a identidade da reserva, o número único que o canal de vendas atribuiu a ela. Cada canal tem seu próprio formato de numeração. Por exemplo, o Booking.com usa números longos como 3456789012, enquanto o Airbnb usa códigos alfanuméricos como HMABCDEF123.

Este número é clicável. Quando você clica nele, abre uma nova tela com todos os detalhes completos da reserva: informações do hóspede, dados de contato, detalhes da acomodação, valores discriminados, observações (quando aplicável).

Use este número sempre que precisar se comunicar com o canal sobre a reserva. É a referência que eles usam para identificá-la no sistema deles.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hunit_-_Reservas_imagea_b019182d.png)

### **Coluna: Hóspede**

Aqui aparece o nome do cliente que fez a reserva. É geralmente o nome da pessoa que vai fazer o check-in.

Importante: Este é o nome que veio do canal. Se houver algum erro de grafia ou cadastro incorreto, você verá aqui exatamente como está no sistema do canal. Se precisar de correção, normalmente isso deve ser feito no canal de origem.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hunit_-_Reservas_image18_c452e3f7.png)

### **Coluna: Canal**

Esta coluna mostra de qual canal veio a reserva. Os nomes ajudam a identificar rapidamente: você verá se veio da Booking, da Expedia, do Airbnb, ou do HBOOK (seu motor próprio de reservas).

Por que isso importa: Saber rapidamente de qual canal veio cada reserva ajuda você a aplicar os procedimentos corretos.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hunit_-_Reservas_image5_528ba9fc.png)

### **Coluna: Tipo de Quarto**

Aqui você vê qual categoria de acomodação foi reservada. O nome que aparece é exatamente como está cadastrado no seu sistema: Quarto Standard, Suíte Premium, Apartamento Luxo, Chalé Família, etc.

Esta informação é crítica para a operação. A governanta precisa saber qual tipo de quarto preparar. A recepção precisa confirmar na hora do check-in se o quarto disponível corresponde ao que foi reservado. O gerente de receitas analisa qual categoria vende mais para ajustar estratégias de preço.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hunit_-_Reservas_imageb_0f68bee6.png)

### **Coluna: Reservado**

Esta coluna mostra a data e hora exata em que a reserva foi criada no sistema. É o momento em que o hóspede finalizou a compra no canal.

Por que acompanhar isso: Permite análises de padrões de venda. Você vai perceber, por exemplo, que recebe mais reservas durante a semana ou nos fins de semana. Vai identificar os horários de pico de vendas. Pode correlacionar campanhas de marketing com picos de reserva. Em situações de overbooking ou disputas, a ordem temporal das reservas pode ser relevante.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hunit_-_Reservas_image10_f8ad03fa.png)

### **Coluna: Período da Estadia**

Aqui você vê as datas de check-in e checkout da reserva. É apresentado no formato: Check-in: DD/MM/AAAA - Checkout: DD/MM/AAAA.

Esta é uma das informações mais consultadas porque define quando você precisa ter o quarto disponível e quando ele será liberado novamente. A operação inteira do hotel gira em torno destas datas: limpeza, manutenção, preparação de check-in, planejamento de refeições, escalas de trabalho, etc.

Dica operacional: Comece cada dia conferindo as reservas com check-in para hoje e para amanhã. Garanta que a recepção está preparada, que os quartos estão prontos e que não há nenhum impedimento para receber os hóspedes.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hunit_-_Reservas_image12_c15f610c.png)

### **Coluna: Nº Integração PMS**

Este campo se aplica a somente alguns PMS’s. Algum geram código de confirmação. Este campo mostra o código que seu PMS gerou quando recebeu e confirmou a reserva. Cada sistema de PMS tem seu próprio formato de código (os que fornecem): alguns usam números sequenciais, outros usam combinações de letras e números, alguns incluem a data, etc.

Se seu PMS fornece código de integração e este campo estiver vazio, significa que a reserva ainda não foi confirmada pelo PMS. Pode ser porque está com status "Pendente" (aguardando o PMS buscar) ou porque há algum erro de integração.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hunit_-_Reservas_image15_12626a2e.png)

### **Coluna: Integração**

Esta coluna mostra o status da integração com o PMS através de um **número de 1 a 5**, exatamente os mesmos números que você viu no filtro "Status da Integração (PMS)".

O número que aparece nesta coluna tem o seguinte significado:

**1 - Pendente** Reserva aguardando o PMS acatar (disponível na API).

**2 - Sucesso** Reserva enviada e confirmada com sucesso no PMS.

**3 - Com Erro** Houve falha ao enviar a reserva para o PMS.

**4 - Não Habilitado Integração** A integração não está ativa ou a reserva entrou antes da integração ser ativada.

**5 - Cancelada** Reserva foi disponibilizada 20 vezes na API e não foi acatada pelo PMS.

**Como usar esta coluna:**

A visualização rápida através dos números é intencional: você deve conseguir, de relance, identificar se há problemas. Quando você vê o número **2** em várias reservas, sabe que está tudo funcionando bem. Quando vê os números **3** ou **5**, sabe imediatamente que precisa investigar.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hunit_-_Reservas_image4_aec56d42.png)

### **Coluna: Última Modificação**

Mostra a data e hora da última vez que a reserva sofreu alguma alteração. Modificações podem incluir: mudança de datas, alteração de nome do hóspede, upgrade ou downgrade de categoria, alteração de valores, atualização de status, adição de observações, etc.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hunit_-_Reservas_image6_0b5c5e31.png)

### **Coluna: Status**

Esta coluna mostra se a reserva está "Ativa" ou "Cancelada". É uma informação visual rápida e direta.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hunit_-_Reservas_image7_6da6648c.png)

### **Coluna: Pagamento**

Indica o método ou modalidade de pagamento registrado para a reserva. Você verá aqui se é Hotel Collect, Canal Collect, ou outros métodos específicos.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hunit_-_Reservas_image14_89e27365.png)

### **Coluna: Cartão (quando aplicável)**

Se você tem o produto HPAY-HUNIT contratado, verá nesta coluna um ícone de cartão que muda de cor conforme o status do processamento do pagamento.

Verde significa que a cobrança foi processada com sucesso. Você tem a garantia financeira e pode se preparar para receber o hóspede sem preocupações com no-show.

Vermelho indica que houve falha na cobrança. O cartão foi recusado pela operadora. Aqui você precisa agir: entre em contato com o hóspede, solicite atualização dos dados do cartão, ou ofereça formas alternativas de garantir a reserva. Se o hóspede não responder ou não resolver, você pode considerar cancelar a reserva para evitar no-show.

Cinza mostra que a cobrança ainda não foi processada.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hunit_-_Reservas_image9_548f6c4d.png) Processado

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hunit_-_Reservas_imaged_f71c31d8.png) Negado

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hunit_-_Reservas_imagee_01ecbad5.png) Não processado

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hunit_-_Reservas_image13_50ac0e0f.png)

### **Coluna: Total**

Aqui você vê o valor total da reserva em reais. Este valor inclui todas as diárias, taxas e serviços adicionais que foram incluídos na reserva. É o que o hóspede pagou (ou vai pagar) pela hospedagem.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hunit_-_Reservas_image16_e974d7b7.png)

## **7. Compreendendo os Totalizadores**

Na parte inferior da tela, você encontra uma seção extremamente útil: os totalizadores. Esta área resume financeiramente as reservas que estão sendo exibidas, e entender a diferença entre os dois tipos de totais é fundamental.

### **Totais da Página**

Este totalizador mostra a soma apenas das reservas que estão visíveis na página atual da tela. Se há 100 reservas nos seus filtros, mas a tela mostra 20 por vez, este total reflete apenas essas 20.

Quando é útil: Para conferências rápidas do que está visível. Para fazer contas mentais rápidas. Quando você está revisando reserva por reserva e quer confirmar os valores da tela atual.

### **Totais Gerais**

Este é o totalizador mais importante. Ele soma TODAS as reservas que atendem aos seus filtros, mesmo que estejam distribuídas em múltiplas páginas. Se você filtrou 500 reservas e elas estão distribuídas em 25 páginas, este total considera todas as 500.

O sistema divide os totais gerais em categorias importantes:

**Total de Reservas Canceladas:** Soma de todos os valores de reservas que foram canceladas. É importante acompanhar isso porque representa receita que você esperava, mas não vai receber. Análise de cancelamentos ajuda a entender sazonalidade e a ajustar políticas de cancelamento.

**Total de Reservas Ativas:** Esta é sua receita confirmada. Soma de todas as reservas válidas, que vão gerar ocupação e faturamento real. Este é o número que importa para previsões financeiras.

**Total Geral:** Soma de tudo - ativas e canceladas. Útil para análises históricas e para entender o volume total de vendas antes dos cancelamentos.

**Comissão:** Mostra o total de comissões que você vai pagar aos canais pelas reservas exibidas. Este valor é calculado automaticamente com base nos percentuais de comissão de cada canal. É fundamental para cálculo de lucratividade real.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hunit_-_Reservas_image_68f286b4.png)

## **Glossário de Termos**

|  |  |
| --- | --- |
| **Termo** | **Definição** |
| **HUNIT** | Sistema de channel manager da Hsystem que gerencia reservas e sincroniza informações com canais de venda online. |
| **PMS** | Property Management System. Software de gestão interna do hotel que controla toda operação: reservas, check-in, checkout, faturamento, governança, manutenção, etc. |
| **Canal de Vendas** | Site ou plataforma online onde quartos são oferecidos para reserva, como Booking.com, Expedia, Airbnb, Decolar, etc. |
| **HBOOK** | Motor de reservas próprio da Hsystem, que permite vendas diretas pelo site do hotel sem intermediação de outros canais. |
| **Hotel Collect** | Modalidade de pagamento onde o hóspede paga diretamente ao hotel, seja no check-in ou conforme política estabelecida. |
| **Canal Collect** | Modalidade onde o canal processa o pagamento do hóspede e repassa ao hotel após descontar comissão acordada. |
| **HPAY-HUNIT** | Produto adicional da Hsystem que permite processar cobranças de cartão de crédito diretamente pelo sistema HUNIT. |
| **Status de Integração** | Situação da comunicação entre HUNIT e PMS sobre uma reserva específica (Pendente, Sucesso, Com Erro, etc.). |
| **Nº Integração PMS** | Código único gerado pelo PMS quando confirma o recebimento de uma reserva, usado como referência entre sistemas. |
| **API** | Application Programming Interface. Sistema de comunicação automática entre softwares diferentes, usado para sincronizar reservas entre HUNIT e PMS. |
| **CSV** | Comma-Separated Values. Formato de arquivo texto que organiza dados em colunas separadas por vírgulas, compatível com Excel e Google Sheets. |
| **Check-in** | Data e horário de entrada do hóspede no hotel, início da hospedagem. |
| **Checkout** | Data e horário de saída do hóspede do hotel, fim da hospedagem. |
| **Categoria** | Tipo ou classificação de acomodação oferecida pelo hotel (Quarto Standard, Suíte Premium, Chalé, etc.). |
| **Comissão** | Percentual ou valor fixo pago ao canal de vendas pela intermediação da reserva, descontado do valor total. |
| **Timestamp** | Registro automático de data e hora exata em que algo aconteceu no sistema. |
| **No-show** | Situação onde o hóspede não comparece ao hotel na data prevista de check-in sem avisar previamente. |
| **Overbooking** | Situação onde mais quartos foram vendidos do que o hotel possui disponível, gerando conflito de reservas. |
| **Ticket Médio** | Valor médio por reserva, calculado dividindo o faturamento total pelo número de reservas. |
| **RevPAR** | Revenue Per Available Room. Indicador que mede receita por quarto disponível, usado para análise de performance. |
| **Filtro** | Ferramenta que permite selecionar e visualizar apenas informações que atendem critérios específicos definidos pelo usuário. |
| **Totalizador** | Componente que calcula e exibe somas de valores das reservas filtradas, apresentando resumos financeiros. |