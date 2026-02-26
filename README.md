# 🎾 El Fin de la Era de los Big 3
### Análisis del dominio de Federer, Nadal y Djokovic vs las nuevas generaciones (2015-2024)

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Status](https://img.shields.io/badge/Status-En%20Desarrollo-yellow)

---

## 📖 Descripción

Durante una década, tres jugadores redefinieron los límites del tenis hasta que el tiempo, los retiros y una nueva generación finalmente les arrebató el trono, dejando en el camino a toda una generación que nunca tuvo su oportunidad.

Este proyecto analiza con datos reales la evolución del dominio en el tenis ATP entre 2015 y 2024, contando la historia de tres generaciones: el Big 3, la Generación Olvidada y la Nueva Generación.

---

## 📊 Estructura del Proyecto

```
tennis-analytics-big3/
│
├── notebooks/
│   ├── capitulo1_big3_vs_nueva_gen.ipynb
│   └── capitulo2_generacion_olvidada.ipynb
│
├── imagenes/
│   ├── 01_big3_vs_nueva_gen.png
│   ├── 02_titulos_individuales.png
│   ├── 03_titulos_por_superficie.png
│   ├── 04_porcentaje_dominio.png
│   ├── 05_gen_olvidada_finales.png
│   ├── 06_ventana_dominio.png
│   └── 07_gen_olvidada_individual.png
│
└── README.md
```

---

## 📚 Fuente de Datos

Los datos provienen del repositorio público de **Jeff Sackmann**:
- 🔗 [tennis_atp — GitHub](https://github.com/JeffSackmann/tennis_atp)

Se utilizaron los archivos `atp_matches_{año}.csv` desde 2015 hasta 2024, filtrando únicamente torneos **Grand Slam** y **Masters 1000**.

---

## 🎭 La Historia en Capítulos

### Capítulo 1 — El Imperio y su Caída

Análisis del dominio colectivo e individual del Big 3 (Federer, Nadal, Djokovic) frente a la Nueva Generación (Alcaraz, Sinner, Medvedev, Zverev).

**Visualizaciones:**
- Títulos por grupo por año (2015-2024)
- Títulos individuales del Big 3 vs Nueva Generación
- Dominio por superficie (Hard, Clay, Grass)
- Porcentaje de dominio por grupo por año

**Hallazgos clave:**
- En 2015 el Big 3 ganó el 77% de los torneos grandes
- El cruce histórico ocurrió en 2021-2022 cuando la Nueva Gen alcanzó al Big 3
- En 2024 el Big 3 desapareció completamente con 0% de títulos
- Djokovic fue el dominador absoluto en cancha dura, Nadal en tierra batida
- Alcaraz es el único de la Nueva Gen que domina todas las superficies

---

### Capítulo 2 — La Generación Olvidada

Análisis profundo de Zverev, Medvedev, Thiem y Tsitsipas: la generación que llegó en el peor momento posible.

**Visualizaciones:**
- Victorias vs derrotas en finales por jugador
- Ventana de dominio por generación
- Evolución individual con títulos y finales perdidas

**Hallazgos clave:**
- Thiem perdió sus 4 finales grandes contra el Big 3, nunca tuvo otra oportunidad
- Tsitsipas perdió 5 de sus 6 finales contra el Big 3
- Medvedev jugó 16 finales, el más activo pero bloqueado por dos generaciones
- Zverev es el único jugador que perdió finales contra las 3 generaciones distintas
- Su único peak (2016) ocurrió cuando el Big 3 estaba lesionado, no porque los superaran

---

## 🛠️ Tecnologías Utilizadas

- **Python 3.x**
- **Pandas** — limpieza y análisis de datos
- **Matplotlib** — visualizaciones
- **Seaborn** — gráficos estadísticos
- **Jupyter Notebook** — entorno de desarrollo

---

## ▶️ Cómo Ejecutar el Proyecto

1. Clona el repositorio:
```bash
git clone https://github.com/gabrielhdez41/tennis-analytics-big3.git
cd tennis-analytics-big3
```

2. Instala las dependencias:
```bash
pip install pandas matplotlib seaborn jupyter
```

3. Abre Jupyter y ejecuta los notebooks en orden:
```bash
jupyter notebook
```

---

## 🔮 Próximos Pasos

- [ ] Capítulo 3: Sinner vs Alcaraz — La batalla por el trono
- [ ] Análisis de estadísticas de saque por generación
- [ ] Predicción de resultados con Machine Learning

---

## 👤 Autor

**Gabriel Hdez**
- GitHub: [@gabrielhdez41](https://github.com/gabrielhdez41)

---

## 📄 Licencia

Este proyecto es de uso educativo y personal. Los datos pertenecen a Jeff Sackmann bajo su licencia correspondiente.
