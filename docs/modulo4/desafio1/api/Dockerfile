FROM python:3.12-trixie

WORKDIR /app

# Copiar código
COPY ./ ./

# Instalar dependências Python
RUN pip install -r requirements.txt 

# Expor porta
EXPOSE 8000

# Comando padrão
CMD ["python", "manage.py", "runserver", "0.0.0.0:8000"]
