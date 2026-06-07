# Contexto e Objetivos

**Contexto:**
Muitos brasileiros cresceram sem acesso a ensinamentos simples sobre economia. Não por incapacidade, mas porque esse conhecimento sempre foi tratado como coisa distante, complicada ou de gente abastada. A realidade da maioria é feita de trabalho duro, contas no limite e a sensação de que nunca sobra nada no fim do mês. Faltou quem sentasse ao lado e explicasse, com paciência e sem arrogância, que economia não é bicho de sete cabeças: é o jeito de cuidar do que se ganha com tanto suor.

**Objetivo:**
Trazer, de forma simples e humana, o básico da economia para quem nunca teve essa chance. A ideia não é formar especialistas, mas dar as ferramentas mínimas para que qualquer pessoa possa tomar decisões melhores, sair das armadilhas do dinheiro e plantar as sementes de uma vida mais próspera e edificante. É mostrar que prosperidade não é luxo, é dignidade. E que isso está ao alcance de quem entende, mesmo com pouco, como fazer o dinheiro trabalhar a favor dos seus sonhos, e não contra a sua paz.

# Curadoria de Fontes

## Como foi feita:

**Como foi feita a curadoria:**

- Usei a inteligência artificial do modelo Perplexity, direcionando a busca para assuntos básicos de economia.
- O foco foi atender quem nunca teve acesso a esses conteúdos, com linguagem simples e útil.
- A pesquisa foi restrita a fontes de universidades brasileiras, para garantir autoridade e confiabilidade.
- Os temas foram selecionados por ajudarem a tomar decisões reais, com o pouco que se tem.

**Critérios da seleção:**

- Conteúdo essencial para organizar a vida financeira sem complicação.
- Explicações que partem da realidade de quem vive de salário e suor.
- Base acadêmica sólida, mas traduzida para o dia a dia do trabalhador.
- Orientação prática, que caiba no orçamento apertado e gere mudança imediata.

**Resultado:**
Uma curadoria enxuta e confiável, feita para devolver dignidade e esperança a quem sempre foi deixado de fora da conversa sobre economia.

## Links:

| #   | Link                                                                                                                                                      | Pertence a                        | Instituição                                 | Localização                  |
| --- | --------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------- | ------------------------------------------- | ---------------------------- |
| 1   | https://proedu.rnp.br/bitstream/handle/123456789/733/3a_disciplina_-Introducao_a_Economia.pdf                                                             | PROEdu / RNP                      | Ministério da Educação (MEC)                | Brasil (nacional) proedu.rnp |
| 2   | https://www.home.ufam.edu.br/andersonlfc/Introducao_a_Economica/Manual%20de%20Economia.pdf                                                                | Anderson Luiz F. Costa            | UFAM (Universidade Federal do Amazonas)     | Manaus, AM ufam+1            |
| 3   | https://www.eco.unicamp.br/images/publicacoes/Livros/geral/Economia%20em%2010%20Licoes.pdf                                                                | Fernando Nogueira da Costa        | UNICAMP (Universidade Estadual de Campinas) | Campinas, SP eco.unicamp+1   |
| 4   | https://riu.ufam.edu.br/bitstream/prefix/5532/9/C)%20Introdu%C3%A7%C3%A3o%20%C3%A0%20Economia%20A.pdf%20Introdu%C3%A7%C3%A3o%20%C3%A0%20Economia%20A.pdf) | Lenice Ypiranga                   | UFAM (Universidade Federal do Amazonas)     | Manaus, AM riu.ufam.edu+1    |
| 5   | https://www.repositorio.ufal.br/jspui/bitstream/riufal/7121/1/Finan%C3%A7as%20pessoais%20para%20iniciantes                                                | Autor não identificado no snippet | UFAL (Universidade Federal de Alagoas)      | Maceió, AL repositorio.ufal  |

# Engenharia de Prompts e "Cicatrizes"

## Diretiva

O primeiro prompt, que fiz foi algo para estabelecer regras: estabalecendo um contextor para as perguntas, que tom tomar, restrições, como deve ser entregue a reposta. Isso foi inserido na parte de personalização da conversa e segue da seguinte forma:

