# Análise  exploratória de dados usando dados de vídeo do YouTube


## Referencias 

Esse plojeto foi inspirado em um video tutoria feito pelo canal da [Thu Vu data analytics (Em inglês)](https://www.youtube.com/channel/UCJQJAI7IjbLcpsjWdSzYz0Q), onde ela abordas varios conceitos de data science, tutoriras e dicas sobre a area.

[Create a Unique Data Portfolio Project with Youtube API for Python](https://www.youtube.com/watch?v=D56_Cx36oGY&t=837s)

## Introdução

Dentro deste projeto, irei explorar o seguinte:

* Conhecendo a API do Youtube e como obter dados de vídeo.
* Analisar dados de vídeo e verificar diferentes informações comuns sobre o que faz um vídeo ter um bom desempenho no Youtube.

    Por exemplo:
     * O número de curtidas e comentários é importante para um vídeo obter mais visualizações?
     * A duração do vídeo é importante para visualizações e interação (curtidas/comentários)?
     * Com que frequência eles enviam novos vídeos? Em quais dias da semana?
     * Explorar os tópicos de tendências usando técnicas de PNL
     * Quais comentarios estão sendo feitos nas seções de comentários dos vídeos
     
## Etapas do projeto

1. Obter os dados de vídeo por meio da API do Youtube.
    - Isso inclui várias pequenas etapas: criar uma chave de desenvolvedor, solicitar dados e transformar as respostas em um dataframe.
2. Tratamentos dados.
3. Análise exploratória de dados


## Conjunto de dados

 O datasete foi criado usando [Google Youtube Data API version 3.0](https://developers.google.com/youtube/v3). 
 
E está particularmente focado em analisar os dados do canal **Você Sabia?**
   - O Canal Voce Sabia reune as melhores curiosidades, historias e fatos interessantes do mundo. 
   Apresentando por Lukas Marques e Daniel Molo.


## Ética da fonte de dados
De acordo com o guia da API do Youtube, o uso da API do Youtube é gratuito, desde que seu aplicativo envie solicitações dentro de um limite de cota. "A API de dados do YouTube usa uma cota para garantir que os desenvolvedores usem o serviço conforme pretendido e não criem aplicativos que reduzam injustamente a qualidade do serviço ou limitem o acesso de outros." A alocação de cota padrão para cada aplicativo é de 10.000 unidades por dia, e você pode solicite cota adicional preenchendo um formulário para os serviços de API do YouTube se você atingir o limite de cota.

Como todos os dados solicitados da API do YouTube são dados públicos (que todos na Internet podem ver no Youtube), não há problemas específicos de privacidade no que me diz respeito. Além disso, os dados são obtidos apenas para fins de pesquisa neste caso e não para quaisquer interesses comerciais.
