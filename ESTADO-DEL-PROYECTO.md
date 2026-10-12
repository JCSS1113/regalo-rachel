# 📌 Estado del proyecto — Regalo para Rachel

> Nota de seguimiento. Si la sesión de trabajo se pierde, con este archivo
> sabes exactamente en qué vamos y qué falta.

**Última actualización:** 12 de octubre de 2026

---

## ✅ Datos confirmados (por Juan Carlos)

| Dato | Valor |
|---|---|
| Quién | **Juan Carlos** & **Rachel** |
| Qué celebramos | **Fiesta de bodas** (NO el día de boda oficial) |
| Fecha | **15 de octubre** de 2026, 19:00 (hora de la cuenta regresiva) |
| Años | **4** |
| Regalo elegido | Página web sorpresa |

---

## ✅ Lo que ya está terminado

- [x] Carpeta del proyecto: `Desktop\opencode\regalo-rachel\`
- [x] Página `index.html` completa (autocontenida, un solo archivo)
- [x] Preloader con corazón latiendo
- [x] Portada: nombres, "4 años", pétalos cayendo animados en canvas
- [x] **Cuenta regresiva en vivo** al 15/oct/2026 → al llegar a cero sale **confeti**
- [x] Línea de tiempo de 4 momentos
- [x] **Galería con rotación automática** (sin clic):
      cada tarjeta cambia sola `1 → 2 → 3 → 4 → 5 → 6 → 1`,
      fundido cruzado + zoom lento (Ken Burns) + efecto ola entre tarjetas,
      pie de foto con texto y número (`3 / 6`)
- [x] Botón **⏸ / ▶** para pausar o reanudar la rotación
- [x] **8 tarjetas "Razones por las que te amo"** — ✅ *aprobadas por Juan Carlos*
- [x] Sobre con lacre que se abre → muestra la **carta** — ✅ *texto aprobado, no tocar*
- [x] Frase final: **"Feliz fiesta de bodas, Princesita"**
      (con "Princesita" en mayúscula, a pedido de Juan Carlos)
- [x] **🎵 MÚSICA PUESTA:** `musica.mp3` (7.8 MB, MP3 válido) ya está en la
      carpeta. Es *"Flowers"* de FSCM Productions — **libre de derechos
      (CC BY 4.0)**, descargada de free-stock-music.com. El crédito obligatorio
      está en el pie de página.
- [x] **La música arranca SOLA con el primer toque/clic** de ella en la
      pantalla (los navegadores no permiten autoplay). Botón ♪ = pausar/reanudar.
- [x] **🔒 VISTA BLOQUEADA:** hasta el 15/oct **solo se ve la cuenta regresiva**
      (no se puede deslizar). Al llegar a cero se desbloquea sola, sale confeti
      y aparece la indicación "Desliza tu sorpresa".
      → Para **VER la página completa antes de tiempo**: agregar `?vista=todo`
      al final del link (`index.html?vista=todo`).
- [x] **🎵 Música: Ed Sheeran — "Perfect"** (video **oficial** del canal de
      Ed Sheeran, ID `2Vv-BfVoq4g`) suena de fondo con el primer toque.
      Marcado como **`EDITA 7`** para cambiar de canción.
      *No se descargó el MP3: es una canción con derechos de autor. Se usa el
      reproductor oficial de YouTube, que es legal. Si no hay internet, cae
      automáticamente a `musica.mp3` ("Flowers", CC BY 4.0).*
- [x] **Recuadro de la cuenta regresiva subido** (menos pegado al final):
      `.hero` pasó de `70px` a `150px` de margen inferior (y `124px` en móvil).
- [x] **Repo Git inicializado** en la carpeta (`git init -b main`), user.name y
      user.name configurados, listo para el primer commit.
- [x] Diseño responsive (celular y PC) + respeta "reducir movimiento"
- [x] **Las 6 fotos ya están puestas** y verificadas: `fotos/1.jpg` … `6.jpg`
      (1536×2048, 2048×1536, 640×960, 1367×2048, 1756×2048, 2048×1367)
- [x] Código validado: JS sin errores, etiquetas balanceadas

---

## ⬜ Lo que FALTA (pendientes)

1. **🌐 Publicarla en GitHub Pages (Opción A).** Repo local ya creado.
   **Falta UN paso que solo Juan Carlos puede hacer** porque usa su cuenta:
   abrir una terminal en la carpeta y ejecutar `gh auth login`
   (→ elige *GitHub.com* → *HTTPS* → *Login with a web browser* → copia el
   código y lo pega en el navegador). Una vez autenticado, se termina todo
   desde acá: crear el repo, subir, activar Pages y dar el link.
   - ⚠️ **AVISO DE PRIVACIDAD:** las fotos, los nombres y la carta quedarían
     en internet. Si el repo es **público**, cualquiera con el link las ve.
2. *(Opcional)* Revisar/editar los hitos de la **línea de tiempo** (`EDITA 2`).
3. *(Opcional)* Cambiar la canción de fondo → `EDITA 7` (ID de YouTube).

> ✅ **APROBADO y NO TOCAR:** la **carta** (`EDITA 4`), las **8 razones** (`EDITA 3`)
> y la frase final *"Feliz fiesta de bodas, princesita"* — Juan Carlos los dio por buenos.

---

## 🗺️ Cómo retomar el trabajo

Abre `index.html` y busca en el código los marcadores `EDITA 1` … `EDITA 6`.

| Marcador | Qué controla |
|---|---|
| `EDITA 1` | Fecha/hora de la cuenta regresiva (año, mes 0-11, día, hora) — *octubre = 9* |
| `EDITA 2` | Los 4 hitos de la línea de tiempo |
| `EDITA 3` | Las 8 razones |
| `EDITA 4` | La carta final |
| `EDITA 5` | Archivo de música |
| `EDITA 6` | Galería: `CICLO` (ms por foto, va en 4200), `ONDA` (ms de retardo, 170) y los textos del pie |

---

## 🎨 Estilo actual (por si hay que cambiarlo)

- Elegante romántico: fondo **vino/burdeos** con **dorado**, tipografía
  *Cormorant Garamond* + *Great Vibes* (manuscrita) + *Montserrat*.
- Alternativas ofrecidas y pendientes de elegir si no gusta:
  flores y pasteles 🌸 · scrapbook polaroid 📷 · minimalista ✨

## 💡 Ideas pendientes (no pedidas aún)

- Agregar la **fecha oficial de la boda** como dato aparte junto a la de la fiesta.
- Subir la página a internet (Netlify Drop / GitHub Pages) para enviarla por link.