- **Persona e contexto**: Você é um educador popular que ensina economia básica usando o método Paulo Freire. Seus alunos são jovens e adultos com escolaridade máxima equivalente à 5ª série. A aula deve começar pela realidade concreta deles — feira, salário, contas de casa, trocas, trabalho na roça ou na cidade — e seguir em diálogo.
- **Princípios do método**: Problematize em vez de dar respostas prontas. Use perguntas geradoras ("Por que o pão tem preço?"). Valorize o saber do aluno e relacione cada conceito à sua vivência. Estimule a “leitura do mundo” econômica, promovendo consciência crítica.
- **Linguagem obrigatória**: Palavras simples, frases curtas. Nada de jargões como "PIB", "inflação" ou "custo de oportunidade" sem explicação com exemplos do cotidiano (ex.: "escolher entre comprar arroz ou feijão"). Tom de conversa, como se falasse com um vizinho.
- **Formato da resposta**: Exclusivamente uma lista de tópicos. Use marcadores como `-` ou números. Cada item deve ser uma pequena unidade de sentido, dialogada. Nada de parágrafos longos ou texto corrido.
- **Extensão**: A lista completa não pode ultrapassar 500 palavras. Seja direto, mas não omita o essencial.
- **Conteúdo essencial a cobrir (nesta ordem ou próximo)**:
  - O que é economia (cuidar da casa, da comunidade, dos recursos).
  - Escassez: nem tudo chega para todo mundo, por isso precisamos escolher.
  - Escolhas e renúncias: toda decisão tem um custo (tempo, dinheiro, esforço).
  - Troca e moeda: por que usamos dinheiro, e como ele facilita a vida.
  - Trabalho e produção: de onde vêm as coisas que consumimos.
  - Consumo e orçamento familiar: ganhar, gastar e anotar para não faltar.
  - Preços simples: como a oferta e a procura influenciam o preço na feira, no mercado.
  - Poupança: guardar um pouco hoje para realizar um sonho ou enfrentar imprevistos.
  - Economia solidária e comunidade: cooperativas, mutirões, como ajudar uns aos outros fortalece a todos.
- **Encerramento freiriano**: O último tópico deve convidar o aluno a refletir sobre o que aprendeu e pensar em uma pequena ação que pode aplicar na sua vida ou na sua comunidade, reforçando a ideia de que a economia é feita por pessoas e pode ser transformada por elas.
- **Regra final**: Não inclua introduções, conclusões nem comentários fora da lista. A saída é apenas a lista de tópicos, sem títulos ou formatações extras.

## Dificuldades

Realizei testes simples no chat e constatei que, enquanto para algumas perguntas houve resposta adequada, para outras o sistema não dispunha de base suficiente. Acredito que o desempenho seria significativamente aprimorado se a base de conteúdo fosse ampliada, incluindo materiais audiovisuais de criadores influentes desse segmento, como os canais @MePoupe (Nathalia Arcuri) e @PrimoPobre (Eduardo Feldberg). Ressalto, contudo, que foi observada a regra de utilizar até cinco fontes abertas em formato PDF.

# 📘 Miniguia de Estudo: Economia Básica para Quem Nunca Teve Chance

## 1. Resumos Estruturados por Tema

### O que é Economia

- Economia é cuidar da casa, da comunidade, dos recursos que temos
- Não é coisa de richer ou de especialista: é o jeito de cuidar do que se ganha com suor
- Trata de como usamos o pouco que temos para não faltar o essencial

### Escassez e Escolhas

- Nem tudo chega para todo mundo: há pouco dinheiro, muito tempo de trabalho, poucas coisas disponíveis
- Por isso precisamos escolher: comprar arroz ou feijão? Pagar luz ou água?
- Toda escolha tem um custo: o que você deixa de fazer ou comprar por escolher outra coisa

### Troca e Moeda

- antigamente as pessoas trocavam coisas diretamente (troca de galinha por pão)
- O dinheiro facilita: é um meio aceito por todos para trocar por qualquer coisa
- Sem dinheiro, teríamos que encontrar alguém que tivesse o que você quer E que quisesse o que você tem

### Trabalho e Produção

- As coisas que consumimos vêm do trabalho de alguém: o pão vem do padeiro, a roupa da costureira
- Trabalho gera valor: quanto mais útil ou difícil for o trabalho, mais as pessoas estão dispostas a pagar
- produção precisa ser organizada: alguém planta, outro colhe, outro transporte, outro vende

### Consumo e Orçamento Familiar

- Ganhar, gastar e anotar: anotar é o segredo para não faltar
- Orçamento é saber quanto entra e quanto sai antes do fim do mês
- Regra simples: primeiro paga o essencial (comida, luz, casa), depois o resto

### Preços: Oferta e Procura

- Preço na feira muda: quando tem muita laranja, o preço cai; quando tem pouca, sobe
- Oferta = quanto tem disponível; Procura = quanto as pessoas querem comprar
- Preço é o equilíbrio entre o que tem e o que querem

### Poupança e Reserva

- Guardar um pouco hoje para o amanhã: para sonhos ou para imprevistos
- Mesmo com pouco, guardar 5% ou 10% já faz diferença no final do ano
- Poupança é segurança: quando a doença chega ou o emprego acaba, você não desmorona

### Economia Solidária e Comunidade

- Cooperativas, mutirões, trocar ajuda: quando unimos forças, todos ganham
- Ajuda mútua fortalece: quem ajuda hoje, é ajudado amanhã
- Economía não é só indivíduo: é comunidade, é coletivo, é se ajudar

---

## 2. Glossário de Conceitos Chave

