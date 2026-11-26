# NAN CONTROL

**04 · Validação funcional de controle infravermelho Android · Novembro de 2026**

[Voltar ao portfólio](../README.md)

## Problema

Avaliar o controle de um equipamento próprio por infravermelho e investigar conectividade local como frente experimental distinta.

## Minha participação

Operei os dispositivos, testei comandos em bancada autorizada e observei reações físicas. Agentes de IA implementaram o aplicativo e os testes; a auditoria examinou integridade e regressões selecionadas.

## Resultados históricos

| Verificação | Resultado | Limite |
| --- | --- | --- |
| IR | Suporte a 38 kHz exibido | Sem medição instrumental externa |
| v0.1.1 e v0.2.0 | 12 comandos responderam fisicamente, conforme relato do operador | Sem ensaio independente de cada tecla |
| Wi-Fi | Descoberta SSDP sem sucesso; resposta XML no navegador relatada | Controle por rede não demonstrado |
| v0.2.1 | 51 arquivos conferidos; quatro arquivos do motor IR idênticos | Auditoria histórica; sem recompilação independente ou novo teste físico considerado nesta edição |

## Aprendizados e continuidade

Sucesso da API não prova reação física. Uma leitura HTTP não demonstra autorização para controle. Falhas de descoberta exigem hipóteses testáveis e registro de resultados negativos. Retomar validação física conforme escopo autorizado antes de declarar regressão resolvida.

Referência: [Android ConsumerIrManager](https://developer.android.com/reference/android/hardware/ConsumerIrManager)

*Bancada pessoal; sem APK, perfis de sinais, código operacional ou dados privados. Não é produto homologado.*
