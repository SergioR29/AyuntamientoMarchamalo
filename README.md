# COLABORACIÓN CON EL AYUNTAMIENTO DE MARCHAMALO 🏛️🏢

Desarrollo colaborativo de una solución de escritorio compatible con Windows para optimizar procesos manuales de gestión de información de los empleados destinada al personal de RRHH. Proyecto presentado en redes sociales y producto final puesto en producción actualmente.  
  
Funciones:  
  
- Evaluación de los empleados.  
- Gestión de competencias.  
- Generación de informes de desempeño y del listado de las notas medias de todos los empleados en PDF.  
- Visualización de ayuda práctica para el usuario en el uso de la aplicación.  
- Exportación masiva de datos de los empleados en un fichero CSV que puede ser visualizado manualmente en Excel.  
- Función que permite dar de baja al empleado seleccionado.  
- Gestión de los empleados dados de baja y posibilidad de eliminar la baja de cada uno por separado.  
- Visualización de las personas que cumplen trienio en los próximos 30 días.  
- Configuración de notificaciones por correo electrónico en el que se pueden añadir hasta 3 emails destinatarios, marcar una casilla para activar un aviso de cumplimiento de trienio al enviar el correo y pulsar un botón para enviar un correo de trienios mediante el protocolo SMTP.  
- Botón para recargar la información de nuevo en la tabla de empleados de la pantalla principal y en la de los empleados dados de baja.  

![icono](https://github.com/user-attachments/assets/bbb46556-8048-4ffd-82fa-56f60876f87c)

Noticia en las redes sociales del ayuntamiento:  
  
<div>
  <a href="https://www.instagram.com/p/DKb6KS6M-bp/?utm_source=ig_web_copy_link&igsh=MzRlODBiNWFlZA==" style="text-decoration: none;"><img src="https://skillicons.dev/icons?i=instagram" alt="Instagram" style="width:45px;height:45px;"/></a>&nbsp;&nbsp;
  <a href="https://www.facebook.com/AytoMarchamalo/posts/-el-ayuntamiento-y-el-ies-brianda-de-mendoza-colaboran-para-desarrollar-nuevo-so/1148917313932060/" style="text-decoration: none;"><img src="https://upload.wikimedia.org/wikipedia/commons/5/51/Facebook_f_logo_%282019%29.svg" alt="Facebook" style="width:45px;height:45px;"/></a>
</div><br/>
  
**_Nota_**: Por motivos de confidencialidad y acuerdos de prácticas, el código fuente de este proyecto no puede ser publicado. Sin embargo, puedo detallar mi contribución y las tecnologías utilizadas en una entrevista.

## TECNOLOGÍAS UTILIZADAS
Lenguaje de Programación: **Python 3.12**  
Entorno de Desarrollo: **Visual Studio Code**  
Patrón de Diseño y Arquitectura: **MVC**  

Frameworks: **PySide6 (Qt)**  
Base de Datos: **SQLite**  

Generación de PDF: **xhtml2pdf**  
Preparación de las plantillas HTML y CSS: **Formateo nativo de strings**  

## MI CONTRIBUCIÓN Y RESPONSABILIDADES 
Mis principales áreas de desarrollo y responsabilidades en este proyecto fueron:

* **Ventana Principal:**
    * **_Competencias_**: Implementé la funcionalidad para crear y asociar competencias a cargos, facilitando así la evaluación de cada empleado según su cargo.
      
    * **_Medias_**: Desarrollé la visualización y la generación de informes en PDF sobre las notas medias de los empleados, distinguiendo entre aquellos con y sin calificación.

* **Ficha del Empleado:**
    * **_Informe_**: Fui el encargado de desarrollar la funcionalidad completa para la **generación del PDF** correspondiente al informe general de desempeño del empleado. Mi compañero se centró en construir los datos del informe, incluyendo las notas de cada competencia del empleado y la visualización de la nota media.
      
    * **_Evaluación_**: Fui el responsable del desarrollo integral de este módulo, incluyendo tanto la **interfaz de usuario intuitiva** como el **código subyacente**. Esto permitió evaluar las competencias del cargo del empleado, registrar su nivel de desempeño, calcular automáticamente la nota media de todas las competencias calificadas y asociarla a la evaluación final del empleado.    

         
* Modificación de la base de datos para crear las nuevas tablas de competencias y de datos de evaluación de los empleados.  

## VENTANA PRINCIPAL
<img src="https://github.com/user-attachments/assets/5e549590-b55a-454d-956e-5a696309695d" width="720" height="360">

## FICHA DEL EMPLEADO
<img src="https://github.com/user-attachments/assets/40e625c9-189f-4055-a24b-2b41c87728f6" width="720" height="360">
