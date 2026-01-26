**HUNIT - Relatório de Atualizações**

**Guia Completo para Acompanhar Suas Atualizações nos Canais**

## **1. Por Que Este Relatório É Importante**

Imagine a seguinte situação: você acabou de atualizar os preços de todas as suas categorias para a alta temporada. Passou a manhã toda configurando valores diferenciados para finais de semana, ajustando estadia mínima e liberando disponibilidade. Depois de tanto trabalho, surge aquela dúvida: será que tudo chegou corretamente nos canais? O Booking.com recebeu os novos preços? A Expedia está mostrando a disponibilidade atualizada? As restrições foram aplicadas no Hotelbeds?

É exatamente para responder essas perguntas que existe o Relatório de Atualizações do HUNIT. Esta não é apenas mais uma tela do sistema - é sua ferramenta de auditoria, seu mecanismo de controle de qualidade, sua garantia de que o trabalho que você fez está realmente refletido nos canais onde seus clientes fazem reservas.

Pense no Relatório de Atualizações como um registro histórico completo de tudo que você modificou e enviou para os canais. É como ter um diário detalhado que registra cada ajuste de preço, cada alteração de disponibilidade, cada restrição aplicada. Mais do que isso, ele mostra se cada uma dessas atualizações foi bem-sucedida ou se encontrou algum problema no caminho.

Neste guia, vamos explorar cada recurso desta poderosa ferramenta. Você vai aprender não apenas a gerar relatórios, mas a interpretar cada informação, identificar problemas rapidamente e usar esses dados para tomar decisões estratégicas sobre sua operação.

## **2. Como Acessar o Relatório de Atualizações**

Para acessar esta funcionalidade, o caminho é simples e direto. Faça login no sistema HUNIT e, no menu superior, localize a opção **Atualizações**. Ao clicar nela, você verá um submenu com várias opções. Procure e clique em **Relatório de atualizações**.

Você será direcionado para uma tela limpa e organizada, dividida em duas partes principais: a área de filtros no topo, onde você configura o que quer consultar, e a área de resultados logo abaixo, onde aparecerão os dados solicitados após você clicar em "Gerar Relatório".

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hunit_-_Relatorio_de_image_d339c380.png)

## **3. Entendendo a Lógica do Sistema**

Antes de mergulharmos nos filtros e nas colunas do relatório, é importante entender como o sistema funciona nos bastidores. Quando você faz uma atualização no HUNIT - seja de preço, disponibilidade ou restrições - o sistema não simplesmente "muda um número". Na verdade, ele cria uma requisição formal que será enviada para cada canal configurado.

Pense nisso como enviar cartas registradas. Você coloca cada atualização em um "envelope" digital, endereça para o canal correto (Booking, Expedia, etc.), e o sistema envia. Depois, fica aguardando a confirmação de recebimento e processamento por parte do canal. O Relatório de Atualizações é exatamente o registro de todas essas "cartas" que você enviou: quando foram enviadas, para onde foram, o que continham e se chegaram ao destino com sucesso.

Cada linha do relatório representa uma dessas requisições. Uma única ação sua na tela de Atualizações pode gerar várias linhas no relatório, porque pode estar enviando informações para múltiplos canais ou múltiplas categorias de quarto. Isso é perfeitamente normal e esperado.

## **4. Dominando os Filtros: Encontrando Exatamente O Que Você Precisa**

A primeira área da tela, onde ficam os filtros, é o seu centro de comando. É aqui que você define exatamente quais atualizações quer visualizar. Vamos explorar cada filtro em detalhes, entendendo não apenas o que ele faz, mas quando e por que você deveria usá-lo.

### **Filtro: Status da Atualização**

Este é provavelmente o filtro mais importante de todos, porque mostra se suas atualizações foram bem-sucedidas ou se encontraram problemas. Vamos entender cada opção disponível:

**Opção "Todos":** Esta é a visão completa, sem filtros de status. Mostra tudo que foi enviado, independentemente do resultado. Use esta opção quando quiser ter uma visão panorâmica de toda a atividade de atualização em um período.

**Opção "Pendente":** Esta opção mostra atualizações que ainda estão em processamento pelos canais. Quando você envia uma atualização, ela não é processada instantaneamente - há uma fila de processamento. Normalmente, atualizações ficam pendentes por apenas alguns segundos ou minutos, mas dependendo do volume e do canal, pode demorar um pouco mais.

