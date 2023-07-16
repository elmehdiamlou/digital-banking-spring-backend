# Digital Banking Spring Backend

✅ Upgrade from Spring Boot 2 to Spring Boot 3 and secure the backend with stateless authentication using JWT.

- Some requests documented in HTTP Client `rest-api.http`

<pre>
POST http://localhost:8085/auth/login
Content-Type: application/x-www-form-urlencoded

username=admin&password=12345
   
<> <a href="/scratches/2023-07-16T125032.200.json">2023-07-16T125032.200.json</a>
<> <a href="/scratches/2023-07-16T123901.200.json">2023-07-16T123901.200.json</a>

###
GET http://localhost:8085/auth/profile
Accept: application/json
Authorization: Bearer eyJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1c2VyIiwiZXhwIjoxNjg5NTA4MTIwLCJpYXQiOjE2ODk1MDc1MjAsInNjb3BlIjoiVVNFUiJ9.fA7iVHKMVCUyU4FL00ztUAT8RlsqenYTpJdMAcX0Lhk

<> <a href="/scratches/2023-07-16T124054.200.json">2023-07-16T124054.200.json</a>

###
GET http://localhost:8085/customers
Accept: application/json
Authorization: Bearer eyJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1c2VyIiwiZXhwIjoxNjg5NTA4MTIwLCJpYXQiOjE2ODk1MDc1MjAsInNjb3BlIjoiVVNFUiJ9.fA7iVHKMVCUyU4FL00ztUAT8RlsqenYTpJdMAcX0Lhk

<> <a href="/scratches/2023-07-16T124714.200.json">2023-07-16T124714.200.json</a>

###
POST http://localhost:8085/customers
Content-Type: application/json
Authorization: Bearer eyJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJhZG1pbiIsImV4cCI6MTY4OTUwODgzMiwiaWF0IjoxNjg5NTA4MjMyLCJzY29wZSI6IkFETUlOIFVTRVIifQ.85Qg5kclHAP1ou4jFKMXxTafODx93K8fKpWfPUOFD9Y

{
   "name": "Elmehdi", "email": "elmehdiamlou@gmail.com"
}

<> <a href="/scratches/2023-07-16T125304.200.json">2023-07-16T125304.200.json</a>
</pre>
