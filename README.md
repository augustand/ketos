# Cross Container Builder (xcbuild)

[![GoDoc](https://godoc.org/github.com/setekhid/ketos?status.svg)](https://godoc.org/github.com/setekhid/ketos) [![Go Report Card](https://goreportcard.com/badge/github.com/setekhid/ketos)](https://goreportcard.com/report/github.com/setekhid/ketos)

A tasting project for Go Hackathon 2017 Shanghai.

This project aims to help you building a docker image in CI platform better.

## Hackathon Team

```
Ace-Tang   (github.com/ace-tang) <aceapril@126.com>
Huitse Tai (github.com/setekhid) <geb.1989@gmail.com>
```

## Building & Usage

```bash
docker build -t setekhid/ketos:latest .
docker run -it --rm  setekhid/ketos:latest xcb help
```
