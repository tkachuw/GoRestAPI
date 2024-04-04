run: build
	@./bin/api

build:
	@go build -o bin/api

test:
	@go test -v ./...

tidy:
	@go mod tidy

db:
	@docker-compose up -d db