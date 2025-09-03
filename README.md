# CP4-IOT — Análise de Dados de Consumidores de Energia

##  Descrição
Este repositório reúne o projeto CP4-IOT, cuja proposta é analisar dados de consumo energético utilizando técnicas e tecnologias de IoT (Internet das Coisas). O foco está na aquisição, processamento e visualização de dados de consumo elétrico, contribuindo com compreensão de padrões, eficiência e possibilitando insights para gerenciamento energético.

##  Conteúdo
- `data/` — (opcional) pasta para armazenar os dados brutos (ex: arquivos CSV, logs de leitores inteligentes).
- `src/` — código-fonte utilizado para aquisição, limpeza, análise e visualização.
- `notebooks/` — notebooks Jupyter com exploração de dados e relatórios.
- `reports/` — resultados gerados (gráficos, relatórios em PDF, dashboards estáticos).
- `README.md` — este arquivo.
- `requirements.txt` — listagem das dependências Python necessárias.
- `LICENSE` — (opcional) licença do projeto.

##  Requisitos
- **Python 3.8+**
- Principais bibliotecas:
  - `pandas`, `numpy` — manipulação de dados;
  - `matplotlib`, `seaborn`, `plotly` — visualização;
  - `scikit-learn` — possíveis análises e modelagem;
  - `jupyter` — para execução dos notebooks.
  
Instalação recomendada em ambiente virtual:

```bash
python -m venv .venv
source .venv/bin/activate     # Linux/macOS
.\\.venv\\Scripts\\activate   # Windows
pip install -r requirements.txt
Como usar
Clone este repositório:

bash
Copiar código
git clone https://github.com/ViniciusRibeiroNery/CP4-IOT.git
Coloque seus arquivos de dados em data/, se houver.

Ative o ambiente virtual e instale dependências.

Execute os notebooks em notebooks/:

Os notebooks contêm análises passo a passo, visualizações e comentários explicativos.

Os resultados são exportados em reports/ (gráficos, tabelas, dashboards).

Funcionalidades (exemplos)
Limpeza e tratamento de dados de consumo energético.

Agregações por período (hora, dia, semana, mês).

Detecção de padrões sazonais ou de horários de pico.

Comparação entre perfis de consumo (residencial, comercial, sazonalidade, etc.).

Análises exploratórias com visualizações interativas.
