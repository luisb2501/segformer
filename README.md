# 🎨 Segmentador de Prendas de Ropa con SegFormer

![Python](https://img.shields.io/badge/Python-3.7%2B-blue)
![Gradio](https://img.shields.io/badge/Gradio-3.0%2B-orange)
![HuggingFace](https://img.shields.io/badge/🤗%20Transformers-4.0%2B-yellow)

Este proyecto implementa una interfaz interactiva para segmentar prendas de ropa en imágenes utilizando el modelo SegFormer de HuggingFace y Gradio.

## 🚀 Características

- Segmentación de 18 categorías diferentes de prendas y partes del cuerpo
- Interfaz web interactiva para cargar y procesar imágenes
- Visualización de resultados con superposición de colores y leyenda
- Modelo pre-entrenado de alta precisión

## 🛠️ Tecnologías Utilizadas

- [Python](https://www.python.org/)
- [Gradio](https://www.gradio.app/)
- [HuggingFace Transformers](https://huggingface.co/transformers/)
- [PyTorch](https://pytorch.org/)
- [Matplotlib](https://matplotlib.org/)
- [NumPy](https://numpy.org/)
- [Pillow](https://python-pillow.org/)

## 📋 Categorías de Segmentación

| ID | Categoría | Color |
|----|-----------|-------|
| 0 | Fondo | Negro |
| 1 | Sombrero | Rojo |
| 2 | Cabello | Verde |
| 3 | Gafas de sol | Azul |
| 4 | Ropa superior | Amarillo |
| 5 | Falda | Magenta |
| 6 | Pantalones | Cian |
| 7 | Vestido | Gris claro |
| 8 | Cinturón | Marrón |
| 9 | Zapato izquierdo | Oliva |
| 10 | Zapato derecho | Verde oscuro |
| 11 | Cara | Púrpura |
| 12 | Pierna izquierda | Turquesa |
| 13 | Pierna derecha | Azul marino |
| 14 | Brazo izquierdo | Naranja |
| 15 | Brazo derecho | Rosa |
| 16 | Bolso | Índigo |
| 17 | Bufanda | Verde primavera |

## 🚀 Cómo usar

1. Clona este repositorio
2. Instala las dependencias: `pip install -r requirements.txt`
3. Ejecuta el script: `python segmentador_ropa.py`
4. Abre la interfaz web generada por Gradio
5. Sube una imagen y observa los resultados de la segmentación


## 🤝 Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un issue para discutir cambios importantes antes de crear un pull request.

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.

---

Desarrollado por Luis Bermeo
