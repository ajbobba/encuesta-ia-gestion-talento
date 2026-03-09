# Encuesta: Percepción de la IA en la Gestión de Talento Humano

> Análisis estadístico de una encuesta realizada como parte de una tesis de maestría sobre cómo líderes, colaboradores, directivos y profesionales de RRHH perciben la incorporación de inteligencia artificial en la gestión de personas.

---

## Contexto

Este repositorio contiene el código de análisis de datos de una encuesta aplicada a **193 personas** distribuidas en cuatro roles organizacionales: Colaboradores, Líderes, Dirección/Gerencia y RRHH. La encuesta abarca temas de familiaridad con IA, aceptación de tecnologías específicas, factores de retención y preocupaciones éticas.

---

## Estructura del análisis

| Sección | Descripción |
|---|---|
| 1. Configuración | Carga de datos, limpieza y preparación |
| 2. Perfil de Encuestados | Distribución por rol, género, modalidad y empresa |
| 3. Factores de Retención | Análisis de los factores que retienen talento y su correlación con la intención de irse |
| 4. Familiaridad y Uso de IA | Nivel de familiaridad, frecuencia de uso, confianza y percepción |
| 5. Percepción por Rol: Gestión de Talento | Análisis Likert por rol sobre aplicaciones de IA en RRHH |
| 6. Percepción por Rol: Comunicación y Emociones | Análisis Likert sobre IA en análisis de comunicación y emociones |
| 7. Preocupaciones Éticas | Dos dimensiones: Preocupación por privacidad y Valoración de transparencia |
| 8. Análisis por Tecnología | Scoring de aceptación para 8 tecnologías (People Analytics, Sentiment Analysis, Chatbots, etc.) |
| 9. Correlaciones | Correlaciones de Spearman entre variables clave |
| 10. Síntesis de Hallazgos | Hallazgos principales y recomendaciones |

---

## Tecnologías analizadas

`People Analytics` · `Upskilling/Reskilling` · `Chatbots RRHH` · `Sentiment Analysis` · `Bienestar Emocional` · `Movilidad Interna` · `Network Analysis` · `Compensación IA`

---

## Stack técnico

- **Python 3** · Jupyter Notebook
- `pandas` · `numpy` — manipulación y análisis de datos
- `scipy` — estadística (Spearman, Kruskal-Wallis, Mann-Whitney)
- `matplotlib` · `seaborn` — visualizaciones
- `python-docx` · `pygments` — exportación a Word con syntax highlighting

---

## Archivos

```
analisis_encuesta_tesis_20260127.ipynb   # Notebook principal
notebook_a_word.py                       # Script de exportación a Word (.docx)
```

---

## Muestra

| Rol | n | % |
|---|---|---|
| Colaborador | 93 | 48.2% |
| Líder | 50 | 25.9% |
| Dirección/Gerencia | 29 | 15.0% |
| RRHH | 21 | 10.9% |
| **Total** | **193** | **100%** |

Modalidad: Híbrido (44%) · Remoto (34%) · Presencial (22%)

---

## Hallazgos principales

- Las tecnologías de **"desarrollo" (Upskilling, Movilidad, Compensación)** tienen mayor aceptación que las de **"vigilancia" (Sentiment Analysis, Network Analysis)**
- **Dirección/Gerencia** muestra mayor aceptación general de IA; **Colaboradores** son los más cautelosos
- La **confianza en IA** y la **familiaridad** son los predictores más fuertes de aceptación tecnológica
- Existe una tensión ética entre la valoración de transparencia y la preocupación por privacidad

---

## Autor

**Agustín Bobba** — Tesis de Maestría
