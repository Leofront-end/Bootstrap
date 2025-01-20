# BARRAS DE NAVEGAÇÃO
Colocar a logo (navbar-brand)
```
<a href="" class="navbar-brand">Bootstrap 5</a>
```

Deixar alinhado verticalmente (d-flex align-items-center)
```
<a href="" class="navbar-brand d-flex align-items-center">
```

Colocar texto a direita (navbar-text)
```
<span class="navbar-text">Curso Completo</span>
```

Links na barra de navegação / Colocar também o (navbar-expand-sm) para aparecer
```
<div class="collapse navbar-collapse">
    <div class="navbar-nav">
        <a href="#" class="nav-link">Principal</a>
        <a href="#" class="nav-link">Produtos</a>
        <a href="#" class="nav-link">Contatos</a>
        <a href="#" class="nav-link">Sobre</a>
    </div>
</div>
```
```
<nav class="navbar bg-light navbar-expand-sm">
```

Deixar mais escuro para mostrar que está ativo (active)
```
<a href="#" class="nav-link active">Principal</a>
```

Deixar desativado (disabled)
```
<a href="#" class="nav-link disabled">Sobre</a>
```

Menu hamburguer A div é o conteudo e o button é o botão do hamburguer
```
<button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#menuNavbar">
    <span class="navbar-toggler-icon"></span>
</button>
<div class="collapse navbar-collapse" id="menuNavbar">
    <div class="navbar-nav">
        <a href="#" class="nav-link active">Principal</a>
        <a href="#" class="nav-link">Produtos</a>
        <a href="#" class="nav-link">Contatos</a>
        <a href="#" class="nav-link disabled">Sobre</a>
    </div>
</div>
```

Buscar
```
<form action="" class="d-flex">
    <div class="input-group">
        <input type="search" name="" id="" class="form-control" placeholder="Buscar...">
        <button type="submit" class="btn btn-outline-success">Buscar</button>
    </div>
</form>
```

Menu dropdown 
```
<div class="dropdown">
    <a href="#" class="nav-link dropdown-toggle" data-bs-toggle="dropdown">Produtos</a>
    <ul class="dropdown-menu">
        <li>
            <a href="#" class="dropdown-item">Produto 1</a>
        </li>
        <li>
            <a href="#" class="dropdown-item">Produto 2</a>
        </li>
        <li>
            <a href="#" class="dropdown-item">Produto 3</a>
        </li>
        <li>
            <a href="#" class="dropdown-item">Produto 4</a>
        </li>
        <li>
            <a href="#" class="dropdown-item">Produto 5</a>
        </li>
    </ul>
</div>
```

Colocar a navbar escura (bg-dark navbar-dark)
```
<nav class="navbar bg-dark navbar-dark navbar-expand-sm">
```

Alinhar a direita os links (ms-auto)
```
<div class="navbar-nav ms-auto">
```

Alinhar os submenus no final do dropdown (dropdown-menu-end)
```
<ul class="dropdown-menu dropdown-menu-end">
```

Aumentar o tamanho verticalmente (py-2)
```
<nav class="navbar bg-dark navbar-dark navbar-expand-sm py-2">
```

Deixar a nav fixado no topo (sticky-top)
```
<nav class="navbar bg-dark navbar-dark navbar-expand-sm py-2 sticky-top">
```

Deixar o footer fixado em baixo (sticky-bottom)
```
<footer class="p-4 bg-dark text-light text-center sticky-bottom">Todos os direitos reservados</footer>
```

Caso o conteudo seja pouco (fixed-bottom)
```
    <footer class="p-4 bg-dark text-light text-center fixed-bottom">Todos os direitos reservados</footer>
```