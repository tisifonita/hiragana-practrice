# ひらがな · Ficha de práctica

Web estática para practicar hiragana con una ficha de casillas dobles. En cada pareja aparece hiragana o romaji, y la otra mitad queda vacía para escribir con el Apple Pencil o con el dedo.

## Publicar gratis con GitHub Pages

1. Entra en https://github.com e inicia sesión (o crea una cuenta).
2. Pulsa **New repository**. Ponle, por ejemplo, `hiragana-practice` y marca **Public**.
3. Sube el archivo `index.html` de esta carpeta al repositorio (Add file → Upload files → Commit changes).
4. Ve a **Settings → Pages**.
5. En **Build and deployment**, selecciona **Deploy from a branch**; rama `main` y carpeta `/(root)`. Pulsa **Save**.
6. Espera un poco y GitHub te dará una URL con formato `https://tu-usuario.github.io/hiragana-practice/`.

Abre esa URL en Safari en el iPad. La ficha funciona sin servidor ni base de datos.

## Notas
- La escritura se dibuja en el navegador; no se reconoce automáticamente como texto.
- Usa **Nueva ficha aleatoria** para barajar las sílabas y cambiar qué mitad aparece como pista.
- **Ver respuesta** muestra la solución de una pareja; **Mostrar respuestas** las muestra todas.
- **Imprimir / guardar PDF** abre la opción de impresión del navegador.
- Esta versión incluye hiragana básico, dakuten/handakuten y combinaciones pequeñas. La romanización se mantiene consistente para el ejercicio; algunas sílabas raras como ぢ/づ y sus combinaciones tienen más de una romanización posible.
