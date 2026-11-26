# NAN SECURITY

**02 · Hardening de Wi-Fi · Novembro de 2026**

[Voltar ao portfólio](../README.md)

## Problema

Revisar controles básicos de proteção de uma rede própria, sem ampliar o escopo para pentest ou auditoria integral.

## Minha participação

Inspecionei opções do equipamento, realizei alterações autorizadas e conferi conectividade. A análise dos protocolos e a documentação foram guiadas por IA.

## Resultados registrados

| Verificação | Evidência | Limite |
| --- | --- | --- |
| Autenticação e criptografia | WPA2-Personal com AES e WPS desativado em configuração observada | Não valida todos os clientes ou toda a rede |
| Conectividade | Funcionamento relatado após manutenção | Sem teste exaustivo de disponibilidade |
| Segmentação | Distinção entre SSID e isolamento estudada | Isolamento não comprovado |

## Aprendizados e próximos passos

WPS desnecessário amplia superfície de exposição. Modos de transição WPA2/WPA3 não comprovam a cifra utilizada por todos os clientes. Separar redes por nome não prova isolamento. A próxima prática proposta é validar acesso permitido e negado em laboratório isolado, com dados fictícios.

Não são divulgados modelo, firmware, identificadores, provedor, topologia ou parâmetros detalhados de uma rede em uso.

Referências: [Wi-Fi Alliance](https://www.wi-fi.org/discover-wi-fi/security) · [NIST SP 800-153](https://csrc.nist.gov/pubs/sp/800/153/final)

*Prática pessoal guiada; não representa serviço profissional de auditoria de segurança.*
