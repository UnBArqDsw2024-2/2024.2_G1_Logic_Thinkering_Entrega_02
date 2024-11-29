# Backward From

## Introdução

<div align="justify">&emsp;&emsp;
Uma parte essencial da Engenharia de Requisitos é conseguir manter o rastreamento de todos os requisitos levantados, sabendo, a todo momento, não apenas de onde surgiram, mas também onde estão implementados, garantindo que foram atendidos e estão devidamente alinhados com as necessidades dos stakeholders. Nesse contexto, o conceito do Backward From desempenha um papel fundamental ao possibilitar a análise reversa de dependências. Ele permite rastrear a origem de um requisito, tarefa ou objetivo, facilitando a compreensão de como cada elemento do sistema foi derivado e sua importância dentro do escopo geral do projeto.

&emsp;&emsp;Essa abordagem é particularmente relevante em projetos de mods para jogos como Minecraft, onde as demandas criativas e técnicas precisam ser cuidadosamente alinhadas. Por meio do Backward From, a equipe pode garantir que cada funcionalidade ou objetivo planejado tenha uma origem clara, esteja conectado às necessidades dos stakeholders e seja implementado de forma eficiente e alinhada ao escopo definido.

</div>

## Objetivo

<div align="justify">&emsp;&emsp;
O objetivo do Backward From para a equipe, além de manter a rastreabilidade dos requisitos levantados, é de consolidar o escopo do projeto, garantindo que a equipe esteja alinhada com o que será implementado e quais tópicos serão descartados. Ademais, o documento visa também simplificar o processo de verificação durante o desenvolvimento, garantindo que a implementação esteja alinhada com os requisitos elicitados.

&emsp;&emsp;Além disso, o documento minimiza ambiguidades durante o desenvolvimento, permitindo identificar rapidamente quais itens foram implementados, estão pendentes ou precisam de revisão. Portanto, espera-se aumentar a eficácia no rastreamento e alinhamento dos requisitos com os objetivos do projeto.

</div>

## Metodologia

<div align="justify">&emsp;&emsp;
Para a confecção do Backward From, definimos que cada autor - presente em uma reunião extraordinária do dia 18 de novembro - do seu respectivo documento - elaborados na primeira etapa da disciplina - seria responsável por apresentar os requisitos levantados relacionados aos artefatos que produziu. Em seguida, utilizamos uma matriz de rastreabilidade, conectando os requisitos às respectivas elicitações de forma estruturada e coerente. Posteriormente, validamos o documento em uma reunião geral da equipe para debater os requisitos e garantir o alinhamento de todo o time de desenvolvedores com o tema, antes de iniciarmos o processo de modelagem.

&emsp;&emsp;Além disso, ferramentas como GitHub Issues e Pull Requests serão empregadas para gerenciar as tarefas e garantir o rastreamento contínuo dos requisitos.

</div>

## Resultados

<div align="justify">&emsp;&emsp;
Os requisitos funcionais e não funcionais coletados no processo de desenho e elicitação podem ser encontrados resumidos nos quadros 1 e 2, respectivamente.
</div>

<center>
 <b>Quadro 1 -</b> Requisitos Funcionais
</center>

