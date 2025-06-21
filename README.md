# Fundamentos do JavaScript Clássico

## INTEGRAÇÕES

### Integrar JavaScript de forma interna 

~~~ html
./index.html

    <!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JavaScript</title>   
</head>
<body>
    

    <script>
        console.log("Helo World!");
    </script>
</body>
</html>
~~~

### Integrar JavaScript de forma externa

- Criar diretório ***src*** na raiz do projeto
- Criar arquivo ***script.js*** na raiz do diretório ***src***
- Integrar de forma externa o arquivo ***script*** no arquivo ***index.html***

~~~ html
./index.html

    <!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JavaScript</title>   
</head>
<body>
    
    <script src="./src/script.js"></script>
</body>
</html>
~~~

## COMENTÁRIOS

### Comentário de linha

~~~ javascript

// comentário de linha

~~~

### Comentário de bloco simples

~~~ javascript

// comentário de bloco simples

~~~

### Comentário de bloco com marcadores

~~~ javascript

// comentário de bloco com marcadore

~~~