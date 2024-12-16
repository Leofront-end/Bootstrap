# Imagens e Figuras
Fica Exatamente o tamanho do container de maneira responsiva
```
<div class="container">
    <img src="Musica.jpg" alt="imagem responsiva" class="img-fluid ">
</div>
```

Imagem com bordas e levemente arredondados
```
<div class="container">
    <img src="Musica.jpg" alt="imagem responsiva" class="img-thumbnail ">
</div>
```

Deixar os cantos arredondados da imagem
```
<div class="container">
    <img src="Musica.jpg" alt="imagem responsiva" class="img-fluid rounded">
</div>
```

Imagem do lado esquedo e texto do lado direito com uma margin de 3
```
<div class="container">
    <img src="Musica.jpg" alt="" class="col-3 img-thumbnail float-start me-3">
    <p class="lead">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quas non quia dolorum quisquam velit aspernatur error veritatis itaque odit ullam iure quidem ducimus perspiciatis recusandae labore rerum id aliquid ut saepe, esse quibusdam facere fugiat. Culpa nobis deserunt aliquid quo fugit, inventore, facilis reiciendis expedita nostrum voluptatem vel ex impedit in vitae repellendus autem! Nam reprehenderit esse aut a aliquid ipsam ad est illo similique id, quis iure consequuntur voluptatibus voluptatum pariatur, quae optio in placeat quos necessitatibus omnis eos.</p>
</div>
```

Imagem do lado direito e texto do lado esquerdo com uma margin de 3 na esquerda para não juntar com o texto, e a borda arredonda na imagem
```
<div class="container">
    <img src="Musica.jpg" alt="" class="col-3 rounded float-end ms-3">
    <p class="lead text-end">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quas non quia dolorum quisquam velit aspernatur error veritatis itaque odit ullam iure quidem ducimus perspiciatis recusandae labore rerum id aliquid ut saepe, esse quibusdam facere fugiat. Culpa nobis deserunt aliquid quo fugit, inventore, facilis reiciendis expedita nostrum voluptatem vel ex impedit in vitae repellendus autem! Nam reprehenderit esse aut a aliquid ipsam ad est illo similique id, quis iure consequuntur voluptatibus voluptatum pariatur, quae optio in placeat quos necessitatibus omnis eos.</p>
</div>
```