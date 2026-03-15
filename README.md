# tyke-web
Tyke-web: Username OSINT Tool website

Tyke as a web service.

**Tyke** es una herramienta OSINT (reconocimiento) que busca la presencia de un nombre de usuario en cientos de plataformas y redes sociales. Esta es su versión web, lista para desplegar en servicios como Northflank, Render o cualquier host que soporte Python.

> ⚠️ **Importante**: Esta herramienta es solo para fines educativos y de investigación. No la uses sin autorización ni con intenciones maliciosas.

---

## 🚀 Características

- Búsqueda en **568 sitios** (según tu lista en `sites.py`).
- Sistema de puntuación (scoring) para clasificar resultados en **EXISTS_HIGH**, **EXISTS_WEAK**, **NOT_FOUND**.
- Filtrado por perfiles: `core`, `security`, `dev`, `social`, `gaming`, `creative`, `business`.
- Interfaz web responsive (HTML/CSS/JS) que muestra los resultados agrupados por usuario y ordenados por puntuación.
- Backend en Python/Flask que ejecuta la lógica original de Tyke.

---

## License

This project is licensed under the **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International** license.

See the [LICENSE](LICENSE) file for details.

License URL: https://creativecommons.org/licenses/by-nc-sa/4.0/
