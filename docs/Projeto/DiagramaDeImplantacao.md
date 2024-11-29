# Diagrama de Implantação

## Introdução

<!--
- **Apresente o tema do projeto ou estudo;**
- **Busque trazer referências no decorrer do texto;**
- Destaque a relevância do diagrama ou abordagem para a área de aplicação.
- Mencione brevemente os principais aspectos que serão abordados no documento.
-->

<div align="justify">

&emsp;&emsp;
O **Diagrama de Implantação** é fundamental na modelagem de aplicações que envolvem diferentes dispositivos, pois permite representar visualmente as características físicas de um sistema e suas necessidades de hardware - como, por exemplo, servidores, estações, topologias e protocolos de comunicação (GUEDES, 2009). O diagrama de implantação é uma representação visual das arquiteturas físicas envolvidas na execução do sistema.

</div>

<div align="justify">

&emsp;&emsp;
Além disso, essa representação demonstra a distribuição dos módulos do sistema utilizando os conceitos de nós e associações, contribuindo para a identificação de possíveis gargalos e conflitos entre componentes. Tal análise facilita o processo de tomada de decisões pela equipe de desenvolvimento ao documentar elementos principais como servidores, APIs e dependências externas, uma vez que se torna possível identificar uma visão geral da organização técnica do sistema o que garante melhor compreensão da estrutura do projeto para toda a equipe (GUEDES, 2009; PAIVA, 2021). Este tipo de diagrama é essencial para entender como o mod será hospedado, testado e distribuído, e como ele interage com o cliente do Minecraft e servidores.

</div>

## Objetivo

<!--
- **Declare o que se pretende alcançar com o diagrama em projetos no geral; Busque referenciar!**
- **Declare o que se pretende alcançar com o diagrama para equipe neste contexto;**
- **Destaque os resultados esperados, como soluções para problemas, melhorias no entendimento ou suporte à tomada de decisões.**
-->

<div align="justify">

&emsp;&emsp;
O objetivo do diagrama de implantação é mapear como o projeto será integrado ao cliente do Minecraft, descrevendo as APIs que serão consumidas, assim como se ficarão atreladas ao cliente ou ao servidor. Para a equipe de desenvolvimento, o diagrama fornece clareza sobre as dependências de hardware e software, facilitando a tomada de decisões sobre compatibilidade, configuração de servidores e ambientes de teste. Ele também destaca os fluxos de comunicação e a alocação de recursos, garantindo que a arquitetura física do sistema suporte as funcionalidades previstas no diagrama de classes.

</div>

## Metodologia

<!--
- **Explique o processo utilizado para desenvolver o trabalho. COMO foi feito?**
- **Descreva as ferramentas, técnicas ou referências utilizadas na construção do diagrama ou solução. Se houver alguma ferramenta específica determinada pela professora, a sugestão é usá-la sendo em qualquer etapa do processo. Podem começar com uma ferramenta que já são familiarizados e depois explorar outras ferramentas.**
- Se desejarem, podem citar os desafios encontrados seguindo a metodologia, propostas de melhoria, etc.
-->

<div align="justify">

&emsp;&emsp;
O desenvolvimento do diagrama foi baseado nos requisitos não funcionais de compatibilidade e desempenho, buscando garantir a integração eficaz entre diferentes versões do Minecraft e servidores, enquanto minimiza impactos negativos no desempenho do sistema.

</div>

<div align="justify"> &emsp;&emsp;
Para representar as interações entre os componentes, ferramentas UML foram utilizadas, resultando em um diagrama que demonstra como o mod interage com as instâncias do servidor, o cliente do jogo e outros. O modelo foi estruturado de forma a destacar as dependências entre os elementos, como o arquivo principal do mod (Logic-Thinking.jar), módulos auxiliares como AlmostUnified.jar e JEI.jar, para garantir compatibilidade com outros mod's, e o framework Fabric Loader.

</div>

## Resultados

<!--
- **Apresente o produto final, como o diagrama ou solução desenvolvida.**
- **Desenvolva ao menos um parágrafo referenciando a figura**
- **Adicione "Figura 1 - Título da Figura/Quadro/Tabela" acima e "Fonte: " abaixo dela**
- Destaque os pontos principais ou insights obtidos durante o processo.
- **APRESENTE AS VERSÕES DO DIAGRAMA!! Podem usar o formato abaixo para poluir menos a página**
-->

<div align="justify">

&emsp;&emsp;
O diagrama de implantação demonstra como o mod interage com o cliente do Minecraft e com servidores multiplayer. Ele destaca o papel dos módulos na gestão dos sinais de redstone e a interação com o hardware do jogador. Componentes como o servidor de Minecraft são mostrados hospedando instâncias do mod, enquanto o cliente é responsável pela execução das interfaces gráficas e elementos visuais, como o minimapa. A representação também ilustra o uso de bibliotecas externas e APIs de Minecraft para integrar as funcionalidades do mod ao jogo.

</div>

A última versão do Diagrama de Implantação pode ser vista na Figura 1.

<center><b>Figura 1 -</b> Diagrama de Implantação Versão 2.0</center>
<center>

