---
    title: Tutorial realización de una campaña de ventas
    descripción: Este tutorial proporciona una descripción detallada de todas las tareas implicadas en la realización de una campaña de ventas en Business Central.
    autor: SorenGP

    ms.service: dynamics365-business-central
    ms.topic: conceptual
    ms.devlang: na
    ms.tgt_pltfrm: na
    ms.workload: na
    ms.search.keywords:
    ms.date: 06/24/2021
    ms.author: edupont

---
# Tutorial realización de una campaña de ventas

Una campaña es cualquier tipo de actividad que involucra a varios contactos. Una parte importante de la configuración de una campaña implica seleccionar el público objetivo de su campaña. Para este propósito, en \[! INCLUDE[prod\_short](includes/prod_short.md)], puede crear un segmento o un grupo de contactos mediante filtros.  

 Estas características se utilizan en Ventas y Marketing para planificar cuidadosamente sus actividades de marketing y para administrar sus interacciones con contactos y clientes. Puede crear campañas y configurar segmentos de sus contactos para correos y otros tipos de interacciones con sus contactos y clientes potenciales.  

 Las funciones campaña y segmento con sus procesos automatizados le permiten planificar, organizar y realizar un seguimiento de sus actividades de marketing. Esto aumentará las posibilidades de ganar nuevos clientes y retener a los clientes existentes.  

## Acerca de este tutorial

 En este tutorial se muestra el proceso de seguimiento de una feria comercial y la orientación a clientes potenciales (contactos) en una campaña de seguimiento.  

 El tutorial presenta la característica de administración de campañas y segmentos en el departamento de ventas y marketing. En este tutorial se muestran las siguientes tareas:  

- Preparación de los datos.
- Configuración de una campaña.  
- Seleccionar el público objetivo.  
- Minería de datos.  
- Envío de cartas a los contactos.  
- Registro de respuestas de campaña.  

## Roles

 En este tutorial se muestran las tareas que realizan los siguientes roles de usuario:  

- Gerente de Marketing o Gerente de Ventas  
- Personal de marketing  

## prerrequisitos

 Para poder realizar las tareas del tutorial, debe instalar el archivo \[! INCLUIR[prod\_short](includes/prod_short.md)].  

## cuento

 El gerente de marketing en el departamento de ventas de CRONUS es responsable de planificar las campañas y ejecutarlas. También toma decisiones sobre en qué ferias comerciales participar y evalúa el progreso de la campaña.  

 El empleado de marketing del departamento de marketing se encarga de producir, distribuir y colocar material de marketing.  

 La compañía acaba de lanzar un nuevo producto llamado Rome Guest Chair. El producto fue promocionado recientemente en una feria comercial, Office Futurus. Muchos clientes expresaron gran interés en el producto, y como parte de un esfuerzo promocional, a los clientes que compraron Rome Guest Chair durante un período de campaña se les ofreció un precio de campaña especial.  

 Una de las tareas del personal de marketing después de la feria es ingresar a todos los clientes potenciales como contactos.  

 El director de marketing configura una campaña, crea un segmento que contiene todos los contactos nuevos y, a continuación, extrae los datos de contacto para seleccionar el público objetivo de la campaña.  

 El empleado ayuda a enviar cartas de agradecimiento a todos los contactos que dejaron sus tarjetas con el personal en el stand, y finalmente, el gerente registra todas las respuestas que reciben de los posibles clientes.  

## Configuración de una campaña

 Tan pronto como el empleado ha introducido las tarjetas de visita recibidas en la feria, el gerente de marketing configura una tarjeta de campaña para gestionar las actividades involucradas en la campaña.  

### Para configurar una campaña  

1. Elija la ![bombilla que abre la función Información.hacer,](media/ui-search/search_small.png "Dime qué quieres") escribe **Campañas**, y, a continuación, elige el vínculo relacionado.  
2. Elija la acción **Nuevo** para crear una nueva campaña. En la tarjeta de campaña, pulse **Intro** para que se inserte automáticamente un número de campaña.  
3. En el campo **Descripción,** escriba una descripción para la campaña, por ejemplo, **feria comercial Office**Futurus.  
4. Elija el **campo Código de** estado y seleccione el código de estado "1-PLAN". 
5. Rellene los campos **Fecha** de inicio y Fecha **** de finalización de la campaña según corresponda.  

## Selección del público objetivo

 El director de marketing crea un segmento para seleccionar los contactos con los que desea interactuar.  
 
 Al crear un segmento, puede usar una variedad de criterios para seleccionar los contactos que deben ser destinos para el segmento. Por ejemplo, puede seleccionar personas de contacto que trabajan en un sitio de cliente o en un sitio de cliente potencial que son responsables de las compras en su empresa. Los filtros se utilizan para agregar contactos de acuerdo con los criterios que mejor se adapten a sus propósitos. Por ejemplo, puede optar por filtrar por la responsabilidad laboral de la persona de contacto o la relación comercial o la industria de la empresa de contacto. Para este tutorial, elegiremos el filtro **Responsabilidad** del trabajo para seleccionar contactos.

