export GO111MODULE=on

all: isucari

isucari: *.go
	go build -o isucari

lint:
	golangci-lint run
