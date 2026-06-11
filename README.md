# Deep Learning

## Departamento de Ciencias de la Computación — Universidad de Chile

Repositorio del curso de Deep Learning del DCC - Uchile.

Esta es la versión **rediseñada** del curso: **8 clases de 3 horas**, organizadas en **4 módulos**. Cada módulo tiene una **clase de teoría** (apunte en Colab en vivo, con conceptos y demos) y una **clase práctica** (laboratorio guiado con ejercicios y soluciones). Todo en PyTorch.

> **Cómo abrir los notebooks:** haz clic en el badge ![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg). El notebook se abre en modo lectura/playground; para guardar tus cambios usa *Archivo → Guardar una copia en Drive*. Para las clases prácticas de los módulos 2 a 4 conviene activar GPU en *Entorno de ejecución → Cambiar tipo de entorno → GPU*.
>
> **Leyenda:** ✅ disponible · 🚧 en construcción. Los badges 🚧 quedarán activos cuando se suba el notebook correspondiente a la rama `main`.

---

## Estructura del curso

### Módulo 1 — Fundamentos ✅ 

Del perceptrón a los Transformers: MLP, funciones de pérdida, gradiente descendente, backpropagation, optimización y regularización.

- **Clase 1 · Teoría** — Del perceptrón a los Transformers
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ivansipiran/Deep-Learning/blob/main/M1_Clase1_Teoria_Fundamentos.ipynb)
    - Infografías 🖼️: [Datos en IA](infografias/M1/01_Representación_Vectorial_en_IA.png), [El perceptrón](infografias/M1/02_El_Perceptron_Atomo_de_la_IA.png), [Perceptrón Multicapa](infografias/M1/03_Perceptrón_Multicapa.png), [Funciones de Loss](infografias/M1/04_Funciones_de_Perdida.png), [Descenso de Gradiente](infografias/M1/05_Descenso_de_Gradiente.png), [Backpropagation](infografias/M1/06_Backpropagation_en_Aprendizaje_Profundo.png), [Generalización en Redes Neuronales](infografias/M1/07_Generalizacion_en_redes_neuronales.png)
- **Clase 2 · Práctica** — Construyendo redes desde cero en PyTorch
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ivansipiran/Deep-Learning/blob/main/M1_Clase2_Practica_Fundamentos.ipynb)

### Módulo 2 — Visión computacional 🚧

Convolución, redes convolucionales, arquitecturas (LeNet → ResNet), transfer learning y Vision Transformers.

- **Clase 3 · Teoría** — De las CNN a los Vision Transformers
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ivansipiran/Deep-Learning/blob/main/M2_Clase3_Teoria_Vision.ipynb)
- **Clase 4 · Práctica** — CNN, data augmentation y transfer learning
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ivansipiran/Deep-Learning/blob/main/M2_Clase4_Practica_Vision.ipynb)

### Módulo 3 — Procesamiento de Lenguaje Natural 🚧

Representación de texto y embeddings, RNN/LSTM, seq2seq y atención, Transformers y LLMs.

- **Clase 5 · Teoría** — De las RNN a los LLMs
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ivansipiran/Deep-Learning/blob/main/M3_Clase5_Teoria_NLP.ipynb)
- **Clase 6 · Práctica** — Clasificación con RNN, fine-tuning de BERT y uso de un LLM
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ivansipiran/Deep-Learning/blob/main/M3_Clase6_Practica_NLP.ipynb)

### Módulo 4 — Temas avanzados 🚧

Modelos generativos (VAE, GAN, difusión), modelos multimodales (CLIP, BLIP) y agentes.

- **Clase 7 · Teoría** — Generative AI, multimodal y agentes
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ivansipiran/Deep-Learning/blob/main/M4_Clase7_Teoria_Avanzado.ipynb)
- **Clase 8 · Práctica** — CLIP, generación con difusión y un agente simple
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ivansipiran/Deep-Learning/blob/main/M4_Clase8_Practica_Avanzado.ipynb)

---

## Material complementario (curso extendido)

El repositorio conserva el material del curso semestral completo, útil como referencia y profundización:

- **Slides** por tema en la carpeta [`Slides/`](https://github.com/ivansipiran/CC6204-Deep-Learning/tree/main/Slides) (perceptrón, backpropagation, optimización, CNN, arquitecturas, transfer learning, modelos de secuencias, NMT + atención, Transformers, modelos generativos).
- **Laboratorios** adicionales en la carpeta [`Labs/`](https://github.com/ivansipiran/CC6204-Deep-Learning/tree/main/Labs) (clasificación binaria, MNIST multiclase, convolución, arquitecturas CNN, detección de objetos con YOLO y SSD, RNN, NMT con atención, ViT, BERT, autoencoders, VAE, GAN).

## Recursos

- *Deep Learning*, Goodfellow, Bengio, Courville — https://www.deeplearningbook.org/
- *Neural Networks and Deep Learning*, Nielsen — http://neuralnetworksanddeeplearning.com/
- *Dive into Deep Learning* — https://d2l.ai/
