# ⚽ Fútbol - Top 100 Leyendas del Fútbol Mundial

![Football](https://img.shields.io/badge/Football-Soccer-green?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3.8+-blue?style=for-the-badge&logo=python)
![Status](https://img.shields.io/badge/Status-Complete-success?style=for-the-badge)

## 📋 Descripción

Análisis exploratorio completo de los **100 mejores futbolistas de la historia** utilizando Python, Pandas, Machine Learning y visualizaciones profesionales.

## 🎯 Objetivos

- Analizar estadísticas de los mejores futbolistas (1945-2024)
- Identificar correlaciones entre goles, asistencias y títulos
- Segmentar jugadores con clustering K-Means
- Visualizar evolución del fútbol por décadas

## 🏆 Hallazgos Principales

### Top 5 Jugadores

1. **Lionel Messi** - Rating: 99.2/100 - 821 goles - 8 Balones de Oro
2. **Cristiano Ronaldo** - Rating: 98.8/100 - 895 goles - 5 Balones de Oro
3. **Pelé** - Rating: 98.5/100 - 767 goles - 3 Mundiales
4. **Diego Maradona** - Rating: 98.2/100 - 346 goles - 1 Mundial
5. **Johan Cruyff** - Rating: 97.8/100 - 291 goles - 3 Balones de Oro

### Estadísticas Clave

- **Calificación Promedio:** 82.1/100
- **Máximo Goleador:** Cristiano Ronaldo (895 goles)
- **Más Balones de Oro:** Lionel Messi (8)
- **Más Champions League:** Cristiano Ronaldo (5)
- **Confederación dominante:** UEFA (70%)

## 📊 Dataset

- **Total jugadores:** 100
- **Período:** 1945-2024
- **Variables:** 19 columnas
- **Jugadores activos:** 30

## 🛠️ Tecnologías

- **Python 3.8+**
- **Pandas, NumPy** - Manipulación de datos
- **Matplotlib, Seaborn, Plotly** - Visualizaciones
- **Scikit-learn** - Clustering K-Means
- **Scipy** - Tests estadísticos

## 📁 Archivos del Proyecto
```
├── Futbol_Top100_Leyendas.csv          # Dataset original
├── Futbol_Top100_Analizado.csv         # Dataset con clusters
├── Resumen_Analisis_Futbol.csv         # Métricas principales
├── Analisis_Por_Decada.csv             # Evolución temporal
├── Analisis_Por_Confederacion.csv      # Análisis geográfico
├── Estadisticas_Por_Posicion.csv       # Por posición
├── Hallazgos_Principales.txt           # Insights en texto
└── Futbol_Analisis_Completo.zip        # Todo en ZIP
```

## 🚀 Cómo Usar
```python
import pandas as pd

# Cargar datos
df = pd.read_csv('Futbol_Top100_Leyendas.csv')

# Explorar
print(df.head())
print(df.describe())

# Ver hallazgos
with open('Hallazgos_Principales.txt', 'r', encoding='utf-8') as f:
    print(f.read())
```

## 📈 Análisis Realizados

1. ✅ Análisis Exploratorio de Datos (EDA)
2. ✅ Matriz de Correlaciones
3. ✅ Análisis Temporal por Décadas
4. ✅ Clustering K-Means (4 grupos)
5. ✅ Análisis por Confederación y Posición
6. ✅ Tests Estadísticos (ANOVA, Shapiro-Wilk)

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Para contribuir:

1. Fork el proyecto
2. Crea una rama (`git checkout -b feature/mejora`)
3. Commit (`git commit -m 'Mejora agregada'`)
4. Push (`git push origin feature/mejora`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver [LICENSE](LICENSE) para más detalles.

## 👤 Autor

**Programan1008**
- GitHub: [@Programan1008](https://github.com/Programan1008)

## 🙏 Agradecimientos

- Datos de fuentes públicas (Transfermarkt, FIFA, UEFA)
- Comunidad de data science
- Fanáticos del fútbol mundial

---

⭐ **Si te gustó este proyecto, dale una estrella!**
