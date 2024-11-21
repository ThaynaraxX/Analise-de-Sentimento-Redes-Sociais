# Meu Projeto de Análise de Sentimentos no Instagram: Versão Simplificada

Criei um projeto que analisa como as pessoas estão se sentindo nos comentários de posts do Instagram. Usei a API do Instagram e um modelo de inteligência artificial super legal chamado BERT para descobrir se os comentários são positivos, negativos ou neutros.

Como meu projeto funciona:

1. Coleto os comentários: Meu programa se conecta ao Instagram e pega todos os comentários de um post que eu escolher.
2. Limpo os comentários:  Dou uma organizada nos comentários, tirando emojis, links e palavras comuns que não ajudam na análise.
3. Analiso os sentimentos: Uso o modelo BERT para entender como as pessoas estão se sentindo em cada comentário.
4. Mostro os resultados: rio um arquivo com os resultados, mostrando o sentimento de cada comentário e a "certeza" do modelo sobre essa classificação.

Para usar meu projeto:

1. Instalar as ferramentas: pip install requests pandas torch transformers nltk
2. Obter permissão do Instagram:**  Preciso criar um app no Facebook Developer Portal para  acessar a API do Instagram.
3. Colocar meu código de acesso no programa: Substituo o texto "SEU_ACCESS_TOKEN" pelo código que recebi no passo anterior.
4. Encontrar o ID do post: Pego o número de identificação do post que quero analisar.
5. Rodar o programa: É só executar o script Python.
6. Ver os resultados: Abro o arquivo "sentiment_analysis_results.csv" para ver a análise de cada comentário.

Ferramentas que usei:

requests: Para me conectar na API do Instagram.
pandas: Para organizar os dados.
torch: Para usar o modelo BERT.
transformers: Para facilitar o uso do BERT.
nltk: Para limpar os comentários.

Importante:
Devo usar meu próprio código de acesso do Instagram.
Contas comerciais do Instagram funcionam melhor com meu programa.

