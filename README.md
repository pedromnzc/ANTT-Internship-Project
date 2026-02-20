# ANTT Internship Project 

## 📌 Descrição
Projeto de ingestão e processamento de dados da Ouvidoria da ANTT.
Os dados brutos são convertidos para formato Parquet para otimização de armazenamento e performance.

## 🗂 Estrutura do Projeto

```
project/
│
├── data/
├── scripts/  # Script em Quarto Markdown
├── README.md
└── requirements.txt
```

## 🛠 Tecnologias Utilizadas

- Python
- Pandas
- PyArrow
- Qarto Markdown
- Parquet

## 🚀 Como Executar

1. Clone o repositório:
   ```bash
   git clone
   ```
   
2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

3. Execute os scripts em Qarto Markdown para processar os dados:
   ```bash
   quarto render scripts/ --to html
   ```

## 📊 Resultados
Os dados processados estão disponíveis no formato Parquet, otimizados para análise e consulta eficiente em ferramentas de big data.