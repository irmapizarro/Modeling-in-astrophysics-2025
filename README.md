# Modeling-in-astrophysics-2025

# Proyectos de Modelamiento en Astrofísica (USACH, 2025A)

Este repositorio contiene los tres proyectos desarrollados por Irma Pizarro durante el curso **Modelamiento en Astrofísica**, impartido en la Universidad de Santiago de Chile (USACH) en el semestre 2025A. Cada proyecto fue guiado por un profesor distinto y aborda un problema diferente usando herramientas de modelamiento físico y computacional.

---

## 📁 Proyecto 1: Modelo del Potencial de Roche y Estabilidad en Sistemas Binarios

**Archivo principal**: `Modelamiento_Ileyk-4.pdf`

### Descripción:
Se modela la dinámica de una partícula de prueba bajo el potencial de Roche generado por dos masas puntuales \( M_1 \) y \( M_2 \) en rotación mutua. Se adimensionaliza el sistema para facilitar la simulación y se integran numéricamente las ecuaciones de movimiento en el marco rotante.

### Objetivos:
- Simular trayectorias de partículas en el plano binario.
- Identificar regiones de estabilidad o escape.
- Explorar los puntos de Lagrange y la geometría del potencial efectivo.

### Herramientas:
- Python (NumPy, SciPy)
- Integración numérica de EDOs
- Visualización con Matplotlib

---

## 📁 Proyecto 2: Modelamiento del Bronceado Humano

**Archivo principal**: `Bronceado_CamposPizarro.pdf`

### Descripción:
Se construye un modelo fisiológico para describir la síntesis de melanina, la acumulación de energía UV y el daño solar en función del tiempo y la localización geográfica. Se incorpora la influencia del tipo de piel, el protector solar (FPS) y la irradiancia simulada.

### Objetivos:
- Determinar la eficiencia del bronceado en distintas ubicaciones y condiciones.
- Optimizar la exposición solar segura.
- Visualizar mapas de eficiencia de bronceado.

### Herramientas:
- Python (SciPy, pandas, pvlib, Matplotlib)
- Resolución de EDOs (Runge-Kutta 5(4))
- Simulación geográfica sobre una malla lat-lon

---

## 📁 Proyecto 3: Modelamiento de SEDs en Estrellas Jóvenes (YSOs)

**Archivos**: `proyecto_modelamiento_pt2.ipynb`, `YSO_model2_irma_angel.ipynb`

### Descripción:
Se modela la emisión espectral de objetos estelares jóvenes (YSOs) combinando una estrella central y un disco circumestelar. Se utilizan modelos físicos para reproducir las distribuciones espectrales de energía (SEDs) observadas.

### Objetivos:
- Ajustar modelos teóricos a datos observacionales de YSOs.
- Explorar la influencia de parámetros como el índice de opacidad β, el radio interno/externo del disco, y la temperatura.
- Implementar modelos de disco plano y discos con capas.

### Herramientas:
- Python (Astropy, NumPy, Matplotlib)
- Métodos de ajuste espectral
- Análisis SED con datos reales

---

## 📌 Créditos

- **Estudiante**: Irma Pizarro  
- **Curso**: Modelamiento en Astrofísica (USACH, 2025A)  
- **Profesores**: Ileyk El Mellah, [Nombre profesor Proyecto 2], [Nombre profesor Proyecto 3]

---

## 🧠 Notas finales

Cada uno de estos proyectos aplica conceptos avanzados de física, astrofísica y biofísica usando herramientas de simulación numérica. Este repositorio puede servir como base para futuras investigaciones o extensiones en contextos biomédicos, astrofísicos o educativos.

