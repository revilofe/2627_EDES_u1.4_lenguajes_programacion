# EDES U1 P15 - Clasificación y características de los lenguajes

Plantilla de entrega para la práctica
[EDES-U1.-Practica015](https://revilofe.github.io/section3/u01/practica/EDES-U1.-Practica015/).

Este repositorio corresponde a un equipo de 3-4 personas. Completad este
`README.md`, añadid los archivos fuente que hayáis creado y conservad evidencias
reproducibles de las ejecuciones. No baséis la clasificación únicamente en las
etiquetas «compilado» e «interpretado»: indicad siempre la implementación o el
entorno considerado.

## 1. Identificación del equipo

| Dato | Valor |
|---|---|
| Grupo | <!-- Por ejemplo, P15-G01. --> |
| Integrante 1 | <!-- Username y nombre. --> |
| Integrante 2 | <!-- Username y nombre. --> |
| Integrante 3 | <!-- Username y nombre. --> |
| Integrante 4 | <!-- Username y nombre, si procede. --> |
| Reparto de roles | <!-- Edición, ejecución y registro de evidencias. --> |
| Fecha | <!-- Completa este dato. --> |

## 2. Itinerario y entorno

Elegid el itinerario asignado:

- [ ] Itinerario A: C y Python.
- [ ] Itinerario B: Java y JavaScript.

| Herramienta | Versión | Sistema o entorno |
|---|---|---|
| Sistema operativo |  |  |
| Editor o IDE |  |  |
| Primera herramienta del itinerario |  |  |
| Segunda herramienta del itinerario |  |  |
| Entorno web, navegador o Node.js, si procede |  |  |

Incluid los comandos usados para consultar las versiones, por ejemplo
`gcc --version`, `python --version`, `javac --version`, `java --version` o
`node --version`.

## 3. Misma suma en dos lenguajes

Los dos programas deben calcular `5 + 7` y mostrar `12`. Conservad en el
repositorio los archivos fuente correspondientes al itinerario.

### 3.1. Archivos y comandos

| Lenguaje | Archivo | Comando de traducción o ejecución | Resultado |
|---|---|---|---|
|  |  |  |  |
|  |  |  |  |

Escribid los comandos exactos y explicad qué herramienta interviene antes y
durante la ejecución.

```text
<!-- Comandos ejecutados y salida inicial. -->
```

### 3.2. Comparación del proceso

- ¿Qué comando o herramienta transforma el código antes de ejecutarlo?
- ¿Qué archivo o representación intermedia se obtiene, si se puede observar?
- ¿Qué entorno debe estar disponible para ejecutar el programa?
- ¿Qué diferencias habéis observado entre editar, traducir y ejecutar?

**Respuesta del equipo:**

<!-- Escribid una explicación razonada. -->

### 3.3. Comprobación de errores

Si habéis realizado la comprobación opcional, describid el error introducido, el
diagnóstico, la corrección y el momento en que se detectó. Diferenciad un error
sintáctico de un error que aparece durante la ejecución.

**Respuesta:**

<!-- Documentad la prueba o indicad que no se realizó. -->

## 4. Abstracción y bajo nivel

Completad la comparación entre Python o Java, C y el fragmento de ensamblador:

```asm
MOV AX, 5
ADD AX, 7
MOV BX, AX
```

El fragmento representa instrucciones de estilo Intel/x86 para analizar la
cercanía a la máquina. No es un programa completo que deba ejecutarse tal cual.

| Aspecto | Python o Java | C | Ensamblador del ejemplo |
|---|---|---|---|
| Nivel de abstracción relativo |  |  |  |
| Operación y resultado expresado |  |  |  |
| Registros o detalles de máquina visibles |  |  |  |
| Portabilidad y herramientas necesarias |  |  |  |

Explicad por qué «C es de bajo nivel» es una descripción relativa e incompleta.

**Respuesta:**

<!-- Escribid la explicación. -->

Indicad también dos ventajas y dos limitaciones de los niveles comparados, y
relacionadlas con un contexto concreto.

## 5. Estilos y paradigmas

### 5.1. Orientación a objetos

Documentad la ejecución de `Main.java` y la salida `Velocidad: 10`.

- Clase identificada:
- Objeto creado:
- Atributos:
- Método que cambia el estado:
- Salida obtenida:

```text
<!-- Comandos y salida de la ejecución. -->
```

### 5.2. Función pura

Documentad la ejecución de `suma_funcional.py` y la salida `12`.

- Entradas de la función:
- Valor devuelto:
- Estado externo modificado:
- Motivo por el que se considera pura en este ejemplo:

```text
<!-- Comandos y salida de la ejecución. -->
```

### 5.3. Comparación

Explicad qué cambia al conservar estado en un objeto frente a devolver un valor
desde una función. Recordad que Java y Python son lenguajes multiparadigma.

**Respuesta:**

<!-- Escribid la comparación. -->

## 6. Clasificación razonada

Completad una fila por lenguaje. Indicad la implementación o el entorno
considerado y evitad afirmaciones absolutas.

| Lenguaje | Implementación o entorno | Ejecución observada o habitual | Abstracción relativa | Paradigmas posibles | Uso representativo |
|---|---|---|---|---|---|
| C |  |  |  |  |  |
| Python |  |  |  |  |  |
| Java |  |  |  |  |  |
| JavaScript |  |  |  |  |  |
| Ensamblador |  |  |  |  |  |

## 7. Recomendación técnica

Elegid un escenario:

- [ ] Firmware de un sensor con recursos limitados.
- [ ] Aplicación web con interacción en el navegador.
- [ ] Prototipo de análisis de datos.

Lenguaje recomendado:

<!-- Escribid el lenguaje o combinación elegida. -->

Razón 1:

<!-- Relacionadla con requisitos, ecosistema o mantenimiento. -->

Razón 2:

<!-- Relacionadla con requisitos, ecosistema o mantenimiento. -->

Limitación de la recomendación:

<!-- Explicad cuándo dejaría de ser una buena elección. -->

## 8. Prácticas generales de trabajo

Identificad al menos cinco prácticas transferibles. Cada una debe incluir una
evidencia de esta actividad y el error que ayuda a prevenir.

| Práctica | Evidencia observada | Error que ayuda a prevenir |
|---|---|---|
|  |  |  |
|  |  |  |
|  |  |  |
|  |  |  |
|  |  |  |

## 9. Evidencias y reflexión

Incluid capturas o transcripciones de las salidas, versiones, comandos y
diagnósticos. Si una herramienta web oculta una etapa, explicadlo y aportad la
evidencia que sí sea posible conservar.

```text
<!-- Enlaces a capturas o transcripciones. -->
```

Reflexión final del equipo:

<!-- Explicad qué habéis aprendido sobre ejecución, abstracción, paradigmas y
clasificación de lenguajes. -->

## 10. Lista de comprobación

- [ ] Hemos identificado al equipo, el itinerario y el entorno.
- [ ] Hemos conservado los archivos fuente creados.
- [ ] Hemos registrado comandos, versiones y salidas de los dos lenguajes.
- [ ] Hemos comparado Python o Java, C y ensamblador.
- [ ] Hemos analizado orientación a objetos y función pura.
- [ ] Hemos clasificado C, Python, Java, JavaScript y ensamblador con matices.
- [ ] Hemos recomendado un lenguaje para un escenario y explicado una limitación.
- [ ] Hemos documentado al menos cinco prácticas generales con evidencias.
- [ ] Hemos añadido las conclusiones y evidencias del equipo.
