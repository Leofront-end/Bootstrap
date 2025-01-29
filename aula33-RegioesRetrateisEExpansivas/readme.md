# REGIÕES RETRATEIS E EXPANSIVAS

Botão da parte retratil
```
<div class="container my-3">
    <div class="accordion">
        <div class="accordion-item">
            <div class="accordion-header">
                <button class="accordion-button" type="button">Região 1</button>
            </div>
            <div class="accordion-collapse"></div>
        </div>
    </div>
</div>
```

Fechar e abrir conteudo
```
<div class="accordion">
    <div class="accordion-item">
        <div class="accordion-header">
            <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#item1">Região 1</button>
        </div>
        <div class="accordion-collapse collapse show" id="item1">
            <div class="accordion-body">
                Conteudo 1. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Perferendis, expedita provident. Magni expedita labore assumenda quas nostrum amet sequi quos. Iste cum dolor quod deserunt repellendus sunt aspernatur enim asperiores dicta eum, corporis sapiente tenetur totam, pariatur ab exercitationem odit soluta autem? Odit incidunt minima ullam illum. Repellendus, adipisci minus.
            </div>
        </div>
    </div>
</div>
```

Mostrar só o primero conteudo tirar o show dos outros
```
<div class="accordion-item">
    <div class="accordion-header">
        <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#item2">Região 2</button>
    </div>
    <div class="accordion-collapse collapse" id="item2">
        <div class="accordion-body">
            Conteudo 2. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Perferendis, expedita provident. Magni expedita labore assumenda quas nostrum amet sequi quos. Iste cum dolor quod deserunt repellendus sunt aspernatur enim asperiores dicta eum, corporis sapiente tenetur totam, pariatur ab exercitationem odit soluta autem? Odit incidunt minima ullam illum. Repellendus, adipisci minus.
        </div>
    </div>
</div>
<div class="accordion-item">
    <div class="accordion-header">
        <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#item3">Região 3</button>
    </div>
    <div class="accordion-collapse collapse" id="item3">
        <div class="accordion-body">
            Conteudo 3. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Perferendis, expedita provident. Magni expedita labore assumenda quas nostrum amet sequi quos. Iste cum dolor quod deserunt repellendus sunt aspernatur enim asperiores dicta eum, corporis sapiente tenetur totam, pariatur ab exercitationem odit soluta autem? Odit incidunt minima ullam illum. Repellendus, adipisci minus.
        </div>
    </div>
</div>
```

Mostrar o botão de maneira fechada (collapsed)
```
<button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#item3">Região 3</button>
```

Abrir um de cada vez
```
<div class="accordion" id="acc1">
    <div class="accordion-item">
        <div class="accordion-header">
            <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#item1">Região 1</button>
        </div>
        <div class="accordion-collapse collapse show" data-bs-parent="#acc1" id="item1">
            <div class="accordion-body">
                Conteudo 1. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Perferendis, expedita provident. Magni expedita labore assumenda quas nostrum amet sequi quos. Iste cum dolor quod deserunt repellendus sunt aspernatur enim asperiores dicta eum, corporis sapiente tenetur totam, pariatur ab exercitationem odit soluta autem? Odit incidunt minima ullam illum. Repellendus, adipisci minus.
            </div>
        </div>
    </div>
    <div class="accordion-item">
        <div class="accordion-header">
            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#item2">Região 2</button>
        </div>
        <div class="accordion-collapse collapse" data-bs-parent="#acc1" id="item2">
            <div class="accordion-body">
                Conteudo 2. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Perferendis, expedita provident. Magni expedita labore assumenda quas nostrum amet sequi quos. Iste cum dolor quod deserunt repellendus sunt aspernatur enim asperiores dicta eum, corporis sapiente tenetur totam, pariatur ab exercitationem odit soluta autem? Odit incidunt minima ullam illum. Repellendus, adipisci minus.
            </div>
        </div>
    </div>
    <div class="accordion-item">
        <div class="accordion-header">
            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#item3">Região 3</button>
        </div>
        <div class="accordion-collapse collapse" data-bs-parent="#acc1" id="item3">
            <div class="accordion-body">
                Conteudo 3. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Perferendis, expedita provident. Magni expedita labore assumenda quas nostrum amet sequi quos. Iste cum dolor quod deserunt repellendus sunt aspernatur enim asperiores dicta eum, corporis sapiente tenetur totam, pariatur ab exercitationem odit soluta autem? Odit incidunt minima ullam illum. Repellendus, adipisci minus.
            </div>
        </div>
    </div>
</div>
```

Deixar mais quadrado (accordion-flush)
```
<div class="accordion accordion-flush" id="acc1">
```