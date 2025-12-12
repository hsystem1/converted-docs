Documentação: Marketing – Recuperação de reservas

Visão geral

Este documento descreve o processo de configuração de recuperação de reservas no sistema Hbook (Motor de reservas)

**Objetivo da funcionalidade**

A tela de recuperação de reservas permite ao hotel configurar mensagens que serão disparadas automaticamente para os hóspedes em caso de abandono de carrinho, garantindo comunicação rápida, clara e padronizada.

Como funciona a recuperação de reservas

Quando um hóspede inicia o processo de reserva e não finaliza, o sistema envia automaticamente um e-mail de remarketing convidando-o a retornar e concluir a compra.

Você pode personalizar o texto desse e-mail para torná-lo mais atrativo.

**Acesso a funcionalidade**

Acessar a ferramenta Hbook (Motor de reservas)

Caminho: MARKETING – RECUPERAÇÃO DE RESERVAS

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_–_Recuperaçã_image_ec9aac2a.png)

**Configurações do Booking Recovery:**

Neste menu, você poderá ativar o envio automático e editar o conteúdo do e-mail que o hóspede irá receber.

**Campos de marcação (checkbox):**

**Ativo:** Quando **marcado**, habilita a função de Booking Recovery, ou seja, o sistema passa a enviar os e-mails de recuperação de reserva para hóspedes que abandonaram o processo de reserva. Quando **desmarcado** não é enviado o e-mail.

**Sinalizar o hotel a cada reserva abandonada:** Quando marcado, o sistema envia uma notificação ao hotel sempre que uma reserva for abandonada pelo cliente no processo de finalização.

**Importante**: o e-mail de recuperação de reservas leva 30 minutos para ser enviado após o cliente abandonar.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_–_Recuperaçã_image6_b1e0c2a6.png)

**Campo de preenchimento:**

**Assunto do E-mail**: Campo de texto para inserir o título/assunto que será exibido no e-mail enviado ao hóspede.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_–_Recuperaçã_image2_d3816a93.png)

**Texto do e-mail que irá para o visitante**: Editor de texto (com opções de formatação, negrito, itálico, listas, links, imagens, etc.) onde é montado o corpo do e-mail de recuperação.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_–_Recuperaçã_image3_c582b5a2.png)

Ao finalizar o cadastro clicar no botão roxo no canto inferior direto.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_–_Recuperaçã_image5_8ce010dd.png)

**Acompanhando reservas abandonadas**

Para visualizar as reservas abandonadas, vá até o menu **Reservas > Lista de Reservas** e utilize o filtro de status **Abandonadas**.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_–_Recuperaçã_image4_ed439073.png)

**Variáveis disponíveis:**

**Bandeiras:** Corresponde a configuração de idiomas por bandeira.

Cada bandeira representa um idioma (português, inglês e espanhol).

O cliente (hotel) precisa escrever o conteúdo manualmente no idioma correspondente à bandeira escolhida.

O sistema **não faz tradução automática** — portanto, se o hotel deseja que o texto apareça em inglês ou espanhol, ele mesmo deve inserir a versão traduzida.

Esse conteúdo será exibido no **motor de reservas público**, permitindo que o hóspede selecione o idioma desejado e veja as informações já traduzidas.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_104414_dff1/images/Hbook_–_Recuperaçã_image7_2bafbdd5.png)

{{NomeDoHospede}} - Busca a informação preenchida no campo “Nome” e “Sobrenome”

{{DataDoCheckin}} - Busca a informação preenchida como “Data de check-in”

{{DataDoCheckout}} - Busca a informação preenchida como “Data de checkout”

{{NomeDoHotel}} - Busca a informação preenchida no campo “Nome do hotel”

{{NumeroDaReserva}} - Busca a informação gerada de “número da reserva”

Metadados do Documento

|  |  |
| --- | --- |
| **Sistema:** | **HBook (Motor de Reservas)** |
| **Módulo:** | Marketing |
| **Funcionalidade:** | Recuperação de reservas |
| **Data de referência:** | 27/10/2025 |
| **Tipo de documento:** | Guia de configuração |