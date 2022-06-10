## API Reference
### Book
####  an book
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

### Request example:
```json
{
   "livro":{
      "id":3,
      "created_at":"2022-06-08T18:04:31.000000Z",
      "updated_at":"2022-06-08T18:04:31.000000Z",
      "nome":"Banana Power",
      "autor":"BJ",
      "ano":2010,
      "status":0,
      "sinopse":null
   }
}
```
### Response 201:
```json
{
	"message":"success",
}

