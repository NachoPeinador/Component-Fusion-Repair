# Reparación Óptima de Redes Neuronales: Alcanzando los Límites Teóricos en la Recuperación de Fragmentos mediante la Fusión de Componentes

[![Read in English](https://img.shields.io/badge/Read%20in-English%20%F0%9F%87%AC%F0%9F%87%A7-007BFF.svg)](README_EN.md)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0008--1822--3452-A6CE39.svg?logo=orcid&logoColor=white)](https://orcid.org/0009-0008-1822-3452) [![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT) [![DOI](https://img.shields.io/badge/DOI-PENDIENTE-lightgrey.svg)]() [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1234567.svg)](https://doi.org/10.5281/zenodo.1234567)

Este repositorio contiene el código, los datos y los experimentos del artículo de investigación "Optimal Neural Network Repair: Achieving Theoretical Limits in Fragment Recovery via Component Fusion".

El proyecto establece y valida empíricamente el límite teórico para la reparación de redes neuronales: el número mínimo de conexiones requeridas para restaurar la integridad estructural es exactamente igual al número de componentes fragmentados. Nuestros hallazgos se validan en una red a gran escala (850 neuronas) bajo daño severo (poda aleatoria del 85%) y se confirman con un robusto análisis estadístico de 100 réplicas independientes.¹

![Análisis estadístico de las estrategias de reparación](figures/figure_robustness_analysis.png)
*Análisis estadístico de las estrategias de reparación en 100 réplicas independientes bajo una poda aleatoria del 85%, demostrando la consistencia perfecta y la superioridad de la Fusión de Componentes.*
¹

## 🎯 Contribuciones Principales
* 🔬 **Límite Teórico Validado:** Demostramos que el mínimo de conexiones para una reparación completa es igual al número de fragmentos ($C_{\text{min}} = F$).¹
* 💯 **Fiabilidad Determinista:** Nuestro método (Fusión de Componentes) alcanzó una tasa de éxito del 100% en 100 réplicas, mientras que los baselines lograron solo un 1% y 0%.¹
* 💡 **Optimalidad de Recursos:** Logramos una reparación perfecta utilizando un 50% menos de conexiones que las estrategias de referencia, a las cuales se les otorgó el doble de presupuesto y aun así fallaron.¹
* ⚙️ **Rigor Estadístico:** Todos los hallazgos fueron validados bajo condiciones de estrés severo (poda aleatoria del 85% en una red de 850 neuronas) para garantizar su robustez.¹

## 🔬 Experimento Interactivo y Reproducible
Este repositorio está diseñado para la ciencia abierta y la reproducibilidad total. Puedes ejecutar el pipeline completo, desde la generación de la red hasta el análisis estadístico y la visualización de resultados, en el siguiente cuaderno de Google Colab.

**Pipeline de Validación Completo**
Ejecuta el experimento a gran escala y el test de robustez de 100 réplicas para validar los hallazgos del artículo.

## 📂 Estructura del Repositorio
* `Component_Fusion_Experiment.ipynb`: El cuaderno de Colab interactivo con todos los experimentos.
* `/data`: Contiene los archivos .csv con los resultados detallados de las 100 réplicas.
* `/figures`: Contiene las figuras generadas en alta calidad para el artículo.
* `LICENSE`: La licencia MIT del proyecto.
* `README.md`: Este archivo.

## 🔬 Ciencia Independiente y Abierta
Este trabajo se realizó de manera completamente independiente, sin financiación institucional ni corporativa, demostrando que la investigación de frontera puede surgir también desde entornos abiertos y accesibles. Este proyecto es la aplicación práctica y validación empírica de los principios explorados en el [proyecto Topological Reinforcement Operator](https://github.com/NachoPeinador/Topological-Reinforcement-Operator).

[![Sponsor @NachoPeinador](https://img.shields.io/badge/Hazte%20Sponsor-%E2%9D%A4-%23db61a2.svg)](https://github.com/sponsors/NachoPeinador)

## 🚀 Apoya y Difunde esta Investigación
Como investigador independiente, la visibilidad y el impacto de este trabajo dependen en gran medida del apoyo de la comunidad. Si esta investigación te ha resultado útil o interesante, aquí tienes algunas formas concretas de ayudar:

* **⭐️ Dale una Estrella en GitHub:** Es la forma más rápida y directa de mostrar tu apoyo y ayudar a que otros descubran este proyecto.
* **🔄 Comparte en Redes Sociales:** Publica un enlace al preprint del artículo o a este repositorio en Twitter (X), LinkedIn o tu red académica preferida.
* **✍️ Cita el Trabajo:** Si esta metodología inspira tu propia investigación, la citación es la forma más valiosa de reconocimiento en la ciencia.
* **💬 Inicia una Discusión:** ¿Tienes ideas, preguntas o críticas constructivas? Abre un "Issue" aquí en el repositorio.

¡Gracias por tu apoyo para hacer visible la ciencia independiente!

## ✍️ Citación
Fragmento de código BibTeX
```bibtex
@article{PeinadorSala2025,
  author    = {Jos\'{e} Ignacio Peinador Sala},
  title     = {Optimal Neural Network Repair: Achieving Theoretical Limits in Fragment Recovery via Component Fusion},
  journal   = {arXiv preprint arXiv:XXXX.XXXXX},
  year      = {2025}
}
