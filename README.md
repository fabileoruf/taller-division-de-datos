# División de datos con Iris

Píldora de Fabiana Leonardo Rufino sobre entrenamiento, validación y prueba. El reto consiste en elegir una regresión logística para reconocer flores nuevas y explicar qué resultado permite confiar en ella.

## Práctica en parejas

[Abrir la práctica en Google Colab](https://colab.research.google.com/github/fabileoruf/taller-division-de-datos/blob/main/taller_iris.ipynb) · [Ver el cuaderno en GitHub](taller_iris.ipynb) · [Diapositivas en PDF](presentacion.pdf)

En Colab, ejecuta las celdas en orden y espera a la señal de la ponente antes de abrir la prueba final. Google Colab requiere conexión. Para trabajar en local, instala las dependencias antes de la sesión. La práctica usa el conjunto Iris incluido en scikit-learn.

Con Python 3.12 en macOS o Linux:

```sh
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
python -m jupyterlab taller_iris.ipynb
```

En Windows PowerShell, activa el entorno con `.venv\Scripts\Activate.ps1`.

1. Examina una fila de Iris y distingue las medidas de la etiqueta.
2. Divide las 150 flores en 90 de entrenamiento, 30 de validación y 30 de prueba. Comprueba los índices y las especies.
3. Compara dos valores de C usando solo la validación. Anota la elección antes de avanzar.
4. Evalúa el modelo elegido una vez en prueba. Expresa la nota como aciertos sobre el tamaño de la muestra.

## Taller de una hora

| Minutos | Trabajo en clase |
| --- | --- |
| 00–05 | Votación sobre un modelo que reconoce todas las flores con las que practicó. |
| 05–12 | Analogía del examen y presentación de Iris. |
| 12–32 | Práctica guiada y decisión por parejas. |
| 32–38 | Validación cruzada y discusión oral en inglés. |
| 38–57 | Detectives de datos. Cada equipo investiga, defiende y revisa un caso. |
| 57–60 | Respuesta individual, preguntas y cierre en inglés. |

La [ficha del equipo](detectives.pdf) incluye los tres casos. Se puede imprimir o proyectar. Cada equipo entrega una pista, una reparación y una comprobación.

## Fuentes

- Fotografía de Iris versicolor en la diapositiva 4: U.S. Fish and Wildlife Service, dominio público. [Ficha de la imagen](https://commons.wikimedia.org/wiki/File:Iris_versicolor_FWS.jpg)
- [Iris en scikit-learn](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_iris.html)
- [Validación y división de datos](https://scikit-learn.org/stable/modules/cross_validation.html)
- [Errores frecuentes y fugas de información](https://scikit-learn.org/stable/common_pitfalls.html)
