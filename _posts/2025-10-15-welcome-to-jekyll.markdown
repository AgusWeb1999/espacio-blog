---
layout: post
title: "Visualización en tiempo real de la ISS con Python"
date: 2025-10-15
categories: [ciencia, satélites]
tags: [python, iss, skyfield, nasa]
---

En este artículo mostramos cómo usar la librería **Skyfield** en Python para obtener la posición actual de la Estación Espacial Internacional y graficarla sobre un mapa interactivo 🌍.

```python
from skyfield.api import load
