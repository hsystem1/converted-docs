**Configurar Flutuações HPRICE**

**Visão Geral**

Aqui é onde você vai **automatizar** sua estratégia de **preços**, portanto, use esta função com bastante atenção. Sempre que houver uma leitura, serão aplicadas as regras aqui configuradas para redefinir suas tarifas nos canais de vendas.

**Objetivo da funcionalidade**

Objetivo principal de configurar **flutuação**, é gerenciar o ciclo de vida e a aplicação das suas estratégias de preços dinâmicos.

**Casos de Uso**

**Por que usar essa funcionalidade?**

* **Alta Ocupação / Picos de Demanda:** **Garantia de Preço Máximo:** A regra de flutuação sobe a tarifa em $10\%$ ou um valor fixo ($R\$ 50,00$) automaticamente quando atinge o limite de ocupação, maximizando a receita no pico de demanda sem você monitorar.
* B**aixa Ocupação / Vendas Lentas: Estímulo à Venda:** A regra de flutuação **reduz a tarifa** em 5% ou 30,00 para tornar o preço mais atrativo e estimular as reservas quando a demanda está fraca.
* **Sazonalidade (Eventos e Feriados): Tarifa Otimizada para o Período:** Permite criar um **conjunto de regras específico** (como no exemplo "Ano novo 2025") com preços base mais altos ou flutuações mais agressivas, garantindo o máximo de lucro em dias de alta certeza de demanda.
* **Regras de Últimas Unidades:** Captura de Valor: A flutuação aumenta significativamente o preço quando a disponibilidade está quase no fim, explorando a escassez do produto.

**Importante! É nesta tela que irão constar todos os cadastros de estratégias vigentes e vencidas, também fazer bloqueios de flutuação.**

**Acesso a funcionalidade**

**Navegação no sistema**

**Caminho: Flutuação> Configurar Flutuações**

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_154601_bb25/images/Configurar_Flutuaço_image8_1aa0f344.png)

**Configuração de Flutuação**

**Localização: Regras de Flutuação**

**Acesse a seção: Configurar Flutuação**

**Opção 1:** Para cadastrar uma nova estratégia é só clicar em: **Adicionar Novo conjunto de regras de flutuação.**

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_154601_bb25/images/Configurar_Flutuaço_imagee_57c51f71.png)

**Opção 2: Preenchimento do novo conjunto de regras**

* **Descrição: Nome para identificar a estratégia *(adicionar um nome exemplo)***

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_154601_bb25/images/Configurar_Flutuaço_image3_2f1a4cd1.png)

* **Datas:** Períodos m que essas regras estarão vigentes e, se há alguma delimitação de dias da semana. Para adicionar mais datas é só clicar no botão “+” **(Adicionar períodos exemplo)**

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_154601_bb25/images/Configurar_Flutuaço_imaged_c6601463.png)

* **Faixa de ocupação:** Porcentagem de ocupação em que irá flutuar, voce pode calcular em porcentagem a quantidade de quartos que deseja flutuar para adicionar nessa ***(adicionar ocupação exemplo)***

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_154601_bb25/images/Configurar_Flutuaço_image5_1c56d862.png)

* **Preço:**Tarifa que será enviada para cada **faixa de ocupação**

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_154601_bb25/images/Configurar_Flutuaço_image7_ffc3933b.png)

Todas essas informações juntas serão as regras de flutuação. O HPrice sempre irá respeitar exatamente o que está configurado no conjunto, então, não será enviado preços para uma data que não esteja nos cadastros, ou um preço que não tenha sido cadastrado

**Opção 3:** Considerando que o hotel já tenha realizado o primeiro passo que é cadastro na lista de **BARs:**

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_154601_bb25/images/Configurar_Flutuaço_image4_b06b5c3b.png)

Todas essas informações juntas serão as regras de flutuação. O HPrice sempre irá respeitar exatamente o que está configurado no conjunto, então, não será enviado preços para uma data que não esteja nos cadastros, ou um preço que não tenha sido cadastrado

