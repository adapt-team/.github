## API Reference

#### Authorize into lavalink server

```http
  GET /api/v1/lavalink
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `authorization` | `string` | **Required**. API Token |

#### Get project version

```http
  GET /api/v1/version
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `Product`      | `string` | **Optional**. Project to fetch version from |
