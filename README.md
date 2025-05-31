# PFC_I
Implementaciones

## Ejecución de HippoRAG

Este es un ejemplo de salida al ejecutar el script principal con los parámetros de prueba, este dataset de prueba puede ser visto en HippoRAG/reproduce/dataset/sample.json:

```bash
$ python3 main.py --dataset sample --llm_base_url https://api.openai.com/v1 --llm_name gpt-4o-mini --embedding_name nvidia/NV-Embed-v2

INFO: Cargando plantillas de prompts...
INFO: Cargando grafo: 38 nodos, 115 aristas
INFO: Encoding de entidades y hechos...
INFO: Construyendo grafo...
INFO: Resultados de evaluación (retrieval): {'Recall@1': 0.0, 'Recall@200': 1.0}
INFO: Resultados de evaluación (QA): {'ExactMatch': 1.0, 'F1': 1.0}
```

## Entrega de avances semana 26 de Mayo al 1 de Junio
La carpeta que se especifica el avance para esta semana es SURE, acorde al documento enviado por correo.
La carpeta HippoRAG aun falta modificar ciertas cosas, fue subida como muestra del primer avance por que se pudo ejecutar para realizar pruebas con dataset de ejemplo, esta a futura modificacion.
Muchas gracias :D


