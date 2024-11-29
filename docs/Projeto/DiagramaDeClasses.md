## Introdução 
<!--  
- **Apresente o tema do projeto ou estudo;**
- **Busque trazer referências no decorrer do texto;**
- Destaque a relevância do diagrama ou abordagem para a área de aplicação.
- Mencione brevemente os principais aspectos que serão abordados no documento.
-->
<div align="justify">&emsp;&emsp;
O uso de diagramas de classes é fundamental em engenharia de software, pois promove clareza na modelagem do sistema, garantindo rastreabilidade e organização dos requisitos. Ao ilustrar a estrutura de classes, destacam-se relações, atributos e métodos que permitem maior entendimento da arquitetura proposta, favorecendo a implementação colaborativa e eficiente.
</div>

## Objetivo
<!--  
- **Declare o que se pretende alcançar com o diagrama em projetos no geral; Busque referenciar!**
- **Declare o que se pretende alcançar com o diagrama para equipe neste contexto;**
- **Destaque os resultados esperados, como soluções para problemas, melhorias no entendimento ou suporte à tomada de decisões.**
-->
<div align="justify">&emsp;&emsp;
O diagrama de classes visa facilitar a compreensão e implementação das funcionalidades do mod, oferecendo uma visão estruturada dos blocos, itens e sistemas introduzidos. Para a equipe, o objetivo é mitigar ambiguidades durante o desenvolvimento, evidenciar dependências entre classes e suportar a expansão futura do sistema. Especificamente neste contexto, espera-se que o diagrama funcione como uma referência centralizada para a modelagem do código, promovendo padronização e integração das novas funcionalidades ao código original do jogo.
</div>

## Metodologia
<!--  
- **Explique o processo utilizado para desenvolver o trabalho. COMO foi feito?**
- **Descreva as ferramentas, técnicas ou referências utilizadas na construção do diagrama ou solução. Se houver alguma ferramenta específica determinada pela professora, a sugestão é usá-la sendo em qualquer etapa do processo. Podem começar com uma ferramenta que já são familiarizados e depois explorar outras ferramentas.**
- Se desejarem, podem citar os desafios encontrados seguindo a metodologia, propostas de melhoria, etc.
-->

<div align="justify">&emsp;&emsp;
A construção do diagrama seguiu os princípios de orientação a objetos, alinhando-se à arquitetura do Minecraft na versão Fabric 1.21.X, toda
a documentação referente a essa versão está disponível em <a href="https://docs.fabricmc.net/">https://docs.fabricmc.net/</a>, além disso
funcionalidades que não estavam de acordo com a documentação foram implementadas através de engenharia reversa do código fonte do minecraft
disponível em <a href="https://github.com/FabricMC/fabric-example-mod">https://github.com/FabricMC/fabric-example-mod</a>.
</div>
<div align="justify">&emsp;&emsp;
Sendo assim a base foi estruturada considerando as classes principais do jogo original, que foram estendidas para incluir novos comportamentos. Ferramentas de modelagem UML foram utilizadas para criar o diagrama, permitindo representação visual das relações, como heranças e associações. O processo foi iterativo, revisando e validando os requisitos junto à equipe, e ajustando a modelagem para garantir consistência com os objetivos do projeto.
</div>
<div align="justify">&emsp;&emsp;
Ademais foi analisando a arquitetura de componentes do jogo original foi possível separar o mod em 3 funcionalidades gerais sendo elas:
</div>
<br>
<div style="margin: 0 auto; width: fit-content;">

| **Nome**         | **Requisito Funcional**                               | **Responsável**                                         |
|------------------|-------------------------------------------------------|---------------------------------------------------------|
| Itens Comuns     | RFO1,                                                 | Gabriela Lemos, João Carvalho, Thomas Alves             |
| Itens Complexos  | RF02, RF03                                            | João Carvalho, Thomas Alves, André Silva                |
| Blocos Comuns    | RF04                                                  | Eduardo Sandes, João Carvalho                           |
| Blocos Complexos | RF06, RF07, RF08, RF09, RF12, RF16, RF17, RF18, RF19, | Artur Bartz, João Carvalho, Eduardo Sandes, André Silva |
| Minimapa         | RF10, RF11,                                           | Artur Bartz, João Carvalho, André Silva, Thomas Alves   |
| Livros           | RF14, RF15, RF24                                      | Samara Santos, João Carvalho                            |

