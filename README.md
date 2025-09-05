# Imersao Dados Alura

Projeto realizado numa imersão de dados da Alura, onde pude aprender como deixar os dados prontos para uso, gerar gráficos e gerar uma página web com estes dados.

---

# 📊 Dashboard de Análise de Salários na Área de Dados

Este projeto é um **dashboard interativo** desenvolvido com [Streamlit](https://streamlit.io/) para explorar e analisar **salários na área de dados**.

A aplicação permite filtrar, visualizar e interpretar tendências salariais por cargo, senioridade, tipo de contrato, tamanho da empresa e outros aspectos.

---

## ✨ Funcionalidades

* **Filtros dinâmicos** na barra lateral:

  * Ano
  * Senioridade
  * Tipo de contrato
  * Tamanho da empresa

* **Métricas gerais (KPIs)**:

  * Salário médio (USD)
  * Salário máximo (USD)
  * Total de registros filtrados
  * Cargo mais frequente

* **Gráficos interativos com Plotly**:

  * 📊 **Top 10 cargos por salário médio**
  * 📈 **Distribuição de salários (histograma)**
  * 🥧 **Proporção dos tipos de trabalho (remoto, híbrido, presencial)**
  * 🌍 **Mapa coroplético**: salário médio de Cientistas de Dados por país

* **Tabela detalhada** com todos os dados filtrados

---

## 🚀 Tecnologias Utilizadas

* [Python 3.8+](https://www.python.org/)
* [Streamlit](https://streamlit.io/) — criação do dashboard
* [Pandas](https://pandas.pydata.org/) — manipulação dos dados
* [Plotly Express](https://plotly.com/python/plotly-express/) — visualizações interativas

---

## 💾 Fonte dos Dados

Os dados vêm de um repositório público no GitHub:

📂 [dados-imersao-final.csv](https://raw.githubusercontent.com/vqrca/dashboard_salarios_dados/refs/heads/main/dados-imersao-final.csv)

---

## ⚙️ Como Executar Localmente

### 1. Pré-requisitos

* Python 3.8 ou superior
* pip instalado

### 2. Clonar o repositório ou salvar o código

```bash
git clone <URL_DO_SEU_REPOSITORIO>
cd <NOME_DO_DIRETORIO>
```

Caso não use git, salve o código em um arquivo `app.py`.

### 3. Criar ambiente virtual (opcional, recomendado)

```bash
# Windows
python -m venv venv
.\venv\Scripts\activate

# macOS/Linux
python3 -m venv venv
source venv/bin/activate
```

### 4. Instalar dependências

Crie um arquivo `requirements.txt` com:

```
pandas==2.2.3
streamlit==1.44.1
plotly==5.24.1
```

E rode:

```bash
pip install -r requirements.txt
```

### 5. Executar a aplicação

```bash
streamlit run app.py
```

Abra no navegador: [http://localhost:8501](http://localhost:8501)

---

## 📂 Estrutura do Projeto

```
📁 dashboard-salarios
 ├── app.py               # Código principal do Streamlit
 ├── requirements.txt     # Dependências do projeto
 └── README.md            # Documentação
```

---

## 📌 Melhorias Futuras

* Adicionar novos filtros (gênero, setor de atuação, etc.)
* Criar opção de download dos dados filtrados
* Comparações entre anos lado a lado
