## ProjetoBuzzfeedDecolaTech

Este projeto foi feito usando o [Angular CLI](https://github.com/angular/angular-cli) versão 19.2.1.

# Projeto que simula uma ideia como as do BuzzFeed.

- O projeto em questão simula quizz como são feitos no buzzfeed usando a mecânica de singlepage e reaproveitamento de componentes.
- No projeto eu vou estar deixando algumas variáveis de perguntas e repostas para que vocês possam estar modelando ao seu bel prazer e estar brincando também.

É só acessar o arquivo : 

```bash
quizz_question.json
```

A partir dele vocês pode colocar os questionários e alternativas seguindo o modelo inputado.

## Modelagem para se utilizar. 

<hr> 

### modelo 1
{
  "title": "Descubra se você seria um Alien",
  "questions": [
    {
      "id": 1,
      "question": "Como você se sente em relação à comida terráquea?",
      "options": [
        {"id": 1, "name": "Amo experimentar pratos diferentes", "alias": "B"},
        {"id": 2, "name": "Prefiro minha dieta especial", "alias": "A"},
        {"id": 3, "name": "Como de tudo um pouco", "alias": "B"}
      ]
    },
    {
      "id": 2,
      "question": "Qual é a sua opinião sobre viagens espaciais?",
      "options": [
        {"id": 1, "name": "Sonho em explorar o universo", "alias": "B"},
        {"id": 2, "name": "Já conheço o espaço muito bem", "alias": "A"},
        {"id": 3, "name": "Prefiro ficar na Terra", "alias": "B"}
      ]
    },
    {
      "id": 3,
      "question": "Como você reage ao encontrar algo desconhecido?",
      "options": [
        {"id": 1, "name": "Fico curioso e quero aprender mais", "alias": "B"},
        {"id": 2, "name": "Já conheço a maioria das coisas", "alias": "A"},
        {"id": 3, "name": "Evito o desconhecido", "alias": "B"}
      ]
    },
    {
      "id": 4,
      "question": "Qual seria seu disfarce perfeito na Terra?",
      "options": [
        {"id": 1, "name": "Uma pessoa comum", "alias": "A"},
        {"id": 2, "name": "Um animal de estimação", "alias": "A"},
        {"id": 3, "name": "Não preciso de disfarce", "alias": "B"}
      ]
    },
    {
      "id": 5,
      "question": "Como você se comunica com os outros?",
      "options": [
        {"id": 1, "name": "Uso a fala e gestos", "alias": "B"},
        {"id": 2, "name": "Telepatia é meu forte", "alias": "A"},
        {"id": 3, "name": "Prefiro escrever", "alias": "B"}
      ]
    }
  ],
  "results": {
    "A": "Você muito provavelmente seria um Alien!",
    "B": "Você muito provavelmente seria um Humano!"
  }
}
<hr>

 ### modelo 2

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

### modelo 3 

{
  "title": "Você seria um Mago ou um Cientista?",
  "questions": [
    {
      "id": 1,
      "question": "Como você busca conhecimento?",
      "options": [
        {"id": 1, "name": "Através de livros antigos e místicos", "alias": "A"},
        {"id": 2, "name": "Por meio de experimentos e pesquisas", "alias": "B"},
        {"id": 3, "name": "Observando o mundo ao meu redor", "alias": "B"}
      ]
    },
    {
      "id": 2,
      "question": "Qual ferramenta você prefere?",
      "options": [
        {"id": 1, "name": "Varinha mágica", "alias": "A"},
        {"id": 2, "name": "Microscópio", "alias": "B"},
        {"id": 3, "name": "Livro de feitiços", "alias": "A"}
      ]
    },
    {
      "id": 3,
      "question": "Como você resolve problemas?",
      "options": [
        {"id": 1, "name": "Com magia e encantamentos", "alias": "A"},
        {"id": 2, "name": "Com lógica e razão", "alias": "B"},
        {"id": 3, "name": "Com criatividade", "alias": "B"}
      ]
    },
    {
      "id": 4,
      "question": "O que mais te fascina no desconhecido?",
      "options": [
        {"id": 1, "name": "O mistério do sobrenatural", "alias": "A"},
        {"id": 2, "name": "As leis da natureza e do universo", "alias": "B"},
        {"id": 3, "name": "As possibilidades infinitas", "alias": "B"}
      ]
    },
    {
      "id": 5,
      "question": "Se pudesse escolher um dom, qual seria?",
      "options": [
        {"id": 1, "name": "Controlar os elementos", "alias": "A"},
        {"id": 2, "name": "Descobrir todos os segredos do universo", "alias": "B"},
        {"id": 3, "name": "Criar algo inovador", "alias": "B"}
      ]
    }
  ],
  "results": {
    "A": "Você muito provavelmente seria um Mago!",
    "B": "Você muito provavelmente seria um Cientista!"
  }
}

### modelo 4 

- aqui eu explorei colocar 3 alternativas diferentes.

{
  "title": "Você seria um Humano, um Alien ou um Robô?",
  "questions": [
    {
      "id": 1,
      "question": "Como você reage ao desconhecido?",
      "options": [
        {"id": 1, "name": "Com curiosidade, mas também cautela", "alias": "A"},
        {"id": 2, "name": "Quero explorar e entender tudo imediatamente", "alias": "B"},
        {"id": 3, "name": "Apenas analiso friamente e processo as informações", "alias": "C"}
      ]
    },
    {
      "id": 2,
      "question": "O que é mais importante para você?",
      "options": [
        {"id": 1, "name": "Emoções e conexões com os outros", "alias": "A"},
        {"id": 2, "name": "O conhecimento e a evolução", "alias": "B"},
        {"id": 3, "name": "A eficiência e a lógica", "alias": "C"}
      ]
    },
    {
      "id": 3,
      "question": "Como você toma decisões?",
      "options": [
        {"id": 1, "name": "Sigo meus instintos e sentimentos", "alias": "A"},
        {"id": 2, "name": "Analiso todas as opções e escolho a mais vantajosa", "alias": "B"},
        {"id": 3, "name": "Utilizo dados e cálculos para determinar a melhor escolha", "alias": "C"}
      ]
    },
    {
      "id": 4,
      "question": "Como você se comunica melhor?",
      "options": [
        {"id": 1, "name": "Por meio de palavras e expressões faciais", "alias": "A"},
        {"id": 2, "name": "Por telepatia ou formas não convencionais", "alias": "B"},
        {"id": 3, "name": "Através de códigos e linguagem precisa", "alias": "C"}
      ]
    },
    {
      "id": 5,
      "question": "Qual ambiente você prefere?",
      "options": [
        {"id": 1, "name": "Lugares aconchegantes e cheios de vida", "alias": "A"},
        {"id": 2, "name": "Mundos desconhecidos e misteriosos", "alias": "B"},
        {"id": 3, "name": "Ambientes tecnológicos e organizados", "alias": "C"}
      ]
    }
  ],
  "results": {
    "A": "Você muito provavelmente seria um Humano!",
    "B": "Você muito provavelmente seria um Alien!",
    "C": "Você muito provavelmente seria um Robô!"
  }
}

<hr>

# Considerações Finais.

- este foi um trabalho bem tranquilo de fazer e implementar, foi divertido e acredito que todos vão gostar.

Eu poderia ter feito muito mais coisas porém tive que seguir um pouco a risca os meus estudos no curso da DecolaTech por falta de tempo para entrega dos projetos.
Posteriormente estarei vindo em todos esses projetos e aprimorando eles mil vezes mais.



