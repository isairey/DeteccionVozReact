<div align="center">

<img width="220" src="https://cdn-icons-png.flaticon.com/512/4712/4712027.png" />

# 🎙️ Voice Activity Detection for JavaScript

### Detección inteligente de voz en navegador, Node.js y React 🚀

<p align="center">
  <b>Voice Activity Detection for JavaScript</b> es una librería moderna para detectar actividad de voz en tiempo real utilizando JavaScript, ONNX Runtime y Silero VAD, compatible con navegadores, Node.js y aplicaciones React.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/JavaScript-VAD-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
  <img src="https://img.shields.io/badge/React-AudioDetection-61DAFB?style=for-the-badge&logo=react&logoColor=black">
  <img src="https://img.shields.io/badge/Node.js-VAD-339933?style=for-the-badge&logo=node.js&logoColor=white">
  <img src="https://img.shields.io/badge/ONNX-Runtime-blueviolet?style=for-the-badge">
</p>

<p align="center">
  <a href="#-acerca-del-proyecto">Acerca</a> •
  <a href="#-características">Características</a> •
  <a href="#-tecnologías-utilizadas">Tecnologías</a> •
  <a href="#-instalación">Instalación</a> •
  <a href="#-uso-rápido">Uso</a>
</p>

</div>

---

# 🌌 Acerca del proyecto

**Voice Activity Detection for JavaScript** es una librería diseñada para detectar automáticamente cuándo una persona está hablando utilizando inteligencia artificial y procesamiento de audio en tiempo real.

El sistema permite:

- 🎤 Detectar voz desde el navegador
- ⚡ Procesar audio en tiempo real
- 🌐 Funcionar en aplicaciones web modernas
- 🧠 Utilizar modelos Silero VAD
- 🔊 Detectar inicio y fin del habla
- 📡 Integrarse con React y Node.js
- 🚀 Crear asistentes virtuales y apps de voz
- 🎧 Procesar audio con ONNX Runtime

---

# ✨ Características

## 🎙️ Detección de voz inteligente

- Inicio automático de detección
- Fin automático de voz
- Procesamiento en tiempo real
- Alta precisión VAD

---

## 🌐 Compatibilidad multiplataforma

- Navegadores modernos
- Node.js
- React
- Aplicaciones web

---

## ⚡ Integración sencilla

- Script tag
- NPM Packages
- React Hooks
- Node Modules

---

## 🧠 Inteligencia artificial

- Silero VAD
- ONNX Runtime
- Machine Learning
- Procesamiento optimizado

---

# 👨‍💻 Arquitectura del sistema

## 🎤 Captura de audio

Sistema encargado de obtener audio desde el micrófono.

### Funcionalidades

- Acceso al micrófono
- Captura en tiempo real
- Streaming de audio
- Procesamiento continuo

---

## 🧠 Voice Activity Detection

Módulo principal encargado de detectar actividad de voz.

### Funcionalidades

- Detección de habla
- Inicio y fin de voz
- Filtrado inteligente
- IA optimizada

---

## 🌐 Integración Web

Sistema compatible con aplicaciones frontend y backend.

### Funcionalidades

- Integración React
- Compatibilidad Node.js
- Browser support
- APIs modernas

---

# 🛠️ Tecnologías utilizadas

## ⚙️ Frontend & Backend

<p>
  <img src="https://skillicons.dev/icons?i=js,react,nodejs" />
</p>

- JavaScript
- React
- Node.js
- TypeScript Ready

---

## 🧠 Inteligencia artificial

- Silero VAD
- ONNX Runtime Web
- ONNX Runtime Node
- Audio ML Processing

---

## 🧰 Herramientas

<p>
  <img src="https://skillicons.dev/icons?i=git,github,vscode,npm" />
</p>

- Git
- GitHub
- VS Code
- NPM

---

# 📂 Estructura del proyecto

```bash
voice-activity-detection-js/
│
├── packages/
│   ├── vad-web/
│   ├── vad-node/
│   ├── vad-react/
│
├── docs/
├── examples/
├── dist/
├── package.json
└── README.md
```

---

# ⚡ Instalación

## 📋 Requisitos

- Node.js
- Navegador moderno
- Micrófono
- NPM o Yarn

---

# 🚀 Configuración del proyecto

## 1️⃣ Instalar paquete para navegador

```bash
npm install @ricky0123/vad-web
```

---

## 2️⃣ Instalar paquete React

```bash
npm install @ricky0123/vad-react
```

---

## 3️⃣ Instalar paquete Node.js

```bash
npm install @ricky0123/vad-node
```

---

# ▶️ Uso rápido

## 🌐 Script en navegador

```html
<script src="https://cdn.jsdelivr.net/npm/onnxruntime-web/dist/ort.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@ricky0123/vad-web/dist/bundle.min.js"></script>

<script>
async function main() {

  const myvad = await vad.MicVAD.new({
    onSpeechStart: () => {
      console.log("Speech start detected")
    },

    onSpeechEnd: (audio) => {
      console.log(audio)
    }
  })

  myvad.start()
}

main()
</script>
```

---

# ⚛️ Integración React

## 🎤 Funcionalidades

- React Hooks
- Estado dinámico
- Detección automática
- Audio en tiempo real

---

# 🟢 Node.js Support

## ⚡ Backend Voice Detection

- Procesamiento de audio
- Integración con servidores
- Streaming en tiempo real
- APIs de voz

---

# 📊 Funcionalidades principales

## 🎙️ Procesamiento de voz

- Detección automática
- Audio streaming
- Captura inteligente
- Eventos personalizados

---

## 🧠 Machine Learning

- Silero AI Models
- ONNX Runtime
- Voice classification
- Audio analysis

---

## 🌐 Aplicaciones web

- Voice assistants
- AI chatbots
- Real-time audio apps
- Interactive systems

---

# 🧠 Objetivos del proyecto

## 🎯 Aprendizaje y desarrollo

- Procesamiento de audio
- Machine Learning
- JavaScript avanzado
- Integración React
- Sistemas de voz
- IA aplicada
- Web Audio APIs

---

# 🚧 Roadmap

## 🔮 Próximas mejoras

- 🤖 Mejor precisión IA
- 📱 Soporte móvil avanzado
- 🌐 Más integraciones frontend
- 🔊 Reducción de ruido
- ⚡ Optimización de rendimiento
- ☁️ Integración cloud
- 🎧 Soporte multicanal

---

# 🤝 Contribuciones

Las contribuciones son bienvenidas ❤️

## Cómo contribuir

1. Fork del proyecto

```bash
git checkout -b feature/new-feature
```

2. Commit

```bash
git commit -m "✨ Add new feature"
```

3. Push

```bash
git push origin feature/new-feature
```

4. Pull Request 🚀

---

# 👨‍💻 Desarrollador

<div align="center">

## Ricky0123 — JavaScript Audio Developer

Desarrollador enfocado en procesamiento de voz, inteligencia artificial y aplicaciones modernas en JavaScript 🚀

</div>

---

# 🌟 Apoya el proyecto

⭐ Dale una estrella  
🍴 Haz fork  
📢 Comparte el proyecto

---

# 📜 Licencia

Proyecto open source orientado al desarrollo de aplicaciones inteligentes de voz y procesamiento de audio en JavaScript.

---

<div align="center">

### 🎙️ Voice Activity Detection for JavaScript — detección de voz inteligente en tiempo real 🚀

</div>
