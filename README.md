# 🎂 Fábrica de Pasteles Sanrio para Diana

¡Órale! ¡Bienvenido a la Fábrica de Pasteles Sanrio! Un juego padrísimo donde podrás hornear pasteles deliciosos para tus personajes favoritos de Sanrio.

## 🌟 ¿De qué se trata?

Es un juego súper divertido donde los personajes de Sanrio (Hello Kitty, Pochacco, My Melody, y muchos más) vienen a tu pastelería a pedir sus pasteles favoritos. ¡Tu chamba es prepararles exactamente lo que quieren!

## 🎮 ¿Cómo se juega?

1. **Lee el pedido**: Cada personaje te dirá qué tipo de pastel quiere. ¡Ponle atención a la notita amarilla!
2. **Elige los ingredientes**:
   - **Base**: Vainilla, Chocolate, Fresa o Red Velvet
   - **Crema**: Blanca, Rosa, Café o Azul
   - **Decoración**: Frutillas, Estrellas, Corazones o Chispas
   - **Extra**: Velita, Macarrón, Galleta o Cereza
3. **Hornea y entrega**: Dale al botón "Hornear y entregar pastel 🎂"
4. **¡Gana estrellas!**: Entre más aciertes, más estrellas ⭐ ganarás

## 🎯 Características bien chidas

- **Personajes Sanrio**: ¡Conoce a Hello Kitty, Pochacco, My Melody, Keroppi, Cinnamoroll, Tuxedo Sam, Badtz-Maru, Pekkle, Pompompurin y hasta Zan!
- **Temáticas cambiantes**: Conforme avances, desbloquearás nuevas temáticas:
  - Clásico Sanrio (café)
  - Sanrio Acuático (azul)
  - Sanrio Dulce (rosa)
- **Animaciones padrísimas**: Los personajes se mueven y bailan mientras esperan
- **Música y sonidos**:
  - Música de fondo relajante que cambia entre 4 pistas
  - Efectos de sonido de máquina de escribir al aparecer los pedidos
  - Botón de silencio 🔊/🔇 por si quieres jugar sin sonido
- **Guarda tu progreso**: El juego guarda automáticamente tus puntos y pedidos completados

## 🚀 ¿Cómo echarlo a andar?

### Opción 1: Abrirlo directo

Nomás abre el archivo `index.html` en tu navegador favorito (Chrome, Firefox, Safari, etc.)

### Opción 2: Con un servidor local

Si quieres que jale mejor el audio:

```bash
# Con Python 3
python -m http.server 8000

# O con Node.js
npx http-server
```

Luego abre `http://localhost:8000` en tu navegador.

## 📁 Estructura del proyecto

```
UpdateFabrica/
├── index.html         # El mero mero juego
├── README.md          # Este archivo que estás leyendo
└── sound/             # Carpeta con los sonidos
    ├── fabrica-de-pasteles-01.ogg
    ├── fabrica-de-pasteles-02.ogg
    ├── fabrica-de-pasteles-03.ogg
    ├── fabrica-de-pasteles-04.ogg
    ├── key.ogg        # Sonido de tecla
    └── space.ogg      # Sonido de espacio
```

## 🎨 Tecnologías usadas

- **HTML5 Canvas**: Para dibujar todos los gráficos del juego
- **JavaScript vanilla**: ¡Sin frameworks, puro código limpio!
- **LocalStorage**: Para guardar tu progreso
- **Audio API**: Para la música y efectos de sonido

## 💡 Tips para jugar mejor

- Fíjate bien en la nota amarilla del pedido - ahí está toda la información
- Los personajes tienen animaciones de espera diferentes, ¡obsérvalos!
- Cada 50 puntos cambias de temática
- Si te equivocas no pasa nada, ¡sigue intentando!

## 🤝 Créditos

Este juego fue hecho con mucho cariño para Diana. ¡Esperamos que te diviertas un montón preparando pasteles para tus amigos de Sanrio!

## 📝 Notas

- El juego funciona mejor en navegadores modernos
- Es responsivo, así que también puedes jugarlo en tu celular o tablet
- Los sonidos pueden no reproducirse automáticamente en algunos navegadores por restricciones de seguridad

¡Ándale pues! ¡A hornear se ha dicho! 🎂✨
