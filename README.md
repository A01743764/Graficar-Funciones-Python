# Evaluador de Funciones Basico

## Descripcion
Este proyecto es un **evaluador de funciones matematicas** desarrollado en Python que permite calcular valores y generar graficas para diferentes tipos de funciones. Es una herramienta educativa diseñada para ayudar en el estudio y visualizacion de funciones matematicas basicas.

## Funcionalidades
El evaluador soporta las siguientes funciones matematicas:

1. **Funcion Lineal**: `f(x) = mx + b`
2. **Funcion Cuadratica**: `f(x) = ax² + bx + c`
3. **Funcion Cubica**: `f(x) = ax³ + bx² + cx + d`
4. **Funcion Exponencial**: `f(x) = aˣ`
5. **Funcion Logaritmica**: `f(x) = logₐ(x)`
6. **Funcion Racional**: `f(x) = a/(bx)`
7. **Funcion Raiz**: `f(x) = ⁿ√x` (x^(1/n))

## Caracteristicas Tecnicas

### Librerias Utilizadas
- **NumPy**: Para operaciones matematicas
- **Matplotlib**: Para generacion de graficas
- **Math**: Para funciones matematicas basicas

### Funcionalidades del Sistema
- **Evaluacion de funciones** en rangos personalizables
- **Generacion de graficas** automaticas
- **Guardado de resultados** en archivo de registro (`registro.txt`)
- **Exportacion de graficas** como imagenes PNG
- **Validacion de entradas** para evitar errores matematicos

## Instalacion y Uso

### Prerrequisitos
```bash
pip install numpy matplotlib
```

### Ejecucion
```bash
python EFP_notebook.ipynb
```

### Flujo de Uso
1. **Seleccionar tipo de funcion** (1-7)
2. **Ingresar parametros** especificos de cada funcion
3. **Definir rango de evaluacion** (valor inferior, superior e intervalo)
4. **Visualizar resultados** (valores calculados y grafica)
5. **Resultados guardados** automaticamente en `registro.txt`

## Estructura del Proyecto

```
EFP_notebook.ipynb          # Notebook principal del proyecto
registro.txt               # Archivo de registro de funciones evaluadas
lineal.png                 # Grafica de funcion lineal (generada)
cuadratica.png             # Grafica de funcion cuadratica (generada)
cubica.png                 # Grafica de funcion cubica (generada)
exp.png                    # Grafica de funcion exponencial (generada)
log.png                    # Grafica de funcion logaritmica (generada)
racional.png               # Grafica de funcion racional (generada)
raiz.png                   # Grafica de funcion raiz (generada)
```

## Validaciones Implementadas

### Para todas las funciones:
- Validacion de rangos de evaluacion
- Manejo de valores inversos (inferior > superior)

### Validaciones especificas:
- **Logaritmica**: Base > 0 y ≠ 1, dominio > 0
- **Racional**: Evita division por cero
- **Raiz**: Manejo de raices pares con numeros negativos

## Ejemplo de Salida

```
La funcion lineal es:
f(x) = 2.0x + 1.0

Los valores de x son: [0.0, 1.0, 2.0, 3.0]
Los valores de y son: [1.0, 3.0, 5.0, 7.0]
```

## Autor
**Jesus Oscar Flores Cota** - A01743764

## Licencia
Este proyecto es de uso academico y educativo.
