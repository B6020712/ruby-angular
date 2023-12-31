# My first time coding both Ruby on Rails and Angular
| Role     | Technology |
|:---------|----------: |
| Frontend | `Angular`  |
| Backend  | `Ruby`     |
| Database | `SQLite3`  |

---
**Angular(npm) Command's**
```node
ng serve --open
```
> note: don't forget to go inside frontend directory
---

**Ruby on Rails Command's**
```ruby
rails server
rails console
```
> note: don't forget to go inside backend directory
---
**Database(with Curl) Command's**
| Role                          | Commands                                                                                                                                     |
|:------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------|
| get all                       | `curl -X GET http://127.0.0.1:3000/api/v1/articles`                                                                                          |
| get article by id             | `curl -X GET http://127.0.0.1:3000/api/v1/articles/1`                                                                                        |
| post article:                 | `curl -X POST http://127.0.0.1:3000/api/v1/articles -H "Content-Type: application/json" -d "{\"title\":\"\",\"body\":\"\",\"author\":\"\"}"` |
| update(put) article:          | `curl -X PUT http://127.0.0.1:3000/api/v1/articles -H "Content-Type: application/json" -d "{\"title\":\"\",\"body\":\"\",\"author\":\"\"}"`  |
| delete(destroy) article by id | `curl -X DELETE http://127.0.0.1:3000/api/v1/articles/4`                                                                                     |