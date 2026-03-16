# 🤖 ChatBotIA - Gemini Streaming 🚀

¡Bienvenido a **ChatBotIA**! Este proyecto es una aplicación web moderna desarrollada con **Spring Boot** que integra la potencia de **Google Gemini AI** para ofrecer una experiencia de chat con respuestas en tiempo real (Streaming).

Este repositorio es el resultado de un proceso de optimización técnica para lograr una interfaz fluida, segura y visualmente atractiva, ideal para proyectos académicos o profesionales de TI.

---

## 🌟 Características Destacadas

* **⚡ Streaming de Alto Rendimiento:** Implementación de Server-Sent Events (SSE) para que las respuestas aparezcan palabra por palabra.
* **📝 Formato Impecable:** Integración con `Marked.js` para renderizar Markdown (negritas, títulos, listas) de forma automática.
* **🛠️ Limpieza de Tokens:** Algoritmo personalizado en JavaScript para evitar palabras cortadas y preservar espacios naturales de la IA.
* **🎨 Interfaz Moderna:** Estilizado con **Tailwind CSS** en modo oscuro, con animaciones de carga y burbujas de chat dinámicas.
* **🔒 Seguridad de Grado Profesional:** Uso de **Variables de Entorno** para proteger la API Key de Google.

---

## 🛠️ Stack Tecnológico

| Componente | Tecnología |
| :--- | :--- |
| **Backend** | Java 21 + Spring Boot 3.x |
| **Inteligencia Artificial** | Google Gemini API (Spring AI) |
| **Frontend** | HTML5, Tailwind CSS, JavaScript (ES6+) |
| **Librerías Cliente** | Marked.js (Markdown Parser) |
| **IDE** | Spring Tool Suite (STS) |

---

## ⚙️ Configuración e Instalación

### 1. Requisitos
* JDK 21 instalado.
* Maven 3.x.
* API Key de Gemini (Consíguela en Google AI Studio).

### 2. Variable de Entorno
Para que el proyecto funcione correctamente, configura la siguiente variable en tu sistema o IDE:
- `GEMINI_API_KEY`: Tu clave privada de Google AI.

### 3. Ejecución Local
1. Clona el repositorio.
2. Configura la variable de entorno.
3. Ejecuta el proyecto desde STS o mediante terminal:
   ```bash
   mvn spring-boot:run
