# Apache Spark com Delta Lake e Iceberg

## Pré-requisitos
- Python 3.11+
- Java 11 (necessário para o Spark)
- UV instalado (`pip install uv`)

## Como executar

```bash
git clone https://github.com/seu-usuario/spark-delta-iceberg
cd spark-delta-iceberg
uv sync
uv run jupyter lab
```

## Versões utilizadas
| Biblioteca     | Versão  |
|----------------|---------|
| PySpark        | 3.5.1   |
| delta-spark    | 3.2.0   |
| PyIceberg      | 0.6.0   |
| JupyterLab     | 4.x     |

## Notebooks
- `notebooks/delta_lake.ipynb` — exemplos com Delta Lake
- `notebooks/iceberg.ipynb` — exemplos com Apache Iceberg