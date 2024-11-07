# Taller - RAG - LLM

El objetivo de este taller es implementar una arquitectura **RAG (Retrieval-Augmented Generation)** utilizando las herramientas de OpenAI y el framework **LangChain**.

En este repositorio se realiza el tutorial de LangChain **[Build a Simple LLM Application with LCEL](https://python.langchain.com/docs/tutorials/llm_chain/)**. Se creó un entorno virtual en Python junto con un archivo Jupyter Notebook para la ejecución del tutorial.

### Servidor con LangServe

**LangServer** facilita a los desarrolladores la implementación de una interfaz REST API que permite interactuar con LangChain. A través de esta interfaz, se pueden enviar cadenas de texto (prompts) a un servidor que ejecuta modelos LLM (Large Language Models) de OpenAI para realizar tareas de procesamiento y generación de texto.

### Setup

- **Python 3.12.1**: Lenguaje de programación utilizado para ejecutar todo el entorno. Asegúrate de tener Python instalado (preferiblemente una versión 3.7 o superior).
- **Jupyter Notebook**: Utilizado para interactuar con el código y visualizar los resultados del modelo LLM.
- **LangChain**: Framework de Python utilizado para crear flujos de trabajo con modelos de lenguaje y datos externos.
- **LangServe**: Servidor de Python que expone el modelo LLM como una API REST, permitiendo la interacción a través de solicitudes HTTP.


### Instalación

1. **Clonar el repositorio** desde GitHub:
   ```bash
   git clone https://github.com/SebSanUwU/TallerLangChainTutorial
   ```
2. **Navegar al directorio del proyecto**:
   ```bash
   cd TallerLangChainTutorial
   ```
3. **Crear y activar el entorno virtual (opcional pero recomendado)**:
   Si no tienes un entorno virtual, puedes crearlo y activarlo con los siguientes comandos:
   ```bash
   python -m venv .venv
   # En Windows
   .venv\Scripts\activate
   # En Linux/Mac
   source .venv/bin/activate
   ```
4. **Ejecutar el servidor LangServe**:
   Una vez que hayas instalado las dependencias, puedes iniciar el servidor con el siguiente comando (python3 dependiendo de la version que se tenga):
   ```bash
   python langchainserver.py
   ```
5. **Abrir el archivo Jupyter Notebook** para interactuar con el modelo LLM:
   Después de ejecutar el servidor, abre el archivo `tutorial.ipynb` para probar los ejemplos y hacer uso de la interfaz del modelo.

   ```bash
   jupyter notebook tutorial.ipynb
   ```

   Aquí podrás ver cómo interactuar con LangChain y el modelo LLM a través de los prompts definidos en el servidor. Asegurate de agregar tu API KEY para la ejecucion.

### Construido con

- **Python**: Lenguaje de programación utilizado.
- **LangChain**: Framework para crear aplicaciones que integran modelos LLM y recuperación de datos.
- **OpenAI**: API para interactuar con modelos GPT y otros modelos de lenguaje.
- **Jupyter Notebook**: Herramienta para interactuar de manera interactiva con el código.

### Autor

* **Juan Sebastián Camargo Sánchez** - *AREP* - [SebSanUwU](https://github.com/SebSanUwU)