Quando usar: Logo após fazer uma atualização importante, se você gerar o relatório imediatamente, muitas atualizações ainda estarão como "Pendente". Isso é normal. Aguarde alguns minutos e consulte novamente. No entanto, se você vê atualizações que permanecem pendentes por horas ou dias, há um problema que precisa ser investigado - pode ser uma falha de comunicação com o canal.

**Opção "Sucesso":** Esta é a opção que você quer ver. Mostra apenas as atualizações que foram enviadas e confirmadas com êxito pelos canais. Quando uma atualização aparece como "Sucesso", você tem a certeza de que aquela informação está ativa no canal e disponível para os clientes verem.

Quando usar: Depois de fazer uma atualização crítica (como ajustar preços para um evento especial ou liberar disponibilidade de última hora), use este filtro para confirmar rapidamente que tudo foi aplicado com sucesso. É sua validação de que o trabalho foi concluído corretamente.

**Opção "Bloqueado":** Esta opção é uma bandeira vermelha. Mostra atualizações que foram impedidas por alguma restrição ou regra do canal. Isso pode acontecer por diversos motivos: há alguma configuração de contrato que impede certos tipos de atualização, o preço que você tentou enviar está abaixo do mínimo aceito pelo canal, ou há alguma inconsistência nos dados enviados.

Quando usar: Se você percebe que seus preços não estão aparecendo em um canal específico, ou que disponibilidades não estão sendo atualizadas, filtre por "Bloqueado". Você poderá identificar exatamente quais atualizações foram impedidas e investigar o motivo.

Ação recomendada: Atualizações bloqueadas geralmente requerem correção na configuração do canal ou ajuste na forma como você está enviando as informações. Documente o padrão de bloqueios e entre em contato com o suporte da HSystem ou do canal para resolver.

**Opção "Cancelado":** Esta opção mostra atualizações que foram canceladas após serem bloqueadas. Vamos entender como isso funciona:

Quando uma atualização é enviada e o canal a rejeita por algum motivo (configuração incorreta, valor fora dos limites aceitos, problema de mapeamento, etc.), ela fica com status "Bloqueado". Neste ponto, você tem duas opções: investigar o problema, corrigir e reenviar a atualização, ou simplesmente excluir aquele bloqueio do sistema.

Se você escolher excluir o bloqueio em vez de corrigi-lo, aquela atualização passa de "Bloqueado" para "Cancelado". É como se você estivesse dizendo ao sistema: "Tudo bem, não vou mais tentar enviar essa atualização específica".

**Atenção importante:** Cancelar um bloqueio não resolve o problema - apenas remove aquela tentativa específica do sistema. Se o problema era real (por exemplo, uma configuração de mapeamento errada), ele vai se repetir nas próximas vezes que você tentar atualizar a mesma coisa. Use "Cancelado" apenas quando você realmente quer descartar aquela atualização específica, não como forma de "varrer o problema para debaixo do tapete".

**Opção "Somente Disponibilidade":** Este é um filtro especializado que mostra apenas atualizações relacionadas à quantidade de quartos disponíveis, ignorando atualizações de preços e restrições. É extremamente útil quando você quer focar especificamente no gerenciamento de inventário.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hunit_-_Relatorio_de_imagec_03a3ca5e.png)

### **Filtro: Período (Data de Submissão)**

Este filtro é fundamental porque define a janela de tempo que você quer analisar. Ele se refere à data em que as atualizações foram ENVIADAS (não a data para a qual os preços ou disponibilidades são válidos - isso você verá na coluna "Período" do relatório).

**Campos "De" e "Até":** Aqui você define o intervalo de datas de submissão que quer consultar. O sistema recomenda fortemente que você selecione um intervalo máximo de 2 dias. Por quê? Porque quanto maior o período, mais atualizações serão listadas, e relatórios muito extensos podem ficar lentos para carregar e difíceis de analisar.

**Estratégia recomendada:** Em vez de gerar um relatório gigante de um mês inteiro, faça relatórios menores e mais focados. Se precisa analisar um mês, faça em partes: primeira semana, segunda semana, etc. Isso mantém os relatórios ágeis e mais fáceis de interpretar.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hunit_-_Relatorio_de_image5_52e9664c.png)

