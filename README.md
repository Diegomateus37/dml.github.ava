# dml.github.ava

<!DOCTYPE html>

<html lang="pt-br">


<style>
    

    body {
        padding: 0;
        margin: 0;
        background-color: #181818!important;
    }

    #login {
        display: flex;
        align-items: center;
        justify-content: center;
        height: 100vh;
        font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    }

    .card {
        background-color: #fff;
        padding: 50px;
        border-radius: 20px;
        width:450px;
        height: 300px;
    }

    .card-header {
        padding-bottom: 60px;
        opacity: 0.8;
        color: #000000;
        margin-left: auto;
        margin-right: 10px;
        width: 11em;
        margin-top: -100px;
        
    }

    .card-header::after {
        content: "";
        width: 70px;
        height: 1px;
        background-color: #000000;
        display: block;
        margin-top: -17px;
        margin-left: -5px;

    }

    .card-content label {
        color: #000000;
        font-size: 13px;
        opacity: 0.8;
        display: flex;
        width: 3px;
    }

    .card-content-area-img {
        display: table-column;
        flex-direction: column;
        padding:10px 0;
        display: flex;
        text-align:justify;
        margin-left: 1px;
        margin-right: auto;
        width: 13em;
        height: 1em;
        margin-top: 70px;
    }

    .card-content-area {
        display: table-column;
        flex-direction: row;
        padding:10px 10px;
        display: flex;
        text-align: justify;
        margin-left: auto;
        margin-right: 2px;
        width: 11em;
        height: 2em;
        margin-top: -10px;
    }

    .card-content-area input {
        margin-top: 15px;
        padding:5px 10px;
        background-color: transparent;
        border:none;
        border-bottom: 1px solid #e1e1e1;
        outline: none;
        color: #000000;
    }

    .card-footer {
        display: flex;
        flex-direction: column;
        width: 28em;
        margin-top: 20px;
        marker-mid: 20px;
    }

    .card-footer .submit{
        width: 100%;
        height: 35px;
        background-color: #181818!important;
        border:none;
        color:#e1e1e1;
        margin: 30px 0;
        margin-left: auto;
        margin-right: -15px;
        width: 15em;
        margin-top: -5px;
    }

    .card-footer a {
        text-align: right;
        font-size: 11px;
        opacity: 0.8;
        color: #000000;
        text-decoration: none;
        margin-left: auto;
        margin-right: 95px;
        width: 15em;
        margin-top: -20px;
        marker-mid: 20px;
    }

</style>

    <head>

        <meta charset="UTF-8">

        <meta http-equiv="X-UA-Compatible" content="IE=edge">

        <meta name="viewport"content="width=device-width, initial-scale=1.0">

        <link rel="stylesheet" href="style.css">

        <title>Login</title>

    </head>

    <body>

        <div id="login">

            <form class="card">

                

                <div class="card-content">

                	<div class="card-content-area-img">
                		<img src="https://img.freepik.com/vetores-gratis/programador-trabalhando-em-codigo-de-desenvolvimento-web-engenheiro-de-programacao-em-python-php-e-java-script-no-computador_90220-249.jpg?w=740&t=st=1667415796~exp=1667416396~hmac=2657aaa96065684f2ccd916a79176aeed855fce9e71d7b1e48a63e6131120c03">
                	</div>

                	<div class="card-header">

                    	<h2>Login</h2>

                	</div>
                    <div class="card-content-area">

                        <label for="usuario">Usuário</label>

                        <input type="text" id="usuario" autocomplete="off">

                    </div>

                    <div class="card-content-area">

                        <label for="password">Senha</label>

                        <input type="password" id="password" autocomplete="off">

                    </div>

                </div>

                <div class="card-footer">

                    <input type="submit" value="Login" class="submit">

                    <a href="#" class="recuperar_senha">Esqueceu a senha?</a>

                </div>

            </form>

        </div>

    </body>

</html>
