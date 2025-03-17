# Shelfit - Quick Notes & Snippets CLI

A lightweight, fast command-line tool for storing and retrieving notes, links, and code snippets.

## Installation

### Windows
Because sqlite3.lib is included in the package, you can install it with the following command:
```bash
cargo install shelfit
```

### Linux
You may need to install the sqlite3 development library before installing the program:
```bash
sudo apt install libsqlite3-dev
cargo install shelfit
```

## Build 
To build the project, run the following command:
```bash
cargo build
```
If you are on linux, you may need to install the sqlite3 development library first:
```bash
sudo apt install libsqlite3-dev
```