Time-stamp: <2024-07-28 18:39:47 augus>
.. title: Un fin de semana con Julia
.. slug: videos-juliacon-2024
.. date: 2024-07-22 20:44:09 UTC-03:00
.. tags: julia 
.. category: 
.. link: 
.. description: 
.. type: text
.. status: draft

Terminó JuliaCon 2024 y los streamings en vivo están disponibles para ver en YouTube... El único problema es que son grabacciones de entre 8 y 10 horas, uno por cada sala de la conferencia y de tres días distintos.

Así que encontrar las charlas que me interesaban requería un trabajo extra. Luego de ver dos, noté que entre charla y charla en el video mostraban el cronograma de esa sala para ese día. Y lo primero que me vino a la mente fue: "Perfecto, tengo un problema sencillo de automatización para hacerlo con Julia".

Y ya que estoy, puedo probar grabar la pantalla y ver como mi computadora se la banca. Hace un tiempo que quiero intentar hacer *streaming* y esta era una gran oportunidad para empezar a hacerlo.


Entonces, además de poder encontrar de manera sencilla los videos, el ejercicio tenía los objetivos de:

1) Hacer un "Test Drive" de Julia con un problema de varios dominios: Procesamiento de texto y *Scrapping*, Análisis de Imágenes, Interacción con *API Rest*

2) Animarme a grabar un *screen share*, poner a prueba el *setup* de mi computadora para empezar a ver que limitaciones hay y que tengo que aprender.


El [código](https://github.com/akielbowicz/arenero/blob/b00ba7e206977c08c92e1ab3b68d94844f352165/juliacon2024-videos/decargar_yt_list.jl) en su estado natural despues de hacerlo funcionar. 

Como siguiente paso quiero hacer un video *refactorizando* el código. 


Basta de chachara..., 


# Encontrar todos los videos

- 

# Encontrar los *frames* con el cronograma

- performance
- pretalx


# Conclusiones

```julia-repl
julia> versioninfo()
Julia Version 1.10.0
Commit 3120989f39b (2023-12-25 18:01 UTC)
Build Info:
  Official https://julialang.org/ release
Platform Info:
  OS: Linux (x86_64-linux-gnu)
  CPU: 4 × Intel(R) Core(TM) i7-4510U CPU @ 2.00GHz
  WORD_SIZE: 64
  LIBM: libopenlibm
  LLVM: libLLVM-15.0.7 (ORCJIT, haswell)
  Threads: 1 on 4 virtual cores
```


## Grabar videos del desarrollo de un código



## Usar Julia 

- *Pluto.jl*
- *Time To First Plot*
- Integración con *VSCode*
- Desarrollo interactivo
- estructurar código con funciones
- interoperabilidad con formatos estandares
- documentación accesible
- facil benchmark
- librerias 

## Resolver problemas con una computadora

- Limitaciones
- problemas intermedios
- 


Aprovechar las imagenes con el cronograma

Sacar los timestamps del cronograma de pretalx

Matchear las imagenes

Probar como hacer streaming y grabar la pantalla

encontrar el tiempo inicial
