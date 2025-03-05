# Agentes Inteligentes
![[image 3.png]]

Cualquier cosa capaz de percibir su medio ambiente con la ayuda de sensores y actuar en ese medio utilizando actuadores

# Medida de desempeño

Russell & Norvig estudiaran desde su visión de la obtención del máximo de su Medida de desempeño.
**Qué?** →META→Lo que se quiere lograr
**Cómo?** →Unidad→rapido d/t, maximo recorrido \>d \<t 
**Cuándo?** Luego de varias pruebas-largo plazo  
**Quién?** →Autoevaluacion, evaluacion, (diseñador, experto, usuario final)

Tabla P→A conocimiento que puso el diseñador
## Características
### Racionalidad (PRR)

depende de 4 características:
1. Medida éxito desempeño
2. Historial de percepciones
3. Acciones que puede ejecutar
4. Conocimiento del entorno

| Percepciones | Acciones |
| ------------ | -------- |
| P1           | A1       |
| P2           | A2       |
| P3           | A1       |
| …            | …        |
| Pn           | Am       |
Más P→A, agente racional ideal, sistemas expertos
inferencia→analizar→conclusión→acción
### Autonomía

Base de conocimiento→mínimo que sabe el agente→lista creada por el diseñador

Autónomo→no depende del diseñador

Motor de aprendizaje→aprender ante lo desconocido

- identificar algo nuevo
- aprender
- adaptarse

Agente inteligente

Nunca se genera nuevas acciones❌, solo nuevas percepciones

# Estructura

- Hardware→Mecánica, física, equipo completo
- Software→Algoritmos, DB, subprogramas

Pantalla→Actuador

Teclado, mouse→sensores

ejemplo→agente para podar arbustos

# Descriptores

## PAMA

|   |   |
|---|---|
|Percepcion|arbustos crecidos|
|Accion|podar|
|Meta|jardin podado|
|Ambiente|jardin|
## REAS

|   |   |
|---|---|
|Rendimiento|\#arbustos podados|
|Entorno|jardin (ambiente)|
|Actuadores|brazo robotico [tijeras, podadora, ruedas]|
|Sensores|camara, sensor movimiento|
## P→A

|   |   |
|---|---|
|Percepciones|Acciones|
|arbustos credidos|podar|
|arbusto podado|muevo|
|piedra|evado|
|animal|espero|
|grifo|siguiente arbusto|
|otherwise|no hacer nada o al motor de aprendizaje|

# Tipos de entornos

1. Completamente observable→Acceso completo a toda la información del entorno en todo momento
    
    Parcialmente observable→El agente solo tiene acceso a parte de la información
    
2. Deterministas→El próximo estado del entorno está completamente determinado por el estado actual y la acción del agente
    
    Estocásticos→Hay elementos de incertidumbre, y las acciones pueden no llevar siempre al mismo resultado.
    
3. Episódicos→Las decisiones del agente son independientes entre sí, y cada acción no afecta las futuras
    
    Secuenciales→Las acciones anteriores del agente afectan el estado futuro del entorno y las decisiones futuras
    
4. Estático→El entorno no cambia mientras el agente toma decisiones.
    
    Dinámico→El entorno cambia mientras el agente está tomando decisiones
    
5. Discreto→El entorno tiene un número finito de estados y acciones que el agente puede realizar
    
    Continuo→Las acciones y estados son continuos, lo que significa que pueden tener un rango infinito de valores
    
6. Agente Individual→Solo hay un agente que toma decisiones y actúa en el entorno
    
    Multiagente→Existen múltiples agentes que interactúan entre sí, lo que puede involucrar cooperación o competencia, no necesariamente se comunican o trabajan juntos
    
# Tipos de agentes

1. Orientados a utilidad→criterio de utilidad→usuario feliz, de la mejor manera

## Segun Russell & Norvig

Russell & Norvig estudiaran desde su visión de la obtención del máximo de la medida de desempeño

1. Racionales/Reactivos→reaccionan ante una percepción P→A, en tiempo especifico, entorno estático, controlado
2. Bien informados→ademas de tabla P→A consideran tiempo pasado, la mejor acción
3. Orientados a meta→rutas (lista de acciones) para llegar a la meta, seleccionar la mejor opción
4. Aprenden→motor de aprendizaje

## Segun Nwana

Nwana (1998) estudiara los agentes desde su visión de habilidades sociales de su interacción con usuarios y otros agentes

Nwana→social-comunicacion

### Caracteristicas

- Racional→hacer lo correcto
- Proactivos→iniciativa de acciones ante percepciones extrañas
- Comunicarse→social
- Adaptarse→generar acciones ante eventos extraños
- Autonomos→no depende del diseñador

### Dimensiones

1. Movilidad (Estáticos/Móviles)
2. Colaboración (Deliberativos, reactivos)
3. Rol (Información/Internet)
4. Tres atributos (Autonomía, Aprendizaje, Cooperación)

![[image 1.png]]

  

# Definiciones