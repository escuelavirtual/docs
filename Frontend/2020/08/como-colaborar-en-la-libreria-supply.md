# Como colaborar y/o programar en la libreria [Supply][supply-github]

> [Jheyson Saavedra][perfil-github] <br/>
> 18 de agosto el 2020

En este articulo donde veremos como un programador puede contribuir a la elaboracion y creacion de la libreria [supply-tools][supply-npm], Esta libreria sirve para aplicar estilos a proyectos desarrollados con tecnologias web's. Para poder participar hay que tener en cuenta ciertas reglas las cuales son las siguientes:

- El tamano de los tabs debe ser de 2 espacios
- respetar la ubicacion de archivos del core y sus directorios
- No se permiten clases de css o sass con mas de 50 caracteres
- No se permite clases con caracteres espciales como: `!@#$%^&*()+|"?<>`
- Todas las fuentes que se importen deberan venir de [Google Fonts](https://fonts.google.com)
- Las fuentes que no provengan de google fonts deben estar en formato `.otf` o `.ttf`

La libreria esta escrita principalmete en sass y se compila a css. Debemos compilar nuestra colaboracion al hacer pull request, existe algo llamado el "core" de la app que son ciertos archivos de la libreria que contienen lo basico y lo mas importante de esta libreria esos archivos estan en esta ruta `src/sass/`, esos archivos son principalmente dos (por ahora) son los siguentes:

1. `_color.scss` contiene los colores de la libreria en sus clases
2. `_fonts.scss` contiene todas las fuentes posibles para el uso de la libreria

Ahora voy a explicar como se trabaja en esos dos archivos y en los demas en general, y luego explicare sobre los demas tipos de archivos:

- `_color.scss`: En este achivos se especifican los colores a poder usar en la librera un ejemplo seria

```css
.color-background-purple {
  background-color: #888317A;
}
```

todas las clases deben tener un nombre descriptivo pero no muy largo para su facil uso

- `_fonts.scss`: en este archivo de sass se establecen todas las fuentes posibles para usar pueden ser tanto fuentes web como fuentes no webs es decir que no vengan de google fonts.
  En el caso de que se quiera agregar fuentes que no provengan de google fonts deben colocarse en el directorio `src/assets/fonts/`

Contribuidores al articulo:

<!-- el formto debe ser el siguiente
> [NOMBRE_DEL_CONTRIBUDOR](enlace a su github)
> fecha de su colaboracion <br/>
 -->

<center>© Copyright 2020 - Jheyson Saavedra & Explandy - All right reserved</center>

[perfil-github]: https://github.com/JheysonSaavedra
[supply-github]: https://github.com/escuelavirtual/supply-tools
[supply-npm]: https://github.com/escuelavirtual/supply-tools/package
