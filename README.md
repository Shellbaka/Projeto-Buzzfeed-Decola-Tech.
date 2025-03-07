# ProjetoBuzzfeedDecolaTech


## Projeto que simula uma ideia como as do BuzzFeed.

- O projeto em questão simula quizz como são feitos no buzzfeed usando a mecânica de singlepage e reaproveitamento de componentes.
- No projeto eu vou estar deixando algumas variáveis de perguntas e repostas para que vocês possam estar modelando ao seu bel prazer e estar brincando também.

É só acessar o arquivo : 

```bash
quizz_question.json
```

A partir dele vocês podem colocar os questionários e alternativas seguindo o modelo inputado.

# 📜 Questionários Interativos

Este repositório contém diferentes modelos de quizzes interativos em formato JSON, projetados para classificar respostas e gerar resultados personalizados.

## 📝 Modelos Disponíveis

Aqui estão alguns dos modelos implementados:

### 🛸 Modelo 1: "Descubra se você seria um Alien"
Um questionário divertido para determinar se você tem mais características de um humano ou de um alienígena.

### ☠️ Modelo 2: "Você seria um Pirata ou um Marinheiro?"
Descubra se sua personalidade se encaixa melhor como um aventureiro destemido dos mares ou um marinheiro disciplinado.

### 🧙‍♂️ Modelo 3: "Você seria um Mago ou um Cientista?"
Um quiz para explorar se você se inclina mais para o misticismo ou para a ciência e lógica.

### 🤖 Modelo 4: "Você seria um Humano, um Alien ou um Robô?"
Neste questionário, há três alternativas para descobrir se seu jeito de pensar se alinha mais com a emoção humana, a curiosidade alienígena ou a lógica robótica.

## 📂 Estrutura dos Arquivos
Cada quiz segue um formato JSON estruturado da seguinte maneira:

```json
{
  "title": "Título do Quiz",
  "questions": [
    {
      "id": 1,
      "question": "Pergunta aqui",
      "options": [
        {"id": 1, "name": "Opção 1", "alias": "A"},
        {"id": 2, "name": "Opção 2", "alias": "B"}
      ]
    }
  ],
  "results": {
    "A": "Resultado para A",
    "B": "Resultado para B"
  }
}
```

## 🚀 Melhorias Futuras
Este projeto foi desenvolvido dentro do programa DecolaTech, e devido ao prazo de entrega, algumas funcionalidades não foram totalmente exploradas. No futuro, pretendo aprimorar esses quizzes, adicionando mais funcionalidades e refinando a lógica de pontuação.

## 💡 Considerações Finais
Criar esses quizzes foi uma experiência divertida e educativa. Espero que vocês gostem e se divirtam tanto quanto eu ao desenvolvê-los! 😃

Este projeto foi feito usando o [Angular CLI](https://github.com/angular/angular-cli) versão 19.2.1.
---

📌 *Sinta-se à vontade para contribuir ou sugerir melhorias!*

## Vou deixar um exemplo de bonus aqui para vocês aproveitarem.

```json
{
  "title": "Você seria um Pirata ou um Marinheiro?",
  "questions": [
    {
      "id": 1,
      "question": "O que mais te atrai no mar?",
      "options": [
        {"id": 1, "name": "Aventura e tesouros", "alias": "A"},
        {"id": 2, "name": "Disciplina e ordem", "alias": "B"},
        {"id": 3, "name": "A beleza das paisagens", "alias": "B"}
      ]
    },
    {
      "id": 2,
      "question": "Como você lida com regras?",
      "options": [
        {"id": 1, "name": "Regras foram feitas para serem quebradas", "alias": "A"},
        {"id": 2, "name": "Sigo-as à risca", "alias": "B"},
        {"id": 3, "name": "Depende da situação", "alias": "B"}
      ]
    },
    {
      "id": 3,
      "question": "Qual seria sua arma preferida?",
      "options": [
        {"id": 1, "name": "Espada", "alias": "A"},
        {"id": 2, "name": "Canhão", "alias": "B"},
        {"id": 3, "name": "Mosquete", "alias": "B"}
      ]
    },
    {
      "id": 4,
      "question": "O que você faria ao encontrar um navio inimigo?",
      "options": [
        {"id": 1, "name": "Atacaria sem hesitar", "alias": "A"},
        {"id": 2, "name": "Seguiria ordens superiores", "alias": "B"},
        {"id": 3, "name": "Avalio a situação antes de agir", "alias": "B"}
      ]
    },
    {
      "id": 5,
      "question": "Qual é o seu maior desejo?",
      "options": [
        {"id": 1, "name": "Liberdade total", "alias": "A"},
        {"id": 2, "name": "Servir meu país", "alias": "B"},
        {"id": 3, "name": "Explorar o mundo", "alias": "B"}
      ]
    }
  ],
  "results": {
    "A": "Você muito provavelmente seria um Pirata!",
    "B": "Você muito provavelmente seria um Marinheiro!"
  }
}

```
