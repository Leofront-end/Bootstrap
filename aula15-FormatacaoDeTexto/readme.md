# Formatação de Texto
## Alinhamento 
Alinhar a esquerda (text-start)
```
<div class="container">
    <p class="text-start">Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempore enim nisi possimus sed, non aliquam temporibus facere sint libero incidunt odio nam distinctio et illum quod quo quis? Eligendi, facilis.</p>
</div>
```

Alinhar ao centro (text-center)
```
<p class="text-center">Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempore enim nisi possimus sed, non aliquam temporibus facere sint libero incidunt odio nam distinctio et illum quod quo quis? Eligendi, facilis.</p>
```

Alinhar a direita (text-end)
```
<p class="text-end">Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempore enim nisi possimus sed, non aliquam temporibus facere sint libero incidunt odio nam distinctio et illum quod quo quis? Eligendi, facilis.</p>
```

Com breakpoint (text-sm-end)
Ao usar o text-start só vale se for abaixo de sm
```
<p class="text-start text-sm-end">Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempore enim nisi possimus sed, non aliquam temporibus facere sint libero incidunt odio nam distinctio et illum quod quo quis? Eligendi, facilis.</p>
```

## Quebra de linha
Texto em uma linha independente do tamanho do texto (text-nowrap)
```
<p class="text-start text-nowrap">Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempore enim nisi possimus sed, non aliquam temporibus facere sint libero incidunt odio nam distinctio et illum quod quo quis? Eligendi, facilis.</p>
```

Caso uma palavra seja grande demais e deseja pular de linha (text-break)
```
<p class="text-start text-break">Loremipsumdolorsitametconsectetur adipisicingelitMagniperferendiscumquehic,quasimaioresofficiis delenitiquidemplaceatducimusquod!</p>"
```

## Texto em MAIUSCULO/minusculo/Primeira letra da frase em maiusculo
Deixar o texto em minusculo (text-lowercase)
```
<p class="text-start text-lowercase">Lorem ipsum dolor sit amet consectetur adipisicing elit. Eius fugit temporibus, ad aliquam qui, error nihil eveniet quibusdam deserunt, obcaecati eaque consequatur accusamus omnis! Quaerat libero dignissimos non soluta modi.</p>
```

Deixar o texto em maiusculo (text-uppercase)
```
<p class="text-start text-uppercase">Lorem ipsum dolor sit amet consectetur adipisicing elit. Eius fugit temporibus, ad aliquam qui, error nihil eveniet quibusdam deserunt, obcaecati eaque consequatur accusamus omnis! Quaerat libero dignissimos non soluta modi.</p>
```

Deixar a primeira letra de cada frase maiusculo (text-capitalize)
```
<p class="text-start text-capitalize">Lorem ipsum dolor sit amet consectetur adipisicing elit. Eius fugit temporibus, ad aliquam qui, error nihil eveniet quibusdam deserunt, obcaecati eaque consequatur accusamus omnis! Quaerat libero dignissimos non soluta modi.</p>
```

## Tamanho das fontes
Tamanhos da fonte (fs-1)
Varia de 1 a 6 - com o tamanho de h1 a h6
```
<p class="text-start text-capitalize fs-1">Lorem ipsum dolor sit amet consectetur adipisicing elit. Eius fugit temporibus, ad aliquam qui, error nihil eveniet quibusdam deserunt, obcaecati eaque consequatur accusamus omnis! Quaerat libero dignissimos non soluta modi.</p>
```

## Peso e estilo
### Peso
Pesos e estilo das fontes
Negrito (fw-bold)
```
<p class="fw-bold">Texto com peso negrito</p>
```

Semi-negrito (fw-semibold)
```
<p class="fw-semibold">Texto com peso semi-negito </p>
```

Normal (fw-normal)
```
<p class="fw-normal">Texto com peso normal </p>
```

Leve (fw-light)
```
<p class="fw-light">Texto com peso leve</p>
```

### Estilo
Italico (fst-italic)
```
<p class="fst-italic">Texto com estilo italico</p>
```

