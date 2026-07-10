# **Causas comuns de Bloqueio de Processamento e como resolver no HUNIT**

### **Por que conhecer as causas**

Identificar a causa de um bloqueio de processamento permite resolvê-lo com rapidez e evitar a interrupção prolongada de atualizações no canal. A mensagem retornada pelo canal (coluna Mensagem do Canal na tela de bloqueios) é sempre o ponto de partida para o diagnóstico.

**Lembrete:** enquanto o bloqueio estiver ativo, o HUNIT não envia nenhuma atualização ao canal — tarifas, restrições e disponibilidade ficam paradas. Resolva o mais rápido possível.

## **Causa 1 — Valor acima ou abaixo do permitido pelo canal**

### **O que acontece**

Alguns canais trabalham com contratos de valores ou margens de segurança que limitam os preços praticados pelo hotel. Quando o preço enviado ultrapassa o máximo permitido ou fica abaixo do mínimo aceito pela OTA, o canal rejeita a atualização e retorna um erro.

**Exemplo de mensagem do canal:** "At least one rate exceeds maximum bound..."

**Como resolver**

**Se o valor enviado estava incorreto:** edite o bloqueio no HUNIT e ajuste o preço para dentro do limite permitido pelo canal.

**Se o valor enviado é o desejado:** entre em contato diretamente com o canal e solicite a revisão da margem contratada para que o canal passe a aceitar o novo valor.

## **Causa 2 — Divergência de configuração entre o canal e o HUNIT**

### **O que acontece**

Quando alguma configuração do canal (como quantidade de adultos/pax, tipos de tarifa ou categorias de quarto) está diferente do que está configurado no HUNIT, o canal recusa a atualização por inconsistência de dados.

Situações comuns que geram essa divergência:

**Quantidade de Pax diferente:** o HUNIT envia 3 adultos, mas o canal só aceita 2 para aquela categoria.

**Alterações feitas diretamente na extranet do canal** sem comunicar ao suporte da Hsystem para ajuste no HUNIT.

**Tarifa alterada ou excluída no canal** sem atualizar o mapeamento no HUNIT.

**Exemplo de mensagem do canal:** "The number of base guests informed (3) does not match the one for the room (2)."

### **Como resolver**

**Identifique o que diverge:** compare as configurações do canal (via extranet) com as configurações no HUNIT.

**Corrija no lado correspondente:** se a extranet foi alterada sem comunicação, solicite ao suporte da Hsystem o ajuste do mapeamento no HUNIT para alinhar com o que o canal espera.

## **Não conseguiu identificar o motivo**

Se a mensagem do canal não foi suficiente para identificar e resolver o problema, acione o suporte da Hsystem informando que há um bloqueio de processamento ativo. Informe o canal afetado e a mensagem de erro exibida para agilizar a investigação.

Quanto antes o bloqueio for resolvido, menor o risco de o canal continuar vendendo com dados desatualizados.