# Ejercicio de Herencia Rutinas deportivas

## Personas

Las personas hacen distintas rutinas de ejercicios. 
Cuando realizan una rutina su peso baja una cantidad de kilos 
que depende de la cantidad de calorías que quema la rutina durante el tiempo 
en que la persona la practica. También depende de la cantidad de calorías 
que necesita una persona para bajar un kilo. Datos que se detallan a continuación.

### Personas sedentarias:

- Fórmula de peso: ` calorias que baja la rutina en el tiempo que la practica / kilosPorCaloría `

- La cantidad de kilosPorCaloría de las personas sedentarias es 7000

- El tiempo que ejercita una rutina se establece para cada persona

### Personas atletas

Las personas atletas tienen una fórmula parecida a la anterior, sólo 
que al entrenar además de bajar lo que indica la rutina consumen suficiente 
comida que le hace subir un kilo más. Por eso la fórmula de peso es levemente distinta:

- Formula de peso: ` (calorias que baja la rutina / kilosPorCaloría) + 1 `

- La cantidad de kilosPorCaloría de las personas atletas es 8000

- El tiempo que ejercita una rutina es siempre 90.

## Rutinas

En este sistema se contemplan 4 tipos de rutina: Running, Maratón, Remo y Remo
de competición.

Independiente de cual es la rutina, siempre la fórmula para saber cuántas
calorías baja una rutina depende del tiempo que se practique  y una intensidad
con la siguiente fórmula:

- `100 * (tiempo - descanso) * intensidad`

- El tiempo es algo que siempre se le dice a la rutina al momento de consultar cuantas calorías quema
, ya que depende de la persona (ver punto anterior)

- El descanso y la intensidad va depender del tipo de rutina

### Running

- La intensidad se establece para cada rutina en especial
- El descanso es de 5 minutos si el tiempo es mayor a 20, si no 2.

### Remo

- La intensidad es siempre 1.3
- El descanso es tiempo / 5

## Remo de competición

Es un tipo especial de Remo con las siguientes diferencias:

- La intensidad es siempre 1.7
- El descanso son 3 minutos menos de lo que se descansa en una rutina de normal. Pero
ojo, si ese valor es menor a 2, entonces es 2 (Tip: usar el método max de los números)


## Maratón

Es un tipo especial de Running con la siguiente diferencia:

- Las calorías que gasta siempre es el doble de una rutina de running común