</div>

## Resultados
<!--  
- **Apresente o produto final, como o diagrama ou solução desenvolvida.** 
- **Desenvolva ao menos um parágrafo referenciando a figura**
- **Adicione "Figura 1 - Título da Figura/Quadro/Tabela" acima e "Fonte: " abaixo dela**
- Destaque os pontos principais ou insights obtidos durante o processo.
- **APRESENTE AS VERSÕES DO DIAGRAMA!! Podem usar o formato abaixo para poluir menos a página**
-->


<div align="justify">&emsp;&emsp;
O diagrama final inclui classes que implementam portas lógicas no sistema de redstone, que descrevem novos materiais reforçados, que automatizam tarefas de mineração. As classes de novos itens, como ferramentas e armaduras reforçadas, estão integradas com uma interface que centraliza funcionalidades de carga. Além disso, o minimapa interage com classes de sinal para fornecer detecção em tempo real de atividades redstone. Essa modelagem permite escalabilidade e flexibilidade para futuras iterações.
</div>

A Figura 1 apresenta o diagrama de classe final com todas os requisitos do backward from.

<center><b>Figura 1 -</b> Diagrama de classe final</center>

![](https://raw.githubusercontent.com/UnBArqDsw2024-2/2024.2_G1_Logic_Thinkering_Entrega_02/refs/heads/main/assets/diagramaClasse/DCv3.0.png)

<center><b>Fonte:</b> Lemos, Alves, Silva, Carvalho, Sandes, Santos, 2024.</center>

### Versões Anteriores


<details>
<summary>Visualizar versão 2.0</summary>

### Versão 1.1

A Figura 2 e 3 apresenta o Diagrama de Classes dos itens comuns e complexos respectivamente.

<center><b>Figura 2 -</b> Diagrama de Classes de Itens comuns</center>

![](https://raw.githubusercontent.com/UnBArqDsw2024-2/2024.2_G1_Logic_Thinkering_Entrega_02/refs/heads/main/assets/diagramaClasse/DCv2.1.png)

<center><b>Fonte:</b> Lemos, Sandes, Carvalho, 2024.</center>

<br>

<center><b>Figura 3 -</b> Diagrama de Classes de Itens complexos</center>

![](https://raw.githubusercontent.com/UnBArqDsw2024-2/2024.2_G1_Logic_Thinkering_Entrega_02/refs/heads/main/assets/diagramaClasse/DCv2.0.png)

<center><b>Fonte:</b> Alves, 2024.</center>

</details>

<details>
<summary>Visualizar versão 1.0</summary>

### Versão 1.0

Primeiro rascunho do Diagrama de Classes pode ser vista na Figura 4.

<center><b>Figura 4 -</b> Diagrama de Classes versão 1.0</center>

![](https://raw.githubusercontent.com/UnBArqDsw2024-2/2024.2_G1_Logic_Thinkering_Entrega_02/refs/heads/main/assets/diagramaClasse/DCv1.0.png)

<center><b>Fonte:</b> Silva, Bartz, Sandes, Lemos, Carvalho, Santos, Alves, 2024.</center>

</details>

## Conclusão
<!--  
-   **Resuma os pontos principais do trabalho.**
-   **Avalie se os objetivos foram alcançados e o impacto do trabalho.**
-   **Apresente perspectivas para melhorias ou trabalhos futuros.**
-->


<div align="justify">&emsp;&emsp;
O diagrama de classes atinge o objetivo de estruturar os requisitos do mod, promovendo clareza e integração com o código original do Minecraft. Ele é essencial para alinhar a visão da equipe, identificando dependências e promovendo a modularidade do sistema. Melhorias podem ser feitas para garantir maior consistência durante as implementações subsequentes.
</div>

## Bibliografia 

> [1] SERRANO, Milene. Videoaula: [05b - VideoAula - DSW - Modelagem - Diagrama de Classe](https://unbbr-my.sharepoint.com/:v:/g/personal/mileneserrano_unb_br/EZPNTlqmVjNOqXT1Bm2uUrcBsfMyv68qkyEL_rFMNSEy0g?e=lhFYa3). [Online]. Disponível em: [https://unbbr-my.sharepoint.com/:v:/g/personal/mileneserrano_unb_br/EZPNTlqmVjNOqXT1Bm2uUrcBsfMyv68qkyEL_rFMNSEy0g?e=lhFYa3) . Acesso em: 21 nov. 2024.

> [2] Reis, fabio. Videoaula: [Curso de UML O que é um Diagrama de Classes](https://youtu.be/JQSsqMCVi1k) . [Online]. Disponível em: <https://youtu.be/JQSsqMCVi1k>. Acesso em: 24 nov. 2024.

> [3] Reis, fabio. Videoaula: [Curso de UML - Diagrama de Classes - Relacionamentos](https://youtu.be/IJtQWLnHvcQ) . [Online]. Disponível em: <https://youtu.be/IJtQWLnHvcQ>. Acesso em: 24 nov. 2024.

<center>

## Participantes

</center>

<!-- de preferência: em ordem alfabética, seguindo o exemplo: -->

<div style="margin: 0 auto; width: fit-content;">

| Matrícula | Aluno                             | Git                                                   |
|-----------|-----------------------------------|-------------------------------------------------------|
| 221007813 | André Emanuel Bispo da Silva      | [Hunter104](https://github.com/Hunter104)             |
| 221007869 | Artur Henrique Holz Bartz         | [H0lzz](https://github.com/H0lzz)                     |
| 221008024 | Eduardo Matheus dos Santos Sandes | [DiceRunner714](https://github.com/DiceRunner714)     |
| 170010872 | Gabriela de Oliveira Lemos        | [heylisten64](https://github.com/heylisten64)         |
| 221008150 | João Antonio Ginuino Carvalho     | [joaoseisei](https://github.com/joaoseisei)           |
| 221008445 | Samara Letícia Alves dos Santos   | [samarawwleticia](https://github.com/samarawwleticia) |
| 211062526 | Thomas Queiroz Souza Alves        | [thmasq](https://github.com/thmasq)                   |


</div>

---

<center>

## Histórico de Versão

</center>

<div style="margin: 0 auto; width: fit-content;">

| Versão | Data da alteração |                     Alteração                     |                                                                                                                                                                Responsável                                                                                                                                                                |                    Revisor                     | Data de revisão |
|:------:|:-----------------:|:-------------------------------------------------:|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------:|:---------------:|
|  1.0   |       21/11       |               Criação do documento                |                                                                                                                                                  [Artur Barlz](https://github.com/H0lzz)                                                                                                                                                  | [João Carvalho](https://github.com/joaoseisei) |      28/11      |
|  2.0   |       23/11       | Adição da Primeira versão do Diagrama de Classes  | [André Silva](https://github.com/Hunter104), [Artur Barlz](https://github.com/H0lzz), [Euardo Sandes](https://github.com/DiceRunner714), [Gabriela Lemos](https://github.com/heylisten64), [João Carvalho](https://github.com/joaoseisei), [Samara Santos](https://github.com/samarawwleticia), [Thomas Alves](https://github.com/thmasq) | [João Carvalho](https://github.com/joaoseisei) |      28/11      |
|  2.1   |       24/11       | Adiciona referências e estudo do minecraft fabric |                                                  [Artur Barlz](https://github.com/H0lzz), [Euardo Sandes](https://github.com/DiceRunner714), [Gabriela Lemos](https://github.com/heylisten64), [João Carvalho](https://github.com/joaoseisei), [Thomas Alves](https://github.com/thmasq)                                                  | [João Carvalho](https://github.com/joaoseisei) |      28/11      |
|  2.2   |       28/11       |              Adiciona diagrama final              |                     [André Silva](https://github.com/Hunter104), [Euardo Sandes](https://github.com/DiceRunner714), [Gabriela Lemos](https://github.com/heylisten64), [João Carvalho](https://github.com/joaoseisei), [Thomas Alves](https://github.com/thmasq), [Samara Santos](https://github.com/samarawwleticia)                      | [João Carvalho](https://github.com/joaoseisei) |      28/11      |

</div>

## Controle de Revisão

|                  Revisor(es)                   |                                        O que foi realizado                                         |
|:----------------------------------------------:|:--------------------------------------------------------------------------------------------------:|
| [João Carvalho](https://github.com/joaoseisei) | Adiciona detalhamento na metodologia e corrige o diagrama de acordo com o matérial na bibliografia |