# MENSAGENS FLUTUANTES

Arquivo js no canal do (Ricardo Marroquino)[https://www.youtube.com/watch?v=3IDahmYSD6g&list=PL0YuSuacUEWuJN3qb6NP15bzqd8w_oAj7&index=31&ab_channel=RicardoMaroquio]

Cabeçalho (toast-header)
```
<div class="container my-5">
    <div class="toast">
        <div class="toast-header">
            <i class="bi-info-circle me-1"></i>
            <strong class="me-auto">Informação</strong>
            <button class="btn-close ms-auto" data-bs-dismiss="toast"></button>
        </div>
        <div class="toast-body"></div>
    </div>
</div>
```

Botão para fechar a mensagem flutuante
```
<button class="btn-close ms-auto" data-bs-dismiss="toast"></button>
```

Corpo do toast (toast-body)
```
<div class="toast-body">
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Eligendi voluptas iusto dignissimos, iure nulla vitae harum distinctio possimus! Odit, nihil.
</div>
```

Mensagem de visualização
```
<div class="toast">
    <div class="toast-body">
        Chegaram novas mensagens em sua caixa postal
        <div class="mt-2 pt-2 border-top">
            <button class="btn btn-primary btn-sm">Visualizar</button>
            <button class="btn btn-secondary btn-sm" data-bs-dismiss="toast">Ignorar</button>
        </div>
    </div>
</div>
```

Arrumar o tempo que irá aparecer na mensagem flutuante 
```
<div class="toast" data-bs-delay="1000">
```

Mudar a cor da mesangem flutuante (text-bg-dark)
```
<div class="toast text-bg-dark" data-bs-delay="1000">
```

Sistema de notificação a direita
```
<div class="container my-5">
    <button class="btn btn-primary" id="btnToast">Criar Toast</button>

    <div class="toast-container top-0 end-0 p-3" id="toastContainer"></div>
    <div class="toast" id="toast">
        <div class="toast-header">
            <i class="bi-info-circle me-1"></i>
            <strong class="me-auto">Informação</strong>
            <button class="btn-close ms-auto" data-bs-dismiss="toast"></button>
        </div>
        <div class="toast-body">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Eligendi voluptas iusto dignissimos, iure nulla vitae harum distinctio possimus! Odit, nihil.
        </div>
    </div>
</div>
```

Dica flutuante
```
<button class="btn btn-primary" id="btnToast" data-bs-toggle="tooltip" data-bs-title="Este botão cria um novo toast.">Criar Toast</button>
```

Formatando a dica com HTML
```
<button class="btn btn-primary" id="btnToast" data-bs-toggle="tooltip" data-bs-title="Este botão cria um novo <b>toast</b>." data-bs-html="true">Criar Toast</button>
```

Mudar a posição Obs. ao usar o (data-boundary="window") funcionou mas apenas o titulo
```
<button class="btn btn-primary" id="btnToast" data-bs-toggle="tooltip" data-bs-title="Este botão cria um novo <b>toast</b>." data-bs-html="true" data-bs-placement="top">Criar Toast</button>
```
```
<button class="btn btn-primary" id="btnToast" data-bs-toggle="tooltip" data-bs-title="Informação" data-bs-content="Esta é uma informação qualquer." data-bs-placement="top" data-boundary="window">Criar Toast</button>
```

Pop Over
```
<button class="btn btn-primary" id="btnToast" data-bs-toggle="popover" data-bs-title="Informação" data-bs-content="Esta é uma informação qualquer." data-bs-placement="top">Criar Toast</button>
```