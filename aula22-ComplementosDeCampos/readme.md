# COMPLEMENTOS DE CAMPO DE FORMULÁRIO

Agrupar elementos da div em um unico campo (input-group)
```
<div class="mb-3 input-group">
```

Texto como agrupamento do campo (input-group-text)
```
<span class="input-group-text">@</span>
```

Colocar o campo a direita é só trocar a ordem 
```
<input type="text" class="form-control" id="nome">
<label for="nome" class="input-group-text">Nome Completo</label for="nome">
```   

Colocar dois campos de texto
```
<div class="mb-3 input-group">
    <label for="dinheiro" class="input-group-text">R$</label>
    <input type="text" class="form-control text-end" id="dinheiro">
    <label for="dinheiro" class="input-group-text">,00</label>
</div> 
```

Agora dois input para escrever
```
<div class="mb-3 input-group">
    <input type="text" class="form-control text-end" id="email">
    <span class="input-group-text">@</span>
    <input type="text" class="form-control" id="email">
</div> 
```

Usando o textarea
```
<div class="mb-3 input-group">
    <label for="texto" class="input-group-text">Nome Completo</label>
    <textarea name="" id="texto" class="form-control"></textarea>
</div>  
```

Deixar maior (input-group-lg)
```
<div class="mb-3 input-group input-group-lg">
```

Deixar menor (input-group-sm)
```
<div class="mb-3 input-group input-group-sm">
```

Tipo checkbox 
```
<div class="mb-3 input-group">
    <div class="input-group-text">
        <input type="checkbox" class="form-check-input mt-0" name="" id="">
    </div>
    <input type="text" class="form-control">
</div>  
```

Deixar dois input e um texto 
```
<div class="mb-3 input-group">
    <span class="input-group-text">Nome Completo</span>
    <input type="text" class="form-control" id="email" placeholder="Primeiro nome">
    <input type="text" class="form-control" id="email" placeholder="Sobrenome">
</div> 
```

Deixar dois texto e um input
```
<div class="mb-3 input-group">
    <span class="input-group-text">R$</span>
    <span class="input-group-text">BRL</span>
    <input type="text" class="form-control" placeholder="Valor">
</div> 
```