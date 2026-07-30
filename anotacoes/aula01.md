# Aula 01 — Engenharia de Requisitos

**Data:** 27/07/2026  
**Professor:** Ana Cristine

> **Ideia principal da aula:** antes de desenvolver um sistema, precisamos entender corretamente **qual problema deve ser resolvido**, **quem usará o sistema** e **o que ele precisa fazer**.


## 1. O que é um requisito?

Um **requisito** é uma condição, necessidade ou capacidade que o sistema precisa possuir.

### Exemplos

- O sistema deve permitir o cadastro de clientes.
- O usuário deve conseguir redefinir sua senha.
- O sistema deve responder em até dois segundos.
- Apenas funcionários autorizados podem acessar os dados.

> **Requisito é algo que o sistema precisa fazer ou respeitar.**

## 2. Engenharia de Requisitos

A **Engenharia de Requisitos** é o conjunto de atividades utilizadas para:

- descobrir as necessidades dos usuários;
- entender o objetivo do sistema;
- analisar as informações coletadas;
- documentar os requisitos;
- verificar se os requisitos estão corretos;
- controlar alterações ao longo do projeto.

### Exemplo

Uma clínica pede:

> “Queremos um sistema para organizar consultas.”

A Engenharia de Requisitos ajuda a descobrir:

- quem pode marcar consultas;
- quem pode cancelar;
- como os horários serão organizados;
- se o sistema enviará lembretes;
- quais dados precisam ser protegidos.

## 3. Análise de Requisitos

A **Análise de Requisitos** é uma parte da Engenharia de Requisitos.

Sua função é refinar as necessidades e restrições apresentadas pelo usuário, transformando ideias vagas em informações mais claras e precisas.

### Exemplo

Pedido inicial:

> “O sistema precisa ser rápido.”

Depois da análise:

> “O sistema deve apresentar o resultado da busca em até dois segundos.”

> **Analisar requisitos é estudar, esclarecer e detalhar o que foi solicitado.**

## 4. Diferença entre os conceitos

| Conceito                     | Significado                                                                          |
| ---------------------------- | ------------------------------------------------------------------------------------ |
| **Requisito**                | Uma necessidade, capacidade ou restrição do sistema                                  |
| **Análise de Requisitos**    | Processo de estudar e refinar as necessidades coletadas                              |
| **Engenharia de Requisitos** | Processo completo de descobrir, analisar, documentar, validar e gerenciar requisitos |

### Forma fácil de lembrar

Imagine a organização de uma festa:

- **Engenharia de Requisitos:** organizar toda a festa;
- **Análise de Requisitos:** analisar os pedidos dos convidados;
- **Requisito:** “precisa ter bolo de chocolate”.

# 5. Princípios que guiam o processo

## 5.1 Seja ágil

Ser ágil não significa fazer tudo correndo.

Significa:

- trabalhar em pequenas etapas;
- receber feedback frequentemente;
- corrigir problemas rapidamente;
- adaptar o projeto quando necessário.

> **Agilidade é entregar, avaliar e melhorar.**

## 5.2 Foque na qualidade em cada etapa

A qualidade não deve ser verificada apenas quando o sistema estiver pronto.

Cada atividade precisa produzir um resultado de qualidade.

Um requisito mal escrito pode gerar:

- código errado;
- testes errados;
- atrasos;
- desperdício de dinheiro;
- um sistema diferente do esperado.

## 5.3 Esteja preparado para se adaptar

Projetos de software podem mudar.

As mudanças podem ocorrer porque:

- o cliente descobriu uma nova necessidade;
- uma lei foi alterada;
- uma tecnologia deixou de ser adequada;
- o orçamento ou prazo mudou;
- os usuários deram novos feedbacks.

> O planejamento é importante, mas não deve impedir a adaptação.

## 5.4 Construa uma equipe eficaz

Uma equipe eficaz:

- comunica-se bem;
- divide responsabilidades;
- coopera;
- resolve conflitos;
- organiza o próprio trabalho.

> Uma boa tecnologia não salva uma equipe que não se comunica.

## 5.5 Estabeleça mecanismos de comunicação e coordenação

Muitos projetos falham porque informações são perdidas ou interpretadas de maneiras diferentes.

A equipe pode utilizar:

- reuniões;
- registros das decisões;
- documentação;
- ferramentas de acompanhamento;
- validação com os stakeholders.

### Stakeholders

**Stakeholders** são todas as pessoas ou organizações interessadas ou afetadas pelo sistema.

Exemplos:

- clientes;
- usuários;
- desenvolvedores;
- gestores;
- equipe jurídica;
- órgãos reguladores.

## 5.6 Gerencie as mudanças

Uma solicitação de mudança deve ser:

1. registrada;
2. analisada;
3. avaliada;
4. aprovada ou rejeitada;
5. implementada;
6. acompanhada.

Antes de implementar, a equipe deve avaliar:

- impacto no prazo;
- custo;
- riscos;
- partes do sistema afetadas;
- prioridade.


## 5.7 Avalie os riscos

Um **risco** é um acontecimento incerto que pode prejudicar o projeto.

### Exemplos

