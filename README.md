Examples

```
sudo dnf install curl

curl -X GET http://127.0.0.1:5000/tasks

curl -X POST http://127.0.0.1:5000/tasks \
-H "Content-Type: application/json" \
-d '{"title": "Learn Flask", "description": "Flask Todo", "done": false}'


curl -X PUT http://127.0.0.1:5000/tasks/1 \
-H "Content-Type: application/json" \
-d '{"title": "Learn Flask", "description": "Flask REST API Todo Done", "done": true}'


curl -X DELETE http://127.0.0.1:5000/tasks/1
```

