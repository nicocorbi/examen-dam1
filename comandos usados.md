curl -X POST 192.168.60.211:3000/shared_data -d '{"mensaje": "Hola, este es un mensaje en el cuerpo", "numero": 123, "fecha": "2024-12-17"}'
curl -X GET http://192.168.60.211:3000/users
curl -X GET http://192.168.60.211:3000/users/{6}
 curl -X GET "http://192.168.60.211:3000/users/6" -H "APIKEY: G37BU5Y"
curl -X POST "http://192.168.60.211:3000/login"      -H "appkey: G37BU5Y"      -H "Content-Type: application/json"      -H "Accept: application/json"      -d '{"name": "hiddenotter", "password": "otter123"}'


