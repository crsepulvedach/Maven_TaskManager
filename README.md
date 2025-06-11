# 🧠 TaskMaster

**TaskMaster** es una aplicación Java basada en Maven que permite gestionar tareas de forma simple y eficiente. Este proyecto fue creado como parte de un ejercicio para aprender sobre el ciclo de vida de Maven, gestión de dependencias, y buenas prácticas en proyectos colaborativos.

---

## ⚙️ Requisitos

- Java 8
- Maven 3.x
- Git (opcional, para clonar el repo)

---

## 🚀 Comandos Maven más utilizados

| Comando                          | Descripción                                    |
|----------------------------------|------------------------------------------------|
| `mvn compile`                   | Compila el código fuente del proyecto          |
| `mvn test`                      | Ejecuta los tests unitarios                    |
| `mvn clean`                     | Limpia los archivos generados (`target/`)     |
| `mvn package`                   | Empaqueta el proyecto en un `.jar`            |
| `mvn install`                   | Instala el `.jar` en el repositorio local      |

---

## 📦 Dependencias

Estas son algunas de las principales dependencias utilizadas en el proyecto:

- **JUnit 5 (Jupiter)** – Para pruebas unitarias modernas
- **JUnit 4** – Compatibilidad con pruebas anteriores
- **Apache Commons Lang3** – Utilidades extendidas para Strings, fechas, etc.

```xml
<dependency>
  <groupId>org.junit.jupiter</groupId>
  <artifactId>junit-jupiter-api</artifactId>
  <scope>test</scope>
</dependency>

<dependency>
  <groupId>junit</groupId>
  <artifactId>junit</artifactId>
  <version>4.13.2</version>
  <scope>test</scope>
</dependency>

<dependency>
  <groupId>org.apache.commons</groupId>
  <artifactId>commons-lang3</artifactId>
  <version>3.12.0</version>
</dependency>
