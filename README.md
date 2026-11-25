# 📊 Anexo Cuantitativo: Plan Estratégico de Desarrollo Local 2027–2030

**Territorio:** Cantón Tulcán, Provincia del Carchi, Ecuador  
**Enfoque:** Desarrollo Endógeno Sostenible y Cuádruple Hélice  
**Autor:** Salomón Riofrío Rosero  
**Asignatura:** Desarrollo Local  
**Institución:** Centro Educativo  

---

## 🎯 Objetivo del Repositorio

Este repositorio contiene el respaldo computacional, estadístico y econométrico del Plan Estratégico de Desarrollo Local 2027–2030 del cantón Tulcán. Todo el análisis fue desarrollado en Python bajo principios de **reproducibilidad científica** (semilla fija `np.random.seed(42)` y validaciones `assert` en cada módulo).

---

## 📂 Estructura del Proyecto

```text
tulcan-deslocal-2027-2030/
├── notebooks/
│   └── 01_analisis_cuantitativo_tulcan.ipynb   # Notebook principal (Módulos 1 y 2)
├── data/
│   └── raw/
│       └── enemdu_carchi_limpio.csv            # Microdatos ENEMDU 2025 filtrados
├── outputs/
│   ├── figuras/                                # Gráficos APA 7, 300 DPI
│   │   ├── Figura1_Asignacion_Presupuestaria.png
│   │   └── Figura2_Comparacion_Metas_2030.png
│   └── tablas/                                 # Tablas ejecutivas y resumen econométrico
│       ├── asignacion_presupuestaria.csv
│       ├── simulacion_metas_2030.csv
│       └── resumen_econometrico_modulo2.xlsx
├── requirements.txt                            # Dependencias Python fijadas
└── README.md                                   # Este documento
