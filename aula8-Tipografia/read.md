# Tipografia
## Titulos
Esse texto vem sem serifa e com 16px: 
```
<h1>Titulo</h1>
<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Placeat consequuntur numquam maiores eaque iusto doloribus tenetur similique corrupti, aspernatur delectus libero deserunt quos molestiae facere, vel deleniti eligendi, fugit consequatur.</p>
```
Titulos:

```
<div class="container">
    <h1>h1 - Titulo de nivel 1</h1>
    <h2>h2 - Titulo de nivel 2</h2>
    <h3>h3 - Titulo de nivel 3</h3>
    <h4>h4 - Titulo de nivel 4</h4>
    <h5>h5 - Titulo de nivel 5</h5>
    <h6>h6 - Titulo de nivel 6</h6>
</div>              
```
Paragrafos com aspecto de titulo

```
<div class="container">
    <p class="h1">.h1 - classe de titulo de nivel 1</p>
    <p class="h2">.h2 - classe de titulo de nivel 2</p>
    <p class="h3">.h3 - classe de titulo de nivel 3</p>
    <p class="h4">.h4 - classe de titulo de nivel 4</p>
    <p class="h5">.h5 - classe de titulo de nivel 5</p>
    <p class="h6">.h6 - classe de titulo de nivel 6</p>
</div>
```

Fazer o cabeçalho de forma mais elegante
```
 <div class="container">
    <h1 class="display-1">Display 1</h1>
    <h1 class="display-2">Display 2</h1>
    <h1 class="display-3">Display 3</h1>
    <h1 class="display-4">Display 4</h1>
    <h1 class="display-5">Display 5</h1>
    <h1 class="display-6">Display 6</h1>
</div>
```

## Paragrafos
Faz o texto ter um destaque
```
<p class="lead">Lorem ipsum dolor sit amet consectetur adipisicing elit. Maxime alias voluptate ratione tempora. Excepturi sunt, vel repudiandae molestiae, consectetur beatae totam voluptates commodi dolores ea, at provident rerum labore dicta!</p>
```

tipos de p para destaque
```
 <div class="container">
    <p>Texto em <mark>marcado</mark></p>
    <p>Texto com aspecto de <del>Excluido</del></p>
    <p>Texto <s>riscado</s></p>
    <p>Texto <ins>recem-inserido</ins></p>
    <p>Texto <u>sublinhado</u></p>
    <p>Texto <small>pequeno</small></p>
    <p>Texto <strong>encorpado</strong></p>
    <p>Texto <em>italico</em></p>
</div>
```

## Abreviações
Ao passar o mouse em cima ele mostra a abreviação
```
<div class="container">
    <abbr title="Mongo, Express, React e Node">MERN</abbr>
</div>
```

## bloco de citação
```
<div class="container">
    <figure class="text-center">
        <blockquote class="blockquote" cite="Fulano de Tal">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Aspernatur et itaque consequatur nesciunt laborum accusamus architecto omnis officiis iusto, optio maiores suscipit molestiae? Voluptate accusantium illum atque, tempore sequi eos!</p>
        </blockquote>
        <figcation class="blockquote-footer">
            <cite>Fulano Famoso</cite>, diretor de cinema
        </figcation>
    </figure>
</div>
```

## Lista
Lista uma embaixo da outra e uma do lado da outra
Para tirar a bolinha da lista poe na classe list-unstyled
```
<div class="container">
    <ul class="list-unstyled">
        <li>Item 1</li>
        <li>Item 2</li>
        <li>Item 3</li>
        <li>Item 4</li>
        <li>Item 5</li>
        <li>Item 6</li>
    </ul>
    <hr>
    <ul class="list-inline">
        <li class="list-inline-item">item 1</li>
        <li class="list-inline-item">item 2</li>
        <li class="list-inline-item">item 3</li>
        <li class="list-inline-item">item 4</li>
        <li class="list-inline-item">item 5</li>
        <li class="list-inline-item">item 6</li>
    </ul>
</div>
```

Lista de Definições
```
<div class="container">
    <dl>
        <dt>Termo 1</dt>
        <dd>Descrição do Termo 1</dd>
        <dt>Termo 2</dt>
        <dd>Descrição do Termo 2</dd>
        <dt>Termo 3</dt>
        <dd>Descrição do Termo 3</dd>
        <dt>Termo 4</dt>
        <dd>Descrição do Termo 4</dd>
        <dt>Termo 5</dt>
        <dd>Descrição do Termo 5</dd>
    </dl>
</div>
```