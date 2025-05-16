
# 🌤️ Predicción Meteorológica Inteligente

Este sistema avanzado utiliza modelos de **inteligencia artificial** y **aprendizaje automático** para ofrecer predicciones climáticas precisas, localizadas y en tiempo real. Integra datos históricos, sensores remotos e imágenes satelitales para mejorar la toma de decisiones en diversos sectores como agricultura, transporte, energía y gestión de desastres.

---

## 🧠 ¿Cómo funciona?

El sistema procesa más de **1.2 millones de datos diarios** provenientes de múltiples fuentes:

- 📡 Imágenes satelitales
- 🌡️ Sensores remotos
- 📊 Datos históricos meteorológicos

Los modelos entrenados con IA analizan esta información para predecir con un **95% de precisión** las condiciones climáticas en **32 ciudades** monitorizadas.

---

## 🚀 Características

- ✅ **Predicción precisa (95%)** gracias al uso de redes neuronales y técnicas de aprendizaje profundo
- 🌎 **Cobertura en tiempo real 24/7**
- 🏙️ **32 ciudades** en monitoreo constante
- ⚙️ Backend modular para integración con sensores e imágenes satelitales
- 📈 Visualización interactiva de datos históricos y predicciones

---

## 🛠️ Tecnologías utilizadas

- **Python**
- **TensorFlow / PyTorch**
- **OpenCV** (procesamiento de imágenes satelitales)
- **Flask / FastAPI** (API backend)
- **React / HTML-CSS** (Interfaz de usuario)
- **CI/CD con GitHub Actions**

---

## 📁 Estructura del proyecto

```
/
├── frontend/           # Interfaz de usuario (HTML/CSS/JS)
├── backend/            # Lógica de negocio y servicios API
├── models/             # Modelos entrenados de predicción climática
├── data/               # Datos históricos y en tiempo real
├── docs/               # Documentación técnica
└── README.md

```

## ⚙️ Instalación del proyecto

```
git clone https://github.com/tu_usuario/prediccion-meteorologica-inteligente.git
cd prediccion-meteorologica-inteligente

```
# 🧭 Diagrama de Arquitectura
Este diagrama muestra cómo interactúan los componentes del sistema:

![WhatsApp Image 2025-05-14 at 12 17 23 AM](https://github.com/user-attachments/assets/c0ef474c-1494-4a59-bef3-c390be23749f)


# 🧩 Uso
## 🧠 Entrenamiento del modelo (opcional)

1. Coloca los datos climáticos organizados en subcarpetas según el tipo en:

```bash
ai_model/datasets/climate_data/
```

2. Ejecuta el cuaderno de entrenamiento para reentrenar el modelo usando datos históricos, imágenes satelitales y sensores IoT:

```bash
ai_model/notebooks/model_training.ipynb
```

## 🌐 Endpoint del backend

- **Ruta**:  
  `http://localhost:35000/`

- **Método**:  
  `POST`

- **Body (JSON)**:

```json
{
  "latitude": 4.6097,
  "longitude": -74.0817,
  "datetime": "2025-05-16T14:00:00"
}
```

- **Respuesta esperada**:

```json
{
  "location": "Bogotá",
  "temperature": "22°C",
  "humidity": "68%",
  "precipitation": "Lluvia ligera",
  "confidence": "94%"
}
```

## 📱 Aplicación Web

La interfaz web permite:

- 🌆 Consultar predicciones meteorológicas por ciudad y horario.  
- 📈 Visualizar gráficos con datos históricos.  
- ☁️ Acceder a datos en tiempo real desde sensores y satélites.

**URL local de acceso**:  
```url
http://localhost:35000
```

🎥 Video Demostrativo
Mira el sistema en funcionamiento:

🔗 Ver video en YouTube <!-- Reemplaza con tu enlace real -->
