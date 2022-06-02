# JAVA REST-API-Spring-boot

**Full project structure**

![Project Structure](https://user-images.githubusercontent.com/20375942/171577456-dfd11d8f-e732-4b70-b59f-19e6a3a21ca7.png)


**Send data as JSON**

[request] (http://localhost:8084/api/user)

``{
    "id": 7,
    "name": "Tiger"
}``

**Response**

``
{
    "id": 6,
    "name": "Tiger"
}
``

**Postman request-response**

![POST method](https://user-images.githubusercontent.com/20375942/171575689-31cfe084-8d0d-4f46-8726-4447eeff1f93.png)


**Get data as JSON - Response**
[request] (http://localhost:8084/api/user)
``
{
    "id": 6,
    "name": "Tiger"
}
``

**Postman request for all entry-> response**

![Get method](https://user-images.githubusercontent.com/20375942/171573779-e5b18094-e574-4ac8-af10-3ea451dfc5fa.png)


**Get data as JSON - Response**
[request] (http://localhost:8084/api/user/1)
``
{
    "id": 6,
    "name": "Tiger"
}
``

**Postman request for single entry-> response**

![Get single user](https://user-images.githubusercontent.com/20375942/171574120-550ac435-8a92-4e31-9ea6-3ee85ed243c1.png)


