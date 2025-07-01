# **Instruções para o Projeto Final Individual \- 7 de julho de 2025**

Curso: Tomada de Decisão com Visualização de Dados

Tiago Afonso

## 1\. Objetivo do Projeto

O objetivo deste projeto final individual é a aplicação prática das competências do curso. Cada aluno irá formular uma pergunta analítica, preparar os dados necessários e, por fim, desenhar uma visualização de dados (entre 1 a 3 gráficos) que comunique uma resposta clara e impactante.

Este trabalho é uma avaliação da capacidade de transformar dados brutos em conhecimento visual. O sucesso não reside na complexidade da análise, mas na clareza, elegância e poder de persuasão da visualização.

## 2\. Fases do Projeto Individual

**Fase 1**: A Pergunta de Partida

Tudo começa com uma excelente pergunta. O primeiro passo é definir uma questão específica e que possa ser respondida através de dados. Uma pergunta bem formulada é 50% do projeto.

*Exemplos de Perguntas Orientadas a Dados:*

\-Economia/Finanças: Como evoluiu a taxa de inflação em Portugal comparativamente à média da Zona Euro desde o início de 2022? Existe uma correlação visível entre a subida das taxas de juro do BCE e o abrandamento?

\-Gestão/Negócios: Qual dos nossos cinco produtos gera maior receita por cada euro investido em marketing? A sazonalidade afeta todos os produtos da mesma forma?

\-Social/Demografia: Qual a relação entre o nível de escolaridade e a taxa de desemprego jovem nos distritos do interior de Portugal na última década?

\-Energia (Exemplo): De que forma a produção de energia solar em Portugal tem compensado a redução da produção hídrica em anos de seca (e.g., comparar 2017 com 2023)?

\-Desporto: Qual o perfil de desempenho de um atleta ao longo de uma época? A performance (e.g., golos, pontos, tempos) é consistente em casa e fora?

Como gerar perguntas com um Chat de LLM (Copilot, ChatGPT, Gemini, etc.)

Pode usar um LLM como um parceiro de brainstorming. O segredo é dar-lhe um contexto claro. Experimente prompts como estes:

*\-"Atua como um analista de dados. Estou a fazer um projeto sobre \[inserir tema, ex: 'o mercado imobiliário em Lisboa'\]. Sugere-me 5 perguntas específicas que possam ser respondidas com dados quantitativos. As perguntas devem envolver uma comparação ao longo do tempo ou entre diferentes categorias."*

*\-"Tenho acesso a um dataset sobre \[descrever o dataset, ex: 'as emissões de CO2 por país desde 1990'\]. Formula 3 perguntas de investigação que uma visualização de dados (como um gráfico de linhas ou de barras) possa responder de forma eficaz. Uma das perguntas deve focar-se numa anomalia ou numa mudança drástica nos dados."*

*\-"Quero explorar a relação entre \[variável A, ex: 'o PIB per capita'\] e \[variável B, ex: 'a esperança média de vida'\]. Dá-me um exemplo de uma pergunta clara para um projeto de visualização de dados e sugere que tipo de gráfico (ex: scatter plot) seria mais adequado para a explorar."*

\-Em alternativa podem fazer upload do cabeçalho dos dados (nome das colunas) e escrever “*Considerando a imagem, escreve perguntas orientadas a dados*”.

**Fase 2**: Recolha e Limpeza dos Dados

Com a pergunta definida, encontre dados de fontes credíveis (INE, Pordata, Eurostat, Banco de Portugal, Kaggle, etc.). Use o Power Query para limpar e preparar os dados. Lembre-se que esta fase, embora invisível no resultado final, é a fundação de um bom projeto.

Sites:

[Find Open Datasets and Machine Learning Projects | Kaggle](https://www.kaggle.com/datasets)

[UCI Machine Learning Repository](https://archive.ics.uci.edu/)

[Dataset Search](https://datasetsearch.research.google.com/)

[https://www.pordata.pt/pt/estatisticas](https://www.pordata.pt/pt/estatisticas)

Se não conseguirem encontrar os dados, enviem mensagem no Teams até dia **1 de julho** para solicitar os dados.

**Fase 3**: A Arte da Visualização (Excel ou Power BI) 

Aqui é onde a análise ganha vida. O objetivo é criar 1 a 3 gráficos que contem uma história clara. A ferramenta é um meio; os princípios de design são o mais importante.

Mais Dicas para uma Visualização de Excelência:

*\-O Princípio da Simplicidade:* Muitas vezes, o gráfico mais simples é o mais poderoso. A primeira ação ao criar um gráfico deve ser remover o que não é essencial. Pergunte a si mesmo: as grelhas são necessárias? E os limites? E aquela sombra? Se a resposta for "não", remova.

\-Escolha o Gráfico Correto para a História:

* *Gráfico de Linhas*: Ideal para mostrar tendências e evoluções ao longo do tempo.  
  * *Gráfico de Barras/Colunas*: Perfeito para comparar categorias (e.g., vendas por produto, população por país). Ordene sempre as barras de forma lógica (crescente, decrescente, etc.), a não ser que a ordem seja intrínseca (e.g., meses).  
  * *Gráfico de Dispersão* (Scatter Plot): Essencial para mostrar a relação e correlação entre duas variáveis numéricas.

[https://www.data-to-viz.com/](https://www.data-to-viz.com/)

\-Utilize a Cor com Intenção, não como Decoração: A cor deve servir um propósito. Use-a para destacar o dado mais importante (e.g., o país, a empresa), para agrupar categorias ou para assinalar valores positivos/negativos. Use tons neutros (como o cinzento) para o contexto e uma cor forte e saturada para a mensagem principal.

\-Crie uma Hierarquia Visual Clara: O elemento mais importante deve ser visualmente dominante. O título do gráfico deve ser a principal conclusão, não uma descrição aborrecida.

* Título Fraco: "Vendas Trimestrais"  
  * Título Forte: "Vendas recuperam 45% no 3º Trimestre após quebra histórica"

\-Rótulos Diretos: Se possível, coloque os rótulos dos dados diretamente nas linhas ou barras em vez de depender de um eixo ou de uma legenda separada. Facilita a leitura e reduz a carga cognitiva do público.

Exemplos:

[https://www.visualcapitalist.com/](https://www.visualcapitalist.com/)

[https://informationisbeautiful.net/](https://informationisbeautiful.net/)

[https://www.datawrapper.de/charts](https://www.datawrapper.de/charts)

## 3\. A Apresentação (até 2 Minutos)

A apresentação deve ser concisa, direta e memorável.

1. A Pergunta (+/-30s): Apresente a questão de partida.  
2. A Revelação Visual (+/-60s): Mostre o gráfico. Não o descreva, interprete. Guie diretamente para o *insight*. "Como podem ver aqui nesta linha ascendente..."  
3. A Resposta (+/-30s): Conclua com a resposta direta à pergunta.

Como contar uma história com dados: [https://www.youtube.com/watch?v=HnlWiVs9P5o](https://www.youtube.com/watch?v=HnlWiVs9P5o)

## 4\. Critérios de Avaliação

1. Qualidade da Pergunta Analítica: Clareza, especificidade e pertinência.  
2. Eficácia da Visualização (Critério Principal): Escolha do gráfico, clareza, impacto visual, uso eficaz de cor e texto, e ausência de ruído.  
3. Clareza do Insight: A validade e profundidade da conclusão retirada da visualização.  
4. Apresentação e Comunicação: Capacidade de síntese e clareza na apresentação oral.

