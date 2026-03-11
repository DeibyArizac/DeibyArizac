<p align="center">
  <img src="assets/banner.svg" alt="Deiby Ariza" width="100%"/>
</p>

<p align="center">
  <a href="https://linkedin.com/in/deibyariza"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:deibyarizac@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=flat&logo=gmail&logoColor=white" alt="Gmail"></a>
</p>

---

Ingeniero Electronico (UIS, acreditada ABET) con +4 anos en IA/ML y +10 en tecnologia. Construyo sistemas de inteligencia artificial que llegan a produccion — plataformas documentales con LLMs en entornos air-gapped sobre GPUs NVIDIA H200, pipelines RAG, modelos de ML entrenados desde cero, y 3 productos SaaS propios en produccion. Lidero equipos tecnicos y diseno arquitecturas que escalan.

---

## Productos en produccion

<table>
  <tr>
    <td align="center" width="50%">
      <img src="assets/verboxi-logo.png" alt="Verboxi" height="50"/><br/><br/>
      <a href="https://verboxi.com"><strong>verboxi.com</strong></a><br/>
      <sub>Tutor de ingles con IA conversacional. Streaming SSE con TTS paralelo (latencia menor a 2s), gamificacion completa (XP, streaks, 18 badges, SRS), pagos recurrentes con Wompi.</sub>
    </td>
    <td align="center" width="50%">
      <img src="assets/deplorix-logo.svg" alt="Deplorix" height="50"/><br/><br/>
      <a href="https://deplorix.com"><strong>deplorix.com</strong></a><br/>
      <sub>Generacion de documentos profesionales con IA. Multi-proveedor LLM (OpenAI, DeepSeek, Cloudflare AI), pipeline auto-fix de 5 intentos, edicion inteligente por secciones.</sub>
    </td>
  </tr>
</table>

---

## Stack tecnologico

**IA / Machine Learning**

![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic-191919?style=flat&logo=anthropic&logoColor=white)
![DeepSeek](https://img.shields.io/badge/DeepSeek-000?style=flat&logoColor=white)
![LLaMA](https://img.shields.io/badge/LLaMA-0467DF?style=flat&logo=meta&logoColor=white)
![vLLM](https://img.shields.io/badge/vLLM-FF6F00?style=flat)
![Ollama](https://img.shields.io/badge/Ollama-000?style=flat)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=flat)

**Cloud y Serverless**

![AWS Lambda](https://img.shields.io/badge/Lambda-FF9900?style=flat&logo=awslambda&logoColor=white)
![S3](https://img.shields.io/badge/S3-569A31?style=flat&logo=amazons3&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat&logo=amazondynamodb&logoColor=white)
![Cognito](https://img.shields.io/badge/Cognito-DD344C?style=flat)
![OpenSearch](https://img.shields.io/badge/OpenSearch-005EB8?style=flat&logo=opensearch&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat&logo=terraform&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat&logo=cloudflare&logoColor=white)

**Infraestructura**

![Kubernetes](https://img.shields.io/badge/K3s-FFC61C?style=flat&logo=kubernetes&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)

**Desarrollo**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000?style=flat&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat&logo=nodedotjs&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-0F0F11?style=flat&logo=angular&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)

**Datos**

![Polars](https://img.shields.io/badge/Polars-CD792C?style=flat&logo=polars&logoColor=white)
![Puppeteer](https://img.shields.io/badge/Puppeteer-40B5A4?style=flat&logo=puppeteer&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat&logo=selenium&logoColor=white)

---

## Trabajo destacado

### Modelos de ML propios

**Hit Song Predictor** — Modelo ensemble (MLP + CNN + XGBoost) entrenado desde cero sobre 83 features de audio extraidas con librosa + espectrogramas mel 128x128 para la CNN. 74.2% de accuracy prediciendo exito de canciones usando solo audio, sin metadata de Spotify. Desplegado en AWS Lambda con inferencia en tiempo real.

**Sistema de recomendacion musical** — Modelos entrenados sobre +5M registros de artistas. Indexacion de +450,000 perfiles en OpenSearch con busquedas en menos de 50ms. Endpoints de inferencia en FastAPI en menos de 100ms.

### Sistemas de IA empresariales

**Plataforma de inteligencia documental** — Para el sector defensa de Colombia. LLMs locales desplegados on-premise en entornos air-gapped sobre 4x NVIDIA H200 GPUs, pipeline RAG con pgvector, streaming SSE, orquestacion en Kubernetes (K3s). Rescate de un sistema de 2.3M documentos en cluster de 6 nodos tras falla catastrofica de almacenamiento — 99.5% uptime post-estabilizacion.

**Plataformas de IA gubernamentales** — RAG multi-proveedor (OpenAI, Azure OpenAI, Ollama, vLLM), prototipos para entidades de seguridad, encuestas ISO 9001, gestion interna.

**Scraper de gran escala** — Ingestion de +10M registros de +75 emisoras de radio en OpenSearch y S3.

### Mega Pipeline de audio (ConcertPlaza)

Pipeline completo: Whisper transcribe la letra, GPT la mejora con feedback de 3 agentes expertos IA (productor, ingeniero de mezcla, letrista), GPT construye prompt inteligente para Suno usando hit score + diagnostico + recomendaciones, Suno genera la cancion, Demucs separa stems, y se mezclan 2 versiones finales con los instrumentales mejorados. Todo orquestado en una sola Lambda de 15 minutos.

---

## Trayectoria

**BIT512 Soluciones TI** — Lider de IA / Ingeniero Senior de IA *(2025 - presente)*
10+ proyectos: Eclipse, JANUS, Hydra, Nexus, Sortex, Compensar HCM, plataformas gubernamentales.

**IncubApp Venture Capital** — AI Technical Project Manager *(2024 - 2025)*
Proyectos de IA para startups del portafolio. 100% de entregas a tiempo.

**IncubApp Venture Capital** — Data Scientist y ML Engineer *(2021 - 2024)*
Modelos de recomendacion, scraping masivo, fine-tuning de LLMs, inferencia ML en produccion.

---

## Formacion

**Ingenieria Electronica** — Universidad Industrial de Santander (acreditada ABET)
**Tecnico en Sistemas** — SENA
AWS Cloud Practitioner | Cisco IoT y Networking | Web App Security

---

<p align="center">
  <a href="https://linkedin.com/in/deibyariza">linkedin.com/in/deibyariza</a> ·
  <a href="mailto:deibyarizac@gmail.com">deibyarizac@gmail.com</a> ·
  Bucaramanga, Colombia
</p>
