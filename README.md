<p align="center"><img src="logo.svg" width="96" alt="RatioAvis"></p>

# RatioAvis

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23050777.svg)](https://doi.org/10.5281/zenodo.23050777)

**La razón al servicio del ave · Reason in the service of the bird**

👉 **App:** https://hectortecumshe-ai.github.io/RatioAvis/ — botón **ES / EN** para cambiar de idioma.

*Ratio* (latín): razón, cálculo, origen de la palabra «ración». *Avis*: ave.

---

## Español

RatioAvis formula dietas de **mínimo costo para pollo de engorda** mediante programación lineal (método símplex en dos fases con certificado de optimalidad). Es un solo archivo HTML que funciona en el navegador: sin instalación, sin servidor, y ningún dato sale de la computadora del usuario.

- Líneas genéticas: Ross 308, Arbor Acres Plus, Cobb 500, Hubbard Efficiency Plus, pollo de crecimiento lento, NRC (1994) y perfil personalizado (NASEM 2025, Tablas Brasileñas 2024).
- Condiciones de producción: altitud, calor, balance electrolítico y pigmentación.
- 29 ingredientes con aminoácidos totales y digestibles, matriz editable.
- Programa multifase, informe, exportación a CSV y proyecto guardable.
- **Dos vistas (botón Productor / Científico):** la de productor muestra lo esencial en lenguaje sencillo, con hoja de mezclado en kg y costo por pollo; la científica muestra el modelo de programación lineal, precios sombra, costos reducidos, certificado de dualidad, los 20 nutrientes, validación y referencias, con exportación del modelo en JSON.
- Ayuda contextual: cada parámetro, índice e indicador tiene un signo **?** con su concepto y escala de decisión.
- **Validación:** reencuentra exactamente 6 de 6 fórmulas publicadas (Rev. Mex. Cienc. Pecu. 2020; *Animals* 2025; *Poultry* 2022) y coincide con HiGHS/SciPy en 400 problemas aleatorios.

## English

RatioAvis formulates **least-cost broiler diets** by linear programming (two-phase simplex with an optimality certificate). It is a single HTML file running in the browser: no installation, no server, and no data leaves the user's computer.

- Genetic lines: Ross 308, Arbor Acres Plus, Cobb 500, Hubbard Efficiency Plus, slow-growing birds, NRC (1994) and a custom profile (NASEM 2025, Brazilian Tables 2024).
- Production conditions: altitude, heat, electrolyte balance and pigmentation.
- 29 ingredients with total and digestible amino acids, editable matrix.
- Multiphase program, report, CSV export and savable project.
- **Two views (Producer / Scientist button):** the producer view shows the essentials in plain language, with a mixing sheet in kg and cost per bird; the scientist view shows the linear-programming model, shadow prices, reduced costs, duality certificate, all 20 nutrients, validation and references, with JSON export of the model.
- Context help: every parameter, index and indicator has a **?** sign with its concept and decision scale.
- **Validation:** recovers exactly 6 of 6 published formulas and matches HiGHS/SciPy on 400 random problems.

## Cómo citar · How to cite

Mojica-Zárate, H. T., & Barrera-Guzmán, L. A. (2026). *RatioAvis: Guided least-cost diet formulation for broiler chickens* (Version 1.1.0) [Software]. https://doi.org/10.5281/zenodo.23050777

## Autores · Authors

Héctor Tecumshé Mojica Zárate · Luis Ángel Barrera Guzmán — MIT License

> Herramienta de apoyo; los resultados deben ser revisados por un profesional en nutrición animal. · Decision-support tool; results should be reviewed by a qualified animal nutritionist.