**Como pensar sobre este filtro:**

Se você quer validar uma atualização que acabou de fazer agora, coloque a data de hoje em ambos os campos.

Se você quer revisar o que foi feito ontem, coloque a data de ontem em ambos os campos.

Se você quer ver o que aconteceu durante uma semana específica, você pode fazer dia por dia ou em blocos de 2 dias.

### **Filtro: Canais**

Este filtro permite que você foque sua análise em um canal específico ou veja todos de uma vez. É extremamente útil quando você quer validar se um canal específico está recebendo e processando suas atualizações corretamente.

**Quando selecionar "Todos":** Use quando quiser ter uma visão geral de como suas atualizações estão performando em todos os canais simultaneamente. É útil para identificar se um problema é generalizado ou específico de um canal.

**Quando selecionar um canal específico:** Use quando você suspeita que há um problema com um canal em particular, ou quando precisa validar que atualizações críticas chegaram a um canal importante, ou ainda quando está em negociação/análise de performance de um canal específico e precisa de dados.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hunit_-_Relatorio_de_image7_4203a7ab.png)

### **Filtro: Tipo de Quarto**

Este filtro permite segmentar suas análises por categoria de acomodação. Cada hotel tem suas categorias (Standard, Luxo, Suíte, etc.) e às vezes você quer focar em uma específica.

**Quando visualizar todas:** Use para ter uma visão completa de toda a operação. É útil quando você fez atualizações em massa envolvendo todas as categorias e quer confirmar que todas foram processadas.

**Quando filtrar por categoria específica:** Use quando você atualizou apenas uma categoria e quer validar especificamente ela. Também é útil se você suspeita que uma categoria específica está com problemas de atualização, ou se você está analisando a estratégia de precificação de uma categoria em particular.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hunit_-_Relatorio_de_image10_5ad41a21.png)

### **Filtro: Origem**

Este é um filtro muito interessante que muita gente não explora adequadamente. Ele mostra DE ONDE dentro do sistema HUNIT partiu cada atualização. Entender isso é importante para rastreabilidade e controle.

**Opção "Todas":** Mostra atualizações vindas de qualquer origem. Use para uma visão completa, especialmente se você tem múltiplas formas de atualizar o sistema (manual, PMS, etc.).

**Opção "Tela Atualização":** Mostra apenas atualizações que foram feitas manualmente por alguém na tela de Atualizações em Massa. São as atualizações que um usuário sentou, configurou e enviou conscientemente.

Quando usar: Você fez uma atualização manual há pouco tempo e quer confirmar especificamente ela. Você quer entender quantas atualizações manuais estão sendo feitas versus automáticas. Você precisa auditar ações manuais de usuários específicos.

**Opção "Grade de Disponibilidade":** Mostra atualizações que foram feitas diretamente através da grade de disponibilidade, onde você pode clicar e ajustar números rapidamente. Essa opção é somente quando a gestão é manual no sistema Hunit, você que atualiza a disponibilidade, quando se tem PMS não tem essa opção habilitada, para evitar divergências.

Quando usar: Você ou alguém da equipe estava trabalhando diretamente na grade ajustando disponibilidades e quer confirmar se todas as alterações foram enviadas. É útil para validar correções rápidas que são feitas visualmente na grade.

**Opção "Inventário Integrado" ou "Serviço Integração":** Esta é para atualizações que vieram automaticamente do seu PMS através da integração. Quando o PMS envia uma nova disponibilidade ou quando há uma reserva que diminui o inventário, essas atualizações aparecem com esta origem.

Quando usar: Você quer validar se a integração com o PMS está funcionando corretamente. Você quer entender o volume de atualizações automáticas versus manuais. Você precisa investigar se uma mudança no PMS foi refletida corretamente nos canais.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hunit_-_Relatorio_de_image12_14e2621d.png)

## **5. Gerando o Relatório**

Depois de configurar todos os filtros conforme sua necessidade, chega o momento de gerar o relatório. Clique no botão **"Gerar Relatório"** e aguarde alguns instantes enquanto o sistema processa sua solicitação.

O tempo de processamento varia conforme a quantidade de dados solicitados. Um relatório de um dia com poucos canais carrega em segundos. Um relatório de 2 dias com todos os canais e todas as categorias pode demorar um pouco mais. Seja paciente - o sistema está vasculhando milhares de registros para trazer exatamente o que você pediu.

