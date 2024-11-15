# `collection` resource

Base endpoint:

```shell

{base_url}/collections
```

The `collection` resource contains details pertinent to the book collection. A `collection` may be blank, or include one or more books.

## Resource properties

Sample `user` resource

```js

{
   "collection_id": 101,
   "user_id": 1,
   "name": "Favorite Classics",
   "privacy": "private",
   "created_at": "2023-08-15",
   "books":
    {}
}
```

| Property name | Type | Description | Required? |
| ------------- | ----------- | ----------- | ----------- |
| `collection_id` | number | ID of the collection | Yes |
| `user_id` | number | The user's ID  | Yes |
| `name` | string | A title for the collection  | Yes |
| `privacy` | string | The user's privacy choice  | Yes |
| `created_at` | string | The date the collection was created  | Yes |
| `books` | array | List of books inthe collection  | No |

## READ

* 
