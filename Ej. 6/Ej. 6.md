Selectores: *, .container, .container href, h1, #titulo, !important

NOTA: !important no es un selector pero interactua con estos provocando tener prioridad ante cualquier otro. No es recomendable porque rompe la cascada natural de las hojas de estilo. En caso de haber dos important, tendra prioridad el selector con mas peso al que este asociado. 

1. #titulo (1,0,0)
2. .container href (0,1,1)
3. .container (0,1,0)
4. h1 (0,0,1)
5. * (0,0,0)