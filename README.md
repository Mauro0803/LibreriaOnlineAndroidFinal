# EVALUACIÓN FINAL: Librería Online App

## Descripción del Proyecto
Esta es la primera versión de la interfaz de usuario para una aplicación móvil de librería online. Permite al usuario ver un catálogo de libros y navegar a una pantalla de detalles al seleccionar un ítem.

## Requerimientos Implementados
* **Pantalla Principal (MainActivity):** Contiene un `RecyclerView` mostrando la lista de libros con su imagen (`ImageView`), título/descripción (`TextView`), y un botón (`Button`).
* **Navegación:** La selección de un libro inicia una nueva actividad (`DetalleActivity`) utilizando un **Intent** y pasando los datos del libro seleccionado (título y descripción).

## Estructura del Código y Gestión de Versiones (GitHub)
* **Lenguaje:** Kotlin
* **Elementos UI:** RecyclerView, CardView, Intent.
* **Gestión de Código:**
    1. Se ha utilizado un repositorio en GitHub para el control de versiones.
    2. **Ramas utilizadas:** El desarrollo se realizó en la rama principal (`main`/`master`). Para trabajo concurrente, se recomienda crear ramas de funcionalidad (ej: `feature/detalles-libro`) y fusionar vía Pull Request.
    3. **Documentación:** La organización del proyecto sigue las buenas prácticas de Android Studio.

## Cómo Ejecutar el Proyecto
1. Clona el repositorio a tu máquina local.
2. Abre la carpeta `LibreriaOnlineApp` en Android Studio.
3. El IDE sincronizará automáticamente las dependencias (Gradle).
4. Ejecuta la aplicación en un emulador o dispositivo físico.

## Capturas de Pantalla
### Pantalla Principal
![Captura de la Pantalla Principal](https://raw.githubusercontent.com/Mauro0803/LibreriaOnlineAndroidFinal/master/screenshots/Screenshot_Pantalla_Principal.png)

### Pantalla de Detalles
![Captura de la Pantalla de Detalles](https://raw.githubusercontent.com/Mauro0803/LibreriaOnlineAndroidFinal/master/screenshots/Screenshot_Pantalla_Detalle.png)
