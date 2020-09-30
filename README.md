#Delilah Resto

<h1>dsdsa</h1>
<p>Hola mundo </p>


#EndPoints
<p>Agregar usuario</p>
<p>// El role del user puede ser ADMIN | USER </p>
```
    [POST] /user/add
    {
        "USER_NAME": "",
        "FULL_NAME": "",
        "EMAIL": "",
        "PHONE_COUNTRY_CODE": "",
        "PHONE_NUMBER": "",
        "ADDRESS": "",
        "PASSWORD": "",
        "ROLE": "" 
    }
```

```
    [RESPUESTA] 
    {
        "fieldCount": 0,
        "affectedRows": 1,
        "insertId": 15,
        "info": "",
        "serverStatus": 2,
        "warningStatus": 0
    }
```