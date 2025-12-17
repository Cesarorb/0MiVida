## `-Dmaven.test.skip=true`

- **Qué hace:**
    
    - Evita **compilar** las clases de test y también evita **ejecutarlas**.
        
    - Es decir, Maven ni siquiera genera los `.class` de tus tests.
        
- **Impacto:**
    
    - Acelera más el build porque se salta tanto la compilación como la ejecución de tests.
        
    - Si tus tests tienen dependencias o código que se usa en otros módulos, puede romper builds que esperan esas clases compiladas.
        
- **Uso típico:**
    
    - Cuando quieres un build rápido y sabes que no necesitas ni siquiera compilar los tests (ej. en CI para un build preliminar).