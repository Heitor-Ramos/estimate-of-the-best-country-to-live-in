# 1 - Identificação de uma base de dados de interesse:

Fonte:

https://worldhappiness.report/ed/2023/

https://happiness-report.s3.amazonaws.com/2023/WHR+23_Statistical_Appendix.pdf 

Dataset:

[World Happiness Report 2023.csv](https://github.com/Luannsz/estimate-of-the-best-country-to-live-in/files/15422833/World.Happiness.Report.2023.csv)

## Integrantes do grupos:

HEITOR RAMOS DE OLIVEIRA 

JOÃO HENRIQUE PEREIRINHA SORRENTINO 

LUAN INAIBES GUIMARÃES 

RAFAEL BRANDÃO DE OLIVEIRA 

SERENA FERREIRA MOREIRA 

## Introdução 

Segundo o Dicionário Brasileiro da Língua Portuguesa, felicidade é o “estado de espírito de quem se encontra alegre ou satisfeito”. Não atando-se apenas ao conceito, a existência da felicidade como algo realizável e alcançável tornou-se tema de pesquisa, discussão e análise. Diante disso, foi estabelecido, em 2012, pela Assembleia Geral das Nações Unidas, o Dia Internacional da Felicidade, comemorado anualmente dia 20 de março. Tendo isso em perspectiva, a significância da ideia de felicidade passou a ser algo visto para além de um cenário pessoal, emocional e individual, mas plural, racional, social e político. A felicidade nacional passou a ser um objetivo operacional para os governos. O sucesso ou o fracasso de um país é também presumível pelo estado de espírito prevalente na população. 

## Contextualização 

O Relatório Mundial da Felicidade é uma pesquisa em desenvolvimento desde 2012. Com o intuito de realizar medições estatísticas da felicidade global, seu reconhecimento foi impulsionado conforme governos, organizações e comunidades passaram a interpretar os indicadores de felicidade como algo fundamental para tomada de decisões sociais, econômicas e, sobretudo, políticas. Os relatórios anuais refletem a demanda mundial pela atenção à felicidade e o bem-estar social — componentes primários e essenciais para a formação e implementação de políticas governamentais que direcionam o mundo a uma agenda de desenvolvimento sustentável, com enfoque na melhor qualidade do desenvolvimento humano. 

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

*Foram eliminados os atributos upperwhisker, lowerwhisker e Dystopia + residual.

## Apresentação de uma amostra dos dados:

![image](https://github.com/Luannsz/estimate-of-the-best-country-to-live-in/assets/164661514/21c34e93-3f24-4125-8004-7144c24c4760)

## Explicação dos  atributos: 

### Ladder score: 

Proveniente da pesquisa Gallup World Poll (GWP), realizada dia 20 de janeiro de 2023, a pontuação de felicidade ou bem-estar subjetivo (nome da variável "ladder") é a resposta média nacional à pergunta “Imagine uma escada com degraus numerados de 0 na parte inferior a 10 no topo. O topo da escada representa a melhor vida possível para você e a parte inferior da escada representa a pior vida possível para você. Em qual degrau da escada você diria que se sente neste momento?”. Essa medida é também conhecida como "escada da vida de Cantril".

### Standard error of ladder score: 

O erro padrão da pontuação da escada é uma medida estatística que indica a precisão da estimativa da pontuação média de felicidade de um país.

### Logged GDP per capita: 

As estatísticas do PIB per capita (nome da variável "gdp"), foram extraídas dos Indicadores de Desenvolvimento Mundial (metadados atualizados pela última vez em 22 de janeiro de 2023).
  
### Social support: 

O suporte social (ou ter alguém em quem contar em tempos de dificuldade), é a média nacional das respostas binárias (0 ou 1) para a pergunta da GWP "Se você estivesse em apuros, você teria parentes ou amigos em quem poderia contar para ajudá-lo sempre que precisasse, ou não?"

### Healthy life expectancy: 

A expectativa de vida saudável é calculada com base nos dados extraídos do repositório de dados da Organização Mundial da Saúde (OMS), sobre observatório global de saúde.

### Freedom to make life choices: 

A liberdade para fazer escolhas é a média nacional das respostas à pergunta da GWP "Você está satisfeito ou insatisfeito com sua liberdade de escolher o que fazer com sua vida?"
  
### Generosity: 

Generosidade é a média nacional da resposta à pergunta da GWP "Você doou dinheiro para uma instituição de caridade no último mês?" no PIB per capita.

### Perceptions of corruption: 

Percepção de corrupção é a média nacional das respostas a duas perguntas na GWP: "A corrupção é generalizada no governo ou não?" e "A corrupção é generalizada nas empresas ou não?" A percepção geral é apenas a média das duas respostas binárias (0 ou 1). No caso em que a percepção de corrupção no governo está ausente, foi usada a percepção de corrupção nos negócios como a percepção geral. A percepção de corrupção em nível nacional é apenas a resposta média da percepção geral em nível individual.

### Ladder score in Dystopia: 

A pontuação da escada em distopia é um conceito teórico usado no relatório como um ponto de referência. Dystopia representa o país hipotético com os piores valores possíveis em cada um desses indicadores, criando uma base inferior contra a qual as pontuações reais dos países são comparadas. A ideia é mostrar o quanto cada país está acima de um cenário extremamente desfavorável. 

### Explained by:

Os atributos precedidos por "Explained by" são utilizados em um modelo de regressão, para explicar a variação na pontuação de felicidade entre os países. A pontuação de felicidade é baseada em respostas a perguntas sobre a satisfação com a vida, e os fatores "Explained by" mostram quanto cada um desses aspectos contribui para a pontuação total. Para cada fator é atribuído um valor com base nas respostas de cada país, e esses valores são combinados para calcular a pontuação geral de felicidade. Dessa forma, "Explained by" indica a parcela da felicidade que pode ser atribuída a cada um desses determinantes.

# 2- Definição do problema:
## Pergunta orientada a dados:

Quais são os países (Country name) com as pontuações mais altas e mais baixas na escada de bem-estar subjetivo (Ladder score)?

## Análise exploratória de dados: 

[Código da Análise](https://github.com/Luannsz/estimate-of-the-best-country-to-live-in/blob/main/analysis.ipynb)  

### Ladder Score  

• Média: 5.54  
• Mediana: 5.68  
• Desvio Padrão: 1.14  
• Percentis:  
   25% Percentil: 4.72  
   50% Percentil: 5.68  
   75% Percentil: 6.33  

#### Análise:  
A média de 5.54 e a mediana de 5.68 indicam que os escores de felicidade global estão em um nível moderado, com uma distribuição simétrica. O desvio padrão de 1.14 mostra uma variação considerável, sugerindo que fatores diversos influenciam a felicidade em diferentes 
países. A diferença entre os percentis 25% e 75% (4.72 a 6.33) indica uma ampla distribuição nos níveis de felicidade.  

### Logged GDP per Capita  

• Média: 9.45  
• Mediana: 9.57  
• Desvio Padrão: 1.21  
• Percentis:  
   25% Percentil: 8.59  
   50% Percentil: 9.57  
   75% Percentil: 10.54  

#### Análise:  
A média de 9.45 e a mediana de 9.57 sugerem que a maioria dos países possui um nível moderado de riqueza econômica. O desvio padrão de 1.21 indica disparidades significativas entre os países. A diferença entre os percentis 25% e 75% (8.59 a 10.54) demonstra uma forte 
correlação entre PIB per capita e felicidade, refletindo a desigualdade econômica global.

### Social Support  

• Média: 0.80  
• Mediana: 0.83  
• Desvio Padrão: 0.13  
• Percentis:  
   25% Percentil: 0.72  
   50% Percentil: 0.83  
   75% Percentil: 0.90  

#### Análise:  
Com uma média de 0.80 e uma mediana de 0.83, o suporte social é um fator crucial, indicando que a maioria dos países valoriza as redes de apoio. O desvio padrão de 0.13 mostra que há alguma variação, mas a maioria dos países tem bons níveis de suporte social. A 
variação entre os percentis 25% e 75% (0.72 a 0.90) indica a importância desse fator na percepção de felicidade.

### Healthy Life Expectancy  

• Média: 64.97 anos  
• Mediana: 65.84 anos  
• Desvio Padrão: 5.75 anos  
• Percentis:  
   25% Percentil: 60.65 anos  
   50% Percentil: 65.84 anos  
   75% Percentil: 69.41 anos  

#### Análise:  
A média de 64.97 anos e a mediana de 65.84 anos reforçam a importância da saúde na percepção de felicidade. O desvio padrão de 5.75 anos aponta para diferenças substanciais nos sistemas de saúde globalmente. A variação entre os percentis 25% e 75% (60.65 a 69.41 anos) 
destaca as desigualdades na saúde e longevidade, que afetam o bem-estar.

### Freedom to Make Life Choices  

• Média: 0.79  
• Mediana: 0.80  
• Desvio Padrão: 0.11  
• Percentis:  
   25% Percentil: 0.72  
   50% Percentil: 0.80  
   75% Percentil: 0.87  

#### Análise:  
A média elevada de 0.79 e a mediana de 0.80 refletem a alta valorização da liberdade pessoal. O desvio padrão de 0.11 indica uma variação moderada entre os países. A variação entre os percentis 25% e 75% (0.72 a 0.87) mostra que a liberdade para fazer escolhas de vida 
é um fator importante para a felicidade.

### Generosity  

• Média: 0.02  
• Mediana: 0.00  
• Desvio Padrão: 0.14  
• Percentis:  
   25% Percentil: -0.07  
   50% Percentil: 0.00  
   75% Percentil: 0.12  

#### Análise:  
A generosidade, com uma média baixa de 0.02 e uma mediana de 0.00, sugere que pode não ser um fator primário de felicidade ou é difícil de medir. O desvio padrão de 0.14 mostra uma variação significativa. A variação entre os percentis 25% e 75% (-0.07 a 0.12) indica 
que a generosidade pode ser percebida de maneira muito diferente entre os países.  

### Perceptions of Corruption  

• Média: 0.73  
• Mediana: 0.77  
• Desvio Padrão: 0.18  
• Percentis:  
   25% Percentil: 0.67  
   50% Percentil: 0.77  
   75% Percentil: 0.85  

#### Análise:  
Uma média de 0.73 e uma mediana de 0.77 nas percepções de corrupção indicam que a corrupção é uma preocupação significativa em muitos países. O desvio padrão de 0.18 mostra uma variação considerável. A variação entre os percentis 25% e 75% (0.67 a 0.85) sugere que a 
corrupção é percebida de maneira diversa entre os países, afetando a felicidade global.   

# 3- Visualização de dados:  

[Código dos Gráficos](https://github.com/Luannsz/estimate-of-the-best-country-to-live-in/blob/main/GraphsE.ipynb)  

### Mapa do Índice de Felicidade
![__results___mapa](https://github.com/Luannsz/estimate-of-the-best-country-to-live-in/blob/main/images/mapa%20por%20indice%20de%20felicidade.png)  

O gráfico representado em de globo nos mostra uma clara divisão, onde os países desenvolvidos tendem a ter maiores índices de felicidade, refletindo melhores condições socioeconômicas e alta qualidade de vida. Ao contrário das regiões menos desenvolvidas, com conflitos e pobreza apresentam níveis de felicidade mais baixos do que o normal. 

![__results___1](https://github.com/Luannsz/estimate-of-the-best-country-to-live-in/blob/main/images/top%2010%20maior%20indice.png)  

Esses países têm índices de felicidade muito próximos, todos em torno de 7 a 8 pontos. A presença de países nórdicos como Finlândia, Dinamarca, Islândia, Suécia e Noruega é notável, refletindo a consistência dessas 
nações em proporcionar altos níveis de bem-estar aos seus cidadãos.  

![__results___2](https://github.com/Luannsz/estimate-of-the-best-country-to-live-in/blob/main/images/top%2010%20menor%20indice.png)  

Esses países apresentam índices de felicidade muito baixos, variando de aproximadamente 2 a 4 pontos. Muitos deles estão localizados na África ou em regiões de conflito, refletindo desafios significativos em termos de 
qualidade de vida e bem-estar.  

![__results___3](https://github.com/Luannsz/estimate-of-the-best-country-to-live-in/blob/main/images/top%2010%20maior%20suporte.png)  

Novamente, os países nórdicos aparecem com destaque, reforçando a ideia de que o suporte social é um fator importante na qualidade de vida e, possivelmente, na felicidade geral dos habitantes.  

![__results___4](https://github.com/Luannsz/estimate-of-the-best-country-to-live-in/blob/main/images/top%2010%20menor%20suporte.png)  

Estes países têm suporte social bastante limitado, o que pode contribuir para os baixos níveis de felicidade observados. A falta de suporte social pode significar menos redes de segurança e menos assistência em momentos 
de necessidade, afetando negativamente a qualidade de vida.  

![__results___5](https://github.com/Luannsz/estimate-of-the-best-country-to-live-in/blob/main/images/top%2010%20maior%20expectativa.png) 

Esses países têm expectativas de vida bastante elevadas, todas próximas ou acima dos 80 anos. A presença de nações asiáticas como Hong Kong, Japão, Singapura e Coreia do Sul, junto com países europeus como Suíça, 
Espanha, França e Suécia, é notável. 

![__results___6](https://github.com/Luannsz/estimate-of-the-best-country-to-live-in/blob/main/images/top%2010%20menor%20expectativa.png)  

Esses países têm expectativas de vida significativamente mais baixas, em torno de 50 anos. A maioria está localizada na África, refletindo desafios substanciais em saúde, nutrição, conflitos e infraestrutura.  
  
# 4- Análise crítica e conclusão: 

Os países que estão no topo da escada de felicidade são: Finlândia, Dinamarca, Islândia, Israel e Holanda. 
Os países que estão na base da escada de felicidade são: Afeganistão, Líbano, Serra Leoa, Zimbábue e Congo (Kinshasa).

Pontuação dos respectivos países na Ladder Score:
| País |  Pontuação |
| Finlândia | 7.804 |
| Dinamarca | 7.586 |
| Islândia | 7.530 |
| Israel | 7.473 |
| Holanda | 7.403 |
| ... | ... |
| Congo (Kinshasa) | 3.207 |
| Zimbábue | 3.204 |
| Serra Leoa | 3.138 |
| Líbano | 2.392 |
| Afeganistão | 1.859 |

Explicação: a pontuação dos países na Ladder Score estão diretamente relacionados aos gráficos de suporte social e expectativa de vida, visto que a maioria deles que se encontram em posições altas ou baixas na pontuação de felicidade também estão em posições similares nos outros gráficos, como por exemplo Finlândia, Dinamarca e Islândia ocupando as 3 primeiras posições nas listas tanto de felicidade quanto de suporte social, e Afeganistão e Serra Leoa presentes dentre as 10 piores condições de todas as três.
Análise das pontuações do gráfico do mapa: é visível uma concentração alta da felicidade na região dos países nórdicos, os quais se desenvolveram bem nos últimos séculos e são países bem consolidados, sem conflitos e com renda estável. Por outro lado, há escassez nos países mesopotâmicos e africanos, onde se concentram guerras e pobreza nos dias atuais.


### Conclusão da Análise Exploratória de Dados:
Os dados fornecem uma visão detalhada dos fatores que influenciam a felicidade global. Investir em saúde, reduzir desigualdades econômicas, fortalecer o suporte social, promover a liberdade pessoal e combater a corrupção são estratégias chave para melhorar a felicidade mundial, perceptíveis ao se comparar as situações dos países que estão no topo aos da base. 

### Análise Geral da Visualização de Dados:
Os gráficos mostram uma correlação significativa entre a expectativa de vida, felicidade e suporte social. Os países com maior expectativa de vida, como Suíça, Israel, Suécia e Espanha, também aparecem nos rankings de 
felicidade e suporte social, indicando que uma população mais saudável tende a ser mais feliz e bem amparada socialmente.  

Por outro lado, países com menor expectativa de vida como Afeganistão, Serra Leoa e Zimbábue, também estão entre os que têm os menores índices de felicidade e suporte social. Isso sugere que desafios em saúde e bem-
estar, falta de infraestrutura e conflitos podem reduzir significativamente a qualidade de vida e a felicidade geral da população.

### Conclusão da Análise de Visualização de Dados:
Países que investem em suporte social e bem-estar tendem a ter cidadãos mais longevos e, consequentemente, mais felizes, pois terão certa segurança quanto às doenças que podem vir acompanhadas à idade, e conseguirão aproveitar a terceira idade com atividades do agrado pessoal. Em contraste, regiões que enfrentam desafios socioeconômicos e de saúde significativos precisam de intervenções abrangentes para melhorar a qualidade de vida e 
aumentar a felicidade de seus habitantes.  

**Exemplo: 

Verificamos que as classificações e as pontuações dos países se mantêm relativamente inalteradas, com algumas exceções. Por exemplo, a Malásia registou um declínio acentuado na Ladder Score de 2018 para 2019.  

Outro fator que percebemos é que 8 dos 10 primeiros países mais felizes se situam na Europa e, além disso, 5 deles são da Escandinávia (Finlândia, Dinamarca, Islândia, Suécia e Noruega). Estes fatos são esperados, uma vez que estes países são conhecidos pela sua elevada qualidade de vida.

E para países com um declínio acentuado. Um fato que deveria ser esperado é se o índice de felicidade medido é baixo, geralmente indica baixos níveis de liberdade, direitos humanos e elevados níveis de corrupção governamental. Sem intervenção externa positiva, é natural que estes fatores conduzam a uma espiral de reforço negativo que agrava ainda mais a tristeza no país.   

Curiosamente, as pontuações do Afeganistão e do Líbano eram relativamente mais altas, mas depois caíram significativamente a partir de 2017. Se consultarmos fontes externas, podemos ver mais ou menos porque, no Afeganistão, após a ocupação americana do país, que terminou em 2021, o Tailbã assumiu o poder em agosto de 2021, e impuseram numerosas regras e políticas que violavam os direitos humanos, especialmente das mulheres. Também reprimiram a liberdade de expressão, fecharam à força organizações da sociedade civil e desmantelaram gabinetes governamentais centrados nos direitos humanos. 
Enquanto isso, o Líbano está atualmente a atravessar uma crise financeira que começou por volta de 2019 e foi ainda mais exacerbada pela pandemia de COVID-19, pela explosão do porto de Beirute em 2020 e pela invasão russa à 
Ucrânia. O país foi ainda mais devastado pelas sanções dos EUA contra o governo da Síria e o Hezbollah, apoiado pelo Irã. Em particular, a sua moeda foi desvalorizada em 90%, com níveis de inflação de três dígitos. 

___________

a) Um TEXTO descrevendo cada uma das etapas indicadas anteriormente. O texto deve ser entregue em formato científico. No site da Biblioteca da PUC Minas existem orientações para Elaborar, formatar artigo científico

b) A base de dados tratada (não precisa ser a original) em formato CSV ou Excel.

c) Um VÍDEO do projeto com a apresentação dos resultados obtidos (dados estatísticas e visuais). É importante que o vídeo inicialize com a citação ou apresentação dos membros da equipe e a contextualização da origem da base de dados. Não é necessário que todos apresentem. Vídeo deve ter no máximo 5 minutos.

