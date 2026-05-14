# Web Scraping in C

A small educational project focused on building a simple web scraping tool in C.

## Objective

The purpose of this project is to explore and practice:

- **libcurl** for HTTP requests and web content retrieval
- **File handling** (reading and writing files)
- **GTK 3.0** for creating a basic graphical interface
- **Modular C programming** and project organization

## Features

- Fetch HTML content from a given URL
- Parse and extract useful information
- Save retrieved data locally
- Display results through a simple GTK interface

## Technologies

- **C**
- **libcurl**
- **GTK 3.0**
- **GCC**
- **Makefile** *(if you add one)*

## Build

Compile with:

```bash
gcc *.c -o scraper $(pkg-config --cflags --libs gtk+-3.0 libcurl)
```

## Run

```bash
./scraper
```

## Project Structure

```text
.
├── main.c
├── curl.c
├── curl.h
├── file_related.c
├── file_related.h
├── inputs.c
├── inputs.h
├── utils.c
├── utils.h
└── README.md
```

## Notes

This project is for learning purposes only.
