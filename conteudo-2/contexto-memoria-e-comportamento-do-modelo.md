---
description: Como contexto, memória e parâmetros influenciam o comportamento de um LLM.
---

# Contexto, memória e comportamento do modelo

Se existe uma ideia central para usar bem um LLM, ela é esta: **contexto importa muito**.

O modelo responde com base naquilo que está disponível na conversa ou na requisição atual. Isso inclui instruções, exemplos, histórico da interação e qualquer outro dado que tenha sido fornecido.

## O que é janela de contexto

A **context window** é o espaço total de informação que o modelo consegue considerar em uma única execução.

Esse espaço é compartilhado por vários elementos, como:

* instruções do sistema;
* prompt do usuário;
* histórico da conversa;
* documentos enviados;
* resposta que será gerada.

Quando esse espaço fica muito grande, parte da informação pode perder relevância ou nem caber mais dentro do limite.

## Contexto atual versus memória persistente

É importante diferenciar duas ideias:

* **contexto atual**: é o que está disponível naquela interação;
* **memória persistente**: é a capacidade de manter informações relevantes ao longo do tempo, quando a ferramenta oferece esse recurso.

Nem todo LLM tem memória persistente de verdade. Muitas vezes, o que parece memória é apenas reaproveitamento do histórico recente.

## Parâmetros que mudam o comportamento

Além do contexto, o comportamento do modelo também pode mudar por causa de configurações como:

* **temperatura**: influencia o nível de criatividade e variação;
* **tamanho da resposta**: pode limitar ou expandir a saída;
* **latência**: afeta a experiência de uso em tarefas interativas;
* **custo**: impacta decisões de arquitetura e escalabilidade.

Na prática, respostas mais criativas nem sempre são melhores. Em tarefas técnicas, geralmente faz mais sentido preferir consistência e previsibilidade.

## Exemplo rápido

Se você pede um resumo objetivo de um documento técnico, uma configuração mais previsível tende a funcionar melhor. Já em uma atividade de brainstorming, pode fazer sentido aceitar mais variação nas respostas.

## [AQUI VAI UMA IMAGEM]

Prompt da imagem:
Criar uma ilustração didática sobre contexto, memória e comportamento de um modelo de linguagem. A imagem deve representar uma grande janela de contexto contendo instruções, histórico, documentos e resposta, com uma distinção visual clara entre contexto temporário e memória persistente. Incluir também um pequeno painel lateral com controles conceituais como temperatura, tamanho de resposta, custo e latência. O visual deve ser técnico, elegante, claro e educacional, com fundo claro, cores suaves e composição organizada em camadas. Proporção 16:9.

## Resumo

O modelo responde com base no contexto disponível e nas configurações usadas. Entender isso ajuda a escrever melhores prompts e a prever melhor o comportamento da ferramenta.

