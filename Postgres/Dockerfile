# Utiliza a imagem oficial mais recente do PostgreSQL como base.
FROM postgres:latest

# Defina variáveis de ambiente para configurar o PostgreSQL
ENV POSTGRES_DB=bd_ADS3
ENV POSTGRES_USER=ADS3
ENV POSTGRES_PASSWORD=faat

# Copie o script de inicialização para o diretório de inicialização do PostgreSQL
COPY init.sql /docker-entrypoint-initdb.d/

EXPOSE 5432