# Aula 4 - Construindo um Dashboard com Streamlit

Nesta aula, você vai conhecer a biblioteca Streamlit e aprender a criar um dashboard interativo de forma prática. Com ele, será possível visualizar dados, aplicar filtros e gerar gráficos em tempo real, facilitando a análise e a apresentação das informações.

## 📘 O que você vai aprender

- Conhecer a biblioteca Streamlit para criar dashboards interativos.
- Desenvolver interfaces simples para visualização de dados.
- Aplicar filtros dinâmicos para explorar os dados em tempo real.
- Gerar gráficos direto no dashboard para facilitar a análise.
---

## Instalando dependencias e rodando projeto

1. Criar o ambiente virtual:

```bash
python3 -m venv .venv
```

2. Ativar o ambiente virtual em Windows:

```bash
.venv\Scripts\Activate
```

3. Ativar o ambiente virtual em MAC/LINUX:
```bash
source .venv/bin/activate
```

4. Criar um arquivo chamado requirements.txt e adicionar os pacotes necessários

```bash
pandas==2.2.3
streamlit==1.44.1
plotly==5.24.1
```

5. Instalar as bibliotecas necessárias

```bash
pip install -r requirements.txt
```

6. Criar a Interface do Dashboard com Streamlit

7. Realizar o deploy do Dashboard no Streamlit Cloud: https://streamlit.io/cloud

## 📂 Arquivos da Aula

️📊 **Dados:** [dados-imersao-final.csv](./dados-imersao-final.csv)  
*Arquivo CSV com os dados que são usados para criar o Dashboard.*

🐍 **Script:** [app.py](./app.py)  
*Arquivo Python que manipula os dados importados e cria o Dashboard.*

📘 **Requerimentos:** [requirements.txt](./requirements.txt)  
*Arquivo TXT contem lista de bibliotecas necesssarias para serem instaladas.*

---

## 🧭 Navegação

🔙 [Voltar para o índice de aulas](../README.md)