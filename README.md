# Tarea de Investigación: Explorando Git

## Preguntas:

1. **¿Qué es Git y para qué sirve?**

   Git es un una herramienta muy potente, rapida, agil y de sotware libre. tiene un sistema de trabajo con ramas que lo hacen especialmente potente. Estas ramas se destinan
   hacer proyectos divergentes de un proyecto principal, para hacer experimentos o para probar nuevas funcionalidades.
    
2. **¿Cuáles son las ventajas de usar Git?**

   unas de las ventajas de git es su sistema distribuido, que permite el trabajo incluso sin conexion
   -crear ramas y mezclarlas
   -superrapido y ligero
   -permite flujos de trabajo muy flexibles.

3. **¿Qué diferencia hay entre Git y GitHub/GitLab/Bitbucket?**

   Git es una herramienta de control de versiones que permite realizar todo tipo de operaciones para recuperar datos del servidor central y
   los otros son plataformas que ofrecen herramientas adiccionales, como gestion de proyectos CI, CD.

4. **¿Qué hacen los siguientes comandos Git?**:  
   `Git clone`: clona un repositorio en un directorio nuevo creado.
   
   `Git add`: Este comando actuliza el indice usando el contenido actual encontrado en el arbol de trabajo, para alistar el
 contenido preparado para la sgte confirmacion. ,

   `Git commit`: Crea una nueva confirmacion con el contenido actual del indice y el mensaje de bitacora dado que describe los cambios
   
   `Git push`:  Se encarga de transladar esos cambios al repositorio remoto.

   `Git pull`: Actualiza la version local de un repositorio desde otro remoto.
   
   `Git branch`: permite cambiar,  crear o eliminar ramas de un proyecto 

   `Git merge`: Es un comando del sistema de git que se utiliza para fusionar dos ramas o branches en una y guardar los cambios
   con seguridad

   `Git checkout`: Te permite desplazarte entre las ramas creadas por git branch.


5. **¿Qué es un repositorio y cuáles son los tipos de repositorios que existen?**

   Es un lugar donde puedes almacenar el codigo, los archivos y el historial de revisiones de cada archivo, Puede contar con
   multiples colaboradores y ser publico o privado.

   tipos de repositorios existentes:

   
-   Repositorios institucionales

-   Repositorios temáticos

-   Repositorios de datos

-   Repositorios científicos

-   Repositorios de objetos de aprendizaje

-   Repositorios de patrimonio cultural
      
6. **¿Qué son los "branch" en Git y para qué se utilizan?**

   Es una forma de separar el trabajo en curso de la base de codigo principal. Permite crear, listar o eliminar versiones del codigo del proyecto
   sobre el que estas trabajando, sin afectar la base del codigo principal. un branch de Git es una bifurcacion del estado del codigo que crea un nuevo camino
   para la evolucion del mismo.

7. **Describe un flujo de trabajo típico con Git.  (Ejemplo: Gitflow)**

   cd mi-proyecto
   git init
   git remote add origin https://github.com/Tzaziki0o/mi-proyecto.git
   git add .
   git commit -m "Subiendo mi proyecto inicial"
   git push origin main


8. **¿Qué es un "merge conflict" y cómo se resuelve?**

   Los conflictos de fusión ocurren cuando se hacen cambios contrapuestos en la misma línea de un archivo o cuando una persona 
   edita un archivo y otra persona borra el mismo archivo
   
   Para resolver un conflicto de fusión causado por cambios de líneas contrapuestos, 
   debes decidir qué cambios incorporar desde las diferentes ramas de una confirmación nueva
