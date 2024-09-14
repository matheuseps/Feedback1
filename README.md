# Análise de Sentimentos de Tweets

## Descrição do Projeto

Este projeto realiza a análise de sentimentos de tweets, classificando-os como positivos ou negativos. Utiliza um modelo de machine learning baseado em Naive Bayes Multinomial para a classificação. O pipeline de processamento de texto e o modelo são combinados para prever o sentimento dos tweets, permitindo insights sobre a opinião pública expressa nas redes sociais.

## Funcionalidades

- **Carregamento de Dados**: Carrega um arquivo CSV contendo tweets e suas respectivas classificações de sentimento.
- **Pré-processamento**: Verifica a presença das colunas necessárias e divide os dados em conjuntos de treinamento e teste.
- **Treinamento do Modelo**: Treina um modelo de Naive Bayes Multinomial para classificação de sentimentos.
- **Avaliação do Modelo**: Avalia o modelo usando métricas como acurácia e relatório de classificação.
- **Visualização**:
  - **Matriz de Confusão**: Visualiza o desempenho do modelo na classificação dos sentimentos.
  - **Distribuição de Sentimentos**: Plota a distribuição de sentimentos positivos e negativos no conjunto de dados.

## Instalação

Para instalar e executar o projeto, siga estas etapas:

1. **Clone o Repositório**:
   ```bash
   git clone https://github.com/usuario/repo.git
   cd repo

**Arquitetura**
Modelo Utilizado: Naive Bayes Multinomial.

CountVectorizer: Converte o texto dos tweets em uma matriz de contagem de palavras.
MultinomialNB: Classificador que utiliza o teorema de Bayes com a suposição de independência das características.
Racionalidade da Arquitetura:

O Naive Bayes é eficaz para a classificação de texto devido à sua simplicidade e ao fato de que é bem adequado para problemas com características discretas como contagens de palavras.
O CountVectorizer transforma o texto em uma forma numérica que o modelo pode processar, permitindo a análise eficiente de grandes volumes de dados textuais.
Base de Dados
A base de dados utilizada contém tweets com duas colunas principais:

tweet_text: O texto do tweet.
sentiment: A classificação do sentimento do tweet (0 para negativo e 1 para positivo).
O arquivo CSV deve estar no formato adequado e deve conter essas duas colunas para que o modelo funcione corretamente.

Contribuição

### Explicação das Seções

- **Descrição do Projeto**: Fornece uma visão geral do projeto e seu objetivo.
- **Funcionalidades**: Lista as principais funcionalidades implementadas.
- **Instalação**: Instruções sobre como instalar e configurar o projeto.
- **Uso**: Instruções sobre como executar o script e o que ele faz.
- **Arquitetura**: Detalha a arquitetura do modelo de IA e a razão para a escolha da arquitetura.
- **Base de Dados**: Descreve a estrutura da base de dados utilizada.
- **Contribuição**: Informa como outros podem contribuir para o projeto.
- **Licença**: Detalha a licença do projeto.
- **Contato**: Fornece informações de contato para dúvidas ou mais informações.

Este README fornece uma visão completa e clara do seu projeto, facilitando para outros entendê-lo e usá-lo. Se precisar de mais ajustes ou adicionar informações específicas, sinta-se à vontade para modificar conforme necessário.


