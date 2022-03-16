# Tela-de-login
<!DOCTYPE html>

<html lang="pt-BR">
    <meta charset="UFT-8">
    <meta http-equiv="X-UA-compatible" content="IE-edge"> 
    <meta name="viewport" content="width=device-widht, initial-scale=1.0">
    <head>
        <title>Tela de login</title>
        <style>
            body{
                font-family: Arial, Helvetica, sans-serif;
                background-image: linear-gradient(45deg, cyan, yellow);
            }
            div{
                background-color: rgba(0, 0, 0, 0.9);
                position: absolute;
                top: 50%;
                left: 50%;
                transform: translate(-50%,-50%);
                padding: 80px;
                border-radius: 15px;
                color: #fff;
            }
            input{
                padding: 15px;
                border: none;
                outline: none;
                font-size: 15px;
            }
            button{
                background-color: dodgerblue;
                border: none;
                padding: 15px;
                width: 100%;
                border-radius: 10px;
                color: white;
                font-size: 15px;
                
            }
            button:hover{
                background-color: deepskyblue;
                cursor: pointer;
            }
        </style>
    </head>
            <div>
                <h1>Login</h1>
                <input type="text" placeholder="Nome">
                <br> <br>
                <input type="password" placeholder="Senha">
                <br><br>
                <button>Entrar</button>
            </div>


</html>
