---
description: Cuidados fundamentais ao permitir que agentes usem ferramentas externas.
---

# Segurança, controle e previsibilidade

Dar acesso a ferramentas externas não é uma decisão pequena.

Quando um agente pode consultar ou acionar sistemas reais, entram em cena preocupações como segurança, rastreabilidade e impacto operacional.

## Cuidados básicos

Entre os cuidados mais importantes, vale destacar:

* controlar permissões;
* validar entradas;
* limitar impacto de operações perigosas;
* tratar erros e timeouts;
* registrar logs e auditoria.

## O risco do acesso amplo demais

Se o agente recebe acesso sem limites claros, podem surgir problemas como:

* consulta de dados sensíveis sem necessidade;
* chamadas indevidas;
* ações perigosas;
* comportamento difícil de rastrear;
* custo inesperado.

## Previsibilidade importa

Uma boa integração não é apenas “funciona”. Ela também precisa ser previsível.

Isso significa que o agente deve saber:

* quando usar a ferramenta;
* como chamar a ferramenta;
* o que esperar de resposta;
* quando interromper e pedir confirmação.

## Exemplo rápido

Consultar um banco em modo leitura é bem diferente de permitir alterações sem confirmação. A forma como a capacidade é exposta muda bastante o nível de risco.

## [AQUI VAI UMA IMAGEM]

Prompt da imagem:
Criar uma ilustração didática sobre segurança, controle e previsibilidade em integrações de agentes com ferramentas externas. A imagem deve mostrar um agente conectado a sistemas externos, mas passando por camadas visuais de permissão, validação, logs, limites de ação e confirmação. O objetivo é transmitir a ideia de integração segura e controlada. O estilo deve ser técnico, moderno, limpo e educacional, com fundo claro e proporção 16:9.

## Resumo

Integrar agentes com ferramentas externas exige controle. Segurança, validação, logs e previsibilidade são partes centrais da solução, não detalhes opcionais.

