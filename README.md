# interdisciplinar
Trabalha Interdisciplinar ADS - 1º Semestre
<!doctype html>
<html lang="en">

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.1/css/bootstrap.min.css" integrity="sha384-WskhaSGFgHYWDcbwN70/dfYBj47jz9qbsMId/iRN3ewGhXQFZCSftd1LZCfmhktB"
        crossorigin="anonymous">
    <title>(Nome do Sistema)</title>
</head>

<script>
    function Cadastro() {
        location.href = "file:///C:/Users/opet/Documents/Interdisciplinar/Cadastro.html"
    }
    function Login() {
        var done = 0;
        var usuario = document.getElementsByName('usuario')[0].value;
        usuario = usuario.toLowerCase();
        var senha = document.getElementsByName('senha')[0].value;
        senha = senha.toLowerCase();
        if (usuario == "admin" && senha == "admin") {
            window.location = "file:///C:/Users/opet/Documents/Interdisciplinar/Inicio.html";
            done = 1;
        }
        if (done == 0) { alert("Dados incorretos, tente novamente"); }
    }
</script>

<style>
    .jumbotron {
        background-color: hsl(204, 100%, 49%)
    }

    h1 {
        color: white
    }

    p {
        color: white
    }
</style>

<body>
    <center>
        <div class="jumbotron jumbotron-fluid">
            <div class="container">
                <h1 class="display-4">Bem Vindo!</h1>
                <p class="lead">Entre ou Cadastre-se!</p>
            </div>
        </div>
    </center>
</body>

<body>
    <style>
        p.boxmodel2 {
            width: 300px;
            height: 150px;
            color: rgb(0, 0, 0);
            padding: 20px;
            border: 5px solid rgb(0, 0, 0);
        }
    </style>
    <center>
        <div class="col-md-3 mb-3">
            <div id="all">
                <div id="login-box">
                    <div id="login-inputs">
                        <input type="text" class="form-control" placeholder="Nome de usuário" name="usuario">
                        <br />
                        <input type="password" class="form-control" placeholder="Senha" name="senha">
                    </div>
                    <br>
                    <div id="enviar">
                        <input type="button" class="btn btn-primary" onclick="Login()" value="Login">
                        <a href="#">Esqueceu a sua senha?</a>
                    </div>
                </div>
            </div>
            <a href="file:///C:/Users/opet/Documents/Interdisciplinar/Cadastro.html" title="Pequena Descrição">Não possui login? Cadastre-se aqui</a>
    </center>
</body>
