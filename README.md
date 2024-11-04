```
El sistema operativo básico estáhecho de los siguientes tres componentes:
  1.- Bootloader(Syslinux)  2.- Kernel  3.- User space (BusyBox)
El boot carga al kernel, y el kernel carga a BusyBox.
Pasos que seguí:
  Primero instalé cwl y docker en Windows. 
  Después seguí los pasos detallados por un usuario de YouTube llamado "Nir Lichtman" los cuales detallaré en un archivo aparte.
  Una vez construido la distribuición, logré bootearlo y acceder a las opciones básicas que BusyBox ofrece.

Al concluir esta primera prueba, decidí seguir con el siguiente paso: Crear una distribuición gráfica.
Una distribuición gráfica es algo distinta a la anterior, añadiendo un componente extra:
   1.- Bootloader(Syslinux)  2.- Kernel  3.- User space (BusyBox) 4.- Window manager (En este proyecto se usará microwindows.
Este proyecto es técnicamente más complejo, así que, en este momento sigo trabajando en ello pero prontó subiré el proceso.

Mi proyecto final creo que será tener un USB booteable ya sea del primer o segundo sistema operativo.
```
