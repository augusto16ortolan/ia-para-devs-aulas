---
description: Componentes mínimos que ajudam a estruturar um servidor MCP.
---

# Estrutura básica de um servidor MCP

Antes de pensar em recursos avançados, vale entender a estrutura mínima de um servidor MCP.

## O que normalmente existe no projeto

Mesmo em exemplos pequenos, costuma haver pelo menos:

* inicialização do servidor;
* definição das capacidades expostas;
* lógica de entrada e saída;
* conexão com algum recurso interno ou externo;
* tratamento básico de erros.

## Pensando em responsabilidades

Uma forma simples de organizar esse tipo de projeto é separar:

* o que expõe a interface do servidor;
* o que implementa a regra da tool ou do resource;
* o que conversa com API, banco ou arquivo;
* o que valida entrada e organiza a resposta.

Isso ajuda a manter o código mais legível e mais fácil de evoluir.

## Contrato entre cliente e servidor

Outro ponto importante é pensar em contrato.

O cliente precisa entender:

* o nome da capacidade exposta;
* quais parâmetros ela espera;
* que tipo de retorno ela produz;
* o que acontece em caso de erro.

## Exemplo rápido

Se uma tool recebe um `id_cliente`, o servidor precisa deixar claro:

* que esse parâmetro é necessário;
* qual formato ele deve ter;
* o que será retornado se o cliente existir;
* o que acontece se o valor vier inválido.

## [AQUI VAI UMA IMAGEM]

Prompt da imagem:
Criar uma ilustração didática da estrutura básica de um servidor MCP. A imagem deve mostrar o projeto dividido em blocos como inicialização do servidor, definição de capabilities, camada de validação, lógica de negócio e acesso a recursos externos. Usar um layout em camadas ou módulos, com setas indicando responsabilidades e fluxo interno. O estilo deve ser técnico, moderno, limpo e adequado para ensino de arquitetura de software, com fundo claro e proporção 16:9.

## Resumo

A estrutura básica de um servidor MCP gira em torno de inicialização, exposição de capacidades, validação e integração com recursos. Mesmo num projeto pequeno, essa organização já faz diferença.

