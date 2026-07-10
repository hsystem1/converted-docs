# **Como adicionar o carrossel de comparação de quartos no HAI (chatbot)**

O componente de Comparação de Quartos exibe um carrossel interativo com as categorias de hospedagem disponíveis diretamente no chat. É especialmente útil quando o hóspede pergunta sobre os tipos de quarto — em vez de uma resposta textual longa, o chatbot apresenta um card visual para cada categoria, com imagem, nome e detalhes, que o hóspede pode navegar deslizando.

**Recomendação de uso:** adicione o carrossel de Comparação de Quartos à intenção relacionada a dúvidas sobre tipos de acomodação. É uma das configurações mais impactantes para a experiência do hóspede — transforma uma resposta simples em uma apresentação visual das opções do hotel.

## **Como acessar**

No HAI, acesse Menu superior → Meu Robô e selecione no menu lateral a intenção à qual deseja adicionar o carrossel — por exemplo, a intenção que responde perguntas sobre quartos ou acomodações.

## **Passo a passo — Adicionar o carrossel**

**Acesse o menu Meu Robô e localize a intenção**

No HBOT, clique em Menu superior → Meu Robô. No menu lateral esquerdo, selecione a intenção desejada — geralmente a que responde dúvidas sobre tipos de quarto ou acomodações disponíveis.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_07_10_165204_05e9/images/Como_adicionar_o_car_image_9f4bac80.png)

**Clique em Nova Resposta +**

Na área de respostas da intenção selecionada, clique no botão Nova Resposta +. Um menu com os tipos de resposta disponíveis será exibido.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_07_10_165204_05e9/images/Como_adicionar_o_car_image_9f4bac80.png)

**Selecione a opção Comparação de Quartos**

No menu que se abrir, clique em Comparação de Quartos. O componente de carrossel será adicionado automaticamente à lista de respostas da intenção.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_07_10_165204_05e9/images/Como_adicionar_o_car_image_9f4bac80.png)

**Confira a pré-visualização**

Ao lado do componente adicionado, o campo de pré-visualização exibe exatamente como o carrossel aparecerá para o hóspede no chat — com os cards das categorias de quarto configuradas no motor de reservas. Verifique se as informações estão corretas antes de salvar.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_07_10_165204_05e9/images/Como_adicionar_o_car_image_9f4bac80.png)

**Ative o botão de reserva (opcional)**

Se desejar que o hóspede possa iniciar a reserva diretamente pelo carrossel, ative a flag Mostrar botão de reserva. Quando habilitada, um botão de reserva será inserido em cada card do carrossel, permitindo que o hóspede prossiga para a reserva sem sair da conversa.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_07_10_165204_05e9/images/Como_adicionar_o_car_image_9f4bac80.png)

**Com botão de reserva ativado:** o hóspede vê os quartos e pode clicar diretamente em Reservar no card da categoria desejada.

**Sem botão de reserva:** o carrossel exibe apenas as informações e imagens das categorias, sem opção de reserva direta — útil quando a reserva é processada manualmente pela equipe.

**Clique em Salvar**

Após configurar o componente, clique no botão Salvar localizado no canto inferior direito da tela (botão na cor azul). As alterações serão registradas e o robô passará a exibir o carrossel como resposta àquela intenção.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_07_10_165204_05e9/images/Como_adicionar_o_car_image_9f4bac80.png)

Sem clicar em Salvar, o carrossel não será adicionado — as alterações são descartadas ao sair da tela ou navegar para outra intenção.

## **Notas**

* **O conteúdo do carrossel é gerado automaticamente:** as categorias exibidas são as mesmas cadastradas no motor de reservas (HBOOK) — não é necessário configurar manualmente cada card.
* **Combinando com texto:** você pode adicionar uma resposta de texto antes do carrossel na mesma intenção — ex.: "Confira as nossas categorias de quarto:" seguido do componente de Comparação de Quartos.
* **Substituir ou remover:** para remover o carrossel, clique no ícone de lixeira no card do componente e salve. Para substituir, remova o atual e adicione um novo.