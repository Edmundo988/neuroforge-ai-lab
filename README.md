# ⚡ NeuroForge AI Lab

Plataforma educativa interactiva para aprender, visualizar y experimentar con **inteligencia artificial y redes neuronales**.

NeuroForge integra un simulador visual en el navegador con una API de IA desarrollada en Python.

## ✨ Características

- Simulación visual de redes neuronales.
- Entrenamiento automático y paso a paso.
- Predicciones mediante una IA real.
- Configuración de capas y neuronas.
- Ajuste de la tasa de aprendizaje.
- Funciones de activación:
  - ReLU
  - Leaky ReLU
  - Sigmoid
  - Tanh
  - ELU
- Datasets:
  - XOR
  - Círculo 2D
  - Espiral 2D
  - Lunas 2D
- Métricas en tiempo real:
  - Loss
  - Precisión
  - Gradiente máximo
  - Neuronas muertas
  - Vanishing gradients
  - Exploding gradients
- Predicciones con nivel de confianza.
- Gráficas de pérdida y precisión.
- Visualización de la frontera de decisión.
- Diseño adaptable para dispositivos móviles.
- Documentación automática de la API con Swagger.

## 🧠 Tecnologías

### Frontend

- HTML5
- CSS3
- JavaScript
- Canvas API
- Fetch API

### Backend

- Python
- FastAPI
- Uvicorn
- scikit-learn
- NumPy
- Pydantic

## 📂 Estructura del proyecto

```text
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
Entra en la carpeta del backend:

cd backend
Crea un entorno virtual:

python -m venv .venv
Activa el entorno virtual.

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
Abre el archivo:

frontend/index.html
También puedes utilizar la extensión Live Server de Visual Studio Code.

El backend debe estar activo para utilizar las funciones de inteligencia artificial.

🔌 Endpoints de la API
Comprobar el estado del servidor
GET /
Entrenar el modelo
POST /train
Ejemplo:

POST /train?epochs=10&dataset=moons
Realizar una predicción
POST /predict
Datos de ejemplo:

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
Consultar métricas
GET /metrics
🎮 Cómo utilizar NeuroForge
Selecciona un dataset.
Configura las capas ocultas.
Define el número de neuronas.
Ajusta la tasa de aprendizaje.
Elige una función de activación.
Presiona Entrenar IA.
Observa la pérdida y la precisión.
Prueba nuevos puntos.
Analiza las predicciones y la frontera de decisión.
📊 Métricas disponibles
Pérdida MSE.
Precisión del modelo.
Confianza de la predicción.
Gradiente máximo.
Neuronas muertas.
Vanishing gradients.
Exploding gradients.
Número de épocas.
Tiempo de entrenamiento.
📚 Conceptos educativos
NeuroForge permite estudiar:

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

Restringir los orígenes permitidos en CORS.
Validar todas las entradas.
Añadir autenticación.
Aplicar límites de solicitudes.
Proteger los modelos guardados.
Utilizar variables de entorno.
Evitar almacenar información sensible.
🚧 Próximas mejoras
Asistente educativo conversacional.
Soporte para TensorFlow y PyTorch.
Importación de archivos CSV.
Exportación de modelos.
Historial de entrenamientos.
Sistema de usuarios.
Despliegue con Docker.
Publicación en la nube.
Soporte para más idiomas.
🤝 Contribuciones
Las contribuciones son bienvenidas.

Realiza un fork del repositorio.
Crea una nueva rama:
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
