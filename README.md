# Project Rogue (take 2)


## dev on Windows
https://github.com/veandco/go-sdl2/issues/328#issuecomment-385334568

- Install choco
- `choco install golang`
- `choco install msys2`
- Open msys2
  - `pacman -Syu`
  - `pacman -S mingw64/mingw-w64-x86_64-gcc`
  - `pacman -S mingw64/mingw-w64-x86_64-SDL2`
- Add `C:\tools\msys64\mingw64\bin` to PATH
- `go get -v github.com/veandco/go-sdl2/sdl@master`
- Copy SDL.dll to exe folder (project folder)
