**E-mail pré/pós check-in**

**Hbook**

**1. Para que serve esta função?**

O objetivo é automatizar a comunicação com o cliente, garantindo que ele receba informações importantes sem que você precise enviar manualmente.

* **Boas-vindas:** Enviar lembretes e informações úteis antes da viagem.
* **Horários:** Relembrar os horários de entrada **(check-in)** e saída **(checkout)**.
* **Pesquisa de Satisfação:** Pedir a opinião do hóspede após a estadia ou oferecer descontos para o futuro.

**2. Por que usar essa funcionalidade?**

* Envio antecipado de informações: Enviar e-mail de boas-vindas antes da data de check-in com lembretes importantes.

**Lembretes de horário:** Relembrar o hóspede do horário de **check-in** e **checkout.**

Pesquisas e feedback: Configurar pesquisa de satisfação no e-mail de pós-checkout ou oferecer descontos para futuras reservas.

**3. Como acessar?**

* Caminho: **MARKETING – E-MAIL PRÉ/PÓS CHECKIN**

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hbook_- Email pré_p_image3_94606046.png)

**4. E-mail de pré-check-in:**

Campos de marcação **(checkbox):**

* **Ativo:** Quando **marcado**, o sistema passa a enviar os e-mails de pré-check-in. Quando desmarcado não é enviado o e-mail.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hbook_- Email pré_p_imagea_79b11a51.png)

**5. Enviar no ato da Reserva:**

* Quando **marcado**, habilita a função de que no dia da realização da reserva o hóspede também recebe o e-mail de pré check-in, ou seja, o sistema passa a enviar os e-mails de pré check-in no ato da confirmação da reserva.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hbook_- Email pré_p_image6_bb6ee3d2.png)

Quando **desmarcado**, o hotel pode escolher quantos dias antes do check-in esse e-mail será enviado ao hóspede.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hbook_- Email pré_p_image7_3d8611f7.png)

**6. Texto do e-mail que irá para o hóspede:**

* Editor de texto (com opções de formatação, negrito, itálico, listas, links, imagens, etc.) onde é montado o corpo do e-mail de pré check-in.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hbook_- Email pré_p_image_ca7d2f12.png)

**7. E-mail de pós-checkout:**

Campos de marcação (checkbox):

* **Ativo**: Quando marcado, o sistema passa a enviar os e-mails de pós-checkout. Quando desmarcado não é enviado o e-mail.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hbook_- Email pré_p_image9_0cf091a1.png)

**8. Enviar no dia do checkout:**

* Quando **marcado**, habilita a função de que no dia da saída, o sistema passa a enviar os e-mails de pós-checkout.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hbook_- Email pré_p_image5_165d08df.png)

Quando **desmarcado**, o hotel pode escolher quantos dias depois do checkout esse e-mail será enviado ao hóspede.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hbook_- Email pré_p_image8_97017b3e.png)

**9. Texto do e-mail que irá para o hóspede:**

* Editor de texto (com opções de formatação, negrito, itálico, listas, links, imagens, etc.) onde é montado o corpo do e-mail de pré check-in.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hbook_- Email pré_p_image4_a721ddae.png)

Ao finalizar o cadastro clicar no botão roxo no canto inferior direto.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hbook_- Email pré_p_imageb_e653cb8a.png)

**10. Variáveis disponíveis:**

* Bandeiras: Corresponde a configuração de idiomas por bandeira.
* Cada bandeira representa um idioma (português, inglês e espanhol).
* O cliente (hotel) precisa escrever o conteúdo manualmente no idioma correspondente à bandeira escolhida.
* O sistema não faz tradução automática — portanto, se o hotel deseja que o texto apareça em inglês ou espanhol, ele mesmo deve inserir a versão traduzida.

Esse conteúdo será exibido no motor de reservas público, permitindo que o hóspede selecione o idioma desejado e veja as informações já traduzidas.

![Imagem](https://raw.githubusercontent.com/hsystem1/converted-docs/main/batch_2026_01_26_164604_a198/images/Hbook_- Email pré_p_image2_b0ce2826.png)

{{NomeDoHospede}} - Busca a informação preenchida no campo “Nome” e “Sobrenome”

{{DataDoCheckin}} - Busca a informação preenchida como “Data de check-in”

{{DataDoCheckout}} - Busca a informação preenchida como “Data de checkout”

{{NomeDoHotel}} - Busca a informação preenchida no campo “Nome do hotel”

{{NumeroDaReserva}} - Busca a informação gerada de “número da reserva”

**Glossário**

|  |  |
| --- | --- |
| **Sistema:** | **HBook (Motor de Reservas)** |
| **Check-in** | Momento da chegada e entrada do hospede no hotel |
| **Check-out** | Momento da saída e encerramento da conta do hospede |
| **Checkbox (Caixa de marcação)** | Aquele pequeno quadrado que você clica para marcar ou desmarcar uma função. |
| **Disparar e-mail** | Termo usado para o envio automático de mensagens pelo sistema. |
| Variáveis | Códigos entre chaves que o sistema substitui automaticamente por informações personalizadas (como o nome do cliente). |