# 🥂 Regalo para Rachel — 4 Años de Fiesta de Bodas

Página sorpresa para el **15 de octubre**. Cuenta regresiva en vivo, pétalos,
línea de tiempo, **galería que rota sola**, tarjetas con razones y una carta
que se abre desde un sobre.

---

## ▶️ Cómo verla

Haz **doble clic** en `index.html`. Se abre en el navegador (Chrome, Edge, Firefox).

> ⚠️ Se ve mejor con **internet** (carga las tipografías de Google Fonts).
> Sin internet también funciona, solo con otras fuentes.

---

## ✏️ Qué personalizar (está todo marcado en el código)

Abre `index.html` con el Bloc de notas o VS Code y busca estos textos:

| Buscar | Qué cambia |
|---|---|
| `EDITA 1` | **Fecha y hora** de la cuenta regresiva (ya está en 15/oct/2026 19:00) |
| `EDITA 2` | Los 4 momentos de la **línea de tiempo** (pon tus fechas reales) |
| `EDITA 3` | Las **razones** de las tarjetas (son ejemplos, cámbialas por las tuyas) |
| `EDITA 4` | La **carta / dedicatoria** final |
| `EDITA 5` | El archivo de **música** |
| `EDITA 6` | La **galería**: velocidad de cambio y el pie de texto de cada foto |

También puedes cambiar los **nombres** buscando `Juan Carlos` y `Rachel`.

> Meses en la fecha: enero=0, febrero=1, … **octubre=9**.

---

## 📸 Las fotos (rotan solas, sin clic)

1. Copia tus imágenes a la carpeta **`fotos/`**
2. Renómbralas exactamente: `1.jpg`, `2.jpg`, `3.jpg`, `4.jpg`, `5.jpg`, `6.jpg`
3. Listo. **No hay que tocar el código.**

**Cómo se muestran:** cada tarjeta cambia sola cada pocos segundos
(`1 → 2 → 3 → 4 → 5 → 6 → 1 …`) con un fundido suave y efecto ola entre ellas.
Abajo de cada foto aparece su pie de texto y el número (`3 / 6`).

- **⏸** (botón de la esquina) → pausa la rotación para quedarse mirando una foto
- **▶** → la vuelve a poner en marcha
- Si falta alguna foto, esa tarjeta muestra el cartón elegante en su lugar

---

## 🎵 Cómo poner la canción de ustedes

1. Pon tu archivo de audio en la misma carpeta del regalo
2. Renómbralo a **`musica.mp3`**
3. El botón ♪ de arriba a la derecha la activa
   (los navegadores no dejan que suene sola, debe darle click)

---

## 📱 Regalarla

- **Celular:** abrirla en el cel y dejarlo listo, o envíala por WhatsApp
  (si subes la carpeta a un servicio tipo Netlify Drop / GitHub Pages, te queda
  un **link** que puedes enviarle y se abre desde cualquier lugar).
- **Sorpresa extra:** presiona `F11` para pantalla completa y proyéctala.
- **La cuenta regresiva llega a cero el 15 de octubre** y sale confeti 🎉

---

## 📁 Estructura

```
regalo-rachel/
├── index.html      ← la página (el regalo)
├── README.md       ← estas instrucciones
└── fotos/          ← aquí van sus fotos (1.jpg … 6.jpg)
```
