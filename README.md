# 🐚 Simple Go Shell

A minimalist command-line shell written in Go. This shell allows users to run system commands, change directories, and exit—similarly to how Bash or Zsh work, but in a much simpler form. It's a great learning project for understanding how shells process user input and execute commands in Unix-like environments.

---

## ✨ Features

- Run basic system commands (e.g., `ls`, `echo`, `pwd`)
- Built-in support for:
  - `cd` (change directory)
  - `exit` (quit the shell)
- Displays the current working directory before each prompt
- Handles user input using buffered I/O
- Errors and command output appear just like in a normal terminal

---

## Demo 
![alt Preview Image](https://github.com/mahesh-diwan/go-shell/blob/main/assets/image.png)
## Video Preview
<h3 align="center">
<img align="center" width="80%" src=https://github.com/mahesh-diwan/go-shell/blob/main/assets/video.mp4 />
</h3>

## 📦 Requirements

- [Go](https://go.dev/dl/) 1.18 or later
- A Unix-like OS (Linux, macOS, or WSL on Windows)

---

## 🚀 How to Install & Run

### 1. Clone the Repository
```bash
git clone https://github.com/<your-username>/go-shell.git
cd go-shell
```
### 2. Run the Shell
```bash 
go run main.go
```
## How It Works
-Reads user input via bufio.Reader

-Supports built-in commands via switch logic

-Other commands are executed via os/exec.Command

-Displays prompt using os.Getwd() to get current directory

## License
This project is licensed under the MIT License. Feel free to use and modify it for educational or personal use.

## Connect

Author: [Mahesh Diwan](https://www.linkedin.com/in/mahesh-diwan/) 

Feel free to reach out with questions or suggestions!