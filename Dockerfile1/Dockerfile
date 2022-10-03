FROM alpine:latest
LABEL maintainer="Muskan Khosla"
ENV HTTP_PORT="9000"
#Install git
RUN apk update
RUN apk add git
RUN mkdir /app
#Set working directory
WORKDIR /app
CMD ["echo", "hello world"]
EXPOSE 80
