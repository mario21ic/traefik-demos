FROM php:7.3-alpine
ENV PORT=8080
ENV PORT_TWO=8081
WORKDIR /app
COPY . .
EXPOSE ${PORT}
ENTRYPOINT ["sh", "/app/docker-entrypoint.sh"]