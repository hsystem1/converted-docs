Documentação: E-mail pré/pós check-in

Visão geral

Este documento descreve o processo de configuração de E-mail pré/pós check-in no sistema Hbook (Motor de reservas)

**Objetivo da funcionalidade**

A tela de e-mail de pré/pós check-in permite ao hotel configurar mensagens que serão disparadas automaticamente para os hóspedes antes do seu check-in e pós checkout, garantindo comunicação rápida, clara e padronizada.

**Casos de Uso**

**Por que usar essa funcionalidade?**

Envio antecipado de informações: Enviar e-mail de boas-vindas antes da data de check-in com lembretes importantes.

Lembretes de horário: Relembrar o hóspede do horário de check-in e checkout.

Pesquisas e feedback: Configurar pesquisa de satisfação no e-mail de pós-checkout ou oferecer descontos para futuras reservas.

**Acesso a funcionalidade**

Acessar a ferramenta Hbook (Motor de reservas)

Caminho: MARKETING – E-MAIL PRÉ/PÓS CHECKIN

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hbook_- Email pré p_image3_94606046.png)

**E-mail de pré-check-in:**

Campos de marcação (checkbox):

**Ativo:** Quando **marcado**, o sistema passa a enviar os e-mails de pré-check-in. Quando desmarcado não é enviado o e-mail.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hbook_- Email pré p_imagea_79b11a51.png)

**Enviar no ato da Reserva:** Quando **marcado**, habilita a função de que no dia da realização da reserva o hóspede também recebe o e-mail de pré check-in, ou seja, o sistema passa a enviar os e-mails de pré check-in no ato da confirmação da reserva.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hbook_- Email pré p_image6_bb6ee3d2.png)

Quando **desmarcado**, o hotel pode escolher quantos dias antes do check-in esse e-mail será enviado ao hóspede.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hbook_- Email pré p_image7_3d8611f7.png)

**Texto do e-mail que irá para o hóspede:** Editor de texto (com opções de formatação, negrito, itálico, listas, links, imagens, etc.) onde é montado o corpo do e-mail de pré check-in.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hbook_- Email pré p_image_ca7d2f12.png)

**E-mail de pós-checkout:**

Campos de marcação (checkbox):

**Ativo**: Quando marcado, o sistema passa a enviar os e-mails de pós-checkout. Quando desmarcado não é enviado o e-mail.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hbook_- Email pré p_image9_0cf091a1.png)

**Enviar no dia do checkout:** Quando **marcado**, habilita a função de que no dia da saída, o sistema passa a enviar os e-mails de pós-checkout.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hbook_- Email pré p_image5_165d08df.png)

Quando **desmarcado**, o hotel pode escolher quantos dias depois do checkout esse e-mail será enviado ao hóspede.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hbook_- Email pré p_image8_97017b3e.png)

**Texto do e-mail que irá para o hóspede:** Editor de texto (com opções de formatação, negrito, itálico, listas, links, imagens, etc.) onde é montado o corpo do e-mail de pré check-in.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hbook_- Email pré p_image4_a721ddae.png)

Ao finalizar o cadastro clicar no botão roxo no canto inferior direto.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hbook_- Email pré p_imageb_e653cb8a.png)

**Variáveis disponíveis:**

Bandeiras: Corresponde a configuração de idiomas por bandeira.

Cada bandeira representa um idioma (português, inglês e espanhol).

O cliente (hotel) precisa escrever o conteúdo manualmente no idioma correspondente à bandeira escolhida.

O sistema não faz tradução automática — portanto, se o hotel deseja que o texto apareça em inglês ou espanhol, ele mesmo deve inserir a versão traduzida.

Esse conteúdo será exibido no motor de reservas público, permitindo que o hóspede selecione o idioma desejado e veja as informações já traduzidas.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2025_12_12_135154_97be/images/Hbook_- Email pré p_image2_b0ce2826.png)

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
| **Funcionalidade:** | E-mail pré/pós check-in |
| **Data de referência:** | 27/10/2025 |
| **Tipo de documento:** | Guia de configuração |