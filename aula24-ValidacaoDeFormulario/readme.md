# VALIDAÇÃO DE FORMULARIO
Validar o formulario e desativar a validação padrão (.needs-validation/ novalidate)
```
<form method="post" class="needs-validation" novalidate>
```

Usar esse (Site)[https://getbootstrap.com/docs/5.3/forms/validation/] e por o script dele

Criar uma mensagem caso de erro (invalid-feedback)
```
<div class="invalid-feedback">
    Você deve informar o logradouro
</div>
```

Criar uma classe no input para valido (is-valid)
```
<input type="text" class="form-control is-valid" id="logradouro" required>
```

Caso não seja valido o input (is-invalid)
```
<input type="text" class="form-control is-invalid" id="cep" pattern="[0-9]{8}" required>
```