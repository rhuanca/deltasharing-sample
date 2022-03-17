## Get Shares

```
curl --location --request GET 'localhost:8080/delta-sharing/shares' \
--header 'Authorization: Bearer 123456789'
```

## Get Schemas

```
curl --location --request GET 'localhost:8080/delta-sharing/shares/customer2/schemas' \
--header 'Authorization: Bearer 123456789'
```
## Get Tables

```
curl --location --request GET '172.20.0.2:8080/delta-sharing/shares/customer2/schemas/performance/tables' \
--header 'Authorization: Bearer 123456789'
```

## Query Table
```
curl --location --request POST 'localhost:8080/delta-sharing/shares/customer2/schemas/performance/tables/sales/query' \
--header 'Authorization: Bearer 123456789' \
--header 'Content-Type: application/json' \
--data-raw '{
}'
```