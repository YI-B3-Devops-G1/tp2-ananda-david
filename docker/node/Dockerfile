FROM node:lts-alpine

ENV NODE_ENV development
ENV API_PORT 3000

WORKDIR /app
RUN chown -R node:node /app
USER node

CMD [ "npm", "run", "start" ]

