---
description: Como pensar em tools e resources ao implementar um servidor MCP.
---

# Expondo ferramentas e recursos

O coração de um servidor MCP está nas capacidades que ele oferece.

Na prática, isso costuma aparecer principalmente como tools e resources.

## Expondo uma tool

Uma tool faz sentido quando o cliente precisa acionar uma operação.

Por exemplo:

* consultar dados;
* buscar registros;
* transformar uma informação;
* executar uma rotina segura e bem definida.

## Expondo um resource

Um resource faz sentido quando o objetivo é disponibilizar contexto ou dados para consulta.

Isso pode incluir:

* documentos;
* arquivos locais;
* conteúdos de apoio;
* conjuntos de dados estáticos ou semiestáticos.

## O que faz sentido expor

Nem tudo precisa virar tool ou resource.

Vale pensar:

* essa capacidade é realmente útil para o cliente?
* o nome dela está claro?
* a entrada faz sentido?
* a resposta será útil e compreensível?

## Tratamento de erro e resposta clara

Mesmo num exemplo simples, vale planejar:

* o que acontece se faltar parâmetro;
* o que acontece se o recurso não responder;
* como devolver um erro que o cliente consiga entender.

## Exemplo rápido

Uma tool chamada `buscar_pedido` pode receber um número de pedido e devolver o status atual. Já um resource pode expor uma tabela ou documento com regras internas de operação.

## [AQUI VAI UMA IMAGEM]

Prompt da imagem:
Criar uma ilustração didática comparando tools e resources em um servidor MCP. A imagem deve mostrar dois blocos centrais: um representando ações operacionais, como consultar ou buscar dados, e outro representando recursos de contexto, como arquivos e documentos. Conectar esses blocos a um servidor MCP e a um cliente de IA, destacando a diferença entre operar e consultar. O estilo deve ser técnico, educacional e moderno, com fundo claro, composição organizada e proporção 16:9.

## Resumo

Tools e resources ajudam a organizar o que o servidor oferece. A escolha entre um e outro depende do tipo de capacidade que o cliente precisa consumir.

