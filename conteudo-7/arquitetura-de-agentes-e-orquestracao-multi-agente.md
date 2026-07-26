---
description: Como agentes raciocinam, usam ferramentas e se organizam em conjunto.
---

# Arquitetura de agentes e orquestração multiagente

Um agente é mais do que um chatbot com outro nome.

Ele recebe um objetivo, decide um próximo passo, pode usar ferramentas e tenta continuar até chegar a um resultado útil.

## O loop básico

Em termos simples, o agente costuma seguir um ciclo parecido com:

* pensar no problema;
* escolher uma ação;
* usar uma ferramenta, se necessário;
* observar o retorno;
* decidir o próximo passo.

Esse fluxo aparece em abordagens como ReAct e tool-calling.

## Quando usar um agente único

* quando a tarefa é simples;
* quando o número de ferramentas é pequeno;
* quando o controle precisa ser mais previsível;
* quando a comunicação entre vários agentes não traria benefício real.

## Quando usar vários agentes

* quando há especializações claras;
* quando cada agente pode cuidar de uma parte do problema;
* quando a tarefa tem muitas etapas diferentes;
* quando faz sentido ter um orquestrador coordenando a equipe.

## Exemplo rápido

Um agente único pode resolver bem uma tarefa de consulta e resumo. Já um fluxo com vários agentes pode fazer mais sentido quando um agente pesquisa, outro analisa e outro monta a resposta final.

## O que o aluno deve guardar

* agente tem objetivo e ação;
* o loop de raciocínio e ação ajuda a entender o comportamento;
* multiagente só vale quando a divisão de responsabilidades compensa;
* mais agentes nem sempre significam mais qualidade.

## [AQUI VAI UMA IMAGEM]

Prompt da imagem:
Criar uma ilustração didática sobre arquitetura de agentes e orquestração multiagente. A imagem deve mostrar, em uma composição clara, um agente principal executando um loop de raciocínio e ação, com setas circulares entre "think", "act" e "observe", e, ao lado, uma equipe de três agentes especializados coordenados por um orquestrador central. Incluir pequenas indicações visuais de tool-calling e function-calling, com estilo técnico, moderno e profissional, fundo claro, alta legibilidade e sem aparência cartunesca. Proporção 16:9.

## Resumo

Agentes recebem objetivos, executam ações e podem usar ferramentas. Quando a tarefa fica mais complexa, faz sentido pensar em orquestração e especialização.

