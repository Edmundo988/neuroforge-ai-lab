⚡ NeuroForge AI Lab
Plataforma educativa interactiva para aprender, visualizar y experimentar con inteligencia artificial y redes neuronales.

NeuroForge integra un simulador visual en el navegador con una API de IA en Python para entrenar modelos, realizar predicciones y analizar su rendimiento.

✨ Mejoras incorporadas
Arquitectura separada entre frontend y backend.
API de IA con FastAPI.
Modelo de clasificación con scikit-learn.
Entrenamiento automático y manual.
Predicciones en tiempo real.
Gráficas de pérdida y precisión.
Visualización de la frontera de decisión.
Datasets XOR, círculo, espiral y lunas.
Configuración de capas, neuronas y tasa de aprendizaje.
Funciones ReLU, Leaky ReLU, Sigmoid, Tanh y ELU.
Métricas de gradientes y neuronas muertas.
Validación de datos.
Manejo de errores de conexión.
Diseño adaptable para móviles.
Documentación automática mediante Swagger.
Código organizado y preparado para futuras extensiones.
🧠 Tecnologías
Frontend
HTML5
CSS3
JavaScript
Canvas API
Fetch API
Backend
Python
FastAPI
Uvicorn
scikit-learn
NumPy
Pydantic
📂 Estructura del proyecto
neuroforge-ai-lab/
├── frontend/
│   ├── index.html
│   ├── styles.css
│   └── app.js
├── backend/
│   ├── main.py
│   ├── model.py
│   ├── schemas.py
│   ├── requirements.txt
│   └── saved_models/
├── assets/
├── .gitignore
└── README.md
⚙️ Instalación
Clona el repositorio:

git clone https://github.com/Edmundo988/neuroforge-ai-lab.git
cd neuroforge-ai-lab
🐍 Configuración del backend
Entra en la carpeta:

cd backend
Crea un entorno virtual:

python -m venv .venv
Actívalo.

Windows
.venv\Scripts\activate
Linux o macOS
source .venv/bin/activate
Instala las dependencias:

pip install -r requirements.txt
Inicia el servidor:

uvicorn main:app --reload
La API estará disponible en:

http://127.0.0.1:8000
Documentación interactiva:

http://127.0.0.1:8000/docs
🌐 Ejecutar el frontend
Abre frontend/index.html en el navegador o utiliza Live Server en Visual Studio Code.

El backend debe estar activo para utilizar las funciones de IA.

🔌 API
Estado del servidor
GET /
Entrenar el modelo
POST /train
Parámetros:

epochs=10
dataset=moons
Realizar una predicción
POST /predict
Ejemplo:

{
  "x": 0.5,
  "y": 0.5
}
Respuesta:

{
  "prediction": 1,
  "probabilities": [0.18, 0.82],
  "confidence": 0.82
}
Obtener métricas
GET /metrics
🎮 Uso
Selecciona el dataset.
Configura las capas ocultas.
Define el número de neuronas.
Ajusta la tasa de aprendizaje.
Elige la función de activación.
Presiona Entrenar IA.
Observa la pérdida y la precisión.
Prueba nuevos puntos para obtener predicciones.
Analiza la frontera de decisión.
📊 Métricas disponibles
Pérdida MSE.
Precisión.
Confianza de la predicción.
Gradiente máximo.
Neuronas muertas.
Vanishing gradients.
Exploding gradients.
Tiempo de entrenamiento.
Número de épocas.
📚 Objetivos educativos
NeuroForge permite comprender:

Inteligencia artificial.
Aprendizaje automático.
Redes neuronales.
Clasificación binaria.
Propagación hacia adelante.
Backpropagation.
Descenso de gradiente.
Funciones de activación.
Inicialización He.
Sobreajuste.
Evaluación de modelos.
🛡️ Seguridad
Antes de utilizar el proyecto en producción, se recomienda:

Restringir CORS.
Validar todas las entradas.
Añadir autenticación.
Aplicar límites de solicitudes.
No almacenar datos sensibles.
Proteger los modelos guardados.
Configurar variables de entorno.
🚧 Próximas mejoras
Asistente educativo conversacional.
Soporte para TensorFlow y PyTorch.
Exportación de modelos.
Importación de datasets CSV.
Sistema de usuarios.
Historial de entrenamientos.
Modo oscuro y claro.
Traducción a varios idiomas.
Despliegue con Docker.
Publicación en la nube.
🤝 Contribuciones
Realiza un fork.
Crea una rama:
git checkout -b nueva-funcionalidad
Realiza tus cambios.
Confirma los cambios:
git commit -m "Añadir nueva funcionalidad"
Envía un pull request.
📄 Licencia
Este proyecto aún no tiene una licencia definida.

👤 Autor
Edmundo Ramírez

GitHub: @Edmundo988

Aprende, experimenta y construye con inteligencia artificial usando NeuroForge AI Lab.
