# Como Reproduzir o Experimento

1. Configuração do Ambiente

CONDA:
 ```
conda create --name missing-data --file requerimentos-conda.txt
conda activate missing-data
 ```

venv:
 ```
python -m venv venv
source venv/bin/activate  # No Windows: venv\Scripts\activate
pip install -r requeriments_venv.txt
 ```
Execução paralela -> NUM_PROCESSADORES, ajuste a variável para corresponder ao seu hardware.

Após configurar, é possível executar o notebook sem problemas.