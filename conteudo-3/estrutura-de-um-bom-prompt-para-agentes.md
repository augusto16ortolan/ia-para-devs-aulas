---
description: Componentes que ajudam a estruturar prompts mais úteis para agentes.
---

# Estrutura de um bom prompt para agentes

Um bom prompt para agentes não precisa ser gigante, mas precisa ser organizado.

Na prática, ele costuma funcionar melhor quando deixa claro o papel do sistema, o objetivo, os limites e o formato esperado da resposta.

## Componentes comuns

Entre os blocos mais importantes, vale destacar:

* **System prompt:** define regras, postura, escopo e comportamento geral;
* **User prompt:** traz a tarefa ou necessidade atual do usuário;
* **instruções de ferramenta:** dizem quando e como usar capacidades externas;
* **formato de saída:** ajuda a manter a resposta organizada;
* **restrições:** evitam comportamento exagerado ou inadequado.

## Papel e objetivo

Dois elementos fazem muita diferença:

* dizer quem o agente deve ser naquele contexto;
* dizer o que exatamente ele deve tentar resolver.

Isso ajuda o modelo a organizar melhor a resposta e reduz ambiguidades.

## Formato de saída

Muitas respostas melhoram bastante quando o prompt já informa a estrutura esperada, por exemplo:

* resumo curto;
* lista de riscos;
* resposta em etapas;
* tabela comparativa;
* saída em JSON.

Quando o formato é importante, vale dizer isso desde o começo.

## Exemplo rápido

Em vez de pedir:

* "Analise isso."

você pode pedir:

* "Analise este problema como um assistente técnico. Explique a causa provável, os riscos e os próximos passos em até 5 tópicos."

Essa pequena mudança já melhora bastante a previsibilidade da resposta.

## [AQUI VAI UMA IMAGEM]

Prompt da imagem:
Criar uma ilustração didática mostrando a estrutura de um bom prompt para agentes. A imagem deve apresentar um grande bloco de prompt dividido visualmente em seções como system prompt, user prompt, tool instructions, restrições e formato de saída. Cada seção deve estar claramente rotulada com design limpo e setas apontando para um agente de IA no lado direito. O estilo deve ser técnico, moderno, minimalista e muito claro para fins educacionais, com fundo claro, excelente organização visual e proporção 16:9.

## Resumo

Um bom prompt para agentes costuma combinar papel, objetivo, limites, instruções de ferramenta e formato de saída. A organização importa tanto quanto o conteúdo.

