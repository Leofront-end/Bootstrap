# FORMULARIOS
## Formulario comum
Aparencia padrão de um formulário
```
<div class="container">
    <form>
        <div>
            <label for="email">E-mail</label>
            <input type="email" id="email">
            <div>Nunca compartilharemos seu email com terceiros</div>
        </div>
        <div>
            <label for="senha">Senha</label>
            <input type="text" id="senha">
        </div>
        <div>
            <input type="checkbox" id="lembrar">
            <label for="lembrar">Lembrar de mim</label>
        </div>
        <button type="submit">Entrar</button>
    </form>
</div>
```

## Label e Input
Usada para os label (form-label)
```
<label for="email" class="form-label">E-mail</label>
```

Usada para os campos de preenchimento (form-control)
```
<input type="email" id="email" class="form-control">
```

Usada para textos de erros ou informações (form-text)
```
<div class="form-text">Nunca compartilharemos seu email com terceiros</div>
```

### Checagem
Para o campo de checagem usar o (form-check)
```
<div class="mb-3 form-check">
    <input type="checkbox" id="lembrar" class="form-check-input">
    <label for="lembrar" class="form-check-label">Lembrar de mim</label>
</div>
```

Para o input de checagem (form-check-input)
```
<input type="checkbox" id="lembrar" class="form-check-input">
```

Para o label de checagem (form-check-label)
```
<label for="lembrar" class="form-check-label">Lembrar de mim</label>
```

## Botão
Usar a classe de botão (btn)
```
<button type="submit" class="btn">Entrar</button>
```

Colocar cor no botão (btn-primary)
```
<button type="submit" class="btn btn-primary">Entrar</button>
```

## Atributos para campos de formulários 
Desativar o form(disabled)
```
<input type="email" id="email" class="form-control" disabled>
```

Apenas para ver e não conseguir digitar (readonly)
```
<input type="email" id="email" class="form-control" readonly>
```

Adicionar um valor (value)
```
<input type="email" id="email" class="form-control" readonly value="email@email.com">
```

Informar uma mensagem para o campo de preenchimento (placeholder)
```
<input type="email" id="email" class="form-control" placeholder="Digite seu e-mail">
```

## Mais classes
Deixar a classe um pouco maior que a do padrão (form-control-lg)
```
<input type="email" id="email" class="form-control form-control-lg" placeholder="Digite seu e-mail">
```

Deixar a classe um pouco menor que a do padrão (form-control-sm)
```
<input type="email" id="email" class="form-control form-control-sm" placeholder="Digite seu e-mail">
```

Deixar como se fosse um texto comum (form-control-plaintext)
```
<input type="email" id="email" class="form-control form-control-plaintext" placeholder="Digite seu e-mail">
```

## Input
Enviar arquivos (form-control)
```
<input type="file" id="arquivo" class="form-control">
```

Input do tipo de cor (form-control)
```
<input type="color" id="cor" class="form-control">
```

Usando um datalist 
```
<div class="mb-3">
    <label for="" class="form-label">Cidade</label>
    <input type="text" class="form-control" placeholder="Digite para buscar..." list="cidades">
    <datalist id="cidades">
        <option value="Cidade 1"></option>
        <option value="Cidade 2"></option>
        <option value="Cidade 3"></option>
        <option value="Cidade 4"></option>
        <option value="Cidade 5"></option>
        <option value="Cidade 6"></option>
    </datalist>
</div>
```