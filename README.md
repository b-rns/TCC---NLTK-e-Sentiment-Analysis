# TCC_NLTK_and_sentiment_analysis
**A percepção dos usuários de redes sociais sobre a tecnologia de NFT e suas aplicações analisadas sob a ótica da análise de sentimentos com processamento de linguagem natural**


O presente estudo teve como objetivo captar a percepção dos usuários de redes sociais sobre a tecnologia de NFT, produto da empresa OpenSea, objeto de estudo deste trabalho. As analises foram efetuadas sob a óptica da ciência de dados, mais especificamente com a análise de sentimento com machine learning em postagens da rede social Twiter. Para atingir este fim, optou-se pela utilização de ferramentas de Data Science em scripts desenvolvidos em Python para coletar 60 mil de postagens do Twiter via API, estrutura-los, transformá-los com técnicas de processamento de linguagem natural e aplicar a função de análise de sentimentos do  modelo VADER (Valence Aware Dictionary and sEntiment Reasoner) para classificar os tweets como positivos, negativos ou neutros, e analisá-los em busca de informações relevantes acerca da percepção dos usuários sobre o tema. As conclusões sobre as analises nos permitiram inferir que, no período analisado, 59% do fluxo de mensagens se refere a textos publicitários e anúncios de obras digitais publicados pelos seus criadores e 41% refletem opiniões de usuários sobre o tema. O conteúdo do texto dos tweets destes 41% é em sua maioria, 52%, positivo, 40% é neutro e 7% negativo, tais resultados nos permitiram separar os dados de acordo com o sentimento, avaliar as palavras mais frequentes e compreender melhor a percepção dos usuários sobre o tema.  

**Este repositório guarda os scripts desenvolvidos para as três etapas este estudo, coleta, transformação e modelagem dos dados.**

1 - coleta -> script desenvolvido em Python para a coleta e armazenamento de dados da API do Twiter

2 - limpeza_processamento -> script desenvolvido para a limpeza, tokenização, lemantização e separação dos spams com um modelo supervisionado Naive Bayes, este script separou os spams das opiniões para tornar o dataset mais adequado para as etapas seguintes

3 - aplicacao_vader  -> Neste notebook está a aplicação do SentimentItensifierAnaliser() para a analise de sentimentos e classificação dos tweets como positivos, negativos ou neutros, há também a exproração visual em gráficos e Word Clouds.

O estudo completo com os resultados e análises pode ser econtrado no link abaixo:

