**authRoute**
| HTTP Method | URL Path | Description |
|-------------|--------------------|---------------|
| POST | /api/auth/register | create a user |
| POST | /api/auth/login | login a user |

**usersRoute**
| HTTP Method | URL Path | Description |
|-------------|-------------------------|-----------------|
| PUT | /api/users/:id | update a user |
| DELETE | /api/users/:id | delete a user |
| GET | /api/users/:id | get a user |
| PUT | /api/users/:id/follow | follow a user |
| PUT | /api/users/:id/unfollow | unfollow a user |

**postsRoute**
| HTTP Method | URL Path | Description |
|-------------|-------------------------|---------------------|
| POST | /api/posts/ | create a post |
| PUT | /api/posts/:id | update a post |
| DELETE | /api/posts/:id | delete a post |
| PUT | /api/post/:id/like | like/dislike a post |
| GET | /api/posts/:id | get a post |
| GET | /api/posts/timeline/all | get timeline posts |

**create a `.env` in the root directory**

```dosini
MONGO_URL = "your mongo url"
```
