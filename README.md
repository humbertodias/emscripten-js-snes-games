# Emscripten js-snes Games

Play old SNES games on your browser

# Prerequires

1. Python

# Run

Clone

```
git clone https://github.com/humbertodias/emscripten-js-snes-games.git
```

Into 

```
cd emscripten-js-snes-games/
```

Server

```
python -m SimpleHTTPServer 9090
```

Open on your browser

```
open http://localhost:9090
```

Select your rom

![Preview](doc/load-game.png)

1. Press **X** on **Load Game**

2. Later **X** on **/**

3. Finally **X** on **Legend of Zelda, The - A Link to the Past (USA).sfc**




# Output

![Preview](doc/preview.png)


# Tested Browsers

Browser | Performance |
------------- | -------------
Firefox | Fast
Chrome | Fast
Safari | Slow
Opera | Normal
IE | Didn't try


# References

1. RetroArch

	[http://toadking.com/retroarch/snes9x-next.html](http://toadking.com/retroarch/snes9x-next.html)

2. XNes

	[https://github.com/tjwei/xnes](https://github.com/tjwei/xnes)