Quando o relatório carregar, você verá uma tabela organizada com múltiplas colunas. Cada linha representa uma atualização específica que foi enviada. Pode parecer muita informação à primeira vista, mas vamos destrinchar cada coluna para que tudo faça sentido.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hunit_-_Relatorio_de_image13_b65da342.png)

## **6. Interpretando Cada Coluna do Relatório: O Guia Definitivo**

Agora vem a parte mais importante: entender o que cada coluna do relatório está te dizendo. Cada uma traz uma informação específica que, quando combinada com as outras, conta a história completa de uma atualização.

### **Coluna 1: Data da Requisição**

Esta coluna mostra o dia e horário exato, até o minuto, em que a atualização foi enviada ao canal. É o timestamp (Data e hora) da ação.

**Por que isso importa:** Permite que você correlacione atualizações com ações específicas que você ou sua equipe fizeram. Se você atualizou preços às 14h30, deve ver atualizações com esse horário (ou poucos minutos depois). Também é útil para entender a ordem cronológica dos eventos, especialmente quando você fez múltiplas atualizações seguidas.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hunit_-_Relatorio_de_image8_5f9b5269.png)

### **Coluna 2: Período**

Esta coluna é diferente da anterior - ela não mostra quando a atualização foi enviada, mas sim PARA QUAIS DATAS aquela atualização se aplica. É o intervalo de datas de estadia para o qual você configurou preços, disponibilidades ou restrições.

**Formato da informação:** Você verá algo como "01/11/2025 até 16/12/2025" e logo abaixo uma linha mostrando os dias da semana incluídos: "Dom, Seg, Ter, Qua, Qui, Sex, Sáb".

**Por que os dias da semana importam:** Muitas vezes você não atualiza todos os dias da semana uniformemente. Talvez você tenha aplicado um preço especial apenas para finais de semana (Sexta, Sábado, Domingo). Esta informação deixa claro exatamente quais dias foram afetados pela atualização.

**Exemplo prático:** Você está investigando por que um preço está errado na próxima sexta-feira. Ao gerar o relatório, você vê que a última atualização para aquele período incluiu apenas "Seg, Ter, Qua, Qui". Descobriu o problema: você esqueceu de incluir a sexta-feira na atualização. Agora sabe que precisa fazer uma atualização complementar.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hunit_-_Relatorio_de_imagea_e15c0ed3.png)

### **Coluna 3: Canal**

Esta coluna simplesmente informa para qual canal de venda aquela atualização específica foi enviada. Você verá nomes como "Expedia", "Booking", "Hotelbeds", "Airbnb", entre outros.

**Por que conferir isso:** Confirma que a atualização foi para o canal correto. Às vezes você pode querer atualizar apenas alguns canais específicos, e esta coluna permite validar se suas configurações foram aplicadas corretamente.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hunit_-_Relatorio_de_imagef_357bed3e.png)

### **Coluna 4: Tipo de Quarto**

Aqui você vê qual categoria de acomodação foi afetada por aquela atualização. O nome que aparece é exatamente como está cadastrado no seu sistema: pode ser "Stand Twin 2 Pax", "Stand Twin 1 Pax -- Sem Café", "Suíte Premium", "Chalé Família", etc.

**Importante:** Você pode ver o mesmo período e canal repetidos várias vezes com categorias diferentes. Isso é normal - significa que você atualizou múltiplas categorias de uma vez, e cada uma gerou sua própria linha no relatório.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hunit_-_Relatorio_de_image11_8e545e0b.png)

### **Colunas 5: Tarifa Venda / Tarifa Net**

Estas duas colunas trabalham juntas e mostram, quando aplicável, os valores monetários que foram enviados ao canal.

**Tarifa Venda:** É o preço público, o valor que aparece para o cliente final no canal. É o preço "de prateleira".

**Tarifa Net:** É o valor líquido, geralmente usado em canais que trabalham com modelo merchant (onde o canal compra do hotel e revende ao cliente com markup próprio). Nem todos os canais usam tarifa net.

**Quando estas colunas ficam em branco:** Se estas colunas estão vazias, significa que aquela atualização específica não incluiu mudança de preços. Foi uma atualização de disponibilidade, restrição ou alguma outra configuração. Isso é perfeitamente normal.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hunit_-_Relatorio_de_image4_964317ea.png)

