## Diferencia en stack.yaml:
    - Resolver distinto al de los tps.
# Dependences:
    - base: cosas basicas de haskell. ****
    - pretty: pretty printer library. ****
    - mtl: monadas para transformers. ****
    - QuickCheck: automatic testing de propiedades. *-**
    - parsec: paser monadico. **-*
    - containers: algunas estructuras de datos inmutables. *-**
    - haskeline: linea de comandos para inputs de usuarios. -**-
    - strict: tipos basicos estrictos para evitar lazy haskell util para states. *--*
    - exceptions: exeptions. -**-
    - array: arrays mutables e inmutables con sus monadas. --*-
    - directory: operaciones para interactuar con archivos y directorios. ---*
    - ansi-wl-pprint: pretty printer con colores. -*--
# Default Extensions:
    - TupleSections: facilidad de crear cosas con tuplas ( , True) === \x -> (x, True). ****
    - MultiWayIf: ifs como guardas o cases. ****
    - FlexibleInstances: creacion de instancias flexibles. Para clases creo. *-**
    - LambdaCase: fuciona lambda functions con el cases, \case -> (x1->y1; x2->y2; ...; ). -**-
    - PatternSynonyms: parecido a renombre de tipos pero no se. *--*
    - StandaloneDeriving: permite "extender" los tipos con declaraciones dentro de un tipo. *--*
    - GADTs: Generalised Algebraic Data Types. *--*
    - DataKinds: extiende el sistema de kinds *. --*-
    - FlexibleContexts: creacion de clases mas complejas. --*-
