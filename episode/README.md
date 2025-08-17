# Episode Query

This section contains GraphQL queries to fetch details of a specific episode from the API.

## Files
- `episode-page-1.graphql` → Query for episode with ID 1
- `episode-page-1-output.json` → Output of the query

## Fields Retrieved
Each query retrieves:
- `id`
- `name`
- `air_date`
- `episode`

## Example Query
```graphql
query {
  episode(id: 1) {
    id
    name
    air_date
    episode
  }
}