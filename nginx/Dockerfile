# Usar la imagen oficial de Nginx
FROM nginx:latest

# Copiar archivos de configuración
COPY nginx.conf /etc/nginx/nginx.conf

# Copiar archivos HTML para cada host
COPY myblog1 /usr/share/nginx/html/myblog1
COPY myblog2 /usr/share/nginx/html/myblog2
COPY myblog3 /usr/share/nginx/html/myblog3
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]

