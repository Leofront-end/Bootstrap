# Configuração De Visibilidade

## Dispĺay
Usando o display block (d-block)
```
<div class="p-4 col-3 d-block m-3 bg-primary"></div>
<div class="p-4 col-3 d-block m-3 bg-primary"></div>
<div class="p-4 col-3 d-block m-3 bg-primary"></div>
```

Usando o display inline (d-inline)
A largura não da pra mudar, também se sobrepos com a div de cima
```
<div class="p-4 col-3 d-inline m-3 bg-primary"></div>
<div class="p-4 col-3 d-inline m-3 bg-success"></div>
<div class="p-4 col-3 d-inline m-3 bg-warning"></div>
```

Usando o display inline block (d-inline-block)
A largura ja mudou nesse
```
<div class="p-4 col-3 d-inline-block m-3 bg-primary"></div>
<div class="p-4 col-3 d-inline-block m-3 bg-success"></div>
<div class="p-4 col-3 d-inline-block m-3 bg-warning"></div>
```

A partir do breakpoint lg ela ira se mostrar (d-none d-lg-block)
```
<div class="p-4 col-3 d-none d-lg-block m-3 bg-primary"></div>
```

Ocultar a partir do breakpoint lg (d-lg-none)
```
<div class="p-4 col-3 d-block d-lg-none m-3 bg-success"></div>
```

Tirar algo para quando for imprimir (d-print-none)
```
<header class="p-3 text-bg-dark d-print-none">
```

Tirar do site a aparecer quando for imprimir (d-none d-print-block)
```
<p class="d-none d-print-block">Fonte: Leofront-end.com.br</p>
```

## invisivel
Deixar invisivel mas ainda oculpando o espaço (invisible)
```
<div class="p-4 col-3 m-3 bg-sucess invisible"></div>
```

## Barra de rolagem
Deixar com barra de rolagem na vertical para não ultrapassar o conteudo (overflow-auto)
```
<div class="border p-2 col-3 overflow-auto">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Dolor ut maxime doloremque vitae odit a quia, vero, veritatis assumenda voluptate consectetur enim omnis et voluptas nulla! Recusandae quae voluptas unde!</div>
```

Ocultar o conteudo que estava transbordando (overflow-hidden)
```
<div class="border p-2 col-3 overflow-hidden">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Consectetur recusandae dolorum ipsa tenetur possimus commodi officia accusamus ad nobis mollitia? Laboriosam, dolore obcaecati? Fugiat unde impedit a nesciunt ipsa sed!</div>
```

Deixar o transbordamento de conteudo visivel (overflow-visible) 
```
<div class="border p-2 col-3 overflow-visible">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Consectetur recusandae dolorum ipsa tenetur possimus commodi officia accusamus ad nobis mollitia? Laboriosam, dolore obcaecati? Fugiat unde impedit a nesciunt ipsa sed!</div>
```

Barra de rolagem na vertical e horizontal (overflow-scroll)
```
<div class="border p-2 col-3 overflow-scroll">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Consectetur recusandae dolorum ipsa tenetur possimus commodi officia accusamus ad nobis mollitia? Laboriosam, dolore obcaecati? Fugiat unde impedit a nesciunt ipsa sed!</div>
```