### **Coluna 6: Estadia Mínima (Est. Mín.)**

Esta coluna mostra se houve definição ou alteração do número mínimo de noites exigido para reservas no período selecionado. Você verá um número (2, 3, 5, etc.) ou ficará em branco se nenhuma estadia mínima foi configurada naquela atualização.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hunit_-_Relatorio_de_image6_1c6d1392.png)

### **Coluna 7: Disponibilidade**

Esta coluna indica a quantidade de unidades (quartos) disponíveis que foram enviadas para o canal. É o seu inventário disponível para venda.

**Números que você verá:** Pode ser qualquer número de 0 para cima. Zero significa que você fechou aquela categoria para aquele período. Um número positivo indica quantos quartos estão disponíveis para reserva.

**Disponibilidade atualizada pela integração com PMS:** Se você tem PMS integrado, esta coluna é especialmente importante para validar a sincronização. A disponibilidade que aparece aqui deveria corresponder ao que está no seu PMS (considerando reservas já confirmadas). Divergências sistemáticas indicam problemas de integração que precisam ser resolvidos.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hunit_-_Relatorio_de_imaged_7070af77.png)

### **Colunas 8: Data de Chegada e Data de Partida**

Estas duas colunas mostram se você aplicou restrições de check-in (chegada) ou check-out (partida) para o período. O sistema mostra simplesmente "Sim" ou "Não".

**"Sim" significa:** Existe uma restrição configurada. Para Data de Chegada "Sim", significa que aquele dia está bloqueado para check-in (fecho de chegada). Para Data de Partida "Sim", significa que aquele dia está bloqueado para checkout (fecho de saída).

**"Não" significa:** Sem restrição. As reservas são permitidas normalmente. O hóspede pode fazer check-in ou checkout livremente.

**Por que usar fechos de chegada/saída:** São ferramentas avançadas de revenue management. Um fecho de chegada pode te ajudar a manter hóspedes por mais noites. Um fecho de saída pode evitar que um hóspede saia em um dia específico, forçando-o a estender a estadia.

**Exemplo de problema:** Um cliente reclama que tentou reservar, mas o sistema não deixou, mesmo havendo disponibilidade. Você gera o relatório e descobre que há "Sim" em Data de Chegada para aquele dia - você bloqueou inadvertidamente as chegadas. Agora sabe que precisa remover essa restrição.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hunit_-_Relatorio_de_imagee_b331b659.png)

### **Coluna 9: Venda Parada**

Este é o stop de venda, o bloqueio total. Quando esta coluna mostra "Sim", significa que você fechou completamente aquela categoria para venda naquele período e canal. Nenhuma reserva será aceita, independentemente de haver ou não disponibilidade.

**"Sim":** Vendas bloqueadas. O quarto não aparece disponível para reserva no canal.

**"Não":** Vendas abertas. O quarto pode ser reservado (desde que haja disponibilidade).

**Quando você faria isso:** Durante reformas (o quarto não está apto para uso). Durante overbooking (precisa pausar vendas urgentemente até resolver). Estrategicamente, para forçar vendas em outras categorias (fecha a mais barata para empurrar vendas para categorias mais caras). Durante problemas técnicos ou operacionais.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hunit_-_Relatorio_de_image2_058aedef.png)

### **Coluna 10: Usuário**

Esta coluna identifica quem realizou a atualização. Você verá o nome do usuário ou e-mail de quem estava logado no sistema no momento da ação.

**Por que isso é importante:** Rastreabilidade e responsabilização. Se algo deu errado, você sabe quem fez. Se algo foi muito bem-feito, você sabe quem parabenizar. Para hotéis com múltiplos usuários acessando o sistema, é essencial saber quem fez o quê.

**Cenário de auditoria:** Você percebe que preços estão sendo alterados de forma não planejada. Gera um relatório e descobre que um usuário específico está fazendo atualizações fora do processo estabelecido. Isso indica necessidade de treinamento ou revisão de permissões de acesso.

**Situação automática:** Se a atualização veio de uma integração automática com PMS, esta coluna pode mostrar "Sistema" ou "Integração" em vez de um nome de usuário. Isso é normal e indica que foi uma ação automática, não manual.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hunit_-_Relatorio_de_image9_be5628fa.png)

