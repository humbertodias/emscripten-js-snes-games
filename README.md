# Emscripten JS SNES Games

Play classic **SNES games directly in your browser** using an Emscripten port of a SNES emulator.

🎮 [Live Demo](https://humbertodias.github.io/emscripten-js-snes-games/)



# Running Locally

### 1. Clone the repository

```bash
git clone https://github.com/humbertodias/emscripten-js-snes-games.git
```

### 2. Start a local web server

```bash
cd emscripten-js-snes-games
python3 -m http.server 9090
```
### 3. Open the application

Open your browser and go to: http://localhost:9090



# Loading a Game

1. Click **Load Game**
2. Navigate to `/`
3. Select a ROM file, for example:

```
Legend of Zelda, The - A Link to the Past (USA).sfc
```

![Load Game](doc/load-game.png)

### Output

![Game Preview](doc/preview.png)



# Tested Browsers

| Browser           | Performance |
| -- | -- |
| Firefox           | Fast        |
| Chrome            | Fast        |
| Safari            | Slow        |
| Opera             | Normal      |
| Internet Explorer | Not tested  |



# References

* [RetroArch](http://toadking.com/retroarch/snes9x-next.html)
* [XNes](https://github.com/tjwei/xnes)



# Notes

* You must provide your own SNES ROM files.
* Performance depends on the browser and hardware.
