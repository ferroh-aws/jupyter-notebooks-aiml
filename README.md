# Laboratorios de AI/ML

En este repositorio se encuentran una serie de libros de Jupyter con los cuales es posible experimentar algunas de las funcionalidades de los servicios de AI/ML de Amazon.

## Amazon Rekognition

El archivo ```rekognition_lab.ipynb``` contiene ejercicios que pueden ser utilizados para experimentar con las diferentes características de Rekognition sobre imágenes.

## Amazon Transcribe y Amazon Comprehend

El archivo ```transcribe_lab.ipynb``` contiene ejercicios para experimentar con Amazon Transcribe y utilizar la transcripción con el servicio de Amazon Comprehend.

## Amazon CloudFormation y Amazon SageMaker

El archivo ```immersion-day.yaml``` puede ser utilizado para crear una instancia de Jupyter Notebook dentro de SageMaker.

Los recursos creados son:
- Bucket de S3 para almacenar transcripciones y resultados de análisis de documentos
- Rol de IAM utilizado por Amazon Comprehend con acceso al bucket de S3
- Instancia de Jupyter ml.t3.medium
- Rol para Jupyter con acceso a los servicios de Amazon Rekognition, Amazon Transcribe, Amazon Comprehend y permisos de lectura y escritura al bucket creado.