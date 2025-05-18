# Assistente-de-Orienta-o-de-Curso
Assistente de orientação de curso em Python com API Gemini

# Descrição do Projeto:

Este projeto em Python é um assistente interativo de linha de comando (CLI) desenvolvido para ajudar usuários a encontrar ou confirmar a escolha de um curso de faculdade. Utilizando a API do Google Gemini, o assistente sugere cursos com base nos interesses do usuário e, posteriormente, oferece uma checklist detalhada para reflexão sobre cursos específicos, gerando uma conclusão final baseada nas respostas.

O objetivo é fornecer uma ferramenta que auxilie na falta de inspiração ou na necessidade de uma análise mais estruturada durante o processo de decisão de carreira acadêmica.

# Funcionalidades

* **Sugestão Inicial de Cursos:** Gera uma lista de possíveis cursos com base nos interesses, habilidades ou nichos informados pelo usuário, utilizando a inteligência do Google Gemini.
* **Detalhes de Cursos:** Permite ao usuário obter um breve resumo e informações sobre conteúdos, duração, área de atuação e média salarial para cursos específicos, consultando o Gemini.
* **Checklist de Reflexão:** Apresenta uma série de perguntas para o usuário refletir sobre cursos de interesse, incluindo aspectos de Bacharelado/Licenciatura e compatibilidade pessoal.
* **Cálculo de Score de Compatibilidade:** Atribui uma pontuação para cada curso analisado na checklist com base nas respostas ('Sim' = 1 ponto, 'Talvez/Pensando' = 0.5 pontos).
* **Análise e Conclusão Final:** Processa os resultados das checklists (incluindo scores e respostas detalhadas, como a preferência por Bacharelado/Licenciatura e aptidão para vida acadêmica/professor) e utiliza o Gemini para gerar uma conclusão personalizada, identificando cursos com alta compatibilidade e sugerindo um 'melhor match' (com a ressalva de ser apenas uma sugestão).

# Tecnologias Utilizadas

* **Python:** Linguagem de programação principal.
* **Google Generative AI SDK:** Biblioteca Python para interagir com a API do Google Gemini.

## Pré-requisitos

Para rodar este projeto, você precisa ter instalado:

* Python 3.7 ou superior
* A biblioteca `google-generativeai`
* Uma chave de API válida do Google AI Studio 


## Como Usar

1.  Ao iniciar, o assistente KELL perguntará seu nome.
2.  Ele perguntará se você já tem algo em mente (cursos, áreas, interesses).
3.  Com base na sua resposta, ele fará perguntas para coletar informações para o Gemini.
4.  O Gemini irá sugerir uma lista inicial de cursos.
5.  Você terá a opção de pedir mais detalhes sobre qualquer curso da lista.
6.  Em seguida, você poderá iniciar a 'Checklist de Reflexão' para um ou mais cursos. Para cada curso escolhido, você responderá perguntas, incluindo sobre Bacharelado/Licenciatura e aptidão para a vida de professor.
7.  Suas respostas serão pontuadas e guardadas. Você poderá fazer a checklist para outros cursos.
8.  Ao finalizar as checklists, o programa enviará todos os seus resultados para o Gemini, que irá analisar suas respostas e gerar uma conclusão personalizada, destacando cursos de alta compatibilidade e sugerindo um 'melhor match' (com a ressalva de ser apenas uma sugestão).

---

**Autor:** _thiago_