<!-- ![versão_final](https://raw.githubusercontent.com/UnBArqDsw2024-2/2024.2_G1_Logic_Thinkering_Entrega_02/refs/heads/main/assets/diagamaImplantacao/DIv2.png) -->

![versão_final](https://raw.githubusercontent.com/UnBArqDsw2024-2/2024.2_G1_Logic_Thinkering_Entrega_02/refs/heads/main/assets/diagramaImplantacao/DIv2.png)

</center>
<center><b>Fonte: </b> Queioz, Carvalho, Lemos, 2024</center>

### Versões Anteriores

<details>

<summary>Visualizar versão 1.0</summary>

### Versão 1.0

Primeira versão do Diagrama de Implantação pode ser vista na Figura 2.

<center><b>Figura 2 -</b> Diagrama de Implantação Versão 1.0</center>
<center>

![versão_1.0](https://raw.githubusercontent.com/UnBArqDsw2024-2/2024.2_G1_Logic_Thinkering_Entrega_02/refs/heads/main/assets/diagramaImplantacao/DIv1.png)

</center>
<center><b>Fonte: </b>Lemos, 2024</center>

</details>

## Conclusão

<!--
-   **Resuma os pontos principais do trabalho.**
-   **Avalie se os objetivos foram alcançados e o impacto do trabalho.**
-   **Apresente perspectivas para melhorias ou trabalhos futuros.**
-->

<div align="justify">

&emsp;&emsp;
Portanto, O diagrama garante que a arquitetura física do projeto é compatível com os requisitos funcionais e não funcionais, abordando questões de desempenho, compatibilidade e escalabilidade. Ele fornece uma base sólida para testes em diferentes ambientes e simplifica o diagnóstico de problemas relacionados à execução do mod. O trabalho futuro pode incluir a modelagem de configurações avançadas de servidores e a avaliação de tecnologias adicionais que possam otimizar a experiência do usuário em ambientes multiplayer.

</div>

## Bibliografia

<!-- - **Altere!**-->

> [1]: GUEDES, Gilleanes TA. UML 2. **Uma Abordagem Prática”, São Paulo, Novatec**, p. 32, 2009.

> [2]: PAIVA, Professor. **Curso de UML - Diagrama de Implantação**. Ano de publicação: 2021. Disponível em: [https://www.youtube.com/watch?v=DgERD0HgggQ](https://www.youtube.com/watch?v=DgERD0HgggQ). Acesso em: 21 nov. 2024.

<center>

## Participantes

</center>

<!-- de preferência: em ordem alfabética, seguindo o exemplo: -->

<div style="margin: 0 auto; width: fit-content;">

| Matrícula | Aluno                             | Git                                               |
| --------- | --------------------------------- | ------------------------------------------------- |
| 221007869 | Artur Henrique Holz Bartz         | [H0lzz](https://github.com/H0lzz)                 |
| 170010872 | Gabriela de Oliveira Lemos        | [heylisten64](https://github.com/heylisten64)     |
| 211062526 | Thomas Queiroz Souza Alves        | [thmasq](https://github.com/thmasq)               |
| 221008150 | João Antonio Ginuino Carvalho     | [joaoseisei](https://github.com/joaoseisei)       |
| 221008024 | Eduardo Matheus dos Santos Sandes | [DiceRunner714](https://github.com/DiceRunner714) |

</div>

---

<center>

## Histórico de Versão

</center>

<!-- Lembre de alterar a data -->

<div style="margin: 0 auto; width: fit-content;">

| Versão | Data da alteração |                         Alteração                          |                                                               Responsável                                                               |                      Revisor                       | Data de revisão |
| :----: | :---------------: | :--------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------: | :-------------: |
|  1.0   |       21/11       | Criação do documento e adição de Introdução e Bibliografia |                                            [Gabriela Lemos](https://github.com/heylisten64)                                             |      [Artur Bartz](https://github.com/H0lzz)       |      25/11      |
|  2.0   |       25/11       |  Adição de Objetivos, Metodologia, Resultados e Conclusão  |                                                 [Artur Bartz](https://github.com/H0lzz)                                                 |    [joaoseisei](https://github.com/joaoseisei)     |      27/11      |
|  2.1   |       25/11       |           Adiciona versão melhorada do diagrama            | [Gabriela Lemos](https://github.com/heylisten64), [Thomas Q](https://github.com/thmasq), [João Carvalho](https://github.com/joaoseisei) | [Eduardo Sandes](https://github.com/DiceRunner714) |      27/11      |

</div>

## Controle de Revisão

|                          Revisor(es)                          |                                                                                    O que foi realizado                                                                                     |
| :-----------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|            [Artur Bartz](https://github.com/H0lzz)            | Foi revisada a Introdução e adicionado informações que o diagrama reflete na hospedagem, testagem e distribuição do mod, assim como sua interação com o cliente do Minecraft e servidores. |
|          [joaoseisei](https://github.com/joaoseisei)          |                                                             Corrige a identação dos parágrafos e adiciona versões anteriores.                                                              |
|             [Thomas Q](https://github.com/thmasq)             |                                                                    Clarificação nos Objetivos; Formatação do documento                                                                     |
| [ViniciussdeOliveira](https://github.com/ViniciussdeOliveira) |                                                                                 Corrige o link das imagens                                                                                 |
|      [Eduardo Sandes](https://github.com/DiceRunner714)       |                                                                                   Incrementa metodologia                                                                                   |
