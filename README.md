# Cobertura Vacinal e Mortalidade — Análise por Município (2022)

Trabalho final (TP2) da disciplina de Ciência de Dados — UNESP.
**Tema 1:** Cobertura vacinal e mortalidade infantil por região.

## Pergunta central

Existe relação entre a cobertura vacinal contra poliomielite e a taxa de 
mortalidade entre municípios e regiões brasileiras?

## Dados utilizados

| Arquivo | Fonte | Sistema | Link de acesso | Data de download |
|---|---|---|---|---|
| ImunizaçãoPorMunicípio2022.csv | Ministério da Saúde/DATASUS | PNI | https://datasus.saude.gov.br/informacoes-de-saude-tabnet/| 16/09/2026 |
| NascidosVivosPorMunicípio2022.csv | Ministério da Saúde/DATASUS | SINASC | https://datasus.saude.gov.br/informacoes-de-saude-tabnet/ | 16/09/2026 |
| ÓbitosPorMunicípio2022.csv | Ministério da Saúde/DATASUS | SIM | https://datasus.saude.gov.br/informacoes-de-saude-tabnet/ | 16/09/2026 |

## Estrutura do repositório

├── datasets_notebook_requirements

└── README.md

## Como rodar

1. Clone o repositório:
```bash
   git clone https://github.com/deltageneral186/Projeto-Final-de-Ciencia-de-Dados
```

2. Crie um ambiente virtual (recomendado):
```bash
   python -m venv venv
   venv\Scripts\activate    # Windows
   source venv/bin/activate # Linux/Mac
```

3. Instale as dependências:
```bash
   pip install -r requirements.txt
```

4. Abra o notebook:
```bash
   jupyter notebook Projeto_Final_de_Ciência_de_Dados.ipynb
```

5. Execute todas as células em ordem (Kernel → Restart & Run All), já 
   que os CSVs estão no mesmo diretório do notebook e são carregados por 
   caminho relativo.

## Autores
Samuel Souza Del Grande

Kauã Guimarães Esperança
