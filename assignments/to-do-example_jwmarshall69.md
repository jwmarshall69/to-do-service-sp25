# Code examples

**Author:** Jimmie Marshall

## cURL example

Lists user information, including first and last name, email, and user ID.

### cURL command

```shell
curl http://localhost:3000/users 
```

### cURL response

``` shell

  {
    "last_name": "Martinez",
    "first_name": "Marty",
    "email": "m.martinez@example.com",
    "id": 3
  }

```

## Postman example

Add a task for Marty Martinez (User 3) to attend Daughter's Piano recital a 2025-04-2T15:00, with a 30 minute warning. 

## Postman command

```shell
http://localhost:3000/tasks
```

## Postman response

```shell
  {
      "user_id": 1,
      "title": "Piano recital",
      "description": "Daughter's first concert appearance",
      "due_date": "2025-04-02T15:00",
      "warning": "-30",
      "id": 2
  }

```

### Request data

```shell
{
    "user_id": 1,
    "title": "Piano recital",
    "description": "Daughter's first concert appearance",
    "due_date": "2025-04-02T15:00",
    "warning": "-30",
}
   ```

**Method**: POST

```shell
<replace with the request used for this example>
```

### Postman response

```shell
{
   "user_id": 1,
    "title": "Piano recital",
    "description": "Daughter's first concert appearance",
    "due_date": "2025-04-02T15:00",
    "warning": "-30",
    "id": 2
}
```
