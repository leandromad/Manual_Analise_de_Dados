# Manual_Analise_de_Dados

## REFERÊNCIA ABNT 

FÁVERO, Luiz Paulo Lopes e BELFIORE, Patrícia Prado. Manual de análise de dados: estatística e modelagem multivariada com excel, SPSS e stata. . Rio de Janeiro: Elsevier. . Acesso em: 07 jul. 2022.

## 

## Capitulo 1

### Variáveis Não Métricas ou Qualitativas
  Podem ser visualizadas através de distribuição de frequência ou de forma gráfica, sem o cálculo de medidas de posição, disperção e de formato. A única exceção é em relação à mode, medida que fornece o valor mais frequente de uma variável

  - Para que haja condições de se calcular medidas-resumo como média e desvio-padrão, a variável em estudo deve ser, necessariamente, quantitativa.

  Frequentemente ocorre a classificação incorreta quando a variável apresenta valores numéricos nos dados. Como no exemplo a seguir (Tabela 1.1) que levante dados da renda familiar de uma amostra de consumidores, com base em determinadas faixas salariais.


  <div align="center">
    <img src="https://user-images.githubusercontent.com/82683162/216629429-cd8c9ad2-4f52-43f5-9ab3-4e332186395a.png" />
    <p>Tabela 1.1 Faixas de renda familiar x classe social</p>
  </div>

  Observe que ambas as variáveis são qualitativas, já que os dados são representados por faixas. Nesse caso, é possível apenas o cálculo de frequências, e não de medidas-resumo, como média e desvio-padrão. Outro comum encontrado em trabalhos que utilizam variáveis qualitativas representadas por números é o cálculo da média da amostra, ou de qualquer outra medida-resumo. O pesquisador calcula, inicialmente, a média dos limites de cada faixa, supondo que esse valor corresponde à média real dos consumidores situados naquela faixa; mas como a distribuição dos dados não é necessariamente linear ou simétrica em torno da média, essa hipótese é muitas vezes violada.
  
### Variáveis Métricas ou Quantitativs
Podem ser representadas de forma gráfica (gráfico de linhas, dispersão, histograma, ramo-e-folhas e boxplot) por meio de medidas de posições ou localizações (média, mediana, moda, quartis, decis e percentis) medidas de dispersão ou variabilidade (amplitude, desvio-padrão, desvio-médio, variância, erro-padrão e coeficiente de variância) ou ainda por meio de medidas de forma como assimetria e curtose.
 
- Pode-se classificar as variáveis através de escalas de mensuração. As **Variáveis Qualitativas** e as **Variáveis Quantitativas** são classificadas conforme a Figura 1.1.

<div align="center">
    <img src="https://user-images.githubusercontent.com/82683162/216635243-a854dee6-7ea6-483b-b571-021776aa5c2f.png" />
    <p>Figura 1.1 Tipos de variáveis x escalas de mensuração</p>
  </div>

### Variáveis não Métricas - escala nominal
  A escala nominal classifica as unidades em classes ou categorias em relação à caraterística representada, não 
estabelecendo qualquer relação de grandeza ou de ordem. É denominada nominal porque as categorias se diferenciam apenas pelo nome.
  Podem ser atribuídos rótulos numéricos às categorias das variáveis, porém, operações aritméticas como adição, subtração, multiplicação e divisão sobre esses números não são admissíveis. A escala nominal permite apenas algumas operações aritméticas mais elementares. Por exemplo, pode-se contar o número de elementos de cada classe ou ainda aplicar testes de hipóteses referentes à distribuição das unidades da população nas classes. Desta forma, a maioria das estatísticas usuais, como média e desvio-padrão, não tem sentido para variáveis qualitativas de escala nominal. 
  Como exemplos de variáveis não métricas em escalas nominais, podemos mencionar profissão, religião, cor, estado civil, localização geográfica ou país de origem. 
  Imagine uma variável não métrica relativa ao país de origem de um grupo de 10 grandes empresas multinacionais. Para representar as categorias da variável País de origem, podemos utilizar números, atribuindo o valor 1 para Estados Unidos, 2 para Holanda, 3 para China, 4 para Reino Unido e 5 para Brasil, como mostra a Tabela 
1.2. Nesse caso, os números servem apenas como rótulos ou etiquetas para identificar e classificar os objetos. 

<div align="center">
    <img src="https://user-images.githubusercontent.com/82683162/216639009-cc6f43fd-126f-4f43-ab89-a93870c2e24c.png" />
    <p>Tabela 1.2 Empresas e país de origem</p>
</div>

### Variáveis não Métricas - escala ordinal
  Uma variável não métrica em escala ordinal classifica as unidades em classes ou categorias em relação à característica representada, estabelecendo uma relação de ordem entre as unidades das diferentes categorias. A escala ordinal é uma escala de ordenação, designando uma posição relativa das classes segundo uma direção. Qualquer conjunto de valores pode ser atribuído às categorias das variáveis, desde que a ordem entre elas seja respeitada. 
  Assim como na escala nominal, operações aritméticas (somas, diferenças, multiplicações e divisões) entre esses 
valores não fazem sentido. Desse modo, a aplicação das estatísticas descritivas usuais também é limitada para variáveis de natureza nominal. Como o número das escalas tem apenas um significado de classificação, as estatísticas descritivas que podem ser utilizadas para dados ordinais são as tabelas de distribuições de frequência, gráficos (incluindo o de barras e setores) e o cálculo da moda.
  Exemplos de variáveis ordinais incluem opinião e escalas de preferência de consumidores, grau de escolaridade, classe social, faixa etária, etc. 
  Imagine uma variável não métrica denominada Classificação que mede a preferência de um grupo de consumidores em relação a uma marca de vinho. A criação dos rótulos para cada categoria da variável ordinal está especificada na Tabela 1.3. O valor 1 é atribuído à pior classificação, o valor 2 para a segunda pior e assim sucessivamente, até o valor 5 para a melhor classificação, como mostra esta tabela. 
  
<div align="center">
    <img src="https://user-images.githubusercontent.com/82683162/216653139-0616177c-721f-4341-be82-5a3fd93abe72.png" />
    <p>Tabela 1.3 Classificação dos consumidores em relação a uma marca de vinho.</p>
</div>

### Variável quantitativa - escala intervalar
  A escala intervalar, além de ordenar as unidades quanto à característica mensurada, possui uma unidade de 
medida constante. A origem ou o ponto zero dessa escala de medida é arbitrário e não expressa ausência de quantidade. 
  Um exemplo clássico de escala intervalar é a temperatura medida em graus Celsius (ºC) ou Fahrenheit (ºF). A escolha do zero é arbitrária e diferenças de temperaturas iguais são determinadas por meio da identificação de volumes iguais de expansão no líquido usado no termômetro. Dessa forma, a escala intervalar permite inferir diferenças entre unidades a serem medidas, porém, não se pode afirmar que um valor em um intervalo específico da escala seja múltiplo de outro. Por exemplo, suponha dois objetos medidos a uma temperatura de 15ºC e 30ºC, respectivamente. A mensuração da temperatura permite determinar o quanto um objeto é mais quente que o 
outro, porém, não se pode afirmar que o objeto com 30ºC está duas vezes mais quente que o outro com 15ºC.  
  A maioria das estatísticas descritivas pode ser aplicada para dados de variável com escala intervalar, com exceção de estatísticas baseadas na escala de razão, como o coeficiente de variação. 


  
