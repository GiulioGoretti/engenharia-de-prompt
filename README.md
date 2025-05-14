# engenharia-de-prompt
Resumo do Curso na DIO: Microsoft 50 Anos - Prompts Inteligentes

# Engenharia de Prompt para Modelos de Linguagem de IA
## O que é um prompt?
Um prompt é uma instrução, pergunta ou comando textual utilizado para interagir com um modelo de linguagem como o ChatGPT, Claude, Gemini ou LLaMA. Ele funciona como o ponto de partida da comunicação, guiando o modelo para gerar respostas específicas, criativas ou funcionais.

Exemplo simples:

"Escreva uma redação sobre os impactos da tecnologia na educação."

### Onde e como os prompts são utilizados?
Prompts são utilizados em diversas aplicações com modelos de linguagem, como:

Assistentes virtuais (ex: ChatGPT, Siri, Alexa)

Ferramentas de produtividade (resumo de textos, geração de e-mails, code copilots)

Automação de tarefas empresariais (relatórios, análise de dados)

Educação e tutoria (resolução de exercícios, explicações)

Geração de conteúdo (roteiros, textos criativos, posts para redes sociais)

### Por que os prompts são fundamentais?
Um bom prompt pode ser a diferença entre uma resposta vaga e uma resposta precisa e útil. Prompts bem elaborados:

Reduzem ambiguidades

Aumentam a qualidade e relevância das respostas

Direcionam o modelo a seguir um estilo, formato ou comportamento específico

Economizam tempo ao evitar múltiplas tentativas

### Quais são os componentes de um prompt?
Um prompt eficaz pode conter os seguintes elementos:

Contexto: Fornece informações de fundo para orientar a resposta.

Instrução clara: Diz exatamente o que se espera da IA.

Formato desejado: Pode incluir estrutura, tom, ou até a linguagem da resposta.

Exemplos (Few-shot prompting): Mostram como a resposta deve parecer.

Papéis ou personas (Role prompting): Definem um "papel" que o modelo deve adotar (ex: "Você é um advogado").

### Técnicas de Engenharia de Prompt
Aqui estão as principais estratégias:

1. Zero-shot Prompting
Solicita uma tarefa diretamente, sem fornecer exemplos.

"Traduza o seguinte texto para o inglês: 'Bom dia, como vai você?'"

2. One-shot Prompting
Fornece um único exemplo antes da tarefa.

"Exemplo: 'Olá' → 'Hello'. Agora traduza: 'Boa noite' →"

3. Few-shot Prompting
Fornece vários exemplos para ajudar o modelo a identificar padrões.

"Exemplos:
'Casa' → 'House'
'Gato' → 'Cat'
Agora traduza: 'Cachorro' →"

4. Chain-of-Thought Prompting
Pede para o modelo explicar o raciocínio passo a passo.

"Explique como resolver esta equação: 2x + 3 = 7"

5. Role Prompting
Define um papel ou profissão para o modelo.

"Você é um professor de história. Explique a Revolução Francesa de forma acessível para adolescentes."

6. Rewriting Prompts (Refinamento iterativo)
Ajusta o prompt com base na resposta anterior até alcançar a saída desejada.

### Dicas adicionais
Seja específico: quanto mais claro for o pedido, melhor a resposta.

Evite ambiguidades: palavras vagas geram respostas genéricas.

Teste variações do prompt: pequenas mudanças fazem grande diferença.

Use limitações explícitas: "em até 100 palavras", "sem jargões técnicos", etc.

### Casos de uso práticos
Currículos: "Crie um currículo baseado neste resumo profissional..."

E-mails: "Escreva um e-mail formal pedindo alteração de prazo..."

Programação: "Crie um código em Python que organize uma lista alfabética..."

Estudo: "Resuma este artigo em tópicos..."


