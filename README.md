[![author](https://img.shields.io/badge/author-leandrovalter-red.svg)](https://www.linkedin.com/in/leandrovalter) [![author](https://img.shields.io/badge/author-thiagooliveira-green.svg)](https://www.linkedin.com/in/tiago-almeida-de-oliveira-9b3baa27/)


<h1>Análise de sobrevivência</h1>
<h6>Modelando dados com cesura<h6>
   
<p align="center">
<img src="19876.jpg" alt="drawing" width="500"/>
</p>


<p style="text-align:justify;"> A análise de sobrevivência é o estudo dos tempos de sobrevivência e dos fatores que os influenciam. Os tipos de estudos com resultados de sobrevivência incluem ensaios clínicos, estudos observacionais prospectivos e retrospectivos e experimentos com animais. Poderia ser estudado o tempo desde o nascimento até a morte, tempo desde a entrada em um ensaio clínico até a morte ou progressão da doença, ou tempo desde o nascimento até o desenvolvimento do câncer de mama.</p> 
</p>  
O nosso interresse também pode se referir a um acontecimento positivo. Por exemplo, o acompanhamento de pacientes que foram diagnósticados com COVID-19 até o momento que tenham uma resposta imune ao vírus, assim bloqueando a ação do vírus.
 

Os estudos de sobrevivência podem envolver estimativa da distribuição de sobrevivência, comparações das distribuições de sobrevivência de vários tratamentos ou intervenções ou elucidação dos fatores que influenciam os tempos de sobrevivência. 

Análise de Sobrevivência é caracterizada pela presença de censura nos dados. Onde censura pode ser definida como ausência da ocorrência do evento durante o tempo de estudo. Ou seja, por motivos que não envolvem o objetivo do estudo, o elemento não apresenta falha ou, até  mesmo quando os eventos iniciais ou finais não são observados com precisão.

Podem existir muitos movitos para ser registrada a censura no estudo. Por exemplo, a impossibilidade de um paciente continuar a participar do estudo, substituição de um equipamento, etc. Assim, o tempo até a ocorrência da censura é registrado e levado em consideração nos modelos de sobrevivência. 


Como fazer uma análise de sobrevivência?

Muitos softwares de análise estatística possuem recursos para se estimar os modelos de sobrevivência. Por exemplo, tanto o *R* quanto o *Python* possuem específicas para a análise de dados de sobrevivência. Abaixo temos exemplos de análises comentadas em *software R* (Breve em Python).

## Projetos:
Projetos de análise de sobrevivência:

* **Modelos de riscos proporcionais de Cox:** https://rpubs.com/ValterL/coxph01 -**R**
