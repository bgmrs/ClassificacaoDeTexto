#  Classificador de Sentimentos de Textos

## Descrição do Projeto
Utilizando uma base de dados extraída do Kaggle, o projeto implementa um pipeline de processamento e classificação de textos. As principais etapas do projeto incluem:

  - **Pré-processamento dos Dados**:
    
    **Limpeza e Padronização**: Aplicação de Regex para remover caracteres indesejados e padronizar o formato dos textos.
    
    **Tratamento de Texto**: Inclui a remoção de stop words, lematização (redução das palavras às suas formas básicas), tokenização (divisão do texto em unidades menores, como palavras), conversão para lowercase (para uniformidade), e remoção de acentuação e caracteres especiais. Essas etapas são essenciais para garantir que o modelo se concentre apenas nas       informações relevantes.
    
  - **Representação dos Textos**:

    **CountVectorizer**: Conversão dos textos em uma matriz de contagem de palavras. O CountVectorizer transforma o texto em uma representação numérica, onde cada palavra é representada por um valor que indica sua frequência no texto.

  - **Reamostragem**:

    **Hold Out**: Separação dos dados em conjuntos de treino e teste. A técnica de hold out é usada para dividir o dataset em um conjunto de treino, utilizado para treinar o modelo, e um conjunto de teste, utilizado para avaliar o desempenho do modelo.
    
  - **Modelo de Classificação**:

    **Regressão Logística**: Implementação de um modelo de regressão logística, adequado para problemas de classificação binária, como a distinção entre sentimentos positivos e negativos. A regressão logística estima a probabilidade de uma amostra pertencer a uma das classes (POSITIVO ou NEGATIVO).
    
  - **Avaliação**: 

    **F1 Score**: Utilização do F1 Score como métrica principal para avaliar o desempenho do modelo. O F1 Score é uma medida que combina a precisão e a revocação, proporcionando uma única métrica que considera tanto os falsos positivos quanto os falsos negativos, sendo particularmente útil para problemas de classificação desbalanceada.

## Como Executar

1. Clone o repositório:

  ```git clone https://github.com/bgmrs/ClassificacaoDeTexto```

2. Instale as dependências:

  ```pip install -r requirements.txt```

3. Navegue até o Diretório do Projeto:

```cd ClassificacaoDeTexto```

4. Execute o Notebook:

```jupyter notebook classificacaodetexto.ipynb```

### Detalhes Adicionais

**Notas Pessoais**: O notebook contém células de Markdown com anotações e explicações detalhadas sobre cada etapa do processo. Comentários adicionais podem ser encontrados nas células de código para detalhes sobre abordagens específicas e decisões tomadas durante o desenvolvimento.

## Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e enviar pull requests.

## Licença
Este projeto é licenciado sob a [Apache License 2.0](LICENSE)  - veja o arquivo [LICENSE](LICENSE) para detalhes.

