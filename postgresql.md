#Notes on working with PostgreSQL
### Connect to DB:
`psql DBNAME USERNAME`

### Show connection info inside psql:
`\c`

### Show databases inside psql:
`\l`

### Create INDEX:
`CREATE INDEX idx_name ON table_name (column_name);`

### Create Index and not block the table:
`CREATE INDEX CONCURRENTLY idx_name ON table_name (column_name);`

### Quit from psql:
`\q`
