# Intercambio Navideño (GitHub Pages)

Sitio estático listo para publicar en **GitHub Pages**.

## Estructura
- `index.html` — App React (via CDN) + Tailwind, con lista precargada.
- `README.txt` — Este archivo.

## Publicar en GitHub Pages (paso a paso)
1. Crea un repositorio nuevo en GitHub, por ejemplo: `intercambio-nombres`.
2. Sube los archivos contenidos en esta carpeta (`index.html` y `README.txt`) a la rama `main`.
3. Entra a **Settings → Pages**.
4. En **Build and deployment**, elige:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` / `/root`
5. Guarda. GitHub generará una URL pública en pocos minutos, algo como:
   `https://TU-USUARIO.github.io/intercambio-nombres/`

## Uso
- Al abrir la página verás la lista de nombres ya precargada.
- En **Admin**: presiona **“Generar sorteo”** para crear las asignaciones sin repeticiones.
- Comparte el **ID del evento** si quieres separar múltiples sorteos en el mismo navegador.
- En **Participante**: escribe tu nombre exactamente como aparece y verás a quién te tocó.

> Todo se guarda en el navegador (localStorage) por **ID de evento**. Si cambias el ID con “nuevo”, se inicia un sorteo independiente.
