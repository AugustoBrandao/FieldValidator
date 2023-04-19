# Comandos
``````
1- npm init                                     //gerar o package.json
2- npm install validator                        //instalar biblioteca validator
3- npm install cpf                              //instalar biblioteca cpf
4- npx vite                                     //executar o Vite
5- npm install @trybe/eslint-config-frontend    //instalando o ESLint da Trybe
``````

## Configurando Package.json 
`````
    "scripts": {
        "test": "echo \"Error: no test specified\" && exit 1",
        "dev": "npx vite --open",                               // npm run dev
        "lint": "eslint ./src"                                  // npm run lint
    },
`````

## Crie o arquivo .eslintrc.json e coloque:
`````
    {
        "extends" : "@trybe/eslint-config-frontend"
    }
`````

## Crie o arquivo .gitignore

`````
node_modules/
