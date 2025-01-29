# COMPONENTES SIMPLES
## Caminhos
Indicador de caminho de 3 nivieis
```
<div class="container my-5">
    <nav class="breadcrumb">
        <li class="breadcrumb-item">
            <a href="#">Nivel 1</a>
        </li>
        <li class="breadcrumb-item">
            <a href="#">Nivel 2</a>
        </li>
        <li class="breadcrumb-item">
            <a href="#">Nivel 3</a>
        </li>
    </nav>
</div>
```

Mudar a / Para outra coisa (style="--bs-breadcrumb-divider: ' > '")
```
<nav class="breadcrumb" style="--bs-breadcrumb-divider: ' > '">
```

## Carregar
Indicador de carregamento (spinner-border)
```
<div class="spinner-border"></div>
```

Mudar a cor do carregamento (text-primary)
```
<div class="spinner-border text-primary"></div>
```

Pequeno (spinner-border-sm)
```
<div class="spinner-border text-primary spinner-border-sm"></div>
```

Grande (spinner-border-lg)
```
<div class="spinner-border text-primary spinner-border-lg"></div>
```

Spinner piscando
```
<div class="spinner-grow"></div>
```

## Barra de progresso
Barra de progresso
```
<div class="progress">
    <div class="progress-bar w-75">75%</div>
</div>
```

Mudar a cor (bg-dark)
```
<div class="progress-bar w-75 bg-dark">75%</div>
```

Barra de progresso separadas
```
<div class="progress">
    <div class="progress-bar w-25 bg-primary">25%</div>
    <div class="progress-bar w-25 bg-success">25%</div>
    <div class="progress-bar w-25 bg-danger">25%</div>
</div>
```

Barra de progresso listrada (bar-progress-striper)
```
<div class="progress-bar w-75 bg-dark progress-bar-striped">75%</div>
```

Animação da barra de progresso (bar-progress-animated)
```
<div class="progress-bar w-75 bg-dark progress-bar-striped progress-bar-animated">75%</div>
```

Configurar a altura (style="height:20px")
```
<div class="progress" style="height: 20px;">
```

## Botões de paginação
Os botões de pagina
```
<ul class="pagination">
    <li class="page-item">
        <a href="#" class="page-link">1</a>
    </li>
    <li class="page-item">
        <a href="#" class="page-link">2</a>
    </li>
    <li class="page-item">
        <a href="#" class="page-link">3</a>
    </li>
    <li class="page-item">
        <a href="#" class="page-link">4</a>
    </li>
    <li class="page-item">
        <a href="#" class="page-link">5</a>
    </li>
</ul>
```

Deixar um ativo (active)
```
<li class="page-item active">
```

Deixar desativo (disabled)
```
<li class="page-item disabled">
```

Deixar menor (pagination-sm)
```
<ul class="pagination pagination-sm">
```

Deixar maior (pagination-lg)
```
<ul class="pagination pagination-lg">
```

Deixar centralizado (justify-content-center)
```
<ul class="pagination justify-content-center">
```

Deixar no final (justify-content-end)
```
<ul class="pagination justify-content-end">
```

Botão que abre texto
```
<p>
    <button class="btn btn-primary" data-bs-toggle="collapse" data-bs-target="#painel">Mostrar</button>
</p>
<div class="collapse" id="painel">
    <p class="lead">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos magni maxime tempora impedit possimus adipisci ipsam, ea fugiat reiciendis voluptates officiis distinctio dolorem rem placeat corrupti iste. Animi asperiores provident eaque sunt consectetur labore dolorem aspernatur sed nulla omnis, ad est iusto, tempore voluptas possimus beatae, nemo laboriosam quis. Debitis in beatae est hic quidem cupiditate, et quis. Deleniti veritatis cumque corporis autem ipsa illum minus iste voluptatem accusamus iure dignissimos, sunt temporibus illo aut dolorem explicabo voluptatibus eaque facere itaque corrupti qui natus tenetur, laudantium a? Hic magni aperiam nemo doloribus veritatis iusto vel dolore distinctio. Molestias, eius fuga.</p>
</div>
```

Vir da esquerda para a direita (collapse-horizontal)
```
<div class="collapse collapse-horizontal" id="painel">
```