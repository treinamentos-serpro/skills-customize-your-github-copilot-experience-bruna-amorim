# Guia de criação de tarefas

Este documento reúne as regras e boas práticas para criar novas tarefas no portal educacional.

## Objetivo da tarefa

Toda tarefa deve ajudar o aluno a praticar um conceito de programação de forma clara e incremental. O foco deve ser a aprendizagem, não apenas a exigência de código.

## Estrutura obrigatória

Cada tarefa deve seguir esta organização:

- pasta em `assignments/`
- arquivo `README.md`
- `starter-code.py` quando necessário
- materiais extras somente se forem relevantes

## Modelo de README

O `README.md` deve seguir o template em `templates/assignment-template.md`.

### Estrutura esperada

```md
# 📘 Atividade: [Título da Atividade]

## 🎯 Objetivo

[Descrição do objetivo]

## 📝 Tarefas

### 🛠️ [Título da Tarefa]

#### Descrição
[Descrição clara do que o aluno deve fazer]

#### Requisitos
O programa concluído deve:

- [Requisito 1]
- [Requisito 2]
- [Requisito 3]
```

## Boas práticas

- use títulos curtos e objetivos claros
- apresente de 2 a 3 tarefas por atividade
- escreva requisitos específicos e verificáveis
- mantenha a linguagem motivadora e acessível
- prioritize exemplos simples e fáceis de entender
- evite instruções ambíguas ou excessivamente longas

## Padrões para arquivos auxiliares

### `starter-code.py`

O código inicial deve:

- ser funcional
- ter comentários curtos quando necessário
- conter apenas a base mínima para o aluno completar a tarefa
- facilitar o entendimento sem entregar a solução completa

## Exemplo de boa tarefa

Uma tarefa boa normalmente:

1. ensina um conceito central
2. exige a aplicação prática do conceito
3. tem requisitos mensuráveis
4. pode ser resolvida em um tempo adequado
5. prepara o aluno para o próximo nível de dificuldade

## Checklist final

Antes de finalizar uma tarefa, confirme:

- a pasta está em `assignments/`
- existe `README.md`
- o template foi respeitado
- os objetivos estão claros
- as tarefas são bem definidas
- o nível de dificuldade está adequado
- o material está pronto para ser publicado


# Assignment Design Guide

Orientações para desenhar conteúdo de assignment: o que ensinar e como definir o escopo. Para formatação e estrutura em markdown, os arquivos de instruções do projeto já tratam isso automaticamente.

## Difficulty & Scope

- Defina de 2 a 4 tarefas por assignment que evoluam entre si
- Comece com algo que um aluno consiga terminar em menos de 10 minutos e depois aumente a complexidade
- A última tarefa pode ser um objetivo ambicioso, mas as anteriores devem construir confiança
- Foque em um conceito central por assignment (ex.: "loops", não "loops + file I/O + error handling")

## Starter Code

Inclua starter code quando:

- A assignment precisar de boilerplate que o estudante não deve escrever do zero
- Você quiser que os estudantes sigam uma assinatura de função ou estrutura específica

Evite quando o objetivo for escrever algo do zero (ex.: "write a script that...").

## Exemplos de Tópicos por Dificuldade

- **Beginner**: variables, conditionals, loops, string formatting
- **Intermediate**: functions, lists/dicts, file I/O, basic classes
- **Advanced**: APIs, data analysis, testing, web frameworks