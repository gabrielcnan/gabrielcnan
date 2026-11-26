# NAN ROKU

**05 · Comunicação e permissões em IoT · Novembro de 2026**

[Voltar ao portfólio](../README.md)

## Problema

Entender a diferença entre conectividade, autorização e resposta física de um dispositivo multimídia próprio em rede local.

## Minha participação

Executei consultas orientadas, comparei respostas HTTP e observei o comportamento físico. O agente de engenharia desenvolveu a ferramenta PowerShell e testes; o agente auditor revisou artefatos e identificou ressalvas.

## Resultados históricos

| Verificação | Resultado | Limite |
| --- | --- | --- |
| Permissões | HTTP 200 e 403 em operações distintas | Não constitui bypass ou pentest |
| Reação física | Duas ações confirmadas pelo operador | Sem homologação integral |
| Diagnóstico v0.1.1 | Quatro GET com HTTP 200 em ciclo real; dois ciclos simulados | Simulação separada do estado real |
| v0.2.1 | 23 arquivos com hashes conferidos; 38 testes simulados reportados pela engenharia | Testes não reproduzidos independentemente; execução física pendente na evidência considerada |

## Aprendizados e continuidade

Uma resposta HTTP não comprova execução física. Resultados antigos não podem ser tratados como evidência de uma nova tentativa. Parsing XML e autorização precisam de validação explícita e negação por padrão. A revisão estática identificou pendências; não há root, modificação de firmware, exploração ou integração externa demonstrados.

Referências: [Roku ECP](https://developer.roku.com/dev/docs/external-control-api) · [OWASP XML External Entity Prevention](https://cheatsheetseries.owasp.org/cheatsheets/XML_External_Entity_Prevention_Cheat_Sheet.html)

*Laboratório autorizado, sem configurações atuais, identificadores, contas ou logs brutos.*
