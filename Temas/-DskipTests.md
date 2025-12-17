- **Qué hace:**
    
    - **Compila** las clases de test, pero **no las ejecuta**.
        
    - Maven genera los `.class` de tus tests, pero no corre JUnit/TestNG.
        
- **Impacto:**
    
    - Build un poco más lento que `-Dmaven.test.skip=true` porque sí compila los tests.
        
    - Pero más seguro si otros módulos dependen de esas clases de test (ej. en proyectos multi‑módulo).
        
- **Uso típico:**
    
    - Cuando quieres asegurarte de que los tests al menos compilen, pero no perder tiempo ejecutándolos.