### **Coluna 11: Origem**

Já falamos sobre este filtro anteriormente, mas ele também aparece como uma coluna no relatório. Aqui você vê, para cada linha, de onde aquela atualização específica foi gerada.

**Valores que você verá:** "Tela Atualização" (manual), "Grade de Disponibilidade" (ajuste visual), "Inventário Integrado" ou "Serviço Integração" (do PMS).

**Análise de padrões:** Olhe esta coluna ao longo de várias linhas. Você vai começar a ver padrões: determinados tipos de atualização sempre vêm de determinada origem. Por exemplo, atualizações de disponibilidade geralmente vêm do PMS (Inventário Integrado), enquanto atualizações de preços vêm da Tela Atualização (manual).

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hunit_-_Relatorio_de_image3_ffabfc74.png)

**Coluna 12: Status**

Esta é a coluna que resume tudo: mostra se aquela atualização específica foi bem-sucedida ou encontrou problemas. É o veredicto final.

**Sucesso:** Texto indicando sucesso. A atualização foi enviada, recebida e processada corretamente pelo canal. Está ativa e funcionando. É o resultado que você quer ver em todas as linhas.

**Pendente:** Texto indicando processamento. A atualização foi enviada mas ainda não foi confirmada pelo canal. Pode estar em uma fila de processamento. Normalmente resolve em minutos, mas se persistir por horas, investigue.

**Bloqueado:** Texto indicando bloqueio. A atualização foi rejeitada pelo canal por algum motivo. Precisa de investigação e ação corretiva. Pode ser problema de configuração, violação de regras contratuais, inconsistência nos dados, ou outros motivos.

**Cancelado:** Texto indicando cancelado. Esta opção mostra atualizações que foram canceladas/excluídas após serem bloqueadas.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hunit_-_Relatorio_de_imageb_9af14912.png)

## **Glossário de Termos**

|  |  |
| --- | --- |
| **Termo** | **Definição** |
| **HUNIT** | Sistema de channel manager da Hsystem que distribui informações de preços, disponibilidade e restrições para canais de venda online. |
| **Requisição** | Pacote de informações enviado do HUNIT para um canal específico, contendo atualizações de preços, disponibilidade ou restrições. |
| **Status** | Estado atual de uma atualização: pode ser Sucesso (processada), Pendente (aguardando), Bloqueado (rejeitada) ou Cancelado. |
| **Canal de Venda** | Plataforma online onde quartos são oferecidos para reserva, como Booking.com, Expedia, Airbnb, Hotelbeds. |
| **Tarifa Venda** | Preço público que aparece para o cliente final no canal de vendas. |
| **Tarifa Net** | Valor líquido usado em canais merchant, onde o canal compra do hotel e revende com markup próprio. |
| **Estadia Mínima** | Número mínimo de noites exigido para aceitar uma reserva em determinado período. |
| **Disponibilidade** | Quantidade de quartos disponíveis para venda em uma categoria específica. |
| **Fecho de Chegada** | Restrição que bloqueia check-ins em uma data específica. |
| **Fecho de Saída** | Restrição que bloqueia check-outs em uma data específica. |
| **Stop de Venda** | Bloqueio total de vendas de uma categoria, independentemente de haver disponibilidade. |
| **Categoria** | Tipo de acomodação oferecida pelo hotel (Quarto Standard, Suíte Premium, Chalé, etc.). |
| **PMS** | Property Management System. Sistema de gestão interna do hotel que controla operação, reservas e faturamento. |
| **Origem** | Indica de onde dentro do HUNIT partiu uma atualização (Tela Atualização, Grade de Disponibilidade, Inventário Integrado). |
| **Timestamp** | Registro de data e hora exata em que algo aconteceu no sistema. |
| **Revenue Management** | Gestão estratégica de preços e disponibilidade para maximizar receita do hotel. |
| **Inventário** | Quantidade total de quartos disponíveis de uma categoria. |
| **Processamento** | Análise e aplicação de uma atualização pelo canal de vendas. |
| **Merchant** | Modelo de negócio onde o canal compra do hotel a preço net e revende ao cliente com markup próprio. |
| **Comissão** | Percentual ou valor pago ao canal pela intermediação de vendas. |