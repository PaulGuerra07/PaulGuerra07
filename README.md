# Paúl Andrés Guerra Vicuña

**Ingeniería en Ciencia de Datos e Inteligencia Artificial — Universidad Nacional de Chimborazo (UNACH)**
Riobamba, Ecuador · Carrera de 8 semestres · Cursando el tercer semestre

Trabajo como **Analista de Datos en la Sociedad Ecuatoriana de Estadística (SEE)**, donde convierto información dispersa en decisiones de portafolio, precio y operación. Me interesa el punto donde la estadística y la programación se encuentran: estructuras de datos, algoritmos sobre grafos, análisis numérico y visualización de resultados.

Los repositorios de abajo reúnen mi trabajo académico, organizado por materia y por nivel de complejidad. Cada uno tiene su propio README con el problema que resuelve, las estructuras y algoritmos aplicados, y las instrucciones para ejecutarlo.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat&logo=cplusplus&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![NetworkX](https://img.shields.io/badge/NetworkX-2C5BB4?style=flat)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)

---

## Trabajo profesional — Sociedad Ecuatoriana de Estadística

| Entregable | Qué resuelve |
| --- | --- |
| **Buscador de Carreras SEE × Pearson** ([en producción](https://see-ec.org/wp-content/uploads/CarrerasUniversitarias_SEE_Pearson.html)) | 1.808 programas académicos públicos de 90 instituciones, 467 carreras, 17 campos de conocimiento y 24 provincias, en una aplicación web de archivo único con filtros combinados, comparador de carreras y simulador de puntaje de admisión. Sin dependencias externas. |
| **Benchmarking del mercado ecuatoriano de formación en datos** | 95 cursos de la competencia perfilados en 8 áreas temáticas frente a 26 variables cada uno. El análisis de brechas resultante es el que la Dirección Ejecutiva usó para definir el portafolio de formación 2026. |

---

## Proyectos destacados

### [Sistema de delivery — Zamora Chinchipe](https://github.com/PaulGuerra07/sistema-delivery-zamora-chinchipe)

Proyecto integrador de Estructuras de Datos. Gestiona el inventario de paquetes de una empresa de delivery y calcula la ruta óptima de entrega sobre la red vial de los ocho cantones de la provincia.

Reúne casi todo el temario en un solo sistema: lista doblemente enlazada para el inventario, cola FIFO para los pedidos pendientes, grafo ponderado con Dijkstra para la ruta más corta (con el costo ajustado según el estado real de cada vía), flujo máximo por Edmonds-Karp para la capacidad de transporte, y búsqueda binaria sobre el inventario previamente ordenado. Incluye una comparación empírica entre Bubble Sort y Quick Sort, e indicadores de desempeño calculados con NumPy. Interfaz de escritorio en Tkinter con siete pestañas.

### [Árboles de búsqueda: recomendador musical y comparación BST / AVL / Rojo-Negro](https://github.com/PaulGuerra07/arbol-bst-recomendacion-musical)

Dos trabajos sobre árboles. El primero implementa un árbol binario de búsqueda para un motor de recomendación musical, construido con nodos y punteros propios, con recomendación por duración y poda recursiva.

El segundo compara BST, AVL y Rojo-Negro sobre el mismo conjunto de ocho transacciones bancarias. El resultado es medible: al insertar los IDs en orden ascendente —como hace cualquier contador autoincremental— el BST degeneró en una lista de ocho niveles y necesitó siete pasos para localizar una transacción, mientras que el AVL y el Rojo-Negro la encontraron en dos. En un motor antifraude esa diferencia decide si el pago se congela a tiempo.

### [Red de rutas aéreas EcoVuelo](https://github.com/PaulGuerra07/grafos-rutas-aereas-ecovuelo)

Grafo dirigido y ponderado sobre siete ciudades reales de la Costa ecuatoriana, con lista de adyacencia propia. Implementa las diez operaciones fundamentales sobre grafos —vértices, aristas ponderadas, adyacencia, grado de entrada y salida— más recorridos BFS con cola y DFS con pila, reutilizando el DFS para verificar si toda la red es alcanzable desde una ciudad dada.

---

## Estructuras de Datos

El recorrido completo del curso, de lo más básico a lo más complejo.

| # | Proyecto | Estructura | Caso de aplicación |
| --- | --- | --- | --- |
| 1 | [lista-compras-cpp-python](https://github.com/PaulGuerra07/lista-compras-cpp-python) | Estructura dinámica básica | El mismo problema resuelto en C++ y en Python para comparar ambos lenguajes |
| 2 | [limpieza-datos-regex-python](https://github.com/PaulGuerra07/limpieza-datos-regex-python) | Cadenas, registros y diccionarios | Normalización de un dataset de texto sucio con expresiones regulares |
| 3 | [listas-enlazadas-sistema-clinica](https://github.com/PaulGuerra07/listas-enlazadas-sistema-clinica) | Lista simple, doble y doble circular | Historial de atenciones, sala de espera y monitoreo de signos vitales |
| 4 | [pilas-colas-gestion-pedidos](https://github.com/PaulGuerra07/pilas-colas-gestion-pedidos) | Pila LIFO y cola FIFO | Pedidos y reclamos de una app de delivery en hora pico |
| 5 | [arbol-bst-recomendacion-musical](https://github.com/PaulGuerra07/arbol-bst-recomendacion-musical) | BST, AVL y Rojo-Negro | Recomendación musical y motor antifraude bancario |
| 6 | [grafos-rutas-aereas-ecovuelo](https://github.com/PaulGuerra07/grafos-rutas-aereas-ecovuelo) | Grafo dirigido y ponderado, BFS y DFS | Red aérea de la Costa ecuatoriana |
| 7 | [sistema-delivery-zamora-chinchipe](https://github.com/PaulGuerra07/sistema-delivery-zamora-chinchipe) | Proyecto integrador | Gestión de paquetes y optimización de rutas |

## Programación 2 — Python aplicado

| Proyecto | Tema |
| --- | --- |
| [poo-analizador-datos-python](https://github.com/PaulGuerra07/poo-analizador-datos-python) | Encapsulamiento: una clase que agrupa un conjunto de datos y sus operaciones estadísticas |
| [poo-herencia-polimorfismo-modelos-ia](https://github.com/PaulGuerra07/poo-herencia-polimorfismo-modelos-ia) | Herencia y polimorfismo sobre una jerarquía de modelos de aprendizaje automático |
| [numpy-analisis-consumo-energetico](https://github.com/PaulGuerra07/numpy-analisis-consumo-energetico) | Arreglos bidimensionales y agregaciones por eje con NumPy |

## Fundamentos de Programación — C++

| Proyecto | Tema |
| --- | --- |
| [operadores-ternarios-ejercicios-cpp](https://github.com/PaulGuerra07/operadores-ternarios-ejercicios-cpp) | Operadores ternarios, lógicos y relacionales |
| [estructuras-control-ejercicios-cpp](https://github.com/PaulGuerra07/estructuras-control-ejercicios-cpp) | Ciclos y selección múltiple |
| [funciones-sobrecarga-ejercicios-cpp](https://github.com/PaulGuerra07/funciones-sobrecarga-ejercicios-cpp) | Sobrecarga de funciones y paso por referencia |
| [registro-actividad-fisica-cpp](https://github.com/PaulGuerra07/registro-actividad-fisica-cpp) | Arreglos paralelos con media, mediana y moda |
| [recursividad-ejercicios-cpp](https://github.com/PaulGuerra07/recursividad-ejercicios-cpp) | Recursión y backtracking: permutaciones, Fibonacci, series de Taylor y criptoaritmética |
| [gestion-biblioteca-escolar-cpp](https://github.com/PaulGuerra07/gestion-biblioteca-escolar-cpp) | Matrices dinámicas, ordenamiento, búsqueda y reportes |
| [monitoreo-produccion-industrial-cpp](https://github.com/PaulGuerra07/monitoreo-produccion-industrial-cpp) | Análisis de producción, consumo energético y ausencias |
| [gestor-coleccion-musical-cpp](https://github.com/PaulGuerra07/gestor-coleccion-musical-cpp) | Proyecto final: estructuras, matrices de análisis y vectores |

## Cálculo

| Proyecto | Tema |
| --- | --- |
| [integracion-numerica-regla-trapecio](https://github.com/PaulGuerra07/integracion-numerica-regla-trapecio) | Estimación de distancia recorrida integrando la curva velocidad-tiempo |

---

## Certificaciones

| Certificación | Emisor | Detalle |
| --- | --- | --- |
| Business Intelligence con Power BI avanzado integrado con Python y R | Sociedad Ecuatoriana de Estadística | 20 horas · abril–mayo 2026 |
| Operador del Sistema Nacional de Contratación Pública (SNCP) | SERCOP | marzo 2026 · vigencia 2 años |
| Metodologías de Investigación con Inteligencia Artificial | Progressio América Latina | 120 horas · marzo 2026 |
| I Congreso Internacional de Ciberseguridad e Inteligencia Artificial (CIBERAI 2025) | ESPOCH | junio 2025 |
| Suficiencia en Inglés — Nivel B2 (MCER) | Centro de Idiomas, ESPOCH | 720 horas · febrero 2022 |
| Beca Santander \| Inglés Online — British Council | British Council | en curso |

---

## About

Data Science and Artificial Intelligence student at Universidad Nacional de Chimborazo and Data Analyst at the Ecuadorian Statistical Society (SEE), where I turn scattered information into decisions about portfolio, pricing and operations. The repositories here collect my academic work — data structures and algorithms in Python and C++, numerical analysis and applied statistics — organised by subject and complexity. Every repository documents the problem it solves, the structures and algorithms it applies, and how to run it. Repository documentation is written in Spanish; I am comfortable working in English.

## Contacto

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/paulguerravicuna)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:gpaul4342@gmail.com)
