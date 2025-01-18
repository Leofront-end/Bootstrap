# AGRUPAMENTO DE BOTÕES E MENUS FLUTUANTES
## Agrupamento de Botões
Todo agrupamento de botões fica dentro do (btn-group)
```
<div class="btn-group">
    <button class="btn btn-primary">Botão 1</button>
    <button class="btn btn-primary">Botão 2</button>
    <button class="btn btn-primary">Botão 3</button>
</div>
```

Se for exclusivos 
```
<div class="btn-group">
    <input type="radio" name="grupo" id="btn1" class="btn-check">
    <label for="btn1" class="btn btn-outline-primary">Botão de Checagem 1</label>
    <input type="radio" name="grupo" id="btn2" class="btn-check">
    <label for="btn2" class="btn btn-outline-primary">Botão de Checagem 2</label>
    <input type="radio" name="grupo" id="btn3" class="btn-check">
    <label for="btn3" class="btn btn-outline-primary">Botão de Checagem 3</label>
</div>
```

Se não forem exclusivos
```
<div class="btn-group">
    <input type="checkbox" id="btn1" class="btn-check">
    <label for="btn1" class="btn btn-outline-primary">Botão de Checagem 1</label>
    <input type="checkbox" id="btn2" class="btn-check">
    <label for="btn2" class="btn btn-outline-primary">Botão de Checagem 2</label>
    <input type="checkbox" id="btn3" class="btn-check">
    <label for="btn3" class="btn btn-outline-primary">Botão de Checagem 3</label>
</div>
```

Agrupamento com icones
```
<div class="btn-group me-2">
    <button class="btn btn-primary">
        <i class="bi-folder2-open"></i>
    </button>
    <button class="btn btn-primary">
        <i class="bi-save"></i>
    </button>
    <button class="btn btn-primary">
        <i class="bi-paperclip"></i>
    </button>
    <button class="btn btn-primary">
        <i class="bi-image"></i>
    </button>
</div>
```

Campo de busca com botão
```
<div class="input-group">
    <input type="search" name="" id="" class="form-control">
    <button class="btn btn-primary">
        <i class="bi-search"></i>
    </button>
</div>
```

## Menu flutuante
Sub Menus
```
<div class="dropdown">
    <button class="btn btn-secondary dropdown-toggle" data-bs-toggle="dropdown">Submenus</button>
    <ul class="dropdown-menu">
        <li>
            <a href="#" class="dropdown-item">Submenu 1</a>
        </li>
        <li>
            <a href="#" class="dropdown-item">Submenu 2</a>
        </li>
        <li>
            <a href="#" class="dropdown-item">Submenu 3</a>
        </li>
    </ul>
</div>
```