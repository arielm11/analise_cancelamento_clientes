# Análise de Cancelamento de Clientes
Este projeto tem como objetivo analisar uma base de dados para entender os motivos de cancelamento de clientes e propor soluções para reduzir essa taxa. Utilizando Python e bibliotecas como `pandas` e `plotly`, vamos explorar, tratar e visualizar os dados para identificar padrões e fatores críticos que impactam o cancelamento de clientes.

## 🎯 Objetivo
O projeto visa explorar uma base de dados contendo informações de clientes, como idade, sexo, dias de atraso, total gasto, entre outros, com o intuito de:
- Identificar as causas do cancelamento de clientes.
- Propor soluções para reduzir a taxa de cancelamento.
- Aplicar técnicas de análise de dados utilizando Python e bibliotecas como `pandas` e `plotly`.

## ⚙️ Funcionalidades
- Carregar e analisar a base de dados de clientes.
- Realizar a limpeza e o tratamento dos dados (remoção de valores nulos e irrelevantes).
- Calcular a taxa de cancelamento de clientes.
- Analisar diferentes tipos de contrato (mensal, trimestral, anual) e como eles impactam os cancelamentos.
- Gerar gráficos interativos com a biblioteca `plotly` para visualização de padrões.
- Identificar fatores críticos que influenciam o comportamento de cancelamento dos clientes.

## 📋 Pré-requisitos
Antes de começar, você precisará instalar as seguintes ferramentas:
- **Python 3.x**: [Instalar Python](https://www.python.org/)
- Biblioteca **pandas** para manipulação de dados:
  ```bash
  pip install pandas
  ```
- Biblioteca **plotly** para manipulação de dados:
  ```bash
  pip install plotly
  ```

## 📁 Estrutura do Projeto
- `dados.csv`: Base de dados com informações dos clientes.
- `scripts/analise.py`: Código para tratamento e análise de dados.
- `scripts/visualizacao.py`: Código para geração de gráficos interativos.
- `README.md`: Arquivo de documentação (este).
- `requirements.txt`: Lista de dependências do projeto.

## 🔧 Como Usar
1. Clone este repositório:
  ```bash
  git clone https://github.com/arielm11/analise_cancelamento_clientes.git
  cd seu-repositorio
  ```
2. Certifique-se de ter o arquivo `dados.csv` no mesmo diretório do script.
3. Instale as dependências:
  ```bash
  pip install -r requirements.txt
  ```
4. Execute o script para carregar e analisar os dados:
  ```bash
  python scripts/analise.py
  ```
5. Após a análise, execute o script para gerar os gráficos interativos:
  ```bash
  python scripts/visualizacao.py
  ```
## 🖥️ Tecnologias Utilizadas
- Python
- Pandas
- Plotly