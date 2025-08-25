# Proyecto: Spring Data con H2

Este proyecto es una demostración sencilla de cómo utilizar **Spring Data** junto con la base de datos en memoria **H2**. El objetivo es mostrar la integración básica y el uso de persistencia de datos en una aplicación Java con Spring Boot.

## Características principales
- Uso de **Spring Boot** para facilitar la configuración y el despliegue.
- Persistencia de datos con **Spring Data JPA**.
- Base de datos en memoria **H2** para pruebas y desarrollo rápido.
- Acceso a la consola web de H2 para visualizar y manipular los datos.

## Instalación y ejecución

### 1. Clonar el repositorio

```bash
git clone <URL_DEL_REPOSITORIO>
cd h2.database
```

### 2. Ejecutar la aplicación

En la raíz del proyecto, ejecuta:

```bash
./mvnw spring-boot:run
```

O en Windows:

```bash
mvnw.cmd spring-boot:run
```

Esto iniciará la aplicación en el puerto **8080**.

### 3. Acceder a la consola H2

Abre tu navegador y visita:

[http://localhost:8080/h2-console/](http://localhost:8080/h2-console/)

- **JDBC URL:** `jdbc:h2:mem:testdb`
- **Usuario:** `sa`
- **Contraseña:** (dejar en blanco)

## ¿Qué se hizo?
- Se configuró un proyecto Spring Boot con dependencias de Spring Data JPA y H2.
- Se crearon entidades y repositorios para persistir datos en la base H2.
- Se incluyó un archivo `data.sql` para poblar la base con datos de ejemplo al iniciar.
- Se habilitó la consola web de H2 para facilitar la visualización de los datos.

---

¡Explora el código y experimenta con la base de datos en memoria!

