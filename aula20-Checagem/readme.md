# CAMPOS DE CHECAGEM
## Checkbox
Para a div do checkbox (form-check)
```
<div class="mb-3 form-check"></div>
```

Para a caixa (form-check-input)
```
<input type="checkbox" class="form-check-input" id="novo">
```

Para o label (form-check-label)
```
<label for="novo" class="form-check-label">Produto Novo</label>
```

Para desabilitar (disabled)
```
<input type="checkbox" class="form-check-input" id="novo" disabled>
```

Marcado ou desmarcado (form-switch)
```
<div class="mb-3 form-switch">
```

Para colocar um do lado do outro (form-check-inline)
```
<div class="mb-3 form-check form-check-inline">
```

Para fazer alinhados a direita (form-check-reverse)
```
<div class="mb-3 form-check form-check-reverse">
```

Fazer um botão no checkbox (btn-check / btn btn-primary)
```
<div class="mb-3">
    <input type="checkbox" name="" id="EntregaRapida" class="btn-check">
    <label for="EntregaRapida" class="btn btn-primary">Entrega Rápida</label>
</div>
```

Agora fazer um botão com contorno (btn-outline-primary)
```
<label for="EntregaRapida" class="btn btn-outline-primary">Entrega Rápida</label>
```

## Radio

Para marcar um ou outro (name="mesmo nome nos dois")
```
<div class="mb-3 form-check">
    <input type="radio" class="form-check-input" id="novo" name="estado" value="n">
    <label for="novo" class="form-check-label">Produto Novo</label>
</div>
<div class="mb-3 form-check">
    <input type="radio" class="form-check-input" id="novo" name="estado" value="u">
    <label for="novo" class="form-check-label">Produto Usado</label>
</div>
```

O valor enviado será pelo value (value="")
```
<div class="mb-3 form-check">
    <input type="radio" class="form-check-input" id="novo" name="estado" value="n">
    <label for="novo" class="form-check-label">Produto Novo</label>
</div>
```

Para desabilitar (disabled) 
```
<input type="radio" class="form-check-input" id="novo" name="estado" value="n" disabled>
```

Para colocar um do lado do outro (form-check-inline)
```
<div class="mb-3 form-check form-check-inline">
```

Para fazer alinhados a direita (form-check-reverse)
```
<div class="mb-3 form-check form-check-reverse">
```

Da para fazer botões marcaveis com o radio (name="O mesmo nome")
```
<div class="mb-3">
    <input type="radio" name="TipoEntrega" id="EntregaRapida" class="btn-check">
    <label for="EntregaRapida" class="btn btn-outline-primary">Entrega Rápida</label>
</div>
<div class="mb-3">
    <input type="radio" name="TipoEntrega" id="EntregaLenta" class="btn-check">
    <label for="EntregaLenta" class="btn btn-outline-primary">Entrega Lenta</label>
</div>
```