| Conceito                  | Definição Simples                                                                                        |
| ------------------------- | -------------------------------------------------------------------------------------------------------- |
| **Economia**              | Cuidar do que se tem: dinheiro, tempo, recursos da casa e da comunidade                                  |
| **Escassez**              | Não ter tudo o que precisa ou quer: por isso precisa escolher                                            |
| **Escolha**               | Decidir entre duas ou mais opções: toda escolha tem um custo                                             |
| **Custo de oportunidade** | O que você deixa de ter por escolher outra coisa (ex: comprar celular = não pagar parte da conta de luz) |
| **Troca**                 | Dar algo para receber algo em retorno: base de toda economia                                             |
| **Moeda/Dinheiro**        | Meio aceito por todos para facilitar a troca de coisas                                                   |
| **Trabalho**              | Esforço humano que gera coisas ou serviços que têm valor                                                 |
| **Produção**              | Criar ou fazer coisas que as pessoas vão consumir                                                        |
| **Consumo**               | Usar ou gastar o que foi produzido: comer, vestir, morar                                                 |
| **Orçamento**             | Plano de quanto entra e quanto sai de dinheiro na casa                                                   |
| **Oferta**                | Quantidade de algo que está disponível para vender                                                       |
| **Procura**               | Quantidade de algo que as pessoas querem comprar                                                         |
| **Preço**                 | Quanto se paga por algo: resultado do equilíbrio entre oferta e procura                                  |
| **Poupança**              | Guardar parte do que ganha para o futuro ou para imprevistos                                             |
| **Reserva de emergência** | Dinheiro guardado só para quando algo ruim acontecer (doença, desemprego)                                |
| **Economia solidária**    | Trabalhar e ajudar juntos: cooperativas, mutirões, troca de serviços                                     |
| **Investimento**          | Usar dinheiro hoje para ter mais amanhã (pode ser estudo, negócio, aplicação)                            |
| **Juro**                  | Preço de alugar dinheiro: quem pede paga, quem empresta recebe                                           |
| **Inflação**              | Quando os preços sobem geral: o mesmo dinheiro compra menos coisas                                       |
| **Dignidade financeira**  | Ter o suficiente para viver com respeito, sem depender de ninguém                                        |

---

## 3. Prompts Reutilizáveis para Futura Revisões

### Prompt 1: Explicar Conceito com Exemplo do Cotidiano

```text
Explique [CONCEITO] usando apenas exemplos do dia a dia de quem vive de salário mínimo.
Use linguagem de conversa, como se falasse com um vizinho na feira.
Máximo 150 palavras, sem jargões.

```

### Prompt 2: Gerar Exercício Prático

```text
Crie um exercício prático sobre [TEMA] que uma pessoa com ensino fundamental possa fazer hoje mesmo.
O exercício deve usar apenas papel, caneta e o orçamento real da casa dela.
Inclua passo a passo e o que esperar aprender.

```

### Prompt 3: Comparar duas Opções Financeiras

```text
Compare [OPÇÃO A] e [OPÇÃO B] para uma família de 4 pessoas adultas que ganha 2 salários mínimos.
Mostre prós e contras de cada uma em linguagem simples.
Recomende uma para cada situação: (1) quando há um parente desempregado, (2) quando há dívida.

```

### Prompt 4: Simplificar Jargão Econômico

```text
Traduza [JARGÃO ECONÔMICO] para linguagem de feira.
Use máximo 3 frases, todas com no máximo 15 palavras cada.
Inclua um exemplo concreto de como isso afeta o preço do pão ou do feijão.

```

### Prompt 5: Planejamento de Ação Imediata

```text
Crie um plano de 7 dias para [OBJETIVO FINANCEIRO] para alguém que trabalha 10h por dia e tem pouco tempo.
Cada dia deve ter uma ação de no máximo 15 minutos.
Inclua o que fazer se falhar em um dia.

```

---

## 4. Como Usar Este Miniguia

### Para Revisão Rápida

- Leia um tema por dia (8 dias para cobrir tudo)
- Anote no caderno 1 coisa que vai aplicar no dia seguinte
- Revise o glossário quando encontrar palavra desconhecida

### Para Ensinar Outrem

- Escolha um tema por encontro com a comunidade
- Use os exemplos do resumo come ponto de partida
- Convide cada pessoa a compartilhar sua experiência sobre o tema

### Para Aplicação Prática

- Pegue o orçamento da sua casa esta semana
- Identifique 1 escolha que você pode melhorar usando o conceito de escassez
- Comece a guardar mesmo que seja R$ 1,00 por dia

---

## 5. Reflexão Final Freiriana

> _"O que você aprendeu hoje que pode aplicar ainda esta semana na sua casa ou na sua comunidade?"_

**Sua ação**: Escolha **uma** coisa deste miniguia e aplique nos próximos 7 dias. Pode ser:

- Anotar todas as entradas e saídas de dinheiro
- Guardar 5% do que ganhar
- Conversar com vizinhos sobre trocar serviços
- Explicar para um familiar o que é escassez usando exemplo da feira

**Lembre-se**: Economia não é feita por especialistas. É feita por pessoas como você, que decidem cuidar do que têm com dignidade. **Você já é economista da sua própria vida**. Agora só precisa ter consciência do que já faz.
