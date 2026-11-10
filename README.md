# Calculadora Java

Calculadora base con sus principales funciones,  y probar el control de versiones.
Practica 3 con Maven Git y GitHub

# Requisitos y Compilación

Lenguaje: Java 21 o superior
Herramienta: NetBeans Maven
Compilar: Para compilar el proyecto ejecuta `mvn clean compile`

# Métodos Disponibles
La clase `Calculadora` incluye las siguientes operaciones:

`sumar(a, b)`: Suma dos valores.
`restar(a, b)`: Resta el segundo valor al primero.
`multiplicar(a, b)`: Multiplica ambos valores.
`dividir(a, b)`: Divide el primero entre el segundo. Lanza una excepción si el divisor es 0.
`potencia(base, exponente)`: Eleva la base al exponente indicado.
`modulo(a, b)`: Calcula el resto de la división. Lanza una excepción si el divisor es 0.

# Ejemplo de ejecución

Al ejecutar el proyecto se mostrará:
Suma: 25.0
Resta: 15.0
Multiplicación: 100.0
División: 4.0
Potencia (2^3): 8.0
Módulo (20%3): 2.0