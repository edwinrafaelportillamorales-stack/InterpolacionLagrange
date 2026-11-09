# Métodos de Interpolación Numérica

## Descripción general
Este proyecto implementa dos métodos de interpolación numérica utilizando el lenguaje de programación Java, el método de Lagrange y el método de Newton mediante diferencias divididas.
El objetivo es calcular valores aproximados de una función a partir de un conjunto de puntos conocidos, utilizando polinomios de interpolación.

# Métodos implementados
1. Interpolación de Lagrange
Utiliza polinomios base para construir un polinomio que pasa por todos los puntos proporcionados. Cada término se calcula mediante una productoria que permite obtener el valor interpolado.
2. Interpolación de Newton
Utiliza el método de diferencias divididas para construir el polinomio interpolante. El programa calcula y muestra la tabla de diferencias divididas antes de evaluar el polinomio.

## Requerimientos del entorno
- Java JDK 17 o superior.
- IDE: NetBeans, IntelliJ IDEA o Visual Studio Code.
- Extensión de Java para Visual Studio Code (si se utiliza este editor).

# Ejecución del programa
1. Clonar o descargar el repositorio.
2. Abrir el proyecto en el IDE de preferencia.
3. Verificar que esté configurado el JDK correspondiente.
4. Ejecutar la clase `Main.java`.
5. Ingresar o utilizar los puntos definidos en el programa.
6. Consultar los resultados obtenidos mediante ambos métodos.

## Pruebas numéricas

Para comprobar el funcionamiento de los métodos se utilizaron los siguientes puntos:
x = {1.0, 2.0, 4.0};
y = {2.0, 3.0, 10.0};
Punto de evaluación: x = 3.0

## Resultados del método de Lagrange
--- METODO DE LAGRANGE ---
El valor estimado en x = 3.00 es P(3.00) = 5.6667

--- METODO DE NEWTON ---

--- TABLA DE DIFERENCIAS DIVIDIDAS ---
x_i	f[x_i]	Orden 1	Orden 2	
-----------------------------------------------------
1.00	2.0000	1.0000	0.8333	
2.00	3.0000	3.5000	
4.00	10.0000	

--- COEFICIENTES DEL POLINOMIO (a_k) ---
a_0 = 2.0000
a_1 = 1.0000
a_2 = 0.8333

--- RESULTADO DE LA INTERPOLACION ---
El valor estimado en x = 3.00 es P(3.00) = 5.6667
