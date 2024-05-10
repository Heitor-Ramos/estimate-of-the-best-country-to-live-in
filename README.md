1 - Identificação de uma base de dados de interesse:

> A base de dados necessariamente deverá possuir também dados relativos ao ano de 2022.

Fonte:

https://worldhappiness.report/  
https://worldhappiness.report/data/

Datasets:

[WorldHappinessReportDatasets.zip](https://github.com/Luannsz/estimate-of-the-best-country-to-live-in/files/15269340/WorldHappinessReportDatasets.zip)

> Dicionário de dados: deve apresentar o nome do campo/atributo, o tipo do dado e uma breve descrição.

Dicionário de dados original: 

2021:
| Variáveis | Tipo de Dado | Descrição |
| ----------| ------------ | ----------|
Country name | textual | O nome do país. |
Regional indicator | textual | Indicador regional: O agrupamento ou indicador regional ao qual o país pertence. |
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

2022:
| Variáveis | Tipo de Dado | Descrição |
| ----------| ------------ | ----------|
RANK | numérico ordinal | Rank (Classificação): A posição de um país em relação aos outros países, ordenada pela pontuação de felicidade.
Country | textual | O nome do país. |
Happiness score| numérico | Pontuação de felicidade: Representa a pontuação geral de felicidade atribuída a um país.
Whisker-high  | numérico | Limite superior da caixa (whisker): A extremidade superior do intervalo de confiança para a pontuação na escada. |
Whisker-low | numérico | Limite inferior da caixa (whisker): A extremidade inferior do intervalo de confiança para a pontuação na escada. |
Dystopia (1.83) + residual| numérico | Dystopia (1.83) + residual: Refere-se a uma pontuação composta, que inclui um valor fixo para Dystopia (1.83) e qualquer variação residual que não pode ser explicada pelos fatores medidos.
Explained by: Log GDP per capita | numérico | (Explicado por: Log PIB per capita): Refere-se à contribuição da renda per capita (PIB) para a pontuação na escada. |
Explained by: Social support | numérico | (Explicado por: Apoio social): Indica a contribuição do apoio social para a pontuação na escada. |
Explained by: Healthy life expectancy | numérico | (Explicado por: Expectativa de vida saudável): Refere-se à contribuição da expectativa de vida saudável para a pontuação na escada. |
Explained by: Freedom to make life choices | numérico | (Explicado por: Liberdade para fazer escolhas de vida): Indica a contribuição da liberdade individual para tomar decisões de vida para a pontuação na escada. | 
Explained by: Generosity | numérico | (Explicado por: Generosidade): Refere-se à contribuição da generosidade para a pontuação na escada. |
Explained by: Perceptions of corruption | numérico | (Explicado por: Percepções de corrupção): Indica a contribuição das percepções de corrupção para a pontuação na escada. |

2023: 
| Variáveis | Tipo de Dado | Descrição |
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

Dicionário de dados modificado:

2021, 2022, 2023:
| Variáveis | Tipo de Dado | Descrição |
| ----------| ------------ | ----------|
Country | textual | O nome do país. |
Whisker-high  | numérico | Limite superior da caixa (whisker): A extremidade superior do intervalo de confiança para a pontuação na escada. |
Whisker-low | numérico | Limite inferior da caixa (whisker): A extremidade inferior do intervalo de confiança para a pontuação na escada. |
Explained by: Log GDP per capita | numérico | (Explicado por: Log PIB per capita): Refere-se à contribuição da renda per capita (PIB) para a pontuação na escada. |
Explained by: Social support | numérico | (Explicado por: Apoio social): Indica a contribuição do apoio social para a pontuação na escada. |
Explained by: Healthy life expectancy | numérico | (Explicado por: Expectativa de vida saudável): Refere-se à contribuição da expectativa de vida saudável para a pontuação na escada. |
Explained by: Freedom to make life choices | numérico | (Explicado por: Liberdade para fazer escolhas de vida): Indica a contribuição da liberdade individual para tomar decisões de vida para a pontuação na escada. | 
Explained by: Generosity | numérico | (Explicado por: Generosidade): Refere-se à contribuição da generosidade para a pontuação na escada. |
Explained by: Perceptions of corruption | numérico | (Explicado por: Percepções de corrupção): Indica a contribuição das percepções de corrupção para a pontuação na escada. |


> Complemente com uma a apresentação de um fragmento/amostra de dos dados (algumas poucas linhas).

> Caso tenha feito limpeza e redução da base de dados, descreve como isso foi feito. Indique o que significa cada linha e cada coluna selecionadas para o trabalho.


	2- Definição do problema:

> Pergunta orientada a dados.

Dados fatores como o PIB per capita, o suporte social, a expectativa de vida saudável, a liberdade para fazer escolhas de vida, a generosidade e as percepções de corrupção de diversos países, nos anos de 2021, 2022 e 2023, qual o país mais oportuno de se habitar em 2024.

(Whisker-high, Whisker-low ... pensando se inclui +isso)

> Deixe claro no seu objetivo qual dado você pretende utilizar para responder a pergunta.

Country name / Nome do país: 

(Acho que isso não tá certo não)

# Análise exploratória de dados: 

## Visualização de dados:  

### Pontuação dos países mais felizes  
![Resultado 1](https://github.com/Luannsz/estimate-of-the-best-country-to-live-in/blob/main/images/resultado%201.png)  

De igual modo, podemos investigar as classificações dos países ao longo do tempo:

### Classificação dos países mais felizes  
![Resultado 2](https://github.com/Luannsz/estimate-of-the-best-country-to-live-in/blob/main/images/resultado%202.png)  

### Pontuação dos países mais tristes   

![Resultado 3](https://github.com/Luannsz/estimate-of-the-best-country-to-live-in/blob/main/images/resultado%203.png)  

Do mesmo modo, podemos investigar as pontuações e as classificações dos países mais tristes, que poderíamos definir como tendo as pontuações mais baixas da escada da felicidade em 2023.  

Verificamos que 8 em cada 10 destes países são de África, que historicamente tem sido devastada pela guerra, pelo colonialismo e pela desigualdade e corrupção. Os dois últimos países (Afeganistão e Líbano) foram 
devastados por numerosas guerras (guerra do Afeganistão, guerra do Líbano em 2006). 

### Classificação dos países mais tristes  
![Resultado 4](https://github.com/Luannsz/estimate-of-the-best-country-to-live-in/blob/main/images/resultado%204.png)  


## Análise crítica e conclusão: 

Verificamos que as classificações e as pontuações dos países se mantêm relativamente inalteradas, com algumas excepções. Por exemplo, a Malásia registou um declínio acentuado na sua pontuação da escada de 2018 
para 2019.  

Outro fator que percebemos é que 8 dos 10 primeiros países mais felizes se situam na Europa e, além disso, 5 deles são da Escandinávia (Finlândia, Dinamarca, Islândia, Suécia e Noruega). Estes fatos são esperados, uma 
vez que estes países são conhecidos pela sua elevada qualidade de vida.

E para países com um declínio acentuado. Um fato que deveria ser esperado é se o índice de felicidade medido é baixo, geralmente indica baixos níveis de liberdade, direitos humanos e elevados níveis de corrupção 
governamental. Sem intervenção externa, é natural que estes fatores conduzam a uma espiral de reforço negativo que agrava ainda mais a tristeza no país.  

Elevados níveis de corrupção governamental e sem intervenção externa, é natural que estes fatores conduzam a uma espiral de reforço negativo que agrava ainda mais a tristeza no país.  

Curiosamente, as pontuações do Afeganistão e do Líbano eram relativamente mais altas, mas depois caíram significativamente a partir de 2017. Se consultarmos fontes externas, podemos ver mais ou menos porque é que isto 
acontece:

Afeganistão: Após a ocupação americana do país, que terminou em 2021, o Tailban assumiu o poder em agosto de 2021. Impuseram numerosas regras e políticas que violavam os direitos humanos, especialmente das mulheres.
Também reprimiram a liberdade de expressão, fecharam à força organizações da sociedade civil e desmantelaram gabinetes governamentais centrados nos direitos humanos. 

Líbano: O Líbano está atualmente a atravessar uma crise financeira que começou por volta de 2019 e foi ainda mais exacerbada pela pandemia de COVID-19, pela explosão do porto de Beirute em 2020 e pela invasão russa da 
Ucrânia. Foi ainda mais devastada pelas sanções dos EUA contra o governo da Síria e o Hezbollah, apoiado pelo Irão. Em particular, a sua moeda foi desvalorizada em 90%, com níveis de inflação de três dígitos. 

___________

Na capa do trabalho deverá haver a indicação do NOME COMPLETO de cada um dos integrantes da equipe. 

a) Um TEXTO descrevendo cada uma das etapas indicadas anteriormente. O texto deve ser entregue em formato científico. No site da Biblioteca da PUC Minas existem orientações para Elaborar, formatar artigo científico

> Introdução + contextualização, pergunta orientada a dados, objetivo + justificativa, preparação dos dados + transformação dos dados...

b) A base de dados tratada (não precisa ser a original) em formato CSV ou Excel.

c) Um VÍDEO do projeto com a apresentação dos resultados obtidos (dados estatísticas e visuais). É importante que o vídeo inicialize com a citação ou apresentação dos membros da equipe e a contextualização da origem da base de dados. Não é necessário que todos apresentem. Vídeo deve ter no máximo 5 minutos.




2021:
Country name
Regional indicator
Ladder score
Standard error of ladder score
upperwhisker
lowerwhisker
Logged GDP per capita
Social support
Healthy life expectancy
Freedom to make life choices
Generosity
Perceptions of corruption
Ladder score in Dystopia
Explained by: Log GDP per capita
Explained by: Social support
Explained by: Healthy life expectancy
Explained by: Freedom to make life choices
Explained by: Generosity
Explained by: Perceptions of corruption
Dystopia + residual

2022:
RANK
Country
Happiness score
Whisker-high,Whisker-low
Dystopia (1.83) + residual
Explained by: GDP per capita
Explained by: Social support
Explained by: Healthy life expectancy
Explained by: Freedom to make life choices
Explained by: Generosity
Explained by: Perceptions of corruption

2023: 
Country name
Ladder score
Standard error of ladder score
upperwhisker
lowerwhisker
Logged GDP per capita
Social support
Healthy life expectancy
Freedom to make life choices
Generosity
Perceptions of corruption
Ladder score in Dystopia
Explained by: Log GDP per capita
Explained by: Social support
Explained by: Healthy life expectancy
Explained by: Freedom to make life choices
Explained by: Generosity
Explained by: Perceptions of corruption
Dystopia + residual






