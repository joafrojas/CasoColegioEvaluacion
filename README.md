# CasoColegioEvaluacion

# Sistema de Inteligencia Artificial — Colegio San Pedro Valle Grande

Proyecto enfocado en utilizar Inteligencia Artificial como apoyo educativo para mejorar el aprendizaje de los estudiantes y reducir parte de la carga de trabajo de los docentes.

# Objetivo

Diseñar un sistema de agentes de IA utilizando LLM y RAG, con el propósito de entregar tutorías personalizadas, apoyar a los estudiantes en sus dudas y ayudar a los profesores en la creación de material educativo.

# Problemática

El proyecto busca abordar principalmente:

Falta de personalización del aprendizaje.
Sobrecarga de trabajo de los docentes.
Falta de herramientas interactivas para el aprendizaje autónomo.

# Tecnologías y arquitectura

La propuesta utiliza:

Mistral-Small como modelo de lenguaje.
RAG para recuperar información desde material educativo.
Qdrant como base de datos vectorial.
Embeddings para transformar los documentos en vectores.
Arquitectura Multi-Agent.
Agentes
Tutor Virtual: responde dudas y explica contenidos paso a paso.
Asistente Docente: ayuda a crear guías, ejercicios y actividades.
Monitor Académico: identifica dificultades recurrentes y genera alertas.
Agente Enrutador: dirige las consultas al agente correspondiente.
Seguridad

# El sistema considera medidas de privacidad como:

Anonimización de datos personales.
Uso de identificadores internos.
Filtros de seguridad (Guardrails).
Derivación al profesor cuando la IA no tiene suficiente certeza.
RAG

El sistema procesa material educativo del colegio mediante chunking, embeddings y búsqueda vectorial, para entregar respuestas basadas en los documentos recuperados.

# Integrantes
Fernando Villalobos
Nicolas Sotomayor
Joan Rojas

# Estado

Proyecto académico — Propuesta de solución con Inteligencia Artificial.
