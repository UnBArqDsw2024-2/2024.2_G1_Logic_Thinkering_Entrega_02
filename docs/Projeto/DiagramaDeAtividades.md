# Diagrama de Atividade

## Introdução

<!--
- **Apresente o tema do projeto ou estudo;**
- **Busque trazer referências no decorrer do texto;**
- Destaque a relevância do diagrama ou abordagem para a área de aplicação.
- Mencione brevemente os principais aspectos que serão abordados no documento.
-->

<div align="justify">

&emsp;&emsp;
O **Diagrama de Atividade** é responsável por representar visualmente o fluxo de atividades que envolve sequência de ações, decisões e interações em um determinado contexto. Essa estrutura de modelagem delineia os passos necessários a serem seguidos para a conclusão de uma atividade específica, com foco nos procedimentos, processos de negócio e fluxo de trabalho. Isso possibilita a melhor compreensão dos processos para a equipe de desenvolvimento bem como para as partes interessadas, o que viabiliza uma melhor comunicação sobre como atividades e comportamentos são organizados e executados (GUEDES, 2009; SERRANO, 2020).
</div>

<div align="justify">

&emsp;&emsp;
Este diagrama possui um formato que se assemelha à notação BPMN por possuir nós de ação, fluxo de controle, nós inicial e final e nós de decisão. Além disso, a notação conta com uma série de outros recursos como: **(1)** nós de bifurcação/união; **(2)** nós de objeto; **(3)** nós de parâmetro; **(4)** nós de buffer central; **(5)** nós de repositório de dados; **(6)** nós de atividade estruturada; **(7)** alfinetes; **(8)** exceções; **(9)** ações de envio de sinal; **(10)** ações de de evento de aceitação; **(11)** ações de evento de tempo de aceitação; **(12)** ações de chamada de comportamento; **(13)** ações de chamada de operação; **(14)** partições de atividade; **(15)** regiões de atividade interrompível; **(16)** regiões de expansão; **(17)** nós condicionais; **(18)** nós de laço; **(19)** conectores; **(20)** final de fluxo e **(21)** fluxo de objetos. Dessa forma, a ideia é do desenvolvimento de um diagrama simples a primeiro momento mas que posteriormente possa sofrer adições de demais recursos desta modelagem (GUEDES, 2009; SERRANO, 2020).
</div>

## Objetivo

<!--
- **Declare o que se pretende alcançar com o diagrama em projetos no geral; Busque referenciar!**
- **Declare o que se pretende alcançar com o diagrama para equipe neste contexto;**
- **Destaque os resultados esperados, como soluções para problemas, melhorias no entendimento ou suporte à tomada de decisões.**
-->

<!-- ideias: capturar fluxo sequencial e paralelo de atividades
- modelagem de processos de negocios e fluxos de execucao
- identificar gargalos
- definir prioridades>
-->

<div align="justify">

&emsp;&emsp;
O **Diagrama de Atividade** foi utilizado com o objetivo de modelar e facilitar a vizualização do funcionamento de componententes do mod, descrevendo comportamentos dinâmicos e a interação entre o jogo, o mod, seus compontentes e o jogador em diferentes cenários.
</div>

<div align="justify">

&emsp;&emsp;
Essa notação é utilizada para representar fluxos de trabalho ou tarefas, identificar pontos de decisão e atividades que podem ocorrer de forma sequencial, simultânea ou condicional. Além disso, serve para facilitar o entendimento e a comunicação entre a equipe de desenvolvimento, de modo que as funcionalidades envolvidas sejam de fácil compreensão para os membros do grupo.
</div>

<div align="justify">

&emsp;&emsp;
Por fim, também contribui para a análise e otimização de processos, ajudando a identificar oportunidades de melhora. Amplamente aplicado na modelagem de casos de uso, automação de processos e design de sistemas, esse diagrama é uma base importante tanto na fase de levantamento de requisitos quanto no design, garantindo que os fluxos sejam bem compreendidos e implementados corretamente.
</div>

## Metodologia

<!--
- **Explique o processo utilizado para desenvolver o trabalho. COMO foi feito?**
- **Descreva as ferramentas, técnicas ou referências utilizadas na construção do diagrama ou solução. Se houver alguma ferramenta específica determinada pela professora, a sugestão é usá-la sendo em qualquer etapa do processo. Podem começar com uma ferramenta que já são familiarizados e depois explorar outras ferramentas.**
- Se desejarem, podem citar os desafios encontrados seguindo a metodologia, propostas de melhoria, etc.
-->

<div align="justify">

&emsp;&emsp;
Para realizar o **Diagrama de Atividades** nos organizamos da seguinte forma: revisamos o documento do **Backward From** e agrupamos requisitos funcionais de forma que juntos formassem uma das partições do diagrama. Nomeamos em um grupo e agrupamos os requisitos e geramos os seguintes conjuntos em que cada um da tarefa ficou responsável por realizar, que pode ser visto na Tabela 1.
</div>

