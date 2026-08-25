# Turno Noche

### Integrantes
- **Galo Bautista Del Vacchio** [5]
- **Mateo Maccarrone** [5]

### Descripción del Proyecto
Videojuego de **terror psicológico y exploración narrativa en 2D** con perspectiva aérea (*top-down*), ambientado en las instalaciones de la **Escuela Técnica N.º 35** [1, 6]. El jugador asume el rol de un estudiante del turno noche que debe explorar el edificio, recolectar pistas y resolver acertijos lógicos para desvelar los misterios del establecimiento y lograr escapar, en una experiencia inspirada en clásicos del género como *Corpse Party* [1].

### Tecnologías Utilizadas
- **Lenguaje:** Java 21 (JDK 21) [3, 4]
- **Framework:** LibGDX (Versión 1.14.2) [3]
- **Interfaz y Diálogos:** Scene2D (módulo nativo de LibGDX) [6, 7]
- **Mapas:** Tiled Map Editor (.tmx) [6, 8]
- **Persistencia de Datos:** SQLite mediante la API JDBC *(Previsto para ser implementado y configurado en la fase correspondiente del desarrollo)* [3, 6].

### Enlace a la Wiki del Proyecto
Podés consultar la propuesta formal, los alcances detallados y la planificación del proyecto en nuestra Wiki de GitHub:  
**[Acceder a la Wiki de la Propuesta](https://github.com/galodelvacchio777/juego-turno-noche/wiki)** [9]

---

### Requisitos Previos
* **Java JDK 21** instalado de forma obligatoria y configurado en las variables de entorno (`JAVA_HOME`) [4].
* Se recomienda utilizar **IntelliJ IDEA** como entorno de desarrollo (IDE) para la correcta importación de Gradle [10].

---

### Instrucciones de Instalación y Ejecución

Abrí una terminal en tu computadora y ejecutá los siguientes comandos en orden para clonar, ingresar al directorio y correr el juego:

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/galodelvacchio777/juego-turno-noche.git
   ``` [4]

2. **Ingresar a la carpeta raíz del proyecto:**
   ```bash
   cd juego-turno-noche
   ``` [4]

3. **Ejecutar el proyecto (Módulo de Escritorio):**
   * En **Windows (CMD o PowerShell):**
     ```cmd
     gradlew lwjgl3:run
     ``` [4]
   * En **Linux / macOS:**
     ```bash
     chmod +x gradlew
     ./gradlew lwjgl3:run
     ``` [4]
