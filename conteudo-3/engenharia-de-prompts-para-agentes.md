---
description: Como mudar o prompt quando o objetivo deixa de ser apenas conversa e passa a ser comportamento de agente.
---

# Engenharia de prompts para agentes

Prompt de chatbot e prompt de agente não são a mesma coisa.

Um chatbot normalmente responde perguntas. Um agente, por outro lado, recebe um objetivo, pode usar ferramentas e precisa manter um comportamento mais controlado.

## O que muda

Em prompts para agentes, costuma ser importante explicitar:

* papel do agente;
* objetivo principal;
* limites de ação;
* ferramentas disponíveis;
* quando agir e quando perguntar;
* como responder ao final.

## Componentes comuns

* **System prompt:** define comportamento geral, regras e postura.
* **User prompt:** traz a tarefa ou a demanda do usuário.
* **Tool instructions:** explicam quando e como usar ferramentas externas.
* **Controle de saída:** ajuda a manter o formato esperado.

## Boas práticas

* ser claro sobre a função do agente;
* evitar instruções ambíguas;
* limitar excessos de autonomia;
* orientar o formato de resposta;
* deixar explicitado quando a ferramenta deve ser usada.

## [AQUI VAI UMA IMAGEM]

Prompt da imagem:
Criar uma ilustração comparando visualmente um prompt de chatbot e um prompt de agente. A imagem deve ter duas colunas lado a lado. Na primeira, um chatbot recebendo uma pergunta simples e respondendo texto. Na segunda, um agente com system prompt, instruções de ferramentas e uma pequena lista de ações possíveis, mostrando que ele planeja antes de responder. Destacar visualmente os blocos "system", "user" e "tools" com design limpo e didático. O estilo deve ser moderno, profissional, claro e organizado, com fundo claro, tipografia discreta e cores suaves. Proporção 16:9.

## O que evitar

* prompts muito vagos;
* pedir para o agente fazer "tudo";
* instruções contraditórias;
* liberar ferramentas sem necessidade;
* respostas sem formato definido quando o fluxo exigir padrão.

