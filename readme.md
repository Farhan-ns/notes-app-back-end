# Notes API
All notes are stored in notes.js
## Endpoints
### Get All Notes
```js
GET /notes
```

### Get Note by ID
```js
GET /notes/{id}
```

### Add Note
```js
POST /notes
```
```js
Note Object:
{
    title,
    tags[],
    body
}
```

### Edit Note
```js
PUT /notes/{id}
```
```js
Note Object:
{
    title,
    tags[],
    body
}
``` 

### Delete Note
```js
DELETE /notes/{id}
```