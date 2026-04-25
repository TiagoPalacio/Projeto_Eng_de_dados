# 🧊 Apache Iceberg

O **Apache Iceberg** é um formato de tabela aberto e de alto desempenho projetado para gigantescos volumes de dados. Ele nasceu dentro da Netflix para resolver os problemas de lentidão na hora de consultar milhares de arquivos em diretórios complexos.

## Diferenciais
O Iceberg rastreia dados no nível do *arquivo*, e não no nível da pasta. Isso significa que as consultas são extremamente rápidas.

* **Evolução de Esquema:** Permite adicionar, remover ou renomear colunas da nossa tabela de Motoristas ou Corridas sem precisar reescrever o banco de dados inteiro (o que é vital para o crescimento do aplicativo).
* **Time Travel:** Permite consultar como a tabela de corridas estava em qualquer momento do passado.