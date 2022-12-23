<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="exercicio4.css">
    </head>
<body>
<div class="container">
    <header>
        <nav>
            <div class="menu">
                <div class="menu_gmail">
                    Gmail
                </div>
                <div class="menu_imagens">
                    Imagens
                </div>
                <div class="menu_icon">
                   <img src="https://icon-library.com/images/app-menu-icon/app-menu-icon-10.jpg">
                </div>
                <div class="menu_login">
                    <button>Fazer login</button>
                </div>
        </nav>
    </header>
    </div>
    <div class="meio">
        <div class="image">
            <img src="images/google.png">
        </div>
        <div class="pesquisa">
                <div class="pesquisa_parte1">
            <div class="lupa">
                <img src="images/google_lupa.png">
            </div>
            </div>
            <div class="pesquisa_parte2">
            <div class="teclado">
                <img src="images/google_teclado.png">
            </div>
            <div class="microfone">
                <img src="images/google_microfone.png">
            </div>
            <div class="camera">
                <img src="images/google_camera.png">
            </div>
            </div>
        </div>
        <div class="meio_fim">
            <div class="pesquisa_google">
            <button class="button_pesquisa">Pesquisa Google</button>
        </div>
            <div class="google_sorte">
                <button class="button_sorte">Estou com sorte</button>
            </div>
        </div>
    </div>
        <footer class="footer">
                <div class="pais">
                    Brasil
                </div>
                <div class="ultima_linha">
                    <div class="parte1">
                        <ul>
                            <li><a href="">Sobre</a></li>
                            <li><a href="">Publicidade</a></li>
                            <li><a href="">Negócios</a></li>
                            <li><a href="">Como funciona a Pesquisa</a></li>
                        </ul>
                    </div>
                    <div class="parte2">
                        <ul>
                            <li><a href="">Privacidade</a></li>
                            <li><a href="">Termos</a></li>
                            <li><a href="">Configurações</a></li>
                        </ul>
                    </div>
                </div>
            </div>
        </footer>
</div>



</body>    
</html>


* {
    font-family: arial;
}
body {
    background-color: #2c2c2c;
    margin: 0;
    padding: 0;
}
.container {
    margin: 0;
    padding: 10px;
}
.menu {
    display: flex;
    justify-content: flex-end;
}
.menu_gmail {
    color: white;
    margin-right: 15px;
    margin-top: 8px;
}
.menu_imagens {
    color: white;
    margin-right: 15px;
    margin-top: 8px;
}
.menu_icon {
    margin-right: 15px;
    margin-top: 5px;
}
.menu_icon img {
    height: 25px;
}
.menu_icon img:hover {
    cursor: pointer;
    box-shadow: #6c6c6c 20px;
}
.menu_login {
    margin-right: 15px;
}
.menu_login button {
    color: white;
    background-color: rgb(58, 58, 204);
    padding: 10px;
    padding-left: 15px;
    padding-right: 15px;
    border-radius: 5px;
    border: none;
}
.menu_login button:hover {
    cursor: pointer;
    background-color: rgb(24, 24, 206);
}
.meio {
    display: flex;
    justify-content: center;
    flex-direction: column;
    align-items: center;
    margin-top: 100px;
}
.pesquisa {
    border: 1px solid #9c9c9c;
    border-radius: 25px;
    width: 600px;
    height: 50px;
    margin-top: 20px;
    display: flex;
    justify-content: space-between;
}
.pesquisa:hover {
    cursor: pointer;
    border: none;
    background-color: #6c6c6c;
}
.lupa img {
    margin-left: 13px;
    margin-top: 18px;
    height: 20px;
}
.teclado img {
    height: 30px;
    margin-right: 13px;
}
.microfone img {
    height: 30px;
    margin-right: 13px;
}
.camera img {
    height: 30px;
}
.pesquisa_parte2 {
    display: flex;
    justify-content: flex-end;
    margin-top: 12px;
    margin-right: 15px;
}
.meio_fim {
    display: flex;
    justify-content: space-around;
    margin-top: 30px;
}
.pesquisa_google {
margin-right: 7px;
}
.pesquisa_google button {
    background-color: #6c6c6c;
    color: white;
    font-size: 15px;
    border: none;
    border-radius: 5px;
    padding: 12px;
    padding-left: 25px;
    padding-right: 25px;
}
.pesquisa_google button:hover {
    cursor: pointer;
    border: 1px solid white;
}
.google_sorte {
    margin-left: 7px;
}
.google_sorte button {
    background-color: #6c6c6c;
    color: white;
    font-size: 15px;
    border: none;
    border-radius: 5px;
    padding: 12px;
    padding-left: 25px;
    padding-right: 25px;
}
.google_sorte button:hover {
    cursor: pointer;
    border: 1px solid white;
}
footer {
    position: absolute;
    bottom: 0;
    width: 100%;
    background-color: #1b1b1b;
}
.pais {
    font-size: 14px;
    color: white;
    padding: 10px 30px;
    border-bottom: 1px solid #dadce0;
}
.ultima_linha {
    font-size: 14px;
    display: flex;
    justify-content: space-between;
}
footer ul, footer li {
    list-style: none;
    padding-right: 30px;
}
footer a {
    text-decoration: none;
    color: white;
}
.parte1 ul {
    display: flex;
    justify-content: space-around;
}
.parte2 ul {
    display: flex;
    justify-content: space-around;
}
