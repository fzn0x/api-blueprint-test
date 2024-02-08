FORMAT: 1A

# Notes API
This API example demonstrates how to manage your notes

# Notes
Notes all activity

This is the first group of resources in this document. It is **recognized** by
the **keyword `notes`** and its name is `todo`.

Any following resource definition is considered to be a part of this group
until another group is defined. It is **customary** to increase header level of
resources (and actions) nested under a resource.

## Todos [/todos]

### Retrieve a todo [GET]

+ Response 200 (text/plain)

        [
          {
            id: 1,
            todo: "Wow Yeah",
            timeStamp: 2138127831272218937182973,
          }
        ]

## Todo [/todos/{id}]

A Todo contains information about the todo and the creation time.

+ Parameters
    + id (string)

        The ID of the desired todo.

### Get a Todo [GET]

+ Response 200 (text/plain)

        [
          {
            id: 1,
            todo: "Wow Yeah",
            timeStamp: 2138127831272218937182973,
          }
        ]

### Update a Todo [PUT]

+ Response 200 (text/plain)

        [
          {
            id: 1,
            todo: "Wow Yeah",
            timeStamp: 2138127831272218937182973,
          }
        ]

### Delete a Todo [DELETE]

+ Response 200 (text/plain)

        [
          {
            id: 1,
            todo: "Wow Yeah",
            timeStamp: 2138127831272218937182973,
          }
        ]
