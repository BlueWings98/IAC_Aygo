# Reporte de Actividad: Implementación de una Función AWS Lambda con AWS CDK

## Descripción de la Actividad

Se llevó a cabo la implementación de una función AWS Lambda utilizando el **AWS Cloud Development Kit (CDK)**. El objetivo principal fue familiarizarse con la creación y despliegue de recursos en AWS mediante código, siguiendo las guías oficiales proporcionadas por AWS.

## Recursos Implementados

1.  **Stack Generado en AWS**  
    Se creó un stack que incluye los recursos necesarios para la ejecución de la función Lambda, asegurando su correcta configuración y permisos asociados.

2.  **Función Lambda: `HelloWorldFunction`**  
    Se desarrolló una función Lambda básica que retorna el mensaje "Hello, World!" al ser invocada, sirviendo como punto de partida para comprender el despliegue de funciones mediante AWS CDK.


## Talleres Realizados

Para completar la actividad, se siguieron los pasos detallados en los siguientes tutoriales oficiales de AWS:

-   [Cómo empezar con el AWS CDK](https://docs.aws.amazon.com/es_es/cdk/v2/guide/getting_started.html)  
    Este tutorial proporciona una introducción al AWS CDK, incluyendo la instalación y configuración de las herramientas necesarias para su uso.

-   [Tutorial: Crea tu primera aplicación AWS CDK](https://docs.aws.amazon.com/es_es/cdk/v2/guide/hello_world.html)  
    En este tutorial se guía al usuario en la creación de una aplicación básica utilizando AWS CDK, que incluye la implementación de una función Lambda.


## Evidencias

A continuación, se presentan las capturas de pantalla obtenidas durante el proceso. Estas imágenes se encuentran almacenadas en la carpeta `Evidence` ubicada en el directorio raíz del proyecto.

1.  **Stack Generado**


    Esta imagen muestra el stack creado en la cuenta de AWS, evidenciando la correcta implementación de los recursos.
    ![Evidencia 1](Evidencia1.png)


2.  **Función Lambda: `HelloWorldFunction`**


    Aquí se observa la función Lambda desplegada y configurada correctamente, lista para ser invocada.
    ![Evidencia2](Evidencia2.png)

## Reflexión de la actividad
Esta actividad presentó varios desafios.

1. Las licencias que se utilizaron para la actividad estaban limitadas en roles. Esto significó que no se pudo seguir el tutorial como estaba diseñado y tocó buscar soluciones alternativas para lograr los objetivos.
2. Muchas de estas soluciones alternativas eran poco intuitivas y requerian conocimiento específico de la nube. Esto fue especialmente notorio en la fase de despliegue donde se tuvo que quemar el ID del rol en el código y además ejecutar el comando de despliegue indicando el rol otra vez.
3. El moodle no generó buen streaming del segundo video y se tenia que recargar aveces cada 3 segundos de video lo que generó que se extendiera la actividad innescesariamente.

En general esta actividad fue una buena primera aproximación a la infraestructura como código pero si dejó la sensación que se está manejando una complejidad alta y de alta fragilidad, donde se necesita de un experto para hacer cambios asi sean menores para no generar bloqueos.

## Conclusión

La actividad se completó exitosamente, logrando desplegar la función Lambda `HelloWorldFunction` utilizando AWS CDK. Este ejercicio permitió comprender el flujo de trabajo para la creación y despliegue de recursos en AWS mediante código, siguiendo las mejores prácticas recomendadas por AWS.

## Próximos Pasos

1.  **Explorar Configuraciones Avanzadas de AWS CDK**  
    Investigar características más complejas y personalizadas que ofrece AWS CDK para la gestión de infraestructura.

2.  **Implementar Funciones Lambda Más Complejas**  
    Desarrollar funciones que interactúen con otros servicios de AWS, como S3, DynamoDB o API Gateway, para construir aplicaciones más robustas.

3.  **Automatizar Despliegues Utilizando CI/CD**  
    Integrar pipelines de integración y entrega continua para automatizar el proceso de despliegue de las funciones y recursos creados.


----------

**Fecha de Generación del Reporte:** 15 de noviembre de 2024  
**Autor:** Sebastian Novoa