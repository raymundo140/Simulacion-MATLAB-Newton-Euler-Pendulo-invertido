# Péndulo Invertido con Control PD en MATLAB

Este repositorio contiene la implementación de un **péndulo invertido sobre un carrito**, controlado mediante un **controlador PD (Proporcional-Derivativo)** en MATLAB.

## 📌 Descripción
El objetivo del sistema es mantener el equilibrio del péndulo sobre el carrito mediante el ajuste de una fuerza de control **u**. Para ello, se utiliza un **control PD** que regula la posición del carrito y el ángulo del péndulo.

El código realiza lo siguiente:
- Define los parámetros físicos del sistema.
- Establece condiciones iniciales.
- Implementa un **control PD** basado en errores de posición y velocidad.
- Resuelve las ecuaciones de movimiento mediante **integración numérica (método de Euler).**
- Grafica la evolución de la **posición y velocidad** del carrito y el péndulo.

## 📂 Estructura del repositorio
```
📁 pendulo-invertido-matlab
│── 📜 README.md
│── 📜 pendulo_invertido.m   # Código principal en MATLAB
│── 📜 control_PD.m          # Implementación del controlador PD
│── 📜 graficas.m            # Script para generar gráficos
└── 📁 img                   # Carpeta con imágenes de las simulaciones
```

## 🚀 Instalación y Ejecución
### 1️⃣ Requisitos
- MATLAB (R2020a o superior recomendado)

### 2️⃣ Clonar el repositorio
```bash
git clone https://github.com/tu-usuario/pendulo-invertido-matlab.git
cd pendulo-invertido-matlab
```

### 3️⃣ Ejecutar el código en MATLAB
Abre **MATLAB** y corre el script principal:
```matlab
run('pendulo_invertido.m')
```
Esto iniciará la simulación del péndulo invertido y generará los gráficos de la evolución del sistema.

## 📊 Resultados esperados
Tras la ejecución del código, se generarán las siguientes gráficas:
- **Evolución de la posición y velocidad del carrito**
- **Evolución del ángulo y velocidad angular del péndulo**
- **Evolución de la fuerza de control aplicada**

## 🛠️ Mejoras futuras
- Implementar un **controlador PID** en lugar de PD para mejorar la respuesta del sistema.
- Agregar una interfaz gráfica en MATLAB.
- Extender el código para simulación en **Simulink**.

## 📜 Licencia
Este proyecto es de código abierto bajo la **Licencia MIT**.

---
📌 **Autores:** [Tu Nombre] - [Tu Usuario de GitHub]  
📌 **Repositorio:** [GitHub Repo](https://github.com/tu-usuario/pendulo-invertido-matlab)
