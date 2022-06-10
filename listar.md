## API Reference
### Book
#### list an book
list an book
```http
  POST http://127.0.0.1:8000/api/book
``` 
 Parameter | Type     | Description                       
| :-------- | :------- | :-------------------------------- |
`name`| `string` | **Required**. Book's name |
`author`| `string` | **Required**. Full name of author |
`year`| `int` | **Required**. Year of publish |
`status`| `boolean` | **Required**. Status |
`synopsis`| `text` | **Optional**. The Book's synopsis |

### Request example:
```json
{
   "livros":[
      {
         "id":1,
         "created_at":"2022-06-08T18:04:30.000000Z",
         "updated_at":"2022-06-08T18:04:30.000000Z",
         "nome":"Banana Power",
         "autor":"BJ",
         "ano":1941,
         "status":0,
         "sinopse":null
      },
      {
         "id":2,
         "created_at":"2022-06-08T18:04:31.000000Z",
         "updated_at":"2022-06-08T18:04:31.000000Z",
         "nome":"Banana Power",
         "autor":"BJ",
         "ano":1925,
         "status":0,
         "sinopse":null
      },
      {
         "id":3,
         "created_at":"2022-06-08T18:04:31.000000Z",
         "updated_at":"2022-06-08T18:04:31.000000Z",
         "nome":"Banana Power",
         "autor":"BJ",
         "ano":2010,
         "status":0,
         "sinopse":null
      },
      {
         "id":4,
         "created_at":"2022-06-08T18:04:31.000000Z",
         "updated_at":"2022-06-08T18:04:31.000000Z",
         "nome":"Banana Power",
         "autor":"BJ",
         "ano":2015,
         "status":0,
         "sinopse":null
      },
      {
         "id":5,
         "created_at":"2022-06-08T18:07:28.000000Z",
         "updated_at":"2022-06-08T18:07:28.000000Z",
         "nome":"Banana Power",
         "autor":"BJ",
         "ano":1901,
         "status":1,
         "sinopse":null
      },
      {
         "id":6,
         "created_at":"2022-06-08T18:07:28.000000Z",
         "updated_at":"2022-06-08T18:07:28.000000Z",
         "nome":"Banana Power",
         "autor":"BJ",
         "ano":1930,
         "status":1,
         "sinopse":null
      },
      {
         "id":7,
         "created_at":"2022-06-08T18:07:28.000000Z",
         "updated_at":"2022-06-08T18:07:28.000000Z",
         "nome":"Banana Power",
         "autor":"BJ",
         "ano":1909,
         "status":0,
         "sinopse":null
      },
      {
         "id":8,
         "created_at":"2022-06-08T18:07:28.000000Z",
         "updated_at":"2022-06-08T18:07:28.000000Z",
         "nome":"Banana Power",
         "autor":"BJ",
         "ano":2002,
         "status":1,
         "sinopse":null
      },
      {
         "id":9,
         "created_at":"2022-06-09T19:56:00.000000Z",
         "updated_at":"2022-06-09T19:56:00.000000Z",
         "nome":"Apple Power",
         "autor":"CJ",
         "ano":1943,
         "status":1,
         "sinopse":null
      },
      {
         "id":10,
         "created_at":"2022-06-09T19:56:00.000000Z",
         "updated_at":"2022-06-09T19:56:00.000000Z",
         "nome":"Apple Power",
         "autor":"CJ",
         "ano":1992,
         "status":1,
         "sinopse":null
      },
      {
         "id":11,
         "created_at":"2022-06-09T19:56:00.000000Z",
         "updated_at":"2022-06-09T19:56:00.000000Z",
         "nome":"Apple Power",
         "autor":"CJ",
         "ano":1939,
         "status":0,
         "sinopse":null
      },
      {
         "id":12,
         "created_at":"2022-06-09T19:56:00.000000Z",
         "updated_at":"2022-06-09T19:56:00.000000Z",
         "nome":"Apple Power",
         "autor":"CJ",
         "ano":1923,
         "status":1,
         "sinopse":null
      },
      {
         "id":13,
         "created_at":"2022-06-09T19:56:20.000000Z",
         "updated_at":"2022-06-09T19:56:20.000000Z",
         "nome":"Pinapple Power",
         "autor":"PW",
         "ano":2009,
         "status":0,
         "sinopse":null
      },
      {
         "id":14,
         "created_at":"2022-06-09T19:56:20.000000Z",
         "updated_at":"2022-06-09T19:56:20.000000Z",
         "nome":"Pinapple Power",
         "autor":"PW",
         "ano":1914,
         "status":1,
         "sinopse":null
      },
      {
         "id":15,
         "created_at":"2022-06-09T19:56:20.000000Z",
         "updated_at":"2022-06-09T19:56:20.000000Z",
         "nome":"Pinapple Power",
         "autor":"PW",
         "ano":1944,
         "status":0,
         "sinopse":null
      },
      {
         "id":16,
         "created_at":"2022-06-09T19:56:20.000000Z",
         "updated_at":"2022-06-09T19:56:20.000000Z",
         "nome":"Pinapple Power",
         "autor":"PW",
         "ano":1961,
         "status":1,
         "sinopse":null
      },
      {
         "id":17,
         "created_at":"2022-06-09T19:56:39.000000Z",
         "updated_at":"2022-06-09T19:56:39.000000Z",
         "nome":"kiwi Power",
         "autor":"KW",
         "ano":2020,
         "status":0,
         "sinopse":null
      },
      {
         "id":18,
         "created_at":"2022-06-09T19:56:39.000000Z",
         "updated_at":"2022-06-09T19:56:39.000000Z",
         "nome":"kiwi Power",
         "autor":"KW",
         "ano":1993,
         "status":0,
         "sinopse":null
      },
      {
         "id":19,
         "created_at":"2022-06-09T19:56:39.000000Z",
         "updated_at":"2022-06-09T19:56:39.000000Z",
         "nome":"kiwi Power",
         "autor":"KW",
         "ano":1976,
         "status":1,
         "sinopse":null
      },
      {
         "id":20,
         "created_at":"2022-06-09T19:56:39.000000Z",
         "updated_at":"2022-06-09T19:56:39.000000Z",
         "nome":"kiwi Power",
         "autor":"KW",
         "ano":1934,
         "status":0,
         "sinopse":null
      }
   ]
}
```
### Response 201:
```json
{
	"message":"success",
}

