# Edición da revista en liña a través de Typst.App

A principal vantaxe desta opción é que só require conexión á internet e unha conta
de balde. Polo que evitamos posíbeis rompedeiros de cabeza con Scoop e Makefiles
fóra de entornos GNU/Linux.

O primeiro paso é a creación dunha conta de Typst, unha vez feito isto
engadiremos un novo documento (`Empty document`) dende o «Dashboard». Dentro do
documento, no panel esquerdo, hai un menú de «Files» que permite subir ficheiros
coa opción «Upload a new file». Para poder compilar unha revista/artigo necesitaremos
obrigatoriamente os seguintes ficheiros/cartafoles:

```
.
├── estilo.typ
├── fontes/
├── logos/
├── momentum-citacions.csl
└── revistas/
    └── XXX/
```

[IMAXE]

sendo `XXX/` o cartafol da revista que queremos editar. Para obtelos sen usar
`git`, a forma máis doada é descargar o ZIP do repositorio e copiar e pegar o
que faga falla. Por outro lado, a versión gratuíta de Typst.App ten un límite de 100
ficheiros por documento, polo que se desaconsella subir todo o repositorio. O resultado debería ter esta forma:

[IMAXE]

Para visualizar un artigo (`artigo_VICTOR_DD.typ`) ou a revista completa
(`revista_004.typ`) prememos o ollo que aparece á dereita do nome do documento:

[IMAXE]
