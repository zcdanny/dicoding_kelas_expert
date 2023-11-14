# Forum API

### Users & Authentication

- User Registration

`POST /users`

- User Login

`POST /authentications`

- Update authentication / refresh access token

`PUT /authentications`

- User Logout

`DELETE /authentications`

### Threads

- Add a Thread

`POST /threads`

- View Thread Details

`GET /threads/{threadId}`

### Thread Comments

- Add Comment to a Thread

`POST /threads/{threadId}/comments`

- Delete Comment on a Thread

`DELETE /threads/{threadId}/comments/{commentId}`

- Like or Unlike a Comment on a Thread

`PUT /threads/{threadId}/comments/{commentId}/likes`

### Thread Comment Replies

- Add Reply to a Thread Comment

`POST /threads/{threadId}/comments/{commentId}/replies`

- Delete Reply on a Thread Comment

`DELETE /threads/{threadId}/comments/{commentId}/replies/{replyId}`
