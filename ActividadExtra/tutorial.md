---

marp: true
author: Carlos Villaseñor
size: 4:3
theme: gaia

---

# Tutorial

### Carlos Miguel Villaseñor Venegas
#### Práctica 9 POO
##### Marp for VS Code
##### Markmap
##### PlantUML Previewer

---

# Marp for VS Code
En este programa es donde se esta creando esta presentación, haciendo uso de el lenguaje Markdown, algunas de las posibles modificaciones que se pueden hacer son :

---

#### Listas / Viñetas
- Viñeta 1
- Viñeta 2
    - Viñeta 2.1
    - **negritas**
    - *italicas*
    - ~~tachado~~~ 
    - `quoted`

---

#### Imagenes
![Markdown](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/2560px-Markdown-mark.svg.png)

---

#### Imagenes ajustadas
![width:800px height:550px](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/2560px-Markdown-mark.svg.png)

---

#### Imagenes descargadas
![width:800px](MarpforVSCode.jpg)

---

#### Hipervinculos

<https://www.unam.mx>
<correo@dominio.com>

Yo estudio en la [UNAM](https://www.unam.mx)

---

#### Tabla

|Tit 1|Tit 2|Tit 3|
|---|---|---|
|espacio (0,0)|espacio (0,1)|espacio (0,2)|
|espacio (1,0)|espacio (1,1)|espacio (1,2)|

---

# Markmap
Esta aplicación nos sirve para crear mapas que muestren una jerarquía entre varios elementos.

Utilizando # podemos maracar la jerarquía entre los elementos 



Para ver el diagrama ejemplo ir a el archivo "MapaPerro"

---

# PlantUML Previewer

Con este programa se pueden crear diagramas de flujo y diagramas de clase.
Los diagramas de clase empiezan con el comando @startuml y terminan con el comando @enduml.
Entre estos dos comandos podemos crear packetes, clases normales y abstractas, e interfaces
Para cada una de ellas se tiene que poner el tipo de clase seguido de unas llaves y dentro de estas agregarle sus atributos y métodos.

---

Si se quiere indicar que un conjunto de clases están dentro de un paquete, estas se tienen que crear dentro de las llaves del paquete.
Si se quiere crear las flechas de una clase a otra que indiquen la herencia entre ellas, se tiene que poner:  la clase a la que quieres llegar"<|--" la clase de la que sale la flecha.

Para crear un diagrama de flujo igual se tiene que inicial con "@startuml" y terminar con "@enduml", además se tiene que incluir un "start" y un "end" al inicio y al final del diagarama.

---

Adentro se colocan las ordenes que se quiere ilustrar tomando en cuenta las siguientes reglas:
- Se colocan ":" para crear un nuevo elemento
- En las condiciones se tiene que indicar cuando terminen de la forma "end" y el tipo de instrucción que se detiene 
- Después de cada instrucción que no de inicio a una iteración o condición se coloca n ";".
