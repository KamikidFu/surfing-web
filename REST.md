# RESTful Route Design

*Ver 0.1*



## About User

| Name          | Path                      | HTTP | Purpose                              |
| ------------- | ------------------------- | ---- | ------------------------------------ |
| Create User   | /user/new                 | GET  | Show new user form                   |
| Validate User | /user/:username/:password | GET  | Validate the specific user           |
| Show User     | /user/:id                 | GET  | Show the particular user             |
| Edit User     | /user/:id/edit            | GET  | Show edit form for the specific user |
| Update User   | /user/:id                 | PUT  | Update a particular user             |



## About Article

| Name           | Path              | HTTP   | Purpose                                 |
| -------------- | ----------------- | ------ | --------------------------------------- |
| List Article   | /article          | GET    | List all article                        |
| Create Article | /article/new      | GET    | Show new article form                   |
| Show Article   | /article/:id      | GET    | Show info about the specific article    |
| Edit Article   | /article/:id/edit | GET    | Show edit form for the specific article |
| Update Article | /article/:id      | PUT    | Update a particular article             |
| Delete Article | /article/:id      | DELETE | Delete a particular article             |



## About Comment

| Name            | Path                      | HTTP | Purpose                                             |
| --------------- | ------------------------- | ---- | --------------------------------------------------- |
| List Comments   | /article/:id/comments     | GET  | List all comments related to the particular article |
| Create Comment  | /article/:id/new          | GET  | Show new comment form                               |
| Reply a comment | /article/:id/comments/:id | PUT  | Add reply comment to the certain comment            |



