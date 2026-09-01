<div align="center">

# CodeLab

### Algoritmos, IA y Herramientas de Desarrollo

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

</div>

---

## Que es CodeLab

Repositorio personal de algoritmos de programacion, inteligencia artificial, scripts utiles y herramientas que creo o utilizo para agilizar el desarrollo. Funciona como guia de referencia y cuaderno de trabajo.

---

## Estructura

```
codelab/
├── algorithms/                         Algoritmos de Programacion
│   ├── sorting/                        Ordenamiento (bubble, merge, quick, heap...)
│   ├── searching/                      Busqueda (binary, bfs, dfs...)
│   ├── graph/                          Grafos (dijkstra, bellman-ford, kruskal...)
│   ├── dynamic-programming/            Programacion dinamica
│   ├── greedy/                         Algoritmos voraces
│   ├── divide-and-conquer/             Divide y venceras
│   └── backtracking/                   Retroceso
│
├── data-structures/                    Estructuras de Datos
│   ├── linear/                         Listas, colas, pilas
│   ├── trees/                          Arboles, BST, AVL, Heap
│   ├── graphs/                         Representacion de grafos
│   └── hashing/                        Tablas hash
│
├── machine-learning/                   Algoritmos de ML
│   ├── linear-models/                  Regresion lineal, logistic
│   ├── tree-based/                     Arboles de decision, Random Forest
│   ├── ensemble/                       XGBoost, LightGBM, Stacking
│   ├── clustering/                     K-means, DBSCAN, jerarquico
│   └── regression/                     Regresion polinomial, SVR
│
├── deep-learning/                      Redes Neuronales
│   ├── feedforward/                    Perceptron, MLP
│   ├── cnn/                            Convolucionales
│   ├── rnn-lstm/                       Recurrentes y LSTM
│   ├── transformers/                   Attention, BERT, GPT
│   ├── gan/                            Redes Generativas
│   └── autoencoders/                   Autoencoders, VAE
│
├── natural-language-processing/        Procesamiento de Lenguaje
│   ├── tokenization/                   Tokenizacion y normalizacion
│   ├── embeddings/                     Word2Vec, GloVe, FastText
│   ├── sentiment-analysis/            Analisis de sentimiento
│   ├── named-entity-recognition/       Reconocimiento de entidades
│   └── language-models/                Modelos de lenguaje
│
├── computer-vision/                    Vision por Computadora
│   ├── image-processing/               Filtros, operaciones morfologicas
│   ├── object-detection/               Deteccion de objetos
│   └── segmentation/                   Segmentacion semantica
│
├── optimization/                       Optimizacion
│   ├── gradient-descent/               Descenso de gradiente
│   ├── genetic-algorithms/             Algoritmos geneticos
│   └── convex/                         Optimizacion convexa
│
├── reinforcement-learning/             Aprendizaje por Refuerzo
│   ├── q-learning/                     Q-Learning, DQN
│   └── policy-gradient/               REINFORCE, PPO, A2C
│
├── tools/                              Herramientas y Scripts
│   ├── scripts/                        Scripts de uso diario
│   ├── automation/                     Automatizaciones
│   ├── dev-utils/                      Utilidades de desarrollo
│   ├── cli-tools/                      Herramientas de linea de comandos
│   └── productivity/                   Productividad
│
├── snippets/                           Snippets de Codigo
│   ├── python/                         Python
│   ├── javascript/                     JavaScript/TypeScript
│   ├── shell/                          Bash/Zsh
│   ├── dart/                           Dart/Flutter
│   └── sql/                            SQL
│
├── cheatsheets/                        Hojas de Referencia
│   ├── python/                         Python rapido
│   ├── math/                           Matematicas para ML
│   └── ml/                             Machine Learning
│
├── patterns/                           Patrones
│   ├── design/                         Patrones de diseno (GoF)
│   └── architectural/                  Arquitectura de software
│
└── projects/                           Proyectos de Ejemplo
    ├── beginner/                       Principiante
    ├── intermediate/                   Intermedio
    └── advanced/                       Avanzado
```

---

## Herramientas y Scripts

Lo que creo y utilizo para agilizar el desarrollo:

| Tipo | Contenido |
|------|-----------|
| **scripts/** | Scripts Python/Shell para tareas repetitivas |
| **automation/** | Automatizaciones de build, deploy, testing |
| **dev-utils/** | Utilidades: generadores, convertidores, validadores |
| **cli-tools/** | Comandos personalizados para la terminal |
| **productivity/** | Configuraciones, templates, atajos |

---

## Convenciones

- Cada algoritmo tiene: explicacion, complejidad temporal/espalacial, implementacion
- Scripts ejecutables tienen docstring con uso y permisos `chmod +x`
- Snippets incluyen ejemplo de uso
- Archivos `.md` documentan conceptos con formulas y diagramas
- Naming: `kebab-case` para carpetas, `snake_case` para archivos Python

---

## Uso

```bash
# Clonar
git clone https://github.com/jaquingv-dev/codelab.git
cd codelab

# Ejecutar un algoritmo
python algorithms/sorting/merge_sort.py

# Ejecutar un script util
chmod +x tools/scripts/my-tool.py
./tools/scripts/my-tool.py
```

---

## Dependencias Comunes

```txt
# ML/Data Science
numpy
pandas
scikit-learn
tensorflow
torch

# NLP
nltk
spacy
transformers

# Visualization
matplotlib
seaborn
plotly

# Utils
rich
click
tqdm
```

---

<div align="center">

Codigo, algoritmos y herramientas

</div>
