![Seekop](https://www.sicopweb.com/8.0/workspace/styles/images/logos/sicop.png)

# 🚀 Examen Técnico: Spring Boot y Angular con Giphy Integration

## 🎯 Objetivo
Desarrollar una API con **Spring Boot** que interactúe con la **API de Giphy** https://developers.giphy.com/ 🖼️ y permita a los usuarios buscar imágenes, marcar favoritos y gestionarlos. La funcionalidad será expuesta a través de una aplicación en **Angular**.

## 🛠️ Requisitos del Back-end (Spring Boot)
- **API REST**: Implementar utilizando Spring Boot `2.7.X` o `3.X.X`.
- **Giphy API Integration**: Conectar con la API de Giphy para obtener imágenes según términos de búsqueda.
- **Gestión de Favoritos**: Endpoints para marcar y desmarcar imágenes como favoritas, y para listar los favoritos.
- **Persistencia**: Utilizar **H2 en memoria** para almacenar favoritos con inicialización automática de la base de datos.
- **Logging y Documentación**: Integrar **Log4j/SLF4J** y documentar la API con **Swagger/OpenAPI**.
- **Pruebas y DevOps**: Incluir pruebas automatizadas y un flujo básico de DevOps con **Docker** 🐳.

## 🖥️ Requisitos del Front-end (Angular)
- **Interfaz de Usuario**: Crear una aplicación Angular `9+` que permita realizar búsquedas y mostrar resultados.
- **Favoritos**: Permitir al usuario seleccionar favoritos desde los resultados y visualizar o eliminar los marcados.
- **Responsividad**: Debe ser responsivo 📱.
- **Diseño UX**: Usar alguna librería de componente como ng-zorro, bootstrap, nebular, etc.
- **Efectos**: Agregar efectos visualmente atractivos.

## 📦 Entrega
- Proporcione el código fuente completo en **GitHub** como un "fork" del repositorio proporcionado, con un "pull request" 🌐.
- Incluya un **README** con instrucciones para configurar, ejecutar la aplicación y la suite de pruebas.

## ✔️ Evaluación
- **Funcionalidad**: Se comprobará que la aplicación cumple con los requisitos ✅.
- **Código y Diseño**: Claridad, calidad, uso de buenas prácticas 👍.
- **Documentación**: Completa y clara 📚.
- **Eficiencia**: En el cumplimiento de la tarea y en la solución presentada ⏱️.

## ➕ Extras
No es necesario cumplir con estos puntos, más sin embargo serán tomados en cuenta si los llegas a realizar.
- Proceso independiente para la instalación automática de los scripts de base de datos.
- Implementación de algún flujo de devops.
- Dockerizar Aplicación 🐳.
- Despliegue del aplicativo en la nube o en un servidor On-premise ☁️.
- Monitor de entradas y salidas para cada petición, imprimir en el log las entradas y salidas de cada proceso asociado una con un Id único 🔍.
- Integración de pruebas automatizadas 🧪.
- Integración con SonarQube 📈.