Normal (fst-normal)
```
<p class="fst-normal">Texto com estilo normal</p>
```

## Altura da linha de texto
Linhas coladas (lh-1)
```
<p class="lh-1">Lorem ipsum dolor sit amet, consectetur adipisicing elit. A enim quod nobis beatae dicta temporibus sed et molestiae excepturi, explicabo culpa quasi repellat doloribus, facilis, quidem corrupti quibusdam laboriosam libero?</p>
```

Linha um pouco mais alta que a 1 (lh-sm)
```
<p class="lh-sm">Lorem ipsum dolor sit amet, consectetur adipisicing elit. A enim quod nobis beatae dicta temporibus sed et molestiae excepturi, explicabo culpa quasi repellat doloribus, facilis, quidem corrupti quibusdam laboriosam libero?</p>
```

Altura padrão (lh-base)
```
<p class="lh-base">Lorem ipsum dolor sit amet, consectetur adipisicing elit. A enim quod nobis beatae dicta temporibus sed et molestiae excepturi, explicabo culpa quasi repellat doloribus, facilis, quidem corrupti quibusdam laboriosam libero?</p>
```

Espaçamento duplo (lh-lg)
```
<p class="lh-lg">Lorem ipsum dolor sit amet, consectetur adipisicing elit. A enim quod nobis beatae dicta temporibus sed et molestiae excepturi, explicabo culpa quasi repellat doloribus, facilis, quidem corrupti quibusdam laboriosam libero?</p>
```

## Tamanho de fonte
Deixar as letras do mesmo tamanho (font-monospace)
```
<p class="lh-lg font-monospace">Lorem ipsum dolor sit amet, consectetur adipisicing elit. A enim quod nobis beatae dicta temporibus sed et molestiae excepturi, explicabo culpa quasi repellat doloribus, facilis, quidem corrupti quibusdam laboriosam libero?</p>
```
## Link
Deixar o link da mesma cor do texto (text-reset)
O text-muted é só para deixar o texto cinza
```
<p class="lh-lg font-monospace text-muted">
    Lorem ipsum dolor sit amet, consectetur adipisicing elit. A enim quod nobis beatae dicta temporibus sed et molestiae excepturi, explicabo culpa quasi repellat doloribus, facilis, quidem corrupti quibusdam laboriosam libero? <a href="#" class="text-reset">Link Qualquer</a>
</p>
```

## Sublinhado e riscado
Tirar o sublinhado do link (text-decoration-none)
```
<a href="#" class="text-reset text-decoration-none">Link Qualquer</a>
```

Colocar o texto em sublinhado (text-decoration-underline)
```
<p class="lh-lg font-monospace text-muted text-decoration-underline">
    Lorem ipsum dolor sit amet, consectetur adipisicing elit. A enim quod nobis beatae dicta temporibus sed et molestiae excepturi, explicabo culpa quasi repellat doloribus, facilis, quidem corrupti quibusdam laboriosam libero? <a href="#" class="text-reset text-decoration-none">Link Qualquer</a>
</p>
```

Deixar o texto riscado (text-decoration-line-through)
```
<p class="lh-lg font-monospace text-muted text-decoration-line-through">
    Lorem ipsum dolor sit amet, consectetur adipisicing elit. A enim quod nobis beatae dicta temporibus sed et molestiae excepturi, explicabo culpa quasi repellat doloribus, facilis, quidem corrupti quibusdam laboriosam libero? <a href="#" class="text-reset text-decoration-none">Link Qualquer</a>
</p>
```

## Mostrar apenas a primeira linha
Mostra apenas a primeira linha (text-truncate)
```
<p class="lh-lg font-monospace text-truncate">
    Lorem ipsum dolor sit amet, consectetur adipisicing elit. A enim quod nobis beatae dicta temporibus sed et molestiae excepturi, explicabo culpa quasi repellat doloribus, facilis, quidem corrupti quibusdam laboriosam libero? <a href="#" class="text-reset text-decoration-none">Link Qualquer</a>
</p>
```