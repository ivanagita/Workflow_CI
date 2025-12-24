FROM python:3.11-slim

# Set working directory di dalam container
WORKDIR /app

# Copy semua file dari folder MLProject ke container
COPY . /app

# Install library yang dibutuhin
RUN pip install --no-cache-dir pandas scikit-learn mlflow

# Perintah untuk jalanin script training
CMD ["python", "modelling.py"]
