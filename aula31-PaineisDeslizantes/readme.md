# PAINEIS DESLIZANTES

Painel na Esquerda
```
<div class="offcanvas offcanvas-start show" id="painel" tabindex="-1"></div>
```

Painel na direita (offcanvas-end)
```
<div class="offcanvas offcanvas-end text-bg-info" id="painel" tabindex="-1" data-bs-scroll="true" data-bs-backdrop="static">
```

Painel em cima (offcanvas-top)
```
<div class="offcanvas offcanvas-top text-bg-info" id="painel" tabindex="-1" data-bs-scroll="true" data-bs-backdrop="static">
```

Painel em baixo (offcanvas-bottom)
```
<div class="offcanvas offcanvas-bottom text-bg-info" id="painel" tabindex="-1" data-bs-scroll="true" data-bs-backdrop="static">
```

Cabeçalho (offcanvas-header)
```
<div class="offcanvas-header"></div>
```

Corpo (offcanvas-body)
```
<div class="offcanvas-body"></div>
```

Titulo (offcanvas-title)
```
<h5 class="offcanvas-title">Painel</h5>
```

X para fechar 
```
<button class="btn-close" data-bs-dismiss="offcanvas"></button>
```

Obs. No corpo poderia por qualquer coisa

Abrir o painel com botão
```
<nav class="navbar bg-dark navbar-dark">
    <div class="container">
        <a href="" class="navbar-brand">OffCanvas</a>
        <div>
            <button class="btn btn-primary" data-bs-toggle="offcanvas" data-bs-target="#painel">Painel</button>
        </div>
    </div>
</nav>
<div class="offcanvas offcanvas-start" id="painel" tabindex="-1">
    <div class="offcanvas-header">
        <h5 class="offcanvas-title">Painel</h5>
        <button class="btn-close" data-bs-dismiss="offcanvas"></button>
    </div>
    <div class="offcanvas-body"></div>
</div>
```

Abrir painel com link
```
<nav class="navbar bg-dark navbar-dark">
    <div class="container">
        <a href="" class="navbar-brand">OffCanvas</a>
        <div>
            <button class="btn btn-primary" data-bs-toggle="offcanvas" data-bs-target="#painel">Painel</button>
            <a href="#painel" class="btn btn-success" data-bs-toggle="offcanvas">Painel</a>
        </div>
    </div>
</nav>
<div class="offcanvas offcanvas-start" id="painel" tabindex="-1">
    <div class="offcanvas-header">
        <h5 class="offcanvas-title">Painel</h5>
        <button class="btn-close" data-bs-dismiss="offcanvas"></button>
    </div>
    <div class="offcanvas-body"></div>
</div>
```

Conseguir descer o conteudo mesmo com o painel aberto (data-bs-scroll="true")
```
<div class="offcanvas offcanvas-start" id="painel" tabindex="-1" data-bs-scroll="true">
```

Tirar o cinza do backdrop (data-bs-backdrop="false")
```
<div class="offcanvas offcanvas-start" id="painel" tabindex="-1" data-bs-scroll="true">
```

Deixar o backdrop fixo, só saindo se clicar no X (data-bs-backdrop="static")
```
<div class="offcanvas offcanvas-start" id="painel" tabindex="-1" data-bs-scroll="true" data-bs-backdrop="static">
```

Colocar cor (text-bg-info)
```
<div class="offcanvas offcanvas-start text-bg-info" id="painel" tabindex="-1" data-bs-scroll="true" data-bs-backdrop="static">
```

Alterar a largura (style="--bs-offcanvas-width:120px;")
```
<div class="offcanvas offcanvas-start text-bg-info" id="painel" tabindex="-1" data-bs-scroll="true" data-bs-backdrop="static" style="--bs-offcanvas-width:120px;">
```