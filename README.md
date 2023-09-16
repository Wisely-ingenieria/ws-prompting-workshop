# Prompting Workshop

Este repositorio contiene los scripts utilizados en el taller de Prompting.

## Variables de entorno

Las variables de entorno en el archivo `.env` estan referenciados en `.env.reference`. Estos incluyen:

| Variable de Entorno | Descripción |
| --- | --- |
| `OPENAI_API_TYPE` | El tipo de API de OpenAI. |
| `OPENAI_API_BASE` | La URL base de la API de OpenAI. |
| `OPENAI_API_VERSION` | La versión de la API de OpenAI. |
| `OPENAI_API_KEY` | La clave de la API de OpenAI. |
| `OPENAI_EMBEDDING_MODEL` | El nombre del modelo de incrustación de OpenAI utilizado para generar vectores de incrustación. |

## Requisitos

Para ejecutar los scripts de este proyecto, necesitarás:

- Credenciales Azure.
- Credenciales de API de Azure OpenAI.
- Utilizar Python 3.10+.
- Instalar las bibliotecas de Python 

    `pip install requirement.txt`