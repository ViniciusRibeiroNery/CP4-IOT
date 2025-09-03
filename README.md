# CP4-IOT — Análise de Dados de Consumidores de Energia

## 📌 Descrição
Este repositório reúne o projeto **CP4-IOT**, com foco na análise de dados de consumo energético utilizando técnicas e tecnologias de IoT (Internet das Coisas).  
O objetivo é explorar padrões de consumo, sazonalidade e comportamento energético a partir de conjuntos de dados públicos.

## 📂 Estrutura do Repositório
- `notebooks/` — Notebooks Jupyter contendo as análises, gráficos e experimentos.
- `data/` — **(vazia no repositório)**  
   ➝ Coloque aqui os arquivos baixados manualmente dos links oficiais listados abaixo.  
- `README.md` — Este arquivo com instruções.

## 📥 Conjuntos de Dados
Os arquivos de dados **não estão incluídos** neste repositório devido ao tamanho e política de distribuição.  
Baixe manualmente dos links oficiais da UCI Machine Learning Repository:

- [Individual household electric power consumption](https://archive.ics.uci.edu/dataset/235/individual+household+electric+power+consumption)  
- [Appliances energy prediction](https://archive.ics.uci.edu/dataset/374/appliances+energy+prediction)

Após o download, coloque os arquivos dentro da pasta `data/`.

## ⚙️ Requisitos
- Python 3.8+  
- Bibliotecas principais:  
  - `pandas`, `numpy` — manipulação de dados  
  - `matplotlib`, `seaborn` — visualização  
  - `scikit-learn` — modelagem e análise  
  - `jupyter` — execução dos notebooks  

Crie um ambiente virtual e instale as dependências:
```bash
python -m venv .venv
source .venv/bin/activate     # Linux/macOS
.\\.venv\\Scripts\\activate   # Windows
pip install -r requirements.txt
▶️ Como executar
Clone este repositório:

bash
Copiar código
git clone https://github.com/ViniciusRibeiroNery/CP4-IOT.git
Baixe os datasets e coloque os arquivos em data/.

Abra e execute os notebooks em notebooks/ com Jupyter.

Analise os gráficos e resultados gerados.

📊 Funcionalidades esperadas
Limpeza e tratamento dos dados energéticos.

Criação de séries temporais e estatísticas descritivas.

Comparação entre padrões de consumo em diferentes condições (estações do ano, horários de pico).

Modelagem e previsão com técnicas de Machine Learning.
