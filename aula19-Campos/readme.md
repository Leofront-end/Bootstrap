# CAMPOS SELECT, RANGE E BOTÕES
## Select

Uso do select (form-select)
```
<select class="form-select">
```

Para diminur o tamanho é só envolver numa div (col-4)
```
<div class="col-4">
    <select class="form-select">
        <option value="">Opção 1</option>
        <option value="">Opção 2</option>
        <option value="">Opção 3</option>
        <option value="">Opção 4</option>
        <option value="">Opção 5</option>
        <option value="">Opção 6</option>
    </select>
</div>
```

Para deixar o campo um pouco maior (form-select-lg)
```
<select class="form-select form-select-lg">
```

Para deixar o campo um pouco menor (form-select-sm)
```
<select class="form-select form-select-sm">
```

Mostrar 4 opções com uma barra de rolagem (multiple)
```
<select class="form-select form-select" multiple>
```

Para mostrar as 6 opções (size="6")
```
<select class="form-select form-select" multiple size="6">
```

Desabilitar o campo (disabled)
```
<select class="form-select form-select" multiple size="6" disabled>
```

## Range
Classe do range (form-range)
```
<input type="range" id="faixa" class="form-range">
```

- Minimo (min)
- Maximo (max)
- Passo (step)
- Valor (value)
```
<input type="range" id="faixa" class="form-range" min="1" max="5" step="1" value="4">   
```

## Botões
Da para usar classe de botões no link (btn btn-primary)
```
<a href="#" class="btn btn-primary">Link</a>
```

Apenas o contorno (btn-outline-primary)
```
<a href="#" class="btn btn-outline-primary">Link</a>
```

Deixar o botão um pouco maior (btn-lg)
```
<a href="#" class="btn btn-outline-primary btn-lg">Link</a>
```

Deixar o botão um pouco menor (btn-sm)
```
<a href="#" class="btn btn-outline-primary btn-sm">Link</a>
```

Deixar botão desabilitado (disabled)
```
<button class="btn btn-warning" disabled>Botão</button>
```