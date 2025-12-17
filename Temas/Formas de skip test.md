![[-Dmaven.test.skip=true]]

![[-DskipTests]]

## 📊 Comparación rápida

| Opción                                  | ¿Compila tests? | ¿Ejecuta tests? | Velocidad     | Riesgo                       |
| --------------------------------------- | --------------- | --------------- | ------------- | ---------------------------- |
| [[-Dmaven.test.skip=true]]              | ❌ No            | ❌ No            | 🚀 Más rápido | ⚠️ Puede romper dependencias |
| [[-DskipTests]] / IntelliJ “Skip tests” | ✅ Sí            | ❌ No            | ⚡ Medio       | ✅ Seguro para dependencias   |

👉 En resumen:

- **IntelliJ “Skip tests”** = compila pero no ejecuta.
    
- `-Dmaven.test.skip=true` = ni compila ni ejecuta.
    

Si lo que quieres es **solo evitar la ejecución** pero mantener la compilación, usa la opción de IntelliJ o `-DskipTests`. Si lo que quieres es **máxima velocidad y no te importa perder compilación de tests**, usa `-Dmaven.test.skip=true`.