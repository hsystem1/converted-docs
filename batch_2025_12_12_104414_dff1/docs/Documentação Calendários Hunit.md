**Documentação: Calendários Hunit**

**Visão Geral**

A principal melhoria é a introdução da **Nova Grade de Informações,** que segmenta os dados de calendário por canal e categoria, resultando em uma **melhora significativa de desempenho** por não exigir o carregamento completo do calendário.

Essa **Grade de Informações** exibe, por canal individualmente, os dados de valores, restrições e disponibilidades enviados. Há também uma **Grade de Disponibilidade** dedicada a mostrar as disponibilidades recebidas de sistemas **PMS** ou inseridas diretamente no sistema **HUNIT**.

**Objetivo da Funcionalidade**

* **Por que usar essa funcionalidade?**
* **Precisão informações de disponibilidade:** Idênticas em todos os canais.
* **Segurança Redução:** Drástica do risco de **overbooking** e custos associados.
* **Eficiência Atualizações** de inventário em **tempo real** com um único clique
* **Performance**Permite reajustar preços e restrições rapidamente para maximizar a **receita.**

**Casos de Uso**

**Por que usar essa funcionalidade?**

**Navegação no sistema HUNIT>CALENDARIO**

**Configuração Calendários: Acesse Grade de Informações (Nova)**![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Documentação_Calen_image3_fe677534.png)

**Opção 1: A NOVA GRADE de Disponibilidade** e Tarifas mantém todas as informações da grade anterior, mas apresenta uma **estrutura segmentada**.

* **Acesse o HUNIT:** No menu superior do sistema, navegue até a seção de **CALENDARIOS** e selecione a opção **GRADE DE INFORMAÇÕES (NOVA)** Além da performance, facilita no comparativo entre **canais de venda** ou categorias diferentes, pois pode ser selecionado I**ndividualmente.**
* **Selecione os Canais:** O sistema exibirá a tela para que você selecione os canais cujas informações deseja carregar.
* **Para Visualizar Canais Específicos:** Clique individualmente no(s) nome(s) do(s) canal(is) desejado(s) (ex: **BOOKING**, **EXPEDIA**, **HOTELBEDS**).
* **Para Visualizar Todos os Canais:** Clique no botão **MARCAR TODOS**.
* **Carregue a Grade:** Após selecionar o(s) canais, clique no botão verde **IR PARA A GRADE** para carregar os dados e iniciar o gerenciamento de tarifas e disponibilidade.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Documentação_Calen_image_262c995d.png)

**Configuração Calendários: Grade de Informações**

**Opção 2:** A Grade de Informações é o painel central onde você visualiza o status atual (Valores, Restrições e Disponibilidade) para cada dia em cada categoria.

* **Linhas com Fundo Branco**: **Disponibilidade Liberada:** A venda está aberta.
* **Destaques com Fundo Vermelho: Venda Fechada:** Indica que a disponibilidade foi zerada (o número acima do valor é '0') ou que as vendas estão fechadas. Para verificar, clique sobre o valor e consulte o histórico de atualizações.
* **Triângulo amarelo**: Indica a existência de alguma restrição na data. Para mais detalhes, clique em "**Exibir restrições**" e identifique qual restrição se aplica sendo:

1. **Número:** Corresponde a estadia mínima de acordo com o número
2. **S:** Fechamento de **Saida** - Não é possível consultar com check out nessa data
3. **C** – Fechamento de **chegada** - Não é possível consultar com check in nessa data

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Documentação_Calen_image6_a7d673ea.png)

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Documentação_Calen_image7_6c2b45f0.png)

**Ações possíveis no Calendário**

**Opção 3: Menu superior permite gerenciar e interagir com os dados da grade**

* **Exibir Restrições:** Habilita um campo abaixo dos valores para mostrar as restrições aplicadas na data.
* Clicando novamente em **Exibir Restrições**, aparecerá a opção de **Esconder Restrições.**

**Quando usar:** Para verificar o tipo de restrição que o **Triângulo Amarelo** está indicando.

* **Imprimir:** Gera um arquivo do Calendário para impressão da grade que está em tela.
* **Carregar Grade:** Carrega as informações do canal selecionado, preenchendo as células em branco.

**Sempre** que o calendário for aberto, pois as informações iniciais estão em branco por padrão.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Documentação_Calen_image4_854f1b11.png)

**Grade de Disponibilidade**

**Opção 4: A grade de disponibilidade, é recebida pelo sistema PMS (Sistema de Gestão da Propriedade)**

* O **Hunit** permite que seja atualizado as **disponibilidades**, tanto na página de **disponibilidade** quanto na página de **atualizações**, mas para isso é necessário que a propriedade não possua integração com **PMS (Sistema de Gestão da Propriedade)**![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Documentação_Calen_image5_d52df527.png)
* Na tela de **atualizações** é possível atualizar e conferir as disponibilidades. Ao clicar sobre o valor e alterar o campo vai ficar em destaque, pendente de confirmação. Após definir um valor de disponibilidade, basta clicar em **ATUALIZAR.**

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Documentação_Calen_image2_0ee9a9ff.png)

**Variáveis Disponíveis**

* Grade de informações (Nova)
* Grade de informações
* Grade de disponibilidade

**Encerramento! Pronto agora você pode configurar sua aba de calendários.**

**Metadados do Documento**

|  |  |
| --- | --- |
| Sistema | Hunit (Gestor de Canais) |
| Modulo | Calendários |
| Funcionalidade | Disponibilidade/Tarifa |
| Data de Referência | 30/10/2025 |
| Tipo de Documento | Guia de configuração para treinamento IA |
| Versão | 1.0 |