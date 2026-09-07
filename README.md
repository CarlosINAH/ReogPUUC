# RE-ORG PUUC — Sección 4

Herramienta interactiva para ayudar al **Museo Arqueológico del Puuc** (Zona Arqueológica de **Kabah**, Yucatán) a **colocar mejor sus deshumidificadores y dataloggers**, aplicando el método **RE-ORG** (ICCROM · UNESCO · CCI) del **INAH**.

Es un **solo archivo HTML**, funciona **sin conexión** (doble clic) y también puede publicarse en la web.

## Qué hace

Sobre el plano real del museo (las **5 salas** alrededor del Patio Central con la Casa Maya), se trabaja **sala por sala** para encontrar la posición correcta del equipo:

- **A escala** — cada sala se dibuja con su medida en metros, con barra de escala.
- **Deshumidificador Hisense DH50K1R** (23.7 L/día, 460 W, R32) — cobertura de diseño ≈ 60 m²/equipo. El juego calcula cuántos hacen falta y el % de área cubierta.
- **Datalogger HTC-2** (T°/HR) — regla de colocación: donde represente a la colección, lejos de puertas/ventanas y del propio deshumidificador.
- **Clima real** — 40 °C con sensación térmica (índice de calor) según la humedad; meta de conservación ≈ 50 % HR.
- **Cerrar puertas y ventanas** para que el control de humedad funcione.
- Avance guardado por navegador (localStorage): las salas terminadas quedan ✓.

## Salas

| Sala | Medida aprox. | Área |
|---|---|---|
| Norte | 12.5 × 12.5 m | 156 m² |
| Sur | 11.5 × 8 m | 92 m² |
| Oriente | 6 × 29.5 m | 177 m² |
| Poniente | 6 × 25 m | 150 m² |
| Temporal | 6 × 25 m | 150 m² |

> **Nota sobre la escala:** el plano oficial trae cotas en metros y área total **978.3 m²**, pero la casilla de escala no viene rotulada, así que las medidas por sala son **aproximadas** (derivadas de las proporciones del plano). Son editables en el bloque `SALAS` del código; al cambiarlas, el juego se redibuja a escala automáticamente.

## Cómo usarlo

1. Descarga el repositorio (o solo `index.html`).
2. Abre **`index.html`** con doble clic en Chrome o Edge.
3. Elige una sala en el plano, coloca deshumidificadores 💨 y dataloggers 🌡️, cierra puertas/ventanas 🔒 y pulsa **Evaluar colocación**.

## Ver en línea (GitHub Pages)

En **Settings → Pages**, selecciona la rama `main` y carpeta `/ (root)`. Quedará disponible en:
`https://carlosinah.github.io/reogpuuc/`

---
INAH · Museo Arqueológico del Puuc (Kabah) · Método RE-ORG (ICCROM · UNESCO · CCI)
