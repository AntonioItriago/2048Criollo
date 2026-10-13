# 2048Criollo
2048 Criollo 🫓🇻🇪 | Un divertido juego estilo 2048 adaptado como Telegram Mini App con la gastronomía venezolana (arepas, cachapas, patacones). Desarrollado en HTML5/JS con respuesta háptica y monetización mediante anuncios (banners y rewarded ads para deshacer movimientos). ¡Fusiona y llega al Gran Banquete!
# 🫓 2048 Criollo — Telegram Mini App 🇻🇪

![2048 Criollo Banner](watermarked_img_12040922423444946440.jpg)

**2048 Criollo** es una divertida adaptación cultural y gastronómica del clásico juego de rompecabezas numérico 2048, desarrollada específicamente para ejecutarse como una **Telegram Mini App**. 

En lugar de números abstractos, los jugadores deslizan y fusionan platos y elementos emblemáticos de la cocina venezolana —desde la masa de harina de maíz hasta el Gran Banquete Criollo— mientras compiten por alcanzar la máxima puntuación.

---

## 🎮 Mecánica de Juego

* **Tablero:** Grilla interactiva de $4 \times 4$.
* **Controles:** Gestos táctiles (*swipes*) optimizados para dispositivos móviles y navegación con teclado para escritorio.
* **Sistema de Evolución:** Dos fichas idénticas al colisionar se combinan para formar el siguiente nivel gastronómico:

| Nivel | Ficha / Platillo |
| :---: | :--- |
| **2** | Masa de Harina Pan |
| **4** | Arepa Viuda |
| **8** | Arepa Queso Blanco |
| **16** | Arepa Pelúa |
| **32** | Arepa Reina Pepiada |
| **64** | Cachapa con Queso de Mano |
| **128** | Empanada Pabellón |
| **256** | Patacón Zuliano |
| **512** | Pabellón Criollo |
| **1024** | Sancocho de Gallina |
| **2048** | **¡El Gran Banquete Criollo!** 🏆 |

---

## 💡 Características Principales

* 📱 **Experiencia Mobile-First:** Diseñada para ofrecer fluidez y tiempos de respuesta mínimos dentro del cliente de Telegram.
* 📳 **Respuesta Háptica (Haptic Feedback):** Vibración sutil integrada al realizar fusiones e interacciones clave mediante `@telegram-apps/sdk`.
* 💾 **Persistencia Local:** Guardado automático del estado de la partida y de la máxima puntuación local (`localStorage`).
* 🎨 **Interfaz Atractiva:** Paleta de colores vibrante, sombras suaves y estética plana moderna con toques 3D.

---

## 💰 Estrategia de Monetización

* **Banner Ads (Impresiones Continuas):**
  * Ubicado en la parte superior/inferior fuera de la grilla jugable para no interrumpir la experiencia de juego.
* **Rewarded Video Ads ("Deshacer Movimiento / Undo"):**
  * Si el jugador comete un error o queda sin movimientos válidos, puede visualizar un video publicitario para revertir el tablero al turno anterior.

---

## 🛠️ Tecnologías Utilizadas

* **Frontend:** HTML5, CSS3, JavaScript (ES6+) / React / Vite.
* **Telegram Integration:** Telegram WebApp SDK (`https://telegram.org/js/telegram-web-app.js`).
* **Monetización:** Redes de anuncios compatibles con Telegram Mini Apps (Adsgram, Monetag, etc.).
* **Deployment:** Alojado en infraestructura HTTPS (Vercel / Netlify / Render).
