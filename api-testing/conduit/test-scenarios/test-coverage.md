# Test Coverage – Conduit API

|     Feature       |                 Endpoint                | Tested |
|-------------------|-----------------------------------------|--------|
| User Registration | POST   /api/users                       |   ✅   |
| User Login        | POST   /api/users/login                 |   ✅   |
| Create Article    | POST   /api/articles                    |   ✅   |
| Delete Article    | DELETE /api/articles/:slug              |   ✅   |
| Get Tags          | GET    /api/tags                        |   ✅   |
| Create Comment    | POST   /api/articles/:slug/comments     |   ✅   |
| Delete Comment    | DELETE /api/articles/:slug/comments/:id |   ✅   |

