# CalculadoraBasica

Aplicación de escritorio en Java (Swing) con una calculadora básica y un conversor
de °F a °C. Proyecto de NetBeans (Ant) para Programación III.

## Requisitos
- Git
- JDK 24 o superior (el proyecto está configurado con `javac.source=24`). Probado con JDK 25 (Temurin).
- Apache NetBeans. Probado con la versión 31.

## Cómo ejecutarlo
1. Clona el repositorio:
```
   git clone https://github.com/cesarwick917-lab/programacion3-proyecto. programacion3-proyecto
```
2. En NetBeans: File > Open Project... y elige la carpeta `CalculadoraBasica`
   (la que está dentro del repositorio clonado).
3. Clic derecho sobre el proyecto > Run (o F6). Se abre la ventana
   "Calculadora y Conversor"; no hace falta configurar nada más.
4. Para comprobar que funciona: escribe 8 en Valor1 y 2 en Valor2, pulsa Sumar
   y el campo Resultado muestra la suma.

## Nota sobre la terminal
El proyecto usa la librería Absolute Layout (`libs.absolutelayout` en
`nbproject/project.properties`), que viene incluida con NetBeans. Por eso se
recomienda abrir y ejecutar el proyecto desde NetBeans; compilar con `ant`
fuera de NetBeans requiere tener esa librería disponible.