---
description: Formas comuns de conectar agentes a sistemas externos.
---

# Principais formas de integração

Existem diferentes formas de conectar agentes a ferramentas externas. Nesta disciplina, duas ideias aparecem com bastante destaque: MCP e function calling direto.

## MCP

O MCP organiza a exposição de tools, resources e prompts por meio de uma camada mais padronizada.

Isso tende a ajudar quando:

* existem várias capacidades;
* mais de um cliente pode consumir o mesmo servidor;
* a arquitetura precisa crescer com mais organização.

## Function calling direto

Em alguns cenários, o agente pode usar chamadas diretas para funções ou operações definidas localmente.

Essa abordagem pode ser suficiente quando:

* o fluxo é pequeno;
* o número de operações é baixo;
* a solução ainda está em estágio inicial;
* a integração é bem específica.

## Outras possibilidades

Dependendo da arquitetura, também pode haver integração por:

* APIs REST;
* banco de dados;
* sistema de arquivos;
* filas e eventos;
* serviços internos especializados.

## Exemplo rápido

Se a aplicação precisa apenas de duas operações simples, uma integração direta pode bastar. Mas, se várias ferramentas começarem a ser usadas por múltiplos clientes, o MCP tende a fazer mais sentido.

## [AQUI VAI UMA IMAGEM]

Prompt da imagem:
Criar uma ilustração didática comparando principais formas de integração de agentes com ferramentas externas. A imagem deve mostrar um agente conectado a ferramentas por dois caminhos principais: MCP e function calling direto. Também incluir discretamente APIs, bancos, arquivos e serviços internos como destinos possíveis. O estilo deve ser técnico, limpo, moderno e educacional, com fundo claro, composição comparativa bem organizada e proporção 16:9.

## Resumo

MCP e function calling direto são duas formas importantes de integração. A escolha depende do tamanho do problema, da quantidade de ferramentas e da necessidade de organização arquitetural.

