## API Reference
### Book
#### Create an book
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
	"name": "The Way",
	"author": "Josh Clarence Jackson",
	"year": 2010,
	"status": 1
}
```
### Response 201:
```json
{
	"message":"success",
}

