# **Como acionar o suporte para disponibilidade divergente entre PMS e HUNIT**

Acione o suporte da Hsystem quando a disponibilidade do PMS não estiver refletindo corretamente no HUNIT — e você já tiver verificado o reenvio do PMS, avaliado limitadores e bloqueios, e confirmado o código de integração sem resolver o problema.

Antes de acionar o suporte, realize as verificações descritas no artigo Como diagnosticar disponibilidade divergente entre PMS e HUNIT. Elas resolvem a maioria dos casos sem necessidade de suporte.

## **Informações necessárias para o suporte**

Reúna as informações abaixo antes de entrar em contato. Quanto mais completo o relato, mais rápida a análise e resolução.

|  |  |
| --- | --- |
| **Informação** | **O que informar** |
| Nome do PMS | Qual sistema de gestão você utiliza. Ex.: Desbravador, Newhotel, Hits, Hospedin. |
| Categoria afetada | Nome da categoria com divergência. Ex.: Standard, Superior, Luxo, Suíte Premium. |
| Código de integração | Código de integração da categoria no PMS, se disponível. Ex.: STD, LUX, 12345, SUITE\_PREM. |
| Data ou período | Data específica ou intervalo com divergência. Ex.: 12/03/2025 ou 12/03 a 15/03 ou todo abril/2025. |
| Reenvio solicitado? | Já solicitou reenvio ao PMS? Informe: Sim / Não. Se sim, indique quando foi, se o PMS confirmou e se houve alguma mudança após o reenvio. |
| Logs do PMS | Possui os logs de envio do PMS? Informe: Sim / Não. Se sim, anexe os logs ao contato com o suporte. |
| Disponibilidade no PMS | Quantos quartos o PMS mostra disponíveis. Ex.: 5 quartos, ou print da tela. |
| Disponibilidade no HUNIT | Quantos quartos o HUNIT mostra na Grade de Disponibilidade. Ex.: 0 quartos, ou print da grade. |

## **Modelo de relato para o suporte**

**PMS utilizado:** Desbravador **Categoria:** Standard 2 pax — código de integração: STD **Período:** 12/03/2025 a 15/03/2025 **Reenvio solicitado ao PMS:** Sim — solicitado em 11/03, PMS confirmou o envio, mas a disponibilidade não apareceu no HUNIT **Logs do PMS:** Sim — logs anexados **Disponibilidade no PMS:** 5 quartos disponíveis **Disponibilidade no HUNIT:** 0 quartos na Grade de Disponibilidade

## **O que o suporte fará após receber as informações**

|  |  |
| --- | --- |
| **Etapa** | **Ação** |
| 1 — Análise dos logs | Verifica os logs de recebimento no HUNIT para confirmar se a disponibilidade foi enviada pelo PMS. |
| 2 — Verificação do código | Confere se o código de integração está correto e se a disponibilidade está sendo direcionada para a categoria certa. |
| 3 — Análise de restrições | Verifica se há configurações no HUNIT que estejam bloqueando a atualização. |
| 4 — Contato com o PMS | Se identificar problema na comunicação, pode entrar em contato com o PMS para resolver em conjunto. |
| 5 — Correção e validação | Implementa a correção necessária e confirma se a disponibilidade foi normalizada. |
| 6 — Retorno | Informa sobre a causa e a solução aplicada. |

## **Notas**

* **Logs do PMS aceleram a investigação.** Se o PMS confirmar que enviou a disponibilidade mas ela não chegou ao HUNIT, os logs são a principal evidência para identificar a causa.
* **Se o problema afetar mais de uma categoria ou período,** informe todos os casos em um único contato para que o suporte analise o conjunto.