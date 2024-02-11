# Aplicação de modelos ARIMA para a previsão de casos de dengue na cidade de Sorocaba

## Sobre o projeto

O objetivo deste projeto foi verificar a aplicabilidade de modelos de séries temporais para a caracterização da dinâmica temporal da dengue na cidade de Sorocaba utilizando a metodologia de Box e Jenkins. A partir dos dados obtidos pela API Infodengue, foi explorado o comportamento dos dados ao longo do tempo, verificada a existência de correlação temporal e construídos modelos com diferentes parâmetros. Por fim, dois modelos selecionados foram avaliados simulando o seu comportamento ao longo do tempo, atualizando de forma iterativa os dados utilizados por eles.

## Como utilizar esse projeto
Para utilizar o código desde projeto, siga os passos a seguir:
1. Clone o repositório:
```
git clone https://github.com/amandashichinoe/dengue-forecast-using-ARIMA.git
```
2. Acesse a pasta do repositório e crie um ambiente virtual:
```
cd dengue-forecast-using-ARIMA
virtualenv venv
```
3. Ative o ambiente virtual conforme o seu Sistema Operacional
```
# Para Windows
.\venv\Scripts\activate

# Para macOS ou Linux
source venv/bin/activate
```

4. Instale as bibliotecas utilizadas no projeto:
```
pip install -r requirements.txt
```

### Estrutura de pastas e arquivos
`datasets/`: Contém os datasets utilizados no projeto.<br>
`notebooks/`: Contém os notebooks com os códigos em Python utilizados no projeto.<br>
`notebooks/data_wrangling.ipynb`: Notebook com o código utilizado para extrair os dados da API.<br>
`notebooks/notebook.ipynb`: Notebook contendo as etapas de tratamento inicial dos dados, análise exploratória, ajustes do modelo e avaliações do desempenho.

## Contribuições e Limitações:
Este projeto foi desenvolvido e apresentado como trabalho de conclusão de curso para a obtenção do título de especialista em Data Science and Analytics.<br>
Limitações incluem a dependência de dados secundários e a consideração de subnotificações.

## Como Contribuir:
Caso identifique melhorias ou queira contribuir, sinta-se à vontade para fazer um fork do projeto, enviar pull requests ou entrar em contato comigo.

## Licença
[GPL-3.0 license - GNU GENERAL PUBLIC LICENSE](https://github.com/amandashichinoe/dengue-forecast-using-ARIMA?tab=GPL-3.0-1-ov-file)