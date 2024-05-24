# 1 - Identificação de uma base de dados de interesse:

Fonte:

https://worldhappiness.report/  
https://worldhappiness.report/data/

Dataset:

[World Happiness Report 2023.csv](https://github.com/Luannsz/estimate-of-the-best-country-to-live-in/files/15422833/World.Happiness.Report.2023.csv)

## Dicionário de dados original: 

| Atributos | Tipo de Dado | Descrição |
| ----------| ------------ | ----------|
Country name | textual | O nome do país. |
Ladder score | numérico | Pontuação na escada: Uma medida de bem-estar subjetivo, frequentemente usada como um proxy para felicidade ou satisfação com a vida. |
Standard error of ladder score | numérico | Erro padrão da pontuação na escada: O erro padrão associado à pontuação na escada, indicando a precisão da estimativa. |
upperwhisker | numérico | Limite superior da caixa (whisker): A extremidade superior do intervalo de confiança para a pontuação na escada. |
lowerwhisker | numérico | Limite inferior da caixa (whisker): A extremidade inferior do intervalo de confiança para a pontuação na escada. |
Logged GDP per capita | numérico | PIB per capita registrado: O logaritmo natural do Produto Interno Bruto (PIB) per capita, uma medida de desempenho econômico. |
Social support | numérico | Apoio social: Uma medida da força de redes sociais e sistemas de apoio dentro de um país. |
Healthy life expectancy | numérico | Expectativa de vida saudável: O número médio de anos que uma pessoa pode esperar viver em boa saúde. |
Freedom to make life choices | numérico | Liberdade para fazer escolhas de vida: O grau de liberdade que os indivíduos têm ao fazer escolhas de vida, como em suas carreiras, relacionamentos e atividades pessoais. |
Generosity | numérico | Generosidade: A tendência dos indivíduos de se engajarem em atos de caridade ou de ajudar os outros. |
Perceptions of corruption | numérico | Percepções de corrupção: O nível percebido de corrupção dentro de um país. |
Ladder score in Dystopia | numérico | Pontuação na escada em Dystopia: A pontuação hipotética mais baixa possível na escada, usada como ponto de referência. |
Explained by: Log GDP per capita | numérico | (Explicado por: Log PIB per capita): Refere-se à contribuição da renda per capita (PIB) para a pontuação na escada. |
Explained by: Social support | numérico | (Explicado por: Apoio social): Indica a contribuição do apoio social para a pontuação na escada. |
Explained by: Healthy life expectancy | numérico | (Explicado por: Expectativa de vida saudável): Refere-se à contribuição da expectativa de vida saudável para a pontuação na escada. |
Explained by: Freedom to make life choices | numérico | (Explicado por: Liberdade para fazer escolhas de vida): Indica a contribuição da liberdade individual para tomar decisões de vida para a pontuação na escada. | 
Explained by: Generosity | numérico | (Explicado por: Generosidade): Refere-se à contribuição da generosidade para a pontuação na escada. |
Explained by: Perceptions of corruption | numérico | (Explicado por: Percepções de corrupção): Indica a contribuição das percepções de corrupção para a pontuação na escada. |
Dystopia + residual | numérico | Dystopia + residual: Uma combinação da pontuação hipotética mais baixa possível na escada (Dystopia) e qualquer variância não explicada (residual) nos dados. |

## Dicionário de dados modificado:

| Atributos | Tipo de Dado | Descrição |
| ----------| ------------ | ----------|
Country name | textual | O nome do país. |
Ladder score | numérico | Pontuação na escada: Uma medida de bem-estar subjetivo, frequentemente usada como um proxy para felicidade ou satisfação com a vida. |
Standard error of ladder score | numérico | Erro padrão da pontuação na escada: O erro padrão associado à pontuação na escada, indicando a precisão da estimativa. |
Logged GDP per capita | numérico | PIB per capita registrado: O logaritmo natural do Produto Interno Bruto (PIB) per capita, uma medida de desempenho econômico. |
Social support | numérico | Apoio social: Uma medida da força de redes sociais e sistemas de apoio dentro de um país. |
Healthy life expectancy | numérico | Expectativa de vida saudável: O número médio de anos que uma pessoa pode esperar viver em boa saúde. |
Freedom to make life choices | numérico | Liberdade para fazer escolhas de vida: O grau de liberdade que os indivíduos têm ao fazer escolhas de vida, como em suas carreiras, relacionamentos e atividades pessoais. |
Generosity | numérico | Generosidade: A tendência dos indivíduos de se engajarem em atos de caridade ou de ajudar os outros. |
Perceptions of corruption | numérico | Percepções de corrupção: O nível percebido de corrupção dentro de um país. |
Ladder score in Dystopia | numérico | Pontuação na escada em Dystopia: A pontuação hipotética mais baixa possível na escada, usada como ponto de referência. |
Explained by: Log GDP per capita | numérico | (Explicado por: Log PIB per capita): Refere-se à contribuição da renda per capita (PIB) para a pontuação na escada. |
Explained by: Social support | numérico | (Explicado por: Apoio social): Indica a contribuição do apoio social para a pontuação na escada. |
Explained by: Healthy life expectancy | numérico | (Explicado por: Expectativa de vida saudável): Refere-se à contribuição da expectativa de vida saudável para a pontuação na escada. |
Explained by: Freedom to make life choices | numérico | (Explicado por: Liberdade para fazer escolhas de vida): Indica a contribuição da liberdade individual para tomar decisões de vida para a pontuação na escada. | 
Explained by: Generosity | numérico | (Explicado por: Generosidade): Refere-se à contribuição da generosidade para a pontuação na escada. |
Explained by: Perceptions of corruption | numérico | (Explicado por: Percepções de corrupção): Indica a contribuição das percepções de corrupção para a pontuação na escada. |
Dystopia + residual | numérico | Dystopia + residual: Uma combinação da pontuação hipotética mais baixa possível na escada (Dystopia) e qualquer variância não explicada (residual) nos dados. |

*Foram eliminados os atributos upperwhisker e lowerwhisker.

## Apresentação de uma amostra dos dados:

Country name	Ladder score	Standard error of ladder score	Logged GDP per capita	Social support	Healthy life expectancy	Freedom to make life choices	Generosity	Perceptions of corruption	Ladder score in Dystopia	Explained by: Log GDP per capita	Explained by: Social support	Explained by: Healthy life expectancy	Explained by: Freedom to make life choices	Explained by: Generosity	Explained by: Perceptions of corruption	Dystopia + residual		
Finland 	7.804	0.036	10.792	0.969	71.150	0.961	-0.019	0.182	1.778	1.888	1.585	0.535	0.772	0.126	0.535	2.363		
Denmark 	7.586	0.041	10.962	0.954	71.250	0.934	0.134	0.196	1.778	1.949	1.548	0.537	0.734	0.208	0.525	2.084		
Iceland 	7.530	0.049	10.896	0.983	72.050	0.936	0.211	0.668	1.778	1.926	1.620	0.559	0.738	0.250	0.187	2.250		
Israel 	        7.473	0.032	10.639	0.943	72.697	0.809	-0.023	0.708	1.778	1.833	1.521	0.577	0.569	0.124	0.158	2.691		
Netherlands	7.403	0.029	10.942	0.930	71.550	0.887	0.213	0.379	1.778	1.942	1.488	0.545	0.672	0.251	0.394	2.110		
Sweden	        7.395	0.037	10.883	0.939	72.150	0.948	0.165	0.202	1.778	1.921	1.510	0.562	0.754	0.225	0.520	1.903		
Norway	        7.315	0.044	11.088	0.943	71.500	0.947	0.141	0.283	1.778	1.994	1.521	0.544	0.752	0.212	0.463	1.829		
Switzerland	7.240	0.043	11.164	0.920	72.900	0.891	0.027	0.266	1.778	2.022	1.463	0.582	0.678	0.151	0.475	1.870		
Luxembourg	7.228	0.069	11.660	0.879	71.675	0.915	0.024	0.345	1.778	2.200	1.357	0.549	0.710	0.149	0.418	1.845	

## Explicação dos  atributos: 

https://happiness-report.s3.amazonaws.com/2023/WHR+23_Statistical_Appendix.pdf 
(página 1 à 3)

# 2- Definição do problema:
## Pergunta orientada a dados:

Quais são os países (Country name) com as pontuações mais altas e mais baixas na escada de bem-estar subjetivo (Ladder score)?

## Análise exploratória de dados: 

- Análise exploratória de dados: fatos e oportunidades. Utilizando métodos estatísticos simples, como média, mediana, moda, desvio padrão, percentil, o grupo deverá apresentar fatos a respeitos dos dados obtidos.  
	- Espera-se que sejam utilizados/entregues pelos menos quatro medidas/métodos.


# 3- Visualização de dados:  

- Utilizando ferramentas de visualização de dados (ex. Excel, PowerBI, GapMinder, Tableau), os alunos deverão construir e apresentar gráficos, tabelas sumarizadas, infográficos ou outros elementos visuais que descrevam os dados.
	- Espera-se que o grupo apresente pelo menos três gráficos/resultados visuais.

Tentando te ajudar com os atributos pra você pensar quais os melhores gráficos pra gente:
   2023: 
Country name *

Ladder score *
Standard error of ladder score

-> Atributos que influenciam na pontuação da escada:
Logged GDP per capita
Social support 
Healthy life expectancy 
Freedom to make life choices 
Generosity
Perceptions of corruption 

-> Refere-se à contribuição para a pontuação na escada:
Explained by: Log GDP per capita
Explained by: Social support
Explained by: Healthy life expectancy
Explained by: Freedom to make life choices
Explained by: Generosity
Explained by: Perceptions of corruption

-> Distopia = cenário hipotético 
Ladder score in Dystopia
Dystopia + residual
_____________
ATRIBUTOS DELETADOS:
upperwhisker
lowerwhisker 

# 4- Análise crítica e conclusão: 

Os países que estão no topo da escada de felicidade são:
Os países que estão na base da escada de felicidade são:
Explicação: relação da pontuação da Ladder score com os seguintes atributos: Logged GDP per capital, Social support, Healthy life expectancy, Freedom to make life choices, Generosity, Perceptions of corruption 

**Exemplo: 

Verificamos que as classificações e as pontuações dos países se mantêm relativamente inalteradas, com algumas excepções. Por exemplo, a Malásia registou um declínio acentuado na sua pontuação da escada de 2018 
para 2019.  

Outro fator que percebemos é que 8 dos 10 primeiros países mais felizes se situam na Europa e, além disso, 5 deles são da Escandinávia (Finlândia, Dinamarca, Islândia, Suécia e Noruega). Estes fatos são esperados, uma vez que estes países são conhecidos pela sua elevada qualidade de vida.

E para países com um declínio acentuado. Um fato que deveria ser esperado é se o índice de felicidade medido é baixo, geralmente indica baixos níveis de liberdade, direitos humanos e elevados níveis de corrupção governamental. Sem intervenção externa, é natural que estes fatores conduzam a uma espiral de reforço negativo que agrava ainda mais a tristeza no país.  

Elevados níveis de corrupção governamental e sem intervenção externa, é natural que estes fatores conduzam a uma espiral de reforço negativo que agrava ainda mais a tristeza no país.  

Curiosamente, as pontuações do Afeganistão e do Líbano eram relativamente mais altas, mas depois caíram significativamente a partir de 2017. Se consultarmos fontes externas, podemos ver mais ou menos porque é que isto acontece:

Afeganistão: Após a ocupação americana do país, que terminou em 2021, o Tailban assumiu o poder em agosto de 2021. Impuseram numerosas regras e políticas que violavam os direitos humanos, especialmente das mulheres.
Também reprimiram a liberdade de expressão, fecharam à força organizações da sociedade civil e desmantelaram gabinetes governamentais centrados nos direitos humanos. 

Líbano: O Líbano está atualmente a atravessar uma crise financeira que começou por volta de 2019 e foi ainda mais exacerbada pela pandemia de COVID-19, pela explosão do porto de Beirute em 2020 e pela invasão russa da 
Ucrânia. Foi ainda mais devastada pelas sanções dos EUA contra o governo da Síria e o Hezbollah, apoiado pelo Irão. Em particular, a sua moeda foi desvalorizada em 90%, com níveis de inflação de três dígitos. 

___________

Na capa do trabalho deverá haver a indicação do NOME COMPLETO de cada um dos integrantes da equipe. 

a) Um TEXTO descrevendo cada uma das etapas indicadas anteriormente. O texto deve ser entregue em formato científico. No site da Biblioteca da PUC Minas existem orientações para Elaborar, formatar artigo científico

> Breve introdução e contextualização sobre o dataset + (pegar o dicionário de dados e o fragmento) + explicação das variáveis em formato numérico;
> (pegar pergunta orientada a dados) + descrição dos 4 métodos de análise exploratória dos dados (pegar imagens);
> Descrição dos 3 elementos visuais (pegar imagens);
> Análise crítica -> hipóteses + conclusão;
> Vídeo.

b) A base de dados tratada (não precisa ser a original) em formato CSV ou Excel.

c) Um VÍDEO do projeto com a apresentação dos resultados obtidos (dados estatísticas e visuais). É importante que o vídeo inicialize com a citação ou apresentação dos membros da equipe e a contextualização da origem da base de dados. Não é necessário que todos apresentem. Vídeo deve ter no máximo 5 minutos.

