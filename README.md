# 🌹 Kit de Oración · Día de las Madres

Landing page espiritual para el Santo Rosario, diseñada para acompañar el Kit físico de oración.

---

## 🚀 Despliegue en Vercel (recomendado, gratis)

### Opción A — Arrastra y suelta (más fácil)
1. Ve a [vercel.com](https://vercel.com) y crea una cuenta gratuita.
2. En el dashboard, haz clic en **"Add New → Project"**.
3. Elige **"Upload folder"** o arrastra la carpeta `kit-oracion-madres/`.
4. Vercel detecta que es HTML estático → clic en **Deploy**.
5. En minutos tendrás una URL tipo `kit-oracion-madres.vercel.app`.
6. ¡Listo! Esa URL es la que va en tu código QR.

### Opción B — GitHub + Vercel (mejor para actualizaciones)
1. Sube la carpeta a un repositorio en GitHub.
2. En Vercel, conecta el repositorio.
3. Cada vez que actualices el repo, Vercel despliega automáticamente.

---

## 🔗 Alternativas gratuitas

| Servicio | Cómo |
|---|---|
| **Netlify** | Arrastra la carpeta en netlify.com/drop |
| **GitHub Pages** | Habilita Pages en el repo |
| **Tiiny.host** | Sube el index.html directo, URL al instante |

---

## 📱 Generar el Código QR

Una vez tengas la URL de Vercel:

1. Ve a [qr-code-generator.com](https://www.qr-code-generator.com) o [qrcode-monkey.com](https://www.qrcode-monkey.com)
2. Pega tu URL (ej: `https://kit-oracion-madres.vercel.app`)
3. Personaliza: usa colores dorado/rosado para que combine con el kit
4. Descarga en alta resolución (SVG o PNG 1000px+)
5. Incluye el QR en el diseño físico del kit

---

## ✏️ Cómo personalizar el contenido

Todo el contenido editable está en el archivo `index.html`, en la sección `<script>`, en los objetos:

```js
// Textos de las oraciones
const PRAYERS = { ... }

// Los 4 tipos de misterios
const MYSTERIES = { ... }

// Qué misterios van cada día
const DAY_MYSTERIES = { ... }

// Preguntas frecuentes
const FAQS = [ ... ]
```

---

## 💎 Ideas para hacerlo más premium (sin complicarlo)

- **Dominio propio**: Compra `kitdeoracion.com` (~$12/año) y conéctalo a Vercel
- **Audio**: Agrega un botón para reproducir música instrumental de fondo (usa una canción libre de derechos del Ave María)
- **PWA**: Añade un `manifest.json` para que se pueda instalar como app en el celular
- **Analítica**: Conecta Google Analytics o Vercel Analytics para ver cuántas personas usan el kit
- **Multilenguaje**: Agrega versión en inglés para familias bilingües
- **Modo nocturno**: Añade un toggle para usar con luz baja durante la oración

---

## 🎁 Sugerencia para el kit físico

El kit ideal incluye:
- 📸 Imagen impresa de la Virgen María (5×7 cm o tarjeta)
- 📿 Opcional: un pequeño rosario
- 🔲 Código QR impreso en la parte trasera o en una tarjetita
- 💌 Sobre con mensaje de dedicatoria

---

*Hecho con amor y fe 🌹 · Ad Majorem Dei Gloriam*