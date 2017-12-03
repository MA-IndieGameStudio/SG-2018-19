# Sony Game Project - 2018/19

## Prerrequisitos para participar

### Software

Distinguimos dos roles dentro del equipo: programador y modelador. El software que deberá instalar en su ordenador personal para poder participar, dependerá de si quiere contribuir programando o modelando:

* Programador:
  * Motor del juego: [CryEngine](https://www.cryengine.com/).
  * Entornos de programación: [Visual Studio Community](https://www.visualstudio.com/es/downloads/) (recomendado) o [Notepad ++](https://notepad-plus-plus.org/download/v7.5.2.html).
* Modelador: [3ds Max](https://www.autodesk.es/products/3ds-max/overview), [Blender](https://www.blender.org/), etc. (libre elección).
* Todos: Software del estudio para cuestiones de organización, etc.

Nota: CryEngine y Visual Studio Community son gratuitos, además de Blender y Notepad++. Se le entregará una copia del software del estudio, así como una credencial intransferible.

### Aptitudes básicas en programación

A cada programador se le dará una copia de [CryENGINE Game Programming with C++, C#, and Lua](https://www.amazon.es/CryENGINE-Game-Programming-Filip-Lundgren-ebook/dp/B00GUKM79Q). No obstante, deberá conocer de antemano los siguientes lenguajes:

* C++ y/o C# a nivel intermedio (C# es similar a Java y sabiendo éste último es muy fácil aprender C#).
* Lua a nivel básico (https://www.lua.org/manual/5.1/es/manual.html).
* XML a nivel básico (https://www.w3schools.com/xml/).

Nota: Es recomendable conocer las librerías de CryEngine, el editor y su funcionamiento, en general.

Nota 2: Si no se conoce Lua o XML, pero si C++ y/o C#, se puede participar, pero debe saberse al menos lo básico de Lua o XML (reconocer si el código es de uno de estos lenguajes, estructura, etc).

## Metodología de programación

Dado que cada programador dispone de una copia del proyecto base y trabaja sobre dicha copia, surge el problema de combinar el trabajo de uno con el de otro, ya que no podemos trabajar sobre un mismo proyecto en la nube (concurrencia). Para solventar esto, sincronizaremos los proyectos en todos los ordenadores antes de finalizar una release o lanzamiento.

### Formato de las versiones
```
<ID Fase de desarrollo>.<ID Subetapa de la fase de desarrollo>.<Release o lanzamiento>
```
La siguiente tabla recoge las IDs de cada una de las fases de desarrollo:

| Etapa               |  ID |
|---------------------|-----|
| Pre-Alpha           |  0  |
| Alpha               |  1  |
| Beta                |  2  |
| Comercializado      |  3  |

Por ejemplo, la versión 1.12.2 significa: 2ª release de la subetapa 12 de la fase alpha.

Una etapa puede estar dividida en subetapas, por ejemplo: IA (subetapa 5), vehículos (subetapa 6), etc. Sirven para indicar la temática
de los lanzamientos (privados o disponibles en forma de actualización). 

### Sincronización de proyectos

Para poder sincronizar los proyectos fácilmente, asignaremos a cada programador una tarea y un nombre para su layer. El programador solo podrá modificar las entidades que pertenezcan a su [layer](http://docs.cryengine.com/display/SDKDOC2/Using+Layers#UsingLayers-LayerControl).

Cuando termine su tarea, lo notificará y aportará en un zip, la layer exportada (.lyr) y los códigos que haya modificado o creado. Además debe adjuntar un README, en el que explique qué ha hecho y cómo.

Nota: Podrá modificar un código si y solo si se le autoriza. En caso de que borre algún script o lo modifique sin querer, puede solicitar que se le reenvie.
