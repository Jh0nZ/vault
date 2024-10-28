# Resolución de un problema

![[image 4.png|image 4.png]]

# Conjunto problema

- Ei→estado inicio
- S(x)→funcion sucesora→permite cambiar de estados
- PM→prueba meta→llegue al objetivo?
- CR→costo ruta→costo de la solucion optima seleccionada
- EE→espacio estado→estado,acciones→que acciones puedo ejecutar en mi estado actual?

Estado→descripcion de una situcaion en un tiempo t (estaticos)

detallar como quiera el diseñador

# Tipos de problemas

- Un solo estado
- Multiples estados
- Contingencia→existe probabilidad de estado
- Exploracion→no conocemos estados

# Busquedas

## Estructura

arboles, nodos, estados, hojas, margen de frontera, nivel, profundidad

## Parametros de evaluacion

1. Completitud→se completo al menos una ruta solución?
2. Optimidad→solución optima bajo criterio
3. Complejidad Temporal→costo temporal u/t
4. Complejidad Espacial→costo espacio u/e

### Costos

- Costo ruta→costo en linea→lo unico que ve el usuario
- Costo busqueda→costo fuera de linea→lo que no ve el usuario
- Costo total→Costo ruta+Costo busqueda

Formulo→busco→ejecuto

# Metodologias de busqueda

## Busquedas ciegas

No tenemos ninguna informacion para generar una ruta directa

### Primero en anchura

generar estados por nivel, desde el Em armamos la ruta en reversa (no recomendado si la solución es muy profunda)

### Primero en profundidad

encontrar la solucion en la rama principal haciendo uso de una pila

*generar el primer nivel en anchura

### Profundidad limitada

mejora de primero en profundidad, limitar el niel en profundidad→limite en 50 (un numero grande)→reduzco limite hasta no tener una solucion

### Liimite iterativo

limite→hasta donde construir el arbol

incremento→valor para incrementar el limite si no lo encontramos

*para el costo de ruta sumar todas las generaciones anteriores

### Costo uniforme

grafos, elegir el camino mas corto

## Busquedas heuristicas

cual sera la mejor siguiente accion o estado (bajo criterios)

Heuristica→Eureka (lo alcance)

formula, condicion, algoritmo, procedimiento, criterio→surge del analisis del problema

(como alcanzar y que quiero alcanzar)

- meta
- medida de rendimiento
- cuantitativa(rapido) o cualitativa(dificil subjetivo→necesitas criterios de pertenencia→cerca<1m)

cuantas heuristicas?→unica forma de evaluar un problema→existe posibilidad de plantear varias

### Avara

menor costo→tacaño→minimizacion heuristica

calcular heuristicas en cada estado→seleccionar el valor mas pequeño→expandirse hasta la meta

  

### a*

f=h(v)+g(v)

f=heuristica+Costo Ruta en el Margen

### Metodo constructivo/Propagacion de restricciones

### Reparacion heuristica/Minimizacion de conflictos

  

## Optimizacion de funciones

### Ascenso de colina

Iniciar en un Ei’ la primera vez como primero en anchura, plantear una función de evaluación, seleccionar al nodo con el valor del f(v) óptimo hasta encontrar Em

### Enfriamiento simulado

si un valor minimo se repite en varios niveles entro en duda para mi e🔼3, vuelvo donde tome una desicion

## Busqueda en juegos

### Minimax

### Poda alfa-beta

Si Alfa>= Beta=> Alfa=Alfa  
Si Alfa< Beta=> Alfa=Beta  

23 septiembre

![[1000082764.jpg]]

![[1000082773.jpg]]

![[1000082775.jpg]]

![[1000082776.jpg]]

![[1000082774.jpg]]

![[1000082762.jpg]]

![[1000082763.jpg]]

25 septiembre

![[1000083109.jpg]]

![[1000083108.jpg]]

![[1000083100.jpg]]

![[1000083094.jpg]]

![[1000083096.jpg]]

![[1000083099.jpg]]

![[1000083093.jpg]]