<center>
<b>Tabela 1 -</b> Divisão de Tarefas
</center>
<br>
<div style="margin: 0 auto; width: fit-content;">

| Nome              | Requisito Funcional    | Responsável |
|-------------------|------------------------|-------------|
| Minérios          | RF01, RF02, RF03       | Thomas      |
| Portas Lógicas    | RF06, RF19             | João        |
| Antena            | RF07, RF08, RF09, RF12 | Eduardo     |
| Minimapa          | RF10, RF11, RF24       | Gabriela    |
| Livro             | RF14, RF15, RF23       | Cássio      |
| Robôs             | RF16, RF18             | Vinícius    |
| Circuitos Lógicos | RF17                   | Sunamita    |

</div>

<div align="justify">

&emsp;&emsp;
Nos baseamos na bibliografia encontrada **UML2 - Uma Abordagem Prática** Usamos a ferramenta Draw.io e trabalhamos de forma síncrona utilizando o Discord para debater questões da notação. [Aqui](https://ibb.co/Cwh9KQW) podemos ver parte da equipe trabalhando.
</div>

## Legenda de Símbolos

<div align="justify">

&emsp;&emsp;
Na tabela 2 a seguir estão dispostos os símbolos utilizados nos Diagramas de Atividades desenvolvidos
</div>

<center>
<b>Tabela 2 -</b> Divisão de Tarefas
</center>
<br>
<div style="margin: 0 auto; width: fit-content;">

| Símbolo                                                                                       | Nome                  | Descrição                                                                                    |
|-----------------------------------------------------------------------------------------------|-----------------------|----------------------------------------------------------------------------------------------|
| <img src="/assets/atividades/inicio.png" style="width: 7vw;" alt="Símbolo de início">         | Símbolo de início     | Representa o início de um processo ou atividade.                                             |
| <img src="/assets/atividades/atividades.png" style="width: 7vw;" alt="Símbolo de atividade">  | Símbolo de atividade  | Indica uma etapa de execução ou uma tarefa no processo.                                      |
| <img src="/assets/atividades/bifurcacao.png" style="width: 7vw;" alt="Símbolo de bifurcação"> | Símbolo de bifurcação | Representa um ponto de decisão que divide o fluxo em dois ou mais caminhos.                  |
| <img src="/assets/atividades/juncao.png" style="width: 7vw;" alt="Símbolo de junção">         | Símbolo de junção     | Indica a convergência de múltiplos fluxos em um único caminho.                               |
| <img src="/assets/atividades/decisao.png" style="width: 7vw;" alt="Símbolo de decisão">       | Símbolo de decisão    | Representa um ponto em que uma escolha é feita, geralmente entre opções "sim" ou "não".      |
| <img src="/assets/atividades/alfinete.png" style="width: 7vw;" alt="Símbolo de decisão">      | Símbolo de alfinete   | Representa um nó de entrada ou saída de uma ação, responsável por fornecer ou receber dados. |
| <img src="/assets/atividades/fim.png" style="width: 7vw;" alt="Símbolo de término">           | Símbolo de término    | Indica o fim de um processo ou atividade.                                                    |

</div>

## Resultados

<!--
- **Apresente o produto final, como o diagrama ou solução desenvolvida.**
- **Desenvolva ao menos um parágrafo referenciando a figura**
- **Adicione "Figura 1 - Título da Figura/Quadro/Tabela" acima e "Fonte: " abaixo dela**
- Destaque os pontos principais ou insights obtidos durante o processo.
- **APRESENTE AS VERSÕES DO DIAGRAMA!! Podem usar o formato abaixo para poluir menos a página**
-->

A Figura 1 representa o Diagrama de Atividade proposto pela equipe.

<center><b>Figura 1 -</b> Diagrama de Atividade atual da equipe</center>

![Versão 1.0](../assets/diagramaatividade.png)

<center><b>Fonte:</b> </center>

### Versões Anteriores

<details>
<summary>Visualizar versão 1.0</summary>

### Versão 1.0

A Figura 2 representa o Diagrama de Atividade proposto pela equipe.

<center><b>Figura 2 -</b> Diagrama de Atividade versão 1.0</center>

![Versão 1.0](../assets/diagramaatividade.png)

<center><b>Fonte:</b> </center>

</details>

## Conclusão

<!--
-   **Resuma os pontos principais do trabalho.**
-   **Avalie se os objetivos foram alcançados e o impacto do trabalho.**
-   **Apresente perspectivas para melhorias ou trabalhos futuros.**
-->

<div align="justify">

&emsp;&emsp;
Os diagramas de atividades desenvolvido apresentou uma visão clara e estruturada dos processos relacionados as funcionalidades a serem implementadas, destacando os principais passos, decisões e interações envolvidas. Por meio dele, foi possível identificar problemas e dificuldades relativos a futura implementação de alguns requisitos permitindo a equipe abordar e resolver esses conflitos sem gastar muito tempo com retrabalho, comprovando portanto sua utilidade para a análise e comunicação entre os envolvidos no projeto. Um exemplo disso foi a decisão de simplificar a implementação dos fios de cobre, uma vez que o planejamento da equipe ia além do requisito correspondente, o que dificultaria muito a implementação. Os objetivos propostos foram plenamente alcançados, pois o diagrama facilitou o entendimento das atividades e promoveu alinhamento entre os membros em diversos aspectos, como por exemplo em como a transmissão de sinais sem fio estava contida nos requisitos ligados às antenas de redstone.
</div>


<div align="justify">

&emsp;&emsp;
Ademais, os diagramas de atividades construídos consolidaram a visão coletiva da equipe, superando possíveis discordâncias entre os subgrupos e promovendo uma integração mais eficiente. A fragmentação dos requisitos em fluxos, estados e processos detalhados não apenas tornou mais claro o entendimento para as fases de desenvolvimento e teste, mas também proporcionou uma base sólida para futuras iterações do projeto. Esse nível de detalhamento garante que todos os envolvidos tenham uma compreensão uniforme dos objetivos e desafios do sistema, o que potencializa a qualidade das entregas bem como sua fidelidade aos requisitos elicitados. Além disso, os diagramas abrem caminho para melhorias contínuas, como a inclusão de métricas de desempenho e a validação cruzada com outros artefatos, garantindo que o processo de desenvolvimento seja ágil e eficaz.
</div>

## Bibliografia

<!-- - **Altere!**-->

> [1] SERRANO, Milene. Videoaula: [06c - VídeoAula - DSW - Modelagem - Diagrama de Atividades](https://unbbr-my.sharepoint.com/:v:/g/personal/mileneserrano_unb_br/Ed9k-OvMH7hMlNMj6CGVenMBSyeVrDBOdg84Czx_aHI9gw?e=ZzFF4A). [Online]. Disponível em: [https://unbbr-my.sharepoint.com/:v:/g/personal/mileneserrano_unb_br/Ed9k-OvMH7hMlNMj6CGVenMBSyeVrDBOdg84Czx_aHI9gw?e=ZzFF4A](https://unbbr-my.sharepoint.com/:v:/g/personal/mileneserrano_unb_br/EcEx3UfhmvlAliVpLUlXelQBfaD1EFsNIpL32EMWqRptYg?e=qeIjLP). 2020. Acesso em: 25 nov. 2024.

> [2] GUEDES, Gilleanes TA. UML 2. **Uma Abordagem Prática”, São Paulo, Novatec**. 2009.

<center>

## Participantes

</center>

<!-- de preferência: em ordem alfabética, seguindo o exemplo: -->

<div style="margin: 0 auto; width: fit-content;">

| Matrícula | Aluno                                 | Git                                                           |
|-----------|---------------------------------------|---------------------------------------------------------------|
| 221021886 | Cássio Sousa dos Reis                 | [csreis72](https://github.com/csreis72)                       |
| 221008024 | Eduardo Matheus dos Santos Sandes     | [DiceRunner714](https://github.com/DiceRunner714)             |
| 170010872 | Gabriela de Oliveira Lemos            | [heylisten64](https://github.com/heylisten64)                 |
| 221008150 | João Antonio Ginuino Carvalho         | [joaoseisei](https://github.com/joaoseisei)                   |
| 221008697 | Sunamita Vitória Rodrigues dos Santos | [sunamit](https://github.com/sunamit)                         |
| 211062526 | Thomas Queiroz Souza Alves            | [thmasq](https://github.com/thmasq)                           |
| 202017263 | Vinicius de Oliveira Santos           | [ViniciussdeOliveira](https://github.com/ViniciussdeOliveira) |


</div>

---

<center>

## Histórico de Versão

</center>

<!-- Lembre de alterar a data -->

<div style="margin: 0 auto; width: fit-content;">

| Versão | Data da alteração |                         Alteração                          |                                        Responsável                                         | Revisor | Data de revisão |
|:------:|:-----------------:|:----------------------------------------------------------:|:------------------------------------------------------------------------------------------:|:-------:|:---------------:|
|  1.0   |       25/11       | Criação do documento e adição de introdução e bibliografia |                      [Gabriela Lemos](https://github.com/heylisten64)                      |
|  1.0   |       26/11       |                   Adição de metodologia                    |                      [Gabriela Lemos](https://github.com/heylisten64)                      |
|  1.0   |       27/11       |                     Adiciona conclusão                     |                     [DiceRunner714](https://github.com/DiceRunner714)                      |
|  1.0   |       27/11       |              Adiciona legenda e contribuição               | [joaoseisei](https://github.com/joaoseisei), [heylisten64](https://github.com/heylisten64) |

</div>

## Controle de Revisão

| Revisor(es) | O que foi realizado |
| :---------: | :-----------------: |
|             |                     |