# CAMPOS COM TITULOS FLUTUANTES

1. Deixar o label embaixo do input 
```
<input type="email" name="" id="email" class="form-control">
<label for="email" class="form-label">E-mail</label>
```

2. Colocar a classe (form-floating)
```
<div class="form-floating">
    <input type="email" name="" id="email" class="form-control">
    <label for="email" class="form-label">E-mail</label>
</div>
```

3. Colocar o placeholder vazio (placeholder=" ")
```
<input type="email" name="" id="email" class="form-control" placeholder=" ">
```

Usar o text area com titulo fluante 
```
<div class="form-floating">
    <textarea name="" id="msg" class="form-control" style="height:100px" placeholder=" "></textarea>
    <label for="msg">Mensagem</label>
</div>
```

Uso do select no texto flutuante Não funciona com o size
```
  <div class="form-floating">
    <select name="" id="cidade" class="form-select" placegolder=" ">
        <option value="">Cidade 1</option>
        <option value="">Cidade 2</option>
        <option value="">Cidade 3</option>
        <option value="">Cidade 4</option>
        <option value="">Cidade 5</option>
    </select>
    <label for="cidade">Cidade</label>
</div>
```