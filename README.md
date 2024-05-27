# SDSS Galaxy Classification DR18

Tópico L - Trabalho prático 2 - IA - Grupo A2_22

- Félix Martins, up202108837
- Pedro Lima, up202108806
- Pedro Januário, up202108768

## Instalação de dependências

A solução requer a instalação das bibliotecas presentes no ficheiro `requirements.txt`. Tal pode ser feito através dos comandos:

### Linux / macOS

```bash
python -m venv .venv        # Create a python virtual environment
source .venv/bin/activate   # Activate the virtual environment
pip install -r requirements.txt # Install the required libraries
```

### Windows

```bash
python -m venv .venv    # Create a python virtual environment
.venv\Scripts\activate  # Activate the virtual environment
pip install -r requirements.txt # Install the required libraries
```

Para desativar o "ambiente", basta correr o comando:
```bash
deactivate
```

<div style="page-break-after: always;"></div>

## Execução

Todo o código encontra-se sob a forma de Jupyter Notebooks.

O trabalho desenvolvido pode ser encarado como contendo 3 fases/passos:

 - 1 &mdash; Pré-processamento dos dados
    - Seguir o ficheiro `data.ipynb`
 - 2 &mdash; Exploração dos modelos de classificação
    - No ficheiro `algorithms_discovery.ipynb`, os vários modelos de classificação disponíveis, bem como combinações de diferentes valores para os respetivos parâmetros, são testados com os dados disponíveis, de modo a descobrir, para cada modelo, que conjunto de parâmetros leva a melhores resultados.
 - 3 &mdash; Execução final
    - Por último, `algorithms_final.ipynb` comporta a execução dos vários modelos de classificação, com os parâmetros obtidos na fase anterior sobre o conjunto completo* dos dados.

*Conforme os ajustes levados a cabo na fase de pré-processamento, que incluem corte de alguns objetos.

***

Grupo A2_22, maio de 2024
