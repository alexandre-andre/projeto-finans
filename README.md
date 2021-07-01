Descrevendo o site

Header

Dentro do header criamos uma unica nav divida em duas partes: logo e navegacao.

parte 1
<a>logo com a imagem do logo


Para haver responsividade (criamos o hamburguer, lembrando q na nav colocamos navbar-expand-sm)
<button class=navbar-toggler data-toggle=collapse data-target=#+id que será colapsada>
<span class=navbar-toggler-icon>

parte 2
<div class=collapse navbar-collapse id=<...>> 
<ul class=ml-auto>

    <nav class="navbar navbar-expand-sm navbar-light bg-warning">

            <div class="container">

                <a href="#" class="navbar-brand">
                    <img src="img/logo.png" width="142">
                </a>

                <button class="navbar-toggler" data-toggle="collapse" data-target="#nav-principal">
                    <span class="navbar-toggler-icon"></span>
                </button>

                <div class="collapse navbar-collapse" id="nav-principal">
                    <ul class="navbar-nav ml-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Recusros</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="">Beneficios</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="">Precos</a>
                    </li>
                    <li class="nav-item">
                        <a class="btn btn-outline-light" href="#">Entrar</a>
                    </li>
                    </ul>
                </div>

            </div>

    </nav>

