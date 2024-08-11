# Use a imagem base do Apache HTTP Server
FROM httpd:latest

# Defina o diretório de trabalho
WORKDIR /usr/local/apache2/htdocs/

# Copie os arquivos do contexto de build para o diretório de trabalho
COPY . .

# Exponha a porta 80
EXPOSE 80

# Comando para iniciar o Apache em primeiro plano
CMD ["httpd-foreground"]
