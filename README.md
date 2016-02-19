# gomario
Basic Golang text-mode Mario-like game - My first Go program

![Screenshot](screenshot.png?raw=true)

## Quick run on Darwin (Mac OS X)
```
wget https://github.com/MarianoGappa/gomario/raw/master/bin/darwin/main && chmod +x main && ./main
```

## ~~Quick run on Linux~~ Coming soon
```
wget https://github.com/MarianoGappa/gomario/raw/master/bin/linux/main && chmod +x main && ./main
```

## Instructions to compile -> run
```
# TODO missing termbox dependencies on repo content
cd ~/workspace && git clone git@github.com:MarianoGappa/gomario.git
cd gomario
go run main.go
# Reach the red square!
```

## Disclaimer
Mostly works; there is some race condition on gravity checking vs moving that sometimes makes Mario fall off perfectly good floors :P
