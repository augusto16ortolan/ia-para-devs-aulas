---
description: Fundamentos práticos para entender como LLMs funcionam sem aprofundar em matemática.
---

# Fundamentos de LLMs para devs

Antes de usar agentes, MCP ou copilotos, vale entender o básico de um LLM.

O ponto aqui não é estudar estatística nem treinamento de redes neurais. A meta é entender como o modelo responde, como ele usa contexto e por que o prompt muda tanto o resultado.

## O que interessa na prática

* **Tokens:** o modelo não lê palavras exatamente como humanos; ele trabalha com unidades menores de texto.
* **Context window:** é o espaço de contexto que o modelo consegue considerar de uma vez.
* **Prompting:** é a forma como você organiza a entrada para orientar a resposta.
* **Limites:** o modelo pode errar, simplificar demais ou inventar informações.

## Como pensar no funcionamento

Imagine que o LLM é um sistema de previsão de texto muito avançado. Ele recebe o contexto, observa o padrão da conversa e gera a continuação mais provável para a sua solicitação.

Isso ajuda a entender por que:

* instruções claras funcionam melhor;
* contexto ruim gera resposta ruim;
* mensagens longas demais podem perder informação importante;
* pequenos detalhes na escrita influenciam bastante o resultado.

## O que o aluno precisa memorizar

* o modelo não "sabe" tudo;
* ele trabalha com contexto limitado;
* o prompt influencia o comportamento;
* respostas devem ser verificadas quando o uso é técnico ou crítico.

## [AQUI VAI UMA IMAGEM]

Prompt da imagem:
Criar uma ilustração didática que explique, de forma visual e simples, como um LLM funciona na prática. A composição deve mostrar um prompt de entrada sendo quebrado em tokens, passando por uma janela de contexto representada como uma faixa ou quadro central, e gerando uma resposta de saída. Incluir elementos visuais discretos como blocos, setas, pequenas etiquetas "tokens", "context window" e "response". O estilo deve ser técnico, limpo e moderno, voltado para um material educacional para desenvolvedores, com fundo claro, boa hierarquia visual, design editorial, sem exagero futurista e sem parecer publicidade. Proporção 16:9.

## Fechamento

Se o aluno entender tokens, contexto e prompting, ele já tem a base suficiente para seguir para engenharia de prompts, copilotos e agentes.

