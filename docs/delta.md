# 🌊 Delta Lake

O **Delta Lake** é uma camada de armazenamento open-source que traz confiabilidade para os Data Lakes (que por padrão são caóticos). Ele foi originalmente criado pela Databricks.

## Por que usamos no projeto?
Em um sistema de Despachos, motoristas mudam de "Ativo" para "Inativo" e corridas são atualizadas o tempo todo. Em um Data Lake tradicional, não podemos fazer `UPDATE` ou `DELETE` com facilidade. O Delta Lake resolve isso adicionando **Transações ACID**.

* **No código:** Quando rodamos `spark.sql("UPDATE corridas...")` usando a extensão Delta, ele garantiu que a alteração do status da corrida não corrompesse a tabela.