# ![RealWorld Example App](logo.png)

> ### Golang/Echo codebase containing real world examples (CRUD, auth, advanced patterns, etc) 


This codebase was created to demonstrate a fully fledged fullstack application built with **Golang/Echo** including CRUD operations, authentication, routing, pagination, and more.
## Directory Structure

```bash
├── main.go
├── article
│   └── article.go
├── db
│   └── db.go
├── handler
│   ├── article.go
│   ├── article_test.go
│   ├── handler.go
│   ├── handler_test.go
│   ├── request.go
│   ├── response.go
│   ├── routes.go
│   ├── user.go
│   └── user_test.go
├── model
│   ├── article.go
│   └── user.go
├── router
│   ├── middleware
│   │   └── jwt.go
│   ├── router.go
│   └── validator.go
├── store
│   ├── article.go
│   └── user.go
├── user
│   └── user.go
└── utils
    ├── errors.go
    ├── jwt.go
    └── utils.go

9 directories, 33 files
```

## Requirements

- Golang v1.11+: [Installation Guide](https://golang.org/doc/install)
- `dep`: [Installation Guide](https://golang.github.io/dep/docs/installation.html)
## Getting started

### Install Golang (go1.11+)

Please check the official golang installation guide before you start. [Official Documentation](https://golang.org/doc/install)
Also make sure you have installed a go1.11+ version.

### Environment Config

make sure your ~/.*shrc have those variable:

```bash
➜  echo $GOPATH
/Users/allpyjs/go
➜  echo $GOROOT
/usr/local/go/
➜  echo $PATH
...:/usr/local/go/bin:/Users/allpyjs/test//bin:/usr/local/go/bin
```

For more info and detailed instructions please check this guide: [Setting GOPATH](https://github.com/golang/go/wiki/SettingGOPATH)

### Clone the repository

Clone this repository:

```bash
➜ git clone https://github.com/allpyjs/golang-echo-realworld--app.git
```

Or simply use the following command which will handle cloning the repo:

```bash
➜ go get -u -v github.com/allpyjs/golang-echo-realworld--app
```

Switch to the repo folder

```bash
➜ cd $GOPATH/src/github.com/allpyjs/golang-echo-realworld--app
```

### Install dependencies

```bash
➜ go mod download
```

### Run

```bash
➜ go run main.go
```

### Build

```bash
➜ go build
```

### Tests

```bash
➜ go test ./...
```
