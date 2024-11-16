# Usando recuroso de tradução, texto e fala com IA no Microsoft Azure.

* Utlezei dois recursos disponíveis dentro de cada studio (Idioma e Fala);

  # - IA de Fala:
  * Aplicação utilzada foi a de trascrever áudio em texto.
    - Foi selecionado um audio do WhatsApp para efetuar a trasncição
    - Aplicação que pode ser aplicada de forma estratégica para inclusão de pessoal com empresas e serviços do dia a dia.
    - Veja a imagem e o JSON da aplicação teste:
      
  
![image](https://github.com/user-attachments/assets/0d76e8da-3929-4b57-a76f-5dc31e14643f)

JSON:
[
    {
        "Id": "ca1a886b4e4645658c8b448fb2b6c50a",
        "RecognitionStatus": 0,
        "Offset": 5100000,
        "Duration": 78000000,
        "Channel": 0,
        "DisplayText": "A hora que você estiver voltando de carro, passa lá na natação e pega o João, porque o João quer ir no atletismo com você.",
        "NBest": [
            {
                "Confidence": 0.7985899,
                "Lexical": "a hora que você estiver voltando de carro passa lá na natação e pega o joão porque o joão quer ir no atletismo com você",
                "ITN": "a hora que você estiver voltando de carro passa lá na natação e pega o joão porque o joão quer ir no atletismo com você",
                "MaskedITN": "a hora que você estiver voltando de carro passa lá na natação e pega o joão porque o joão quer ir no atletismo com você",
                "Display": "A hora que você estiver voltando de carro, passa lá na natação e pega o João, porque o João quer ir no atletismo com você.",
                "Words": [
                    {
                        "Word": "a",
                        "Offset": 5100000,
                        "Duration": 2800000
                    },
                    {
                        "Word": "hora",
                        "Offset": 7900000,
                        "Duration": 3600000
                    },
                    {
                        "Word": "que",
                        "Offset": 11500000,
                        "Duration": 2000000
                    },
                    {
                        "Word": "você",
                        "Offset": 13500000,
                        "Duration": 5600000
                    },
                    {
                        "Word": "estiver",
                        "Offset": 19100000,
                        "Duration": 3200000
                    },
                    {
                        "Word": "voltando",
                        "Offset": 22300000,
                        "Duration": 7200000
                    },
                    {
                        "Word": "de",
                        "Offset": 29500000,
                        "Duration": 1200000
                    },
                    {
                        "Word": "carro",
                        "Offset": 30700000,
                        "Duration": 6400000
                    },
                    {
                        "Word": "passa",
                        "Offset": 38300000,
                        "Duration": 4800000
                    },
                    {
                        "Word": "lá",
                        "Offset": 43100000,
                        "Duration": 800000
                    },
                    {
                        "Word": "na",
                        "Offset": 43900000,
                        "Duration": 1200000
                    },
                    {
                        "Word": "natação",
                        "Offset": 45100000,
                        "Duration": 6000000
                    },
                    {
                        "Word": "e",
                        "Offset": 51100000,
                        "Duration": 400000
                    },
                    {
                        "Word": "pega",
                        "Offset": 51500000,
                        "Duration": 2800000
                    },
                    {
                        "Word": "o",
                        "Offset": 54300000,
                        "Duration": 400000
                    },
                    {
                        "Word": "joão",
                        "Offset": 54700000,
                        "Duration": 4000000
                    },
                    {
                        "Word": "porque",
                        "Offset": 64700000,
                        "Duration": 2000000
                    },
                    {
                        "Word": "o",
                        "Offset": 66700000,
                        "Duration": 400000
                    },
                    {
                        "Word": "joão",
                        "Offset": 67100000,
                        "Duration": 2400000
                    },
                    {
                        "Word": "quer",
                        "Offset": 69500000,
                        "Duration": 1200000
                    },
                    {
                        "Word": "ir",
                        "Offset": 70700000,
                        "Duration": 800000
                    },
                    {
                        "Word": "no",
                        "Offset": 71500000,
                        "Duration": 800000
                    },
                    {
                        "Word": "atletismo",
                        "Offset": 72300000,
                        "Duration": 6000000
                    },
                    {
                        "Word": "com",
                        "Offset": 78300000,
                        "Duration": 1200000
                    },
                    {
                        "Word": "você",
                        "Offset": 79500000,
                        "Duration": 3600000
                    }
                ]
            },
            {
                "Confidence": 0.7985899,
                "Lexical": "a hora que você estiver voltando de carro passa lá na natação e pega o joão porque o joão quer ir no atletismo com você",
                "ITN": "a hora que você estiver voltando de carro passa lá na natação e pega o joão porque o joão quer ir no atletismo com você",
                "MaskedITN": "a hora que você estiver voltando de carro passa lá na natação e pega o joão porque o joão quer ir no atletismo com você",
                "Display": "a hora que você estiver voltando de carro passa lá na natação e pega o joão porque o joão quer ir no atletismo com você",
                "Words": [
                    {
                        "Word": "a",
                        "Offset": 5100000,
                        "Duration": 2800000
                    },
                    {
                        "Word": "hora",
                        "Offset": 7900000,
                        "Duration": 3600000
                    },
                    {
                        "Word": "que",
                        "Offset": 11500000,
                        "Duration": 2000000
                    },
                    {
                        "Word": "você",
                        "Offset": 13500000,
                        "Duration": 5600000
                    },
                    {
                        "Word": "estiver",
                        "Offset": 19100000,
                        "Duration": 3200000
                    },
                    {
                        "Word": "voltando",
                        "Offset": 22300000,
                        "Duration": 7200000
                    },
                    {
                        "Word": "de",
                        "Offset": 29500000,
                        "Duration": 1200000
                    },
                    {
                        "Word": "carro",
                        "Offset": 30700000,
                        "Duration": 6400000
                    },
                    {
                        "Word": "passa",
                        "Offset": 38300000,
                        "Duration": 4800000
                    },
                    {
                        "Word": "lá",
                        "Offset": 43100000,
                        "Duration": 800000
                    },
                    {
                        "Word": "na",
                        "Offset": 43900000,
                        "Duration": 1200000
                    },
                    {
                        "Word": "natação",
                        "Offset": 45100000,
                        "Duration": 6000000
                    },
                    {
                        "Word": "e",
                        "Offset": 51100000,
                        "Duration": 400000
                    },
                    {
                        "Word": "pega",
                        "Offset": 51500000,
                        "Duration": 2800000
                    },
                    {
                        "Word": "o",
                        "Offset": 54300000,
                        "Duration": 400000
                    },
                    {
                        "Word": "joão",
                        "Offset": 54700000,
                        "Duration": 4000000
                    },
                    {
                        "Word": "porque",
                        "Offset": 64700000,
                        "Duration": 2000000
                    },
                    {
                        "Word": "o",
                        "Offset": 66700000,
                        "Duration": 400000
                    },
                    {
                        "Word": "joão",
                        "Offset": 67100000,
                        "Duration": 2400000
                    },
                    {
                        "Word": "quer",
                        "Offset": 69500000,
                        "Duration": 1200000
                    },
                    {
                        "Word": "ir",
                        "Offset": 70700000,
                        "Duration": 800000
                    },
                    {
                        "Word": "no",
                        "Offset": 71500000,
                        "Duration": 800000
                    },
                    {
                        "Word": "atletismo",
                        "Offset": 72300000,
                        "Duration": 6000000
                    },
                    {
                        "Word": "com",
                        "Offset": 78300000,
                        "Duration": 1200000
                    },
                    {
                        "Word": "você",
                        "Offset": 79500000,
                        "Duration": 4800000
                    }
                ]
            },
            {
                "Confidence": 0.7985899,
                "Lexical": "a hora que você estiver voltando de carro passa lá na natação e pega o joão porque o joão quer ir no atletismo com você",
                "ITN": "a hora que você estiver voltando de carro passa lá na natação e pega o joão porque o joão quer ir no atletismo com você",
                "MaskedITN": "a hora que você estiver voltando de carro passa lá na natação e pega o joão porque o joão quer ir no atletismo com você",
                "Display": "a hora que você estiver voltando de carro passa lá na natação e pega o joão porque o joão quer ir no atletismo com você",
                "Words": [
                    {
                        "Word": "a",
                        "Offset": 5100000,
                        "Duration": 2800000
                    },
                    {
                        "Word": "hora",
                        "Offset": 7900000,
                        "Duration": 3600000
                    },
                    {
                        "Word": "que",
                        "Offset": 11500000,
                        "Duration": 2000000
                    },
                    {
                        "Word": "você",
                        "Offset": 13500000,
                        "Duration": 5600000
                    },
                    {
                        "Word": "estiver",
                        "Offset": 19100000,
                        "Duration": 3200000
                    },
                    {
                        "Word": "voltando",
                        "Offset": 22300000,
                        "Duration": 7200000
                    },
                    {
                        "Word": "de",
                        "Offset": 29500000,
                        "Duration": 1200000
                    },
                    {
                        "Word": "carro",
                        "Offset": 30700000,
                        "Duration": 6400000
                    },
                    {
                        "Word": "passa",
                        "Offset": 38300000,
                        "Duration": 4800000
                    },
                    {
                        "Word": "lá",
                        "Offset": 43100000,
                        "Duration": 800000
                    },
                    {
                        "Word": "na",
                        "Offset": 43900000,
                        "Duration": 1200000
                    },
                    {
                        "Word": "natação",
                        "Offset": 45100000,
                        "Duration": 6000000
                    },
                    {
                        "Word": "e",
                        "Offset": 51100000,
                        "Duration": 400000
                    },
                    {
                        "Word": "pega",
                        "Offset": 51500000,
                        "Duration": 2800000
                    },
                    {
                        "Word": "o",
                        "Offset": 54300000,
                        "Duration": 400000
                    },
                    {
                        "Word": "joão",
                        "Offset": 54700000,
                        "Duration": 4000000
                    },
                    {
                        "Word": "porque",
                        "Offset": 64700000,
                        "Duration": 2000000
                    },
                    {
                        "Word": "o",
                        "Offset": 66700000,
                        "Duration": 400000
                    },
                    {
                        "Word": "joão",
                        "Offset": 67100000,
                        "Duration": 2400000
                    },
                    {
                        "Word": "quer",
                        "Offset": 69500000,
                        "Duration": 1200000
                    },
                    {
                        "Word": "ir",
                        "Offset": 70700000,
                        "Duration": 800000
                    },
                    {
                        "Word": "no",
                        "Offset": 71500000,
                        "Duration": 800000
                    },
                    {
                        "Word": "atletismo",
                        "Offset": 72300000,
                        "Duration": 6000000
                    },
                    {
                        "Word": "com",
                        "Offset": 78300000,
                        "Duration": 1200000
                    },
                    {
                        "Word": "você",
                        "Offset": 79500000,
                        "Duration": 4800000
                    }
                ]
            },
            {
                "Confidence": 0.7985899,
                "Lexical": "a hora que você estiver voltando de carro passa lá na natação e pega o joão porque o joão quer ir no atletismo com você",
                "ITN": "a hora que você estiver voltando de carro passa lá na natação e pega o joão porque o joão quer ir no atletismo com você",
                "MaskedITN": "a hora que você estiver voltando de carro passa lá na natação e pega o joão porque o joão quer ir no atletismo com você",
                "Display": "a hora que você estiver voltando de carro passa lá na natação e pega o joão porque o joão quer ir no atletismo com você",
                "Words": [
                    {
                        "Word": "a",
                        "Offset": 5100000,
                        "Duration": 2800000
                    },
                    {
                        "Word": "hora",
                        "Offset": 7900000,
                        "Duration": 3600000
                    },
                    {
                        "Word": "que",
                        "Offset": 11500000,
                        "Duration": 2000000
                    },
                    {
                        "Word": "você",
                        "Offset": 13500000,
                        "Duration": 5600000
                    },
                    {
                        "Word": "estiver",
                        "Offset": 19100000,
                        "Duration": 3200000
                    },
                    {
                        "Word": "voltando",
                        "Offset": 22300000,
                        "Duration": 7200000
                    },
                    {
                        "Word": "de",
                        "Offset": 29500000,
                        "Duration": 1200000
                    },
                    {
                        "Word": "carro",
                        "Offset": 30700000,
                        "Duration": 6400000
                    },
                    {
                        "Word": "passa",
                        "Offset": 38300000,
                        "Duration": 4800000
                    },
                    {
                        "Word": "lá",
                        "Offset": 43100000,
                        "Duration": 800000
                    },
                    {
                        "Word": "na",
                        "Offset": 43900000,
                        "Duration": 1200000
                    },
                    {
                        "Word": "natação",
                        "Offset": 45100000,
                        "Duration": 6000000
                    },
                    {
                        "Word": "e",
                        "Offset": 51100000,
                        "Duration": 400000
                    },
                    {
                        "Word": "pega",
                        "Offset": 51500000,
                        "Duration": 2800000
                    },
                    {
                        "Word": "o",
                        "Offset": 54300000,
                        "Duration": 400000
                    },
                    {
                        "Word": "joão",
                        "Offset": 54700000,
                        "Duration": 4000000
                    },
                    {
                        "Word": "porque",
                        "Offset": 64700000,
                        "Duration": 2000000
                    },
                    {
                        "Word": "o",
                        "Offset": 66700000,
                        "Duration": 400000
                    },
                    {
                        "Word": "joão",
                        "Offset": 67100000,
                        "Duration": 2400000
                    },
                    {
                        "Word": "quer",
                        "Offset": 69500000,
                        "Duration": 1200000
                    },
                    {
                        "Word": "ir",
                        "Offset": 70700000,
                        "Duration": 800000
                    },
                    {
                        "Word": "no",
                        "Offset": 71500000,
                        "Duration": 800000
                    },
                    {
                        "Word": "atletismo",
                        "Offset": 72300000,
                        "Duration": 6000000
                    },
                    {
                        "Word": "com",
                        "Offset": 78300000,
                        "Duration": 1200000
                    },
                    {
                        "Word": "você",
                        "Offset": 79500000,
                        "Duration": 4800000
                    }
                ]
            },
            {
                "Confidence": 0.7985899,
                "Lexical": "a hora que você estiver voltando de carro passa lá na natação e pega o joão porque o joão quer ir no atletismo com você",
                "ITN": "a hora que você estiver voltando de carro passa lá na natação e pega o joão porque o joão quer ir no atletismo com você",
                "MaskedITN": "a hora que você estiver voltando de carro passa lá na natação e pega o joão porque o joão quer ir no atletismo com você",
                "Display": "a hora que você estiver voltando de carro passa lá na natação e pega o joão porque o joão quer ir no atletismo com você",
                "Words": [
                    {
                        "Word": "a",
                        "Offset": 5100000,
                        "Duration": 2800000
                    },
                    {
                        "Word": "hora",
                        "Offset": 7900000,
                        "Duration": 3600000
                    },
                    {
                        "Word": "que",
                        "Offset": 11500000,
                        "Duration": 2000000
                    },
                    {
                        "Word": "você",
                        "Offset": 13500000,
                        "Duration": 5600000
                    },
                    {
                        "Word": "estiver",
                        "Offset": 19100000,
                        "Duration": 3200000
                    },
                    {
                        "Word": "voltando",
                        "Offset": 22300000,
                        "Duration": 7200000
                    },
                    {
                        "Word": "de",
                        "Offset": 29500000,
                        "Duration": 1200000
                    },
                    {
                        "Word": "carro",
                        "Offset": 30700000,
                        "Duration": 6400000
                    },
                    {
                        "Word": "passa",
                        "Offset": 38300000,
                        "Duration": 4800000
                    },
                    {
                        "Word": "lá",
                        "Offset": 43100000,
                        "Duration": 800000
                    },
                    {
                        "Word": "na",
                        "Offset": 43900000,
                        "Duration": 1200000
                    },
                    {
                        "Word": "natação",
                        "Offset": 45100000,
                        "Duration": 6000000
                    },
                    {
                        "Word": "e",
                        "Offset": 51100000,
                        "Duration": 400000
                    },
                    {
                        "Word": "pega",
                        "Offset": 51500000,
                        "Duration": 2800000
                    },
                    {
                        "Word": "o",
                        "Offset": 54300000,
                        "Duration": 400000
                    },
                    {
                        "Word": "joão",
                        "Offset": 54700000,
                        "Duration": 4000000
                    },
                    {
                        "Word": "porque",
                        "Offset": 64700000,
                        "Duration": 2000000
                    },
                    {
                        "Word": "o",
                        "Offset": 66700000,
                        "Duration": 400000
                    },
                    {
                        "Word": "joão",
                        "Offset": 67100000,
                        "Duration": 2400000
                    },
                    {
                        "Word": "quer",
                        "Offset": 69500000,
                        "Duration": 1200000
                    },
                    {
                        "Word": "ir",
                        "Offset": 70700000,
                        "Duration": 800000
                    },
                    {
                        "Word": "no",
                        "Offset": 71500000,
                        "Duration": 800000
                    },
                    {
                        "Word": "atletismo",
                        "Offset": 72300000,
                        "Duration": 6000000
                    },
                    {
                        "Word": "com",
                        "Offset": 78300000,
                        "Duration": 1200000
                    },
                    {
                        "Word": "você",
                        "Offset": 79500000,
                        "Duration": 4800000
                    }
                ]
            }
        ]
    }
]


# - Studio de IDIOMA
* Aplicação utilzada foi a de Analisar sentimentos e opiniões.
    - Foi selecionado uma reclamação do site relcame aqui:
    - Aplicação que pode ser utilizada para área de marketing, vendas e pós venda de forma de correção e aprendizagem sobre o produto e pontos fortes.
        - Em aplicações de longa escala para grandes empresas e aplicação acessível a pequenos e médios negócios, custo da aplicação baixo ou gratuito.
    - Veja a imagem e o JSON da aplicação teste:

![image](https://github.com/user-attachments/assets/79f37314-4659-420f-83b3-666a537afee5)

JSON:
{
    "documents": [
        {
            "id": "id__1085",
            "sentiment": "mixed",
            "confidenceScores": {
                "positive": 0.25,
                "neutral": 0.04,
                "negative": 0.71
            },
            "sentences": [
                {
                    "sentiment": "negative",
                    "confidenceScores": {
                        "positive": 0,
                        "neutral": 0,
                        "negative": 1
                    },
                    "offset": 0,
                    "length": 124,
                    "text": "Registro esta reclamação como um alerta para as pessoas que pensam em adquirir um curso de pós-graduação nesta instituição. ",
                    "targets": [],
                    "assessments": []
                },
                {
                    "sentiment": "negative",
                    "confidenceScores": {
                        "positive": 0,
                        "neutral": 0,
                        "negative": 1
                    },
                    "offset": 124,
                    "length": 234,
                    "text": "Gostaria de ter tido acesso a essas informações antes de realizar a minha matrícula e, infelizmente, deixar passar o prazo de 7 dias, tendo assim que pagar uma taxa para o cancelamento da matrícula, mesmo sem ter assinado o contrato.\n",
                    "targets": [],
                    "assessments": []
                },
                {
                    "sentiment": "positive",
                    "confidenceScores": {
                        "positive": 0.53,
                        "neutral": 0.3,
                        "negative": 0.17
                    },
                    "offset": 358,
                    "length": 185,
                    "text": "Apesar de as disciplinas do curso serem de 80 horas, consegui concluir a primeira disciplina em 3 dias, estudando cerca de 2 horas por dia e tirando nota máxima na prova da disciplina. ",
                    "targets": [],
                    "assessments": []
                },
                {
                    "sentiment": "negative",
                    "confidenceScores": {
                        "positive": 0,
                        "neutral": 0.01,
                        "negative": 0.99
                    },
                    "offset": 543,
                    "length": 77,
                    "text": "Ou seja: o conteúdo apresentado não justifica a carga horária que é vendida. ",
                    "targets": [
                        {
                            "sentiment": "negative",
                            "confidenceScores": {
                                "positive": 0.02,
                                "negative": 0.98
                            },
                            "offset": 555,
                            "length": 8,
                            "text": "conteúdo",
                            "relations": [
                                {
                                    "relationType": "assessment",
                                    "ref": "#/documents/0/sentences/3/assessments/0"
                                }
                            ]
                        }
                    ],
                    "assessments": [
                        {
                            "sentiment": "negative",
                            "confidenceScores": {
                                "positive": 0.02,
                                "negative": 0.98
                            },
                            "offset": 580,
                            "length": 9,
                            "text": "justifica",
                            "isNegated": true
                        }
                    ]
                },
                {
                    "sentiment": "negative",
                    "confidenceScores": {
                        "positive": 0,
                        "neutral": 0,
                        "negative": 1
                    },
                    "offset": 620,
                    "length": 178,
                    "text": "Cada disciplina se resume a 4 aulas de menos de 20 minutos (algumas de 10 minutos), nada caprichadas, apenas com um professor falando de forma muito superficial sobre o assunto. ",
                    "targets": [
                        {
                            "sentiment": "negative",
                            "confidenceScores": {
                                "positive": 0.1,
                                "negative": 0.9
                            },
                            "offset": 626,
                            "length": 10,
                            "text": "disciplina",
                            "relations": [
                                {
                                    "relationType": "assessment",
                                    "ref": "#/documents/0/sentences/4/assessments/0"
                                }
                            ]
                        }
                    ],
                    "assessments": [
                        {
                            "sentiment": "negative",
                            "confidenceScores": {
                                "positive": 0.1,
                                "negative": 0.9
                            },
                            "offset": 710,
                            "length": 11,
                            "text": "caprichadas",
                            "isNegated": true
                        }
                    ]
                },
                {
                    "sentiment": "negative",
                    "confidenceScores": {
                        "positive": 0,
                        "neutral": 0,
                        "negative": 1
                    },
                    "offset": 798,
                    "length": 146,
                    "text": "O e-book, apesar de apresentar algumas outras informações relevantes, também não é muito aprofundado, além de conter diversos erros ortográficos.\n",
                    "targets": [
                        {
                            "sentiment": "negative",
                            "confidenceScores": {
                                "positive": 0.02,
                                "negative": 0.98
                            },
                            "offset": 801,
                            "length": 6,
                            "text": "e-book",
                            "relations": [
                                {
                                    "relationType": "assessment",
                                    "ref": "#/documents/0/sentences/5/assessments/0"
                                }
                            ]
                        }
                    ],
                    "assessments": [
                        {
                            "sentiment": "negative",
                            "confidenceScores": {
                                "positive": 0.02,
                                "negative": 0.98
                            },
                            "offset": 888,
                            "length": 11,
                            "text": "aprofundado",
                            "isNegated": true
                        }
                    ]
                },
                {
                    "sentiment": "negative",
                    "confidenceScores": {
                        "positive": 0,
                        "neutral": 0,
                        "negative": 1
                    },
                    "offset": 944,
                    "length": 243,
                    "text": "Na segunda pós que iniciei, a professora passa a aula inteira de 20 minutos lendo um texto (com uma oratória bem ruim), o que mostra que era tão despreparada a respeito do conteúdo que não era capaz de realizar uma aula explicativa sobre ele. ",
                    "targets": [
                        {
                            "sentiment": "negative",
                            "confidenceScores": {
                                "positive": 0.02,
                                "negative": 0.98
                            },
                            "offset": 976,
                            "length": 10,
                            "text": "professora",
                            "relations": [
                                {
                                    "relationType": "assessment",
                                    "ref": "#/documents/0/sentences/6/assessments/0"
                                },
                                {
                                    "relationType": "assessment",
                                    "ref": "#/documents/0/sentences/6/assessments/1"
                                }
                            ]
                        }
                    ],
                    "assessments": [
                        {
                            "sentiment": "negative",
                            "confidenceScores": {
                                "positive": 0.03,
                                "negative": 0.97
                            },
                            "offset": 1059,
                            "length": 4,
                            "text": "ruim",
                            "isNegated": false
                        },
                        {
                            "sentiment": "negative",
                            "confidenceScores": {
                                "positive": 0.01,
                                "negative": 0.99
                            },
                            "offset": 1091,
                            "length": 12,
                            "text": "despreparada",
                            "isNegated": false
                        }
                    ]
                },
                {
                    "sentiment": "positive",
                    "confidenceScores": {
                        "positive": 1,
                        "neutral": 0,
                        "negative": 0
                    },
                    "offset": 1187,
                    "length": 116,
                    "text": "Leitura direta qualquer pessoa pode fazer, inclusive seria mais fácil entender o assunto se eu mesma lesse o texto.\n",
                    "targets": [],
                    "assessments": []
                },
                {
                    "sentiment": "negative",
                    "confidenceScores": {
                        "positive": 0.24,
                        "neutral": 0.11,
                        "negative": 0.65
                    },
                    "offset": 1303,
                    "length": 131,
                    "text": "O que mais me surpreende é que essa faculdade possui nota 5 no MEC, o que me faz questionar os critérios que o MEC vem utilizando.\n",
                    "targets": [],
                    "assessments": []
                },
                {
                    "sentiment": "neutral",
                    "confidenceScores": {
                        "positive": 0.01,
                        "neutral": 0.98,
                        "negative": 0.01
                    },
                    "offset": 1434,
                    "length": 213,
                    "text": "Outro ponto que observei é que eles possuem diversos cursos na sua plataforma, para atrair o máximo de alunos possível, mas, se você observar as disciplinas, os conteúdos de cada nicho são praticamente os mesmos. ",
                    "targets": [],
                    "assessments": []
                },
                {
                    "sentiment": "negative",
                    "confidenceScores": {
                        "positive": 0,
                        "neutral": 0,
                        "negative": 1
                    },
                    "offset": 1647,
                    "length": 217,
                    "text": "Eu, que sou da área ambiental, não consegui escolher outro curso da mesma área, pois iria estudar praticamente as mesmas disciplinas, em ordem diferente, e, consequentemente, desperdiçaria a segunda pós que \"ganhei\".\n",
                    "targets": [],
                    "assessments": []
                },
                {
                    "sentiment": "positive",
                    "confidenceScores": {
                        "positive": 0.99,
                        "neutral": 0,
                        "negative": 0.01
                    },
                    "offset": 1864,
                    "length": 308,
                    "text": "Espero que este alerta ajude alguém a procurar uma faculdade que realmente esteja disposta a apresentar um conteúdo de qualidade, formando profissionais para o mercado de trabalho, e não apenas visando o lucro, investindo muito em uma publicidade convincente e quase nada no conteúdo que se propõe a ensinar.",
                    "targets": [],
                    "assessments": []
                }
            ],
            "warnings": []
        }
    ],
    "errors": [],
    "modelVersion": "2024-03-01"
}
