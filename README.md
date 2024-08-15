#  Classificador de Sentimentos de Textos

## Descrição do Projeto
Utilizando uma base de dados extraída do Kaggle, o projeto implementa um pipeline de processamento e classificação de textos. As principais etapas do projeto incluem:

  - **Pré-processamento dos Dados**: Aplicação de Regex para limpeza e padronização dos textos.
  - **Representação dos Textos**: Uso do CountVectorizer para converter o texto em uma matriz de contagem de palavras.
  - **Reamostragem**: Implementação da técnica de hold out para separar os dados em conjuntos de treino e teste.
  - **Modelo de Classificação**:  Implementação de Regressão Logística para classificar os sentimentos como POSITIVO ou NEGATIVO.
  - **Avaliação**: Utilização do F1 Score como métrica principal para medir o desempenho do modelo.

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
Este projeto é licenciado sob a MIT License - veja o arquivo LICENSE para detalhes.