| ID   | Descrição                                                                                                                        | Origem                                                                      | Implementado | Prioridade |
| ---- | -------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------- | ------------ | ---------- |
| RF01 | Adicionar três novos minérios (ametista reforçada, esmeralda reforçada e cobre reforçado)                                        | BS1, Rich Picture, Análise de SWOT                                          | Não          | Alta       |
| RF02 | Permitir o uso desses minérios para criar armaduras e ferramentas                                                                | BS1, Rich Picture, Persona 5, Persona 6, Análise de SWOT                    | Não          | Alta       |
| RF03 | Implementar uma mecânica (carga) que conecte as funcionalidades das novas armaduras com as ferramentas feitas dos novos minérios | BS1, Persona 6, Análise de SWOT                                             | Não          | Alta       |
| RF04 | Criar um bloco especial que suporte múltiplos sinais de redstone ao mesmo tempo (matriz de fios)                                 | BS1, Persona 1, Persona 3, Rich Picture, Persona 4, Análise de SWOT, NFR001 | Não          | Alta       |
| RF05 | Cada sinal deve poder ser individualmente controlado e ajustado dentro do bloco                                                  | BS1, Persona 1, Persona 3, Persona 4                                        | Não          | Alta       |
| RF06 | Adicionar blocos de portas lógicas (AND, OR, XOR, NOT) para redstone                                                             | BS1, Persona 1, Persona 4, NFR001                                           | Não          | Alta       |
| RF07 | Adicionar um bloco de antena                                                                                                     | BS1, Persona 1, , Persona 4, Rich Picture                                   | Não          | Média      |
| RF08 | Inverter a direção do sinal (vertical ou horizontal) recebido pela antena                                                        | BS1, Persona 1, Persona 4, NFR001                                           | Não          | Baixa      |
| RF09 | Definir um alcance específico para a transmissão vertical                                                                        | BS1, Persona 1                                                              | Não          | Baixa      |
| RF10 | Mostra sinal de redstone no minimapa                                                                                             | BS1, Rich Picture                                                           | Não          | Baixa      |
| RF11 | Incluir configurações para que o jogador possa ativar/desativar a funcionalidade do minimapa                                     | BS1                                                                         | Não          | Baixa      |
| RF12 | Adicionar uma funcionalidade que permite que os sinais de redstone sejam transmitidos sem fio                                    | BS1, Persona 1, Persona 3                                                   | Não          | Alta       |
| RF13 | Permitir que o jogador configure redes de sinal                                                                                  | BS1, Persona 2, Persona 5                                                   | Não          | Média      |
| RF14 | Incluir um livro digital no jogo que explique os conceitos básicos de eletrônica usados no mod                                   | BS1, Persona 2, Rich Picture                                                | Não          | Alta       |
| RF15 | Dividir o livro em seções didáticas que o jogador pode ler para aprender sobre eletrônica e lógica de circuitos                  | BS1, Persona 2, Análise de SWOT                                             | Não          | Alta       |
| RF16 | Adicionar robôs de mineração                                                                                                     | BS1, Persona 3, Rich Pictures, Persona 6, Análise de SWOT                   | Não          | Baixo      |
| RF17 | Permitir ao jogador construir circuitos lógicos sem a necessidade de componentes externos (timer, clock…)                        | BS1, Persona 1                                                              | Não          | Alta       |
| RF18 | Os robôs de mineração devem minerar somente o que o jogador configurar                                                           | BS1, Persona 3                                                              | Não          | Baixa      |
| RF19 | Permitir a integração das portas lógicas com os sistemas de redstone já existentes                                               | BS1, Persona 1, Persona 4                                                   | Não          | Alta       |
| RF20 | Utilização do Almost Unified (garante que os crafts não darão conflitos com outros mods)                                         | NFR001, NFR003                                                              | Não          | Média      |
| RF21 | Adição dos crafts no JEI                                                                                                         | NRF002                                                                      | Não          | Média      |
| RF22 | Mod não deve ter problemas de duplicação de itens ou drop errado quando quebrados                                                | NRF004                                                                      | Não          | Média      |
| RF23 | Disponibilizar quizzes com recompensas                                                                                           | NFR001                                                                      | Não          | Baixíssima |
| RF24 | Adicionar um minimapa                                                                                                            |                                                                             | Não          | Baixíssima |

<center>
 <b>Fonte:</b> Autoria própria, 2024.
</center>

<center>
 <b>Quadro 2 -</b> Requisitos Não Funcionais
</center>

| ID    | Descrição                                                                                                                                            | Origem                                                                    | Implementado | Prioridade |
| ----- | ---------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------- | ------------ | ---------- |
| RNF01 | As funcionalidades e mecânicas devem ser intuitivas para jogadores de qualquer nível de experiência                                                  | BS1, Análise de SWOT, Diagrama de Ishikawa (adaptação), Persona 2         | Não          | Alta       |
| RNF02 | As novas mecânicas e blocos não devem impactar significativamente o desempenho do jogo, mesmo em servidores com muitos jogadores                     | BS1, Análise de SWOT, Persona 3                                           | Não          | Alta       |
| RNF03 | O conteúdo educativo no livro deve ser claro e adequado para iniciantes, promovendo o aprendizado de eletrônica de forma prática e integrada ao jogo | BS1, Análise de SWOT, Diagrama de Ishikawa (adaptação), Persona 5, NFR002 | Não          | Alta       |
| RNF04 | O mod deve ser compatível com versões populares do Minecraft                                                                                         | BS1, Análise de SWOT                                                      | Não          | Alta       |
| RNF05 | Utilizar imagens, ícones e texturas objetivas                                                                                                        | BS1, NFR004, NFR002                                                       | Não          | Alta       |
| RNF06 | Garantir compatibilidade com as APIs para Minecraft                                                                                                  | BS1                                                                       | Não          | Alta       |
| RNF07 | Redes de sinal com uma interface amigável                                                                                                            | RF013                                                                     | Não          | Média      |
| RNF08 | Mod não deve ter problemas de duplicação de itens ou drop errado quando quebrados                                                                    | NRF004                                                                    | Não          | Alta       |

