---
description: O que é MCP, por que existe e como ele organiza a integração de ferramentas.
---

# Introdução ao Model Context Protocol

O MCP surgiu para resolver um problema muito comum: integrar ferramentas e dados a assistentes e agentes sem criar uma integração totalmente diferente para cada caso.

## Ideia central

Em vez de cada ferramenta ser acoplada diretamente ao agente, o MCP organiza a comunicação entre:

* **client**;
* **server**;
* **tools**;
* **contexto**.

Isso facilita a expansão do sistema e deixa a integração mais padronizada.

## Por que isso importa

Sem um padrão, cada agente acaba com uma forma diferente de conversar com API, banco de dados, arquivo ou serviço externo.

Com MCP, o ecossistema fica mais organizado e previsível.

## O que o aluno precisa guardar

* MCP é um protocolo de integração;
* ele ajuda a expor capacidades como ferramentas;
* ele organiza melhor o acesso a contexto e recursos;
* ele é muito útil quando um agente precisa conversar com várias fontes.

## [AQUI VAI UMA IMAGEM]

Prompt da imagem:
Criar uma ilustração didática explicando a arquitetura cliente-servidor do MCP. A cena deve mostrar, de forma clara e horizontal, um cliente de IA, um servidor MCP no centro e três tipos de recursos conectados: uma API, um banco de dados e um sistema de arquivos. Usar setas indicando fluxo de requisição e resposta, com pequenos rótulos como "client", "MCP server", "tools" e "resources". O visual deve ser limpo, técnico e moderno, com fundo claro, linhas finas, organização em camadas e aparência educativa, sem estilo cartoon e sem excesso de texto. Proporção 16:9.