- atraso na entrega;
- falta de orçamento;
- saída de um integrante da equipe;
- requisitos mal compreendidos;
- falha de uma tecnologia;
- baixa participação do cliente.

A equipe deve criar um **plano de contingência**, ou seja, decidir antes o que fará caso o risco aconteça.

## 5.8 Produza materiais que tenham valor

A equipe deve criar apenas documentos, modelos ou diagramas que realmente ajudem o projeto.

Exemplos:

- documento de requisitos;
- protótipo;
- diagrama;
- lista de prioridades;
- caso de uso;
- modelo de processo.

> Não devemos criar documentos apenas por obrigação. Eles precisam ser úteis.

# 6. As sete fases da Engenharia de Requisitos

1. **Concepção**
2. **Levantamento**
3. **Elaboração**
4. **Negociação**
5. **Especificação**
6. **Validação**
7. **Gerenciamento de Requisitos**

Uma forma apresentada no slide para memorizar é:

> **COLEN ESVAGE**

## 6.1 Concepção

É o momento em que uma necessidade de negócio é identificada.

A equipe começa a entender:

- qual problema existe;
- por que o sistema é necessário;
- quem está envolvido;
- quais são os objetivos iniciais.

> **Concepção = perceber que existe um problema ou oportunidade.**

## 6.2 Levantamento

Também pode ser chamado de **elicitação de requisitos**.

É a fase de conversar com usuários e stakeholders para descobrir suas necessidades.

Técnicas possíveis:

- entrevistas;
- questionários;
- observação;
- brainstorming;
- workshops;
- protótipos;
- casos de uso.

> **Levantamento = descobrir o que as pessoas precisam.**

## 6.3 Elaboração

Na elaboração, as informações coletadas são detalhadas e refinadas.

A equipe cria cenários que representam como os usuários irão interagir com o sistema.

> **Elaboração = transformar ideias em cenários mais detalhados.**

## 6.4 Negociação

Nem todos os requisitos poderão ser implementados imediatamente.

Durante a negociação, a equipe deve:

- discutir conflitos;
- ordenar requisitos;
- definir prioridades;
- alinhar expectativas;
- decidir o que será feito primeiro.

> **Negociação = decidir o que realmente será feito.**


## 6.5 Especificação

É a fase de documentar os requisitos de forma clara e precisa.

A especificação pode utilizar:

- texto;
- diagramas;
- modelos;
- casos de uso;
- histórias de usuário;
- protótipos.

### Exemplo ruim

> “O sistema deve ser fácil.”

### Exemplo melhor

> “Um usuário deve conseguir concluir o cadastro em até três minutos.”

> **Especificação = registrar claramente o que foi decidido.**

## 6.6 Validação

A validação verifica se os requisitos estão corretos e representam as necessidades reais dos usuários.

A equipe procura eliminar:

- ambiguidades;
- inconsistências;
- omissões;
- conflitos;
- erros.

### Perguntas de validação

- O requisito está claro?
- Ele pode ser testado?
- Está completo?
- É possível implementá-lo?
- Representa o que o cliente precisa?
- Contradiz algum outro requisito?

> **Validação = confirmar que estamos construindo a coisa certa.**

## 6.7 Gerenciamento de Requisitos

O gerenciamento acompanha os requisitos durante todo o ciclo de vida do projeto.

Ele envolve:

- registrar requisitos;
- analisar alterações;
- controlar versões;
- acompanhar prioridades;
- manter a rastreabilidade;
- verificar o estado de cada requisito.

### Rastreabilidade

Rastreabilidade é a capacidade de acompanhar um requisito desde sua origem até sua implementação e seus testes.

> **Gerenciamento = acompanhar os requisitos e suas mudanças durante o projeto.**

# 7. Exemplo completo

Imagine que uma biblioteca deseja criar um aplicativo.

## Concepção

A biblioteca identifica o problema:

> Os usuários enfrentam filas para renovar livros.

## Levantamento

A equipe descobre que o sistema deve:

- permitir renovação;
- mostrar a data de devolução;
- avisar sobre atrasos;
- impedir renovação quando houver reserva.

## Elaboração

A equipe descreve como o usuário fará a renovação.

## Negociação

O envio de notificações por SMS é considerado caro.

A equipe decide começar apenas com notificações no aplicativo.

## Especificação

> “O sistema deve permitir a renovação de um livro, desde que ele não esteja atrasado ou reservado por outro usuário.”

## Validação

Bibliotecários e usuários verificam se o requisito está correto.

## Gerenciamento

Quando a biblioteca decidir adicionar notificações por e-mail, a mudança será registrada e analisada.

# 8. Conceitos principais

- **Requisito:** necessidade, condição ou capacidade do sistema.
- **Análise de Requisitos:** refinamento das necessidades coletadas.
- **Engenharia de Requisitos:** conjunto completo de atividades relacionadas aos requisitos.
- **Stakeholder:** pessoa ou organização interessada ou afetada pelo sistema.
- **Risco:** situação incerta que pode prejudicar o projeto.
- **Validação:** verificação de que os requisitos estão corretos.
- **Gerenciamento:** controle e acompanhamento dos requisitos e de suas mudanças.
