FROM golang

EXPOSE 8080

WORKDIR /src/app

COPY . .

RUN ["go", "mod", "init", "gohelloworld"]

CMD ["go", "run", "main.go"]
