# Pipeline 
- operações em streams retornam novas streams. Então é possível criar uma cadeia de operações (fluxo de processamento).

## Operações intermediárias e terminais
  O pipeline é composto por zero ou mais operações intermediárias e 
uma terminal.

## Operação intermediária: 
  Produz uma nova streams (encadeamento).<br/>
  Só executa quando uma operação terminal é invocada (lazy evaluation).
### Operações intermediárias
- filter
- map
- flatmap
- peek
- distinct
- sorted
- skip
- limit (*)

## Operação terminal: 
  Produz um objeto não-stream (coleção ou outro).<br/>
  Determina o fim do processamento da stream.
### Operações terminais
- forEach
- forEachOrdered
- toArray
- reduce
- collect
- min
- max
- count
- anyMatch (*)
- allMatch (*)
- noneMatch (*)
- findFirst (*)
- findAny (*)

