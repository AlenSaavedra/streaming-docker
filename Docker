# Usa la imagen base de Nginx
FROM nginx:latest

# Copia el archivo de configuración de Nginx personalizado
COPY web/config/nginx.conf /etc/nginx/nginx.conf

# Copia los archivos estáticos de la aplicación web al directorio de Nginx
COPY web/public /usr/share/nginx/html

# Exponer el puerto 80 para el tráfico HTTP
EXPOSE 80

# Comando por defecto para iniciar Nginx
CMD ["nginx", "-g", "daemon off;"]
