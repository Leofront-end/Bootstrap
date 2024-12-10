# Formatação de colunas

```
<div class="container">
    <div class="row ">
            <!--

            Ajustar Horizontalmente
                justify-content-start deixa centralizado no começo
                justify-content-center deixa centralizado no meio
                justify-content-end deixa centralizado no final
                justify-content-between deixa um espaço entre as colunas
                justify-content-around deixa um espaço entre as colunas e metade do espaço no começo e final
                justify-content-evenly deixa um espaço entre as colunas e no inicio e no fim
            -->
            <div class="col-3 mx-auto">Coluna 1</div><!--
                    ALIGN
                        align-self-start deixa apenas o item no começo
                        align-self-center deixa apenas o item no meio
                        align-self-end deixa apenas o item no final
                    ORDER
                        order-last faz o item ir para o final
                        order-first faz o item ir para o começo
                        order-n° faz o item ir para o numero
                    offset-n° desloca o numero de colunas para o lado

                    ms-auto poe uma margin esquerda do numero que estiver disponivel
                    mx-auto poe uma margin centralizada do numero que estiver disponivel
                -->
                <div class="col-3 ">Coluna 2</div><!---->
            <!-- <div class="w-100"></div> Quebra de linha-->
            <!-- <div class="col-3 ">Coluna 3</div><!--align-self-end --> 
        </div>
    </div>
```

## Ajustar Verticalmente
- Align-items-start para alinhar todos os itens
```
<div class="row Align-items-start">
```

- Align-items-*xxl*-center o *breakpoint* do xxl ent só ira funcionar a partir de 1300px mais ou menos

```
<div class="row Align-items-xxl-center">
```

## Ajustar Horizontalmente
- justify-content-start deixa centralizado no começo
```
<div class="row justify-content-start">
```

```
<div class="row ">
```

```
<div class="row ">
```

```
<div class="row ">
```

```
<div class="row ">
```
## ALIGN

## ORDER

## OFFSET

## MARGIN