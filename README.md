# Componentes Arquitectura

## Tabla de contenidos
* [Introducción](#introduction)
* [Aceleradores](#acelerators)
* [Helpers](#helpers)
  * [Funciones](#functions)
  * [Interfaces](#interfaces)
* [Plugins](#plugins)
* [Contacto](#contact)
  * Colaborar
  * Reportar incidencias
  * Cómo conseguirlo
  * Peticiones


## <a name="introduction">Introducción</a>
Nos hemos dado cuenta que en muchos proyectos tenemos que hacer el mismo  trabajo una y otra vez. Cada implementación tiene sus errores y faltas y cuesta tiempo mantenerlos y hacerlos avanzar. Es por esto que nos surgió la pregunta ¿y si hiciéramos componentes que pudiéramos integrar en cualquier proyecto que tuviera la necesidad?
Con esta motivación hemos empezado a desarrollar este tipo de aceleradores y helpers, desde botones pequeños a aplicaciones completas. Tener estos componentes ayuda a reducir el tiempo de desarrollo de soluciones completas (parte del trabajo está hecho) y además están más depurados (al estar usándose en diferentes sitios se han ido corrigiendo errores reportados desde varias fuentes).


## <a name="acelerators">Aceleradores</a>
Los componentes desarrollados y listos de usar son los siguientes:
Parametric tables: componente de tablas paramétricas con clave/valor multilingüe con panel de administración
People Admin: componente para la administración de usuarios y grupos.
Distribution Lists: componente de listas de distribución. Cada lista de distribución tendrá destinatarios y se relacionan con modelos de proceso donde se lanzarán.
Process Launcher: lanzador de procesos con panel de administración para establecer permisos de visibilidad y estilos.

## <a name="helpers">Helpers</a>

Funciones y componentes de interfaz pequeños útiles para dar estilo o hacer comprobaciones de una manera rápida y limpia.
### <a name="functions">Funciones</a>
**VAO_IsNullOrEmpty**: comprueba si un input es nulo o vacío (sustituye a a!isNullOrEmpty)

**VAO_UnionArray**: Union seguro de arrays.

**VAO_CalculatePageElements**: Calcula los índices de los objetos para una página.

**VAO_CreateDictionaryFromArrays**: Crea diccionario desde arrays (keys y values).

**VAO_ValidateUsername**: Valida el nombre de un usuario
### <a name="interfaces">Interface snippets</a>
**VAO_Checkbox**: Checkbox made with icons. <img src="img/checkbox.gif" align="top" />

**VAO_CustomPaginator**: Paginador custom. <img src="img/customPaginator.png" align="top" />

**VAO_ToggleIcon**: Toggle para opciones/booleanos. <img src="img/toggle_crop.gif" align="middle" />

**VAO_Sidebar**: Sidebar con opciones.
## <a name="plugins">Plugins</a>

## <a name="contact">Contacto</a>
