# Configuração de Posicionamento

Fixar a classe azul no topo (fixed-top)
```
<div class="p-5 bg-primary fixed-top"></div>
```

Fixar em baixo (fixed-bottom)
```
<div class="p-5 bg-dark fixed-bottom"></div>
```

Deixar por tras do fixo para preencher espaço (p-5 invisible)
```
<div class="p-5 invisible"></div>
```

Quando a div estiver no meio e ao rolar e ela ficar no topo (sticky-top)
```
<div class="p-5 bg-warning sticky-top"></div>
```

Quando a div estiver no meio e ao rolar e ela ficar em baixo (sticky-bottom)
```
<div class="p-5 bg-warning sticky-bottom"></div>
```

Quando passar por ela e ela grudar tanto em cima ou em baixo (sticky-bottom sticky-top)
```
<div class="p-5 bg-warning sticky-bottom sticky-top"></div>
```

## Empilhamentos de elementos
Fazer se tornar uma pilha na vertical(vstack)
```
<div class="container my-3 vstack">
```

Espaçamento de 0 a 5 (gap-3)
```
<div class="container my-3 vstack gap-3">
```

Espaçamento com breakpoint (gap-sm-3)
```
<div class="container my-3 vstack gap-sm-3">
```

Empilhamento na horizontal (hstack)
```
<div class="container my-3 hstack gap-3">
```

Barra vertical (vr)
```
<div class="vr"></div>
```

Deixar a barra com uma separação fazendo uma margin na esquerda (ms-auto)
```
<div class="vr ms-auto"></div>
```

## Posicionamento
Oculpa somente a area preenchida (position-absolute)
```
<div class="p-5 bg-success position-absolute"></div>
```

O elemento de cima se for relativo as margens não vão contar (position-relative)
```
<div class="container my-3 position-relative">
```