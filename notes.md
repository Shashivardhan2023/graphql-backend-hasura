- GraphQL is an API query language and run-time
- Hasura is a backend server for parsing and automating these queries.

Fields:
- sorting with `order_by`: choose columns by which to sort and additionally ascending, descending and nulls_first or nulls_last
  - use `distinct_on` to avoid querying duplicate entries
- filtering and full-text search with `where`: choose columns and values to filter using conditional operations
- combining filters with `_and`, `_not` and `_or`
- pagination with `limit` and `offset`

Operations:
- Mutations used to create, update and delete items
- Queries used to fetch data
- Subscriptions used to fetch data in realtime