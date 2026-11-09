# Ejercicio 3: EjemplarNoDisponibleException

## Explicación Lógica
1. **Excepción Verificada:** Al heredar de `Exception`, el compilador obliga a declarar `throws EjemplarNoDisponibleException` en la firma del método o a capturarla con `try-catch`.
2. **Regla de Negocio:** Se evalúa que `ejemplaresDisponibles > 0`. Si no hay stock, se interrumpe la operación lanzando la excepción con la información del libro afectado.