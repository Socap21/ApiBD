# Mi Proyecto API

Activar el entorno virtual
.venv\Scripts\Activate

Iniciar Api
uvicorn main:app --reload

Servidor
http://127.0.0.1:8000

Interactuar con la Api
http://127.0.0.1:8000/docs (usando Swagger UI)
http://127.0.0.1:8000/redoc (usando ReDoc)

Camando para interactuar con la base de datos
curl -X GET "http://127.0.0.1:8000/endpoint"
