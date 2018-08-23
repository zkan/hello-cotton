# Fake REST API

This can be run with `cotton -u https://jsonplaceholder.typicode.com fake-rest-api.md`

## GET /posts/1

Get one post.

## Expectation

| Assert | Expected |
| - | - |
| StatusCode | 200 |
| Header.Content-Type | application/json; charset=utf-8 |
| Data.userId | 1 |
| Data.id | 1 |
| Data.title | sunt aut facere repellat provident occaecati excepturi optio reprehenderit |
| Data.body | quia et suscipit\nsuscipit recusandae consequuntur expedita et cum\nreprehenderit molestiae ut ut quas totam\nnostrum rerum est autem sunt rem eveniet architecto |
