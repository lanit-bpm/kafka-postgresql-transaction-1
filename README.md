# kafka-postgresql-transaction-1
Реализация распределенных транзакций в парадигме strong consistency, охватывающих Kafka и реляционную СУБД (PostgreSQL).

В данном проекте реализован вариант с (deprecated) ChainedTransactionManager

В проекте используются testcontainers для Kafka и PostgreSQL, поэтому для запуска нужен Docker