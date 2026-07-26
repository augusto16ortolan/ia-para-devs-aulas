---
description: Motivação do MCP e o problema que ele tenta resolver.
---

# O que é MCP e por que ele existe

O MCP, ou **Model Context Protocol**, surgiu para resolver um problema que aparece com frequência quando sistemas de IA começam a interagir com ferramentas externas.

Sem um padrão, cada integração tende a ser construída de um jeito diferente. Isso pode funcionar no começo, mas fica mais confuso à medida que o número de ferramentas cresce.

## O problema sem padrão

Imagine um agente que precisa acessar:

* uma API de vendas;
* um banco de dados;
* arquivos locais;
* documentação interna;
* um serviço externo de busca.

Se cada integração for montada de forma isolada, o sistema tende a ficar:

* mais acoplado;
* mais difícil de manter;
* mais difícil de escalar;
* menos previsível.

## A ideia central do MCP

O MCP propõe um jeito mais organizado de expor capacidades para clientes de IA.

Em vez de cada ferramenta “falar” diretamente com o agente de um jeito próprio, o protocolo ajuda a padronizar como essas capacidades são apresentadas e consumidas.

## Por que isso importa para desenvolvimento

Para quem trabalha com software, isso significa:

* mais clareza arquitetural;
* mais reaproveitamento;
* mais organização nas integrações;
* menos improviso conforme o sistema cresce.

## Exemplo rápido

Se um assistente precisa consultar clientes, ler um arquivo e buscar dados em uma API, o MCP ajuda a organizar essas capacidades dentro de uma estrutura mais consistente, em vez de criar uma ponte diferente para cada caso.

## [AQUI VAI UMA IMAGEM]

Prompt da imagem:
Criar uma ilustração didática mostrando o problema que o MCP resolve. A imagem deve comparar dois cenários: à esquerda, várias integrações diretas e confusas entre um agente e múltiplas ferramentas externas; à direita, um cenário organizado em que um servidor MCP centraliza e padroniza o acesso às mesmas ferramentas. O visual deve enfatizar contraste entre bagunça arquitetural e organização modular. Estilo técnico, editorial e limpo, com fundo claro, setas visíveis e composição horizontal em 16:9.

## Resumo

O MCP existe porque integrar ferramentas com IA sem padrão tende a gerar acoplamento e confusão. O protocolo ajuda a organizar essa comunicação de forma mais previsível.

