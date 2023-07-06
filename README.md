# My first time coding both Ruby on Rails and Angular
### Frontend: Angular
### Backend: Ruby
### Database: SQLite3

**Ruby on Rails Command's**
* run server: `rails server`
* run console: `rails console`
> note: don't forget to go in to backend folder

**Database(with Curl) Command's**
* get all: `curl -X GET http://127.0.0.1:3000/api/v1/articles`
* get article by id: `curl -X GET http://127.0.0.1:3000/api/v1/articles/1`
* post article:  `curl -X POST http://127.0.0.1:3000/api/v1/articles -H "Content-Type: application/json" -d "{\"title\":\"\",\"body\":\"\",\"author\":\"\"}"`
* update(put) article:  `curl -X PUT http://127.0.0.1:3000/api/v1/articles -H "Content-Type: application/json" -d "{\"title\":\"\",\"body\":\"\",\"author\":\"\"}"`
* delete(destroy) article by id: `curl -X DELETE http://127.0.0.1:3000/api/v1/articles/4`