### Para crear un segmento con los contactos relevantes  

1. Elija la acción **Navegar** y, a continuación, elija **Segments**.  
2. Elija la acción **Nuevo** para crear un nuevo segmento. En la tarjeta de segmento, seleccione **Entrar** para que se inserte automáticamente un número de segmento.  
3. En la ficha desplegable **General,** en el campo **Descripción,** especifique, por ejemplo, *Visitantes en la feria*Office Futurus.
4. Elija la acción **Agregar contactos** para abrir el filtro Agregar **contactos.**   
5. Desplácese hacia abajo hasta la ficha desplegable **Responsabilidad** del trabajo de contacto, seleccione el filtro **Compra** como **** Código de responsabilidad del trabajo y elija el botón **Aceptar.**   

La página **Segmento** ahora contiene una lista de contactos basada en el filtro que escribió. En la ficha desplegable **** General, en la **ficha desplegable No. del** campo Líneas, puede ver de un vistazo el número de contactos que cumplen estos criterios.  

> \[!NOTE]  
> Puede guardar los criterios de segmentación para reutilizarlos en una fase posterior.

### Para guardar los criterios de segmentación

1. En la página **Segmento,** elija **Actions .**
2. Elija **Funciones**, luego **Segmento**, y, a continuación, elija la acción **Guardar criterios.**   
3. En la página **Guardar criterios** de segmento, escriba un código para el segmento. En el campo **Descripción,** especifique una descripción de los criterios de segmento.
4. Elija el botón **Aceptar.**   

## Minería de datos

 El gerente de marketing echa un vistazo más de cerca a la lista segmentada de contactos y se da cuenta de que la lista es demasiado grande. Decide reducir la lista en función de los clientes reales y potenciales para asegurarse de que se centra en el grupo objetivo correcto. Este proceso de refinación y reducción de los datos también se conoce como minería de datos.  

### Para quitar contactos del segmento  

1. En la página **Segmento,** elija **Actions .**
2. En la barra de menús siguiente, elija **Funciones**, elija ****, Contactosy elija **Reducir contactos**.  

  Esto abre el cuadro **de diálogo Quitar contactos – Reducir.**   
4. En la ficha desplegable **Relación** comercial de contacto, seleccione el filtro **CUST** como **Código**, de relación comercialy elija el botón **Aceptar.** 

 La página **Segmento** ahora contiene una lista reducida de contactos y en el **no. del** campo Líneas, puede ver el número de contactos que ahora cumplen estos nuevos criterios.  

 > \[!NOTE]  
 > Si tiene que invertir esta eliminación de un grupo de contactos, puede hacerlo mediante la función **Volver atrás.**  En otras palabras, puede deshacer la última segmentación.  

### Para recuperar los contactos eliminados

1. En la página **Segmento,** elija la acción **Segmento.** 
2. Elija la acción **Volver atrás.** 

Los contactos que acaba de quitar se vuelven a agregar a la lista de contactos.

## Vincular un segmento a una campaña

El director de marketing decide que la lista reducida es la lista final de contactos que desea que formen parte de la campaña. Por lo tanto, vinculan este segmento a la campaña futurus feria.  

### Para vincular un segmento a la campaña  

1. En la página **** Segmento, en la **** ficha desplegable **Campaña,** elija el campo Número de campaña para seleccionar la campaña a la que desea adjuntar el segmento, por ejemplo, **CP0001**.
2. Seleccione **Sí**.  
3. Dado que este segmento es el objetivo de la campaña, seleccione la casilla **De destino de** la campaña y elija **Sí**.  

## Envío de cartas y mensajes de correo electrónico a contactos

 El empleado de marketing ayuda al gerente de marketing a enviar correspondencia a los clientes potenciales, en la que les agradecen por visitar la feria comercial.

### Para usar un segmento para enviar una carta a un contacto  

> \[!NOTE]  
> En este procedimiento tiene que adjuntar un documento de Word. Puede agregar datos adjuntos en cualquier idioma.

> \[!NOTE]  
> Si es necesario, haga clic en el icono **Editar lápiz** para abrir la página en modo de edición.

1. Abra la **tarjeta segmento** para los visitantes en la feria ****FUTURUS.  
2. En la ficha desplegable **Interacción,** en el campo **Código de plantilla** de interacción, seleccione el bus de código de plantilla Carta de **empresa** y seleccione **Sí**.
3. Elija el campo **Código** de idioma (predeterminado) para abrir la página **Idiomas de interacción de** segmentos. Seleccione un **código** de idioma y, a continuación, elija el botón **Aceptar.** 
4. Asegúrese de que el **Tipo de correspondencia** (predeterminado) está establecido en Copia **impresa**.
5. En el campo **Datos adjuntos,** seleccione el cuadro Puntos **suspensivos.**  Se abrirá el cuadro de diálogo Importar datos adjuntos.
    1. Seleccione el botón **Elegir** para elegir el archivo.
    1. Busque el archivo y seleccione el botón **Abrir** para adjuntarlo.
