# ALERTA, BADGES E LISTAS
## Alerta
Alerta simples (alert alert-primary)
```
<div class="container py-5">
    <div class="alert alert-primary">Este é um alerta simples</div>
</div>
```

link de alerta (alert-link)
```
<a href="#" class="alert-link">Clique Aqui!</a>
```

titulo de alerta (alert-heading)
```
            <h4 class="alert-heading"><i class="bi-info-circle"></i> Informação</h4>
```

Criar X para fechar o alerta (alert-dismissible btn-close)
```
<div class="alert alert-primary alert-dismissible">
    <h4 class="alert-heading"><i class="bi-info-circle"></i> Informação</h4>
    <p>Este é um alerta simples</p>
    <button class="btn-close" data-bs-dismiss="alert"></button>
    <a href="#" class="alert-link">Clique Aqui!</a>
</div>
```

Fechar de maneira mais suave (fade show)
```
    <div class="alert alert-primary alert-dismissible fade show">
```

## Badges

Criar uma caixa ao redor da frase (badge bg-secondary)
```
<h2>Exemplo de texto em cápsula
    <span class="badge bg-secondary">Novo</span>
</h2>
```

Botão de notificação com número
```
<button class="btn btn-primary position-relative">Notificações
    <span class="badge text-bg-danger position-absolute top-0 start-100 translate-middle rounded-pill">8</span>
</button>
```

Botão de notificação sem o número
```
<button class="btn btn-primary position-relative ms-4">Notificações
    <span class="badge text-bg-danger position-absolute top-0 start-100 translate-middle rounded-circle p-2 border border-light"> </span>
</button>
```

## Listas de agrupamentos
Lista 
```
<div class="list-group">
    <li class="list-group-item">Item 1</li>
    <li class="list-group-item">Item 2</li>
    <li class="list-group-item">Item 3</li>
    <li class="list-group-item">Item 4</li>
    <li class="list-group-item">Item 5</li>
</div>
```

Item abilitado (active)
```
<li class="list-group-item active">Item 1</li>
```

Item desabilitado (disabled)
```
<li class="list-group-item disabled">Item 4</li>
```

Lista de item com links
```
<div class="list-group">
    <a href="#" class="list-group-item list-group-item-action">Link 1</a>
    <a href="#" class="list-group-item list-group-item-action">Link 2</a>
    <a href="#" class="list-group-item list-group-item-action">Link 3</a>
    <a href="#" class="list-group-item list-group-item-action">Link 4</a>
    <a href="#" class="list-group-item list-group-item-action">Link 5</a>
</div>
```

Lista de item com botões
```
<div class="list-group">
    <button class="list-group-item list-group-item-action">Botão 1</button>
    <button class="list-group-item list-group-item-action">Botão 2</button>
    <button class="list-group-item list-group-item-action">Botão 3</button>
    <button class="list-group-item list-group-item-action">Botão 4</button>
    <button class="list-group-item list-group-item-action">Botão 5</button>
</div>
```

Apenas as linhas de dentro (list-group-flush)
```
<div class="list-group list-group-flush">
```

Lista de items com numeros
```
<ol class="list-group list-group-numbered">
    <li class="list-group-item">Item 1</li>
    <li class="list-group-item">Item 2</li>
    <li class="list-group-item">Item 3</li>
    <li class="list-group-item">Item 4</li>
    <li class="list-group-item">Item 5</li>
</ol>
```

Tematico
```
<div class="list-group">
    <a href="#" class="list-group-item list-group-item-action">
        <div class="d-flex w-100 justify-content-between">
            <h5 class="mb-1">Título da Noticia</h5>
            <small>5 dias atras</small>
        </div>
        <p class="mb-1">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Assumenda, in commodi cumque quas laboriosam repellat autem dolor? Dolores, ratione animi?</p>
        <small class="text-muted">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Tenetur, est?</small>
    </a>
    <a href="#" class="list-group-item list-group-item-action">
        <div class="d-flex w-100 justify-content-between">
            <h5 class="mb-1">Título da Noticia</h5>
            <small>5 dias atras</small>
        </div>
        <p class="mb-1">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Assumenda, in commodi cumque quas laboriosam repellat autem dolor? Dolores, ratione animi?</p>
        <small class="text-muted">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Tenetur, est?</small>
    </a>
    <a href="#" class="list-group-item list-group-item-action">
        <div class="d-flex w-100 justify-content-between">
            <h5 class="mb-1">Título da Noticia</h5>
            <small>5 dias atras</small>
        </div>
        <p class="mb-1">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Assumenda, in commodi cumque quas laboriosam repellat autem dolor? Dolores, ratione animi?</p>
        <small class="text-muted">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Tenetur, est?</small>
    </a>
    <a href="#" class="list-group-item list-group-item-action">
        <div class="d-flex w-100 justify-content-between">
            <h5 class="mb-1">Título da Noticia</h5>
            <small>5 dias atras</small>
        </div>
        <p class="mb-1">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Assumenda, in commodi cumque quas laboriosam repellat autem dolor? Dolores, ratione animi?</p>
        <small class="text-muted">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Tenetur, est?</small>
    </a>
</div>
```

Colocando cor (list-group-item-warning)
```
<a href="#" class="list-group-item list-group-item-action list-group-item-warning">
    <div class="d-flex w-100 justify-content-between">
        <h5 class="mb-1">Título da Noticia</h5>
        <small>5 dias atras</small>
    </div>
    <p class="mb-1">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Assumenda, in commodi cumque quas laboriosam repellat autem dolor? Dolores, ratione animi?</p>
    <small class="text-muted">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Tenetur, est?</small>
</a>
```