FROM node:10.10.0

ARG APP_VERSION
ARG INSTANCE_NAME
ARG SECRET_KEY
ARG PORT

ENV APP_VERSION=${APP_VERSION}
ENV INSTANCE_NAME=${INSTANCE_NAME}
ENV SECRET_KEY=${SECRET_KEY}
ENV PORT=${PORT}

WORKDIR /app
COPY . .
RUN npm install
