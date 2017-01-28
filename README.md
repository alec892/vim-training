<p align="center">
  <img src="https://cloud.githubusercontent.com/assets/25358716/22319543/b313ec52-e351-11e6-9bf9-12b062e1d6f9.png">
</p>

Vim es un editor de texto muy potente que nos ayuda a realizar cambios muy eficientemente. Y aunque la curva de aprendizaje es alta por la gran cantidad de comandos que tiene, al dominarlos nuestra productividad a la hora de desarrollar aumentara.

## Getting Started

### Modos de Vim

 * __Modo Inserción:__ Permite editar el texto como cualquier otro editor. Se ingresa a este modo con la tecla `i`.
 * __Modo Normal:__ Se ingresa a este modo con la tecla `Esc`. Este modo provee formas para navegar y manipular texto.
 * __Modo Visual:__ Se ingresa a este modo con la tecla `v`. En este modo puedes seleccionar el texto y manipular lo seleccionado.
 
### Movimientos del Cursor

```shell    
      ^                 
      k                  1. La tecla h mueve el cursor a la izquierda
  <h     l>              2. La tecla l mueve el cursor a la derecha
      j                  3. La tecla k mueve el cursor hacia arriba
      v                  4. La tecla j mueve el cursor hacia abajo
```
## Comandos para Insertar

|Command        |Description                                |
|:-------------:|-------------------------------------------|
|`i`            |insetar en la posicion actual              |
|`shift + i`    |inserta al inicio de la linea              |
|`a`            |inserta despues de la ubicacion actual     |
|`shift + a`    |inserta al final de la linea               |
|`o`            |inserta una linea debajo de la linea actual|
|`shift + o`    |inserta una linea encimade la linea actual |
