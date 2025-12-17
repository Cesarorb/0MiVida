- `mvn clean`
    
    - Elimina la carpeta `target/` donde se generan los archivos compilados, clases y paquetes.
        
    - Se usa para empezar desde cero y evitar residuos de compilaciones anteriores.
        
- `mvn compile`
    
    - Compila el código fuente del proyecto (normalmente en `src/main/java`).
        
    - Genera los `.class` en la carpeta `target/classes`.
        
- `mvn test`
    
    - Ejecuta las pruebas unitarias (normalmente en `src/test/java`).
        
    - Usa frameworks como JUnit o TestNG.
        
    - Si alguna prueba falla, Maven detiene el proceso.
        
- `mvn package`
    
    - Empaqueta el proyecto en un formato distribuible (por ejemplo `.jar` o `.war`).
        
    - El archivo resultante se guarda en `target/`.
        
- `mvn install`
    
    - Compila, prueba y empaqueta el proyecto.
        
    - Luego instala el artefacto en el repositorio local (`~/.m2/repository`).
        
    - Esto permite que otros proyectos en tu máquina lo usen como dependencia.
        
- `mvn deploy`
    
    - Similar a `install`, pero además sube el artefacto a un repositorio remoto (por ejemplo Nexus o Artifactory).
        
    - Se usa en entornos colaborativos para compartir librerías.
        
- `mvn site`
    
    - Genera documentación del proyecto en formato HTML (informes de dependencias, pruebas, etc.).
        
    - Se guarda en `target/site`.
        
- `mvn validate`
    
    - Verifica que el proyecto esté correctamente configurado y que el `pom.xml` sea válido.
        
- `mvn verify`
    
    - Ejecuta todas las verificaciones necesarias para asegurar que el proyecto está listo para empaquetarse.
        
    - Incluye pruebas de integración si están configuradas.