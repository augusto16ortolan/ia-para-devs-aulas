---
description: Cuidados essenciais com dados e segurança em sistemas que usam IA.
---

# Privacidade, dados e segurança

Soluções com IA frequentemente lidam com informações sensíveis, contexto de projeto, código-fonte, documentos internos e dados de usuários.

Por isso, privacidade e segurança precisam ser tratadas como parte central da arquitetura.

## O que precisa de atenção

Alguns pontos importantes:

* quais dados estão sendo enviados ao modelo;
* quem pode acessar esses dados;
* quais ferramentas têm permissão de leitura ou escrita;
* como entradas externas são tratadas;
* que tipo de risco existe em prompts maliciosos.

## Prompt injection

Um tema importante aqui é o **prompt injection**.

Em termos simples, isso acontece quando instruções maliciosas ou indevidas tentam desviar o comportamento esperado do sistema.

Esse risco cresce quando o agente:

* lê conteúdo externo;
* acessa documentos não confiáveis;
* usa ferramentas com autonomia;
* mistura contexto seguro com contexto não validado.

## Exemplo rápido

Se um agente lê um documento externo e esse documento tenta induzir o sistema a ignorar regras anteriores, o comportamento final pode ficar comprometido.

## [AQUI VAI UMA IMAGEM]

Prompt da imagem:
Criar uma ilustração didática sobre privacidade, dados e segurança em sistemas com IA. A imagem deve mostrar um agente ou assistente conectado a documentos, banco de dados, arquivos e APIs, passando por camadas visuais de proteção como permissões, validação, privacidade e defesa contra prompt injection. O estilo deve ser técnico, moderno, limpo e educacional, com fundo claro e proporção 16:9.

## Resumo

Privacidade, segurança e proteção contra prompt injection são parte essencial de qualquer solução séria com IA. Não são detalhes adicionais, mas parte da base do sistema.

