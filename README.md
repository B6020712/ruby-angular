# My first time coding both Ruby on Rails and Angular
### Frontend: Angular
### Backend: Ruby
### Database: SQLite3
<hr>
#### <u>Ruby on Rails Command's</u><br>
* run server: <i>rails server</i><br>
* run console: <i>rails console</i><br>
> note: don't forget to go in to backend folder</p><br>
<hr>
#### <u>Database(with Curl) Command's</u><br>
* get all: <i>curl -X GET http://127.0.0.1:3000/api/v1/articles</i><br>
* get article by id: <i>curl -X GET http://127.0.0.1:3000/api/v1/articles/1</i><br>
* post article:  <i>curl -X POST http://127.0.0.1:3000/api/v1/articles -H "Content-Type: application/json" -d "{\"title\":\"\",\"body\":\"\",\"author\":\"\"}"</i><br>
* update(put) article:  <i>curl -X PUT http://127.0.0.1:3000/api/v1/articles -H "Content-Type: application/json" -d "{\"title\":\"\",\"body\":\"\",\"author\":\"\"}"</i><br>
* delete(destroy) article by id: <i>curl -X DELETE http://127.0.0.1:3000/api/v1/articles/4</i><br>