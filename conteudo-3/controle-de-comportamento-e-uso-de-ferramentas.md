---
description: Como orientar quando o agente deve agir, perguntar ou usar ferramentas.
---

# Controle de comportamento e uso de ferramentas

Quando um agente pode usar ferramentas, o prompt precisa orientar não apenas o que ele deve responder, mas também **como ele deve se comportar ao longo da tarefa**.

## Decidir quando agir

Um agente pode precisar:

* responder diretamente;
* pedir esclarecimentos;
* consultar uma ferramenta;
* seguir etapas antes de responder;
* interromper uma ação por falta de segurança ou contexto.

Se o prompt não deixa isso claro, o comportamento pode ficar imprevisível.

## Limitar autonomia

Nem sempre é desejável dar liberdade total ao agente.

Em vários cenários, faz sentido orientar coisas como:

* quando ele deve perguntar antes de agir;
* quando deve evitar mudanças sensíveis;
* quando deve consultar uma fonte externa;
* quando deve recusar uma ação arriscada;
* quando deve encerrar e pedir confirmação.

## Ferramentas não devem ser usadas “sem pensar”

Uma boa instrução de ferramenta ajuda o agente a entender:

* para que a ferramenta serve;
* quando ela deve ser usada;
* quando ela não deve ser usada;
* que tipo de resposta deve ser produzida depois do uso.

## Exemplo rápido

Em vez de dizer apenas:

* "Use as ferramentas disponíveis."

vale mais dizer algo como:

* "Use a ferramenta de busca apenas quando a resposta depender de informação externa atualizada. Se a tarefa puder ser resolvida com o contexto já disponível, responda sem chamar a ferramenta."

## [AQUI VAI UMA IMAGEM]

Prompt da imagem:
Criar uma ilustração didática sobre controle de comportamento e uso de ferramentas por agentes. A imagem deve mostrar um agente central com três caminhos possíveis: responder diretamente, fazer uma pergunta de esclarecimento ou usar uma ferramenta externa. Cada caminho deve ter uma lógica visual de decisão, como um fluxograma simplificado. Incluir também blocos discretos indicando limites de autonomia, segurança e confirmação antes de ações sensíveis. Estilo técnico, moderno, organizado e educacional, com fundo claro e proporção 16:9.

## Resumo

Prompts para agentes precisam orientar não só a resposta final, mas também o momento de agir, perguntar, consultar ferramentas e respeitar limites.

