# Formatação de colunas

```
<div class="container">
    <div class="row">
            <div class="col-3 ">Coluna 1</div>
            <div class="col-3 ">Coluna 2</div>
            <div class="w-100"></div>
            <div class="col-3 ">Coluna 3</div>
        </div>
    </div>
</div>
```

## Ajustar Verticalmente
### ITEMS
- Align-items-**start** para alinhar todos os itens no **começo** verticalmente
```
<div class="row align-items-start"></div>
```

- Align-items-**center** para alinhar todos os itens no **centro** verticalmente
```
<div class="row align-items-center"></div>
```

- Align-items-**end** para alinhar todos os itens no **final** verticalmente
```
<div class="row align-items-end"></div>
```

### SELF
- Align-self-**start** para alinhar um dos itens no **começo** verticalmente
```
<div class="row align-self-start"></div>
```

- Align-self-**center** para alinhar um dos itens no **centro** verticalmente
```
<div class="row align-self-center"></div>
```

- Align-self-**end** para alinhar um dos itens no **final** verticalmente
```
<div class="row align-self-end"></div>
```

### COM BREAKPOINT
- Align-items-**xxl**-center o **breakpoint** do xxl ent só ira funcionar a partir de 1300px mais ou menos

```
<div class="row Align-items-xxl-center"></div>
```

## Ajustar Horizontalmente
- justify-content-**start** deixa centralizado no **começo**
```
<div class="row justify-content-start"></div>
```

- justify-content-**center** deixa centralizado no **meio**
```
<div class="row justify-content-center"></div>
```

- justify-content-**end** deixa centralizado no **final**
```
<div class="row justify-content-end"></div>
```

- justify-content-**between** deixa um espaço **entre** as colunas
```
<div class="row justify-content-between"></div>
```

- justify-content-**around** deixa um espaço **entre** as colunas e **metade do espaço** no começo e final
```
<div class="row justify-content-around"></div>
```

- justify-content-**evenly** deixa um espaço **entre** as colunas e **no inicio e no fim**
```
<div class="row justify-content-evenly"></div>
```

## ORDER
- order-**last** faz o item ir para o **final**
```
 <div class="col-3 order-last"></div>
```
 
- order-**first** faz o item ir para o **começo**
```
 <div class="col-3 order-first"></div>
```

- order-**n°** faz o item ir para o **numero**
```
 <div class="col-3 order-n°"></div>
```
## OFFSET
- offset-n° desloca o numero de colunas para **o lado**
```
<div class="col-3 offset-n°"></div>
```

## Quebra de linha
- **Quebra de linha**
```
<div class="w-100"></div> 
```

## MARGIN
- ms-**auto** poe uma **margin esquerda** do numero que estiver disponivel
```
<div class="col-3 mx-auto">Coluna 1</div>
```

- mx-**auto** poe uma **margin centralizada** do numero que estiver disponivel
```
<div class="col-3 mx-auto">Coluna 1</div>
```

## OBSERCAÇÃO
- **TODOS OS ITEMS A CIMA TEM VARIAÇÃO DE BREAKPOINT**