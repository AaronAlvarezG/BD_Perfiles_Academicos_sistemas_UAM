# BD_Perfiles_Academicos_sistemas_UAM
Conjunto de datos estructurado de perfiles académicos y publicaciones, recolectado desde plataformas públicas como ORCID, Scopus, Google Scholar y el portal institucional UAM, con el objetivo de alimentar un sistema de recomendación basado en grafos de conocimiento.

# Dataset de Perfiles Académicos - UAM

Este repositorio contiene el dataset generado como parte del trabajo titulado:

**“Sistema de búsqueda y recomendación de perfiles académicos basado en grafos de conocimiento”**

El dataset fue construido a partir de la recolección, validación y estructuración de datos de investigadores adscritos al Departamento de Sistemas de la Universidad Autónoma Metropolitana (UAM), combinando fuentes institucionales y bases académicas públicas.

---

## 📂 Estructura del repositorio

- `/data/json/`: Archivos en formato JSON.
- `/data/xml/`: Archivos en formato XML.
- `/data/csv/`: Archivos en formato CSV.
- `investigadores.*`: Información consolidada sobre los investigadores.
- `articulos.*`: Publicaciones académicas asociadas a cada investigador.

---

## 🧮 Fuentes de datos utilizadas

- [Portal de Investigación UAM](https://investigacion.uam.mx)
- [ORCID API](https://orcid.org/)
- [Scopus API](https://dev.elsevier.com/)
- [Google Scholar](https://scholar.google.com/) mediante web scraping controlado

---

## 🔍 Campos incluidos

### 🧑 Investigadores

- ID Investigador
- Nombre completo
- Perfil institucional
- Correo electrónico
- Grado académico
- Cuerpo académico
- Identificadores en ORCID, Scopus y Google Scholar
- Áreas de interés
- Trabajo académico
- Incidencia en los ODS

### 📄 Publicaciones

- Título
- Año
- Autores
- Resumen
- DOI
- Revista / Conferencia
- Fuente (Scopus, ORCID, Scholar)
- Enlace al artículo
- Citas totales (cuando disponibles)

---

## 🛠️ Tecnologías utilizadas

- Python
- Selenium
- BeautifulSoup
- ORCID & Scopus APIs
- Exportación en formatos CSV, JSON y XML

---

## 📜 Licencia

Este dataset se distribuye con fines académicos y de investigación. Los datos provienen de fuentes públicas y se respetan las políticas de uso de cada plataforma. Si reutilizas este dataset, por favor cita este repositorio o la publicación asociada.

---

## ✏️ Cita sugerida
