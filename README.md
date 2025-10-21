# Simple Go Server with Template Rendering

This is a minimal Go web server that serves HTML templates. It's designed for learning purposes or as a starting point for building more complex Go web applications.

## Features

- Serves HTML pages using Go's `html/template` package.
- Easy-to-extend template system.
- Simple routing for multiple pages.
- Lightweight and minimal dependencies.

## Prerequisites

- [Go](https://golang.org/doc/install) 1.20+ installed on your machine.
- [chi](https://github.com/go-chi/chi/v5) Uses Chi router v5
- [scs](https://github.com/alexedwards/scs/v2) For session and cookie system
- [NoSurf](https://github.com/alexedwards/scs/v2) For csrf Token system
## Installation

1. Clone this repository:
2. Before stsrt you need to install pre requisities

```bash
git clone https://github.com/yourusername/your-repo-name.git
cd ./simple-web-app-go
go get github.com/go-chi/chi/v5
go get github.com/alexedwards/scs/v2
go get github.com/alexedwards/scs/v2
go run ./cmd/web/
```