**Importante!** Ao cadastrar as regras e flutuação ou ao editar uma **BAR,** depois de clicar em **SALVAR** aparecera um pop-up conforme demostrado abaixo;

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_154601_bb25/images/Configurar_Flutuaço_image6_23fde94a.png)

Ao clicar em **SIM**, o **HPRCE** enviara a correção das tarifas.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_154601_bb25/images/Configurar_Flutuaço_imagea_ef05b050.png)

**Observação:**

* Uma boa forma de entender quando deve ser feito um novo cadastro é pensar que eles servem para enviar regras de acordo com o comportamento da sua demanda, se a propriedade possui uma demanda de alta, média e baixa, e é aplicado um preço diferente para cada uma dessas demandas, então cada uma terá um conjunto. Se para os finais de semana pretende flutuar com regras de ocupação diferente, então para esses dias também deve se ter um conjunto separado.
* Não é possível cadastra o mesmo período em conjuntos diferentes.
* **O HPRICE** envia flutuação para até 2 aos, mediante o envio de disponibilidade.

**Configurar Flutuações**

**Localização: Regras Vencidas**

**Opção 4:** Na seção de **Flutuação, Configurar Flutuações,** localize e clique na aba **"Regras Vencidas"**

* ***Atenção:*** Diferentemente da aba "Regras de flutuação" (que mostra as regras ativas), esta aba lista apenas aquelas que já tiveram o seu período de aplicação encerrado.

**Ao visualizar uma regra vencida, você terá informações importantes para análise:**

* Identificação da sua estratégia (Ex: "REGRA GERAL 2024" ou "FERIADOS 2024").
* **Período de Ativação (Vencido):** A data de início e fim em que a regra foi aplicada. ***Exemplo:*** Para a "REGRA GERAL 2024", o período ativo anterior foi de **17/09/2024 até 11/10/2024**.
* **Dias da Semana:** Indicação dos dias que a regra impactou (S, T, Q, Q, S, S, D).
* **Regras Registradas:** O número de condições de flutuação que faziam parte desse conjunto (Ex: "5 Regras registradas").

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_154601_bb25/images/Configurar_Flutuaço_image_5159594b.png)

**Opção 5:** Ações sobre as regras vencidas

* Os ícones de ação no lado direito continuam disponíveis, mesmo para regras vencidas:
* **Lápis (Editar):** Permite visualizar as condições internas que foram usadas. É ideal para **revisão de desempenho**.
* **Ícone de Documento (Duplicar/Copiar):** É a ação mais útil aqui! Se a regra "FERIADOS 2024" teve um bom resultado, você pode **duplicá-la** para criar a "FERIADOS 2025" sem ter que configurar tudo do zero.
* **Lixeira (Excluir):** Remove permanentemente o histórico dessa regra.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_154601_bb25/images/Configurar_Flutuaço_image2_481d1859.png)

**Localização: Flutuação Bloqueada**

**Opção 6: Na seção de Flutuação, Configurar Flutuações,** Clique na aba **"Flutuação Bloqueada"**

* Clique no botão **"+ Adicionar período de flutuação bloqueada"**.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_154601_bb25/images/Configurar_Flutuaço_image9_7e39eeb2.png)

* No campo **"De\*"**, insira a data de início do seu bloqueio manual **(Ex**: **13/03/2025)**
* No campo **"Até\*"**, insira a data final do seu bloqueio **(Ex: 31/03/2025).**

Após configurar todos os períodos que você deseja bloquear, certifique-se de salvar (o botão “**Salvar Alterações**” estaria visível no canto inferior direito fora de recorte da imagem, mas é o passo final)

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_11_154601_bb25/images/Configurar_Flutuaço_imagec_3a94f429.png)

**Variáveis Disponíveis**

* **Regras de Flutuação**
* **Regras Vencidas**
* **Flutuação Bloqueada**

**Encerramento!**

**Pronto,** agora você pode configurar e visualizar sua flutuação.

**Metadados do Documento**

|  |  |
| --- | --- |
| Sistema | Hprice |
| Módulo | Flutuação |
| Funcionalidade | Configurar Flutuação |
| Data de referência | 04/11/2025 |
| Tipo de documento | Guia de configuração para treinamento da IA |
| Versão | 1.0 |