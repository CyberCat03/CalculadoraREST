# Calculadora REST - Resumen Ejecutivo

## Descripción

Este proyecto consiste en el desarrollo de una API REST de una calculadora en línea que permite a los usuarios realizar operaciones matemáticas básicas como suma, resta, multiplicación y división. La solución busca ofrecer una herramienta fácil de usar para realizar cálculos matemáticos de manera rápida y precisa.

## Problema Identificado

Los usuarios necesitan una manera conveniente y accesible de realizar cálculos matemáticos básicos sin la necesidad de utilizar una calculadora física o una aplicación compleja. La solución busca cubrir esta necesidad al proporcionar una API REST que puede ser utilizada desde cualquier dispositivo con acceso a internet.

## Solución

La solución consiste en una API REST implementada en Java utilizando el framework Spring Boot. La API acepta solicitudes HTTP con dos números y una operación matemática y devuelve el resultado correspondiente. Se han implementado endpoints para realizar sumas, restas, multiplicaciones y divisiones.

## Arquitectura

La arquitectura de la aplicación se basa en una estructura de controladores, servicios y repositorios, siguiendo las mejores prácticas de desarrollo de Spring Boot. Se utilizan pruebas unitarias para asegurar la calidad del código y garantizar el funcionamiento correcto de las operaciones matemáticas.

## Tabla de Contenidos

1. [Requerimientos](#requerimientos)
2. [Instalación](#instalación)
3. [Configuración](#configuración)
4. [Uso](#uso)
5. [Contribución](#contribución)
6. [Roadmap](#roadmap)

## Requerimientos

- Servidores de aplicación: Apache Tomcat (para despliegue local).
- Paquetes adicionales: Spring Boot, Spring Web, JUnit (para pruebas unitarias).
- Versión de Java: Java 11.

## Instalación

1. Clonar este repositorio.
2. Importar el proyecto en tu IDE preferido.
3. Configurar el proyecto para utilizar Java 11.
4. Ejecutar el proyecto en un servidor de aplicación (por ejemplo, Apache Tomcat) para pruebas locales.

## Configuración

- Los archivos de configuración se encuentran en la carpeta `src/main/resources`.
- Puedes configurar el puerto del servidor, la conexión a la base de datos (si es necesario), etc.

## Uso

### Usuario Final

Consulta la [documentación en línea](https://example.com/documentation) para obtener instrucciones detalladas sobre cómo utilizar la API y realizar operaciones matemáticas.

### Usuario Administrador

La configuración del producto y los archivos de configuración se encuentran en la carpeta `src/main/resources`.

## Contribución

¡Gracias por tu interés en contribuir al proyecto!

1. Clona este repositorio.
2. Crea un nuevo branch: `git checkout -b feature/nueva-funcionalidad`.
3. Realiza tus cambios y realiza commits: `git commit -m "Agrega nueva funcionalidad"`.
4. Envía un pull request al repositorio principal.
5. Espera a que tu pull request sea revisado y aceptado.

## Roadmap

- Implementar funcionalidad de cálculo de potencias.
- Agregar autenticación para proteger la API.
- Mejorar la documentación en línea con ejemplos detallados.
