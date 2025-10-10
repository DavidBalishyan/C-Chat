# How to run the app locally?
To run this app locally on your machine you will need
1. POSIX shell (MacOS/Linux/BSD)
2. gcc/clang (C/C++ compiler)
3. golang
## Install the requirements
Golang (go)
```bash
# For linux or BSD, see https://go.dev/
# For MacOS, you can use Homebrew
brew install go
``` 
gcc (C/C++)
```bash
# For MacOS, use Homebrew
# For debian based linux distros, use apt
sudo apt install build-essential
# For Arch based distros, use pacman
sudo pacman -S build-essential
```
## Server
```bash
cd server
gcc main.c -o server
./server
```
Default port for server is <strong>8080</strong>. You can change this if you want from the <strong>server/loader.h</strong> file by changing a <strong>DEFINE</strong>
## Client
``` bash
cd client
go run main.go 127.0.0.1:PORT
```
Replace "PORT" with the <strong>port</strong> that you are using for the server

# Demo (recording)
<!-- <video width="320" height="240" controls autoplay> -->
<!-- <video width="320" height="240" controls autoplay> -->
  <!-- Your browser does not support the video tag. -->
  <!-- <a src="./demo.mp4" target="_blank">Watch video here</a> -->
<!-- </video> -->
<div style="position:relative; width:100%; height:0px; padding-bottom:56.250%">
    <iframe allow="fullscreen" allowfullscreen height="100%" src="https://streamable.com/e/x02cqw?" 
        width="100%" 
        style="
        border:none; 
        width:100%; 
        height:100%; 
        position:absolute; 
        left:0px; 
        top:0px; 
        overflow:hidden;
        ">
    </iframe>
</div>
