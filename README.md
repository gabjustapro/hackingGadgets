# 🛠️ Arsenal Físico de Hacking Ético

Este proyecto es una **página web interactiva** que presenta una colección curada de herramientas físicas utilizadas por profesionales del **hacking ético** y la **seguridad informática**. La idea principal es documentar, categorizar y hacer seguimiento de dispositivos reales, tanto comerciales como DIY (hazlo tú mismo), utilizados para pruebas de penetración, análisis forense, auditorías de redes y experimentación educativa.

---

## 🌐 Tecnologías Utilizadas

- **HTML5 + CSS3**
- **Tailwind CSS** para estilos rápidos y modernos.
- **JavaScript** para la lógica de interacción (cálculo de precios, filtros, estados, etc.).
- Fuentes y efectos visuales personalizados para una experiencia hacker-style.

---

## 🧩 Funcionalidades

### ✅ Inventario Interactivo
Cada gadget cuenta con:
- Imagen representativa.
- Descripción técnica.
- Precio de compra.
- Enlace directo al proveedor.
- Estado (comprado o no, mediante interruptor).
- Etiquetas (tags) que indican su categoría: `USB`, `WiFi`, `RFID`, `SDR`, `DIY`, etc.

### 💰 Contador Total de Inversión
La web calcula automáticamente el total invertido en gadgets, sumando solo aquellos que están marcados como "comprados" por el usuario.

### 🔍 Filtros por Categoría
Botones en la parte superior permiten filtrar los gadgets por tipo de ataque o tecnología:
- `RF Tools`
- `USB Attacks`
- `Wi-Fi`
- `Data Exfiltration`
- `Todos`

### 🛠️ Sección de Tools Caseras
Incluye una categoría especial para herramientas **DIY o caseras**, como antenas o adaptadores modificados manualmente, acompañados de enlaces para explorarlas.

### 🌌 Diseño y Experiencia Visual
- Estética inspirada en terminales, con efectos glitch y colores neón.
- Animaciones ligeras.
- Cursor personalizado y fondos con gráficos relacionados al análisis de datos.

---

## 📁 Estructura de Archivos

/img/ → Imágenes de gadgets y favicon
/toolsCaseros/ → Herramientas DIY (hackingWifi.html, etc.)
index.html → Página principal del arsenal
style.css (opcional) → Estilos personalizados si se separan
README.md → Este documento

---

## 🧠 Objetivo del Proyecto

> Fomentar el aprendizaje práctico en ciberseguridad mediante la documentación y experimentación con gadgets físicos reales. El sitio no promueve el uso ilegal de estas herramientas, sino su aplicación ética en entornos controlados para formación, investigación o testeo.

---

## 📌 Ejemplos de Gadgets Incluidos

| Nombre         | Categoría       | Precio     |
|----------------|------------------|------------|
| Digispark      | USB / HID        | $2.00      |
| ESP-WROOM-32   | WiFi / IoT       | $8.99      |
| Flipper Zero   | Multiherramienta | $229.00    |
| Key Croc       | Keylogger / WiFi | $200.00    |
| Bash Bunny     | USB / Payloads   | $250.00    |
| HackRF One     | SDR / RF         | $369.05    |
| UHFKill        | Jammer / RFID    | $1,495.00  |

Y muchos más...

---

## 📦 Instalación

Este proyecto es **estático**, por lo tanto no requiere backend. Puedes:

1. Clonar el repositorio:

```bash
git clone https://github.com/tu_usuario/arsenal-hacking.git
```

2. Abrir el archivo index.html directamente en tu navegador.

## 🔐 Disclaimer

> Esta plataforma es educativa y está dirigida a pentesters, investigadores, docentes y entusiastas de la seguridad informática. El uso indebido de las herramientas aquí listadas no es responsabilidad del desarrollador. Siempre actúa bajo principios de ética y consentimiento.

## 👤 Autor

d1se0
