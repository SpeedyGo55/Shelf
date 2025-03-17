# Shelfit - Quick Notes & Snippets CLI

A lightweight, fast command-line tool for storing and retrieving notes, links, and code snippets.

## Installation

### Windows
Because sqlite3.lib is included in the repository, you can install it with the following command:
```bash
cargo install --path .
```

### Linux
You need to install the sqlite3 development library before installing the program:
```bash
sudo apt install libsqlite3-dev
cargo install --path .
```

## Build 
To build the project, run the following command:
```bash
cargo build
```
If you are o