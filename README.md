# api-serverless-aws

## Despliegue de endpoints

Actualice las dependencias 
```sh
npm install
```

Instalación de serverless 
```sh
npm install serverless -g
```

Configuración de usuario AWS 
(url: https://www.serverless.com/framework/docs/providers/aws/guide/credentials/)
```sh
serverless config credentials --provider aws --key AKIAZZC4UEFHBZVIMBMF --secret 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
```

Despliegue
```sh
serverless deploy
```

Star Wars API
```sh
https://swapi.dev/
```


## Funciones AWS Lambda
Revisar archivo docs/Manual de uso

- Agregar empleado
https://vu65b71shj.execute-api.us-east-1.amazonaws.com/dev/api/employee/add 

- Modificar empleado
https://vu65b71shj.execute-api.us-east-1.amazonaws.com/dev/api/employee/upd

- Recuperar empleado
https://vu65b71shj.execute-api.us-east-1.amazonaws.com/dev/api/employee/get/{employee_id}

- Recuperar recursos
https://vu65b71shj.execute-api.us-east-1.amazonaws.com/dev/api/starwars/{resource} 

- Recuperar recurso especifico
https://vu65b71shj.execute-api.us-east-1.amazonaws.com/dev/api/starwars/{resource}/{idOrSchema}
