
#### Example Request
```bash
curl \
-XPUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"add":{"Cache-Control":"no-cache, no-store","X-XSS-Protection":"1; mode=block"}}' \
https://api.ngrok.com/endpoint_configurations/ec_2GjCRYrx4kjpz4br7N8WEEV30Y6/response_headers