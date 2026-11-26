# NAN WATCH LITE

**06 · Comunicação BLE e validação de wearable · Novembro de 2026**

[Voltar ao portfólio](../README.md)

## Problema

Investigar comunicação local e personalização visual de um wearable próprio, sem substituir firmware.

## Minha participação

Operei ferramentas BLE e o dispositivo, acompanhei leituras, formulei hipóteses sobre renderização e confirmei notificações e recursos gráficos. Implementação e testes de software foram assistidos por agentes de IA.

## Resultados históricos

| Verificação | Resultado | Limite |
| --- | --- | --- |
| GATT | 11 serviços e 46 características enumerados; duas leituras de revisão | Sem comprovação de identidade criptográfica |
| Sessão | Aceitação pelo dispositivo registrada | Autenticação mútua não comprovada |
| Notificação | Exibição física e recuperação no histórico confirmadas | Uma tentativa posterior falhou sem diagnóstico conclusivo |
| Mostrador | Protótipo visual aprovado | Firmware não substituído |
| Software | 76 testes offline até uma etapa; 95 na seguinte conforme relatório e revisão histórica | Contagens cumulativas, não somáveis; não são testes físicos |
| Integridade | 97 hashes de quatro pacotes conferidos | Não comprova segurança integral |

## Aprendizados e continuidade

Advertising, conexão GATT, pareamento e bonding são conceitos distintos. Aceitação pelo transporte não comprova entrega na tela. Uma sessão aceita não demonstra autenticação mútua. Captura física de eventos e resposta automática permanecem sem validação na documentação considerada; o segundo hardware não integra esses resultados.

Referências: [Bluetooth SIG](https://www.bluetooth.com/learn-about-bluetooth/tech-overview/) · [Bleak](https://bleak.readthedocs.io/)

*Laboratório guiado; sem chaves, identificadores, recursos proprietários ou dados biométricos. Não é produto comercial.*
