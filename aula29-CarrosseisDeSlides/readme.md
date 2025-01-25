# CARROSEL DE SLIDES

Carrosel
```
<div class="container py-5">
    <div class="carousel slide" data-bs-ride="carousel">
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img src="https://picsum.photos/1280/420?random=1" alt="" class="d-block w-100">
            </div>
            <div class="carousel-item">
                <img src="https://picsum.photos/1280/420?random=2" alt="" class="d-block w-100">
            </div>
            <div class="carousel-item">
                <img src="https://picsum.photos/1280/420?random=3" alt="" class="d-block w-100">
            </div>
        </div>
    </div>
</div>
```

Botão de voltar 
```
<div class="carousel slide" data-bs-ride="carousel" id="ads">
    <div class="carousel-inner">
        <div class="carousel-item active">
            <img src="https://picsum.photos/1280/420?random=1" alt="" class="d-block w-100">
        </div>
        <div class="carousel-item">
            <img src="https://picsum.photos/1280/420?random=2" alt="" class="d-block w-100">
        </div>
        <div class="carousel-item">
            <img src="https://picsum.photos/1280/420?random=3" alt="" class="d-block w-100">
        </div>
    </div>
    <button class="carousel-control-prev" data-bs-target="#ads" data-bs-slide="prev">
        <span class="carousel-control-prev-icon"></span>
    </button>
</div>
```

Botão de Passar
```
<button class="carousel-control-next" data-bs-target="#ads" data-bs-slide="next">
    <span class="carousel-control-next-icon"></span>
</button>
```

Botões de indicadores
```
<div class="carousel-indicators">
    <button class="active" data-bs-target="#ads" data-bs-slide-to="0"></button>
    <button class="" data-bs-target="#ads" data-bs-slide-to="1"></button>
    <button class="" data-bs-target="#ads" data-bs-slide-to="2"></button>
</div>
```

Por texto no carrosel
```
<div class="carousel-item active">
    <img src="https://picsum.photos/1280/420?random=1" alt="" class="d-block w-100">
    <div class="carousel-caption d-none d-md-block">
        <h5>Titulo do slide 1</h5>
        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Culpa asperiores quidem impedit rerum placeat architecto dolorem non in eveniet! Fuga molestiae alias nostrum illum quam est dolore veniam provident modi.</p>
    </div>
</div>
```

Colocar uma transição de sumindo e aparecendo (carousel-fade)
```
<div class="carousel slide carousel-fade" data-bs-ride="carousel" id="ads">
```

Colocar tempo que ira aparecer o slide e mostrar o proximo em milisegundos (data-bs-interval="3000")
```
<div class="carousel-item active" data-bs-interval="3000">
```

Desativar passar por touch (data-bs-touch="false")
```
<div class="carousel slide carousel-fade" data-bs-ride="carousel" id="ads" data-bs-touch="false">
```

Deixar o carrosel escuro (carousel-dark)
```
<div class="carousel slide carousel-fade carousel-dark" data-bs-ride="carousel" id="ads" >
```