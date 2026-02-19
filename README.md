[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/KDSjTOkm)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=22736036&assignment_repo_type=AssignmentRepo)
# Actividad obligatoria Unidad 3 - Tarea RA3. Detección y corrección de vulnerabilidades de aplicaciones web


**Índice**

[Objetivos](#objetivos)

[Resultados de aprendizaje y Criterios de Evaluación](#resultados-de-aprendizaje-y-criterios-de-evaluación)

[Desarrollo](#desarrollo)

[Entrega](#entrega)


---
# Objetivos

- Saber manejar las principales listas en fuentes abiertas sobre vulnerabilidades, debilidades, etc., saber relacionarlas y  extraer información de ellas.
- Saber aplicar el estandar ASVS e identificar las comprobaciones a realizar en una aplicación según el nivel de seguridad de la misma.

---
# Resultados de aprendizaje y Criterios de Evaluación

Esta actividad se relaciona con el resultado de aprendizaje y criterios de evaluación RA 2 a, b,c y d.

---
# Desarrollo

Lee la tarea hasta el final para ver lo que tienes que entregar e ir cogiendo las evidencias y ver lo que tienes que documentar.

## Clonar repositorio de la tarea.

Utilizaremos `GitHub Classroom` para la entrega de esta actividad.

- Usa el siguiente código de invitación para la tarea en `GitHub Classroom`: <https://classroom.github.com/a/KDSjTOkm> y acepta la invitación:

![](./docs/images/tu3.png)

Puedes acceder a la tarea desde el enlace de `github` o clonando el repositorio desde `Visual Studio Code`.

![](./docs/images/tu31.png)

Si le das a Acceder con Visual Studio Code, tendrás que dar a permitir abrir, enlaces, descargar extensiones para vscode, etc.....

![](./docs/images/tu32.png)

- Si le das al repositorio, te llevará a tu repositorio. Te habrá creado un repositorio en tu espacio personal que tendrás que modificar.


![](./docs/images/tu33.png)

- Desde mi panel de control tendré acceso a tu repositorio, o sea que ya no tendrás que poner tu repositorio como público.

-

## Apartado 1 -  Actividad: Creación del entorno de Pruebas.

Crea el [entorno de pruebas indicado en la actividad](../Actividad-CreacionEntornoPrueba/README.md).
Crea un archivo en `MarkDown` con nombre `CreaciónEntornoPrueba.md` donde **brevémente**, expliques cómo has creado el entorno de pruebas e incorpore capturas de pantalla donde se pueda ver la que se ha creado correctamente.


## Apartado 2 - Vulnerabilidades de inyección de datos de entrada.

Realiza alguna de las actividades que tienen que ver con **vulnerabilidades de inyección de código** o de **otros tipos vulnerabilidades de entrada**.

Crea un documento en `Markdown` con nombre `ActividadVulnerabilidadesDatosEntrada.md` donde pegarás las capturas de pantalla que evidencien la realización de:

- Estado inicial y vulnerabilidad.
- Solución o mitigación 1 implementeada,(no es necesario poner todos los pasos).
- Solución o mitigación 2 implementeada.
...
- Incorpora tambien un par de lineas para cada solución implementada, indicando qué medidas hemos tomado para securizar o mitigar los ataques.


## Apartado 3 - Actividad de Autenticación, vulnerabilidades de gestión de sesiones, protección de datos sensibles o Control de acceso.

Realiza alguna de las actividades que tienen que ver con vulnerabilidades que tienen que ver con **Autenticación y vulnerabilidades de gestión de sesiones**  o de **Protección de datos sensibles y Control de acceso**.

Crea un documento en `Markdown` con nombre `ActividadAutenticacion.md` donde pegarás las capturas de pantalla que evidencien la realización de:

- Estado inicial y vulnerabilidad.
- Solución o mitigación 1 implementeada,(no es necesario poner todos los pasos).
- Solución o mitigación 2 implementeada.
...
- Incorpora tambien un par de lineas para cada solución implementada, indicando qué medidas hemos tomado para securizar o mitigar los ataques.

## Apartado 4 - Actividad sobre errores en la Seguridad y componentes vulnerables.

Realiza alguna de las actividades que tienen que ver con vulnerabilidades que tienen que ver con **errores en la seguridad y componentes vulnerables**.

Crea un documento en `Markdown` con nombre `ActividadSeguridad` donde pegarás las capturas de pantalla que evidencien la realización de:

- Estado inicial y vulnerabilidad.
- Solución o mitigación 1 implementeada,(no es necesario poner todos los pasos).
- Solución o mitigación 2 implementeada.
...
- Incorpora tambien un par de lineas para cada solución implementada, indicando qué medidas hemos tomado para securizar o mitigar los ataques.

## Apartado 5 - Escaneo estático y dinámico de una aplicación web.

Tienes en la carpeta `app` una [aplicación spring java con nombre store_app](./files/store-app.zip).

1. Realiza sobre ella un Análisis Estático de Código  (SAST) con la herramienta `SonarQube`.
1. Crea un contenedor docker donde se ejecute la aplicación.
1. Realiza un Análisis de Seguridad con una herramienta DAST (Nessus o OwASP ZAP)
1. Con los resultados del análisis estático y dinámico realiza una tabla con al menos 5 problemas en los que indicarás:

| - Vulnerabilidad     | Nombre/breve descripción de la vulnerabilidad    |
|----------------------|--------------------------------------------------|
| - CWE                | Código CWE y nombre                              |
| - Consecuencias      | Qué riesgos puede provocar la vulnerabilidad     |
| - Localización       | Archivos de la aplicación a los que afecta       |
| - Exploit(s)         | Como se “ataca” la aplicación                    |
| - Solución           |Modificaciones realizadas en la aplicación para resolver la vulnerabilidad   |
| - Otra información     | Lo que consideres necesario para aclarar la vulnerabilidad |

Vamos desgranando los pasos sobre todo la compilación y creación del contenedor con Docker:

### Compilación de la aplicación.



---
# Entrega

## Indicaciones de entrega

Crea un repositorio privado en Github con nombre **Unidad3-TareaRA3-TuNombre** y lo compartes con el profesor en modo de sólo lectura.

> Observa que al ser repositorio privado, te va a dar error al configurar `GitHub Pages`. Para esto puedes **cambiar el repositorio a público** únicamente cuando configures `Github Pages` o quieras ver el resultado. Después asegúrate que vuelve a ser privado.

Publicarás el repositorio en `GitHub Pages` al igual que hicimos en las otras tareas.

> Recuerda añadir toda la estructura de `mkdocs`, `requeriments.txt` y el `workflow` de `GitHub Actions` para que se genere la documentación en `GitHub Pages`.
> Recuerda, que como he comentado antes, mientras el repositorio es privado, pueden fallar el `workflow`.
>> Con php podemos crear un servidor web para visualizar los archivos creados: `php -S 0:8080` nos muestra el contenido web del directorio actual, por lo que si yo estoy en la rama `gh-pages` debería de mostrarse lo mismo que en `github.io`.

Una vez realizada la tarea, el envío se realizará a través de la plataforma.
Deberás de entregar al menos:

- El **repositorio** que has creado, **comprimido** en un archivo.
- El **enlace** a tu repositorio en la página de `github.com`.
- Revisa que has añadido como colaborador en tu repositorio de GitHub al profesor: `PPSvjp` **Settings** > **Collaborators**.

La documentación en `GitHub Pages` debe de contener al menos:
- Archivo **Index.md** con enlace al resto de secciones.

- Las siguientes **secciones**:

    - **Apartado 1: Creación del entorno de Pruebas.**: donde figure la documentación realizada en el [apartado 1](#apartado-1----actividad-creación-del-entorno-de-pruebas).

    - **Apartado 2 - Actividad de vulnerabilidades de inyección de datos de entrada**: donde figure la documentación realizada en el [apartado 2](#apartado-2---vulnerabilidades-de-inyección-de-datos-de-entrada).

    - **Apartado 3 - Apartado 3 - Actividad de Autenticación, vulnerabilidades de gestión de sesiones, protección de datos sensibles o Control de acceso**: donde figure la documentación realizada en el [apartado 3](#apartado-3---actividad-de-autenticación-vulnerabilidades-de-gestión-de-sesiones-protección-de-datos-sensibles-o-control-de-acceso).

    - **Apartado 4 - Actividad sobre errores en la Seguridad y componentes vulnerables**: donde figure la documentación realizada en el [apartado 4](#apartado-5---escaneo-estático-y-dinámico-de-una-aplicación-web).

    - **Apartado 5 - Escaneo estático y dinámico de aplicación web**: donde figure la documentación realizada en el [apartado 5](#apartado-5---escaneo-estático-y-dinámico-de-una-aplicación-web).


El archivo comprimido se nombrará siguiendo las siguientes pautas:

`PPS-Unidad3-TareaRA3-Apellido1_Apellido2_Nombre`

Asegúrate que el nombre no contenga la letra ñ, tildes ni caracteres especiales extraños. Así por ejemplo la alumna Begoña Sánchez Mañas para la primera unidad del MP de PPS, debería nombrar esta tarea como...

PPS-Unidad3-TareaRA3-sanchez_manas_begona

## Calificación de la tarea

La puntuación de los apartados es la siguiente:

Si **no se adjunta el repositorio comprimido, no se indica la documentación del repositorio en github.io o no se añade como colaborador en el repositorio al profesor**, la tarea será **calificada como 0**

> NOTA IMPORTANTE
>
> Aquellos apartados/subapartados en los que las capturas de pantalla no sean claras o no tengan como fondo de pantalla la plataforma con tu usuario mostrando claramente la foto de tu perfil, no serán corregidos.

En el resto de los casos, la puntuación de los apartados es la siguiente:
**Apartado 1**- Actividad: Creación del entorno de Pruebas. Con un máximo de 1 punto.

**Apartado 2** - Actividad Vulnerabilidad de datos de entrada. Con un máximo de 1 punto.

**Apartado 3** - Actividad de Autenticación, Gestión de sesiones o Control de acceso. Con un máximo de 1 punto.

**Apartado 4** - Actividad sobre Errores en la Seguridad o componentes vulnerables. Con un máximo de 1 punto.

**Apartado 5** - Análisis estático y dinámico de aplicación web. Con un máximo de 4 puntos.

**Documentación**: presentación, extensión, exactitud, riqueza en síntaxis de MarkDown, etc de la documentación del repostorio. Con un máximo de 2 puntos.

Para superar la tarea habrá que conseguir 5 puntos o más.

---
[![Licencia: CC BY-NC-SA 4.0](https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
