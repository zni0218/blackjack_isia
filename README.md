Agente de Aprendizagem por Reforço para Blackjack

 Sobre o projeto

Este projeto foi desenvolvido no âmbito da unidade curricular Introdução a Sistemas Inteligentes e Autónomos, durante o terceiro ano da Licenciatura em Inteligência Artificial e Ciência de Dados.

O objetivo consiste em desenvolver, treinar e avaliar agentes de Aprendizagem por Reforço (Reinforcement Learning) capazes de aprender a jogar Blackjack, explorando diferentes algoritmos e comparando o seu desempenho em ambientes com configurações distintas.

O projeto utiliza como ponto de partida o ambiente Blackjack da biblioteca Gymnasium (Toy Text), tendo sido introduzidas alterações ao ambiente original para facilitar e melhorar o processo de treino dos agentes.

 Ambiente Blackjack

O Blackjack é um jogo de cartas no qual o objetivo consiste em obter uma mão cujo valor se aproxime de 21, sem ultrapassar esse limite, procurando vencer a mão do dealer.

Neste projeto, o jogo é utilizado como ambiente experimental para estudar a capacidade dos agentes de aprender estratégias através da interação com o ambiente e das recompensas recebidas pelas suas ações.

Foram considerados dois ambientes:

Ambiente original: a implementação Blackjack disponibilizada pela biblioteca Gymnasium.
Ambiente modificado: uma versão alterada para explorar diferentes condições de treino e analisar o seu impacto na aprendizagem dos agentes.

 Aprendizagem por Reforço

Foram treinados agentes com diferentes algoritmos de Aprendizagem por Reforço, permitindo comparar o comportamento e os resultados obtidos nas duas versões do ambiente.

O processo envolve a interação dos agentes com o jogo, a seleção de ações e a aprendizagem a partir das recompensas recebidas. A comparação experimental permite estudar como as características do ambiente e os algoritmos utilizados influenciam o processo de aprendizagem e o desempenho final.

 Experiências e comparação de resultados

Uma componente central do projeto consiste na avaliação dos diferentes algoritmos nos ambientes original e modificado.

Esta abordagem permite analisar os resultados dos agentes em condições distintas e investigar se as alterações introduzidas no ambiente contribuem para melhorar o treino ou o desempenho das estratégias aprendidas.

Os detalhes das experiências realizadas, da metodologia utilizada e dos resultados obtidos encontram-se na apresentação PowerPoint disponibilizada no repositório.

 Tecnologias utilizadas

Python — implementação e execução das experiências.

Gymnasium — ambiente de simulação Blackjack.

Stable-Baselines3 — implementação e treino de algoritmos de Aprendizagem por Reforço.

TensorFlow — ferramentas de aprendizagem automática utilizadas no projeto.

Reinforcement Learning — treino e avaliação de agentes autónomos.

 Objetivos de aprendizagem

Este projeto permitiu aprofundar conhecimentos sobre Aprendizagem por Reforço, treino de agentes autónomos, configuração de ambientes de simulação e avaliação experimental de algoritmos.

Representa uma aplicação prática de Inteligência Artificial na qual são exploradas diferentes abordagens para aprender estratégias de decisão num ambiente com recompensas e resultados incertos.

 Documentação

Para conhecer em maior detalhe a implementação, os algoritmos utilizados, as experiências realizadas e os resultados obtidos, consulta a apresentação PowerPoint incluída neste repositório.