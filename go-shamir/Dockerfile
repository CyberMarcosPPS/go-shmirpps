# Usa la imagen oficial de Go como imagen base
FROM golang:latest

# Establece el directorio de trabajo dentro del contenedor
WORKDIR /app

# Copia el código fuente de la aplicación Go al contenedor
COPY . .

# Compila la aplicación Go. Reemplaza 'main.go' con el archivo correcto si es necesario.
RUN go build -o bin/shamir cli/main.go