<center>
 <b>Fonte:</b> Autoria própria, 2024.
</center>

## Estrutura do Projeto

<div align="justify">

&emsp;&emsp;
O projeto apresenta uma organização inicial que segue um template padrão, oferecendo uma base estruturada para o desenvolvimento. A documentação inclui orientações para novos contribuidores e uma visão geral do objetivo do projeto.

&emsp;&emsp;
Como o foco inicial está voltado para a organização interna e o planejamento do projeto, ainda não há pull requests abertos no projeto. Essa abordagem reflete a intenção de criar uma base sólida antes de avançar para a implementação em si. A organização em módulos do projeto deixa evidente que o mesmo está preparado para se adaptar às necessidades específicas do projeto conforme ele evolui.

&emsp;&emsp;
Através da divisão de diretórios que dividem código, documentação e recursos, o código fonte do mod é organizado para incluir classes da orientação a objetos e pacotes para cada requisito funcional listado acima, garantindo a organização do projeto.

</div>

## Bibliografia

> [1] JOHNSEN, Einar Broch (Ed.); WIMMER, Manuel (Ed.). Fundamental Approaches to Software Engineering: Proceedings of the 25th International Conference, FASE 2022. Cham: Springer Nature, 2022. Disponível em: https://library.oapen.org/bitstream/20.500.12657/54029/1/978-3-030-99429-7.pdf. Acesso em: 18 nov. 2024.

<center>

## Participantes

</center>

<!-- de preferência: em ordem alfabética, seguindo o exemplo: -->

<div style="margin: 0 auto; width: fit-content;">

| Matrícula | Aluno                             | Git                                                           |
| --------- | --------------------------------- | ------------------------------------------------------------- |
| 221007869 | Artur Henrique Holz Bartz         | [H0lzz](https://github.com/H0lzz)                             |
| 221931265 | Carlos Eduardo Rodrigues          | [carlos-kadu](https://github.com/carlos-kadu)                 |
| 221008024 | Eduardo Matheus dos Santos Sandes | [DiceRunner714](https://github.com/DiceRunner714)             |
| 170010872 | Gabriela de Oliveira Lemos        | [heylisten64](https://github.com/heylisten64)                 |
| 221008150 | João Antonio Ginuino Carvalho     | [joaoseisei](https://github.com/joaoseisei)                   |
| 221037993 | Patrícia Helena Macedo da Silva   | [patyhelenaa](https://github.com/patyhelenaa)                 |
| 211062526 | Thomas Queiroz Souza Alves        | [thmasq](https://github.com/thmasq)                           |
| 202017263 | Vinicius de Oliveira Santos       | [ViniciussdeOliveira](https://github.com/ViniciussdeOliveira) |

</div>

---

<center>

## Histórico de Versão

</center>

<!-- Lembre de alterar a data -->

<div style="margin: 0 auto; width: fit-content;">

| Versão | Data da alteração |                                Alteração                                |                                                                                                                                                                            Responsável                                                                                                                                                                             |                    Revisor                     | Data de revisão |
| :----: | :---------------: | :---------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------: | :-------------: |
|  1.0   |       19/11       |          Criação do documento, adição de Introdução, Objetivos          | [Eduardo Sandes](https://github.com/DiceRunner714), [Gabriela Lemos](https://github.com/heylisten64), [João Carvalho](https://github.com/joaoseisei), [Vinicius Santos](https://github.com/ViniciussdeOliveira), [Carlos Rodrigues](https://github.com/carlos-kadu), [Patrícia Silva](https://github.com/patyhelenaa), [Thomas Queiroz](https://github.com/thmasq) |    [Artur Bartz](https://github.com/H0lzz)     |   19/11/2024    |
|  1.1   |       19/11       | Criação do tópico de Estrutura do Projeto, criou o RF19, criou o RNF06, |                                                                                                                                                              [Artur Bartz](https://github.com/H0lzz)                                                                                                                                                               | [João Carvalho](https://github.com/joaoseisei) |   28/11/2024    |

</div>

## Controle de Revisão

|                  Revisor(es)                   |                                                                                              O que foi realizado                                                                                               |
| :--------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|    [Artur Bartz](https://github.com/H0lzz)     | Adicionou informações adicionais nos tópicos de Introduçao, Objetivos e Metodologia, adicionou uma nova coluna “Prioridade” nas tabelas dos requisitos funcionais e não funcionais, adicionou uma bibliografia |
| [João Carvalho](https://github.com/joaoseisei) |                                                        Corrige nome dos participantes e remove duplicações e adiciona identação na estrutura do projeto                                                        |
