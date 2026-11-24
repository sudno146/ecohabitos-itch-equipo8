# 🌿 EcoHábitos ITCh

### Lo que consumes deja huella.

Aplicación web desarrollada como parte del proyecto integrador de la asignatura **Desarrollo Sustentable**, del Instituto Tecnológico de Chilpancingo.

EcoHábitos permite estimar la huella ambiental mensual de una persona a partir de sus hábitos de consumo, mostrando indicadores de agua directa, agua virtual, emisiones de CO₂ equivalente y gasto económico.

## 🌎 Aplicación en línea

**Acceso a la aplicación:** [EcoHábitos ITCh](https://TU-USUARIO.github.io/ecohabitos-itch-equipo8/)

> Sustituir el enlace anterior por la dirección real generada por GitHub Pages.

## 📌 Características principales

- Registro de hábitos de consumo mensual.
- Cálculo de agua directa y agua virtual.
- Estimación de emisiones de CO₂ equivalente (CO₂e).
- Estimación del gasto económico por categoría.
- Visualización gráfica de resultados.
- Equivalencia del consumo de agua en playeras.
- Recomendaciones personalizadas.
- Meta de reducción del 10 %.
- Historial de resultados mediante almacenamiento local.
- Exportación del historial a formato CSV.
- Validación de entradas numéricas.
- Consulta de metodología y factores utilizados.

## 🧩 Módulos de la aplicación

La aplicación está organizada en siete categorías:

| Módulo | Descripción |
|---|---|
| Agua | Consumo doméstico de agua. |
| Alimentos | Consumo de productos alimenticios y agua virtual. |
| Ropa | Huella asociada a prendas y calzado. |
| Transporte | Estimación de emisiones por desplazamientos. |
| Energía | Consumo eléctrico y gas LP. |
| Tecnología | Impacto asociado a dispositivos electrónicos e impresiones. |
| Residuos | Estimación de residuos y emisiones relacionadas. |

## 🛠️ Tecnologías utilizadas

- **HTML5:** estructura de la aplicación.
- **CSS3:** estilos, diseño adaptable y componentes visuales.
- **JavaScript:** validaciones, procesamiento de datos y funciones de cálculo.
- **localStorage:** persistencia local del historial.
- **GitHub Pages:** alojamiento y publicación de la aplicación.

La aplicación está implementada en un único archivo HTML, sin necesidad de instalar dependencias ni ejecutar un servidor de desarrollo.

## 🚀 Instalación y ejecución

No se requiere instalación.

### Ejecución local

1. Descargar o clonar este repositorio.
2. Abrir el archivo `index.html`.
3. Ejecutarlo en un navegador moderno, preferentemente Google Chrome.
4. Completar los módulos de consumo.
5. Pulsar el botón de cálculo para obtener los resultados.

### Ejecución en línea

También puede utilizarse directamente desde el enlace de GitHub Pages.

## 📊 Prueba de funcionamiento

La aplicación incorpora un caso de prueba de referencia correspondiente al Anexo B.

Resultados esperados del módulo de agua:

| Indicador | Resultado esperado |
|---|---:|
| Agua directa | 2,598 L |
| Gasto | $90 MXN |
| Estado de la prueba | PASA |

Estos resultados corresponden al caso de prueba y no representan un consumo real de todos los usuarios.

## 💾 Almacenamiento y privacidad

La aplicación utiliza `localStorage` para conservar el historial en el navegador del dispositivo.

- No solicita nombre ni correo electrónico.
- El historial permanece almacenado localmente.
- Los datos del historial no se sincronizan automáticamente con un servidor.
- El usuario puede descargar o eliminar su historial.

Los resultados son estimaciones educativas y dependen de los factores y supuestos utilizados.

## 📚 Metodología y documentación

Los cálculos utilizan factores ambientales documentados, unidades de medida y referencias bibliográficas.

La aplicación incorpora una sección de metodología y fuentes para consultar los factores utilizados y sus niveles de certeza.

La documentación académica complementaria comprende:

- Anexo A: prácticas de programación.
- Anexo D: archivo común de factores.
- Anexo G: registro de pruebas.
- Anexo F: protocolo de prueba con usuarios.

## 👥 Equipo de desarrollo

**Equipo 8 — Versión C**

Instituto Tecnológico de Chilpancingo (ITCh).

- Cesar Garduño
- Rubén Santana
- Ricardo Abreu
- Marcos Pérez

**Asignatura:** Desarrollo Sustentable  
**Proyecto:** EcoHábitos ITCh  
**Papel del equipo:** Motor de cálculo y factores.

## ⚠️ Consideraciones

EcoHábitos es una herramienta educativa de estimación ambiental. Sus resultados no deben interpretarse como mediciones exactas de la huella individual ni como valores universales.

Algunos factores corresponden a promedios o aproximaciones y pueden variar según la región, el producto y las condiciones de consumo.

## 📄 Licencia

Proyecto académico desarrollado para fines educativos.

Las condiciones de reutilización y distribución deben establecerse con autorización de sus autores y de acuerdo con las disposiciones aplicables del proyecto.
