## Fast, async, multithreaded bomber

###

<div align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original.svg" height="200" alt="go logo"  />
  <img width="0" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" height="200" alt="docker logo"  />
</div>

###

### Project structure:

```go
├── cmd
│   └── main.go
├── core
│   ├── email_bomber.go
│   ├── generator.go
│   └── sms_bomber.go
├── Dockerfile
├── go.mod
├── LICENSE
└── README.md
```

## Installation

```sh
git clone https://github.com/kenjitheman/tomaranai_bomber
```

## Usage

- Run it:

```sh
cd cmd
go run main.go
```

- Or run it using docker:

```sh
docker build -t your_image_name .
docker run -d -p 8080:80 your_image_name
```

## Contributing

- Pull requests are welcome, for major changes, please open an issue first to
  discuss what you would like to change.

## License

- [MIT](https://choosealicense.com/licenses/mit/)
