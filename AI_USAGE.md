
**Herramienta usada:** Claude (Anthropic).

## Qué usé de la IA

- **A.1 (carga de FastText) y B.1 (`vector_documento`):** le pedí ayuda para
  acordarme de los métodos exactos de la librería `fasttext`
  (`get_word_vector`, `get_dimension`, `get_words`). Yo ya sabía la lógica
  (promediar vectores, validar caso vacío), pero no recordaba los nombres
  exactos de las funciones.

- **A.2 / A.4 (vecinos y analogías):** la sintaxis de `get_nearest_neighbors`
  y `get_analogies` la saqué con ayuda de la IA porque no la había usado
  antes. Los comentarios de interpretación (por qué falla la analogía
  país-capital) los reescribí con mis palabras después de correr el código
  y ver el resultado real.

- **B.2 (`buscar_semantico`):** pegué mi `preprocesar()` del Lab 3, 
  la IA solo ayudó a armar el ranking ordenando por coseno, que es análogo
  a lo que ya tenía en `buscar_tfidf`.

## Qué hice yo sin ayuda

- A.3 (`cos_vec`) la escribí ya que es la fórmula de coseno que ya
  había usado en labs anteriores.
- B.3 y B.4 (comparación de los tres sistemas y re-evaluación con nDCG) los
  armé yo reusando `evaluar_sistema` del Lab 3 tal cual estaba, solo le
  agregué la función `buscar_semantico` a la comparación.
- Las respuestas escritas a las preguntas las redacté yo después
  de ver las salidas.

