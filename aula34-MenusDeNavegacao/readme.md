# MENUS DE NAVEGAÇÃO

Menus com link 
```
<ul class="nav">
    <li class="nav-item">
        <a href="#1" class="nav-link">Link 1</a>
    </li>
    <li class="nav-item">
        <a href="#2" class="nav-link">Link 2</a>
    </li>
    <li class="nav-item">
        <a href="#3" class="nav-link">Link 3</a>
    </li>
    <li class="nav-item">
        <a href="#4" class="nav-link">Link 4</a>
    </li>
</ul>
```

Mostrar o link que está na pagina (active)
```
<a href="#1" class="nav-link active">Link 1</a>
```

Mostrar o link desativo (disabled)
```
<a href="#4" class="nav-link disabled">Link 4</a>
```

Igual ao anterior
```
<nav class="nav">
    <a href="#1" class="nav-link">Link 1</a>
    <a href="#2" class="nav-link">Link 2</a>
    <a href="#3" class="nav-link">Link 3</a>
    <a href="#4" class="nav-link">Link 4</a>
</nav>
```

Deixar empilhado na vertical (flex-column)
```
<nav class="nav flex-column">
```

Se parecer com uma guia/aba (nav-tabs)
```
<nav class="nav nav-tabs">
    <a href="#1" class="nav-link active">Link 1</a>
    <a href="#2" class="nav-link">Link 2</a>
    <a href="#3" class="nav-link">Link 3</a>
    <a href="#4" class="nav-link disabled">Link 4</a>
</nav>
```

O item ativo se parece com um botão (nav-pills)
```
<nav class="nav nav-pills">
    <a href="#1" class="nav-link active">Link 1</a>
    <a href="#2" class="nav-link">Link 2</a>
    <a href="#3" class="nav-link">Link 3</a>
    <a href="#4" class="nav-link disabled">Link 4</a>
</nav>
```

O item ativo com uma linha em baixo e em negrito (nav-underline)
```
<nav class="nav nav-underline">
    <a href="#1" class="nav-link active">Link 1</a>
    <a href="#2" class="nav-link">Link 2</a>
    <a href="#3" class="nav-link">Link 3</a>
    <a href="#4" class="nav-link disabled">Link 4</a>
</nav>
```

Alinhar no centro (justify-content-center)
```
<nav class="nav nav-underline justify-content-center">
    <a href="#1" class="nav-link active">Link 1</a>
    <a href="#2" class="nav-link">Link 2</a>
    <a href="#3" class="nav-link">Link 3</a>
    <a href="#4" class="nav-link disabled">Link 4</a>
</nav>
```

Alinhar no final (justify-content-end)
```
<nav class="nav nav-underline justify-content-end">
    <a href="#1" class="nav-link active">Link 1</a>
    <a href="#2" class="nav-link">Link 2</a>
    <a href="#3" class="nav-link">Link 3</a>
    <a href="#4" class="nav-link disabled">Link 4</a>
</nav>
```

Oculpar a largura inteira do elemento pai (nav-fill)
```
<nav class="nav nav-underline nav-fill">
    <a href="#1" class="nav-link active">Link 1</a>
    <a href="#2" class="nav-link">Link 2</a>
    <a href="#3" class="nav-link">Link 3</a>
    <a href="#4" class="nav-link disabled">Link 4</a>
</nav>
```

Deixar divido igualmente o tamanho de cada um (nav-justified)
```
<nav class="nav nav-underline nav-justified">
    <a href="#1" class="nav-link active">Link 1</a>
    <a href="#2" class="nav-link">Link 2</a>
    <a href="#3" class="nav-link">Link 3</a>
    <a href="#4" class="nav-link disabled">Link 4</a>
</nav>