6. En el campo **Asunto (predeterminado),** escriba el siguiente texto de ejemplo: **Gracias por visitar la**feria. Presione la tecla TAB para salir del campo y seleccione el botón **Sí.** 
7. Deslice el **enviar documentos** de Word como Attmt a activado y seleccione el botón **Sí.** 
8. Elija la acción **Registro**. En la ventana emergente Segmento de registro, habilite: **Crear segmento de seguimiento**
9. Elija el botón **** Aceptar para iniciar el **trabajo por lotes segmento de registro**.  

Se envían los datos adjuntos. Cuando haya terminado el proceso, elija el botón **Aceptar** para el mensaje que indica que se ha registrado el segmento.  

 Las letras se imprimen automáticamente y se registra el segmento. Dado que el segmento se ha registrado, ya no está en la lista de segmentos, pero se mueve a la lista de segmentos registrados. Para ver esa lista, elija la ![bombilla que abre la función Información.el icono qué desea hacer,](media/ui-search/search_small.png "Dígame") escriba Segmentos ****, registradosy, a continuación, elija el vínculo relacionado.  

Una vez registrado el segmento, cada carta que se envía se registra como una interacción, que puede ver en el registro.  

Elija la ![bombilla que abre la función Información.el icono qué desea hacer,](media/ui-search/search_small.png "Dígame") escriba Entradas ****, del registro de interaccióny, a continuación, elija el vínculo relacionado. Hay una entrada para cada carta enviada.  

### Para enviar un mensaje de correo electrónico a un contacto  

1. En la ficha desplegable **** Interacción, en el campo **Código** de plantilla de interacción, seleccione la plantilla Carta de empresa, codifique **BUS**.  
2. En el campo **Asunto (predeterminado),** escriba el siguiente texto de ejemplo: **Gracias por visitar la**feria.  
3. En el campo **Tipo** de correspondencia, elija ****Correo electrónico.  
4. Especifique la configuración de idioma y adjunte un documento de Word, como en el procedimiento anterior.  
5. Elija la acción **Registrar.**  Se abre la página **Segmento** de registro.  
6. Active la casilla **Enviar datos adjuntos** para que los datos adjuntos se envíen por correo electrónico.  
7. Active la casilla **Crear** segmento de seguimiento.  
8. Elija el botón **Aceptar.**   

 Las cartas se envían automáticamente por correo electrónico y se registra el segmento. Dado que el segmento se ha registrado, ya no está en la lista de segmentos, pero se guarda en la lista de segmentos registrados. Para ver esa lista, elija la ![bombilla que abre la función Información.el icono qué desea hacer,](media/ui-search/search_small.png "Dígame") escriba Segmentos ****, registradosy, a continuación, elija el vínculo relacionado.  

## Registro de respuestas de campaña

 Durante las próximas dos semanas, los posibles clientes responden a la carta. El gerente de marketing desea realizar un seguimiento de las respuestas y registrar estas interacciones.  

 Para ello, configure un segmento para los contactos que han respondido a la carta.  

### Para registrar las respuestas de la campaña  

1. En la página **** Segmento, en la ficha desplegable **** Interacción, elija el campo **Código de plantilla** de interacción.  

 No hay ninguna plantilla de interacción para registrar las respuestas a las campañas. Por lo tanto, cree una nueva plantilla.  

2. En la lista desplegable **Plantillas** de interacción, elija la acción **** Nuevo.  
3. En el campo **Código,** escriba **RESP**, y, en el campo **Descripción,** escriba Respuestas ****de campaña.  
4. Elija el botón **Aceptar.** 
5. Elija **Sí** para confirmar que desea aplicar este código de plantilla de interacción a todas las líneas de segmento.
6. En la ficha desplegable **Campaña,** seleccione el campo Respuesta **a** la campaña. Elija **Sí** para confirmar el mensaje Ha modificado la *respuesta de la campaña*.  
7. En la página **Segmento,** elija la acción **Registrar.**   
8. En la **página Segmento** de registro, desactive la casilla Enviar datos **adjuntos.**  A continuación, elija el botón **Aceptar** para confirmar el mensaje de que se ha registrado el segmento.  
  
## Ver también  
[Gestión de relaciones](marketing-relationship-management.md)  
 [Tutoriales de procesos empresariales](walkthrough-business-process-walkthroughs.md)  
 \[Trabajando con \[! INCLUIR[prod\_short](includes/prod_short.md)]\](ui-work-product.md)


\[! INCLUDE[footer-include](includes/footer-banner.md)]
