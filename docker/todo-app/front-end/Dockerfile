FROM node:16-alpine3.12
EXPOSE 3000
WORKDIR /app/front-end
ADD node_modules.tar.gz .
COPY . .
ENTRYPOINT ["npm"]
CMD ["start"]