# Guía de Derechos — Pasajeros Vuelo VB 6019 (AIFA → Mérida)

Sitio estático ultrarrápido (cero compilación, un solo `index.html`) para ayudar a los pasajeros afectados en Puerta 104 a ejercer sus derechos conforme al **Artículo 47 Bis de la Ley de Aviación Civil** y la **Ley Federal de Protección al Consumidor**.

## Cómo publicarlo en GitHub + Vercel en 1 minuto

El repositorio Git local ya está inicializado con su primer commit en la rama `main`.

### Paso 1: Subir a GitHub
1. Crea un repositorio nuevo y vacío en [github.com/new](https://github.com/new) (por ejemplo `vuelo6019`, sin marcar *Add a README*).
2. Copia la URL de tu repo y ejecuta en esta carpeta:

```powershell
git remote add origin https://github.com/TU_USUARIO/vuelo6019.git
git push -u origin main
```

### Paso 2: Publicar en Vercel
1. Entra a [vercel.com/new](https://vercel.com/new) con tu cuenta de GitHub.
2. Haz clic en **Import** junto al repositorio `vuelo6019`.
3. No cambies nada (Vercel detecta automáticamente que es estático gracias a `index.html` y `vercel.json`) y haz clic en **Deploy**.
4. En ~10 segundos tendrás tu URL pública (ej. `https://vuelo6019.vercel.app`) y el **Código QR de la página apuntará automáticamente a esa URL**.

---

### Alternativa Exprés (Sin pasar por GitHub, directo desde terminal)
Si quieres publicarlo en 20 segundos directo a Vercel desde PowerShell:

```powershell
npx vercel --prod
```
