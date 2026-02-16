# proyecto-final-extra
Proyecto Final — Puntos Extra  
Curso: Introducción a la Programación de Computadoras  

Este programa es una versión mejorada del cotizador de seguros de la empresa TK‑U.  
Incluye nuevas funcionalidades solicitadas como puntos extra:  
- Cotizaciones múltiples mediante un ciclo  
- Recargos adicionales por propiedades  
- Recargo adicional basado en los ingresos del asegurado  

---

1. Funcionamiento General del Programa

El programa permite realizar **cotizaciones ilimitadas**, una tras otra, hasta que el usuario escriba la palabra **"Salir"**.  
Cada cotización solicita los datos del asegurado y calcula el precio final del seguro aplicando diferentes recargos.

El flujo general es:

1. Preguntar si desea cotizar o salir  
2. Solicitar datos del asegurado  
3. Calcular recargos según:
   - Edad del asegurado  
   - Edad del cónyuge  
   - Cantidad de hijos  
   - Cantidad de propiedades  
   - Ingresos mensuales  
4. Sumar todos los recargos  
5. Mostrar el precio final  
6. Repetir el proceso  

---

2. Partes del Problema que se Consideran

Edad del asegurado  
Dependiendo del rango de edad, se aplica un recargo sobre el precio base:

- 18–24 años → 10%  
- 25–49 años → 20%  
- 50 años o más → 30%  

Estado civil y edad del cónyuge  
Si el asegurado está casado, se aplica un recargo adicional usando los mismos rangos de edad.

Cantidad de hijos  
Cada hijo genera un recargo del **20% del precio base**.

Cantidad de propiedades (Punto Extra)  
Cada propiedad genera un recargo del **35% del precio base**.

Ingresos del asegurado (Punto Extra)  
Se aplica un recargo del **5% del salario mensual** del asegurado.

Cotizaciones múltiples (Punto Extra)  
El programa funciona dentro de un ciclo que solo termina cuando el usuario escribe **"Salir"**.

---

🧮 3. Algoritmo del Programa (Paso a Paso)

1. Mostrar mensaje para iniciar o salir  
2. Si el usuario escribe “Salir”, terminar  
3. Solicitar nombre  
4. Solicitar edad  
5. Solicitar estado civil  
6. Si está casado, solicitar edad del cónyuge  
7. Preguntar si tiene hijos  
8. Si tiene, solicitar cuántos  
9. Preguntar si tiene propiedades  
10. Si tiene, solicitar cuántas  
11. Solicitar salario mensual  
12. Calcular recargo por edad  
13. Calcular recargo por cónyuge  
14. Calcular recargo por hijos  
15. Calcular recargo por propiedades  
16. Calcular recargo por ingresos  
17. Sumar todos los recargos  
18. Calcular precio final  
19. Mostrar resultados  
20. Volver al paso 1  

---

4. Archivos del Repositorio

El repositorio contiene:

- `proyecto_final.js` — Código completo con puntos extra  
- `README.md` — Documentación del programa  
- `Análisis del Problema.txt` — Explicación del problema  
- `Algoritmo del Cotizador.txt` — Pasos del algoritmo  

---

5. Posibles Mejoras Futuras

- Validar que todos los datos ingresados sean números válidos  
- Evitar que el usuario deje campos vacíos  
- Crear una interfaz gráfica en HTML  
- Guardar las cotizaciones en un archivo o base de datos  
- Mostrar un resumen final de todas las cotizaciones realizadas  

---

6. Autor

**Juan Pablo López López**  
Introducción a la Programación de Computadoras  
Año 2026

---

Estado del Proyecto

Proyecto completado con puntos extra.
