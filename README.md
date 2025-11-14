# Conversor de PDF para CSV e Excel

Este programa converte os dados de um formulário em um arquivo PDF para os formatos CSV e Excel.

## Como usar

### 1. Pré-requisitos

- Python 3
- Um ambiente virtual (recomendado)

### 2. Instalação

1.  Crie e ative um ambiente virtual:
    ```bash
    python3 -m venv venv
    source venv/bin/activate 
    ```

2.  Instale as dependências:
    ```bash
    pip install -r requirements.txt
    ```

### 3. Execução

Para executar a conversão, rode o seguinte comando a partir do diretório raiz do projeto:

```bash
python3 src/converter.py
```

Isso irá gerar os arquivos `DBPR_BES_Inspection_Report.csv` e `DBPR_BES_Inspection_Report.xlsx` no diretório raiz.

## Estrutura do Projeto

```
.
├── DBPR_BES_Inspection_Report.pdf
├── job_description.txt
├── README.md
├── src
│   └── converter.py
└── venv
```
